## Alternate React Frameworks

React out of the box is not SEO friendly. Previously, lots of different techniques were used to render React elements such that they could be crawled by SEO bots. The following frameworks were designed to allow devs to build SEO-friendly sites using React techniques and best practices.

### Next
Next uses server-side rendering whereby HTML code is generated from the server itself. The browser then receives pre-rendered HTML rather than an empty div. Next requires a server to run. It creates HTML on runtime from the server. Next does not dictate how data should be handled.

### Gatsby
Rather than using server-side rendering, Gatsby uses "Static Site Generator". These build HTML code during the "build". It doesn't use the server to generate HTML. Then the browser can receive that HTML code. In the case of Gatsby, the build takes in Markdown files and converts them into proper HTML. Gatsby can function without a server. Gatsby just generates pure HTML/CSS/JS which makes it easy to host and easy to scale to high traffic loads. Gatsby filters data through a GraphQL database. 
