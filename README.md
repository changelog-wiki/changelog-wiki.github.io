# Changelog Wiki
This repo is for the main site at https://changelog.wiki.

## Contributor Guidelines
### Categories
The category should denote the platform the system is on, here is a list of valid platforms:
* Windows
* MacOS
* Linux
* Xbox One
* PS4
* Nintendo Switch
* iOS
* Android

### Tags
The tag should denote the name of the software and what type of software it is, for example:

* Vim
* Text Editor

Here is a list of valid types of software: (More added as time goes on)
* Game
* Text Editor
* Operating System
* Software
* Web Browser

### Changelogs

When creating a new page, please place it in the appropriate folder. Usually located as: `content/post/<platform>/<name of software>/<date>-<version>.md`
At the top of the file, place the following information:
```js
+++
author = "<your GitHub username>"
title = "<name of the software> <version> Update"
date = "<date of release in YYYY-MM-DD format>"
categories = [
    "<platform which the software runs on>",
]
tags = [
    "<name of the software>",
    "<type of software>"
]
+++
```

Afterwards you can place the changelog. 
* If the developers provide a changelog you should copy and paste it exactly as is, as well as provide a source link at the bottom.
* If no changelog is provided try to find a community made one of a reputable source, these can be paraphrased in order to make it shorter and easy to read.

## Notes
* If the software has already had a changelog on here before, please try to keep the naming consistent. This allows users to more easily find it when searching the tags.
* If you disagree with how the name is written out, bring it up in your PR! We are always wanting to improve and your feedback is valuable.
* If a software is available on multiple platforms, you are free to put as many as the changelog is applicable to in the categories section, although you should denote any platform specific updates within the changelog. However if the version numbering is different on the platforms please make new posts for each one.
* If you need to convert a table from a website into markdown, the website https://tabletomarkdown.com/ is recommended.