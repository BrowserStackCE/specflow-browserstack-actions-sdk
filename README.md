# browserstack-specflow-sdk

This repository uses the [BrowserStack plugin by specflow](https://github.com/SpecFlowOSS/SpecFlow.Actions/tree/main/Plugins/Specflow.Actions.Browserstack)

To run the test cases you can simply use the Test explorer in Visual Studio

there are some shortcomings of this plugin.
1. Once installed you cannot run tests locally by setting any environment variable (like how we do in our SDKs by setting BROWSERSTACK_AUTOMATE= False).
2. Running in parallel is a complicated since we need a new json file for each device browser combination.
3. In the docs they have mentioned that it only supports desktop browsers but I was able to run on mobile (no sure whats the catch)
