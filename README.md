# Country flag mapper

This package provides country flags as SVG icons, in a square (1x1) aspect ratio, mapped to country and locale IDs.

The flags are sourced from the [flag-icons](https://github.com/lipis/flag-icons) library.

### Installation

```bash
npm install --save @cloudblueconnect/country-flag-mapper
```

### Usage

```js
import {
  flags,
  locales,
  localeFlags,
} from '@cloudblueconnect/country-flag-mapper';

// Getting Portugal's flag
const PORTUGAL_FLAG = flags.PT;

// Getting the icon for the spanish locale
const SPANISH_LANGUAGE_ICON = localeFlags.es;

// Getting the icon for a different spanish locale
const ARGENTINIAN_SPANISH_ICON = localeFlags[locales.ARGENTINIAN_SPANISH];
```

## License

`@cloudblueconnect/country-flag-mapper` is licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).