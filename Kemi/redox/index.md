---
layout: default
title: Introduktion til redoxreaktioner
---

# 🔬 Introduktion til oxidation og reduktion

En **redoxreaktion** er en kemisk reaktion, hvor der både sker en **oxidation** og en **reduktion**.

- **Oxidation**: Et stof **afgiver elektroner.**
- **Reduktion**: Et stof **optager elektroner.**

Ved en redoxreaktion sker der en overførsel af elektroner. Således er der ved en redoxreaktion et stof der oxideres og et stof der reduceres.

## Eksempel: Reaktion mellem magnesium og dioxygen

$$
2 \, \mathrm{Mg}{(s)} + \mathrm{O}_2{(g)} \rightarrow 2 \, \mathrm{MgO}{(s)}
$$

<div>
  <p> $ a^2 + b^2 = c^2 $</p>
  <p>Og en displayformel ...:</p>
  $$ E = mc^2 $$
</div>

Vi kan skrive dette som to **delreaktioner**, som gør det mere tydeligt, hvad der sker:

<div style="display:flex; gap: 30px; margin-bottom: 20px;">
  <div style="flex:1; background:#fdecea; padding:15px; border-radius:6px;">
    <h3>🔴 Oxidation</h3>
    <p> <span class="math">$ 2 \, \mathrm{Mg} \rightarrow 2 \, \mathrm{Mg}^{2+} + 4 e^- $ </span> </p>
  </div>
  <div style="flex:1; background:#e9f7ef; padding:15px; border-radius:6px;">
    <h3>🟢 Reduktion</h3>
    <p>$ \mathrm{O}_2 + 4 e^- \rightarrow 2 \, \mathrm{O}^{2-} $</p>
  </div>
</div>

**Her kan vi se at:**

- Magnesium oxideres, fordi magnesium ved reaktionen **afgiver elektroner**.
- Oxygen reduceres, fordi oxygen ved reaktionen **optager elektroner**.

---

## Opgaver: Skriv og forklar delreaktionerne ved redoxreaktioner

Start med at løse opgaverne på papir. Skriv derefter løsningsforslaget ind med den specielle notation, som man kan se i sidebaren til venstre. Tjek om svaret er rigtigt.

<!-- Opgave 1 -->
<div class="task">
  <h3>Opgave 1: Magnesium og kobber(II)ion</h3>
  <p>\( \mathrm{Mg} + \mathrm{Cu}^{2+} \rightarrow \mathrm{Mg}^{2+} + \mathrm{Cu} \)</p>

  <label for="ox1">Skriv oxidation (delreaktion):</label><br />
  <input type="text" id="ox1" placeholder="fx Mg -> Mg^2+ + 2e^-" />

  <label for="red1">Skriv reduktion (delreaktion):</label><br />
  <input type="text" id="red1" placeholder="fx Cu^2+ + 2e^- -> Cu" />

  <button onclick="checkOpgave1()">Tjek svar – opgave 1</button>

  <div id="feedback1" class="feedback"></div>
</div>

<!-- Opgave 2 -->
<div class="task">
  <h3>Opgave 2: Zink og kobber(II)ion</h3>
  <p>\( \mathrm{Zn} + \mathrm{Cu}^{2+} \rightarrow \mathrm{Zn}^{2+} + \mathrm{Cu} \)</p>

  <label for="sam2">Skriv samlet reaktion:</label><br />
  <input type="text" id="sam2" placeholder="fx Zn + Cu^2+ -> Zn^2+ + Cu" />

  <label for="ox2">Skriv oxidationsdelreaktionen:</label><br />
  <input type="text" id="ox2" placeholder="fx Zn -> Zn^2+ + 2e^-" />

  <label for="red2">Skriv reduktionsdelreaktionen:</label><br />
  <input type="text" id="red2" placeholder="fx Cu^2+ + 2e^- -> Cu" />

  <button onclick="checkOpgave2()">Tjek svar – opgave 2</button>

  <div id="feedback2" class="feedback"></div>
</div>

---

<!-- Opgave 4 -->
<div class="task">
  <h3>Opgave 4: Oxidationstal i Mg + S → MgS</h3>
  <p>Indtast oxidationstallene som hele tal (fx -2, 0, 2).</p>

  <label for="mgf">Mg (før):</label><br />
  <input type="text" id="mgf" placeholder="fx 0" />

  <label for="sf">S (før):</label><br />
  <input type="text" id="sf" placeholder="fx 0" />

  <label for="mga">Mg i MgS:</label><br />
  <input type="text" id="mga" placeholder="fx 2" />

  <label for="sa">S i MgS:</label><br />
  <input type="text" id="sa" placeholder="fx -2" />

  <button onclick="checkOpgave4()">Tjek oxidationstal – opgave 4</button>

  <div id="feedback4" class="feedback"></div>
</div>

---

<!-- Opgave 5 -->
<div class="task">
  <h3>Opgave 5: Oxidationstal i Zn + Cu²⁺ → Zn²⁺ + Cu</h3>
  <p>Indtast oxidationstallene som hele tal (fx -2, 0, 2). Felterne starter tomme.</p>

  <label for="znf">Zn (før):</label><br />
  <input type="text" id="znf" placeholder="fx 0" />

  <label for="cuf">Cu (før):</label><br />
  <input type="text" id="cuf" placeholder="fx 2" />

  <label for="zna">Zn i Zn²⁺:</label><br />
  <input type="text" id="zna" placeholder="fx 2" />

  <label for="cua">Cu i Cu:</label><br />
  <input type="text" id="cua" placeholder="fx 0" />

  <button onclick="checkOpgave5()">Tjek oxidationstal – opgave 5</button>

  <div id="feedback5" class="feedback"></div>
</div>
