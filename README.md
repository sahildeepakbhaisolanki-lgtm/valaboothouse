# valaboothouse<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vala Boot House | Official Catalog</title>
    <style>
        :root { --primary: #1a1a1a; --accent: #d32f2f; --bg: #fdfdfd; }
        body { font-family: 'Helvetica', sans-serif; margin: 0; background: var(--bg); color: #333; line-height: 1.6; }
        header { background: var(--primary); color: white; padding: 3rem 1rem; text-align: center; border-bottom: 5px solid var(--accent); }
        h1 { margin: 0; font-size: 2.5rem; letter-spacing: 2px; }
        .section-title { text-align: center; margin: 3rem 0 1.5rem; font-size: 1.8rem; text-transform: uppercase; border-bottom: 2px solid #ddd; display: inline-block; width: 100%; padding-bottom: 10px; }
        .container { max-width: 1200px; margin: auto; padding: 0 20px; }
        
        /* Brand Bar */
        .brands { background: #eee; padding: 10px; text-align: center; font-weight: bold; font-size: 0.8rem; color: #666; }

        /* Grid System */
        .catalog-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 2rem; }
        .card { background: white; border: 1px solid #eee; border-radius: 12px; overflow: hidden; transition: 0.3s; }
        .card:hover { box-shadow: 0 10px 20px rgba(0,0,0,0.1); }
        .img-placeholder { background: #f0f0f0; height: 220px; display: flex; align-items: center; justify-content: center; color: #aaa; font-size: 0.9rem; }
        .info { padding: 1.5rem; }
        .category-tag { font-size: 0.7rem; background: var(--accent); color: white; padding: 3px 8px; border-radius: 4px; text-transform: uppercase; }
        .item-name { font-size: 1.2rem; font-weight: bold; margin: 10px 0; }
        .brands-list { color: #666; font-size: 0.85rem; margin-bottom: 15px; }
        
        .whatsapp-btn { display: block; text-align: center; background: #25D366; color: white; text-decoration: none; padding: 10px; border-radius: 6px; font-weight: bold; }
        
        footer { background: #1a1a1a; color: white; text-align: center; padding: 2rem; margin-top: 4rem; }
    </style>
</head>
<body>

<header>
    <h1>VALA BOOT HOUSE</h1>
    <p>Premium Footwear for Men, Women & Kids</p>
</header>

<div class="brands">
    CAMPUS | ASIAN | SPEED | COLUMBUS | REDCHILLY | AIR | HITWAY | PARAGON
</div>

<div class="container">

    <h2 class="section-title">Sports & Sneakers (Huge Collection)</h2>
    <div class="catalog-grid">
        <div class="card">
            <div class="img-placeholder">[ Photo: Sports Shoe ]</div>
            <div class="info">
                <span class="category-tag">Men & Women</span>
                <div class="item-name">Premium Sports Collection</div>
                <p class="brands-list">Brands: Campus, Asian, Columbus, Speed</p>
                <a href="https://wa.me/YOURNUMBER" class="whatsapp-btn">Check Sizes</a>
            </div>
        </div>
        <div class="card">
            <div class="img-placeholder">[ Photo: Sneakers ]</div>
            <div class="info">
                <span class="category-tag">Menswear</span>
                <div class="item-name">Casual Lifestyle Sneakers</div>
                <p class="brands-list">Brands: Redchilly, Air, Hitway</p>
                <a href="https://wa.me/YOURNUMBER" class="whatsapp-btn">Check Sizes</a>
            </div>
        </div>
    </div>

    <h2 class="section-title">Menswear: Leather & Traditional</h2>
    <div class="catalog-grid">
        <div class="card">
            <div class="img-placeholder">[ Photo: Leather Shoe ]</div>
            <div class="info">
                <span class="category-tag">Party Wear</span>
                <div class="item-name">Formal Leather & Loafers</div>
                <a href="https://wa.me/YOURNUMBER" class="whatsapp-btn">Ask for Price</a>
            </div>
        </div>
        <div class="card">
            <div class="img-placeholder">[ Photo: Mojadi ]</div>
            <div class="info">
                <span class="category-tag">Traditional</span>
                <div class="item-name">Premium Mojadi Collection</div>
                <a href="https://wa.me/YOURNUMBER" class="whatsapp-btn">See Designs</a>
            </div>
        </div>
    </div>

    <h2 class="section-title" style="color: var(--accent);">★ Kids Special Section ★</h2>
    <div class="catalog-grid">
        <div class="card" style="border: 2px dashed var(--accent);">
            <div class="img-placeholder"> [ Photo: Kids Shoes ] </div>
            <div class="info">
                <span class="category-tag">Boys & Girls</span>
                <div class="item-name">Kids Sports & School Shoes</div>
                <p class="brands-list">Paragon, Disney & More</p>
                <a href="https://wa.me/YOURNUMBER" class="whatsapp-btn">Check Availability</a>
            </div>
        </div>
    </div>

</div>

<footer>
    <h3>Vala Boot House</h3>
    <p>Specialists in Sports, Leather, Mojadi & Kids Wear</p>
    <p>Address: [Enter Your Shop Address Here]</p>
</footer>

</body>
</html>
