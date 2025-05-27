# Github Actions for liferay-database-infra

## Workflows
### [Sync liferay-portal fork](https://github.com/liferay-database-infra/github-actions/blob/master/.github/workflows/sync-liferay-portal.yml)

This is a cron job that runs hourly to sync [liferay-database-infra/liferay-portal](https://github.com/jorgediaz-lr/liferay-portal) to [liferay/liferay-portal](https://github.com/liferay/liferay-portal)

## Configuration

*(using the `liferay-database-infra` user)*

### Create a new Action:

Go to https://github.com/liferay-database-infra/github-actions/actions => create "new workflow" => "set up a workflow yourself" 

### Create or renew the personal access token (PAT)

Github cli uses a personal access token to authenticate: `GH_TOKEN: ${{ secrets.PAT }}`

To create it, go to https://github.com/settings/personal-access-tokens

Once it is created, copy it to the actions secrets: https://github.com/liferay-database-infra/github-actions/settings/secrets/actions
