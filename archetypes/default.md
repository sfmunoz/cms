---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
summary: '{{ replace .File.ContentBaseName "-" " " }}'
url: 'tips/:slug'
date: '{{ .Date }}'
tags: {{ range split .File.ContentBaseName "-" }}
  - {{ . -}}
{{ end }}
draft: false
---
