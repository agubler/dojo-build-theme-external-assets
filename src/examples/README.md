# failing-theme widget library

- [Usage](#usage)

## Usage

To use the `failing-theme` package in your project, you will need to install the package:

```bash
npm install failing-theme
```

This package contains *all* of the widgets in this repo.

To use a widget in your application, you will need to import each widget individually:

```ts
import Button from 'failing-theme/button';
```

Each widget module has a default export of the widget itself, as well as named exports for things such as properties specific to the widget:

```ts
import Button, { ButtonProperties } from 'failing-theme/button';
```