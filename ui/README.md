---

# syn sample UI

This is UI is built using svelte from the standard svelte template for [Svelte](https://svelte.dev) apps. It lives at https://github.com/sveltejs/template.


## Get started

Install the dependencies...

```bash
cd ui
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see the UI running.

Note: the syn happ must be running with the installed_app_id="syn" on port 8888.  Which will happen if you launch it with [holochain-run-dna](https://github.com/holochain-open-dev/holochain-run-dna)


## Using TypeScript

This template comes with a script to set up a TypeScript development environment, you can run it immediately after cloning the template with:

```bash
node scripts/setupTypeScript.js
```

Or remove the script via:

```bash
rm scripts/setupTypeScript.js
```