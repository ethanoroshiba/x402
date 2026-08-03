---
"@x402/core": patch
---

Merge server and client builder-code `s` arrays during extension re-merge instead of dropping the client's, and treat echoed extension-info arrays as additive (client-first, deduped, with scalar/array coercion) in extension echo validation. Payment-requirements `extra` matching is unaffected and continues to require exact array equality.
