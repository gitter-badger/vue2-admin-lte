<p align = "center">
<img src="https://github.com/devjin0617/vue2-admin-lte/blob/master/vue2-admin-lte-logo.png?raw=true">
<br>
<img src="https://img.shields.io/badge/AdminLTE-2.3.11-blue.svg"> <img src="https://img.shields.io/badge/jquery-3.1.1-lightgrey.svg"> <img src="https://img.shields.io/badge/bootstrap-3.3.7-blue.svg"> <img src="https://img.shields.io/badge/vue-2.2.1-brightgreen.svg"> <img src="https://img.shields.io/badge/vuex-2.2.1-brightgreen.svg"> <img src="https://img.shields.io/badge/vue--router-2.3.0-green.svg">
</p>

# vue2-admin-lte

> AdminLTE of Admin control panel template Based on Vuejs 2.x Front-end Framework.

![](https://github.com/devjin0617/vue2-admin-lte/blob/master/capture.png?raw=true)

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests: comping soon
# npm run unit

# run e2e tests: comping soon
# npm run e2e

# run all tests: comping soon
# npm test
```

## Example

```vue
<template>

  <DirectChat
    :talkList="talkList"
    :badgeCount="3"
    theme="primary"
    title="Direct Chat"
    placeholder="Type Messages ..."
  ></DirectChat>
  
</template>


<script>

export default {
  name: 'App',
  data () {
    return {
      talkList: [
        {
          name: 'Alexander Pierce',
          date: new Date(),
          profileImage: 'http://path/to/image',
          message: `Is this template really for free? That's unbelievable`,
          isMine: false
        },
        {
          name: 'Sarah Bullock',
          date: new Date(),
          profileImage: 'http://path/to/image',
          message: `You better believe it!`,
          isMine: true
        }
    }
  }
}

</script>
```

## Contributing to Vue2 AdminLTE

The following is a set of guidelines for contributing to `Vue2 AdminLTE`.

### Submitting Issues

You can create an issue [here](https://github.com/devjin0617/vue2-admin-lte/issues).

If you can, please include:
- The version, name of Browser you are using
- The operating system you are using

Other things that will help resolve your issue:
- Screenshots or gif
- dev tools or an alert
- Perform a search to see if a similar issue has already been submitted


### Submitting Pull Requests

- Include screenshots and animated gif in your pull request whenever possible.
- Use short, present tense commit messages.
