# blog-assets

Public images for the blogs, served over https by jsDelivr so that link
previews and search engines can load them (a post's first image becomes its
`og:image`).

- `stepfix/YYYY-MM/<topic>-<hash>.jpg`: the cover of each StepFix Notes post
  (https://stepfixnotes.blogspot.com/), drawn by StepFix Notes.

Posts link a file pinned to the commit that added it, for example
`https://cdn.jsdelivr.net/gh/SeoTaeMin0508/blog-assets@<commit>/stepfix/2026-10/<file>.jpg`.
The file name carries a hash of its bytes, so a file is never replaced, only
added. The publisher writes here automatically; please do not rename or delete
files that a published post links.
