# brsp-chat-lib

[![NPM version][npm-image]][npm-url]
[![Build][github-build]][github-build-url]
![npm-typescript]
[![License][github-license]][github-license-url]

## Installation:

```bash
npm install brsp-chat-lib --save-dev
```

or

```bash
yarn add -D brsp-chat-lib
```

## Usage :

Add `MyCounter` to your component:

```js
import React from 'react'
import ReactDOM from 'react-dom/client'
import { MyCounter } from 'brsp-chat-lib'

const root = ReactDOM.createRoot(document.getElementById('root') as HTMLElement)
root.render(
    <React.StrictMode>
        <div>
            <h2>Default counter</h2>
            <MyCounter />
        </div>
        <hr />
        <div>
            <h2>Counter with predefined value</h2>
            <MyCounter value={5} />
        </div>
    </React.StrictMode>,
)

```

[npm-url]: https://www.npmjs.com/package/brsp-chat-lib
[npm-image]: https://img.shields.io/npm/v/brsp-chat-lib
[github-license]: https://img.shields.io/github/license/gapon2401/brsp-chat-lib
[github-license-url]: https://github.com/gapon2401/brsp-chat-lib/blob/master/LICENSE
[github-build]: https://github.com/gapon2401/brsp-chat-lib/actions/workflows/publish.yml/badge.svg
[github-build-url]: https://github.com/gapon2401/brsp-chat-lib/actions/workflows/publish.yml
[npm-typescript]: https://img.shields.io/npm/types/brsp-chat-lib
