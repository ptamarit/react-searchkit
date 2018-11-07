<!--
  This file is part of React-SearchKit.
  Copyright (C) 2018 CERN.

  React-SearchKit is free software; you can redistribute it and/or modify it
  under the terms of the MIT License; see LICENSE file for more details.
-->

---
id: results-per-page
title: ResultsPerPage
---

`ResultsPerPages` renders a list of the possible number of results per page.

## Usage

### Props

| Name                          | Required  | Default       | Type      | Description             |
| ------------------------------|-----------|---------------| ----------|-------------------------|
| ``values``                    | yes       |               | {array}  | Array of options to show(Each option should be an object with keys `text`, `value`|
| ``defaultValue``              | yes       |               | {string}  | Default dropdown value |

```jsx
<ResultsPerPage
  values={this.resultsPerPageValues}
  defaultValue={10}
/>
```

## Usage when overriding template

Props below are available in your renderElement function when you override the template.

### Props

| Name              | Default       | Type      | Description             |
| ------------------|---------------| ----------|-------------------------|
| ``renderElement`` | null          | {func}    | Function to override the the component's template |
| ``currentSize``   | -             | {number}  | Selected dropdown size value |
| ``values``        | -             | {string}  | Array of options to show(Each option should be an object with keys `text`, `value` |
| ``onValueChange`` | -             | {func}  | Function to call when dropdown value is changed |