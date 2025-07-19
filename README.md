# JS Length Unit Converter

A simple JavaScript tool to convert between kilometers (km), miles, and feet (ft).

## Features

- Supports conversion between:
  - km ↔ miles
  - km ↔ ft
  - miles ↔ ft
- Detects and reports invalid units
- Clean, readable, and beginner-friendly JavaScript code

## Example Usage

```js
convertLength(5, 'km', 'miles'); // "3.125 miles"
convertLength(5280, 'ft', 'miles'); // "1 miles"
convertLength(5, 'kg', 'ft'); // "Invalid unit kg"
