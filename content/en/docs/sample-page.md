
---
title: "Sample Page"
linkTitle: "Sample"
weight: 50
---

{{< html >}}
<p style="color: blue">Have a look at the sauce to see how to execute arbitrary scripts with raw html shortcodes</p>
<p id="to-mutate">Old Content Value</p>
<script>
  document.getElementById('to-mutate').innerHTML = 'New Content Value'
</script>
{{< /html >}}

Notice that although it is in the docs root, there isn't a top navbar link because there is no menu:main specified in the frontmatter
