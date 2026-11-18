---
"@commercetools/nimbus": patch
---

`@commercetools/nimbus/plugins/stub`: named imports of a stubbed
`@commercetools/nimbus` no longer fail the build with webpack 5.110.0 or later
("export 'X' (imported as 'X') was not found in '@commercetools/nimbus'") when
`strictExportPresence` is enabled. Stubbed imports resolve to `undefined` again.
