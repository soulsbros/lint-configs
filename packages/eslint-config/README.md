# `@soulsbros/eslint-config`

A comprehensive Eslint configuration

## Usage

Create a `.eslintrc` file with the following:

```
{
  "extends": [
    "@soulsbros/eslint-config"
  ],
}
```

Note: there is an [issue](https://github.com/prettier/eslint-plugin-prettier/issues/396)
with `eslint-plugin-prettier` and `eslint-config-prettier` not installing correctly
for some reason, so you'll have to install those as devDependency manually
in the subprojects that extend this config
