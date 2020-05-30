# AWS with Vue.js Tutorial

AWS Solution Architect Documentation Using Vue.js

## Getting Started

### Prerequisites

Vue.js project environment is created by @vue/cli

```
npm install -g @vue/cli
vue create example-vue-project
```
Tip: example-vue-project is the name of the project. You can obviously choose any valid name for your project.
And repeat

```
cd example-vue-project
npm run serve
```
Tip: The command will allow you to run a local development server from the [localhost:8000](http://localhost:8080) address.

### Hello World

Remove the contents in App.vue and HelloWorld.vue (inside components).

Add these code in App.vue
```
<template>
    <h1> Hello World</h1>
</template>
```
### Dynamic Hello World

Change the contents in App.vue like this.

```
<template>
    <h1>{{message}}</h1>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      message: "Hello World"
    };
  }
};
</script>

<style>
</style>

```
**/<template/>** contain html codes, **/<script/>** contains javascript codes and **/<style/>** css codes.

    
