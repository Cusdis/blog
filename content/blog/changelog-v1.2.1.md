---
title: "Changelog: iframe-based widget"
date: 2021-05-21
tag:
  - changelog
---

So excited to announce `v1.2.0`, which is a minor version update.

The reason why this update is a minor version update, is we changed the implementation of the comment widget. In `v1.1.x`, the widget will be appended on the DOM element directly on your page. 

In order to not affect the style on users' page, we need to use scoped css and give the element a scoped class name. But it doesn't solve the problem that the user's page style will affect the widget's style, and sometimes would cause [global variable conflict](https://github.com/fluid-dev/hexo-theme-fluid/pull/480#issuecomment-840296743).

The best practice is to load the widget in an iframe. Since the widget in iframe run in a different context, we refacted our widget UI with [TailwindCSS](https://tailwindcss.com/).

The SDK api didn't change. It means users don't have to change the code in their pages. The only breaking change is customizing style by css variable doesn't work anymore. We need to figure out another way to achieve it.