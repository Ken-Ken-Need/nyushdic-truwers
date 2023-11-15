# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Truwers - A new way to track your diet

Our app is a brand new diet tracking app that allow users to input natural language descriptions of their meal, and generate a visualized statistics of nutrition intakes such as Calories and Protein. Aiming at helping those who are building up their habit to keep track of their diet, our app seek to make the interaction with it as natural and smooth as possible.

Powered by ``GPT-3.5-Turbo``, we allow users to describe their meal in anyway they like instead of going through the lengthy process of searching and determining the amount of conventional diet tracking apps.

For instance, you can interact with our app in the following way:

* I ate an apple and a cup of milk for breakfast today. And I had a can of coca cola.
* You will see the visualized version of the following data:
* ```
  {food} {amount} {calories} {protein}
  apple:1,95,0
  milk:240,120,8
  coca cola:1,140,0
  ```

  The more specified the food and the amount are, the more accurate the result will be.

## Getting Started

First, make sure you set your valid GPT-API key in the ``envs``file.

Second, install all the dependenceis with ``npm``, and run the development server:

```bash
# Navigate to the correct directory
cd <the folder of this project>

# Install the dependencies
npm install

# Run the code
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

The app would report error if the food you input is not valid.
