# Open Source Community Maintenance

> Or, how to open source

Work in progress. Open an issue if you've got questions, or tweet at @richlitt, or better yet, email richard@burntfen.com.

## Table of Contents

## Introduction

### What is this thing

This is a list of notes, tools, and resources for how to run an open source community-based project on GitHub, today.

...

## Chapter 1: Read the thing that says "README"

Your README file is generally the go-to document for people to understand, install, use and interact with your module. Standardizing how your README files are written ensure that they have all the elements necessary for people to easily understand and engage with your module. By using a Standard README format, the process of creating and maintaining accurate and well-written documentation that describes what your module is for, how it can be installed, how it is used, and any other relevant details, will be far easier for you.

## Chapter 7: Edit your package, Jason

[`package.json`](https://docs.npmjs.com/files/package.json) is a plain JSON (Java Script Objet Notation) text file which contains the metadata information about your module and is the best way to manage locally installed npm packages. By adding this metadata information to your module you identify it as a unique package, allowing for other developers to to install and update your module using npm. The package.json file also defines which packages your module depends on and allows you to specificy which versions of those packages it should use.

TK More on these, here: docs.npmjs.com/files/package.json

#### `bugs`

The "bugs" field contains the information which people need to report issues with your module. The field can be populated with a url to your module's issue tracker and/or the email address to which such issues should be reported. Including this information allows for any potential issues with your module to be reported by other developers.

#### `homepage`

The "homepage" field contains the url to your project's homepage. Including this information in package.json allows for developers to find your project's homepage and all the valuable information it contains.

#### `authors`

The "author" field in a package.json file indicates the person who wrote the package, allowing the publisher to share the author's name, email, and url. The "author" field gives credit to the person for writing the package and shares their contact information for people to contact, or learn more about, the author and their projects.

## Chapter 8: Your license

Adding a license to your open source project is essential for lettings other users know what they can and cannot do with your code, so you should share this information in your README.md file. As there are a wide variety of open source licenses out there, you can use [www.choosealicense.com](www.choosealicense.com) to choose the right fit for your project.

Licenses can be lengthy, so once you have chosen the right one, include it in a LICENSE.txt or LICENSE.md file in the root of your repository. Then, you will want to reference it in your README.md's "License" section in an abbreviated fashion. This way, your are informing users on how they can and cannot use your code AND keeping your README.md file clean and concise.

For example, if you use the MIT License you can abbreviate it in your "License" section as: [MIT](LICENSE.md) © 2018 Richard Littauer. For a second example, check out this README.md file's "License" section!

## Install / Usage

This is a documentation-only repository. There's nothing to install. There's nothing to run. Just read, for now.

## Contribute

This project is very much a work in progress WIP. Feel free to contribute by opening issues, or, even better, pull requests. Any and all help would be appreciated.

## License

[Creative Commons CC-BY-NC-SA 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode) (c) 2018 Burnt Fen Creative LLC
