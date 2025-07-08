---
layout: default
title: "Kemi - STX Læringsportal"
---

# ⚗️ Kemi

Velkommen til kemidelen af læringsportalen!

- [Ioner og ionforbindelser](./ioner/index.html)
<div style="text-align: center;">
$$
\ce{Na+, Cl-, SO4^{2-}, NH4+}
$$
</div>
- [Organisk kemi](./organ/index.html)
<div style="text-align: center;">
$$
\ce{CH3COOH + CH3CH2CH2CH2OH \rightleftharpoons CH3COOCH2CH2CH2CH3 + H2O}
$$
</div>

<h3>-</h3>

{% raw %}
<div style="display: flex; align-items: center; gap: 15px;">
  
  <!-- Eddikesyre -->
  <div>
    <div id="aceticAcid" style="width: 180px; height: 150px;"></div>
    <p style="text-align: center;">CH<sub>3</sub>COOH</p>
  </div>
  
  <div style="font-size: 30px;"> + </div>
  
  <!-- Butanol -->
  <div>
    <div id="butanol" style="width: 180px; height: 150px;"></div>
    <p style="text-align: center;">CH<sub>3</sub>CH<sub>2</sub>CH<sub>2</sub>CH<sub>2</sub>OH</p>
  </div>
  
  <div style="font-size: 40px;">→</div>
  
  <!-- Butylacetat -->
  <div>
    <div id="butylAcetate" style="width: 180px; height: 150px;"></div>
    <p style="text-align: center;">CH<sub>3</sub>COOCH<sub>2</sub>CH<sub>2</sub>CH<sub>2</sub>CH<sub>3</sub></p>
  </div>
  
  <div style="font-size: 30px;"> + </div>
  
  <!-- Vand -->
  <div>
    <div id="water" style="width: 100px; height: 150px;"></div>
    <p style="text-align: center;">H<sub>2</sub>O</p>
  </div>
  
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    // Indlæs molekyler med SMILES

    // Eddikesyre
    const aceticAcid = Kekule.IO.loadFormatData('CC(=O)O', 'smi');
    const viewer1 = new Kekule.ChemWidget.Viewer('aceticAcid');
    viewer1.setChemObj(aceticAcid);

    // Butanol (1-butanol)
    const butanol = Kekule.IO.loadFormatData('CCCCO', 'smi');
    const viewer2 = new Kekule.ChemWidget.Viewer('butanol');
    viewer2.setChemObj(butanol);

    // Butylacetat (ester)
    const butylAcetate = Kekule.IO.loadFormatData('CC(=O)OCCCC', 'smi');
    const viewer3 = new Kekule.ChemWidget.Viewer('butylAcetate');
    viewer3.setChemObj(butylAcetate);

    // Vand
    const water = Kekule.IO.loadFormatData('O', 'smi');
    const viewer4 = new Kekule.ChemWidget.Viewer('water');
    viewer4.setChemObj(water);
  });
</script>

{% endraw %}



- [Redoxreaktioner](./redox/index.html)
- Syre-basereaktioner
<div style="text-align: center;">
$$
\ce{CH3COOH + H2O \rightleftharpoons CH3COO- + H3O+}
$$
</div>
- [Kemiske reaktioners hastigheder](./hasti/index.html)
- [Kemisk ligevægte](./ligevaeg/index.html)
- [Fedtstoffer - triglycerider](./fedtst/index.html )

<div style="text-align: center;">
[Tilbage til forsiden](https://jenskaalby.github.io/matkem/) 
</div>

