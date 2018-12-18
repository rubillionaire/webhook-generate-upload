# Deprecation notice.

This repository is no longer being used. Instead https://github.com/risd/webhook will download webook-generate packages (such as [@risd/webhook-generate](https://www.npmjs.com/package/@risd/webhook-generate)) from npm, and untar them in order to create and update sites.

# webhook-generate-upload

Series of npm scripts to clone the [`risd/webhook-generate`][risd-webhook-generate] repo, zip, and upload to a Google Cloud Storage bucket. The generate zip file will be available at http://webhook-assets.risd.systems/generator.zip.

To use: `npm install & npm start`.

### Updating the Generate Repo

Make updates to the [`risd/webhook-generate`][risd-webhook-generate]. The latest files on the master branch will be used to populate the zip file used when `rm-wh create` is run.

[risd-webhook-generate]:http://github.com/risd/webhook-generate
