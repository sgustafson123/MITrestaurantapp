# API Strapi Delivroo clone


### Install dependencies
```bash
$ npm
```

### Run the server
```bash
$ npm dev
```

### build for production and launch server
```bash
$ npm build
$ npm start
```

### Permissions configuration

For the **Public** role:
- Application
  - Resaurant
    - find
    - findone
  - Dish
    - find

For the **Authenticated** role:
- Application
  - Resaurant
    - find
    - findone
  - Dish
    - find
  - Order
    - create

---

For detailed explanation on how things work, checkout the [Strapi docs](https://github.com/nuxt/strapi).