# qa-function-nodejs

Example repository for publishing an HTTP function: Node.js, with Google's Functions
Framework, built with Google's buildpacks.

- The function to run is `helloHttp`, named in `package.json` (`functions-framework --target=helloHttp`), so it is proposed when the repository is imported.
- It answers every request with a fixed text, so a 200 shows it is up.
