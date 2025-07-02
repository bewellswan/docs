# Mila Health Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mila Health CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g milacli
```

Run the following command at the root of your documentation (where docs.json is)

```
milacli dev
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard.

#### Troubleshooting

- milacli dev isn't running - Run `milacli install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `docs.jsonM`