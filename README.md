# yarn-pnp-vite-ts-react-template

This boilerplate will easily let you work with react+typescript using vite and yarn pnp for extra speed ⚡⚡⚡.

SASS batteries included 😉
## Requirements
- Yarn - Update to its latest version (i've only tested with ^3)

## Install 
Easy as 
```sh
$ git clone https://github.com/JavierScars/yarn-pnp-vite-ts-react-template.git
$ cd yarn-pnp-vite-ts-react-template
$ yarn
$ yarn run configure
$ yarn dev
```
## Build
Just run
```sh
$ yarn build
```

## Settings
### path Aliases
To add new path aliases, add them to the ```resolve.alias``` property of the ```vite.config.ts``` file and in the ```compilerOptions.path``` property of the ```tsconfig.json``` file. It's pretty easy just follow the existing examples 😄.

## Support
I've tested the typescript autocomplete feature only in VSCode, I don't really know if it will work in others IDEs.

If you have any problems please check for the command
```
yarn dlx @yarnpkg/sdks
```
It's what makes VSCode support pnp packages in vscode.