# Game Dev Markdown Templates

This folder contains markdown template for a Game Design Document. The template is broken up into a tree structure with one Markdown file per section similar to a website. This file structure helps clean up the file system, prevents slow Markdown renderers from glitching, and helps you focus on writhing one section at a time. In order to edit these files we recommend you use [Visual Studio Code](https://code.visualstudio.com/). [Atom](https://atom.io/) is okay but the Markdown renderer is notoriously bad as of the writing of this.

## Document Templates

* [Game Design Document Markdown Template](./gdd/readme.md)

## Mission and Vision

The mission of Markdown Game Development is to help you start out or get your project onto the right foot and increase productivity with Don't Repeat Yourself (DRY) documentation. Our vision is to automate as much documentation as possible with [KabukiPress](https://github.com/kabuki-starship/kabukipress).

## MVP RoadMap

***When you're first starting out your project, your roadmap should be here in the root `readme.md` file because people have very low tolerance for non-working code, they will just move on in search of the easy thing and you can't blame them, so if you're trying to woo contributors, you must do it with your Mission and vision, then immediately after show the action plan that someone else things is a good idea achievable, and worth their time to contribute too.***

We can achieve a Minimum Viable Product by completing the following project phases:

1. Foo - In this phase we will say hello world.
1. Bar - In this phase we will say Foo and Bar.

This is a good idea because foo and bar are both common names for abstract functions.

## Organization

 There are different Markdown templates for different tasks:

* Markdown Software Engineering
* [Markdown Game Design](https://github.com/kabuki-starship/markdown.game_dev)
* [Markdown Cookbook](https://github.com/kabuki-starship/markdown.cookbook)

 Each template shares the same GitHub markdown templates using the [docs repo](https://github.com/kabuki-starship/docs).

## Quickstart Guide

**1.** Clone the repo recursively or else you don't get the `/docs` folder.

```BASH
git clone --recursive https://github.com/kabuki-starship/markdown.game_dev.git
```

**2.** Copy the documents you want into your repo, but do not copy the .git folder because it will mess up the GitHub templates.

**3.** We've found [Visual Studio Code](code.visualstudio.com) to the best Markdown editor. Open Visual Studio Code, right click on the Explorer, and click on Add Folder to Workspace, then point it to your project repo's root folder.

**4.** Find and replace all instances of "Markdown Software Engineering" with your projects name, and find and replace all instances of "Your Name <<https://your-github-page.github.io>>" with your name and a pointer to your GitHub page. Please don't put your personal email on the copyright, you want to make them contact you through a website so you can keep your personal information private.

**5.** Delete the lines in the License you don't need.

**6.** To upload the files to the web, just upload them to your GitHub repo.

**7.** If you would like to create a statically generated website from the Markdown files, check out [KabukiPress](https://github.com/kabuki-starship/kabukipress). We are seeking Modern Embedded-C++ code contributors.

## Contributions

If you have any essential game document templates, please fee free to submit them via an Issue ticket. Thanks.

## License

***This template is not copyrighted, this is just an example license.***

Copyright 2019 (C) Your Name <<your.email@address.com>>, the IP Owner; all rights reserved (R).

This file and the folder and repository it is contained in are private and contain intellectual property, trade secrets, copyrighted material, and other protected works, the IP, that are the property of the IP Owner. You must get explicit permission from the IP Owner to possess, view, modify, share, duplicate, discuss, or publicly display the IP.
