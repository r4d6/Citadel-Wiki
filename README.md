Citadel Wiki
===

## Wiki Contributing

Everything under the `citadel-wiki/` folder will be automatically rendered into wiki pages, respecting folder paths.

For example, `citadel-wiki/engineering/atmospherics.md` will be rendered as `/citadel-wiki/engineering/atmospherics`.
All links between pages should follow this pattern. Always begin with the root `/citadel-wiki/`.

All static content should be uploaded to the `citadel-wiki-static/` folder, and can be linked to with the root path being `/citadel-wiki-static/`. This preserves folders and file paths.

> The names of these folders and endpoints is subject to change, but is easily mass editable via scripts, so don't worry.

A rendering of this repository can be found at [katlin.dog/citadel-wiki](https://katlin.dog/citadel-wiki).

## Pages

Pages should be written in Markdown. [This cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) provides good example on syntax. A barebones example page can be found in `citadel-wiki/example-template.md` and rendered at [katlin.dog/citadel-wiki/example-template](https://katlin.dog/citadel-wiki/example-template)

Links to header can be made within pages by making an `#id` link, using the slug of the header. For example, the slug of the header **"Assistants: What not to do"** would be `#assistants-what-not-to-do`. Alphanumeric characters and hyphens only.