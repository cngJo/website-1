---
title: Monthly updates (June 2024)
description: 26 releases this month! What's new in the UnJS ecosystem?
authors:
  - name:
    picture:
    twitter:
category:
  - releases
packages:
  - c12
  - compatx
  - h3
  - jiti
  - mkdist
  - mlly
  - nitro
  - serve-placeholder
  - unbuild
  - unhead
  - unpdf
publishedAt: 2024-06-28T01:04:14.509Z
modifiedAt: 2024-06-28T01:04:14.509Z
---

## c12

This month, we release 2 new releases (0 major release, 1 minor release and 1 patch release):

- [v1.11.1](https://github.com/unjs/c12/releases/tag/v1.11.1)
- [v1.11.0](https://github.com/unjs/c12/releases/tag/v1.11.0)

### fixes

- **update:** Await on `onUpdate` ([6b37c98](https://github.com/unjs/c12/commit/6b37c98))
- **update:** Respect falsy value of `onCreate` ([cc4e991](https://github.com/unjs/c12/commit/cc4e991))
- **update:** Use relative path to resolve config ([8b58b25](https://github.com/unjs/c12/commit/8b58b25))

### enhancements

- Resolvable configs ([#159](https://github.com/unjs/c12/pull/159))
- Custom merger to replace built-in defu ([#160](https://github.com/unjs/c12/pull/160))
- Config update util ([#162](https://github.com/unjs/c12/pull/162))
### fixes
- **loadConfig:** `config` is not nullable ([#161](https://github.com/unjs/c12/pull/161))

### refactors

- Internally use named sources ([#158](https://github.com/unjs/c12/pull/158))

## compatx

This month, we release 8 new releases (0 major release, 0 minor release and 8 patch releases):

- [v0.1.8](https://github.com/unjs/compatx/releases/tag/v0.1.8)
- [v0.1.7](https://github.com/unjs/compatx/releases/tag/v0.1.7)
- [v0.1.6](https://github.com/unjs/compatx/releases/tag/v0.1.6)
- [v0.1.5](https://github.com/unjs/compatx/releases/tag/v0.1.5)
- [v0.1.4](https://github.com/unjs/compatx/releases/tag/v0.1.4)
- [v0.1.3](https://github.com/unjs/compatx/releases/tag/v0.1.3)
- [v0.1.2](https://github.com/unjs/compatx/releases/tag/v0.1.2)
- [v0.1.1](https://github.com/unjs/compatx/releases/tag/v0.1.1)

### enhancements

- FormatCompatibilityDate utility ([130f038](https://github.com/unjs/compatx/commit/130f038))

### fixes

- Normalize default if is string ([9526a1d](https://github.com/unjs/compatx/commit/9526a1d))

### refactors

- Make compat date types better ([ebd54a5](https://github.com/unjs/compatx/commit/ebd54a5))

## h3

This month, we release 1 new release (0 major release, 1 minor release and 0 patch release):

- [v1.12.0](https://github.com/unjs/h3/releases/tag/v1.12.0)

### enhancements

- Improve typed headers ([#625](https://github.com/unjs/h3/pull/625))
- Export event-stream types ([112fa33](https://github.com/unjs/h3/commit/112fa33))

### fixes

- **getRequestUrl:** Forward options to  internal `getRequestProtocol` ([#776](https://github.com/unjs/h3/pull/776))
- **readRawBody:** Read chunked body ([#652](https://github.com/unjs/h3/pull/652))
- **proxy:** Better error when upstream proxy fails ([#746](https://github.com/unjs/h3/pull/746))
- **node:** Make sure `onBeforeResponse` and `onAfterResponse` are called with error code ([#756](https://github.com/unjs/h3/pull/756))
- **sse:** Prevent `onClosed` from firing twice in `EventStream` ([#704](https://github.com/unjs/h3/pull/704))
- **plain:** Avoid import from unenv internals ([#781](https://github.com/unjs/h3/pull/781), [76736ea](https://github.com/unjs/h3/commit/76736ea))

### refactors

- **session:** Remove unnecessary async for clear ([#729](https://github.com/unjs/h3/pull/729))

### documentation

- Fix typos ([#699](https://github.com/unjs/h3/pull/699)) ([#707](https://github.com/unjs/h3/pull/707)) ([#712](https://github.com/unjs/h3/pull/712)) ([#730](https://github.com/unjs/h3/pull/730)) ([#732](https://github.com/unjs/h3/pull/732)) ([#766](https://github.com/unjs/h3/pull/766)) ([#764](https://github.com/unjs/h3/pull/764)) ([#738](https://github.com/unjs/h3/pull/738)) ([#758](https://github.com/unjs/h3/pull/758)) ([#734](https://github.com/unjs/h3/pull/734))
- Remove extra space ([#718](https://github.com/unjs/h3/pull/718))
- Add semi ([#710](https://github.com/unjs/h3/pull/710))
- **event-handler:** Fix typo ([#684](https://github.com/unjs/h3/pull/684))
- Add jsdoc examples for response utils ([#677](https://github.com/unjs/h3/pull/677))
- Add note for `getRequestIP` return value ([#726](https://github.com/unjs/h3/pull/726))
- Fix session example ([#702](https://github.com/unjs/h3/pull/702))
- Add jsdoc examples for request utils ([#680](https://github.com/unjs/h3/pull/680))
- Correct zod validation example ([#735](https://github.com/unjs/h3/pull/735))
- Add usage example for `handleCors` ([#747](https://github.com/unjs/h3/pull/747))
- Update mogen example to use `combined` log format ([#771](https://github.com/unjs/h3/pull/771))
- **examples:** Add cors example ([#700](https://github.com/unjs/h3/pull/700))
- Fix `respondWith` event object ([#775](https://github.com/unjs/h3/pull/775))
- Provide `async` for request body ([#777](https://github.com/unjs/h3/pull/777))
- **error-handling:** Add string vs object errors and update `createError` jsdoc ([#762](https://github.com/unjs/h3/pull/762))

## jiti

This month, we release 5 new releases (0 major release, 0 minor release and 5 patch releases):

- [v1.21.6](https://github.com/unjs/jiti/releases/tag/v1.21.6)
- [v1.21.5](https://github.com/unjs/jiti/releases/tag/v1.21.5)
- [v1.21.3](https://github.com/unjs/jiti/releases/tag/v1.21.3)
- [v1.21.2](https://github.com/unjs/jiti/releases/tag/v1.21.2)
- [v1.21.1](https://github.com/unjs/jiti/releases/tag/v1.21.1)

### fixes

- Use internal cached modules only if loaded ([#247](https://github.com/unjs/jiti/pull/247))

### from 1.21.4

- Avoid `node:` protocol for node 14 compatibility ([5d877de](https://github.com/unjs/jiti/commit/5d877de))
- Update deps ([5e11181](https://github.com/unjs/jiti/commit/5e11181))

## mkdist

This month, we release 2 new releases (0 major release, 0 minor release and 2 patch releases):

- [v1.5.3](https://github.com/unjs/mkdist/releases/tag/v1.5.3)
- [v1.5.2](https://github.com/unjs/mkdist/releases/tag/v1.5.2)

### fixes

- **dts:** Use `ts.convertCompilerOptionsFromJson` to normalise ([#224](https://github.com/unjs/mkdist/pull/224))

## mlly

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v1.7.1](https://github.com/unjs/mlly/releases/tag/v1.7.1)

### fixes

- **interopDefault:** Assign props to default function export ([#258](https://github.com/unjs/mlly/pull/258))

## nitro

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v2.9.7](https://github.com/unjs/nitro/releases/tag/v2.9.7)

### fixes

- **github-pages:** Prerender `/` by default ([#2334](https://github.com/unjs/nitro/pull/2334)) (8b5cbc590e3948b7abc5569dd06ab43b955a4ae8)
- Deduplicate plugins ([#2391](https://github.com/unjs/nitro/pull/2391)) (4293b8b1db5e1d1a12778efeba852c5f07da8a3f)
- Add `.tsx` and `.jsx` to node-resolve extensions ([#2398](https://github.com/unjs/nitro/pull/2398)) (d2c0d74140b7b8f166d5937d736830b55177dd07)
- **typescript:** Set `compilerOptions.noEmit` to avoid `tsconfig.json` warning ([#2402](https://github.com/unjs/nitro/pull/2402)) (6b6777eb73fde6337c87242ddf62406e06f0fcd3)
- **prerender:** Only try to add `/` after prerender:routes hook ([#2348](https://github.com/unjs/nitro/pull/2348)) (fb88efdc614e3b3b1e9dd76dfb342f9f0aff229c)
- Pass custom entry filename when resolving prerenderer ([#2461](https://github.com/unjs/nitro/pull/2461)) (9bd662258a3d727805248f69ea8280ccf8e31675)
- **public-assets:** Do not shadow paths that share prefix ([#2516](https://github.com/unjs/nitro/pull/2516)) (72db8482e837c9fc50b5c928ff5636ba2cbb51cf)
- **openapi:** Update swagger-ui version to v5 for OpenAPI v3.1 support ([#2343](https://github.com/unjs/nitro/pull/2343)) (9e2cd8af32b2ea803b52ca0df282c588356161a2)
- Convert `CapturedErrorContext` to interface to allow type augmentation ([#2393](https://github.com/unjs/nitro/pull/2393)) (45ff175ec9ce962ddc8cbe67925bb2136279c80b)
- **renderer:** Check full path for `/favicon.ico` placeholder ([#2553](https://github.com/unjs/nitro/pull/2553)) (b86bb4580c2f6df855c9c7f184613877ebd7b58e)
- Use relative paths in `nitro-config.d.ts` ([#2471](https://github.com/unjs/nitro/pull/2471)) (4d70b759e1d8c50bb6a43a471c77eaf205bcb760)
- **prerender:** Extract links from explicit html routes ([#2517](https://github.com/unjs/nitro/pull/2517)) (e1f87c590d6ca8ebb338ecd0d0b4d4b85eb75042)
- **cloudflare-pages:** Remove `.html` extension from generated `_routes.json` ([#2498](https://github.com/unjs/nitro/pull/2498)) (79b85feec37c6c796df4ac453fcd4dd012d9be7b)
- **core:** Resolve modules with esm compatibility ([#2514](https://github.com/unjs/nitro/pull/2514)) (4657ada0e372cf36a78fec29de0b96b582923832)
- Update cli preset with esm module format ([#2539](https://github.com/unjs/nitro/pull/2539)) (f6f23270c841514fa3f9d7162ece83f13ab4108c)
- **types:** Infer types correctly when method is omitted ([#2551](https://github.com/unjs/nitro/pull/2551)) (f76d21be811766009757dd0eebf05ff8aa7e795f)
- **deno-server:** Explicitly remove cert/key from options if either is not set ([#2373](https://github.com/unjs/nitro/pull/2373)) (d887f4a62a300be5c24dea7bfd1ede324a1dfe7a)
- **azure:** Correctly handle maxAge cookie option ([#2403](https://github.com/unjs/nitro/pull/2403)) (aabdc9c5c78c011a212c754058160ed23391361d)
- **netlify:** Ensure preview command is correct ([#2561](https://github.com/unjs/nitro/pull/2561)) (d16a47bd4dac8674db8538ff8b6235131c75230f)
- **iis:** Deep merge configs ([#2358](https://github.com/unjs/nitro/pull/2358)) (f03addd248a85d0093b71e8ac8e2523c590a35d2)
- **iis:** Parse without explicitArray to allow merging `web.config` ([#2457](https://github.com/unjs/nitro/pull/2457)) (6c3e0805d38c80fcad9430d1e5beeeee65bbbaa5)
- **vercel:** Support custom baseURL ([#2464](https://github.com/unjs/nitro/pull/2464)) (61f2079a605fca81b578894edfdbb0c328db12a3)
- Lower-case accepted handler method ([#2382](https://github.com/unjs/nitro/pull/2382)) (e60e114f33ce02866d931c70518268a5e94509ee)
- **defineCachedEventHandler:** Add `event.context.cache` ([#2519](https://github.com/unjs/nitro/pull/2519)) (fc3968ba9993321cbe090c8818d22f3efa10e9d1)

## serve-placeholder

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v2.0.2](https://github.com/unjs/serve-placeholder/releases/tag/v2.0.2)

### refactors

- Update repo ([f516ffe](https://github.com/unjs/serve-placeholder/commit/f516ffe))

### documentation

- Fix `.js` to `.ts` ([4d8aff6](https://github.com/unjs/serve-placeholder/commit/4d8aff6))
- Fix typo ([578500a](https://github.com/unjs/serve-placeholder/commit/578500a))

## unbuild

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v3.0.0-rc.2](https://github.com/unjs/unbuild/releases/tag/v3.0.0-rc.2)

### enhancements

- Support `copy` builder ([#389](https://github.com/unjs/unbuild/pull/389))
- Experimental active watcher for rollup ([#364](https://github.com/unjs/unbuild/pull/364))
- **rollup:** Add `.mts` and `.cts` to supported extensions ([633ffe9](https://github.com/unjs/unbuild/commit/633ffe9))
- Support custom jiti plugins for stub mode ([#368](https://github.com/unjs/unbuild/pull/368))

### fixes

- Generate stub types of with explicit extension import if pkg type is `module` ([#371](https://github.com/unjs/unbuild/pull/371))
- Correct dts generation for stub mode ([#314](https://github.com/unjs/unbuild/pull/314))
- **rollup:** Handle aliases when checking for externals ([#384](https://github.com/unjs/unbuild/pull/384))
- **rollup:** Update `importAttributesKey` to `with` ([27bcba8](https://github.com/unjs/unbuild/commit/27bcba8))

### documentation

- Add more jsdocs ([#363](https://github.com/unjs/unbuild/pull/363))
- Add examples ([#334](https://github.com/unjs/unbuild/pull/334))

## unhead

This month, we release 3 new releases (0 major release, 0 minor release and 3 patch releases):

- [v1.9.14](https://github.com/unjs/unhead/releases/tag/v1.9.14)
- [v1.9.13](https://github.com/unjs/unhead/releases/tag/v1.9.13)
- [v1.9.12](https://github.com/unjs/unhead/releases/tag/v1.9.12)

### bug fixes

- **unhead**: `style` side effect not clearing - by @harlan-zw [<samp>(baf8b)</samp>](https://github.com/unjs/unhead/commit/baf8bc92)

### 🏎 performance

- **scripts**: Process triggers async on animation frames - by @harlan-zw [<samp>(325cb)</samp>](https://github.com/unjs/unhead/commit/325cbd37)

## unpdf

This month, we release 1 new release (0 major release, 1 minor release and 0 patch release):

- [v0.11.0](https://github.com/unjs/unpdf/releases/tag/v0.11.0)

### breaking changes

- Remove deprecated `defineUnPDFConfig` - by @johannschopplich [<samp>(9f53e)</samp>](https://github.com/unjs/unpdf/commit/9f53e11)

### features

- Expose `createIsomorphicCanvasFactory` - by @johannschopplich [<samp>(9c687)</samp>](https://github.com/unjs/unpdf/commit/9c687a3)
- Upgrade PDF.js to v4.0.379 - by @johannschopplich [<samp>(55ca5)</samp>](https://github.com/unjs/unpdf/commit/55ca5c4)
- Improve `extractText` type - by @himself65 in https://github.com/unjs/unpdf/issues/11 [<samp>(477b2)</samp>](https://github.com/unjs/unpdf/commit/477b228)
- Updgrade PDF.js to v4.3 - by @johannschopplich in https://github.com/unjs/unpdf/issues/13 [<samp>(d1284)</samp>](https://github.com/unjs/unpdf/commit/d128424)

### bug fixes

- Export types from `pdfjs-dist` - by @eltigerchino in https://github.com/unjs/unpdf/issues/7 [<samp>(d651c)</samp>](https://github.com/unjs/unpdf/commit/d651c33)
- Reduce whitespace to single space in extracted text - by @johannschopplich [<samp>(58660)</samp>](https://github.com/unjs/unpdf/commit/586604a)
- Extract text concatenation - by @pserrer1 in https://github.com/unjs/unpdf/issues/12 [<samp>(4664e)</samp>](https://github.com/unjs/unpdf/commit/4664ee2)