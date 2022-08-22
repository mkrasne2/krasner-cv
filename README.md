<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby's CV starter
</h1>

Create your resume in a few minutes with this totally responsive starter using React. Show off your skills, work experiences and activities in github. This is an 
altered fork of https://github.com/santosfrancisco/gatsby-starter-cv

### Sections
- About
- Skills
- Job experiences
- Github repositories
- Portifolio

### Features
- Responsive Design, optimized for Mobile devices
- Google Analytics
- SEO
- PWA
- Dark mode
- Animations

## 📷 Preview

### Mobile

![Preview mobile](./preview-mobile.gif)

### Desktop

![Preview desktop](./preview-desktop.gif)

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the default starter.

    ```sh
    # create a new Gatsby site using the default starter
    npx gatsby new my-default-starter https://github.com/santosfrancisco/gatsby-starter-cv
    ```

2.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```sh
    cd my-default-starter/
    npm run develop
    ```

3.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    \_Note: You'll also see a second link: `http://localhost:8000/___graphql`. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql).\_

    Open the `my-default-starter` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

4. **Generate production build**

    That command will generate a production build on _public_ folder
    ```sh
      npm run build
    ```

5. **Deploy to Github pages**

    That command will deploy the production build to gh-pages branch of your repository
    > ⚠️ don't forget to check `pathPrefix` in the configuration file.


    ```sh
      npm run deploy
    ```

## Configuration

Update the configuration file with your data. The configuration file is in ```data/siteConfig.js```

:warning: NOTE: Please change googleAnalyticsId to your ID.  See https://analytics.google.com for details.

> **Skills** is a set of your personal skills and their respective levels ranging from > 0 to 100.
> **jobs** is a set of your work experiences

```js
  module.exports = {
    siteTitle: 'Hi! I\'m Mark!',
    siteDescription: `Self-taught Web3 developer, blockchain enthusiast, and decentralization advocate`,
    keyWords: ['gatsbyjs', 'react', 'curriculum'],
    authorName: 'Mark Krasner',
    twitterUsername: 'stochasticgood',
    githubUsername: 'mkrasne2',
    authorAvatar: '/images/avatar1.jpeg',
    authorDescription: `Self-taught full-stack Web3 developer, passionate about reducing usability friction to onboard the next wave of mainstream blockchain use cases. <br />
       <br />
      I currently freelance as a fullstack developer and mainly work with <strong>Solidity, Javascript, NodeJS, and React.</strong>`,
    skills: [
      {
        name: 'HTML',
        level: 70
      },
      {
        name: 'CSS',
        level: 60
      },
      {
        name: 'Javascript',
        level: 50
      },
      {
        name: 'NodeJs',
        level: 40
      },
      {
        name: 'React',
        level: 60
      },
      {
        name: 'Git',
        level: 70
      },
      {
      name: 'Solidity',
      level: 60
    }
    ],
    jobs: [
      /* more jobs here */
      {
       
    
      },  
    ],
    
    social: {
      twitter: "https://twitter.com/stochasticgood",
      linkedin: "https://www.linkedin.com/in/krasnermark/",
      github: "https://github.com/mkrasne2",
      email: "mzkrasner@gmail.com"
    },
    siteUrl: 'https://mkrasne2.github.io/krasner-cv',
    pathPrefix: '/gatsby-starter-cv', // Note: it must *not* have a trailing slash.
    siteCover: '/images/cover1.jpeg',
    googleAnalyticsId: 'UA-000000000-1',
    background_color: '#ffffff',
    theme_color: '#25303B',
    fontColor: "#000000cc",
    enableDarkmode: true, // If true, enables dark mode switch
    display: 'minimal-ui',
    icon: 'src/assets/gatsby-icon.png',
    headerLinks: [
      {
        label: 'Home',
        url: '/',
      },
      
    ]
  }

```




