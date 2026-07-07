---
theme: default
background: title.jpg
class: text-center my-auto
highlighter: shiki
transition: slide-left
title: University Research Directions
---

<div class="bg-black/15 p-5 rounded-lg backdrop-blur-sm inline-block">
  <h1 class="text-4xl font-extrabold text-white tracking-wide uppercase">University Research Directions</h1>
  <h2 class="text-xl font-extrabold text-white tracking-wide uppercase">Working Version</h2>
</div>

---
transition: slide-left
style: 'background: #0f0f0f'
title: Four Research Pillars
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
      <p class="text-white font-extrabold text-sm leading-snug mb-2">Digital Transformation, AI & Supercomputing</p>
      <p class="text-[#00A499] text-[9px] uppercase tracking-widest font-semibold leading-relaxed">HPC · Quantum Computing · AI · Big Data</p>
    </div>
  </div>

  <div class="pillar flex-1 relative overflow-hidden border-r border-white/10 group">
    <img src="./top/02p.png" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 ease-out group-hover:scale-105" />
    <div class="absolute inset-0 bg-gradient-to-t from-black/92 via-black/20 to-black/50"></div>
    <div class="accent-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
    <div class="absolute top-3 left-4 font-black leading-none text-[#00A499] opacity-[0.12] select-none" style="font-size: 6.5rem;">02</div>
    <div class="pillar-label absolute inset-x-0 bottom-0 px-5 pb-6">
      <div class="w-6 h-px bg-[#00A499] mb-3"></div>
      <p class="text-white font-extrabold text-sm leading-snug mb-2">Advanced Materials, Semiconductors & Microsystems</p>
      <p class="text-[#00A499] text-[9px] uppercase tracking-widest font-semibold leading-relaxed">Chips · GaN/SiC · Nanomaterials · 3D Printing</p>
    </div>
  </div>

  <div class="pillar flex-1 relative overflow-hidden border-r border-white/10 group">
    <img src="./top/03p.png" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 ease-out group-hover:scale-105" />
    <div class="absolute inset-0 bg-gradient-to-t from-black/92 via-black/20 to-black/50"></div>
    <div class="accent-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
    <div class="absolute top-3 left-4 font-black leading-none text-[#00A499] opacity-[0.12] select-none" style="font-size: 6.5rem;">03</div>
    <div class="pillar-label absolute inset-x-0 bottom-0 px-5 pb-6">
      <div class="w-6 h-px bg-[#00A499] mb-3"></div>
      <p class="text-white font-extrabold text-sm leading-snug mb-2">Autonomous Systems, Robotics & Smart Mobility</p>
      <p class="text-[#00A499] text-[9px] uppercase tracking-widest font-semibold leading-relaxed">Robotics · Drones · Space · Autonomous Vehicles</p>
    </div>
  </div>

  <div class="pillar flex-1 relative overflow-hidden group">
    <img src="./top/04p.png" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 ease-out group-hover:scale-105" />
    <div class="absolute inset-0 bg-gradient-to-t from-black/92 via-black/20 to-black/50"></div>
    <div class="accent-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
    <div class="absolute top-3 left-4 font-black leading-none text-[#00A499] opacity-[0.12] select-none" style="font-size: 6.5rem;">04</div>
    <div class="pillar-label absolute inset-x-0 bottom-0 px-5 pb-6">
      <div class="w-6 h-px bg-[#00A499] mb-3"></div>
      <p class="text-white font-extrabold text-sm leading-snug mb-2">Sustainability, Security & Societal Health</p>
      <p class="text-[#00A499] text-[9px] uppercase tracking-widest font-semibold leading-relaxed">Energy · Security · Biomedicine · Economics</p>
    </div>
  </div>

</div>

---
transition: slide-left
style: 'background: #111'
title: Pillar 01 – Digital Transformation, AI & Supercomputing
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
      <span class="text-[#00A499] text-[9px] font-bold uppercase tracking-[0.3em]">Pillar 01</span>
      <h2 class="text-white font-extrabold leading-snug mt-2 mb-3" style="font-size: 24px; line-height: 1.4;">Digital Transformation, AI & Supercomputing</h2>
      <div class="w-8 h-px bg-[#00A499] mb-3"></div>
      <p class="text-neutral-400 text-[11px] leading-relaxed">The university's digital and computing core driving modern industry and science.</p>
    </div>
    <div class="relative z-10">
      <p class="text-[9px] text-neutral-600 uppercase tracking-widest">2 research clusters</p>
    </div>
  </div>

  <div class="flex-1 flex">
    <div class="pi1-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-04-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi1-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-4 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">1.1</div>
      <div class="absolute inset-x-0 bottom-0 px-5 pb-7">
        <p class="text-white font-extrabold text-xl leading-snug mb-4" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">High-Performance & Quantum Computing</p>
        <div class="flex flex-wrap gap-1.5">
          <span class="text-[9px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-2 py-0.5">HPC</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Quantum Optimisation</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">LUMI-Q</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Quantum ML</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Material Simulation</span>
        </div>
      </div>
    </div>
    <div class="pi1-card flex-1 relative overflow-hidden">
      <img src="./topic-06-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi1-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-4 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">1.2</div>
      <div class="absolute inset-x-0 bottom-0 px-5 pb-7">
        <p class="text-white font-extrabold text-xl leading-snug mb-4" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Applied AI & Data Analytics</p>
        <div class="flex flex-wrap gap-1.5">
          <span class="text-[9px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-2 py-0.5">AI & ML</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Digital Twins</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">5G / 6G</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Big Data</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Neural Networks</span>
        </div>
      </div>
    </div>
  </div>

</div>

---
transition: slide-left
style: 'background: #111'
title: Pillar 02 – Advanced Materials, Semiconductors & Microsystems
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
      <span class="text-[#00A499] text-[9px] font-bold uppercase tracking-[0.3em]">Pillar 02</span>
      <h2 class="text-white font-extrabold leading-snug mt-2 mb-3" style="font-size: 24px; line-height: 1.4;">Advanced Materials, Semiconductors & Microsystems</h2>
      <div class="w-8 h-px bg-[#00A499] mb-3"></div>
      <p class="text-neutral-400 text-[11px] leading-relaxed">Materials research from atomic structure to final hardware components.</p>
    </div>
    <div class="relative z-10">
      <p class="text-[9px] text-neutral-600 uppercase tracking-widest">2 research clusters</p>
    </div>
  </div>

  <div class="flex-1 flex">
    <div class="pi2-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-01-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi2-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-4 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">2.1</div>
      <div class="absolute inset-x-0 bottom-0 px-5 pb-7">
        <p class="text-white font-extrabold text-xl leading-snug mb-4" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Chip Technologies & Semiconductor Systems</p>
        <div class="flex flex-wrap gap-1.5">
          <span class="text-[9px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-2 py-0.5">IC Design</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">GaN / SiC</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Microsystems</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Clean Rooms</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Heterogeneous Integration</span>
        </div>
      </div>
    </div>
    <div class="pi2-card flex-1 relative overflow-hidden">
      <img src="./topic-07-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi2-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-4 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">2.2</div>
      <div class="absolute inset-x-0 bottom-0 px-5 pb-7">
        <p class="text-white font-extrabold text-xl leading-snug mb-4" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Advanced Materials & Nanotechnology</p>
        <div class="flex flex-wrap gap-1.5">
          <span class="text-[9px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-2 py-0.5">Nanomaterials</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Metal 3D Printing</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Biodegradable Mat.</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Composites</span>
          <span class="text-[9px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-2 py-0.5">Energy Storage</span>
        </div>
      </div>
    </div>
  </div>

</div>

---
transition: slide-left
style: 'background: #111'
title: Pillar 03 – Autonomous Systems, Robotics & Smart Mobility
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
      <span class="text-[#00A499] text-[9px] font-bold uppercase tracking-[0.3em]">Pillar 03</span>
      <h2 class="text-white font-extrabold leading-snug mt-2 mb-3" style="font-size: 24px; line-height: 1.4;">Autonomous Systems, Robotics & Smart Mobility</h2>
      <div class="w-8 h-px bg-[#00A499] mb-3"></div>
      <p class="text-neutral-400 text-[10px] leading-relaxed">Intelligent machines and transport systems changing the way we move on land, in the air, and in space.</p>
    </div>
    <div class="relative z-10">
      <p class="text-[9px] text-neutral-600 uppercase tracking-widest">4 research clusters</p>
    </div>
  </div>

  <div class="flex-1 flex">
    <div class="pi3-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-08-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi3-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">3.1</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Robotics & Industry 4.0</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Industrial Robotics</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Mechatronics</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Predictive Maintenance</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Cobotics</span>
        </div>
      </div>
    </div>
    <div class="pi3-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-02-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi3-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">3.2</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Space Technologies</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">CONREX / ISS</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Microsatellites</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Nanorobotics</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Earth Observation</span>
        </div>
      </div>
    </div>
    <div class="pi3-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-03-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi3-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">3.3</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Defence Technologies</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Drone Swarms</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Autonomous Vehicles</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Cyber Defence</span>
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
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Smart Mobility</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Autonomous Driving</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Electromobility</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Telematics</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Smart Cities</span>
        </div>
      </div>
    </div>
  </div>

</div>

---
transition: slide-left
style: 'background: #111'
title: Pillar 04 – Sustainability, Security & Societal Health
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
      <span class="text-[#00A499] text-[9px] font-bold uppercase tracking-[0.3em]">Pillar 04</span>
      <h2 class="text-white font-extrabold leading-snug mt-2 mb-3" style="font-size: 24px; line-height: 1.4;">Sustainability, Security & Societal Health</h2>
      <div class="w-8 h-px bg-[#00A499] mb-3"></div>
      <p class="text-neutral-400 text-[10px] leading-relaxed">Interdisciplinary research focused on protecting lives, planetary health, and economic resilience.</p>
    </div>
    <div class="relative z-10">
      <p class="text-[9px] text-neutral-600 uppercase tracking-widest">4 research clusters</p>
    </div>
  </div>

  <div class="flex-1 flex">
    <div class="pi4-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-05-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi4-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">4.1</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Sustainable Energy</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Renewable Energy</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Hydrogen</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Smart Grids</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Circular Economy</span>
        </div>
      </div>
    </div>
    <div class="pi4-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-09-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi4-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">4.2</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Security & Resilience</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Fire Engineering</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Critical Infrastructure</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Cybersecurity</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Crisis Management</span>
        </div>
      </div>
    </div>
    <div class="pi4-card flex-1 relative overflow-hidden border-r border-white/10">
      <img src="./topic-11-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi4-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">4.3</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Biomedical Engineering</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Biosensors</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Nanorobotics</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Telemedicine</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Assistive Tech.</span>
        </div>
      </div>
    </div>
    <div class="pi4-card flex-1 relative overflow-hidden">
      <img src="./topic-12-p.jpg" class="absolute top-0 left-0 w-full object-cover" style="height: 110%;" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/10 to-black/40"></div>
      <div class="pi4-bar absolute top-0 inset-x-0 h-[3px] bg-[#00A499]"></div>
      <div class="absolute top-4 left-3 bg-[#00A499] text-black text-[8px] font-black uppercase tracking-[0.2em] px-1.5 py-0.5">4.4</div>
      <div class="absolute inset-x-0 bottom-0 px-4 pb-6">
        <p class="text-white font-extrabold text-base leading-snug mb-3" style="text-shadow: 0 2px 10px rgba(0,0,0,0.9);">Economics & Management</p>
        <div class="flex flex-wrap gap-1">
          <span class="text-[8px] font-bold uppercase tracking-wider text-black bg-[#00A499] px-1.5 py-0.5">Strategic Management</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Fin. Modelling</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Climate Economics</span>
          <span class="text-[8px] font-bold uppercase tracking-wider text-[#00A499] border border-[#00A499]/60 px-1.5 py-0.5">Impact Analysis</span>
        </div>
      </div>
    </div>
  </div>

</div>

---
layout: topic
transition: slide-left
title: Quantum Computing & Hybrid HPC Systems
image: ./topic-04-p.jpg
contactPhoto: ./kozubek.jpg
contactName: 'prof. Ing. Tomáš Kozubek, Ph.D.'
---

::annotation::
We are pushing the boundaries of high-performance computing into the era of quantum acceleration. We leverage the cutting-edge superconducting LUMI-Q system and focus on developing the software stack and quantum algorithms. Our research aims for seamless integration of quantum processors with classical supercomputing infrastructure.

::bullets::
- Quantum-classical hybrid algorithms
- Quantum optimisation (logistics, finance, industrial planning)
- Quantum chemistry and atomic-level material simulation
- Quantum machine learning
- Quantum software stacks and error mitigation techniques

---
layout: topic
transition: slide-left
title: Artificial Intelligence, Digitalisation & Cyber-Physical Systems
image: ./topic-06-p.jpg
contactPhoto: ./platos.jpg
contactName: 'prof. Ing. Jan Platoš, Ph.D.'
---

::annotation::
Transforming the world digitally through data. We focus on processing extreme volumes of data, supercomputer simulations, and applied artificial intelligence that is reshaping industry and society.

::bullets::
- High Performance Computing and quantum computing
- Machine learning, neural networks, and artificial intelligence
- Digital twins for process simulation
- Internet of Things and 5G/6G communication networks
- Advanced visualisation and big data analytics

---
layout: topic
transition: slide-left
title: Chip Technologies & Semiconductor Systems
image: ./topic-01-p.jpg
contactPhoto: ./skotnicova.jpg
contactName: 'doc. Ing. Kateřina Skotnicová, Ph.D.'
---

::annotation::
A response to the global chip shortage and Europe's drive for technological sovereignty. We cover the full value chain, from IC architecture design to novel material development and power electronics testing for the automotive and energy sectors.

::bullets::
- Design and validation of integrated circuits
- Power electronics and novel substrates (GaN, SiC)
- Microsystems and sensors for extreme environments
- Advanced packaging and heterogeneous integration
- Clean rooms and semiconductor manufacturing technologies

---
layout: topic
transition: slide-left
title: Advanced Materials & Materials Technologies
image: ./topic-07-p.jpg
contactPhoto: ./zboril.jpg
contactName: 'prof. RNDr. Radek Zbořil, Ph.D.'
---

::annotation::
Research at the limits of what is physically possible. We develop materials with unique properties for extreme conditions, energy applications, and medicine — from atomic structure to industrial production.

::bullets::
- Nanomaterials and nanotechnology
- Materials for energy storage and hydrogen
- Additive manufacturing (3D printing) of metals and polymers
- Biodegradable and biocompatible materials
- Development of composites and materials for extreme loading

---
layout: topic
transition: slide-left
title: Robotics, Automation & Industry 4.0
image: ./topic-08-p.jpg
contactPhoto: ./mahdal.jpg
contactName: 'doc. Ing. Miroslav Mahdal, Ph.D.'
---

::annotation::
The future of manufacturing. We replace manual labour with intelligent machines that collaborate with people (collaborative robotics) and make independent data-driven decisions.

::bullets::
- Industrial and service robotics
- Mechatronics and control systems
- Predictive maintenance and diagnostics
- Fully automated production lines
- Human-robot interaction (cobotics)

---
layout: topic
transition: slide-left
title: Space Technologies & Exploration
image: ./topic-02-p.jpg
contactPhoto: ./martinek.jpg
contactName: 'prof. Ing. Radek Martinek, Ph.D.'
---

::annotation::
Under FEI's leadership, the university sends experiments to the International Space Station (ISS) as part of European Space Agency (ESA) missions. Our research integrates nanorobotics, biomedicine, and sensing for cutting-edge applied research in space.

::bullets::
- Orbital nanorobotics (CONREX – the world's first such orbital experiment)
- Intelligent astronaut health monitoring (ISS T-shirt project)
- Hardware for microsatellites and on-board satellite systems
- Processing Earth observation data using supercomputers
- Materials resistant to cosmic radiation and extreme temperatures
- Advanced signal processing
- Intelligent data analysis

---
layout: topic
transition: slide-left
title: Defence Technologies & Dual-Use Technologies
image: ./topic-03-p.jpg
contactPhoto: ./jan_necas.jpg
contactName: 'prof. Ing. Jan Nečas, Ph.D.'
---

::annotation::
Research aimed at enhancing national resilience and security within the NATO, DIANA, and European Defence Fund frameworks. We develop autonomous systems serving emergency services and modern defence — from AI drones to heavy hydrogen-powered vehicles.

::bullets::
- AI-powered processing of data from drone swarms
- Hydrogen-powered heavy vehicles with remote and autonomous control
- Automatic real-time detection, classification, and localisation of objects
- Cyber defence and protection of critical infrastructure
- Materials for ballistic protection and camouflage

---
layout: topic
transition: slide-left
title: Smart Mobility & Transport Systems
image: ./topic-10-p.jpg
contactPhoto: ./simonik.jpg
contactName: 'doc. Ing. Petr Šimoník, Ph.D.'
---

::annotation::
A revolution in the movement of people and goods. We develop vehicles of the future and systems that manage urban transport efficiently, safely, and autonomously.

::bullets::
- Autonomous driving and vehicle systems
- Electromobility and alternative powertrains
- Logistics and telematics
- Vehicle design and construction (e.g. Formula Student)
- Intelligent transport systems for smart cities

---
layout: topic
transition: slide-left
title: Sustainable Energy & Environmental Technologies
image: ./topic-05-p.jpg
contactPhoto: ./misak.jpg
contactName: 'prof. Ing. Stanislav Mišák, Ph.D.'
---

::annotation::
A comprehensive approach to energy — from resource extraction and processing through efficient production and energy storage to minimising environmental impact. We address energy self-sufficiency, the transition to low-emission and renewable sources, use of secondary raw materials, and advanced technologies for air and water protection.

::bullets::
- Renewable energy sources, hydrogen technologies, and biomass utilisation
- Decontamination, flue gas cleaning, and surface and waste water treatment
- Industry decarbonisation, CO₂ capture and utilisation
- Recycling, circular economy, and waste utilisation (waste-to-energy)
- Energy storage and Smart Grids
- Critical raw materials and sustainable mining

---
layout: topic
transition: slide-left
title: Safety, Security & Societal Resilience
image: ./topic-09-p.jpg
contactPhoto: ./jankuj.jpg
contactName: 'Ing. Vojtěch Jankůj, Ph.D.'
---

::annotation::
Protecting lives, infrastructure, and data. We investigate how to prevent disasters (fires, explosions, cyberattacks) and ensure that society and technology remain resilient in crisis situations.

::bullets::
- Fire engineering and industrial safety
- Critical infrastructure protection and defence research
- Cybersecurity and crisis management
- Territorial resilience and environmental risks
- Social resilience and civil protection

---
layout: topic
transition: slide-left
title: Biomedical Engineering & Health
image: ./topic-11-p.jpg
contactPhoto: ./kahankova.jpg
contactName: 'doc. Ing. Radana Vilímková Kahánková, Ph.D.'
---

::annotation::
Technology in service of health. We combine engineering with medicine to develop new diagnostic methods, sensors, nanorobots, and rehabilitation devices.

::bullets::
- Biomedical sensors and signal processing
- Nanorobotics for targeted drug delivery
- Biomechanics and assistive technologies
- Medical data analysis and telemedicine
- Smart implants and surgical robotic systems

---
layout: topic
transition: slide-left
title: Economics, Management & Decision-Making
image: ./topic-12-p.jpg
contactPhoto: ./melecky.jpg
contactName: 'doc. Ing. Aleš Melecký, Ph.D.'
---

::annotation::
The brain and nervous system of innovation. We provide tools for effective management of businesses and public institutions, analyse the economic impact of technologies, and optimise decision-making processes in uncertain times.

::bullets::
- Strategic management and process optimisation
- Financial modelling and risk analysis
- Energy and climate change economics
- Behavioural economics and management
- Analysis of the impact of new technologies on the labour market

---
transition: slide-left
title: Thank You
---

<div class="absolute inset-0">
  <img src="./last.jpg" class="w-full h-full object-cover" />
  <div class="absolute inset-0 bg-black/25"></div>
</div>
<div class="absolute inset-x-0 top-0 flex flex-col items-center pt-16 pb-10">
  <div class="bg-black/50 backdrop-blur-sm rounded-2xl px-12 py-8 flex flex-col items-center gap-5">
    <h1 class="text-6xl font-extrabold text-white tracking-wide">Thank you for your attention</h1>
    <div class="w-24 h-1 rounded bg-[#00A499]"></div>
    <p class="text-xl text-neutral-100">Prototype website available at</p>
    <a href="https://www.janplatos.cz/vav/" class="text-[#00A499] text-2xl font-semibold hover:underline">www.janplatos.cz/vav</a>
  </div>
</div>
