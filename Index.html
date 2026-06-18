```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SĒN — Sensory Wellness Sanctuary</title>
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:ital,wght@0,400;0,600;0,700;1,400&family=Plus+Jakarta+Sans:wght@200;400;600&family=Syne:wght@400;600;800&display=swap" rel="stylesheet">
  
  <!-- Lucide Icons CDN -->
  <script src="https://unpkg.com/lucide@latest"></script>

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            serif: ['Cinzel', 'Georgia', 'serif'],
            sans: ['"Plus Jakarta Sans"', 'sans-serif'],
            syne: ['Syne', 'sans-serif'],
          },
          colors: {
            stone: {
              950: '#0a0a09',
              900: '#141412',
              800: '#1f1e1c',
              700: '#2a2825',
              600: '#3a3834',
              400: '#8c857b',
              200: '#e5e0d8',
            },
            accent: {
              gold: '#d1a170',
              goldHover: '#c29363',
              glow: 'rgba(209, 161, 112, 0.15)',
            }
          }
        }
      }
    }
  </script>

  <style>
    :root {
      --bg-dark: #0a0a09;
      --bg-stone: #141412;
      --text-light: #e5e0d8;
      --text-muted: #8c857b;
      --gold: #d1a170;
      --gold-glow: rgba(209, 161, 112, 0.15);
      --border: #262421;
    }

    body {
      background-color: var(--bg-dark);
      color: var(--text-light);
      font-family: 'Plus Jakarta Sans', sans-serif;
      overflow-x: hidden;
      -webkit-font-smoothing: antialiased;
    }

    /* Custom Scrollbar */
    ::-webkit-scrollbar {
      width: 6px;
    }
    ::-webkit-scrollbar-track {
      background: var(--bg-dark);
    }
    ::-webkit-scrollbar-thumb {
      background: #2a2825;
      border-radius: 3px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: var(--gold);
    }

    /* Custom grain overlay */
    .grain {
      position: fixed;
      top: 0; left: 0; width: 100%; height: 100%;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 250 250' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noiseFilter'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noiseFilter)'/%3E%3C/svg%3E");
      opacity: 0.03;
      pointer-events: none;
      z-index: 9999;
    }

    /* Ambient Lighting Gradation Overlays */
    .light-mesh {
      position: fixed;
      inset: 0;
      pointer-events: none;
      z-index: 0;
      opacity: 0.8;
      transition: background 1.2s cubic-bezier(0.4, 0, 0.2, 1);
    }

    /* Custom styles to prevent layout shifts */
    .glow-bg {
      background: radial-gradient(circle at 50% 30%, var(--gold-glow) 0%, transparent 60%);
    }

    input[type="date"]::-webkit-calendar-picker-indicator {
      filter: invert(0.8) sepia(0.4) saturate(2) hue-rotate(10deg);
    }
  </style>
</head>
<body class="selection:bg-[#d1a170] selection:text-[#0a0a09]">

  <div class="grain"></div>

  <!-- DYNAMIC AMBIENT LIGHTING MESH -->
  <div id="ambientMesh" class="light-mesh" style="background: radial-gradient(circle, rgba(230,175,115,0.15) 0%, rgba(10,10,9,0) 70%);"></div>

  <!-- HEADER BAR -->
  <header class="fixed top-0 w-full z-40 border-b border-[#1f1e1c]/70 bg-[#0a0a09]/90 backdrop-blur-md">
    <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
      <div class="flex items-center gap-3">
        <span class="font-serif text-2xl tracking-[0.3em] text-[#e5e0d8] font-bold">
          SĒN<span class="text-[#d1a170]">.</span>
        </span>
        <span class="hidden sm:inline-block text-[10px] tracking-[0.2em] uppercase px-2 py-0.5 border border-[#2a2825] text-[#8c857b]">
          SENSORY SANCTUARY
        </span>
      </div>

      <div class="flex items-center gap-6">
        <!-- Live Audio Controller Widget -->
        <div class="flex items-center gap-3 px-4 py-2 rounded-full bg-[#141412] border border-[#2a2825]">
          <button 
            id="globalAudioBtn"
            onclick="toggleAudio()" 
            class="flex items-center gap-2 text-xs uppercase tracking-widest transition-all text-[#8c857b] hover:text-[#e5e0d8]"
          >
            <i id="audioIcon" data-lucide="volume-x" class="w-3.5 h-3.5"></i>
            <span class="hidden md:inline" id="audioBtnText">PLAY AUDIO</span>
          </button>
          
          <div id="volumeControlContainer" class="hidden flex items-center">
            <input 
              id="volumeSlider"
              type="range" 
              min="0.1" 
              max="0.9" 
              step="0.05"
              value="0.4"
              oninput="handleVolumeChange(this.value)"
              class="w-16 h-1 bg-[#262421] accent-[#d1a170] cursor-pointer rounded-full ml-1"
            />
          </div>
        </div>

        <button 
          onclick="openBooking('rit-01')"
          class="px-5 py-2.5 bg-[#d1a170] hover:bg-[#c29363] text-[#0a0a09] font-syne font-semibold text-xs tracking-widest uppercase transition-colors rounded-sm"
        >
          BOOK RITUAL
        </button>
      </div>
    </div>
  </header>

  <!-- HERO SECTION -->
  <section class="relative pt-44 pb-20 px-6 max-w-7xl mx-auto z-10 flex flex-col md:flex-row gap-16 items-center">
    <div class="flex-grow space-y-8 md:w-1/2">
      <div class="flex items-center gap-3 text-xs tracking-widest uppercase text-[#d1a170] font-semibold">
        <span class="h-1.5 w-1.5 rounded-full bg-[#d1a170] animate-ping"></span>
        VIBRATIONAL RE-ALIGNMENT FOR HIGH PERFORMANCE
      </div>
      
      <h1 class="font-serif text-5xl sm:text-7xl leading-[1.1] tracking-tight uppercase">
        Pure <span class="text-[#d1a170] italic">Sensory</span> Restoration<span class="text-[#d1a170]">.</span>
      </h1>

      <p class="text-[#8c857b] text-base leading-relaxed max-w-lg">
        SĒN combines physical therapies, custom sound frequencies, and ambient light-states into a single synchronized ritual to reset the human biological rhythm.
      </p>

      <div class="flex flex-col sm:flex-row gap-4 pt-4">
        <a 
          href="#rituals"
          class="px-6 py-4 border border-[#2a2825] hover:border-[#d1a170] text-[#e5e0d8] hover:text-[#d1a170] text-center font-syne text-xs tracking-widest uppercase transition-all rounded-sm flex items-center justify-center gap-2"
        >
          EXPLORE RITUALS <i data-lucide="chevron-right" class="w-3.5 h-3.5"></i>
        </a>
        <button 
          onclick="scrollToConfigurator()"
          class="px-6 py-4 bg-[#141412] hover:bg-[#1a1917] border border-[#2a2825] text-center font-syne text-xs tracking-widest uppercase text-[#e5e0d8] rounded-sm transition-all flex items-center justify-center gap-2"
        >
          <i data-lucide="sliders" class="w-3.5 h-3.5 text-[#d1a170]"></i> CONFIGURE SESSION
        </button>
      </div>
    </div>

    <!-- Ambient Display Mockup -->
    <div class="w-full md:w-1/2 relative">
      <div class="border border-[#2a2825] bg-[#141412]/50 p-6 md:p-10 rounded-sm relative overflow-hidden backdrop-blur-md">
        <div class="absolute top-0 right-0 p-4 font-serif text-[#2a2825] text-9xl leading-none select-none pointer-events-none">SĒN</div>
        
        <div class="relative z-10 space-y-8">
          <div class="flex justify-between items-center border-b border-[#2a2825] pb-4">
            <span class="text-xs uppercase tracking-widest text-[#8c857b]">ACTIVE SYSTEM ENVIRONMENT</span>
            <span class="text-[10px] text-[#d1a170] font-semibold tracking-widest uppercase bg-[#2a241f] px-2 py-0.5 rounded-xs">ONLINE</span>
          </div>

          <div class="space-y-2">
            <div class="text-xs text-[#8c857b] uppercase tracking-wider">Sound Frequency State</div>
            <div class="text-3xl font-serif text-[#d1a170]">
              <span id="activeFreqText">432</span>Hz <span class="text-sm font-sans text-[#8c857b] ml-2">/ Solfeggio Harmonic</span>
            </div>
          </div>

          <div class="space-y-2">
            <div class="text-xs text-[#8c857b] uppercase tracking-wider">Lighting Atmosphere</div>
            <div class="text-xl font-serif text-[#e5e0d8] flex items-center gap-3">
              <span id="activeHueIndicator" class="w-3 h-3 rounded-full bg-[#E6AF73]"></span>
              <span id="activeHueText">Dawn Amber</span>
            </div>
          </div>

          <div class="p-4 bg-[#0a0a09]/80 border border-[#262421] rounded-sm text-xs text-[#8c857b] leading-relaxed flex gap-3 items-start">
            <i data-lucide="wind" class="text-[#d1a170] shrink-0 w-4 h-4 mt-0.5"></i>
            <span>Interact with the settings below to adjust the ambient state, or configure the actual synthesized sounds to prepare your mind.</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- RITUALS PORTFOLIO -->
  <section id="rituals" class="py-24 px-6 border-t border-[#1f1e1c]/70 bg-[#0c0c0b]/80 relative z-10">
    <div class="max-w-7xl mx-auto space-y-16">
      <div class="text-center space-y-4">
        <h2 class="font-serif text-3xl sm:text-5xl uppercase tracking-wider">THE CORE RITUALS</h2>
        <div class="w-12 h-[1px] bg-[#d1a170] mx-auto"></div>
        <p class="text-sm text-[#8c857b] max-w-md mx-auto">
          Our therapies leverage ancient physical alignment methods calibrated to high-frequency modern sensory science.
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
        <!-- Ritual Card 1 -->
        <div class="group border border-[#2a2825] bg-[#141412] overflow-hidden flex flex-col h-full rounded-sm hover:border-[#d1a170]/50 transition-all duration-500">
          <div class="h-64 relative overflow-hidden bg-stone-900">
            <img 
              src="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?auto=format&fit=crop&q=80&w=1200&h=800" 
              alt="Anima Sound Bath"
              class="w-full h-full object-cover opacity-80 group-hover:scale-105 transition-transform duration-700 ease-out"
              onerror="this.src='https://images.unsplash.com/photo-1518241353330-0f7941c2d9b5?auto=format&fit=crop&q=80&w=600'"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#141412] to-transparent"></div>
            <span class="absolute bottom-4 left-4 bg-[#0a0a09]/90 border border-[#2a2825] text-xs px-3 py-1 uppercase tracking-widest text-[#d1a170]">
              Vibrational
            </span>
          </div>
          <div class="p-6 md:p-8 flex flex-col flex-grow justify-between space-y-6">
            <div class="space-y-4">
              <div class="flex justify-between items-start">
                <h3 class="font-serif text-2xl uppercase tracking-wide group-hover:text-[#d1a170] transition-colors">Anima Sound Bath</h3>
                <span class="font-serif text-lg text-[#d1a170]">$240</span>
              </div>
              <div class="flex items-center gap-4 text-xs text-[#8c857b] uppercase">
                <span class="flex items-center gap-1"><i data-lucide="clock" class="w-3 h-3"></i> 75 min</span>
                <span>•</span>
                <span>IN-HOUSE SPA RESORT</span>
              </div>
              <p class="text-xs text-[#8c857b] leading-relaxed">Immersion inside high-resonance quartz singing bowls calibrated to 432Hz. Dissolves physical resistance and rewires neural rhythms.</p>
              <div class="space-y-2 pt-2 border-t border-[#1f1e1c]">
                <div class="text-[10px] tracking-widest text-[#d1a170] uppercase font-semibold">EXPECTED BIOMARKER CHANGES:</div>
                <ul class="space-y-1.5">
                  <li class="text-xs text-[#8c857b] flex items-center gap-2">
                    <span class="w-1.5 h-1.5 bg-[#d1a170] rounded-full shrink-0"></span>
                    Decompresses nervous system
                  </li>
                  <li class="text-xs text-[#8c857b] flex items-center gap-2">
                    <span class="w-1.5 h-1.5 bg-[#d1a170] rounded-full shrink-0"></span>
                    Improves sleep latency
                  </li>
                  <li class="text-xs text-[#8c857b] flex items-center gap-2">
                    <span class="w-1.5 h-1.5 bg-[#d1a170] rounded-full shrink-0"></span>
                    Acoustic massage on cellular level
                  </li>
                </ul>
              </div>
            </div>
            <button 
              onclick="openBooking('rit-01')"
              class="w-full py-3 bg-[#2a2825]/40 hover:bg-[#d1a170] text-[#e5e0d8] hover:text-[#0a0a09] text-xs tracking-widest uppercase transition-all font-syne font-semibold rounded-sm border border-[#2a2825]"
            >
              SELECT & RESERVATION
            </button>
          </div>
        </div>

        <!-- Ritual Card 2 -->
        <div class="group border border-[#2a2825] bg-[#141412] overflow-hidden flex flex-col h-full rounded-sm hover:border-[#d1a170]/50 transition-all duration-500">
          <div class="h-64 relative overflow-hidden bg-stone-900">
            <img 
              src="https://images.unsplash.com/photo-1600334089648-b0d9d3028eb2?auto=format&fit=crop&q=80&w=1200&h=800" 
              alt="Obsidian Thermal Release"
              class="w-full h-full object-cover opacity-80 group-hover:scale-105 transition-transform duration-700 ease-out"
              onerror="this.src='https://images.unsplash.com/photo-1518241353330-0f7941c2d9b5?auto=format&fit=crop&q=80&w=600'"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#141412] to-transparent"></div>
            <span class="absolute bottom-4 left-4 bg-[#0a0a09]/90 border border-[#2a2825] text-xs px-3 py-1 uppercase tracking-widest text-[#d1a170]">
              Thermotherapy
            </span>
          </div>
          <div class="p-6 md:p-8 flex flex-col flex-grow justify-between space-y-6">
            <div class="space-y-4">
              <div class="flex justify-between items-start">
                <h3 class="font-serif text-2xl uppercase tracking-wide group-hover:text-[#d1a170] transition-colors">Obsidian Thermal</h3>
                <span class="font-serif text-lg text-[#d1a170]">$290</span>
              </div>
              <div class="flex items-center gap-4 text-xs text-[#8c857b] uppercase">
                <span class="flex items-center gap-1"><i data-lucide="clock" class="w-3 h-3"></i> 90 min</span>
                <span>•</span>
                <span>IN-HOUSE SPA RESORT</span>
              </div>
              <p class="text-xs text-[#8c857b] leading-relaxed">Deep tissue alignment incorporating raw volcanic basalt stones bathed in cold-pressed vetiver and native wood infusions.</p>
              <div class="space-y-2 pt-2 border-t border-[#1f1e1c]">
                <div class="text-[10px] tracking-widest text-[#d1a170] uppercase font-semibold">EXPECTED BIOMARKER CHANGES:</div>
                <ul class="space-y-1.5">
                  <li class="text-xs text-[#8c857b] flex items-center gap-2">
                    <span class="w-1.5 h-1.5 bg-[#d1a170] rounded-full shrink-0"></span>
                    Intense microcirculation
                  </li>
                  <li class="text-xs text-[#8c857b] flex items-center gap-2">
                    <span class="w-1.5 h-1.5 bg-[#d1a170] rounded-full shrink-0"></span>
                    Myofascial tension collapse
                  </li>
                  <li class="text-xs text-[#8c857b] flex items-center gap-2">
                    <span class="w-1.5 h-1.5 bg-[#d1a170] rounded-full shrink-0"></span>
                    Removes systemic inflammation
                  </li>
                </ul>
              </div>
            </div>
            <button 
              onclick="openBooking('rit-02')"
              class="w-full py-3 bg-[#2a2825]/40 hover:bg-[#d1a170] text-[#e5e0d8] hover:text-[#0a0a09] text-xs tracking-widest uppercase transition-all font-syne font-semibold rounded-sm border border-[#2a2825]"
            >
              SELECT & RESERVATION
            </button>
          </div>
        </div>

        <!-- Ritual Card 3 -->
        <div class="group border border-[#2a2825] bg-[#141412] overflow-hidden flex flex-col h-full rounded-sm hover:border-[#d1a170]/50 transition-all duration-500">
          <div class="h-64 relative overflow-hidden bg-stone-900">
            <img 
              src="https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&q=80&w=1200&h=800" 
              alt="Circadian Reset Ritual"
              class="w-full h-full object-cover opacity-80 group-hover:scale-105 transition-transform duration-700 ease-out"
              onerror="this.src='https://images.unsplash.com/photo-1518241353330-0f7941c2d9b5?auto=format&fit=crop&q=80&w=600'"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#141412] to-transparent"></div>
            <span class="absolute bottom-4 left-4 bg-[#0a0a09]/90 border border-[#2a2825] text-xs px-3 py-1 uppercase tracking-widest text-[#d1a170]">
              Sensory Chronology
            </span>
          </div>
          <div class="p-6 md:p-8 flex flex-col flex-grow justify-between space-y-6">
            <div class="space-y-4">
              <div class="flex justify-between items-start">
                <h3 class="font-serif text-2xl uppercase tracking-wide group-hover:text-[#d1a170] transition-colors">Circadian Reset</h3>
                <span class="font-serif text-lg text-[#d1a170]">$340</span>
              </div>
              <div class="flex items-center gap-4 text-xs text-[#8c857b] uppercase">
                <span class="flex items-center gap-1"><i data-lucide="clock" class="w-3 h-3"></i> 105 min</span>
                <span>•</span>
                <span>IN-HOUSE SPA RESORT</span>
              </div>
              <p class="text-xs text-[#8c857b] leading-relaxed">A synchronized massage and lighting protocol designed to simulate natural light shifts, realigning your internal hormonal clock.</p>
              <div class="space-y-2 pt-2 border-t border-[#1f1e1c]">
                <div class="text-[10px] tracking-widest text-[#d1a170] uppercase font-semibold">EXPECTED BIOMARKER CHANGES:</div>
                <ul class="space-y-1.5">
                  <li class="text-xs text-[#8c857b] flex items-center gap-2">
                    <span class="w-1.5 h-1.5 bg-[#d1a170] rounded-full shrink-0"></span>
                    Re-establishes natural sleep cycles
                  </li>
                  <li class="text-xs text-[#8c857b] flex items-center gap-2">
                    <span class="w-1.5 h-1.5 bg-[#d1a170] rounded-full shrink-0"></span>
                    Relieves high chronic cortisol
                  </li>
                  <li class="text-xs text-[#8c857b] flex items-center gap-2">
                    <span class="w-1.5 h-1.5 bg-[#d1a170] rounded-full shrink-0"></span>
                    Sensory deprivation healing
                  </li>
                </ul>
              </div>
            </div>
            <button 
              onclick="openBooking('rit-03')"
              class="w-full py-3 bg-[#2a2825]/40 hover:bg-[#d1a170] text-[#e5e0d8] hover:text-[#0a0a09] text-xs tracking-widest uppercase transition-all font-syne font-semibold rounded-sm border border-[#2a2825]"
            >
              SELECT & RESERVATION
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- SENSORY CONFIGURATOR -->
  <section id="configurator" class="py-24 px-6 max-w-7xl mx-auto relative z-10">
    <div class="grid grid-cols-1 lg:grid-cols-12 gap-16 items-center">
      
      <div class="lg:col-span-5 space-y-8">
        <span class="text-xs uppercase tracking-widest text-[#d1a170] font-semibold border-b border-[#d1a170]/30 pb-1">INTERACTIVE TOOL</span>
        <h2 class="font-serif text-4xl sm:text-5xl uppercase tracking-wider leading-tight">
          Acoustic & Light <br/><span class="text-[#d1a170] italic">Customizer</span>
        </h2>
        <p class="text-sm text-[#8c857b] leading-relaxed">
          Every therapeutic room is retrofitted with programmable sound arrays and custom temperature-spectrum lighting. Tune the ambient environment using the panels to preview and pre-load your preferred bio-state.
        </p>

        <!-- Audio State alert -->
        <div id="audioInitBanner" class="p-4 border border-[#2a2825] bg-[#141412]/80 rounded-sm">
          <button 
            onclick="toggleAudio()"
            class="w-full py-3 bg-[#d1a170]/10 hover:bg-[#d1a170] text-[#d1a170] hover:text-[#0a0a09] border border-[#d1a170]/30 text-xs tracking-widest uppercase transition-all rounded-sm flex items-center justify-center gap-2 font-syne font-semibold"
          >
            <i data-lucide="volume-2" class="w-4 h-4"></i> INITIALIZE LIVE AUDIO SYNTH
          </button>
        </div>
      </div>

      <div class="lg:col-span-7 bg-[#141412] border border-[#2a2825] p-6 md:p-10 rounded-sm space-y-10 backdrop-blur-md">
        
        <!-- Control Group 1: Light Spectrum -->
        <div class="space-y-4">
          <div class="flex justify-between items-center">
            <span class="text-xs uppercase tracking-widest text-[#d1a170] font-semibold">1. Ambient Light Spectrum</span>
            <span id="controlLightText" class="text-xs text-[#8c857b] uppercase font-mono">Dawn Amber</span>
          </div>
          <div class="grid grid-cols-3 gap-3">
            <button
              id="light-dawn"
              onclick="setLightState('dawn')"
              class="p-4 border text-left rounded-sm transition-all relative border-[#d1a170] bg-[#1f1c1a]"
            >
              <span class="absolute top-2 right-2 w-2 h-2 rounded-full bg-[#E6AF73]"></span>
              <span class="block text-xs uppercase tracking-wider text-[#e5e0d8] font-bold">Dawn</span>
              <span class="block text-[9px] text-[#8c857b] mt-1">Amber Hue</span>
            </button>
            <button
              id="light-twilight"
              onclick="setLightState('twilight')"
              class="p-4 border text-left rounded-sm transition-all relative border-[#262421] bg-[#0c0c0b] hover:border-[#8c857b]/30"
            >
              <span class="absolute top-2 right-2 w-2 h-2 rounded-full bg-[#5E72E4]"></span>
              <span class="block text-xs uppercase tracking-wider text-[#e5e0d8] font-bold">Twilight</span>
              <span class="block text-[9px] text-[#8c857b] mt-1">Indigo Hue</span>
            </button>
            <button
              id="light-forest"
              onclick="setLightState('forest')"
              class="p-4 border text-left rounded-sm transition-all relative border-[#262421] bg-[#0c0c0b] hover:border-[#8c857b]/30"
            >
              <span class="absolute top-2 right-2 w-2 h-2 rounded-full bg-[#52786B]"></span>
              <span class="block text-xs uppercase tracking-wider text-[#e5e0d8] font-bold">Cedar</span>
              <span class="block text-[9px] text-[#8c857b] mt-1">Shadow Hue</span>
            </button>
          </div>
        </div>

        <!-- Control Group 2: Auditory Frequency -->
        <div class="space-y-4">
          <div class="flex justify-between items-center">
            <span class="text-xs uppercase tracking-widest text-[#d1a170] font-semibold">2. Solfeggio Bio-Harmonics</span>
            <span id="controlFreqText" class="text-xs text-[#8c857b] uppercase font-mono">432Hz Resonance</span>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-3">
            <button
              id="freq-432"
              onclick="setFrequency(432)"
              class="p-4 border text-left rounded-sm transition-all border-[#d1a170] bg-[#1f1c1a]"
            >
              <div class="font-serif text-lg text-[#e5e0d8]">432Hz</div>
              <div class="text-[10px] text-[#8c857b] leading-tight mt-1">Natural Healing & Organic Peace</div>
            </button>
            <button
              id="freq-528"
              onclick="setFrequency(528)"
              class="p-4 border text-left rounded-sm transition-all border-[#262421] bg-[#0c0c0b] hover:border-[#8c857b]/30"
            >
              <div class="font-serif text-lg text-[#e5e0d8]">528Hz</div>
              <div class="text-[10px] text-[#8c857b] leading-tight mt-1">Deep Tissue Transformation</div>
            </button>
            <button
              id="freq-963"
              onclick="setFrequency(963)"
              class="p-4 border text-left rounded-sm transition-all border-[#262421] bg-[#0c0c0b] hover:border-[#8c857b]/30"
            >
              <div class="font-serif text-lg text-[#e5e0d8]">963Hz</div>
              <div class="text-[10px] text-[#8c857b] leading-tight mt-1">Pineal Activation & Pure Space</div>
            </button>
          </div>
        </div>

        <!-- Simulated Live Visual Feedback Graph -->
        <div class="space-y-2 border-t border-[#2a2825] pt-6">
          <div class="flex justify-between items-center text-[10px] uppercase tracking-widest text-[#8c857b]">
            <span>Neural Resonance Map Preview</span>
            <span id="visualizerActiveText">Inactive</span>
          </div>
          
          <div class="h-16 flex items-end gap-1 bg-[#0c0c0b] border border-[#2a2825] p-2 overflow-hidden rounded-sm">
            <!-- 24 animated equalizer bars -->
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
            <div class="eq-bar flex-grow bg-[#d1a170]/80 rounded-t-xs h-2 transition-all duration-300"></div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- SANCTUARY AMENITIES MAP & DETAIL -->
  <section class="py-24 px-6 border-t border-[#1f1e1c]/70 bg-[#0c0c0b] relative z-10">
    <div class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
      <div class="space-y-6">
        <span class="text-xs uppercase tracking-widest text-[#d1a170] font-semibold">SPACE DESIGN</span>
        <h2 class="font-serif text-3xl sm:text-5xl uppercase tracking-wider">A Physical <br/>Obsidian Escape</h2>
        <p class="text-sm text-[#8c857b] leading-relaxed">
          Located in the high basalt cliffs overlooking the northern coastline, our physical space acts as a Faraday-cage environment. No digital interruptions, no ambient wireless pollution. Just premium natural elements coupled with elite state restoration architecture.
        </p>

        <div class="grid grid-cols-2 gap-6 pt-4">
          <div class="space-y-2">
            <div class="font-serif text-lg text-[#e5e0d8] flex items-center gap-2">
              <span class="h-1.5 w-1.5 rounded-full bg-[#d1a170]"></span>
              Acoustic Isolation
            </div>
            <p class="text-xs text-[#8c857b] leading-relaxed">Double soundproof concrete layers separating each ritual capsule.</p>
          </div>
          <div class="space-y-2">
            <div class="font-serif text-lg text-[#e5e0d8] flex items-center gap-2">
              <span class="h-1.5 w-1.5 rounded-full bg-[#d1a170]"></span>
              Thermal Purity
            </div>
            <p class="text-xs text-[#8c857b] leading-relaxed">Infrared-charged heat tiles providing dynamic dry-heat alignment.</p>
          </div>
        </div>
      </div>

      <div class="relative group">
        <div class="absolute inset-0 border border-[#d1a170]/30 -translate-x-3 translate-y-3 z-0 pointer-events-none"></div>
        <div class="relative z-10 border border-[#2a2825] overflow-hidden bg-[#141412] rounded-sm">
          <img 
            src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&q=80&w=1200&h=800" 
            alt="Spa Room Design"
            class="w-full h-auto object-cover grayscale opacity-90 group-hover:grayscale-0 transition-all duration-700"
            onerror="this.src='https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&q=80&w=600'"
          />
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-[#050505] border-t border-[#1f1e1c]/70 py-16 px-6 relative z-10">
    <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-start md:items-center gap-8">
      <div class="space-y-3">
        <div class="font-serif text-2xl tracking-[0.3em] uppercase text-[#e5e0d8]">SĒN RITUALS</div>
        <p class="text-xs text-[#8c857b]">All hardware, physical architecture, and sensory frequencies engineered in-house.</p>
      </div>

      <div class="flex flex-col sm:flex-row gap-8 text-xs text-[#8c857b] tracking-wider">
        <div class="space-y-2">
          <div class="text-[#d1a170] uppercase font-semibold">LOCATIONS</div>
          <p>Basalt Cliffs Sanctuary, Suite 100 <br/>North Coastline</p>
        </div>
        <div class="space-y-2">
          <div class="text-[#d1a170] uppercase font-semibold">COMMUNICATION</div>
          <p>spa@senrituals.luxury <br/>+1 (800) 900-3490</p>
        </div>
      </div>
    </div>

    <div class="max-w-7xl mx-auto mt-12 pt-8 border-t border-[#1f1e1c]/70 flex flex-col sm:flex-row justify-between text-xs text-[#8c857b] gap-4">
      <div>&copy; <span id="currentYear"></span> SĒN SANCTUARY SYSTEMS. ALL WORLDWIDE COGNITIVE PROTOCOLS RESERVED.</div>
      <div class="flex items-center gap-2">
        <span class="w-2 h-2 rounded-full bg-[#d1a170] animate-pulse"></span>
        SYSTEM COMPILER VERSION: 2026.04.1
      </div>
    </div>
  </footer>

  <!-- BOOKING MODAL & FLOW ENGINE -->
  <div id="bookingModal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-[#0a0a09]/95 backdrop-blur-md overflow-y-auto hidden">
    <div class="w-full max-w-2xl bg-[#141412] border border-[#2a2825] p-6 md:p-10 rounded-sm relative shadow-2xl">
      
      <!-- Close Button -->
      <button 
        onclick="closeBooking()"
        class="absolute top-4 right-4 text-[#8c857b] hover:text-[#e5e0d8] p-2"
      >
        <i data-lucide="x" class="w-5 h-5"></i>
      </button>

      <!-- Progress Indicator -->
      <div class="flex items-center gap-4 text-xs tracking-widest text-[#8c857b] uppercase mb-8 border-b border-[#2a2825] pb-4">
        <span id="step1Indicator" class="text-[#d1a170] font-bold">01. Choose Treatment</span>
        <i data-lucide="chevron-right" class="w-3 h-3 text-[#2a2825]"></i>
        <span id="step2Indicator" class="">02. Chronology</span>
        <i data-lucide="chevron-right" class="w-3 h-3 text-[#2a2825]"></i>
        <span id="step3Indicator" class="">03. Registration</span>
      </div>

      <!-- STEP 1 Form Panel -->
      <div id="step1Panel" class="space-y-6">
        <div class="space-y-1">
          <h3 class="font-serif text-2xl uppercase tracking-wide text-[#e5e0d8]">SELECT RITUAL</h3>
          <p class="text-xs text-[#8c857b]">Each treatment aligns perfectly with our calibrated soundscapes.</p>
        </div>
        
        <div class="space-y-3">
          <!-- Selection options -->
          <div 
            onclick="selectRitualOption('rit-01')" 
            id="opt-rit-01"
            class="p-4 border rounded-sm cursor-pointer transition-all flex justify-between items-center border-[#d1a170] bg-[#1f1c1a]"
          >
            <div class="space-y-1">
              <h4 class="font-serif text-lg text-[#e5e0d8]">Anima Sound Bath</h4>
              <p class="text-xs text-[#8c857b]">75 min / Vibrational</p>
            </div>
            <div class="flex items-center gap-4">
              <span class="font-serif text-sm text-[#d1a170]">$240</span>
              <div id="check-rit-01" class="w-4 h-4 rounded-full border border-[#d1a170] bg-[#d1a170] flex items-center justify-center">
                <i data-lucide="check" class="w-2.5 h-2.5 text-[#0a0a09]"></i>
              </div>
            </div>
          </div>

          <div 
            onclick="selectRitualOption('rit-02')" 
            id="opt-rit-02"
            class="p-4 border rounded-sm cursor-pointer transition-all flex justify-between items-center border-[#262421] bg-[#0c0c0b] hover:border-[#8c857b]/30"
          >
            <div class="space-y-1">
              <h4 class="font-serif text-lg text-[#e5e0d8]">Obsidian Thermal Release</h4>
              <p class="text-xs text-[#8c857b]">90 min / Thermotherapy</p>
            </div>
            <div class="flex items-center gap-4">
              <span class="font-serif text-sm text-[#d1a170]">$290</span>
              <div id="check-rit-02" class="w-4 h-4 rounded-full border border-[#8c857b] flex items-center justify-center"></div>
            </div>
          </div>

          <div 
            onclick="selectRitualOption('rit-03')" 
            id="opt-rit-03"
            class="p-4 border rounded-sm cursor-pointer transition-all flex justify-between items-center border-[#262421] bg-[#0c0c0b] hover:border-[#8c857b]/30"
          >
            <div class="space-y-1">
              <h4 class="font-serif text-lg text-[#e5e0d8]">Circadian Reset Ritual</h4>
              <p class="text-xs text-[#8c857b]">105 min / Sensory Chronology</p>
            </div>
            <div class="flex items-center gap-4">
              <span class="font-serif text-sm text-[#d1a170]">$340</span>
              <div id="check-rit-03" class="w-4 h-4 rounded-full border border-[#8c857b] flex items-center justify-center"></div>
            </div>
          </div>
        </div>

        <div class="pt-4 flex justify-end">
          <button 
            type="button"
            onclick="goToStep(2)"
            class="px-6 py-3 bg-[#d1a170] text-[#0a0a09] font-syne text-xs tracking-widest uppercase rounded-sm font-bold flex items-center gap-2"
          >
            NEXT STEP <i data-lucide="chevron-right" class="w-3.5 h-3.5"></i>
          </button>
        </div>
      </div>

      <!-- STEP 2 Form Panel -->
      <div id="step2Panel" class="space-y-6 hidden">
        <div class="space-y-1">
          <h3 class="font-serif text-2xl uppercase tracking-wide text-[#e5e0d8]">SELECT CHRONOLOGY</h3>
          <p class="text-xs text-[#8c857b]">Reservations are structured to guarantee sensory isolation. Select your preferred slot.</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
          <div class="space-y-2">
            <label class="block text-xs uppercase tracking-widest text-[#8c857b]">Appointment Date</label>
            <div class="relative">
              <i data-lucide="calendar" class="absolute left-3 top-3.5 text-[#d1a170] w-4 h-4"></i>
              <input 
                id="bookingDateInput"
                type="date" 
                required
                class="w-full bg-[#0c0c0b] border border-[#2a2825] p-3 pl-10 text-xs text-[#e5e0d8] focus:border-[#d1a170] focus:outline-none rounded-sm"
              />
            </div>
          </div>

          <div class="space-y-2">
            <label class="block text-xs uppercase tracking-widest text-[#8c857b]">Available Space Hours</label>
            <div class="relative">
              <i data-lucide="clock" class="absolute left-3 top-3.5 text-[#d1a170] w-4 h-4"></i>
              <select 
                id="bookingTimeInput"
                required
                class="w-full bg-[#0c0c0b] border border-[#2a2825] p-3 pl-10 text-xs text-[#e5e0d8] focus:border-[#d1a170] focus:outline-none rounded-sm"
              >
                <option value="">-- Choose Time Window --</option>
                <option value="09:00">09:00 AM - Circadian Dawn</option>
                <option value="11:30">11:30 AM - High Solar</option>
                <option value="14:00">02:00 PM - Afternoon Stasis</option>
                <option value="16:30">04:30 PM - Twilight Indigo</option>
                <option value="19:00">07:00 PM - Deep Night Obsidian</option>
              </select>
            </div>
          </div>
        </div>

        <div class="pt-4 flex justify-between">
          <button 
            type="button"
            onclick="goToStep(1)"
            class="px-6 py-3 border border-[#2a2825] text-[#e5e0d8] font-syne text-xs tracking-widest uppercase rounded-sm hover:border-[#8c857b]/50"
          >
            BACK
          </button>
          <button 
            type="button"
            onclick="validateStep2()"
            class="px-6 py-3 bg-[#d1a170] text-[#0a0a09] font-syne text-xs tracking-widest uppercase rounded-sm font-bold flex items-center gap-2"
          >
            CONTINUE <i data-lucide="chevron-right" class="w-3.5 h-3.5"></i>
          </button>
        </div>
      </div>

      <!-- STEP 3 Form Panel -->
      <div id="step3Panel" class="space-y-6 hidden">
        <div class="space-y-1">
          <h3 class="font-serif text-2xl uppercase tracking-wide text-[#e5e0d8]">SENSORY REGISTRATION</h3>
          <p class="text-xs text-[#8c857b]">Provide security and communication protocols to prepare the room configuration.</p>
        </div>

        <form id="bookingForm" onsubmit="handleRegistrationSubmit(event)" class="space-y-6">
          <div class="space-y-4">
            <div class="relative">
              <i data-lucide="user" class="absolute left-3 top-3.5 text-[#d1a170] w-4 h-4"></i>
              <input 
                id="guestName"
                type="text" 
                placeholder="FULL GUEST NAME"
                required
                class="w-full bg-[#0c0c0b] border border-[#2a2825] p-3 pl-10 text-xs text-[#e5e0d8] focus:border-[#d1a170] focus:outline-none rounded-sm uppercase tracking-wider"
              />
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
              <div class="relative">
                <i data-lucide="mail" class="absolute left-3 top-3.5 text-[#d1a170] w-4 h-4"></i>
                <input 
                  id="guestEmail"
                  type="email" 
                  placeholder="EMAIL CORRESPONDENCE"
                  required
                  class="w-full bg-[#0c0c0b] border border-[#2a2825] p-3 pl-10 text-xs text-[#e5e0d8] focus:border-[#d1a170] focus:outline-none rounded-sm tracking-wider"
                />
              </div>

              <div class="relative">
                <i data-lucide="phone" class="absolute left-3 top-3.5 text-[#d1a170] w-4 h-4"></i>
                <input 
                  id="guestPhone"
                  type="tel" 
                  placeholder="CONTACT NUMBER"
                  required
                  class="w-full bg-[#0c0c0b] border border-[#2a2825] p-3 pl-10 text-xs text-[#e5e0d8] focus:border-[#d1a170] focus:outline-none rounded-sm tracking-wider"
                />
              </div>
            </div>

            <div class="p-4 bg-[#1a1917]/50 border border-[#2a2825] rounded-sm space-y-2 text-xs text-[#8c857b]">
              <div class="text-xs text-[#d1a170] uppercase tracking-widest font-semibold flex items-center gap-2">
                <i data-lucide="lock" class="w-3.5 h-3.5"></i> Privacy Crypt Guard
              </div>
              <p>Your session details, configured frequencies, and health information are fully encrypted. We delete digital trace logs 24 hours after completion.</p>
            </div>
          </div>

          <div class="pt-4 flex justify-between">
            <button 
              type="button"
              onclick="goToStep(2)"
              class="px-6 py-3 border border-[#2a2825] text-[#e5e0d8] font-syne text-xs tracking-widest uppercase rounded-sm hover:border-[#8c857b]/50"
            >
              BACK
            </button>

            <button 
              type="submit"
              id="submitReservationBtn"
              class="px-8 py-4 bg-[#d1a170] hover:bg-[#c29363] text-[#0a0a09] font-syne text-xs tracking-widest uppercase rounded-sm font-bold flex items-center justify-center gap-2 min-w-[200px]"
            >
              <span id="submitSpinner" class="hidden w-4 h-4 border-2 border-[#0a0a09] border-t-transparent rounded-full animate-spin"></span>
              <span id="submitBtnLabel">CONFIRM RESERVATION <i data-lucide="sparkles" class="w-3.5 h-3.5 inline"></i></span>
            </button>
          </div>
        </form>
      </div>

      <!-- SUCCESS SCREEN -->
      <div id="successPanel" class="space-y-6 text-center py-8 hidden">
        <div class="w-16 h-16 rounded-full border-2 border-[#d1a170] flex items-center justify-center mx-auto text-[#d1a170]">
          <i data-lucide="check" class="w-8 h-8"></i>
        </div>

        <h3 class="font-serif text-3xl uppercase tracking-wide text-[#e5e0d8]">SENSORY SLOT SECURED</h3>
        
        <div class="p-6 bg-[#0c0c0b] border border-[#2a2825] rounded-sm max-w-md mx-auto text-left space-y-4 text-xs">
          <div class="flex justify-between border-b border-[#1f1e1c] pb-2 text-[#8c857b] uppercase">
            <span>Receipt ID</span>
            <span id="successReceiptId" class="text-white font-mono font-bold">SEN-823491</span>
          </div>
          <div class="flex justify-between">
            <span class="text-[#8c857b] uppercase">RITUAL</span>
            <span id="successRitualName" class="text-white font-bold">Anima Sound Bath</span>
          </div>
          <div class="flex justify-between">
            <span class="text-[#8c857b] uppercase">CHRONOLOGY</span>
            <span id="successChronology" class="text-white font-bold">2026-06-25 @ 14:00</span>
          </div>
          <div class="flex justify-between">
            <span class="text-[#8c857b] uppercase">SOUND FREQUENCY PRE-SET</span>
            <span id="successFreq" class="text-[#d1a170] font-bold">432Hz</span>
          </div>
          <div class="flex justify-between">
            <span class="text-[#8c857b] uppercase">GUEST</span>
            <span id="successGuestName" class="text-white font-bold uppercase">ALEXANDER DUPONT</span>
          </div>
        </div>

        <p class="text-xs text-[#8c857b] max-w-sm mx-auto leading-relaxed">
          A secure confirmation code has been dispatched. Please arrive 15 minutes before your Circadian session to complete acclimatization.
        </p>

        <div class="pt-4">
          <button 
            onclick="closeBooking()"
            class="px-6 py-3 bg-[#d1a170] hover:bg-[#c29363] text-[#0a0a09] font-syne text-xs tracking-widest uppercase rounded-sm font-bold"
          >
            RETURN TO SANCTUARY
          </button>
        </div>
      </div>

    </div>
  </div>

  <!-- SPA AUDIO SYSTEM & INTERACTIVITY ENGINE -->
  <script>
    // System Constant Data
    const RITUAL_DATA = {
      'rit-01': { title: 'Anima Sound Bath', price: '$240' },
      'rit-02': { title: 'Obsidian Thermal Release', price: '$290' },
      'rit-03': { title: 'Circadian Reset Ritual', price: '$340' }
    };

    const LIGHT_STATES = {
      dawn: { name: 'Dawn Amber', gradient: 'radial-gradient(circle, rgba(230,175,115,0.15) 0%, rgba(10,10,9,0) 70%)', color: '#E6AF73' },
      twilight: { name: 'Twilight Indigo', gradient: 'radial-gradient(circle, rgba(94,114,228,0.12) 0%, rgba(10,10,9,0) 70%)', color: '#5E72E4' },
      forest: { name: 'Cedar Shadow', gradient: 'radial-gradient(circle, rgba(82,120,107,0.15) 0%, rgba(10,10,9,0) 70%)', color: '#52786B' }
    };

    const FREQUENCIES = {
      432: 'Natural Healing & Organic Peace',
      528: 'Deep Tissue Transformation',
      963: 'Pineal Activation & Pure Space'
    };

    // App State Variables
    let audioEnabled = false;
    let ambientVolume = 0.4;
    let selectedHz = 432;
    let currentLight = 'dawn';
    let currentBookedRitualId = 'rit-01';
    let currentBookingStep = 1;

    // Web Audio Nodes
    let audioCtx = null;
    let osc1 = null;
    let osc2 = null;
    let filter = null;
    let noise = null;
    let noiseFilter = null;
    let noiseGain = null;
    let masterGain = null;
    let visualizerInterval = null;

    // Set Footer Year dynamically
    document.getElementById('currentYear').innerText = new Date().getFullYear();

    // Initialize Lucide Icons on launch
    window.addEventListener('DOMContentLoaded', () => {
      lucide.createIcons();
    });

    // Scroll auxiliary helper
    function scrollToConfigurator() {
      document.getElementById('configurator').scrollIntoView();
      if (!audioEnabled) {
        toggleAudio();
      }
    }

    // Dynamic Atmosphere Light State Engine
    function setLightState(stateKey) {
      const state = LIGHT_STATES[stateKey];
      if (!state) return;
      currentLight = stateKey;

      // Update background mesh instantly with transitions
      document.getElementById('ambientMesh').style.background = state.gradient;

      // Update displays
      document.getElementById('activeHueIndicator').style.backgroundColor = state.color;
      document.getElementById('activeHueText').innerText = state.name;
      document.getElementById('controlLightText').innerText = state.name;

      // Swap button active styling in configurator
      ['dawn', 'twilight', 'forest'].forEach(key => {
        const btn = document.getElementById(`light-${key}`);
        if (key === stateKey) {
          btn.className = 'p-4 border text-left rounded-sm transition-all relative border-[#d1a170] bg-[#1f1c1a]';
        } else {
          btn.className = 'p-4 border text-left rounded-sm transition-all relative border-[#262421] bg-[#0c0c0b] hover:border-[#8c857b]/30';
        }
      });
    }

    // Frequency Controller
    function setFrequency(hz) {
      selectedHz = hz;
      document.getElementById('activeFreqText').innerText = hz;
      document.getElementById('controlFreqText').innerText = `${hz}Hz Resonance`;

      // Update Audio nodes if running
      if (audioEnabled && audioCtx && osc1 && osc2) {
        const baseFreq = selectedHz / 4; // deep base
        osc1.frequency.setValueAtTime(baseFreq, audioCtx.currentTime);
        osc2.frequency.setValueAtTime(baseFreq * 1.004, audioCtx.currentTime);
      }

      // Sync active state UI
      Object.keys(FREQUENCIES).forEach(key => {
        const btn = document.getElementById(`freq-${key}`);
        if (parseInt(key) === hz) {
          btn.className = 'p-4 border text-left rounded-sm transition-all border-[#d1a170] bg-[#1f1c1a]';
        } else {
          btn.className = 'p-4 border text-left rounded-sm transition-all border-[#262421] bg-[#0c0c0b] hover:border-[#8c857b]/30';
        }
      });

      // Automatically turn audio ON when user explores specific frequencies
      if (!audioEnabled) {
        toggleAudio();
      }
    }

    // Audio Engine Handlers (Web Audio API)
    function toggleAudio() {
      audioEnabled = !audioEnabled;
      
      const audioIcon = document.getElementById('audioIcon');
      const audioBtnText = document.getElementById('audioBtnText');
      const volumeControl = document.getElementById('volumeControlContainer');
      const visualizerText = document.getElementById('visualizerActiveText');
      const initBanner = document.getElementById('audioInitBanner');

      if (audioEnabled) {
        // Update elements
        audioIcon.setAttribute('data-lucide', 'volume-2');
        audioIcon.classList.add('animate-pulse');
        audioBtnText.innerText = 'AUDIO LIVE';
        volumeControl.classList.remove('hidden');
        visualizerText.innerText = 'Active';
        initBanner.classList.add('hidden');
        lucide.createIcons();

        startAmbientSynth();
        startVisualizer();
      } else {
        audioIcon.setAttribute('data-lucide', 'volume-x');
        audioIcon.classList.remove('animate-pulse');
        audioBtnText.innerText = 'PLAY AUDIO';
        volumeControl.classList.add('hidden');
        visualizerText.innerText = 'Inactive';
        initBanner.classList.remove('hidden');
        lucide.createIcons();

        stopAmbientSynth();
        stopVisualizer();
      }
    }

    function handleVolumeChange(value) {
      ambientVolume = parseFloat(value);
      if (masterGain && audioCtx) {
        masterGain.gain.linearRampToValueAtTime(ambientVolume, audioCtx.currentTime + 0.3);
      }
    }

    function startAmbientSynth() {
      try {
        const AudioContext = window.AudioContext || window.webkitAudioContext;
        if (!AudioContext) return;

        audioCtx = new AudioContext();

        // Setup master gain Node
        masterGain = audioCtx.createGain();
        masterGain.gain.setValueAtTime(0, audioCtx.currentTime);

        // Setup Deep low harmonic drone
        osc1 = audioCtx.createOscillator();
        osc1.type = 'sine';
        osc1.frequency.setValueAtTime(selectedHz / 4, audioCtx.currentTime);

        // Sub beating warmth frequency
        osc2 = audioCtx.createOscillator();
        osc2.type = 'triangle';
        osc2.frequency.setValueAtTime((selectedHz / 4) * 1.004, audioCtx.currentTime);

        // Filtering harsh highs
        filter = audioCtx.createBiquadFilter();
        filter.type = 'lowpass';
        filter.frequency.setValueAtTime(140, audioCtx.currentTime);
        filter.Q.setValueAtTime(1, audioCtx.currentTime);

        // Synthesize dynamic organic rain/ocean noise buffer
        const bufferSize = audioCtx.sampleRate * 2;
        const noiseBuffer = audioCtx.createBuffer(1, bufferSize, audioCtx.sampleRate);
        const output = noiseBuffer.getChannelData(0);
        for (let i = 0; i < bufferSize; i++) {
          output[i] = Math.random() * 2 - 1;
        }

        noise = audioCtx.createBufferSource();
        noise.buffer = noiseBuffer;
        noise.loop = true;

        noiseFilter = audioCtx.createBiquadFilter();
        noiseFilter.type = 'bandpass';
        noiseFilter.frequency.setValueAtTime(400, audioCtx.currentTime);
        noiseFilter.Q.setValueAtTime(0.5, audioCtx.currentTime);

        noiseGain = audioCtx.createGain();
        noiseGain.gain.setValueAtTime(0.12, audioCtx.currentTime);

        // Chain connections
        osc1.connect(filter);
        osc2.connect(filter);
        
        noise.connect(noiseFilter);
        noiseFilter.connect(noiseGain);
        
        filter.connect(masterGain);
        noiseGain.connect(masterGain);
        
        masterGain.connect(audioCtx.destination);

        // Kick off continuous oscillators
        osc1.start();
        osc2.start();
        noise.start();

        // Fade in Master level gracefully
        masterGain.gain.linearRampToValueAtTime(ambientVolume, audioCtx.currentTime + 1.5);
      } catch (err) {
        console.warn("Sensory engine initial setup bypass", err);
      }
    }

    function stopAmbientSynth() {
      if (audioCtx) {
        try {
          if (masterGain) {
            masterGain.gain.linearRampToValueAtTime(0, audioCtx.currentTime + 0.4);
          }
          setTimeout(() => {
            if (audioCtx && audioCtx.state !== 'closed') {
              audioCtx.close();
            }
          }, 500);
        } catch (e) {
          console.warn(e);
        }
      }
    }

    // Visualizer simulation mapping
    function startVisualizer() {
      const bars = document.querySelectorAll('.eq-bar');
      visualizerInterval = setInterval(() => {
        bars.forEach(bar => {
          const heightPct = Math.floor(Math.random() * 80) + 15;
          bar.style.height = `${heightPct}%`;
        });
      }, 150);
    }

    function stopVisualizer() {
      if (visualizerInterval) {
        clearInterval(visualizerInterval);
      }
      const bars = document.querySelectorAll('.eq-bar');
      bars.forEach(bar => {
        bar.style.height = '8px';
      });
    }

    // Booking Modal Orchestration System
    function openBooking(defaultRitualId) {
      document.getElementById('bookingModal').classList.remove('hidden');
      document.body.classList.add('overflow-hidden');
      selectRitualOption(defaultRitualId || 'rit-01');
      goToStep(1);
    }

    function closeBooking() {
      document.getElementById('bookingModal').classList.add('hidden');
      document.body.classList.remove('overflow-hidden');
      resetBookingForms();
    }

    function selectRitualOption(ritualId) {
      currentBookedRitualId = ritualId;
      ['rit-01', 'rit-02', 'rit-03'].forEach(id => {
        const row = document.getElementById(`opt-${id}`);
        const check = document.getElementById(`check-${id}`);
        if (id === ritualId) {
          row.className = 'p-4 border rounded-sm cursor-pointer transition-all flex justify-between items-center border-[#d1a170] bg-[#1f1c1a]';
          check.className = 'w-4 h-4 rounded-full border border-[#d1a170] bg-[#d1a170] flex items-center justify-center';
          check.innerHTML = '<i data-lucide="check" class="w-2.5 h-2.5 text-[#0a0a09]"></i>';
        } else {
          row.className = 'p-4 border rounded-sm cursor-pointer transition-all flex justify-between items-center border-[#262421] bg-[#0c0c0b] hover:border-[#8c857b]/30';
          check.className = 'w-4 h-4 rounded-full border border-[#8c857b] flex items-center justify-center';
          check.innerHTML = '';
        }
      });
      lucide.createIcons();
    }

    function goToStep(step) {
      currentBookingStep = step;

      // Hide all panels
      document.getElementById('step1Panel').classList.add('hidden');
      document.getElementById('step2Panel').classList.add('hidden');
      document.getElementById('step3Panel').classList.add('hidden');
      document.getElementById('successPanel').classList.add('hidden');

      // Sync Navigation Header Style Indicators
      document.getElementById('step1Indicator').className = step === 1 ? 'text-[#d1a170] font-bold' : 'text-[#8c857b]';
      document.getElementById('step2Indicator').className = step === 2 ? 'text-[#d1a170] font-bold' : 'text-[#8c857b]';
      document.getElementById('step3Indicator').className = step === 3 ? 'text-[#d1a170] font-bold' : 'text-[#8c857b]';

      // Show Selected Panel
      if (step === 1) {
        document.getElementById('step1Panel').classList.remove('hidden');
      } else if (step === 2) {
        document.getElementById('step2Panel').classList.remove('hidden');
      } else if (step === 3) {
        document.getElementById('step3Panel').classList.remove('hidden');
      }
    }

    function validateStep2() {
      const date = document.getElementById('bookingDateInput').value;
      const time = document.getElementById('bookingTimeInput').value;
      
      if (!date || !time) {
        showCustomNotice("Sensory Chronology", "Please pick both a valid reservation date and a preferred timeslot.");
        return;
      }
      goToStep(3);
    }

    function handleRegistrationSubmit(event) {
      event.preventDefault();
      
      const btn = document.getElementById('submitReservationBtn');
      const spinner = document.getElementById('submitSpinner');
      const btnLabel = document.getElementById('submitBtnLabel');

      // Set disabled state & loading indicators
      btn.disabled = true;
      spinner.classList.remove('hidden');
      btnLabel.classList.add('hidden');

      // Pull Input Data
      const guestName = document.getElementById('guestName').value;
      const guestEmail = document.getElementById('guestEmail').value;
      const guestPhone = document.getElementById('guestPhone').value;
      const bookingDate = document.getElementById('bookingDateInput').value;
      const bookingTime = document.getElementById('bookingTimeInput').value;
      const activeRitual = RITUAL_DATA[currentBookedRitualId];

      setTimeout(() => {
        // Simulated Reservation Success Page Population
        document.getElementById('successReceiptId').innerText = `SEN-${Math.floor(100000 + Math.random() * 900000)}`;
        document.getElementById('successRitualName').innerText = activeRitual.title;
        document.getElementById('successChronology').innerText = `${bookingDate} @ ${bookingTime}`;
        document.getElementById('successFreq').innerText = `${selectedHz}Hz`;
        document.getElementById('successGuestName').innerText = guestName.toUpperCase();

        // Pivot view panel state
        document.getElementById('step3Panel').classList.add('hidden');
        document.getElementById('successPanel').classList.remove('hidden');
        
        // Reset navigation step indicators
        document.getElementById('step1Indicator').className = 'text-[#8c857b]';
        document.getElementById('step2Indicator').className = 'text-[#8c857b]';
        document.getElementById('step3Indicator').className = 'text-[#8c857b]';

        btn.disabled = false;
        spinner.classList.add('hidden');
        btnLabel.classList.remove('hidden');
      }, 1800);
    }

    function resetBookingForms() {
      document.getElementById('bookingForm').reset();
      document.getElementById('bookingDateInput').value = '';
      document.getElementById('bookingTimeInput').value = '';
      currentBookingStep = 1;
    }

    // Custom Elegant Dialog Overlay helper (replaces standard browser alerts)
    function showCustomNotice(title, text) {
      const overlay = document.createElement('div');
      overlay.className = 'fixed inset-0 z-[100] flex items-center justify-center p-4 bg-black/80 backdrop-blur-sm';
      overlay.id = 'noticeOverlay';
      overlay.innerHTML = `
        <div class="w-full max-w-sm bg-[#141412] border border-[#d1a170]/40 p-6 rounded-sm space-y-4 shadow-2xl">
          <h4 class="font-serif text-lg text-[#d1a170] uppercase tracking-wider">${title}</h4>
          <p class="text-xs text-[#8c857b] leading-relaxed">${text}</p>
          <button 
            onclick="document.getElementById('noticeOverlay').remove()"
            class="w-full py-2 bg-[#d1a170] text-[#0a0a09] font-syne text-xs tracking-widest uppercase font-bold rounded-sm hover:bg-[#c29363] transition-colors"
          >
            DISMISS
          </button>
        </div>
      `;
      document.body.appendChild(overlay);
    }
  </script>
</body>
</html>

```
-
