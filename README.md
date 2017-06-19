vue-nano-boilerplate
=========

Minimum usable vue boilerplate posible, thanks to [vue-cli build](https://github.com/vuejs/vue-cli/blob/master/docs/build.md). No package.json or npm required, just `vue-cli`

Supports __hot module replacement__, babel __es2015__ + __async/await__ + __object spread__.

You can extend the build process using `config.js` file (see vue-cli build docs)

```
# Install vue-cli if you haven't already
npm install -g vue-cli     

# Create a new project based on this template
vue init edus44/vue-nano-boilerplate my-project 

cd my-project 

# To start developing
make 

# To build /dist folder production-ready
make build 
```
