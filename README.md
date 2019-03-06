# share-compare
Helping you select sharing component tool chain - Bit, Lerna, Yarn workspaces, storybook

# Intro
The purpose of this repository is to help you select the best tool chain to share your component library inside your organization or publicly.
The project contain 2 parts: 
* Hands on part - this part will guide you step by step from cloning the project to the final result of each tool. This way you will not only *read* about it, but *feel* it.
* Theoretical part - This part will review some of the advantages and disadvantages of each tool to help you summery the findings in a more organize way. It will also cover some features that are not part of the hands on part (it's just too much to include all features).

*Disclaimer:*
Some of this tools requires a massive refactor to apply on your own library. In this project we pre structured it in a way to best fit for each tool to save you this time and keep the instructions short as possible. We will talk about the refactor in the theoretical part.

# Project structure
This project composed from 2 packages:
* react - a package that contain few different ui components (such as buttons)
* utils - a package that contain few different utils components such as array manipulation, date utils etc'.

The components are taken (copied) from OS projects such as react-foundation, date-fns, lodash, ramda.

# Comparing factors
In order to make the compare more organized we will focus on some common challenges, every one come to share a component library are faced.

## Isolate components
This factor is about how easier it to go from a state you have a bunch of files in your file system that represents different components to a unit which can be shared with others.
This contain different aspects such as dependency managements, version management, build process, test process.

## Modify components
This about how easier it to change an existing component when a bug found or new feature required. Who can make that change, what pre-requisites he needs for this change, and how to sync that change to others once completed.

## Discover components
This is about your ability to find your components, experience them, and choose them.

### Find components
How you find an existing component in by context.
For example how do you find buttons which written in React.

### Experience components
See and play with live component

### Choose components
Ability to choose your component by different features such as: Tests coverage, docs, performance, downloads, last update, author etc'

## Dependency management
How easy is to manage dependencies between different components. What happen when you update a component with dependent. How do you declare the dependencies graph.

## Version management
How easy and flexible is to version a component. A group of components. What happens to versions when there are dependencies.

# Hands on

## The Bit way

## Lerna way
Locked / Independent mode

## Yarn workspaces way

## Storybook