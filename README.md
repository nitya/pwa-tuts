# PWA Tutorials - By Example

## Objective
Create a set of code samples that explore creating, building, deploying, and testing, a basic PWA - using popular front-end frameworks and static site generators.

> How do we choose the frameworks and generators for this purpose?

We can look at [Stack Overflow Report 2021](https://insights.stackoverflow.com/survey/2021#section-most-popular-technologies-web-frameworks), [Stack Overflow Trends](https://insights.stackoverflow.com/trends?tags=jquery%2Cangularjs%2Cangular%2Creactjs%2Cvue.js%2Csvelte), [Octoverse](https://octoverse.github.com/) etc. for broad trends. For now, I'll focus on [Rising Stars of JS, 2022](https://risingstars.js.org/2021/en) which reflects popular and _emerging_ technologies that are less likely to have established tutorials already out there.

_Items marked with * are not in top 10, just for personal curiosity. Color key:_
 * 🔴  = priority, likely next
 * 🟠  = in progress
 * 🟢  = completed

---

## Tutorial Structure

Ideally the tutorial should show the following steps:

| Step | Description |
|:---|:---|
| Basic App | Build the boilerplate app/site. Preview locally to verify things work. Run Lighthouse audit (mobile, desktop) and save scores - optional. |
| Deploy to Azure | I'll use [Azure App Service]() for web apps and [Azure Static Web Apps](https://docs.microsoft.com/en-us/azure/static-web-apps/) for static site generators, for convenience.|
| PWABuilder Audit | Run PWABuilder audit to get PWA-readiness score for deployment to App Stores. Use recommendations to fix score and get basic PWA. |
| Playwright Test | Integrate Playwright end-to-end testing, automate with actions, show basic mobile/desktop screenshots capture as proof.|
| Lighthouse Audit | Run final audit with Lighthouse to gauge overall performance, accessibility and SEO compliance - plus reinforce PWA improvements. |

---
<br/>
<br/>

## [Node.JS Frameworks](https://risingstars.js.org/2021/en#section-nodejs-framework) 

Typically work with a favored front-end framework to provide full-stack development solutions.

| Name | Tutorial | Basic App | Deploy to Azure | PWABuilder Audit | Playwright Test | Lighthouse Audit |
|:-- |:-- |:-- |:-- |:-- |:-- |:--|
| Next.js | | | | | | |
| Nest | | | | | | |
| Strapi | | | | | | |
| Remix | | | | | | |
| Nuxt | | | | | | |
| SvelteKit | | | | | | |
| Fastify | | | | | | |
| Blitz | | | | | | |
| Redwood | | | | | | |
| [Express](http://expressjs.com/en/starter/generator.html) | [In-Progress](https://nitya-express-pwa.azurewebsites.net/)| 🟢 | 🟢  | 🟠 |  | |
---

<br/>
<br/>

## [Front End Frameworks](https://risingstars.js.org/2021/en#section-framework)

| Name | Tutorial | Basic App | Deploy to Azure | PWABuilder Audit | Playwright Test | Lighthouse Audit |
|:-- |:-- |:-- |:-- |:-- |:-- |:--|
| React |  | 🟢  | 🟠 | | | |
| Vue.js| | | | | | |
| Svelte | | | | | | |
| Angular | | | | | | |
| Solid | | | | | | |
| Alpine.js | | | | | | |
| vue-next| | | | | | |
| petite-vue | | | | | | |
| Lit | | 🔴  | | | | |
| htmx | | | | | | |

---


<br/>
<br/>

## [Static Site Generators](https://risingstars.js.org/2021/en#section-ssg)


| Name | Tutorial | Basic App | Deploy to Azure | PWABuilder Audit | Playwright Test | Lighthouse Audit |
|:-- |:-- |:-- |:-- |:-- |:-- |:--|
| [Next.js](https://nextjs.org/), _Vercel_| | | | | |
| [Astro](https://astro.build/), _AstroTC_ | | | | | 
| [Docusaurus](http://docusaurus.io), _Facebook_ |[In Progress](https://docu-demo.nitya.dev)  | 🟢 | 🟢  | 🟢 | 🟠  | 🟢  |
| Nuxt | | | | | | |
| Gatsby | | | | | | |
| Eleventy | | | | | | |
| Hexo | | | | | | |
| VuePress | | | | | | |
| Gridsome | | | | | | |
| Docsify* | | | | | | |
---