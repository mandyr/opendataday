Open Data Day is a gathering of citizens in cities around the world to write applications, liberate data, create visualizations and publish analyses using open public data to show support for and encourage the adoption of open data policies by the world's local, regional and national governments.

You're invited. Again. The next Open Data Day will take place on Saturday, 4 March 2017.

Check <http://opendataday.org/> for public website.

## Editing / contributing

This site is built with [Lektor](https://www.getlektor.com/).

It has a bunch of [dependencies](https://github.com/okfn/opendataday/blob/v2/package.json), so do an `npm install`.

`grunt` will watch for changes to your SCSS files, and also icons (see [svgstore](https://github.com/FWeinb/grunt-svgstore)).

### TODO

#### Map

Needs to be added [here](https://github.com/okfn/opendataday/blob/v2/templates/home.html#L60).

#### Translations (currently commented out)

To translate the site we need to duplicate the [contents.lr](https://github.com/okfn/opendataday/blob/v2/content/contents.lr) file, and save with the language code in the file name, like [contents+de.lr](https://github.com/okfn/opendataday/blob/v2/content/contents%2Bde.lr).

We also need to add translations to [global-content.ini](https://github.com/okfn/opendataday/blob/v2/databags/global-content.ini) and [main-nav.ini
](https://github.com/okfn/opendataday/blob/v2/databags/main-nav.ini).

If we are adding new language to the site we also need to:

- Add the new language to [languages.json](https://github.com/okfn/opendataday/blob/v2/databags/languages.json)
- Add the language to [project.lektorproject](https://github.com/okfn/opendataday/blob/v2/project.lektorproject).

## Previous version

The previous version of the site has been moved to the [v1](https://github.com/okfn/opendataday/tree/v1) branch.
