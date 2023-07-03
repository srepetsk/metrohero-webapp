# MetroHero Webapp

## Developer Setup

1. Globally install [nvm](https://github.com/creationix/nvm)
2. Globally install node: `nvm install 8.9.4`
3. Globally install gulp (using the same version defined in package.json): `npm install --global gulp-cli@^2.3.0`
4. (Optional) Globally install [npm-check](https://www.npmjs.com/package/npm-check)
5. Run `npm install` in the project directory to install dependencies

## Running Locally

To test against a running local instance of metrohero-server:
  ```
  ./node_modules/gulp-cli/bin/gulp.js watch --test
  ```

Or, to test against live production:
  ```
  ./node_modules/gulp-cli/bin/gulp.js watch --production
  ```

# FAQ
if you want to add banner announcements to the app itself, that would require modifying the webapp code (see the `metrohero-webapp` repository) and deploying those changes to the server.
