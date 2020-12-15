---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
url: {{ sha1 .File.TranslationBaseName}}
---

