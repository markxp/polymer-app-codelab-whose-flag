# google codelab example - whose-flag-app

[codelab](https://codelabs.developers.google.com/codelabs/whose-flag)

see different branches for completion.

## step 10 deploy to firebase

- polymer.json "sources" changes files for polymer-tools to process production code. default: ["src/**/*"] (see [polymer.json spec](https://www.polymer-project.org/2.0/docs/tools/polymer-json))
- Build your production code: `polymer build`
- Create a new firebase project
- In your project root folder: `firebase init`
- select hosting functionality
- `firebase deploy`