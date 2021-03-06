# 20xr - ESLint Shareable Config

#### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for 20xr

## Install

```bash
npm install eslint-config-20xr
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the 20xr shareable config, first run this:

```bash
npm install eslint-config-20xr
```

Then, add this to your .eslintrc file:

```
{
  "extends": "20xr"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.
