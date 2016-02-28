# System Designer

[![npm version](https://badge.fury.io/js/system-designer.svg)](http://badge.fury.io/js/system-designer)
[![Build Status](https://travis-ci.org/system-sdk/system-designer.svg?branch=master)](https://travis-ci.org/system-sdk/system-designer)
[![devDependency Status](https://david-dm.org/system-sdk/system-designer/dev-status.svg)](https://david-dm.org/system-sdk/system-designer#info=devDependencies)

![Image Alt](http://designfirst.io/img/v2/system-designer.png)

#### What is System Designer ?

Design is the base of every app. 
[System Designer](http://designfirst.io) will help you to create **JavaScript Application Systems**, applications driven by the design.

Features:

* **No file-system**: focus on your business logic and not on the structure of your project. Your entire project is stored in a NoSQL DB and it can be exported in a single JSON object.
* **Hot-reload**: updating a method in System Designer will automatically inject it in your connected app. You do not need to reload your app to see your latests modifications.
* **Remote designing** : get the model, behaviors and components of all running apps and update them live.
* **Module builder**: Your HTML or CSS can be required in your app.

You can test System Designer [here](https://system-designer.github.io).

System Designer is part of the [System SDK project](https://github.com/system-sdk).
System SDK is a SDK for building JavaScript Application Systems.

## Installation

#### Direct download

* [Download the zip file](https://github.com/system-sdk/system-designer/archive/master.zip) of this project,
* unzip it and
* open `/system-designer-master/designer/index.html` with Mozilla Firefox.

#### Node.js

```sh
$ npm install system-designer --save
```

Then:

* open `/node_modules/system-designer/designer/index.html` with Mozilla Firefox or Google Chrome.

#### Bower

```sh
$ bower install system-designer --save
```

Then:

* open `/bower_components/system-designer/designer/index.html` with Mozilla Firefox or Google Chrome.

## Build

#### Installation

Once you have cloned the repository:

```sh
# needed by grunt (maybe you have this installed already)
$ npm install -g grunt-cli
$ npm install
$ bower install
```	 	

#### Grunt tasks

Here are the different tasks you can use to automate tasks:


```sh
# clean
$ grunt clean
# build
$ grunt build
# watch
$ grunt watch
# start the app
$ grunt start
```

To run System Designer, go to [http://localhost:9001/](http://localhost:9001/) .

## Documentation

* [Quick Start](https://system-designer.github.io/documentation/documentation.html)

## Licence

Copyright (C) 2016 - Erwan Carriou
 
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
 
You should have received a copy of the GNU General Public License
along with this program.  If not, see http://www.gnu.org/licenses/. 