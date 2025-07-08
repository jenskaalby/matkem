---
layout: default
title: "Test af Kekule.js"
---

# Test af Kekule.js

<div id="molviewer" style="width: 300px; height: 200px; border: 1px solid #ccc;"></div>

{% raw %}
<script>
  document.addEventListener("DOMContentLoaded", function() {
    const mol = Kekule.IO.loadFormatData('CCO', 'smi'); // Etanol som testmolekyle
    const viewer = new Kekule.ChemWidget.Viewer(document.getElementById('molviewer'));
    viewer.setChemObj(mol);
  });
</script>
{% endraw %}
