# Foundation Demo

Demo static site generation with [ZURB Foundation](http://foundation.zurb.com)

## Installation

Install:
- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

Run:
- `npm install -g bower foundation-cli`
- `npm install`
- `bower install`

## Building

Dev Server:
- `npm start`

Prod Build (located in `dist/`)
- `npm build`

## GitLab CI

Define the following secret variables:
- `SSH_HOST`: Server IP
- `SSH_HOST_KEY`: SSH Server Fingerprint
- `SSH_PRIVATE_KEY`: SSH Private Key
