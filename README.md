# auto-commit

🌳 Making green your Github stats, powered by [Github Actions](https://github.com/features/actions)

[![Auto commit](https://github.com/jieponk/auto/workflows/Auto%20commit/badge.svg)](https://github.com/jieponk/auto/actions?query=workflow%3A%22Auto+commit%22)

![Jieponk's Github Stats](https://ghchart.rshah.org/jieponk)

## Make it your own

- Create your own repo with click "**Use this template**" button (⚠️ forked repo will not work)

Or just do in the manual way:

- ✅ Create your own repo
- ✅ Copy file `.github/workflows/autocommit.yml` and `LAST_UPDATED` to your repo
- ✅ You have to configure your repository. Go to: **Settings** -> **Action** -> **General** -> **Workflow permissions** and choose **"Read and write permissions"**
- ✅ Change the `email` and `name` information on file [autocommit.yml, line 29 and 30](github.com/jieponk/auto/blob/master/.github/workflows/autocommit.yml#L29)
- ✅ Change the scheduling time on file [autocommit.yml, line 10](github.com/jieponk/auto/blob/master/.github/workflows/autocommit.yml#L10). You can use [crontab.guru](https://crontab.guru/) if you are not familiar with the cron schedule string. For first time, you can try to run it in every hour with string `1 * * * *` .
- ✅ Consider to support me, at least click the 🌟 button

## Article (in Bahasa Indonesia)

- https://mazipan.space/membuat-commit-otomatis-ke-github/

## Repo using this auto-commit

- You can add your repo here


## Credits

- [Github Actions](https://github.com/features/actions)
- [ad-m/github-push-action](https://github.com/ad-m/github-push-action)

## Consider to Support

- 👉 🌍 [Paypal](https://www.paypal.me/jieponk?utm_source=github)


---

© 2020 Crafted by Rudi Parwanto

