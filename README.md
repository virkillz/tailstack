# Tailstack

This is a fork from other project: [stitches](https://github.com/amiechen/stitches-template-generator)

The project goals are:
- Upgrade all to the stable version (v.1)
- Use different color method such as primary, secondary, danger, warning, success
- Used as snippet catalog
- To be able to readjust the tailwind config, regenerate css, minify and use it as drag drop HTML composer.




## Running it locally

cd into Tailstack directory.

```
npm install
```

Run server

```
npm run start
```


Recompile JS

```
browserify main.js -o bundle.js
```

Recompile CSS if you modify tailwind.comnfig.js.

```
npm run refresh
```

## Make your own templates

Feel free to take this project and re-factor to your need! Not everyone wants these templates for their projects. Here are the steps:

1. Add your own HTML template (with tailwind.css classes) into the `templates` folder
2. Add a filter button for it in the `index.html`. (i.e. add `<button class="text-black font-semibold hover:text-green px-2 py-1 transition-normal" data-filter="st-<your template name>">Tabs</button>`)
3. Done! refresh to check out your own templates.


## License

MIT 
