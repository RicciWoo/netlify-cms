---
path: "/blog/my-first-post"
date: "2019-05-04"
title: "My first blog post"
---

#### Frontmatter for metadata in markdown files

When you create a Markdown file, you can include a set of key value pairs that can be used to provide additional data relevant to specific pages in the GraphQL data layer. This data is called frontmatter and is denoted by the triple dashes at the start and end of the block. This block will be parsed by 'gatsby-transformer-remark' as 'frontmatter'. The GraphQL API will provide the key value pairs as data in our React components.
