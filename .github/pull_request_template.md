Thank you for sending in this pull request. Please make sure you take a look at the [contributing file](https://github.com/actions/starter-workflows/blob/master/CONTRIBUTING.md). Here's a few things for you to consider in this pull request:

- [ ] Include a good description of the workflow.
- [ ] Links to the language or tool will be nice (unless its really obvious)

In the workflow and properties files:

- [ ] Includes a matching `ci/properties/*.properties.json` file.
- [ ] Use title case for the names of workflows and steps, for example "Run tests".
- [ ] The name of CI workflows should only be the name of the language or platform: for example "Go" (not "Go CI" or "Go Build")
- [ ] Include comments in the workflow for any parts that are not obvious or could use clarification.
- [ ] CI workflows should run `push`.
- [ ] Packaging workflows should run on `release` with `types: [created]`.

Some general notes:

- [ ] Does not use an Action that isn't in the `actions` organization.
- [ ] Does not send data to any 3rd party service except for the purposes of installing dependencies.
- [ ] Does not use a paid service or product.
"publishConfig": { "registry": "https://npm.pkg.github.com/" }
// Step 2: Authenticate
$ npm login --registry=https://npm.pkg.github.com/

// Step 3: Publish
$ npm publish
© 2020 GitHub
