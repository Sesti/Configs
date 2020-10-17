# CONFIGS

This is my configs repository for new projects or to complete started ones.

## PRETTIER

To install prettier for your project run install script or 
```
npm i -D prettier
```

Copy package.json file or add in your "scripts" :
```
"format": "prettier \"src/**/*.{js,html}\" --write"
```

Install prettier extension for vscode

File -> Preferences -> Settings -> Search format on save and *check*
                                -> Search require config and *check*

## ESLINT

To install eslint for your projects run install script or
```
npm install -D eslint eslint-config-prettier
```

Copy config file from repository or create one from scratch

Copy package.json file or add in your "scripts" :
```
"lint": "eslint \"src/**/*.{js,html}\" --quiet"
```

Install eslint extension for vscode

## PARCEL

To install parcel for your project run install script or
```
npm i -D parcel-bundler
```

Copy package.json filr or add in your "scripts" : 
```
"dev": "parcel src/index.html"
```
