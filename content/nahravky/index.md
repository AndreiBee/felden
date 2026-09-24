---
title: "Nahrávky 🎧"
---

### Lekce zdarma – Hrudník

<div id="lekce-1-audio">
    <audio controls controlsList="nodownload" style="width:100%;" src="File_03.mp3"></audio>
</div>

### Lekce zdarma – Pánev

<div id="lekce-1-audio">
    <audio controls controlsList="nodownload" style="width:100%;" src="File_02.mp3"></audio>
</div>

### Lekce zdarma – Rotace

<div id="lekce-1-audio">
    <audio controls controlsList="nodownload" style="width:100%;" src="File_01.mp3"></audio>
</div>

<div style="text-align:center; margin: 2rem 0;">
  <p>Chcete přístup k dalším nahrávkám?</p>
  <a id="cta-clenska-sekce" href="/clenska-sekce/">Členská sekce</a>
</div>

<details class="access-info">
  <summary>
    <span>Jak získat přístup do placené sekce?</span>
    <svg class="chevron" viewBox="0 0 24 24" width="18" height="18" aria-hidden="true"><path d="M6 9l6 6 6-6" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
  </summary>
  <ol>
    <li>Zaplaťte <strong>200 Kč</strong> pomocí QR kódu níže.<br><img src="qr.png" alt="QR kód pro platbu 200 Kč" class="qr-code"></li>
    <li>Do zprávy pro příjemce (poznámka k platbě) uveďte <strong>e-mailovou adresu</strong>, kterou chcete používat pro přihlášení do placené sekce.</li>
    <li>Jakmile platbu spárujeme, přidáme váš e-mail na seznam povolených uživatelů.</li>
    <li>Na stránce <a href="/clenska-sekce/">Členská sekce</a> zadejte stejný e-mail – přijde vám na něj 6místný přihlašovací kód, který zadáte do okna Cloudflare.</li>
    <li>Po zadání kódu si vás toto zařízení na pár dní zapamatuje, takže e-mail nebudete muset zadávat znovu při každé návštěvě.</li>
  </ol>
</details>

<style>
#lekce-1-audio audio {
  width: 100%;
  display: block;
}
.max-w-fit:has(#lekce-1-audio) {
  max-width: none;
  width: 100%;
}
#cta-clenska-sekce {
  display: inline-block;
  padding: 0.9rem 2.4rem;
  border-radius: 999px;
  background: linear-gradient(135deg, rgb(var(--color-primary-500)), rgb(var(--color-secondary-600)));
  color: #fff;
  font-weight: 700;
  font-size: 1.15rem;
  text-decoration: none;
  box-shadow: 0 8px 24px rgba(0,0,0,0.25);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
#cta-clenska-sekce:hover {
  transform: translateY(-3px) scale(1.03);
  box-shadow: 0 12px 32px rgba(0,0,0,0.3);
  color: #fff;
}
#cta-clenska-sekce:active {
  transform: translateY(-1px) scale(1);
}

.access-info {
  max-width: 32rem;
  margin: 0.5rem auto 2rem;
  border: 1px solid rgb(var(--color-primary-500) / 0.35);
  border-radius: 1rem;
  padding: 0.9rem 1.2rem;
}
.access-info summary {
  cursor: pointer;
  list-style: none;
  display: flex;
  align-items: center;
  justify-content: space-between;
  font-weight: 700;
  color: rgb(var(--color-primary-600));
}
.access-info summary::-webkit-details-marker { display: none; }
.access-info .chevron { transition: transform 0.2s ease; flex-shrink: 0; margin-left: 0.75rem; }
.access-info[open] .chevron { transform: rotate(180deg); }
.access-info ol { margin: 1rem 0 0; padding-left: 1.25rem; }
.access-info li { margin-bottom: 0.75rem; }
.access-info li:last-child { margin-bottom: 0; }
.access-info .qr-code { display: block; max-width: 200px; margin-top: 0.5rem; border-radius: 0.5rem; }
</style>
