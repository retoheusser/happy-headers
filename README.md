# happy-headers

Installation

```bash
yarn add happy-headers
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