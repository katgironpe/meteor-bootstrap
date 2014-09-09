# Meteor &amp; Bootstrap Template

A starter boilerplate app template for [Meteor](http://meteor.com) using [IronRouter](https://github.com/EventedMind/iron-router) and Twitter Boostrap.

This is based on [Void](https://github.com/SachaG/Void) template.

## Installation

If you already have Meteor and [Meteorite](https://github.com/oortcloud/meteorite/), the template is ready to go. Just clone it locally, run it with `mrt`, and start coding!

If not, here are the full instructions:

```
curl https://install.meteor.com | /bin/sh
npm install -g meteorite
git clone https://github.com/SachaG/Void.git myApp
cd myApp
mrt
```

## Features

- Client-side routing
- Publications/subscriptions
- Basic permissions
- Common templates
- Twitter Bootstrap

## File Structure


```
├── client
│   ├── css
│   │   ├── alerts.less
│   │   ├── badges.less
│   │   ├── bootstrap.less
│   │   ├── breadcrumbs.less
│   │   ├── button-groups.less
│   │   ├── buttons.less
│   │   ├── carousel.less
│   │   ├── close.less
│   │   ├── code.less
│   │   ├── component-animations.less
│   │   ├── dropdowns.less
│   │   ├── forms.less
│   │   ├── glyphicons.less
│   │   ├── grid.less
│   │   ├── input-groups.less
│   │   ├── jumbotron.less
│   │   ├── labels.less
│   │   ├── list-group.less
│   │   ├── media.less
│   │   ├── mixins
│   │   │   ├── alerts.less
│   │   │   ├── background-variant.less
│   │   │   ├── border-radius.less
│   │   │   ├── buttons.less
│   │   │   ├── center-block.less
│   │   │   ├── clearfix.less
│   │   │   ├── forms.less
│   │   │   ├── gradients.less
│   │   │   ├── grid-framework.less
│   │   │   ├── grid.less
│   │   │   ├── hide-text.less
│   │   │   ├── image.less
│   │   │   ├── labels.less
│   │   │   ├── list-group.less
│   │   │   ├── nav-divider.less
│   │   │   ├── nav-vertical-align.less
│   │   │   ├── opacity.less
│   │   │   ├── pagination.less
│   │   │   ├── panels.less
│   │   │   ├── progress-bar.less
│   │   │   ├── reset-filter.less
│   │   │   ├── resize.less
│   │   │   ├── responsive-visibility.less
│   │   │   ├── size.less
│   │   │   ├── tab-focus.less
│   │   │   ├── table-row.less
│   │   │   ├── text-emphasis.less
│   │   │   ├── text-overflow.less
│   │   │   └── vendor-prefixes.less
│   │   ├── mixins.less
│   │   ├── modals.less
│   │   ├── navbar.less
│   │   ├── navs.less
│   │   ├── normalize.less
│   │   ├── pager.less
│   │   ├── pagination.less
│   │   ├── panels.less
│   │   ├── popovers.less
│   │   ├── print.less
│   │   ├── progress-bars.less
│   │   ├── responsive-embed.less
│   │   ├── responsive-utilities.less
│   │   ├── scaffolding.less
│   │   ├── tables.less
│   │   ├── theme.less
│   │   ├── thumbnails.less
│   │   ├── tooltip.less
│   │   ├── type.less
│   │   ├── utilities.less
│   │   ├── variables.less
│   │   └── wells.less
│   ├── helpers
│   │   ├── flash.js
│   │   ├── handlebars.js
│   │   └── router.js
│   ├── js
│   │   ├── affix.js
│   │   ├── alert.js
│   │   ├── button.js
│   │   ├── carousel.js
│   │   ├── collapse.js
│   │   ├── dropdown.js
│   │   ├── modal.js
│   │   ├── popover.js
│   │   ├── scrollspy.js
│   │   ├── tab.js
│   │   ├── tooltip.js
│   │   └── transition.js
│   ├── main.css
│   ├── main.html
│   ├── main.js
│   ├── main.less
│   └── views
│       ├── common
│       │   ├── footer.html
│       │   ├── header.html
│       │   ├── header.js
│       │   ├── layout.html
│       │   ├── loading.html
│       │   └── notFound.html
│       ├── items
│       │   ├── item.html
│       │   ├── item.js
│       │   ├── items.html
│       │   └── items.js
│       ├── pages
│       │   ├── content.html
│       │   └── homepage.html
│       └── users
│           ├── forgot.html
│           ├── forgot.js
│           ├── login.html
│           ├── login.js
│           ├── signup.html
│           └── signup.js
├── lib
│   ├── helpers.js
│   └── permissions.js
├── models
│   └── items.js
├── packages
│   └── sample-package
│       ├── package.js
│       └── sample.js
├── public
│   └── fonts
│       ├── glyphicons-halflings-regular.eot
│       ├── glyphicons-halflings-regular.svg
│       ├── glyphicons-halflings-regular.ttf
│       └── glyphicons-halflings-regular.woff
└── server
    ├── publications.js
    └── seed.js
```


## Other Boilerplates

- [meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) by matteodem
- [meteor-jw-opinionated-skeleton](https://github.com/jamesdwilson/meteor-jw-opinionated-skeleton) by jamesdwilson (CoffeeScript)
- [meteor-boilerplate](https://github.com/BeDifferential/meteor-boilerplate) by BeDifferential (CoffeeScript)
