---
title: "Changelog: Webhook, i18n, SMTP"
date: 2021-04-26
tag:
  - changelog
---

We are happy to launch `v1.1.1`.

## Webhook

Inaddition to Email notification, we also provide Webhook, which is a more flexible way to customize notification by users themselves, such as integrating with Slack, Discord, Telegram, etc. 

Checkout the [documentation](https://cusdis.com/doc#/advanced/webhook) to know more about how to use webhook.

We can't wait to see people show how they use Webhook to integrate Cusdis into their tools! Please share with us!

## Pagination ([#54](https://github.com/djyde/cusdis/pull/54))

Thanks to [Travis Geis](https://github.com/ottobonn), we enhance the comments paginator in dashboard and widget.

## i18n

We support internationalize in the comment widget now. [Documentation](https://cusdis.com/doc#/advanced/i18n).

You are super welcome to contribute your language into Cusdis! Feel free to create a PR.

Thanks [pablopvsky](https://github.com/pablopvsky) to contribute Spanish.

We are still working on i18n for the dashboard.

## SMTP

You can enable Email notification in self-host Cusdis by setting SMTP configuration. [Documentation](https://cusdis.com/doc#/features/notification?id=self-host)

Thanks [frostming](https://github.com/frostming) to help test this feature.