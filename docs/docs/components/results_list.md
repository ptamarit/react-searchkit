<!--
  This file is part of React-SearchKit.
  Copyright (C) 2018 CERN.

  React-SearchKit is free software; you can redistribute it and/or modify it
  under the terms of the MIT License; see LICENSE file for more details.
-->

---
id: results-list
title: ResultsList
---

`ResultsList` renders the list of results as a list.

## Usage

```jsx
<ResultsList />
```

## Usage when overriding template

Props below are available in your renderElement function when you override the template.

### Props

| Name              | Default       | Type      | Description             |
| ------------------|---------------| ----------|-------------|
| ``renderElement`` |               | {func}    | Function to override the the component's template |
| ``items``         | []            | {array}   | Array of items to be presented |
| ``item``          |  -            | {object}   | One item of the `items` array |
| ``index``         |  -            | {number}   | Index of the item in the `items` array |