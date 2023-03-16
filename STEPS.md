# Steps

## Creating first nest.js app

Since some code is generated you should have nest CLI installed.

```
cd apps
nest new api-1
```

Note: choose yarn as packet manager

Remove generated .git and .gitignore

Change generated tsconfig to:

```
{
  "extends": "tsconfig/nestjs.json",
  "compilerOptions": {
    "outDir": "./dist",
    "baseUrl": "./"
  }
}
```

Add `"../../node_modules",` to tsconfig.build.json
