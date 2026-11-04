# Commands

## flags

-d is shorthand for --development
-e is shorthand for --environment

### install CLI

```
yarn add --dev @shopify/cli
npx shopify version
```

### pull the store files from server

```
npx shopify theme pull -e development
```

### Run locally

```
npx shopify theme dev -e development
http://127.0.0.1:9292/
```

### send changes to prod

```
npx shopify theme push -e development
```

### pull theme from developer -d

```
npx shopify theme pull -d
```
