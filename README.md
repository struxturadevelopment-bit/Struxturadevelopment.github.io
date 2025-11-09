# Struxturadevelopment.github.io
<!doctype html>

<html lang="en">  
<head>  
  <meta charset="utf-8" />  
  <meta name="viewport" content="width=device-width,initial-scale=1" />  
  <title>StruxturaDev — Build Your Brand. Own the Web.</title>  
  <link rel="icon" href="https://static.photos/technology/200x200/42" />  
  <script src="https://cdn.tailwindcss.com"></script>  
  <script src="https://unpkg.com/feather-icons"></script>  
  <style>  
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');  
    :root{  
      --accent:#111827;  
      --muted:#6b7280;  
      --card:#ffffff;  
      --bg:#f9fafb;  
    }  
    body{font-family:'Inter',sans-serif;background:var(--bg);color:#0f172a;-webkit-font-smoothing:antialiased}  
    .gradient-text{background:linear-gradient(90deg,#000,#333);-webkit-background-clip:text;background-clip:text;color:transparent}  
    .hover-scale{transition:transform .25s ease;will-change:transform}  
    .hover-scale:hover{transform:translateY(-4px)}  
    .container{max-width:1100px;margin:0 auto;padding:48px 20px}  
    .pp-button{display:inline-flex;align-items:center;gap:.6rem;padding:.7rem 1.1rem;border-radius:10px;text-decoration:none;font-weight:600;border:1px solid rgba(0,0,0,0.08)}  
    .pp-button:focus{outline:3px solid rgba(37,99,235,0.2);outline-offset:2px}  
    .currency-small{font-size:.92rem;color:var(--muted)}  
    .price-local{font-size:1.4rem;font-weight:700}  
    .price-usd{font-size:.95rem;color:#475569}  
    .currency-select{max-width:220px}  
  </style>  
</head>  
<body>  
  <!-- NAV -->  
  <header class="bg-white shadow-sm sticky top-0 z-40">  
    <div class="container flex items-center justify-between">  
      <div class="flex items-center gap-3">  
        <svg class="w-8 h-8 text-black" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M3 7h18M3 17h18M7 3v18" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>  
        <div>  
          <div class="text-lg font-bold">StruxturaDev</div>  
          <div class="text-xs text-gray-500">Build Your Brand. Own the Web.</div>  
        </div>  
      </div>  <nav class="hidden md:flex items-center gap-6 text-sm text-gray-700">  
    <a href="#services" class="hover:text-black">Services</a>  
    <a href="#pricing" class="hover:text-black">Pricing</a>  
    <a href="#portfolio" class="hover:text-black">Portfolio</a>  
    <a href="#contact" class="hover:text-black">Contact</a>  
  </nav>  

  <div class="md:hidden">  
    <button id="menu-btn" aria-label="Open menu" class="p-2">  
      <svg class="w-6 h-6" viewBox="0 0 24 24" fill="none"><path d="M4 6h16M4 12h16M4 18h16" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>  
    </button>  
  </div>  
</div>

  </header>    <!-- HERO -->    <section class="container text-center mt-10">  
    <h1 class="text-3xl md:text-5xl font-extrabold mb-4">Build Your Digital Presence</h1>  
    <p class="text-xl text-gray-600 max-w-2xl mx-auto mb-6">Affordable, professional website design for global customers — primary reference in USD.</p>  
    <p class="text-lg font-semibold mb-6">Build Your Brand. Own the Web.</p>  
    <div class="flex justify-center gap-4">  
      <a href="#pricing" class="bg-black text-white px-6 py-3 rounded-lg hover:opacity-95">View Pricing</a>  
      <a href="#contact" class="border border-black text-black px-6 py-3 rounded-lg">Get a Quote</a>  
    </div>  
  </section>    <!-- SERVICES -->    <section id="services" class="container mt-16">  
    <div class="text-center mb-10">  
      <h2 class="text-2xl font-bold mb-2">Our Service</h2>  
      <p class="text-gray-600 max-w-2xl mx-auto">We focus on fast, modern website design that converts visitors into customers.</p>  
    </div>  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">  
  <div class="p-6 rounded-xl bg-white shadow hover-scale">  
    <div class="w-12 h-12 bg-black text-white rounded-lg flex items-center justify-center mb-4">  
      <i data-feather="monitor" class="w-5 h-5"></i>  
    </div>  
    <h3 class="font-semibold mb-2">Custom Website Design</h3>  
    <p class="text-sm text-gray-600">Tailored, responsive websites that look great on every device.</p>  
  </div>  

  <div class="p-6 rounded-xl bg-white shadow hover-scale">  
    <div class="w-12 h-12 bg-black text-white rounded-lg flex items-center justify-center mb-4">  
      <i data-feather="refresh-ccw" class="w-5 h-5"></i>  
    </div>  
    <h3 class="font-semibold mb-2">Speed & Performance</h3>  
    <p class="text-sm text-gray-600">Optimised for fast loading and great SEO foundations.</p>  
  </div>  

  <div class="p-6 rounded-xl bg-white shadow hover-scale">  
    <div class="w-12 h-12 bg-black text-white rounded-lg flex items-center justify-center mb-4">  
      <i data-feather="tool" class="w-5 h-5"></i>  
    </div>  
    <h3 class="font-semibold mb-2">Support & Maintenance</h3>  
    <p class="text-sm text-gray-600">Ongoing support packages, hosting and optional add-ons available.</p>  
  </div>  
</div>

  </section>    <!-- PORTFOLIO -->    <section id="portfolio" class="container mt-16">  
    <div class="text-center mb-8">  
      <h2 class="text-2xl font-bold">Selected Work</h2>  
      <p class="text-gray-600">Some sites we've built for local businesses.</p>  
    </div>  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">  
  <div class="bg-white rounded-xl overflow-hidden shadow hover-scale">  
    <img src="https://static.photos/technology/640x360/1" alt="Cafe Website" class="w-full h-44 object-cover">  
    <div class="p-4">  
      <h4 class="font-semibold">Cafe Website</h4>  
      <p class="text-sm text-gray-600">Menu, contact & bookings for a Cape Town coffee shop.</p>  
    </div>  
  </div>  

  <div class="bg-white rounded-xl overflow-hidden shadow hover-scale">  
    <img src="https://static.photos/retail/640x360/2" alt="Fashion Store" class="w-full h-44 object-cover">  
    <div class="p-4">  
      <h4 class="font-semibold">Local Boutique</h4>  
      <p class="text-sm text-gray-600">Simple catalog and WhatsApp integration for sales.</p>  
    </div>  
  </div>  

  <div class="bg-white rounded-xl overflow-hidden shadow hover-scale">  
    <img src="https://static.photos/workspace/640x360/3" alt="Consulting Firm" class="w-full h-44 object-cover">  
    <div class="p-4">  
      <h4 class="font-semibold">Consulting Firm</h4>  
      <p class="text-sm text-gray-600">Professional services website built for trust.</p>  
    </div>  
  </div>  
</div>

  </section>    <!-- PRICING with currency system -->    <section id="pricing" class="container mt-16">  
    <div class="flex flex-col md:flex-row items-center justify-between mb-6 gap-4">  
      <div>  
        <h2 class="text-2xl font-bold">Simple Pricing — USD Primary</h2>  
        <p class="text-gray-600">Base prices are in USD. Prices below auto-convert to visitor currency (ZAR is not shown).</p>  
      </div>  <div class="flex items-center gap-3">  
    <label for="currency-select" class="text-sm text-gray-600">Show prices in</label>  
    <select id="currency-select" class="currency-select border rounded px-3 py-2">  
      <!-- Options will be injected by JS -->  
    </select>  
  </div>  
</div>  

<div class="grid grid-cols-1 md:grid-cols-3 gap-6">  
  <!-- Starter -->  
  <div class="bg-white rounded-xl p-6 shadow hover-scale flex flex-col">  
    <div class="mb-4">  
      <h3 class="text-xl font-semibold">Starter</h3>  
      <div class="text-2xl font-bold mt-2" id="starter-local">—</div>  
      <div class="price-usd mt-1" id="starter-usd">$350 in USD</div>  
    </div>  
    <ul class="text-sm text-gray-600 mb-6 space-y-2 flex-grow">  
      <li>1–3 Page Website</li>  
      <li>Mobile Responsive</li>  
      <li>Basic contact form</li>  
      <li>One round of revisions</li>  
    </ul>  

    <a id="starter-pay" class="pp-button bg-white border-gray-200 hover:shadow-sm" target="_blank" rel="noopener noreferrer" href="https://www.paypal.me/PrinceShoko603/350USD">  
      Pay $350  
    </a>  
  </div>  

  <!-- Professional -->  
  <div class="bg-white rounded-xl p-6 shadow-lg border-2 border-blue-500 hover-scale flex flex-col">  
    <div class="mb-4">  
      <h3 class="text-xl font-semibold">Professional</h3>  
      <div class="text-2xl font-bold mt-2" id="pro-local">—</div>  
      <div class="price-usd mt-1" id="pro-usd">$700 in USD</div>  
    </div>  
    <ul class="text-sm text-gray-600 mb-6 space-y-2 flex-grow">  
      <li>Up to 5 Pages</li>  
      <li>Advanced layout & copy support</li>  
      <li>Speed & basic SEO setup</li>  
      <li>WhatsApp or contact integration</li>  
    </ul>  

    <a id="pro-pay" class="pp-button" target="_blank" rel="noopener noreferrer" href="https://www.paypal.me/PrinceShoko603/700USD">Pay $700</a>  
  </div>  

  <!-- Premium -->  
  <div class="bg-white rounded-xl p-6 shadow hover-scale flex flex-col">  
    <div class="mb-4">  
      <h3 class="text-xl font-semibold">Premium</h3>  
      <div class="text-2xl font-bold mt-2" id="premium-local">—</div>  
      <div class="price-usd mt-1" id="premium-usd">$900 in USD</div>  
    </div>  
    <ul class="text-sm text-gray-600 mb-6 space-y-2 flex-grow">  
      <li>Full custom website (up to 8 pages)</li>  
      <li>Easier future expansion (shop add-ons available)</li>  
      <li>Analytics & conversion tracking setup</li>  
      <li>Priority support & one month of tweaks</li>  
    </ul>  

    <a id="premium-pay" class="pp-button" target="_blank" rel="noopener noreferrer" href="https://www.paypal.me/PrinceShoko603/900USD">Pay $900</a>  
  </div>  
</div>  

<p class="text-xs text-gray-500 mt-4">Note: the Pay buttons open your PayPal.me link with the USD amount. PayPal may display currency conversion options to the payer.</p>

  </section>    <!-- CONTACT -->    <section id="contact" class="container mt-16 mb-20">  
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-start">  
      <div>  
        <h2 class="text-2xl font-bold mb-3">Let's talk about your site</h2>  
        <p class="text-gray-600 mb-6">Free consultation & tailored quote. Proudly based in Johannesburg.</p>  <div class="space-y-4">  
      <div class="flex items-start gap-3">  
        <div class="bg-black text-white p-3 rounded-lg"><i data-feather="mail" class="w-4 h-4"></i></div>  
        <div>  
          <div class="text-xs text-gray-500">Email</div>  
          <div class="font-medium">struxturadev.co.za</div>  
        </div>  
      </div>  

      <div class="flex items-start gap-3">  
        <div class="bg-black text-white p-3 rounded-lg"><i data-feather="phone" class="w-4 h-4"></i></div>  
        <div>  
          <div class="text-xs text-gray-500">Phone</div>  
          <div class="font-medium">+27 68 983 0346</div>  
          <div class="font-medium">+27 61 032 0177</div>  
        </div>  
      </div>  

      <div class="flex items-start gap-3">  
        <div class="bg-black text-white p-3 rounded-lg"><i data-feather="map-pin" class="w-4 h-4"></i></div>  
        <div>  
          <div class="text-xs text-gray-500">Location</div>  
          <div class="font-medium">Johannesburg, South Africa</div>  
        </div>  
      </div>  
    </div>  
  </div>  

  <div class="bg-white p-6 rounded-xl shadow">  
    <form id="contact-form">  
      <div class="mb-3">  
        <label class="text-sm font-medium">Name</label>  
        <input type="text" id="name" class="w-full border rounded px-3 py-2 mt-1" placeholder="Your name" required>  
      </div>  
      <div class="mb-3">  
        <label class="text-sm font-medium">Email</label>  
        <input type="email" id="email" class="w-full border rounded px-3 py-2 mt-1" placeholder="you@example.com" required>  
      </div>  
      <div class="mb-3">  
        <label class="text-sm font-medium">Message</label>  
        <textarea id="message" rows="4" class="w-full border rounded px-3 py-2 mt-1" placeholder="Tell us about your project" required></textarea>  
      </div>  
      <button type="submit" class="w-full bg-black text-white py-2 rounded">Send Message</button>  
    </form>  
  </div>  
</div>

  </section>    <!-- FOOTER -->    <footer class="bg-black text-white py-8">  
    <div class="container flex flex-col md:flex-row justify-between items-center">  
      <div class="mb-4 md:mb-0">  
        <div class="font-bold">StruxturaDev</div>  
        <div class="text-xs text-gray-300">Affordable websites for global customers</div>  
      </div>  
      <div class="text-xs text-gray-300">© <span id="year"></span> StruxturaDev. All rights reserved.</div>  
    </div>  
  </footer>    <script>  
    // ---------- CONFIG ----------  
    const PAYPAL_ME = "https://www.paypal.me/PrinceShoko603";  
    // Base USD prices (as you provided)  
    const PRICES_USD = {  
      starter: 350,  
      pro: 700,  
      premium: 900  
    };  
  
    // Supported currencies (full 21 + USD)  
    const SUPPORTED = [  
      "USD","AUD","CAD","CHF","CZK","DKK","EUR","GBP","HKD","HUF","ILS","JPY",  
      "MXN","NOK","NZD","PHP","PLN","RUB","SEK","SGD","THB","TWD"  
    ];  
  
    // A small map for Intl.NumberFormat locales & options where needed  
    const CURRENCY_FORMAT_OVERRIDES = {  
      "HUF": { maximumFractionDigits: 0, minimumFractionDigits: 0 },  
      "JPY": { maximumFractionDigits: 0, minimumFractionDigits: 0 },  
      "TWD": { maximumFractionDigits: 0, minimumFractionDigits: 0 }  
    };  
  
    // ---------- DOM ----------  
    const currencySelect = document.getElementById('currency-select');  
    const starterLocal = document.getElementById('starter-local');  
    const proLocal = document.getElementById('pro-local');  
    const premiumLocal = document.getElementById('premium-local');  
    const starterUsd = document.getElementById('starter-usd');  
    const proUsd = document.getElementById('pro-usd');  
    const premiumUsd = document.getElementById('premium-usd');  
    const starterPay = document.getElementById('starter-pay');  
    const proPay = document.getElementById('pro-pay');  
    const premiumPay = document.getElementById('premium-pay');  
  
    // ---------- UTIL ----------  
    function formatCurrency(amount, currencyCode) {  
      const opts = { style: 'currency', currency: currencyCode };  
      const override = CURRENCY_FORMAT_OVERRIDES[currencyCode];  
      if (override) Object.assign(opts, override);  
      try {  
        // Use undefined locale so browser picks a suitable one, which is fine for display  
        return new Intl.NumberFormat(undefined, opts).format(amount);  
      } catch (e) {  
        // fallback simple  
        return `${currencyCode} ${amount.toFixed(2)}`;  
      }  
    }  
  
    function toTwoDecimals(n) {  
      return Math.round(n * 100) / 100;  
    }  
  
    // ---------- Rates & Geo ----------  
    let rates = { USD: 1.0 }; // fallback  
    let visitorCurrency = "USD";  
  
    async function fetchRates() {  
      try {  
        const res = await fetch('https://api.exchangerate-api.com/v4/latest/USD', { cache: "no-store" });  
        if (!res.ok) throw new Error('Rate fetch failed');  
        const data = await res.json();  
        rates = data.rates || rates;  
      } catch (err) {  
        console.warn('Exchange rate API failed — using fallback rates (USD only).', err);  
        rates = { USD: 1.0 };  
      }  
    }  
  
    async function detectVisitorCurrency() {  
      try {  
        // ipapi.co returns JSON with currency field, no key required for basic access  
        const res = await fetch('https://ipapi.co/json/');  
        if (!res.ok) throw new Error('IP detect failed');  
        const data = await res.json();  
        const cur = (data.currency || "USD").toUpperCase();  
        if (SUPPORTED.includes(cur)) return cur;  
        return "USD";  
      } catch (err) {  
        console.warn('IP detection failed, defaulting to USD', err);  
        return "USD";  
      }  
    }  
  
    // ---------- UI update ----------  
    function updateDisplayedPrices(chosenCurrency) {  
      const rate = rates[chosenCurrency] ? rates[chosenCurrency] : null;  
      // If rate is missing, fall back to USD display  
      if (!rate) {  
        // show USD amounts only  
        starterLocal.textContent = formatCurrency(PRICES_USD.starter, 'USD');  
        proLocal.textContent = formatCurrency(PRICES_USD.pro, 'USD');  
        premiumLocal.textContent = formatCurrency(PRICES_USD.premium, 'USD');  
      } else {  
        // Convert USD -> targetCurrency (amount_in_target = USD_amount * rate[target])  
        const sLocal = toTwoDecimals(PRICES_USD.starter * rate);  
        const pLocal = toTwoDecimals(PRICES_USD.pro * rate);  
        const pmLocal = toTwoDecimals(PRICES_USD.premium * rate);  
  
        starterLocal.textContent = formatCurrency(sLocal, chosenCurrency);  
        proLocal.textContent = formatCurrency(pLocal, chosenCurrency);  
        premiumLocal.textContent = formatCurrency(pmLocal, chosenCurrency);  
      }  
  
      // USD lines (always show)  
      starterUsd.textContent = `$${PRICES_USD.starter} in USD`;  
      proUsd.textContent = `$${PRICES_USD.pro} in USD`;  
      premiumUsd.textContent = `$${PRICES_USD.premium} in USD`;  
  
      // Update PayPal links to use USD amounts (append currency code to paypal.me)  
      starterPay.href = `${PAYPAL_ME}/${PRICES_USD.starter}USD`;  
      proPay.href = `${PAYPAL_ME}/${PRICES_USD.pro}USD`;  
      premiumPay.href = `${PAYPAL_ME}/${PRICES_USD.premium}USD`;  
    }  
  
    // ---------- Dropdown population ----------  
    function populateCurrencyDropdown() {  
      // Clear  
      currencySelect.innerHTML = '';  
      // Add USD first  
      SUPPORTED.forEach(code => {  
        const opt = document.createElement('option');  
        opt.value = code;  
        opt.textContent = code;  
        currencySelect.appendChild(opt);  
      });  
    }  
  
    // ---------- Initialization ----------  
    async function initCurrencySystem() {  
      populateCurrencyDropdown();  
      await fetchRates();  
      const detected = await detectVisitorCurrency();  
  
      // Load user chosen from localStorage if present  
      const stored = localStorage.getItem('struxtura_currency');  
      visitorCurrency = stored || detected || "USD";  
      if (!SUPPORTED.includes(visitorCurrency)) visitorCurrency = "USD";  
  
      currencySelect.value = visitorCurrency;  
      updateDisplayedPrices(visitorCurrency);  
  
      // on change -> update and save  
      currencySelect.addEventListener('change', (e) => {  
        const chosen = e.target.value;  
        if (SUPPORTED.includes(chosen)) {  
          visitorCurrency = chosen;  
          localStorage.setItem('struxtura_currency', chosen);  
          updateDisplayedPrices(chosen);  
        }  
      });  
  
      // If rates update later, you could refresh periodically  
    }  
  
    // ---------- Boot ----------  
    document.getElementById('year').textContent = new Date().getFullYear();  
    document.querySelectorAll('[href^="#"]').forEach(a=>{  
      a.addEventListener('click', e=>{  
        e.preventDefault();  
        const t = document.querySelector(a.getAttribute('href'));  
        if(t) t.scrollIntoView({behavior:'smooth'});  
      });  
    });  
    feather && feather.replace();  
  
    // Contact form demo handler  
    document.getElementById('contact-form').addEventListener('submit', function(e){  
      e.preventDefault();  
      alert('Thanks — message received! I can hook this up to email or Airtable when you want.');  
      this.reset();  
    });  
  
    // Start  
    initCurrencySystem();  
  
  </script>  </body>  
        </html> 
