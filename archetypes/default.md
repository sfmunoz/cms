---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
summary: '{{ replace .File.ContentBaseName "-" " " }}'
date: '{{ .Date }}'
tags: {{ range split .File.ContentBaseName "-" }}
  - {{ . -}}
{{ end }}
draft: false
---
