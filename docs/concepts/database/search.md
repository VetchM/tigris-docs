# Search Operations

Tigris can automatically create a search indexes for database collections and
manage synchronizing collections from the database into a search index.

Search operations support the following features:

- **Full-text search**: Ability to perform full-text search queries on the
  collections
- **Faceted search**: Ability to perform facet query to aggregate search results
  by fields.
- **Searching on nested fields**: Ability to perform search on nested fields
- **Projection**: Ability to include or exclude fields that are not needed in
  the result

Tigris TypeScript SDK provides the following API to search documents in a
collection:

- [search()](../../sdkstools/typescript/database/search.mdx#searching-for-documents):
  search for one or more documents in a collection

See the [Filters](filters.md) section to learn more about the filters supported
in search operations.

See the language-specific sections for more examples of Search operations:

- [Search in TypeScript](../../sdkstools/typescript/search/index.mdx)
- [Search in Go](../../sdkstools/golang/database/search.mdx)
- [Search in Java](../../sdkstools/java/database/search.mdx)
