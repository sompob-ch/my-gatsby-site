<p align="center">
  <a href="https://www.gatsbyjs.com/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter-ts">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby Minimal TypeScript Starter
</h1>

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the minimal TypeScript starter.

    ```shell
    # create a new Gatsby site using the minimal TypeScript starter
    npm init gatsby -- -ts
    ```

2.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```shell
    cd my-gatsby-site/
    npm run develop
    ```

3.  **Open the code and start customizing!**

    Your site is now running at http://localhost:8000!

    Edit `src/pages/index.tsx` to see your site update in real-time!

4.  **Learn more**

    - [Documentation](https://www.gatsbyjs.com/docs/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter-ts)
    - [Tutorials](https://www.gatsbyjs.com/docs/tutorial/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter-ts)
    - [Guides](https://www.gatsbyjs.com/docs/how-to/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter-ts)
    - [API Reference](https://www.gatsbyjs.com/docs/api-reference/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter-ts)
    - [Plugin Library](https://www.gatsbyjs.com/plugins?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter-ts)
    - [Cheat Sheet](https://www.gatsbyjs.com/docs/cheat-sheet/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter-ts)

## 🚀 Quick start (Netlify)

Deploy this starter with one click on [Netlify](https://app.netlify.com/signup):

[<img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify" />](https://app.netlify.com/start/deploy?repository=https://github.com/gatsbyjs/gatsby-starter-minimal-ts)

## Key takeaways
React is a library that helps you break down your UI into smaller pieces called components. A component is a function that returns a React element. React elements can be written in JSX.
Page components contain all the UI elements for a specific page of your site. Gatsby automatically creates pages for components that are the default exports of files in the src/pages directory. The name of the file will be used as the route for the page.
You can use the Gatsby Head API by exporting a named function Head to define metadata for the page.
Building-block components are smaller reusable parts of your UI. They can be imported into page components or other building block components.
You can import pre-built components (like Link) from other packages, or you can write your own custom components from scratch (like Layout).
You can use props to change how a component renders. You can define your own props when you build a component. React also has some built-in props, like children and className.
Gatsby isn’t opinionated about what styling approach you want to use, but it works with CSS Modules by default.

Source plugins pull data from their original location into the Gatsby GraphQL data layer.
You can use the GraphiQL endpoint (localhost:8000/___graphql) to explore the data in the data layer and design GraphQL queries.
You can write GraphQL queries to pull data out of the data layer and into your React components.
To pull data into a “building block” component, use the useStaticQuery hook.
To pull data into a page component, use a page query.
You can use React components inside the Gatsby Head API.