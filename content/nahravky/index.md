---
title: "Nahrávky 🎧"
---

### Lekce zdarma 1 – Rotace

<div id="lekce-1-audio">
    <audio controls style="width:100%;" src="File_1.mp3"></audio>
</div>

<div style="text-align:center; margin: 2rem 0;">
  <p>Chcete přístup k dalším nahrávkám?</p>
  <a id="cta-clenska-sekce" href="/clenska-sekce/">Členská sekce</a>
</div>

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
</style>
