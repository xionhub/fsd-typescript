# @xionhub/fsd-typescript

@xionhub/fsd-typescript is a shared tsconfig.json configuration library built with the assumption of being used with [@xionhub/fsd-prettier](https://github.com/xionhub/fsd-prettier).

This library surprisingly relies on TypeScript and is recommended for use with [@xionhub/fsd-prettier](https://github.com/xionhub/fsd-prettier).

For more information, please refer to the [@xionhub/fsd-prettier](https://github.com/xionhub/fsd-prettier) document.

## Overview

@xionhub/fsd-typescript helps set up path allias to quickly and easily comply with feature sliced ​​design and leads to close integration with @xionhub/fsd-prettier.

## Installation

To install the @xionhub/fsd-typescript in your project, use the following command:

```
npm install -D @xionhub/fsd-typescript
```

```
pnpm install -D @xionhub/fsd-typescript
```

```
yarn add -D @xionhub/fsd-typescript
```

## Usage

Add the following settings to the path section of tsconfig.json:

```json
  "extends": ["@xionhub/fsd-typescript"],
  "compilerOptions": {
    "baseUrl": ".",
  },
```

baseUrl and extends are very important.

BaseUrl should be based on where your src folder is located (usually ".")

## Maintainers

[@XionWCFM](https://github.com/XionWCFM)

## License

MIT
