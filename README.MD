# Strong API constants

HTTP protocol useful constants (headers, status codes, content types, methods)

## Installation

### npm

`npm install @vladbasin/strong-api-constants`

### yarn

`yarn add @vladbasin/strong-api-constants`

## Usage

```typescript
import { HttpContentTypes, HttpHeaders, HttpRequestMethods, HttpStatusCodes } from '.';

console.log(HttpHeaders.AcceptCharset);
console.log(HttpRequestMethods.Post);
console.log(HttpContentTypes.ApplicationJson);
console.log(HttpStatusCodes.Accepted);
```
