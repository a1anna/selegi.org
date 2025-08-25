---
layout: default
title: "Selegi — Currency of the Islands"
---

<!-- Hero Section -->
<section class="hero" style="padding:3rem 1rem;">
  <h1 style="
    display:flex; align-items:center; justify-content:center; gap:14px; margin:0;
    font-size:clamp(2.2rem,5vw,3.4rem);
  ">
    <img
      src="{{ '/assets/images/token.png' | relative_url }}?v={{ site.time | date: '%s' }}"
      alt="Selegi Token"
      style="height:110px; width:auto; vertical-align:middle;"
    >
    <span>Selegi</span>
  </h1>
  <p class="muted" style="font-size:1.15rem; text-align:center; margin-top:.75rem;">
    Secure • Fast • Community-powered currency for the Pacific Islands.
  </p>
</section>


<!-- About Card -->
<div class="card container">
  <h2>Our Token</h2>
  <p>
    The Selegi Token is built to connect communities and power local economies. 
    Designed for remittances, everyday purchases, and community commerce—built 
    on the Stellar network for speed, affordability, and accessibility.
  </p>
  <img src="{{ '/assets/images/token.png' | relative_url }}?v={{ site.time | date: '%s' }}"
       alt="Selegi Token" width="200" style="display:block; margin:1rem auto;">
</div>

<!-- Details Card -->
<div class="card container">
  <h2>Quick Details</h2>
  <ul>
    <li><strong>Issuer (Faiva):</strong> <code>GBXHLUI5ZHKHYMJ3YB55YI5ZD3DOUXODWG2QPB6K5JQKEGZKJDLZR4XY</code></li>
    <li><strong>Asset Code:</strong> SELEGI</li>
    <li><strong>Stellar TOML:</strong> <code>/.well-known/stellar.toml</code></li>
    <li><strong>StellarExpert:</strong> 
      <a href="https://stellar.expert/explorer/public/asset/SELEGI-GBXHLUI5ZHKHYMJ3YB55YI5ZD3DOUXODWG2QPB6K5JQKEGZKJDLZR4XY">
      View SELEGI</a>
    </li>
  </ul>
</div>

<!-- Roadmap Card -->
<div class="card container">
  <h2>Roadmap</h2>
  <ul>
    <li>Stablecoin backing (1:1 reserve)</li>
    <li>Vendor integrations and QR payments</li>
    <li>On/Off ramps for fiat and USDC</li>
  </ul>
</div>

<!-- Footer -->
<footer>
  <img src="{{ '/assets/images/token.png' | relative_url }}?v={{ site.time | date: '%s' }}"
       alt="Selegi Token" />

  <p>© <span id="year"></span> Selegi — Currency of the Islands</p>

  <nav>
    <a href="https://stellar.expert/explorer/public/asset/SELEGI-GBXHLUI5ZHKHYMJ3YB55YI5ZD3DOUXODWG2QPB6K5JQKEGZKJDLZR4XY" target="_blank">
      StellarExpert
    </a>
    ·
    <a href="/.well-known/stellar.toml" target="_blank">Stellar TOML</a>
    ·
    <a href="mailto:contact@selegi.org">Contact</a>
  </nav>

  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</footer>

