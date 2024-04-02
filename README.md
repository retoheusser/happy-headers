# happy-headers

Installation

```bash
npm install happy-headers
yarn add happy-headers
pnpm install happy-headers
bun add happy-headers
```

Usage

```ts
import getHeaders from 'happy-headers'

fetch('/friends-v1', {
  ...
  headers: {
    Authorization: 'Bearer xyz...',
    ...getHeaders()
  },
  ...
})
```