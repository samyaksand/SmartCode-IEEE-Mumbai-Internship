# SmartCode-IEEE-Mumbai

[![Hits](https://hits.sh/github.com/samyaksand/SmartCode-IEEE-Mumbai-Internship.svg?style=for-the-badge&label=Total%20Views&extraCount=240&color=0c6ef1)](https://hits.sh/github.com/samyaksand/SmartCode-IEEE-Mumbai-Internship/)

### Internship Project : Real Time Collaborative Code Editor with Chat App
SmartCode is a real-time collaborative online code editor. Users can talk using the chat app in real time over the internet using our web-based application.

### Medium Article 
#### Link - https://medium.com/@samyaksand/creating-a-collaborative-code-editor-website-at-the-ieee-mumbai-an-in-depth-look-7c641f2305cc

<img src="https://user-images.githubusercontent.com/62803746/216034191-2ea82f42-b33b-41ed-86ac-1f677bd75ce4.png" data-canonical-src="https://user-images.githubusercontent.com/62803746/216034191-2ea82f42-b33b-41ed-86ac-1f677bd75ce4.png" width="300" height="300" />
<img src="https://user-images.githubusercontent.com/62803746/216753880-850f5aba-dd3e-4b6b-ab37-1f4d910ae2ab.png" style="display: inline-block; width: 300px" height="300" >


### SmartCode Website - https://team74-ieee-mumbai-internship.netlify.app/
### Code Editor page - https://smartcode-ieee-internship.netlify.app/
### SvelteJS Real Time ChatApp Website  - https://samyaksand-sveltejs-chat-app-ieee-internship.vercel.app/


### ChatApp Demo Video

![Samyak Internship_Realtime ChatApp Svelte_Video Demo](https://user-images.githubusercontent.com/62803746/212531403-3625535d-1959-4b2f-9eab-951728464b01.gif)

### Code Editor Demo Video 

![Code Editor](https://github.com/samyaksand/SmartCode-IEEE-Mumbai-Internship/blob/main/Frontend/public/playground_assets/Smart%20Code%20-%20Made%20with%20Clipchamp.gif)
## Contribution

- Samyak - Realtime ChatApp, website deployments
- Harsh - Code Editor Page
- Varsha - Landing Page
- Rishika - Linking page

## Steps to run project on localhost

## Get started

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000)

# Svelte + Vite

This template should help get you started developing with Svelte in Vite.

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Svelte](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode).

## Need an official Svelte framework?

Check out [SvelteKit](https://github.com/sveltejs/kit#readme), which is also powered by Vite. Deploy anywhere with its serverless-first approach and adapt to various platforms, with out of the box support for TypeScript, SCSS, and Less, and easily-added support for mdsvex, GraphQL, PostCSS, Tailwind CSS, and more.

## Technical considerations

**Why use this over SvelteKit?**

- It brings its own routing solution which might not be preferable for some users.
- It is first and foremost a framework that just happens to use Vite under the hood, not a Vite app.
  `vite dev` and `vite build` wouldn't work in a SvelteKit environment, for example.

This template contains as little as possible to get started with Vite + Svelte, while taking into account the developer experience with regards to HMR and intellisense. It demonstrates capabilities on par with the other `create-vite` templates and is a good starting point for beginners dipping their toes into a Vite + Svelte project.

Should you later need the extended capabilities and extensibility provided by SvelteKit, the template has been structured similarly to SvelteKit so that it is easy to migrate.

**Why `global.d.ts` instead of `compilerOptions.types` inside `jsconfig.json` or `tsconfig.json`?**

Setting `compilerOptions.types` shuts out all other types not explicitly listed in the configuration. Using triple-slash references keeps the default TypeScript setting of accepting type information from the entire workspace, while also adding `svelte` and `vite/client` type information.

**Why include `.vscode/extensions.json`?**

Other templates indirectly recommend extensions via the README, but this file allows VS Code to prompt the user to install the recommended extension upon opening the project.

**Why enable `checkJs` in the JS template?**

It is likely that most cases of changing variable types in runtime are likely to be accidental, rather than deliberate. This provides advanced typechecking out of the box. Should you like to take advantage of the dynamically-typed nature of JavaScript, it is trivial to change the configuration.

**Why is HMR not preserving my local component state?**

HMR state preservation comes with a number of gotchas! It has been disabled by default in both `svelte-hmr` and `@sveltejs/vite-plugin-svelte` due to its often surprising behavior. You can read the details [here](https://github.com/rixo/svelte-hmr#svelte-hmr).

If you have state that's important to retain within a component, consider creating an external store which would not be replaced by HMR.

```js
// store.js
// An extremely simple external store
import { writable } from "svelte/store"; 
export default writable(0);
```
