# Candle SDK Monorepo

## Prerequisites

- Yarn v3 (If unfamilair consult https://yarnpkg.com/getting-started/install to get started and familiarise yourself)
- Node v14 and above

## Versioning (Canary)

yarn lerna version --no-changelog --no-git-tag-version --preid canary --yes

## Publishing (Canary)

yarn run lerna publish from-package --dist-tag canary --no-git-reset --no-verify-access --preid canary --yes

## Core SDK

### Testing

```sh 
yarn workspace @candlelabs/core-sdk test
```

### Build

```sh 
yarn workspace @candlelabs/core-sdk build
```

## Limit Order SDK

### Testing

```sh 
yarn workspace @candlelabs/limit-order-sdk test
```

### Build

```sh 
yarn workspace @candlelabs/limit-order-sdk build
```

## Trident SDK

### Testing

```sh 
yarn workspace @candlelabs/trident-sdk test
```

### Build

```sh 
yarn workspace @candlelabs/trident-sdk build
```

## Tines SDK

### Testing

```sh 
yarn workspace @candlelabs/tines test
```

### Build

```sh 
yarn workspace @candlelabs/tines build
```