# Tailstack

A simple tool to generate and compose common component into HTML. All component will be rewrite into Tailwind v.1


## Running it locally

cd into Stitches directory.

```
npm install
```

Run Browserify to bundle all node modules.

```
browserify main.js -o bundle.js
```

Recompile tailwind css.

```
npx tailwind build stitches.css -c ./tailwind.config.js -o ./output.css
```

## Make your own templates

Feel free to take this project and re-factor to your need! Not everyone wants these templates for their projects. Here are the steps:

1. Read the [Contributing guideline here](./CONTRIBUTING.md).
2. Run the project locally (see the section above)
3. Use [200 ok](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en) to run the repo in browser (because file download requires http).
4. Add your own HTML template (with tailwind.css classes) into the `templates` folder
5. Add a filter button for it in the `index.html`. (i.e. add `<button class="text-black font-semibold hover:text-green px-2 py-1 transition-normal" data-filter="st-<your template name>">Tabs</button>`)
6. Done! refresh to check out your own templates.


## License

MIT 
