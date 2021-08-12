<style>
.inline img, .inline h3{
   display:inline-block;
   vertical-align: middle;
}
.block-quote {
    padding: 16px 24px;
    background-color: #f3f5f7;
    border-left: 8px solid #747bff;
    border-radius: 2px;
}
.block-quote .title {
    font-weight: 600;
}
.block-quote a {
    color: #747bff
}
</style>

<p align="center">
    <a href="https://github.com/roremdev/rick-morty/javascript">
        <img src="https://img.shields.io/badge/JavaScript-1.0.0-green?style=for-the-badge&logo=JavaScript" alt="JavaScript" />
    </a>
    <a href="https://github.com/roremdev/rick-morty/react">
        <img src="https://img.shields.io/badge/React-gray?style=for-the-badge&logo=React" alt="React" />
    </a>
    <a href="https://github.com/roremdev/rick-morty/vue">
        <img src="https://img.shields.io/badge/Vue-gray?style=for-the-badge&logo=Vue.js" alt="Vue" />
    </a>
    <a href="https://github.com/roremdev/rick-morty/svelte">
        <img src="https://img.shields.io/badge/Svelte-gray?style=for-the-badge&logo=Svelte" alt="Svelte" />
    </a>
</p>

<p align="center">
    <img src="images/logo.svg" alt="Logo" width="80" height="80">
    <h3 align="center">SPA Rick & Morty</h3>
    <p align="center"> A little spa app built with React, Vue, Svelte</p>
</p>

## About The Project
The propuse of this project is to create a SPA (Single Page Application) that will be a simple example of how to use React, Vue, Svelte and other modern frontend technologies.

The use for this project will depend on the use case:
- For customize the integration project with builders like webpack, rollup, etc.
- For create pipelining for hooks made in git/github, travis, cypress, etc.
- Also, for improve the inside code or testing new features either in the frontend or fetching data from some kind of API (REST API, GraphQL, etc).

<div class="inline">
    <img src="images/vite.svg" alt="vite" width="24"/>
    <h3>Built with Vite</h3>
</div>

The initial construction of this project was made with [Vite](https://vitejs.dev/).

The main fact for use Vite is because all solutions, separately, are lowing developer experience in measure that applications is growing.

Vite improves the dev server start time by first dividing the modules in an application into two categories: **dependencies** and **source code**.

Other reasons for using Vite are:
* [Improve updates](https://vitejs.dev/guide/why.html#slow-updates)
* [Bundle for productions](https://vitejs.dev/guide/why.html#why-bundle-for-production)

## Getting Started
<div class="block-quote">
    <p class="title">Compatibility Note</p>
    <p>Vite requires <a href="https://nodejs.org/en/">Node.js</a> version >=12.0.0.</p>
</div>

### Branches
For check each version code, you can change the current branch:
```bash
    git checkout [branch_name]
```
Branch names supported are:
* `javascript`: JavaScript vanilla
* `react`: React library
* `vue`: Vue framework
* `svelte`: Svelte framework

> Note. You need to install all dependencies from `package.json`. Recomended with `npm install`.
