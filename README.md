# vue-news-app

> A [beautiful animated news application that is production ready](https://vue-news-app.firebaseapp.com/).  , which was built using one of the most popular JavaScript Framework for building interactive user interfaces Vue.js along with Vuetify, a Vue powered UI library to speed up the Application UI construction.

> You can build this app step-by-step, following the ultimate tutorial at [ButterCMS](https://buttercms.com/blog/build-a-beautiful-animated-news-app-with-vuejs-and-vuetify).  

## Project Overview

![News Application Rachid Sakara](https://i.ibb.co/dc56dbh/Feature-Article.png?raw=true)

![News Application Rachid Sakara](https://i.ibb.co/zNggXk3/Default.png?raw=true)

![News Application Rachid Sakara](https://i.ibb.co/rd2RTDd/News-Application.png?raw=true)

![News Application Rachid Sakara](https://i.ibb.co/yWSP5Rz/Beautiful-News-Application-with-Vue-Js-and-Vuetify.png?raw=true)


## Setup Your Free API Key

> To fetch the news data from the [News API](https://newsapi.org/) backend server, we'll need to generate a new Api Key. To do so, head over to the News API official site and click on the “Get API key” button to register for a new account. 

> Once the registration process is done, you’ll be redirect to dashboard where the API key is already generated for you. 

> Now, to implement your key, open the `/src/App.vue` file. Then, inside the `<script>` tag put you key to where it said: 'Put_Your_API_Key_Here' as shown below:

```
<script>
...
data() {
    return {
      drawer: true, // true to show/hide the side navigation drawer 
      api_key: 'Put_Your_API_Key_Here',
      articles: [],
      errors: [] 
    }
  },
...
</script>
```

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
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
