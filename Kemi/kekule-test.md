---
layout: default
title: Kekule test
---

<h2>Ethanol-test med Kekule.js</h2>

<div id="molviewer" style="width: 300px; height: 200px; border: 1px solid #ccc;"></div>

{% raw %}
<script>
document.addEventListener("DOMContentLoaded", function() {
  const smiles = 'CCO';  // Ethanol
  const mol = Kekule.IO.loadFormatData(smiles, 'smi');
  const viewer = new Kekule.ChemWidget.Viewer(document.getElementById('molviewer'));
  viewer.setChemObj(mol);
});
</script>
{% endraw %}
