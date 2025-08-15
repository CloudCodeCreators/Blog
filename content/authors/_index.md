---
title: "About Us"
date: 2025-08-15
---

Welcome! We are a team of passionate writers and developers. Learn more about each author below:

{{< rawhtml >}}
<div class="authors-grid grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 max-w-prose mx-auto my-5">
  {{ range .Site.Data.authors }}
    <div class="author-card border p-4 rounded shadow hover:shadow-lg transition">
      <img src="{{ .avatar }}" alt="{{ .name }}" class="w-24 h-24 rounded-full mx-auto">
      <h3 class="mt-4 text-center font-bold">{{ .name }}</h3>
      <p class="mt-2 text-center text-sm text-gray-600">{{ .bio }}</p>
      <p class="mt-2 text-center text-sm">
        {{ with .social.twitter }}<a href="https://twitter.com/{{ . }}" target="_blank">Twitter</a>{{ end }}
        {{ with .social.linkedin }} | <a href="https://linkedin.com/in/{{ . }}" target="_blank">LinkedIn</a>{{ end }}
      </p>
    </div>
  {{ end }}
</div>
{{< /rawhtml >}}
