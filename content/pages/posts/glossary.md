---
layout: post
title: Glossary
subtitle: lorem-ipsum
date: '2022-05-21'
thumb_img_alt: lorem-ipsum
excerpt: lorem-ipsum
hide_header: false
seo:
  title: ''
  description: ''
  robots: []
  extra: []
thumb_img_path: /images/web-dev-back.jpg
content_img_path: /images/web-dev-back.jpg
---
## A

### AST

Abstract Syntax Tree: A tree representation of the source code that is found during a [compilation](https://www.gatsbyjs.com/docs/glossary/#compiler) step between two languages. For example, [gatsby-transformer-remark](https://www.gatsbyjs.com/plugins/gatsby-transformer-remark/) will create an AST from [Markdown](https://www.gatsbyjs.com/docs/glossary/#markdown) to describe a Markdown document in a tree structure using the [Remark](https://www.gatsbyjs.com/docs/glossary/#remark) parser.

### API

Application Programming Interface: A method for one application to communicate with another. For example, a [source plugin](https://www.gatsbyjs.com/docs/glossary/#source-plugin) will often use an API to get its data.

### Accessibility

The inclusive practice of removing barriers that prevent interaction with, or access to websites, by people with disabilities. When sites are correctly designed, developed and edited for accessibility, generally all users have equal access to information and functionality. Read about [Gatsby’s Commitment to Accessibility](https://www.gatsbyjs.com/blog/2019-04-18-gatsby-commitment-to-accessibility/).

## B

### Babel

A tool that lets you write the most modern [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript), and during the [build](https://www.gatsbyjs.com/docs/glossary/#build) process it gets [transpiled](https://www.gatsbyjs.com/docs/glossary/#transpile) to code that most web browsers can understand.

### Backend

The behind the scenes that the [public](https://www.gatsbyjs.com/docs/glossary/#public) does not see. This often refers to the control panel of your [CMS](https://www.gatsbyjs.com/docs/glossary/#cms). These are often powered by server-side programming languages such as Node.js, PHP, Go, ASP.net, Ruby, or Java.

### [Build](https://www.gatsbyjs.com/docs/glossary/build/)

In Gatsby, this is the process of taking your code and content and packaging it into a website that can be hosted and accessed. Commonly referred to as *build time*. See also: [backend](https://www.gatsbyjs.com/docs/glossary/#backend) and [server-side](https://www.gatsbyjs.com/docs/glossary/#server-side).

## C

### Cache

A storage of information locally that might be used again, so computations and lookups can be retrieved faster from one place. Gatsby uses a cache to store information so it can build your site faster when you’re developing without needing to do the same work twice.

### CLI

Command Line Interface: An application that runs on your computer through the [command line](https://www.gatsbyjs.com/docs/glossary/#command-line) and interacted with your keyboard.

Gatsby has two command line interfaces. One, [`gatsby`](https://www.gatsbyjs.com/docs/reference/gatsby-cli/), for day-to-day development with Gatsby and another, [`gatsby-dev`](https://www.gatsbyjs.com/contributing/code-contributions#setting-up-your-local-dev-environment), for those who contribute to the Gatsby project.

### Client-side

Client-side refers to operations that are performed by the user’s browser in a [client–server relationship](https://en.wikipedia.org/wiki/Client%E2%80%93server_model) in a computer network. In Gatsby, this is important when [working with packages](https://www.gatsbyjs.com/docs/using-client-side-only-packages/) that rely on objects in the [browser DOM](https://www.gatsbyjs.com/docs/glossary/#dom), such as `window` or `navigator`. See also: [server-side](https://www.gatsbyjs.com/docs/glossary/#server-side), [frontend](https://www.gatsbyjs.com/docs/glossary/#frontend), and [backend](https://www.gatsbyjs.com/docs/glossary/#backend).

### Client-side rendering

The practice of using JavaScript to render pages on the [client-side](https://www.gatsbyjs.com/docs/glossary/#client-side), as opposed to [server-side rendering](https://www.gatsbyjs.com/docs/glossary/server-side-rendering/) alone. Gatsby uses [React](https://www.gatsbyjs.com/docs/glossary/#react) and the [`@reach/router`](https://reach.tech/router/) library to enhance HTML pages compiled at [build time](https://www.gatsbyjs.com/docs/glossary/#build) to navigate site pages in a web browser without traditional page reloads, enabling performance techniques like preloading and [pre-fetching](https://www.gatsbyjs.com/docs/reference/routing/creating-routes/#performance-and-prefetching), [intersection observer and responsive `srcset`](https://www.gatsbyjs.com/blog/2019-04-02-behind-the-scenes-what-makes-gatsby-great/#modern-apis-in-gatsby) for images, and more. See also: [routing](https://www.gatsbyjs.com/docs/glossary/#routing), which is handled on the client-side in Gatsby by default.

### CMS

Content Management System: an application where you can manage your content and have it saved to a database or file for accessing later. Examples of Content Management Systems include WordPress, Drupal, Contentful, and Netlify CMS.

### Command Line

A text-based interface to run commands on your computer. The default Command Line applications for Mac and Windows are `Terminal` and `Command Prompt` respectively.

### Compiler

A compiler is a program that translates code written in one language to another language. For example [Gatsby](https://www.gatsbyjs.com/docs/glossary/#gatsby) can compile [React](https://www.gatsbyjs.com/docs/glossary/#react) applications into static [HTML](https://www.gatsbyjs.com/docs/glossary/#html) files. See also: [transpile](https://www.gatsbyjs.com/docs/glossary/#transpile).

### Component

Components are independent and re-usable chunks of code powered by [React](https://www.gatsbyjs.com/docs/glossary/#react) that, when combined, make up your website or app.

A component can include components within it. In fact, [pages](https://www.gatsbyjs.com/docs/glossary/#page) and [templates](https://www.gatsbyjs.com/docs/glossary/#template) are examples of components.

### Config

The configuration file, `gatsby-config.js`/`gatsby-config.ts` tells Gatsby information about your website. A common option to set in this config is your site’s metadata that can power your SEO meta tags.

### [Content Delivery Network](https://www.gatsbyjs.com/docs/glossary/content-delivery-network/)

A content delivery network (CDN) is a highly distributed network of servers that stores copies of your content in locations that are closer to your site’s visitors. Content delivery networks improve your site’s performance by reducing the time needed to complete a network request.

### [Continuous Deployment](https://www.gatsbyjs.com/docs/glossary/continuous-deployment/)

Continuous deployment (CD) automates the process of releasing changes to your project. A continuous deployment workflow automatically builds and tests your project, and publishes your changes only when they pass the required tests.

### CSS

[CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) stands for Cascading Style Sheets, and it’s a major part of the Web Platform with [HTML](https://www.gatsbyjs.com/docs/glossary/#html) and [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript). CSS is a language for styling webpages designed to be highly backwards-compatible. As new features are rolled out to end users, [CSS parsers](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/#CSS_parsing) can safely ignore unsupported features and enhance with the properties they do support. CSS accomplishes this with its *cascading* design, fundamental to styling with new techniques like [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/CSS_Grid_and_Progressive_Enhancement) while providing fallbacks for older browsers. Gatsby supports multiple [approaches to styling](https://www.gatsbyjs.com/docs/styling/), including regular CSS files, CSS modules, and CSS-in-JS.

## D

### Data Source

Content and data’s origin point, typically integrated into Gatsby with [source plugins](https://www.gatsbyjs.com/docs/glossary/#source-plugin). A data source is often a [Headless CMS](https://www.gatsbyjs.com/docs/glossary/#headless-cms), but it could also include Markdown, JSON, or YAML files.

### Database

A database is a structured collection of data or content. Often a [CMS](https://www.gatsbyjs.com/docs/glossary/#cms) will save to a database using [backend technologies](https://www.gatsbyjs.com/docs/glossary/#backend). They’re often accessed in Gatsby via a [source plugin](https://www.gatsbyjs.com/docs/glossary/#source-plugin)

### Decoupled

Decoupling describes the separation of different concerns. With [Gatsby](https://www.gatsbyjs.com/docs/glossary/#gatsby) this most commonly means decoupling the [frontend](https://www.gatsbyjs.com/docs/glossary/#frontend) from the [backend](https://www.gatsbyjs.com/docs/glossary/#backend), like with [Decoupled Drupal](https://dri.es/how-to-decouple-drupal-in-2019) or [Headless WordPress](https://www.smashingmagazine.com/2018/10/headless-wordpress-decoupled/).

### [Decoupled Drupal](https://www.gatsbyjs.com/docs/glossary/decoupled-drupal/)

Decoupling refers to the practice of using Drupal as a [headless CMS](https://www.gatsbyjs.com/docs/glossary/#headless-cms). A decoupled Drupal instance functions as a content API that returns JSON for your [frontend](https://www.gatsbyjs.com/docs/glossary/#frontend) to consume.

### Deferred Static Generation (DSG)

[Deferred Static Generation (DSG)](https://www.gatsbyjs.com/docs/how-to/rendering-options/using-deferred-static-generation/) is one of [Gatsby’s rendering options](https://www.gatsbyjs.com/docs/conceptual/rendering-options/) and allows you to defer non-critical page generation to user request, speeding up build times. Instead of generating every page at build time, you can decide to build certain pages up front and others only when a user accesses the page at run time.

### Deploy

The process of [building](https://www.gatsbyjs.com/docs/glossary/#build) your website or app and uploading onto a [hosting provider](https://www.gatsbyjs.com/docs/glossary/#hosting).

### Development Environment

The [environment](https://www.gatsbyjs.com/docs/glossary/#environment) when you’re developing your code. It’s accessed through the [CLI](https://www.gatsbyjs.com/docs/glossary/#cli) using `gatsby develop`, and provides extra error reporting and things to help you debug before building for [production](https://www.gatsbyjs.com/docs/glossary/#production-environment).

### DOM

The Document Object Model, commonly referred to as “the DOM”, is a standard browser API that connects web pages to scripts or programming languages by representing the structure of an HTML document in memory. Developers commonly interact with the DOM through [HTML](https://www.gatsbyjs.com/docs/glossary/#html) markup (written in [JSX](https://www.gatsbyjs.com/docs/glossary/#jsx) in Gatsby), as well as both [React](https://reactjs.org/docs/react-dom.html) and [vanilla JavaScript](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction#DOM_and_JavaScript) code. Another important aspect of utilizing the DOM to its full potential is writing [accessible](https://www.gatsbyjs.com/docs/glossary/#accessibility) HTML markup to expose a page’s structure to assistive technology.

## E

### ECMAScript

ECMAScript (often referred to as ES) is a specification for scripting languages. [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript) is an implementation of ECMAScript. Often developers will use [Babel](https://www.gatsbyjs.com/docs/glossary/#babel) to [transpile](https://www.gatsbyjs.com/docs/glossary/#transpile) the latest ECMAScript code into more widely supported JavaScript.

### Environment

The environment that Gatsby runs in. For example, when you are writing your code you probably want as much debugging as possible, but that’s undesirable on the live website or app. As such, Gatsby can change its behavior depending on the environment it’s in.

Gatsby supports two environments by default, the [development environment](https://www.gatsbyjs.com/docs/glossary/#development-environment) and the [production environment](https://www.gatsbyjs.com/docs/glossary/#production-environment).

### Environment Variables

[Environment Variables](https://www.gatsbyjs.com/docs/how-to/local-development/environment-variables/) allow you to customize the behavior of your app depending on its [environment](https://www.gatsbyjs.com/docs/glossary/#environment). For instance, you may wish to get content from a staging CMS during development and connect to your production CMS when you [build](https://www.gatsbyjs.com/docs/glossary/#build) your site. With environment variables you can set a different URL for each environment.

## F

### Filesystem

The way files are organized. With Gatsby, it means having files in the same place as your website’s or app’s code instead of pulling data from an external [source](https://www.gatsbyjs.com/docs/glossary/#data-source). Common filesystem usage in Gatsby includes Markdown content, images, data files, and other assets.

### Frontend

The [public-facing](https://www.gatsbyjs.com/docs/glossary/#public) interface for your website or app, delivered using web technologies: HTML, CSS, and JavaScript. For more insight into how the Web Platform brings these technologies together, check out this article on [How Browsers Work](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/).

## G

### Gatsby

Gatsby is a modern website framework that builds performance into every website or app by leveraging the latest web technologies such as [React](https://www.gatsbyjs.com/docs/glossary/#react), [GraphQL](https://www.gatsbyjs.com/docs/glossary/#graphql), and modern [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript). Gatsby makes it easy to create blazing fast, compelling web experiences without needing to become a performance expert.

### [GraphQL](https://www.gatsbyjs.com/docs/glossary/graphql/)

A [query](https://www.gatsbyjs.com/docs/glossary/#query) language that allows you to pull data into your website or app. It’s the [interface that Gatsby uses](https://www.gatsbyjs.com/docs/graphql/) for managing site data.

## H

### HTML

A markup language that every web browser is able to understand. It stands for Hypertext Markup Language. [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) gives your web content a universal informational structure, defining things like headings, paragraphs, and more. It is also key to providing an accessible website.

### [Headless CMS](https://www.gatsbyjs.com/docs/glossary/headless-cms/)

A [CMS](https://www.gatsbyjs.com/docs/glossary/#cms) that only handles the [backend](https://www.gatsbyjs.com/docs/glossary/#backend) content management instead of handling both the backend and [frontend](https://www.gatsbyjs.com/docs/glossary/#frontend). This type of setup is also referred to as [Decoupled](https://www.gatsbyjs.com/docs/glossary/#decoupled).

### [Headless WordPress](https://www.gatsbyjs.com/docs/glossary/headless-wordpress/)

The practice of using JSON returned from the WordPress REST API as a [headless CMS](https://www.gatsbyjs.com/docs/glossary/#headless-cms). It allows you to use WordPress to write and edit content that can be consumed by any client capable of parsing JSON.

### Hosting

A hosting provider keeps a copy of your website or app and makes it accessible to [the public](https://www.gatsbyjs.com/docs/glossary/#public). [Common hosting providers for Gatsby](https://www.gatsbyjs.com/docs/deploying-and-hosting/) projects include Netlify, AWS, S3, Surge, Heroku, and more.

### Hot module replacement

A feature in use when you run `gatsby develop` that live updates your site on save of code in a text editor by automatically replacing modules, or chunks of code, in an open browser window. Gatsby uses [Fast Refresh](https://www.gatsbyjs.com/docs/reference/local-development/fast-refresh/).

### [Hydration](https://www.gatsbyjs.com/docs/glossary/hydration/)

Once a site has been [built](https://www.gatsbyjs.com/docs/glossary/#build) by Gatsby and loaded in a web browser, [client-side](https://www.gatsbyjs.com/docs/glossary/#client-side) JavaScript assets will download and turn the site into a full React application that can manipulate the [DOM](https://www.gatsbyjs.com/docs/glossary/#dom). This process is often called re-hydration as it runs some of the same JavaScript code used to generate Gatsby pages, but this time with browser DOM APIs like `window` available.

## I

### Inference

As part of its data layer and [build](https://www.gatsbyjs.com/docs/glossary/#build) process, Gatsby will automatically **infer** a [schema](https://www.gatsbyjs.com/docs/glossary/#schema), or type-based structure, based on available data sources (e.g. Markdown file nodes, WordPress posts, etc.). More control can be gained over this structure by using Gatsby’s [Schema Customization API](https://www.gatsbyjs.com/docs/reference/graphql-data-layer/schema-customization/).

### [Infrastructure as Code](https://www.gatsbyjs.com/docs/glossary/infrastructure-as-code/)

Infrastructure as Code is the practice of using configuration files and scripts to automate the process of setting up your development, testing, and production environments.

## J

### [JAMStack](https://www.gatsbyjs.com/docs/glossary/jamstack/)

JAMStack refers to a modern web architecture using [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript), [APIs](https://www.gatsbyjs.com/docs/glossary/#api), and ([HTML](https://www.gatsbyjs.com/docs/glossary/#html)) markup. From [JAMStack.org](https://jamstack.org/): “It’s a new way of building websites and apps that delivers better performance, higher security, lower cost of scaling, and a better developer experience.”

### JavaScript

A programming language that helps us make the web dynamic and interactive. [JavaScript](https://developer.mozilla.org/en-US/docs/Web/Javascript) is a widely deployed web technology in browsers. It is also used on the server-side with [Node.js](https://www.gatsbyjs.com/docs/glossary/#node). It is an implementation of the [ECMAScript](https://www.gatsbyjs.com/docs/glossary/#ECMAScript) specification.

### [JSX](https://www.gatsbyjs.com/docs/glossary/jsx/)

JSX is an extension to JavaScript that allows developers to write HTML and custom components in the same piece of code. The [React team recommends](https://reactjs.org/docs/introducing-jsx.html) using it to describe what a [UI](https://www.gatsbyjs.com/docs/glossary/#UI) should look like. JSX may remind you of a template language, but it comes with the full power of JavaScript. Some important details to note are that because JSX uses JavaScript, some HTML attributes in your markup have to be swapped out to avoid reserved words in JavaScript (things like `htmlFor` and `className`).

## K

## L

### Linting

Linting is the process of running a program that will analyze code for potential errors. The Gatsby project uses [prettier](https://prettier.io/) to identify and fix common style issues. Another example of a linter commonly used in React projects is [eslint-plugin-jsx-a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y), which checks for common [accessibility](https://www.gatsbyjs.com/docs/glossary/#accessibility) issues in development.

## M

### [MDX](https://www.gatsbyjs.com/docs/glossary/mdx/)

Extends [Markdown](https://www.gatsbyjs.com/docs/glossary/#markdown) to support [React](https://www.gatsbyjs.com/docs/glossary/#react) [components](https://www.gatsbyjs.com/docs/glossary/#component) within your content.

### [Markdown](https://www.gatsbyjs.com/docs/glossary/markdown/)

A way of writing HTML content with plain text, using special characters to denote content types such as hash symbols for [headings](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements), and underscores and asterisks for text emphasis.

## N

### [npm](https://www.gatsbyjs.com/docs/glossary/npm/)

[Node](https://www.gatsbyjs.com/docs/glossary/#node) [package](https://www.gatsbyjs.com/docs/glossary/#package) manager. Allows you to install and update other packages that your project depends on. [Gatsby](https://www.gatsbyjs.com/docs/glossary/#gatsby) and [React](https://www.gatsbyjs.com/docs/glossary/#react) are examples of your project’s dependencies. See also: [Yarn](https://www.gatsbyjs.com/docs/glossary/#yarn).

### Node

Gatsby uses [data nodes](https://www.gatsbyjs.com/docs/reference/graphql-data-layer/node-interface/) to represent a single piece of data. A [data source](https://www.gatsbyjs.com/docs/glossary/#data-source) will create multiple nodes.

### [Node.js](https://www.gatsbyjs.com/docs/glossary/node/)

A program that lets you run [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript) on your computer. Gatsby is powered by Node.

## O

## P

### Package

A package usually describes a [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript) program that has additional information about how it should be distributed and used, such as its version number. [npm](https://www.gatsbyjs.com/docs/glossary/#npm) and [Yarn](https://www.gatsbyjs.com/docs/glossary/#yarn) manages and installs the packages your project uses. [Gatsby](https://www.gatsbyjs.com/docs/glossary/#gatsby) itself is a package.

### Page

An [HTML](https://www.gatsbyjs.com/docs/glossary/#html) page.

This also often refers to [components](https://www.gatsbyjs.com/docs/glossary/#component) that live in `/src/pages/` and are converted to pages by [Gatsby](https://www.gatsbyjs.com/docs/glossary/#gatsby), as well as [pages created dynamically](https://www.gatsbyjs.com/docs/creating-and-modifying-pages/#creating-pages-in-gatsby-nodejs) in your `gatsby-node.js` file.

### Plugin

Additional code that adds functionality to Gatsby that wasn’t included out-of-the-box. Common [Gatsby plugins](https://www.gatsbyjs.com/plugins/) include [source](https://www.gatsbyjs.com/docs/glossary/#source-plugin) and [transformer](https://www.gatsbyjs.com/docs/glossary/#transformer) plugins for pulling in and manipulating data, respectively.

### Production Environment

The [environment](https://www.gatsbyjs.com/docs/glossary/#environment) for the [built](https://www.gatsbyjs.com/docs/glossary/#build) website or app that users will experience when [deployed](https://www.gatsbyjs.com/docs/glossary/#deploy). It can be accessed through the [CLI](https://www.gatsbyjs.com/docs/glossary/#cli) using `gatsby build` or `gatsby serve`.

### Programmatically

Something that automatically happens based on your code and configuration. For example, you might [configure](https://www.gatsbyjs.com/docs/glossary/#config) your project to create a [page](https://www.gatsbyjs.com/docs/glossary/#page) for every blog post written, or read and display the current year as part of a copyright in your site footer.

### [Progressive Enhancement](https://www.gatsbyjs.com/docs/glossary/progressive-enhancement/)

Progressive enhancement is a strategy for the web that emphasizes core page content is loaded from a server before anything else, without [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript) as a requirement to load. This strategy then progressively adds more complex layers of presentation and features on top of the content as the end user’s browser/network connection allow. Gatsby’s default approach to [building](https://www.gatsbyjs.com/docs/glossary/#build) pages ahead-of-time means content will load first and enhance as scripts download and execute.

### Public

This usually refers to either a member of the public (as opposed to your team) or the folder `/public` in which your [built](https://www.gatsbyjs.com/docs/glossary/#build) website or app is saved.

## Q

### Query

The process of requesting specific data from somewhere. With Gatsby you normally query with [GraphQL](https://www.gatsbyjs.com/docs/glossary/#graphql).

## R

### [React](https://www.gatsbyjs.com/docs/glossary/react/)

A code library (written with [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript)) for building user interfaces. It’s the framework that [Gatsby](https://www.gatsbyjs.com/docs/glossary/#gatsby) uses to build pages and structure content.

### Remark

A parser to translate [Markdown](https://www.gatsbyjs.com/docs/glossary/#markdown) to other formats like [HTML](https://www.gatsbyjs.com/docs/glossary/#html) or [React](https://www.gatsbyjs.com/docs/glossary/#react) code.

### Runtime

Runtime is when a program is running (or being executable); it can refer to a few things. [Node.js](https://www.gatsbyjs.com/docs/glossary/#nodejs) is a [server-side](https://www.gatsbyjs.com/docs/glossary/#server-side) runtime that executes JavaScript code. [Client-side JavaScript](https://www.gatsbyjs.com/docs/glossary/#client-side), on the other hand, refers to the browser runtime where traditional JavaScript code executes. Gatsby compiles your site at [build time](https://www.gatsbyjs.com/docs/glossary/#build) and [rehydrates with a React runtime](https://www.gatsbyjs.com/docs/glossary/#hydration) to provide a fast, interactive, and dynamic user experience.

### Routing

Routing is the mechanism for loading the correct content in a website or app based on a network request - usually a URL. For example, it allows for routing URLs like `/about-us` to the appropriate [page](https://www.gatsbyjs.com/docs/glossary/#page), [template](https://www.gatsbyjs.com/docs/glossary/#template), or [component](https://www.gatsbyjs.com/docs/glossary/#component).

## S

### Schema

An exact representation of how data is stored in a system, such as tables and fields in a database or a JSON file structure. In Gatsby, the GraphQL schema expresses all queryable data - or data that components can ask about as part of Gatsby’s data layer.

### Server-side

The server-side part of the [client-server relationship](https://en.wikipedia.org/wiki/Client%E2%80%93server_model) refers to operations performed by a computer program which manages access to a centralized resource or service in a computer network. See also: [frontend](https://www.gatsbyjs.com/docs/glossary/#frontend) and [backend](https://www.gatsbyjs.com/docs/glossary/#backend).

### [Server-side rendering](https://www.gatsbyjs.com/docs/glossary/server-side-rendering/)

Using a [Node.js](https://www.gatsbyjs.com/docs/glossary/#nodejs)-based server to generate HTML in response to a request from a user agent such as a browser. Gatsby uses the server-side technology [Node.js](https://www.gatsbyjs.com/docs/glossary/#nodejs) to compile pages at build time, as opposed to serving them at [browser runtime](https://www.gatsbyjs.com/docs/glossary/#runtime) with [client-side](https://www.gatsbyjs.com/docs/glossary/#client-side) JavaScript.

### Source Code

Source code is your code that lives in `/src/` folder and makes up the unique aspects of your website or app. It is made up of [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript) and sometimes [CSS](https://www.gatsbyjs.com/docs/glossary/#css) and other files.

The source code gets [built](https://www.gatsbyjs.com/docs/glossary/#build) into the site the [public](https://www.gatsbyjs.com/docs/glossary/#public) will see.

### Source Plugin

A [plugin](https://www.gatsbyjs.com/docs/glossary/#plugin) that adds additional [data sources](https://www.gatsbyjs.com/docs/glossary/#data-source) to Gatsby that can then be [queried](https://www.gatsbyjs.com/docs/glossary/#query) by your [pages](https://www.gatsbyjs.com/docs/glossary/#page) and [components](https://www.gatsbyjs.com/docs/glossary/#component).

### Starter

A pre-configured Gatsby project that can be used as a starting point for your project. They can be discovered using the [Gatsby Starter Library](https://www.gatsbyjs.com/starters/) and installed using the [Gatsby CLI](https://www.gatsbyjs.com/docs/starters/).

### Static

Gatsby [builds](https://www.gatsbyjs.com/docs/glossary/#build) static versions of your page that can be easily [hosted](https://www.gatsbyjs.com/docs/glossary/#hosting). This is in contrast to dynamic systems in which each page is generated on-the-fly. Being static affords major performance gains because the work only needs to be done once per content or code change.

It also refers to the `/static` folder which is automatically copied into `/public` on each [build](https://www.gatsbyjs.com/docs/glossary/#build) for files that don’t need to be processed by Gatsby but do need to exist in [public](https://www.gatsbyjs.com/docs/glossary/#public).

### [Static Site Generator](https://www.gatsbyjs.com/docs/glossary/static-site-generator/)

A software application that creates HTML pages from templates or [components](https://www.gatsbyjs.com/docs/glossary/#component) and a given content source.

## T

### Template

A [component](https://www.gatsbyjs.com/docs/glossary/#component) that is [programmatically](https://www.gatsbyjs.com/docs/glossary/#programmatically) turned into a page by Gatsby.

### Theme

A Gatsby theme is like a WordPress theme that is composable (with other themes), extendable (with more logic), and replaceable ([shadowing](https://www.gatsbyjs.com/blog/2019-04-29-component-shadowing/)). Gatsby themes can have any facet of a Gatsby app packaged inside of them, and can also offer any number of knobs to turn features on or off.

### Transformer

A [plugin](https://www.gatsbyjs.com/docs/glossary/#plugin) that transforms one type of data to another. For example you might transform a spreadsheet into a [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript) array.

### Transpile

The process of converting code from one syntax or format to another, such as TypeScript, a superset of JavaScript which provides custom type checking during development. [Babel](https://www.gatsbyjs.com/docs/glossary/#babel) is another common example of transpilation that reformats newer JavaScript code following the [ECMAScript](https://www.gatsbyjs.com/docs/glossary/#ecmascript) standard to be more backwards-compatible during the site [compilation](https://www.gatsbyjs.com/docs/glossary/#compiler) process.

## U

### UI

A UI refers to a User Interface. In the field of human-computer interaction, a UI is a space where interactions between humans and machines occur. The goal of this interaction is to allow effective operation and control of the machine from the human end, while the machine simultaneously feeds back information that aids the user’s decision-making process (such as error messages or notifications).

## V

## W

### [webpack](https://www.gatsbyjs.com/docs/glossary/webpack/)

A [JavaScript](https://www.gatsbyjs.com/docs/glossary/#javascript) application that Gatsby uses to bundle your website’s code up. This happens automatically on [build](https://www.gatsbyjs.com/docs/glossary/#build).

### [WPGraphQL](https://www.gatsbyjs.com/docs/glossary/wpgraphql/)

A WordPress plugin that adds [GraphQL](https://www.gatsbyjs.com/docs/glossary/#graphql) capabilities to WordPress. It’s another way that you can use WordPress as a content source for Gatsby.

## X

## Y

### [Yarn](https://www.gatsbyjs.com/docs/glossary/yarn/)

A [package](https://www.gatsbyjs.com/docs/glossary/#package) manager that some prefer to [npm](https://www.gatsbyjs.com/docs/glossary/#npm). It is also required for [developing Gatsby](https://www.gatsbyjs.com/contributing/code-contributions#setting-up-your-local-dev-environment).

