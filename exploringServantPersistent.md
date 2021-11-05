# Exploring Servant Persistent

## Overview

### List of files

```
.
├── app
│   └── Main.hs
├── assets
│   ├── api.js
│   └── index.html
├── config
│   └── keter.yml
├── deploy.sh
├── exploringServantPersistent.md
├── Makefile
├── servant-persistent.cabal
├── Setup.hs
├── src
│   ├── Api
│   │   └── User.hs
│   ├── Api.hs
│   ├── Config.hs
│   ├── DevelMain.hs
│   ├── Init.hs
│   ├── Logger.hs
│   └── Models.hs
├── stack.yaml
├── stack.yaml.lock
├── stylish-haskell.sh
└── test
    ├── ApiSpec.hs
    ├── Spec.hs
    └── UserDbSpec.hs

6 directories, 24 files
```

### List of modules

```
├── app
│   └── Main.hs
└── src
    ├── Api
    │   └── User.hs
    ├── Api.hs
    ├── Config.hs
    ├── DevelMain.hs
    ├── Init.hs
    ├── Logger.hs
    └── Models.hs
```

### description (wild guess) of each module

#### app/Main.hs

It has the main function. Load configuration and start the server

#### src/Api/User.hs

User endpoint.

#### src/Api.hs

Group all needed endpoint (User, Static)

#### src/Config.hs

Definition of the initial configuration

#### src/DevelMain.hs

A replacement of main for development

#### src/Init.hs

Initilize application data and configuration (database information, etc)

#### src/Logger.hs

Functions for logging

#### src/Models.hs

Define the models for persistance.

## Data flow

### Server start

- Entry point
- Data
- Values (i.e Globals)    
- Flow (through functions)

### Request received

- Entry point
- Data
- Values (i.e Globals)    
- Flow (through functions)
