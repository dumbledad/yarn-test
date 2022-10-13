# Yarn Test

Just me playing around to understand Yarn a bit

# Notes

- [.gitignore](https://yarnpkg.com/getting-started/qa#which-files-should-be-gitignored)
- `yarn set version stable` locks the yarn version used by this project to the latest stable version ([docs](https://yarnpkg.com/cli/set/version))
- From [recipes](https://yarnpkg.com/getting-started/recipes)
  - `yarn add --dev typescript` add typescript ([docs](https://yarnpkg.com/cli/add))
  - `yarn dlx @yarnpkg/sdks vscode` adding VSCode integration ([Editor SDKs](https://yarnpkg.com/getting-started/editor-sdks) & [dlx docs](https://yarnpkg.com/cli/dlx))
  - `yarn plugin import typescript` enable Yarn's TypeScript plugin, which helps manage @types/* dependencies automatically ([docs](https://yarnpkg.com/cli/plugin/import))
  - After adding an `app.ts` file it can be compiled with `yarn tsc app.ts` and the resulting json run with `node app.js`
  - I still do not understand what is meant by [dependencies](https://docs.npmjs.com/cli/v8/configuring-npm/package-json#devdependencies) in yarn and how to use them
