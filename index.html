<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wooden Art Store</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: Arial, sans-serif; background: #f5efe6; color: #3a1a00; }

        nav {
            position: sticky; top: 0;
            background: #3a1a00;
            display: flex; justify-content: space-between; align-items: center;
            padding: 14px 20px; z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.4);
        }
        nav h2 { color: #f5c87a; font-size: 18px; }
        nav ul { display: flex; gap: 18px; list-style: none; }
        nav ul li a { color: #f5c87a; text-decoration: none; font-size: 13px; }
        nav ul li a:hover { color: #fff; }

        header {
            text-align: center; padding: 55px 20px;
            background: linear-gradient(135deg, #5a2d0c, #c8860a); color: white;
        }
        header h1 { font-size: 34px; margin-bottom: 8px; letter-spacing: 1px; }
        header p { opacity: 0.88; font-size: 15px; }

        .section-title {
            text-align: center; margin: 35px 20px 15px;
            font-size: 22px; color: #5a2d0c; font-weight: bold;
            padding-bottom: 10px;
            border-bottom: 3px solid #c8860a;
        }

        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(290px, 1fr));
            gap: 25px;
            padding: 20px 25px 30px;
        }

        .card {
            background: white;
            border-radius: 14px;
            overflow: hidden;
            box-shadow: 0 5px 18px rgba(90,45,12,0.15);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .card:hover {
            transform: translateY(-6px);
            box-shadow: 0 12px 30px rgba(90,45,12,0.28);
        }

        .painting-frame {
            position: relative;
            background: #3a1a00;
            padding: 10px;
        }
        .painting-frame svg {
            width: 100%; height: 195px; display: block;
            border: 4px solid #C8860A;
            border-radius: 4px;
        }
        .frame-label {
            position: absolute; bottom: 14px; left: 50%;
            transform: translateX(-50%);
            background: rgba(0,0,0,0.55);
            color: #f5c87a; font-size: 10px; padding: 2px 10px;
            border-radius: 20px; white-space: nowrap; font-weight: bold;
        }

        .card-body { padding: 14px 16px 16px; }

        .card-body h4 {
            color: #5a2d0c; font-size: 16px; font-weight: bold;
            margin-bottom: 10px; padding-bottom: 8px;
            border-bottom: 1px solid #f0e6d3;
        }

        .specs-table { width: 100%; border-collapse: collapse; margin-bottom: 13px; font-size: 13px; }
        .specs-table tr { border-bottom: 1px solid #f5ede0; }
        .specs-table td { padding: 5px 2px; }
        .specs-table td:first-child { color: #999; width: 42%; }
        .specs-table td:last-child { color: #3a1a00; font-weight: bold; }

        .price-row {
            display: flex; justify-content: space-between; align-items: center;
            margin-bottom: 12px;
        }
        .price { color: #2d7a2d; font-size: 22px; font-weight: bold; }
        .badge {
            font-size: 11px; padding: 3px 10px; border-radius: 20px;
            font-weight: bold; background: #fff3e0; color: #e65100;
        }

        .btn-row { display: flex; gap: 8px; }
        .buy-btn {
            flex: 1; background: linear-gradient(135deg, #5a2d0c, #c8860a);
            border: none; padding: 11px; border-radius: 25px;
            color: white; cursor: pointer; font-weight: bold; font-size: 13px;
            transition: 0.3s;
        }
        .buy-btn:hover { opacity: 0.85; transform: scale(1.03); }
        .wa-btn {
            flex: 1; background: #25d366;
            border: none; padding: 11px; border-radius: 25px;
            color: white; cursor: pointer; font-weight: bold; font-size: 13px;
            transition: 0.3s;
        }
        .wa-btn:hover { opacity: 0.85; }

        /* POPUP */
        .overlay { display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.5); z-index: 1999; }
        .overlay.active { display: block; }
        .popup {
            display: none; position: fixed; top: 50%; left: 50%;
            transform: translate(-50%, -50%);
            background: #fff8f0; padding: 24px; border-radius: 16px;
            z-index: 2000; width: 92%; max-width: 360px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.35);
        }
        .popup.active { display: block; }
        .popup h3 { color: #5a2d0c; margin-bottom: 14px; font-size: 17px; }
        .popup-item { background: #f5ede0; padding: 8px 12px; border-radius: 8px; margin-bottom: 12px; font-size: 13px; color: #5a2d0c; font-weight: bold; }
        .popup input {
            width: 100%; padding: 10px 12px; margin: 6px 0;
            border: 1px solid #d4a96a; border-radius: 8px;
            background: #fff; color: #3a1a00; outline: none; font-size: 14px;
        }
        .popup input:focus { border-color: #c8860a; box-shadow: 0 0 6px #c8860a44; }
        .qty-box { display: flex; justify-content: center; align-items: center; gap: 14px; margin: 10px 0; }
        .qty-box button {
            width: 34px; height: 34px; border: none; border-radius: 50%;
            background: linear-gradient(135deg, #5a2d0c, #c8860a);
            color: white; font-size: 20px; cursor: pointer; line-height: 1;
        }
        .qty-box input {
            width: 55px; text-align: center; padding: 7px;
            border: 1px solid #d4a96a; border-radius: 8px;
            font-size: 16px; font-weight: bold; margin: 0;
        }
        #totalPrice { font-size: 18px; font-weight: bold; color: #2d7a2d; text-align: center; margin: 8px 0; }
        .close-btn {
            background: #cc3300; width: 100%; margin-bottom: 10px;
            border: none; padding: 10px; border-radius: 25px;
            color: white; cursor: pointer; font-weight: bold; font-size: 14px;
        }

        .whatsapp-float {
            position: fixed; bottom: 22px; right: 22px; background: #25d366;
            width: 58px; height: 58px; border-radius: 50%;
            display: flex; align-items: center; justify-content: center;
            font-size: 28px; text-decoration: none;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3); z-index: 999;
        }

        footer {
            background: #3a1a00; color: #f5c87a;
            padding: 24px; text-align: center; font-size: 13px;
        }
        footer p { margin: 4px 0; }
    </style>
</head>
<body>

<nav>
    <h2>🪵 Wooden Art Store</h2>
    <ul>
        <li><a href="#landscape">Landscape</a></li>
        <li><a href="#nature">Nature</a></li>
        <li><a href="#abstract">Abstract</a></li>
    </ul>
</nav>

<header>
    <h1>🪵 Wooden Art Store</h1>
    <p>Handcrafted Acrylic Paintings on Wooden Board • Made in India</p>
</header>

<!-- LANDSCAPE -->
<div class="section-title" id="landscape">🏔️ Landscape Paintings</div>
<div class="products-grid">

    <div class="card">
        <div class="painting-frame">
            <svg viewBox="0 0 300 190" xmlns="http://www.w3.org/2000/svg">
              <rect width="300" height="190" fill="#87CEEB"/>
              <rect x="0" y="60" width="300" height="20" fill="#E8A040" opacity="0.4"/>
              <polygon points="0,120 70,45 140,120" fill="#6B3A1A"/>
              <polygon points="70,120 150,38 230,120" fill="#8B4A2A"/>
              <polygon points="160,120 230,52 300,120" fill="#7B4020"/>
              <polygon points="70,45 86,63 54,63" fill="white" opacity="0.9"/>
              <polygon points="150,38 166,57 134,57" fill="white" opacity="0.9"/>
              <polygon points="230,52 244,68 216,68" fill="white" opacity="0.85"/>
              <rect x="0" y="120" width="300" height="70" fill="#4a7a20"/>
              <ellipse cx="150" cy="145" rx="75" ry="18" fill="#4A90CA" opacity="0.85"/>
              <path d="M75,145 Q150,130 225,145" stroke="#87CEEB" stroke-width="2" fill="none" opacity="0.5"/>
              <polygon points="30,120 43,92 56,120" fill="#2d5a00"/>
              <polygon points="240,120 253,90 266,120" fill="#2d5a00"/>
              <polygon points="255,120 266,94 277,120" fill="#3a7000"/>
            </svg>
            <div class="frame-label">MOUNTAIN LANDSCAPE</div>
        </div>
        <div class="card-body">
            <h4>Mountain Landscape Painting</h4>
            <table class="specs-table">
                <tr><td>Material</td><td>Wooden Board</td></tr>
                <tr><td>Size</td><td>24" x 36"</td></tr>
                <tr><td>Finish</td><td>Matt + Glossy</td></tr>
                <tr><td>Frame Type</td><td>Wooden Frame</td></tr>
                <tr><td>Hanging</td><td>Wall Mounted</td></tr>
                <tr><td>Origin</td><td>Made in India</td></tr>
            </table>
            <div class="price-row">
                <span class="price">₹1,299</span>
                <span class="badge">⭐ Bestseller</span>
            </div>
            <div class="btn-row">
                <button class="buy-btn" onclick="openPopup('Mountain Landscape Painting',1299)">🛒 Buy Now</button>
                <button class="wa-btn" onclick="waEnquiry('Mountain Landscape Painting',1299)">💬 Enquiry</button>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="painting-frame">
            <svg viewBox="0 0 300 190" xmlns="http://www.w3.org/2000/svg">
              <rect width="300" height="190" fill="#FF7B35"/>
              <rect x="0" y="0" width="300" height="60" fill="#FF4500" opacity="0.5"/>
              <circle cx="150" cy="55" r="35" fill="#FFD700" opacity="0.95"/>
              <circle cx="150" cy="55" r="25" fill="#FFF176"/>
              <polygon points="0,120 60,85 120,120" fill="#1a3a00" opacity="0.9"/>
              <polygon points="60,120 110,88 160,120" fill="#1a3a00"/>
              <polygon points="150,120 200,82 250,120" fill="#1a3a00" opacity="0.9"/>
              <polygon points="220,120 255,90 290,120" fill="#1a3a00"/>
              <path d="M0,140 Q50,125 100,135 Q150,145 200,130 Q250,118 300,128 L300,190 L0,190Z" fill="#1a5a8a"/>
              <path d="M0,138 Q75,125 150,135 Q225,145 300,128" stroke="#87CEEB" stroke-width="2" fill="none" opacity="0.5"/>
              <path d="M130,190 Q147,155 150,135 Q153,155 170,190" fill="#FFD700" opacity="0.15"/>
            </svg>
            <div class="frame-label">SUNSET RIVER</div>
        </div>
        <div class="card-body">
            <h4>Sunset River Painting</h4>
            <table class="specs-table">
                <tr><td>Material</td><td>Wooden Board</td></tr>
                <tr><td>Size</td><td>18" x 24"</td></tr>
                <tr><td>Finish</td><td>Glossy</td></tr>
                <tr><td>Frame Type</td><td>Wooden Frame</td></tr>
                <tr><td>Hanging</td><td>Wall Mounted</td></tr>
                <tr><td>Origin</td><td>Made in India</td></tr>
            </table>
            <div class="price-row">
                <span class="price">₹999</span>
                <span class="badge">🔥 Hot Deal</span>
            </div>
            <div class="btn-row">
                <button class="buy-btn" onclick="openPopup('Sunset River Painting',999)">🛒 Buy Now</button>
                <button class="wa-btn" onclick="waEnquiry('Sunset River Painting',999)">💬 Enquiry</button>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="painting-frame">
            <svg viewBox="0 0 300 190" xmlns="http://www.w3.org/2000/svg">
              <rect width="300" height="190" fill="#0a0a2a"/>
              <circle cx="80" cy="30" r="2" fill="white" opacity="0.8"/>
              <circle cx="140" cy="20" r="1.5" fill="white"/>
              <circle cx="200" cy="35" r="2" fill="white" opacity="0.7"/>
              <circle cx="255" cy="22" r="1.5" fill="white"/>
              <circle cx="50" cy="50" r="1" fill="white" opacity="0.6"/>
              <circle cx="175" cy="48" r="1.5" fill="white"/>
              <circle cx="270" cy="42" r="1" fill="white" opacity="0.8"/>
              <circle cx="230" cy="35" r="18" fill="#FFFACD" opacity="0.95"/>
              <circle cx="240" cy="28" r="13" fill="#0a0a2a"/>
              <polygon points="0,120 30,75 60,120" fill="#0d2600"/>
              <polygon points="35,120 60,72 85,120" fill="#0d3000"/>
              <polygon points="70,120 98,65 126,120" fill="#0d2800"/>
              <polygon points="100,120 130,60 160,120" fill="#0d2600"/>
              <polygon points="155,120 183,65 211,120" fill="#0d2800"/>
              <polygon points="195,120 220,70 245,120" fill="#0d2600"/>
              <polygon points="238,120 260,75 282,120" fill="#0d3000"/>
              <rect x="0" y="120" width="300" height="70" fill="#0d1a3a"/>
              <path d="M0,132 Q75,124 150,130 Q225,136 300,124" stroke="#2a5a8a" stroke-width="1.5" fill="none" opacity="0.6"/>
              <path d="M135,190 Q147,148 150,120 Q153,148 165,190" fill="#FFFACD" opacity="0.18"/>
            </svg>
            <div class="frame-label">MOONLIT FOREST</div>
        </div>
        <div class="card-body">
            <h4>Moonlit Forest Painting</h4>
            <table class="specs-table">
                <tr><td>Material</td><td>Wooden Board</td></tr>
                <tr><td>Size</td><td>24" x 30"</td></tr>
                <tr><td>Finish</td><td>Matt Finish</td></tr>
                <tr><td>Frame Type</td><td>Wooden Frame</td></tr>
                <tr><td>Hanging</td><td>Wall Mounted</td></tr>
                <tr><td>Origin</td><td>Made in India</td></tr>
            </table>
            <div class="price-row">
                <span class="price">₹1,499</span>
                <span class="badge">✨ Premium</span>
            </div>
            <div class="btn-row">
                <button class="buy-btn" onclick="openPopup('Moonlit Forest Painting',1499)">🛒 Buy Now</button>
                <button class="wa-btn" onclick="waEnquiry('Moonlit Forest Painting',1499)">💬 Enquiry</button>
            </div>
        </div>
    </div>

</div>

<!-- NATURE -->
<div class="section-title" id="nature">🌿 Nature Paintings</div>
<div class="products-grid">

    <div class="card">
        <div class="painting-frame">
            <svg viewBox="0 0 300 190" xmlns="http://www.w3.org/2000/svg">
              <rect width="300" height="190" fill="#87CEEB"/>
              <ellipse cx="80" cy="35" rx="40" ry="16" fill="white" opacity="0.9"/>
              <ellipse cx="112" cy="29" rx="32" ry="13" fill="white" opacity="0.85"/>
              <ellipse cx="220" cy="40" rx="35" ry="14" fill="white" opacity="0.9"/>
              <path d="M0,100 Q75,65 150,90 Q210,70 300,85 L300,190 L0,190Z" fill="#4a7a20"/>
              <path d="M0,115 Q75,85 150,108 Q215,88 300,102 L300,190 L0,190Z" fill="#5a8a28"/>
              <path d="M0,130 Q75,108 150,125 Q215,108 300,118 L300,190 L0,190Z" fill="#6a9a30"/>
              <ellipse cx="150" cy="148" rx="55" ry="14" fill="#4A90CA" opacity="0.7"/>
              <path d="M95,148 Q150,138 205,148" stroke="#87CEEB" stroke-width="1.5" fill="none" opacity="0.5"/>
              <polygon points="98,108 112,80 126,108" fill="#2d5a00"/>
              <polygon points="155,106 168,76 181,106" fill="#3a7000"/>
              <polygon points="172,108 184,80 196,108" fill="#2d5a00"/>
              <rect x="45" y="95" width="18" height="25" fill="#8B4513"/>
              <polygon points="36,95 54,68 72,95" fill="#2d5a00"/>
            </svg>
            <div class="frame-label">GREEN VALLEY</div>
        </div>
        <div class="card-body">
            <h4>Green Valley Painting</h4>
            <table class="specs-table">
                <tr><td>Material</td><td>Wooden Board</td></tr>
                <tr><td>Size</td><td>20" x 28"</td></tr>
                <tr><td>Finish</td><td>Matt + Glossy</td></tr>
                <tr><td>Frame Type</td><td>Wooden Frame</td></tr>
                <tr><td>Hanging</td><td>Wall Mounted</td></tr>
                <tr><td>Origin</td><td>Made in India</td></tr>
            </table>
            <div class="price-row">
                <span class="price">₹1,149</span>
                <span class="badge">🌿 Nature</span>
            </div>
            <div class="btn-row">
                <button class="buy-btn" onclick="openPopup('Green Valley Painting',1149)">🛒 Buy Now</button>
                <button class="wa-btn" onclick="waEnquiry('Green Valley Painting',1149)">💬 Enquiry</button>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="painting-frame">
            <svg viewBox="0 0 300 190" xmlns="http://www.w3.org/2000/svg">
              <rect width="300" height="190" fill="#C8D8E8"/>
              <polygon points="0,110 85,38 170,110" fill="#9aafbe"/>
              <polygon points="75,110 165,32 255,110" fill="#b0c0ce"/>
              <polygon points="145,110 225,48 300,110" fill="#9aafbe"/>
              <polygon points="85,38 106,60 64,60" fill="white"/>
              <polygon points="165,32 186,57 144,57" fill="white"/>
              <polygon points="225,48 244,67 206,67" fill="white"/>
              <rect x="0" y="110" width="300" height="80" fill="white"/>
              <rect x="0" y="148" width="300" height="42" fill="#e0e8f0"/>
              <ellipse cx="150" cy="135" rx="90" ry="20" fill="#A8C8E8" opacity="0.7"/>
              <polygon points="20,110 35,88 50,110" fill="#6a8a9a" opacity="0.5"/>
              <polygon points="255,110 270,86 285,110" fill="#6a8a9a" opacity="0.5"/>
            </svg>
            <div class="frame-label">WINTER PEAKS</div>
        </div>
        <div class="card-body">
            <h4>Winter Peaks Painting</h4>
            <table class="specs-table">
                <tr><td>Material</td><td>Wooden Board</td></tr>
                <tr><td>Size</td><td>24" x 36"</td></tr>
                <tr><td>Finish</td><td>Glossy</td></tr>
                <tr><td>Frame Type</td><td>Wooden Frame</td></tr>
                <tr><td>Hanging</td><td>Wall Mounted</td></tr>
                <tr><td>Origin</td><td>Made in India</td></tr>
            </table>
            <div class="price-row">
                <span class="price">₹1,399</span>
                <span class="badge">❄️ Special</span>
            </div>
            <div class="btn-row">
                <button class="buy-btn" onclick="openPopup('Winter Peaks Painting',1399)">🛒 Buy Now</button>
                <button class="wa-btn" onclick="waEnquiry('Winter Peaks Painting',1399)">💬 Enquiry</button>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="painting-frame">
            <svg viewBox="0 0 300 190" xmlns="http://www.w3.org/2000/svg">
              <rect width="300" height="190" fill="#2d6a2d"/>
              <rect x="0" y="0" width="300" height="70" fill="#1a4a1a"/>
              <ellipse cx="80" cy="32" rx="32" ry="14" fill="#3a8a3a" opacity="0.8"/>
              <ellipse cx="200" cy="28" rx="28" ry="12" fill="#3a8a3a" opacity="0.7"/>
              <rect x="143" y="0" width="14" height="190" fill="#4A90CA" opacity="0.6"/>
              <path d="M143,0 Q138,95 143,190" stroke="#87CEEB" stroke-width="1.5" fill="none" opacity="0.4"/>
              <polygon points="20,190 48,120 76,190" fill="#1a4a00"/>
              <polygon points="55,190 80,115 105,190" fill="#1a4a00"/>
              <polygon points="195,190 222,115 249,190" fill="#1a4a00"/>
              <polygon points="225,190 250,120 275,190" fill="#1a4a00"/>
              <rect x="0" y="160" width="300" height="30" fill="#0d2a0d" opacity="0.5"/>
            </svg>
            <div class="frame-label">FOREST STREAM</div>
        </div>
        <div class="card-body">
            <h4>Forest Stream Painting</h4>
            <table class="specs-table">
                <tr><td>Material</td><td>Wooden Board</td></tr>
                <tr><td>Size</td><td>18" x 24"</td></tr>
                <tr><td>Finish</td><td>Matt Finish</td></tr>
                <tr><td>Frame Type</td><td>Wooden Frame</td></tr>
                <tr><td>Hanging</td><td>Wall Mounted</td></tr>
                <tr><td>Origin</td><td>Made in India</td></tr>
            </table>
            <div class="price-row">
                <span class="price">₹1,099</span>
                <span class="badge">🌊 New</span>
            </div>
            <div class="btn-row">
                <button class="buy-btn" onclick="openPopup('Forest Stream Painting',1099)">🛒 Buy Now</button>
                <button class="wa-btn" onclick="waEnquiry('Forest Stream Painting',1099)">💬 Enquiry</button>
            </div>
        </div>
    </div>

</div>

<!-- ABSTRACT -->
<div class="section-title" id="abstract">🎨 Abstract Paintings</div>
<div class="products-grid">

    <div class="card">
        <div class="painting-frame">
            <svg viewBox="0 0 300 190" xmlns="http://www.w3.org/2000/svg">
              <rect width="300" height="190" fill="#1a0a2a"/>
              <ellipse cx="100" cy="95" rx="70" ry="70" fill="#FF6B35" opacity="0.7"/>
              <ellipse cx="200" cy="95" rx="70" ry="70" fill="#4A90CA" opacity="0.7"/>
              <ellipse cx="150" cy="70" rx="60" ry="60" fill="#FFD700" opacity="0.5"/>
              <ellipse cx="150" cy="120" rx="45" ry="45" fill="#E040FB" opacity="0.4"/>
              <circle cx="150" cy="95" r="30" fill="white" opacity="0.15"/>
              <path d="M50,30 Q150,10 250,30" stroke="#FFD700" stroke-width="2" fill="none" opacity="0.4"/>
              <path d="M50,160 Q150,180 250,160" stroke="#FF6B35" stroke-width="2" fill="none" opacity="0.4"/>
            </svg>
            <div class="frame-label">COSMIC ABSTRACT</div>
        </div>
        <div class="card-body">
            <h4>Cosmic Abstract Painting</h4>
            <table class="specs-table">
                <tr><td>Material</td><td>Wooden Board</td></tr>
                <tr><td>Size</td><td>20" x 20"</td></tr>
                <tr><td>Finish</td><td>Glossy</td></tr>
                <tr><td>Frame Type</td><td>Wooden Frame</td></tr>
                <tr><td>Hanging</td><td>Wall Mounted</td></tr>
                <tr><td>Origin</td><td>Made in India</td></tr>
            </table>
            <div class="price-row">
                <span class="price">₹1,199</span>
                <span class="badge">🎨 Abstract</span>
            </div>
            <div class="btn-row">
                <button class="buy-btn" onclick="openPopup('Cosmic Abstract Painting',1199)">🛒 Buy Now</button>
                <button class="wa-btn" onclick="waEnquiry('Cosmic Abstract Painting',1199)">💬 Enquiry</button>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="painting-frame">
            <svg viewBox="0 0 300 190" xmlns="http://www.w3.org/2000/svg">
              <rect width="300" height="190" fill="#fff8f0"/>
              <path d="M0,60 Q75,30 150,60 Q225,90 300,60 L300,0 L0,0Z" fill="#FF9966" opacity="0.7"/>
              <path d="M0,120 Q75,90 150,120 Q225,150 300,120 L300,190 L0,190Z" fill="#5a2d0c" opacity="0.6"/>
              <circle cx="80" cy="95" r="40" fill="#C8860A" opacity="0.5"/>
              <circle cx="220" cy="95" r="40" fill="#8B4513" opacity="0.5"/>
              <circle cx="150" cy="95" r="35" fill="#f5c87a" opacity="0.6"/>
              <path d="M30,95 Q150,40 270,95" stroke="#5a2d0c" stroke-width="3" fill="none" opacity="0.4"/>
              <path d="M30,95 Q150,150 270,95" stroke="#C8860A" stroke-width="3" fill="none" opacity="0.4"/>
            </svg>
            <div class="frame-label">GOLDEN WAVE</div>
        </div>
        <div class="card-body">
            <h4>Golden Wave Abstract</h4>
            <table class="specs-table">
                <tr><td>Material</td><td>Wooden Board</td></tr>
                <tr><td>Size</td><td>24" x 24"</td></tr>
                <tr><td>Finish</td><td>Matt + Glossy</td></tr>
                <tr><td>Frame Type</td><td>Wooden Frame</td></tr>
                <tr><td>Hanging</td><td>Wall Mounted</td></tr>
                <tr><td>Origin</td><td>Made in India</td></tr>
            </table>
            <div class="price-row">
                <span class="price">₹1,349</span>
                <span class="badge">✨ Popular</span>
            </div>
            <div class="btn-row">
                <button class="buy-btn" onclick="openPopup('Golden Wave Abstract',1349)">🛒 Buy Now</button>
                <button class="wa-btn" onclick="waEnquiry('Golden Wave Abstract',1349)">💬 Enquiry</button>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="painting-frame">
            <svg viewBox="0 0 300 190" xmlns="http://www.w3.org/2000/svg">
              <rect width="300" height="190" fill="#0a1a0a"/>
              <rect x="0" y="0" width="150" height="95" fill="#1a4a1a" opacity="0.8"/>
              <rect x="150" y="0" width="150" height="95" fill="#4A2808" opacity="0.8"/>
              <rect x="0" y="95" width="150" height="95" fill="#4A2808" opacity="0.8"/>
              <rect x="150" y="95" width="150" height="95" fill="#1a1a4a" opacity="0.8"/>
              <circle cx="150" cy="95" r="55" fill="none" stroke="#C8860A" stroke-width="6" opacity="0.8"/>
              <circle cx="150" cy="95" r="35" fill="none" stroke="#f5c87a" stroke-width="3" opacity="0.6"/>
              <circle cx="150" cy="95" r="15" fill="#C8860A" opacity="0.9"/>
              <line x1="150" y1="0" x2="150" y2="190" stroke="#C8860A" stroke-width="2" opacity="0.3"/>
              <line x1="0" y1="95" x2="300" y2="95" stroke="#C8860A" stroke-width="2" opacity="0.3"/>
            </svg>
            <div class="frame-label">HARMONY ABSTRACT</div>
        </div>
        <div class="card-body">
            <h4>Harmony Abstract Painting</h4>
            <table class="specs-table">
                <tr><td>Material</td><td>Wooden Board</td></tr>
                <tr><td>Size</td><td>18" x 18"</td></tr>
                <tr><td>Finish</td><td>Glossy</td></tr>
                <tr><td>Frame Type</td><td>Wooden Frame</td></tr>
                <tr><td>Hanging</td><td>Wall Mounted</td></tr>
                <tr><td>Origin</td><td>Made in India</td></tr>
            </table>
            <div class="price-row">
                <span class="price">₹899</span>
                <span class="badge">🆕 New Arrival</span>
            </div>
            <div class="btn-row">
                <button class="buy-btn" onclick="openPopup('Harmony Abstract Painting',899)">🛒 Buy Now</button>
                <button class="wa-btn" onclick="waEnquiry('Harmony Abstract Painting',899)">💬 Enquiry</button>
            </div>
        </div>
    </div>

</div>

<!-- POPUP OVERLAY -->
<div class="overlay" id="overlay" onclick="closePopup()"></div>

<!-- POPUP -->
<div class="popup" id="popup">
    <button class="close-btn" onclick="closePopup()">✕ Close</button>
    <h3>🛒 Place Your Order</h3>
    <div class="popup-item" id="popupItem">Item Name</div>
    <input id="name" placeholder="Your Full Name" />
    <input id="address" placeholder="Delivery Address" />
    <input id="phone" placeholder="Phone Number" type="tel" />
    <div class="qty-box">
        <button onclick="decreaseQty()">−</button>
        <input type="number" id="quantity" value="1" min="1" />
        <button onclick="increaseQty()">+</button>
    </div>
    <p id="totalPrice">Total: ₹0</p>
    <button class="buy-btn" style="width:100%;margin-top:6px;padding:12px;font-size:14px" onclick="sendOrder()">📲 Send Order on WhatsApp</button>
</div>

<a class="whatsapp-float" href="https://wa.me/91XXXXXXXXXX" target="_blank">💬</a>

<footer>
    <p>© 2026 Wooden Art Store | Handcrafted with ❤️ in India</p>
    <p style="margin-top:8px;opacity:0.75">📞 WhatsApp: +91-XXXXXXXXXX &nbsp;|&nbsp; All India Delivery</p>
</footer>

<script>
let itemName = "";
let itemPrice = 0;

function openPopup(name, price) {
    itemName = name;
    itemPrice = price;
    document.getElementById("popupItem").innerText = "🖼️ " + name;
    document.getElementById("quantity").value = 1;
    document.getElementById("popup").classList.add("active");
    document.getElementById("overlay").classList.add("active");
    updateTotal();
}

function closePopup() {
    document.getElementById("popup").classList.remove("active");
    document.getElementById("overlay").classList.remove("active");
}

function increaseQty() {
    let q = document.getElementById("quantity");
    q.value++;
    updateTotal();
}

function decreaseQty() {
    let q = document.getElementById("quantity");
    if (parseInt(q.value) > 1) { q.value--; updateTotal(); }
}

function updateTotal() {
    let q = document.getElementById("quantity").value;
    document.getElementById("totalPrice").innerText = "Total: ₹" + (q * itemPrice).toLocaleString('en-IN');
}

function sendOrder() {
    let name = document.getElementById("name").value.trim();
    let address = document.getElementById("address").value.trim();
    let phone = document.getElementById("phone").value.trim();
    let quantity = document.getElementById("quantity").value;

    if (!name || !address || !phone) {
        alert("⚠️ Please fill all details!");
        return;
    }

    let msg =
        "Hello Wooden Art Store 🪵\n\n" +
        "🖼️ Item: " + itemName + "\n" +
        "🔢 Qty: " + quantity + "\n" +
        "💰 Total: ₹" + (quantity * itemPrice).toLocaleString('en-IN') + "\n\n" +
        "👤 Name: " + name + "\n" +
        "📍 Address: " + address + "\n" +
        "📞 Phone: " + phone;

    closePopup();
    setTimeout(() => {
        window.open("https://wa.me/91XXXXXXXXXX?text=" + encodeURIComponent(msg), "_blank");
    }, 300);
}

function waEnquiry(name, price) {
    let msg = "Hello! I'm interested in:\n\n🖼️ " + name + "\n💰 Price: ₹" + price.toLocaleString('en-IN') + "\n\nPlease share more details.";
    window.open("https://wa.me/91XXXXXXXXXX?text=" + encodeURIComponent(msg), "_blank");
}
</script>
</body>
</html>
