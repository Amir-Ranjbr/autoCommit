# auto-commit

🌳 Making green your Github stats, powered by [Github Actions](https://github.com/features/actions)

## Make it your own

- Create your own repo with click "**Use this template**" button (forked repo will not work)

Or just do in the manual way:

- Create your own repo
- You have to configure your repository - Settings -> Action -> General -> Workflow permissions and choose read and write permissions
- Copy file `.github/workflows/autocommit.yml` and `LAST_UPDATED` to your repo
- Change the `email` and `name` information on file [autocommit.yml, line 31 and 32](https://github.com/amir-ranjbr/autoCommit/blob/main/.github/workflows/autocommit.yml#L31)
- Change the scheduling time on file [autocommit.yml, line 10](https://github.com/amir-ranjbr/autoCommit/blob/main/.github/workflows/autocommit.yml#L10). You can use [crontab.guru](https://crontab.guru/) if you are not familiar with the cron schedule string. For first time, you can try to run it in every hour with string `1 * * * *` .
- Consider to support me, at least click the 🌟 button

## Repo using this auto-commit

- You can add your repo here

## Credits

- [Github Actions](https://github.com/features/actions)
- [ad-m/github-push-action](https://github.com/ad-m/github-push-action)
