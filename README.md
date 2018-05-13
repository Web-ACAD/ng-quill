[![NPM version](https://img.shields.io/npm/v/@webacad/ng-quill.svg?style=flat-square)](https://www.npmjs.com/package/@webacad/ng-quill)
[![Build Status](https://img.shields.io/travis/Web-ACAD/ng-quill.svg?style=flat-square)](https://travis-ci.org/Web-ACAD/ng-quill)

# WebACAD/Quill

[Quill](https://quilljs.com/) editor integration for angular forms.

## Installation

```bash
$ npm install --save @angular/common@^5.0
$ npm install --save @angular/core@^5.0
$ npm install --save @angular/forms@^5.0
$ npm install --save quill
$ npm install --save rxjs
$ npm install --save @webacad/ng-quill
```

or with yarn

```bash
$ yarn add @angular/common@^5.0
$ yarn add @angular/core@^5.0
$ yarn add @angular/forms@^5.0
$ yarn add quill
$ yarn add rxjs
$ yarn add @webacad/ng-quill
```

## Register module

**app.module.ts:**

```typescript
import {QuillModule} from '@webacad/ng-quill';

@NgModule({
    imports: [
        QuillModule,
    ],
})
export class AppModule {}
```

## Usage

```html
<wa-quill theme="snow"></wa-quill>
```

**Available options:**

* `theme`: quill `theme` options, [docs](https://quilljs.com/docs/themes/)

## Using in angular forms

This package implements all the necessary code for angular forms. That means that you can use it just like any other 
ordinary form control.
