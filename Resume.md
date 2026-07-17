---
output: pdf_document
papersize: letter
geometry: margin=0.75in
fontsize: 10pt
colorlinks: false
header-includes:
  - \usepackage{fontspec}
  - \usepackage{fontawesome}
  - \usepackage{enumitem}
  - \usepackage{titlesec}
  - \usepackage{needspace}
  - \usepackage{ragged2e}
  - \setlist[itemize]{leftmargin=1.3em,itemsep=0.08em,topsep=0.02em,parsep=0em,partopsep=0em,after=\vspace{0em}}
  - \setlist[enumerate]{leftmargin=1.5em,itemsep=0.34em,topsep=0.06em,parsep=0em,partopsep=0em}
  - \input{section-format.tex}
  - \titlespacing*{\section}{0pt}{0.48em}{0.28em}
  - \setlength{\parindent}{0pt}
  - \setlength{\parskip}{0em}
  - \raggedbottom
  - \RaggedRight
  - \hyphenpenalty=10000
  - \exhyphenpenalty=10000
---

\begin{center}
{\LARGE\textbf{Arvin Zaker}}\\[-0.1em]
\href{mailto:arvzaker@student.ubc.ca}{\faEnvelopeO\ arvzaker@student.ubc.ca}\quad | \quad
\href{https://github.com/ArvinZaker}{\faGithub\ github.com/ArvinZaker}
\end{center}

\vspace{-0.65em}

# Education

**Doctor of Medicine (MD)** \hfill \textbf{Aug 2025--Present}  
_University of British Columbia (UBC), Vancouver, BC_

**Honours Bachelor of Science, Translational and Molecular Medicine** \hfill \textbf{Sep 2019--Apr 2023}  
_University of Ottawa, Ottawa, ON; cumulative grade point average: 9.98/10_

# Research Experience

**Medical Imaging Artificial Intelligence** \hfill \textbf{Feb 2026--Present}  
_University of British Columbia, Vancouver, BC_  
_Supervisor: Dr. Ilker Hacihaliloglu_

- Built a Python Digital Imaging and Communications in Medicine (DICOM)-to-embedding pipeline for 38,357 mammography image pairs across an initial 7-dataset cohort assembled from 14 datasets.
- Trained and evaluated 1,176 models using 21 image embeddings, 8 classifiers, and 7 weighting or sampling conditions.
- Performed held-out failure analysis on 773 Emory Breast Imaging Dataset (EMBED) image pairs by breast density, race, ethnicity, and histology.

**E-Cigarette Flavour Policy Evaluation** \hfill \textbf{Feb 2026--Present}  
_University of British Columbia, Vancouver, BC_  
_Supervisor: Dr. Kevin Duan_

- Mapped monthly flavour-policy exposure across 10 provinces and 4 Canadian Tobacco and Nicotine Survey (CTNS) waves.
- Developed survey-weighted difference-in-differences analyses across 3 policy groups for vaping, cigarette, and cannabis-use outcomes.

**Epigenomics and Chromatin Biology** \hfill \textbf{Mar 2024--Jan 2026}  
_University of Ottawa, Ottawa, ON_  
_Supervisor: Dr. Arvind Mer_  
_Repository: \faGithub\ \href{https://github.com/ArvinZaker/cut_run_pipeline_nix}{ArvinZaker/cut\_run\_pipeline\_nix}_

- Analyzed clinical exosomal DNA to identify differentially methylated regions and pathways and integrated multi-omics evidence from 44 studies and databases.
- Built a reproducible CUT\&RUN workflow for processing, quality control, annotation, and collaborator use.
- Aggregated and visualized CXXC1 mutational data across the genome and plant homeodomain (PHD).

**Text-Mining Feature Selection for Anticancer Drug Response** \hfill \textbf{Sep 2023--Feb 2024}  
_University of Ottawa, Ottawa, ON_  
_Supervisor: Dr. Arvind Mer_  
_Repository: \faGithub\ \href{https://github.com/merlab/text_features}{merlab/text\_features}_

- Devised and benchmarked text-mining feature-selection methods across drug-response prediction models and validation datasets.
- Built reproducible local and high-performance computing workflows and visualizations for model evaluation.

**Bacterial Genomics** \hfill \textbf{Jul 2023--Feb 2024}  
_University of Ottawa, Ottawa, ON_  
_Supervisors: Dr. Arvind Mer and Dr. Vanessa M. D'Costa_

- Built genomic annotation and phylogenetic-analysis workflows and characterized type IV secretion system clusters across 118 _Acinetobacter_ bacterial and plasmid strains.

**SMC5/6 Cancer Phenogenomics** \hfill \textbf{May 2022--Aug 2022}  
_University of Ottawa, Ottawa, ON_  
_Supervisors: Dr. Arvind Mer and Dr. Damien D'Amours_  
_Repository: \faGithub\ \href{https://github.com/merlab/SMC5-6_complex}{merlab/SMC5-6\_complex}_

- Analyzed SMC5/6 alterations, genomic instability, transcriptomic changes, cancer phenotypes, and survival in a pan-cancer cohort of more than 65,000 patients across 144 studies.

**Optogenetic Neurophysiology** \hfill \textbf{Mar 2022--Sep 2024}  
_University of Ottawa, Ottawa, ON_  
_Supervisors: Dr. Arvind Mer and Dr. Greg Silasi_

- Co-developed software to quantify hemodynamic and cortical responses to optogenetic stimulation after stroke.

**Patient-Derived Xenograft Drug-Response Modelling** \hfill \textbf{Jan 2022--Feb 2024}  
_University of Ottawa, Ottawa, ON_  
_Supervisor: Dr. Arvind Mer_

- Developed the open-source xeMetron package to calculate and compare 250 existing and novel measures of patient-derived xenograft treatment response.
- Performed transcriptomic biomarker discovery and built machine-learning models to predict anticancer drug response, including paclitaxel response in clinical-trial data, and model breast-cancer survival using The Cancer Genome Atlas.

**Bacteriophage Discovery** \hfill \textbf{Sep 2021--Apr 2022}  
_University of Ottawa, Ottawa, ON_  
_Supervisor: Dr. Adam Rudner_

- Isolated, amplified, characterized, and annotated 2 novel bacteriophages, Arzan and Khorshid.

**Muscle Physiology** \hfill \textbf{Nov 2020--Jul 2022}  
_University of Ottawa, Ottawa, ON_  
_Supervisor: Dr. Jean-Marc Renaud_

- Designed electrophysiology experiments on adenosine receptors and skeletal-muscle fatigue and performed tissue staining, fluorescence imaging, and quantitative image analysis.

# Peer-Reviewed Publications

1. Asare-Werehene M, **Zaker A**, Tripathi S, Communal L, Carmona E, Mes-Masson A-M, Tsang BK, Mer A. Spotlight on nuclear PD-L1 in ovarian cancer chemoresistance: hidden but mighty. _Front Immunol._ 2025;16. \href{https://doi.org/10.3389/fimmu.2025.1543529}{doi:10.3389/fimmu.2025.1543529}.

2. Grégoire S, Grégoire J, Yang Y, Capitani S, Joshi M, Sarvan S, **Zaker A**, Ning Z, Figeys D, Ulrich K, Brunzelle JS, Mer A, Couture J-F. Structural insights into an atypical histone binding mechanism by a PHD finger. _Structure._ 2024;32(9):1498--1506.e4. \href{https://doi.org/10.1016/j.str.2024.06.017}{doi:10.1016/j.str.2024.06.017}.

3. Wu G, **Zaker A** (co-first author), Ebrahimi A, Tripathi S, Mer AS. Text-mining-based feature selection for anticancer drug response prediction. _Bioinform Adv._ 2024;4(1):vbae047. \href{https://doi.org/10.1093/bioadv/vbae047}{doi:10.1093/bioadv/vbae047}.

4. Nasser F, Gaudreau A, Lubega S, **Zaker A**, Xia X, Mer AS, D'Costa VM. Characterization of the diversity of type IV secretion system-encoding plasmids in _Acinetobacter_. _Emerg Microbes Infect._ 2024;13(1):2320929. \href{https://doi.org/10.1080/22221751.2024.2320929}{doi:10.1080/22221751.2024.2320929}.

5. Roy S, **Zaker A**, Mer A, D'Amours D. Large-scale phenogenomic analysis of human cancers uncovers frequent alterations affecting SMC5/6 complex components in breast cancer. _NAR Cancer._ 2023;5(3):zcad047. \href{https://doi.org/10.1093/narcan/zcad047}{doi:10.1093/narcan/zcad047}.

# Presentations, Posters, Seminars & Abstracts

1. **Poster and oral presentations; presenting author.** Roy S, **Zaker A**, Mer A, D'Amours D. Large-scale phenogenomic analysis of human cancers uncovers frequent alterations affecting SMC5/6 complex components in breast cancer. _Canadian Society for Molecular Biosciences International Conference_; May 2023; Ottawa, ON. Approximately 10 projects were selected nationally for oral presentation.

2. **Oral presentation; presenting author.** **Zaker A**, Mer A. Comparative analysis of drug response metrics in patient-derived xenografts. _4th Annual University of Ottawa Faculty of Medicine Research Day_; Sep 2022; Ottawa, ON. Panel question period; 18 students were selected.

3. **Seminar; presenter.** **Zaker A**, Mer A. Comparative analysis of drug response metrics in patient-derived xenografts. _University of Ottawa Translational and Molecular Medicine Seminar_; Apr 2022. Twenty-minute presentation and question period.

4. **Poster presentation; presenting author.** **Zaker A**, Mer A. Analysis of drug response in patient-derived xenografts. _Faculty of Medicine, University of Ottawa_; Feb 2022; Ottawa, ON.

5. **Poster and oral presentations; presenting author.** **Zaker A**, McCarthy L, Jung D, Karunakaran G, Rudner A. Discovery and characterization of bacteriophage Arzan. _University of Ottawa Faculty of Medicine_; Dec 2021; Ottawa, ON.

6. **Abstract and poster presentation; presenting author.** **Zaker A**, McRae C, Renaud JM. Role of adenosine receptors in mouse skeletal-muscle fatigue kinetics. _University of Ottawa Undergraduate Research Opportunity Program Symposium_; Mar 2021.

\Needspace{9\baselineskip}
7. **Published abstract and presentation; co-presenter.** Featherstone A, Radar A, Salama A, Tiukuvaara S, Ferri O, **Zaker A**, Algharbi S, Mahdi O, Setia G, Friesen R, Wang GSY, Li J, Gao R, Jung D, Karunakaran G, Znamenski E, Ristovski M, Sarakbi R, Freitas JD, McCarthy L, Williams EC, D'Ambrosio L, Wheaton K, Rudner AD. \href{https://seaphages.org/abstracts/summary/980/}{Give us a millet of your time: dehusking the singleton bacteriophage Arzan}. _Science Education Alliance--Phage Hunters Advancing Genomics and Evolutionary Science Symposium_; 2022; Pittsburgh, PA.

8. **Published abstract and presentation; co-presenter.** Friesen R, Algharbi S, **Zaker A**, Mahdi O, Gao R, Ferri O, Li J, Wang GSY, Heffernan C, Featherstone A, Radar A, Gandelman M, Chander N, Bancud SE, Rege I, Shriraam R, Jung D, Karunakaran G, Sarakbi R, Znamenski E, Ristovski M, Freitas JD, McCarthy L, Williams EC, D'Ambrosio L, Chan K, Wheaton K, Rudner AD. \href{https://seaphages.org/abstracts/summary/978/}{Investigating nucleotide-binding proteins in bacteriophage JohnDoe}. _Science Education Alliance--Phage Hunters Advancing Genomics and Evolutionary Science Symposium_; 2022; Pittsburgh, PA.

9. **Published abstract and presentation; co-presenter.** Cildir Z, Abdisalam S, Alam A, **Zaker A**, Toex N, Chandra A, Jung D, Karunakaran G, Znamenski E, Freitas JD, McCarthy L, Williams EC, D'Ambrosio L, Wheaton K, Rudner AD. \href{https://seaphages.org/abstracts/summary/973/}{Prophage liberation! A method to increase the titer of the temperate phages Khorsid and Winseler}. _Science Education Alliance--Phage Hunters Advancing Genomics and Evolutionary Science Symposium_; 2022; Pittsburgh, PA.

# Leadership & Governance

**Research and Innovation Lead** \hfill \textbf{Jul 2026--Present}  
_MD Student Learning Group, University of British Columbia, Vancouver, BC_

- Lead the research and innovation portfolio, connecting peers with learning opportunities and promoting evidence-informed practice, emerging technologies, and student-led scholarship.

**Vice-President, External Relations** \hfill \textbf{Jul 2026--Present}  
_Artificial Intelligence in Medicine Society, University of British Columbia, Vancouver, BC_

- Helped launch a student community focused on responsible artificial intelligence in health care and build external partnerships for panels, workshops, and collaborative projects.

**Chief Technology Officer** \hfill \textbf{Jun 2026--Present}  
_Learn Freely, nonprofit organization, Vancouver, BC_

- Lead development of a learning management system and workflows for tutoring assignments, progress tracking, project management, and organizational collaboration.

**Board Member** \hfill \textbf{Jun 2026--Present}  
_Inclusion, Diversity and Equity Advisory Committee, Doctors of BC, Vancouver, BC; three-year term_

- Selected to advise the Board of Directors on equity, diversity, and inclusion across governance bodies, members, and the medical profession.

**Founder and President** \hfill \textbf{Jun 2020--Sep 2024}  
_Hands on Health Magazine, University of Ottawa, Ottawa, ON_

- Founded and led a 20+ member team that published 50+ faculty-reviewed, evidence-based health articles.
- Built editorial, review, and communication workflows that sustained publication during remote operations.

**Founder and President** \hfill \textbf{Dec 2020--Apr 2023}  
_Canadians Sharing Locally and Globally uOttawa, University of Ottawa, Ottawa, ON_

- Partnered with a local charity to help raise more than $100,000 for personal protective equipment and ventilators for rural hospitals in India.
- Led advocacy events and social media outreach on global health inequities and social determinants of health.

# Teaching & Mentorship

**Founder and Production Designer** \hfill \textbf{Apr 2026--Present}  
_UBC Integrated Anatomy Atlas, University of British Columbia, Vancouver, BC_

- Founded and produced a faculty-approved anatomy platform spanning both preclinical years and collaborated with faculty to integrate it into UBC's Elentra learning management system for access by all medical students.
- Produced anatomy images and 320 question cards across 14 laboratory modules in Anki, study-site, and simulated bell-ringer formats.
- Built a Python production pipeline with standardized image attribution, contributor guidance, approval tracking, and automated quality checks.

**Premedical Student Mentor** \hfill \textbf{Aug 2025--Present}  
_Supporting Applications, Supporting Interviews (SASI), Community of Support, Temerty Faculty of Medicine, University of Toronto, Toronto, ON_

- Mentor premedical students from groups underrepresented in medicine through individualized application strategy and feedback on written submissions.

**Science, Technology, Engineering, and Mathematics Tutor** \hfill \textbf{Sep 2023--Jul 2025}  
_Oxford Learning Oak Ridges and Inspiration Learning, Toronto, ON_

- Tutored 20+ students from grades 1--12 and university across biology, chemistry, physics, and mathematics using individualized learning plans.

**Peer Tutor and Mentor** \hfill \textbf{Sep 2018--Present}

- Guided 50+ middle-school and high-school students in science and mathematics and supported transitions to university through academic guidance and peer mentorship.

# Community Engagement

**First-Year Representative** \hfill \textbf{Sep 2025--Sep 2026}  
_Persian Medical Society, University of British Columbia, Vancouver, BC_

- Help create and promote peer-support, mentorship, and cultural events for Persian-identifying students and allies, strengthening community connection and inclusive representation within the medical school.

\Needspace{4\baselineskip}
**Administrative Receptionist** \hfill \textbf{Sep 2022--Jun 2023}  
_Chadha Medical Clinic, Ottawa, ON_

- Coordinated appointments, referrals, and screenings in a primary-care practice serving approximately 5,000 patients and managed 60+ patient contacts weekly.

\Needspace{4\baselineskip}
**Volunteer Coordinator and Co-Chair** \hfill \textbf{Sep 2020--Sep 2024}  
_Best Buddies uOttawa, University of Ottawa, Ottawa, ON_

- Recruited and paired 50+ student volunteers with people with intellectual and developmental disabilities.
- Led accessible events and revised recruitment to address audiovisual and language barriers identified through feedback.

# Honours, Scholarships & Awards

**Florence E. Heighway Summer Research Award** \hfill \textbf{Jun 2026--Aug 2026}  
_Faculty of Medicine Summer Student Research Program, University of British Columbia, Vancouver, BC_

- Awarded 8 weeks of funding for a mammography artificial-intelligence failure-analysis project.

**Third Place, IFHP NavAID Challenge** \hfill \textbf{Jun 2026}  
_University of British Columbia, Vancouver, BC_

- Collaborated with 2 medical students to develop a 75-minute refugee-health case with 4 decision points and 7 interprofessional objectives.

**Undergraduate Student Research Award** \hfill \textbf{May 2023--Aug 2023}  
_Natural Sciences and Engineering Research Council of Canada, University of Ottawa, Ottawa, ON_

- Awarded $7,500 for a 3-month research project based on academic merit and research-proposal quality; one of 88 awards at the University of Ottawa.

**Translational and Molecular Medicine Summer Training Award** \hfill \textbf{May 2022--Aug 2022}  
_University of Ottawa, Ottawa, ON_

- Awarded $8,900 for a 3-month supervised research project based on academic merit and research-proposal quality.

**Work in Biomedical Research Scholarship** \hfill \textbf{May 2022--Aug 2022}  
_University of Ottawa, Ottawa, ON_

- Awarded $3,500 for a 3-month research project through a competition with a success rate below 50\%.

**Undergraduate Research Opportunity Program Award** \hfill \textbf{Dec 2020}  
_University of Ottawa, Ottawa, ON_

- Awarded $1,000 for a 4-month supervised research project based on academic merit and research-proposal quality.

**Dean's Honour List and Merit Scholarship**, University of Ottawa \hfill \textbf{Sep 2019--Apr 2023}

# Projects & Interests

**Explainable Heart-Disease Risk Modelling** \hfill \textbf{Mar 2026}  
_National Canadian Medical Datathon, Vancouver, BC_  
_Repository: \faGithub\ \href{https://github.com/ArvinZaker/md_datathon_2026}{ArvinZaker/md\_datathon\_2026}_

- Collaborated with 5 colleagues to integrate 920 records from 4 University of California, Irvine heart-disease cohorts and develop a regularized logistic-regression model with a held-out receiver operating characteristic area under the curve of 0.925.
- Built CLEAR, an R Shiny demonstration tool providing individualized risk estimates, SHapley Additive exPlanations, and plain-language feature summaries.

**Clinical Bioinformatics Reproducibility Project** \hfill \textbf{Mar 2023}  
_Repository: \faGithub\ \href{https://github.com/ArvinZaker/vinas-clin-sci-2022}{ArvinZaker/vinas-clin-sci-2022}_

- Reproduced the bioinformatics analysis reported by Viñas et al. (2020; PMID: 32662516) and produced a documented report, presentation, and explanatory visualizations.

**Systems Administration and Research Computing** \hfill \textbf{Jan 2022--Present}

- Built and maintain a 16-terabyte Unraid server for centralized family storage, automated backups, data recovery, and Docker-based web services.
- Built and administer 3 Linux workstations for bioinformatics, machine learning, and high-performance computing.
