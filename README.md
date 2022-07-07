# TachyonCMS Multi-Site App

This is a starting point for building a Quasar app backed by TachyonCMS content.

We will support both static and semi-static page generation. Only the semi-static routes required for domain parking are fully baked.

This app supports operating under different domains from one deployed website, while still providing unique content for each domain.

## Managing Content

You can use the free CMS editor available at https://www.tachyoncms.org/.

## Content Directories

There are three directories that have TachyonCMS flows defined.

1. `app/src/tcms-config` - Define the sites and hotsnames supported here.

2. `app/src/tcms` - Define content for static pages here.

3. `app/public/tcms` - Define content for semi-static serving here.
