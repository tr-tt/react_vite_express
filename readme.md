# 0 Overview

This small projects shows how to integrate react v18 with express using react-router-dom v6.

# 1 Create project

In a shell,

```sh
npm create vite@latest
```

# 2 Dependencies

### Production

* compression ;
* express : the js server ;
* react : core library ;
* react-dom : allows to build web ui ;
* react-router-dom : builds a website with routes ;
* sirv : replaces express-static.

### Development

* @vitejs/plugin-react ;
* cross-env : inject env variables in npm commands ;
* nodemon : reloads the server code on updates ;
* vite : the bundler.

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