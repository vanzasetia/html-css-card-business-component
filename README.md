# Card Business Component with HTML and CSS

This is a practice project to compare the performance of React, Preact, and Svelte with the "HTML CSS" website.

This project is a static website.

I create this project as an example to practice the basic of those JavaScript frameworks.

You can see the live site:

[Card Business Component with HTML and CSS](https://laurasmithbusiness.netlify.app/)

## Built with

- HTML Semantic Tags
- [BEM (Block, Element, Modifier)](https://sparkbox.com/foundry/bem_by_example)
- CSS Flexbox
- Mobile-first workflow

## What I learned

I learned about performance.

## How fast is the website?

I compare the page weight of the same website but built with different technologies.

Here is a list of the same version of the card component but built with different technologies:

- [Card Business Component with Svelte](https://svelte-laurasmithbusiness.netlify.app/) - [vanzasetia/svelte-card-business-component: Practice project to learn Svelte. A responsive card component. It is a static website.](https://github.com/vanzasetia/svelte-card-business-component)
- [Card Business Component with Preact](https://preact-laurasmithbusiness.netlify.app/) - [vanzasetia/preact-card-business-component: Practice project to learn Preact. A responsive card component. It is a static website.](https://github.com/vanzasetia/preact-card-business-component)
- [Card Business Component with React](https://react-laurasmithbusiness.netlify.app/) - [vanzasetia/react-card-business-component: Practice project to learn React. A responsive card component. It is a static website.](https://github.com/vanzasetia/react-card-business-component)

Let's compare the page weight of each website:

| Website                                        | Page Weight |
| ---------------------------------------------- | :---------: |
| https://laurasmithbusiness.netlify.app/        |  17.1 KiB   |
| https://svelte-laurasmithbusiness.netlify.app/ |  20.6 KiB   |
| https://preact-laurasmithbusiness.netlify.app/ |  25.9 KiB   |
| https://react-laurasmithbusiness.netlify.app/  |  61.1 KiB   |

The heaviest page weight is the website made by using React. Here are some of the key findings that the website that is built with React is:

- **3.6x** heavier than the "HTML CSS" website,
- **3.0x** heavier than the Svelte website, and
- **2.4x** heavier than the Preact website.

The lightest page weight is the website that is built with standard technologies — HTML and CSS. Here are some of the key findings that the website that is built with HTML and CSS is:

- **1.2x** lighter than the Svelte website,
- **1.5x** lighter than the Preact website, and
- **3.5x** lighter than the React website.

The reason for this is happening is because **frameworks come with other stuff**. So, the page weight will be higher than the "HTML CSS" website.

The page weight information is coming from:

- [Report for: https://laurasmithbusiness.netlify.app/ | PageSpeed Insights](https://pagespeed.web.dev/report?url=https%3A%2F%2Flaurasmithbusiness.netlify.app%2F)
- [Report for: https://preact-laurasmithbusiness.netlify.app/ | PageSpeed Insights](https://pagespeed.web.dev/report?url=https%3A%2F%2Fpreact-laurasmithbusiness.netlify.app%2F)
- [Report for: https://react-laurasmithbusiness.netlify.app/ | PageSpeed Insights](https://pagespeed.web.dev/report?url=https%3A%2F%2Freact-laurasmithbusiness.netlify.app%2F)
- [Report for: https://svelte-laurasmithbusiness.netlify.app/ | PageSpeed Insights](https://pagespeed.web.dev/report?url=https%3A%2F%2Fsvelte-laurasmithbusiness.netlify.app%2F)

### Can they survive without JavaScript?

The websites that can survive without JavaScript are the websites that are built with "HTML CSS" and Preact. The other two will show "You need to enable JavaScript to run this app." if the users disable JavaScript in their browser.

## License

[MIT](./LICENSE)
