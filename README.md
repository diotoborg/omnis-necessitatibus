# @diotoborg/omnis-necessitatibus

🤙 International phone input component for React

![npm-version](https://img.shields.io/npm/v/@diotoborg/omnis-necessitatibus)
![build-status-badge](https://img.shields.io/github/actions/workflow/status/goveo/@diotoborg/omnis-necessitatibus/release.yml?branch=master)
![install-size-badge](https://badgen.net/packagephobia/install/@diotoborg/omnis-necessitatibus)
[![codecov](https://codecov.io/gh/goveo/@diotoborg/omnis-necessitatibus/branch/master/graph/badge.svg?token=SHEF4U216O)](https://codecov.io/gh/goveo/@diotoborg/omnis-necessitatibus)
![downloads](https://img.shields.io/npm/dt/@diotoborg/omnis-necessitatibus)
![Semantic Release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)
[![stars](https://img.shields.io/github/stars/goveo/@diotoborg/omnis-necessitatibus?style=social)](https://github.com/diotoborg/omnis-necessitatibus)

[Live demo: Storybook](https://@diotoborg/omnis-necessitatibus-storybook.vercel.app)

![demo-gif](https://user-images.githubusercontent.com/25800848/215350455-0d362e64-d621-4856-a384-ab18d4a0d5fa.gif)

## Features

- 😎 **Easy to integrate** - Just import and use, no need for the initial setup. Integrate with any UI library using a headless hook.
- 🔍 **Country guessing** - Just start typing and the component will guess the country and format the phone. Country flags are rendered using [Twemoji](https://twemoji.twitter.com/).
- ✨ **Lightweight** - Low bundle size, no third-party dependencies.
- 🌈 **Easy to customize** - Customize styles and component behavior using props.
- ⌨ **Caret position handling** - Typing in the middle of the input, selection and deletion feels naturally.
- ✔️ **Validation** - Easily validate entered phone numbers using provided functions.

## Installation

```sh
$ npm i @diotoborg/omnis-necessitatibus
```

## Basic usage

```tsx
import { useState } from 'react';
import { PhoneInput } from '@diotoborg/omnis-necessitatibus';
import '@diotoborg/omnis-necessitatibus/style.css';

const App = () => {
  const [phone, setPhone] = useState('');

  return (
    <div>
      <PhoneInput
        defaultCountry="ua"
        value={phone}
        onChange={(phone) => setPhone(phone)}
      />
    </div>
  );
};
```

## Documentation

Find the full API reference on [official documentation](https://@diotoborg/omnis-necessitatibus-docs.vercel.app/).

## Migration

You can encounter some breaking changes after update between major versions.

Checkout migration documents that contain a list of breaking changes and ways to migrate:
<br/>
[Update from v3 to v4](https://@diotoborg/omnis-necessitatibus-docs.vercel.app/docs/Migrations/migrate-to-v4)
<br/>
[Update from v2 to v3](https://@diotoborg/omnis-necessitatibus-docs.vercel.app/docs/Migrations/migrate-to-v3)
<br/>
[Update from v1 to v2](https://@diotoborg/omnis-necessitatibus-docs.vercel.app/docs/Migrations/migrate-to-v2)
