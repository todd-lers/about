---
layout: default
title: News
---


-->

<style>
    /* Accordion Transitions */
    .accordion-content {
        transition: grid-template-rows 0.3s ease-out, opacity 0.3s ease;
        display: grid;
        grid-template-rows: 0fr;
        opacity: 0;
    }
    .accordion-content.active {
        grid-template-rows: 1fr;
        opacity: 1;
    }
    .accordion-inner {
        overflow: hidden;
    }
    .chevron { transition: transform 0.3s ease; }
    .chevron.rotate { transform: rotate(180deg); }
    
    /* Image adjustments */
    .news-img {
        border-radius: 0.25rem; /* rounded-sm */
        box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* shadow-md */
        object-fit: cover;
    }
</style>

<div class="max-w-4xl mx-auto">
    
    <!-- Header Section -->
    <div class="mb-12 border-b border-slate-200 pb-8">
        <h1 class="text-4xl font-extrabold text-brand-dark mb-6">News</h1>
        <div class="flex flex-wrap gap-4 items-center justify-end">
            <div class="ml-auto flex gap-2">
                <button onclick="toggleAll(true)" class="text-xs font-bold text-brand-primary hover:text-brand-primary-dark uppercase tracking-wider">Expand All</button>
                <span class="text-slate-300">|</span>
                <button onclick="toggleAll(false)" class="text-xs font-bold text-slate-500 hover:text-slate-700 uppercase tracking-wider">Collapse All</button>
            </div>
        </div>
    </div>

    <!-- News List -->
    <div class="space-y-3" id="news-container">

        <!-- 2025 -->
        <div class="year-block group">
            <div onclick="toggleYear('2025')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2025</h2>
                <i id="icon-2025" class="fas fa-chevron-down text-slate-400 chevron rotate"></i>
            </div>
            <div id="content-2025" class="accordion-content active">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">July 31rd 2025</strong>
                            Yinuo passed her PhD Viva with minor corrections. Congrats Dr.Wang!
                            <div class="flex justify-center gap-3 flex-wrap mt-4">
                                <img src="./news items supporting info/Yinuoviva1.jpeg" class="w-[30%] news-img" alt="Yinuo Viva 1">
                                <img src="./news items supporting info/yinuoviva2.jpeg" class="w-[30%] news-img" alt="Yinuo Viva 2">
                                <img src="./news items supporting info/YinuoExaminers.jpg" class="w-[30%] news-img" alt="Yinuo Examiners">
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2024 -->
        <div class="year-block group">
            <div onclick="toggleYear('2024')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2024</h2>
                <i id="icon-2024" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2024" class="accordion-content active">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Dec 11th 2024</strong>
                            We head to the British Museum for the Silk Roads exhibition, then to the pub for a Science Jeopardy quiz.
                            <div class="flex justify-center gap-4 mt-4">
                                <img src="./news items supporting info/British Museum Trip 2024.jpg" class="w-1/2 news-img" alt="British Museum Trip">
                                <img src="./news items supporting info/Jeopardy Pub Quiz.jpg" class="w-1/2 news-img" alt="Jeopardy Pub Quiz">
                            </div>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Nov 5th 2024</strong>
                            Mat hosted an SGC-Industry event at the Wellcome Trust on the potential future impact of AI and machine learning on drug discovery, written up <a href="https://www.ucl.ac.uk/lifesciences-faculty/news/2024/dec/future-impact-machine-learning-drug-discovery" class="text-brand-primary font-bold hover:underline">here</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 19th 2024</strong>
                            Eve Carter featured in an <a href="https://www.thesgc.org/blogs/celebrating-impact-sgc-postdocs-open-science" class="text-brand-primary font-bold hover:underline">article</a> from the Structural Genomics Consortium celebrating Postdoc Appreciation Week.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 11th 2024</strong>
                            Congratulations to the group's cohort of MSc Drug Discovery and Pharma Management students (Xin, Annabella, Ulfa, Ryan, Natnaree and Marc) on their successful presentations and the end of their course! Good luck to them with whatever is next!
                            <div class="mt-4 flex justify-center">
                                <img src="./news items supporting info/MSc Drug Discovery2.jpeg" class="w-[40%] news-img" alt="MSc Students">
                            </div>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 5th 2024</strong>
                            Eve, Gui, Kangping, and Yinuo enjoyed presenting their work at the XXVIII EFMC International Symposium on Medicinal Chemistry (<a href="https://www.efmc-ismc.org/" class="text-brand-primary font-bold hover:underline">EFMC-ISMC 2024</a>), hosted in Rome, Italy.
                            <div class="mt-4 flex justify-center">
                                <img src="./news items supporting info/EFMC-ISMC2024.png" class="w-[75%] news-img" alt="EFMC Conference">
                            </div>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 2nd 2024</strong>
                            Mat features in a <a href="https://www.chemistryworld.com/careers/will-open-science-change-chemistry/4020023.article" class="text-brand-primary font-bold hover:underline">Chemistry World article</a> entitled "Will Open Science Change Chemistry?".
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">August 28th 2024</strong>
                            Hadia presented her research at the <a href="https://gp2a.org/" class="text-brand-primary font-bold hover:underline">GP2A</a> 32nd annual conference hosted by the University of Coimbra.
                            <div class="mt-4 flex justify-center">
                                <img src="./news items supporting info/Hadia 2nd annual conference-GP2A 2024.jpg" class="w-[40%] news-img" alt="Hadia GP2A">
                            </div>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">August 20th 2024</strong>
                            Hadia presented her research at the PDRA Symposium at UCL Chemistry.
                            <div class="mt-4 flex justify-center">
                                <img src="./news items supporting info/Hadia PDRA Symposium at UCL Chemistry.jpg" class="w-[75%] news-img" alt="Hadia PDRA">
                            </div>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">July 31st 2024</strong>
                            Wellington's supervisor from Unicamp, Brazil, Prof Carlos Roque Duarte Correia, dropped by to say hello and see the lab.
                            <div class="mt-4 flex justify-center">
                                <img src="./news items supporting info/Prof Carlos Roque Duarte Correia.jpg" class="w-[40%] news-img" alt="Prof Correia">
                            </div>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">July 24th 2024</strong>
                            As part of his project, Mohsen has been spending time with the SGC in Toronto. Here he is running an SPR using Biacore T200 to see if his compounds have a binder against a plasmodium WDR.
                            <div class="mt-4 flex justify-center">
                                <img src="./news items supporting info/Mohsen_SGC.png" class="w-[90%] news-img" alt="Mohsen SGC">
                            </div>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">July 20th 2024</strong>
                            Eve presented her research at the Gordon Research Seminar on Mammalian Reproduction in Barcelona.
                            <div class="mt-4 flex justify-center">
                                <img src="./news items supporting info/Eve-Gordon Research Seminar on Mammalian Reproduction.jpg" class="w-[40%] news-img" alt="Eve Gordon Seminar">
                            </div>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">July 8th 2024</strong>
                            In line with our strong commitment to sustainability, we are pleased to announce that we have received the LEAF Bronze Award. Learn more about the UCL LEAF programme <a href="https://www.ucl.ac.uk/sustainable/take-action/staff-action/leaf-laboratory-efficiency-assessment-framework" class="text-brand-primary font-bold hover:underline">here</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">July 6th 2024</strong>
                            Yinuo had a fantastic time at the ULLA  Summer School 2024 in Leiden University  — Shaping the Future of Drug Research: From Design to Therapy! It was an amazing week of talks and a great opportunity to network with a diverse range of PhD students from 10 different universities.
                            <div class="mt-4 flex justify-center">
                                <img src="./news items supporting info/Yinuo_ULLA2.png" class="w-[90%] news-img" alt="Yinuo ULLA">
                            </div>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">June 28th 2024</strong>
                            We say farewell to our visitor from the State University of Campinas, Wellington Da Silva, who has been working on marinoquinolines as part of Open Source Malaria. Wellington is going back to ace his PhD in Brazil and hopefully we'll see him again.
                            <div class="mt-4 flex justify-center">
                                <img src="./news items supporting info/Goodbye_Wellington2.jpg" class="w-[75%] news-img" alt="Goodbye Wellington">
                            </div>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">June 3rd 2024</strong>
                            Yinuo has been awarded from the UCL FLS Conference Fund to present her research at the XXVIII EFMC International Symposium on Medicinal Chemistry in September.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 21st 2024</strong>
                            Today we said farewell to BVGH Fellow Evans Mainsah, and look forward to visiting him in his home town of Buea, Cameroon, where he is seeking new medicines for the treatment of river blindness (onchocerciasis).
                            <div class="mt-4 flex justify-center">
                                <img src="./pics/people/goodbye_evans.png" class="w-[75%] news-img" alt="Goodbye Evans">
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2023 -->
        <div class="year-block group">
            <div onclick="toggleYear('2023')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2023</h2>
                <i id="icon-2023" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2023" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 26th 2023</strong>
                            An Open Science Award. The <a href="https://github.com/OpenSourceMycetoma" class="text-brand-primary font-bold hover:underline">MycetOS</a> drug discovery project, founded by Mat, was awarded the <a href="https://www.eur.nl/en/news/winners-announced-eur-open-and-responsible-science-awards" class="text-brand-primary font-bold hover:underline">Open Research prize by the Erasmus University of Rotterdam</a>. The project uses open-source research methods to find new potential treatments for the neglected tropical disease, mycetoma, without secrecy or patents. Contributors to the project include Mat's PhD student Dmitrij Melechov, staff at Erasmus University and the Drugs for Neglected Diseases initiative and many others, such as the UK school children who have made new candidate molecules and, most recently, a cohort of our very own MSc Drug Discovery students in the School of Pharmacy in 2023.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2022 -->
        <div class="year-block group">
            <div onclick="toggleYear('2022')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2022</h2>
                <i id="icon-2022" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2022" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">June 7th 2022</strong>
                            Mat contributed to a report on open data sharing practices during the COVID pandemic, that was <a href="https://zenodo.org/record/6620854#.YtknTZDMI-Q" class="text-brand-primary font-bold hover:underline">published today</a> by Wellcome, UKRI and the Bill and Melinda Gates Foundation.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 20th 2022</strong>
                            The group receives about £2M from the National Institutes of Health as part of a $63M award to an antiviral drug discovery centre, <a href="https://uncnews.unc.edu/2022/05/20/unc-chapel-hill-receives-65m-from-nih-for-antiviral-drug-development-center/" class="text-brand-primary font-bold hover:underline">READDI-AViDD</a>, based at the University of North Carolina, Chapel Hill. Mat's group will work on the medicinal chemistry of multiple projects and will share all findings publicly in real time, in line with the group's open science principles. The aim is to work together to improve our pandemic preparedness. <a href="https://www.ucl.ac.uk/lifesciences-faculty/news/2022/jun/professor-matthew-todd-and-professor-robin-ketteler-awarded-grant" class="text-brand-primary font-bold hover:underline">UCL news item</a>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Mar 28th 2022</strong>
                            Mat is awarded £10,000 from the Rosetrees Trust following a successful application for funding led by the open science non-profit, Ersilia.io. The project will allow iterative design-synthesis-test cycles for the leading project in Open Source Malaria, where new potential antimalarials will be designed using Ersilia's AI/ML methods and evaluated in blood stage potency assays.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Mar 28th 2022</strong>
                            Mat is awarded $250K from the Bill and Melinda Gates Foundation and the Structural Genomics Consortium as part of an $5M consortium aimed at finding new non-hormonal female contraceptives. This major open science initiative, running for three years, will have project champions across UCL, Toronto, University of North Carolina Chapel Hill, Frankfurt, McGill and Karolinska. The UCL team's job is to find potent, selective, cell-penetrant inhibitors of phospholipase C zeta 1, an under-explored target central to human fertilisation. <a href="https://github.com/StructuralGenomicsConsortium/CNP5-PLCZ1" class="text-brand-primary font-bold hover:underline">Science details</a>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Mar 15th 2022</strong>
                            The group's research is mentioned in the Financial Times' article <a href="https://www.ft.com/content/61e1d51e-b415-4161-b157-032e5207ab7f" class="text-brand-primary font-bold hover:underline">"Will ‘open-source’ vaccines narrow the inequality gap exposed by Covid?"</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 14th 2022</strong>
                            Mat wins £35,604 from the EPSRC Impact Acceleration Account/Knowledge Exchange and Innovation Funding scheme to run an AI/ML open science challenge to find new starting points for antibiotics. With Brooks Paige (Turing Institute) and Peter Coveney (Chemistry), a protein target is being provided, and AI/ML researchers who use "generative" methods for molecule generation can predict compounds that will bind that protein. Mat's lab will make or buy the molecules, which will be evaluated at the University of Warwick, with all data being shared in real time. You can find details <a href="https://github.com/opensourceantibiotics/murligase/issues/69" class="text-brand-primary font-bold hover:underline">here</a>
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 3rd 2022</strong>
                            Tom and Mat featured in a <a href="https://www.chemistryworld.com/opinion/a-call-for-open-science-student-leaders/4015107.article" class="text-brand-primary font-bold hover:underline">Chemistry World article</a> about the <a href="https://github.com/mattodd/blog/issues/6" class="text-brand-primary font-bold hover:underline">Sir James Murray Student Champion</a> concept.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2020 -->
        <div class="year-block group">
            <div onclick="toggleYear('2020')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2020</h2>
                <i id="icon-2020" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2020" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Mar 26th 2020</strong>
                            Mat is named in the <a href="https://themedicinemaker.com/power-list/2020" class="text-brand-primary font-bold hover:underline">Medicine Maker 2020 Power List</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 11th 2020</strong>
                            Mat co-founds the company <a href="https://www.m4idpharma.com/" class="text-brand-primary font-bold hover:underline">M4ID Pharma</a>, with a mission to develop medicines for infectious disease using open science.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 10th 2020</strong>
                            Congratulations to Edwin as he submits his corrected PhD thesis, to become Dr Tse.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2019 -->
        <div class="year-block group">
            <div onclick="toggleYear('2019')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2019</h2>
                <i id="icon-2019" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2019" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Dec 6th 2019</strong>
                            Open Source Malaria's computational modelling competition (funded by the AI3SD network) <a href="https://www.news-medical.net/news/20191206/Intellegens-and-Optibrium-announce-success-in-the-Open-Source-Malaria-global-initiative.aspx" class="text-brand-primary font-bold hover:underline">attracts a winning entry from the private sector firms Optibrium and Intellegens</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Nov 27th 2019</strong>
                            Mat talks at the Innovation Lecture hosted by UCL's Institute of Brand and Innovation Law, entitled "<a href="https://www.ucl.ac.uk/ibil/events/past-events/events-2019" class="text-brand-primary font-bold hover:underline">Patents vs Open Innovation: Incentivising 'Medicines for the Many'</a>" hosted by Sir Robin Jacob and The Hon. Mr Justice Birss.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 24th 2019</strong>
                            Mat is mentioned in the new Labour Party policy document "<a href="https://labour.org.uk/press/labour-will-take-pharmaceutical-companies-put-public-health-private-profit-corbyn/" class="text-brand-primary font-bold hover:underline">Medicines for the Many</a>" as an example of new approaches to the development of affordable medicines.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">June 25th 2019</strong>
                            With Sevenoaks school we're awarded a <a href="https://www.sevenoaksschool.org/news/science/article/news/royal-society-partnership-grant-funds-new-pharma-research/?tx_news_pi1%5Bcontroller%5D=News&tx_news_pi1%5Baction%5D=detail&cHash=9d3259d5503ca90dcef8bfbdf546af05" class="text-brand-primary font-bold hover:underline">Royal Society partnership grant</a> to work <a href="https://github.com/OpenSourceMycetoma" class="text-brand-primary font-bold hover:underline">open source on new medicines for mycetoma</a>, a fungal infection for which there are no drugs. The research will involve 6th-form school students generating new molecules. If it works, we can use the project as a guide for others. See also <a href="https://github.com/TheBreakingGoodProject" class="text-brand-primary font-bold hover:underline">Breaking Good</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Mar 22nd 2019</strong>
                            Edwin's review on the past, present and future of anti-malarial medicines is <a href="https://malariajournal.biomedcentral.com/articles/10.1186/s12936-019-2724-z" class="text-brand-primary font-bold hover:underline">published</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Jan 18th 2019</strong>
                            Mat delivers TedX talk entitled "<a href="https://www.youtube.com/watch?v=DeC0YS3j2E4" class="text-brand-primary font-bold hover:underline">Can Openness Pay?</a>", detailing the possible use of regulatory data exclusivity to help fund open source drug discovery.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2018 -->
        <div class="year-block group">
            <div onclick="toggleYear('2018')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2018</h2>
                <i id="icon-2018" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2018" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Aug 8th 2018</strong>
                            Congratulations to Edwin for being selected as one of the three Sydney University Chemical Society Le Fevre Lecturers for 2018.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Jan 23rd 2018</strong>
                            Mat delivers <a href="https://www.youtube.com/watch?v=VBodnd68iwU" class="text-brand-primary font-bold hover:underline">a keynote on open drug discovery at linux.con.au in Sydney</a>.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2017 -->
        <div class="year-block group">
            <div onclick="toggleYear('2017')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2017</h2>
                <i id="icon-2017" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2017" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Nov 2017</strong>
                            Mat joins Expert Advisory Committee of the <a href="http://www.guidetopharmacology.org/" class="text-brand-primary font-bold hover:underline">IUPHAR/BPS Guide to PHARMACOLOGY database</a> malaria project.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 19th 2017</strong>
                            Yu Heng's work on <a href="http://onlinelibrary.wiley.com/doi/10.1002/chem.201703488/abstract" class="text-brand-primary font-bold hover:underline">the coordinating ability of cyclam scorpionands</a> is finally published.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Aug 31st 2017</strong>
                            Mat, Alice, the Sydney Grammar School students and Open Source Malaria are featured on <a href="http://www.comedycentral.com.au/the-daily-show-with-trevor-noah/videos/august-31-2017-australian-students-stick-it-to-martin-shkreli#australian-students-stick-it-to-martin-shkreli" class="text-brand-primary font-bold hover:underline">The Daily Show with Trevor Noah</a> (US only <a href="https://www.youtube.com/watch?v=G4up_3JhNIQ&feature=youtu.be" class="text-brand-primary font-bold hover:underline">Youtube video</a>).
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">June 22nd 2017</strong>
                            Mat interviewed for <a href="http://www.beilstein.tv/video/the-open-source-chemistry-lab/" class="text-brand-primary font-bold hover:underline">Beilstein TV</a> on whether the chemistry community is embracing open science and open data.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">June 21st 2017</strong>
                            Althea Tsang's paper on <a href="http://onlinelibrary.wiley.com/doi/10.1002/chem.201700430/abstract" class="text-brand-primary font-bold hover:underline">the mechanism of CDC reactions</a> finally comes out.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 4th 2017</strong>
                            Mat is one of 100 people named on the <a href="https://themedicinemaker.com/power-list/2017/" class="text-brand-primary font-bold hover:underline">Medicine Maker Power List 2017</a>, as a Champion of Change, for his work on Open Source Malaria.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Apr 19th 2017</strong>
                            Paper published that describes a <a href="http://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1002276" class="text-brand-primary font-bold hover:underline">roadmap for open source pharma</a>, with an associated <a href="https://www.theguardian.com/commentisfree/2017/apr/19/why-open-source-pharma-is-the-path-to-both-cheaper-and-new-medicines" class="text-brand-primary font-bold hover:underline">explainer in the Guardian</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 8th 2017</strong>
                            The collaboration between Sydney Grammar School and Open Source Malaria is <a href="https://www.teachermagazine.com.au/articles/daraprim-students-a-lesson-in-perseverance?utm_source=Gonski&utm_medium=article&utm_content=Part1" class="text-brand-primary font-bold hover:underline">featured in Teacher Magazine</a>.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2016 -->
        <div class="year-block group">
            <div onclick="toggleYear('2016')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2016</h2>
                <i id="icon-2016" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2016" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Dec 1 2016</strong>
                            Alice Williamson and Mat <a href="https://hitachi-social-innovation-awards.thinkable.org/winners" class="text-brand-primary font-bold hover:underline">win the Jury Prize of the Hitachi Innovation Award</a> with a pitch on "Breaking Good" - how to involve students and the public in the synthesis of much-needed medicines.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Nov 30th 2016</strong>
                            Sydney Grammar School completes the synthesis of Daraprim using Open Source Malaria's platform. <a href="https://github.com/OpenSourceMalaria/OSM_To_Do_List/issues/472" class="text-brand-primary font-bold hover:underline">The story goes viral</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 14th 2016</strong>
                            The <a href="https://github.com/OpenSourceMalaria/OSM_To_Do_List/issues/434" class="text-brand-primary font-bold hover:underline">first Open Source Malaria paper</a> is published.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">June 2nd 2016</strong>
                            Open Source Malaria <a href="http://parasite.org.au/wp-content/uploads/2010/05/ASPnewsletterVol27No1lores.pdf" class="text-brand-primary font-bold hover:underline">featured in the Newsletter of the Australian Society for Parasitology</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 13th 2016</strong>
                            Mat's work on schistosomiasis, Open Source Malaria and the Open Source Pharma Foundation featured in both <a href="http://www.thelancet.com/journals/lancet/article/PIIS0140-6736%2816%2930518-9/abstract" class="text-brand-primary font-bold hover:underline">The Lancet</a> and <a href="http://www.nature.com/nature/journal/v533/n7602_supp/full/533S68a.html" class="text-brand-primary font-bold hover:underline">Nature</a>.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2015 -->
        <div class="year-block group">
            <div onclick="toggleYear('2015')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2015</h2>
                <i id="icon-2015" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2015" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Nov 17th 2015</strong>
                            Mat wins in the <a href="http://www.socmedawards.com/malaria2015/page/winner" class="text-brand-primary font-bold hover:underline">Malaria Innovator category of the Social Media Awards</a> (<a href="http://www.socmedawards.com/malaria2015/page/content/41" class="text-brand-primary font-bold hover:underline">Article</a>, <a href="https://www.youtube.com/watch?v=LlGXz2bxcUI" class="text-brand-primary font-bold hover:underline">interview</a> and even <a href="http://www.socmedawards.com/malaria2015/page/content/47" class="text-brand-primary font-bold hover:underline">artwork</a>).
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 30th 2015</strong>
                            The Open Source Malaria consortium is <a href="http://ands.us7.list-manage.com/track/click?u=b542ef52e49302569068046d9&id=6ef868a690&e=77cd7367f5" class="text-brand-primary font-bold hover:underline">featured in <em>Share</em></a>, the newsletter of the Australian National Data Service.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 28th 2015</strong>
                            Mat delivers one of the NSW Chief Scientist's <a href="http://www.sonicinteractive.com.au/srdt_edms/srdt-invite-todd.html" class="text-brand-primary font-bold hover:underline">Breakfast Seminars</a> on <em>Openness Boosts Research</em> (<a href="http://www.slideshare.net/MatthewTodd5/nsw-chief-scientist-breakfast-seminar" class="text-brand-primary font-bold hover:underline">Slides</a>).
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 23rd 2015</strong>
                            Mat writes about <a href="http://blogs.plos.org/yoursay/2015/10/22/talking-drug-prices-pt-6-openness-vs-secrecy-in-drug-development-by-mat-todd/" class="text-brand-primary font-bold hover:underline">openness vs. secrecy in drug development</a> as part of a series on this topic at PLoS Blogs.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 2015</strong>
                            The fantastic work of Erin Sheridan and the boys at Sydney Grammar as part of the Open Source Malaria consortium is featured in the <a href="http://www.sydgram.nsw.edu.au/files/sgsmagazine/SGSmagazine_iss1_Winter2015.pdf" class="text-brand-primary font-bold hover:underline">school's winter newsletter</a> (p36). You can read their <a href="http://figshare.com/articles/Open_Source_Malaria_2015/1513845" class="text-brand-primary font-bold hover:underline">research reports</a> directly, too.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 1st 2015</strong>
                            Mat is part of a team of four awarded $3M by the Tata Trusts to create the Open Source Pharma Foundation. Here is the <a href="http://www.tatatrusts.org/article/inside/Tata-Trusts-support-the-creation-of-the-Open-Source-Pharma-Foundation" class="text-brand-primary font-bold hover:underline">press release</a> and articles: <a href="http://spicyip.com/2015/09/creation-of-linux-for-drugs-gets-support-from-tata-trusts.html" class="text-brand-primary font-bold hover:underline">1</a>, <a href="https://d.wifo.org/t/open-source-pharma-foundation/161" class="text-brand-primary font-bold hover:underline">2</a>, <a href="http://www.thehindubusinessline.com/economy/tata-trusts-support-creation-of-open-source-pharma-foundation/article7703087.ece" class="text-brand-primary font-bold hover:underline">3</a>. The aspect of prizes as part of OSP is picked up by the <a href="http://www.economist.com/news/business/21679203-high-cost-rd-used-explain-why-drugs-giants-merge-and-why-they-must-charge" class="text-brand-primary font-bold hover:underline">Economist</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 2015</strong>
                            Mat helps create and then run the <a href="http://www.opensourcepharma.net/germany-2015.html" class="text-brand-primary font-bold hover:underline">Second Open Source Pharma Conference</a> in Marburg, Germany. The meeting's <a href="http://tinyurl.com/OSP2Final" class="text-brand-primary font-bold hover:underline">To Do list</a> is available. An <a href="http://www.consortiuminfo.org/standardsblog/article.php?story=20150904123645851" class="text-brand-primary font-bold hover:underline">article</a> about the meeting from one of the participants sparks a <a href="http://blogs.sciencemag.org/pipeline/archives/2015/09/08/magic-open-source-savings-await" class="text-brand-primary font-bold hover:underline">lengthy debate on the merits of OSP at Derek Lowe's blog</a> and <a href="http://esr.ibiblio.org/?p=6837" class="text-brand-primary font-bold hover:underline">further debate on Eric Raymond's blog</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">July 31st 2015</strong>
                            Alice Williamson leads a team that includes Mat in a successful application for a University of Sydney Small Educational Innovation Grant on Open Research in the Undergraduate Laboratory, following <a href="http://malaria.ourexperiment.org/the_osm_blog/11566/Alice_Williamsons_Open_Source_Undergrad_Lab_Course.html" class="text-brand-primary font-bold hover:underline">Alice's pilot of this idea</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">July 7th 2015</strong>
                            The group is awarded a 3-year ARC Linkage Grant (LP150101226) with the <a href="http://www.mmv.org/" class="text-brand-primary font-bold hover:underline">Medicines for Malaria Venture</a> and <a href="http://biology.anu.edu.au/research/labs/kirk-lab-membrane-transport-parasites" class="text-brand-primary font-bold hover:underline">Kiaran Kirk</a> to use the <a href="http://opensourcemalaria.org/" class="text-brand-primary font-bold hover:underline">Open Source Malaria</a> platform to make new compounds that will reveal the details of an important antimalarial target, PfATP4.
                            <br>June 29th 2015: Alice Williamson writes about open science and the OSM consortium in a <a href="http://www.abc.net.au/science/articles/2015/06/29/4254093.htm" class="text-brand-primary font-bold hover:underline">piece for ABC Science</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 22nd 2015</strong>
                            Mat <a href="http://www.future-science.com/doi/full/10.4155/fmc.15.28" class="text-brand-primary font-bold hover:underline">interviewed</a> in Future Medicinal Chemistry about the use of open source research models, and is part of an <a href="http://www.future-science.com/doi/full/10.4155/fmc.15.29" class="text-brand-primary font-bold hover:underline">Ask the Experts</a> panel on Rethinking the Drug Discovery Model in neglected tropical diseases. These articles were part of an <a href="http://www.future-science.com/toc/fmc/7/6" class="text-brand-primary font-bold hover:underline">open access special issue on schistosomiasis</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 20th 2015</strong>
                            Mat talks on "<a href="http://www.isntd.org/#/isntd-d-2015-todd/4589881721" class="text-brand-primary font-bold hover:underline">The Six Principles of Open Source Drug Discovery</a>" and chairs a panel session on "<a href="http://www.isntd.org/#/isntd-d-15-panel-14/4589888426" class="text-brand-primary font-bold hover:underline">Open Source: Models for Collaboration</a>" at the <a href="http://www.isntdd3.com/" class="text-brand-primary font-bold hover:underline">ISNTD-D3</a> meeting at the Wellcome Trust in London.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Apr 30th 2015</strong>
                            OSM's <a href="https://www.youtube.com/watch?v=o29cq7uYWFc" class="text-brand-primary font-bold hover:underline">introductory video</a> comes an honorable 7th in the <a href="https://www.thinkable.org/competition/6" class="text-brand-primary font-bold hover:underline">Thinkable Open Innovation competition</a> - well done to the winners.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Mar 7th 2015</strong>
                            Alice Williamson is <a href="https://www.unsw.edu.au/top5under40" class="text-brand-primary font-bold hover:underline">one of the winners of the ABC's Top 5 Under 40 competition!</a> Here's a <a href="http://www.abc.net.au/radionational/programs/scienceshow/alice-williamson/6283462" class="text-brand-primary font-bold hover:underline">video</a> she made in the competition. She now gets to make a full radio show on a subject of her choosing.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2014 -->
        <div class="year-block group">
            <div onclick="toggleYear('2014')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2014</h2>
                <i id="icon-2014" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2014" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 26th 2014</strong>
                            <a href="http://sydney.edu.au/science/chemistry/news-events/articles/issue-25/opening-new-ways-to-treat-malaria.shtml" class="text-brand-primary font-bold hover:underline">Article on Open Source Malaria (OSM)</a> appears in the School of Chemistry's Newsletter, ChemNews.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 18th 2014</strong>
                            Mat <a href="http://www.cbc.ca/radio/day6/can-open-source-pharma-cure-ebola-and-other-neglected-killers-1.2772158" class="text-brand-primary font-bold hover:underline">interviewed on Canadian and US Radio</a> about Open Source Pharma and Ebola.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 18th 2014</strong>
                            Invited talk and <a href="http://pubs.rsc.org/en/Content/ArticleLanding/2014/FD/C4FD90079K#!divAbstract" class="text-brand-primary font-bold hover:underline">associated discussion</a> at the RSC Faraday Discussions meeting on Physical Chemistry of Functionalised Biomedical Nanoparticles, Bristol UK.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Aug 22nd 2014</strong>
                            Mat speaks on <a href="https://youtu.be/rQtA1gXRZjk?t=26m51s" class="text-brand-primary font-bold hover:underline">how to do science openly</a> at the Open Science, Open Issues conference in Rio.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">July 16-18 2014</strong>
                            Mat co-organises the first <a href="http://www.opensourcepharma.net/" class="text-brand-primary font-bold hover:underline">Open Source Pharma</a> conference that takes place at the Rockefeller Foundation's Bellagio Centre on Lake Como, Italy. The meeting creates a set of principles for <a href="http://www.who.int/tdr/news/2014/open-source-pharma-mtg/en/" class="text-brand-primary font-bold hover:underline">Medicine for All</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">June 26th 2014</strong>
                            The Open Source Malaria project is <a href="http://www.ands.org.au/newsletters/newsletter-2014-07.pdf" class="text-brand-primary font-bold hover:underline">featured in the newsletter</a> of the Australian National Data Service.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2013 -->
        <div class="year-block group">
            <div onclick="toggleYear('2013')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2013</h2>
                <i id="icon-2013" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2013" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 31st 2013</strong>
                            Mat <a href="https://mediawarehouse.qut.edu.au/QMW/player/?dID=20605" class="text-brand-primary font-bold hover:underline">speaks about open data and open access</a> at the Open Access Research conference at QUT, Brisbane.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 21st 2013</strong>
                            The <a href="http://opensourcemalaria.org/#" class="text-brand-primary font-bold hover:underline">Open Source Malaria Consortium</a> wins one of three $30K Google/PLoS/Wellcome Trust <a href="http://asap.plos.org/" class="text-brand-primary font-bold hover:underline">ASAP awards</a>. <a href="http://live.worldbank.org/open-access-week-2013" class="text-brand-primary font-bold hover:underline">Webcast from the World Bank</a> (award is from 1:08 in). <a href="http://www.youtube.com/watch?v=gCOokjOiVTc" class="text-brand-primary font-bold hover:underline">Background video</a>. Picked up in <a href="http://theconversation.com/open-source-malaria-project-head-wins-accelerating-science-award-19420" class="text-brand-primary font-bold hover:underline">The Conversation</a>, by <a href="http://www.mmv.org/newsroom/news/mmv-partner-receives-plos-accelerating-science-award" class="text-brand-primary font-bold hover:underline">MMV</a>. Interview at <a href="http://blogs.plos.org/mindthebrain/2013/10/01/asap-awards-interview-with-mat-todd/" class="text-brand-primary font-bold hover:underline">PLoS Blogs</a>. Bill Gates <a href="https://twitter.com/BillGates/status/395647331670167552" class="text-brand-primary font-bold hover:underline">tweets</a> about the project.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 26th 2013</strong>
                            Mat runs conference session on "<a href="http://www.who.int/tdr/news/2013/odd/en/" class="text-brand-primary font-bold hover:underline">Is Open Source Drug Discovery Practical?</a>" at WHO, Geneva, addressing, among other things, whether patents are necessary in drug discovery.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 11th 2013</strong>
                            Mat <a href="http://www.mmv.org/partnering/interviews/drug-discovery-difference" class="text-brand-primary font-bold hover:underline">interviewed by MMV</a> about open drug discovery.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 17th 2013</strong>
                            Mat talks about open source drug discovery at the <a href="http://www.goldlabcolorado.com/2013Speakers.html" class="text-brand-primary font-bold hover:underline">2013 GoldLab Symposium</a> in Boulder, Colorado.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 15th 2013</strong>
                            Mat is quoted in an <a href="http://www.theatlantic.com/health/archive/2013/05/how-drug-companies-keep-medicine-out-of-reach/275853/" class="text-brand-primary font-bold hover:underline">article in The Atlantic</a> on "de-linking" drug R&D from the cost of medicines.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 10th 2013</strong>
                            Mat <a href="http://webconf.ucc.usyd.edu.au/p1rg7idbbus/" class="text-brand-primary font-bold hover:underline">talks at Sydney Uni</a> about the group's use of the electronic lab notebook Labtrove.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 1st 2013</strong>
                            The <a href="https://plus.google.com/u/0/b/114702323662314783325/114702323662314783325/posts" class="text-brand-primary font-bold hover:underline">OSDD Malaria project</a> is mentioned as one of the top innovations worldwide in malaria by <a href="http://www.guardian.co.uk/global-development-professionals-network/2013/apr/29/malaria-innovations-top-ten-world-malaria-day" class="text-brand-primary font-bold hover:underline">The Guardian newspaper</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Apr 22nd 2013</strong>
                            Congratulations to Nilupa as she <a href="http://openwetware.org/wiki/Image:Nilupa_PhD_Submission.JPG" class="text-brand-primary font-bold hover:underline">hands in her corrected PhD thesis</a>, to become Dr Amarasinghe.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Apr 18th 2013</strong>
                            Congratulations to Mingfeng as he <a href="http://openwetware.org/wiki/Image:Mingfeng_PhD_Submission.jpg" class="text-brand-primary font-bold hover:underline">hands in his corrected PhD thesis</a>, to become Dr Yu.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Mar 28th 2013</strong>
                            Mat's <a href="https://theconversation.com/open-publishing-is-happening-the-only-question-is-how-13100" class="text-brand-primary font-bold hover:underline">piece about open access and open science comes out in The Conversation</a> in response to number of Nature articles on the subject.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 15th 2013</strong>
                            Congratulations to new Honours student Kat Badiola for winning a <a href="http://sydney.edu.au/about/profile/honour_roll/2012/index.shtml" class="text-brand-primary font-bold hover:underline">University of Sydney Academic Merit Prize</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Jan 30th 2013</strong>
                            Congratulations to Althea on submitting her PhD thesis.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Jan 30th 2013</strong>
                            The <a href="https://twitter.com/OSDDMalaria" class="text-brand-primary font-bold hover:underline">OSDDMalaria</a> team is featured in an <a href="http://www.rsc.org/chemistryworld/2013/01/crowdfunding-crowdsourcing" class="text-brand-primary font-bold hover:underline">article on crowdsourcing</a> in the RSC's Chemistry World magazine.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Jan 25th 2013</strong>
                            Mat is <a href="http://blogs.nature.com/thescepticalchymist/2013/01/reactions-matthew-todd.html" class="text-brand-primary font-bold hover:underline">interviewed</a> in the Nature Chemistry blog <em>The Sceptical Chymist</em>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Jan 17th 2013</strong>
                            Mat publishes an <a href="http://www.abc.net.au/unleashed/4468970.html" class="text-brand-primary font-bold hover:underline">opinion piece on open access</a> on the ABC News site, The Drum.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2012 -->
        <div class="year-block group">
            <div onclick="toggleYear('2012')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2012</h2>
                <i id="icon-2012" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2012" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Nov 7th 2012</strong>
                            The group's open source research featured on SciDev.Net in a <a href="http://www.scidev.net/en/science-and-innovation-policy/science-networks/features/a-match-made-in-cyberspace-how-networks-nurture-science-.html" class="text-brand-primary font-bold hover:underline">story on science networks</a>. This follows an <a href="http://www.scidev.net/en/health/drug-development/news/study-finds-success-factors-for-open-source-drug-discovery--1.html" class="text-brand-primary font-bold hover:underline">earlier story</a> covering the case study (below) analysing The Synaptic Leap's achievements.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 20th 2012</strong>
                            <a href="http://www.plosntds.org/article/info%3Adoi%2F10.1371%2Fjournal.pntd.0001827" class="text-brand-primary font-bold hover:underline">Study published</a> comparing The Synaptic Leap and Indian OSDD Projects.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 20th 2012</strong>
                            Open letter to the new CEO of the Australian Research Council about the value of open data is published in <a href="https://theconversation.edu.au/scientific-data-should-be-shared-an-open-letter-to-the-arc-9458" class="text-brand-primary font-bold hover:underline">The Conversation</a> with a link to the <a href="https://docs.google.com/document/d/1bcrrzu4Ljono5V_UqdJogtB-043XmxWVkm-jH9kw3m0/edit" class="text-brand-primary font-bold hover:underline">Google Doc</a> that can be signed. Please feel free to add your name. Stephen Matchett comments on it in <a href="http://blogs.theaustralian.news.com.au/thecommonroom/index.php/theaustralian/comments/half_baked_solutions_dont_set/" class="text-brand-primary font-bold hover:underline">The Australian</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 19th 2012</strong>
                            Mat delivers <a href="http://bambuser.com/v/2993803" class="text-brand-primary font-bold hover:underline">keynote about open source drug discovery</a> at the 1st Open Knowledge Festival in Helsinki.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 13th 2012</strong>
                            Interview with Mat on open science <a href="http://healthresearchpolicy.org/blog/2012/sep/13/insider-views-collaborative-rd-health-qa-matt-todd" class="text-brand-primary font-bold hover:underline">published</a> by the Results for Development Institute.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Aug 31 2012</strong>
                            Congratulations to Mingfeng, Nilupa and Soo for submitting their PhD theses.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 4th 2012</strong>
                            Mat presents some of the group's research at the <a href="http://sydney.edu.au/foundations_of_science/events/integration.shtml" class="text-brand-primary font-bold hover:underline">University of Sydney Integration in Biology and Medicine Conference</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 3rd 2012</strong>
                            Althea is awarded a RJW Le Fevre Research Travelling Scholarship from the School of Chemistry to present her research at an overseas conference later this year.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 24th 2012</strong>
                            We play host to the first Open Source Drug Discovery for Malaria meeting. An account of the meeting is <a href="http://www.thesynapticleap.org/node/390" class="text-brand-primary font-bold hover:underline">here</a>, and the current playlist of talks is <a href="http://www.youtube.com/playlist?list=PL84A4E62C3C72863D" class="text-brand-primary font-bold hover:underline">here</a>. A Sydney Uni news feature on the meeting is <a href="http://sydney.edu.au/news/84.html?newsstoryid=8800" class="text-brand-primary font-bold hover:underline">here</a> and <a href="http://sydney.edu.au/news/science/397.html?newsstoryid=8775" class="text-brand-primary font-bold hover:underline">here</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 18th 2012</strong>
                            Mat talks at a session on "<a href="http://aaas.confex.com/aaas/2012/webprogram/Session4869.html" class="text-brand-primary font-bold hover:underline">Innovating Innovation</a>" at the AAAS meeting in Vancouver.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Jan 27th 2012</strong>
                            Mat's <a href="http://intermolecular.wordpress.com/2012/01/26/goodbye-elsevier-goodbye-tet-lett-etc/" class="text-brand-primary font-bold hover:underline">blog post</a> on open access is republished on the <a href="http://blogs.lse.ac.uk/impactofsocialsciences/2012/02/01/stand-down-journal-referee/" class="text-brand-primary font-bold hover:underline">LSE blog</a>.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2011 -->
        <div class="year-block group">
            <div onclick="toggleYear('2011')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2011</h2>
                <i id="icon-2011" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2011" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Nov 23rd 2011</strong>
                            Mat wins a NSW Science and Engineering Award in the "Emerging Research" category for open science. Story is <a href="http://sydney.edu.au/news/84.html?newscategoryid=1&newsstoryid=8271" class="text-brand-primary font-bold hover:underline">here</a> and <a href="http://www.business.nsw.gov.au/networking-and-events/awards/nsw-science-engineering-awards/nsw-scientist-of-the-year-2011-winners" class="text-brand-primary font-bold hover:underline">here</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Nov 1st 2011</strong>
                            Two Australian Research Council grants awarded. ARC Discovery (DP120104035): Charting Intercellular Space, M. H. Todd, P. J. Rutledge and P. J. Smith ($348K) and ARC Linkage (LP120100552): Open Source Drug Discovery for Malaria, M. H. Todd and T. N. C. Wells ($320K).
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 28th 2011</strong>
                            Mat talks at Sydney University's Open Access Week - recording <a href="http://www.library.usyd.edu.au/stream/openaccessweek2011todd/" class="text-brand-primary font-bold hover:underline">here</a> and on <a href="http://www.youtube.com/watch?v=rRd15GMbprA" class="text-brand-primary font-bold hover:underline">Youtube</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 20th 2011</strong>
                            Mat's article entitled "We eat what we are – let's detoxify the word 'chemical'" appears in <a href="http://theconversation.edu.au/we-eat-what-we-are-lets-detoxify-the-word-chemical-3642" class="text-brand-primary font-bold hover:underline">The Conversation</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Septr 23rd 2011</strong>
                            Our second open science paper is published, describing how <a href="http://www.nature.com/nchem/journal/v3/n10/full/nchem.1149.html" class="text-brand-primary font-bold hover:underline">Open Science is a Research Accelerator</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 21st 2011</strong>
                            Our first open science paper is published, on the <a href="http://www.plosntds.org/article/info%3Adoi%2F10.1371%2Fjournal.pntd.0001260" class="text-brand-primary font-bold hover:underline">Resolution of Praziquantel</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Aug 19th 2011</strong>
                            Ahamed <a href="http://twitpic.com/68aaxc" class="text-brand-primary font-bold hover:underline">submits his corrected PhD thesis</a> today, and we welcome two new postdocs to the group, <a href="http://twitter.com/#!/paulylioja" class="text-brand-primary font-bold hover:underline">Paul Ylioja</a> and Murray Robertson.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Apr 8th 2011</strong>
                            Mat talks about the future of web-based chemical collaboration at the <a href="http://twitpic.com/4igb3e" class="text-brand-primary font-bold hover:underline">Cyberchemistry meeting</a> at the Pacific Northwest National Laboratory, Washington State.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 21st 2011</strong>
                            Congratulations to Swapnil on his award of a <a href="http://agile2.ucc.usyd.edu.au/ro/opportunities/scholarships/75" class="text-brand-primary font-bold hover:underline">Henry Bertie and Florence Mabel Gritton Research Scholarship</a>. Drinks are on him...
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 15th 2011</strong>
                            A new industry-sponsored PhD position in medicinal chemistry is available. If you're interested, please contact Mat. Only Australian residents are eligible for this opening.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 15th 2011</strong>
                            The awesome and long-awaited <a href="http://dx.doi.org/10.1021/ed100867m" class="text-brand-primary font-bold hover:underline">Treasure Hunt paper</a> comes out in <em>J. Chem. Ed.</em> - this turns a campus map into a play area for a Chemistry-themed treasure hunt.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Jan 27th 2011</strong>
                            Mat is named as one of the University's top 10 lecturers for 2010 in a <a href="http://www.lectureroftheyear.com.au/winners_list_2010.php" class="text-brand-primary font-bold hover:underline">nationwide poll</a>.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2010 -->
        <div class="year-block group">
            <div onclick="toggleYear('2010')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2010</h2>
                <i id="icon-2010" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2010" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-8 py-6 px-2 text-sm leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <strong class="text-brand-dark block mb-2">Nov 3rd 2010</strong>
                            Congratulations to Ahamed for being selected as one of the three <a href="http://www.chem.usyd.edu.au/~sucs/history/lefevrestudents.htm" class="text-brand-primary font-bold hover:underline">Sydney University Chemical Society Le Fevre Lecturers</a> for 2010.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Oct 6th 2010</strong>
                            Mat <a href="http://bit.ly/ihKBMC" class="text-brand-primary font-bold hover:underline">talks about open science and electronic lab notebooks</a> at USyd's eResearch showcase.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 23rd 2010</strong>
                            Yu Heng's first paper is accepted into <em>Chem. Eur. J.</em> and he's off to start his PhD with <a href="http://www.ch.cam.ac.uk/staff/drs.html" class="text-brand-primary font-bold hover:underline">Dave Spring</a>. Paper available <a href="http://dx.doi.org/10.1002/chem.201002477" class="text-brand-primary font-bold hover:underline">here</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 20th 2010</strong>
                            Ahamed, Thiru and lots of other peoples' paper on how dihydroisoquinoline reacts with nitromethane is <a href="http://dx.doi.org/10.1002/ejoc.201000955" class="text-brand-primary font-bold hover:underline">published</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Sept 6th 2010</strong>
                            Ahamed's review on catalytic asymmetric additions of C-nucleophiles to <em>N</em>-heterocycles is <a href="http://onlinelibrary.wiley.com/doi/10.1002/ejoc.201000877/abstract" class="text-brand-primary font-bold hover:underline">published</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Aug 6th 2010</strong>
                            Mat <a href="http://igniteshow.com/videos/open-science-we-can-all-help" class="text-brand-primary font-bold hover:underline">speaks on Open Science</a> at Ignite Sydney. Mat's talk's currently the most watched from the night.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">June 2010</strong>
                            Our lab's open science approach <a href="http://search.informit.com.au/documentSummary;dn=069595129263397;res=IELENG" class="text-brand-primary font-bold hover:underline">featured in Chemistry in Australia</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">May 11th 2010</strong>
                            Mat is awarded a Citation for Excellence in Teaching from the Faculty of Science at The University of Sydney.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Apr 6th 2010</strong>
                            Mat talks about open science at <a href="http://www.youtube.com/watch?v=yWnTJw042OM" class="text-brand-primary font-bold hover:underline">Google</a>. The talk is picked up <a href="http://www.iijiij.com/2011/01/28/the-most-inspiring-introduction-to-open-science-ever-07275/comment-page-1#comment-3728" class="text-brand-primary font-bold hover:underline">here</a>.
                        </li>
                        <li>
                            <strong class="text-brand-dark block mb-2">Feb 4th 2010</strong>
                            Our open science project is the subject of a <a href="http://www.nature.com/news/2010/100204/full/news.2010.50.html" class="text-brand-primary font-bold hover:underline">feature article in Nature</a>.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

    </div>
    
</div>

<script>
    function toggleYear(year) {
        const content = document.getElementById(`content-${year}`);
        const icon = document.getElementById(`icon-${year}`);
        
        // Toggle active classes
        if (content.classList.contains('active')) {
            content.classList.remove('active');
            icon.classList.remove('rotate');
            // Adjust styling for inactive border
            icon.parentElement.classList.remove('border-brand-primary');
            icon.parentElement.classList.add('border-slate-200');
        } else {
            content.classList.add('active');
            icon.classList.add('rotate');
            // Adjust styling for active border
            icon.parentElement.classList.remove('border-slate-200');
            icon.parentElement.classList.add('border-brand-primary');
        }
    }

    function toggleAll(expand) {
        const contents = document.querySelectorAll('.accordion-content');
        const icons = document.querySelectorAll('.chevron');
        
        contents.forEach((content, index) => {
            if (expand) {
                content.classList.add('active');
                icons[index].classList.add('rotate');
                icons[index].parentElement.classList.add('border-brand-primary');
                icons[index].parentElement.classList.remove('border-slate-200');
            } else {
                content.classList.remove('active');
                icons[index].classList.remove('rotate');
                icons[index].parentElement.classList.remove('border-brand-primary');
                icons[index].parentElement.classList.add('border-slate-200');
            }
        });
    }
</script>
