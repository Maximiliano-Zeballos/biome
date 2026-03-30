---
"@biomejs/biome": patch
---

Fixed Grit queries that use native Biome AST node names with native field names. Queries such as `JsConditionalExpression(consequent = $cons, alternate = $alt)` now compile successfully in `biome search`.
