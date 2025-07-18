<!--

  DO NOT EDIT.

  This markdown file was autogenerated using a mixture of the following files as the source of truth for its data:
  - ../../src/rules/no-interpolation-in-attributes.ts
  - ../../tests/rules/no-interpolation-in-attributes/cases.ts

  In order to update this file, it is therefore those files which need to be updated, as well as potentially the generator script:
  - ../../../../tools/scripts/generate-rule-docs.ts

-->

<br>

# `@angular-eslint/template/no-interpolation-in-attributes`

Ensures that property-binding is used instead of interpolation in attributes.

- Type: suggestion
- 🔧 Supports autofix (`--fix`)

<br>

## Rule Options

The rule accepts an options object with the following properties:

````ts
interface Options {
  /**
   * When `true`, only attribute values that are entirely interpolations will fail, whereas values with interpolations that form part of larger strings will be allowed.
   *
   * For example, when set to `true` the following code will not fail for the `alt` attribute but will still fail for the `src` attribute:
   *
   * ```html
   * <img alt="Poke user {{ username }}" src="{{ pokeSrc }}" />
   * ```
   *
   *
   * Default: `false`
   */
  allowSubstringInterpolation?: boolean;
}

````

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
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<input type="text" name="{{ foo }}">
                         ~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<input type="text" name="{{ foo }}bar">
                         ~~~~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<input type="text" attr.data-myExample="{{ foo }}">
                                        ~~~~~~~~~
```

<br>

---

<br>

#### Custom Config

```json
{
  "rules": {
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error",
      {
        "allowSubstringInterpolation": false
      }
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<input type="text" name="{{ foo }}bar">
                         ~~~~~~~~~~~~
```

<br>

---

<br>

#### Custom Config

```json
{
  "rules": {
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error",
      {
        "allowSubstringInterpolation": true
      }
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<img alt="{{username}} is online" src="{{src}}">
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
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<input type="text" [name]="foo">
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<input type="text" name="foo" [(ngModel)]="foo">
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<input type="text" [name]="foo + 'bar'">
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<input type="text" [name]="foo | bar">
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<div>{{ content }}</div>
```

<br>

---

<br>

#### Custom Config

```json
{
  "rules": {
    "@angular-eslint/template/no-interpolation-in-attributes": [
      "error",
      {
        "allowSubstringInterpolation": true
      }
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<img class="icon icon--{{size}}" alt="{{username}} is online" src="online.png">
```

</details>

<br>
