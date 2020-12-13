---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
url: {{hmac "sha1" "halin" .Title}}

---

<!-- url: {{hmac "sha1" "halin" .File.TranslationBaseName}} -->
