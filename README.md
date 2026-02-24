<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Couture Optique of Woodstock | Luxury Eyewear</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        /* This creates a subtle "expensive paper" texture */
        .texture-bg {
            background-color: #f7f3f0;
            background-image: url("https://www.transparenttextures.com/patterns/linen-paper.png");
        }
        h1, h2, h3, h4, .serif { font-family: 'Playfair Display', serif; }
        body { font-family: 'Inter', sans-serif; }
        .accent-gold { color: #b08d57; }
        .bg-gold { background-color: #b08d57; }
        .border-gold { border-color: #b08d57; }
    </style>
</head>
<body class="texture-bg text-slate-900">

    <div class="bg-stone-900 text-white text-[10px] uppercase tracking-[0.3em] py-2.5 text-center">
        High-End Styles • Neighborhood Prices • Woodstock, GA
    </div>

    <nav class="bg-white/90 backdrop-blur-md sticky top-0 z-50 border-b border-stone-200">
        <div class="container mx-auto px-8 py-5 flex justify-between items-center">
            <h1 class="text-2xl font-bold tracking-widest uppercase text-stone-800">Couture <span class="italic font-light accent-gold lowercase">Optique</span></h1>
            <div class="hidden lg:flex space-x-10 text-xs uppercase tracking-widest font-semibold text-stone-600">
                <a href="#collections" class="hover:accent-gold transition">Collections</a>
                <a href="#clinical" class="hover:accent-gold transition">Clinical Care</a>
                <a href="#boutique" class="hover:accent-gold transition">The Boutique</a>
            </div>
            <a href="tel:7705550123" class="border-2 border-gold px-6 py-2 text-xs uppercase tracking-widest font-bold accent-gold hover:bg-gold hover:text-white transition">Book Appointment</a>
        </div>
    </nav>

    <header class="relative bg-emerald-950 h-[75vh] flex items-center overflow-hidden">
        <div class="absolute inset-0 opacity-40 bg-[url('https://images.unsplash.com/photo-1511556820780-d912e42b4980?auto=format&fit=crop&q=80')] bg-cover bg-center"></div>
        <div class="container mx-auto px-8 z-10">
            <div class="max-w-2xl text-white">
                <span class="uppercase tracking-[0.4em] text-xs font-bold accent-gold mb-6 block">Woodstock Boutique</span>
                <h2 class="text-7xl mb-6 leading-tight">High-End Vision.<br><span class="italic font-light accent-gold">Accessible Style.</span></h2>
                <p class="text-xl mb-10 text-stone-300 leading-relaxed font-light max-w-lg">Why choose between designer labels and your budget? Experience concierge clinical care and hand-picked independent frames without the luxury markup.</p>
                <div class="flex gap-6">
                    <a href="#collections" class="bg-gold text-white px-10 py-4 font-bold uppercase tracking-widest text-xs hover:bg-white hover:text-gold transition shadow-xl">Explore Frames</a>
                </div>
            </div>
        </div>
    </header>

    <section id="collections" class="py-24">
        <div class="container mx-auto px-8">
            <div class="flex flex-col md:flex-row justify-between items-end mb-16 border-b border-stone-300 pb-8">
                <div class="max-w-md">
                    <h3 class="text-4xl mb-4 text-stone-800 uppercase tracking-tight">The <span class="accent-gold italic">Curated</span> Edit</h3>
                    <p class="text-stone-600 font-light">Independent designers from Paris, Milan, and New York—priced for our local community.</p>
                </div>
                <div class="mt-8 md:mt-0 italic accent-gold text-lg">Hand-picked styles &rarr;</div>
            </div>
            
            <div class="grid md:grid-cols-3 gap-12">
                <div class="group cursor-pointer">
                    <div class="aspect-[4/5] bg-stone-200 mb-6 overflow-hidden shadow-md border-t-4 border-gold">
                        <div class="w-full h-full bg-stone-300 group-hover:scale-105 transition duration-700 flex items-center justify-center text-stone-500 italic">Parisian Chic</div>
                    </div>
                    <h4 class="text-2xl mb-1 text-stone-800 uppercase tracking-tighter">The Heritage Series</h4>
                    <p class="text-sm accent-gold uppercase tracking-widest font-bold">Designer Craftsmanship</p>
                </div>
                <div class="group cursor-pointer">
                    <div class="aspect-[4/5] bg-stone-200 mb-6 overflow-hidden shadow-md border-t-4 border-gold">
                        <div class="w-full h-full bg-stone-400 group-hover:scale-105 transition duration-700 flex items-center justify-center text-stone-500 italic">Minimalist</div>
                    </div>
                    <h4 class="text-2xl mb-1 text-stone-800 uppercase tracking-tighter">Titanium Luxe</h4>
                    <p class="text-sm accent-gold uppercase tracking-widest font-bold">Unmatched Durability</p>
                </div>
                <div class="group cursor-pointer">
                    <div class="aspect-[4/5] bg-stone-200 mb-6 overflow-hidden shadow-md border-t-4 border-gold">
                        <div class="w-full h-full bg-stone-300 group-hover:scale-105 transition duration-700 flex items-center justify-center text-stone-500 italic">Avant-Garde</div>
                    </div>
                    <h4 class="text-2xl mb-1 text-stone-800 uppercase tracking-tighter">The Bespoke Edit</h4>
                    <p class="text-sm accent-gold uppercase tracking-widest font-bold">Limited Availability</p>
                </div>
            </div>
        </div>
    </section>

</body>
</html>
