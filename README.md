# Every support documentation

These pages are published at https://docs.every.ai and retrieved by Every's agent through `search_mintlify_docs`. Incorrect feature claims can become incorrect support answers.

## Accuracy and release boundaries

Verify customer-facing instructions against the production code in `every-fastapi` and `every-react` (`origin/main`). Compare `origin/staging` separately: staging features are not production features. Keep pending feature notes in the meta-repo's plan or release entry, rather than presenting them as available in these pages. Check feature flags and permissions before making universal availability claims.

The backend's `support_agent_product_docs` snippet supplies web navigation. Feature semantics belong in these pages and current domain guidance, not a duplicate embedded handbook. When navigation changes, check both sources.

## Local validation

Run `mint broken-links`, then `mint dev` from this directory for a local preview. Check changed pages and navigation before publishing.

## Publishing

Pushing this repository's `main` automatically deploys the public Mintlify site. Local audit and edit requests do not authorize that production deployment; use the `update-user-facing-docs` workflow and obtain explicit production approval first.
