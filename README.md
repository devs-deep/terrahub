# Welcome to TerraHub

## Quick Links

[TerraHub CLI](#terrahub-cli) | [TerraHub API](#terrahub-api) | [TerraHub Console](#terrahub-console) | [Install CLI](#install-cli) | [Examples and More](#examples)

Official TerraHub Documentation: https://docs.terrahub.io


## TerraHub CLI

terraform automation and orchestration tool
* built using [node.js](https://nodejs.org)
* published using [npm](https://www.npmjs.com/package/terrahub)
* managed using [github](https://github.com/TerraHubCorp/terrahub)
* documented using [gitbook](https://docs.terrahub.io)


## TerraHub API

data and logs management, requires token to collect anything
* built using [node.js](https://nodejs.org)
* managed using [swagger](https://www.terrahub.io/api)
* documented using [swagger](https://www.terrahub.io/api)


## TerraHub Console

enterprise friendly GUI to show realtime terraform executions, as well as
auditing and reporting capabilities for historical terraform runs
* built using [vue.js](https://vuejs.org)
* managed using [webpack](https://webpack.js.org)
* published using [terrahub](https://console.terrahub.io)


## Install CLI

Getting started with TerraHub CLI is pretty straightforward:

1. Check if `npm` is installed:

  ```shell
  npm -v
  ```

  The output should look similar to the one below (no need to copy paste):

  ```text
  v3.10.0
  ```

  > NOTE: If `npm` is missing, check out [Downloading and installing Node.js and npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

2. Install `terrahub` globally using `npm`:

  ```shell
  npm install --global terrahub
  ```

  The output should look similar to the one below (no need to copy paste):

  ```text
  ~/.nvm/versions/node/v6.10.0/lib
  └── terrahub@0.0.1
  ```

3. Test if `terrahub` cli was installed properly:

  ```shell
  terrahub --help
  ```

  > NOTE: [TerraHub CLI](https://www.npmjs.com/package/terrahub) doesn't magically collect your data and upload to [TerraHub API](https://www.terrahub.io/api), which is further visualized in [TerraHub Console](https://console.terrahub.io). In order to do that, please sign up for a free account at [console.terrahub.io](https://console.terrahub.io) and navigate to [Settings](https://console.terrahub.io/settings) page to copy TerraHub Token. Next, setup TerraHub Token as `THUB_TOKEN` environmental variable or update `token` value in global config file - `$HOME/.terrahub/.terrahub.json`.


## Examples

![TerraHub CLI and TerraHub Console in Action](https://raw.githubusercontent.com/TerraHubCorp/terrahub/dev/docs/images/terrahub-in-action.gif "TerraHub CLI and TerraHub Console in Action")

Examples and Documentation:
* [Terraform Automation using AWS Provider](https://github.com/TerraHubCorp/demo-terraform-automation-aws)
* [Terraform Automation using Google Provider](https://github.com/TerraHubCorp/demo-terraform-automation-google)
* [Official TerraHub Documentation](https://docs.terrahub.io)
