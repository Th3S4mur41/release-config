# @th3s4mur41/release-config

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?machine=basicLinux32gb&repo=445480037&ref=main)

![Package version](https://img.shields.io/github/package-json/v/Th3S4mur41/release-config)
![GitHub last commit](https://img.shields.io/github/last-commit/Th3S4mur41/release-config)
![Release](https://github.com/Th3S4mur41/release-config/actions/workflows/on_push.yml/badge.svg?branch=main)

A configuration for semantic-release that will create patches for dependencies updates

## Prerequistes

### Install NPM

Install Node.js and NPM in your local development environment by following the instructions at [npmjs.com](https://nodejs.org/).
When installation is complete, verify you can use NPM in your terminal by running:

`npm --version`

The NPM version is shown in the output:

`8.1.0`

### Create a project

_Skip this step if you already have a package.json_

To create a project:

Create an empty directory.
Go to the directory and initialize an empty package by running:

`npm init`

Enter responses to the questions. Ensure the package name follows the naming convention and is scoped to the project or group where the registry exists.

A package.json file is created

## Installation

```
npm install @th3S4mur41/release-config
```

or

```
yarn add @th3S4mur41/release-config
```

## Usage

Add a `.releaserc.json` file to the root of your project with the following content:

```
{
"extends": "@th3S4mur41/release-config"
}
```

Done, now you can release your project automatically by running `npx semantic-release`
