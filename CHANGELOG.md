## 20.1.1 (2025-06-19)

### 🩹 Fixes

- update typescript-eslint packages to v8.34.1 ([#2522](https://github.com/angular-eslint/angular-eslint/pull/2522))
- update dependency @angular/compiler to v20.0.4 ([#2532](https://github.com/angular-eslint/angular-eslint/pull/2532))
- **eslint-plugin:** [no-output-on-prefix] update style guide link ([#2514](https://github.com/angular-eslint/angular-eslint/pull/2514))
- **eslint-plugin-template:** [no-interpolation-in-attributes] use keySpan as attr. range and sourceSpan as replacement range ([#2531](https://github.com/angular-eslint/angular-eslint/pull/2531))

### ❤️ Thank You

- Niklas Wolf
- Victor Santelé

## 20.1.0 (2025-06-16)

### 🚀 Features

- **eslint-plugin:** add rules to ban experimental and developer preview ([#2037](https://github.com/angular-eslint/angular-eslint/pull/2037))

### 🩹 Fixes

- update dependency @angular/compiler to v20.0.3 ([#2505](https://github.com/angular-eslint/angular-eslint/pull/2505))
- update dependency eslint to v9.29.0 ([#2520](https://github.com/angular-eslint/angular-eslint/pull/2520))
- update typescript-eslint packages to v8.34.0 ([#2511](https://github.com/angular-eslint/angular-eslint/pull/2511))

### ❤️ Thank You

- Daniel Kimmich @json-derulo

# 20.0.0 (2025-06-06)

As always we recommend that you update your existing workspaces by using `ng update` as we provide some helpful schematics to help migrate your workspaces to the latest and greatest. Running the following will update Angular, the Angular CLI and angular-eslint together:

```sh
ng update @angular/core @angular/cli angular-eslint
```

### 🚀 Features

- ⚠️ switch to angular v20 ([e2b46ef4](https://github.com/angular-eslint/angular-eslint/commit/e2b46ef4))
- ⚠️ **eslint-lint:** add prefer-inject to recommended ([c8367d3b](https://github.com/angular-eslint/angular-eslint/commit/c8367d3b))
- ⚠️ **eslint-plugin:** switch prefer-standalone fix to suggestion, reference guide ([4583034f](https://github.com/angular-eslint/angular-eslint/commit/4583034f))
- ⚠️ **eslint-plugin:** remove (component|directive)-class-suffix from recommended ([c1022ee6](https://github.com/angular-eslint/angular-eslint/commit/c1022ee6))
- ⚠️ **template-parser:** do not suppress parse errors by default ([#2255](https://github.com/angular-eslint/angular-eslint/pull/2255))

### 🩹 Fixes

- ⚠️ **eslint-plugin:** [sort-keys-in-type-decorator] default orders now include all known keys ([9183385d](https://github.com/angular-eslint/angular-eslint/commit/9183385d))

### ⚠️ Breaking Changes

- ⚠️ **eslint-plugin:** [sort-keys-in-type-decorator] default orders now include all known keys ([9183385d](https://github.com/angular-eslint/angular-eslint/commit/9183385d))
- ⚠️ switch to angular v20 ([e2b46ef4](https://github.com/angular-eslint/angular-eslint/commit/e2b46ef4))
- ⚠️ **eslint-lint:** add prefer-inject to recommended ([c8367d3b](https://github.com/angular-eslint/angular-eslint/commit/c8367d3b))
- ⚠️ **eslint-plugin:** remove (component|directive)-class-suffix from recommended ([c1022ee6](https://github.com/angular-eslint/angular-eslint/commit/c1022ee6))
- ⚠️ **eslint-plugin:** switch prefer-standalone fix to suggestion, reference guide ([4583034f](https://github.com/angular-eslint/angular-eslint/commit/4583034f))
- ⚠️ **template-parser:** do not suppress parse errors by default ([#2255](https://github.com/angular-eslint/angular-eslint/pull/2255))

### ❤️ Thank You

- Dave @reduckted
- JamesHenry @JamesHenry

## 19.8.0 (2025-06-06)

### 🚀 Features

- **eslint-plugin-template:** [no-interpolation-in-attributes] add fixer ([#2501](https://github.com/angular-eslint/angular-eslint/pull/2501))

### ❤️ Thank You

- Niklas Wolf

## 19.7.1 (2025-06-03)

### 🩹 Fixes

- update typescript-eslint packages to v8.33.1 ([#2496](https://github.com/angular-eslint/angular-eslint/pull/2496))
- **eslint-plugin:** [no-uncalled-signals] handle direct signal calls in member expressions ([#2491](https://github.com/angular-eslint/angular-eslint/pull/2491))

### ❤️ Thank You

- James Henry @JamesHenry

## 19.7.0 (2025-06-02)

### 🚀 Features

- **eslint-plugin:** add no-uncalled-signals rule ([#2383](https://github.com/angular-eslint/angular-eslint/pull/2383))
- **eslint-plugin:** [require-localize-metadata] add requireCustomId option ([#2430](https://github.com/angular-eslint/angular-eslint/pull/2430))
- **eslint-plugin-template:** [click-events-have-key-events] Added ignoreWithDirectives option ([#2365](https://github.com/angular-eslint/angular-eslint/pull/2365))

### 🩹 Fixes

- update typescript-eslint packages to v8.33.0 ([#2465](https://github.com/angular-eslint/angular-eslint/pull/2465))
- update dependency @angular/compiler to v19.2.14 ([#2477](https://github.com/angular-eslint/angular-eslint/pull/2477))
- update dependency ignore to v7.0.5 ([#2485](https://github.com/angular-eslint/angular-eslint/pull/2485))
- update dependency eslint to v9.28.0 ([#2484](https://github.com/angular-eslint/angular-eslint/pull/2484))
- **eslint-plugin-template:** set template-parser as peer dependency ([#2487](https://github.com/angular-eslint/angular-eslint/pull/2487))
- **eslint-plugin-template:** any valid DOM element with role button is interactive ([#2488](https://github.com/angular-eslint/angular-eslint/pull/2488))
- **eslint-plugin-template:** [label-has-associated-control] labelComponents should override default label inputs ([#2360](https://github.com/angular-eslint/angular-eslint/pull/2360))
- **eslint-plugin-template:** [prefer-template-literal] handle nested and concatenations in template literal ([#2466](https://github.com/angular-eslint/angular-eslint/pull/2466))
- **schematics:** ensure @eslint/js and @angular-eslint/builder are always available in non-npm repos ([#2486](https://github.com/angular-eslint/angular-eslint/pull/2486))

### ❤️ Thank You

- Cullen Prestegard @cprestegard
- Guillaume DROUARD
- Igor Dimitrijevic
- James Henry @JamesHenry
- jelledijkstra97 @jelledijkstra97
- Stephen Jackson

## 19.6.0 (2025-05-27)

### 🚀 Features

- **eslint-plugin:** [prefer-inject] add new rule ([#2461](https://github.com/angular-eslint/angular-eslint/pull/2461))

### 🩹 Fixes

- respect existing eslint.config.ts, eslint.config.cts, eslint.config.mts files ([#2458](https://github.com/angular-eslint/angular-eslint/pull/2458))
- **eslint-plugin:** [sort-keys-in-type-decorator] preserve unconfigured properties during autofix ([#2456](https://github.com/angular-eslint/angular-eslint/pull/2456))
- **eslint-plugin:** [use-lifecycle-interface] do not report if the method uses override ([#2463](https://github.com/angular-eslint/angular-eslint/pull/2463))

### ❤️ Thank You

- James Henry @JamesHenry

## 19.5.0 (2025-05-25)

### 🚀 Features

- **builder:** add stats option ([#2453](https://github.com/angular-eslint/angular-eslint/pull/2453))
- **eslint-plugin:** introduce sort keys in type-decorator rule ([#2187](https://github.com/angular-eslint/angular-eslint/pull/2187))
- **eslint-plugin-template:** [no-nested-tags] add rule ([#2398](https://github.com/angular-eslint/angular-eslint/pull/2398))
- **eslint-plugin-template:** add rule prefer-at-empty ([#2352](https://github.com/angular-eslint/angular-eslint/pull/2352))
- **schematics:** support --skip-install for ng-add ([#2451](https://github.com/angular-eslint/angular-eslint/pull/2451))

### 🩹 Fixes

- update dependency semver to v7.7.2 ([#2421](https://github.com/angular-eslint/angular-eslint/pull/2421))
- update typescript-eslint packages to v8.32.1 ([#2422](https://github.com/angular-eslint/angular-eslint/pull/2422))
- update dependency @angular/compiler to v19.2.13 ([#2438](https://github.com/angular-eslint/angular-eslint/pull/2438))
- update dependency eslint to v9.27.0 ([#2431](https://github.com/angular-eslint/angular-eslint/pull/2431))
- **builder:** correct option name in flat config error ([#2443](https://github.com/angular-eslint/angular-eslint/pull/2443))
- **eslint-plugin-template:** [prefer-template-literal] handle parentheses in autofix ([#2418](https://github.com/angular-eslint/angular-eslint/pull/2418))
- **eslint-plugin-template:** [alt-text] ensure multiple attributes do not cause false negatives ([#2441](https://github.com/angular-eslint/angular-eslint/pull/2441))
- **eslint-plugin-template:** [cyclomatic-complexity] handle new control flow syntax ([#2447](https://github.com/angular-eslint/angular-eslint/pull/2447))
- **eslint-plugin-template:** [prefer-at-empty] remove closing brace from @if when no longer needed ([#2450](https://github.com/angular-eslint/angular-eslint/pull/2450))

### ❤️ Thank You

- Alexander von Weiss @sod
- Benjamin Schäublin
- Dave @reduckted
- Guillaume DROUARD
- James Henry @JamesHenry

## 19.4.0 (2025-05-08)

### 🚀 Features

- **eslint-plugin:** add rule prefer-output-emitter-ref ([#2324](https://github.com/angular-eslint/angular-eslint/pull/2324))
- **eslint-plugin-template:** [no-interpolation-in-attributes] add allowSubstringInterpolation option ([#2373](https://github.com/angular-eslint/angular-eslint/pull/2373))
- **eslint-plugin-template:** Add `prefer-template-literal` rule ([#2308](https://github.com/angular-eslint/angular-eslint/pull/2308))

### 🩹 Fixes

- update dependency @angular/compiler to v19.2.10 ([#2394](https://github.com/angular-eslint/angular-eslint/pull/2394))
- update dependency ignore to v7.0.4 ([#2396](https://github.com/angular-eslint/angular-eslint/pull/2396))
- update typescript-eslint packages to v8.32.0 ([#2399](https://github.com/angular-eslint/angular-eslint/pull/2399))
- update dependency eslint to v9.26.0 ([#2409](https://github.com/angular-eslint/angular-eslint/pull/2409))
- **eslint-plugin-template:** [no-any] handle key reads ([#1701](https://github.com/angular-eslint/angular-eslint/pull/1701), [#2335](https://github.com/angular-eslint/angular-eslint/pull/2335))
- **eslint-plugin-template:** correct column adjustment for inline template message locations ([#2358](https://github.com/angular-eslint/angular-eslint/pull/2358))
- **eslint-plugin-template:** remove backticks from inline template with interpolation ([#2368](https://github.com/angular-eslint/angular-eslint/pull/2368))

### ❤️ Thank You

- daiscog @daiscog
- Dave @reduckted
- Evgeny Stepanovych @undsoft
- Guillaume DROUARD

## 19.3.0 (2025-03-22)

### 🚀 Features

- use @angular/compiler 19.2.3 and rename some AST nodes to match ([#2320](https://github.com/angular-eslint/angular-eslint/pull/2320))
- **eslint-plugin-template:** [button-has-type] add option to ignore missing type ([#2326](https://github.com/angular-eslint/angular-eslint/pull/2326))
- **eslint-plugin-template:** add rule prefer-contextual-for-variables ([#2311](https://github.com/angular-eslint/angular-eslint/pull/2311))
- **template-parser:** visit @let child nodes ([#2312](https://github.com/angular-eslint/angular-eslint/pull/2312))

### 🩹 Fixes

- update typescript-eslint packages to v8.26.1 ([#2313](https://github.com/angular-eslint/angular-eslint/pull/2313))
- update typescript-eslint packages to v8.27.0 ([#2328](https://github.com/angular-eslint/angular-eslint/pull/2328))
- update dependency eslint to v9.23.0 ([#2331](https://github.com/angular-eslint/angular-eslint/pull/2331))
- **eslint-plugin-template:** [i18n] Avoid exception in i18n rule with allowMarkupInContent=false ([#2327](https://github.com/angular-eslint/angular-eslint/pull/2327))
- **eslint-plugin-template:** [attributes-order] order i18n attributes ([#2307](https://github.com/angular-eslint/angular-eslint/pull/2307))
- **eslint-plugin-template:** [attributes-order] treat inputs without square brackets as attributes ([#2316](https://github.com/angular-eslint/angular-eslint/pull/2316))

### ❤️ Thank You

- Dave @reduckted
- m-akinc @m-akinc

## 19.2.1 (2025-03-08)

### 🩹 Fixes

- update dependency @angular/compiler to v19.2.1 ([#2288](https://github.com/angular-eslint/angular-eslint/pull/2288))
- update dependency eslint-scope to v8.3.0 ([#2296](https://github.com/angular-eslint/angular-eslint/pull/2296))
- update typescript-eslint packages to v8.26.0 ([#2282](https://github.com/angular-eslint/angular-eslint/pull/2282))
- update dependency eslint to v9.22.0 ([#2294](https://github.com/angular-eslint/angular-eslint/pull/2294))
- **eslint-plugin-template:** [prefer-self-closing-tags] resolve wrong reports when structural directive + no content + no self-closing ([#2287](https://github.com/angular-eslint/angular-eslint/pull/2287))

### ❤️ Thank You

- Guillaume DROUARD

## 19.2.0 (2025-03-02)

### 🚀 Features

- **eslint-plugin:** add rule require-lifecycle-on-prototype ([#2259](https://github.com/angular-eslint/angular-eslint/pull/2259))

### 🩹 Fixes

- update dependency @angular/compiler to v19.2.0 ([#2268](https://github.com/angular-eslint/angular-eslint/pull/2268))
- update dependency eslint to v9.21.0 ([#2243](https://github.com/angular-eslint/angular-eslint/pull/2243))
- update typescript-eslint packages to v8.25.0 ([#2263](https://github.com/angular-eslint/angular-eslint/pull/2263))
- **eslint-plugin:** [no-output-native] update native event names ([#2236](https://github.com/angular-eslint/angular-eslint/pull/2236))
- **eslint-plugin-template:** [prefer-self-closing-tags] do not treat comments as whitespace ([#2256](https://github.com/angular-eslint/angular-eslint/pull/2256))
- **eslint-plugin-template:** [prefer-self-closing-tags] allow nested ng-content ([#2257](https://github.com/angular-eslint/angular-eslint/pull/2257))
- **eslint-plugin-template:** [prefer-static-string-properties] do not check structural directives ([#2253](https://github.com/angular-eslint/angular-eslint/pull/2253))
- **eslint-plugin-template:** find inline templates on components in blocks ([#2238](https://github.com/angular-eslint/angular-eslint/pull/2238))
- **prefer-static-string-properties:** resolve bug with directives ([#2271](https://github.com/angular-eslint/angular-eslint/pull/2271))
- **prefer-static-string-properties:** exclude special attributes ([#2273](https://github.com/angular-eslint/angular-eslint/pull/2273))

### ❤️ Thank You

- Dave @reduckted
- Marie Briand @mbriand-lucca

## 19.1.0 (2025-02-09)

### 🚀 Features

- **eslint-plugin:** prefer-signals read-only suggestion is now a fix ([#2175](https://github.com/angular-eslint/angular-eslint/pull/2175))
- **eslint-plugin:** prefer-signals now checks .asReadonly() calls ([#2218](https://github.com/angular-eslint/angular-eslint/pull/2218))
- **eslint-plugin-template:** add rule prefer-static-string-properties ([#2228](https://github.com/angular-eslint/angular-eslint/pull/2228))

### 🩹 Fixes

- update dependency ignore to v7 ([#2200](https://github.com/angular-eslint/angular-eslint/pull/2200))
- update dependency @angular/compiler to v19.1.5 ([#2226](https://github.com/angular-eslint/angular-eslint/pull/2226))
- update dependency semver to v7.7.1 ([#2225](https://github.com/angular-eslint/angular-eslint/pull/2225))
- update typescript-eslint packages to v8.23.0 ([#2212](https://github.com/angular-eslint/angular-eslint/pull/2212))
- update dependency eslint to v9.20.0 ([#2217](https://github.com/angular-eslint/angular-eslint/pull/2217))
- **eslint-plugin:** [prefer-signals] support linkedSignal ([#2213](https://github.com/angular-eslint/angular-eslint/pull/2213))
- **eslint-plugin:** [no-input-prefix] false positive on input initializer value ([#2184](https://github.com/angular-eslint/angular-eslint/pull/2184))
- **eslint-plugin-template:** [prefer-self-closing-tags] do not remove HTML-encoded whitespace ([#2229](https://github.com/angular-eslint/angular-eslint/pull/2229))
- **eslint-plugin-template:** [attribute-order] check for ng-template within svg ([#2223](https://github.com/angular-eslint/angular-eslint/pull/2223))

### ❤️ Thank You

- Cédric Exbrayat @cexbrayat
- Dave @reduckted
- Lucas Neto Moreira

## 19.0.2 (2024-12-10)

### 🩹 Fixes

- update typescript-eslint packages to v8.18.0 ([#2171](https://github.com/angular-eslint/angular-eslint/pull/2171))
- **eslint-plugin:** [prefer-standalone] error range should only include property and value ([#2172](https://github.com/angular-eslint/angular-eslint/pull/2172))

### ❤️ Thank You

- James Henry @JamesHenry

## 19.0.1 (2024-12-06)

### 🩹 Fixes

- update dependency @angular/compiler to v19.0.3 ([#2159](https://github.com/angular-eslint/angular-eslint/pull/2159))
- update dependency eslint to v9.16.0 ([#2148](https://github.com/angular-eslint/angular-eslint/pull/2148))
- update typescript-eslint packages to v8.17.0 ([#2153](https://github.com/angular-eslint/angular-eslint/pull/2153))
- **eslint-plugin:** add prefer-signals rule to exported config ([#2150](https://github.com/angular-eslint/angular-eslint/pull/2150))
- **eslint-plugin-template:** prevent the slot tag from being self-closing ([#2088](https://github.com/angular-eslint/angular-eslint/pull/2088))

### ❤️ Thank You

- Joan Llenas @joanllenas
- Quentin Deroubaix @quentinderoubaix

# 19.0.0 (2024-11-29)

As always we recommend that you update your existing workspaces by using `ng update` as we provide some helpful schematics to help migrate your workspaces to the latest and greatest.

However, please note that the `angular-eslint` package itself now supports being referenced as the schematics collection, so...

**IF YOU ARE ALREADY USING `angular-eslint` and ESLint v9 and flat config** you can now do the following:

```sh
ng update @angular/core @angular/cli angular-eslint
```

(Note: If you encounter any issues with this, you may need to update to the latest v18 release of `angular-eslint` first)

**IF YOU ARE STILL USING `@angular-eslint/schematics` and ESLint v8 and `.eslintrc.json` configs** you can still do the following:

```sh
ng update @angular/core @angular/cli @angular-eslint/schematics
```

**NOTE: There will not be any migration of your setup to ESLint v9 or flat configs for existing ESLint v8 workspaces while migrating to angular-eslint v19.**

We will explore landing an opt in migration schematic in a minor release after `19.0.0`.

### 🚀 Features

- update angular packages to the stable v19 ([#2120](https://github.com/angular-eslint/angular-eslint/pull/2120))
- allow referencing angular-eslint as the schematics collection ([2be3107b](https://github.com/angular-eslint/angular-eslint/commit/2be3107b))
- ⚠️ **eslint-plugin:** remove deprecated prefer-standalone-component rule ([#2112](https://github.com/angular-eslint/angular-eslint/pull/2112))
- ⚠️ **eslint-plugin:** prefer-standalone recognizes that standalone is the default ([#2096](https://github.com/angular-eslint/angular-eslint/pull/2096))
- ⚠️ **eslint-plugin:** remove deprecated sort-ngmodule-metadata-arrays rule ([#2114](https://github.com/angular-eslint/angular-eslint/pull/2114))
- ⚠️ **eslint-plugin:** remove deprecated no-host-metadata-property rule ([#2113](https://github.com/angular-eslint/angular-eslint/pull/2113))
- **eslint-plugin:** new rule prefer-signals ([#1872](https://github.com/angular-eslint/angular-eslint/pull/1872))
- ⚠️ **eslint-plugin:** promote prefer-standalone to recommended ([8dfdc4f4](https://github.com/angular-eslint/angular-eslint/commit/8dfdc4f4))

### ⚠️ Breaking Changes

- ⚠️ **eslint-plugin:** promote prefer-standalone to recommended ([8dfdc4f4](https://github.com/angular-eslint/angular-eslint/commit/8dfdc4f4))
- ⚠️ **eslint-plugin:** remove deprecated no-host-metadata-property rule ([#2113](https://github.com/angular-eslint/angular-eslint/pull/2113))
- ⚠️ **eslint-plugin:** remove deprecated sort-ngmodule-metadata-arrays rule ([#2114](https://github.com/angular-eslint/angular-eslint/pull/2114))
- ⚠️ **eslint-plugin:** prefer-standalone recognizes that standalone is the default ([#2096](https://github.com/angular-eslint/angular-eslint/pull/2096))
- ⚠️ **eslint-plugin:** remove deprecated prefer-standalone-component rule ([#2112](https://github.com/angular-eslint/angular-eslint/pull/2112))

### ❤️ Thank You

- Daniel Kimmich @json-derulo
- Dave @reduckted
- James Henry @JamesHenry
- JamesHenry @JamesHenry
- Leosvel Pérez Espinosa @leosvelperez

## 18.4.3 (2024-11-29)

### 🩹 Fixes

- yarn pnp issues ([#2143](https://github.com/angular-eslint/angular-eslint/pull/2143))
- update dependency @angular/compiler to v18.2.13 ([#2139](https://github.com/angular-eslint/angular-eslint/pull/2139))
- update typescript-eslint packages to v8.16.0 ([#2135](https://github.com/angular-eslint/angular-eslint/pull/2135))

### ❤️ Thank You

- James Henry @JamesHenry

## 18.4.2 (2024-11-23)

### 🩹 Fixes

- update dependency eslint-scope to v8.2.0 ([#2106](https://github.com/angular-eslint/angular-eslint/pull/2106))
- **angular-eslint:** allow using angular-eslint with ng add and ng update ([#2134](https://github.com/angular-eslint/angular-eslint/pull/2134))
- **eslint-plugin:** handle `output()` and `input()` functions in various rules ([#2098](https://github.com/angular-eslint/angular-eslint/pull/2098))
- **eslint-plugin:** fix placement of lifecycle interface for subclasses ([#1965](https://github.com/angular-eslint/angular-eslint/pull/1965))

### ❤️ Thank You

- Aleksandr Martirosyan
- Dave @reduckted
- James Henry @JamesHenry

## 18.4.1 (2024-11-18)

### 🩹 Fixes

- update dependency ignore to v6 ([#2047](https://github.com/angular-eslint/angular-eslint/pull/2047))
- update dependency @angular/compiler to v18.2.12 ([#2090](https://github.com/angular-eslint/angular-eslint/pull/2090))

## 18.4.0 (2024-10-21)

### 🚀 Features

- support ESM configs and .cjs and .mjs extensions ([#2068](https://github.com/angular-eslint/angular-eslint/pull/2068))

### 🩹 Fixes

- update dependency aria-query to v5.3.2 ([#2053](https://github.com/angular-eslint/angular-eslint/pull/2053))
- update dependency @angular/compiler to v18.2.8 ([#2049](https://github.com/angular-eslint/angular-eslint/pull/2049))
- update dependency eslint-scope to v8.1.0 ([#2075](https://github.com/angular-eslint/angular-eslint/pull/2075))
- update typescript-eslint packages to v8.10.0 ([#2046](https://github.com/angular-eslint/angular-eslint/pull/2046))
- update dependency eslint to v9.13.0, support noConfigLookup ([#2045](https://github.com/angular-eslint/angular-eslint/pull/2045))
- **eslint-plugin:** update list of native events ([#1881](https://github.com/angular-eslint/angular-eslint/pull/1881))
- **template-parser:** traverse ng-content fallback content ([#2031](https://github.com/angular-eslint/angular-eslint/pull/2031))

### ❤️ Thank You

- Dementii K @demkalkov
- James Henry @JamesHenry
- Matt Lewis @mattlewis92

## 18.3.1 (2024-09-11)

### 🩹 Fixes

- update dependency eslint to v9.9.1 ([#2008](https://github.com/angular-eslint/angular-eslint/pull/2008))
- update dependency @angular/compiler to v18.2.1 ([#2006](https://github.com/angular-eslint/angular-eslint/pull/2006))
- update typescript-eslint packages to v8.2.0 ([#2001](https://github.com/angular-eslint/angular-eslint/pull/2001))
- **template-parser:** visit receiver of Call expression ([#2015](https://github.com/angular-eslint/angular-eslint/pull/2015))

### ❤️ Thank You

- James Henry @JamesHenry
- Paweł Maniecki @P4

## 18.3.0 (2024-08-13)

### 🚀 Features

- **eslint-plugin:** new rule runtime-localize ([#1898](https://github.com/angular-eslint/angular-eslint/pull/1898))

### 🩹 Fixes

- update dependency eslint to v9.9.0 ([#1976](https://github.com/angular-eslint/angular-eslint/pull/1976))
- update dependency @angular/compiler to v18.1.4 ([#1973](https://github.com/angular-eslint/angular-eslint/pull/1973))
- update dependency ignore to v5.3.2 ([#1979](https://github.com/angular-eslint/angular-eslint/pull/1979))
- update typescript-eslint packages to v8.1.0 ([#1982](https://github.com/angular-eslint/angular-eslint/pull/1982))
- **eslint-plugin-template:** [interactive-supports-focus] allowList with form as default option to support event bubbling ([#1922](https://github.com/angular-eslint/angular-eslint/pull/1922))
- **eslint-plugin-template:** [prefer-self-closing-tags] fix ng-content with rich default content ([#1971](https://github.com/angular-eslint/angular-eslint/pull/1971))
- **prefer-self-closing-tags:** handle both forward and backward slash ([#1967](https://github.com/angular-eslint/angular-eslint/pull/1967))

### ❤️ Thank You

- Daniel Kimmich @json-derulo
- James Henry @JamesHenry
- m-akinc @m-akinc
- Sandi Barr @sandikbarr
- Simon

## 18.2.0 (2024-07-31)

### 🚀 Features

- update typescript-eslint to v8 stable, eslint v9.8.0 ([#1956](https://github.com/angular-eslint/angular-eslint/pull/1956))

Run `ng update @angular-eslint/schematics` to automatically update your v8 prerelease dependencies of typescript-eslint to v8.0.0, as well as ESLint to v9.8.0 (if you are still using typescript-eslint v7 and ESLint v8 you will be unaffected by this migration).

### 🩹 Fixes

- update dependency axobject-query to v4.1.0 ([#1936](https://github.com/angular-eslint/angular-eslint/pull/1936))
- update dependency semver to v7.6.3 ([#1933](https://github.com/angular-eslint/angular-eslint/pull/1933))
- update dependency eslint-scope to v8.0.2 ([#1932](https://github.com/angular-eslint/angular-eslint/pull/1932))
- update dependency @angular/compiler to v18.1.3 ([#1954](https://github.com/angular-eslint/angular-eslint/pull/1954))
- update nrwl monorepo to v19.5.4 ([#1950](https://github.com/angular-eslint/angular-eslint/pull/1950))
- **eslint-plugin:** [prefer-standalone] ignore empty Directive decorators ([#1949](https://github.com/angular-eslint/angular-eslint/pull/1949))
- **eslint-plugin-template:** add meta to preprocessor to resolve eslint cache error ([#1924](https://github.com/angular-eslint/angular-eslint/pull/1924))

### ❤️ Thank You

- James Henry @JamesHenry
- kwiateusz @kwiateusz
- Paweł Maniecki @P4

## 18.1.0 (2024-07-01)

### 🚀 Features

- **eslint-plugin:** [prefer-output-readonly] support output() function ([#1876](https://github.com/angular-eslint/angular-eslint/pull/1876))
- **eslint-plugin:** [no-call-expression] add allowPrefix and allowSuffix ([#1897](https://github.com/angular-eslint/angular-eslint/pull/1897))

### 🩹 Fixes

- update dependency @angular/compiler to v18.0.2 ([#1852](https://github.com/angular-eslint/angular-eslint/pull/1852))
- update dependency eslint to v9.5.0 ([#1886](https://github.com/angular-eslint/angular-eslint/pull/1886))
- update dependency eslint to v9.6.0 ([#1900](https://github.com/angular-eslint/angular-eslint/pull/1900))
- update dependency @angular/compiler to v18.0.5 ([#1893](https://github.com/angular-eslint/angular-eslint/pull/1893))
- update nrwl monorepo to v19.3.2 ([#1902](https://github.com/angular-eslint/angular-eslint/pull/1902))
- update typescript-eslint packages to v8.0.0-alpha.38 ([#1904](https://github.com/angular-eslint/angular-eslint/pull/1904))
- **eslint-plugin-template:** [prefer-self-closing-tags] always ignore index.html files ([#1865](https://github.com/angular-eslint/angular-eslint/pull/1865))
- **eslint-plugin-template:** [prefer-self-closing-tags] support ng-content with fallback content ([#1880](https://github.com/angular-eslint/angular-eslint/pull/1880))
- **test-utils:** use configured RuleTester.afterAll over global ([#1878](https://github.com/angular-eslint/angular-eslint/pull/1878))

### ❤️ Thank You

- Christian Svensson
- Daniel Kimmich @json-derulo
- Dave @reduckted
- Martijn van der Meij
- Maximilian Main @MaximilianMain

## 18.0.1 (2024-05-30)

### 🩹 Fixes

- move typescript-eslint packages to peerDeps, consistently allow v7 and v8 ([#1856](https://github.com/angular-eslint/angular-eslint/pull/1856))

As part of the v18 release, support for typescript-eslint v8 prereleases was added. For authors of custom rules that consume the `@angular-eslint/utils` or new `@angular-eslint/test-utils` packages, the initial way this was set up with dependencies could cause type conflicts between v7 and v8. To resolve this the `@angular-eslint/*` packages now depend on `@typescript-eslint/*` packages via a peerDependency which permits both v7 and v8 prereleases.

### ❤️ Thank You

- James Henry @JamesHenry

# 18.0.0 (2024-05-29)

As always we recommend that you update your existing workspaces by using `ng update` as we provide some helpful schematics to help migrate your workspaces to the latest and greatest. Running the following will update Angular, the Angular CLI and angular-eslint together:

```sh
ng update @angular/core @angular/cli @angular-eslint/schematics
```

**NOTE: There will not be any migration of your setup to ESLint v9 or flat configs for existing workspaces in v18.**

The ESLint team are working on auto-migrate tooling which we will leverage in an opt-in conversion generator once it is ready in a v18 minor release and consider full auto-migration in v19 in six months (aligned with Angular major release schedule as always).

If you want to manually migrate your workspace to use ESLint v9, `typescript-eslint` v8, and flat config you are welcome to and it should be fully supported in v18.

> **If you are going to attempt this, we strongly recommended creating a fresh Angular v18 workspace and adding angular-eslint to it per the instructions below and then copying the dependencies and configs that it applies into your existing workspace**

Here is an example of what the new flat config with `angular-eslint` v18, `typescript-eslint` v8, and ESLint v9 looks like:

![image](https://github.com/angular-eslint/angular-eslint/assets/900523/3f25ad48-ba00-4950-a5d3-546376a1a9f7)

---

## Adding to New Angular Workspaces in v18

There is a decision to be made when adding to new Angular v18 workspaces.

Just as before, if you want to add `angular-eslint` to a workspace with no existing lint setup, you leverage `ng add` with the `@angular-eslint/schematics` package.

The difference is in v18, you have the option of using either:

- the latest version of ESLint v9, with the latest default so called "flat config" (`eslint.config.js`) alongside the latest prerelease of `typescript-eslint` v8 (https://typescript-eslint.io/blog/announcing-typescript-eslint-v8-beta)
  **OR**
- the final stable version of ESLint v8, with the legacy so called "eslintrc" config (`.eslintrc.json`) and the latest stable version of `typescript-eslint` v7

**The ESLint v9 option is the default scenario if you simply run `ng add` with no other changes.** If you want to signal to `angular-eslint` that you instead want to go with the ESLint v8 option, simply add an `eslint` v8 (the exact version does not matter, it just needs to be less than 9) `devDependency` in your package.json before running the `ng add`. That's it - you don't even need to install the `eslint` package, it just needs to be listed there.

E.g.
![image](https://github.com/angular-eslint/angular-eslint/assets/900523/128681fc-9149-45b3-a4da-dfe55dbf8a76)

Here are example "after" root `package.json` files from the two scenarios:

**1. No `eslint` devDependency specified before running `ng add`**, use the default ESLint v9 setup. This will use the new `angular-eslint` and `typescript-eslint` core packages, so you will see much fewer individual devDependencies added:

![image](https://github.com/angular-eslint/angular-eslint/assets/900523/54e62bd9-ddc5-407a-92f8-03de2819ac9b)

**2. `eslint` v8 devDependency is specified before running `ng-add`**. Use ESlint `8.57.0` and the traditional `@typescript-eslint/` and `@angular-eslint/` packages.

![image](https://github.com/angular-eslint/angular-eslint/assets/900523/548aa968-3459-46c4-8a11-5769a5d55f7a)

---

### 🚀 Features

- ⚠️ update to Angular v18, drop support for Angular v17 ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))
- ⚠️ deprecate no-host-metadata-property rule and remove from recommended config of `@angular-eslint/eslint-plugin` ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))
- ⚠️ drop support for ESLint v7 ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))
- ⚠️ migrate test related utils out of `@angular-eslint/utils` into new `@angular-eslint/test-utils` package ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))
- add support for ESLint v9 (maintaining support for the final version of ESLint v8 - `8.57.0`). ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))
- add the new `angular-eslint` core package for use in ESLint v9 workspaces ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))
- generate new configs as the new default flat config with ESLint v9 and `typescript-eslint` v8 prereleases ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))

### 🩹 Fixes

- update links from angular.io to angular.dev ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))

#### ⚠️ Breaking Changes

- ⚠️ update to Angular v18, drop support for Angular v17 ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))
- ⚠️ deprecate no-host-metadata-property rule and remove from recommended config of `@angular-eslint/eslint-plugin` ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))
- ⚠️ drop support for ESLint v7 ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))
- ⚠️ migrate test related utils out of `@angular-eslint/utils` into new `@angular-eslint/test-utils` package ([#1830](https://github.com/angular-eslint/angular-eslint/pull/1830))

### ❤️ Thank You

- James Henry @JamesHenry

## 17.5.2 (2024-05-28)

### 🩹 Fixes

- update typescript-eslint packages to v7.11.0 ([#1846](https://github.com/angular-eslint/angular-eslint/pull/1846))

## 17.5.1 (2024-05-23)

### 🩹 Fixes

- update dependency @angular/compiler to v17.3.10 ([#1835](https://github.com/angular-eslint/angular-eslint/pull/1835))

## 17.5.0 (2024-05-22)

### 🚀 Features

- **eslint-plugin:** [use-lifecycle-interface] add fixer for the rule ([#1691](https://github.com/angular-eslint/angular-eslint/pull/1691))
- **eslint-plugin-template:** [i18n] add allowMarkupInContent option ([#1795](https://github.com/angular-eslint/angular-eslint/pull/1795))

### 🩹 Fixes

- update dependency @angular/compiler to v17.3.9 ([#1821](https://github.com/angular-eslint/angular-eslint/pull/1821))
- update typescript-eslint packages to v7.10.0 ([#1822](https://github.com/angular-eslint/angular-eslint/pull/1822))
- **eslint-plugin:** [no-input-rename] incorrectly triggers on input transforms ([#1809](https://github.com/angular-eslint/angular-eslint/pull/1809))
- **eslint-plugin-template:** [label-has-associated-control] check id's in the for attribute of a label for existence ([#1761](https://github.com/angular-eslint/angular-eslint/pull/1761))

### ❤️ Thank You

- Auke Bruinsma
- Jonathan Kolberg @bulldog98
- m-akinc @m-akinc
- Mateusz

## 17.4.1 (2024-05-15)

### 🩹 Fixes

- update dependency @angular/compiler to v17.3.8 ([#1797](https://github.com/angular-eslint/angular-eslint/pull/1797))
- **schematics:** ignore nx cache ([#1816](https://github.com/angular-eslint/angular-eslint/pull/1816))

### ❤️ Thank You

- James Henry @JamesHenry

## 17.4.0 (2024-05-07)

### 🚀 Features

- **eslint-plugin:** [no-duplicates-in-metadata-arrays] new rule ([#1779](https://github.com/angular-eslint/angular-eslint/pull/1779))

### 🩹 Fixes

- update dependency @angular/compiler to v17.3.4 ([#1750](https://github.com/angular-eslint/angular-eslint/pull/1750))
- update dependency eslint-scope to v8.0.1 ([#1762](https://github.com/angular-eslint/angular-eslint/pull/1762))
- update dependency @angular/compiler to v17.3.6 ([#1775](https://github.com/angular-eslint/angular-eslint/pull/1775))
- update typescript-eslint packages to v7.8.0 ([#1786](https://github.com/angular-eslint/angular-eslint/pull/1786))
- **eslint-plugin:** [sort-ngmodule-metadata-arrays] deprecate rule ([#1781](https://github.com/angular-eslint/angular-eslint/pull/1781))
- **eslint-plugin-template:** [attributes-order] calculate valueless structural directive start/end positions correctly ([#1726](https://github.com/angular-eslint/angular-eslint/pull/1726))
- **schematics:** update schema.json with latest from Angular ([a5adbfc](https://github.com/angular-eslint/angular-eslint/commit/a5adbfc))

### ❤️ Thank You

- “JamesHenry” @JamesHenry
- Adrian Baran @abaran30
- Brad Kovach @bradkovach

## 17.3.0 (2024-03-15)

### 🚀 Features

- **eslint-plugin:** add consistent-component-styles rule ([#1710](https://github.com/angular-eslint/angular-eslint/pull/1710))
- **eslint-plugin:** add prefer-standalone rule for checking all components, directives and pipes ([#1627](https://github.com/angular-eslint/angular-eslint/pull/1627))

### 🩹 Fixes

- update dependency tmp to v0.2.3 ([#1734](https://github.com/angular-eslint/angular-eslint/pull/1734))
- migrate to nx 18 ([#1732](https://github.com/angular-eslint/angular-eslint/pull/1732))
- update dependency ignore to v5.3.1 ([#1733](https://github.com/angular-eslint/angular-eslint/pull/1733))
- update dependency eslint to v8.57.0 ([#1739](https://github.com/angular-eslint/angular-eslint/pull/1739))
- update typescript-eslint packages to v7 (major) ([#1742](https://github.com/angular-eslint/angular-eslint/pull/1742))
- update dependency @angular/compiler to v17.3.0 ([#1713](https://github.com/angular-eslint/angular-eslint/pull/1713))
- output declaration files in all packages ([#1724](https://github.com/angular-eslint/angular-eslint/pull/1724))
- **eslint-plugin-template:** [eqeqeq] calculate offset to find true absolute source span ([#1709](https://github.com/angular-eslint/angular-eslint/pull/1709))

### ❤️ Thank You

- Christian Svensson
- Dave @reduckted
- James Henry @JamesHenry
- Joey Jacobs @joeyj
- Luis Estevez @estevezluis

## 17.2.1 (2024-01-20)

### 🩹 Fixes

- update typescript-eslint packages to v6.18.1 ([#1685](https://github.com/angular-eslint/angular-eslint/pull/1685))
- update typescript-eslint packages to v6.19.0 ([#1703](https://github.com/angular-eslint/angular-eslint/pull/1703))
- update dependency @angular/compiler to v17.1.0 ([#1689](https://github.com/angular-eslint/angular-eslint/pull/1689))
- **eslint-plugin-template:** [no-call-expression] False negative with the new control flow syntax ([#1677](https://github.com/angular-eslint/angular-eslint/pull/1677))
- **eslint-plugin-template:** handle i18n tags on structural direcives ([#1662](https://github.com/angular-eslint/angular-eslint/pull/1662))

### ❤️ Thank You

- Adam Reisinger @Res42
- Matt Lewis @mattlewis92

## 17.2.0 (2024-01-06)

### 🚀 Features

- **eslint-plugin:** [no-async-lifecycle-method] add rule ([#1643](https://github.com/angular-eslint/angular-eslint/pull/1643))

### 🩹 Fixes

- update dependency eslint to v8.56.0 ([#1657](https://github.com/angular-eslint/angular-eslint/pull/1657))
- update typescript-eslint packages to v6.18.0 ([#1682](https://github.com/angular-eslint/angular-eslint/pull/1682))
- update dependency @angular/compiler to v17.0.8 ([#1618](https://github.com/angular-eslint/angular-eslint/pull/1618))
- update dependency eslint-scope to v8 ([#1683](https://github.com/angular-eslint/angular-eslint/pull/1683))
- **eslint-plugin-template:** fix control flow syntax with i18n rule ([#1656](https://github.com/angular-eslint/angular-eslint/pull/1656))

### ❤️ Thank You

- Matt Lewis @mattlewis92
- Steven Chim @chimurai

## 17.1.1

### 🩹 Fixes

- update nrwl monorepo to v17.1.3 ([#1632](https://github.com/angular-eslint/angular-eslint/pull/1632))
- update typescript-eslint packages to v6.12.0 ([#1631](https://github.com/angular-eslint/angular-eslint/pull/1631))
- update dependency ignore to v5.3.0 ([#1622](https://github.com/angular-eslint/angular-eslint/pull/1622))
- update dependency eslint to v8.54.0 ([#1625](https://github.com/angular-eslint/angular-eslint/pull/1625))
- update typescript-eslint packages to v6.13.0 ([#1644](https://github.com/angular-eslint/angular-eslint/pull/1644))
- update typescript-eslint packages to v6.13.1 ([#1649](https://github.com/angular-eslint/angular-eslint/pull/1649))
- **eslint-plugin:** fix max inline declarations rule for styles string ([#1630](https://github.com/angular-eslint/angular-eslint/pull/1630))
- **eslint-plugin-template:** [prefer-ngsrc] Do not prefer ngsrc for base64-encoded strings ([#1628](https://github.com/angular-eslint/angular-eslint/pull/1628))
- **eslint-plugin-template:** [prefer-control-flow] prevent error when… ([#1634](https://github.com/angular-eslint/angular-eslint/pull/1634))

### ❤️ Thank You

- Christian Svensson
- Daniel Kimmich @json-derulo
- Luis Estevez @estevezluis

## 17.1.0

### 🚀 Features

- **eslint-plugin-template:** [no-negated-async] values used with the async pipe are not negated ([#1606](https://github.com/angular-eslint/angular-eslint/pull/1606))
- **eslint-plugin-template:** [prefer-control-flow] add rule ([#1600](https://github.com/angular-eslint/angular-eslint/pull/1600))

### 🩹 Fixes

- update nrwl monorepo to v17.1.2 ([#1617](https://github.com/angular-eslint/angular-eslint/pull/1617))
- update dependency @angular/compiler to v17.0.2 ([#1607](https://github.com/angular-eslint/angular-eslint/pull/1607))
- update typescript-eslint packages to v6.11.0 ([#1612](https://github.com/angular-eslint/angular-eslint/pull/1612))
- **eslint-plugin-template:** [attributes-order] fixes for structural directives and i18n ordering ([#1602](https://github.com/angular-eslint/angular-eslint/pull/1602))

### ❤️ Thank You

- Adrian Baran @abaran30
- Daniel Kimmich @json-derulo
- Phil McCloghry-Laing @pmccloghrylaing

# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [17.0.1](https://github.com/angular-eslint/angular-eslint/compare/v17.0.0...v17.0.1) (2023-11-09)

### Bug Fixes

- **parser:** do not error on [@defer](https://github.com/defer) usage in Angular 17 ([#1604](https://github.com/angular-eslint/angular-eslint/issues/1604)) ([df5419f](https://github.com/angular-eslint/angular-eslint/commit/df5419faf10dcf2ecd8e70a19349a1ca9859fb2b))
- update dependency @angular/compiler to v17.0.1 ([#1601](https://github.com/angular-eslint/angular-eslint/issues/1601)) ([237a969](https://github.com/angular-eslint/angular-eslint/commit/237a96905d586a25c7b51c03253ef7d8ab932959))

# [17.0.0](https://github.com/angular-eslint/angular-eslint/compare/v16.3.1...v17.0.0) (2023-11-08)

As always we recommend that you update your existing workspaces by using `ng update` as we provide some helpful schematics to help migrate your workspaces to the latest and greatest. Running the following will update Angular, the Angular CLI and angular-eslint together:

```sh
ng update @angular/core @angular/cli @angular-eslint/schematics
```

### Bug Fixes

- no declarations for eslint plugins ([2498238](https://github.com/angular-eslint/angular-eslint/commit/2498238ac64caaa539ac9d165157c6c4c937e747))

### Features

- **eslint-plugin-template:** [prefer-self-closing-tags] consider ng-content and ng-template elements ([#1573](https://github.com/angular-eslint/angular-eslint/issues/1573)) ([8e97d20](https://github.com/angular-eslint/angular-eslint/commit/8e97d20752669c2afa7b2ae456d16a96aabd8a80))

### BREAKING CHANGES

- As always, the major version primarily communicates the alignment with Angular's major version. Only Angular 17 is supported by angular-eslint 17.
- Your Node version must now be 18.13.0 or higher. Node 16 support has been dropped in alignment with Angular 17, as Node 16 is EOL.
- typescript-eslint v6 is now used by angular-eslint, and we will migrate existing workspaces when you use `ng update`. You may notice that some rule reports or configs have changed as a result, and we will not be able to automatically migrate all differences. Please see the typescript-eslint blog post about v6 for full information about the changes: https://typescript-eslint.io/blog/announcing-typescript-eslint-v6

## [16.3.1](https://github.com/angular-eslint/angular-eslint/compare/v16.3.0...v16.3.1) (2023-11-08)

**Note:** Version bump only for package @angular-eslint/angular-eslint

# [16.3.0](https://github.com/angular-eslint/angular-eslint/compare/v16.2.0...v16.3.0) (2023-11-08)

### Bug Fixes

- generate type declarations for published packages ([#1586](https://github.com/angular-eslint/angular-eslint/issues/1586)) ([ba5740b](https://github.com/angular-eslint/angular-eslint/commit/ba5740bc76c994d1fe35be7c1c7fee3ced647aff))
- update dependency @angular/compiler to v16.2.12 ([#1571](https://github.com/angular-eslint/angular-eslint/issues/1571)) ([1e0704f](https://github.com/angular-eslint/angular-eslint/commit/1e0704f995138badeb32f80709a783420c3873be))
- update dependency @angular/compiler to v16.2.9 ([#1535](https://github.com/angular-eslint/angular-eslint/issues/1535)) ([4532eec](https://github.com/angular-eslint/angular-eslint/commit/4532eecfa05abc984d7cd5d727ab89e540d85276))
- update dependency axobject-query to v4 ([#1581](https://github.com/angular-eslint/angular-eslint/issues/1581)) ([0b6cd1a](https://github.com/angular-eslint/angular-eslint/commit/0b6cd1a2f05e4407e7422e337cc45234dd1d6209))
- update dependency eslint to v8.50.0 ([#1538](https://github.com/angular-eslint/angular-eslint/issues/1538)) ([edfb9f7](https://github.com/angular-eslint/angular-eslint/commit/edfb9f76cde41a955fbe0a7ca40ec64b18303a62))
- update dependency eslint to v8.51.0 ([#1556](https://github.com/angular-eslint/angular-eslint/issues/1556)) ([dca9e5f](https://github.com/angular-eslint/angular-eslint/commit/dca9e5fd8293517f3a3ab667df2260e58e128d87))
- update to @angular/cli v16.2.10 ([#1593](https://github.com/angular-eslint/angular-eslint/issues/1593)) ([a49fc81](https://github.com/angular-eslint/angular-eslint/commit/a49fc81b7e21bd2f6500041e7b6a639b6240d8a3))

### Features

- **eslint-plugin-template:** allow `alias` option in [use-track-by-function] ([#1497](https://github.com/angular-eslint/angular-eslint/issues/1497)) ([354d394](https://github.com/angular-eslint/angular-eslint/commit/354d394d2ea866b4f21cbbad84d84b2e102066f5))

# [16.2.0](https://github.com/angular-eslint/angular-eslint/compare/v16.1.2...v16.2.0) (2023-09-17)

### Bug Fixes

- **eslint-plugin-template:** [prefer-self-closing-tags] improve code style of fixer result ([#1520](https://github.com/angular-eslint/angular-eslint/issues/1520)) ([6a86f19](https://github.com/angular-eslint/angular-eslint/commit/6a86f1903dc91cc8c46b910b22c89c66cae7e416))
- **eslint-plugin-template:** fix fixer of inline templates ([#1472](https://github.com/angular-eslint/angular-eslint/issues/1472)) ([470e12b](https://github.com/angular-eslint/angular-eslint/commit/470e12b5b482857735e2140e3524a5726d4fc6a8))
- **eslint-plugin:** [use-component-selector] applies to template literals ([#1468](https://github.com/angular-eslint/angular-eslint/issues/1468)) ([cbe60d3](https://github.com/angular-eslint/angular-eslint/commit/cbe60d3acd0dafe4256c56fa0147e377ef5e6471))
- update dependency @angular/compiler to v16.2.5 ([#1517](https://github.com/angular-eslint/angular-eslint/issues/1517)) ([fcfe7cc](https://github.com/angular-eslint/angular-eslint/commit/fcfe7ccae975eb67f1dec256c2073bb5a2930740))
- update dependency axobject-query to v3.2.1 ([#1524](https://github.com/angular-eslint/angular-eslint/issues/1524)) ([bb171d4](https://github.com/angular-eslint/angular-eslint/commit/bb171d489a099af8109464e8efeb08273d8a1dbd))
- update dependency eslint to v8.49.0 ([#1511](https://github.com/angular-eslint/angular-eslint/issues/1511)) ([abeb9f5](https://github.com/angular-eslint/angular-eslint/commit/abeb9f5b0c8d751689ec28bb10799ad27177b085))

### Features

- **eslint-plugin-template:** [prefer-ngsrc] add rule ([#1477](https://github.com/angular-eslint/angular-eslint/issues/1477)) ([0cfbc80](https://github.com/angular-eslint/angular-eslint/commit/0cfbc8096185a3851ca30d2f48cd939f027b1774))
- **eslint-plugin:** [sort-lifecycle-methods] add rule ([#1320](https://github.com/angular-eslint/angular-eslint/issues/1320)) ([47f7975](https://github.com/angular-eslint/angular-eslint/commit/47f7975aefb18e81aac5919f6586054d65b84f6f))

## [16.1.2](https://github.com/angular-eslint/angular-eslint/compare/v16.1.1...v16.1.2) (2023-09-04)

### Bug Fixes

- **angular-eslint:** ignore hostDirectives for no-output-rename and no-outputs-metadata-property ([#1466](https://github.com/angular-eslint/angular-eslint/issues/1466)) ([208bf25](https://github.com/angular-eslint/angular-eslint/commit/208bf25ec3662a1d6fdcaa32a27a9015ddf5e9ce))
- update dependency @angular/compiler to v16.2.3 ([#1458](https://github.com/angular-eslint/angular-eslint/issues/1458)) ([2b895a8](https://github.com/angular-eslint/angular-eslint/commit/2b895a8b45dfc16a8d03e149c47ef1c47c414e2e))

## [16.1.1](https://github.com/angular-eslint/angular-eslint/compare/v16.1.0...v16.1.1) (2023-08-20)

### Bug Fixes

- **eslint-plugin-template:** [attributes-order] Handle explicit ng-template usage ([#1465](https://github.com/angular-eslint/angular-eslint/issues/1465)) ([7d1f592](https://github.com/angular-eslint/angular-eslint/commit/7d1f5926fdad1adddc6f060d5bb3053562d0903f))
- **eslint-plugin-template:** update links to Angular i18n docs ([#1476](https://github.com/angular-eslint/angular-eslint/issues/1476)) ([9633058](https://github.com/angular-eslint/angular-eslint/commit/9633058f014842b66e7ff9d81f90520ce7628a8a))
- **eslint-plugin:** export require-localize-metadata rule ([#1469](https://github.com/angular-eslint/angular-eslint/issues/1469)) ([e3dc936](https://github.com/angular-eslint/angular-eslint/commit/e3dc9366a8f0c56c7637228e340d2b51c8297448))
- update dependency eslint to v8.45.0 ([#1461](https://github.com/angular-eslint/angular-eslint/issues/1461)) ([9c95032](https://github.com/angular-eslint/angular-eslint/commit/9c95032b63fcc75a0c7777a62583885b8c8ad119))
- update dependency eslint to v8.47.0 ([#1489](https://github.com/angular-eslint/angular-eslint/issues/1489)) ([047338a](https://github.com/angular-eslint/angular-eslint/commit/047338af94ff36c4fce69bb0c44b660d89c40377))
- update dependency eslint-scope to v7.2.2 ([#1460](https://github.com/angular-eslint/angular-eslint/issues/1460)) ([0bb6dca](https://github.com/angular-eslint/angular-eslint/commit/0bb6dca5f96a80e56c7fdffc2fab310105e6f081))

# [16.1.0](https://github.com/angular-eslint/angular-eslint/compare/v16.0.3...v16.1.0) (2023-07-12)

### Bug Fixes

- **eslint-plugin-template:** [attributes-order] fixes for structural directives and "dotted" names ([#1448](https://github.com/angular-eslint/angular-eslint/issues/1448)) ([90c0e91](https://github.com/angular-eslint/angular-eslint/commit/90c0e916654297b29cabf8289b1811ed307018ab))
- **eslint-plugin:** [valid-aria] tristate "mixed" value not handled ([#1398](https://github.com/angular-eslint/angular-eslint/issues/1398)) ([e7c762a](https://github.com/angular-eslint/angular-eslint/commit/e7c762a33177fd915f5c3c9cb3a36292ba126e61))
- update dependency @angular/compiler to v16.1.2 ([#1411](https://github.com/angular-eslint/angular-eslint/issues/1411)) ([cd1622e](https://github.com/angular-eslint/angular-eslint/commit/cd1622e725b0771584878e5ad18a41e02ea78671))
- update dependency @angular/compiler to v16.1.4 ([#1439](https://github.com/angular-eslint/angular-eslint/issues/1439)) ([a239094](https://github.com/angular-eslint/angular-eslint/commit/a239094777927046a6c5822611c5e63ebeb314db))
- update dependency aria-query to v5.3.0 ([#1441](https://github.com/angular-eslint/angular-eslint/issues/1441)) ([4b3a9dd](https://github.com/angular-eslint/angular-eslint/commit/4b3a9dd3e1b9b4ce868b7c9810fa53e834f0acf6))
- update dependency eslint to v8.41.0 ([#1394](https://github.com/angular-eslint/angular-eslint/issues/1394)) ([02b34fb](https://github.com/angular-eslint/angular-eslint/commit/02b34fb2dd953c6956e4111d3e1c56016e71169a))
- update dependency eslint to v8.44.0 ([#1415](https://github.com/angular-eslint/angular-eslint/issues/1415)) ([8735f7b](https://github.com/angular-eslint/angular-eslint/commit/8735f7b0e0ceef55b89f593e0d21becbff456c49))
- update nrwl monorepo to v16.5.1 ([#1443](https://github.com/angular-eslint/angular-eslint/issues/1443)) ([15bff48](https://github.com/angular-eslint/angular-eslint/commit/15bff489485d91a936867193e7c7bba3fb9e3a76))
- update typescript-eslint packages to v5.59.8 ([#1393](https://github.com/angular-eslint/angular-eslint/issues/1393)) ([5b0e87e](https://github.com/angular-eslint/angular-eslint/commit/5b0e87e47756685e2b71fb29d4657cbe715496b6))
- update typescript-eslint packages to v5.59.9 ([#1420](https://github.com/angular-eslint/angular-eslint/issues/1420)) ([fdd817f](https://github.com/angular-eslint/angular-eslint/commit/fdd817f706031826c921013f750331b3342053ed))
- update typescript-eslint packages to v5.62.0 ([#1444](https://github.com/angular-eslint/angular-eslint/issues/1444)) ([4affbf4](https://github.com/angular-eslint/angular-eslint/commit/4affbf421f92528b5616c2b3cd60373b136374c7))

### Features

- **eslint-plugin-template:** [no-duplicate-attributes] add allowStylePrecedenceDuplicates option ([#1407](https://github.com/angular-eslint/angular-eslint/issues/1407)) ([6f69af8](https://github.com/angular-eslint/angular-eslint/commit/6f69af8fd39b130f15453c46b1a9688360566c8b))
- **eslint-plugin-template:** [self-closing-tags] add rule ([#1322](https://github.com/angular-eslint/angular-eslint/issues/1322)) ([6d26c59](https://github.com/angular-eslint/angular-eslint/commit/6d26c590e4b15e0b28a6ff7467560537e2b9b92d))
- **eslint-plugin:** add prefer-standalone-component rule ([#1317](https://github.com/angular-eslint/angular-eslint/issues/1317)) ([94e4d4e](https://github.com/angular-eslint/angular-eslint/commit/94e4d4e88f91d262baed21c42a52ad0c823970fa))

## [16.0.3](https://github.com/angular-eslint/angular-eslint/compare/v16.0.2...v16.0.3) (2023-05-29)

### Bug Fixes

- update dependency @angular/compiler to v16.0.3 ([#1378](https://github.com/angular-eslint/angular-eslint/issues/1378)) ([1bc04bf](https://github.com/angular-eslint/angular-eslint/commit/1bc04bf887267d1d6956009f970fb5ee996c069a))
- update dependency eslint-scope to v7.2.0 ([#1373](https://github.com/angular-eslint/angular-eslint/issues/1373)) ([ccbb170](https://github.com/angular-eslint/angular-eslint/commit/ccbb1707a28e65f791b2951830a54455de5dfc56))
- update nrwl monorepo to v16.2.2 ([#1391](https://github.com/angular-eslint/angular-eslint/issues/1391)) ([9f140e6](https://github.com/angular-eslint/angular-eslint/commit/9f140e6dd6845f403ffeb3b2437bdbcd36fb7ec0))
- update typescript-eslint packages to v5.59.7 ([#1392](https://github.com/angular-eslint/angular-eslint/issues/1392)) ([cf40e34](https://github.com/angular-eslint/angular-eslint/commit/cf40e349943ec8acf97515dec344099a24f9c2c5))

## [16.0.2](https://github.com/angular-eslint/angular-eslint/compare/v16.0.1...v16.0.2) (2023-05-17)

### Bug Fixes

- update dependency eslint to v8.40.0 ([#1341](https://github.com/angular-eslint/angular-eslint/issues/1341)) ([44f4233](https://github.com/angular-eslint/angular-eslint/commit/44f4233962d6ae8846556af829d470dff038eed6))
- update nrwl monorepo to v16.1.3 ([#1371](https://github.com/angular-eslint/angular-eslint/issues/1371)) ([323d2c9](https://github.com/angular-eslint/angular-eslint/commit/323d2c94d4b4f88159a7b9fc448118ad6437cc95))

## [16.0.1](https://github.com/angular-eslint/angular-eslint/compare/v16.0.0...v16.0.1) (2023-05-03)

### Bug Fixes

- **schematics:** ensure placeholder schema for convert-tslint-to-eslint is copied to dist ([3c6f377](https://github.com/angular-eslint/angular-eslint/commit/3c6f3775fa305a6826584bc11fe3df5f45d07136))

# [16.0.0](https://github.com/angular-eslint/angular-eslint/compare/v16.0.0-alpha.1...v16.0.0) (2023-05-03)

As always we recommend that you update your existing workspaces by using `ng update` as we provide some helpful schematics to help migrate your workspaces to the latest and greatest. Running the following will update Angular, the Angular CLI and angular-eslint together:

```sh
ng update @angular/core @angular/cli @angular-eslint/schematics
```

### Features

- **eslint-plugin-template:** All accessibility rules are now grouped together and exposed via a new `@angular-eslint/template/accessibility` config. See the main README.md for an example of it in action. Our schematics will explicitly add it for you in new configs, but you are free to remove it if you wish (also note the BREAKING CHANGE regarding accessibility rule names below)
- **builder:** support `reportUnusedDisableDirectives` option
- **builder:** respect using `eslint.config.js` (a.k.a Flat Config) if it is already present. Our schematics will only be updated to generate Flat Config once it is the default way of configuring ESLint later in the year.
- bump `eslint` and all `@typescript-eslint` packages to the latest (handled for you automatically by our `ng update` schematic)

### BREAKING CHANGES

- As always, the major version primarily communicates the alignment with Angular's major version. Only Angular 16 is supported by angular-eslint 16.
- Your Node version must now be 16.13.0 or higher. Node 14 support has been dropped in alignment with Angular 16, as Node 14 is EOL.
- **eslint-plugin:** The legacy `base`, `recommended--extra`, `ng-cli-compat` and `ng-cli-compat--formatting` configs have been removed. See the updated guide on migrating from TSLint for more information: [./docs/MIGRATING_FROM_TSLINT.md](./docs/MIGRATING_FROM_TSLINT.md)
- **eslint-plugin-template:** The legacy `base` config has been removed. See the updated guide on migrating from TSLint for more information: [./docs/MIGRATING_FROM_TSLINT.md](./docs/MIGRATING_FROM_TSLINT.md)
- **schematics:** The legacy `convert-tslint-to-eslint` schematic has been removed. See the updated guide on migrating from TSLint for more information: [./docs/MIGRATING_FROM_TSLINT.md](./docs/MIGRATING_FROM_TSLINT.md)
- **eslint-plugin-template:** The deprecated `accessibility-label-for` rule has been removed. `label-has-associated-control` should be used instead. An automated migration was provided when `label-has-associated-control` was first added, so hopefully this should not impact too many folks.
- **eslint-plugin-template:** Previously some, but not all, accessibility related rules had a prefix of `accessibility-` in their name. This is inconsistent with all other rules which do not attempt to communicate _why_ they exist in their names. Therefore that naming prefix has been removed from all rules for consistency. The accessibility related rules can easily be identified from the new `@angular-eslint/template/accessibility` shared config. See the main README.md for an example of it in action.

## [15.2.1](https://github.com/angular-eslint/angular-eslint/compare/v15.2.0...v15.2.1) (2023-02-10)

### Bug Fixes

- **eslint-plugin-template:** [i18n] handle ng-template properly ([#1257](https://github.com/angular-eslint/angular-eslint/issues/1257)) ([7b0877d](https://github.com/angular-eslint/angular-eslint/commit/7b0877dbaceefb60f933895034bad06e995b867e))
- update dependency @angular/compiler to v15.1.4 ([#1282](https://github.com/angular-eslint/angular-eslint/issues/1282)) ([d1b3d59](https://github.com/angular-eslint/angular-eslint/commit/d1b3d590679a1ad76c4a469fb5d1f82c5a5b1794))
- update dependency eslint to v8.32.0 ([#1276](https://github.com/angular-eslint/angular-eslint/issues/1276)) ([15d2e23](https://github.com/angular-eslint/angular-eslint/commit/15d2e23a963012a7d59d26d39889cb030f626d6a))
- update dependency eslint to v8.33.0 ([#1292](https://github.com/angular-eslint/angular-eslint/issues/1292)) ([bd82b42](https://github.com/angular-eslint/angular-eslint/commit/bd82b42792d7979734f4e3252ea702a78f752bc9))
- update typescript-eslint packages to v5.48.2 ([#1278](https://github.com/angular-eslint/angular-eslint/issues/1278)) ([69d56a7](https://github.com/angular-eslint/angular-eslint/commit/69d56a7dfac576bff136329ce46917a8257a6aab))

# [15.2.0](https://github.com/angular-eslint/angular-eslint/compare/v15.1.0...v15.2.0) (2023-01-14)

### Bug Fixes

- **eslint-plugin:** [component-selector] enhance check for prefix and kebab-case ([#1250](https://github.com/angular-eslint/angular-eslint/issues/1250)) ([16827e4](https://github.com/angular-eslint/angular-eslint/commit/16827e4cfb203de588a4a0b7adf0eadc56542b38))
- **eslint-plugin:** [no-inputs-metadata-property] do not report on directive composition API ([#1248](https://github.com/angular-eslint/angular-eslint/issues/1248)) ([539cf9f](https://github.com/angular-eslint/angular-eslint/commit/539cf9f0cd33eae888cd27087ec9c22379161c93))
- update dependency @angular/compiler to v15.0.2 ([#1245](https://github.com/angular-eslint/angular-eslint/issues/1245)) ([061601f](https://github.com/angular-eslint/angular-eslint/commit/061601fea0c5592592c9e27b0aaeb4a0eadf1419))
- update dependency @angular/compiler to v15.1.0 ([#1252](https://github.com/angular-eslint/angular-eslint/issues/1252)) ([4295c59](https://github.com/angular-eslint/angular-eslint/commit/4295c595c452a48d56caa4571b6964e87ea60fc1))
- update dependency eslint to v8.29.0 ([#1246](https://github.com/angular-eslint/angular-eslint/issues/1246)) ([10c14d2](https://github.com/angular-eslint/angular-eslint/commit/10c14d2e1aaf8185258969226e006a32b3731219))
- update dependency eslint to v8.31.0 ([#1262](https://github.com/angular-eslint/angular-eslint/issues/1262)) ([db89c85](https://github.com/angular-eslint/angular-eslint/commit/db89c85956b583c3f865c8ca8bcd4622b1c2925a))
- update dependency ignore to v5.2.1 ([#1237](https://github.com/angular-eslint/angular-eslint/issues/1237)) ([609e06b](https://github.com/angular-eslint/angular-eslint/commit/609e06b9258c284729a2ff6515e27b3bc9b433a8))
- update dependency ignore to v5.2.4 ([#1263](https://github.com/angular-eslint/angular-eslint/issues/1263)) ([a220e0c](https://github.com/angular-eslint/angular-eslint/commit/a220e0ce051d8b07157e5559a891810a414d7e66))
- update typescript-eslint packages to v5.45.1 ([#1239](https://github.com/angular-eslint/angular-eslint/issues/1239)) ([abb7f79](https://github.com/angular-eslint/angular-eslint/commit/abb7f794b685a57ce696db9624a2ce66f81c6b4b))
- update typescript-eslint packages to v5.48.1 ([#1255](https://github.com/angular-eslint/angular-eslint/issues/1255)) ([11151d1](https://github.com/angular-eslint/angular-eslint/commit/11151d17dc82d04276169e3c898e2aa7f11136b1))
- **utils:** use test case filename when specified ([#1259](https://github.com/angular-eslint/angular-eslint/issues/1259)) ([37bfd14](https://github.com/angular-eslint/angular-eslint/commit/37bfd14cfa14e213c13bad5fe87c057487bac6c3))
- **utils:** use tsconfigRootDir as root dir when specified ([#1260](https://github.com/angular-eslint/angular-eslint/issues/1260)) ([19fe26c](https://github.com/angular-eslint/angular-eslint/commit/19fe26cbad8047567f939e7a6f8b910b42439f54))

### Features

- **eslint-plugin-template:** [i18n] option to require i18n metadata meaning ([#1234](https://github.com/angular-eslint/angular-eslint/issues/1234)) ([4ef0290](https://github.com/angular-eslint/angular-eslint/commit/4ef02902f5216ee8a6fab1faf1798ac559341ffc))
- **eslint-plugin-template:** [no-interpolation-in-attributes] new rule added ([#1242](https://github.com/angular-eslint/angular-eslint/issues/1242)) ([977cb3a](https://github.com/angular-eslint/angular-eslint/commit/977cb3ad623c4d70a0e83b04c0cbe409edf88515))
- **eslint-plugin:** [require-localize-metadata] option to require meaning ([#1235](https://github.com/angular-eslint/angular-eslint/issues/1235)) ([b870123](https://github.com/angular-eslint/angular-eslint/commit/b8701230c14798705be7624af9a03e73792c6f2c))

# [15.1.0](https://github.com/angular-eslint/angular-eslint/compare/v15.0.0...v15.1.0) (2022-11-24)

### Bug Fixes

- **eslint-plugin-template:** [accessibility-valid-aria] use Number() to parse numeric values ([#1218](https://github.com/angular-eslint/angular-eslint/issues/1218)) ([6fe40d6](https://github.com/angular-eslint/angular-eslint/commit/6fe40d672197532176686f1c5c8ab080713334bf))
- **eslint-plugin-template:** [i18n] allow more attributes by default ([#1220](https://github.com/angular-eslint/angular-eslint/issues/1220)) ([4232b1c](https://github.com/angular-eslint/angular-eslint/commit/4232b1c1892189623ead2ccd68fcb6d179186e92))
- **eslint-plugin:** [no-input-rename] do not report on directive composition API ([#1231](https://github.com/angular-eslint/angular-eslint/issues/1231)) ([119fba7](https://github.com/angular-eslint/angular-eslint/commit/119fba7142845f53ccbbad106f5b572b0d13bc9e))
- update dependency @angular/compiler to v15.0.1 ([#1223](https://github.com/angular-eslint/angular-eslint/issues/1223)) ([7b7bd76](https://github.com/angular-eslint/angular-eslint/commit/7b7bd769f0239e43c7c53e714196e02b80453916))
- update typescript-eslint packages to v5.44.0 ([#1222](https://github.com/angular-eslint/angular-eslint/issues/1222)) ([5750e3a](https://github.com/angular-eslint/angular-eslint/commit/5750e3af9c7d9b91f5f4cd2fb524625b215bf4b0))

### Features

- **eslint-plugin-template:** [no-call-expression] add allowList option ([#1217](https://github.com/angular-eslint/angular-eslint/issues/1217)) ([a69c809](https://github.com/angular-eslint/angular-eslint/commit/a69c809cd31f142d2f5aff1c34afeb6e4a607a9c))

# [15.0.0](https://github.com/angular-eslint/angular-eslint/compare/v15.0.0-alpha.5...v15.0.0) (2022-11-20)

As always we recommend that you update your existing workspaces by using `ng update` as we provide some helpful schematics to help migrate your workspaces to the latest and greatest. Running the following will update Angular, the Angular CLI and angular-eslint together:

```sh
ng update @angular/core @angular/cli @angular-eslint/schematics
```

### Bug Fixes

- **schematics:** ensure scoped project names have correct eslint extends ([7b3f736](https://github.com/angular-eslint/angular-eslint/commit/7b3f73670e2935faf7c8fc961d7f8fa50a91208e))

### Features

- bump minimum supported eslint version to 7.20.0 ([56ad69f](https://github.com/angular-eslint/angular-eslint/commit/56ad69f92e5b5789f01d19d0c65e46f4573d9493)), closes [#662](https://github.com/angular-eslint/angular-eslint/issues/662)
- **eslint-plugin:** remove no-conflicting-lifecycle from recommended config ([19dd177](https://github.com/angular-eslint/angular-eslint/commit/19dd177137ceec8b7ab021246a26095f01f25366)), closes [#502](https://github.com/angular-eslint/angular-eslint/issues/502)
- fast linting by default, set eslint and typescript-eslint recommended ([#1212](https://github.com/angular-eslint/angular-eslint/issues/1212)) ([1a53ef9](https://github.com/angular-eslint/angular-eslint/commit/1a53ef985fc1ce6dc7b5e9a797c78b46c48a10ac)), closes [#1174](https://github.com/angular-eslint/angular-eslint/issues/1174)
- **schematics:** ng update migration to preserve v14 parserOptions.project for existing workspaces ([1d45914](https://github.com/angular-eslint/angular-eslint/commit/1d45914097a57bf7fdfc5acc9fab0a66cc01898c))

### BREAKING CHANGES

- Your installed version of ESLint must be version 7.20.0 or later (naturally we recommend the latest v8 of ESLint if possible)
- **eslint-plugin:** no-conflicting-lifecycle is no longer included as part of the recommended config and if you wish to continue using it you will need to enable it yourself in your eslint config rules
- New projects will not include `parserOptions.project` configuration in `.eslintrc.json` files by default, see the new guide here [./docs/RULES_REQUIRING_TYPE_INFORMATION.md](./docs/RULES_REQUIRING_TYPE_INFORMATION.md)

# [14.4.0](https://github.com/angular-eslint/angular-eslint/compare/v14.3.1...v14.4.0) (2022-11-20)

### Features

- **utils:** export template parser services ([#1211](https://github.com/angular-eslint/angular-eslint/issues/1211)) ([34a62d2](https://github.com/angular-eslint/angular-eslint/commit/34a62d25f02716eb0d55f095ce732876a4f7590b))

## [14.3.1](https://github.com/angular-eslint/angular-eslint/compare/v14.3.0...v14.3.1) (2022-11-20)

### Bug Fixes

- **no-input-rename:** allow input aliases that match the directive name applied to an element ([#1207](https://github.com/angular-eslint/angular-eslint/issues/1207)) ([aff3344](https://github.com/angular-eslint/angular-eslint/commit/aff33442e0c35440827f144916e07d180965d0e9))
- update dependency eslint to v8.28.0 ([#1210](https://github.com/angular-eslint/angular-eslint/issues/1210)) ([c671e74](https://github.com/angular-eslint/angular-eslint/commit/c671e7484d4dad81c345d176cfedf01d45b5f820))

# [14.3.0](https://github.com/angular-eslint/angular-eslint/compare/v14.2.0...v14.3.0) (2022-11-17)

### Bug Fixes

- update dependency @angular/compiler to v14.2.11 ([#1202](https://github.com/angular-eslint/angular-eslint/issues/1202)) ([6c1eb81](https://github.com/angular-eslint/angular-eslint/commit/6c1eb81522f199ce101516bc670c975dd2a3cc3a))

### Features

- **eslint-plugin-template:** [accessibility-elements-content] add allowList option ([#1201](https://github.com/angular-eslint/angular-eslint/issues/1201)) ([3877f43](https://github.com/angular-eslint/angular-eslint/commit/3877f4350213d934dc3eac440a2dc6168aeef558))
- **eslint-plugin-template:** [no-inline-styles] add rule ([#1162](https://github.com/angular-eslint/angular-eslint/issues/1162)) ([7e1aadf](https://github.com/angular-eslint/angular-eslint/commit/7e1aadf47913124c09a000e231748c3ea981750b))

# [14.2.0](https://github.com/angular-eslint/angular-eslint/compare/v14.1.2...v14.2.0) (2022-11-15)

### Bug Fixes

- update dependency @angular/compiler to v14.2.10 ([#1165](https://github.com/angular-eslint/angular-eslint/issues/1165)) ([bb4bfe5](https://github.com/angular-eslint/angular-eslint/commit/bb4bfe5482f775be41d93e9ae0b130ee372ad413))
- update dependency @angular/compiler to v14.2.3 ([#1143](https://github.com/angular-eslint/angular-eslint/issues/1143)) ([4eb3e74](https://github.com/angular-eslint/angular-eslint/commit/4eb3e74a85bfa3e8beb9e7ee85c2b3340613375c))
- update dependency aria-query to v5.1.3 ([#1183](https://github.com/angular-eslint/angular-eslint/issues/1183)) ([7c5b299](https://github.com/angular-eslint/angular-eslint/commit/7c5b2993dc9fcc235b869bab63d28766637b3147))
- update dependency axobject-query to v3.1.1 ([#1184](https://github.com/angular-eslint/angular-eslint/issues/1184)) ([dcfd43d](https://github.com/angular-eslint/angular-eslint/commit/dcfd43dfc9ffb4acbe127911ae8e9b1de6210839))
- update dependency eslint to v8.27.0 ([#1189](https://github.com/angular-eslint/angular-eslint/issues/1189)) ([d2ae95a](https://github.com/angular-eslint/angular-eslint/commit/d2ae95a4597ac09103103d7783d4e840d521be3c))
- update dependency eslint-scope to v7 ([#1156](https://github.com/angular-eslint/angular-eslint/issues/1156)) ([05bd9e6](https://github.com/angular-eslint/angular-eslint/commit/05bd9e65f1db3488edb4a359d70307884822ffad))
- update typescript-eslint packages to v5.38.1 ([#1152](https://github.com/angular-eslint/angular-eslint/issues/1152)) ([8f6d0ef](https://github.com/angular-eslint/angular-eslint/commit/8f6d0ef1048eac4113cb3efe53ed466b50aff056))
- update typescript-eslint packages to v5.43.0 ([#1190](https://github.com/angular-eslint/angular-eslint/issues/1190)) ([2a4716a](https://github.com/angular-eslint/angular-eslint/commit/2a4716abd83230c2fe4c3ba377fc4fbe527d7b12))

### Features

- **eslint-plugin-template:** [accessibility-interactive-supports-focus] add rule ([#1134](https://github.com/angular-eslint/angular-eslint/issues/1134)) ([d99d8c1](https://github.com/angular-eslint/angular-eslint/commit/d99d8c1c23ece85c5ee37c3515912e90a335be46))
- **eslint-plugin-template:** [accessibility-role-has-required-aria] add rule ([#1100](https://github.com/angular-eslint/angular-eslint/issues/1100)) ([f684df0](https://github.com/angular-eslint/angular-eslint/commit/f684df040ebdf96b695f07f2e3fa6bfe2310c20e))
- **eslint-plugin-template:** [attributes-order] add rule with fixer ([#1066](https://github.com/angular-eslint/angular-eslint/issues/1066)) ([4c789c7](https://github.com/angular-eslint/angular-eslint/commit/4c789c7546c7306c1a010f78fac4582b0c6efdc0))
- **eslint-plugin-template:** [no-duplicate-attributes] Add option to ignore properties ([#1104](https://github.com/angular-eslint/angular-eslint/issues/1104)) ([018d390](https://github.com/angular-eslint/angular-eslint/commit/018d3906c2569df7dda01fd205e1138aec3f1d0c))
- update dependency eslint to v8.24.0 ([#1148](https://github.com/angular-eslint/angular-eslint/issues/1148)) ([5f30b2d](https://github.com/angular-eslint/angular-eslint/commit/5f30b2d1d930660a5b823e012737c280a668d308))
- update typescript-eslint packages to v5.38.0 ([#1140](https://github.com/angular-eslint/angular-eslint/issues/1140)) ([85b4b47](https://github.com/angular-eslint/angular-eslint/commit/85b4b47acea84ae8f633f348805e22aea36de113))

## [14.1.2](https://github.com/angular-eslint/angular-eslint/compare/v14.1.1...v14.1.2) (2022-09-21)

### Bug Fixes

- **builder:** remove nrwl/devkit from builder implementation ([#1142](https://github.com/angular-eslint/angular-eslint/issues/1142)) ([9d5a7fc](https://github.com/angular-eslint/angular-eslint/commit/9d5a7fc1860a598c62ec163b6363e9436afd81a7))

## [14.1.1](https://github.com/angular-eslint/angular-eslint/compare/v14.1.0...v14.1.1) (2022-09-18)

### Bug Fixes

- **eslint-plugin-template:** [click-events-have-key-events]: handle additional outputs ([#1101](https://github.com/angular-eslint/angular-eslint/issues/1101)) ([c608cdb](https://github.com/angular-eslint/angular-eslint/commit/c608cdbfabb81cfbf542a3c846711853cfcbbfbd))
- **eslint-plugin:** [sort-ngmodule-metadata-arrays]: add intl support ([#1099](https://github.com/angular-eslint/angular-eslint/issues/1099)) ([30d133b](https://github.com/angular-eslint/angular-eslint/commit/30d133bd232c1c9587b2af92d471c919ab02bb4d))

# [14.1.0](https://github.com/angular-eslint/angular-eslint/compare/v14.0.4...v14.1.0) (2022-09-18)

### Features

- update dependency eslint to v8.23.1 ([#1137](https://github.com/angular-eslint/angular-eslint/issues/1137)) ([9c9f28b](https://github.com/angular-eslint/angular-eslint/commit/9c9f28b48300ea4893bc0021cb48404acb75ee1b))
- update typescript-eslint packages to v5.37.0 ([#1138](https://github.com/angular-eslint/angular-eslint/issues/1138)) ([96435a8](https://github.com/angular-eslint/angular-eslint/commit/96435a881f40ca9a124c8f44009a6f656f31e1f2))

## [14.0.4](https://github.com/angular-eslint/angular-eslint/compare/v14.0.3...v14.0.4) (2022-09-08)

### Bug Fixes

- **schematics:** prefer sourceRoot if available for root project ([#1114](https://github.com/angular-eslint/angular-eslint/issues/1114)) ([36c62c3](https://github.com/angular-eslint/angular-eslint/commit/36c62c34098b4cf5b841e577038257b2110bf60a))
- support TS 4.8 with Angular 14.2, update dependencies ([#1123](https://github.com/angular-eslint/angular-eslint/issues/1123)) ([a780b59](https://github.com/angular-eslint/angular-eslint/commit/a780b592b42a61f149ae3d1d0f5c55808cb755df))

## [14.0.3](https://github.com/angular-eslint/angular-eslint/compare/v14.0.2...v14.0.3) (2022-08-23)

### Bug Fixes

- **builder:** ensure package works with Angular 14.1.3 ([#1112](https://github.com/angular-eslint/angular-eslint/issues/1112)) ([b00ef2e](https://github.com/angular-eslint/angular-eslint/commit/b00ef2e0de8d3b541dfa963c4c1901bfa380c4b3))

## [14.0.2](https://github.com/angular-eslint/angular-eslint/compare/v14.0.1...v14.0.2) (2022-07-09)

### Bug Fixes

- **builder:** add explicit dependency on nx ([#1088](https://github.com/angular-eslint/angular-eslint/issues/1088)) ([753a383](https://github.com/angular-eslint/angular-eslint/commit/753a3839a402c4a7f22f6de9ccfa84566c4b7572))

## [14.0.1](https://github.com/angular-eslint/angular-eslint/compare/v14.0.0...v14.0.1) (2022-07-08)

### Bug Fixes

- **builder:** update to latest @nrwl/devkit ([#1082](https://github.com/angular-eslint/angular-eslint/issues/1082)) ([cc00a21](https://github.com/angular-eslint/angular-eslint/commit/cc00a21d99e1e9e48431f066b2942473e99390ec))
- remaining references to master (now main) ([#1083](https://github.com/angular-eslint/angular-eslint/issues/1083)) ([8d36232](https://github.com/angular-eslint/angular-eslint/commit/8d36232435e5e09f870fc42c40327cedd703749f))

# [14.0.0](https://github.com/angular-eslint/angular-eslint/compare/v13.5.0...v14.0.0) (2022-06-23)

As always we recommend that you update your existing workspaces by using `ng update` as we provide some helpful schematics to help migrate your workspaces to the latest and greatest. Running the following will update Angular, the Angular CLI and angular-eslint together:

```sh
ng update @angular/core @angular/cli @angular-eslint/schematics
```

### BREAKING CHANGES

This is a major version bump and comes with some breaking changes, one of which might possibly impact your ESLint configuration if you are targeting inline HTML templates with a very specific glob pattern because the virtual filename has changed (read on to learn more).

- update Angular to v14
  - All packages now require the use of Angular CLI >= 14.0.0 < 15.0.0

- dropped support for Node 12 (in alignment with Angular's own version policy)

- extracted inline HTML templates now contain the original Component filename in their processed virtual filename
  - When ESLint runs on your Component files, if you are using the recommended configuration, it will invoke a processor we have set up to extract the inline HTML templates from your Component declarations. Behind the scenes we give these extracted templates virtual filenames ending in `.html` so that rules targeting HTML files can also target your inline templates.
  - **Before:** In v13 the filename looked like this: `inline-template-${++i}.component.html`, where `i` was an incrementing integer (in case for example you had multiple Component declarations in the same `.ts` file.
  - **Now**: In v14 the filename now looks like this `inline-template-${baseFilename}-${++i}.component.html`, where `i` has the same incrementing integer behavior as before, but we now include the base filename within the virtual filename.
    - E.g. if you have a test file in `projects/foo/src/app/app.spec.ts` which declares a Component with an inline template, the virtual filename generated behind the scene for that template will be `inline-template-app.spec.ts-1.component.html`.
    - This new behavior allows you to use ESLint overrides to apply different behavior to Component inline templates in different files.

### Features

- update eslint to `^8.18.0` (automatically migrated via `ng update`)
- update typescript-eslint to `^5.29.0` (automatically migrated via `ng update`)
- update deprecated `cli.defaultCollection` usage in `angular.json` to use `cli.schematicCollections` instead (automatically migrated via `ng update`)

# [13.5.0](https://github.com/angular-eslint/angular-eslint/compare/v13.4.0...v13.5.0) (2022-06-12)

### Features

- **eslint-plugin-template:** [button-has-type] add rule ([#928](https://github.com/angular-eslint/angular-eslint/issues/928)) ([f19bb30](https://github.com/angular-eslint/angular-eslint/commit/f19bb30bf875eacb3bd82709687e4f6ecd6abac7))

# [13.4.0](https://github.com/angular-eslint/angular-eslint/compare/v13.3.0...v13.4.0) (2022-06-11)

### Features

- update typescript-eslint packages to v5.27.1 ([#1022](https://github.com/angular-eslint/angular-eslint/issues/1022)) ([99e8d4a](https://github.com/angular-eslint/angular-eslint/commit/99e8d4a256b8d2d71ee9b809649cb0846fdadeb9))

# [13.3.0](https://github.com/angular-eslint/angular-eslint/compare/v13.2.1...v13.3.0) (2022-06-10)

### Bug Fixes

- **eslint-plugin-template:** [eqeqeq] update suggest message ([#1000](https://github.com/angular-eslint/angular-eslint/issues/1000)) ([821cb8e](https://github.com/angular-eslint/angular-eslint/commit/821cb8ec0f69beb0cc7d1fb60ad653a1c3c77152))
- **eslint-plugin:** [sort-ngmodule-metadata-arrays] do not sort deps property ([#1001](https://github.com/angular-eslint/angular-eslint/issues/1001)) ([e6d12f2](https://github.com/angular-eslint/angular-eslint/commit/e6d12f21f94aeda5667a32d580b002fc1597cff2))

### Features

- **eslint-plugin-template:** [i18n] add requireDescription option ([#988](https://github.com/angular-eslint/angular-eslint/issues/988)) ([8f55ba8](https://github.com/angular-eslint/angular-eslint/commit/8f55ba832dfe54a4b44334802c3691f839e3ce5d))
- update dependency eslint to v8.17.0 ([#979](https://github.com/angular-eslint/angular-eslint/issues/979)) ([7cabac0](https://github.com/angular-eslint/angular-eslint/commit/7cabac039b895316d6a363cd23765cf7311adf2c))

## [13.2.1](https://github.com/angular-eslint/angular-eslint/compare/v13.2.0...v13.2.1) (2022-04-14)

### Bug Fixes

- **eslint-plugin-template:** false positive conditional complexity in BoundAttribute > Interpolation ([#986](https://github.com/angular-eslint/angular-eslint/issues/986)) ([c3f3120](https://github.com/angular-eslint/angular-eslint/commit/c3f3120b57f7dfe7ff1ff3f3a8791b2cf988e905))
- **template-parser:** suppress parse errors by default, add suppressParseErrors parserOption ([#987](https://github.com/angular-eslint/angular-eslint/issues/987)) ([417bee6](https://github.com/angular-eslint/angular-eslint/commit/417bee66dbae5c55d29966de5ca6e86b52075cb8))

# [13.2.0](https://github.com/angular-eslint/angular-eslint/compare/v13.1.0...v13.2.0) (2022-04-03)

### Bug Fixes

- **schematics:** support more permutations of ng-add ([#970](https://github.com/angular-eslint/angular-eslint/issues/970)) ([0bf549b](https://github.com/angular-eslint/angular-eslint/commit/0bf549b758a6921ff602136d9872e10bb924baf3))

### Features

- **eslint-plugin-template:** add require-localize-metadata rule ([#844](https://github.com/angular-eslint/angular-eslint/issues/844)) ([ca1edf0](https://github.com/angular-eslint/angular-eslint/commit/ca1edf0434b497a7bb756789136499243cee8fe9))
- **parser:** propagate parse errors from angular compiler ([#969](https://github.com/angular-eslint/angular-eslint/issues/969)) ([ab9b496](https://github.com/angular-eslint/angular-eslint/commit/ab9b496095c7194d614394c04548f6848c0d6aff))

# [13.1.0](https://github.com/angular-eslint/angular-eslint/compare/v13.0.1...v13.1.0) (2022-02-13)

### Bug Fixes

- **eslint-plugin-template:** [i18n] do not throw when compiler returns null i18n description ([#892](https://github.com/angular-eslint/angular-eslint/issues/892)) ([d349149](https://github.com/angular-eslint/angular-eslint/commit/d3491492b925bd7855d86f7a1fd90297acaee743))
- rule docs links in create-eslint-rule utils ([#907](https://github.com/angular-eslint/angular-eslint/issues/907)) ([94f6e21](https://github.com/angular-eslint/angular-eslint/commit/94f6e2126088ac300e7a010a45e575cadd4d8e78))
- update dependency ignore to v5.2.0 ([#913](https://github.com/angular-eslint/angular-eslint/issues/913)) ([5480102](https://github.com/angular-eslint/angular-eslint/commit/54801025adcd31b721d293e58884b646de41e2b4))

### Features

- **eslint-plugin-template:** [i18n] add checkDuplicateId option ([#868](https://github.com/angular-eslint/angular-eslint/issues/868)) ([edaf46f](https://github.com/angular-eslint/angular-eslint/commit/edaf46f2f321b9d5a3ba148048b997366e79495d))
- update angular/compiler to v13.2.2 ([#834](https://github.com/angular-eslint/angular-eslint/issues/834)) ([9847978](https://github.com/angular-eslint/angular-eslint/commit/9847978778c3772425d727214f0600a04b6c234c))

## [13.0.1](https://github.com/angular-eslint/angular-eslint/compare/v13.0.0...v13.0.1) (2021-11-19)

### Bug Fixes

- **schematics:** auto update eslint-plugin-import as part of v13 ng update ([#836](https://github.com/angular-eslint/angular-eslint/issues/836)) ([705e83b](https://github.com/angular-eslint/angular-eslint/commit/705e83b6da8e3bf77bbf00305972024f9cffd11b))

# [13.0.0](https://github.com/angular-eslint/angular-eslint/compare/v12.7.0...v13.0.0) (2021-11-18)

Whilst this is a major release of the packages, in this case the major version change is primarily there to signify alignment with v13 of Angular.

You should look to migrate to v13 of all Angular packages, as well as v8 of `eslint` and v5 of `typescript-eslint`.

All of this will be handled for you automatically if you leverage the `ng update` schematics provided by `@angular-eslint`. You can simply include `@angular-eslint/schematics` in your `ng update` command alongside `@angular/cli` and `@angular/core`, for example:

```sh
npx ng update @angular/cli @angular/core @angular-eslint/schematics
```

### Features

- angular-eslint v13 ([#780](https://github.com/angular-eslint/angular-eslint/issues/780)) ([f7ce631](https://github.com/angular-eslint/angular-eslint/commit/f7ce631524dd7834a422a5ac93a4c0534f9f23fa))

# [12.7.0](https://github.com/angular-eslint/angular-eslint/compare/v12.6.1...v12.7.0) (2021-11-18)

### Bug Fixes

- update dependency ignore to v5.1.9 ([#784](https://github.com/angular-eslint/angular-eslint/issues/784)) ([e4574ce](https://github.com/angular-eslint/angular-eslint/commit/e4574ce21d9175f6fc5f27e03a0ca6f81b466a96))

### Features

- **builder:** expose nx executor without ng-compat layer ([#808](https://github.com/angular-eslint/angular-eslint/issues/808)) ([b2cd5d1](https://github.com/angular-eslint/angular-eslint/commit/b2cd5d1756ac466882b953b641fed59a3403421a))
- **i18n:** option to require description for i18n metadata ([#804](https://github.com/angular-eslint/angular-eslint/issues/804)) ([7d072e2](https://github.com/angular-eslint/angular-eslint/commit/7d072e2ec053f388adce00be54c75d8c76373699))
- **schematics:** add package group for ng update ([#807](https://github.com/angular-eslint/angular-eslint/issues/807)) ([ce2e47d](https://github.com/angular-eslint/angular-eslint/commit/ce2e47d50a4814f5cea3e075a0c5a3e8dbbfd44e))

## [12.6.1](https://github.com/angular-eslint/angular-eslint/compare/v12.6.0...v12.6.1) (2021-10-26)

### Bug Fixes

- pin dependencies ([#726](https://github.com/angular-eslint/angular-eslint/issues/726)) ([5c21189](https://github.com/angular-eslint/angular-eslint/commit/5c211898d7a678dbc08f9c9205828ed92b28808d))

# [12.6.0](https://github.com/angular-eslint/angular-eslint/compare/v12.5.0...v12.6.0) (2021-10-25)

### Bug Fixes

- **eslint-plugin:** [sort-ngmodule-metadata-arrays] remove the property restriction ([#694](https://github.com/angular-eslint/angular-eslint/issues/694)) ([440f6dc](https://github.com/angular-eslint/angular-eslint/commit/440f6dcd0d6b330d0af879df1acd306f931e2de1))
- **eslint-plugin:** [sort-ngmodule-metadata-arrays] report the correct node ([#693](https://github.com/angular-eslint/angular-eslint/issues/693)) ([886db08](https://github.com/angular-eslint/angular-eslint/commit/886db08eb0791330c999fdbf022f042613ac127c))
- **eslint-plugin:** more appropriate language for no-attribute-decorator ([#696](https://github.com/angular-eslint/angular-eslint/issues/696)) ([4dde82c](https://github.com/angular-eslint/angular-eslint/commit/4dde82cfeded9727341abea079399a7ef1b9dd9f))
- **eslint-plugin-template:** [i18n] ignore empty strings and non-texts within `BoundText` by default ([#683](https://github.com/angular-eslint/angular-eslint/issues/683)) ([4075643](https://github.com/angular-eslint/angular-eslint/commit/4075643f259c791f1995c207ca14c9c93c3098d6))

### Features

- **bundled-angular-compiler:** create own bundle for `@angular/compiler` ([#720](https://github.com/angular-eslint/angular-eslint/issues/720)) ([0c42299](https://github.com/angular-eslint/angular-eslint/commit/0c422993496bb2670fbd31f55a5fe829704f5112))

# [12.5.0](https://github.com/angular-eslint/angular-eslint/compare/v12.4.1...v12.5.0) (2021-09-20)

### Bug Fixes

- **eslint-plugin-template:** [mouse-events-have-key-events] ignore custom components ([#680](https://github.com/angular-eslint/angular-eslint/issues/680)) ([f65874b](https://github.com/angular-eslint/angular-eslint/commit/f65874b6b1fb012f1f8a1a564b6348cd7ae2117f))
- **eslint-plugin-template:** support escape chars in inline templates ([#691](https://github.com/angular-eslint/angular-eslint/issues/691)) ([8b89ec7](https://github.com/angular-eslint/angular-eslint/commit/8b89ec7ba1ebdd5a29914bac457387d4b65bd691))

### Features

- **utils:** publicly expose utils related to eslint-plugin ([#676](https://github.com/angular-eslint/angular-eslint/issues/676)) ([07711f1](https://github.com/angular-eslint/angular-eslint/commit/07711f14f497d01ab767089742d0b77fa25958c7))

## [12.4.1](https://github.com/angular-eslint/angular-eslint/compare/v12.4.0...v12.4.1) (2021-09-09)

### Bug Fixes

- **utils:** add missing filename option for invalid case utils ([#674](https://github.com/angular-eslint/angular-eslint/issues/674)) ([80b72b3](https://github.com/angular-eslint/angular-eslint/commit/80b72b32fc41f240cbf6962883f20ed4c0f37548))

# [12.4.0](https://github.com/angular-eslint/angular-eslint/compare/v12.3.1...v12.4.0) (2021-09-09)

### Bug Fixes

- **eslint-plugin:** [no-empty-lifecycle-method] incorrect suggestions and correct reports ([#606](https://github.com/angular-eslint/angular-eslint/issues/606)) ([a446e8f](https://github.com/angular-eslint/angular-eslint/commit/a446e8ff521725d354dc23242c4ad23bc52c9681))
- **eslint-plugin:** [sort-ngmodule-metadata-arrays] handle literal metadata and computed properties ([#667](https://github.com/angular-eslint/angular-eslint/issues/667)) ([f993069](https://github.com/angular-eslint/angular-eslint/commit/f99306977254e2894ad769448f0cbebd7665cbcd))
- **eslint-plugin:** properly handle computed literals for some rules ([#600](https://github.com/angular-eslint/angular-eslint/issues/600)) ([fbd6ff7](https://github.com/angular-eslint/angular-eslint/commit/fbd6ff7e5c5e4e249cbb5159c36cac3416e9ae3b))
- **eslint-plugin-template:** [i18n] fixes some incorrect reports ([#665](https://github.com/angular-eslint/angular-eslint/issues/665)) ([a011b9d](https://github.com/angular-eslint/angular-eslint/commit/a011b9d6711482f0713e30208d46b38ce266741d))
- **eslint-plugin-template:** [no-call-expression]: `FunctionCall`s not being reported ([#601](https://github.com/angular-eslint/angular-eslint/issues/601)) ([5552b13](https://github.com/angular-eslint/angular-eslint/commit/5552b13a87ff0a04ea92a12f54decfbb0c4f984e))
- **eslint-plugin-template:** include more checks for `isHiddenFromScreenReader` ([#545](https://github.com/angular-eslint/angular-eslint/issues/545)) ([db2bc05](https://github.com/angular-eslint/angular-eslint/commit/db2bc057458bf7080b7848934dd6a30582dced27))

### Features

- **eslint-plugin:** [prefer-on-push-component-change-detection] add suggestion ([#666](https://github.com/angular-eslint/angular-eslint/issues/666)) ([3723c4c](https://github.com/angular-eslint/angular-eslint/commit/3723c4ca591ba8b62b78717e683ee82e7a5a4b07))
- **eslint-plugin:** [use-injectable-provided-in] add suggestion ([#594](https://github.com/angular-eslint/angular-eslint/issues/594)) ([bdef8c7](https://github.com/angular-eslint/angular-eslint/commit/bdef8c77bcc72aa20c58c2c5c8fd0489675adcfd))
- **utils:** make package public ([#673](https://github.com/angular-eslint/angular-eslint/issues/673)) ([0386082](https://github.com/angular-eslint/angular-eslint/commit/0386082feea5291e7d745ce60a6ee29add486299))

## [12.3.1](https://github.com/angular-eslint/angular-eslint/compare/v12.3.0...v12.3.1) (2021-07-15)

### Bug Fixes

- **eslint-plugin:** handle literal `outputs` properly for [*-output-*] rules ([#595](https://github.com/angular-eslint/angular-eslint/issues/595)) ([8621a62](https://github.com/angular-eslint/angular-eslint/commit/8621a62a5360caac33fd87001e2928d7995a5a01))
- **template-parser:** correct typings for cjs ([#597](https://github.com/angular-eslint/angular-eslint/issues/597)) ([bb60224](https://github.com/angular-eslint/angular-eslint/commit/bb6022410139801dfee062b845c3a2d3f7b8a019))

# [12.3.0](https://github.com/angular-eslint/angular-eslint/compare/v12.2.2...v12.3.0) (2021-07-13)

### Bug Fixes

- **eslint-plugin:** [no-input-prefix] handle alias and `inputs` metadata property ([#582](https://github.com/angular-eslint/angular-eslint/issues/582)) ([675ee11](https://github.com/angular-eslint/angular-eslint/commit/675ee11f541e9e08c87df75a9004a12d0f0403bf))
- **eslint-plugin:** [no-input-rename] handle alias and `inputs` metadata property ([#583](https://github.com/angular-eslint/angular-eslint/issues/583)) ([2883e18](https://github.com/angular-eslint/angular-eslint/commit/2883e185abca4cfd2a7191f5c10742d521f48a89))
- **eslint-plugin:** [use-component-view-encapsulation] handle literal `encapsulation` properly ([#586](https://github.com/angular-eslint/angular-eslint/issues/586)) ([3a9b7f4](https://github.com/angular-eslint/angular-eslint/commit/3a9b7f4056b33918ead342efa331d21b9b1f4309))
- **eslint-plugin:** [use-pipe-transform-interface] handle type imports properly in fix ([#592](https://github.com/angular-eslint/angular-eslint/issues/592)) ([ac3fb12](https://github.com/angular-eslint/angular-eslint/commit/ac3fb126f1171284db6a52775c044aaedef2b90e))

### Features

- **builder:** add noEslintrc option ([#588](https://github.com/angular-eslint/angular-eslint/issues/588)) ([4b150bf](https://github.com/angular-eslint/angular-eslint/commit/4b150bff94d80b22aba2c6e2d170235d5ab71251))
- **builder:** add resolvePluginsRelativeTo option ([#590](https://github.com/angular-eslint/angular-eslint/issues/590)) ([3bea308](https://github.com/angular-eslint/angular-eslint/commit/3bea3085db38d28cfdd4fbc8158ba1b69b42e73d))
- **builder:** add rulesdir option ([#589](https://github.com/angular-eslint/angular-eslint/issues/589)) ([ff9557d](https://github.com/angular-eslint/angular-eslint/commit/ff9557d17e4f9f662f241a3db3ec3744fce1d2dc))
- **builder:** added outputFile option ([#587](https://github.com/angular-eslint/angular-eslint/issues/587)) ([420734b](https://github.com/angular-eslint/angular-eslint/commit/420734b891c61dcbcf2404f03db6251b28e458ac))
- **eslint-plugin:** [component-selector] handle shadow dom components properly ([#559](https://github.com/angular-eslint/angular-eslint/issues/559)) ([ecbe684](https://github.com/angular-eslint/angular-eslint/commit/ecbe68431fb73177d905676fef3df9be9c646636))
- **eslint-plugin:** [no-pipe-impure] add suggestion ([#585](https://github.com/angular-eslint/angular-eslint/issues/585)) ([149bf2f](https://github.com/angular-eslint/angular-eslint/commit/149bf2ffe0af7af1b0fc6b249321b50cf5d9f0a6))
- **schematics:** better support @angular/cli 12.1 ([#591](https://github.com/angular-eslint/angular-eslint/issues/591)) ([c5da07b](https://github.com/angular-eslint/angular-eslint/commit/c5da07b2d0c506dde24f0abc3e212db9deeaca82))

## [12.2.2](https://github.com/angular-eslint/angular-eslint/compare/v12.2.1...v12.2.2) (2021-07-10)

### Bug Fixes

- **eslint-plugin:** [no-output-on-prefix] handle `getters` and `outputs` metadata property ([#566](https://github.com/angular-eslint/angular-eslint/issues/566)) ([5884482](https://github.com/angular-eslint/angular-eslint/commit/588448214c31f01ec78ea892095ff0d05048a8c8))
- **eslint-plugin:** [no-output-rename] handle `getters` and `outputs` metadata property ([#568](https://github.com/angular-eslint/angular-eslint/issues/568)) ([c803ffd](https://github.com/angular-eslint/angular-eslint/commit/c803ffdf020a29939cfd7d763e0206198b4eac72))

## [12.2.1](https://github.com/angular-eslint/angular-eslint/compare/v12.2.0...v12.2.1) (2021-07-10)

### Bug Fixes

- **eslint-plugin:** [no-output-native] handle `getters` and `outputs` metadata property ([#567](https://github.com/angular-eslint/angular-eslint/issues/567)) ([22b378d](https://github.com/angular-eslint/angular-eslint/commit/22b378dd0fa9fe8f50bc0858c98f7f453bc5d389))
- **eslint-plugin:** [no-output-on-prefix] correct false positives ([#525](https://github.com/angular-eslint/angular-eslint/issues/525)) ([3a66274](https://github.com/angular-eslint/angular-eslint/commit/3a662740cd0a15e5d96b9f358505795eeb65a1f7))

# [12.2.0](https://github.com/angular-eslint/angular-eslint/compare/v12.1.0...v12.2.0) (2021-06-20)

### Bug Fixes

- **eslint-plugin:** [no-output-native] correct false positives ([#524](https://github.com/angular-eslint/angular-eslint/issues/524)) ([215abec](https://github.com/angular-eslint/angular-eslint/commit/215abec71cfb8bf276701cc4d7368931d7e3a61c))
- **eslint-plugin-template:** [accessibility-table-scope] ignore custom elements ([#550](https://github.com/angular-eslint/angular-eslint/issues/550)) ([53eb56d](https://github.com/angular-eslint/angular-eslint/commit/53eb56d9baa04acf4c228a7a8c6d3d546556b82b))
- **eslint-plugin-template:** [accessibility-valid-aria] ignore custom elements ([#552](https://github.com/angular-eslint/angular-eslint/issues/552)) ([f6466ec](https://github.com/angular-eslint/angular-eslint/commit/f6466ec2b52b0706e65c52bc02cb96c226e7e533))
- **eslint-plugin-template:** [no-autofocus] ignore custom elements ([#540](https://github.com/angular-eslint/angular-eslint/issues/540)) ([366d9df](https://github.com/angular-eslint/angular-eslint/commit/366d9df21415c82b22f2d9edcbcf53a39c70aa86))
- **eslint-plugin-template:** [no-positive-tabindex] ignore custom elements ([#551](https://github.com/angular-eslint/angular-eslint/issues/551)) ([5e33995](https://github.com/angular-eslint/angular-eslint/commit/5e33995ad7742555a4726b9f612fe5c4db190505))

### Features

- **builder:** add `cacheStrategy` option ([#520](https://github.com/angular-eslint/angular-eslint/issues/520)) ([427a9f5](https://github.com/angular-eslint/angular-eslint/commit/427a9f5505de876bc02aba8296a2d231b1d50fa4))
- **eslint-plugin:** [use-component-view-encapsulation] add suggestion ([#501](https://github.com/angular-eslint/angular-eslint/issues/501)) ([ea9e98d](https://github.com/angular-eslint/angular-eslint/commit/ea9e98d140e6ee237bf5cb46a756ec568b14bd11))
- **eslint-plugin-template:** [no-positive-tabindex] add suggestion ([#541](https://github.com/angular-eslint/angular-eslint/issues/541)) ([0582c2a](https://github.com/angular-eslint/angular-eslint/commit/0582c2a91c50a2f777fa6c2f4bc71252f51b8073))

# [12.1.0](https://github.com/angular-eslint/angular-eslint/compare/v12.0.0...v12.1.0) (2021-05-30)

### Bug Fixes

- **eslint-plugin:** [no-host-metadata-property] correct false positive with `allowStatic` option ([#482](https://github.com/angular-eslint/angular-eslint/issues/482)) ([89926d8](https://github.com/angular-eslint/angular-eslint/commit/89926d80b20b391515d4c400232cbf073c1bea4c))
- **eslint-plugin:** [no-output-on-prefix] not reporting failures on alias ([#471](https://github.com/angular-eslint/angular-eslint/issues/471)) ([f9ba372](https://github.com/angular-eslint/angular-eslint/commit/f9ba37253878183a4bd8363d63442b876486ca61))
- **eslint-plugin:** [relative-url-prefix] valid relative urls being reported ([#456](https://github.com/angular-eslint/angular-eslint/issues/456)) ([2247394](https://github.com/angular-eslint/angular-eslint/commit/2247394cf79aad9db892af5ed6378b93f8e327e6))
- **eslint-plugin-template:** [18n] ignore `checkAttributes` properly ([#467](https://github.com/angular-eslint/angular-eslint/issues/467)) ([20e54d7](https://github.com/angular-eslint/angular-eslint/commit/20e54d7699e499478b79735d2f5f7a4f1d419f21))
- **eslint-plugin-template:** [eqeqeq] change fix to suggest ([#465](https://github.com/angular-eslint/angular-eslint/issues/465)) ([a497fde](https://github.com/angular-eslint/angular-eslint/commit/a497fde0ddab7d6b32dd7b16138b00408258829a))
- **eslint-plugin-template:** [no-negated-async] ignore double-bang ([#450](https://github.com/angular-eslint/angular-eslint/issues/450)) ([9d06488](https://github.com/angular-eslint/angular-eslint/commit/9d064880ec1370e51d93848f7cb4575fd5f078f3))
- **schematics:** skip config for tsconfig.e2e.json when no e2e project is present ([#484](https://github.com/angular-eslint/angular-eslint/issues/484)) ([2673e59](https://github.com/angular-eslint/angular-eslint/commit/2673e59ec5e2708b7082fe7347ee1c96030ab6db))
- **template-parser:** generate correct index.d.ts when building ([#480](https://github.com/angular-eslint/angular-eslint/issues/480)) ([e150044](https://github.com/angular-eslint/angular-eslint/commit/e150044b23496a5af42c335e7635429cb122532d))
- **utils:** support passing `data` and `suggestions` individually for each error ([#491](https://github.com/angular-eslint/angular-eslint/issues/491)) ([70b01bd](https://github.com/angular-eslint/angular-eslint/commit/70b01bd83ddcaf3c57cab0701edb424dabf3a25f))

### Features

- **eslint-plugin:** [no-empty-lifecycle-method] add suggestion ([#463](https://github.com/angular-eslint/angular-eslint/issues/463)) ([1d1a329](https://github.com/angular-eslint/angular-eslint/commit/1d1a32971376f3b0b9cc2fee37896ebad8d25b37))
- **eslint-plugin:** [no-host-metadata-property] add option to allow static values ([#478](https://github.com/angular-eslint/angular-eslint/issues/478)) ([d64c832](https://github.com/angular-eslint/angular-eslint/commit/d64c832d6236fd53c56c67cf7c16b1c56b336aeb))
- **eslint-plugin:** [no-input-rename] add option to allow some inputs ([#475](https://github.com/angular-eslint/angular-eslint/issues/475)) ([9c861dc](https://github.com/angular-eslint/angular-eslint/commit/9c861dc8d016d89675c3bfa1f11bac5865d48b8c))
- **eslint-plugin:** [prefer-output-readonly] add suggestion ([#459](https://github.com/angular-eslint/angular-eslint/issues/459)) ([f3ff789](https://github.com/angular-eslint/angular-eslint/commit/f3ff789bfbfa298af74a8755bbacc81935a4682c))
- **eslint-plugin:** [sort-ngmodule-metadata-arrays] add fixer ([#493](https://github.com/angular-eslint/angular-eslint/issues/493)) ([32fae47](https://github.com/angular-eslint/angular-eslint/commit/32fae47cd3c69540e4a5304b5abe1adb7f3c160e))
- **eslint-plugin-template:** [accessibility-table-scope] add fixer ([#490](https://github.com/angular-eslint/angular-eslint/issues/490)) ([f0c4cea](https://github.com/angular-eslint/angular-eslint/commit/f0c4cea954c0cd3fedbda753c055037806574132))
- **eslint-plugin-template:** [accessibility-valid-aria] add suggestion ([#489](https://github.com/angular-eslint/angular-eslint/issues/489)) ([678e1b5](https://github.com/angular-eslint/angular-eslint/commit/678e1b585734cc080b68a32b633c059b15388a4a))
- **eslint-plugin-template:** [no-any] add suggestion ([#486](https://github.com/angular-eslint/angular-eslint/issues/486)) ([720e869](https://github.com/angular-eslint/angular-eslint/commit/720e869e1389c9d3f1b890e08158f4a58c4b122c))
- **eslint-plugin-template:** [no-autofocus] add fixer ([#485](https://github.com/angular-eslint/angular-eslint/issues/485)) ([9450b7d](https://github.com/angular-eslint/angular-eslint/commit/9450b7da90de0d49bf50d02a6ea3e625582399ab))
- **eslint-plugin-template:** [no-distracting-elements] add fixer ([#488](https://github.com/angular-eslint/angular-eslint/issues/488)) ([9cefe67](https://github.com/angular-eslint/angular-eslint/commit/9cefe6792a58f1d7b2d4dbc6828a1642f8c707da))
- **eslint-plugin-template:** [no-duplicate-attributes] add suggestion ([#495](https://github.com/angular-eslint/angular-eslint/issues/495)) ([62cadcd](https://github.com/angular-eslint/angular-eslint/commit/62cadcd9ebe212bb43495a2926a9785ddb8829fb))
- **eslint-plugin-template:** [no-negated-async] add suggestion ([#487](https://github.com/angular-eslint/angular-eslint/issues/487)) ([0b3f9eb](https://github.com/angular-eslint/angular-eslint/commit/0b3f9eb85b6315e123b4a1c03730929d7202219f))
- **schematics:** on `ng add` include a lint command if none exists ([#481](https://github.com/angular-eslint/angular-eslint/issues/481)) ([ae49af4](https://github.com/angular-eslint/angular-eslint/commit/ae49af4ae8af9fef306bda31e156ed4e5ddf058b))
- **utils:** add support for suggestions ([#458](https://github.com/angular-eslint/angular-eslint/issues/458)) ([0ea02ae](https://github.com/angular-eslint/angular-eslint/commit/0ea02ae3d54137347de33614803cc6fb72759080))

# [12.0.0](https://github.com/angular-eslint/angular-eslint/compare/v4.3.0...v12.0.0) (2021-05-13)

### Bug Fixes

- **template-parser:** add missing `Conditional` and its keys to `VisitorKeys` ([#445](https://github.com/angular-eslint/angular-eslint/issues/445)) ([5ad0f1a](https://github.com/angular-eslint/angular-eslint/commit/5ad0f1aeca244dbd27496e5a2d8c569994a24dcf))
- **eslint-plugin-template:** no-negated-async no longer performs equality checks ([#399](https://github.com/angular-eslint/angular-eslint/issues/399))

### Features

- update tslint-to-eslint-config to 2.4.0 ([7352ad2](https://github.com/angular-eslint/angular-eslint/commit/7352ad260644952abebf06773703f7b550d870fb))
- **eslint-plugin-template:** add rule eqeqeq ([#444](https://github.com/angular-eslint/angular-eslint/issues/444)) ([e15148c](https://github.com/angular-eslint/angular-eslint/commit/e15148cc31d54641815d08f97f14b3388d8dcde2))
- update eslint to ^7.26.0, [@typescript-eslint](https://github.com/typescript-eslint) to 4.23.0 ([9e31c38](https://github.com/angular-eslint/angular-eslint/commit/9e31c3881a13d6ce3b642b9c23c67e2e0f2d1aa1))

### BREAKING CHANGES

- update to angular v12 ([c80008d](https://github.com/angular-eslint/angular-eslint/commit/c80008df8f6b9d08daf3043dffc1be45f8cfbe81))
  - All packages now require the use of Angular CLI >= 12.0.0 < 13

- **eslint-plugin-template:** no-negated-async no longer performs equality checks ([#399](https://github.com/angular-eslint/angular-eslint/issues/399))
  - You should add the new `@angular-eslint/template/eqeqeq` rule to your config if you want to continue with the same functionality around equality checks. This will be applied for you by `ng update` automatically.

# [4.3.0](https://github.com/angular-eslint/angular-eslint/compare/v4.2.1...v4.3.0) (2021-05-12)

### Features

- **eslint-plugin-template:** add rule accessibility-label-has-associated-control ([#392](https://github.com/angular-eslint/angular-eslint/issues/392)) ([0851f3e](https://github.com/angular-eslint/angular-eslint/commit/0851f3eeda54c8c9ad01460b91cf8cf67017f1db))

## [4.2.1](https://github.com/angular-eslint/angular-eslint/compare/v4.2.0...v4.2.1) (2021-05-12)

### Bug Fixes

- **eslint-plugin-template:** no-negated-async message tweak ([#427](https://github.com/angular-eslint/angular-eslint/issues/427)) ([08a8330](https://github.com/angular-eslint/angular-eslint/commit/08a8330003a039c353446724d3e363e670c529e0))

# [4.2.0](https://github.com/angular-eslint/angular-eslint/compare/v4.1.0...v4.2.0) (2021-04-28)

### Features

- **schematics:** add add-eslint-to-project schematic ([#426](https://github.com/angular-eslint/angular-eslint/issues/426)) ([7ae557d](https://github.com/angular-eslint/angular-eslint/commit/7ae557d94f53833fbfbf5128d39f64c7bb1c3c5f))

# [4.1.0](https://github.com/angular-eslint/angular-eslint/compare/v4.0.0...v4.1.0) (2021-04-28)

### Bug Fixes

- **schematics:** support workspaces which use targets alias ([#424](https://github.com/angular-eslint/angular-eslint/issues/424)) ([da6bcf7](https://github.com/angular-eslint/angular-eslint/commit/da6bcf70027cc4b339ef2e825a931ec882d4711f))

### Features

- **schematics:** dynamically install tslint-to-eslint-config as needed ([#425](https://github.com/angular-eslint/angular-eslint/issues/425)) ([27ca474](https://github.com/angular-eslint/angular-eslint/commit/27ca474419defb79b552b233689a2dbf31b8ad92))

# [4.0.0](https://github.com/angular-eslint/angular-eslint/compare/v3.0.1...v4.0.0) (2021-04-18)

We have provided automated migrations for you to move to v4.

All you need to do is run the update schematics for `@angular-eslint`:

```sh
npx ng update @angular-eslint/schematics
```

NOTE: For this release, there are no automated migrations to be run, other than automatically updating the version number of your other `@angular-eslint` packages.

### BREAKING CHANGES

- Passing `--collection=@angular-eslint/schematics` to `ng new` is no longer supported:
  - If you attempt to do it you will get a clear error with instructions on what to do instead.
  - This means we have one consistent way to add `@angular-eslint` to a workspace - run `ng add @angular-eslint/schematics` - regardless of whether that workspace is brand new or has existed for a while.

- We have introduced two new options to the `convert-tslint-to-eslint` schematic:
  - `--remove-tslint-if-no-more-tslint-targets` so that we remove TSLint and Codelyzer from the workspace automatically if we detect you have no TSLint usage remaining (`true` by default).
  - `--ignore-existing-tslint-config` so that we can jump straight to the up to date recommended ESLint setup, without converting the previous Angular CLI TSLint setup, which is unnecessary for brand new projects (`false` by default).

### Features

- **schematics:** options for convert-tslint-to-eslint ([#419](https://github.com/angular-eslint/angular-eslint/issues/419)) ([18fd863](https://github.com/angular-eslint/angular-eslint/commit/18fd863d6948578db96252da57702338a8ea5ea0))

## [3.0.1](https://github.com/angular-eslint/angular-eslint/compare/v3.0.0...v3.0.1) (2021-04-18)

### Bug Fixes

- **eslint-plugin:** correctly expose recommended-extra config ([#418](https://github.com/angular-eslint/angular-eslint/issues/418)) ([f727d8c](https://github.com/angular-eslint/angular-eslint/commit/f727d8c05337908b4e8b9e5f34178bb54a390fb0))

# [3.0.0](https://github.com/angular-eslint/angular-eslint/compare/v2.1.1...v3.0.0) (2021-04-17)

PR #388 (f92b184)

We have provided automated migrations for you to move to v3.

All you need to do is run the update schematics for `@angular-eslint`:

```sh
npx ng update @angular-eslint/schematics
```

---

### BREAKING CHANGES

- The `recommended` configs from `@angular-eslint/eslin-plugin` now only configures rules directly from that plugin. This provides an overall more intuitive experience when stacking the recommended config with other plugins from the ecosystem. If you wish to continue having the same experience (with mixed `@angular-eslint` and `@typescript-eslint` rules in the configs you inherit from you can add the new `recommended--extra` config to your ESLint extends in the relevant config.

E.g. extract from .eslintrc.json

```diff
  "extends": [
    "plugin:@angular-eslint/recommended",
+   "plugin:@angular-eslint/recommended--extra",
  ],
```

- Within the `builder`, linting now always runs relative to your workspace root. This should not have any impact on my workflows but is important if you run `ng lint` from within subdirectories of your workspace.

- Within the `builder`, we always make a call to format, even if the lint results are empty. This is important for non-default formatters.

- We have removed the hard peerDependency on the 3rd party eslint plugins `import` `jsdoc` and `prefer-arrow`. These plugins are only required if you are converted an existing workspace to TSLint and they will still be installed on demand in that scenario.

- Within the `eslint-plugin`, the `component-max-inline-declarations` rule will no longer accept negative values as input. Previously it would silently use the default values in this case. An automated migration is provided for this change as part of the `ng update` schematics.

## [2.1.1](https://github.com/angular-eslint/angular-eslint/compare/v2.1.0...v2.1.1) (2021-04-17)

### Bug Fixes

- **eslint-plugin:** `sort-ngmodule-metadata-arrays` reporting false positives ([#408](https://github.com/angular-eslint/angular-eslint/issues/408)) ([149152a](https://github.com/angular-eslint/angular-eslint/commit/149152a43dfad6ef841fd2784ef3168c0de8d91f))
- **eslint-plugin:** directive-class-suffix reporting selectorless directives ([#394](https://github.com/angular-eslint/angular-eslint/issues/394)) ([42d4e5d](https://github.com/angular-eslint/angular-eslint/commit/42d4e5db9a76703ff8556a4050e785a530a90611))
- **eslint-plugin-template:** [i18n] remove unsafe fix ([#411](https://github.com/angular-eslint/angular-eslint/issues/411)) ([3246b8a](https://github.com/angular-eslint/angular-eslint/commit/3246b8a2e762d70cae5512aed06216e4c0669257))

# [2.1.0](https://github.com/angular-eslint/angular-eslint/compare/v2.0.2...v2.1.0) (2021-04-11)

### Bug Fixes

- **builder:** expose maxWarnings option ([#402](https://github.com/angular-eslint/angular-eslint/issues/402)) ([76f5ba4](https://github.com/angular-eslint/angular-eslint/commit/76f5ba42e37af19d6c2026b6268dd634507d1f7b))
- **eslint-plugin:** no-call-expression incorrect reports for conditionals ([#390](https://github.com/angular-eslint/angular-eslint/issues/390)) ([fa9cc73](https://github.com/angular-eslint/angular-eslint/commit/fa9cc7369446f3a7605554754ac57485bf1b1bfb))
- **eslint-plugin-template:** accessibility-elements-content not allowing some attributes/inputs ([#397](https://github.com/angular-eslint/angular-eslint/issues/397)) ([ffedaa2](https://github.com/angular-eslint/angular-eslint/commit/ffedaa24c449af2e5536b235e264180c9a970980))
- **eslint-plugin-template:** i18n ignoreTags not being ignored properly ([#387](https://github.com/angular-eslint/angular-eslint/issues/387)) ([985f6c2](https://github.com/angular-eslint/angular-eslint/commit/985f6c2e8e70e42223a14fc5bd053732817ff4d9))
- **eslint-plugin-template:** i18n reporting when a parent element already contains i18n id ([#398](https://github.com/angular-eslint/angular-eslint/issues/398)) ([c937a3f](https://github.com/angular-eslint/angular-eslint/commit/c937a3f1d364f74acdb2cc17e507820a784ffb8e))

### Features

- **eslint-plugin:** add rule sort-ngmodule-metadata-arrays ([#386](https://github.com/angular-eslint/angular-eslint/issues/386)) ([935afdd](https://github.com/angular-eslint/angular-eslint/commit/935afdda16970f879c3dc45d45b6f5ef7d898d97))
- **template-parser:** support eslint-disable comments in HTML templates ([#405](https://github.com/angular-eslint/angular-eslint/issues/405)) ([5dd9578](https://github.com/angular-eslint/angular-eslint/commit/5dd9578d7c212cdead04c2142b920af6f654f2de))

## [2.0.2](https://github.com/angular-eslint/angular-eslint/compare/v2.0.1...v2.0.2) (2021-03-16)

### Bug Fixes

- **builder:** printInfo should not be taken into account for report ([#376](https://github.com/angular-eslint/angular-eslint/issues/376)) ([d7c6aa4](https://github.com/angular-eslint/angular-eslint/commit/d7c6aa49132100de23bd101f36ffccf6a8b6414e))

## [2.0.1](https://github.com/angular-eslint/angular-eslint/compare/v2.0.0...v2.0.1) (2021-03-14)

### Bug Fixes

- **eslint-plugin-template:** conditional-complexity error from bundling ([#373](https://github.com/angular-eslint/angular-eslint/issues/373)) ([f466c01](https://github.com/angular-eslint/angular-eslint/commit/f466c0157f5ecefe6eae9aa726aaf08853c1894d))

# [2.0.0](https://github.com/angular-eslint/angular-eslint/compare/v1.2.0...v2.0.0) (2021-03-13)

We have provided automated migrations for you to move to v2.

All you need to do is first update to Angular and Angular CLI v11.2.0 or above (see https://update.angular.io for full instructions relating to Angular updates):

```sh
npx ng update @angular/cli @angular/core
```

And then run the update schematics for `@angular-eslint`:

```sh
npx ng update @angular-eslint/schematics
```

---

### Bug Fixes

- **template-parser:** add BindingPipe exp to VisitorKeys ([#337](https://github.com/angular-eslint/angular-eslint/issues/337)) ([#338](https://github.com/angular-eslint/angular-eslint/issues/338)) ([75c406f](https://github.com/angular-eslint/angular-eslint/commit/75c406f9f496740a694681916b8b4cd7b438d574))
- add docs url for both plugins ([#360](https://github.com/angular-eslint/angular-eslint/issues/360)) ([4c9b068](https://github.com/angular-eslint/angular-eslint/commit/4c9b068a13b2ff8e7d5ebc3730564658d7cdc5c6))

### Features

- v2.0.0 ([#358](https://github.com/angular-eslint/angular-eslint/issues/358)) ([737fd04](https://github.com/angular-eslint/angular-eslint/commit/737fd04946a9533698c04665c771d944ffbe430c)), closes [#328](https://github.com/angular-eslint/angular-eslint/issues/328) [#245](https://github.com/angular-eslint/angular-eslint/issues/245)
- **builder:** add maxWarnings option ([#351](https://github.com/angular-eslint/angular-eslint/issues/351)) ([5dc2dc3](https://github.com/angular-eslint/angular-eslint/commit/5dc2dc39e51cb3ec2b5e3c8596404dcb8a98877f))

### BREAKING CHANGES

- The format of results output has changed

- The `use-pipe-decorator` rule no longer exists for use

- feat(template-parser): updated use of parseTemplate to improve loc data
  - Requires @angular/compiler 11.2.0 and above

- feat(schematics): change way indent and quotes are handled by conversion schematics
  - The conversion schematic handle these rules differently

# [1.2.0](https://github.com/angular-eslint/angular-eslint/compare/v1.1.0...v1.2.0) (2021-02-06)

### Bug Fixes

- **eslint-plugin:** component-max-inline-declarations animations not being checked properly ([#313](https://github.com/angular-eslint/angular-eslint/issues/313)) ([61a2a0f](https://github.com/angular-eslint/angular-eslint/commit/61a2a0fc1caf19ced3781560052debf274d708a3))
- **eslint-plugin:** no-lifecycle-call invalid super calls not being reported ([#314](https://github.com/angular-eslint/angular-eslint/issues/314)) ([c44cd5d](https://github.com/angular-eslint/angular-eslint/commit/c44cd5d043a3d203efd1faaed4cbfee2c9ac2e9d))
- **eslint-plugin-template:** accessibility-valid-aria not reporting i… ([#278](https://github.com/angular-eslint/angular-eslint/issues/278)) ([391980f](https://github.com/angular-eslint/angular-eslint/commit/391980fd797787560cb56b71c2f741dd48a1c63f))

### Features

- **eslint-plugin:** add fixer for use-pipe-transform-interface ([#260](https://github.com/angular-eslint/angular-eslint/issues/260)) ([e3f4db6](https://github.com/angular-eslint/angular-eslint/commit/e3f4db6e5d4c062aabfc19d872dc9ee6861fcd44))
- **eslint-plugin-template:** add no duplicate attributes rule ([#302](https://github.com/angular-eslint/angular-eslint/issues/302)) ([c387de5](https://github.com/angular-eslint/angular-eslint/commit/c387de5223f7bb6dfb91a4c6748e307efbf56d9c)), closes [#293](https://github.com/angular-eslint/angular-eslint/issues/293)

# [1.1.0](https://github.com/angular-eslint/angular-eslint/compare/v1.0.0...v1.1.0) (2021-01-14)

### Bug Fixes

- **eslint-plugin:** handle DoBootstrap correctly in lifecycle rules ([#243](https://github.com/angular-eslint/angular-eslint/issues/243)) ([5010b3f](https://github.com/angular-eslint/angular-eslint/commit/5010b3f827b6089c089e5a5d55905aa3ac8839cc))
- **eslint-plugin-template:** conditional-complexity not reporting all cases ([#279](https://github.com/angular-eslint/angular-eslint/issues/279)) ([a4fd077](https://github.com/angular-eslint/angular-eslint/commit/a4fd077a062797c57f63abd9d0a78f60d40c73ca))

### Features

- **eslint-plugin-template:** accessibility-label-for ([#268](https://github.com/angular-eslint/angular-eslint/issues/268)) ([49ab76a](https://github.com/angular-eslint/angular-eslint/commit/49ab76a9ecaf427ba579093293cb7bc2cfc651c6))
