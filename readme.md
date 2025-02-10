# `@miorso/tsconfig`

This package contains a shared reusable TypeScript configuration.

> ⚠️ **Requires TypeScript 5.1 or later**

## Install

```sh
npm install --save-dev @miorso/tsconfig
```

## Usage

Create a `tsconfig.json` file in your project and extend the appropriate configuration:

### For an Application

```json
{
  "extends": "@miorso/tsconfig/app"
}
```

### For a Library Module

```json
{
  "extends": "@miorso/tsconfig/library"
}
```

### For a Base Configuration

```json
{
  "extends": "@miorso/tsconfig/base"
}
```

