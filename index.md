---
layout: default
---

# B FAMILY TREE

{% include family.md %}

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11.6.0/dist/mermaid.esm.min.mjs';
  mermaid.initialize({
    startOnLoad: true,
    theme: 'default'
  });

  document.addEventListener("DOMContentLoaded", () => {
    document.querySelectorAll('a').forEach(a => a.setAttribute('target', '_blank'));
  });
</script>
