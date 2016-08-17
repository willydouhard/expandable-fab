[![Build Status](https://travis-ci.org/willydouhard/expandable-fab.svg?branch=master)](https://travis-ci.org/willydouhard/expandable-fab)

_[Demo and API docs](https://willydouhard.github.io/expandable-fab/components/expandable-fab/)_

WARNING: This component is relying on the web animation api. The poly fill is in the component dependencies, so you just have to include it in your index.html file.

Example:

```html
<script src="bower_components/web-animations-js/web-animations-next-lite.min.js"></script>
```

`expandable-fab` is a paper-fab that can expand into a drawer (android like).

Example:

```html
<expandable-fab
drawer-height="300"
drawer-width="200"
background-color="red"
orientation="top-left"
fab-icon="add"
fab-diameter="60">
     <img class="item" src="icons/logo_docs_64px.png"/>
     <img class="item" src="icons/logo_forms_64px.png"/>
     <img class="item" src="icons/logo_gmail_64px.png"/>
     <img class="item" src="icons/logo_google_plus_64px.png"/>
     <img class="item" src="icons/logo_hangouts_64px.png"/>
     <img class="item" src="icons/logo_slides_64px.png"/>
</expandable-fab>
```

You can style the items you are passing with a css class. If you want to change the way your content is displayed when the drawer is open,
use the --drawer-content-mixin to apply your rules. By default, the component is using flexbox

### Styling
The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| ----------------|-------------|---------- |
| `--drawer-content-mixin` | Mixin applied to the drawer content | `{}` |
