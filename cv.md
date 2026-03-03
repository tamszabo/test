---
layout: default
title: Resume
permalink: /cv/
---

<div class="flex justify-between items-center mb-8 pb-4 border-b border-slate-800">
    <h1 class="text-3xl font-black text-white uppercase tracking-tighter">
        Curriculum <span class="text-indigo-500">Vitae</span>
    </h1>
    <button onclick="window.print()" class="text-xs font-bold uppercase tracking-widest text-slate-500 hover:text-indigo-400 transition">
        Print to PDF 📄
    </button>
</div>

<section class="mb-12">
    <h2 class="text-xl font-bold text-white mb-4">Tamas Szabo</h2>
    <p class="text-slate-400 leading-relaxed italic border-l-2 border-indigo-500 pl-4">
        Senior Data Analyst with over 8 years of experience driving executive decision-making within international corporate environments. Proven track record of translating complex datasets into actionable business insights.
    </p>
</section>

<section class="space-y-10">
    <h2 class="text-xs font-black uppercase tracking-[0.2em] text-indigo-500 mb-6">Professional Experience</h2>
    <div class="relative pl-12">
        <div class="absolute left-0 top-1 w-10 h-10 bg-white rounded-lg p-1 border border-slate-700">
            <img src="{{ '/assets/images/hyundai-logo.png' | relative_url }}" alt="Hyundai" class="w-full h-full object-contain">
        </div>
        <div class="flex flex-col md:flex-row md:justify-between md:items-baseline mb-2">
            <h3 class="text-lg font-bold text-white">Hyundai Motor Europe</h3>
            <span class="text-sm font-mono text-slate-500">10/2023 — 07/2025</span>
        </div>
        <p class="text-indigo-400 text-sm font-semibold mb-3">Senior Data Analyst | Frankfurt am Main</p>
        <ul class="list-disc list-outside ml-4 space-y-1 text-slate-400 text-sm">
            <li><strong>Executive Insights:</strong> Engineered a comprehensive C-suite sales funnel report from SAP, Siebel, and GA4 datasets.</li>
            <li><strong>Infrastructure:</strong> Orchestrated a Tableau Server migration resulting in significant speed increases.</li>
            <li><strong>Leadership:</strong> Launched a Tableau mentorship program, increasing regional data literacy.</li>
        </ul>
    </div>
    <div class="relative pl-12">
        <div class="absolute left-0 top-1 w-10 h-10 bg-slate-800 rounded-lg p-1 border border-slate-700">
            <img src="{{ '/assets/images/starschema-logo.png' | relative_url }}" alt="Starschema" class="w-full h-full object-contain">
        </div>
        <div class="flex flex-col md:flex-row md:justify-between md:items-baseline mb-2">
            <h3 class="text-lg font-bold text-white">Starschema</h3>
            <span class="text-sm font-mono text-slate-500">12/2019 — 09/2023</span>
        </div>
        <p class="text-indigo-400 text-sm font-semibold mb-3">Data Analyst | Budapest, Hungary</p>
        <ul class="list-disc list-outside ml-4 space-y-1 text-slate-400 text-sm">
            <li>Consulted for global giants including <strong>Apple, GE, and BlackRock</strong>.</li>
            <li><strong>Strategic Win:</strong> Led a sports analytics POC that secured the <strong>Los Angeles Rams</strong> as a client.</li>
            <li>Implemented global KPI frameworks ensuring 100% transparency in international reporting.</li>
        </ul>
    </div>
    <div class="relative pl-12">
        <div class="absolute left-0 top-1 w-10 h-10 bg-white rounded-lg p-1 border border-slate-700">
            <img src="{{ '/assets/images/intrum-logo.png' | relative_url }}" alt="Intrum" class="w-full h-full object-contain">
        </div>
        <div class="flex flex-col md:flex-row md:justify-between md:items-baseline mb-2">
            <h3 class="text-lg font-bold text-white">Intrum</h3>
            <span class="text-sm font-mono text-slate-500">07/2017 — 11/2019</span>
        </div>
        <p class="text-indigo-400 text-sm font-semibold mb-3">Business Intelligence Analyst | Budapest, Hungary</p>
        <ul class="list-disc list-outside ml-4 space-y-1 text-slate-400 text-sm">
            <li>Deep-dive cost analysis leading to the strategic discontinuation of a major business line.</li>
            <li>Mentored C-suite stakeholders on BI best practices to drive data-driven decision-making.</li>
        </ul>
    </div>
</section>

<div class="grid grid-cols-1 md:grid-cols-2 gap-12 mt-16 pt-10 border-t border-slate-800">
    <section>
        <h2 class="text-xs font-black uppercase tracking-[0.2em] text-indigo-500 mb-4">Education</h2>
        <h3 class="text-white font-bold">BSc in Mathematics</h3>
        <p class="text-slate-500 text-sm italic">Eötvös Loránd University | 2016</p>
    </section>
    <section>
        <h2 class="text-xs font-black uppercase tracking-[0.2em] text-indigo-500 mb-4">Certificates</h2>
        <div class="flex items-center gap-3">
            <img src="{{ '/assets/images/tableau-specialist.png' | relative_url }}" class="w-8 h-8 opacity-80" alt="Tableau">
            <p class="text-white font-bold text-sm">Tableau Desktop Specialist (2023)</p>
        </div>
    </section>
</div>
