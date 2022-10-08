stub / wip

- set up github pages for examples/readme site: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- update package.json to have correct version, links
- update readme to point to correct repo, have correct version, links
- publish github release

publishing to npm through github (experimental, untested)
see: https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-npm-registry
     https://github.com/c-frame/aframe-physics-system/packages

- add a `.npmrc` file to the repo root, with this line:
    - c-frame:registry=https://npm.pkg.github.com
- add this to package.json:
    "publishConfig": {
        "registry":"https://npm.pkg.github.com"
    },

publishing to npm the old fashioned way:
- clone locally to publish to npm: https://jamescalmus.medium.com/how-to-publish-a-scoped-npm-package-for-your-organization-767af1c99b9f / https://docs.npmjs.com/creating-and-publishing-an-organization-scoped-package
    - npm init --scope=c-frame
    - npm publish --access public
