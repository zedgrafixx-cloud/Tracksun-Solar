<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tracksun Solar Pvt. Ltd. | Clean Energy Solutions</title>
    <!-- Tailwind CSS for Modern Styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- AOS Library for Beautiful Scroll Animations -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        html { scroll-behavior: smooth; }
        .hero-bg {
            background: linear-gradient(rgba(15, 23, 42, 0.65), rgba(15, 23, 42, 0.75)), 
                        url('https://images.unsplash.com/photo-1509391366360-2e959784a276?q=80&w=1920') no-repeat center center/cover;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans overflow-x-hidden">

    <!-- 1. NAVIGATION BAR (Updated for tracksunsolar_2.jpg) -->
    <nav class="fixed w-full bg-white shadow-md z-50 transition-all duration-300 border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-6 py-2 flex justify-between items-center">
            <!-- Logo Integration Section -->
            <div class="flex items-center">
                <a href="#home" class="inline-block bg-slate-950 rounded-xl p-1 shadow-inner">
                    <!-- Referencing tracksunsolar_2.jpg perfectly -->
                    <img src="tracksunsolar_2.jpg" alt="Tracksun Solar Logo" class="h-14 w-auto object-contain block">
                </a>
            </div>
            <div class="hidden md:flex space-x-8 font-semibold text-slate-600">
                <a href="#home" class="hover:text-emerald-600 transition">Home</a>
                <a href="#about" class="hover:text-emerald-600 transition">About Us</a>
                <a href="#solutions" class="hover:text-emerald-600 transition">Solutions</a>
                <a href="#products" class="hover:text-emerald-600 transition">Products</a>
                <a href="#contact" class="hover:text-emerald-600 transition">Contact</a>
            </div>
            <div>
                <a href="tel:+919217333071" class="bg-amber-500 hover:bg-amber-600 text-white px-5 py-2.5 rounded-full font-bold shadow-md transition inline-flex items-center space-x-2">
                    <i class="fas fa-phone"></i> <span>Call Expert</span>
                </a>
            </div>
        </div>
    </nav>

    <!-- 2. HERO SECTION -->
    <section id="home" class="hero-bg h-screen flex flex-col justify-center items-center text-center px-4 pt-16">
        <h1 data-aos="zoom-out" data-aos-duration="1200" class="text-4xl md:text-6xl font-extrabold text-white max-w-4xl leading-tight">
            Shaping The Future Of Renewable Energy
        </h1>
        <p data-aos="fade-up" data-aos-delay="300" data-aos-duration="1000" class="text-lg md:text-xl text-slate-200 mt-6 max-w-2xl">
            ISO 9001:2008 Certified Solar Company & MNRE Approved Channel Partner delivering high-efficiency power systems across India.
        </p>
        <div data-aos="fade-up" data-aos-delay="600" data-aos-duration="1000" class="mt-10 flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
            <a href="#solutions" class="bg-emerald-600 hover:bg-emerald-700 text-white px-8 py-3.5 rounded-full font-bold text-lg shadow-lg transition">Explore Solutions</a>
            <a href="#contact" class="bg-white/10 hover:bg-white/20 text-white border border-white/30 backdrop-blur-sm px-8 py-3.5 rounded-full font-bold text-lg transition">Get Free Quote</a>
        </div>
    </section>

    <!-- 3. TRUSTED BY / STATS SECTION -->
    <section class="py-12 bg-white border-b">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
            <div data-aos="fade-up" data-aos-delay="100">
                <div class="text-4xl font-bold text-emerald-600">2013</div>
                <div class="text-sm text-slate-500 font-medium mt-1">Established Year</div>
            </div>
            <div data-aos="fade-up" data-aos-delay="200">
                <div class="text-4xl font-bold text-emerald-600">10+</div>
                <div class="text-sm text-slate-500 font-medium mt-1">Years Experience</div>
            </div>
            <div data-aos="fade-up" data-aos-delay="300">
                <div class="text-4xl font-bold text-emerald-600">100%</div>
                <div class="text-sm text-slate-500 font-medium mt-1">Quality Inspection</div>
            </div>
            <div data-aos="fade-up" data-aos-delay="400">
                <div class="text-4xl font-bold text-emerald-600">MNRE</div>
                <div class="text-sm text-slate-500 font-medium mt-1">Govt. Approved</div>
            </div>
        </div>
    </section>

    <!-- 4. ABOUT SECTION -->
    <section id="about" class="py-20 max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
        <div data-aos="fade-right" class="relative">
            <img src="https://images.unsplash.com/photo-1508514177221-188b1cf16e9d?q=80&w=800" alt="Solar Panels" class="rounded-2xl shadow-xl">
            <div class="absolute -bottom-6 -right-6 bg-emerald-600 text-white p-6 rounded-2xl shadow-lg hidden sm:block">
                <p class="text-2xl font-bold">State-of-the-Art</p>
                <p class="text-sm opacity-90">Manufacturing in Noida, UP</p>
            </div>
        </div>
        <div data-aos="fade-left" class="space-y-6">
            <span class="text-xs font-bold uppercase tracking-widest text-emerald-600 bg-emerald-50 px-3 py-1 rounded-full">Company Profile</span>
            <h2 class="text-3xl md:text-4xl font-bold text-slate-900">Tracksun Solar Pvt. Ltd.</h2>
            <p class="text-slate-600 leading-relaxed">
                We leverage cutting-edge technology and rigorous 6-step quality control to deliver high-performance solar modules. Operating from our advanced facility in Noida, Uttar Pradesh, every product is engineered for maximum durability and clean energy conversion.
            </p>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 pt-4">
                <div class="flex items-start space-x-3">
                    <i class="fas fa-check-circle text-emerald-500 mt-1"></i>
                    <div><h4 class="font-semibold text-slate-800">ISO 9001:2008</h4><p class="text-xs text-slate-500">Quality Certified Systems</p></div>
                </div>
                <div class="flex items-start space-x-3">
                    <i class="fas fa-check-circle text-emerald-500 mt-1"></i>
                    <div><h4 class="font-semibold text-slate-800">EL Testing Completed</h4><p class="text-xs text-slate-500">100% Electroluminescence verified</p></div>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. SOLUTIONS SECTION -->
    <section id="solutions" class="py-20 bg-slate-100">
        <div class="max-w-7xl mx-auto px-6 text-center mb-16">
            <span class="text-xs font-bold uppercase tracking-widest text-emerald-600 bg-emerald-50 px-3 py-1 rounded-full">What We Do</span>
            <h2 class="text-3xl md:text-4xl font-bold text-slate-900 mt-3">Tailored Solar Engineering</h2>
        </div>
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 lg:grid-cols-4 gap-8">
            <!-- Card 1 -->
            <div data-aos="fade-up" data-aos-delay="100" class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-xl transition transform hover:-translate-y-2 duration-300">
                <div class="w-12 h-12 bg-amber-100 text-amber-600 rounded-xl flex items-center justify-center text-xl font-bold mb-6"><i class="fas fa-home"></i></div>
                <h3 class="text-xl font-bold text-slate-900 mb-3">Home Solar</h3>
                <p class="text-sm text-slate-600">Residential rooftop systems, clean lighting, and robust battery configuration.</p>
            </div>
            <!-- Card 2 -->
            <div data-aos="fade-up" data-aos-delay="200" class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-xl transition transform hover:-translate-y-2 duration-300">
                <div class="w-12 h-12 bg-emerald-100 text-emerald-600 rounded-xl flex items-center justify-center text-xl font-bold mb-6"><i class="fas fa-building"></i></div>
                <h3 class="text-xl font-bold text-slate-900 mb-3">Industrial Units</h3>
                <p class="text-sm text-slate-600">Heavy-duty utility EPC power installations for factories, railways, and campus grids.</p>
            </div>
            <!-- Card 3 -->
            <div data-aos="fade-up" data-aos-delay="300" class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-xl transition transform hover:-translate-y-2 duration-300">
                <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center text-xl font-bold mb-6"><i class="fas fa-tower-cell"></i></div>
                <h3 class="text-xl font-bold text-slate-900 mb-3">Telecom Sector</h3>
                <p class="text-sm text-slate-600">Highly reliable hybrid and off-grid power structures for continuous tower operations.</p>
            </div>
            <!-- Card 4 -->
            <div data-aos="fade-up" data-aos-delay="400" class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-xl transition transform hover:-translate-y-2 duration-300">
                <div class="w-12 h-12 bg-purple-100 text-purple-600 rounded-xl flex items-center justify-center text-xl font-bold mb-6"><i class="fas fa-lightbulb"></i></div>
                <h3 class="text-xl font-bold text-slate-900 mb-3">Solar Lighting</h3>
                <p class="text-sm text-slate-600">Automatic dusk-to-dawn street lights, lanterns, and commercial high-mast set-ups.</p>
            </div>
        </div>
    </section>

    <!-- 6. PRODUCTS CATALOG SECTION -->
    <section id="products" class="py-20 max-w-7xl mx-auto px-6">
        <div class="text-center mb-16">
            <span class="text-xs font-bold uppercase tracking-widest text-emerald-600 bg-emerald-50 px-3 py-1 rounded-full">Product Range</span>
            <h2 class="text-3xl md:text-4xl font-bold text-slate-900 mt-3">Featured Core Configurations</h2>
        </div>
        <div class="grid md:grid-cols-3 gap-8">
            <!-- Product 1 -->
            <div data-aos="flip-left" class="bg-white border rounded-2xl overflow-hidden shadow-sm hover:shadow-md transition">
                <div class="p-6 border-b bg-slate-50"><h3 class="text-xl font-bold text-slate-900">On-Grid Solar System</h3></div>
                <div class="p-6 space-y-4">
                    <p class="text-sm text-slate-600">Export surplus power directly to state DISCOMs via compatible net-metering structures.</p>
                    <div class="text-xs font-semibold text-emerald-600 bg-emerald-50 p-3 rounded-lg">Best for: Drastic corporate & home grid bill reductions.</div>
                </div>
            </div>
            <!-- Product 2 -->
            <div data-aos="flip-left" data-aos-delay="200" class="bg-white border rounded-2xl overflow-hidden shadow-sm hover:shadow-md transition">
                <div class="p-6 border-b bg-slate-50"><h3 class="text-xl font-bold text-slate-900">Off-Grid Solar System</h3></div>
                <div class="p-6 space-y-4">
                    <p class="text-sm text-slate-600">Complete energy autonomy using high-capacity Tubular Gel / Lithium Iron Phosphate setups.</p>
                    <div class="text-xs font-semibold text-amber-600 bg-amber-50 p-3 rounded-lg">Best for: Remote areas with 1-3 days power autonomy.</div>
                </div>
            </div>
            <!-- Product 3 -->
            <div data-aos="flip-left" data-aos-delay="400" class="bg-white border rounded-2xl overflow-hidden shadow-sm hover:shadow-md transition">
                <div class="p-6 border-b bg-slate-50"><h3 class="text-xl font-bold text-slate-900">Hybrid Solar System</h3></div>
                <div class="p-6 space-y-4">
                    <p class="text-sm text-slate-600">Smart PCU hybrid inverter systems delivering the absolute best of both grid & battery backups.</p>
                    <div class="text-xs font-semibold text-blue-600 bg-blue-50 p-3 rounded-lg">Best for: Continuous power with customizable backups.</div>
                </div>
            </div>
        </div>
    </section>

    <!-- 7. CONTACT & LOCATION SECTION -->
    <section id="contact" class="py-20 bg-slate-900 text-white">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12">
            <div data-aos="fade-right">
                <h2 class="text-3xl font-bold text-white mb-6">Ready to Power Your Next Project?</h2>
                <p class="text-slate-400 mb-8">Fill out the quick layout form, or contact us directly using the corporate office info below.</p>
                
                <div class="space-y-6">
                    <div class="flex items-start space-x-4">
                        <i class="fas fa-map-marker-alt text-xl text-amber-500 mt-1"></i>
                        <div>
                            <h4 class="font-bold">Corporate Office Location</h4>
                            <p class="text-sm text-slate-400">A-1805 Tower-A, Spectrum Mall, Sector-75, Noida - 201304 (UP), India</p>
                        </div>
                    </div>
                    <div class="flex items-start space-x-4">
                        <i class="fas fa-envelope text-xl text-amber-500 mt-1"></i>
                        <div>
                            <h4 class="font-bold">Email Communication</h4>
                            <p class="text-sm text-slate-400">Tracksunsolar@gmail.com</p>
                        </div>
                    </div>
                    <div class="flex items-start space-x-4">
                        <i class="fas fa-phone-alt text-xl text-amber-500 mt-1"></i>
                        <div>
                            <h4 class="font-bold">Direct Assistance Helpline</h4>
                            <p class="text-sm text-slate-400">+91 92173 33071 / +91 120-4667255</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Form Template -->
            <div data-aos="fade-left" class="bg-white/5 p-8 rounded-2xl border border-white/10 backdrop-blur-sm">
                <h3 class="text-xl font-bold mb-6 text-amber-400">Request a Free Consultant Quote</h3>
                <form class="space-y-4" onsubmit="event.preventDefault(); alert('Query Registered Simulation!');">
                    <div>
                        <label class="block text-xs uppercase tracking-wider text-slate-400 font-bold mb-2">Your Full Name</label>
                        <input type="text" placeholder="John Doe" class="w-full bg-slate-800 border border-slate-700 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-emerald-500 transition">
                    </div>
                    <div>
                        <label class="block text-xs uppercase tracking-wider text-slate-400 font-bold mb-2">Required Capacity (KWp)</label>
                        <input type="text" placeholder="e.g. 5KWp, 10KWp, 1MW" class="w-full bg-slate-800 border border-slate-700 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-emerald-500 transition">
                    </div>
                    <div>
                        <label class="block text-xs uppercase tracking-wider text-slate-400 font-bold mb-2">Message or Requirement</label>
                        <textarea rows="3" placeholder="Describe your structural roof area..." class="w-full bg-slate-800 border border-slate-700 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-emerald-500 transition"></textarea>
                    </div>
                    <button type="submit" class="w-full bg-emerald-600 hover:bg-emerald-700 text-white font-bold py-3.5 rounded-xl shadow-lg transition">Submit Consultation Query</button>
                </form>
            </div>
        </div>
    </section>

    <!-- 8. FOOTER -->
    <footer class="bg-slate-950 py-6 text-center text-xs text-slate-500 border-t border-slate-900">
        <p>&copy; 2026 Tracksun Solar Pvt. Ltd. All Rights Reserved. Conceptualized Transformation Grid.</p>
    </footer>

    <!-- AOS Script Integration & Initiation -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 800,
            once: false,
            mirror: true
        });
    </script>
</body>
</html>
