<!--

  DO NOT EDIT.

  This markdown file was autogenerated using a mixture of the following files as the source of truth for its data:
  - ../../src/rules/no-call-expression.ts
  - ../../tests/rules/no-call-expression/cases.ts

  In order to update this file, it is therefore those files which need to be updated, as well as potentially the generator script:
  - ../../../../tools/scripts/generate-rule-docs.ts

-->

<br>

# `@angular-eslint/template/no-call-expression`

Disallows calling expressions in templates, except for output handlers

- Type: suggestion

<br>

## Rule Options

The rule accepts an options object with the following properties:

```ts
interface Options {
  /**
   * Default: `[]`
   */
  allowList?: string[];
  /**
   * Default: `undefined`
   */
  allowPrefix?: string;
  /**
   * Default: `undefined`
   */
  allowSuffix?: string;
}

```

<br>

## Usage Examples

> The following examples are generated automatically from the actual unit tests within the plugin, so you can be assured that their behavior is accurate based on the current commit.

<br>

<details>
<summary>❌ - Toggle examples of <strong>incorrect</strong> code for this rule</summary>

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<div>{{ getInfo() }}</div>
        ~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<a href="{{ getUrls().user }}"></a>
            ~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<p [test]="test?.getInfo()"></p>
           ~~~~~~~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<a [href]="id && createUrl() && test($any)">info</a>
                 ~~~~~~~~~~~    ~~~~~~~~~~
{{ id || obj?.nested1() }}
         ~~~~~~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<a [href]="id ? a?.createUrl() : editUrl(3)">info</a>
                ~~~~~~~~~~~~~~   ~~~~~~~~~~
{{ 1 === 2 ? 3 : obj?.nested1() }}
                 ~~~~~~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
{{ obj?.nested1() }} {{ obj!.nested1() }}
   ~~~~~~~~~~~~~~       ~~~~~~~~~~~~~~
<button [type]="obj!.$any(b)!.getType()">info</button>
                ~~~~~~~~~~~~~~~~~~~~~~~
<a [href]="obj.propertyA?.href()">info</a>
           ~~~~~~~~~~~~~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
@if (foo()) {
     ~~~~~
  <div [id]="foo()"></div>
             ~~~~~
} @else if (foo()) {
            ~~~~~
  <div [id]="foo()"></div>
             ~~~~~
} @else {
  <div [id]="foo()"></div>
             ~~~~~
}
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
@switch (foo()) {
         ~~~~~
  @case(foo()) {
        ~~~~~
    <div [id]="foo()"></div>
               ~~~~~
  }
  @default {
    <div [id]="foo()"></div>
               ~~~~~
  }
}
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
@for (item of getFooList(); track item.getId()) {
              ~~~~~~~~~~~~        ~~~~~~~~~~~~
  <div [id]="foo()"></div>
             ~~~~~
} @empty {
  <div [id]="foo()"></div>
             ~~~~~
}
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
@defer (when foo(); prefetch when foo()) {
             ~~~~~                ~~~~~
  <div [id]="foo()"></div>
             ~~~~~
} @error {
  <div [id]="foo()"></div>
             ~~~~~
} @loading {
  <div [id]="foo()"></div>
             ~~~~~
} @placeholder {
  <div [id]="foo()"></div>
             ~~~~~
}
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
{{ foo(bar(), baz()) }}
   ~~~~~~~~~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
{{ foo()() }}
   ~~~~~~~
   ~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
{{ foo().bar() }}
   ~~~~~~~~~~~
   ~~~~~
```

<br>

---

<br>

#### Custom Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error",
      {
        "allowList": [
          "ok"
        ]
      }
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
{{ notOk().ok() }}
   ~~~~~~~
```

</details>

<br>

---

<br>

<details>
<summary>✅ - Toggle examples of <strong>correct</strong> code for this rule</summary>

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
{{ info }}
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button type="button" (click)="handleClick()">Click Here</button>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
{{ $any(info) }}
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<input (change)="obj?.changeHandler()">
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<form [formGroup]="form" (ngSubmit)="form.valid || save()"></form>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<form [formGroup]="form" (ngSubmit)="form.valid && save()"></form>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<form [formGroup]="form" (ngSubmit)="id ? save() : edit()"></form>
```

<br>

---

<br>

#### Custom Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error",
      {
        "allowList": [
          "nested",
          "getHref"
        ],
        "allowPrefix": "$",
        "allowSuffix": "$"
      }
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
{{ obj?.nested() }} {{ obj!.nested() }}
<a [href]="getHref()">info</a>
{{ $validWithPrefix() }} {{ validWithSuffix$() }}
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
@if (condition) {
  <div></div>
} @else if (otherCondition) {
  <div></div>
} @else {
  <div></div>
}
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
@switch (condition) {
  @case(value) {
    <div></div>
  }
  @default {
    <div></div>
  }
}
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
@for (item of list; track item.id) {
  <div></div>
} @empty {
  <div></div>
}
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-call-expression": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
@defer (on viewport(ref); prefetch on viewport(ref)) {
  <div></div>
} @error {
  <div></div>
} @loading {
  <div></div>
} @placeholder {
  <div></div>
}
```

</details>

<br>
