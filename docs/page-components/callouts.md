---
layout: page
title: Callouts
subtitle: Page Components
menubar: docs_menu
show_sidebar: false
toc: true
---

## What are callouts?

Call outs allow you to create a section on a page that has items with an icon, title, subtitle, description and a link. You can use them to promote features or links to important pages in your site and create a landing page.

[View the example landing page](/bulma-clean-theme/landing/) 

## Create a callout data file

Create a data file following the below format. The style is for classes to set the background colour and sizes you would like to use of the Bulma hero container for the callouts.

You can set the height of the callouts in the data file, such as is-small, is-medium or is-large. If unset it will be is-medium by default.

The items have 6 fields, but only the title and subtitle are required. If the icon is a brand icon, such as GitHub in the below example, set `icon_brand: true`.

```yaml
style: is-light
height: is-medium
items:
  - title: Example callout 1
    subtitle: Example subtitle 1
    icon: fa-space-shuttle
    description: >
      The example description text goes here and can be multiple lines.

      For example, such as this. 
    call_to_action_name: Call to action 1
    call_to_action_link: /page-1/
  - title: Example callout 2
    subtitle: Example subtitle 2
    icon: fa-wrench
    description: >
      The example description text goes here and can be multiple lines.

      For example, such as this.
    call_to_action_name: Call to action 2
    call_to_action_link: /page-2/
  - title: Example callout 3
    subtitle: Example subtitle 3
    icon: fa-github
    icon_brand: true
    description: >
      The example description text goes here and can be multiple lines.

      For example, such as this.
    call_to_action_name: Call to action 3
    call_to_action_link: /page-3/
```

## Set the callouts in the frontmatter

To display the callouts on your page, add a callouts property in the front matter and set it to the name of your data file without the extension.

```yaml
layout: page
title: Example Landing Page
subtitle: This is an example landing page
callouts: example_callouts
```