<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StzyWorks | Digital Aesthetics</title>
    
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brandDark: '#0a0a0a',
                        electricBlue: '#0052ff',
                        electricBlueHover: '#0040cc',
                    },
                    fontFamily: {
                        blonden: ['Blonden', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Font Definition Setup */
        @font-face {
            font-family: 'Blonden';
            /* Add your actual font file path in src if hosting locally, e.g., src: url('fonts/blonden.woff2') format('woff2'); */
            src: local('Blonden'), local('Helvetica Neue'), local('Inter'), sans-serif;
            font-weight: normal;
            font-style: normal;
        }

        body {
            background-color: #0a0a0a;
        }

        /* Hide scrollbar for a cleaner look */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0a0a0a; 
        }
        ::-webkit-scrollbar-thumb {
            background: #222; 
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #0052ff; 
        }
    </style>
</head>
<body class="font-blonden text-white bg-brandDark antialiased selection:bg-electricBlue selection:text-white overflow-x-hidden">

    <nav class="fixed top-0 w-full z-50 bg-white/5 backdrop-blur-lg border-b border-white/10" data-aos="fade-down" data-aos-duration="1000">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold tracking-wider text-white">Stzy<span class="text-electricBlue">Works</span></a>
            <a href="#work" class="text-sm tracking-wide text-gray-300 hover:text-electricBlue transition-colors duration-300">Portfolio</a>
        </div>
    </nav>

    <section class="relative min-h-screen flex items-center justify-center px-6 pt-20">
        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[300px] h-[300px] bg-electricBlue/20 rounded-full blur-[120px] pointer-events-none"></div>
        
        <div class="relative z-10 max-w-4xl mx-auto text-center" data-aos="fade-up" data-aos-duration="1200">
            <h1 class="text-5xl md:text-7xl lg:text-8xl font-bold tracking-tight mb-6 leading-tight">
                Crafting the future of <br/>
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-electricBlue to-blue-300">digital aesthetics.</span>
            </h1>
            <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed">
                Specializing in high-end YouTube thumbnails, AI-integrated systems, and elite trading interfaces.
            </p>
            <a href="#work" class="inline-block bg-electricBlue hover:bg-electricBlueHover text-white px-8 py-4 rounded-full font-medium tracking-wide transition-all duration-300 hover:scale-105 hover:shadow-[0_0_20px_rgba(0,82,255,0.4)]">
                View Work
            </a>
        </div>
    </section>

    <section id="work" class="py-24 px-6 max-w-7xl mx-auto">
        <div class="mb-16" data-aos="fade-up">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">Selected Works</h2>
            <div class="w-16 h-1 bg-electricBlue rounded"></div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            
            <div class="bg-white/5 backdrop-blur-md border border-white/10 rounded-2xl p-6 group transition-all duration-300 hover:border-electricBlue/50 hover:-translate-y-2 cursor-pointer" data-aos="fade-up" data-aos-delay="100">
                <div class="w-full h-48 bg-black/40 rounded-xl mb-6 overflow-hidden relative">
                    <div class="absolute inset-0 flex items-center justify-center text-electricBlue group-hover:scale-110 transition-transform duration-500">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z"></path></svg>
                    </div>
                </div>
                <h3 class="text-xl font-semibold mb-2">High-End Thumbnails</h3>
                <p class="text-gray-400 text-sm">Visual hooks engineered for maximum CTR and audience retention.</p>
            </div>

            <div class="bg-white/5 backdrop-blur-md border border-white/10 rounded-2xl p-6 group transition-all duration-300 hover:border-electricBlue/50 hover:-translate-y-2 cursor-pointer" data-aos="fade-up" data-aos-delay="200">
                <div class="w-full h-48 bg-black/40 rounded-xl mb-6 overflow-hidden relative">
                    <div class="absolute inset-0 flex items-center justify-center text-electricBlue group-hover:scale-110 transition-transform duration-500">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                    </div>
                </div>
                <h3 class="text-xl font-semibold mb-2">AI-Integrated Systems</h3>
                <p class="text-gray-400 text-sm">Seamlessly blending machine learning with fluid UI architectures.</p>
            </div>

            <div class="bg-white/5 backdrop-blur-md border border-white/10 rounded-2xl p-6 group transition-all duration-300 hover:border-electricBlue/50 hover:-translate-y-2 cursor-pointer" data-aos="fade-up" data-aos-delay="300">
                <div class="w-full h-48 bg-black/40 rounded-xl mb-6 overflow-hidden relative">
                    <div class="absolute inset-0 flex items-center justify-center text-electricBlue group-hover:scale-110 transition-transform duration-500">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M7 12l3-3 3 3 4-4M8 21l4-4 4 4M3 4h18M4 4h16v12a1 1 0 01-1 1H5a1 1 0 01-1-1V4z"></path></svg>
                    </div>
                </div>
                <h3 class="text-xl font-semibold mb-2">Elite Trading UI</h3>
                <p class="text-gray-400 text-sm">Real-time data visualization wrapped in pixel-perfect dark mode.</p>
            </div>

            <label for="mobile-upload" class="bg-electricBlue/10 backdrop-blur-md border border-electricBlue/30 border-dashed rounded-2xl p-6 flex flex-col items-center justify-center text-center cursor-pointer transition-all duration-300 hover:bg-electricBlue/20 hover:scale-105" data-aos="fade-up" data-aos-delay="400">
                <input type="file" id="mobile-upload" accept="image/*" class="hidden">
                
                <div class="w-16 h-16 bg-electricBlue/20 rounded-full flex items-center justify-center mb-4 text-electricBlue">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-8l-4-4m0 0L8 8m4-4v12"></path></svg>
                </div>
                <h3 class="text-xl font-semibold mb-2 text-white">Upload Media</h3>
                <p class="text-electricBlue text-sm font-medium">Tap to open your mobile gallery or camera.</p>
            </label>

        </div>
    </section>

    <footer class="border-t border-white/10 mt-20" data-aos="fade-up">
        <div class="max-w-7xl mx-auto px-6 py-8 flex flex-col md:flex-row justify-between items-center text-sm text-gray-500">
            <p>&copy; 2026 StzyWorks. All rights reserved.</p>
            <div class="flex space-x-6 mt-4 md:mt-0">
                <a href="#" class="hover:text-electricBlue transition-colors">Twitter</a>
                <a href="#" class="hover:text-electricBlue transition-colors">Instagram</a>
                <a href="#" class="hover:text-electricBlue transition-colors">Dribbble</a>
            </div>
        </div>
    </footer>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        // Initialize AOS animations
        AOS.init({
            once: true,         // whether animation should happen only once - while scrolling down
            offset: 50,         // offset (in px) from the original trigger point
            easing: 'ease-out-cubic',
        });
    </script>
</body>
</html>
