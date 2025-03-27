---
date: {{ .Date }}
# image: ""
lastmod: {{ now.Format "2006-01-02" }}
showTableOfContents: true
title: "{{ replace .File.ContentBaseName `-` ` ` | title }}"
type: "page"
---
