# Bring typing to your react project


Install dev dependencies:

```
yarn add -D @testing-library/jest-dom @testing-library/react @testing-library/user-event @types/jest @types/node @types/react @types/react-dom @types/react-router @types/react-router-dom @types/http-status-codes @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier lint-staged prettier tslint tslint-config-prettier tslint-consistent-codestyle 
```

Add the following parts to package.json:

```
  "eslintConfig": {
    "extends": [
      "react-app",
      "react-app/jest"
    ]
  },
    "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  },
  "engines": {
    "node": "14.15.4"
  },
  "rootDir": ".",
  "roots": [
    "<rootDir>"
  ],
  "moduleNameMapper": {
    "@vendor": "<rootDir>/vendor",
    "@vendor/(.*)": "<rootDir>/vendor/$1"
  }

```
