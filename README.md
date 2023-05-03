# Modern React Template

如果你不想麻烦自己配置一系列的 linter，actions等，可以试试这个。

![](https://img.shields.io/badge/language-react-rgb(20,158,202).svg)
![](https://img.shields.io/badge/build-passing-brightgreen)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![pnpm](https://img.shields.io/badge/pnpm-enabled-brightgreen.svg)](https://pnpm.js.org/)
## Getting started

```shell
# clone the project
git clone git@github.com:RunningLiLi/modern-react-template.git

# enter the project directory
cd modern-react-template

# install dependency
pnpm install

# develop
pnpm run dev
```

## Git

```shell
#add
git add .

#commit,有友好的提示
pnpm run cz
```

使用 `standard-version `自动更新日志，版本信息等

## Build

```shell
# build for production environment
pnpm run build
```

## Advanced

```shell
# preview the release environment effect
pnpm preview

# code check
pnpm lint

# code auto fix
pnpm format
```

## Dependencies

- React
- React Router
- TypeScript
- Vite
- ESLint
- Prettier
- Commitlint
- husky
- standard-version
- commitizen
- pretty-quick
- lint-staged

## License

MIT

Copyright (c) 2023 runninglili
