---
date: {{ .Date }}
# description: ""
# image: ""
lastmod: {{ now.Format "2006-01-02" }}
showTableOfContents: true
# tags: ["",]
title: "{{ replace .File.ContentBaseName `-` ` ` | title }}"
type: "post"
---
