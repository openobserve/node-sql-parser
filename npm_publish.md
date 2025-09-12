Step1:
create .npmrc file with below content:

@openobserve:registry=https://registry.npmjs.org/
//registry.npmjs.org/:_authToken=npm_wZJw****************

Note: replace the active apiToken to publish the package.

Step2: change version in package.json file.

Step3: build the package using npm run build

Step4: Go to output/prod directory and run "npm publish --userconfig=../../.npmrc" command to publish the package