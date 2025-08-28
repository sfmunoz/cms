# CMS

Content Management System involving:

- https://github.com/sfmunoz/sfmunoz.github.io
- https://github.com/sfmunoz/content

Contents:

- [References](#references)
- [Development](#development)

## References

- https://gohugo.io/
- https://github.com/gohugoio/hugo

## Development

Standalone server:

```
$ hugo server -D --disableFastRender --noHTTPCache -t standalone
```

Options:

```
$ hugo server -h
(...)
Flags:
(...)
  -D, --buildDrafts        include content marked as draft
(...)
  --disableFastRender      enables full re-renders on changes
(...)
  --noHTTPCache            prevent HTTP caching
(...)
  -t, --theme strings      themes to use (located in /themes/THEMENAME/)
(...)
```
