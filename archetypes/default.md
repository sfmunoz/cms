---
slug: {{ .File.ContentBaseName }}
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
summary: '{{ replace .File.ContentBaseName "-" " " }}'
url: 'tips/:slug'
date: '{{ .Date }}'
categories: ['tips']
tags: [{{ range $k, $v := split .File.ContentBaseName "-" }}{{ if $k }},{{ end }}'{{ $v }}'{{ end }}]
draft: false
---
