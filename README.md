<title>Borayana LOEUN - Modern Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter & Poppins (for headings) -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Poppins:wght@600;700;800&display=swap" rel="stylesheet">
    <style>
        /* Custom styles for the fonts and smooth scrolling */
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background-color: #F8FAFC; /* Light Blue-Gray */
        }
        h1, h2, h3 {
            font-family: 'Poppins', sans-serif;
        }
        /* Style for active navigation link */
        .nav-link.active {
            font-weight: 700;
            color: #6366F1; /* Tailwind's violet-600 */
            border-bottom: 2px solid #6366F1;
            padding-bottom: 4px;
        }
        /* Custom card hover effect */
        .card-hover:hover {
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            transform: translateY(-5px);
        }
        /* Custom button hover effect */
        .btn-primary {
            transition: all 0.3s ease;
        }
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(99, 102, 241, 0.4);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 antialiased">
    <!-- Header Section -->
    <header class="bg-white shadow-lg sticky top-0 z-50 py-4">
        <nav class="container mx-auto px-4 flex flex-col sm:flex-row justify-between items-center">
            <!-- Brand/Logo -->
            <a href="#about" class="text-3xl font-extrabold text-violet-600 mb-2 sm:mb-0 transform hover:scale-105 transition-transform duration-300">Borayana LOEUN</a>
            <!-- Navigation Links -->
            <ul class="flex space-x-8 text-lg">
                <li><a href="#about" class="nav-link text-gray-700 hover:text-violet-600 transition duration-300">About</a></li>
                <li><a href="#portfolio" class="nav-link text-gray-700 hover:text-violet-600 transition duration-300">Portfolio</a></li>
                <li><a href="#experience" class="nav-link text-gray-700 hover:text-violet-600 transition duration-300">Experience</a></li>
                <li><a href="#skills" class="nav-link text-gray-700 hover:text-violet-600 transition duration-300">Skills</a></li>
                <li><a href="#contact" class="nav-link text-gray-700 hover:text-violet-600 transition duration-300">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content Area -->
    <main class="container mx-auto px-4 py-12 md:py-16">

        <!-- About Me Section -->
        <section id="about" class="bg-white rounded-3xl shadow-xl p-8 md:p-12 mb-16 flex flex-col md:flex-row items-center justify-center space-y-8 md:space-y-0 md:space-x-12">
            <!-- Profile Image -->
            <div class="flex-shrink-0 relative">
                <!-- User's uploaded profile image -->
                <img src="image_a726bd.jpg" alt="Borayana LOEUN Profile Picture" class="w-52 h-52 rounded-full object-cover shadow-2xl border-4 border-violet-300 animate-fade-in">
                <!-- Decorative pulse effect -->
                <span class="absolute top-0 left-0 w-full h-full rounded-full bg-violet-400 opacity-20 animate-pulse"></span>
            </div>
            <!-- About Me Content -->
            <div class="text-center md:text-left max-w-3xl">
                <p class="text-xl text-violet-600 font-semibold mb-3">Hello there!</p>
                <h1 class="text-5xl font-extrabold text-gray-900 leading-tight mb-5">I'm Borayana LOEUN, <br><span class="text-violet-700">a Women and children right's monitor, and content creation.</span></h1>
                <p class="text-lg text-gray-700 leading-relaxed mb-6">
                    With a background in Social Science and Public Law, I blend media expertise with dedicated human rights monitoring and community advocacy. My work focuses on empowering women and children, raising LGBTIQ+ awareness, and driving positive social change through impactful communication and meticulous research.
                </p>
                <a href="#contact" class="inline-block bg-violet-600 text-white font-semibold py-3 px-8 rounded-full shadow-lg hover:bg-violet-700 btn-primary">
                    Let's Connect
                </a>
            </div>
        </section>

        <!-- Portfolio Section -->
        <section id="portfolio" class="mb-16">
            <h2 class="text-4xl font-bold text-gray-900 text-center mb-10">My Photography & Videography Work</h2>

            <!-- Photography Sub-section -->
            <div class="mb-12">
                <h3 class="text-3xl font-bold text-gray-800 mb-6 text-center md:text-left">Photography</h3>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">

            
                    <!-- Project Card: Film Photography -->
                    <div class="bg-white rounded-2xl shadow-lg overflow-hidden transition-all duration-300 card-hover">
                        <img src="https://placehold.co/600x400/BFDBFE/1D4ED8?text=Film+Photography" alt="Film Photography Project" class="w-full h-56 object-cover transform hover:scale-105 transition-transform duration-500">
                        <div class="p-7">
                            <h4 class="text-2xl font-semibold text-gray-900 mb-3">Film-Related Photography</h4>
                            <p class="text-gray-700 mb-5 text-base leading-relaxed">
                                Photography work specifically for film projects, capturing behind-the-scenes, promotional stills, and narrative moments to enhance storytelling.
                            </p>
                            <div class="flex flex-wrap gap-3 mb-5">
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Film Stills</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Promotional</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Set Photography</span>
                            </div>
                            <a href="#" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                View Gallery
                                <svg class="ml-2 w-5 h-5 transition-transform duration-300 group-hover:translate-x-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                            </a>
                            <a href="https://www.facebook.com/share/p/1BeEBnypBK/" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Facebook Post 1 &rarr;
                                </a>
                                <a href="https://www.facebook.com/share/p/19DpzyiPJf/" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Facebook Post 2 &rarr;
                                </a>
                                <a href="https://www.facebook.com/share/p/16cHgRNjXF/" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Facebook Post 3 &rarr;
                                </a>
                                <a href="https://www.facebook.com/share/p/16QUGEkdA7/" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Facebook Post 4 &rarr;
                                </a>
                                <a href="https://www.facebook.com/share/p/1A57zmzJ6s/" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Facebook Post 5 &rarr;
                                </a>
                                <a href="https://www.facebook.com/share/p/1HjyAQpfNs/" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Facebook Post 6 &rarr;
                                </a>
                                <a href="https://www.facebook.com/share/p/1J4Q3ovSm4/" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Facebook Post 7 &rarr;
                                </a>
                        </div>
                    </div>
                    <!-- New Project Card: LICADHO & General Photography -->
                    <div class="bg-white rounded-2xl shadow-lg overflow-hidden transition-all duration-300 card-hover">
                        <img src="https://placehold.co/600x400/F0F2FF/6366F1?text=LICADHO+Photos" alt="LICADHO and General Photography" class="w-full h-56 object-cover transform hover:scale-105 transition-transform duration-500">
                        <div class="p-7">
                            <h4 class="text-2xl font-semibold text-gray-900 mb-3">Human Rights & General Event Photography</h4>
                            <p class="text-gray-700 mb-5 text-base leading-relaxed">
                                Documenting human rights events, workshops, and general social activities through photography, showcasing impactful moments and community engagement.
                            </p>
                            <div class="flex flex-wrap gap-3 mb-5">
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Photojournalism</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Event Photography</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Human Rights</span>
                            </div>
                            <div class="space-y-2">
                                <a href="https://www.licadho-cambodia.org/album/view_photo.php?cat=95#9" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    LICADHO Album 1 &rarr;
                                </a>
                                <a href="https://www.licadho-cambodia.org/album/view_photo.php?cat=112" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    LICADHO Album 2 &rarr;
                                </a>
                                <a href="https://www.licadho-cambodia.org/album/view_photo.php?cat=114#5" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    LICADHO Album 3 &rarr;
                                </a>
                                <a href="https://www.facebook.com/share/p/1A4PnpmqF2/" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Facebook Post 8 &rarr;
                                </a>
                            </div>
                        </div>
                    </div>

                </div>
            </div>

            <!-- Videography Sub-section -->
            <div>
                <h3 class="text-3xl font-bold text-gray-800 mb-6 text-center md:text-left">Videography</h3>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">

                    <!-- New Project Card: Film Production (KongRorest Film Videos) -->
                    <div class="bg-white rounded-2xl shadow-lg overflow-hidden transition-all duration-300 card-hover">
                        <img src="https://placehold.co/600x400/DDE3F0/4F46E5?text=KongRorest+Film+Videos" alt="KongRorest Film Video Production" class="w-full h-56 object-cover transform hover:scale-105 transition-transform duration-500">
                        <div class="p-7">
                            <h4 class="text-2xl font-semibold text-gray-900 mb-3">Film Production (KongRorest Film)</h4>
                            <p class="text-gray-700 mb-5 text-base leading-relaxed">
                                A collection of film and video projects I contributed to during my time as a Camera Operator Intern at KongRorest Film.
                            </p>
                            <div class="flex flex-wrap gap-3 mb-5">
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Film Production</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Camera Operation</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Video Editing</span>
                            </div>
                            <div class="space-y-2">
                                <a href="https://www.facebook.com/kongrotesfilm/videos/419413843345456" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 1 &rarr;
                                </a>
                                <a href="https://www.facebook.com/kongrotesfilm/videos/4790935401015796" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 2 &rarr;
                                </a>
                                <a href="https://www.facebook.com/kongrotesfilm/videos/524648005601168" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 3 &rarr;
                                </a>
                                <a href="https://www.facebook.com/kongrotesfilm/videos/5060778313943992" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 4 &rarr;
                                </a>
                                <a href="https://www.facebook.com/kongrotesfilm/videos/467583274415246" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 5 &rarr;
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- Project Card: Videography - Interviews/Talk Shows -->
                    <div class="bg-white rounded-2xl shadow-lg overflow-hidden transition-all duration-300 card-hover">
                        <img src="https://placehold.co/600x400/DDE3F0/4F46E5?text=Interview+Video" alt="Interview Videography Project" class="w-full h-56 object-cover transform hover:scale-105 transition-transform duration-500">
                        <div class="p-7">
                            <h4 class="text-2xl font-semibold text-gray-900 mb-3">Interview & Talk Show Production</h4>
                            <p class="text-gray-700 mb-5 text-base leading-relaxed">
                                Developed and produced engaging interview segments and talk shows, including content for digital platforms like TikTokTalk, showcasing strong video operation and editing skills.
                            </p>
                            <div class="flex flex-wrap gap-3 mb-5">
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Videography</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Interview</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Editing</span>
                            </div>
                            <a href="#" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                Watch Videos
                                <svg class="ml-2 w-5 h-5 transition-transform duration-300 group-hover:translate-x-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                            </a>
                             <a href="https://www.tiktok.com/@loveisdiversity" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                 See More Videos
                        </div>
                    </div>

                    <!-- Project Card: Videography - Awareness Campaigns (LoveIsDiversity) -->
                    <div class="bg-white rounded-2xl shadow-lg overflow-hidden transition-all duration-300 card-hover">
                        <img src="https://placehold.co/600x400/E0E7FF/4F46E5?text=LoveIsDiversity+Campaigns" alt="LoveIsDiversity Awareness Campaign Video Project" class="w-full h-56 object-cover transform hover:scale-105 transition-transform duration-500">
                        <div class="p-7">
                            <h4 class="text-2xl font-semibold text-gray-900 mb-3">Social Awareness Video Campaigns (LoveIsDiversity)</h4>
                            <p class="text-gray-700 mb-5 text-base leading-relaxed">
                                Produced impactful videos for social awareness, focusing on issues faced by the LGBTIQ+ community, aimed at fostering understanding and promoting acceptance.
                            </p>
                            <div class="flex flex-wrap gap-3 mb-5">
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Social Impact</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">LGBTIQ+ Rights</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Video Production</span>
                            </div>
                            <div class="space-y-2">
                                <a href="https://www.facebook.com/loveisdiversity/videos/475799048447545" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 1 &rarr;
                                </a>
                                <a href="https://www.facebook.com/loveisdiversity/videos/374795035405924" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 2 &rarr;
                                </a>
                                <a href="https://www.facebook.com/loveisdiversity/videos/911047387421037" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 3 &rarr;
                                </a>
                                <a href="https://www.facebook.com/loveisdiversity/videos/701350522083747" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 4 &rarr;
                                </a>
                                <a href="https://www.facebook.com/loveisdiversity/videos/2686647234833605" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 5 &rarr;
                                </a>
                                <a href="https://www.facebook.com/loveisdiversity/videos/254799710920393" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 6 &rarr;
                                </a>
                                <a href="https://www.facebook.com/loveisdiversity/videos/712366414141975" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 7 &rarr;
                                </a>
                                <a href="https://www.facebook.com/loveisdiversity/videos/6770787769623096" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 8 &rarr;
                                </a>
                                <a href="https://www.facebook.com/loveisdiversity/videos/868118901528489" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 9 &rarr;
                                </a>
                                <a href="https://www.facebook.com/loveisdiversity/videos/1306595873396111" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 10 &rarr;
                                </a>
                                <a href="https://www.facebook.com/loveisdiversity/videos/810088197506689" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                    Video 11 &rarr;
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- Project Card: Videography - Blue Dolphin Swimming Club -->
                    <div class="bg-white rounded-2xl shadow-lg overflow-hidden transition-all duration-300 card-hover">
                        <img src="https://placehold.co/600x400/BFDBFE/1D4ED8?text=Blue+Dolphin+Videos" alt="Blue Dolphin Swimming Club Videos" class="w-full h-56 object-cover transform hover:scale-105 transition-transform duration-500">
                        <div class="p-7">
                            <h4 class="text-2xl font-semibold text-gray-900 mb-3">Blue Dolphin Club Media Content</h4>
                            <p class="text-gray-700 mb-5 text-base leading-relaxed">
                                Produced a range of engaging video content for Blue Dolphin Swimming Club, including promotional videos, class highlights (Yoga, Taekwondo), and testimonials.
                            </p>
                            <div class="flex flex-wrap gap-3 mb-5">
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Sports Media</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Promotional Video</span>
                                <span class="text-sm font-medium bg-violet-100 text-violet-700 px-3 py-1.5 rounded-full">Event Highlights</span>
                            </div>
                            <a href="https://www.facebook.com/BlueDolphinSwimmingClubCambodia" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold flex items-center group">
                                See More Videos
                                <svg class="ml-2 w-5 h-5 transition-transform duration-300 group-hover:translate-x-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Work Experience Section -->
        <section id="experience" class="mb-16">
            <h2 class="text-4xl font-bold text-gray-900 text-center mb-10">Professional Journey</h2>
            <div class="space-y-10">
                <!-- Job Entry: Media Officer (Part time) -->
                <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Media Officer (Part-time)</h3>
                            <p class="text-violet-600 text-lg">Blue Dolphin Swimming Club</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">2024 – Present</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Developed, shot, and edited videos and photos for dynamic campaigns and daily content.</li>
                        <li>Designed engaging graphics and layouts for diverse social media platforms and promotional materials.</li>
                        <li>Wrote compelling captions, articles, blog posts, and success stories to amplify club presence.</li>
                        <li>Strategically planned, scheduled, and managed posts across key platforms (Facebook, Instagram, TikTok, YouTube).</li>
                        <li>Monitor analytics for continuous improvement and fostered community engagement through timely responses.</li>
                    </ul>
                    <!-- Link to Facebook Page -->
                    <p class="mt-4 text-sm text-gray-600">
                        Learn more about my work at the <a href="https://www.facebook.com/BlueDolphinSwimmingClubCambodia" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold underline">Blue Dolphin Swimming Club Facebook page</a>.
                    </p>
                </div>

                <!-- Job Entry: Women & Children's Violation Monitor -->
                <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Women & Children's Violation Monitor</h3>
                            <p class="text-violet-600 text-lg">The Cambodian League for the Promotion and Defense of Human Rights (LICADHO)</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">Feb 2023 – Present</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Ensured high-quality investigations, case management, and client services for women and children affected by rights violations.</li>
                        <li>Conducted sensitive interviews, provided crucial legal advice, drafted formal complaints, and accompanied victims for holistic support.</li>
                        <li>Actively supported advocacy initiatives related to women's and children's rights through compelling content, photography, and videography.</li>
                        <li>Engaged in vital monitoring and protection efforts concerning Human Rights, including observing public gatherings and comprehensive reporting.</li>
                    </ul>
                </div>

                <!-- Job Entry: Media Team Leader (Volunteer) -->
                <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Media Team Leader (Volunteer)</h3>
                            <p class="text-violet-600 text-lg">LoveIsDiversity</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">2019 – 2024</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Led initiatives to raise public awareness of LGBTIQ+ people through impactful video production and digital storytelling.</li>
                        <li>Served as a key video and photos operator, assisting in crafting compelling content proposals focused on LGBTIQ+ rights.</li>
                        <li>Managed and optimized TikTok and YouTube channels, contributing to broader digital outreach and community engagement.</li>
                    </ul>
                    <!-- Links to Facebook and TikTok Pages -->
                    <p class="mt-4 text-sm text-gray-600">
                        Explore their work on:
                        <a href="https://www.facebook.com/loveisdiversity" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold underline mr-2">Facebook</a> |
                        <a href="https://www.tiktok.com/@loveisdiversity" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold underline">TikTok</a>
                    </p>
                </div>

                <!-- Job Entry: Prison Project Researcher -->
                <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Prison Project Researcher</h3>
                            <p class="text-violet-600 text-lg">The Cambodian League for the Promotion and Defense of Human Rights (LICADHO)</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">Sep 2018 – Jan 2023</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Assisted in the planning, implementation, monitoring, and reporting of critical activities related to prisoner's rights.</li>
                        <li>Conducted direct visits and interviews with prisoners, providing essential legal advice and intervening in cases of detainee rights violations.</li>
                        <li>Contributed significantly to the "Early Year Behind Bar" project, specifically supporting minor prisoners, mothers, and children in prison.</li>
                    </ul>
                </div>

                <!-- Job Entry: Camera Operator Intern -->
                <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Camera Operator Intern</h3>
                            <p class="text-violet-600 text-lg">KongRorest Film</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">2016 – 2023</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Functioned as a versatile camera operator and film assistant, ensuring smooth production workflows.</li>
                        <li>Managed lighting setups, prepared sets, and contributed to script editing for various film projects.</li>
                    </ul>
                    <!-- Link to Facebook Page -->
                    <p class="mt-4 text-sm text-gray-600">
                        View projects on:
                        <a href="https://www.facebook.com/kongrotesfilm" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold underline mr-2">Facebook</a> |
                        <a href="https://www.tiktok.com/@kongrotes_film" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold underline">TikTok</a>
                    </p>
                </div>

                <!-- Job Entry: Assistant Producer Assistant Director -->
                 <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Assistant Producer / Assistant Director</h3>
                            <p class="text-violet-600 text-lg">CTV9HD Nira and International School</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">2018</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Oversaw general administration and public relations within the Admin and HR departments.</li>
                        <li>Managed and optimized various social media platforms, including Facebook, YouTube, and Instagram.</li>
                        <li>Handled critical pre-production tasks suchs as scouting locations, creating filming schedules, developing budget plans, and writing permission applications.</li>
                    </ul>
                     <a href="https://www.facebook.com/CTV9HDCambodia" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold underline">favebook page</a>
                    </p>
                </div>

                <!-- Job Entry: Assistant Director (Company Administrator) -->
                <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Assistant Director (Company Administrator)</h3>
                            <p class="text-violet-600 text-lg">Morodok Memorial Planning</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">2016 – 2018</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Assisted with comprehensive risk management tasks, encompassing identification, assessment, analysis, and strategic mitigation planning.</li>
                        <li>Actively promoted a risk-aware organizational culture and ensured strict compliance with relevant regulations.</li>
                        <li>Contributed to operational optimization through strategic planning, efficient resource management, and robust quality control.</li>
                        <li>Managed diverse digital marketing activities across social media, graphic design, customer service, and sales support.</li>
                    </ul>
                     <a href="https://www.facebook.com/morodokmp" target="_blank" class="text-violet-600 hover:text-violet-800 font-semibold underline">favebook page</a>
                    </p>
                </div>

                <!-- Job Entry: Intern -->
                <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Intern</h3>
                            <p class="text-violet-600 text-lg">Youth for Peace</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">2015 – 2016</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Engaged in key leadership development programs focused on post-Khmer Rouge youth initiatives.</li>
                        <li>Gained valuable skills in out-of-court dispute resolution, advocacy fundamentals, and professional report and proposal writing.</li>
                        <li>Developed strong negotiation and communication techniques essential for effective conflict resolution and collaboration.</li>
                    </ul>
                </div>

                <!-- Job Entry: Receptionist -->
                <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Receptionist</h3>
                            <p class="text-violet-600 text-lg">Khemara Battambang Hotel</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">2014</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Skillfully managed guest arrivals and departures, overseeing efficient check-in/check-out processes.</li>
                        <li>Provided comprehensive concierge support, ensuring guest satisfaction and seamless experiences.</li>
                        <li>Professionally handled phone inquiries, bookings, and reservation updates.</li>
                        <li>Coordinated effectively with housekeeping and other departments to fulfill guest needs and ensure smooth hotel operations.</li>
                        <li>Prepared accurate monthly financial reports for hotel management, contributing to informed decision-making.</li>
                    </ul>
                </div>

                <!-- Job Entry: Assistant Restaurant Staff (F&B Experience) -->
                <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Assistant Restaurant Staff (F&B Experience)</h3>
                            <p class="text-violet-600 text-lg">BBU Mart</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">2013 – 2015</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Assisted with daily food and beverage services, ensuring efficient and high-quality customer experience.</li>
                        <li>Provided crucial support in kitchen preparation, served customers promptly, and managed orders effectively.</li>
                        <li>Maintained high standards of cleanliness and ensured hygienic food handling practices at all times.</li>
                        <li>Actively assisted the chef with basic food preparation tasks and supported the barista during peak hours.</li>
                    </ul>
                </div>

                <!-- Job Entry: Service Staff & Receptionist (Protocol Duties) -->
                <div class="bg-white rounded-2xl shadow-lg p-7 transition-all duration-300 card-hover">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-2xl font-semibold text-gray-900">Service Staff & Receptionist (Protocol Duties)</h3>
                            <p class="text-violet-600 text-lg">Pronit Pithika</p>
                        </div>
                        <p class="text-gray-500 text-sm font-medium">2013 – 2015</p>
                    </div>
                    <ul class="list-disc list-inside text-gray-700 space-y-2 text-base">
                        <li>Warmly greeted guests and VIP visitors, ensuring a professional and welcoming atmosphere during events and formal gatherings.</li>
                        <li>Provided efficient reception and seating services during ceremonies and conferences, ensuring smooth guest flow.</li>
                        <li>Supported administrative setup for meetings and meticulously coordinated hospitality services to meet high standards.</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="mb-16">
            <h2 class="text-4xl font-bold text-gray-900 text-center mb-10">Skills & Expertise</h2>
            <div class="bg-white rounded-3xl shadow-xl p-8 md:p-12">
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Technical Skills -->
                    <div>
                        <h3 class="text-2xl font-semibold text-gray-900 mb-5 border-b-2 pb-3 border-violet-200">Technical & Software</h3>
                        <ul class="list-disc list-inside text-gray-700 space-y-3 text-base">
                            <li><span class="font-medium text-violet-700">Video Editing:</span> Adobe Premiere Pro, CapCut</li>
                            <li><span class="font-medium text-violet-700">Design:</span> Canva design, Adobe Lightroom (color editing)</li>
                            <li><span class="font-medium text-violet-700">Office Suite:</span> Microsoft Word, Excel, PowerPoint</li>
                            <li><span class="font-medium text-violet-700">Digital Literacy:</span> Internet Research, Email Management</li>
                            <li><span class="font-medium text-violet-700">Camera Operation:</span> Sony Alpha, Canon 70D/5D</li>
                            <li><span class="font-medium text-violet-700">Production Roles:</span> Assistant Producer, Studio Setup, Lighting</li>
                            <li><span class="font-medium text-violet-700">Writing:</span> Script Editing, News Copywriting</li>
                        </ul>
                    </div>
                    <!-- Professional & Soft Skills -->
                    <div>
                        <h3 class="text-2xl font-semibold text-gray-900 mb-5 border-b-2 pb-3 border-violet-200">Professional & Soft Skills</h3>
                        <ul class="list-disc list-inside text-gray-700 space-y-3 text-base">
                            <li>Event Operation & Management</li>
                            <li>Master of Ceremonies (MC)</li>
                            <li>Hospitality Management</li>
                            <li>Strategic Planning & Organization</li>
                            <li>Monitoring & Evaluation Techniques</li>
                            <li>Advanced News Writing</li>
                            <li>Effective Negotiation & Communication</li>
                            <li>Facilitation & Advisory Skills</li>
                            <li>Victim Social Assessment</li>
                            <li>Professional Camera Operation</li>
                            <li>Video Production (End-to-End)</li>
                            <li>Radio Program Moderation</li>
                        </ul>
                    </div>
                    <!-- Languages -->
                    <div>
                        <h3 class="text-2xl font-semibold text-gray-900 mb-5 border-b-2 pb-3 border-violet-200">Languages</h3>
                        <ul class="list-disc list-inside text-gray-700 space-y-3 text-base">
                            <li><span class="font-medium text-violet-700">Khmer:</span> Professional proficiency</li>
                            <li><span class="font-medium text-violet-700">English:</span> Good proficiency</li>
                            <li><span class="font-medium text-violet-700">Thai:</span> Good proficiency</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="bg-white rounded-3xl shadow-xl p-8 md:p-12 text-center">
            <h2 class="text-4xl font-bold text-gray-900 mb-8">Let's Create Something Together</h2>
            <p class="text-lg text-gray-700 mb-8 max-w-2xl mx-auto">
                I am always eager to explore new opportunities, collaborations, and projects that align with my passion for media, human rights, and social impact. Don't hesitate to reach out!
            </p>
            <div class="flex flex-col sm:flex-row justify-center items-center space-y-5 sm:space-y-0 sm:space-x-8">
                <!-- Email Link -->
                <a href="mailto:borayanaloeun@gmail.com" class="bg-violet-600 text-white font-semibold py-4 px-8 rounded-full shadow-lg hover:bg-violet-700 btn-primary flex items-center text-lg">
                    <svg class="w-6 h-6 mr-3" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"></path><path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"></path></svg>
                    borayanaloeun@gmail.com
                </a>
                <!-- Phone Number -->
                <span class="bg-gray-100 text-gray-800 font-semibold py-4 px-8 rounded-full shadow-md flex items-center text-lg">
                    <svg class="w-6 h-6 mr-3 text-violet-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.774a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.06-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"></path></svg>
                    +855 69 364 757
                </span>
            </div>
            <!-- Link to your Resume/CV -->
            <p class="mt-10 text-gray-600 text-base">
                Prefer a quick overview? Download my full <a href="LOEUN BORAYANA CV .pdf" download="LOEUN_BORAYANA_CV.pdf" class="text-violet-600 hover:text-violet-800 font-semibold underline underline-offset-4">Resume/CV here</a>.
            </p>
        </section>

    </main>

    <!-- Footer Section -->
    <footer class="bg-gray-900 text-white py-8 text-center mt-16 rounded-t-3xl shadow-inner">
        <p class="text-sm opacity-90">&copy; 2025 Borayana LOEUN. All rights reserved.</p>
        <div class="mt-3 text-xs text-gray-400 opacity-80">
            Designed with <span class="text-red-400">&hearts;</span> and <a href="https://tailwindcss.com/" target="_blank" class="text-blue-300 hover:underline">Tailwind CSS</a>.
        </div>
    </footer>

    <script>
        // JavaScript to highlight the active navigation link based on scroll position
        const sections = document.querySelectorAll('section[id]');
        const navLinks = document.querySelectorAll('.nav-link');

        window.addEventListener('scroll', () => {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                // Offset adjusted for header height and a smoother transition point
                if (pageYOffset >= sectionTop - window.innerHeight / 3) {
                    current = section.getAttribute('id');
                }
            });

            navLinks.forEach(link => {
                link.classList.remove('active');
                if (link.href.includes(current)) {
                    link.classList.add('active');
                }
            });
        });

        // Initial check for active link on load and on hash change
        const setActiveNav = () => {
            const initialSection = window.location.hash.substring(1) || 'about';
            navLinks.forEach(link => {
                link.classList.remove('active'); // Remove active from all first
                if (link.href.includes(initialSection)) {
                    link.classList.add('active');
                }
            });
        };
        document.addEventListener('DOMContentLoaded', setActiveNav);
        window.addEventListener('hashchange', setActiveNav); // Update on hash change
    </script>
</body>
</html>




