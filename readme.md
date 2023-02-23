# 1 Create project

In a shell,

```sh
npm create vite@latest
```

# 2 Dependencies

### Production

* compression ;
* cross-env : inject env variables in npm commands ;
* express : the js server ;
* react : core library ;
* react-dom : allows to build web ui ;
* react-router-dom : builds a website with routes.

Again in a shell,

```sh
npm i compression cross-env express react-router-dom
```

### Development

* @vitejs/plugin-react ;
* nodemon : reloads the server code on updates ;
* vite : the bundler.

```sh
npm i -D nodemon
```

# 3 Launch

### Development

To launch the app in development mode,

```sh
npm run dev
```

### Production

For launching the app in production mode it first needs to be built,

```sh
npm run build
```

a new directory "dist" will be created, then 

```sh
npm run start
```

# 4 Documentation

[react-router-dom](https://reactrouter.com/en/main/start/examples)
[vite](https://github.com/vitejs/vite-plugin-react/tree/main/playground/ssr-react)