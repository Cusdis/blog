---
title: Integrate Cusdis into Hexo
date: 2021-04-25
---

[Hexo](https://hexo.io) is a popular blog framework in Node.js. It's very easy to integrate Cusdis into hexo. Suppose user has such theme's `_config.yml`:

```yaml
cusdis:
  host:
  app_id: xxx
```

Here is an example in Nunjucks/Swig template syntax:

```
<div id="cusdis_thread"
  data-host="{{ theme.cusdis.host || 'https://cusdis.com' }}"
  data-app-id="{{ theme.cusdis.app_id }}"
  data-page-id="{{ page.path }}"
  data-page-url="{{ page.permalink }}"
  data-page-title="{{ page.title }}"
></div>
```

If you use different template, just follow this cheatsheet:

|  Attribute   | Hexo variable  |
|  ----  | ----  |
| data-host  | _set by user in config_ |
| data-app-id  | _set by user in config_ |
| data-page-id  | page.path |
| data-page-title  | page.title |
| data-page-url  | page.permalink |

Here is an example we integrate Cusdis into [hexo-theme-even](https://github.com/ahonn/hexo-theme-even/pull/280/files).