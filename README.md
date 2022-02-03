<h1 align="center">Welcome to get-a-room 🏨</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.1.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://twitter.com/ooanishoo" target="_blank">
    <img alt="Twitter: ooanishoo" src="https://img.shields.io/twitter/follow/ooanishoo.svg?style=social" />
  </a>
</p>

> A simple frontend UI to book rooms built using garden component, react, typescript with TDD

# Functional Requirements
- Up to eight rooms can be added
- Each room has at least one adult and up to a maximum of five
- Each room has zero or more children up to a maximum of three
- Each child needs to have their age supplied, so we know what kind of bed or cot to provide and what to charge for the room
- Each room has a maximum occupancy of five. This is, adults plus children per room
- The Guest and Room selector should always yield a valid room occupancy, use button disablement to avoid invalid configurations
- A user can either click Search to commit the output to the URL or click the x on top to reset the chosen room selection and revert the UI back to the original state.

## Input rules
The component should be able to pass a string as the default data. These are the rules:

- Rooms are separated by pipe |
- Adults and children are separated by a colon :
- Children ages are separated by a comma ,

### Examples:

- "1:4,6|3" → Two rooms, one with one adult and two children ages four and six and the other with three adults and no children
- "3" → One room with three adults and no children
- "2:4" → One room with two adults and one child aged four
- "1:0,13,16" → One room with one adult and three children (aged zero, thirteen, and sixteen)

<br />


# Getting started
## Install

```sh
yarn install
```

## Usage

```sh
yarn run start
```

## Run tests

```sh
yarn test
```

## Author

👤 **Anish**

* Website: https://anish-tech.carrd.co/
* Twitter: [@ooanishoo](https://twitter.com/ooanishoo)
* Github: [@ooanishoo](https://github.com/ooanishoo)
* LinkedIn: [@ooanishoo](https://linkedin.com/in/ooanishoo)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_