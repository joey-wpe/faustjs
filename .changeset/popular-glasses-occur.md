---
'@faustwp/blocks': major
---

Update of the CoreParagraph block to support the native WP anchor attribute. GitHub issue: "[[feat] Add anchor attribute to core/paragraph block](https://github.com/wpengine/faustjs/issues/1954)"

Introduces new field to `core/paragraph` block: `anchor`. This field allows users to add an anchor to the paragraph block. The anchor is used to create a link to a specific part of the page. The anchor is added to the block's wrapper element as an ID attribute.

**Files changed:**
  - packages/blocks/src/blocks/CoreParagraph.tsx (added anchor attribute)
  - packages/blocks/package.json (updated package version to 6.0.0)
