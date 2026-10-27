# Awesome Robot Scientists

A curated reading list of **robot scientists and robotic laboratories that perform real-world scientific experiments**.

The focus is on physical robots doing science, from robotic assistants and automated experimental platforms to closed-loop, autonomous discovery systems.

**50 papers + 1 technical report** | **Last curated: October 27, 2026** | A selected starting list, not an exhaustive bibliography.

## Mobile Robot index

**10 works: 9 papers + 1 technical report.** Jump to the full entries below. This index highlights systems with a mobile base used for experimental manipulation or sample transport; a fixed linear track alone does not qualify.

| Year | Work | Domain | Mobile robot role |
| --- | --- | --- | --- |
| 2026 | [A mobile robotic process chemist](#process-chemist-2026) | Chemistry | Experimental manipulation and sample transfer |
| 2026 | [Knowledge-driven autonomous materials research via collaborative multi-agent and robotic system](#mars-2026) | Materials Science | Reagent and consumable transport; experimental operations |
| 2026 | [X-Automate brings physical and agentic AI to the lab](#x-automate-2026) | Biomedical Research | Protein sample plate transport (Wall-E); technical report |
| 2025 | [A Multiagent-Driven Robotic AI Chemist Enabling Autonomous Chemical Research On Demand](#multiagent-chemist-2025) | Chemistry | Experimental manipulation across workstations |
| 2024 | [Automated synthesis of oxygen-producing catalysts from Martian meteorites by a robotic AI chemist](#martian-catalysts-2024) | Materials Science | Sample handling across catalyst preparation and testing stations |
| 2024 | [Autonomous mobile robots for exploratory synthetic chemistry](#exploratory-chemistry-2024) | Chemistry | Sample transfer between synthesis and analysis stations |
| 2023 | [A robotic platform for the synthesis of colloidal nanocrystals](#colloidal-nanocrystals-2023) | Materials Science | Microplate transport between experimental modules |
| 2023 | [Inverse design of chiral functional films by a robotic AI-guided system](#chiral-films-2023) | Materials Science | Sample handling across film preparation and testing stations |
| 2022 | [An all-round AI-Chemist with a scientific mind](#all-round-ai-chemist-2022) | Chemistry | Experimental manipulation across workstations |
| 2020 | [A mobile robotic chemist](#mobile-chemist-2020) | Materials Science | Experimental manipulation across photocatalyst workstations |

## Contents

- [Mobile Robot index](#mobile-robot-index)
- [Chemistry](#chemistry)
- [Materials Science](#materials-science)
- [Biology](#biology)
- [Biomedical Research](#biomedical-research)
- [Physics & Optics](#physics--optics)
- [Contributing](#contributing)

## Scope

**Include:** primary research demonstrated on real hardware, with a physical robot performing experimental operations such as sample preparation, manipulation, synthesis, assembly, culturing, or measurement. Mobile robots, fixed robotic arms, liquid-handling robots, and custom robotic manipulation platforms all count.

**Exclude:** software-only AI scientists, simulation-only demonstrations, purely computational discovery, reviews and perspectives, and automated instruments without a demonstrated robotic handling or manipulation component. General-purpose robotics papers are outside the scope unless they demonstrate a scientific experimental application. Robots used only for clinical diagnosis, treatment, rehabilitation, or surgery are outside this laboratory-research scope.

Robot-assisted and fully autonomous systems are both welcome. **Inclusion does not imply that a system autonomously performs the entire scientific process**, nor does it endorse every scientific claim in the paper. Cross-domain work is listed once, under its main experimental application. Selected official technical reports of demonstrated robotic laboratory systems are also included and explicitly distinguished from research papers.

## Reading the list

**Personal verification:** each entry has a checkbox recording whether repository owner **dyjin2** has personally verified that work. Unchecked means not yet personally verified; checked means personally verified. These marks are separate from inclusion in this curated list. To update a mark, edit this README, change `- [ ]` to `- [x]` for that entry, and commit the change.

Papers are ordered by publication year, newest first, then by title within each year. Years follow the journal's formal citation; an earlier online-publication year is noted where relevant. Author lists longer than four names are abbreviated to the first three authors and *et al.*; follow the paper link for the full list.

A journal or conference name indicates the published version. An accompanying arXiv link is an additional reading copy, not a separate entry. Preprint-only papers should be explicitly labelled **arXiv preprint** (or their other preprint server), rather than presented as peer-reviewed publications.

### Hardware tags

Tags describe the demonstrated hardware, independently of the scientific domain or level of autonomy. Hybrid platforms can have multiple tags; a mobile arm is not also tagged as stationary unless a separate fixed arm is used.

- `Mobile Robot`: a robot with a mobile base used within the laboratory, for manipulation or transport.
- `Stationary arm`: an articulated or SCARA robotic arm operating in a fixed workcell, including arms mounted on a fixed linear track.
- `automation station`: a dedicated automated experimental or handling platform, such as a liquid handler, Cartesian gantry, bioprinter, or robotic patch-clamp system. Ordinary analytical instruments alone do not earn this tag.

Tags identify documented components, rather than providing an exhaustive inventory of every instrument in a laboratory.

## Chemistry

*15 papers.*

Reaction discovery, synthesis methods, reaction optimization, and general chemical experimentation platforms.

- [ ] **A flexible and affordable self-driving laboratory for automated reaction optimization**  
  `automation station`  
  Simone Pilon, Elia Savino, Oliver M. Bayley, et al.  
  *Nature Synthesis*, **2026**. [Paper](https://doi.org/10.1038/s44160-026-01053-0)

  <a href="https://www.nature.com/articles/s44160-026-01053-0"><img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs44160-026-01053-0/MediaObjects/44160_2026_1053_Fig1_HTML.png" alt="A flexible and affordable self-driving laboratory for automated reaction optimization — Fig. 1: RoboChem-Flex: a low-cost SDL for closed-loop or human-in-the-loop, multi-objective optimization in synthetic organic chemistry." width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/s44160-026-01053-0">Pilon et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] <a id="process-chemist-2026"></a>**A mobile robotic process chemist**  
  `Mobile Robot` · `automation station`  
  Emma J. Brass, Satheeshkumar Veeramani, Zhengxue Zhou, et al.  
  *Digital Discovery*, **2026**. [Paper](https://doi.org/10.1039/D5DD00563A)

  <a href="https://www.sciencedirect.com/org/science/article/pii/S2635098X2600046X"><img src="https://ars.els-cdn.com/content/image/1-s2.0-S2635098X2600046X-d5dd00563a-f2.gif" alt="A mobile robotic process chemist — Fig. 2" width="520"></a>

  <sub>Image: <a href="https://www.sciencedirect.com/org/science/article/pii/S2635098X2600046X">Brass et al., Fig. 2</a> · <a href="https://creativecommons.org/licenses/by-nc/3.0/">CC BY-NC 3.0</a> · Unmodified.</sub>

- [ ] <a id="multiagent-chemist-2025"></a>**A Multiagent-Driven Robotic AI Chemist Enabling Autonomous Chemical Research On Demand**  
  `Mobile Robot` · `Stationary arm` · `automation station`  
  Tao Song, Man Luo, Xiaolong Zhang, et al.  
  *Journal of the American Chemical Society*, **2025**. [Paper](https://doi.org/10.1021/jacs.4c17738)

  <!-- Image pending: use a verified figure from Song et al. (2025), DOI 10.1021/jacs.4c17738. The previous Zhu et al. (2022) background image was removed because it is not from this paper. -->

- [ ] **ORGANA: A robotic assistant for automated chemistry experimentation and characterization**  
  `Stationary arm`  
  Kourosh Darvish, Marta Skreta, Yuchi Zhao, et al.  
  *Matter*, **2025**. [Paper](https://doi.org/10.1016/j.matt.2024.10.015) | [arXiv](https://arxiv.org/abs/2401.06949)  

  <a href="https://ac-rad.github.io/organa/"><img src="https://ac-rad.github.io/organa/static/images/organa_overview.jpeg" alt="ORGANA: A robotic assistant for automated chemistry experimentation and characterization — ORGANA architecture" width="520"></a>

  <sub>Image: <a href="https://ac-rad.github.io/organa/">Darvish et al., ORGANA architecture</a> · Original image rights apply · Unmodified.</sub>
  *Note: Published online in 2024; assigned to the 2025 journal volume.*

- [ ] **An automatic end-to-end chemical synthesis development platform powered by large language models**  
  `Stationary arm` · `automation station`  
  Yixiang Ruan, Chenyin Lu, Ning Xu, et al.  
  *Nature Communications*, **2024**. [Paper](https://doi.org/10.1038/s41467-024-54457-x)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11585555/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/86bd/11585555/b68fa4761e7f/41467_2024_54457_Fig1_HTML.jpg" alt="An automatic end-to-end chemical synthesis development platform powered by large language models — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11585555/">Ruan et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a> · Unmodified.</sub>

- [ ] **Augmenting large language models with chemistry tools**  
  `automation station`  
  Andres M. Bran, Sam Cox, Oliver Schilter, et al.  
  *Nature Machine Intelligence*, **2024**. [Paper](https://doi.org/10.1038/s42256-024-00832-8)

  <a href="https://www.nature.com/articles/s42256-024-00832-8"><img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs42256-024-00832-8/MediaObjects/42256_2024_832_Fig1_HTML.png" alt="Augmenting large language models with chemistry tools — Fig. 1: Overview and toolset." width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/s42256-024-00832-8">M. Bran et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **Automated self-optimization, intensification, and scale-up of photocatalysis in flow**  
  `automation station`  
  Aidan Slattery, Zhenghui Wen, Pauline Tenblad, et al.  
  *Science*, **2024**. [Paper](https://doi.org/10.1126/science.adj1817)

  <a href="https://hims.uva.nl/content/news/2024/01/autonomous-synthesis-robot-uses-ai-to-speed-up-chemical-discovery.html"><img src="https://hims.uva.nl/binaries/_ht_1736930500156/1360x0-jpg/content/gallery/onderzoek/hims/flow-chemistry/robochemlayoutengmodified.jpg" alt="Automated self-optimization, intensification, and scale-up of photocatalysis in flow — RoboChem system overview" width="520"></a>

  <sub>Image: <a href="https://hims.uva.nl/content/news/2024/01/autonomous-synthesis-robot-uses-ai-to-speed-up-chemical-discovery.html">UvA/HIMS, RoboChem system overview</a> · Original image rights apply · Unmodified.</sub>

- [ ] <a id="exploratory-chemistry-2024"></a>**Autonomous mobile robots for exploratory synthetic chemistry**  
  `Mobile Robot` · `automation station`  
  Tianwei Dai, Sriram Vijayakrishnan, Filip T. Szczypiński, et al.  
  *Nature*, **2024**. [Paper](https://doi.org/10.1038/s41586-024-08173-7)

  <a href="https://www.nature.com/articles/s41586-024-08173-7/figures/5"><img src="https://media.springernature.com/full/springer-static/esm/art%3A10.1038%2Fs41586-024-08173-7/MediaObjects/41586_2024_8173_Fig5_ESM.jpg" alt="Liverpool mobile robot gripper handling an NMR sample rack" width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/s41586-024-08173-7/figures/5">Dai et al. (2024), Extended Data Figure 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **Autonomous chemical research with large language models**  
  `automation station`  
  Daniil A. Boiko, Robert MacKnight, Ben Kline, and Gabe Gomes.  
  *Nature*, **2023**. [Paper](https://doi.org/10.1038/s41586-023-06792-0)

  <a href="https://www.nature.com/articles/s41586-023-06792-0"><img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41586-023-06792-0/MediaObjects/41586_2023_6792_Fig4_HTML.png" alt="Autonomous chemical research with large language models — Fig. 4: Robotic liquid handler control capabilities and integration with analytical tools." width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/s41586-023-06792-0">Boiko et al., Fig. 4</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **Autonomous, multiproperty-driven molecular discovery: From predictions to measurements and back**  
  `automation station`  
  Brent A. Koscher, Richard B. Canty, Matthew A. McDonald, et al.  
  *Science*, **2023**. [Paper](https://doi.org/10.1126/science.adi1407)

  <a href="https://jensenlab.mit.edu/toward-autonomous-molecular-discovery/"><img src="https://jensenlab.mit.edu/wp-content/uploads/sites/34/2023/02/Toward-Autonomous-Molecular-Discovery-image-2.png" alt="Autonomous, multiproperty-driven molecular discovery: From predictions to measurements and back — Robotic platform photograph" width="520"></a>

  <sub>Image: <a href="https://jensenlab.mit.edu/toward-autonomous-molecular-discovery/">Jensen Research Group, MIT, robotic platform photograph</a> · Original image rights apply · Unmodified.</sub>

- [ ] **Large language models for chemistry robotics**  
  `Stationary arm`  
  Naruki Yoshikawa, Marta Skreta, Kourosh Darvish, et al.  
  *Autonomous Robots*, **2023**. [Paper](https://doi.org/10.1007/s10514-023-10136-2)

  <a href="https://link.springer.com/article/10.1007/s10514-023-10136-2"><img src="https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs10514-023-10136-2/MediaObjects/10514_2023_10136_Fig10_HTML.png" alt="Large language models for chemistry robotics — Fig. 10" width="520"></a>

  <sub>Image: <a href="https://link.springer.com/article/10.1007/s10514-023-10136-2">Yoshikawa et al., Fig. 10</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] <a id="all-round-ai-chemist-2022"></a>**An all-round AI-Chemist with a scientific mind**  
  `Mobile Robot` · `automation station`  
  Qing Zhu, Fei Zhang, Yan Huang, et al.  
  *National Science Review*, **2022**. [Paper](https://doi.org/10.1093/nsr/nwac190)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9674120/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/5b66/9674120/ca8e5a80201a/nwac190fig3.jpg" alt="An all-round AI-Chemist with a scientific mind — Figure 3." width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9674120/">Zhu et al., Figure 3</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **Bayesian Optimization of Computer-Proposed Multistep Synthetic Routes on an Automated Robotic Flow Platform**  
  `automation station`  
  Anirudh M. K. Nambiar, Christopher P. Breen, Travis Hart, et al.  
  *ACS Central Science*, **2022**. [Paper](https://doi.org/10.1021/acscentsci.2c00207)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9228554/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/31b7/9228554/9a6b7ffe71a3/oc2c00207_0001.jpg" alt="Bayesian Optimization of Computer-Proposed Multistep Synthetic Routes on an Automated Robotic Flow Platform — Figure 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9228554/">Nambiar et al., Figure 1</a> · <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a> · Unmodified.</sub>

- [ ] **Automated solubility screening platform using computer vision**  
  `Stationary arm` · `automation station`  
  Parisa Shiri, Veronica Lai, Tara Zepel, et al.  
  *iScience*, **2021**. [Paper](https://doi.org/10.1016/j.isci.2021.102176)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7921605/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/56d5/7921605/e3a0007009d7/gr1.jpg" alt="Automated solubility screening platform using computer vision — Figure 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7921605/">Shiri et al., Figure 1</a> · <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a> · Unmodified.</sub>

- [ ] **A robotic platform for flow synthesis of organic compounds informed by AI planning**  
  `automation station`  
  Connor W. Coley, Dale A. Thomas III, Justin A. M. Lummiss, et al.  
  *Science*, **2019**. [Paper](https://doi.org/10.1126/science.aax1566)

  <a href="https://cen.acs.org/synthesis/Automating-synthesis-planning-execution/97/i32"><img src="https://s7d1.scene7.com/is/image/CENODS/09732-leadcon-robotcxd?$responsive$&amp;qlt=90,0&amp;resMode=sharp2&amp;fmt=webp&amp;op_sharpen=1" alt="A robotic platform for flow synthesis of organic compounds informed by AI planning — Robot photograph" width="520"></a>

  <sub>Image: <a href="https://cen.acs.org/synthesis/Automating-synthesis-planning-execution/97/i32">Connor Coley and Felice Frankel, via C&amp;EN</a> · Original image rights apply · Unmodified.</sub>

## Materials Science

*14 papers.*

Discovery, synthesis, assembly, and testing of functional materials, including catalysts, electrolytes, thin films, nanocrystals, and mechanical structures.

- [ ] <a id="mars-2026"></a>**Knowledge-driven autonomous materials research via collaborative multi-agent and robotic system**  
  `Mobile Robot` · `Stationary arm` · `automation station`  
  Tongyu Shi, Yutang Li, Zhanlong Wang, et al.  
  *Matter*, **2026**. [Paper](https://doi.org/10.1016/j.matt.2025.102577)

  <a href="https://www.sciencedirect.com/science/article/abs/pii/S2590238525006204"><img src="https://ars.els-cdn.com/content/image/1-s2.0-S2590238525006204-fx1.jpg" alt="Knowledge-driven autonomous materials research via collaborative multi-agent and robotic system — Graphical abstract" width="520"></a>

  <sub>Image: <a href="https://www.sciencedirect.com/science/article/abs/pii/S2590238525006204">Shi et al., Graphical abstract</a> · Original image rights apply · Unmodified.</sub>

- [ ] **A chemical autonomous robotic platform for end-to-end synthesis of nanoparticles**  
  `automation station`  
  Fan Gao, Hongqiang Li, Zhilong Chen, et al.  
  *Nature Communications*, **2025**. [Paper](https://doi.org/10.1038/s41467-025-62994-2)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12354731/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/a0bc/12354731/98f0f32ca581/41467_2025_62994_Fig1_HTML.jpg" alt="A chemical autonomous robotic platform for end-to-end synthesis of nanoparticles — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12354731/">Gao et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a> · Unmodified.</sub>

- [ ] **Autonomous multi-robot synthesis and optimization of metal halide perovskite nanocrystals**  
  `Stationary arm` · `automation station`  
  Jinge Xu, Christopher H. J. Moran, Arup Ghorai, et al.  
  *Nature Communications*, **2025**. [Paper](https://doi.org/10.1038/s41467-025-63209-4)

  <a href="https://www.nature.com/articles/s41467-025-63209-4/figures/1"><img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41467-025-63209-4/MediaObjects/41467_2025_63209_Fig1_HTML.png" alt="Rainbow multi-robot nanocrystal synthesis platform: system diagram and hardware photograph" width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/s41467-025-63209-4/figures/1">Xu et al. (2025), Figure 1</a> · <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a> · Unmodified.</sub>

- [ ] <a id="martian-catalysts-2024"></a>**Automated synthesis of oxygen-producing catalysts from Martian meteorites by a robotic AI chemist**  
  `Mobile Robot` · `automation station`  
  Qing Zhu, Yan Huang, Donglai Zhou, et al.  
  *Nature Synthesis*, **2024**. [Paper](https://doi.org/10.1038/s44160-023-00424-1)  

  <a href="https://www.nature.com/articles/s44160-023-00424-1"><img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs44160-023-00424-1/MediaObjects/44160_2023_424_Fig1_HTML.png" alt="Automated synthesis of oxygen-producing catalysts from Martian meteorites by a robotic AI chemist — Fig. 1: Workflow of an all-encompassing system for the on-site design and production of an OER electrocatalyst on Mars by an AI chemist consisting of a mobile robot, a computational ‘brain’, a cloud server and 14 task-specific workstations." width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/s44160-023-00424-1">Zhu et al., Fig. 1</a> · Original image rights apply · Unmodified.</sub>
  *Note: Published online in 2023; assigned to the 2024 journal volume.*

- [ ] **Superlative mechanical energy absorbing efficiency discovered through self-driving lab-human partnership**  
  `Stationary arm` · `automation station`  
  Kelsey L. Snapp, Benjamin Verdier, Aldair E. Gongora, et al.  
  *Nature Communications*, **2024**. [Paper](https://doi.org/10.1038/s41467-024-48534-4)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11109101/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/7427/11109101/8e608bf04809/41467_2024_48534_Fig1_HTML.jpg" alt="Superlative mechanical energy absorbing efficiency discovered through self-driving lab-human partnership — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11109101/">Snapp et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **A high-throughput workflow for the synthesis of CdSe nanocrystals using a sonochemical materials acceleration platform**  
  `automation station`  
  Maria Politi, Fabio Baum, Kiran Vaddi, et al.  
  *Digital Discovery*, **2023**. [Paper](https://doi.org/10.1039/D3DD00033H)

  <a href="https://www.sciencedirect.com/org/science/article/pii/S2635098X2300030X"><img src="https://ars.els-cdn.com/content/image/1-s2.0-S2635098X2300030X-d3dd00033h-ga.gif" alt="A high-throughput workflow for the synthesis of CdSe nanocrystals using a sonochemical materials acceleration platform — Graphical abstract" width="520"></a>

  <sub>Image: <a href="https://www.sciencedirect.com/org/science/article/pii/S2635098X2300030X">Politi et al., Graphical abstract</a> · <a href="https://creativecommons.org/licenses/by-nc/3.0/">CC BY-NC 3.0</a> · Unmodified.</sub>

- [ ] <a id="colloidal-nanocrystals-2023"></a>**A robotic platform for the synthesis of colloidal nanocrystals**  
  `Mobile Robot` · `Stationary arm` · `automation station`  
  Haitao Zhao, Wei Chen, Hao Huang, et al.  
  *Nature Synthesis*, **2023**. [Paper](https://doi.org/10.1038/s44160-023-00250-5)

  <a href="https://www.nature.com/articles/s44160-023-00250-5"><img src="https://media.springernature.com/lw685/springer-static/image/art%3A10.1038%2Fs44160-023-00250-5/MediaObjects/44160_2023_250_Fig2_HTML.png" alt="A robotic platform for the synthesis of colloidal nanocrystals — Fig. 2: Robotic platform for NC synthesis and characterization." width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/s44160-023-00250-5">Zhao et al., Fig. 2</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **An autonomous laboratory for the accelerated synthesis of inorganic materials**  
  `Stationary arm` · `automation station`  
  Nathan J. Szymanski, Bernardus Rendy, Yuxing Fei, et al.  
  *Nature*, **2023**. [Paper](https://doi.org/10.1038/s41586-023-06734-w) | [Author correction (2026)](https://doi.org/10.1038/s41586-025-09992-y)  

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10700133/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/4421/10700133/61814c35ae3d/41586_2023_6734_Fig1_HTML.jpg" alt="An autonomous laboratory for the accelerated synthesis of inorganic materials — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10700133/">Szymanski et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>
  *Note: The title above follows the 2026 author correction; the original title referred to "novel materials".*

- [ ] <a id="chiral-films-2023"></a>**Inverse design of chiral functional films by a robotic AI-guided system**  
  `Mobile Robot` · `automation station`  
  Yifan Xie, Shuo Feng, Linxiao Deng, et al.  
  *Nature Communications*, **2023**. [Paper](https://doi.org/10.1038/s41467-023-41951-x)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10551020/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/754b/10551020/fadfea8b8f13/41467_2023_41951_Fig1_HTML.jpg" alt="Inverse design of chiral functional films by a robotic AI-guided system — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10551020/">Xie et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **A self-driving laboratory advances the Pareto front for material properties**  
  `Stationary arm` · `automation station`  
  Benjamin P. MacLeod, Fraser G. L. Parlane, Connor C. Rupnow, et al.  
  *Nature Communications*, **2022**. [Paper](https://doi.org/10.1038/s41467-022-28580-6)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC8863835/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/149c/8863835/6689adb324ab/41467_2022_28580_Fig2_HTML.jpg" alt="A self-driving laboratory advances the Pareto front for material properties — Fig. 2" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC8863835/">MacLeod et al., Fig. 2</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **A Bayesian experimental autonomous researcher for mechanical design**  
  `Stationary arm` · `automation station`  
  Aldair E. Gongora, Bowen Xu, Wyatt Perry, et al.  
  *Science Advances*, **2020**. [Paper](https://doi.org/10.1126/sciadv.aaz1708)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7148087/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/a044/7148087/01b0ee7a4dc8/aaz1708-F1.jpg" alt="A Bayesian experimental autonomous researcher for mechanical design — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7148087/">Gongora et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] <a id="mobile-chemist-2020"></a>**A mobile robotic chemist**  
  `Mobile Robot` · `automation station`  
  Benjamin Burger, Phillip M. Maffettone, Vladimir V. Gusev, et al.  
  *Nature*, **2020**. [Paper](https://doi.org/10.1038/s41586-020-2442-2)

  <a href="https://www.nature.com/articles/s41586-020-2442-2"><img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41586-020-2442-2/MediaObjects/41586_2020_2442_Fig1_HTML.png" alt="A mobile robotic chemist — Fig. 1: Autonomous mobile robot and experimental stations." width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/s41586-020-2442-2">Burger et al., Fig. 1</a> · Original image rights apply · Unmodified.</sub>

- [ ] **Self-driving laboratory for accelerated discovery of thin-film materials**  
  `Stationary arm` · `automation station`  
  Benjamin P. MacLeod, Fraser G. L. Parlane, Thomas D. Morrissey, et al.  
  *Science Advances*, **2020**. [Paper](https://doi.org/10.1126/sciadv.aaz8867) | [arXiv](https://arxiv.org/abs/1906.05398)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7220369/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/2e3c/7220369/0079dd65db41/aaz8867-F1.jpg" alt="Self-driving laboratory for accelerated discovery of thin-film materials — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7220369/">MacLeod et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by-nc/4.0/">CC BY-NC 4.0</a> · Unmodified.</sub>

- [ ] **Autonomous robotic searching and assembly of two-dimensional crystals to build van der Waals superlattices**  
  `Stationary arm` · `automation station`  
  Satoru Masubuchi, Masataka Morimoto, Sei Morikawa, et al.  
  *Nature Communications*, **2018**. [Paper](https://doi.org/10.1038/s41467-018-03723-w)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC5897399/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/dfbd/5897399/04c59f013e7c/41467_2018_3723_Fig1_HTML.jpg" alt="Autonomous robotic searching and assembly of two-dimensional crystals to build van der Waals superlattices — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC5897399/">Masubuchi et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

## Biology

*13 papers.*

Fundamental and synthetic biology, microbiology, protein engineering, biological sample preparation, and experimental neuroscience. General cell-culture platforms also belong here.

- [ ] **Automated prototyping of genetic codes**  
  `automation station`  
  Felix Radford, Nayan Sapers, Hana M. Burgess, et al.  
  *Nature*, **2026**. [Paper](https://doi.org/10.1038/s41586-026-10949-y)

  <a href="https://www.nature.com/articles/s41586-026-10949-y"><img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41586-026-10949-y/MediaObjects/41586_2026_10949_Fig2_HTML.png" alt="Automated prototyping of genetic codes — Fig. 2: Automated reading of aminoacylation with tSCAN." width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/s41586-026-10949-y">Radford et al., Fig. 2</a> · <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a> · Unmodified.</sub>

- [ ] **ProteoAutoNet: high-throughput co-eluted protein analysis with robotics and machine learning**  
  `Stationary arm` · `automation station`  
  Mengge Lyu, Pingping Hu, Guangmei Zhang, et al.  
  *Nature Communications*, **2026**. [Paper](https://doi.org/10.1038/s41467-026-68686-9)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12929803/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/3b57/12929803/e9dcdc3b20ab/41467_2026_68686_Fig1_HTML.jpg" alt="ProteoAutoNet: high-throughput co-eluted protein analysis with robotics and machine learning — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12929803/">Lyu et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **Semantic Representation for Agentic Self-Play in Automated Laboratories**  
  `Stationary arm` · `automation station`  
  Yves Delley, John Coller, Zachary Cutts, et al.  
  *arXiv preprint*, **2026**. [arXiv](https://arxiv.org/abs/2610.32755)

- [ ] **Enabling high-throughput enzyme discovery and engineering with a low-cost, robot-assisted pipeline**  
  `automation station`  
  Brenna Norton-Baker, Mackenzie C. R. Denton, Natasha P. Murphy, et al.  
  *Scientific Reports*, **2024**. [Paper](https://doi.org/10.1038/s41598-024-64938-0)

  <!-- Image hidden for a compact reading list: OT-2 liquid-handling workflow.
  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11196671/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/3224/11196671/6e9bf4b76242/41598_2024_64938_Fig1_HTML.jpg" alt="Enabling high-throughput enzyme discovery and engineering with a low-cost, robot-assisted pipeline — Figure 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11196671/">Norton-Baker et al., Figure 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>
  -->

- [ ] **Self-driving laboratories to autonomously navigate the protein fitness landscape**  
  `automation station`  
  Jacob T. Rapp, Bennett J. Bremer, and Philip A. Romero.  
  *Nature Chemical Engineering*, **2024**. [Paper](https://doi.org/10.1038/s44286-023-00002-4)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10926838/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/f4ac/10926838/5ada46635e2e/nihms-1959490-f0001.jpg" alt="Self-driving laboratories to autonomously navigate the protein fitness landscape — Fig. 1 |" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10926838/">Rapp et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **BacterAI maps microbial metabolism without prior knowledge**  
  `automation station`  
  Adam C. Dama, Kevin S. Kim, Danielle M. Leyva, et al.  
  *Nature Microbiology*, **2023**. [Paper](https://doi.org/10.1038/s41564-023-01376-0)

  <a href="https://www.nature.com/articles/s41564-023-01376-0"><img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41564-023-01376-0/MediaObjects/41564_2023_1376_Fig1_HTML.png" alt="BacterAI maps microbial metabolism without prior knowledge — Fig. 1: BacterAI uses an automated experiment pipeline and an AI agent to study bacterial metabolism." width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/s41564-023-01376-0">Dama et al., Fig. 1</a> · Original image rights apply · Unmodified.</sub>

- [ ] **A Variable Scheduling Maintenance Culture Platform for Mammalian Cells**  
  `Stationary arm`  
  Koji Ochiai, Naohiro Motozawa, Motoki Terada, et al.  
  *SLAS Technology*, **2021**. [Paper](https://doi.org/10.1177/2472630320972109)  

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7985857/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/d1c7/7985857/03ce6bd52a84/10.1177_2472630320972109-fig2.jpg" alt="A Variable Scheduling Maintenance Culture Platform for Mammalian Cells — Figure 2." width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7985857/">Ochiai et al., Figure 2</a> · <a href="https://creativecommons.org/licenses/by-nc/4.0/">CC BY-NC 4.0</a> · Unmodified.</sub>
  *Note: Published online in 2020; assigned to the 2021 journal volume.*

- [ ] **Closed-loop cycles of experiment design, execution, and learning accelerate systems biology model development in yeast**  
  `Stationary arm` · `automation station`  
  Anthony Coutant, Katherine Roper, Daniel Trejo-Banos, et al.  
  *Proceedings of the National Academy of Sciences*, **2019**. [Paper](https://doi.org/10.1073/pnas.1900548116)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC6731661/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/b534/6731661/9f4dec92d33a/pnas.1900548116fig01.jpg" alt="Closed-loop cycles of experiment design, execution, and learning accelerate systems biology model development in yeast — Fig. 1." width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC6731661/">Coutant et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **Towards a fully automated algorithm driven platform for biosystems design**  
  `Stationary arm` · `automation station`  
  Mohammad HamediRad, Ran Chao, Scott Weisberg, et al.  
  *Nature Communications*, **2019**. [Paper](https://doi.org/10.1038/s41467-019-13189-z)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC6853954/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/a9d8/6853954/77b3d04dee2c/41467_2019_13189_Fig1_HTML.jpg" alt="Towards a fully automated algorithm driven platform for biosystems design — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC6853954/">HamediRad et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **Multi-neuron intracellular recording in vivo via interacting autopatching robots**  
  `automation station`  
  Suhasa B. Kodandaramaiah, Francisco J. Flores, Gregory L. Holst, et al.  
  *eLife*, **2018**. [Paper](https://doi.org/10.7554/eLife.24656)

  <!-- Image hidden for a compact reading list: Dedicated electrode micromanipulators with linear actuators; called robotic arms in the paper.
  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC5812718/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/b574/5812718/9a6d10915467/elife-24656-fig2.jpg" alt="Multi-neuron intracellular recording in vivo via interacting autopatching robots — Figure 2." width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC5812718/">Kodandaramaiah et al., Figure 2</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>
  -->

- [ ] **Automated whole-cell patch-clamp electrophysiology of neurons in vivo**  
  `automation station`  
  Suhasa B. Kodandaramaiah, Giovanni Talei Franzesi, Brian Y. Chow, et al.  
  *Nature Methods*, **2012**. [Paper](https://doi.org/10.1038/nmeth.1993)

  <!-- Image hidden for a compact reading list: Dedicated patch-clamp linear actuator.
  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC3427788/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/df2a/3427788/469c38483521/nihms397908f1.jpg" alt="Automated whole-cell patch-clamp electrophysiology of neurons in vivo — Figure 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC3427788/">Kodandaramaiah et al., Figure 1</a> · Original image rights apply · Unmodified.</sub>
  -->

- [ ] **The automation of science**  
  `Stationary arm` · `automation station`  
  Ross D. King, Jem Rowland, Stephen G. Oliver, et al.  
  *Science*, **2009**. [Paper](https://doi.org/10.1126/science.1165620)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC2813846/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/1eaa/2813846/38c6a915e9f6/1759-4499-2-1-2.jpg" alt="The automation of science — Adam robot: Sparkes et al. (2010), Figure 2" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC2813846/">Adam robot: Sparkes et al. (2010), Figure 2</a> · <a href="https://creativecommons.org/licenses/by/2.0">CC BY 2.0</a> · Unmodified.</sub>

- [ ] **Functional genomic hypothesis generation and experimentation by a robot scientist**  
  `automation station`  
  Ross D. King, Kenneth E. Whelan, Ffion M. Jones, et al.  
  *Nature*, **2004**. [Paper](https://doi.org/10.1038/nature02236)

  <a href="https://www.nature.com/articles/nature02236"><img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fnature02236/MediaObjects/41586_2004_Article_BFnature02236_Fig1_HTML.jpg" alt="Functional genomic hypothesis generation and experimentation by a robot scientist — Figure 1" width="520"></a>

  <sub>Image: <a href="https://www.nature.com/articles/nature02236">King et al., Figure 1</a> · Original image rights apply · Unmodified.</sub>

## Biomedical Research

*7 papers + 1 technical report.*

Drug discovery and formulation, disease models, organoids, organ-on-chip experiments, and regenerative medicine. This category covers laboratory research; robots used only for clinical diagnosis, treatment, or surgery are excluded.

- [ ] <a id="x-automate-2026"></a>**X-Automate brings physical and agentic AI to the lab**  
  `Mobile Robot` · `Stationary arm` · `automation station`  
  Xaira Therapeutics.  
  *Official technical report (not a peer-reviewed paper)*, **2026** (October 23). [Report and demonstrations](https://www.xaira.com/news/x-automate-brings-physical-and-agentic-ai-to-labs)

  Mobile robot Wall-E transports protein sample plates; the six-axis X-Bot arm loads and unloads an HPLC instrument.

  <a href="https://www.xaira.com/news/x-automate-brings-physical-and-agentic-ai-to-labs"><img src="https://cdn.prod.website-files.com/6a7c170fadeb1150526cb3e3/6ad667f445d4d788058de0ab_image5.png" alt="X-Automate system architecture and camera views of the HPLC station and mobile robot, Figure 2" width="520"></a>

  <sub>Image: <a href="https://www.xaira.com/news/x-automate-brings-physical-and-agentic-ai-to-labs">Xaira Therapeutics, Figure 2</a> · Original image rights apply · Unmodified.</sub>

- [ ] **Efficient discovery of new medicine formulations using a semi-self-driven robotic formulator**  
  `automation station`  
  Helena Ros, Youssef Abdalla, Michael T. Cook, and David Shorthouse.  
  *Digital Discovery*, **2025**. [Paper](https://doi.org/10.1039/D5DD00171D)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC13576497/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/e85b/13576497/54a781232689/d5dd00171d-f1.webp" alt="Efficient discovery of new medicine formulations using a semi-self-driven robotic formulator — Fig. 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC13576497/">Ros et al., Fig. 1</a> · <a href="https://creativecommons.org/licenses/by/3.0/">CC BY 3.0</a> · Unmodified.</sub>

- [ ] **An Automated Robotic Interface for Assays: Facilitating Machine Learning in Drug Discovery by the Automation of Physicochemical Property Assays**  
  `Stationary arm` · `automation station`  
  Newton P. Wu, Wenyi Wang, Dhireshan Gadiagellan, et al.  
  *ACS Omega*, **2024**. [Paper](https://doi.org/10.1021/acsomega.4c02003)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11170699/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/8f09/11170699/cf252849f7db/ao4c02003_0002.jpg" alt="An Automated Robotic Interface for Assays: Facilitating Machine Learning in Drug Discovery by the Automation of Physicochemical Property Assays — Figure 2" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11170699/">Wu et al., Figure 2</a> · <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a> · Unmodified.</sub>

- [ ] **Robotic search for optimal cell culture in regenerative medicine**  
  `Stationary arm`  
  Genki N. Kanda, Taku Tsuzuki, Motoki Terada, et al.  
  *eLife*, **2022**. [Paper](https://doi.org/10.7554/eLife.77007)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9239686/#fig2s1"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/b85d/9239686/f04c950f7333/elife-77007-fig2-figsupp1.jpg" alt="Maholo LabDroid cell-culture booth, dual robotic arms, and surrounding laboratory equipment" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9239686/#fig2s1">Kanda, Tsuzuki et al. (2022), Figure 2—figure supplement 1</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

- [ ] **Cellular extrusion bioprinting improves kidney organoid reproducibility and conformation**  
  `automation station`  
  Kynan T. Lawlor, Jessica M. Vanslambrouck, J. William Higgins, et al.  
  *Nature Materials*, **2021**. [Paper](https://doi.org/10.1038/s41563-020-00853-9)  

  <!-- Image hidden for a compact reading list: Extrusion bioprinter with XYZ positioning.
  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7855371/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/4d90/7855371/9ed6e5a01fab/nihms-1634620-f0001.jpg" alt="Cellular extrusion bioprinting improves kidney organoid reproducibility and conformation — Figure 1." width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7855371/">Lawlor et al., Figure 1</a> · Original image rights apply · Unmodified.</sub>
  -->
  *Note: Published online in 2020; assigned to the 2021 journal volume.*

- [ ] **Robotic fluidic coupling and interrogation of multiple vascularized organ chips**  
  `automation station`  
  Richard Novak, Miles Ingram, Susan Marquez, et al.  
  *Nature Biomedical Engineering*, **2020**. [Paper](https://doi.org/10.1038/s41551-019-0497-x)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC8057865/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/3a2e/8057865/565fdd064049/nihms-1682565-f0001.jpg" alt="Robotic fluidic coupling and interrogation of multiple vascularized organ chips — Figure 1." width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC8057865/">Novak et al., Figure 1</a> · Original image rights apply · Unmodified.</sub>

- [ ] **High-Throughput Screening Enhances Kidney Organoid Differentiation from Human Pluripotent Stem Cells and Enables Automated Multidimensional Phenotyping**  
  `automation station`  
  Stefan M. Czerniecki, Nelly M. Cruz, Jennifer L. Harder, et al.  
  *Cell Stem Cell*, **2018**. [Paper](https://doi.org/10.1016/j.stem.2018.04.022)

  <!-- Image hidden for a compact reading list: Liquid-handling and automated imaging workflow.
  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC5984728/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/8aed/5984728/07cdd26eae86/nihms969084f1.jpg" alt="High-Throughput Screening Enhances Kidney Organoid Differentiation from Human Pluripotent Stem Cells and Enables Automated Multidimensional Phenotyping — Figure 1" width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC5984728/">Czerniecki et al., Figure 1</a> · Original image rights apply · Unmodified.</sub>
  -->

- [ ] **Cheaper faster drug development validated by the repositioning of drugs against neglected tropical diseases**  
  `Stationary arm` · `automation station`  
  Kevin Williams, Elizabeth Bilsland, Andrew Sparkes, et al.  
  *Journal of the Royal Society Interface*, **2015**. [Paper](https://doi.org/10.1098/rsif.2014.1289)

  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC4345494/"><img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/da1c/4345494/7572a859d5d6/rsif20141289-g2.jpg" alt="Cheaper faster drug development validated by the repositioning of drugs against neglected tropical diseases — Figure 2." width="520"></a>

  <sub>Image: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC4345494/">Williams et al., Figure 2</a> · <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> · Unmodified.</sub>

## Physics & Optics

*1 paper.*

Robotic assembly, alignment, operation, and maintenance of physical and optical experiments.

- [ ] **A Framework for Closed-Loop Robotic Assembly, Alignment and Self-Recovery of Precision Optical Systems**  
  `Stationary arm`  
  Seou Choi, Sachin Vaidya, Caio Silva, et al.  
  *arXiv preprint*, **2026**. [arXiv](https://arxiv.org/abs/2603.21496) | [Project coverage and demonstration](https://news.mit.edu/2026/robotic-lab-runs-optics-experiments-on-demand-0917)

  <a href="https://news.mit.edu/2026/robotic-lab-runs-optics-experiments-on-demand-0917"><img src="https://news.mit.edu/sites/default/files/download/202609/MIT-Robot-Labs-02-press.jpg" alt="Robotic optics laboratory: experimental robot arm setup and researchers demonstrating optical components" width="520"></a>

  <sub>Image: <a href="https://news.mit.edu/2026/robotic-lab-runs-optics-experiments-on-demand-0917">Jennifer Chu / MIT, experimental setup and optical components</a> · CC BY-NC-ND (see MIT News terms) · Unmodified.</sub>

## Contributing

Suggestions, corrections, and pull requests are welcome. Please check that a paper demonstrates real robotic experimentation, choose the most relevant domain and hardware tag(s), and avoid duplicating a preprint and its published version. For a new submission, mention the physical robot or platform in the pull request so that the inclusion criterion can be checked.

Use this format for a published paper:

```markdown
- [ ] **Paper title**  
  `Stationary arm` · `automation station`  
  First Author, Second Author, Third Author, et al.  
  *Journal or Conference*, **YYYY**. [Paper](https://doi.org/DOI) | [arXiv](https://arxiv.org/abs/ID)
```

Leave new entries unchecked; only the repository owner should mark personal verification as complete. Use only the applicable hardware tag(s). Add works tagged `Mobile Robot` to the top index and provide a stable entry anchor. Omit the arXiv link when unavailable. For a preprint-only paper, replace the last line with:

```markdown
  *arXiv preprint*, **YYYY**. [arXiv](https://arxiv.org/abs/ID)
```

When a paper is formally published, update the existing entry with its final title, venue, year, and DOI. Link substantive corrections alongside the paper.

### Images

Images are externally hosted and linked to their sources. Images emphasizing robotic arms, especially mobile robots, are preferred. Selected dedicated automation workflows have their image and credit blocks preserved in HTML comments to keep the rendered list compact. Robot photographs and platform figures are preferred; some entries currently use workflow diagrams or graphical abstracts for review. Image credits and licenses appear below each image; third-party images retain their original licenses. Background images from related publications are explicitly identified. External image URLs may change; the source links and credits help locate replacements. When adding an image, include descriptive alt text, a source link, attribution, and the applicable reuse license.
