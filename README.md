<html>
<html lang="id" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Undangan Pernikahan Retno & Jono</title>
  
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  
  <!-- Google Fonts: Kombinasi Serif Mewah, San-Serif Modern, dan Aksentuasi Jawa -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700&family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&family=Great+Vibes&display=swap" rel="stylesheet">
  
  <!-- FontAwesome untuk Icon UI -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  
  <!-- Animate.css untuk Transisi Elegan -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>

  <style>
    /* Mengatur Font Utama */
    body {
      font-family: 'Plus Jakarta Sans', sans-serif;
      background-color: #fcf9f2; /* Krem Lembut */
      color: #3e3223; /* Cokelat Gelap Hangat khas Jawa */
    }
    
    /* Font Khusus Estetika */
    .font-serif-elegant {
      font-family: 'Playfair Display', serif;
    }
    .font-accent {
      font-family: 'Great Vibes', cursive;
    }
    .font-header {
      font-family: 'Cinzel', serif;
    }
    
    /* Scrollbar Kustom agar Terlihat Premium */
    ::-webkit-scrollbar {
      width: 6px;
    }
    ::-webkit-scrollbar-track {
      background: #f1ebd9;
    }
    ::-webkit-scrollbar-thumb {
      background: #c3a473;
      border-radius: 3px;
    }

    /* Pola Latar Belakang Batik Kawung Halus */
    .bg-batik {
      background-image: radial-gradient(#c3a473 0.5px, transparent 0.5px), radial-gradient(#c3a473 0.5px, #fcf9f2 0.5px);
      background-size: 20px 20px;
      background-position: 0 0, 10px 10px;
      opacity: 0.04;
    }

    /* Glassmorphism Card mewah dengan border tipis keemasan */
    .glass-card {
      background: rgba(255, 255, 255, 0.85);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border: 1px solid rgba(195, 164, 115, 0.25);
    }

    /* Efek Hover Tombol Emas Premium */
    .btn-gold {
      background: linear-gradient(135deg, #c3a473 0%, #a4814d 100%);
      box-shadow: 0 4px 15px rgba(164, 129, 77, 0.2);
      transition: all 0.4s cubic-bezier(0.16, 1, 0.3, 1);
    }
    .btn-gold:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(164, 129, 77, 0.4);
    }

    /* Animasi Daun Gugur untuk Vibe Kalem */
    @keyframes leaf-fall {
      0% { transform: translateY(-5%) rotate(0deg); opacity: 0; }
      10% { opacity: 0.6; }
      90% { opacity: 0.6; }
      100% { transform: translateY(105vh) rotate(360deg); opacity: 0; }
    }
    .leaf-element {
      position: absolute;
      color: #c3a473;
      opacity: 0;
      pointer-events: none;
      z-index: 1;
      animation: leaf-fall 12s linear infinite;
    }
  </style>
</head>
<body class="relative overflow-x-hidden min-h-screen selection:bg-[#c3a473] selection:text-white">

  <!-- Audio Gending Jawa Modern/Lembut -->
  <audio id="bg-music" loop>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-8.mp3" type="audio/mpeg">
  </audio>

  <!-- SCREEN SAVER / COVER UTAMA -->
  <div id="cover-screen" class="fixed inset-0 z-50 flex flex-col items-center justify-between py-12 px-6 bg-[#f7f2e5] transition-all duration-1000 ease-out">
    <div class="absolute inset-0 bg-batik pointer-events-none"></div>
    
    <!-- Animasi Daun Melayang Khusus Cover -->
    <div class="absolute inset-0 overflow-hidden pointer-events-none">
      <span class="leaf-element text-sm" style="left: 10%; animation-delay: 0s;">✿</span>
      <span class="leaf-element text-xs" style="left: 30%; animation-delay: 4s;">❀</span>
      <span class="leaf-element text-sm" style="left: 70%; animation-delay: 2s;">✿</span>
      <span class="leaf-element text-xs" style="left: 85%; animation-delay: 6s;">❀</span>
    </div>

    <!-- Ornament Atas: Gunungan Wayang Mas -->
    <div class="relative z-10 flex justify-center w-full max-w-xs animate__animated animate__fadeInDown">
      <svg class="w-16 h-16 text-[#c3a473]" viewBox="0 0 100 100" fill="currentColor">
        <path d="M50 5 L90 75 C90 75, 75 90, 50 90 C25 90, 10 75, 10 75 L50 5 Z M50 15 L22 68 C28 72, 38 75, 50 75 C62 75, 72 72, 78 68 L50 15 Z" />
        <path d="M50 35 L50 85 M40 50 L60 50 M43 65 L57 65" stroke="currentColor" stroke-width="2" />
      </svg>
    </div>

    <!-- Teks Utama Undangan -->
    <div class="text-center relative z-10 my-auto animate__animated animate__fadeInUp">
      <p class="font-header text-[#a4814d] tracking-[0.25em] text-[11px] uppercase mb-2">Serat Ulem</p>
      <p class="font-serif-elegant italic text-[#544330] text-sm mb-4">Pernikahan Suci</p>
      
      <h1 class="font-accent text-6xl md:text-7xl text-[#8b6531] my-4 leading-tight">Sekar & Danu</h1>
      
      <div class="w-24 h-[1px] bg-[#c3a473] mx-auto my-6 relative">
        <span class="absolute -top-1.5 left-1/2 -translate-x-1/2 text-[10px] text-[#c3a473]">✦</span>
      </div>

      <!-- Kotak Nama Tamu Kustom -->
      <div class="mt-4 mb-8">
        <p class="text-[10px] uppercase tracking-[0.15em] text-[#8c7b68] mb-2">Katur dumateng panjenengan:</p>
        <div class="inline-block px-8 py-3 bg-[#ffffffa0] border border-[#c3a473]/30 rounded-xl shadow-sm">
          <p id="guest-name" class="font-serif-elegant font-semibold text-xl text-[#544330]">Bapak/Ibu/Saudara/i</p>
        </div>
        <p class="text-[10px] text-[#8c7b68] italic mt-2">Sutono</p>
      </div>

      <!-- Tombol Interaktif Buka Undangan -->
      <button onclick="openInvitation()" class="btn-gold px-8 py-4 rounded-full text-white font-medium text-xs tracking-widest uppercase transition-all flex items-center gap-3 mx-auto">
        <i class="fa-solid fa-envelope-open animate-pulse"></i>
        Buka Serat Ulem
      </button>
    </div>

    <!-- Footnote Cover -->
    <div class="relative z-10 text-center max-w-sm animate__animated animate__fadeInUp">
      <p class="font-serif-elegant italic text-xs text-[#8c7b68] leading-relaxed">Tanpa mengurangi rasa hormat, kami mengundang Anda untuk menyaksikan momen sakral bersatunya kasih suci kami.</p>
    </div>
  </div>


  <!-- ISI UTAMA UNDANGAN -->
  <div id="main-content" class="hidden opacity-0 transition-opacity duration-1000 pb-20">
    
    <!-- Floating Music Controller Button -->
    <button id="music-btn" onclick="toggleMusic()" class="fixed bottom-6 right-6 z-40 w-12 h-12 rounded-full bg-[#c3a473] text-white flex items-center justify-center shadow-lg hover:bg-[#a4814d] transition-colors focus:outline-none">
      <i id="music-icon" class="fa-solid fa-volume-high"></i>
    </button>

    <!-- SECTION 1: BANNER UTAMA -->
    <header class="relative min-h-screen flex flex-col justify-center items-center px-4 text-center overflow-hidden">
      <div class="absolute inset-0 bg-batik pointer-events-none"></div>
      
      <!-- Ornamen Pojok Floral Tradisional -->
      <div class="absolute top-0 inset-x-0 h-32 opacity-20 flex justify-between px-6 md:px-16 pointer-events-none">
        <span class="text-7xl text-[#c3a473] rotate-45">✿</span>
        <span class="text-7xl text-[#c3a473] -rotate-45">✿</span>
      </div>

      <!-- Watermark Gunungan Latar Belakang -->
      <div class="absolute inset-0 flex items-center justify-center opacity-[0.02] pointer-events-none">
        <svg class="w-[85vw] h-[85vw] max-w-3xl text-[#a4814d]" viewBox="0 0 100 100" fill="currentColor">
          <path d="M50 5 L90 75 C90 75, 75 90, 50 90 C25 90, 10 75, 10 75 L50 5 Z" />
        </svg>
      </div>

      <div class="relative z-10 space-y-6 max-w-2xl px-4 animate__animated animate__fadeIn">
        <p class="font-header text-[10px] tracking-[0.3em] text-[#a4814d] uppercase font-semibold">Miwiti Bebrayan Agung</p>
        
        <h2 class="font-accent text-7xl md:text-8xl text-[#8b6531] mt-2 mb-4">Sekar & Danu</h2>
        
        <!-- Tanggal Pernikahan -->
        <p class="font-serif-elegant tracking-[0.2em] text-sm md:text-base text-[#544330] font-semibold border-y border-[#c3a473]/30 py-3 inline-block px-10">
          SABTU, 12 DESEMBER 2026
        </p>

        <!-- Puisi / Kutipan Bahasa Jawa Indah -->
        <div class="mt-8 px-4 max-w-lg mx-auto">
          <p class="font-serif-elegant italic text-sm md:text-base text-[#544330] leading-relaxed">
            "Saking kersaning Gusti Ingkang Maha Kawasa, raras roso nyawijiaken salira dumateng ikatan suci, rukun bagya mulya ing salawasna."
          </p>
          <div class="w-12 h-[1px] bg-[#c3a473]/50 mx-auto my-4"></div>
          <p class="text-[10px] text-[#a4814d] uppercase tracking-[0.2em] font-semibold">
            — Serat Pepatah Jawa —
          </p>
        </div>
      </div>

      <!-- Indikator Gulir ke Bawah -->
      <div class="absolute bottom-10 left-1/2 -translate-x-1/2 text-center animate-bounce">
        <span class="text-[9px] uppercase tracking-[0.2em] text-[#a4814d] block mb-2">Gulir Mengandhap</span>
        <i class="fa-solid fa-chevron-down text-[#c3a473] text-sm"></i>
      </div>
    </header>


    <!-- SECTION 2: KALIMAT MUTIARA AL-QURAN -->
    <section class="py-20 px-6 bg-[#f7f2e5] relative text-center">
      <div class="max-w-3xl mx-auto glass-card p-10 md:p-14 rounded-3xl shadow-sm">
        <div class="text-[#c3a473] text-3xl mb-4">✦</div>
        <p class="font-serif-elegant italic text-gray-700 text-sm md:text-base leading-relaxed mb-8">
          "Dan di antara tanda-tanda (kebesaran)-Nya ialah Dia menciptakan pasangan-pasangan untukmu dari jenismu sendiri, agar kamu cenderung dan merasa tenteram kepadanya, dan Dia menjadikan di antaramu rasa kasih dan sayang. Sungguh, pada yang demikian itu benar-benar terdapat tanda-tanda bagi kaum yang berpikir."
        </p>
        <span class="font-header text-xs text-[#a4814d] tracking-[0.15em] font-bold">— Q.S. Ar-Rum: 21 —</span>
      </div>
    </section>


    <!-- SECTION 3: PROFIL KEDUA MEMPELAI -->
    <section class="py-24 px-6 max-w-6xl mx-auto">
      <div class="text-center mb-16">
        <span class="font-header text-xs tracking-[0.2em] text-[#a4814d] uppercase block mb-2">Kaping Kalih Mempelai</span>
        <h2 class="font-serif-elegant text-3xl md:text-4xl text-[#544330] font-bold">Mempelai Kekalih</h2>
        <div class="w-16 h-[2px] bg-[#c3a473] mx-auto mt-4"></div>
      </div>

      <!-- Grid Mempelai -->
      <div class="grid md:grid-cols-2 gap-16 items-start">
        
        <!-- Mempelai Wanita -->
        <div class="flex flex-col items-center text-center space-y-5">
          <!-- Frame Foto Lingkaran Indah -->
          <div class="relative w-48 h-48 md:w-56 md:h-56 rounded-full p-2.5 border-2 border-[#c3a473] bg-white shadow-xl">
            <div class="w-full h-full rounded-full overflow-hidden bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&q=80&w=500');">
              <!-- fallback background color if image fails -->
              <div class="w-full h-full bg-[#f1ebd9]"></div>
            </div>
            <div class="absolute -bottom-2 -right-2 bg-[#fcf9f2] p-2 rounded-full border border-[#c3a473] shadow-sm">
              <span class="text-sm text-[#a4814d]">✿</span>
            </div>
          </div>
          
          <h3 class="font-serif-elegant text-2xl font-bold text-[#544330] mt-3">Sekar Ayu Wandini, S.Pd.</h3>
          <p class="font-accent text-3xl text-[#a4814d]">Sekar</p>
          
          <div class="text-xs text-gray-600 space-y-1 mt-2">
            <p class="font-semibold text-gray-800">Putri Sulung dari:</p>
            <p>Bapak H. Wijaya Kusuma</p>
            <p>dan Ibu Hj. Ratih Wahyuni</p>
            <p class="text-[11px] italic text-[#a4814d] mt-2"><i class="fa-solid fa-location-dot mr-1"></i> Sleman, D.I. Yogyakarta</p>
          </div>
          
          <a href="#" class="inline-flex items-center gap-2 text-xs text-[#a4814d] hover:text-[#8b6531] transition-colors mt-3">
            <i class="fa-brands fa-instagram text-sm"></i> @sekar_ayu
          </a>
        </div>

        <!-- Mempelai Pria -->
        <div class="flex flex-col items-center text-center space-y-5">
          <!-- Frame Foto Lingkaran Indah -->
          <div class="relative w-48 h-48 md:w-56 md:h-56 rounded-full p-2.5 border-2 border-[#c3a473] bg-white shadow-xl">
            <div class="w-full h-full rounded-full overflow-hidden bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&q=80&w=500');">
              <div class="w-full h-full bg-[#f1ebd9]"></div>
            </div>
            <div class="absolute -bottom-2 -left-2 bg-[#fcf9f2] p-2 rounded-full border border-[#c3a473] shadow-sm">
              <span class="text-sm text-[#a4814d]">✿</span>
            </div>
          </div>
          
          <h3 class="font-serif-elegant text-2xl font-bold text-[#544330] mt-3">Danu Hartawan, S.T.</h3>
          <p class="font-accent text-3xl text-[#a4814d]">Danu</p>
          
          <div class="text-xs text-gray-600 space-y-1 mt-2">
            <p class="font-semibold text-gray-800">Putra Bungsu dari:</p>
            <p>Bapak Ir. Handoyo</p>
            <p>dan Ibu Endang Setiowati</p>
            <p class="text-[11px] italic text-[#a4814d] mt-2"><i class="fa-solid fa-location-dot mr-1"></i> Surakarta, Jawa Tengah</p>
          </div>

          <a href="#" class="inline-flex items-center gap-2 text-xs text-[#a4814d] hover:text-[#8b6531] transition-colors mt-3">
            <i class="fa-brands fa-instagram text-sm"></i> @danuhart_
          </a>
        </div>

      </div>
    </section>


    <!-- SECTION 4: COUNTDOWN TIMER -->
    <section class="py-20 px-6 bg-[#f7f2e5] relative">
      <div class="max-w-4xl mx-auto text-center">
        <span class="font-header text-xs tracking-[0.2em] text-[#a4814d] uppercase block mb-3">Sasi & Dinten</span>
        <h3 class="font-serif-elegant text-2xl md:text-3xl text-[#544330] mb-8">Menghitung Hari Bahagia</h3>
        
        <!-- Grid Kotak Countdown Premium -->
        <div class="grid grid-cols-4 gap-4 max-w-lg mx-auto mb-10">
          <div class="bg-white p-4 rounded-2xl border border-[#c3a473]/30 shadow-sm">
            <span id="days" class="font-serif-elegant text-3xl md:text-4xl font-bold text-[#8b6531]">00</span>
            <p class="text-[10px] uppercase tracking-wider text-gray-500 mt-1">Hari</p>
          </div>
          <div class="bg-white p-4 rounded-2xl border border-[#c3a473]/30 shadow-sm">
            <span id="hours" class="font-serif-elegant text-3xl md:text-4xl font-bold text-[#8b6531]">00</span>
            <p class="text-[10px] uppercase tracking-wider text-gray-500 mt-1">Jam</p>
          </div>
          <div class="bg-white p-4 rounded-2xl border border-[#c3a473]/30 shadow-sm">
            <span id="minutes" class="font-serif-elegant text-3xl md:text-4xl font-bold text-[#8b6531]">00</span>
            <p class="text-[10px] uppercase tracking-wider text-gray-500 mt-1">Menit</p>
          </div>
          <div class="bg-white p-4 rounded-2xl border border-[#c3a473]/30 shadow-sm">
            <span id="seconds" class="font-serif-elegant text-3xl md:text-4xl font-bold text-[#8b6531]">00</span>
            <p class="text-[10px] uppercase tracking-wider text-gray-500 mt-1">Detik</p>
          </div>
        </div>

        <!-- Tombol Tambahkan ke Google Calendar -->
        <button onclick="addToCalendar()" class="inline-flex items-center gap-3 px-6 py-3 rounded-full border border-[#c3a473] hover:bg-[#c3a473] hover:text-white transition-all text-xs font-semibold tracking-wider uppercase text-[#a4814d]">
          <i class="fa-regular fa-calendar-check text-sm"></i> Simpan Tanggal ke Google Calendar
        </button>
      </div>
    </section>


    <!-- SECTION 5: DETIL ACARA (AKAD & RESEPSI) -->
    <section class="py-24 px-6 max-w-5xl mx-auto">
      <div class="text-center mb-16">
        <span class="font-header text-xs tracking-[0.2em] text-[#a4814d] uppercase block mb-2">Serat Pahargyan</span>
        <h2 class="font-serif-elegant text-3xl md:text-4xl text-[#544330] font-bold">Waktu & Lokasi Acara</h2>
        <div class="w-16 h-[2px] bg-[#c3a473] mx-auto mt-4"></div>
      </div>

      <div class="grid md:grid-cols-2 gap-8 items-stretch">
        
        <!-- CARD: Akad Nikah -->
        <div class="glass-card p-8 rounded-3xl flex flex-col justify-between border border-[#c3a473]/30 relative overflow-hidden group hover:shadow-lg transition-shadow">
          <div class="absolute -top-6 -right-6 text-7xl text-[#c3a473]/10 pointer-events-none group-hover:scale-110 transition-transform">✿</div>
          
          <div class="space-y-6">
            <div class="flex items-center gap-4">
              <div class="w-12 h-12 rounded-full bg-[#f1ebd9] flex items-center justify-center text-[#8b6531]">
                <i class="fa-solid fa-square-poll-vertical text-xl"></i>
              </div>
              <div>
                <h3 class="font-serif-elegant text-xl font-bold text-[#544330]">Akad Nikah</h3>
                <p class="text-[10px] text-[#a4814d] uppercase tracking-widest font-semibold">Ijab Qobul</p>
              </div>
            </div>

            <div class="h-[1px] bg-[#c3a473]/20 w-full"></div>

            <div class="space-y-4 text-xs md:text-sm text-gray-600">
              <div class="flex items-start gap-3">
                <i class="fa-solid fa-calendar text-[#c3a473] mt-1 text-sm"></i>
                <div>
                  <p class="font-semibold text-gray-800 text-sm">Sabtu, 12 Desember 2026</p>
                  <p class="text-[11px] text-[#8c7b68] italic">Sasi Bakda Mulud - Taun Jawi</p>
                </div>
              </div>

              <div class="flex items-start gap-3">
                <i class="fa-solid fa-clock text-[#c3a473] mt-1 text-sm"></i>
                <div>
                  <p class="font-semibold text-gray-800 text-sm">Pukul 08.00 - 10.00 WIB</p>
                </div>
              </div>

              <div class="flex items-start gap-3">
                <i class="fa-solid fa-location-dot text-[#c3a473] mt-1 text-sm"></i>
                <div>
                  <p class="font-semibold text-gray-800 text-sm">Masjid Agung Syuhada</p>
                  <p class="text-[11px] leading-relaxed mt-0.5">Jl. Dewa Nyoman Oka No.13, Kotabaru, Kec. Gondokusuman, Kota Yogyakarta</p>
                </div>
              </div>
            </div>
          </div>

          <div class="mt-8 pt-4">
            <a href="https://maps.app.goo.gl/9ZpZJb9oG3aR" target="_blank" class="w-full text-center inline-block btn-gold text-white text-xs font-semibold uppercase tracking-wider py-3.5 rounded-xl shadow-sm">
              <i class="fa-solid fa-map-location-dot mr-2"></i> Peta Lokasi Akad
            </a>
          </div>
        </div>

        <!-- CARD: Resepsi Pernikahan -->
        <div class="glass-card p-8 rounded-3xl flex flex-col justify-between border border-[#c3a473]/30 relative overflow-hidden group hover:shadow-lg transition-shadow">
          <div class="absolute -top-6 -right-6 text-7xl text-[#c3a473]/10 pointer-events-none group-hover:scale-110 transition-transform">✿</div>
          
          <div class="space-y-6">
            <div class="flex items-center gap-4">
              <div class="w-12 h-12 rounded-full bg-[#f1ebd9] flex items-center justify-center text-[#8b6531]">
                <i class="fa-solid fa-wine-glass text-xl"></i>
              </div>
              <div>
                <h3 class="font-serif-elegant text-xl font-bold text-[#544330]">Pahargyan / Resepsi</h3>
                <p class="text-[10px] text-[#a4814d] uppercase tracking-widest font-semibold">Pesta Pernikahan</p>
              </div>
            </div>

            <div class="h-[1px] bg-[#c3a473]/20 w-full"></div>

            <div class="space-y-4 text-xs md:text-sm text-gray-600">
              <div class="flex items-start gap-3">
                <i class="fa-solid fa-calendar text-[#c3a473] mt-1 text-sm"></i>
                <div>
                  <p class="font-semibold text-gray-800 text-sm">Sabtu, 12 Desember 2026</p>
                  <p class="text-[11px] text-[#8c7b68] italic">Sasi Bakda Mulud - Taun Jawi</p>
                </div>
              </div>

              <div class="flex items-start gap-3">
                <i class="fa-solid fa-clock text-[#c3a473] mt-1 text-sm"></i>
                <div>
                  <p class="font-semibold text-gray-800 text-sm">Pukul 11.30 - 14.00 WIB</p>
                </div>
              </div>

              <div class="flex items-start gap-3">
                <i class="fa-solid fa-location-dot text-[#c3a473] mt-1 text-sm"></i>
                <div>
                  <p class="font-semibold text-gray-800 text-sm">Ndalem Ngabean Resto & Heritage</p>
                  <p class="text-[11px] leading-relaxed mt-0.5">Ndalem Ngabean, Kraton, Kec. Kraton, Kota Yogyakarta</p>
                </div>
              </div>
            </div>
          </div>

          <div class="mt-8 pt-4">
            <a href="https://maps.app.goo.gl/9ZpZJb9oG3aR" target="_blank" class="w-full text-center inline-block btn-gold text-white text-xs font-semibold uppercase tracking-wider py-3.5 rounded-xl shadow-sm">
              <i class="fa-solid fa-map-location-dot mr-2"></i> Peta Lokasi Resepsi
            </a>
          </div>
        </div>

      </div>
    </section>


    <!-- SECTION 6: GALERI FOTO INTERAKTIF -->
    <section class="py-20 px-6 bg-[#f7f2e5]">
      <div class="max-w-5xl mx-auto">
        <div class="text-center mb-16">
          <span class="font-header text-xs tracking-[0.2em] text-[#a4814d] uppercase block mb-2">Dokumentasi</span>
          <h2 class="font-serif-elegant text-3xl md:text-4xl text-[#544330] font-bold">Galeri Foto Kebersamaan</h2>
          <div class="w-16 h-[2px] bg-[#c3a473] mx-auto mt-4"></div>
        </div>

        <!-- Grid Galeri Foto -->
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
          <div class="overflow-hidden rounded-2xl cursor-pointer shadow-sm group border border-white" onclick="openLightbox('https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&q=80&w=800')">
            <img src="https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&q=80&w=300" alt="Prewedding 1" class="w-full h-48 md:h-64 object-cover group-hover:scale-105 transition-transform duration-500">
          </div>
          <div class="overflow-hidden rounded-2xl cursor-pointer shadow-sm group border border-white" onclick="openLightbox('https://images.unsplash.com/photo-1583939003579-730e3918a45a?auto=format&fit=crop&q=80&w=800')">
            <img src="https://images.unsplash.com/photo-1583939003579-730e3918a45a?auto=format&fit=crop&q=80&w=300" alt="Prewedding 2" class="w-full h-48 md:h-64 object-cover group-hover:scale-105 transition-transform duration-500">
          </div>
          <div class="overflow-hidden rounded-2xl cursor-pointer shadow-sm group border border-white" onclick="openLightbox('https://images.unsplash.com/photo-1606800052052-a08af7148866?auto=format&fit=crop&q=80&w=800')">
            <img src="https://images.unsplash.com/photo-1606800052052-a08af7148866?auto=format&fit=crop&q=80&w=300" alt="Prewedding 3" class="w-full h-48 md:h-64 object-cover group-hover:scale-105 transition-transform duration-500">
          </div>
          <div class="overflow-hidden rounded-2xl cursor-pointer shadow-sm group border border-white" onclick="openLightbox('https://images.unsplash.com/photo-1511285560929-80b456fea0bc?auto=format&fit=crop&q=80&w=800')">
            <img src="https://images.unsplash.com/photo-1511285560929-80b456fea0bc?auto=format&fit=crop&q=80&w=300" alt="Prewedding 4" class="w-full h-48 md:h-64 object-cover group-hover:scale-105 transition-transform duration-500">
          </div>
        </div>
      </div>
    </section>

    <!-- Lightbox Modal untuk Zoom Galeri Foto -->
    <div id="lightbox" class="fixed inset-0 z-50 hidden bg-black/90 flex items-center justify-center p-4" onclick="closeLightbox()">
      <button class="absolute top-6 right-6 text-white text-2xl"><i class="fa-solid fa-xmark"></i></button>
      <img id="lightbox-img" src="" alt="Zoomed View" class="max-w-full max-h-[85vh] rounded-xl object-contain shadow-2xl">
    </div>


    <!-- SECTION 7: KADO DIGITAL (E-GIFT) -->
    <section class="py-24 px-6 max-w-4xl mx-auto text-center">
      <div class="mb-10">
        <span class="font-header text-xs tracking-[0.2em] text-[#a4814d] uppercase block mb-2">Tandha Tresna</span>
        <h2 class="font-serif-elegant text-3xl text-[#544330] font-bold">Kado Digital / Kado Online</h2>
        <div class="w-16 h-[2px] bg-[#c3a473] mx-auto mt-4 mb-6"></div>
        <p class="text-xs text-gray-600 max-w-lg mx-auto leading-relaxed">
          Kagem bapak/ibu ingkang kerso maringi kado dhumateng mempelai, saged dipun kirim lumantar jalur digital wonten ing ngandhap menika:
        </p>
      </div>

      <!-- Kartu Bank -->
      <div class="grid md:grid-cols-2 gap-8 max-w-2xl mx-auto">
        <!-- Kartu Rekening 1 -->
        <div class="glass-card p-6 rounded-2xl border border-[#c3a473]/30 shadow-sm text-left relative overflow-hidden">
          <div class="flex justify-between items-center mb-4">
            <span class="font-bold text-lg text-[#0f5ca8] tracking-wider">BANK BCA</span>
            <i class="fa-solid fa-credit-card text-[#c3a473] text-xl"></i>
          </div>
          <p class="text-[10px] text-gray-500 uppercase tracking-wider mb-1">Nomor Rekening</p>
          <p class="text-xl font-bold font-serif-elegant text-[#544330] mb-3 tracking-wide" id="no-rek-1">1234 5678 90</p>
          <p class="text-xs text-gray-600 mb-4 font-semibold">a.n Sekar Ayu Wandini</p>
          
          <button onclick="copyToClipboard('no-rek-1', 'btn-copy-1')" id="btn-copy-1" class="text-xs text-[#a4814d] hover:text-[#8b6531] border border-[#c3a473]/40 px-4 py-2 rounded-full inline-flex items-center gap-2 bg-white transition-all font-medium">
            <i class="fa-regular fa-copy"></i> Salin Nomor Rekening
          </button>
        </div>

        <!-- Kartu Rekening 2 -->
        <div class="glass-card p-6 rounded-2xl border border-[#c3a473]/30 shadow-sm text-left relative overflow-hidden">
          <div class="flex justify-between items-center mb-4">
            <span class="font-bold text-lg text-[#00a350] tracking-wider">BANK MANDIRI</span>
            <i class="fa-solid fa-credit-card text-[#c3a473] text-xl"></i>
          </div>
          <p class="text-[10px] text-gray-500 uppercase tracking-wider mb-1">Nomor Rekening</p>
          <p class="text-xl font-bold font-serif-elegant text-[#544330] mb-3 tracking-wide" id="no-rek-2">9876 5432 1098</p>
          <p class="text-xs text-gray-600 mb-4 font-semibold">a.n Danu Hartawan</p>
          
          <button onclick="copyToClipboard('no-rek-2', 'btn-copy-2')" id="btn-copy-2" class="text-xs text-[#a4814d] hover:text-[#8b6531] border border-[#c3a473]/40 px-4 py-2 rounded-full inline-flex items-center gap-2 bg-white transition-all font-medium">
            <i class="fa-regular fa-copy"></i> Salin Nomor Rekening
          </button>
        </div>
      </div>

      <!-- Toast Notifikasi Ringan (Custom Pop-up Pengganti Alert) -->
      <div id="toast" class="fixed bottom-24 left-1/2 -translate-x-1/2 bg-[#544330] text-[#fcf9f2] text-xs px-6 py-3.5 rounded-full shadow-lg opacity-0 pointer-events-none transition-all duration-300 z-50 flex items-center gap-2">
        <i class="fa-solid fa-circle-check text-[#c3a473] text-sm"></i>
        <span>Nomor rekening berhasil disalin!</span>
      </div>
    </section>


    <!-- SECTION 8: RSVP & BUKU TAMU (UCAPAN DOA) -->
    <section class="py-24 px-6 bg-[#f7f2e5] relative">
      <div class="max-w-4xl mx-auto">
        <div class="text-center mb-12">
          <span class="font-header text-xs tracking-[0.2em] text-[#a4814d] uppercase block mb-2">Buku Tamu</span>
          <h2 class="font-serif-elegant text-3xl text-[#544330] font-bold">Kirim Ucapan Doa Restu</h2>
          <div class="w-16 h-[2px] bg-[#c3a473] mx-auto mt-4"></div>
        </div>

        <div class="grid md:grid-cols-5 gap-8 items-start">
          
          <!-- Formulir RSVP -->
          <div class="md:col-span-2 glass-card p-6 rounded-2xl border border-[#c3a473]/30">
            <h3 class="font-serif-elegant font-semibold text-lg text-[#544330] mb-4">Konfirmasi Kehadiran</h3>
            
            <form id="rsvp-form" onsubmit="submitWish(event)" class="space-y-4">
              <div>
                <label class="block text-[10px] uppercase tracking-wider text-gray-600 mb-1 font-semibold">Nama Tamu</label>
                <input type="text" id="wish-name" required class="w-full text-xs px-3 py-2.5 rounded-lg border border-[#c3a473]/40 focus:ring-1 focus:ring-[#c3a473] focus:border-[#c3a473] outline-none bg-white/50" placeholder="Ketik nama Anda...">
              </div>

              <div>
                <label class="block text-[10px] uppercase tracking-wider text-gray-600 mb-1 font-semibold">Konfirmasi Kehadiran</label>
                <select id="wish-attendance" required class="w-full text-xs px-3 py-2.5 rounded-lg border border-[#c3a473]/40 focus:ring-1 focus:ring-[#c3a473] focus:border-[#c3a473] outline-none bg-white/50">
                  <option value="Hadir">InsyaAllah Hadir</option>
                  <option value="Ragu-ragu">Masih Ragu-ragu</option>
                  <option value="Tidak Hadir">Sangat Menyesal, Tidak Bisa Hadir</option>
                </select>
              </div>

              <div>
                <label class="block text-[10px] uppercase tracking-wider text-gray-600 mb-1 font-semibold">Doa Restu / Ucapan</label>
                <textarea id="wish-message" rows="4" required class="w-full text-xs px-3 py-2.5 rounded-lg border border-[#c3a473]/40 focus:ring-1 focus:ring-[#c3a473] focus:border-[#c3a473] outline-none bg-white/50" placeholder="Tulis doa tulus Anda..."></textarea>
              </div>

              <button type="submit" class="w-full btn-gold text-white text-xs font-semibold uppercase tracking-wider py-3.5 rounded-lg shadow-sm">
                Kirim Ucapan Doa Restu
              </button>
            </form>
          </div>

          <!-- Tampilan Doa dari Para Tamu -->
          <div class="md:col-span-3 space-y-4">
            <h3 class="font-serif-elegant font-semibold text-lg text-[#544330] mb-4">
              Doa Saking Para Rawuh (<span id="wish-count">0</span>)
            </h3>
            
            <!-- List Scroll Container -->
            <div id="wishes-list" class="max-h-[360px] overflow-y-auto space-y-3 pr-2">
              <!-- Wishes items will be populated here dynamically -->
              <div class="text-center py-8 text-gray-400 text-xs">Sedang memuat doa restu...</div>
            </div>
          </div>

        </div>
      </div>
    </section>


    <!-- FOOTER & CLOSING NOTE -->
    <footer class="py-20 px-6 text-center relative border-t border-[#c3a473]/20">
      <div class="absolute inset-0 bg-batik pointer-events-none"></div>

      <!-- Ornament Gunungan sebagai Penutup -->
      <div class="mb-6">
        <svg class="w-12 h-12 text-[#c3a473] mx-auto opacity-70" viewBox="0 0 100 100" fill="currentColor">
          <path d="M50 5 L90 75 C90 75, 75 90, 50 90 C25 90, 10 75, 10 75 L50 5 Z M50 15 L22 68 C28 72, 38 75, 50 75 C62 75, 72 72, 78 68 L50 15 Z" />
        </svg>
      </div>

      <p class="font-serif-elegant italic text-sm text-gray-600 max-w-xl mx-auto mb-8 leading-relaxed">
        Merupakan suatu kehormatan dan kebahagiaan bagi kami sekeluarga, apabila Bapak/Ibu/Saudara/i berkenan hadir dan memberikan doa restu kepada kedua mempelai.
      </p>

      <p class="text-[10px] uppercase tracking-widest text-[#a4814d] mb-1 font-semibold">Matur Nuwun</p>
      <p class="font-serif-elegant text-xs text-[#544330] mb-8">Kami yang berbahagia,</p>
      
      <p class="font-accent text-5xl text-[#8b6531] mb-2">Sekar & Danu</p>
      <p class="text-xs text-gray-500">Beserta Keluarga Besar Kedua Mempelai</p>

      <div class="mt-20 pt-8 border-t border-gray-200 text-[10px] text-gray-400 tracking-wider">
        <p>© 2026 SEKAR & DANU WEDDING. ALL RIGHTS RESERVED.</p>
        <p class="mt-1">Elegant Traditional Javanese Template.</p>
      </div>
    </footer>

  </div>


  <!-- LOGIKA INTERAKTIF (JAVASCRIPT) -->
  <script>
    // Ambil parameter nama tamu kustom dari URL (contoh: ?to=Bapak+Joko)
    window.addEventListener('DOMContentLoaded', () => {
      const urlParams = new URLSearchParams(window.location.search);
      const guest = urlParams.get('to');
      if (guest) {
        document.getElementById('guest-name').innerText = guest;
      }
      
      // Load data ucapan pertama kali
      loadWishes();
      
      // Jalankan hitung mundur
      startCountdown();
    });

    // Kontrol Musik Latar Belakang & Buka Undangan
    const music = document.getElementById('bg-music');
    const musicBtn = document.getElementById('music-btn');
    const musicIcon = document.getElementById('music-icon');
    let isPlaying = false;

    function openInvitation() {
      // 1. Putar Musik
      playMusic();
      
      // 2. Transisi Sembunyikan Cover
      const cover = document.getElementById('cover-screen');
      cover.classList.add('animate__animated', 'animate__fadeOutUp');
      
      setTimeout(() => {
        cover.style.display = 'none';
        
        // 3. Tampilkan Konten Utama
        const main = document.getElementById('main-content');
        main.classList.remove('hidden');
        setTimeout(() => {
          main.classList.add('opacity-100');
        }, 50);
      }, 1000);
    }

    function playMusic() {
      music.play().then(() => {
        isPlaying = true;
        musicIcon.className = "fa-solid fa-volume-high animate-spin-slow";
      }).catch(err => {
        console.log("Autoplay ditolak browser. User harus menekan tombol musik manual.", err);
      });
    }

    function toggleMusic() {
      if (isPlaying) {
        music.pause();
        isPlaying = false;
        musicIcon.className = "fa-solid fa-volume-xmark";
        musicIcon.classList.remove('animate-spin-slow');
      } else {
        music.play();
        isPlaying = true;
        musicIcon.className = "fa-solid fa-volume-high animate-spin-slow";
      }
    }

    // Logika Hitung Mundur Acara (Target 12 Desember 2026)
    function startCountdown() {
      const targetDate = new Date("Dec 12, 2026 08:00:00").getTime();
      
      const interval = setInterval(() => {
        const now = new Date().getTime();
        const distance = targetDate - now;

        const days = Math.floor(distance / (1000 * 60 * 60 * 24));
        const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
        const seconds = Math.floor((distance % (1000 * 60)) / 1000);

        document.getElementById("days").innerText = String(days).padStart(2, '0');
        document.getElementById("hours").innerText = String(hours).padStart(2, '0');
        document.getElementById("minutes").innerText = String(minutes).padStart(2, '0');
        document.getElementById("seconds").innerText = String(seconds).padStart(2, '0');

        if (distance < 0) {
          clearInterval(interval);
          document.getElementById("days").innerText = "00";
          document.getElementById("hours").innerText = "00";
          document.getElementById("minutes").innerText = "00";
          document.getElementById("seconds").innerText = "00";
        }
      }, 1000);
    }

    // Integrasi Link Google Calendar
    function addToCalendar() {
      const title = "Pernikahan Sekar & Danu";
      const details = "Acara pernikahan Sekar & Danu. Akad: 08.00 WIB, Resepsi: 11.30 WIB.";
      const location = "Masjid Agung Syuhada & Ndalem Ngabean Yogyakarta";
      const dates = "20261212T010000Z/20261212T070000Z"; // Format UTC
      
      const gCalUrl = `https://calendar.google.com/calendar/render?action=TEMPLATE&text=${encodeURIComponent(title)}&dates=${dates}&details=${encodeURIComponent(details)}&location=${encodeURIComponent(location)}`;
      window.open(gCalUrl, '_blank');
    }

    // Zoom Galeri Foto (Lightbox)
    function openLightbox(imgSrc) {
      const lightbox = document.getElementById('lightbox');
      const lightboxImg = document.getElementById('lightbox-img');
      lightboxImg.src = imgSrc;
      lightbox.classList.remove('hidden');
    }

    function closeLightbox() {
      document.getElementById('lightbox').classList.add('hidden');
    }

    // Copy to Clipboard (Fallback demi kompatibilitas browser HP)
    function copyToClipboard(elementId, btnId) {
      const textToCopy = document.getElementById(elementId).innerText.replace(/\s+/g, '');
      
      // Fallback manual input select
      const tempInput = document.createElement("input");
      tempInput.value = textToCopy;
      document.body.appendChild(tempInput);
      tempInput.select();
      document.execCommand("copy");
      document.body.removeChild(tempInput);

      // Tampilkan Toast
      const toast = document.getElementById('toast');
      toast.classList.remove('opacity-0', 'pointer-events-none');
      toast.classList.add('opacity-100');
      
      // Ubah visual tombol sementara waktu
      const originalBtnText = document.getElementById(btnId).innerHTML;
      document.getElementById(btnId).innerHTML = `<i class="fa-solid fa-check"></i> Berhasil Disalin`;
      document.getElementById(btnId).classList.add('bg-emerald-50', 'text-emerald-700', 'border-emerald-300');

      setTimeout(() => {
        toast.classList.remove('opacity-100');
        toast.classList.add('opacity-0', 'pointer-events-none');
        
        document.getElementById(btnId).innerHTML = originalBtnText;
        document.getElementById(btnId).classList.remove('bg-emerald-50', 'text-emerald-700', 'border-emerald-300');
      }, 2500);
    }

    // Simulasi penyimpanan lokal (LocalStorage) untuk RSVP & Ucapan Doa
    const initialWishes = [
      { name: "Setyawan & Keluarga", attendance: "Hadir", message: "Sugeng mengku garwo Sekar lan Danu! Mugi tansah pinaringan berkah saklawase, rukun lan mulyo raras dadi keluwargo sakinah.", date: "10 menit yang lalu" },
      { name: "Siti Rahmawati", attendance: "Hadir", message: "Selamat ya jeng Sekar! Cantik sekali tadi pas akad. Semoga samawa sampai kakek nenek, dapet keturunan sholeh sholehah.", date: "1 jam yang lalu" },
      { name: "Bimo Wicaksono", attendance: "Ragu-ragu", message: "Selamat mas bro Danu! Semoga lancar acaranya dan rukun selalu rumah tangganya.", date: "3 jam yang lalu" }
    ];

    function loadWishes() {
      let wishes = JSON.parse(localStorage.getItem('wedding_wishes'));
      if (!wishes) {
        wishes = initialWishes;
        localStorage.setItem('wedding_wishes', JSON.stringify(wishes));
      }
      renderWishes(wishes);
    }

    function renderWishes(wishes) {
      const wishesList = document.getElementById('wishes-list');
      const wishCount = document.getElementById('wish-count');
      
      wishCount.innerText = wishes.length;
      wishesList.innerHTML = '';

      if (wishes.length === 0) {
        wishesList.innerHTML = `<div class="text-center py-8 text-gray-400 text-xs">Belum ada ucapan. Jadilah yang pertama memberikan doa restu!</div>`;
        return;
      }

      // Menampilkan dari yang terbaru
      wishes.forEach(wish => {
        let badgeColor = "bg-emerald-50 text-emerald-700 border-emerald-200";
        if (wish.attendance === "Ragu-ragu") badgeColor = "bg-amber-50 text-amber-700 border-amber-200";
        if (wish.attendance === "Tidak Hadir") badgeColor = "bg-rose-50 text-rose-700 border-rose-200";

        const wishHtml = `
          <div class="bg-white p-4 rounded-xl shadow-sm border border-gray-100 space-y-2 animate__animated animate__fadeIn">
            <div class="flex justify-between items-start gap-2">
              <div>
                <h4 class="font-bold text-xs text-gray-800">${escapeHTML(wish.name)}</h4>
                <span class="text-[9px] text-gray-400">${wish.date}</span>
              </div>
              <span class="text-[9px] font-semibold border px-2 py-0.5 rounded-full ${badgeColor}">
                ${wish.attendance}
              </span>
            </div>
            <p class="text-xs text-gray-600 leading-relaxed italic">"${escapeHTML(wish.message)}"</p>
          </div>
        `;
        wishesList.insertAdjacentHTML('afterbegin', wishHtml);
      });
    }

    function submitWish(event) {
      event.preventDefault();
      
      const nameInput = document.getElementById('wish-name');
      const attendanceInput = document.getElementById('wish-attendance');
      const messageInput = document.getElementById('wish-message');
      
      const newWish = {
        name: nameInput.value,
        attendance: attendanceInput.value,
        message: messageInput.value,
        date: "Baru saja"
      };

      let wishes = JSON.parse(localStorage.getItem('wedding_wishes')) || [];
      wishes.push(newWish);
      localStorage.setItem('wedding_wishes', JSON.stringify(wishes));
      
      renderWishes(wishes);

      // Reset Form Input
      nameInput.value = '';
      messageInput.value = '';
      
      // Auto-scroll ke bagian atas daftar ucapan
      document.getElementById('wishes-list').scrollTop = 0;
    }

    // Helper sanitasi teks input demi keamanan XSS
    function escapeHTML(str) {
      return str.replace(/[&<>'"]/g, 
        tag => ({
          '&': '&amp;',
          '<': '&lt;',
          '>': '&gt;',
          "'": '&#39;',
          '"': '&quot;'
        }[tag] || tag)
      );
    }
  </script>

  <!-- Spin-slow custom animation helper untuk Musik Tombol -->
  <style>
    @keyframes spin-slow {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
    .animate-spin-slow {
      animation: spin-slow 8s linear infinite;
    }
  </style>

</body>
</html>
