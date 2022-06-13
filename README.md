## [Create new page with different archetypes](https://discourse.gohugo.io/t/create-new-page-with-different-archetypes/32560)

Assuming you have this structure,

├── archetypes
│   ├── default.md
│   ├── post.md
│   └── page.md
├── content
│   ├── pages
│   │   └── page1.md
│   └── posts
│       └── post1.md

You can use the -k flag like this to create new files with a specific archetype:

hugo new -k post posts/post2.md
hugo new -k page pages/page2.md


