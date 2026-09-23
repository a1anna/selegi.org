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
    BUILT ON STELLAR • INSPIRED BY THE PACIFIC • MADE FOR COMMUNITY
  </p>
</section>


<!-- About Card -->
<div class="card container">
  <h2>What is SELEGI?</h2>

  <p>
    SELEGI is an experimental digital asset built on the Stellar network,
    exploring faster and more accessible ways for Pacific communities to
    connect, exchange value, and participate in digital commerce.
  </p>

  <p>
    The project is currently in its early beta stage as we develop the
    technology, community, and real-world use cases behind SELEGI.
  </p>

  <img
    src="{{ '/assets/images/token.png' | relative_url }}?v={{ site.time | date: '%s' }}"
    alt="Selegi Token"
    width="200"
    style="display:block; margin:1rem auto;"
  >
</div>


<!-- Details Card -->
<div class="card container">
  <h2>SELEGI on Stellar</h2>

  <ul>
    <li>
      <strong>Network:</strong> Stellar Mainnet
    </li>

    <li>
      <strong>Asset Code:</strong> SELEGI
    </li>

    <li>
      <strong>Issuer (Faiva):</strong>
      <code>GBXHLUI5ZHKHYMJ3YB55YI5ZD3DOUXODWG2QPB6K5JQKEGZKJDLZR4XY</code>
    </li>

    <li>
      <strong>Stellar TOML:</strong>
      <a href="/.well-known/stellar.toml" target="_blank">
        View Asset Metadata
      </a>
    </li>

    <li>
      <strong>Blockchain Explorer:</strong>
      <a
        href="https://stellar.expert/explorer/public/asset/SELEGI-GBXHLUI5ZHKHYMJ3YB55YI5ZD3DOUXODWG2QPB6K5JQKEGZKJDLZR4XY"
        target="_blank"
      >
        View SELEGI on StellarExpert
      </a>
    </li>
  </ul>
</div>


<!-- Vision Card -->
<div class="card container">
  <h2>Where We're Going</h2>

  <p>
    SELEGI is being developed with a simple idea: explore how blockchain
    technology can make digital commerce more accessible and useful for
    Pacific communities.
  </p>

  <ul>
    <li>Explore community payments and peer-to-peer transfers</li>
    <li>Develop simple QR-based payment experiences</li>
    <li>Explore connections between SELEGI, XLM, USDC, and other digital assets</li>
    <li>Build partnerships and practical real-world use cases</li>
  </ul>
</div>


<!-- Beta Notice -->
<div class="card container">
  <h2>Early Beta</h2>

  <p>
    SELEGI is an early-stage experimental project. Features, economics,
    availability, and future uses may change as the project develops.
    SELEGI is not currently represented as a bank deposit, guaranteed
    investment, or redeemable 1:1 stablecoin.
  </p>
</div>


<!-- Footer -->
<footer>
  <img
    src="{{ '/assets/images/token.png' | relative_url }}?v={{ site.time | date: '%s' }}"
    alt="Selegi Token"
  />

  <p>© <span id="year"></span> Selegi — Currency of the Islands</p>

  <nav>
    <a
      href="https://stellar.expert/explorer/public/asset/SELEGI-GBXHLUI5ZHKHYMJ3YB55YI5ZD3DOUXODWG2QPB6K5JQKEGZKJDLZR4XY"
      target="_blank"
    >
      StellarExpert
    </a>
    ·
    <a href="/.well-known/stellar.toml" target="_blank">
      Stellar TOML
    </a>
    ·
    <a href="mailto:contact@selegi.org">
      Contact
    </a>
  </nav>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</footer>
