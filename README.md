# @hoangcung1804npm/in-modi-architecto

[![GitHub license](https://img.shields.io/github/license/eugenehp/@hoangcung1804npm/in-modi-architecto.svg?color=blue&style=for-the-badge)](./LICENSE)
[![npm](https://img.shields.io/npm/v/@hoangcung1804npm/in-modi-architecto.svg?color=green&style=for-the-badge)](https://www.npmjs.com/package/@hoangcung1804npm/in-modi-architecto)
[![npm downloads](https://img.shields.io/npm/dw/@hoangcung1804npm/in-modi-architecto.svg?label=npm%20downloads&style=for-the-badge)](https://npmcharts.com/compare/@hoangcung1804npm/in-modi-architecto?minimal=true)
[![total npm downloads](https://img.shields.io/npm/dt/@hoangcung1804npm/in-modi-architecto.svg?label=total%20npm%20downloads&style=for-the-badge)](https://npmcharts.com/compare/@hoangcung1804npm/in-modi-architecto?minimal=true)
[![GitHub watchers](https://img.shields.io/github/watchers/eugenehp/@hoangcung1804npm/in-modi-architecto.svg?style=for-the-badge)](https://github.com/hoangcung1804npm/in-modi-architecto/watchers)
[![GitHub stars](https://img.shields.io/github/stars/eugenehp/@hoangcung1804npm/in-modi-architecto.svg?label=GitHub%20stars&style=for-the-badge)](https://github.com/hoangcung1804npm/in-modi-architecto/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/eugenehp/@hoangcung1804npm/in-modi-architecto.svg?style=for-the-badge)](https://github.com/hoangcung1804npm/in-modi-architecto/network/members)
[![open bugs](https://img.shields.io/github/issues-raw/eugenehp/@hoangcung1804npm/in-modi-architecto/bug.svg?color=d73a4a&label=open%20bugs&style=for-the-badge)](https://github.com/hoangcung1804npm/in-modi-architecto/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Abug)
[![total open issues](https://img.shields.io/github/issues-raw/eugenehp/@hoangcung1804npm/in-modi-architecto.svg?label=total%20open%20issues&style=for-the-badge)](https://github.com/hoangcung1804npm/in-modi-architecto/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/eugenehp/@hoangcung1804npm/in-modi-architecto.svg?style=for-the-badge)](https://github.com/hoangcung1804npm/in-modi-architecto/pulls)

[![Packagephobia](https://badgen.net/packagephobia/install/@hoangcung1804npm/in-modi-architecto)](https://packagephobia.com/result?p=@hoangcung1804npm/in-modi-architecto)
[![Bundlephobia](https://badgen.net/bundlephobia/min/@hoangcung1804npm/in-modi-architecto)](https://bundlephobia.com/result?p=@hoangcung1804npm/in-modi-architecto@2.0.0)

`@hoangcung1804npm/in-modi-architecto` is a zero-dependency TypeScript implementation of [RFC4122](https://tools.ietf.org/html/rfc4122) standard **A Universally Unique IDentifier (UUID) URN Namespace**. Please note, this library uses pseudo random generator based on top of `Math.random`. New version with hardware support is WIP.

**Heavily inspired by:**

- [uuid](https://github.com/uuidjs/uuid)
- [pure-uuid](https://github.com/rse/pure-uuid)
- [nanoid](https://www.npmjs.com/package/nanoid)

Huge thanks to [Randy Coulman](https://github.com/randycoulman) for the early version of a code.

## Getting started

Use this steps to install and create UUIDs. Example project is available [here](https://github.com/eugenehp/RNUUID)

### 1. Install

```shell
npm install @hoangcung1804npm/in-modi-architecto
```

### 2. Create a UUID

```javascript
import uuid from '@hoangcung1804npm/in-modi-architecto';
uuid.v4(); // ⇨ '11edc52b-2918-4d71-9058-f7285e29d894'
```

## Documentation

Methods documentation is available [here](./docs/modules.md)

## Troubleshooting

Previous version has been based on `randombytes` that is not compatible with react-native out of the box.
Please submit an [issue](https://github.com/hoangcung1804npm/in-modi-architecto/issues) if you found a bug.

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## Sponsorship

Thank you to our sponsors:

[<img width="300px" src="https://user-images.githubusercontent.com/1857263/114124204-c4e1eb80-98a8-11eb-80ab-64683c24bbc5.png" alt="Reactive Lions™" target="_blank">](https://www.reactivelions.com)

## License

[MIT](./LICENSE)

Copyright (c) 2016-2024 Eugene Hauptmann
