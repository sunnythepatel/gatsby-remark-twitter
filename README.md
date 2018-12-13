# gatsby-remark-twitter

Embed Tweet cards in Gatsby markdown.

### [View a live demo here](https://jmolivas.weknowinc.com/badcamp-2018-wrapup)

## Install

```bash
npm install --save @weknow/gatsby-remark-twitter
```

## How to use

```js
// In your gatsby-config.js
plugins: [
  {
    resolve: "gatsby-transformer-remark",
    options: {
      plugins: ["@weknow/gatsby-remark-twitter"]
    }
  }
];
```

## Usage

```markdown
## Blog post title

This is an example of embedding a single tweet card.
Add any markdown as you normally do, and then insert a valid tweet link anywhere to automatically transform it into an Twitter embed card.

https://twitter.com/gatsbyjs/status/1055939617646465024

You can embed several tweets

https://twitter.com/wesbos/status/1068597847237541888

https://twitter.com/dan_abramov/status/1068884262273933312

```

> __NOTE:__ Make sure to copy the link instead of embed code.

<p align="center"><img src="https://i.imgur.com/evEv2LJ.jpg" alt="screenshot for share > copy tweet link" /></p>

## License

MIT