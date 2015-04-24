# nimm

npm install missing modules

nimm provides a wrapper for a node process that will detect when you've tried to require a module that's not installed, and will prompt you to install it.

## Install

```
npm install -g nimm
```

## Usage

```
nimm my-app.js
```

Then when a missing module is detected a prompt will appear asking if you want to install the module.

Installing the module will restart your app. Not installing the module will exit.
