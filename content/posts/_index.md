---
title: Blog
showTableOfContents: False
---
<html>
<div class="flex flex-row flex-wrap items-center">
  {{/* Output partials */}}
  {{ with ($meta.Get "partials") }}
  {{ delimit . "<span class=\"px-2 text-primary-500\">&middot;</span>" }}
  {{ end }}
</div>
</html>
Find more [about me and the blog here]({{< ref "about" >}}).
