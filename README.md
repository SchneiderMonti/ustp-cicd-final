# USTP CI/CD Tetris

## 🌐 Live Application
[https://schneidermonti.github.io/ustp-cicd-final/](https://schneidermonti.github.io/ustp-cicd-final/)


[![Build](https://github.com/SchneiderMonti/ustp-cicd-final/actions/workflows/build.yml/badge.svg?event=push)](https://github.com/SchneiderMonti/ustp-cicd-final/actions/workflows/build.yml)
[![Publish](https://github.com/SchneiderMonti/ustp-cicd-final/actions/workflows/publish.yml/badge.svg)](https://github.com/SchneiderMonti/ustp-cicd-final/actions/workflows/publish.yml)
[![Release](https://github.com/SchneiderMonti/ustp-cicd-final/actions/workflows/release.yml/badge.svg)](https://github.com/SchneiderMonti/ustp-cicd-final/actions/workflows/release.yml)


## 📦 Project Overview
This repository contains a web-based Tetris application used as part of a CI/CD practical exam. The project demonstrates a complete DevOps pipeline using GitHub Actions, including:

* Automated builds and testing
* Artifact generation
* GitHub Pages deployment
* Automated releases
* Dependency management with Dependabot
* CODEOWNERS enforcement

## 🛠 Local Development

### Install dependencies
npm ci

### Build the project
npm run build

### Run tests
npm test

## ⚙️ CI/CD Workflows

### Build
* Triggered on push to main and pull requests
* Builds the application
* Uploads build artifacts

### Test
* Runs on Linux and Windows
* Executes unit tests
* Uploads test results

### Publish
* Manually triggered
* Deploys build artifacts to GitHub Pages
* No rebuild required

### Release
* Triggered by tags (vX.X.X)
* Creates a GitHub Release
* Attaches build artifacts
* Generates release notes automatically

## 🔐 Repository Rules
* Pull requests required for main
* Force pushes disabled
* Branch deletion disabled
* CODEOWNERS configured for workflow files
* Tag protection for version tags (vX.X.X)

## 🔄 Dependabot
Dependabot is configured to:
* Check npm dependencies weekly
* Group all dependency updates into a single pull request

## 👤 Author
Timon Schneider
CI/CD Practical Exam – USTP

## ✅ Status
* ✔ CI configured
* ✔ Tests passing
* ✔ Pages deployed
* ✔ Releases automated
* ✔ Dependabot active
* ✔ CODEOWNERS configured
