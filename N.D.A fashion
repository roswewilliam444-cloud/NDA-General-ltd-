<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>N.D.A Company Ltd | Premium Fashion & Uniform Marketplace</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    :root {
      --amazon-dark: #131921;
      --amazon-nav: #232F3E;
      --amazon-accent: #FF9900;
      --gold: #dfb76c;
      --gold-hover: #f3cf8a;
      --bg-dark: #0f1111; /* Amazon dark background structure */
      --card-bg: #1a1a1a;
      --text-muted: #a0a0a0;
      --whatsapp-green: #25D366;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      background: var(--bg-dark);
      color: #ffffff;
      line-height: 1.4;
    }

    /* --- Amazon Style Universal Navigation Core --- */
    .amazon-main-header {
      background: var(--amazon-dark);
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .brand-logo {
      color: #ffffff;
      font-size: 20px;
      font-weight: 800;
      text-decoration: none;
      letter-spacing: 1.5px;
      white-space: nowrap;
    }

    .brand-logo span {
      color: var(--amazon-accent);
    }

    .amazon-search-bar {
      flex-grow: 1;
      max-width: 700px;
      display: flex;
      background: #ffffff;
      border-radius: 4px;
      overflow: hidden;
    }

    .amazon-search-bar:focus-within {
      box-shadow: 0 0 0 2px var(--amazon-accent);
    }

    .search-input {
      width: 100%;
      border: none;
      padding: 10px 15px;
      font-size: 14px;
      outline: none;
      color: #111;
    }

    .search-button {
      background: #febd69;
      border: none;
      width: 45px;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 16px;
    }

    .search-button:hover {
      background: #f3a847;
    }

    .user-nav-modules {
      display: flex;
      gap: 15px;
    }

    .nav-box {
      color: #ffffff;
      text-decoration: none;
      font-size: 14px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }

    .nav-box .line-1 {
      font-size: 11px;
      color: #cccccc;
    }

    .nav-box .line-2 {
      font-weight: 700;
    }

    /* --- Amazon Category Utility Belt --- */
    .amazon-sub-nav {
      background: var(--amazon-nav);
      padding: 8px 20px;
      display: flex;
      gap: 15px;
      overflow-x: auto;
      white-space: nowrap;
    }

    .amazon-sub-nav a {
      color: #ffffff;
      text-decoration: none;
      font-size: 13px;
      font-weight: 500;
    }

    .amazon-sub-nav a:hover {
      border-bottom: 1px solid #ffffff;
    }

    /* --- Hero Banner Layout --- */
    .store-banner {
      padding: 40px 20px;
      text-align: center;
      background: linear-gradient(180deg, rgba(35,47,62,0.8) 0%, rgba(15,17,17,1) 100%);
      border-bottom: 1px solid #222;
    }

    .store-banner h1 {
      margin: 0;
      font-size: 32px;
      font-weight: 700;
      color: #ffffff;
    }

    .store-banner p {
      color: var(--gold);
      margin-top: 8px;
      font-size: 15px;
      letter-spacing: 1px;
      text-transform: uppercase;
    }

    /* --- Grid & Content Blocks --- */
    .main-marketplace-container {
      max-width: 1400px;
      margin: 0 auto;
      padding: 20px;
    }

    .department-header {
      font-size: 21px;
      font-weight: 700;
      margin: 30px 0 15px 0;
      color: #ffffff;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .department-header span {
      font-size: 14px;
      font-weight: 400;
      color: var(--text-muted);
    }

    .marketplace-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
      gap: 20px;
      margin-bottom: 40px;
    }

    /* --- The Amazon Product Card Structure --- */
    .product-box {
      background: var(--card-bg);
      border: 1px solid #252525;
      border-radius: 4px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      transition: border-color 0.15s;
    }

    .product-box:hover {
      border-color: var(--amazon-accent);
    }

    .product-image-frame {
      width: 100%;
      height: 260px;
      background: #111;
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .product-image-frame img {
      max-width: 100%;
      max-height: 100%;
      object-fit: cover;
      width: 100%;
      height: 100%;
    }

    .product-details {
      padding: 15px;
      display: flex;
      flex-direction: column;
      flex-grow: 1;
    }

    .product-title {
      font-size: 15px;
      font-weight: 500;
      color: #ffffff;
      margin: 0 0 6px 0;
      line-height: 1.3;
      height: 40px;
      overflow: hidden;
      display: -webkit-box;
      -webkit-line-clamp: 2;
      -webkit-box-orient: vertical;
    }

    .marketplace-rating {
      color: #ff9900;
      font-size: 13px;
      margin-bottom: 8px;
    }

    .marketplace-rating span {
      color: var(--gold);
      margin-left: 4px;
    }

    .marketplace-price-tag {
      font-size: 18px;
      font-weight: 700;
      color: #ffffff;
      margin-bottom: 15px;
    }

    .marketplace-price-tag span {
      font-size: 12px;
      color: var(--gold);
      font-weight: 400;
    }

    /* --- Instant Checkout Pill Button --- */
    .action-pill-button {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 20px;
      background: var(--whatsapp-green);
      color: white;
      font-weight: 600;
      font-size: 14px;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
      margin-top: auto;
      transition: filter 0.2s;
    }

    .action-pill-button:hover {
      filter: brightness(1.1);
    }

    /* --- Amazon Bottom Infobox Layout --- */
    .utility-footer-infoboxes {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 15px;
      margin-top: 50px;
      border-top: 1px solid #222;
      padding-top: 30px;
    }

    .utility-card {
      background: var(--amazon-nav);
      padding: 20px;
      border-radius: 4px;
    }

    .utility-card h3 {
      color: var(--gold);
      margin-top: 0;
      font-size: 16px;
      margin-bottom: 10px;
    }

    .utility-card p {
      color: #dddddd;
      font-size: 13px;
      margin: 5px 0;
    }

    /* --- Base Footer --- */
    .amazon-base-footer {
      text-align: center;
      padding: 30px 20px;
      font-size: 12px;
      color: var(--text-muted);
      background: var(--amazon-dark);
      margin-top: 40px;
    }
  </style>
</head>

<body>

  <header class="amazon-main-header">
    <a href="#" class="brand-logo">N.D.A<span> COMPANY LTD</span></a>
    
    <div class="amazon-search-bar">
      <input type="text" class="search-input" placeholder="Search school cardigans, celebrity fits, streetwear trends...">
      <button class="search-button">🔍</button>
    </div>

    <div class="user-nav-modules">
      <a href="#" class="nav-box">
        <span class="line-1">Hello, Sign In</span>
        <span class="line-2">Account & Lists</span>
      </a>
      <a href="#" class="nav-box">
        <span class="line-1">Returns</span>
        <span class="line-2">& Orders</span>
      </a>
    </div>
  </header>

  <nav class="amazon-sub-nav">
    <a href="#">All Categories</a>
    <a href="#">School Cardigans (DSM)</a>
    <a href="#">Celebrity Closet (Mwanza)</a>
    <a href="#">Urban Casual Wear</a>
    <a href="#">Premium Fits</a>
    <a href="#">Nationwide Delivery</a>
  </nav>

  <div class="store-banner">
    <h1>Premium Fashion & Uniform Hub</h1>
    <p>Corporate Aesthetics • Academic Knitwear Architecture • Street Culture</p>
  </div>

  <div class="main-marketplace-container">

    <h2 class="department-header">📍 Dar es Salaam Branch <span>(Premium School Cardigans & Knitwear)</span></h2>
    
    <div class="marketplace-grid">

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1544717305-2782549b5136?w=500&auto=format&fit=crop&q=80" alt="Classic Navy Blue School Cardigan">
        </div>
        <div class="product-details">
          <h3 class="product-title">School Cardigan Sweater (Classic Navy Blue - Button V-Neck Design)</h3>
          <div class="marketplace-rating">★★★★☆<span>(4.2)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('School Cardigan Sweater Navy Blue - Dar es Salaam')">
            Order via WhatsApp
          </button>
        </div>
      </div>

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1620799140408-edc6dcb6d633?w=500&auto=format&fit=crop&q=80" alt="Plain Grey School Pullover">
        </div>
        <div class="product-details">
          <h3 class="product-title">School Uniform Pullover (Plain Grey - Premium Woven Fabric)</h3>
          <div class="marketplace-rating">★★★★★<span>(4.9)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('School Cardigan Sweater Grey - Dar es Salaam')">
            Order via WhatsApp
          </button>
        </div>
      </div>

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1614975058789-41316d0e2e9c?w=500&auto=format&fit=crop&q=80" alt="Deep Red School Sweater">
        </div>
        <div class="product-details">
          <h3 class="product-title">School Cardigan Sweater (Deep Red - Premium Uniform Knit)</h3>
          <div class="marketplace-rating">★★★★☆<span>(4.0)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('School Cardigan Sweater Red - Dar es Salaam')">
            Order via WhatsApp
          </button>
        </div>
      </div>

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1578587018452-892bacefd3f2?w=500&auto=format&fit=crop&q=80" alt="Bottle Green Academic Sweater">
        </div>
        <div class="product-details">
          <h3 class="product-title">School Cardigan Sweater (Bottle Green - Anti-Shrink High Quality)</h3>
          <div class="marketplace-rating">★★★★★<span>(4.8)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('School Cardigan Sweater Green - Dar es Salaam')">
            Order via WhatsApp
          </button>
        </div>
      </div>

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1551799517-eb8f03cb5e6a?w=500&auto=format&fit=crop&q=80" alt="Maroon School Uniform Cardigan">
        </div>
        <div class="product-details">
          <h3 class="product-title">School Cardigan Sweater (Maroon - Heavy Knit Institutional Style)</h3>
          <div class="marketplace-rating">★★★★☆<span>(4.5)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('School Cardigan Sweater Maroon - Dar es Salaam')">
            Order via WhatsApp
          </button>
        </div>
      </div>

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1611312449412-6cefac5dc3e4?w=500&auto=format&fit=crop&q=80" alt="Sky Blue Academic Cardigan">
        </div>
        <div class="product-details">
          <h3 class="product-title">School Cardigan Sweater (Royal Sky Blue - Soft Anti-Pill Fabric)</h3>
          <div class="marketplace-rating">★★★★★<span>(5.0)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('School Cardigan Sweater Sky Blue - Dar es Salaam')">
            Order via WhatsApp
          </button>
        </div>
      </div>

    </div>

    <h2 class="department-header">📍 Mwanza Branch <span>(Celebrity Clothing & Street Casual Wear)</span></h2>
    
    <div class="marketplace-grid">

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1596755094514-f87e34085b2c?w=500&auto=format&fit=crop&q=80" alt="Celebrity Designer Shirt">
        </div>
        <div class="product-details">
          <h3 class="product-title">Celebrity Designer Runway Premium Button-Down Shirt</h3>
          <div class="marketplace-rating">★★★★★<span>(4.9)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('Celebrity Designer Shirt - Mwanza')">
            Order via WhatsApp
          </button>
        </div>
      </div>

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?w=500&auto=format&fit=crop&q=80" alt="Luxury Streetwear Hoodie">
        </div>
        <div class="product-details">
          <h3 class="product-title">High-End Hypebeast Oversized Street Casual Hoodie</h3>
          <div class="marketplace-rating">★★★★★<span>(4.8)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('Hypebeast Casual Hoodie - Mwanza')">
            Order via WhatsApp
          </button>
        </div>
      </div>

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1593032465175-481da7e4725f?w=500&auto=format&fit=crop&q=80" alt="Slim-Fit Official Suit">
        </div>
        <div class="product-details">
          <h3 class="product-title">Slim-Fit Bespoke Official Suit Set (Premium Textile Blend)</h3>
          <div class="marketplace-rating">★★★★☆<span>(4.6)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('Slim-Fit Official Suit - Mwanza')">
            Order via WhatsApp
          </button>
        </div>
      </div>

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1583743814966-8936f5b7be1a?w=500&auto=format&fit=crop&q=80" alt="Luxury Graphic Tee">
        </div>
        <div class="product-details">
          <h3 class="product-title">Premium Minimalist Heavyweight Luxury Graphic Tee</h3>
          <div class="marketplace-rating">★★★★★<span>(4.7)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('Luxury Graphic Tee - Mwanza')">
            Order via WhatsApp
          </button>
        </div>
      </div>

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246?w=500&auto=format&fit=crop&q=80" alt="Premium Designer Denim">
        </div>
        <div class="product-details">
          <h3 class="product-title">Celebrity Grade Distressed Slim-Fit Designer Denim Jeans</h3>
          <div class="marketplace-rating">★★★★☆<span>(4.4)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('Designer Denim Jeans - Mwanza')">
            Order via WhatsApp
          </button>
        </div>
      </div>

      <div class="product-box">
        <div class="product-image-frame">
          <img src="https://images.unsplash.com/photo-1618220179428-22790b461013?w=500&auto=format&fit=crop&q=80" alt="Urban Casual Jacket">
        </div>
        <div class="product-details">
          <h3 class="product-title">Classic Urban Lightweight Bomber Jacket (Satin-Weave Lining)</h3>
          <div class="marketplace-rating">★★★★☆<span>(4.7)</span></div>
          <div class="marketplace-price-tag"><span>TZS</span> —</div>
          <button class="action-pill-button" onclick="order('Urban Bomber Jacket - Mwanza')">
            Order via WhatsApp
          </button>
        </div>
      </div>

    </div>

    <div class="utility-footer-infoboxes">
      <div class="utility-card">
        <h3>📍 Strategic Logistics</h3>
        <p><strong>Dar es Salaam:</strong> Direct institutional manufacturing center specialized entirely in heavy-grade uniform Cardigans.</p>
        <p><strong>Mwanza:</strong> Premium curated store handling high-fashion street trends, casual clothing and runway garments.</p>
      </div>

      <div class="utility-card">
        <h3>🚚 Nationwide Transit</h3>
        <p>Swift parcel setup via cross-regional bus lines ensuring immediate delivery right to your terminal.</p>
      </div>

      <div class="utility-card">
        <h3>💰 Payment Portals</h3>
        <p>Full support via integrated Mobile Wallets (M-Pesa, Airtel Money, Tigo Pesa) or safe Cash on Delivery arrangements.</p>
      </div>

      <div class="utility-card">
        <h3>🛡️ Quality Infrastructure</h3>
        <p>✔ Strict material audits (Zero Leather policy applied).</p>
        <p>✔ High-thread-count uniform matrices for peak durability.</p>
      </div>
    </div>

  </div>

  <footer class="amazon-base-footer">
    © 2026 N.D.A Company Ltd | Integrated Premium Fashion Hub • High-Density Grid Architecture
  </footer>

  <script>
  function order(name){
    let msg = "Hello N.D.A, I would like to inquire about the price and availability for: " + name + ". Can you assist me?";
    window.open("https://wa.me/255769631376?text=" + encodeURIComponent(msg));
  }
  </script>

</body>
</html>
