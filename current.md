---
layout: default
title: People
---

<!-- 1. PI Section (权威感布局：左图右文) -->
<div class="flex flex-col md:flex-row gap-10 items-start mb-20 border-b border-slate-100 pb-16">
    <!-- 头像卡片 -->
    <div class="w-full md:w-1/3 flex-shrink-0">
        <div class="bg-white p-4 rounded-lg shadow-sm border border-slate-100">
            <div class="aspect-[3/4] overflow-hidden rounded-md mb-4">
                <img src="./pics/people/Meds_for_all.jpg" alt="Prof. Todd" class="w-full h-full object-cover hover:scale-105 transition duration-500">
            </div>
            <h3 class="text-xl font-bold text-brand-dark mb-1">Prof. Matthew Todd</h3>
            <p class="text-brand-primary font-medium text-sm uppercase tracking-wider mb-4">Principal Investigator</p>
            
            <!-- 社交图标 -->
            <div class="flex gap-4 text-slate-400">
                <a href="https://www.linkedin.com/in/matthew-todd-81633313/" class="hover:text-brand-primary transition"><i class="fab fa-linkedin text-xl"></i></a>
                <a href="https://twitter.com/MatToddChem" class="hover:text-brand-primary transition"><i class="fab fa-twitter text-xl"></i></a>
                <a href="https://github.com/mattodd" class="hover:text-brand-primary transition"><i class="fab fa-github text-xl"></i></a>
                <a href="mailto:matthew.todd@ucl.ac.uk" class="hover:text-brand-primary transition"><i class="fas fa-envelope text-xl"></i></a>
            </div>
        </div>
    </div>

    <!-- 介绍文字 -->
    <div class="w-full md:w-2/3 prose prose-slate text-slate-600">
        <p>
            Mat Todd was born in Manchester, England. He was educated at Cambridge University where he obtained an MA in Natural Sciences in 1995 and a PhD in organic chemistry in 1999. He was then a Wellcome Trust postdoc at UC Berkeley, a College Fellow at Cambridge University, and a Lecturer at Queen Mary, University of London. Between 2005 and 2018 he was at the School of Chemistry, The University of Sydney. He is now Professor and Chair of Drug Discovery at University College London (2018-present).
        </p>
        <p>
            He has a significant interest in open science, and how it may be used to accelerate research, with particular emphasis on open source discovery of new medicines. He founded and currently leads several open science consortia such as <a href="http://opensourcemalaria.org/">Open Source Malaria (OSM)</a> and is a founder of a broader Open Source Pharma movement.
        </p>
        <p class="font-serif italic text-brand-dark border-l-4 border-brand-primary pl-4 bg-slate-50 py-2">
            Lab Motto: "To make the right molecule in the right place at the right time."
        </p>
    </div>
</div>


<!-- 2. Postdoc Team (网格布局) -->
<div class="mb-20">
    <h2 class="text-2xl font-bold text-brand-dark mb-8 flex items-center gap-3">
        <span class="w-8 h-1 bg-brand-primary rounded-full"></span>
        Postdoctoral Research Associates
    </h2>

    <!-- Grid Container: 自动对齐的神器 -->
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        
        <!-- Member Card 1 -->
        <div class="group bg-white rounded-lg border border-slate-100 overflow-hidden hover:shadow-xl hover:-translate-y-1 transition-all duration-300">
            <div class="aspect-square overflow-hidden">
                <img src="./pics/people/Eve.jpg" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
            </div>
            <div class="p-6 text-center">
                <h4 class="text-lg font-bold text-brand-dark">Dr Eve Carter</h4>
                <p class="text-sm text-slate-500 mb-4">Postdoc (UCL) • 2022-present</p>
                <div class="flex justify-center gap-4 text-slate-400">
                    <a href="https://github.com/EveCarter" class="hover:text-brand-primary"><i class="fab fa-github"></i></a>
                    <a href="mailto:eve.carter@ucl.ac.uk" class="hover:text-brand-primary"><i class="fas fa-envelope"></i></a>
                </div>
            </div>
        </div>

        <!-- Member Card 2 -->
        <div class="group bg-white rounded-lg border border-slate-100 overflow-hidden hover:shadow-xl hover:-translate-y-1 transition-all duration-300">
            <div class="aspect-square overflow-hidden">
                <img src="./pics/people/Rebecka_Isaksson2.jpg" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
            </div>
            <div class="p-6 text-center">
                <h4 class="text-lg font-bold text-brand-dark">Dr Rebecka Isaksson</h4>
                <p class="text-sm text-slate-500 mb-4">Postdoc (UCL) • 2023-present</p>
                <div class="flex justify-center gap-4 text-slate-400">
                    <a href="#" class="hover:text-brand-primary"><i class="fab fa-twitter"></i></a>
                    <a href="mailto:r.isaksson@ucl.ac.uk" class="hover:text-brand-primary"><i class="fas fa-envelope"></i></a>
                </div>
            </div>
        </div>

        <!-- Member Card 3 -->
        <div class="group bg-white rounded-lg border border-slate-100 overflow-hidden hover:shadow-xl hover:-translate-y-1 transition-all duration-300">
            <div class="aspect-square overflow-hidden bg-slate-100 flex items-center justify-center">
                <!-- 还没有照片时的占位符 -->
                <img src="./pics/people/DanielleHanke.jpg" class="w-full h-full object-cover group-hover:scale-105 transition duration-500" onerror="this.style.display='none'; this.nextElementSibling.style.display='block'">
                <i class="fas fa-user text-4xl text-slate-300 hidden"></i>
            </div>
            <div class="p-6 text-center">
                <h4 class="text-lg font-bold text-brand-dark">Dr Danielle Hanke</h4>
                <p class="text-sm text-slate-500 mb-4">Postdoc (UCL) • 2025-present</p>
                <div class="flex justify-center gap-4 text-slate-400">
                    <a href="mailto:example@ucl.ac.uk" class="hover:text-brand-primary"><i class="fas fa-envelope"></i></a>
                </div>
            </div>
        </div>

    </div>
</div>

<!-- 3. PhD Students (复制上面的结构即可) -->
<div class="mb-20">
    <h2 class="text-2xl font-bold text-brand-dark mb-8 flex items-center gap-3">
        <span class="w-8 h-1 bg-brand-primary rounded-full"></span>
        PhD Students
    </h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        
        <!-- Student Card Example -->
        <div class="group bg-white rounded-lg border border-slate-100 overflow-hidden hover:shadow-lg transition-all">
            <div class="aspect-square overflow-hidden">
                <img src="./pics/people/Yuhang_Wang3.jpg" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
            </div>
            <div class="p-4 text-center">
                <h4 class="font-bold text-brand-dark">Yuhang Wang</h4>
                <p class="text-xs text-slate-500 mb-3">PhD Student • 2019-present</p>
                <div class="flex justify-center gap-3 text-slate-400 text-sm">
                    <a href="#" class="hover:text-brand-primary"><i class="fab fa-linkedin"></i></a>
                    <a href="#" class="hover:text-brand-primary"><i class="fas fa-envelope"></i></a>
                </div>
            </div>
        </div>
        
        <!-- 这里继续复制粘贴其他学生... -->

    </div>
</div>
