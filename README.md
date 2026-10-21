# Nepal-free-fire-top-center
Good
```html
<!DOCTYPE html>
<html lang="en" class="dark scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nepal Free Fire Top Up Center | Official Instant Diamond Store</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Rajdhani & Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Rajdhani:wght@600;700;800&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        gaming: {
                            bg: '#0c0e14',
                            card: '#141822',
                            panel: '#1b202e',
                            border: '#2a3144',
                            orange: '#ff5722',
                            cyan: '#00e5ff',
                            gold: '#ffb300',
                            green: '#10b981'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        gaming: ['Rajdhani', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        body {
            background-color: #0c0e14;
            color: #f1f5f9;
            font-family: 'Inter', sans-serif;
            background-image: 
                radial-gradient(circle at 10% 20%, rgba(255, 87, 34, 0.08) 0%, transparent 35%),
                radial-gradient(circle at 90% 70%, rgba(0, 229, 255, 0.06) 0%, transparent 40%);
            background-attachment: fixed;
        }

        .gaming-font {
            font-family: 'Rajdhani', sans-serif;
        }

        .gradient-text-fire {
            background: linear-gradient(135deg, #ffb300 0%, #ff5722 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .gradient-text-cyan {
            background: linear-gradient(135deg, #00e5ff 0%, #3b82f6 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .btn-fire {
            background: linear-gradient(135deg, #ff5722 0%, #e64a19 100%);
            box-shadow: 0 4px 15px rgba(255, 87, 34, 0.3);
        }
        .btn-fire:hover {
            background: linear-gradient(135deg, #ff7043 0%, #f4511e 100%);
            box-shadow: 0 6px 20px rgba(255, 87, 34, 0.5);
        }

        .glass-card {
            background: rgba(20, 24, 34, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.07);
        }

        .glass-card-hover {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .glass-card-hover:hover {
            transform: translateY(-4px);
            border-color: #ff5722;
            box-shadow: 0 10px 30px -10px rgba(255, 87, 34, 0.3);
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0c0e14;
        }
        ::-webkit-scrollbar-thumb {
            background: #2a3144;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #ff5722;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between antialiased selection:bg-gaming-orange selection:text-white">

    <!-- Toast Container -->
    <div id="toast-container" class="fixed top-20 right-4 sm:right-6 z-50 flex flex-col gap-3 pointer-events-none"></div>

    <!-- Header / Navbar -->
    <header class="sticky top-0 z-40 glass-card border-b border-gaming-border/80">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            
            <!-- Brand Logo -->
            <a href="#" class="flex items-center gap-3 group">
                <div class="w-11 h-11 rounded-xl btn-fire flex items-center justify-center text-white text-2xl font-bold transition-transform duration-300 group-hover:scale-105">
                    <i class="fa-solid fa-fire-flame-curved"></i>
                </div>
                <div>
                    <span class="gaming-font text-2xl font-extrabold tracking-wider text-white block leading-none">
                        NEPAL <span class="gradient-text-fire">TOP UP</span>
                    </span>
                    <span class="text-[11px] text-gray-400 font-medium flex items-center gap-1 mt-0.5">
                        <i class="fa-solid fa-bolt text-gaming-gold text-[10px]"></i> 100% Safe UID Store
                    </span>
                </div>
            </a>

            <!-- Desktop Menu Navigation -->
            <nav class="hidden lg:flex items-center gap-7 text-sm font-semibold text-gray-300">
                <a href="#packages" class="hover:text-gaming-orange transition-colors flex items-center gap-2"><i class="fa-solid fa-gem text-xs"></i> Top Up</a>
                <a href="#offers" class="hover:text-gaming-orange transition-colors flex items-center gap-2"><i class="fa-solid fa-tags text-xs"></i> Special Offers</a>
                <a href="#calculator" class="hover:text-gaming-orange transition-colors flex items-center gap-2"><i class="fa-solid fa-calculator text-xs"></i> Calculator</a>
                <a href="#payment-info" class="hover:text-gaming-orange transition-colors flex items-center gap-2"><i class="fa-solid fa-wallet text-xs"></i> Payment Info</a>
                <a href="#order-track" class="hover:text-gaming-orange transition-colors flex items-center gap-2"><i class="fa-solid fa-truck-fast text-xs"></i> Track Order</a>
                <a href="#support" class="hover:text-gaming-orange transition-colors flex items-center gap-2"><i class="fa-solid fa-headset text-xs"></i> Contact</a>
            </nav>

            <!-- Saved UID Badge & Quick Action -->
            <div class="hidden sm:flex items-center gap-3">
                <div id="nav-uid-badge" class="hidden items-center gap-2 bg-gaming-panel border border-gaming-border px-3 py-1.5 rounded-xl text-xs font-semibold text-gaming-cyan">
                    <i class="fa-solid fa-user-check text-green-400"></i>
                    <span id="nav-saved-uid-text">UID: ---</span>
                </div>
                <a href="#packages" class="btn-fire text-white text-xs font-bold uppercase tracking-wider px-4 py-2.5 rounded-xl transition-all flex items-center gap-2">
                    <i class="fa-solid fa-bag-shopping"></i> Shop Diamonds
                </a>
            </div>

            <!-- Mobile Hamburger Button -->
            <button id="mobile-menu-btn" class="lg:hidden text-gray-300 text-2xl p-2 rounded-xl hover:bg-gaming-panel focus:outline-none">
                <i class="fa-solid fa-bars"></i>
            </button>
        </div>

        <!-- Mobile Drawer Navigation -->
        <div id="mobile-menu" class="hidden lg:hidden border-t border-gaming-border bg-gaming-card px-4 py-4 space-y-3">
            <div id="mobile-uid-badge" class="hidden items-center justify-between bg-gaming-panel p-3 rounded-xl border border-gaming-border text-xs mb-2">
                <span class="text-gray-400">Saved Player UID:</span>
                <span id="mobile-saved-uid-text" class="font-mono text-gaming-cyan font-bold">---</span>
            </div>
            <a href="#packages" class="mobile-nav-link block py-2 text-gray-300 hover:text-gaming-orange"><i class="fa-solid fa-gem w-6"></i> Diamond Packages</a>
            <a href="#offers" class="mobile-nav-link block py-2 text-gray-300 hover:text-gaming-orange"><i class="fa-solid fa-tags w-6"></i> Special Offers</a>
            <a href="#calculator" class="mobile-nav-link block py-2 text-gray-300 hover:text-gaming-orange"><i class="fa-solid fa-calculator w-6"></i> Diamond Calculator</a>
            <a href="#payment-info" class="mobile-nav-link block py-2 text-gray-300 hover:text-gaming-orange"><i class="fa-solid fa-wallet w-6"></i> Payment Instructions</a>
            <a href="#order-track" class="mobile-nav-link block py-2 text-gray-300 hover:text-gaming-orange"><i class="fa-solid fa-truck-fast w-6"></i> Track Order Status</a>
            <a href="#support" class="mobile-nav-link block py-2 text-gray-300 hover:text-gaming-orange"><i class="fa-solid fa-headset w-6"></i> 24/7 Live Support</a>
        </div>
    </header>

    <!-- Main App Container -->
    <main class="flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-8 space-y-12">

        <!-- Hero Section -->
        <section class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
            
            <!-- Hero Left Banner -->
            <div class="lg:col-span-7 space-y-6">
                <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-gaming-orange/10 border border-gaming-orange/30 text-gaming-gold text-xs font-bold">
                    <span class="w-2.5 h-2.5 rounded-full bg-green-400 animate-pulse"></span> 24/7 Automated Processing Active
                </div>

                <h1 class="gaming-font text-4xl sm:text-6xl font-extrabold text-white leading-tight tracking-wide">
                    INSTANT FREE FIRE <br>
                    <span class="gradient-text-fire">DIAMONDS & MEMBERSHIP</span> <br>
                    TOP UP IN NEPAL
                </h1>

                <p class="text-gray-400 text-sm sm:text-base leading-relaxed max-w-2xl">
                    Get Free Fire Diamonds instantly credited to your account using only your <strong class="text-white">Player UID</strong>. Fast, 100% legal, and cheapest rates in Nepal using eSewa, Khalti, IME Pay, or Bank Transfer.
                </p>

                <!-- Hero Features -->
                <div class="grid grid-cols-2 sm:grid-cols-3 gap-3 text-xs font-semibold text-gray-300 pt-2">
                    <div class="flex items-center gap-2 bg-gaming-card p-3 rounded-xl border border-gaming-border">
                        <i class="fa-solid fa-bolt text-gaming-gold text-base"></i>
                        <span>1-5 Min Auto Delivery</span>
                    </div>
                    <div class="flex items-center gap-2 bg-gaming-card p-3 rounded-xl border border-gaming-border">
                        <i class="fa-solid fa-shield-halved text-green-400 text-base"></i>
                        <span>No Password Required</span>
                    </div>
                    <div class="flex items-center gap-2 bg-gaming-card p-3 rounded-xl border border-gaming-border">
                        <i class="fa-solid fa-tags text-gaming-cyan text-base"></i>
                        <span>Lowest Rate Guaranteed</span>
                    </div>
                </div>
            </div>

            <!-- Hero Right: Quick UID Saver Panel -->
            <div class="lg:col-span-5 glass-card p-6 sm:p-7 rounded-2xl border border-gaming-border space-y-5 relative overflow-hidden">
                <div class="absolute -top-12 -right-12 w-32 h-32 bg-gaming-orange/10 rounded-full blur-2xl pointer-events-none"></div>

                <div class="flex items-center justify-between border-b border-gaming-border/80 pb-3">
                    <h3 class="gaming-font text-xl font-bold text-white flex items-center gap-2">
                        <i class="fa-solid fa-id-card text-gaming-orange"></i> ENTER PLAYER UID
                    </h3>
                    <span class="text-[11px] text-gray-400">Step 1 of 2</span>
                </div>

                <p class="text-xs text-gray-400">
                    Save your Free Fire UID now. It will be automatically locked into all package purchases!
                </p>

                <div class="space-y-4">
                    <div>
                        <label class="block text-xs font-semibold text-gray-300 mb-1.5">Free Fire Server Region</label>
                        <select id="hero-server-select" class="w-full bg-gaming-panel border border-gaming-border rounded-xl px-3.5 py-2.5 text-xs font-medium text-gray-200 focus:outline-none focus:border-gaming-orange">
                            <option value="BD/Nepal">Bangladesh / Nepal Server</option>
                            <option value="India">India Server</option>
                            <option value="Global">Global Server</option>
                        </select>
                    </div>

                    <div>
                        <label class="block text-xs font-semibold text-gray-300 mb-1.5">Player UID (User ID)</label>
                        <div class="relative">
                            <input type="number" id="hero-uid-input" placeholder="e.g. 1234567890" class="w-full bg-gaming-panel border border-gaming-border rounded-xl px-3.5 py-2.5 pl-10 text-sm text-white placeholder-gray-500 focus:outline-none focus:border-gaming-orange font-mono">
                            <i class="fa-solid fa-crosshairs absolute left-3.5 top-3 text-gray-500 text-xs"></i>
                        </div>
                    </div>

                    <button onclick="saveHeroUid()" class="w-full btn-fire text-white py-3 rounded-xl font-bold text-xs uppercase tracking-wider transition-all flex items-center justify-center gap-2">
                        <i class="fa-solid fa-bookmark"></i> Save UID for Quick Checkout
                    </button>
                </div>
            </div>
        </section>

        <!-- Package Catalog Section -->
        <section id="packages" class="space-y-6">
            <div class="flex flex-col md:flex-row md:items-center justify-between gap-4 border-b border-gaming-border/80 pb-4">
                <div>
                    <h2 class="gaming-font text-3xl font-extrabold text-white tracking-wide flex items-center gap-3">
                        <i class="fa-solid fa-layer-group text-gaming-orange"></i> SELECT TOP UP PACKAGE
                    </h2>
                    <p class="text-xs text-gray-400 mt-1">Select your desired diamond amount or game pass to continue to instant checkout.</p>
                </div>

                <!-- Category Filter Tabs -->
                <div class="flex flex-wrap gap-2">
                    <button onclick="filterPackages('all')" class="filter-btn active-filter px-4 py-2 rounded-xl text-xs font-bold bg-gaming-orange text-white shadow transition-all" data-category="all">
                        All Items
                    </button>
                    <button onclick="filterPackages('diamonds')" class="filter-btn px-4 py-2 rounded-xl text-xs font-bold bg-gaming-card text-gray-400 border border-gaming-border hover:text-white transition-all" data-category="diamonds">
                        💎 Diamonds
                    </button>
                    <button onclick="filterPackages('membership')" class="filter-btn px-4 py-2 rounded-xl text-xs font-bold bg-gaming-card text-gray-400 border border-gaming-border hover:text-white transition-all" data-category="membership">
                        🎟️ Memberships
                    </button>
                    <button onclick="filterPackages('airdrop')" class="filter-btn px-4 py-2 rounded-xl text-xs font-bold bg-gaming-card text-gray-400 border border-gaming-border hover:text-white transition-all" data-category="airdrop">
                        🎁 Special Airdrops
                    </button>
                    <button onclick="filterPackages('levelup')" class="filter-btn px-4 py-2 rounded-xl text-xs font-bold bg-gaming-card text-gray-400 border border-gaming-border hover:text-white transition-all" data-category="levelup">
                        ⭐ Level Up Pass
                    </button>
                </div>
            </div>

            <!-- Diamond Cards Grid -->
            <div id="packages-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5">
                <!-- JS Inject Package Cards -->
            </div>
        </section>

        <!-- Special Offers Banner -->
        <section id="offers" class="glass-card p-6 sm:p-8 rounded-2xl border border-gaming-border relative overflow-hidden">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-8 space-y-3">
                    <span class="px-3 py-1 rounded-full bg-gaming-gold/10 border border-gaming-gold/30 text-gaming-gold text-[11px] font-bold uppercase tracking-wider">
                        🔥 Flash Sale Offer
                    </span>
                    <h3 class="gaming-font text-3xl font-extrabold text-white tracking-wide">
                        GET 10% EXTRA DIAMONDS ON YOUR FIRST ORDER!
                    </h3>
                    <p class="text-xs sm:text-sm text-gray-400 leading-relaxed">
                        Top up any pack above 520 Diamonds using eSewa or Khalti today and receive instant bonus in-game diamonds directly credited!
                    </p>
                </div>
                <div class="lg:col-span-4 flex justify-start lg:justify-end">
                    <a href="#packages" class="btn-fire text-white px-6 py-3 rounded-xl text-xs font-bold uppercase tracking-wider shadow-lg flex items-center gap-2">
                        <i class="fa-solid fa-bolt"></i> Claim Bonus Pack
                    </a>
                </div>
            </div>
        </section>

        <!-- Interactive Diamond Price Calculator -->
        <section id="calculator" class="glass-card p-6 sm:p-8 rounded-2xl border border-gaming-border space-y-6">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 border-b border-gaming-border pb-4">
                <div>
                    <h3 class="gaming-font text-2xl font-bold text-white flex items-center gap-2">
                        <i class="fa-solid fa-calculator text-gaming-cyan"></i> LIVE DIAMOND COST CALCULATOR
                    </h3>
                    <p class="text-xs text-gray-400 mt-1">Calculate exact Nepali Rupee costs for any custom amount of Free Fire diamonds.</p>
                </div>
                <div class="bg-gaming-panel px-4 py-2 rounded-xl border border-gaming-border text-right">
                    <span class="text-[10px] text-gray-400 block uppercase tracking-wider font-semibold">Standard Rate</span>
                    <span class="text-xs font-bold text-gaming-gold">1 Diamond ≈ रू 1.15 NPR</span>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-8 space-y-6">
                    <div>
                        <div class="flex justify-between items-center mb-2">
                            <label class="text-xs font-bold text-gray-300 uppercase tracking-wider">Drag to select diamonds count</label>
                            <span id="calc-diamond-display" class="gaming-font text-3xl font-extrabold text-gaming-cyan">500 Diamonds</span>
                        </div>
                        <input id="calc-slider" type="range" min="50" max="5600" step="25" value="500" class="w-full h-3 bg-gaming-panel rounded-lg appearance-none cursor-pointer accent-gaming-orange">
                        <div class="flex justify-between text-[11px] text-gray-500 font-mono mt-2">
                            <span>50 💎</span>
                            <span>1000 💎</span>
                            <span>2800 💎</span>
                            <span>5600 💎</span>
                        </div>
                    </div>

                    <!-- Preset Buttons -->
                    <div class="flex flex-wrap gap-2">
                        <button onclick="setCalcValue(100)" class="bg-gaming-panel hover:bg-gaming-border text-gray-300 px-3.5 py-2 rounded-xl text-xs font-semibold border border-gaming-border transition-colors">+100 💎</button>
                        <button onclick="setCalcValue(310)" class="bg-gaming-panel hover:bg-gaming-border text-gray-300 px-3.5 py-2 rounded-xl text-xs font-semibold border border-gaming-border transition-colors">+310 💎</button>
                        <button onclick="setCalcValue(520)" class="bg-gaming-panel hover:bg-gaming-border text-gray-300 px-3.5 py-2 rounded-xl text-xs font-semibold border border-gaming-border transition-colors">+520 💎</button>
                        <button onclick="setCalcValue(1060)" class="bg-gaming-panel hover:bg-gaming-border text-gray-300 px-3.5 py-2 rounded-xl text-xs font-semibold border border-gaming-border transition-colors">+1060 💎</button>
                    </div>
                </div>

                <!-- Calculator Result Panel -->
                <div class="lg:col-span-4 bg-gaming-panel p-6 rounded-2xl border border-gaming-border flex flex-col items-center text-center space-y-4">
                    <div class="w-12 h-12 rounded-full bg-gaming-cyan/10 border border-gaming-cyan/30 flex items-center justify-center text-gaming-cyan text-xl">
                        <i class="fa-solid fa-coins"></i>
                    </div>
                    <div>
                        <span class="text-[11px] text-gray-400 font-semibold uppercase tracking-wider block">Estimated Price</span>
                        <div id="calc-price-npr" class="gaming-font text-4xl font-extrabold text-white">रू 575</div>
                    </div>
                    <button onclick="orderCustomCalculatedPack()" class="w-full btn-fire text-white py-3 rounded-xl font-bold text-xs uppercase tracking-wider transition-all">
                        Buy This Custom Amount
                    </button>
                </div>
            </div>
        </section>

        <!-- Payment Methods & Instructions Section -->
        <section id="payment-info" class="grid grid-cols-1 lg:grid-cols-12 gap-8">
            
            <!-- Payment Accounts Grid -->
            <div class="lg:col-span-7 glass-card p-6 sm:p-8 rounded-2xl border border-gaming-border space-y-6">
                <div class="border-b border-gaming-border pb-4">
                    <h3 class="gaming-font text-2xl font-bold text-white flex items-center gap-2">
                        <i class="fa-solid fa-wallet text-gaming-gold"></i> OFFICIAL PAYMENT ACCOUNTS
                    </h3>
                    <p class="text-xs text-gray-400 mt-1">Send exact payment amount to any of the verified accounts below.</p>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    
                    <!-- eSewa Card -->
                    <div class="bg-gaming-panel p-4 rounded-xl border border-gaming-border flex items-center justify-between">
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 bg-emerald-500/20 text-emerald-400 rounded-lg flex items-center justify-center font-black text-sm">eS</div>
                            <div>
                                <span class="text-xs font-bold text-white block">eSewa Wallet</span>
                                <span class="text-xs text-gray-400 font-mono">9800000000</span>
                            </div>
                        </div>
                        <button onclick="copyToClipboard('9800000000', 'eSewa ID')" class="bg-gaming-card hover:bg-gaming-border text-gaming-gold text-xs px-3 py-1.5 rounded-lg border border-gaming-border transition-colors">
                            <i class="fa-regular fa-copy"></i> Copy
                        </button>
                    </div>

                    <!-- Khalti Card -->
                    <div class="bg-gaming-panel p-4 rounded-xl border border-gaming-border flex items-center justify-between">
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 bg-purple-500/20 text-purple-400 rounded-lg flex items-center justify-center font-black text-sm">Kh</div>
                            <div>
                                <span class="text-xs font-bold text-white block">Khalti Wallet</span>
                                <span class="text-xs text-gray-400 font-mono">9800000000</span>
                            </div>
                        </div>
                        <button onclick="copyToClipboard('9800000000', 'Khalti ID')" class="bg-gaming-card hover:bg-gaming-border text-gaming-gold text-xs px-3 py-1.5 rounded-lg border border-gaming-border transition-colors">
                            <i class="fa-regular fa-copy"></i> Copy
                        </button>
                    </div>

                    <!-- IME Pay Card -->
                    <div class="bg-gaming-panel p-4 rounded-xl border border-gaming-border flex items-center justify-between">
                        <div class="flex items-center gap-3">
                            <div class
```
