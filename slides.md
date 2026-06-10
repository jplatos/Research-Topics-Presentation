---
theme: default
background: title.jpg
class: text-center my-auto
highlighter: shiki
transition: slide-left
title: Výzkumné směry univerzity
---

<!-- SLIDE 1: Úvodní stránka s obrázkem na pozadí -->
<div class="bg-black/15 p-5 rounded-lg backdrop-blur-sm inline-block">
  <h1 class="text-4xl font-extrabold text-white tracking-wide uppercase">Výzkumné směry univerzity</h1>
  <h2 class="text-xl font-extrabold text-white tracking-wide uppercase">Pracovní verze</h2>
</div>

---
transition: slide-left
style: 'background: #0f0f0f'
title: Čtyři výzkumné pilíře
---

<style>
@keyframes pillarRise {
  0%   { transform: translateY(70px); opacity: 0; }
  100% { transform: translateY(0);    opacity: 1; }
}
@keyframes lineGrow {
  from { transform: scaleX(0); transform-origin: left; }
  to   { transform: scaleX(1); transform-origin: left; }
}
@keyframes fadeInUp {
  from { transform: translateY(12px); opacity: 0; }
  to   { transform: translateY(0);    opacity: 1; }
}
.pillar {
  animation: pillarRise 0.8s cubic-bezier(0.22, 1, 0.36, 1) both;
}
.pillar:nth-child(1) { animation-delay: 0.0s; }
.pillar:nth-child(2) { animation-delay: 0.15s; }
.pillar:nth-child(3) { animation-delay: 0.30s; }
.pillar:nth-child(4) { animation-delay: 0.45s; }
.accent-bar {
  animation: lineGrow 0.55s ease-out both;
}
.pillar:nth-child(1) .accent-bar { animation-delay: 0.55s; }
.pillar:nth-child(2) .accent-bar { animation-delay: 0.70s; }
.pillar:nth-child(3) .accent-bar { animation-delay: 0.85s; }
.pillar:nth-child(4) .accent-bar { animation-delay: 1.0s; }
.pillar-label {
  animation: fadeInUp 0.45s ease-out both;
}
.pillar:nth-child(1) .pillar-label { animation-delay: 0.7s; }
.pillar:nth-child(2) .pillar-label { animation-delay: 0.85s; }
.pillar:nth-child(3) .pillar-label { animation-delay: 1.0s; }
.pillar:nth-child(4) .pillar-label { animation-delay: 1.15s; }
</style>

<div class="absolute inset-0 flex">

  <div class="pillar flex-1 relative overflow-hidden border-r border-white/10 group">
    <img src="./top/01p.png" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 ease-out group-hover:scale-105" />
    <div class="absolute inset-0 bg-gradient-to-t from-black/92 via-black/20 to-black/50"></div>
    <div class="accent-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
    <div class="absolute top-3 left-4 font-black leading-none text-[#00A499] opacity-[0.12] select-none" style="font-size: 6.5rem;">01</div>
    <div class="pillar-label absolute inset-x-0 bottom-0 px-5 pb-6">
      <div class="w-6 h-px bg-[#00A499] mb-3"></div>
      <p class="text-white font-extrabold text-sm leading-snug mb-2">Digitální transformace, AI a superpočítání</p>
      <p class="text-[#00A499] text-[9px] uppercase tracking-widest font-semibold leading-relaxed">HPC · Kvantové počítání · AI · Big Data</p>
    </div>
  </div>

  <div class="pillar flex-1 relative overflow-hidden border-r border-white/10 group">
    <img src="./top/02p.png" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 ease-out group-hover:scale-105" />
    <div class="absolute inset-0 bg-gradient-to-t from-black/92 via-black/20 to-black/50"></div>
    <div class="accent-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
    <div class="absolute top-3 left-4 font-black leading-none text-[#00A499] opacity-[0.12] select-none" style="font-size: 6.5rem;">02</div>
    <div class="pillar-label absolute inset-x-0 bottom-0 px-5 pb-6">
      <div class="w-6 h-px bg-[#00A499] mb-3"></div>
      <p class="text-white font-extrabold text-sm leading-snug mb-2">Pokročilé materiály, polovodiče a mikrosystémy</p>
      <p class="text-[#00A499] text-[9px] uppercase tracking-widest font-semibold leading-relaxed">Čipy · GaN/SiC · Nanomateriály · 3D tisk</p>
    </div>
  </div>

  <div class="pillar flex-1 relative overflow-hidden border-r border-white/10 group">
    <img src="./top/03p.png" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 ease-out group-hover:scale-105" />
    <div class="absolute inset-0 bg-gradient-to-t from-black/92 via-black/20 to-black/50"></div>
    <div class="accent-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
    <div class="absolute top-3 left-4 font-black leading-none text-[#00A499] opacity-[0.12] select-none" style="font-size: 6.5rem;">03</div>
    <div class="pillar-label absolute inset-x-0 bottom-0 px-5 pb-6">
      <div class="w-6 h-px bg-[#00A499] mb-3"></div>
      <p class="text-white font-extrabold text-sm leading-snug mb-2">Autonomní systémy, robotika a chytrá mobilita</p>
      <p class="text-[#00A499] text-[9px] uppercase tracking-widest font-semibold leading-relaxed">Robotika · Drony · Vesmír · Autonomní vozidla</p>
    </div>
  </div>

  <div class="pillar flex-1 relative overflow-hidden group">
    <img src="./top/04p.png" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 ease-out group-hover:scale-105" />
    <div class="absolute inset-0 bg-gradient-to-t from-black/92 via-black/20 to-black/50"></div>
    <div class="accent-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
    <div class="absolute top-3 left-4 font-black leading-none text-[#00A499] opacity-[0.12] select-none" style="font-size: 6.5rem;">04</div>
    <div class="pillar-label absolute inset-x-0 bottom-0 px-5 pb-6">
      <div class="w-6 h-px bg-[#00A499] mb-3"></div>
      <p class="text-white font-extrabold text-sm leading-snug mb-2">Udržitelnost, bezpečnost a zdraví společnosti</p>
      <p class="text-[#00A499] text-[9px] uppercase tracking-widest font-semibold leading-relaxed">Energetika · Bezpečnost · Biomedicína · Ekonomika</p>
    </div>
  </div>

</div>

---
transition: slide-left
style: 'background: #111'
title: Pilíř 01 – Digitální transformace, AI a superpočítání
---

<style>
@keyframes spineIn {
  from { transform: translateX(-35px); opacity: 0; }
  to   { transform: translateX(0); opacity: 1; }
}
@keyframes pi1cardRise {
  from { transform: translateY(60px); opacity: 0; }
  to   { transform: translateY(0); opacity: 1; }
}
@keyframes pi1lineGrow {
  from { transform: scaleX(0); transform-origin: left; }
  to   { transform: scaleX(1); }
}
.pi1-spine { animation: spineIn 0.7s cubic-bezier(0.22,1,0.36,1) both 0.05s; }
.pi1-card  { animation: pi1cardRise 0.75s cubic-bezier(0.22,1,0.36,1) both; }
.pi1-card:nth-child(1) { animation-delay: 0.2s; }
.pi1-card:nth-child(2) { animation-delay: 0.35s; }
.pi1-bar { animation: pi1lineGrow 0.5s ease-out both; }
.pi1-card:nth-child(1) .pi1-bar { animation-delay: 0.7s; }
.pi1-card:nth-child(2) .pi1-bar { animation-delay: 0.85s; }
</style>

<div class="absolute inset-0 flex">

  <div class="pi1-spine w-[22%] relative flex flex-col justify-between overflow-hidden border-r border-white/10 px-6 py-7">
    <img src="./top/01p.png" class="absolute inset-0 w-full h-full object-cover opacity-[0.12]" />
    <div class="absolute inset-0 bg-gradient-to-br from-black/80 to-black/95"></div>
    <div class="relative z-10">
      <span class="text-[#00A499] text-[9px] font-bold uppercase tracking-[0.3em]">Pilíř 01</span>
      <h2 class="text-white font-extrabold leading-snug mt-2 mb-3" style="font-size: 24px; line-height: 1.4;">Digitální transformace, AI a superpočítání</h2>
      <div class="w-8 h-px bg-[#00A499] mb-3"></div>
      <p class="text-neutral-400 text-[11px] leading-relaxed">Digitální a výpočetní jádro univerzity pohánějící moderní průmysl i vědu.</p>
    </div>
    <div class="relative z-10">
      <p class="text-[9px] text-neutral-600 uppercase tracking-widest">2 výzkumné okruhy</p>
    </div>
  </div>

  <div class="flex-1 flex">
    <div class="pi1-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-04-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi1-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-4 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">1.1</div>
      <div class="absolute inset-x-0 bottom-0 px-5 pb-7">
        <p class="text-white font-extrabold text-xl leading-snug mb-4" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Vysoce výkonné a kvantové výpočty</p>
        <div class="flex flex-wrap gap-1.5">
          <span class="text-[9px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-2 py-0.5">HPC</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Kvantová optimalizace</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">LUMI-Q</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Kvantové ML</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Simulace materiálů</span>
        </div>
      </div>
    </div>
    <div class="pi1-card flex-1 relative overflow-hidden">
      <img src="./topic-06-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi1-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-4 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">1.2</div>
      <div class="absolute inset-x-0 bottom-0 px-5 pb-7">
        <p class="text-white font-extrabold text-xl leading-snug mb-4" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Aplikovaná AI a datová analytika</p>
        <div class="flex flex-wrap gap-1.5">
          <span class="text-[9px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-2 py-0.5">AI & ML</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Digitální dvojčata</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">5G / 6G</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Big Data</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Neuronové sítě</span>
        </div>
      </div>
    </div>

  </div>

</div>

---
transition: slide-left
style: 'background: #111'
title: Pilíř 02 – Pokročilé materiály, polovodiče a mikrosystémy
---

<style>
@keyframes pi2spineIn {
  from { transform: translateX(-35px); opacity: 0; }
  to   { transform: translateX(0); opacity: 1; }
}
@keyframes pi2cardRise {
  from { transform: translateY(60px); opacity: 0; }
  to   { transform: translateY(0); opacity: 1; }
}
@keyframes pi2lineGrow {
  from { transform: scaleX(0); transform-origin: left; }
  to   { transform: scaleX(1); }
}
.pi2-spine { animation: pi2spineIn 0.7s cubic-bezier(0.22,1,0.36,1) both 0.05s; }
.pi2-card  { animation: pi2cardRise 0.75s cubic-bezier(0.22,1,0.36,1) both; }
.pi2-card:nth-child(1) { animation-delay: 0.2s; }
.pi2-card:nth-child(2) { animation-delay: 0.35s; }
.pi2-bar { animation: pi2lineGrow 0.5s ease-out both; }
.pi2-card:nth-child(1) .pi2-bar { animation-delay: 0.7s; }
.pi2-card:nth-child(2) .pi2-bar { animation-delay: 0.85s; }
</style>

<div class="absolute inset-0 flex">

  <div class="pi2-spine w-[22%] relative flex flex-col justify-between overflow-hidden border-r border-white/10 px-6 py-7">
    <img src="./top/02p.png" class="absolute inset-0 w-full h-full object-cover opacity-[0.12]" />
    <div class="absolute inset-0 bg-gradient-to-br from-black/80 to-black/95"></div>
    <div class="relative z-10">
      <span class="text-[#00A499] text-[9px] font-bold uppercase tracking-[0.3em]">Pilíř 02</span>
      <h2 class="text-white font-extrabold leading-snug mt-2 mb-3" style="font-size: 24px; line-height: 1.4;">Pokročilé materiály, polovodiče a mikrosystémy</h2>
      <div class="w-8 h-px bg-[#00A499] mb-3"></div>
      <p class="text-neutral-400 text-[11px] leading-relaxed">Materiálový výzkum od atomární struktury po finální hardwarové komponenty.</p>
    </div>
    <div class="relative z-10">
      <p class="text-[9px] text-neutral-600 uppercase tracking-widest">2 výzkumné okruhy</p>
    </div>
  </div>

  <div class="flex-1 flex">
    <div class="pi2-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-01-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi2-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-4 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">2.1</div>
      <div class="absolute inset-x-0 bottom-0 px-5 pb-7">
        <p class="text-white font-extrabold text-xl leading-snug mb-4" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Čipové technologie a polovodičové systémy</p>
        <div class="flex flex-wrap gap-1.5">
          <span class="text-[9px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-2 py-0.5">Návrh IC</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">GaN / SiC</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Mikrosystémy</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Čisté prostory</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Heterogenní integrace</span>
        </div>
      </div>
    </div>
    <div class="pi2-card flex-1 relative overflow-hidden">
      <img src="./topic-07-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi2-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-4 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">2.2</div>
      <div class="absolute inset-x-0 bottom-0 px-5 pb-7">
        <p class="text-white font-extrabold text-xl leading-snug mb-4" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Pokročilé materiály a nanotechnologie</p>
        <div class="flex flex-wrap gap-1.5">
          <span class="text-[9px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-2 py-0.5">Nanomateriály</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">3D tisk kovů</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Biodegradabilní mat.</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Kompozity</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Ukládání energie</span>
        </div>
      </div>
    </div>

  </div>

</div>

---
transition: slide-left
style: 'background: #111'
title: Pilíř 03 – Autonomní systémy, robotika a chytrá mobilita
---

<style>
@keyframes pi3spineIn {
  from { transform: translateX(-35px); opacity: 0; }
  to   { transform: translateX(0); opacity: 1; }
}
@keyframes pi3cardRise {
  from { transform: translateY(60px); opacity: 0; }
  to   { transform: translateY(0); opacity: 1; }
}
@keyframes pi3lineGrow {
  from { transform: scaleX(0); transform-origin: left; }
  to   { transform: scaleX(1); }
}
.pi3-spine { animation: pi3spineIn 0.7s cubic-bezier(0.22,1,0.36,1) both 0.05s; }
.pi3-card  { animation: pi3cardRise 0.75s cubic-bezier(0.22,1,0.36,1) both; }
.pi3-card:nth-child(1) { animation-delay: 0.2s; }
.pi3-card:nth-child(2) { animation-delay: 0.30s; }
.pi3-card:nth-child(3) { animation-delay: 0.40s; }
.pi3-card:nth-child(4) { animation-delay: 0.50s; }
.pi3-bar { animation: pi3lineGrow 0.5s ease-out both; }
.pi3-card:nth-child(1) .pi3-bar { animation-delay: 0.65s; }
.pi3-card:nth-child(2) .pi3-bar { animation-delay: 0.75s; }
.pi3-card:nth-child(3) .pi3-bar { animation-delay: 0.85s; }
.pi3-card:nth-child(4) .pi3-bar { animation-delay: 0.95s; }
</style>

<div class="absolute inset-0 flex">

  <div class="pi3-spine w-[18%] relative flex flex-col justify-between overflow-hidden border-r border-white/10 px-5 py-7">
    <img src="./top/03p.png" class="absolute inset-0 w-full h-full object-cover opacity-[0.12]" />
    <div class="absolute inset-0 bg-gradient-to-br from-black/80 to-black/95"></div>
    <div class="relative z-10">
      <span class="text-[#00A499] text-[9px] font-bold uppercase tracking-[0.3em]">Pilíř 03</span>
      <h2 class="text-white font-extrabold leading-snug mt-2 mb-3" style="font-size: 24px; line-height: 1.4;">Autonomní systémy, robotika a chytrá mobilita</h2>
      <div class="w-8 h-px bg-[#00A499] mb-3"></div>
      <p class="text-neutral-400 text-[10px] leading-relaxed">Inteligentní stroje a dopravní systémy měnící pohyb na zemi, ve vzduchu i ve vesmíru.</p>
    </div>
    <div class="relative z-10">
      <p class="text-[9px] text-neutral-600 uppercase tracking-widest">4 výzkumné okruhy</p>
    </div>
  </div>

  <div class="flex-1 flex">
    <div class="pi3-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-08-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi3-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">3.1</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Robotika a Průmysl 4.0</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Průmyslová robotika</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Mechatronika</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Prediktivní údržba</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Kobotika</span>
        </div>
      </div>
    </div>
    <div class="pi3-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-02-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi3-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">3.2</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Vesmírné technologie</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">CONREX / ISS</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Mikrosatelity</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Nanorobotika</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Pozorování Země</span>
        </div>
      </div>
    </div>
    <div class="pi3-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-03-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi3-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">3.3</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Obranné technologie</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Rojy dronů</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Autonomní vozidla</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Kyber obrana</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">NATO / DIANA</span>
        </div>
      </div>
    </div>
    <div class="pi3-card flex-1 relative overflow-hidden">
      <img src="./topic-10-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi3-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">3.4</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Chytrá mobilita</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Autonomní řízení</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Elektromobilita</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Telematika</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Smart cities</span>
        </div>
      </div>
    </div>

  </div>

</div>

---
transition: slide-left
style: 'background: #111'
title: Pilíř 04 – Udržitelnost, bezpečnost a zdraví společnosti
---

<style>
@keyframes pi4spineIn {
  from { transform: translateX(-35px); opacity: 0; }
  to   { transform: translateX(0); opacity: 1; }
}
@keyframes pi4cardRise {
  from { transform: translateY(60px); opacity: 0; }
  to   { transform: translateY(0); opacity: 1; }
}
@keyframes pi4lineGrow {
  from { transform: scaleX(0); transform-origin: left; }
  to   { transform: scaleX(1); }
}
.pi4-spine { animation: pi4spineIn 0.7s cubic-bezier(0.22,1,0.36,1) both 0.05s; }
.pi4-card  { animation: pi4cardRise 0.75s cubic-bezier(0.22,1,0.36,1) both; }
.pi4-card:nth-child(1) { animation-delay: 0.2s; }
.pi4-card:nth-child(2) { animation-delay: 0.30s; }
.pi4-card:nth-child(3) { animation-delay: 0.40s; }
.pi4-card:nth-child(4) { animation-delay: 0.50s; }
.pi4-bar { animation: pi4lineGrow 0.5s ease-out both; }
.pi4-card:nth-child(1) .pi4-bar { animation-delay: 0.65s; }
.pi4-card:nth-child(2) .pi4-bar { animation-delay: 0.75s; }
.pi4-card:nth-child(3) .pi4-bar { animation-delay: 0.85s; }
.pi4-card:nth-child(4) .pi4-bar { animation-delay: 0.95s; }
</style>

<div class="absolute inset-0 flex">

  <div class="pi4-spine w-[18%] relative flex flex-col justify-between overflow-hidden border-r border-white/10 px-5 py-7">
    <img src="./top/04p.png" class="absolute inset-0 w-full h-full object-cover opacity-[0.12]" />
    <div class="absolute inset-0 bg-gradient-to-br from-black/95 to-black/80"></div>
    <div class="relative z-10">
      <span class="text-[#00A499] text-[9px] font-bold uppercase tracking-[0.3em]">Pilíř 04</span>
      <h2 class="text-white font-extrabold leading-snug mt-2 mb-3" style="font-size: 24px; line-height: 1.4;">Udržitelnost, bezpečnost a zdraví společnosti</h2>
      <div class="w-8 h-px bg-[#00A499] mb-3"></div>
      <p class="text-neutral-400 text-[10px] leading-relaxed">Mezioborový výzkum zaměřený na ochranu životů, planetární zdraví a ekonomickou resilienci.</p>
    </div>
    <div class="relative z-10">
      <p class="text-[9px] text-neutral-600 uppercase tracking-widest">4 výzkumné okruhy</p>
    </div>
  </div>

  <div class="flex-1 flex">
    <div class="pi4-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-05-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi4-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">4.1</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Udržitelná energetika</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Obnovitelné zdroje</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Vodík</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Smart Grids</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Cirkulární ekonomika</span>
        </div>
      </div>
    </div>
    <div class="pi4-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-09-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi4-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">4.2</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Bezpečnost a resilience</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Požární inženýrství</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Kritická infrastruktura</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Kyberbezpečnost</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Krizové řízení</span>
        </div>
      </div>
    </div>
    <div class="pi4-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-11-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi4-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">4.3</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Biomedicínské inženýrství</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Biosenzory</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Nanorobotika</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Telemedicína</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Asistenční tech.</span>
        </div>
      </div>
    </div>
    <div class="pi4-card flex-1 relative overflow-hidden">
      <img src="./topic-12-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi4-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">4.4</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Ekonomika a management</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Strategické řízení</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Fin. modelování</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Ekonomika klimatu</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Analýza dopadů</span>
        </div>
      </div>
    </div>

  </div>

</div>

---
layout: topic
transition: slide-left
title: Kvantové počítání a hybridní HPC systémy
image: ./topic-04-p.jpg
contactPhoto: ./kozubek.jpg
contactName: 'prof. Ing. Tomáš Kozubek, Ph.D.'
---

::annotation::
Posouváme hranice vysoce výkonných výpočtů do éry kvantové akcelerace. Využíváme zázemí špičkového supravodivého systému LUMI-Q a zaměřujeme se na vývoj softwarové vrstvy i kvantových algoritmů. Cílem našeho výzkumu je plynulá integrace kvantových procesorů s klasickou superpočítačovou infrastrukturou.

::bullets::
- Kvantově-klasické hybridní algoritmy
- Kvantová optimalizace (logistika, finance, průmyslové plánování)
- Kvantová chemie a simulace materiálů na atomární úrovni
- Kvantové strojové učení
- Kvantové softwarové stacky a techniky zmírňování chyb

---
layout: topic
transition: slide-left
title: Umělá inteligence, digitalizace a kyberneticko-fyzikální systémy
image: ./topic-06-p.jpg
contactPhoto: ./platos.jpg
contactName: 'prof. Ing. Jan Platoš, Ph.D.'
---

::annotation::
Digitální transformace světa prostřednictvím dat. Zaměřujeme se na zpracování extrémních objemů dat, superpočítačové simulace a aplikovanou umělou inteligenci, která mění průmysl i společnost.

::bullets::
- High Performance Computing a kvantové počítání
- Strojové učení, neuronové sítě a umělá inteligence
- Digitální dvojčata pro simulaci procesů
- Internet věcí a komunikační sítě 5G/6G
- Pokročilá vizualizace a analýza velkých dat

---
layout: topic
transition: slide-left
title: Čipové technologie a polovodičové systémy
image: ./topic-01-p.jpg
contactPhoto: ./skotnicova.jpg
contactName: 'doc. Ing. Kateřina Skotnicová, Ph.D.'
---

::annotation::
Reakce na globální nedostatek čipů a evropskou snahu o technologickou suverenitu. Zaměřujeme se na celý hodnotový řetězec, od návrhu architektury integrovaných obvodů až po vývoj nových materiálů a testování výkonové elektroniky pro automobilový a energetický průmysl.

::bullets::
- Návrh a validace integrovaných obvodů
- Výkonová elektronika a nové substráty (GaN, SiC)
- Mikrosystémy a senzory pro extrémní prostředí
- Pokročilé pouzdření a heterogenní integrace
- Čisté prostory a technologie výroby polovodičů

---
layout: topic
transition: slide-left
title: Pokročilé materiály a materiálové technologie
image: ./topic-07-p.jpg
contactPhoto: ./zboril.jpg
contactName: 'prof. RNDr. Radek Zbořil, Ph.D.'
---

::annotation::
Výzkum na hranici fyzikálních možností. Vyvíjíme materiály s unikátními vlastnostmi pro extrémní podmínky, energetiku a medicínu — od atomární struktury až po průmyslovou výrobu.

::bullets::
- Nanomateriály a nanotechnologie
- Materiály pro ukládání energie a vodík
- Aditivní výroba (3D tisk) kovů a polymerů
- Biodegradabilní a biokompatibilní materiály
- Vývoj kompozitů a materiálů pro extrémní zatížení

---
layout: topic
transition: slide-left
title: Robotika, automatizace a Průmysl 4.0
image: ./topic-08-p.jpg
contactPhoto: ./mahdal.jpg
contactName: 'doc. Ing. Miroslav Mahdal, Ph.D.'
---

::annotation::
Budoucnost výroby. Nahrazujeme manuální práci inteligentními stroji, které spolupracují s lidmi (kolaborativní robotika) a činí nezávislá rozhodnutí na základě dat.

::bullets::
- Průmyslová a servisní robotika
- Mechatronika a řídicí systémy
- Prediktivní údržba a diagnostika
- Plně automatizované výrobní linky
- Interakce člověka s robotem (kobotika)

---
layout: topic
transition: slide-left
title: Vesmírné technologie a průzkum
image: ./topic-02-p.jpg
contactPhoto: ./martinek.jpg
contactName: 'prof. Ing. Radek Martinek, Ph.D.'
---

::annotation::
Pod vedením FEI vysílá univerzita experimenty na Mezinárodní vesmírnou stanici (ISS) v rámci misí Evropské vesmírné agentury (ESA). Náš výzkum integruje nanorobotiku, biomedicínu a senzoriku pro špičkový aplikovaný výzkum ve vesmíru.

::bullets::
- Orbitální nanorobotika (CONREX – první takový orbitální experiment na světě)
- Inteligentní monitorování zdraví astronautů (projekt ISS T-shirt)
- Hardware pro mikrosatelity a palubní systémy satelitů
- Zpracování dat z pozorování Země pomocí superpočítačů
- Materiály odolné vůči kosmickému záření a extrémním teplotám
- Pokročilé zpracování signálů
- Inteligentní analýza dat

---
layout: topic
transition: slide-left
title: Obranné technologie a technologie dvojího užití
image: ./topic-03-p.jpg
contactPhoto: ./jan_necas.jpg
contactName: 'prof. Ing. Jan Nečas, Ph.D.'
---

::annotation::
Výzkum zaměřený na zvyšování národní odolnosti a bezpečnosti v rámci programů NATO, DIANA a Evropského obranného fondu. Vyvíjíme autonomní systémy sloužící záchranným složkám i moderní obraně — od AI dronů po těžkou techniku na vodíkový pohon.

::bullets::
- Zpracování dat z rojů dronů pomocí umělé inteligence
- Vodíková těžká vozidla s dálkovým ovládáním a autonomním řízením
- Automatická detekce, klasifikace a lokalizace objektů v reálném čase
- Kybernetická obrana a ochrana kritické infrastruktury
- Materiály pro balistickou ochranu a maskování

---
layout: topic
transition: slide-left
title: Chytrá mobilita a dopravní systémy
image: ./topic-10-p.jpg
contactPhoto: ./simonik.jpg
contactName: 'doc. Ing. Petr Šimoník, Ph.D.'
---

::annotation::
Revoluce v pohybu osob a zboží. Vyvíjíme vozidla budoucnosti a systémy, které řídí městskou dopravu efektivně, bezpečně a autonomně.

::bullets::
- Autonomní řízení a systémy vozidel
- Elektromobilita a alternativní pohony
- Logistika a telematika
- Konstrukce dopravních prostředků (např. Formula Student)
- Inteligentní dopravní systémy pro chytrá města

---
layout: topic
transition: slide-left
title: Udržitelná energetika a environmentální technologie
image: ./topic-05-p.jpg
contactPhoto: ./misak.jpg
contactName: 'prof. Ing. Stanislav Mišák, Ph.D.'
---

::annotation::
Komplexní přístup k energetice — od těžby a zpracování surovin přes efektivní výrobu a akumulaci energie až po minimalizaci dopadů na životní prostředí. Řešíme energetickou soběstačnost, přechod na nízkoemisní a obnovitelné zdroje, využití druhotných surovin a pokročilé technologie pro ochranu ovzduší a vod.

::bullets::
- Obnovitelné zdroje energie, vodíkové technologie a využití biomasy
- Dekontaminace, čištění odpadních plynů a úprava povrchových a odpadních vod
- Dekarbonizace průmyslu, zachycování a využití CO₂
- Recyklace, cirkulární ekonomika a využití odpadů (waste-to-energy)
- Akumulace energie a Smart Grids
- Kritické suroviny a udržitelná těžba

---
layout: topic
transition: slide-left
title: Bezpečnost a společenská resilience
image: ./topic-09-p.jpg
contactPhoto: ./jankuj.jpg
contactName: 'Ing. Vojtěch Jankůj, Ph.D.'
---

::annotation::
Ochrana životů, infrastruktury a dat. Zkoumáme, jak předcházet katastrofám (požáry, výbuchy, kyberútoky) a jak zajistit, aby společnost i technologie odolaly krizovým situacím.

::bullets::
- Požární inženýrství a průmyslová bezpečnost
- Ochrana kritické infrastruktury a obranný výzkum
- Kybernetická bezpečnost a krizové řízení
- Resilience území a environmentální rizika
- Sociální resilience a ochrana obyvatelstva

---
layout: topic
transition: slide-left
title: Biomedicínské inženýrství a zdraví
image: ./topic-11-p.jpg
contactPhoto: ./kahankova.jpg
contactName: 'doc. Ing. Radana Vilímková Kahánková, Ph.D.'
---

::annotation::
Technologie ve službách zdraví. Spojujeme inženýrství s medicínou pro vývoj nových diagnostických metod, senzorů, nanorobotů a rehabilitačních pomůcek.

::bullets::
- Biomedicínské senzory a zpracování signálů
- Nanorobotika pro cílenou distribuci léčiv
- Biomechanika a asistenční technologie
- Analýza lékařských dat a telemedicína
- Chytré implantáty a chirurgické robotické systémy

---
layout: topic
transition: slide-left
title: Ekonomika, management a rozhodování
image: ./topic-12-p.jpg
contactPhoto: ./melecky.jpg
contactName: 'doc. Ing. Aleš Melecký, Ph.D.'
---

::annotation::
Mozek a nervová soustava inovací. Poskytujeme nástroje pro efektivní řízení firem i státu, analyzujeme ekonomické dopady technologií a optimalizujeme rozhodovací procesy v nejisté době.

::bullets::
- Strategické řízení a optimalizace procesů
- Finanční modelování a analýza rizik
- Ekonomika energetiky a klimatických změn
- Behaviorální ekonomie a management
- Analýza dopadů nových technologií na trh práce

---
transition: slide-left
title: Poděkování
---

<div class="absolute inset-0">
  <img src="./last.jpg" class="w-full h-full object-cover" />
  <div class="absolute inset-0 bg-black/25"></div>
</div>
<div class="absolute inset-x-0 top-0 flex flex-col items-center pt-16 pb-10">
  <div class="bg-black/50 backdrop-blur-sm rounded-2xl px-12 py-8 flex flex-col items-center gap-5">
    <h1 class="text-6xl font-extrabold text-white tracking-wide">Děkuji za pozornost</h1>
    <div class="w-24 h-1 rounded bg-[#00A499]"></div>
    <p class="text-xl text-neutral-100">Prototyp webových stránek naleznete na </p>
    <a href="https://www.janplatos.cz/vav/" class="text-[#00A499] text-2xl font-semibold hover:underline">www.janplatos.cz/vav</a>
  </div>
</div>