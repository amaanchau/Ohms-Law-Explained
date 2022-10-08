To get started:

1. Clone the repository:

   ```bash
   git clone https://github.com/justalever/tailwind-airbnb tailwind-airbnb

   cd tailwind-airbnb
   ```

2. Install the dependencies:

   ```bash
   # Using npm
   npm install

   ```

3. Start the development server:

   ```bash
   # Using npm
   npm run serve


   Now you should be able to see the project running at localhost:8080.
   ```

## Building for production

Even though this isn't necessarily a starter kit for a proper project, we've included an example of setting up both [Purgecss](https://www.purgecss.com/) and [cssnano](https://cssnano.co/) to optimize your CSS for production.

To build an optimized version of your CSS, simply run:

```bash
# Using npm
npm run production

# Using Yarn
yarn run production
```

After that's done, check out `./public/build/tailwind.css` to see the optimized output.
