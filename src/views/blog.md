---
layout: layouts/blog.njk
theme: blog
logo: black
menuTypes: ["navigation"]
footerTypes: []

pagination:
  data: blog-posts
  size: 12
  
#permalink: blog{% if pagination.pageNumber > 0 %}/page{{ pagination.pageNumber + 1}}{% endif %}/index.html
---