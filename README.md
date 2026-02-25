<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Couture Optique | Woodstock Luxury Eyewear</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
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

    <div class="bg-stone-900 text-white text-[10px] uppercase tracking-[0.3em] py-2.5 text-center font-semibold shadow-md">
        Luxury Styles • Accessible Prices • 770-555-1234
    </div>

    <nav class="bg-white/95 backdrop-blur-md sticky top-0 z-50 border-b border-stone-200">
        <div class="container mx-auto px-8 py-4 flex justify-between items-center">
            
            <div class="flex flex-col items-center mx-auto lg:mx-0">
                <h1 class="text-2xl font-bold tracking-widest uppercase text-stone-800 leading-none">
                    Couture Optique
                </h1>
                <span class="text-[11px] italic tracking-[0.2em] text-stone-500 font-medium mt-1">
                    of Woodstock
                </span>
            </div>

            <div class="hidden lg:flex space-x-10 text-xs uppercase tracking-widest font-semibold text-stone-600">
                <a href="#collections" class="hover:accent-gold transition">Collections</a>
                <a href="#mission" class="hover:accent-gold transition">Our Mission</a>
                <a href="#visit" class="hover:accent-gold transition">Visit Us</a>
            </div>

            <a href="tel:7705551234" class="border-2 border-gold px-6 py-2 text-xs uppercase tracking-widest font-bold accent-gold hover:bg-gold hover:text-white transition shadow-sm">
                Book Exam
            </a>
        </div>
    </nav>

    <header class="relative bg-emerald-950 h-[75vh] flex items-center overflow-hidden">
        <div class="absolute inset-0 opacity-30 bg-[url('https://images.unsplash.com/photo-1574258495973-f010dfbb5371?q=80&w=2070')] bg-cover bg-center scale-105"></div>
        <div class="container mx-auto px-8 z-10 text-center lg:text-left">
            <div class="max-w-3xl text-white">
                <h2 class="text-5xl md:text-7xl mb-6 leading-tight">Luxury Eye Care. <br><span class="italic font-light accent-gold">Accessible Style.</span></h2>
                <p class="text-xl mb-10 text-stone-300 leading-relaxed font-light max-w-xl">
                    Experience <span class="text-white font-medium italic">concierge clinical eye care</span> and curated frames. <span class="accent-gold font-medium">Designer quality without the designer markup.</span>
                </p>
                <div class="flex flex-col md:flex-row gap-6 justify-center lg:justify-start font-bold">
                    <a href="#collections" class="bg-gold text-white px-10 py-4 uppercase tracking-widest text-xs hover:bg-stone-800 transition shadow-2xl">Explore Frames</a>
                    <a href="#visit" class="border border-white/40 text-white px-10 py-4 uppercase tracking-widest text-xs hover:bg-white hover:text-emerald-900 transition">Contact Us</a>
                </div>
            </div>
        </div>
    </header>

    <section id="mission" class="py-24 bg-white/40 border-b border-stone-200">
        <div class="container mx-auto px-8 text-center max-w-4xl">
            <span class="accent-gold uppercase tracking-[0.4em] text-[10px] font-bold mb-6 block">Our Commitment</span>
            <h3 class="text-4xl mb-8 text-stone-800 tracking-tight leading-snug">Elegance in Sight.<br><span class="italic">Value in Vision.</span></h3>
            <p class="text-xl text-stone-600 font-light leading-relaxed">
                "At Couture Optique, our mission is to redefine the boutique experience. We prove that world-class style and clinical excellence can be both personal and accessible. We are dedicated to providing our Woodstock neighbors with the finest independent eyewear and compassionate care <span class="italic accent-gold">without the designer markup.</span>"
            </p>
        </div>
    </section>

    <section id="collections" class="py-24">
        <div class="container mx-auto px-4">
            <div class="text-center mb-20">
                <h3 class="text-5xl mb-4 text-stone-800 tracking-tight">The <span class="accent-gold italic">Curated</span> Collection</h3>
                <div class="h-1 w-20 bg-gold mx-auto mb-6"></div>
                <p class="text-stone-500 font-light text-sm italic uppercase tracking-[0.2em]">Craftsmanship meets clinical precision</p>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 text-center">
                <div class="group cursor-pointer">
                    <div class="aspect-[4/5] bg-stone-200 mb-6 overflow-hidden shadow-lg border-t-4 border-gold relative">
                        <img src="https://images.unsplash.com/photo-1572635196237-14b3f281503f?q=80&w=1760" alt="Gucci Styles" class="w-full h-full object-cover group-hover:scale-110 transition duration-700 opacity-90 group-hover:opacity-100">
                    </div>
                    <h4 class="text-2xl mb-1 text-stone-800 tracking-tighter uppercase">Gucci Collection</h4>
                    <p class="text-[11px] accent-gold uppercase tracking-widest font-bold italic">Signature Luxury</p>
                </div>

                <div class="group cursor-pointer">
                    <div class="aspect-[4/5] bg-stone-200 mb-6 overflow-hidden shadow-lg border-t-4 border-gold relative">
                        <img src="https://images.unsplash.com/photo-1511499767150-a48a237f0083?q=80&w=1760" alt="Heritage Series" class="w-full h-full object-cover group-hover:scale-110 transition duration-700 opacity-90 group-hover:opacity-100">
                    </div>
                    <h4 class="text-2xl mb-1 text-stone-800 tracking-tighter uppercase">Heritage Series</h4>
                    <p class="text-[11px] accent-gold uppercase tracking-widest font-bold italic">Hand-crafted Acetate</p>
                </div>

                <div class="group cursor-pointer">
                    <div class="aspect-[4/5] bg-stone-200 mb-6 overflow-hidden shadow-lg border-t-4 border-gold relative">
                        <img src="https://images.unsplash.com/photo-1614715838608-dd527c46231d?q=80&w=1760" alt="Oakley Performance" class="w-full h-full object-cover group-hover:scale-110 transition duration-700 opacity-90 group-hover:opacity-100">
                    </div>
                    <h4 class="text-2xl mb-1 text-stone-800 tracking-tighter uppercase">Oakley Performance</h4>
                    <p class="text-[11px] accent-gold uppercase tracking-widest font-bold italic">Precision Engineering</p>
                </div>

                <div class="group cursor-pointer">
                    <div class="aspect-[4/5] bg-stone-200 mb-6 overflow-hidden shadow-lg border-t-4 border-gold relative">
                        <img src="https://images.unsplash.com/photo-1473496169904-658ba7c44d8a?q=80&w=1760" alt="Bespoke Edit" class="w-full h-full object-cover group-hover:scale-110 transition duration-700 opacity-90 group-hover:opacity-100">
                    </div>
                    <h4 class="text-2xl mb-1 text-stone-800 tracking-tighter uppercase">The Bespoke Edit</h4>
                    <p class="text-[11px] accent-gold uppercase tracking-widest font-bold italic">Limited Exclusives</p>
                </div>
            </div>
        </div>
    </section>

    <section id="visit" class="bg-stone-900 py-24 text-white">
        <div class="container mx-auto px-8 grid md:grid-cols-2 gap-16 items-center">
            <div>
                <span class="accent-gold uppercase tracking-[0.3em] text-xs font-bold mb-4 block italic">Our Woodstock Boutique</span>
                <h3 class="text-5xl mb-8 leading-tight">Clinical Excellence.<br>Personal Service.</h3>
                <p class="text-stone-400 font-light text-lg leading-relaxed mb-8">Visit us for a comprehensive medical eye exam and a personalized frame fitting. No rush, no pressure—just exceptional care.</p>
                <div class="space-y-6">
                    <div class="flex items-center gap-4 text-stone-300">
                        <span class="bg-white/5 border border-white/10 p-3 rounded text-gold">📍</span> 
                        <div>
                            <p class="text-[10px] uppercase tracking-widest text-stone-500">Location</p>
                            <p class="text-lg">183 Main St, Woodstock, GA 30188</p>
                        </div>
                    </div>
                    <div class="flex items-center gap-4 text-stone-300">
                        <span class="bg-white/5 border border-white/10 p-3 rounded text-gold">📞</span>
                        <div>
                            <p class="text-[10px] uppercase tracking-widest text-stone-500">Call Us</p>
                            <p class="text-lg font-bold">770-555-1234</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bg-white/5 p-10 border border-white/10 backdrop-blur-sm shadow-2xl rounded-sm">
                <h4 class="text-2xl mb-6 accent-gold uppercase tracking-widest">Boutique Hours</h4>
                <div class="space-y-4 text-stone-300 font-light">
                    <div class="flex justify-between border-b border-white/10 pb-2"><span>Tuesday — Friday</span> <span class="font-semibold">9am — 6pm</span></div>
                    <div class="flex justify-between border-b border-white/10 pb-2"><span>Saturday</span> <span class="font-semibold">10am — 4pm</span></div>
                    <div class="flex justify-between text-stone-600 italic"><span>Sunday — Monday</span> <span>Closed</span></div>
                </div>
                <button onclick="window.location.href='tel:7705551234'" class="w-full mt-10 bg-gold text-white py-4 font-bold uppercase tracking-widest text-xs hover:bg-white hover:text-stone-900 transition">Call to Schedule</button>
            </div>
        </div>
    </section>

    <footer class="bg-stone-950 py-10 border-t border-white/5">
        <div class="container mx-auto px-8 text-center">
            <p class="text-stone-600 text-[10px] uppercase tracking-[0.4em]">© 2026 Couture Optique of Woodstock • Luxury Eyewear & Clinical Care</p>
        </div>
    </footer>

</body>
</html>
