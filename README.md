# template-front
Archivos de configuración para los desarrollo front de NexuxWorld

## To starter
- Install yarn globally
- ```yarn global add flow-bin```
~~~
    "devDependencies": {
        "eslint": "^6.6.0",
        "eslint-config-airbnb": "^18.2.0",
        "eslint-config-prettier": "^6.15.0",
        "eslint-plugin-import": "^2.22.0",
        "eslint-plugin-jsx-a11y": "^6.4.1",
        "eslint-plugin-prettier": "^3.1.4",
        "eslint-plugin-react": "^7.20.3",
        "eslint-plugin-react-hooks": "^4.0.5",
        "flow-bin": "^0.136.0",
        "husky": "^4.3.0",
        "lint-staged": "^10.5.0",
        "node-sass": "^4.14.1",
        "prettier": "^2.1.2"
    }
~~~

## Important
- project generated with ```npx create-generate-app```
- Redux as store data.
- Sass with ```node-sass``` for styles.
- Eslint as lint for js and jsx files.
- prettier as lint for json, css, scss and md files.
- husky for configuration of hooks with ```lint-staged```
- Lint-staged is a hooks executer according files changed.