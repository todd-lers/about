---
layout: default
title: Publications
---


<style>
    /* Accordion Transitions 
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
    
   
    .prose .year-block { margin-bottom: 1rem; }
    .prose a { text-decoration: none; }
    .prose ul > li { margin-top: 0.5em; margin-bottom: 0.5em; }
</style>

<div class="max-w-4xl mx-auto">
    
    <!-- Header Section -->
    <div class="mb-12 border-b border-slate-200 pb-8">
        <h1 class="text-4xl font-extrabold text-brand-dark mb-6">Publications</h1>
        <div class="flex flex-wrap gap-4 items-center">
            <a href="https://orcid.org/0000-0001-7096-4751" target="_blank" class="inline-flex items-center px-4 py-2 bg-slate-100 hover:bg-slate-200 text-slate-700 rounded-sm text-sm font-semibold transition no-underline">
                <i class="fab fa-orcid text-brand-primary mr-2 text-lg"></i> ORCID: 0000-0001-7096-4751
            </a>
            <a href="https://scholar.google.co.uk/citations?hl=en&user=a8lzGHEAAAAJ" target="_blank" class="inline-flex items-center px-4 py-2 bg-slate-100 hover:bg-slate-200 text-slate-700 rounded-sm text-sm font-semibold transition no-underline">
                <i class="fas fa-graduation-cap text-brand-primary mr-2 text-lg"></i> Google Scholar
            </a>
            <div class="ml-auto flex gap-2">
                <button onclick="toggleAll(true)" class="text-xs font-bold text-brand-primary hover:text-brand-primary-dark uppercase tracking-wider">Expand All</button>
                <span class="text-slate-300">|</span>
                <button onclick="toggleAll(false)" class="text-xs font-bold text-slate-500 hover:text-slate-700 uppercase tracking-wider">Collapse All</button>
            </div>
        </div>
    </div>

    <!-- Publications List -->
    <div class="space-y-3" id="publications-container">

        <!-- 2025 -->
        <div class="year-block group">
            <div onclick="toggleYear('2025')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2025</h2>
                <i id="icon-2025" class="fas fa-chevron-down text-slate-400 chevron rotate"></i>
            </div>
            <div id="content-2025" class="accordion-content active">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li>

                        <a href="https://pubs.rsc.org/en/content/articlelanding/2026/md/d5md00772k" class="font-bold text-brand-primary hover:underline block mb-1">Identification of Spirodioxolane nsP2 Helicase Inhibitors with Antialphaviral Activity</a>
                            H. J. Oh, J. D. Sears, B. M. Ramalingam, R. S. Z. Saleem, Z. W. Davis-Gilbert, M. A. Hossain, S. R. Moorman, D. Ohja, S. A. Martinez, J. E. Burdick, R. M. Couñago, N. J. Moorman, M. T. Heise, M. H. Todd and T. M. Willson, <em>RSC Med. Chem.</em> <strong>2025</strong>, <em>in press</em>. 
                        </li>
                        <li>
                        <a href="https://pubs.acs.org/doi/10.1021/acs.jmedchem.5c02354" class="font-bold text-brand-primary hover:underline block mb-1">Idler Compounds: A Simple Protocol for Openly Sharing Fridge Contents for Cross-Screening</a>
                            R. Isaksson, E. M. Carter, C. Hind, J. M. Sutton, H. Rudgyard, A. H. Roberts, C. W. Moon, Y. Wang, Todd Group Researchers, S. Codony, A. L. Martínez, J. Bacon and M. H. Todd, <em>J. Med. Chem.</em> <strong>2026</strong>.
                        </li>
                        <li>
                            <a href="https://www.nature.com/articles/s41570-025-00737-z" class="font-bold text-brand-primary hover:underline block mb-1">Protein–ligand Data at Scale to Support Machine Learning</a>
                            A. M. Edwards <em>et al.</em>, <em>Nat. Rev. Chem.</em> <strong>2025</strong>, <em>in press</em>.
                        </li>
                        <li>
                            <a href="https://doi.org/10.1371/journal.pntd.0013482" class="font-bold text-brand-primary hover:underline block mb-1">Kinome Analysis of <em>Madurella mycetomatis</em> Identified Kinases in the Cell Wall Integrity Pathway as Novel Potential Therapeutic Drug Targets in Eumycetoma Caused by <em>Madurella mycetomatis</em></a>
                            M. Konings, N. Strepis, R.-I. Manabe, A. Hasegawa, S. Chaudhari, S. du Pré, M. Schippers, M. Tagami, J. Ma, Y. Okazaki, M. H. Todd, B. Biersack, V. Masand, A. Verbon, T. Kasukawa, I. Abugessaisa, W. van de Sande, <em>PLOS NTD</em> <strong>2025</strong>, <em>in press</em>.
                        </li>
                        <li>
                            <a href="https://pubs.rsc.org/en/content/articlelanding/2025/md/d5md00427f" class="font-bold text-brand-primary hover:underline block mb-1">Structure–activity Relationships of Fenarimol Analogues with Potent <em>in vitro</em> and <em>in vivo</em> Activity Against <em>Madurella mycetomatis</em>, the Main Causative Agent of Eumycetoma</a>
                            H. P. Duong, D. Melechov, W. Lim, J. Ma, K. Scroggie, L. Rajendra, B. Perry, L. Cruz, P. Rutledge, A. Motion, W van de Sande and M. H. Todd, <em>RSC Med. Chem.</em>, <strong>2025</strong>, <em>16</em>, 6094 - 6108.
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2024 -->
        <div class="year-block group">
            <div onclick="toggleYear('2024')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2024</h2>
                <i id="icon-2024" class="fas fa-chevron-down text-slate-400 chevron rotate"></i>
            </div>
            <div id="content-2024" class="accordion-content active">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li>
                            <span class="font-bold text-slate-900 block mb-1">ABHD2 Activity is Not Required for the Non-genomic Action of Progesterone on Human Sperm</span>
                            O. Arnolds, E. M. Carter, M. Edwards, E. Wigren, E. Homan, P. Ribera, K. Bentley, M. Haraldsson, N. Theo-Emegano, P. Loppnau, M. M. Szewczyk, M. A. Cao, D. Barsyte-Lovejoy, K. Vester, A. Thrun, R. Lesche, J. Münchow, W. F. Zhu, L. Temme, C. Brenker, T. Strünker, M. Sundström, M. H. Todd, A. M. Edwards, C. Tredup, O. Gileadi, <em>submitted</em>. 
                            <a href="https://biorxiv.org/cgi/content/short/2024.12.17.628646v1" class="text-brand-primary font-bold hover:underline ml-1">[Preprint]</a>
                        </li>
                        <li>
                            <a href="https://doi.org/10.1021/acsmedchemlett.4c00131" class="font-bold text-brand-primary hover:underline block mb-1">Open Source Code Contributions to Global Health – the Case of Antimalarial Drug Discovery</a>
                            G. Turon, E. G. Tse, X. Qiu, M. H. Todd and M. Duran-Frigola, <em>ACS Med. Chem. Lett.</em> <strong>2024</strong>, <em>15</em> 1645–1650.
                        </li>
                        <li>
                            <a href="https://www.mdpi.com/1424-8247/17/7/836" class="font-bold text-brand-primary hover:underline block mb-1">Identification of Dihydropyrazolo[1,5-a]pyrazin-4(5H)-ones as Cyclic Products of β-Amidomethyl Vinyl Sulfone Alphavirus Cysteine Protease Inhibitors</a>
                            A. Ghoshal, Á. F. Magalhães, K. H. Asressu, M. A. Hossain, M. H. Todd and T. M. Willson, <em>Pharmaceuticals</em> <strong>2024</strong>, <em>17</em>(7), 836.
                        </li>
                        <li>
                            <a href="https://www.nature.com/articles/s41467-024-45224-z" class="font-bold text-brand-primary hover:underline block mb-1">Reaction Hijacking Inhibition of <em>Plasmodium falciparum</em> Asparagine tRNA Synthetase</a>
                            S. C. Xie, Y. Wang, C. J. Morton, R. D. Metcalfe, C. Dogovski, C. F. A. Pasaje, E. Dunn, M. R. Luth, K. Kumpornsin, E. S Istvan, J. S. Park, K. J. Fairhurst, N. Ketprasit, T. Yeo, O. Yildirim, M. N. Bhebhe, D. M. Klug, P. J. Rutledge, L. C. Godoy, S. Dey, M. L. De Souza, J. L. Siqueira-Neto, Y. Du, T. Puhalovich, M. Amini, G. Shami, D. Loesbanluechai, S. Nie, N. Williamson, G. P. Jana, B. C. Maity, P. Thomson, T. Foley, D. S. Tan, J. C. Niles, B. W. Han, D. E Goldberg, J. Burrows, D. A. Fidock, M. C. S. Lee, E. A. Winzeler, M. D. W. Griffin, M. H. Todd and L. Tilley, <em>Nature Comms</em>. <strong>2024</strong>, <em>15</em>, 937.
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://pubs.acs.org/doi/10.1021/acsinfecdis.3c00286" class="font-bold text-brand-primary hover:underline">Open Source Antibiotics - Simple Diarylimidazoles are Potent Against Methicillin Resistant Staphylococcus Aureus</a><br>D. M. Klug, E. G. Tse, D. G. Silva, Y. Cao, S. A. Charman, J. Chauhan, E. Crighton, M. Dichiara, C. Drake, D. Drewry, F. da Silva Emery, L. Ferrins, L. Graves, E. Hopkins, T. A. C. Kresina, Á. Lorente-Macías, B. Perry, R. Phipps, B. Quiroga, A. Quotadamo, G. Sabatino, A. Sama, A. Schätzlein, Q. J. Simpson, J. Steele, J. Shanu-Wilson, P. Sjö, P. Stapleton, C. Swain, A. Vaideanu, H. Xie, W. Zuercher, M. H. Todd, <em>ACS Infect. Dis.</em> <strong>2023</strong>, <em>9</em>, 2423–2435.</li>
                        <li><a href="https://dx.doi.org/10.1021/acsinfecdis.3c00040" class="font-bold text-brand-primary hover:underline">Structure-property Optimization of a Series of Imidazopyridines for Visceral Leishmaniasis</a><br>M. Dichiara, Q. J. Simpson, A. Quotadamo, H. B. Jalani, A. X. Huang, C. C. Millard, D. M. Klug, E. G. Tse, M. H. Todd, D. Gedder, F. da Silva Emery, J. E. Carlson, S.-L. Zheng, M. Vleminckx, A. Matheeussen, G. Caljon, M. P. Pollastri, P. Sjö, B. Perry, L. Ferrins, <em>ACS Infect. Dis.</em> <strong>2023</strong>, <em>9</em>, 1470–1487.</li>
                        <li><a href="https://pubs.acs.org/doi/abs/10.1021/acschemneuro.2c00498" class="font-bold text-brand-primary hover:underline">Perphenazine-macrocycle Conjugates Rapidly Sequester the Aβ42 Monomer and Prevent Formation of Toxic Oligomers and Amyloid</a><br>S. R. Ball, J. S. P. Adamson, M. A. Sullivan, M. R. Zimmermann, V. Lo, M. Sanz-Hernandez, X. Jiang, A. H. Kwan, A. D. J. McKenzie, E. L. Werry, T. P. J. Knowles, M. Kassiou, G. Meisl, M. H. Todd, P. J. Rutledge, M. Sunde, <em>ACS Chem. Neurosci.</em> <strong>2023</strong>, <em>14</em>, 87-98.</li>
                        <li><a href="https://onlinelibrary.wiley.com/doi/full/10.1002/cbdv.202300151" class="font-bold text-brand-primary hover:underline">Antifungal Activity of Natural Naphthoquinones and Anthraquinones against <em>Madurella mycetomatis</em></a><br>J. Ma, M. H. Todd, W. W. J. van de Sande and B. Biersack, <em>Chem. Biodiversity</em> <strong>2023</strong>, <em>20</em>, e202300151.</li>
                        <li><a href="https://pubs.rsc.org/en/content/articlelanding/2023/md/d2md00441k" class="font-bold text-brand-primary hover:underline">Target 2035–an Update on Private Sector Contributions</a><br>S. Ackloo, A. A. Antolin, J. M. Bartolome, H. Beck, A. N Bullock, U. A. K. Betz, J. Böttcher, P. J. Brown, M. Chaturvedi, A. Crisp,  D. Daniels,  J. Dreher, K. Edfeldt, A. M. Edwards, U. Egner, J. Elkins, C. Fischer, T. Glendorf, S. Goldberg, I. V. Hartung, A. Hillisch, E. Homan, S. Knapp, M. Koester, A. Kraemer, J. Llaveria, U. Lessel, S. Lindemann, L. Linderoth, H. Matsui, M. Michel, F. Montel, A. Mueller-Fahrnow, S, Mueller, D. R. Owen, K. S. Saikatendu, V. Santhakumar, W. Sanderson, C. Scholten, M. Schapira, S. Sharma, B. Shireman, M. Sundström, M. H. Todd, C. Tredup, J. Veneble, T. M. Willson, and C. H Arrowsmith, <em>RSC Med. Chem.</em> <strong>2023</strong>.</li>
                        <li>
                            <span class="font-bold text-slate-900">Metallaphotoredox-Catalyzed Decarboxylative sp3–sp3 Coupling with Iso(thio)chroman and Tetrahydroisoquinoline Cores</span><br>
                            P. A. King, P. J. Rutledge and M. H. Todd, <em>submitted</em>. 
                            <a href="https://chemrxiv.org/engage/chemrxiv/article-details/62ab247f1fdc34fd493beda4" class="text-brand-primary font-bold hover:underline">[Preprint]</a>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1038/s41570-022-00363-z" class="font-bold text-brand-primary hover:underline">CACHE (Critical Assessment of Computational Hit-finding Experiments): A Public-private Partnership Benchmarking Initiative to Enable the Development of Computational Methods for Hit-finding</a><br>S. Ackloo, R. Al-awar, R. E. Amaro, C. H. Arrowsmith, H. Azevedo, R. A. Batey, Y. Bengio, U. A. K. Betz, C. G. Bologa, J. D. Chodera, W. D. Cornell, I. Dunham, G. F. Ecker, K. Edfeldt, A. M. Edwards, M. K. Gilson, C. R. Gordijo, G. Hessler, A. Hillisch, A. Hogner, J. J. Irwin, J. M. Jansen, D. Kuhn, A. R. Leach, A. A. Lee, U. Lessel, J. Moult, I. Muegge, T. I. Oprea, B. G. Perry, P. Riley, K. S. Saikatendu, V. Santhakumar, M. Schapira, C. Scholten, M. H. Todd, M. Vedadi, A. Volkamer, T. M. Willson, <em>Nat. Rev. Chem.</em> <strong>2022</strong>.</li>
                        <li><a href="https://doi.org/10.1039/D1MD00228G" class="font-bold text-brand-primary hover:underline">Target 2035 – Update on the Quest for a Probe for every Protein</a><br>S. Müller, S. Ackloo, A. Al Chawaf, B. Al-Lazikani, A. Antolin, J. B Baell, H. Beck, S. Beedie, U. A. K. Betz, G. A. Bezerra, P. E Brennan, D. Brown, P. J Brown, A. N Bullock, A. J Carter, A. Chaikuad, M. Chaineau, A. Ciulli, I. Collins, J. Dreher, D. Drewry, K. Edfeldt, A. M. Edwards, U. Egner, S. V. Frye, S. M. Fuchs, M. D. Hall, I. V. Hartung, A. Hillisch, S. H. Hitchcock, E. Homan, N. Kannan, J. R. Kiefer, S. Knapp, M. Kostic, S. Kubicek, A. R. Leach, S. Lindemann, B. D. Marsden, H. Matsui, J. L. Meier, D. Merk, M. Michel, M. R. Morgan, A. Mueller-Fahrnow, D. R. Owen, B. G. Perry, S. H. Rosenberg, K. S. Saikatendu, M. Schapira, C. Scholten, S. Sharma, A. Simeonov, M. Sundström, G. Superti-Furga, M. H. Todd, C. Tredup, M. Vedadi, F. von Delft, T. M. Willson, G. E. Winter, P. Workman and C. H Arrowsmith, <em>RSC Med. Chem.</em> <strong>2021</strong>.</li>
                        <li><a href="https://journals.plos.org/plosntds/article?id=10.1371/journal.pntd.0010159" class="font-bold text-brand-primary hover:underline">Screening the Pandemic Response Box Identified Benzimidazole Carbamates, Olorofim and Ravuconazole as Promising Drug Candidates for the Treatment of Eumycetoma</a><br>W. Lim, B. Nyuykonge, K. Eadie, M. Konings, J. Smeets, A. Fahal, A. Bonifaz, M. Todd, B. Perry, K. Samby, J. Burrows, A. Verbon and W. van de Sande <em>PLoS NTD</em> <strong>2022</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2021 -->
        <div class="year-block group">
            <div onclick="toggleYear('2021')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2021</h2>
                <i id="icon-2021" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2021" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1039/D1DT03539H" class="font-bold text-brand-primary hover:underline">Platinum Binding Preferences Dominate the Binding of Novel Polyamide Amidine Anthraquinone Platinum(II) Complexes to DNA</a><br>A. T. S. Lo, J. K. Chen, V. Murray, M. H. Todd and T. W. Hambley, <em>Dalton Trans.</em> <strong>2021</strong>.</li>
                        <li><a href="https://doi.org/10.1021/acs.jmedchem.1c00313" class="font-bold text-brand-primary hover:underline">An Open Drug Discovery Competition: Experimental Validation of Predictive Models in a Series of Novel Antimalarials</a><br>E. G. Tse, L. Aithani, M. Anderson, J. Cardoso-Silva, G. Cincilla, G. J. Conduit, M. Galushka, D. Guan, I. Hallyburton, B. W. J. Irwin, K. Kirk, A. M. Lehane, J. C. R. Lindblom, R. Lui, S. Matthews, J. McCulloch, A. Motion, H. L. Ng, M. Öeren, M. N. Robertson, V. Spadavecchio, V. A. Tatsis, W. P. van Hoorn, A. D. Wade, T. M. Whitehead, P. Willis and M. H. Todd, <em>J. Med. Chem.</em> <strong>2021</strong>.</li>
                        <li><a href="https://doi.org/10.1007/s00775-020-01847-3" class="font-bold text-brand-primary hover:underline">Novel Polyamide Amidine Anthraquinone Platinum(II) Complexes: Cytotoxicity, Cellular Accumulation, and Fluorescence Distributions in 2D and 3D Cell Culture Models</a><br>A, T. S. Lo, N. S. Bryce, A. V. Klein, M. H. Todd and T. W. Hambley, <em>J. Biol. Inorg. Chem.</em> <strong>2021</strong>.</li>
                        <li><a href="http://dx.doi.org/10.1039/d0dt03736b" class="font-bold text-brand-primary hover:underline">Copper(II) Complexes of <em>N</em>-Propargyl Cyclam Ligands Reveal a Range of Coordination Modes and Colours, and Unexpected Reactivity</a><br>A. J. Counsell, M. Yu, M. Shi, A. T. Jones, J. M. Batten, P. Turner, M. H. Todd and P. J. Rutledge, <em>Dalton Trans.</em> <strong>2021</strong>.</li>
                        <li><a href="https://doi.org/10.1021/acs.jchemed.1c00289" class="font-bold text-brand-primary hover:underline">Molecular Docking with Open Access Software: Development of an Online Laboratory Handbook and Remote Workflow for Chemistry and Pharmacy Master's Students to Undertake Computer-Aided Drug Design</a><br>B. Clent, Y. Wang, H. Britton, F. Otto, C. Swain, M. H. Todd, J. Wilden and A. Tabor, <em>J. Chem. Ed.</em> <strong>2021</strong>.</li>
                        <li><a href="https://wellcomeopenresearch.org/articles/6-146/v1" class="font-bold text-brand-primary hover:underline">There is No Market for New Antibiotics: This Allows an Open Approach to Research and Development</a><br>D. M. Klug, F. I. M. Idiris, M. A. T. Blaskovich, F. von Delft, C. G. Dowson, C. Kirchhelle, A. P. Roberts, A. C. Singer and M. H. Todd, <em>Wellcome Open Res.</em> <strong>2021</strong>.</li>
                        <li><a href="https://doi.org/10.1039/D0CS01065K" class="font-bold text-brand-primary hover:underline">A Critical Overview of Computational Approaches Employed for COVID-19 Drug Discovery</a><br>E. N. Muratov, R. Amaro, C. H. Andrade, N. Brown, S. Ekins, D. Fourches, O. Isayev, D. Kozakov, J. Medina-Franco, K. M. Merz, T. I. Oprea, V. Poroikov, G. Schneider, M. H. Todd, A. Varnek, D. A. Winkler, A. Zakharov, A. Cherkasov and A. Tropsha, <em>Chem. Soc. Rev.</em> <strong>2021</strong>.</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://f1000research.com/articles/9-1043" class="font-bold text-brand-primary hover:underline">Open Science Approaches to COVID-19</a><br>E. G. Tse, D. M. Klug and M. H. Todd, <em>F1000Research</em> <strong>2020</strong>.</li>
                        <li><a href="https://pubs.acs.org/doi/10.1021/acs.joc.0c01045" class="font-bold text-brand-primary hover:underline">tele-Substitution Reactions in the Synthesis of a Promising Class of 1,2,4-Triazolo(4,3-a)pyrazine-Based Antimalarials</a><br>M. Korsik, E. G. Tse, D. G. Smith, W. Lewis, P. J. Rutledge, and M. H. Todd, <em>J. Org. Chem.</em> <strong>2020</strong>.</li>
                        <li><a href="https://doi.org/10.1021/acs.jmedchem.0c00746" class="font-bold text-brand-primary hover:underline">Non-Classical Phenyl Bioisosteres as Effective Replacements in a Series of Novel Open Source Antimalarials</a><br>E. G. Tse, S. D. Houston, C. M. Williams, G. P. Savage, L. M. Rendina, I. Hallyburton, M. Anderson, R. Sharma, G. S. Walker, R. S. Obach and M. H. Todd, <em>J. Med. Chem.</em> <strong>2020</strong>.</li>
                        <li><a href="https://doi.org/10.1039/C9SC06460E" class="font-bold text-brand-primary hover:underline">Metal Complexes as a Promising Source for New Antibiotics</a><br>A. Frei, J. Zuegg, A. G. Elliott, M. Baker, S. Braese, C. Brown, F. Chen, C. Dowson, G. Dujardin, N. Jung, A. P. King, A. M. Mansour, M. Massi, J. Moat, H. A. Mohamed, A. K. Renfrew, P. J. Rutledge, P. J. Sadler, M. H. Todd, C. E. Willans, J. J. Wilson, M. A. Cooper and M. A. T. Blaskovich, <em>Chem. Sci.</em> <strong>2020</strong>.</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1002/cmdc.201900565" class="font-bold text-brand-primary hover:underline">Six Laws of Open Source Drug Discovery</a><br>M. H. Todd, <em>ChemMedChem</em> <strong>2019</strong>.</li>
                        <li><a href="https://doi.org/10.1186/s12936-019-2724-z" class="font-bold text-brand-primary hover:underline">The Past, Present and Future of Anti-Malarial Medicines</a><br>E. G. Tse, M. Korsik and M. H. Todd, <em>Malaria J.</em> <strong>2019</strong>.</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1021/acs.jmedchem.8b01533" class="font-bold text-brand-primary hover:underline">Easy-to-Synthesize Spirocyclic Compounds Possess Remarkable <em>In Vivo</em> Activity Against <em>Mycobacterium Tuberculosis</em></a><br>A. Guardia, J. Baiget, M. Cacho, A. Pérez, M. Ortega-Guerra, W. Nxumalo, S. D. Khanye, J. Rullas, F. Ortega, E. Jiménez, E. Pérez-Herrán, M. T. Fraile-Gabaldón, J. Esquivias, R. Fernández, E. Porras-De Francisco, L. Encinas, M. Alonso, I. Giordano, C. Rivero, J. Miguel-Siles, J. G. Osende, K. A. Badiola, P. J. Rutledge, M. H. Todd, M. Remuiñán and C. Alemparte, <em>J. Med. Chem.</em> <strong>2018</strong>.</li>
                        <li><a href="https://doi.org/10.3389/fphar.2018.01035" class="font-bold text-brand-primary hover:underline">Experimentally Validated Pharmacoinformatics Approach to Predict hERG Inhibition Potential of New Chemical Entities</a><br>S. Munawar, M. J Windley, E. G. Tse, M. H. Todd, A. Hill, J. Vandenberg and I. Jabeen, <em>Frontiers Pharmacol.</em> <strong>2018</strong>.</li>
                        <li><a href="https://doi.org/10.1371/journal.pntd.0006437" class="font-bold text-brand-primary hover:underline">Addressing the Most Neglected Diseases through an Open Research Model: the Discovery of Fenarimols as Novel Drug Candidates for Eumycetoma</a><br>W. Lim, Y. Melse, M. Konings, H. P. Duong, K. Eadie, B. Laleu, B. Perry, M. H. Todd, J.-R. Ioset, W. W. J. van de Sande, <em>PLoS NTD</em> <strong>2018</strong>.</li>
                        <li><a href="https://doi.org/10.1021/acs.jmedchem.7b01569" class="font-bold text-brand-primary hover:underline">Anti-Tubercular <em>bis</em>-Substituted Cyclam Derivatives: Structure-Activity Relationships and <em>In Vivo</em> Studies</a><br>M. Spain, J. K.-H. Wong, G. Nagalingam, J. M. Batten, E. Hortle, S. Oehlers, X.-F. Jiang, H. E. Murage, J. T. Orford, P. Crisologo, J. A. Triccas, P. J. Rutledge and M. H. Todd, <em>J. Med. Chem.</em> <strong>2018</strong>.</li>
                        <li><a href="https://doi.org/10.1002/mrc.4669" class="font-bold text-brand-primary hover:underline">The C6H6 NMR Repository: an Integral Solution to Control the Flow of your Data from the Magnet to the Public</a><br>L. Patiny, M. Zasso, D. Kostro, A. Bernal, A. M. Castillo, A. Bolaños, M. A. Asencio, N. Pellet, M. H. Todd, N. Schloerer, S. Kuhn, E. Holmes, S. Javor and J. Wist, <em>Mag. Res. Chem.</em> <strong>2018</strong>.</li>
                        <li><a href="https://doi.org/10.1002/chem.201703488" class="font-bold text-brand-primary hover:underline">Molecular Switches for any pH: A Systematic Study of the Versatile Coordination Behaviour of Cyclam Scorpionands</a><br>Y. H. Lau, J. K. Clegg, J. R. Price, R. B. Marquart, M. H. Todd and P. J. Rutledge, <em>Chem. Eur. J.</em> <strong>2018</strong>.</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1002/chem.201700430" class="font-bold text-brand-primary hover:underline"><em>N</em>-Aryl Groups are Ubiquitous in Cross Dehydrogenative Couplings Because They Stabilize Reactive Intermediates</a><br>A. S.-K. Tsang, A. S. K. Hashmi, P. Comba, M. Kerscher, B. Chan and M. H. Todd, <em>Chem. Eur. J.</em> <strong>2017</strong>.</li>
                        <li><a href="https://doi.org/10.1371/journal.pmed.1002276" class="font-bold text-brand-primary hover:underline">An Open Source Pharma Roadmap</a><br>M. Balasegaram, P. Kolb, J. McKew, J. Menon, P. Olliaro, T. Sablinski, Z. Thomas, M. H. Todd, E. Torreele and J. Wilbanks, <em>PLoS Med.</em> <strong>2017</strong>.</li>
                        <li><a href="https://doi.org/10.3390/molecules22020200" class="font-bold text-brand-primary hover:underline">Recent Advances in Macrocyclic Fluorescent Probes for Ion Sensing</a><br>J. K.-H. Wong, M. H. Todd and P. J. Rutledge, <em>Molecules</em> <strong>2017</strong>.</li>
                        <li><a href="https://doi.org/10.1002/ejic.201601474" class="font-bold text-brand-primary hover:underline">Selective Displacement of a Scorpionand Triazole Ligand from Metallo-Cyclam Complexes Visualised Using NMR Spectroscopy</a><br>J. K.-H. Wong, N. Proschogo, M. H. Todd and P. J. Rutledge, <em>Eur. J. Inorg. Chem.</em> <strong>2017</strong>.</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1021/acscentsci.6b00086" class="font-bold text-brand-primary hover:underline">Open Source Drug Discovery: Highly Potent Antimalarial Compounds Derived from the Tres Cantos Arylpyrroles</a><br>A. E. Williamson, P. M. Ylioja, M. N. Robertson, Y. Antonova-Koch, V. Avery, J. B. Baell, H. Batchu, S. Batra, J. N. Burrows, S. Bhattacharyya, F. Calderon, S. A. Charman, J. Clark, B. Crespo, M. Dean, S. L. Debbert, M. Delves, A. S. M. Dennis, F. Deroose, S. Duffy, S. Fletcher, G. Giaever, I. Hallyburton, F.-J. Gamo, M. Gebbia, R. K. Guy, Z. Hungerford, K. Kirk, M. J. Lafuente-Monasterio, A. Lee, S. Meister, C. Nislow, J. P. Overington, G. Papadatos, L. Patiny, J. Pham, S. A. Ralph, A. Ruecker, E. Ryan, C. Southan, K. Srivastava, C. Swain, M. J. Tarnowski, P. Thomson, P. Turner, I. M. Wallace, T. N. C. Wells, K. White, L. White, P. Willis, E. A. Winzeler, S. Wittlin, and M. H. Todd, <em>ACS Cent. Sci.</em> <strong>2016</strong>.</li>
                        <li><a href="https://doi.org/10.3762/bjoc.12.239" class="font-bold text-brand-primary hover:underline">A Direct Method for the <em>N</em>-Tetraalkylation of Azamacrocycles</a><br>A. J. Counsell, A. T. Jones, M. H. Todd and P. J. Rutledge, <em>Beilstein J. Org. Chem.</em> <strong>2016</strong>.</li>
                        <li><a href="https://doi.org/10.3897/rio.2.e9995" class="font-bold text-brand-primary hover:underline">SCINDR - The SCience INtroDuction Robot that will Connect Open Scientists</a><br>C. Smith, M. H. Todd, L. Patiny, C. Swain, C. Southan, A. E. Williamson and A. Clark, <em>Res. Ideas Outcomes</em> <strong>2016</strong>.</li>
                        <li><a href="https://doi.org/10.1002/open.201600010" class="font-bold text-brand-primary hover:underline">Synthesis and Evaluation of 1,8-Disubstituted-cyclam/naphthalimide Conjugates as Probes for Metal Ions</a><br>J. K.-H. Wong, S. Ast, M. Yu, R. Flehr, A. J. Counsell, P. Turner, P. Crisologo, M. H. Todd and P. J. Rutledge, <em>ChemistryOpen</em> <strong>2016</strong>.</li>
                        <li><a href="https://doi.org/10.1021/acs.jmedchem.6b00432" class="font-bold text-brand-primary hover:underline">Non-Toxic Metal-Cyclam Complexes, a New Class of Compounds with Potency Against Drug-Resistant <em>Mycobacterium tuberculosis</em></a><br>M. Yu, G. Nagalingam, S. Ellis, E. Martinez, V. Sintchenko, M. Spain, P. J. Rutledge, M. H. Todd and J. Triccas, <em>J. Med. Chem.</em> <strong>2016</strong>.</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.3762/bjoc.11.6" class="font-bold text-brand-primary hover:underline">Efficient Deprotection of <em>F</em>-BODIPY Derivatives: Removal of BF2 using Brønsted Acids</a><br>M. Yu, J. K.-H. Wong, C. Tang, P. Turner, M. H. Todd and P. J. Rutledge, <em>Beilstein J. Org. Chem.</em> <strong>2015</strong>.</li>
                        <li><a href="https://doi.org/10.1002/ejic.201402811" class="font-bold text-brand-primary hover:underline">Using Click Chemistry to Tune the Properties and the Fluorescence Response Mechanism of Structurally Similar Probes for Metal Ions</a><br>S. Ast, S. Kuke, P. J. Rutledge and M. H. Todd, <em>Eur. J. Inorg. Chem.</em> <strong>2015</strong>.</li>
                        <li><a href="https://doi.org/10.1039/C4SC02128B" class="font-bold text-brand-primary hover:underline">Experiences with LabTrove, a Researcher-Centric ELN</a><br>K. A. Badiola, C. Bird, W. S. Brocklesby, J. Casson, R. T. Chapman, S. J. Coles, J. R. Cronshaw, A. Fisher, J. G. Frey, D. Gloria, M. C. Grossel, D. B. Hibbert, L. K. Mapp, B. Matthews, A. Milsted, R. S. Minns, K. T. Mueller, K. Murphy, C. Neylon, T. Parkinson, R. Quinnell, J. S. Robinson, M. N. Robertson, M. Robins, E. Springate, G. Tizzard, M. H. Todd, A. E. Williamson, C. Willoughby, E. Yang and P. M. Ylioja, <em>Chem. Sci.</em> <strong>2015</strong>.</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1371/journal.pone.0111782" class="font-bold text-brand-primary hover:underline">Efficient Synthesis and Anti-Tubercular Activity of a Series of Spirocycles: An Exercise in Open Science</a><br>K. A. Badiola, D. H. Quan, J. A. Triccas and M. H. Todd, <em>PLoS ONE</em> <strong>2014</strong>.</li>
                        <li><a href="https://doi.org/10.1039/C4CP03914A" class="font-bold text-brand-primary hover:underline">pH-Responsive Quantum Dots (RQDs) that Combine a Fluorescent Nanoparticle with a pH-Sensitive Dye</a><br>S. Ast, P. J. Rutledge and M. H. Todd, <em>Phys. Chem. Chem. Phys.</em> <strong>2014</strong>.</li>
                        <li><a href="https://doi.org/10.1039/C4MT00122B" class="font-bold text-brand-primary hover:underline">Neuroprotective Peptide-Macrocycle Conjugates Reveal Complex Structure-Activity Relationships in their Interactions with Amyloid ß</a><br>M. Yu, T. M. Ryan, S. Ellis, A. I. Bush, J. A. Triccas, P. J. Rutledge and M. H. Todd, <em>Metallomics</em> <strong>2014</strong>.</li>
                        <li><a href="https://doi.org/10.1039/C4FD00110A" class="font-bold text-brand-primary hover:underline">The Properties and Performance of a pH-Responsive Functionalised Nanoparticle</a><br>S. Ast, P. J. Rutledge and M. H. Todd, <em>Faraday Discuss.</em> <strong>2014</strong>.</li>
                        <li><a href="https://doi.org/10.1128/AAC.02741-14" class="font-bold text-brand-primary hover:underline">Activity of Praziquantel Enantiomers and Main Metabolites against <em>Schistosoma mansoni</em></a><br>I. Meister, K. Ingram-Sieber, N. Cowan, M. H. Todd, M. N. Robertson, C. Meli, M. Patra, G. Gasser and J. Keiser, <em>Antimicrob. Ag. Chemother.</em> <strong>2014</strong>.</li>
                        <li>
                            <a href="http://au.wiley.com/WileyCDA/WileyTitle/productCd-3527330453.html" class="font-bold text-brand-primary hover:underline">Separation of Enantiomers: Synthetic Methods</a><br>M. H. Todd, Ed. Wiley-VCH, <strong>2014</strong>.
                            <ul class="list-disc pl-5 mt-2 space-y-1 text-xs">
                                <li><a href="http://onlinelibrary.wiley.com/doi/10.1002/9783527650880.ch1/summary" class="text-brand-primary font-bold hover:underline">Chapter 1: Introduction: A Survey of How and Why to Separate Enantiomers</a>, M. H. Todd.</li>
                                <li><a href="http://onlinelibrary.wiley.com/doi/10.1002/9783527650880.ch7/summary" class="text-brand-primary font-bold hover:underline">Chapter 7: Rare, Neglected and Potential Synthetic Methods for the Separation of Enantiomers</a>, M. H. Todd.</li>
                                <li><a href="http://dx.doi.org/10.1002/anie.201411359" class="text-brand-primary font-bold hover:underline">Review</a> by Richard Kellogg in <em>Angewandte Chemie</em> described it as "a thoughtfully constructed, and well-written book full of useful information"</li>
                            </ul>
                        </li>
                        <li><a href="https://doi.org/10.1039/9781782620082-00254" class="font-bold text-brand-primary hover:underline">Mechanisms of Cross-Dehydrogenative-Coupling Reactions</a><br>A. S.-K. Tsang, S. J. Park and M. H. Todd, in <em>From C–H to C–C Bonds: Cross Dehydrogenative Coupling</em>, C.-J. Li, Ed., <strong>2014</strong>, Royal Society of Chemistry, Cambridge.</li>
                        <li><a href="https://doi.org/10.1371/journal.pone.0100761" class="font-bold text-brand-primary hover:underline">Incorporating a Piperidinyl Group in the Fluorophore Extends the Fluorescence Lifetime of Click-Derived Cyclam-Naphthalimide Conjugates</a><br>M. Yu, S. Ast, Q. Yu, A. T. S. Lo, R. Flehr, M. H. Todd and P. J. Rutledge, <em>PLoS ONE</em> <strong>2014</strong>.</li>
                        <li><a href="https://doi.org/10.1017/S0031182013001121" class="font-bold text-brand-primary hover:underline">Open Source Drug Discovery – A Limited Tutorial</a><br>M. N. Robertson, P. M. Ylioja, A. E. Williamson, M. Woelfle, M. Robins, K. A. Badiola, P. Willis, P. Olliaro, T. N. C. Wells and M. H. Todd, <em>Parasitology</em> <strong>2014</strong>.</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1021/jm401287m" class="font-bold text-brand-primary hover:underline"><em>In Vitro</em> Metabolic Profile and <em>In Vivo</em> Antischistosomal Activity Studies of (η<sup>6</sup>-Praziquantel)Cr(CO)<sub>3</sub> Derivatives</a><br>M. Patra, K. Ingram, A. Leonidova, V. Pierroz, S. Ferrari, M. N. Robertson, M. H. Todd, J. Keiser and G. Gasser, <em>J. Med. Chem.</em> <strong>2013</strong>.</li>
                        <li><a href="https://doi.org/10.1016/j.tet.2013.07.044" class="font-bold text-brand-primary hover:underline">Synthesis of Elongated Cavitands via Click Reactions and their use as Chemosensors</a><br>Z. Csók, T. Kégl, Y. Li, R. Skoda-Földes, L. Kiss, S. Kunsági-Máté, M. H. Todd and L. Kollár, <em>Tetrahedron</em> <strong>2013</strong>.</li>
                        <li><a href="https://doi.org/10.1371/journal.pcbi.1003244" class="font-bold text-brand-primary hover:underline">Ten Simple Rules for Cultivating Open Science and Collaborative R&D</a><br>H. Masum, A. Rao, B. M. Good, M. H. Todd, A. M. Edwards, L. Chan, B. A. Bunin, A. I. Su, Z. Thomas and P. E. Bourne, <em>PLoS Comp. Biol.</em> <strong>2013</strong>.</li>
                        <li><a href="https://doi.org/10.1039/C3OB40503F" class="font-bold text-brand-primary hover:underline">Enhancing the Usefulness of Cross Dehydrogenative Coupling Reactions with a Removable Protecting Group</a><br>A. S.-K. Tsang, K. Ingram, J. Keiser, B. Hibbert and M. H. Todd, <em>Org. Biomol. Chem.</em> <strong>2013</strong>.</li>
                        <li><a href="https://doi.org/10.1002/open.201300014" class="font-bold text-brand-primary hover:underline">Incorporation of Bulky and Cationic Cyclam-Triazole Moieties into Marimastat Can Generate Potent MMP Inhibitory Activity Without Inducing Cytotoxicity</a><br>M. Yu, N. H. Lim, S. Ellis, H. Nagase, J. A. Triccas, P. J. Rutledge and M. H. Todd, <em>ChemistryOpen</em> <strong>2013</strong>.</li>
                        <li><a href="https://doi.org/10.1002/cbic.201200637" class="font-bold text-brand-primary hover:underline">A Fluorescent "Allosteric Scorpionate" Complex Visualizes a Biological Recognition Event</a><br>M. Yu, P. J. Rutledge and M. H. Todd, <em>ChemBioChem</em> <strong>2013</strong>.</li>
                        <li><span class="font-bold text-slate-900">The Synaptic Leap: Open Science Combating Disease</span><br>P. Parker, B. Schwendimann, K. Thompson and M. H. Todd, in <em>Architecture of Productive Learning Networks</em>, L. Carvalho and P. Goodyear, Eds., <strong>2013</strong>, Routledge (ISBN 978-0-415-81655-7)</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1002/ejic.201201072" class="font-bold text-brand-primary hover:underline">Reversing the Triazole Topology in a Cyclam-Triazole-Dye Ligand Gives a 10-fold Brighter Signal Response to Zn<sup>2+</sup> in Aqueous Solution</a><br>S. Ast, P. J. Rutledge and M. H. Todd, <em>Eur. J. Inorg. Chem.</em> <strong>2012</strong>.</li>
                        <li><a href="https://doi.org/10.1371/journal.pone.0047224" class="font-bold text-brand-primary hover:underline">The Outcome of the Oxidations of Unusual Enediamide Motifs is Governed by the Stabilities of the Intermediate Iminium Ions</a><br>M. Ahamed, B. Chan and M. H. Todd, <em>PLoS ONE</em>, <strong>2012</strong>.</li>
                        <li><a href="https://doi.org/10.1002/adsc.201200558" class="font-bold text-brand-primary hover:underline">The First Catalytic, Enantioselective Aza-Henry Reaction of an Unactivated Cyclic Imine</a><br>N. R. Amarasinghe, P. Turner and M. H. Todd, <em>Adv. Synth. Catal.</em> <strong>2012</strong>.</li>
                        <li><a href="https://doi.org/10.1021/jo2021373" class="font-bold text-brand-primary hover:underline">Oxidative Arylation of Isochroman</a><br>S. J. Park, J. Price and M. H. Todd, <em>J. Org. Chem.</em> <strong>2012</strong>.</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1021/ic2020012" class="font-bold text-brand-primary hover:underline">Copper, Nickel and Zinc Cyclam-Amino Acid and Cyclam-Peptide Complexes may be Synthesized with “Click” Chemistry and are Noncytotoxic</a><br>M. Yu, J. Price, P. Jensen, T. Shelper, C. Lovitt, S. Duffy, L. Windus, V. Avery, P. J. Rutledge and M. H. Todd, <em>Inorg. Chem.</em> <strong>2011</strong>.</li>
                        <li><a href="https://doi.org/10.1038/nchem.1149" class="font-bold text-brand-primary hover:underline">Open Science is a Research Accelerator</a><br>M. Woelfle, P. Olliaro and M. H. Todd, <em>Nat. Chem.</em> <strong>2011</strong>.</li>
                        <li><a href="https://doi.org/10.1371/journal.pntd.0001260" class="font-bold text-brand-primary hover:underline">Resolution of Praziquantel</a><br>M. Woelfle, J.-P. Seerden, J. de Gooijer, K. Pouwer, P. Olliaro and M. H. Todd, <em>PLoS Negl. Trop. Dis.</em> <strong>2011</strong>.</li>
                        <li><a href="https://doi.org/10.1371/journal.pone.0017446" class="font-bold text-brand-primary hover:underline">Polyamide-Scorpion Cyclam Lexitropsins Selectively Bind AT-Rich DNA Independently of the Nature of the Coordinated Metal</a><br>A. T. S. Lo, N. K. Salam, D. E. Hibbs, P. J. Rutledge and M. H. Todd, <em>PLoS One</em> <strong>2011</strong>.</li>
                        <li><a href="https://doi.org/10.1039/C0CS00143K" class="font-bold text-brand-primary hover:underline">Chemical Sensors that Incorporate Click-Derived Triazoles</a><br>Y. H. Lau, P. J. Rutledge, M. Watkinson and M. H. Todd, <em>Chem. Soc. Rev.</em> <strong>2011</strong>.</li>
                        <li><a href="https://doi.org/10.1351/PAC-CON-11-01-01" class="font-bold text-brand-primary hover:underline">A Oxidative Carbon-Carbon Bond-Forming Reaction Proceeds via an Isolable Iminium Ion</a><br>A. S.-K. Tsang, P. Jensen, J. M. Hook, A. S. K. Hashmi and M. H. Todd, <em>Pure Appl. Chem</em>. <strong>2011</strong>.</li>
                        <li><a href="https://doi.org/10.1021/ed100867m" class="font-bold text-brand-primary hover:underline">A Treasure Hunt for Chemistry</a><br>A. J. Bridgeman, R. Connor, P. J. Rutledge and M. H. Todd, <em>J. Chem. Ed.</em> <strong>2011</strong>.</li>
                        <li><a href="https://doi.org/10.1002/chem.201002477" class="font-bold text-brand-primary hover:underline">A Click Fluorophore Sensor that can Distinguish Cu<sup>II</sup> and Hg<sup>II</sup> via Selective Anion-Induced Demetallation</a><br>Y. H. Lau, J. Price, M. H. Todd and P. J. Rutledge, <em>Chem. Eur. J.</em> <strong>2011</strong>.</li>
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
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1071/CH10342" class="font-bold text-brand-primary hover:underline">Gold Catalysis: Reactions of Organogold Compounds with Electrophiles</a><br>A. S. K. Hashmi, T. D. Ramamurthi, M. H. Todd, A. S.-K. Tsang and K. Graf, <em>Aust, J. Chem.</em> <strong>2010</strong>.</li>
                        <li><a href="https://doi.org/10.1002/ejoc.201000955" class="font-bold text-brand-primary hover:underline">Aza-Henry Reactions of 3,4-Dihydroisoquinoline</a><br>M. Ahamed, T. Thirukkumaran, W. Y. Leung, P. Jensen, J. Schroers and M. H. Todd, <em>Eur. J. Org. Chem.</em> <strong>2010</strong>.</li>
                        <li><a href="https://doi.org/10.1002/ejoc.201000877" class="font-bold text-brand-primary hover:underline">Catalytic, Asymmetric Additions of Carbon-Centered Nucleophiles to Nitrogen-Containing Heterocycles</a><br>M. Ahamed and M. H. Todd, <em>Eur. J. Org. Chem.</em> <strong>2010</strong>.</li>
                        <li><a href="https://doi.org/10.1021/ic901939x" class="font-bold text-brand-primary hover:underline">Cyclam-based "Clickates": Homogeneous and Heterogeneous Fluorescent Sensors for Zn(II)</a><br>E. Tamanini, K. Flavin, M. Motevalli, S. Piperno, L. A. Gheber, M. H. Todd and M. Watkinson, <em>Inorg. Chem.</em> <strong>2010</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2009 -->
        <div class="year-block group">
            <div onclick="toggleYear('2009')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2009</h2>
                <i id="icon-2009" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2009" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.3762/bjoc.5.67" class="font-bold text-brand-primary hover:underline">Can We Measure Catalyst Efficiency in Asymmetric Chemical Reactions? A Theoretical Approach</a><br>S. El-Fayyoumy, M. H. Todd and C. J. Richards, <em>Beilstein J. Org. Chem.</em> <strong>2009</strong>.</li>
                        <li><a href="https://doi.org/10.1038/nbt0409-320" class="font-bold text-brand-primary hover:underline">Kernel for Tropical Disease Initiative</a><br>L. Ortí, R. J. Carbajo, U. Pieper, N. Eswar, S. M. Maurer, A. K. Rai, G. Taylor, M. H. Todd, A. Pineda-Lucena, A. Sali and M. A. Marti-Renom, <em>Nature Biotech.</em> <strong>2009</strong>.</li>
                        <li><a href="https://doi.org/10.1002/9783527626816.ch16" class="font-bold text-brand-primary hover:underline">Chemotherapeutic Development Strategies for Schistosomiasis</a><br>C. R. Caffrey, D. L. Williams, M. H. Todd, D. L. Nelson, J. Keiser and J. Utzinger, in <em>Drug Discovery in Infectious Diseases: from Molecular Targets to Drug Candidates</em>, P. M. Selzer, Ed., <strong>2009</strong>, Wiley-VCH, Weinheim.</li>
                        <li><a href="https://doi.org/10.1002/chem.200802425" class="font-bold text-brand-primary hover:underline">Responsive Metal Complexes: A Click-Based "Allosteric Scorpionate" Complex Permits the Detection of a Biological Recognition Events by EPR/ENDOR Spectroscopy</a><br>E. Tamanini, S. E. J. Rigby, M. Motevalli, M. H. Todd and M. Watkinson, <em>Chem. Eur. J.</em> <strong>2009</strong>.</li>
                        <li><a href="https://doi.org/10.1021/ic8017634" class="font-bold text-brand-primary hover:underline">A Synthetically Simple, Click-generated Cyclam-based Zinc(II) Sensor</a><br>E. Tamanini, A. Katewa, L. M. Sedger, M. H. Todd and M. Watkinson, <em>Inorg. Chem.</em> <strong>2009</strong>.</li>
                        <li><a href="https://doi.org/10.1371/journal.pntd.0000418" class="font-bold text-brand-primary hover:underline">A Kernel for Open Source Drug Discovery in Tropical Diseases</a><br>L. Ortí, R. J. Carbajo, U. Pieper, N. Eswar, S. M. Maurer, A. K. Rai, G. Taylor, M. H. Todd, A. Pineda-Lucena, A. Sali and M. A. Marti-Renom, <em>PLoS Negl. Trop. Dis.</em> <strong>2009</strong>.</li>
                        <li><a href="https://doi.org/10.1016/j.tetlet.2008.12.101" class="font-bold text-brand-primary hover:underline">Facile Synthesis of Vicinal Diamines via Oxidation of <em>N</em>-phenyltetrahydroisoquinolines with DDQ</a><br>A.-S. K. Tsang and M. H. Todd, <em>Tetrahedron Lett.</em> <strong>2009</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2008 -->
        <div class="year-block group">
            <div onclick="toggleYear('2008')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2008</h2>
                <i id="icon-2008" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2008" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1016/j.bmcl.2008.03.045" class="font-bold text-brand-primary hover:underline">Synthesis and DNA Binding Ability of Cyclam-Amino Acid Conjugates</a><br>A. V. Ramana, M. Watkinson and M. H. Todd, <em>Bioorg. Med. Chem. Lett.</em> <strong>2008</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2007 -->
        <div class="year-block group">
            <div onclick="toggleYear('2007')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2007</h2>
                <i id="icon-2007" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2007" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1021/jo071175v" class="font-bold text-brand-primary hover:underline">Effective Methods for the Biotinylation of Azamacrocycles</a><br>S. Krivickas, E. Tamanini, M. H. Todd and M. Watkinson, <em>J. Org. Chem.</em> <strong>2007</strong>.</li>
                        <li><a href="https://doi.org/10.1016/j.ijantimicag.2007.05.004" class="font-bold text-brand-primary hover:underline">Is Actin the Praziquantel Receptor?</a><br>A. R. Troiani, L. Pica-Mattoccia, C. Valle, D. Cioli, G. Mignogna, F. Ronketti and M. H. Todd, <em>Int. J. Antimicrob. Ag.</em> <strong>2007</strong>.</li>
                        <li><a href="https://doi.org/10.1016/j.bmcl.2007.05.063" class="font-bold text-brand-primary hover:underline">Praziquantel Derivatives I: Modification of the Aromatic Ring</a><br>F. E. Ronketti, A. V. Ramana, X. Chao-Ming, L. Pica-Mattoccia, D. Cioli and M. H. Todd, <em>Bioorg. Med. Chem. Lett.</em> <strong>2007</strong>.</li>
                        <li><a href="https://doi.org/10.1186/1752-153X-1-3" class="font-bold text-brand-primary hover:underline">Open Access and Open Source in Chemistry</a><br>M. H. Todd, <em>Chem. Central J.</em> <strong>2007</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2006 -->
        <div class="year-block group">
            <div onclick="toggleYear('2006')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2006</h2>
                <i id="icon-2006" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2006" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="http://dx.doi.org/10.1590/S0074-02762006000900046" class="font-bold text-brand-primary hover:underline">The Effects of Drugs, Ions and Poly-L-lysine on the Excretory System of <em>Schistosoma mansoni</em></a><br>J. R. Kusel, F. Oliveira, M. H. Todd, F. Ronketti, S. Lima, A. C.- de Mattos, K. Teixeira, P. M. Z. Coelho, J. A. Thornhill and F. Ribeiro, <em>Mem. Inst. Oswaldo Cruz.</em> <strong>2006</strong>.</li>
                        <li><a href="https://doi.org/10.1016/j.tetasy.2006.07.001" class="font-bold text-brand-primary hover:underline">Improved Synthesis of the Valuable Peptidomimetic Intermediate 3-Azido-4-hydroxy Cyclopentanoic Acid</a><br>E. Tamanini, M. Watkinson and M. H. Todd, <em>Tetrahedron Asymmetry</em> <strong>2006</strong>.</li>
                        <li><a href="https://doi.org/10.1071/CH06095" class="font-bold text-brand-primary hover:underline">Open Source Research – the Power of Us</a><br>T. B. Kepler, M. A. Marti-Renom, S. M. Maurer, A. K. Rai, G. Taylor and M. H. Todd, <em>Aust. J. Chem.</em> <strong>2006</strong>.</li>
                        <li><a href="https://doi.org/10.1016/j.tetlet.2005.12.073" class="font-bold text-brand-primary hover:underline">Solid Phase Synthesis of Praziquantel</a><br>S. El-Fayoummy, W. Mansour and M. H. Todd, <em>Tetrahedron Lett.</em> <strong>2006</strong>.</li>
                        <li><a href="https://doi.org/10.1107/S1600536806006982" class="font-bold text-brand-primary hover:underline">(<em>R</em>)-2-Ferrocenyl-4-hy­droxy­methyl-4,5-di­hydro-1,3-oxazole</a><br>M. H. Todd, S. El-Fayyoumy, M. E. Motevalli and C. J. Richards, <em>Acta Cryst. E.</em> <strong>2006</strong>.</li>
                        <li><a href="https://doi.org/10.1021/jm050232e" class="font-bold text-brand-primary hover:underline">Design and Synthesis of New Tetrazolyl- and Carboxy-biphenylylmethyl-quinazolin-4-one Derivatives as Angiotensin II AT<sub>1</sub> Receptor Antagonists</a><br>M. A. H. Ismail, S. Barker, D. A. Abou El Ella, K. A. M. Abouzid and R. A. Toubar and M. H. Todd, <em>J. Med. Chem.</em> <strong>2006</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2005 -->
        <div class="year-block group">
            <div onclick="toggleYear('2005')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2005</h2>
                <i id="icon-2005" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2005" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1039/B104620A" class="font-bold text-brand-primary hover:underline">Computer-Aided Organic Synthesis</a><br>M. H. Todd, <em>Chem. Soc. Rev.</em> <strong>2005</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2003 -->
        <div class="year-block group">
            <div onclick="toggleYear('2003')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2003</h2>
                <i id="icon-2003" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2003" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1016/j.pt.2003.09.005" class="font-bold text-brand-primary hover:underline">Drugs for the Control of Parasitic Diseases: Current Status and Development in Schistosomiasis</a><br>A. Fenwick, L. Savioli, D. Engels, R. Bergquist and M. H. Todd, <em>Trends Parasitol.</em> <strong>2003</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2002 -->
        <div class="year-block group">
            <div onclick="toggleYear('2002')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2002</h2>
                <i id="icon-2002" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2002" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1039/B104169J" class="font-bold text-brand-primary hover:underline">Asymmetric Autocatalysis: Product Recruitment for the Increase in the Chiral Environment (PRICE)</a><br>M. H. Todd, <em>Chem. Soc. Rev.</em> <strong>2002</strong>.</li>
                        <li><a href="https://doi.org/10.1039/B203957P" class="font-bold text-brand-primary hover:underline">Use of FTICR-MS to Detect Chemical Tags from a Combinatorial Library</a><br>M. H. Todd and C. Abell, <em>Analyst</em> <strong>2002</strong>.</li>
                        <li><a href="https://doi.org/10.1021/jo010990m" class="font-bold text-brand-primary hover:underline">Amino Acid-Derived Heterocycles: Lewis Acid Catalyzed and Radical Cyclizations from Peptide Acetals</a><br>M. H. Todd, C. O. Ndubaku and P. A. Bartlett, <em>J. Org. Chem.</em> <strong>2002</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2001 -->
        <div class="year-block group">
            <div onclick="toggleYear('2001')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2001</h2>
                <i id="icon-2001" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2001" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1021/cc000112m" class="font-bold text-brand-primary hover:underline">Novel Chemical Tagging Method for Combinatorial Synthesis Utilizing Suzuki Chemistry and Fourier Transform Ion Cyclotron Resonance Mass Spectrometry</a><br>M. H. Todd and C. Abell, <em>J. Comb. Chem.</em> <strong>2001</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2000 -->
        <div class="year-block group">
            <div onclick="toggleYear('2000')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">2000</h2>
                <i id="icon-2000" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-2000" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1016/S0040-4039(00)01431-3" class="font-bold text-brand-primary hover:underline">The Attachment and Cleavage of Phenols from Solid Supports and their Single Bead Mass Spectral Analysis</a><br>M. H. Todd and C. Abell, <em>Tetrahedron Lett.</em> <strong>2000</strong>.</li>
                        <li><a href="https://doi.org/10.1002/0471228249.ch2" class="font-bold text-brand-primary hover:underline">Palladium-Catalyzed Carbon-Carbon Bond Formation on Solid Support</a><br>M. H. Todd and C. Abell, in <em>Solid Phase Synthesis</em>, Burgess, K. (Ed.), Wiley-Interscience (New York), <strong>2000</strong>, 25-79.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 1999 -->
        <div class="year-block group">
            <div onclick="toggleYear('1999')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">1999</h2>
                <i id="icon-1999" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-1999" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1021/ol990785h" class="font-bold text-brand-primary hover:underline">A Novel Safety-Catch Linker for the Solid-Phase Synthesis of Amides and Esters</a><br>M. H. Todd, S. F. Oliver and C. Abell, <em>Org. Lett.</em> <strong>1999</strong>.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 1997 -->
        <div class="year-block group">
            <div onclick="toggleYear('1997')" class="flex justify-between items-center bg-slate-50 group-hover:bg-slate-100 p-4 rounded-sm cursor-pointer border-l-4 border-slate-200 hover:border-brand-primary transition select-none">
                <h2 class="text-xl font-bold text-brand-dark m-0">1997</h2>
                <i id="icon-1997" class="fas fa-chevron-down text-slate-400 chevron"></i>
            </div>
            <div id="content-1997" class="accordion-content">
                <div class="accordion-inner">
                    <ul class="space-y-6 py-6 px-2 text-base leading-relaxed text-slate-600 list-none pl-0">
                        <li><a href="https://doi.org/10.1016/S0040-4039(97)01552-9" class="font-bold text-brand-primary hover:underline">Studies on the Synthesis, Characterisation and Reactivity of Aromatic Diboronic Acids</a><br>M. H. Todd, S. Balasubramanian and C. Abell, <em>Tetrahedron Lett.</em> <strong>1997</strong>.</li>
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
