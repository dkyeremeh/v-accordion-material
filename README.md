# V-Accordion Material

This is a material theme for [v-accordion](https://github.com/LukaszWatroba/v-accordion). It follows the material design guideline for [expansion panels](https://material.io/guidelines/components/expansion-panels.html).

With v-accordion-material, you can also create [expansion panels](https://material.io/guidelines/components/expansion-panels.html)  for [angular material](https://material.angularjs.org) using [v-accordion](https://github.com/LukaszWatroba/v-accordion) - (an accordion module for angularjs)

## DEMO
[CodePen](https://codepen.io/anon/pen/PKQWQW)

## Installation instructions

### Bower
Run `bower install v-accordion-material --save`

### Npm
Run `npm i v-accordion-material`

### Yarn
Run `yarn add v-accordion-material`

### Manual Install
1. Download the latest release of v-accordion-material
2. Download [v-accordion](https://github.com/LukaszWatroba/v-accordion)

## Usage
Include the files for `v-accordion`, and `v-accordion-material` in your project

```html
<link href="v-accordion.css" rel="stylesheet" />
<link href="v-accordion-material.css" rel="stylesheet" />

<script src="v-accordion.js"></script>
```

**Follow the instructions** for [v-accordion](https://github.com/LukaszWatroba/v-accordion) to learn to use v-accordion

### Setting Material theme
In order to use this theme, set `v-accordion-material` as the class name of `<v-accordion>` as shown below:

```html
<v-accordion class="v-accordion-material">
...
</v-accordion>
```
### md-title and md-summary
According to the [material design guidelines](https://material.io/guidelines/components/expansion-panels.html) the header should contain a header and a summary. This can be implemented by using the md-title and md-summary components in the v-pane-header as shown below

```html
<v-pane-header>
	<div class="md-title">Title</div>
	<div class="md-summary">The summary of the content</div>
</v-pane-header>
```