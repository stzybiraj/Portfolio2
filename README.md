<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StzyWorks | Digital Luxury</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400;700&family=Inter:wght@300;400&display=swap" rel="stylesheet">
    
    <style>
        /* Base typography setup */
        body { 
            font-family: 'Inter', sans-serif; 
            background-color: #000; 
        }
        h1, h2, .brand-text { 
            font-family: 'Montserrat', sans-serif; 
        }

        /* Branding Glow Effect */
        .neon-glow {
            color: #0077FF; /* Deep Electric Blue */
            text-shadow: 0 0 25px rgba(0, 119, 255, 0.8), 0 0 5px rgba(0, 119, 255, 0.4);
        }

        /* Ambient Background Glow */
        .ambient-radial {
            background: radial-gradient(circle, rgba(14, 60, 150, 0.12) 0%, rgba(60, 20, 100, 0.08) 35%, rgba(0,0,0,0) 70%);
        }

        /* Subtle Branding Divider */
        .premium-divider {
            background: linear-gradient(90deg, rgba(0,119,255,0.9) 0%, rgba(0,119,255,0.1) 80%, transparent 100%);
        }
    </style>
</head>
<body class="bg-gradient-to-b from-[#060a14] to-black min-h-screen text-white overflow-x-hidden relative selection:bg-blue-600/30">

    <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[800px] h-[800px] md:w-[1000px] md:h-[1000px] ambient-radial rounded-full blur-[80px] pointer-events-none z-0"></div>

    <header class="absolute top-0 left-0 w-full flex justify-between items-start z-50 pointer-events-none">
        
        <div class="p-12 md:p-16 flex flex-col pointer-events-auto">
            <div class="brand-text text-3xl md:text-4xl tracking-widest cursor-default select-none flex items-center">
                <span class="font-bold text-white">Stzy</span>
                <span class="font-normal neon-glow ml-[2px]">Works</span>
            </div>
            <div class="h-[1px] w-full max-w-[140px] mt-5 premium-divider opacity-70"></div>
        </div>

        <div class="p-12 md:p-16 flex gap-[8px] items-center justify-center cursor-pointer hover:opacity-60 transition-opacity duration-300 pointer-events-auto mt-2">
            <div class="w-[1px] h-9 bg-white/80"></div>
            <div class="w-[1px] h-9 bg-white/80"></div>
            <div class="w-[1px] h-9 bg-white/80"></div>
        </div>

    </header>

    <main class="relative z-10 flex flex-col items-center justify-center min-h-screen w-full px-6">
        
        <div class="flex flex-col items-center text-center max-w-4xl w-full mt-10">

            <h1 data-aos="fade-up" 
                class="text-4xl md:text-6xl lg:text-7xl font-light tracking-tight mb-14 leading-[1.3] text-white/95">
                Designing <br /> 
                <span class="font-bold text-white">Digital Luxury</span>
            </h1>

            <p data-aos="fade-up" data-aos-delay="200" 
               class="text-gray-500 text-sm md:text-base leading-loose md:leading-[2.2] max-w-xl mb-20 tracking-wide">
                We craft meticulous, high-end digital experiences. By stripping away the unnecessary, we elevate brands through pixel-perfect symmetry, deep aesthetic resonance, and uncompromising performance.
            </p>

            <button data-aos="fade-up" data-aos-delay="400" 
                    class="group relative px-16 py-5 uppercase tracking-[0.25em] text-xs font-semibold rounded-full border border-gray-800 bg-transparent text-gray-300 hover:text-white hover:border-blue-500/40 hover:bg-blue-900/10 hover:shadow-[0_0_30px_rgba(0,119,255,0.25)] transition-all duration-500 ease-out transform hover:scale-105">
                View Work
            </button>
            
        </div>
    </main>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 1600,
            once: true,
            easing: 'ease-out-cubic',
        });
    </script>
</body>
</html>
