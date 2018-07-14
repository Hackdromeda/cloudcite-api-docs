# Style Search API

{% api-method method="post" host="https://api.cloudcite.net" path="/style" %}
{% api-method-summary %}
Style
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="x-api-key" type="string" required=true %}
Your API Key
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="Request" type="object" required=true %}
Use the request formats below
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
It worked!
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=304 %}
{% api-method-response-example-description %}
The response you have cached hasn't changed.
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=400 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=401 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=403 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=422 %}
{% api-method-response-example-description %}
You are missing a required field in the request body.
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=500 %}
{% api-method-response-example-description %}
Something went wrong. Check the request body you sent us.
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

## Supported Styles

* 3 Biotech
* 3D Printing in Medicine
* 3D Research
* 3D-Printed Materials and Systems
* 4OR (4OR-Q J Oper Res)
* AAPG Bulletin
* AAPS Open
* AAPS PharmSciTech
* Abhandlungen aus dem Mathematischen Seminar der Universität Hamburg (Abh. Math. Semin. Univ. Hambg.)
* ABI Technik (German)
* Academic Medicine
* Academic Pediatrics
* Academic Psychiatry
* Academic Questions (Acad. Quest.)
* Academy of Management Discoveries
* Academy of Management Journal
* Academy of Management Learning and Education
* Academy of Management Perspectives
* Academy of Management Proceedings
* Academy of Management Review (AMR)
* Accident Analysis and Prevention
* Accounting Forum
* Accounting History Review
* Accounting, Organizations and Society
* Accounts of Chemical Research (Acc. Chem. Res.)
* Accreditation and Quality Assurance (Accred Qual Assur)
* Achievements in the Life Sciences
* ACM Computing Surveys (CSUR)
* ACM Journal on Emerging Technologies in Computing Systems (JETC)
* ACM SIG Proceedings ("et al." for 15+ authors)
* ACM SIG Proceedings ("et al." for 3+ authors)
* ACM SIGCHI Proceedings - Extended Abstract Format (CHI Extended Abstract Format)
* ACM SIGCHI Proceedings (2016)
* ACM SIGGRAPH
* ACM Transactions on Accessible Computing (TACCESS)
* ACM Transactions on Algorithms (TALG)
* ACM Transactions on Applied Perception (TAP)
* ACM Transactions on Architecture and Code Optimization (TACO)
* ACM Transactions on Asian Language Information Processing (TALIP)
* ACM Transactions on Autonomous and Adaptive Systems (TAAS)
* ACM Transactions on Computation Theory (TOCT)
* ACM Transactions on Computational Logic (TOCL)
* ACM Transactions on Computer Systems (TOCS)
* ACM Transactions on Computer-Human Interaction (TOCHI)
* ACM Transactions on Computing Education (TOCE)
* ACM Transactions on Database Systems (TODS)
* ACM Transactions on Design Automation of Electronic Systems (TODAES)
* ACM Transactions on Embedded Computing Systems (TECS)
* ACM Transactions on Graphics (TOG)
* ACM Transactions on Information and System Security (TISSEC)
* ACM Transactions on Information Systems (TOIS)
* ACM Transactions on Intelligent Systems and Technology (TIST)
* ACM Transactions on Interactive Intelligent Systems (TIIS)
* ACM Transactions on Internet Technology (TOIT)
* ACM Transactions on Knowledge Discovery from Data (TKDD)
* ACM Transactions on Management Information Systems (TMIS)
* ACM Transactions on Mathematical Software (TOMS)
* ACM Transactions on Modeling and Computer Simulation (TOMACS)
* ACM Transactions on Multimedia Computing, Communications, and Applications (TOMCCAP)
* ACM Transactions on Parallel Computing (TOPC)
* ACM Transactions on Programming Languages and Systems (TOPLAS)
* ACM Transactions on Reconfigurable Technology and Systems (TRETS)
* ACM Transactions on Sensor Networks (TOSN)
* ACM Transactions on Software Engineering and Methodology (TOSEM)
* ACM Transactions on Spatial Algorithms and Systems (TSAS)
* ACM Transactions on Speech and Language Processing (TSLP)
* ACM Transactions on Storage (TOS)
* ACM Transactions on the Web (TWEB)
* Acoustics Australia
* ACS Applied Energy Materials (ACS Appl. Energy Mater.)
* ACS Applied Materials & Interfaces (ACS Appl. Mater. Interfaces)
* ACS Applied Nano Materials (ACS Appl. Nano Mater.)
* ACS Biomaterials Science & Engineering
* ACS Catalysis (ACS Catal.)
* ACS Chemical Biology (ACS Chem. Biol.)
* ACS Chemical Neuroscience (ACS Chem. Neurosci.)
* ACS Combinatorial Science (ACS Comb. Sci.)
* ACS Earth and Space Chemistry
* ACS Energy Letters
* ACS Infectious Diseases
* ACS Macro Letters (ACS Macro Lett.)
* ACS Medicinal Chemistry Letters (ACS Med. Chem. Lett.)
* ACS Nano
* ACS Photonics
* ACS Sustainable Chemistry & Engineering (ACS Sustainable Chem. Eng.)
* ACS Synthetic Biology (ACS Synth. Biol.)
* Acta Agriculturae Scandinavica, Section B - Soil & Plant Science
* Acta Amazonica (AA)
* Acta Anaesthesiologica Scandinavica
* Acta Anaesthesiologica Taiwanica (AAT)
* Acta Analytica (Acta Anal)
* Acta Applicandae Mathematicae (Acta Appl Math)
* Acta Astronautica
* Acta Biomaterialia
* Acta Biotheoretica (Acta Biotheor)
* Acta Botanica Gallica
* Acta chirurgiae orthopaedicae et traumatologiae Čechoslovaca
* Acta Crystallographica Section A: Foundations and Advances
* Acta Crystallographica Section B: Structural Science, Crystal Engineering and Materials
* Acta Crystallographica Section C: Structural Chemistry
* Acta Crystallographica Section D: Biological Crystallography
* Acta Crystallographica Section E: Structure Reports Online
* Acta Crystallographica Section F: Structural Biology Communications
* Acta Cytologica
* Acta de Investigación Psicológica
* Acta Diabetologica (Acta Diabetol)
* Acta Ecologica Sinica
* acta ethologica (acta ethol)
* Acta Geochimica
* Acta Geodaetica et Geophysica (Acta Geod Geophys)
* Acta Geotechnica (Acta Geotech.)
* Acta Haematologica
* Acta Haematologica Polonica
* Acta Histochemica
* Acta Materialia
* Acta Mathematica Vietnamica
* Acta Mechanica (Acta Mech)
* Acta Mechanica Sinica
* Acta Mechanica Solida Sinica
* Acta Medica
* Acta Médica Colombiana
* Acta Metallurgica Sinica
* Acta Naturae
* Acta Neurochirurgica
* Acta Neurologica Belgica (Acta Neurol Belg)
* Acta Neuropathologica (Acta Neuropathol)
* Acta Neuropathologica Communications
* Acta Oecologica
* Acta Ophthalmologica
* Acta Orthopaedica
* Acta Orthopædica Belgica
* Acta Orthopaedica et Traumatologica Turcica
* Acta Otorrinolaringológica Española (Spanish)
* Acta Paediatrica
* Acta Palaeontologica Polonica
* Acta Pharmaceutica
* Acta Pharmaceutica Sinica B (APSB)
* Acta Pharmacologica Sinica
* Acta Philosophica (ActaPhil)
* Acta Physiologiae Plantarum (Acta Physiol Plant)
* Acta Polytechnica
* Acta Psychiatrica Scandinavica
* Acta Psychologica
* Acta Radiologica
* Acta Scientiae Veterinariae
* Acta Societatis Botanicorum Poloniae (ASBP)
* Acta Sociológica
* Acta Tropica
* Acta Universitatis Agriculturae et Silviculturae Mendelianae Brunensis (Acta Univ. Agric. Silvic. Mendelianae Brun.)
* Acta Universitatis Agriculturae Sueciae (Swedish University of Agricultural Sciences) (Swedish)
* Acta Veterinaria Scandinavica
* Action Learning: Research and Practice
* Actualités pharmaceutiques
* Actuators
* Acupuncture and Related Therapies
* Acupuncture in Medicine
* Ad Hoc Networks
* Adaptive Human Behavior and Physiology
* Addiction Biology
* Addiction Science & Clinical Practice
* Addictive Behaviors
* Addictive Behaviors Reports
* Additive Manufacturing
* ADHD Attention Deficit and Hyperactivity Disorders (ADHD Atten Def Hyp Disord)
* Adipocyte
* Administration and Policy in Mental Health and Mental Health Services Research (Adm Policy Ment Health)
* Administrative Science Quarterly (ASQ)
* Administrative Sciences
* Adolescent Research Review
* Adsorption
* Advanced Composite Materials
* Advanced Drug Delivery Reviews
* Advanced Engineering Informatics
* Advanced Engineering Materials
* Advanced Functional Materials
* Advanced Healthcare Materials (AHM)
* Advanced Industrial and Engineering Polymer Research
* Advanced Materials
* Advanced Medicinal Chemistry Letters
* Advanced Modeling and Simulation in Engineering Sciences
* Advanced Optical Materials
* Advanced Organic Chemistry Letters
* Advanced Powder Technology
* Advanced Robotics
* Advanced Structural and Chemical Imaging
* Advances in Accounting
* Advances in Alzheimer's Disease
* Advances in Applied Clifford Algebras
* Advances in Biological Regulation
* Advances in Biomarker Sciences and Technology
* Advances in Building Energy Research
* Advances in Climate Change Research
* Advances in Colloid and Interface Science
* Advances in Complex Systems
* Advances in Computational Mathematics (Adv Comput Math)
* Advances in Cosmetic Surgery
* Advances in Data Analysis and Classification (Adv Data Anal Classif)
* Advances in Difference Equations
* Advances in Digestive Medicine
* Advances in Eating Disorders: Theory, Research and Practice
* Advances in Engineering Software
* Advances in Geosciences
* Advances in Health Sciences Education (Adv in Health Sci Educ)
* Advances in Integrative Medicine
* Advances in Life Course Research
* Advances in Manufacturing (Adv. Manuf.)
* Advances in Medical Sciences
* Advances in Natural Sciences: Nanoscience and Nanotechnology
* Advances in Nutrition
* Advances in Oceanography and Limnology
* Advances in Ophthalmology and Optometry
* Advances in Physiology Education
* Advances in Radiation Oncology
* Advances in Radio Science
* Advances in School Mental Health Promotion
* Advances in Science and Research
* Advances in Simulation
* Advances in Space Research
* Advances in Therapy
* Advances in Water Resources
* Aeolian Research
* Aequationes mathematicae (Aequat. Math.)
* Aerobiologia
* Aerosol Science and Technology
* Aerospace
* Aerospace Science and Technology
* Aesthetic Plastic Surgery (Aesth Plast Surg)
* Aethiopica
* Aethiopistische Forschungen
* AEUE - International Journal of Electronics and Communications
* Africa Review
* African and Black Diaspora: An International Journal
* African Archaeological Review (Afr Archaeol Rev)
* African Geographical Review
* African Identities
* African Journal of Emergency Medicine
* African Journal of Urology
* African Zoology
* Afrika Matematika (Afr. Mat.)
* AGE
* Age and Ageing
* Ageing & Society
* Ageing International (Ageing Int)
* Ageing Research Reviews
* Aggression and Violent Behavior
* Aging
* Aging & Mental Health
* Aging Cell
* Aging Clinical and Experimental Research
* Aging Health
* Aging, Neuropsychology, and Cognition
* Agri Gene
* Agricultural and Food Economics
* Agricultural and Forest Meteorology
* Agricultural Research (Agric Res)
* Agricultural Systems
* Agricultural Water Management
* Agriculture
* Agriculture & Food Security
* Agriculture and Human Values (Agric Hum Values)
* Agriculture and Natural Resources
* Agriculture, Ecosystems and Environment
* Agroforestry Systems (Agroforest Syst)
* Agronomy
* Agronomy for Sustainable Development (Agron. Sustain. Dev.)
* Agronomy Journal
* AI & SOCIETY (AI & Soc)
* AIAA Journal
* AIDS
* AIDS and Behavior (AIDS Behav)
* AIDS Care
* AIDS Research and Therapy
* Ain Shams Engineering Journal
* AINS
* AIP Advances
* Air Quality, Atmosphere & Health (Air Qual Atmos Health)
* Aix-Marseille Université - Département d'études asiatiques (French) (AMU-DEA)
* AKCE International Journal of Graphs and Combinatorics
* Aktuelle Dermatologie
* Aktuelle Ernährungsmedizin
* Aktuelle Kardiologie
* Aktuelle Neurologie
* Aktuelle Rheumatologie
* Aktuelle Urologie
* Al-Jami'ah - Journal of Islamic Studies (AJIS)
* Albert-Ludwigs-Universität Freiburg - Geschichte (German)
* Alcohol
* Alcoholism and Drug Addiction
* Alcoholism: Clinical and Experimental Research
* Alergologia Polska- Polish Journal of Allergology
* Alexandria Engineering Journal
* Alexandria Journal of Medicine
* Algal Research
* Algebra universalis (Algebra Univers.)
* Algebras and Representation Theory (Algebr Represent Theor)
* Algorithmica
* Algorithms
* Algorithms for Molecular Biology
* Allergology International (ALIT)
* Allergy
* Allergy, Asthma & Clinical Immunology
* Allgemein- und Viszeralchirurgie up2date
* Alpine Botany (Alp Botany)
* Alter - European Journal of Disability research, Revue européenne de recherche sur le handicap
* Alternatives to Animal Experimentation (ALTEX)
* Alzheimer's & Dementia: Diagnosis, Assessment & Disease Monitoring
* Alzheimer's & Dementia: The Journal of the Alzheimer's Association
* Alzheimer's & Dementia: Translational Research & Clinical Interventions
* Alzheimer's Research & Therapy
* AMAR Analytic Methods in Accident Research.
* AMB Express
* AMBIO
* Ameghiniana
* American Anthropological Association (AAA)
* American Antiquity
* American Association for Cancer Research (AACR)
* American Association of Petroleum Geologists
* American Chemical Society (ACS)
* American Educational Research Journal
* American Entomologist
* American Family Physician
* American Fisheries Society
* American Geophysical Union (AGU)
* American Heart Association
* American Heart Journal
* American Institute of Aeronautics and Astronautics (AIAA)
* American Institute of Physics (AIP)
* American Journal of Agricultural Economics (AJAE)
* American Journal of Alzheimer's Disease & Other Dementias
* American Journal of Archaeology (AJA)
* American Journal of Botany
* American Journal of Cardiovascular Drugs (Am J Cardiovasc Drugs)
* American Journal of Climate Change (AJCC)
* American Journal of Clinical Dermatology (Am J Clin Dermatol)
* American Journal of Clinical Pathology
* American Journal of Community Psychology (Am J Community Psychol)
* American Journal of Criminal Justice (Am J Crim Just)
* American Journal of Dance Therapy (Am J Dance Ther)
* American Journal of Enology and Viticulture (AJEV)
* American Journal of Epidemiology
* American Journal of Gastroenterology Supplements
* American Journal of Health Behavior (AJHB)
* American Journal of Health-System Pharmacy
* American Journal of Hypertension (AJH)
* American Journal of Industrial Medicine
* American Journal of Infection Control
* American Journal of Kidney Diseases
* American Journal of Medical Genetics
* American Journal of Nephrology
* American Journal of Neuroradiology (AJNR)
* American Journal of Obstetrics & Gynecology
* American Journal of Ophthalmology
* American Journal of Ophthalmology Case Reports
* American Journal of Orthodontics & Dentofacial Orthopedics
* American Journal of Orthopsychiatry
* American Journal of Otolaryngology--Head and Neck Medicine and Surgery
* American Journal of Physical Anthropology
* American Journal of Physiology - Cell Physiology
* American Journal of Physiology - Endocrinology and Metabolism
* American Journal of Physiology - Gastrointestinal and Liver Physiology
* American Journal of Physiology - Heart and Circulatory Physiology
* American Journal of Physiology - Lung Cellular and Molecular Physiology
* American Journal of Physiology - Regulatory, Integrative, and Comparative Physiology
* American Journal of Physiology - Renal Physiology
* American Journal of Plant Sciences
* American Journal of Political Science (AJPS)
* American Journal of Potato Research (Am. J. Potato Res.)
* American Journal of Primatology
* American Journal of Public Health
* American Journal of Reproductive Immunology
* American Journal of Respiratory and Critical Care Medicine
* American Journal of Roentgenology (AJR)
* American Journal of Science (AJS)
* American Journal of Surgical Pathology
* American Journal of Translational Research (AJTR)
* American Journal of Veterinary Research
* American Marketing Association (AMA)
* American Medical Association (AMA)
* American Medical Association (no "et al.") (AMA)
* American Medical Association (no URL) (AMA)
* American Medical Association (sorted alphabetically) (AMA)
* American Medical Writers Association Journal (AMWA Journal)
* American Meteorological Society (AMS)
* American Mineralogist
* American Nuclear Society (ANS)
* American Physics Society (APS)
* American Physiological Society (APS)
* American Phytopathological Society (APS)
* American Political Science Association (APSA)
* American Political Science Review
* American Psychological Association 5th edition (APA)
* American Psychological Association 6th edition (APA)
* American Psychological Association 6th edition ("doi:" DOI prefix) (APA)
* American Psychological Association 6th edition (annotated bibliography with abstract) (APA)
* American Psychological Association 6th edition (curriculum vitae, sorted by descending date) (APA)
* American Psychological Association 6th edition (no ampersand) (APA)
* American Psychological Association 6th edition (no DOIs, no issue numbers) (APA)
* American Psychological Association 6th edition (Provost) (French - Canada) (APA FR Provost)
* American Psychological Association 6th edition (single-spaced bibliography) (APA)
* American Psychological Association 6th edition (Turkish) (APA)
* American Psychologist
* American Review of Canadian Studies
* American Society for Microbiology (ASM)
* American Society for Pharmacology and Experimental Therapeutics (ASPET)
* American Society of Agricultural and Biological Engineers (ASABE)
* American Society of Agronomy, Crop Science Society of America, Soil Science Society of America (ASA-CSSA-SSSA)
* American Society of Civil Engineers (ASCE)
* American Society of Mechanical Engineers (ASME)
* American Sociological Association (ASA)
* American Sociological Review
* American Statistical Association (ASA)
* American Veterinary Medical Association
* Amino Acids
* Ampersand
* Amphibia-Reptilia (AMRE)
* AMS Review (AMS Rev)
* Anabases (French)
* Anaerobe
* Anaesthesia
* Anaesthesia and Intensive Care
* Anaesthesia Critical Care & Pain Medicine
* Anales de Antropología
* Anales de Pediatría (Spanish)
* Analog Integrated Circuits and Signal Processing (Analog Integr Circ Sig Process)
* Analysis and Mathematical Physics (Anal.Math.Phys.)
* Analyst
* Analytic Methods in Accident Research
* Analytica Chimica Acta
* Analytical and Bioanalytical Chemistry (Anal Bioanal Chem)
* Analytical Biochemistry
* Analytical Chemistry (Anal. Chem.)
* Analytical Chemistry Research
* Analytical Methods
* Analytical Sciences (Anal. Sci.)
* Anatolia
* Anatomical Science International (Anat Sci Int)
* Anesthesia and Analgesia
* Anesthésie & Réanimation
* Anesthesiology
* Angelaki
* Angewandte Chemie International Edition
* Angiogenesis
* Angiologia (Spanish) (ANGIO)
* Anglia Ruskin University - Harvard
* animal
* Animal Behaviour
* Animal Biotelemetry
* Animal Cells and Systems
* Animal Cognition (Anim Cogn)
* Animal Conservation
* Animal Feed Science and Technology
* Animal Gene
* Animal Migration (AMI)
* Animal Nutrition
* Animal Production Science
* Animal Reproduction Science
* Animal Welfare
* Animals
* Annalen des Naturhistorischen Museums in Wien
* Annales d'Endocrinologie
* Annales de cardiologie et d'angéiologie
* Annales de chirurgie plastique esthétique
* Annales de Chirurgie Vasculaire
* Annales de Dermatologie et de Vénéréologie
* Annales de l'Institut Henri Poincaré / Analyse non linéaire
* Annales de Paléontologie
* Annales de Pathologie
* Annales Françaises d'Anesthésie et de Réanimation
* Annales françaises d'oto-rhino-laryngologie et de pathologie cervico-faciale
* Annales Geophysicae
* Annales Henri Poincaré (Ann. Henri Poincaré)
* Annales mathématiques du Québec
* Annales médico-psychologiques
* Annales Pharmaceutiques Françaises
* Annales. Histoire, Sciences sociales (French)
* ANNALI DELL'UNIVERSITA' DI FERRARA (Ann Univ Ferrara)
* Annali di Matematica Pura ed Applicata (Annali di Matematica)
* Annals of Agrarian Science
* Annals of Agricultural Sciences
* Annals of Allergy, Asthma & Immunology
* Annals of Anatomy
* Annals of Applied Biology
* Annals of Behavioral Medicine
* Annals of Behavioral Science and Medical Education
* Annals of Biomedical Engineering
* Annals of Botany
* Annals of Clinical & Laboratory Science
* Annals of Clinical Biochemistry
* Annals of Clinical Microbiology and Antimicrobials
* Annals of Data Science
* Annals of Diagnostic Pathology
* Annals of Dyslexia (Ann. of Dyslexia)
* Annals of Emergency Medicine
* Annals of Epidemiology
* Annals of Finance (Ann Finance)
* Annals of Forest Science
* Annals of General Psychiatry
* Annals of Global Analysis and Geometry (Ann Glob Anal Geom)
* Annals of Global Health
* Annals of Hematology (Ann Hematol)
* Annals of Intensive Care
* Annals of Internal Medicine
* Annals of Joint (AOJ)
* Annals of Leisure Research
* Annals of Mathematics and Artificial Intelligence (Ann Math Artif Intell)
* Annals of Medicine and Surgery
* Annals of Microbiology (Ann Microbiol)
* Annals of Neurology
* Annals of Nuclear Energy
* Annals of Nuclear Medicine (Ann Nucl Med)
* Annals of Nutrition & Metabolism
* Annals of Occupational and Environmental Medicine
* Annals of Oncology
* Annals of Operations Research (Ann Oper Res)
* Annals of Otology, Rhinology and Laryngology
* Annals of Physical and Rehabilitation Medicine
* Annals of Physics
* Annals of Saudi Medicine
* Annals of Solid and Structural Mechanics (Ann. Solid Struct. Mech.)
* Annals of Surgery
* Annals of Surgical Innovation and Research
* annals of telecommunications - annales des télécommunications (Ann. Telecommun.)
* Annals of the Association of American Geographers
* Annals of the Entomological Society of America
* Annals of the ICRP
* Annals of the Institute of Statistical Mathematics (Ann Inst Stat Math)
* Annals of the New York Academy of Sciences
* Annals of the Rheumatic Diseases
* Annals of the Royal College of Surgeons of England
* Annals of Tourism Research
* Annals of Tropical Paediatrics
* Annals, Academy of Medicine, Singapore
* Annual Review of Analytical Chemistry
* Annual Review of Animal Biosciences
* Annual Review of Anthropology
* Annual Review of Astronomy and Astrophysics
* Annual Review of Biochemistry
* Annual Review of Biomedical Engineering
* Annual Review of Biophysics
* Annual Review of Cell and Developmental Biology
* Annual Review of Chemical and Biomolecular Engineering
* Annual Review of Clinical Psychology
* Annual Review of Condensed Matter Physics
* Annual Review of Earth and Planetary Sciences
* Annual Review of Ecology, Evolution, and Systematics
* Annual Review of Economics
* Annual Review of Entomology
* Annual Review of Environment and Resources
* Annual Review of Financial Economics
* Annual Review of Fluid Mechanics
* Annual Review of Food Science and Technology
* Annual Review of Genetics
* Annual Review of Genomics and Human Genetics
* Annual Review of Immunology
* Annual Review of Law and Social Science
* Annual Review of Marine Science
* Annual Review of Materials Research
* Annual Review of Medicine
* Annual Review of Microbiology
* Annual Review of Neuroscience
* Annual Review of Nuclear and Particle Science
* Annual Review of Nutrition
* Annual Review of Organizational Psychology and Organizational Behavior
* Annual Review of Pathology: Mechanisms of Disease
* Annual Review of Pharmacology and Toxicology
* Annual Review of Physical Chemistry
* Annual Review of Physiology
* Annual Review of Phytopathology
* Annual Review of Plant Biology
* Annual Review of Political Science
* Annual Review of Psychology
* Annual Review of Public Health
* Annual Review of Resource Economics
* Annual Review of Sociology
* Annual Review of Statistics and Its Application
* Annual Review of Virology
* Annual Reviews (author-date)
* Annual Reviews (sorted alphabetically)
* Annual Reviews (sorted by order of appearance, without titles)
* Annual Reviews (sorted by order of appearance)
* Annual Reviews in Control
* ANPET - Congresso de Pesquisa e Ensino em Transportes (Portuguese - Brazil) (ANPET)
* Ansiedad y Estrés
* Antarctic Science
* Anthropocene
* Anthropologie et Sociétés (French)
* Anthropology & Medicine
* Antibiotics
* Antibodies
* Anticancer Research
* Antimicrobial Agents and Chemotherapy (AAC)
* Antimicrobial Resistance and Infection Control
* Antioxidants
* Antiquity
* Antiviral Research
* Antonie van Leeuwenhoek
* Anuario de Psicología
* Anuario de Psicología Jurídica
* Anxiety, Stress & Coping
* AORN Journal
* APCBEE Procedia
* Aphasiology
* APL Materials
* Apollo Medicine
* Apoptosis
* Appetite
* Applicable Algebra in Engineering, Communication and Computing (AAECC)
* Applicable Analysis
* Applied & Translational Genomics
* Applied Acoustics
* Applied Adhesion Science
* Applied and Computational Harmonic Analysis
* Applied and Environmental Microbiology (AEM)
* Applied Animal Behaviour Science
* Applied Biochemistry and Biotechnology (Appl Biochem Biotechnol)
* Applied Catalysis A, General
* Applied Catalysis B: Environmental
* Applied Categorical Structures (Appl Categor Struct)
* Applied Clay Science
* Applied Composite Materials (Appl Compos Mater)
* Applied Computing and Informatics
* Applied Energy
* Applied Engineering in Agriculture
* Applied Entomology and Zoology (Appl Entomol Zool)
* Applied Ergonomics
* Applied Geochemistry
* Applied Geography
* Applied Geomatics (Appl Geomat)
* Applied Health Economics and Health Policy (Appl Health Econ Health Policy)
* Applied In Vitro Toxicology
* Applied Informatics
* Applied Intelligence (Appl Intell)
* Applied Magnetic Resonance (Appl Magn Reson)
* Applied Materials Today
* Applied Mathematical Finance
* Applied Mathematical Modelling
* Applied Mathematics & Optimization (Appl Math Optim)
* Applied Mathematics and Computation
* Applied Mathematics Letters
* Applied Mechanics Reviews
* Applied Microbiology and Biotechnology (Appl Microbiol Biotechnol)
* Applied Nanomedicine
* Applied Nanoscience (Appl Nanosci)
* Applied Network Science
* Applied Nursing Research
* Applied Ocean Research
* Applied Petrochemical Research (Appl Petrochem Res)
* Applied Physics A (Appl. Phys. A)
* Applied Physics B (Appl. Phys. B)
* Applied Physics Letters
* Applied Physiology, Nutrition, and Metabolism
* Applied Psychophysiology and Biofeedback (Appl Psychophysiol Biofeedback)
* Applied Radiation and Isotopes
* Applied Research in Quality of Life (Applied Research Quality Life)
* Applied Sciences
* Applied Soft Computing Journal
* Applied Soil Ecology
* Applied Spatial Analysis and Policy (Appl. Spatial Analysis)
* Applied Spectroscopy
* Applied Spectroscopy Reviews
* Applied Surface Science
* Applied Thermal Engineering
* Applied Water Science (Appl Water Sci)
* Aquacultural Engineering
* Aquaculture
* Aquaculture and Fisheries
* Aquaculture Environment Interactions
* Aquaculture International (Aquacult Int)
* Aquaculture Reports
* Aquatic Biology
* Aquatic Botany
* Aquatic Conservation: Marine and Freshwater Ecosystems
* Aquatic Data
* Aquatic Ecology (Aquat Ecol)
* Aquatic Geochemistry (Aquat Geochem)
* Aquatic Invasions (Aquat. Invasions)
* Aquatic Living Resources
* Aquatic Microbial Ecology
* Aquatic Procedia
* Aquatic Sciences (Aquat Sci)
* Aquatic Toxicology
* Aquitania (French)
* Arab Economic and Business Journal
* Arab Journal of Gastroenterology
* Arab Journal of Urology
* Arabian Journal for Science and Engineering (Arab J Sci Eng)
* Arabian Journal of Chemistry
* Arabian Journal of Geosciences (Arab J Geosci)
* Arabian Journal of Mathematics (Arab J Math)
* Arachne
* Arachnology
* Arboricultural Journal: The International Journal of Urban Forestry
* Archaeological and Anthropological Sciences (Archaeol Anthropol Sci)
* Archaeological Research in Asia
* Archaeometry
* Archeologia Classica (Italian)
* Archéologie médiévale (French)
* Archéologies et Sciences de l'Antiquité (French) (ArScAn)
* Architectural Engineering and Design Management
* Architectural Science Review
* Archiv für die civilistische Praxis (German) (AcP)
* Archiv für Geschichte der Philosophie (AGP)
* Archival Science (Arch Sci)
* Archive for History of Exact Sciences (Arch. Hist. Exact Sci.)
* Archive for Mathematical Logic (Arch. Math. Logic)
* Archive for Rational Mechanics and Analysis (Arch Rational Mech Anal)
* Archive of Applied Mechanics (Arch Appl Mech)
* Archives and Records
* Archives de pédiatrie
* Archives des Maladies du Coeur et des Vaisseaux - Pratique
* Archives des Maladies Professionnelles et de l'Environnement
* Archives of Agronomy and Soil Science
* Archives of Animal Nutrition
* Archives of Biochemistry and Biophysics
* Archives of Cardiovascular Diseases
* Archives of Cardiovascular Diseases Supplements
* Archives of Civil and Mechanical Engineering
* Archives of Computational Methods in Engineering (Arch Computat Methods Eng)
* Archives of Dermatological Research (Arch Dermatol Res)
* Archives of Disease in Childhood
* Archives of Environmental Contamination and Toxicology (Arch Environ Contam Toxicol)
* Archives of Facial Plastic Surgery
* Archives of General Psychiatry
* Archives of Gerontology and Geriatrics
* Archives of Gynecology and Obstetrics (Arch Gynecol Obstet)
* Archives of Internal Medicine
* Archives of Medical Research
* Archives of Microbiology (Arch Microbiol)
* Archives of Neurology
* Archives of Ophthalmology
* Archives of Oral Biology
* Archives of Orthopaedic and Trauma Surgery (Arch Orthop Trauma Surg)
* Archives of Osteoporosis (Arch Osteoporos)
* Archives of Otolaryngology - Head & Neck Surgery
* Archives of Pathology & Laboratory Medicine
* Archives of Pediatrics & Adolescent Medicine
* Archives of Pharmacal Research (Arch. Pharm. Res.)
* Archives of Physical Medicine and Rehabilitation
* Archives of Physiotherapy
* Archives Of Phytopathology And Plant Protection
* Archives of Psychiatric Nursing
* Archives of Public Health
* Archives of Scientific Psychology
* Archives of Sexual Behavior (Arch Sex Behav)
* Archives of Surgery
* Archives of Toxicology (Arch Toxicol)
* Archives of Virology (Arch Virol)
* Archives of Women's Mental Health (Arch Womens Ment Health)
* Archivos de Bronconeumología
* Archivos de Cardiología de México (Spanish)
* Archivos de la Sociedad Española de Oftalmología (Spanish) (OFTAL)
* Archivos de Medicina Interna (Spanish)
* Archivos de Psiquiatría (Spanish)
* Archivum Immunologiae et Therapiae Experimentalis (Arch. Immunol. Ther. Exp.)
* Archivum Latinitatis Medii Aevi (French) (ALMA)
* Arctic Science
* Arctic, Antarctic, and Alpine Research (AAAR)
* Argumentation
* Arhiv za higijenu rada i toksikologiju (Archives of Industrial Hygiene and Toxicology) (Arh Hig Rada Toksikol)
* arktos
* Arnold Mathematical Journal
* Arquivos Brasileiros de Cardiologia (Portuguese - Brazil)
* Arquivos Brasileiros de Endocrinologia & Metabologia
* Art History
* Arteriosclerosis, Thrombosis, and Vascular Biology
* Artery Research (ARTRES)
* Arthritis & Rheumatism
* Arthritis Care & Research
* Arthritis Research & Therapy
* Arthroplasty Today
* Arthropod-Plant Interactions
* Arthroscopy Techniques
* Arthroscopy: The Journal of Arthroscopic and Related Surgery
* Arthroskopie (German) (Arthroskopie)
* Artificial DNA: PNA & XNA
* Artificial Intelligence
* Artificial Intelligence and Law (Artif Intell Law)
* Artificial Intelligence In Medicine
* Artificial Intelligence Review (Artif Intell Rev)
* Artificial Life and Robotics (Artif Life Robotics)
* Arts
* Arts & Health
* Arts University Bournemouth (AUB)
* Arzneimitteltherapie
* ASAIO Journal (American Society for Artificial Internal Organs)
* ASCE-ASME Journal of Risk and Uncertainty in Engineering Systems, Part A: Civil Engineering
* Asia & the Pacific Policy Studies
* Asia Europe Journal (Asia Eur J)
* Asia Pacific Business Review
* Asia Pacific Education Review (Asia Pacific Educ. Rev.)
* Asia Pacific Family Medicine
* Asia Pacific Journal of Counselling and Psychotherapy
* Asia Pacific Journal of Education
* Asia Pacific Journal of Social Work and Development
* Asia Pacific Journal of Tourism Research
* Asia Pacific Journal on Computational Engineering
* Asia Pacific Management Review
* Asia-Pacific Financial Markets (Asia-Pac Financ Markets)
* Asia-Pacific Journal of Accounting & Economics
* Asia-Pacific Journal of Health, Sport and Physical Education
* Asia-Pacific Journal of Sports Medicine, Arthroscopy, Rehabilitation and Technology
* Asia-Pacific Science Education
* Asian American Journal of Psychology
* Asian Anthropology
* Asian Ethnicity
* Asian Geographer
* Asian Journal of Andrology
* Asian Journal of Anesthesiology
* Asian Journal of Business Ethics (Asian J Bus Ethics)
* Asian Journal of Criminology (Asian Criminology)
* Asian Journal of Gambling Issues and Public Health
* Asian Journal of German and European Studies
* Asian Journal of Health Sciences
* Asian Journal of Neurosurgery
* Asian Journal of Pharmaceutical Sciences
* Asian Journal of Psychiatry
* Asian Journal of Surgery
* Asian Journal of Urology
* Asian Pacific Journal of Reproduction (APJR)
* Asian Pacific Journal of Tropical Biomedicine (APJTB)
* Asian Pacific Journal of Tropical Disease (APJTD)
* Asian Pacific Journal of Tropical Medicine (APJTM)
* Asian Philosophy
* Asian Population Studies
* Asian Studies Review
* Asian-Pacific Journal of Second and Foreign Language Education
* ASSAY and Drug Development Technologies
* Assessing Writing
* Assessment & Evaluation in Higher Education
* Assessment in Education: Principles, Policy & Practice
* Associação Brasileira de Normas Técnicas (note, Portuguese - Brazil) (ABNT)
* Associação Brasileira de Normas Técnicas (Portuguese - Brazil) (ABNT)
* Association de Science Régionale de Langue Française (French) (ASRDLF)
* Association for Computational Linguistics - Conference Proceedings (ACL)
* Association for Computing Machinery (ACM)
* AStA Advances in Statistical Analysis (AStA Adv Stat Anal)
* AStA Wirtschafts- und Sozialstatistisches Archiv (AStA Wirtsch Sozialstat Arch)
* Asthma Research and Practice
* ASTRA Proceedings
* Astronomy and Computing
* Astroparticle Physics
* Astrophysics and Space Science (Astrophys Space Sci)
* Atención Familiar
* Atención Primaria (Spanish)
* Atherosclerosis
* Atherosclerosis (Supplements)
* Athletic Training & Sports Health Care
* Atlantic Economic Journal (Atl Econ J)
* Atlantic Studies
* Atlas of Genetics and Cytogenetics in Oncology and Haematology
* Atmosphere
* Atmosphere-Ocean
* Atmospheric Chemistry and Physics
* Atmospheric Chemistry and Physics Discussions
* Atmospheric Environment
* Atmospheric Measurement Techniques
* Atmospheric Measurement Techniques Discussions
* Atmospheric Pollution Research
* Atmospheric Research
* Atomic Data and Nuclear Data Tables
* Atoms
* Attachment & Human Development
* Audiology and Neurotology
* Audiology and Neurotology Extra
* Augenheilkunde up2date
* Augmented Human Research
* Aula Abierta
* Auris Nasus Larynx
* Ausonius Éditions (French)
* Austral Ecology
* Australasian Dispute Resolution Journal (ADRJ)
* Australasian Emergency Care
* Australasian Emergency Nursing Journal
* Australasian Journal of Dermatology
* Australasian Marketing Journal
* Australasian Physical & Engineering Sciences in Medicine (Australas Phys Eng Sci Med)
* Australasian Plant Disease Notes (Australasian Plant Dis. Notes)
* Australasian Plant Pathology (Australasian Plant Pathol.)
* Australian Academic & Research Libraries
* Australian Business Law Review (ABLR)
* Australian Critical Care (AUCC)
* Australian Family Physician
* Australian Feminist Studies
* Australian Geographer
* Australian GST Journal (AGSTJ)
* Australian Guide to Legal Citation (AGLC)
* Australian Historical Studies
* Australian Intellectual Property Journal (AIPJ)
* Australian Journal of Administrative Law (AJ Admin L)
* Australian Journal of Botany
* Australian Journal of Competition and Consumer Law (AJCCL)
* Australian Journal of Earth Sciences
* Australian Journal of Grape and Wine Research
* Australian Journal of International Affairs
* Australian Journal of Learning Difficulties
* Australian Journal of Primary Health
* Australian Journal of Rural Health
* Australian Journal of Zoology
* Australian Mammalogy
* Australian Orthoptic Journal
* Australian Planner
* Australian Systematic Botany
* Australian Tax Review (AT Rev)
* Australian Veterinary Journal (AVJ)
* Austrian Legal (German - Austria)
* Austrian Studies
* Autoimmunity Highlights (Autoimmun Highlights)
* Autoimmunity Reviews
* Automated Software Engineering (Autom Softw Eng)
* Automatica
* Automation in Construction
* Automotive and Engine Technology
* Autonomic Neuroscience: Basic and Clinical
* Autonomous Agents and Multi-Agent Systems (Auton Agent Multi-Agent Syst)
* Autonomous Robots (Auton Robot)
* Autophagy
* Avian Conservation and Ecology
* Avian Diseases
* Avian Pathology
* Avian Research
* Aviation Psychology and Applied Human Factors
* Aviation, Space, and Environmental Medicine (ASEM)
* Axiomathes
* Axioms
* Babes-Bolyai University - Faculty of Orthodox Theology (Romanian)
* Bacteriophage
* Balint-Journal
* Bandung: Journal of the Global South
* Bangladesh Journal of Child Health
* Basal Ganglia
* Basic and Applied Ecology
* Basic and Applied Pathology
* Basic and Clinical Andrology
* Basic Research in Cardiology (Basic Res Cardiol)
* Batteries
* BBA - Bioenergetics
* BBA - Biomembranes
* BBA - Gene Regulatory Mechanisms
* BBA - General Subjects
* BBA - Molecular and Cell Biology of Lipids
* BBA - Molecular Basis of Disease
* BBA - Molecular Cell Research
* BBA - Proteins and Proteomics
* BBA - Reviews on Cancer
* BBA Clinical
* Behavior Analysis in Practice
* Behavior Genetics (Behav Genet)
* Behavior Therapy
* Behavioral and Brain Functions
* Behavioral Ecology
* Behavioral Ecology and Sociobiology (Behav Ecol Sociobiol)
* Behavioral Neuroscience
* Behavioral Sciences
* Behavioral Sciences of Terrorism and Political Aggression
* Behaviour
* Behaviour Research and Therapy
* Behavioural Brain Research
* Behavioural Processes
* Beiträge zur Algebra und Geometrie / Contributions to Algebra and Geometry (Beitr Algebra Geom)
* Beiträge zur Popularmusikforschung (German)
* Bell Labs Technical Journal
* Beltz - Pädagogik (German)
* Beni-Suef University Journal of Basic and Applied Sciences
* Berliner Journal für Soziologie (German) (Berlin J Soziol)
* Best Practice & Research Clinical Anaesthesiology
* Best Practice & Research Clinical Endocrinology & Metabolism
* Best Practice & Research Clinical Gastroenterology
* Best Practice & Research Clinical Haematology
* Best Practice & Research Clinical Obstetrics & Gynaecology
* Best Practice & Research Clinical Rheumatology
* best practice onkologie (German) (best practice onkologie)
* Beverages
* Bibliotek for Læger (Danish)
* Bibliotheca Ephemeridum Theologicarum Lovaniensium (BETL)
* BibTeX generic citation style
* Big Data Analytics
* Big Data and Cognitive Computing
* Big Data Research
* Bijblijven (Dutch)
* Bioactive Carbohydrates and Dietary Fibre
* Bioactive Materials
* Bioanalysis
* Bioarchaeology International
* Bioarchaeology of the Near East (BNE)
* Bioarchitecture
* Biocatalysis and Agricultural Biotechnology
* Biochemical and Biophysical Research Communications
* Biochemical Engineering Journal
* Biochemical Genetics (Biochem Genet)
* Biochemical Journal
* Biochemical Pharmacology
* Biochemical Society Transactions (Biochem Soc Trans)
* Biochemical Systematics and Ecology
* Biochemistry
* Biochemistry and Biophysics Reports
* Biochemistry and Cell Biology
* Biochemistry and Molecular Biology Education (BAMBED)
* Biochimica et Biophysica Acta (BBA)
* Biochimie
* Biochimie Open
* Bioconjugate Chemistry (Bioconjugate Chem.)
* BioControl
* Biocontrol Science and Technology
* Biocybernetics and Biomedical Engineering
* BioData Mining
* Biodegradation
* Biodiversity
* Biodiversity and Conservation (Biodivers Conserv)
* BioDrugs
* Bioelectrochemistry
* Bioelectromagnetics
* BioEnergy Research (Bioenerg. Res.)
* Bioengineered
* Bioengineering
* BioEssays
* Bioethics
* BIOETHICS UPdate
* Biofabrication
* Biofouling
* Biofuels
* Biogeochemistry
* Biogeosciences
* Biogeosciences Discussions
* Biogerontology
* Bioinformatics
* Bioinspiration & Biomimetics
* Biologia
* Biological Agriculture & Horticulture
* Biological and Pharmaceutical Bulletin (Biol. Pharm. Bull.)
* Biological Conservation
* Biological Control
* Biological Cybernetics (Biol Cybern)
* Biological Invasions (Biol Invasions)
* Biological Journal of the Linnean Society (BJLS)
* Biological Procedures Online
* Biological Psychiatry
* Biological Psychology
* Biological Research
* Biological Reviews
* Biological Rhythm Research
* Biological Theory (Biol Theory)
* Biological Trace Element Research (Biol Trace Elem Res)
* Biologically Inspired Cognitive Architectures
* Biologicals
* Biologics in Therapy (Biol Ther)
* Biology
* Biology & Philosophy (Biol Philos)
* Biology and Fertility of Soils (Biol Fertil Soils)
* Biology Direct
* Biology Letters
* Biology of Blood and Marrow Transplantation
* Biology of Reproduction
* Biology of Sex Differences
* Biology Open
* Biomacromolecules
* Biomarker Research
* Biomarkers and Genomic Medicine
* Biomarkers in Medicine
* Biomass and Bioenergy
* Biomass Conversion and Biorefinery (Biomass Conv. Bioref.)
* Biomaterials
* Biomaterials Research
* Biomaterials Science
* Biomatter
* Biomechanics and Modeling in Mechanobiology (Biomech Model Mechanobiol)
* BioMed Central
* BioMed Research International (BRI)
* BioMedical Engineering OnLine
* Biomedical Imaging and Intervention Journal
* Biomedical Journal
* Biomedical Materials
* Biomedical Microdevices (Biomed Microdevices)
* Biomedical Optics Express
* Biomedical Reports
* Biomedical Reviews
* Biomedical Signal Processing and Control
* BioMedicine
* Biomedicine & Aging Pathology
* Biomedicine & Pharmacotherapy
* Biomedicine & Preventive Nutrition
* Biomedicines
* BioMetals (Biometals)
* Biometrics
* Biomicrofluidics
* Biomimetics
* Biomolecular Detection and Quantification
* Biomolecular NMR Assignments (Biomol NMR Assign)
* Biomolecules
* BioNanoScience (BioNanoSci.)
* Bioorganic & Medicinal Chemistry
* Bioorganic & Medicinal Chemistry Letters
* Bioorganic Chemistry
* Biophysical Chemistry
* Biophysical Economics and Resource Quality
* Biophysical Journal
* Biophysical Reviews (Biophys Rev)
* Biophysics Reports
* Biopolymers
* Bioprinting
* Bioprocess and Biosystems Engineering (Bioprocess Biosyst Eng)
* BioPsychoSocial Medicine
* Bioresource Technology
* Bioresource Technology Reports
* BioResources
* Bioresources and Bioprocessing
* Biosemiotics
* Biosensors
* Biosensors and Bioelectronics
* BioSocieties
* Biosurface and Biotribology
* BioSystems
* Biosystems Engineering
* Biota Neotropica (Biota Neotrop.)
* BioTechniques
* Biotechnology Advances
* Biotechnology and Bioengineering
* Biotechnology and Genetic Engineering Reviews
* Biotechnology for Biofuels
* Biotechnology Letters (Biotechnol Lett)
* Biotechnology Progress
* Biotechnology Reports
* Biotechnology Research and Innovation
* Biotribology
* Biotropica
* BIT Numerical Mathematics (Bit Numer Math)
* Biuletyn Polskiego Towarzystwa Językoznawczego (Polish) (Biuletyn PTJ)
* BJOG
* Blood
* Blood Cancer Journal
* Blood Cells, Molecules and Diseases
* Blood Purification
* Blood Reviews
* Bluebook Inline
* Bluebook Law Review
* Bluebook Law Review (2)
* BMC Anesthesiology
* BMC Biochemistry
* BMC Bioinformatics
* BMC Biology
* BMC Biophysics
* BMC Biotechnology
* BMC Cancer
* BMC Cardiovascular Disorders
* BMC Cell Biology
* BMC Clinical Pathology
* BMC Complementary and Alternative Medicine
* BMC Dermatology
* BMC Developmental Biology
* BMC Ear, Nose and Throat Disorders
* BMC Ecology
* BMC Emergency Medicine
* BMC Endocrine Disorders
* BMC Evolutionary Biology
* BMC Family Practice
* BMC Gastroenterology
* BMC Genetics
* BMC Genomics
* BMC Geriatrics
* BMC Health Services Research
* BMC Hematology
* BMC Immunology
* BMC Infectious Diseases
* BMC International Health and Human Rights
* BMC Medical Education
* BMC Medical Ethics
* BMC Medical Genetics
* BMC Medical Genomics
* BMC Medical Imaging
* BMC Medical Informatics and Decision Making
* BMC Medical Research Methodology
* BMC Medicine
* BMC Microbiology
* BMC Molecular Biology
* BMC Musculoskeletal Disorders
* BMC Nephrology
* BMC Neurology
* BMC Neuroscience
* BMC Nursing
* BMC Nutrition
* BMC Obesity
* BMC Ophthalmology
* BMC Oral Health
* BMC Palliative Care
* BMC Pediatrics
* BMC Pharmacology and Toxicology
* BMC Physiology
* BMC Plant Biology
* BMC Pregnancy and Childbirth
* BMC Psychiatry
* BMC Psychology
* BMC Public Health
* BMC Pulmonary Medicine
* BMC Research Notes
* BMC Sports Science, Medicine and Rehabilitation
* BMC Structural Biology
* BMC Surgery
* BMC Systems Biology
* BMC Urology
* BMC Veterinary Research
* BMC Women's Health
* BMC Zoology (BMC Zool)
* BMJ
* BMJ Case Reports
* BMJ Open
* BMJ Open Diabetes Research & Care
* BMJ Open Respiratory Research
* BMJ Quality & Safety
* BMJ Quality Improvement Reports
* BMJ Supportive & Palliative Care
* Body & Society
* Body Image
* Body, Movement and Dance in Psychotherapy
* Boletín de la Sociedad Española de Cerámica y Vidrio
* Boletín de la Sociedad Matemática Mexicana
* Boletín de Pediatría (Spanish)
* Boletín Médico del Hospital Infantil de México (Spanish)
* Bollettino dell'Unione Matematica Italiana
* Bone
* Bone & Joint Research
* Bone Marrow Transplantation
* Bone Reports
* Borderline Personality Disorder and Emotion Dysregulation
* Boreal Environment Research
* Borsa Istanbul Review
* Botanical Studies
* Botany
* Boundary Value Problems
* Boundary-Layer Meteorology (Boundary-Layer Meteorol)
* Bournemouth University - Harvard
* Brachytherapy
* Brain
* Brain and Cognition
* Brain and Development
* Brain and Language
* Brain Behavior and Immunity
* Brain Imaging and Behavior
* Brain Informatics
* Brain Research
* Brain Research Bulletin
* Brain Sciences
* Brain Stimulation
* Brain Structure and Function (Brain Struct Funct)
* Brain Topography (Brain Topogr)
* Brain Tumor Pathology (Brain Tumor Pathol)
* Brain, Behavior and Evolution (BBE)
* Brazilian Journal of Botany
* Brazilian Journal of Infectious Diseases (BJID)
* Brazilian Journal of Microbiology
* Brazilian Journal of Physical Therapy
* Brazilian Journal of Physics (Braz J Phys)
* Brazilian Journal of Science and Technology
* Breast Cancer
* Breast Cancer Management
* Breast Cancer Research
* Breast Cancer Research and Treatment (Breast Cancer Res Treat)
* Breast Care
* BrewingScience
* Briefings in Bioinformatics
* British Dental Journal
* British Journal of Anaesthesia (BJA)
* British Journal of Biomedical Science
* British Journal of Cancer (BJC)
* British Journal of Clinical Psychology
* British Journal of Dermatology
* British Journal of Developmental Psychology
* British Journal of Educational Psychology
* British Journal of Guidance & Counselling
* British Journal of Haematology
* British Journal of Health Psychology
* British Journal of Industrial Relations (BJIR)
* British Journal of Mathematical and Statistical Psychology
* British Journal of Ophthalmology
* British Journal of Pain
* British Journal of Pharmacology (BJP)
* British Journal of Political Science (BJPS)
* British Journal of Psychology
* British Journal of Religious Education
* British Journal of Social Psychology
* British Journal of Sociology of Education
* British Journal of Sports Medicine
* British Journal of Surgery
* British Medical Bulletin
* BRQ Business Research Quarterly
* Budownictwo i Architektura (English)
* Budownictwo i Architektura (Polish)
* Building and Construction Law Journal (BCL)
* Building and Environment
* Building Research & Information
* Building Structure (Chinese)
* Buildings
* Bulletin de Correspondance Hellénique (French)
* Bulletin de la Société Entomologique de France (bsef)
* Bulletin de la Société préhistorique française (French) (BSPF)
* Bulletin des sciences mathématiques
* Bulletin du Cancer
* Bulletin of Earthquake Engineering (Bull Earthquake Eng)
* Bulletin of Engineering Geology and the Environment (Bull Eng Geol Environ)
* Bulletin of Environmental Contamination and Toxicology (Bull Environ Contam Toxicol)
* Bulletin of Faculty of Pharmacy, Cairo University
* Bulletin of Marine Science
* Bulletin of Mathematical Biology (Bull Math Biol)
* Bulletin of Mathematical Sciences (Bull. Math. Sci.)
* Bulletin of the American Meteorological Society
* Bulletin of the American Schools of Oriental Research (BASOR)
* Bulletin of the Chemical Society of Japan (Bull. Chem. Soc. Jpn.)
* Bulletin of the Malaysian Mathematical Sciences Society
* Bulletin of the World Health Organization
* Bulletin of Volcanology (Bull Volcanol)
* Bundesgesundheitsblatt - Gesundheitsforschung - Gesundheitsschutz (German) (Bundesgesundheitsblatt Gesundheitsforschung Gesundheitsschutz)
* Burnout Research
* Burns
* Burns & Trauma
* Burns Open
* Business & Information Systems Engineering (Bus Inf Syst Eng)
* Business Ethics: A European Review
* Business History
* Business Horizons
* Business Research
* Business Trends (Trendy v podnikání)
* BYZANTINA SYMMEIKTA
* Byzantine and Modern Greek Studies (BMGS)
* C
* CAAI Transactions on Intelligence Technology
* Cahiers d'ethnomusicologie (French)
* Cahiers de la puéricultrice
* Cahiers de Nutrition et de Diététique
* Cahiers du Centre Gustave-Glotz (French)
* Calcified Tissue International (Calcif Tissue Int)
* Calcolo
* Calculus of Variations and Partial Differential Equations (Calc. Var.)
* California Agriculture
* Calphad
* Cambridge Archaeological Journal
* Cambridge Journal of Economics (CJE)
* Cambridge Journal of Education
* Cambridge University Press - Law (note) (CUP)
* Cambridge University Press (author-date)
* Cambridge University Press (note) (CUP)
* Cambridge University Press (numeric)
* Campus adventiste du Salève - Faculté adventiste de théologie (French) (FAT France)
* Canadian Association of Radiologists Journal
* Canadian Family Physician
* Canadian Geotechnical Journal
* Canadian Guide to Uniform Legal Citation 7th edition (McGill Guide)
* Canadian Journal of African Studies/ La Revue canadienne des études africaines
* Canadian Journal of Anesthesia/Journal canadien d'anesthésie (Can J Anesth/J Can Anesth)
* Canadian Journal of Animal Science
* Canadian Journal of Behavioural Science
* Canadian Journal of Cardiology
* Canadian Journal of Chemistry
* Canadian Journal of Civil Engineering
* Canadian Journal of Development Studies / Revue canadienne d'études du développement
* Canadian Journal of Dietetic Practice and Research
* Canadian Journal of Earth Sciences
* Canadian Journal of Economics
* Canadian Journal of Electrical and Computer Engineering
* Canadian Journal of Experimental Psychology
* Canadian Journal of Fisheries and Aquatic Sciences
* Canadian Journal of Forest Research
* Canadian Journal of Kidney Health and Disease
* Canadian Journal of Microbiology
* Canadian Journal of Occupational Therapy
* Canadian Journal of Ophthalmology/Journal canadien d'ophtalmologie
* Canadian Journal of Philosophy
* Canadian Journal of Physics (Can J Phys)
* Canadian Journal of Physiology and Pharmacology
* Canadian Journal of Plant Science
* Canadian Journal of Public Health
* Canadian Journal of Soil Science
* Canadian Journal of Surgery
* Canadian Journal of Veterinary Research
* Canadian Journal of Zoology
* Canadian Pharmacists Journal
* Canadian Psychology
* Canadian Public Policy (CPP)
* Cancer / Radiothérapie
* Cancer & Metabolism
* Cancer and Metastasis Reviews (Cancer Metastasis Rev)
* Cancer Biology & Medicine
* Cancer Biology & Therapy
* Cancer Causes & Control (Cancer Causes Control)
* Cancer Cell
* Cancer Cell International
* Cancer Chemotherapy and Pharmacology (Cancer Chemother Pharmacol)
* Cancer Discovery
* Cancer Epidemiology
* Cancer Epidemiology, Biomarkers & Prevention
* Cancer Gene Therapy
* Cancer Genetics
* Cancer Imaging
* Cancer Immunology Research
* Cancer Immunology, Immunotherapy (Cancer Immunol Immunother)
* Cancer Letters
* Cancer Microenvironment
* Cancer Nanotechnology (Cancer Nano)
* Cancer Prevention Research
* Cancer Research
* Cancer Translational Medicine (CTN)
* Cancer Treatment and Research Communications
* Cancer Treatment Reviews
* Cancers
* Canine Genetics and Epidemiology
* Cape Peninsula University of Technology - Harvard (CPUT Harvard)
* Capitalism Nature Socialism
* Carbohydrate Polymers
* Carbohydrate Research
* Carbon
* Carbon Balance and Management
* Carbon Management
* Carbon Resources Conversion
* Carbonates and Evaporites (Carbonates Evaporites)
* Carcinogenesis
* Cardiff University - Harvard
* Cardiff University - Vancouver
* Cardiff University BIOSI - Harvard
* Cardio-Oncology
* Cardiocore (Spanish) (CARCOR)
* Cardiology
* Cardiology and Therapy (Cardiol Ther)
* Cardiorenal Medicine
* CardioVascular and Interventional Radiology (Cardiovasc Intervent Radiol)
* Cardiovascular Diabetology
* Cardiovascular Drugs and Therapy (Cardiovasc Drugs Ther)
* Cardiovascular Intervention and Therapeutics (Cardiovasc Interv and Ther)
* Cardiovascular Pathology
* Cardiovascular Research
* Cardiovascular Revascularization Medicine
* Cardiovascular Toxicology (Cardiovasc Toxicol)
* Cardiovascular Ultrasound
* Caries Research
* Cartography and Geographic Information Science
* Case Reports in Dermatology
* Case Reports in Gastroenterology
* Case Reports in Nephrology and Urology
* Case Reports in Neurology
* Case Reports in Oncology
* Case Reports in Ophthalmology
* Case Reports in Women's Health
* Case Studies in Construction Materials
* Case Studies in Engineering Failure Analysis
* Case Studies in Fire Safety
* Case Studies in Mechanical Systems and Signal Processing
* Case Studies in Nondestructive Testing and Evaluation
* Case Studies in Structural Engineering
* Case Studies in Thermal Engineering
* Case Studies on Transport Policy
* Catalysis Communications
* Catalysis Letters (Catal Lett)
* Catalysis Science & Technology
* Catalysis Surveys from Asia (Catal Surv Asia)
* Catalysis Today
* Catalysts
* Catena
* Cath Lab Digest
* Catholic Biblical Association (full note)
* Catholic Biblical Quarterly
* CBE - Life Sciences Education (LSE)
* CEAS Aeronautical Journal (CEAS Aeronaut J)
* CEAS Space Journal (CEAS Space J)
* Celestial Mechanics and Dynamical Astronomy (Celest Mech Dyn Astr)
* Cell
* Cell & Bioscience
* Cell Adhesion & Migration
* Cell and Tissue Banking (Cell Tissue Bank)
* Cell and Tissue Research (Cell Tissue Res)
* Cell Biochemistry and Biophysics (Cell Biochem Biophys)
* Cell Biology and Toxicology (Cell Biol Toxicol)
* Cell Calcium
* Cell Chemical Biology
* Cell Communication and Signaling
* Cell Cycle
* Cell Death & Differentiation
* Cell Death and Disease
* Cell Division
* Cell Host & Microbe
* Cell journals (numeric, superscript)
* Cell journals (numeric)
* Cell Metabolism
* Cell Regeneration
* Cell Reports
* Cell Research
* Cell Stem Cell
* Cell Stress
* Cell Stress and Chaperones
* Cell Structure and Function (Cell Struct Funct)
* Cell Systems
* Cell Transplantation
* Cells
* Cells Tissues Organs
* Cellular and Molecular Bioengineering
* Cellular and Molecular Gastroenterology and Hepatology
* Cellular and Molecular Immunology
* Cellular and Molecular Life Sciences (Cell. Mol. Life Sci.)
* Cellular and Molecular Neurobiology (Cell Mol Neurobiol)
* Cellular Immunology
* Cellular Logistics
* Cellular Microbiology
* Cellular Oncology (Cell Oncol.)
* Cellular Physiology and Biochemistry
* Cellular Reprogramming
* Cellular Signalling
* Cellulose
* Cement and Concrete Composites
* Cement and Concrete Research
* CEN Case Reports (CEN Case Rep)
* Centaurus
* Central Asian Survey
* Central Bank Review
* Central European Journal of Operations Research (Cent Eur J Oper Res)
* Central European Journal of Public Health (CEJPH)
* Central European Journal of Urology
* Centre de recherche sur les civilisations de l'Asie orientale (French) (CRCAO)
* Cephalalgia
* Ceramics International
* Cerebellum & Ataxias
* Cerebral Cortex
* Cerebrovascular Diseases
* Cerebrovascular Diseases Extra
* Cerevisia
* Česká a slovenská neurologie a neurochirurgie
* Česká zemědělská univerzita v Praze - Fakulta agrobiologie, potravinových a přírodních zdrojů (FAPPZ ČZU)
* Challenges
* Changer d'époque (French)
* Changing English
* Channels
* Chaos
* Chaos, Solitons and Fractals: the interdisciplinary journal of Nonlinear Science, and Nonequilibrium and Complex Phenomena
* Chem
* ChemEngineering
* Chemical and Biological Technologies in Agriculture
* Chemical and Pharmaceutical Bulletin (Chem. Pharm. Bull.)
* Chemical Biology & Drug Design
* Chemical Biology Letters
* Chemical Communications
* Chemical Data Collections
* Chemical Engineering and Processing - Process Intensification
* Chemical Engineering Journal
* Chemical Engineering Research and Design
* Chemical Engineering Science
* Chemical Geology
* Chemical Physics
* Chemical Physics Letters
* Chemical Research in Toxicology (Chem. Res. Toxicol.)
* Chemical Reviews (Chem. Rev.)
* Chemical Science
* Chemical Senses
* Chemical Society Reviews
* Chemico-Biological Interactions
* Chemie der Erde
* Chemie Ingenieur Technik
* Chemistry and Ecology
* Chemistry and Physics of Lipids
* Chemistry Central Journal
* Chemistry Education Research and Practice (CERP)
* Chemistry Letters (Chem. Lett.)
* Chemistry of Materials (Chem. Mater.)
* Chemistry World
* Chemoecology
* Chemometrics and Intelligent Laboratory Systems
* Chemosensors
* Chemosensory Perception (Chem. Percept.)
* Chemosphere
* Chemotherapy
* ChemTexts
* Chest
* Chicago Manual of Style 16th edition (author-date, Basque)
* Chicago Manual of Style 16th edition (author-date, French)
* Chicago Manual of Style 16th edition (author-date, German)
* Chicago Manual of Style 16th edition (author-date)
* Chicago Manual of Style 16th edition (figures and illustrations) (chicago-figures)
* Chicago Manual of Style 16th edition (full note, French)
* Chicago Manual of Style 16th edition (full note)
* Chicago Manual of Style 16th edition (note)
* Chicago Manual of Style 17th edition (author-date)
* Chicago Manual of Style 17th edition (full note, with Ibid.)
* Chicago Manual of Style 17th edition (full note)
* Chicago Manual of Style 17th edition (library list)
* Chicago Manual of Style 17th edition (note, annotated bibliography)
* Chicago Manual of Style 17th edition (note, with Ibid.)
* Chicago Manual of Style 17th edition (note)
* Child & Youth Care Forum (Child Youth Care Forum)
* Child Abuse & Neglect
* Child and Adolescent Psychiatry and Mental Health
* Child and Adolescent Social Work Journal (Child Adolesc Soc Work J)
* Child Indicators Research (Child Ind Res)
* Child Neuropsychology
* Child Psychiatry & Human Development (Child Psychiatry Hum Dev)
* Child's Nervous System (Childs Nerv Syst)
* Children
* Children and Youth Services Review
* Children's Geographies
* Chimerism
* CHIMIA
* China Communications
* China Economic Journal
* China Economic Review
* China Finance and Economic Review
* China Journal of Accounting Research
* China Journal of Accounting Studies
* China Journal of Economic Research
* China Journal of Social Work
* China-EU Law Journal (China-EU Law J)
* Chinese Chemical Letters
* Chinese Herbal Medicines
* Chinese Journal of Aeronautics (CJA)
* Chinese Journal of Cancer
* Chinese Journal of Chemical Engineering
* Chinese Journal of Communication
* Chinese Journal of Physics
* Chinese Journal of Population Resources and Environment
* Chinese Journal of Traumatology
* Chinese Medical Journal
* Chinese Medicine
* Chinese Neurosurgical Journal
* Chinese Nursing Research
* Chinese Physics B
* Chinese Physics C
* Chinese Physics Letters
* Chinese Political Science Review
* Chinese Std GB/T 7714-1987 (numeric, Chinese)
* Chinese Std GB/T 7714-2005 (author-date, Chinese)
* Chinese Std GB/T 7714-2005 (numeric, Chinese)
* Chiropractic & Manual Therapies
* Chiropractic Journal of Australia
* Chromatographia
* Chromatography
* Chromosoma
* Chromosome Research (Chromosome Res)
* Chronic Diseases and Diseases in Canada
* Chronic Diseases and Translational Medicine
* Chroniques des activités archéologiques de l'Ecole française de Rome (French)
* Cilia
* Circuits, Systems, and Signal Processing (Circuits Syst Signal Process)
* Circulation
* Circulation Journal (Circ.J.)
* Cirugia Cardiovascular (Spanish) (CIRCV)
* Cirugía Española (Spanish)
* Cirugía y Cirujanos
* Cirujano General
* Cite Them Right 10th edition - Harvard
* Cities
* Citizen Science: Theory and Practice
* Citizenship Studies
* City
* City & Community
* City, Culture and Society
* City, Territory and Architecture
* Civil Engineering and Environmental Systems
* Civiltà Italiana (Italian)
* Cladistics
* CLARA Architecture/Recherche (French)
* Classical and Quantum Gravity
* Classroom Discourse
* Clay Minerals
* Clays and Clay Minerals
* Clean Technologies and Environmental Policy (Clean Techn Environ Policy)
* Climacteric
* Climate
* Climate Change Economics (CCE)
* Climate Change Responses
* Climate Dynamics (Clim Dyn)
* Climate of the Past
* Climate of the Past Discussions
* Climate Policy
* Climate Research
* Climate Risk Management
* Climate Services
* Climatic Change
* Clinica Chimica Acta
* Clínica e Investigación en Arteriosclerosis (Spanish) (ARTERI)
* Clínica y Salud
* Clinical & Experimental Metastasis (Clin Exp Metastasis)
* Clinical & Experimental Ophthalmology
* Clinical & Translational Immunology
* Clinical Anatomy
* Clinical and Experimental Medicine (Clin Exp Med)
* Clinical and Experimental Nephrology (Clin Exp Nephrol)
* Clinical and Experimental Optometry
* Clinical and Experimental Pharmacology and Physiology
* Clinical and Investigative Medicine
* Clinical and Molecular Allergy
* Clinical and Translational Allergy
* Clinical and Translational Gastroenterology
* Clinical and Translational Imaging
* Clinical and Translational Medicine
* Clinical and Translational Oncology (Clin Transl Oncol)
* Clinical and Translational Radiation Oncology
* Clinical and Vaccine Immunology (CVI)
* Clinical Autonomic Research (Clin Auton Res)
* Clinical Biochemistry
* Clinical Biomechanics
* Clinical Breast Cancer
* Clinical Cancer Research
* Clinical Chemistry
* Clinical Child and Family Psychology Review (Clin Child Fam Psychol Rev)
* Clinical Colorectal Cancer
* Clinical Diabetes and Endocrinology
* Clinical Drug Investigation (Clin Drug Investig)
* Clinical Dysmorphology
* Clinical eHealth
* Clinical Epidemiology and Global Health
* Clinical Epigenetics (Clin Epigenetics)
* Clinical Gastroenterology and Hepatology (CGH)
* Clinical Genitourinary Cancer
* Clinical Hemorheology and Microcirculation
* Clinical Hypertension
* Clinical Imaging
* Clinical Immunology
* Clinical Infectious Diseases
* Clinical Investigation
* Clinical Journal of Gastroenterology (Clin J Gastroenterol)
* Clinical Journal of Sport Medicine (CJSM)
* Clinical Laboratory
* Clinical Lipidology
* Clinical Lung Cancer
* Clinical Lymphoma, Myeloma and Leukemia
* Clinical Mass Spectrometry
* Clinical Medicine
* Clinical Microbiology and Infection
* Clinical Microbiology Newsletter
* Clinical Microbiology Reviews (CMR)
* Clinical Neurology and Neurosurgery
* Clinical Neurophysiology
* Clinical Neurophysiology Practice
* Clinical Neuroradiology (Clin Neuroradiol)
* Clinical Nuclear Medicine
* Clinical Nutrition
* Clinical Nutrition ESPEN
* Clinical Nutrition Experimental
* Clinical Nutrition Supplements
* Clinical Oncology
* Clinical Oral Implants Research (COIR)
* Clinical Oral Investigations (Clin Oral Invest)
* Clinical Orthopaedics and Related Research
* Clinical Otolaryngology
* Clinical Ovarian and Other Gynecologic Cancer
* Clinical Pediatrics
* Clinical Pharmacokinetics (Clin Pharmacokinet)
* Clinical Pharmacology & Therapeutics
* Clinical Phytoscience
* Clinical Plasma Medicine
* Clinical Practice
* Clinical Practice in Pediatric Psychology
* Clinical Proteomics
* Clinical Psychology Review
* Clinical Queries: Nephrology
* Clinical Radiology
* Clinical Research in Cardiology (Clin Res Cardiol)
* Clinical Research in Cardiology Supplements (Clin Res Cardiol Suppl)
* Clinical Reviews in Allergy & Immunology (Clinic Rev Allerg Immunol)
* Clinical Reviews in Bone and Mineral Metabolism (Clinic Rev Bone Miner Metab)
* Clinical Rheumatology (Clin Rheumatol)
* Clinical Sarcoma Research
* Clinical Simulation in Nursing
* Clinical Skin Cancer
* Clinical Social Work Journal (Clin Soc Work J)
* Clinical Spine Surgery
* Clinical Therapeutics
* Clinical Trials and Regulatory Science in Cardiology
* Clinician's Research Digest
* Clinics and Research in Hepatology and Gastroenterology
* Clinics in Dermatology
* Clio Medica
* Cliometrica
* Cluster Computing (Cluster Comput)
* CMAJ (Canadian Medical Association Journal) (CMAJ)
* CNS & Neurological Disorders - Drug Targets
* CNS Drugs
* CNS Oncology
* Coaching | Theorie & Praxis (German)
* Coaching: An International Journal of Theory, Research and Practice
* Coastal Engineering
* Coatings
* CoDesign
* Coevolution
* Cognition
* Cognition & Emotion
* Cognition, Technology & Work (Cogn Tech Work)
* Cognitive and Behavioral Practice
* Cognitive Computation (Cogn Comput)
* Cognitive Development
* Cognitive Neurodynamics (Cogn Neurodyn)
* Cognitive Neuropsychiatry
* Cognitive Neuropsychology
* Cognitive Neuroscience
* Cognitive Processing (Cogn Process)
* Cognitive Psychology
* Cognitive Research
* Cognitive Systems Research
* Cognitive Therapy and Research (Cogn Ther Res)
* Cold Regions Science and Technology
* Cold Spring Harbor Laboratory Press
* Collectanea Mathematica (Collect. Math.)
* Collection de l'Ecole française de Rome (full note, French)
* Collection de l'Ecole française de Rome (note, French)
* Collection du Centre Jean-Bérard (French)
* Collections électroniques de l'INHA (author-date, French)
* Collections électroniques de l'INHA (full note, French)
* Collège Montmorency (note, French - Canada)
* Collegian
* Colloid and Interface Science Communications
* Colloid and Polymer Science (Colloid Polym Sci)
* Colloids and Interfaces
* Colloids and Surfaces A: Physicochemical and Engineering Aspects
* Colloids and Surfaces B: Biointerfaces
* Colombia Médica
* Colombian Journal of Anesthesiology (RCAE)
* coloproctology (German) (coloproctology)
* Colorado State University - School of Biomedical Engineering
* Colorectal Cancer
* Combinatorial Chemistry - an Online journal
* Combinatorial Chemistry & High Throughput Screening
* Comisión Económica para América Latina y el Caribe (Spanish) (CEPAL)
* Communication Education
* Communication et Langages
* Communication Teacher
* Communications in Mathematical Physics (Commun. Math. Phys.)
* Communications in Mathematics and Statistics
* Communications in Nonlinear Science and Numerical Simulation
* Communications in Theoretical Physics
* Communicative & Integrative Biology
* Communist and Post-Communist Studies
* Community Dentistry and Oral Epidemiology
* Community Mental Health Journal (Community Ment Health J)
* Community, Work & Family
* Company and Securities Law Journal (C&SLJ)
* Comparative Biochemistry and Physiology - Part D: Genomics and Proteomics
* Comparative Biochemistry and Physiology, Part A
* Comparative Biochemistry and Physiology, Part B
* Comparative Biochemistry and Physiology, Part C
* Comparative Clinical Pathology (Comp Clin Pathol)
* Comparative Education
* Comparative Immunology, Microbiology and Infectious Diseases
* Comparative Medicine
* Comparative Migration Studies
* Comparative Oriental Manuscript Studies Bulletin (COMSt Bulletin)
* Comparative Politics
* Comparative Population Studies
* Compare: A Journal of Comparative and International Education
* Complementary Therapies in Clinical Practice
* Complementary Therapies in Medicine
* Complex & Intelligent Systems
* Complex Adaptive Systems Modeling
* Complex Analysis and its Synergies
* Complex Analysis and Operator Theory (Complex Anal. Oper. Theory)
* Complex Variables and Elliptic Equations
* Composite Interfaces
* Composite Structures
* Composites Communications
* Composites Part A
* Composites Part B
* Composites Science and Technology
* Comprehensive Psychiatry
* Comptes rendus - Biologies
* Comptes rendus - Geoscience
* Comptes rendus - Mathématique
* Comptes rendus - Mécanique
* Comptes rendus - Palevol
* Comptes rendus - Physique
* Computation
* Computational and Applied Mathematics (Comp. Appl. Math.)
* Computational and Mathematical Organization Theory (Comput Math Organ Theory)
* Computational and Structural Biotechnology Journal
* Computational and Theoretical Chemistry
* Computational Astrophysics and Cosmology
* Computational Biology and Chemistry
* Computational Cognitive Science
* Computational Condensed Matter
* Computational Economics (Comput Econ)
* Computational Geometry: Theory and Applications
* Computational Geosciences (Comput Geosci)
* Computational Management Science (Comput Manag Sci)
* Computational Materials Science
* Computational Mechanics (Comput Mech)
* Computational Methods and Function Theory (Comput. Methods Funct. Theory)
* Computational Optimization and Applications (Comput Optim Appl)
* Computational Particle Mechanics
* Computational Science & Discovery
* Computational Social Networks
* Computational Statistics (Comput Stat)
* Computational Statistics and Data Analysis
* Computational Toxicology
* Computer
* Computer Aided Geometric Design
* Computer Architecture Letters
* Computer Assisted Language Learning
* Computer Communications
* Computer Languages, Systems & Structures
* Computer Law & Security Review: The International Journal of Technology Law and Practice
* Computer Methods and Programs in Biomedicine
* Computer Methods in Applied Mechanics and Engineering
* Computer Methods in Biomechanics and Biomedical Engineering
* Computer Methods in Biomechanics and Biomedical Engineering: Imaging & Visualization
* Computer Networks
* Computer Physics Communications
* Computer Science - Research and Development (Comput Sci Res Dev)
* Computer Science Education
* Computer Science Review
* Computer Speech & Language
* Computer Standards & Interfaces
* Computer und Recht (German) (CR)
* Computer Vision and Image Understanding
* Computer-Aided Design
* Computerized Medical Imaging and Graphics
* Computers
* Computers & Education
* Computers & Graphics
* Computers & Industrial Engineering
* Computers & Security
* Computers and Chemical Engineering
* Computers and Composition
* Computers and Electrical Engineering
* Computers and Electronics in Agriculture
* Computers and Fluids
* Computers and Geosciences
* Computers and Geotechnics
* Computers and Mathematics with Applications
* Computers and Operations Research
* Computers and Structures
* Computers in Biology and Medicine
* Computers in Entertainment (CIE)
* Computers in Human Behavior
* Computers in Industry
* Computers, Environment and Urban Systems
* Computing
* Computing and Visualization in Science (Comput. Visual Sci.)
* Computing in Science & Engineering
* Concepts in Magnetic Resonance Part A
* Condensed Matter
* Conflict and Health
* Connection Science
* Consciousness and Cognition
* Conservation Biology
* Conservation Genetics (Conserv Genet)
* Conservation Genetics Resources (Conservation Genet Resour)
* Conservation Letters
* Conservation Physiology
* Constellations
* Constitutional Political Economy (Const Polit Econ)
* Constraints
* Construction and Building Materials
* Constructive Approximation (Constr Approx)
* Consulting Psychology Journal: Practice and Research
* Consumption Markets & Culture
* Contact Lens and Anterior Eye
* Contaduría y Administración
* Contemporary Arab Affairs
* Contemporary British History
* Contemporary Buddhism
* Contemporary Clinical Trials
* Contemporary Clinical Trials Communications
* Contemporary Educational Psychology
* Contemporary Family Therapy (Contemp Fam Ther)
* Contemporary Islam (Cont Islam)
* Contemporary Italian Politics
* Contemporary Jewry (Cont Jewry)
* Contemporary Justice Review
* Contemporary School Psychology
* Contemporary Social Science
* Contemporary Sociology
* Contemporary South Asia
* Continental Philosophy Review (Cont Philos Rev)
* Continental Shelf Research
* Continuum
* Continuum Mechanics and Thermodynamics (Continuum Mech. Thermodyn.)
* Contraception
* Contraception and Reproductive Medicine
* Contributions to Mineralogy and Petrology (Contrib Mineral Petrol)
* Control & Automation
* Control Engineering Practice
* Coordination Chemistry Reviews
* COPD Research and Practice
* Copeia
* Copernicus Publications
* Cor et Vasa
* Coral Reefs
* Cornea
* Coronary Artery Disease
* Corrosion
* Corrosion Science
* Cortex
* Cosmetics
* Cost Effectiveness and Resource Allocation
* Council of Science Editors, Citation-Name (numeric, sorted alphabetically) (CSE C-N)
* Council of Science Editors, Citation-Sequence (numeric) (CSE C-S)
* Council of Science Editors, Name-Year (author-date) (CSE N-Y)
* Counselling and Psychotherapy Research
* Counselling Psychology Quarterly
* Couple and Family Psychology: Research and Practice
* Coventry University - Harvard (CU Harvard)
* CPT: Pharmacometrics & Systems Pharmacology
* Cranfield University - Harvard (Cranfield Harvard)
* Cranfield University (numeric)
* Creativity and Innovation Management
* Cretaceous Research
* Crime Science
* Crime, Law and Social Change (Crime Law Soc Change)
* Criminal Justice Studies
* Criminal Law Journal (Crim LJ)
* Crisis: The Journal of Crisis Intervention and Suicide Prevention
* Critical African Studies
* Critical Care
* Critical Care Medicine
* Critical Criminology (Crit Crim)
* Critical Discourse Studies
* Critical Perspectives on Accounting
* Critical Public Health
* Critical Reviews in Oncology / Hematology
* Critical Reviews in Plant Sciences
* Critical Studies in Media Communication
* Critical Studies on Security
* Critical Studies on Terrorism
* Critical Ultrasound Journal
* Crop & Pasture Science
* Crop Breeding and Applied Biotechnology (CBAB)
* Crop Protection
* Crop Science
* Cryobiology
* Cryogenics
* Cryptography
* Cryptography and Communications (Cryptogr. Commun.)
* Crystal Growth & Design (Cryst. Growth Des.)
* Crystallography Reviews
* Crystals
* CrystEngComm
* CSI Transactions on ICT (CSIT)
* Cuadernos de Economía
* Cuadernos de Economía y Dirección de la Empresa
* Cuadernos de Filología Clásica. Estudios Griegos e Indoeuropeos (autor-año, Spanish)
* Cultivos Tropicales (Spanish) (CulTrop)
* Cultural Diversity and Ethnic Minority Psychology
* cultural geographies (cg)
* Cultural Studies of Science Education (CSSE)
* Cultural Trends
* Culture and Brain (Cult. Brain)
* Culture and Organization
* Culture and Religion
* Culture, Health & Sexuality
* Culture, Medicine, and Psychiatry
* Current Addiction Reports
* Current Allergy and Asthma Reports (Curr Allergy Asthma Rep)
* Current Alzheimer Research (CAR)
* Current Anesthesiology Reports (Curr Anesthesiol Rep)
* Current Applied Physics
* Current Atherosclerosis Reports (Curr Atheroscler Rep)
* Current Behavioral Neuroscience Reports
* Current Biology
* Current Bladder Dysfunction Reports (Curr Bladder Dysfunct Rep)
* Current Breast Cancer Reports (Curr Breast Cancer Rep)
* Current Cardiology Reports (Curr Cardiol Rep)
* Current Cardiovascular Imaging Reports (Curr Cardiovasc Imaging Rep)
* Current Cardiovascular Risk Reports (Curr Cardiovasc Risk Rep)
* Current Climate Change Reports
* Current Clinical Microbiology Reports
* Current Colorectal Cancer Reports (Curr Colorectal Cancer Rep)
* Current Dermatology Reports (Curr Derm Rep)
* Current Developmental Disorders Reports
* Current Diabetes Reports (Curr Diab Rep)
* Current Emergency and Hospital Medicine Reports (Curr Emerg Hosp Med Rep)
* Current Environmental Health Reports
* Current Epidemiology Reports
* Current Eye Research
* Current Forestry Reports
* Current Fungal Infection Reports (Curr Fungal Infect Rep)
* Current Gastroenterology Reports (Curr Gastroenterol Rep)
* Current Gene Therapy
* Current Genetic Medicine Reports (Curr Genet Med Rep)
* Current Genetics (Curr Genet)
* Current Geriatrics Reports
* Current Heart Failure Reports (Curr Heart Fail Rep)
* Current Hematologic Malignancy Reports (Curr Hematol Malig Rep)
* Current Hepatology Reports
* Current HIV/AIDS Reports (Curr HIV/AIDS Rep)
* Current Hypertension Reports (Curr Hypertens Rep)
* Current Infectious Disease Reports (Curr Infect Dis Rep)
* Current Issues in Language Planning
* Current Issues in Tourism
* Current Landscape Ecology Reports
* Current Medical Research and Opinion
* Current Medicine Research and Practice
* Current Microbiology (Curr Microbiol)
* Current Molecular Biology Reports
* Current Neurology and Neuroscience Reports (Curr Neurol Neurosci Rep)
* Current Nutrition Reports (Curr Nutr Rep)
* Current Obesity Reports (Curr Obes Rep)
* Current Obstetrics and Gynecology Reports (Curr Obstet Gynecol Rep)
* Current Oncology Reports (Curr Oncol Rep)
* Current Ophthalmology Reports (Curr Ophthalmol Rep)
* Current Opinion in Behavioral Sciences
* Current Opinion in Biotechnology
* Current Opinion in Cell Biology
* Current Opinion in Chemical Biology
* Current Opinion in Chemical Engineering
* Current Opinion in Colloid & Interface Science
* Current Opinion in Electrochemistry
* Current Opinion in Environmental Sustainability
* Current Opinion in Food Science
* Current Opinion in Genetics & Development
* Current Opinion in Green and Sustainable Chemistry
* Current Opinion in Immunology
* Current Opinion in Insect Science
* Current Opinion in Microbiology
* Current Opinion in Neurobiology
* Current Opinion in Ophthalmology
* Current Opinion in Pharmacology
* Current Opinion in Plant Biology
* Current Opinion in Psychology
* Current Opinion in Solid State & Materials Science
* Current Opinion in Structural Biology
* Current Opinion in Toxicology
* Current Opinion in Virology
* Current Opinion journals
* Current Oral Health Reports
* Current Osteoporosis Reports (Curr Osteoporos Rep)
* Current Otorhinolaryngology Reports (Curr Otorhinolaryngol Rep)
* Current Pain and Headache Reports (Curr Pain Headache Rep)
* Current Pathobiology Reports (Curr Pathobiol Rep)
* Current Pediatrics Reports (Curr Pediatr Rep)
* Current Pharmaceutical Design (CPD)
* Current Pharmacology Reports
* Current Physical Medicine and Rehabilitation Reports (Curr Phys Med Rehabil Rep)
* Current Plant Biology
* Current Pollution Reports
* Current Problems in Cardiology
* Current Problems in Pediatric and Adolescent Health Care
* Current Problems in Surgery
* Current Proteomics
* Current Protocols journals
* Current Psychiatry Reports (Curr Psychiatry Rep)
* Current Psychology (Curr Psychol)
* Current Pulmonology Reports
* Current Radiology Reports (Curr Radiol Rep)
* Current Research in Translational Medicine
* Current Reviews in Musculoskeletal Medicine (Curr Rev Musculoskelet Med)
* Current Rheumatology Reports (Curr Rheumatol Rep)
* Current Science
* Current Sexual Health Reports
* Current Sleep Medicine Reports
* Current Stem Cell Reports
* Current Surgery Reports (Curr Surg Rep)
* Current Sustainable/Renewable Energy Reports
* Current Therapeutic Research
* Current Topics in Medicinal Chemistry (Curr Top Med Chem)
* Current Transplantation Reports
* Current Trauma Reports
* Current Treatment Options in Allergy
* Current Treatment Options in Cardiovascular Medicine (Curr Treat Options Cardio Med)
* Current Treatment Options in Gastroenterology
* Current Treatment Options in Infectious Diseases
* Current Treatment Options in Neurology (Curr Treat Options Neurol)
* Current Treatment Options in Oncology (Curr. Treat. Options in Oncol.)
* Current Treatment Options in Pediatrics
* Current Treatment Options in Psychiatry
* Current Treatment Options in Rheumatology
* Current Tropical Medicine Reports
* Current Urology
* Current Urology Reports (Curr Urol Rep)
* Currents in Biblical Research
* Currents in Pharmacy Teaching and Learning
* Curriculum Journal
* Customer Needs and Solutions
* Cyberpsychology, Behavior, and Social Networking
* Cytogenetic and Genome Research
* Cytokine
* Cytokine and Growth Factor Reviews
* Cytometry
* Cytotechnology
* Cytotherapy
* Czech Journal of Tourism
* Dairy
* Dairy Science & Technology (Dairy Sci. & Technol.)
* Dalton Transactions
* Danish Medical Journal
* DARU Journal of Pharmaceutical Sciences
* Data
* Data & Knowledge Engineering
* Data in Brief
* Data Mining and Knowledge Discovery (Data Min Knowl Disc)
* Data Science and Engineering
* Data Science Journal
* Database
* Datenbank-Spektrum (German) (Datenbank Spektrum)
* De Buck (Dutch)
* De Economist
* De Montfort University - Harvard
* Deakin University - Harvard
* Debate Feminista
* Debatte: Journal of Contemporary Central and Eastern Europe
* Decision
* DECISION - Indian Institute of Management Calcutta
* Decision Analysis
* Decision Analytics
* Decision Sciences
* Decision Support Systems
* Decisions in Economics and Finance (Decisions Econ Finan)
* Deep-Sea Research Part I
* Deep-Sea Research Part II
* Defence Technology
* Dementia and Geriatric Cognitive Disorders
* Dementia and Geriatric Cognitive Disorders Extra
* Democratization
* Demographic Research
* Demography
* Dendrochronologia
* Dental Abstracts
* Dental Materials
* Dentistry Journal
* Dentomaxillofacial Radiology
* Der Anaesthesist (German) (Anaesthesist)
* Der Chirurg (German) (Chirurg)
* Der Diabetologe (German) (Diabetologe)
* Der Freie Zahnarzt (German) (Freie Zahnarzt)
* Der Gastroenterologe (German) (Gastroenterologe)
* Der Gynäkologe (German) (Gynäkologe)
* Der Hautarzt (German) (Hautarzt)
* Der Internist (German) (Internist)
* der junge zahnarzt (German) (der junge zahnarzt)
* Der Kardiologe (German) (Kardiologe)
* Der MKG-Chirurg (German) (MKG-Chirurg)
* der moderne staat (German) (dms)
* Der Nephrologe (German) (Nephrologe)
* Der Nervenarzt (German) (Nervenarzt)
* Der Notarzt
* Der Nuklearmediziner
* Der Onkologe (German) (Onkologe)
* Der Ophthalmologe (German) (Ophthalmologe)
* Der Orthopäde (German) (Orthopäde)
* Der Pathologe (German) (Pathologe)
* Der Pneumologe (German) (Pneumologe)
* Der Radiologe (German) (Radiologe)
* Der Schmerz (German) (Schmerz)
* Der Unfallchirurg (German) (Unfallchirurg)
* Der Urologe (German) (Urologe)
* Der Zoologische Garten
* Dermato-Endocrinology
* Dermatology
* Dermatology and Therapy (Dermatol Ther (Heidelb))
* Dermatopathology
* Desalination
* Design Automation for Embedded Systems (Des Autom Embed Syst)
* Design Studies
* Designed Monomers and Polymers
* Designs
* Designs, Codes and Cryptography (Des. Codes Cryptogr.)
* Deutsche Gesellschaft für Psychologie (German)
* Deutsche Sprache (German)
* Deutsches Archäologisches Institut (DAI)
* Deutsches Ärzteblatt
* Development
* Development and Change
* Development Engineering
* Development Genes and Evolution (Dev Genes Evol)
* Development in Practice
* Development Policy Review
* Developmental and Comparative Immunology
* Developmental Biology
* Developmental Cell
* Developmental Cognitive Neuroscience
* Developmental Neurobiology
* Developmental Neuroscience
* Developmental Psychology
* Developmental Review
* Diabetes
* Diabetes & Metabolic Syndrome: Clinical Research & Reviews
* Diabetes & Vascular Disease Research
* Diabetes and Metabolism
* Diabetes Care
* Diabetes Management
* Diabetes Research and Clinical Practice
* Diabetes Therapy (Diabetes Ther)
* Diabetologia
* Diabetologie und Stoffwechsel
* Diabetology & Metabolic Syndrome
* Diabetology International (Diabetol Int)
* Diagnostic and Interventional Imaging
* Diagnostic Cytopathology
* Diagnostic Microbiology & Infectious Disease
* Diagnostic Pathology
* Diagnóstico Prenatal (Spanish) (DIAPRE)
* Diagnostics
* Diagnostics in Neuropsychiatry
* Dialectical Anthropology (Dialect Anthropol)
* Dialisis y Trasplante (Spanish) (DIALIS)
* Diamond & Related Materials
* Diaspora Studies
* Diatom Research
* Die Bachelorarbeit (Samac et al.) (in-text, German)
* Die Bachelorarbeit (Samac et al.) (note, German)
* Die Rehabilitation
* Die Wirbelsäule
* Differential Equations and Dynamical Systems (Differ Equ Dyn Syst)
* Differential Geometry and its Applications
* Differentiation
* Digestion
* Digestive and Liver Disease
* Digestive and Liver Disease Supplements
* Digestive Diseases
* Digestive Surgery
* Digital Applications in Archaeology and Cultural Heritage
* Digital Communications and Networks
* Digital Creativity
* Digital Experiences in Mathematics Education
* Digital Investigation
* Digital Journalism
* Digital Signal Processing
* DIN 1505-2 (alphanumeric, German)
* DIN 1505-2 (author-date, German)
* DIN 1505-2 (numeric, German)
* DIN 1505-2 (numeric, sorted alphabetically, German)
* Diplo
* Disability & Society
* Disability and Health Journal
* Disability and Rehabilitation
* Disaster and Military Medicine
* Disaster Health
* Discourse, Context & Media
* Discourse: Studies in the Cultural Politics of Education
* Discovery Medicine (DM)
* Discrete & Computational Geometry (Discrete Comput Geom)
* Discrete Applied Mathematics
* Discrete Event Dynamic Systems (Discrete Event Dyn Syst)
* Discrete Mathematics
* Discrete Optimization
* Disease Models & Mechanisms
* Disease-a-Month
* Diseases
* Diseases of Aquatic Organisms
* Diseases of the Colon & Rectum
* Diseases of the Esophagus
* Displays
* Distributed and Parallel Databases (Distrib Parallel Databases)
* Distributed Computing (Distrib. Comput.)
* Diversity
* Diversity and Distributions
* DMW - Deutsche Medizinische Wochenschrift
* DNA Repair
* DNA Research
* Documenta Ophthalmologica (Doc Ophthalmol)
* Documents d'archéologie française (French) (DAF)
* Domestic Animal Endocrinology
* Donau-Universität Krems - Department für E-Governance in Wirtschaft und Verwaltung (German - Austria)
* Douleurs Evaluation - Diagnostic - Traitement
* Dramatherapy
* Dreaming
* Drinking Water Engineering and Science
* Drinking Water Engineering and Science Discussions
* Drones
* Drug and Alcohol Dependence
* Drug and Therapeutics Bulletin
* Drug Delivery and Translational Research (Drug Deliv. and Transl. Res.)
* Drug Development Research
* Drug Discovery Today: Disease Mechanisms
* Drug Discovery Today: Disease Models
* Drug Discovery Today: Technologies
* Drug Discovery Today: Therapeutic Strategies
* Drug Invention Today
* Drug Metabolism and Disposition
* Drug Metabolism and Pharmacokinetics
* Drug Research
* Drug Resistance Updates
* Drug Safety (Drug Saf)
* Drug Safety - Case Reports
* Drug Testing and Analysis
* Drugs
* Drugs - Real World Outcomes
* Drugs & Aging (Drugs Aging)
* Drugs & Therapy Perspectives (Drugs Ther Perspect)
* Drugs in R&D (Drugs R D)
* Drugs of the Future
* Drugs of Today
* Dublin City University - Harvard (Harvard (DCU))
* Dundalk Institute of Technology - Harvard (Harvard - DkIT)
* Durchstarten zur Diplomarbeit (BHS) (in-text, German)
* Durchstarten zur Diplomarbeit (BHS) (note, German)
* Durchstarten zur Vorwissenschaftlichen Arbeit (AHS) (in-text, German)
* Durchstarten zur Vorwissenschaftlichen Arbeit (AHS) (note, German)
* Durham University Business School - Harvard
* Dyes and Pigments
* Dynamic Games and Applications (Dyn Games Appl)
* Dynamical Systems
* Dynamics of Atmospheres and Oceans
* Dysphagia
* e & i Elektrotechnik und Informationstechnik (German) (Elektrotech. Inftech.)
* e-Neuroforum
* Ear and Hearing
* Early Child Development and Care
* Early Childhood Education Journal (Early Childhood Educ J)
* Early Childhood Research Quarterly
* Early Christianity (EC)
* Early Human Development
* Early Medieval Europe
* Early Popular Visual Culture
* Early Years
* Earth and Planetary Science Letters
* Earth and Space Science
* Earth Interactions
* Earth Perspectives
* Earth Science Informatics (Earth Sci Inform)
* Earth Surface Dynamics
* Earth Surface Dynamics Discussions
* Earth Surface Processes and Landforms
* Earth System Dynamics
* Earth System Dynamics Discussions
* Earth System Science Data
* Earth System Science Data Discussions
* Earth-Observations-X
* Earth-Science Reviews
* Earth, Moon, and Planets (Earth Moon Planets)
* Earth, Planets and Space
* Earth's Future
* Earthquake Engineering & Structural Dynamics (Earthquake Engng. Struct. Dyn.)
* Earthquake Science
* Earthquake Spectra
* East Asian Archives of Psychiatry
* East European Jewish Affairs
* East European Politics
* Eastern Mediterranean Health Journal
* Eating and Weight Disorders - Studies on Anorexia, Bulimia and Obesity
* Eating Behaviors
* EBioMedicine
* Ecclesial Practices
* Ecography
* EcoHealth (Ecohealth)
* Ecohydrology & Hydrobiology
* École de technologie supérieure - APA (French - Canada) (ETS-APA)
* École Pratique des Hautes Études - Sciences historiques et philologiques (French) (EPHE-SHP)
* Ecological Applications
* Ecological Complexity
* Ecological Economics
* Ecological Engineering
* Ecological Entomology
* Ecological Genetics and Genomics
* Ecological Indicators
* Ecological Informatics
* Ecological Modelling
* Ecological Monographs
* Ecological Processes
* Ecological Research (Ecol Res)
* Ecological Restoration (ER)
* Ecology
* Ecology and Society
* Ecology Letters
* Ecology of Freshwater Fish
* Econometrica
* Econometrics
* Econometrics and Statistics
* EconomiA
* Economia Politica
* Economic Analysis and Policy
* Economic Change and Restructuring (Econ Change Restruct)
* Economic Commission for Latin America and the Caribbean (ECLAC)
* Economic Geology
* Economic Modelling
* Economic Systems
* Economic Theory (Econ Theory)
* Economic Theory Bulletin
* Economics and Human Biology
* Economics Letters
* Economics of Education Review
* Economics of Governance (Econ Gov)
* Economics of Innovation and New Technology
* Economics of Transportation
* Économie et Statistique (French) (Éco & Stat)
* Economies
* EcoSal Plus
* Écoscience
* Ecosistemas (Spanish)
* Ecosphere
* Ecosystem Health and Sustainability
* Ecosystem Services
* Ecosystems
* Ecotoxicology
* Ecotoxicology and Environmental Safety
* Edge Hill University - Harvard
* Educación Médica (Spanish)
* Educación Médica Superior
* Educación Química
* Education & Practice
* Education 3-13
* Education and Information Technologies (Educ Inf Technol)
* Education Economics
* Education for Chemical Engineers
* Education Sciences
* Educational Action Research
* Educational Assessment, Evaluation and Accountability (Educ Asse Eval Acc)
* Educational Evaluation and Policy Analysis
* Educational Media International
* Educational Philosophy and Theory
* Educational Psychology
* Educational Psychology in Practice
* Educational Psychology Review (Educ Psychol Rev)
* Educational Research
* Educational Research and Evaluation
* Educational Research for Policy and Practice (Educ Res Policy Prac)
* Educational Research Review
* Educational Researcher
* Educational Review
* Educational Studies
* Educational Studies in Mathematics (Educ Stud Math)
* Educational Technology Research and Development (Education Tech Research Dev)
* Edward Elgar Publishing - Business and Social Sciences
* Efficacy and Mechanism Evaluation
* Egretta (German - Austria) (Egretta)
* Egyptian Informatics Journal
* Egyptian Journal of Anaesthesia
* Egyptian Journal of Basic and Applied Sciences
* Egyptian Journal of Chest Diseases and Tuberculosis
* Egyptian Journal of Ear, Nose, Throat and Allied Sciences
* Egyptian Journal of Medical Human Genetics
* Egyptian Journal of Petroleum
* Egyptian Pediatric Association Gazette
* Eighteenth-Century Life
* Einaudi (Italian)
* EJC Supplements
* EJNMMI Physics
* EJNMMI Radiopharmacy and Chemistry
* EJNMMI Research
* Ekonomie a Management (E+M)
* El profesional de la información (Spanish)
* Electoral Studies
* Electric Power Systems Research
* Electrical Engineering (Electr Eng)
* Electrocatalysis
* Electrochemistry Communications
* Electrochimica Acta
* Electronic Commerce Research (Electron Commer Res)
* Electronic Commerce Research and Applications
* Electronic Journal of Biotechnology
* Electronic Markets (Electron Markets)
* Electronic Notes in Discrete Mathematics
* Electronic Notes in Theoretical Computer Science
* Electronics
* Electronics Letters
* Elementa
* Elsevier - Harvard (with titles)
* Elsevier - Harvard (without titles)
* Elsevier - Harvard 2
* Elsevier - Vancouver
* Elsevier - Vancouver (author-date)
* Elsevier (numeric, with titles, sorted alphabetically)
* Elsevier (numeric, with titles)
* Elsevier (numeric, without titles)
* EMBO reports
* Emerald - Harvard
* Emergency Medicine Journal
* Emergency Radiology (Emerg Radiol)
* Emerging Contaminants
* Emerging Infectious Diseases
* Emerging Markets Review
* Emerging Microbes & Infections
* Emerging Themes in Epidemiology
* Emission Control Science and Technology
* Emotion
* Emotion, Space and Society
* Emotional and Behavioural Difficulties
* Empirica
* Empirical Economics (Empir Econ)
* Empirical Research in Vocational Education and Training
* Empirical Software Engineering (Empir Software Eng)
* Employee Responsibilities and Rights Journal (Employ Respons Rights J)
* Emu - Austral Ornithology
* Endangered Species Research
* Endeavour
* Endeavour College of Natural Health
* Endo-Praxis
* Endocrine
* Endocrine Disruptors
* Endocrine Press
* Endocrine Reviews
* Endocrine-Related Cancer
* Endocrinología y Nutrición (Spanish)
* Endocrinology
* Endokrinologie Informationen
* Endoscopia (Spanish) (ENDOMX)
* Endoscopy
* Endoscopy International Open
* Energies
* Energy
* Energy & Buildings
* Energy & Environmental Science
* Energy & Fuels (Energy Fuels)
* Energy Conversion and Management
* Energy Economics
* Energy Efficiency
* Energy for Sustainable Development
* Energy Policy
* Energy Reports
* Energy Research & Social Science
* Energy Storage Materials
* Energy Strategy Reviews
* Energy Systems (Energy Syst)
* Energy, Ecology and Environment
* Energy, Sustainability and Society
* eNeuro
* eNeurologicalSci
* Enfermedades Infecciosas y Microbiología Clínica (Spanish)
* Enfermería Clínica (Spanish) (ENFCLI)
* Enfermería Intensiva (Spanish) (ENFI)
* Engineering
* Engineering & Technology
* Engineering Analysis with Boundary Elements
* Engineering Applications of Artificial Intelligence
* Engineering Failure Analysis
* Engineering Fracture Mechanics
* Engineering Geology
* Engineering Geology Special Publications
* Engineering in Agriculture, Environment and Food
* Engineering in Life Sciences
* Engineering Management Journal
* Engineering Optimization
* Engineering Science and Technology, an International Journal
* Engineering Structures
* Engineering with Computers
* ENS de Lyon - Centre d'ingénierie documentaire (French) (CID)
* Ensayos sobre Política Económica
* Enterprise Information Systems
* Entertainment Computing
* Entomologia Experimentalis et Applicata
* Entomological Society of America (ESA)
* Entrepreneurship & Regional Development
* Entrepreneurship Theory and Practice (ETP)
* Entropy
* Environment and Planning
* Environment and Planning A
* Environment and Planning B, Planning & Design
* Environment and Planning C, Government & Policy
* Environment and Planning D, Society & Space
* Environment and Urbanization
* Environment International
* Environment Systems and Decisions (Environ Syst Decis)
* Environment, Development and Sustainability (Environ Dev Sustain)
* Environmental & Engineering Geoscience
* Environmental and Ecological Statistics (Environ Ecol Stat)
* Environmental and Experimental Botany
* Environmental and Planning Law Journal (EPLJ)
* Environmental and Resource Economics (Environ Resource Econ)
* Environmental Biology of Fishes (Environ Biol Fish)
* Environmental Chemistry
* Environmental Chemistry Letters (Environ Chem Lett)
* Environmental Communication: A Journal of Nature and Culture
* Environmental Conservation
* Environmental Development
* Environmental Earth Sciences (Environ Earth Sci)
* Environmental Economics and Policy Studies (Environ Econ Policy Stud)
* Environmental Education Research
* Environmental Entomology
* Environmental Evidence
* Environmental Fluid Mechanics (Environ Fluid Mech)
* Environmental Geochemistry and Health (Environ Geochem Health)
* Environmental Geosciences
* Environmental Hazards
* Environmental Health
* Environmental Health and Preventive Medicine (Environ Health Prev Med)
* Environmental Health Perspectives (EHP)
* Environmental Impact Assessment Review
* Environmental Innovation and Societal Transitions
* Environmental Management
* Environmental Microbiology
* Environmental Modeling & Assessment (Environ Model Assess)
* Environmental Modelling and Software
* Environmental Monitoring and Assessment (Environ Monit Assess)
* Environmental Nanotechnology, Monitoring & Management
* Environmental Pollution
* Environmental Processes
* Environmental Research
* Environmental Research Letters
* Environmental Reviews
* Environmental Science & Technology (Environ. Sci. Technol.)
* Environmental Science & Technology Letters (Environ. Sci. Technol. Lett.)
* Environmental Science and Policy
* Environmental Science and Pollution Research (Environ Sci Pollut Res)
* Environmental Science: Nano
* Environmental Science: Processes & Impacts
* Environmental Science: Water Research & Technology
* Environmental Sciences Europe
* Environmental Systems Research
* Environmental Technology
* Environmental Technology & Innovation
* Environmental Technology Reviews
* Environmental Toxicology and Chemistry
* Environmental Toxicology and Pharmacology
* Environmental Values
* Environments
* Environnement, Risques & Santé
* Enzyme and Microbial Technology
* Ephemerides Theologicae Lovanienses (ETL)
* Epidemics
* Épidémiologie et Santé Animale
* Epidemiology
* Epidemiology & Infection
* Epigenetics
* Epigenetics & Chromatin
* Epigenomes
* Epigenomics
* Epilepsia
* Epilepsy & Behavior
* Epilepsy & Behavior Case Reports
* Epilepsy Research
* Epileptology
* EPJ Data Science
* EPJ Nonlinear Biomedical Physics
* EPJ Quantum Technology
* EPJ Techniques and Instrumentation
* EPL
* EPMA Journal
* Equine Veterinary Education
* Equine Veterinary Journal
* ERA Forum
* Ergonomics
* ergoscience
* Erkenntnis (Erkenn)
* Erwerbs-Obstbau (German) (Erwerbs-Obstbau)
* Escola de Comando e Estado-Maior do Exército - ABNT (Portuguese - Brazil) (ABNT-ECEME/ME 21-253)
* Escola de Comando e Estado-Maior do Exército - Instituto Meira Mattos - ABNT (Portuguese - Brazil) (ABNT-ECEME/IMM)
* Escuela Nacional de Antropología e Historia (autor-fecha) (Spanish - Mexico) (ENAH (autor-fecha))
* Escuela Nacional de Antropología e Historia (nota completa) (Spanish - Mexico) (ENAH (nota completa))
* Escuela Nacional de Antropología e Historia (nota corta) (Spanish - Mexico) (ENAH (nota corta))
* Esophagus
* Estuaries and Coasts
* Estuarine, Coastal and Shelf Science
* Estudios de Cultura Maya (Spanish - Mexico)
* Estudios de Historia Moderna y Contemporánea de México
* Estudios de Historia Novohispana
* Estudios Gerenciales
* Ethical Theory and Moral Practice (Ethic Theory Moral Prac)
* Ethics (for book reviews)
* Ethics and Education
* Ethics and Information Technology (Ethics Inf Technol)
* Ethics and Social Welfare
* Ethics in Science and Environmental Politics
* Ethics, Medicine and Public Health
* Ethik in der Medizin (German) (Ethik Med)
* Ethique et Santé
* Ethnic and Racial Studies
* Ethnicity & Health
* Ethnobiology and Conservation (Ethnobiol Conserv)
* Ethnography and Education
* Ethnologie française (French)
* Ethnomusicology
* ÉTS - École de technologie supérieure (French - Canada) (ÉTS)
* Eukaryotic Cell (EC)
* EuPA Open Proteomics
* Euphytica
* Eurasian Business Review
* Eurasian Economic Review
* Eurasian Geography and Economics
* EURASIP Journal on Advances in Signal Processing
* EURASIP Journal on Audio, Speech, and Music Processing
* EURASIP Journal on Bioinformatics and Systems Biology
* EURASIP Journal on Embedded Systems
* EURASIP Journal on Image and Video Processing
* EURASIP Journal on Information Security
* EURASIP Journal on Wireless Communications and Networking
* EURO Journal on Computational Optimization (EURO J Comput Optim)
* EURO Journal on Decision Processes (EURO J Decis Process)
* EURO Journal on Transportation and Logistics (EURO J Transp Logist)
* Euro-Mediterranean Journal for Environmental Integration
* EuroIntervention
* Europace
* European Actuarial Journal (Eur. Actuar. J.)
* European Addiction Research
* European Annals of Otorhinolaryngology, Head and Neck diseases
* European Archaeology - Harvard
* European Archives of Oto-Rhino-Laryngology (Eur Arch Otorhinolaryngol)
* European Archives of Paediatric Dentistry (Eur Arch Paediatr Dent)
* European Archives of Psychiatry and Clinical Neuroscience (Eur Arch Psychiatry Clin Neurosci)
* European Biophysics Journal (Eur Biophys J)
* European Business Organization Law Review
* European Cells & Materials (eCM)
* European Child & Adolescent Psychiatry (Eur Child Adolesc Psychiatry)
* European Early Childhood Education Research Journal
* European Economic Review
* European Food Research and Technology (Eur Food Res Technol)
* European Geriatric Medicine
* European Heart Journal
* European Heart Journal - Acute Cardiovascular Care
* European Heart Journal - Cardiovascular Imaging
* European Journal for Philosophy of Science (Euro Jnl Phil Sci)
* European Journal for Security Research
* European Journal of Ageing (Eur J Ageing)
* European Journal of Agronomy
* European Journal of Applied Physiology (Eur J Appl Physiol)
* European Journal of Business and Economics
* European Journal of Cancer
* European Journal of Cardiovascular Nursing
* European Journal of Cell Biology
* European Journal of Clinical Investigation
* European Journal of Clinical Microbiology & Infectious Diseases
* European Journal of Clinical Nutrition
* European Journal of Clinical Pharmacology (Eur J Clin Pharmacol)
* European Journal of Combinatorics
* European Journal of Developmental Psychology
* European Journal of Drug Metabolism and Pharmacokinetics (Eur J Drug Metab Pharmacokinet)
* European Journal of Education and Psychology
* European Journal of Emergency Medicine
* European Journal of Endocrinology (Eur J Endocrinol)
* European Journal of Engineering Education
* European Journal of Environmental and Civil Engineering
* European Journal of Epidemiology (Eur J Epidemiol)
* European Journal of Family Business
* European Journal of Forest Research (Eur J Forest Res)
* European Journal of Futures Research (Eur J Futures Res)
* European Journal of Gastroenterology & Hepatology
* European Journal of Haematology
* European Journal of Heart Failure
* European Journal of Higher Education
* European Journal of Hospital Pharmacy
* European Journal of Human Genetics
* European Journal of Immunology
* European Journal of Information Systems (EJIS)
* European Journal of Integrative Medicine
* European Journal of Internal Medicine
* European Journal of International Law
* European Journal of Law and Economics (Eur J Law Econ)
* European Journal of Management and Business Economics
* European Journal of Mathematics
* European Journal of Mechanics / A Solids
* European Journal of Mechanics / B Fluids
* European Journal of Medical Genetics
* European Journal of Medical Research
* European Journal of Medicinal Chemistry
* European Journal of Microbiology & Immunology (EUJMI)
* European Journal of Neuroscience
* European Journal of Nuclear Medicine and Molecular Imaging (Eur J Nucl Med Mol Imaging)
* European Journal of Nutrition (Eur J Nutr)
* European Journal of Obstetrics and Gynecology
* European Journal of Oncology Nursing
* European Journal of Operational Research
* European Journal of Ophthalmology
* European Journal of Oral Sciences
* European Journal of Orthopaedic Surgery & Traumatology (Eur J Orthop Surg Traumatol)
* European Journal of Paediatric Neurology (EJPN)
* European Journal of Pain
* European Journal of Pediatrics (Eur J Pediatr)
* European Journal of Pharmaceutical Sciences
* European Journal of Pharmaceutics and Biopharmaceutics
* European Journal of Pharmacology
* European Journal of Physics
* European Journal of Plant Pathology (Eur J Plant Pathol)
* European Journal of Plastic Surgery (Eur J Plast Surg)
* European Journal of Political Economy
* European Journal of Political Research
* European Journal of Population (Eur J Population)
* European Journal of Preventive Cardiology
* European Journal of Protistology
* European Journal of Psychological Assessment
* European Journal of Psychology of Education (Eur J Psychol Educ)
* European Journal of Psychotherapy & Counselling
* European Journal of Psychotraumatology
* European Journal of Public Health (EJPH)
* European Journal of Radiology
* European Journal of Radiology Open
* European Journal of Social Work
* European Journal of Soil Biology
* European Journal of Soil Science
* European Journal of Special Needs Education
* European Journal of Sport Science
* European Journal of Surgical Oncology
* European Journal of Sustainable Development
* European Journal of Teacher Education
* European Journal of Trauma & Dissociation
* European Journal of Trauma and Emergency Surgery (Eur J Trauma Emerg Surg)
* European Journal of Ultrasound (Ultraschall in der Medizin)
* European Journal of Vascular and Endovascular Surgery (EJVS)
* European Journal of Wildlife Research (Eur J Wildl Res)
* European Journal of Wood and Wood Products (Eur. J. Wood Prod.)
* European Journal of Work and Organizational Psychology
* European Journal on Criminal Policy and Research (Eur J Crim Policy Res)
* European Management Journal
* European Medical, Health and Pharmaceutical Journal
* European Neurology
* European Neuropsychopharmacology
* European Orthopaedics and Traumatology (Eur Orthop Traumatol)
* European Polymer Journal
* European Psychiatry
* European Psychologist
* European Radiology (Eur Radiol)
* European Research in Telemedicine/La Recherche Européenne en Télémédecine
* European research on management and business economics
* European Respiratory Journal
* European Retail Research
* European Review of Aging and Physical Activity (Eur Rev Aging Phys Act)
* European Review of History: Revue europeenne d'histoire
* European Review of Social Psychology
* European Society of Cardiology
* European Spine Journal (Eur Spine J)
* European Sport Management Quarterly
* European Surgery (Eur Surg)
* European Surgical Research
* European Thyroid Journal
* European Transport Research Review (Eur. Transp. Res. Rev.)
* European Union Interinstitutional Style Guide
* European Urology
* European Urology Focus
* European Urology Supplements
* European View
* Evaluation and Program Planning
* Evidence-Based Communication Assessment and Intervention
* Evidence-Based Complementary and Alternative Medicine (eCAM)
* Evidence-Based Dentistry
* Evidence-Based Medicine
* Evidence-Based Mental Health
* Evidence-Based Nursing
* EvoDevo
* Evolution
* Evolution & Development
* Evolution and Human Behavior
* Evolution: Education and Outreach
* Evolutionary and Institutional Economics Review
* Evolutionary Anthropology
* Evolutionary Behavioral Sciences
* Evolutionary Bioinformatics
* Evolutionary Biology (Evol Biol)
* Evolutionary Ecology (Evol Ecol)
* Evolutionary Ecology Research (EER)
* Evolutionary Intelligence (Evol. Intel.)
* Evolutionary Psychological Science
* Evolving Systems
* exercer (French)
* Experimental & Molecular Medicine
* Experimental & Translational Stroke Medicine
* Experimental and Applied Acarology (Exp Appl Acarol)
* Experimental and Clinical Endocrinology & Diabetes
* Experimental and Clinical Endocrinology & Diabetes Reports
* Experimental and Clinical Psychopharmacology
* Experimental and Molecular Pathology
* Experimental and Therapeutic Medicine
* Experimental and Toxicologic Pathology
* Experimental Astronomy (Exp Astron)
* Experimental Brain Research (Exp Brain Res)
* Experimental Cell Research
* Experimental Dermatology (ED)
* Experimental Economics (Exp Econ)
* Experimental Eye Research
* Experimental Gerontology
* Experimental Hematology & Oncology
* Experimental Mechanics (Exp Mech)
* Experimental Neurology
* Experimental Parasitology
* Experimental Physiology
* Experimental Psychology
* Experimental Techniques
* Experimental Thermal and Fluid Science
* Experiments in Fluids (Exp Fluids)
* Expert Review of Anti-infective Therapy
* Expert Review of Anticancer Therapy
* Expert Review of Cardiovascular Therapy
* Expert Review of Clinical Immunology
* Expert Review of Clinical Pharmacology
* Expert Review of Endocrinology & Metabolism
* Expert Review of Gastroenterology & Hepatology
* Expert Review of Hematology
* Expert Review of Medical Devices
* Expert Review of Molecular Diagnostics
* Expert Review of Neurotherapeutics
* Expert Review of Ophthalmology
* Expert Review of Pharmacoeconomics & Outcomes Research
* Expert Review of Precision Medicine & Drug Development
* Expert Review of Proteomics
* Expert Review of Quality of Life in Cancer Care
* Expert Review of Respiratory Medicine
* Expert Review of Vaccines
* Expert Systems With Applications
* Explorations in Economic History
* EXPLORE
* Exposure and Health
* Extreme Mechanics Letters
* Extreme Physiology & Medicine
* Extremes
* Extremophiles
* Eye
* Eye & Contact Lens
* Eye and Vision
* F1000Research
* Fachhochschule Kiel - Fachbereich Medien (German) (FH Kiel | Medien)
* Fachhochschule Salzburg - Harvard
* Fachhochschule Vorarlberg (author-date) (FHV Autor-Jahr)
* Fachhochschule Vorarlberg (note)
* Facial Plastic Surgery Clinics of North America (FSC)
* Facies
* Falmouth University - Harvard
* Familial Cancer
* Families, Systems, & Health
* Family Business Review (FBR)
* Family Law Review (Fam L Rev)
* Family Medicine
* Family Science
* Faraday Discussions
* Farmacia Hospitalaria (Spanish)
* Fashion and Textiles
* Fatigue: Biomedicine, Health & Behavior
* Feminist Economics
* Feminist Legal Studies (Fem Leg Stud)
* Feminist Media Studies
* FEMS Microbiology Ecology
* FEMS Microbiology Letters
* FEMS Microbiology Reviews
* FEMS Yeast Research
* Ferdinand Porsche Fern-Fachhochschule (German - Austria) (Ferdinand Porsche FernFH (German - Austria))
* Fermentation
* Fertility and Sterility
* Fertility Research and Practice
* Fetal & Neonatal
* Fetal Diagnosis and Therapy
* Feuillets de Radiologie
* Few-Body Systems (Few-Body Syst)
* Fibers
* Fibrogenesis & Tissue Repair
* Field Crops Research
* Fields Mathematics Education Journal
* Finance and Stochastics (Finance Stoch)
* Finance Research Letters
* Financial Innovation
* Financial Markets and Portfolio Management
* FinanzArchiv - Public Finance Analysis (FA)
* Fine Focus
* Finite Elements in Analysis & Design
* Finite Fields and Their Applications
* Fire Safety Journal
* Fire Science Reviews
* Fire Technology (Fire Technol)
* First Amendment Studies
* First Monday
* First World War Studies
* Fish and Fisheries
* Fish and Shellfish Immunology
* Fish Physiology and Biochemistry (Fish Physiol Biochem)
* Fisheries
* Fisheries Research
* Fisheries Science (Fish Sci)
* Fishery Bulletin
* Fishes
* Fisterra
* Fitoterapia
* Fixed Point Theory and Applications
* FlatChem
* Flavour
* Flavour and Fragrance Journal
* Flexible Services and Manufacturing Journal (Flex Serv Manuf J)
* Flora
* Florida Entomologist
* Flow Measurement and Instrumentation
* Flow, Turbulence and Combustion (Flow Turbulence Combust)
* Fluid Dynamics Research
* Fluid Phase Equilibria
* Fluids
* Fluids and Barriers of the CNS
* Fly
* FOLD&R (Fasti On Line Documents & Research)
* Folia Microbiologica (Folia Microbiol)
* Folia Phoniatrica et Logopaedica
* Folia Primatologica
* Food & Function
* Food Additives & Contaminants: Part A
* Food Additives & Contaminants: Part B
* Food Analytical Methods (Food Anal. Methods)
* Food and Agriculture Organization of the United Nations (FAO)
* Food and Bioprocess Technology (Food Bioprocess Technol)
* Food and Bioproducts Processing
* Food and Chemical Toxicology
* Food and Environmental Virology (Food Environ Virol)
* Food and Waterborne Parasitology
* Food Biophysics
* Food Bioscience
* Food Chemistry
* Food Control
* Food Digestion: Research and Current Opinion (Food Dig.)
* Food Engineering Reviews (Food Eng Rev)
* Food Ethics
* Food Hydrocolloids
* Food Microbiology
* Food Packaging and Shelf Life
* Food Policy
* Food Quality and Preference
* Food Research International
* Food Science and Human Wellness
* Food Security (Food Sec.)
* Food Structure
* Food Webs
* Foods
* Foot & Ankle International
* Foot and Ankle Surgery
* Foreign Policy Analysis
* Forensic Chemistry
* Forensic Science International
* Forensic Science International Supplement Series
* Forensic Science International: Genetics
* Forensic Science International: Genetics Supplement Series
* Forensic Science Review
* Forensic Science, Medicine, and Pathology (Forensic Sci Med Pathol)
* Forensic Toxicology (Forensic Toxicol)
* Forensische Psychiatrie, Psychologie, Kriminologie (German) (Forens Psychiatr Psychol Kriminol)
* Forest Ecology and Management
* Forest Ecosystems
* Forest Policy and Economics
* Forest Science
* Forest Science and Technology
* Forests
* Forests, Trees and Livelihoods
* Formal Methods in System Design (Form Methods Syst Des)
* Formosan Journal of Surgery
* Forschende Komplementärmedizin
* Forschung im Ingenieurwesen (German) (Forsch Ingenieurwes)
* Fortschritte der Neurologie - Psychiatrie
* Forum (German) (Forum)
* Forum der Psychoanalyse (German) (Forum Psychoanal)
* Forum for Social Economics
* Forum: Qualitative Social Research (Forum Qualitative Sozialforschung) (FQS)
* Fossil Record
* Foundations of Chemistry (Found Chem)
* Foundations of Physics (Found Phys)
* Foundations of Science (Found Sci)
* Fractal and Fractional
* France (auteurs et al., auteur-date, French)
* France (auteurs et al., numérotation, French)
* France (tous les auteurs, auteur-date, French)
* France (tous les auteurs, numérotation, French)
* Frauenheilkunde up2date
* Free Radical Biology and Medicine
* Free Radical Research
* Free Radicals and Antioxidants
* Freie Universität Berlin - Geographische Wissenschaften (German)
* French Historical Studies
* French Politics
* Freshwater Biology
* Freshwater Crayfish
* Freshwater Science
* Friedrich Schiller University Jena - Faculty of Medicine
* Frontiers for Young Minds
* Frontiers in Aging Neuroscience
* Frontiers in Applied Mathematics and Statistics
* Frontiers in Astronomy and Space Sciences
* Frontiers in Behavioral Neuroscience
* Frontiers in Bioengineering and Biotechnology
* Frontiers in Built Environment
* Frontiers in Cardiovascular Medicine
* Frontiers in Cell and Developmental Biology
* Frontiers in Cellular and Infection Microbiology
* Frontiers in Cellular Neuroscience
* Frontiers in Chemistry
* Frontiers in Communication
* Frontiers in Computational Neuroscience
* Frontiers in Digital Humanities
* Frontiers in Earth Science
* Frontiers in Ecology and Evolution
* Frontiers in Ecology and the Environment
* Frontiers in Education
* Frontiers in Endocrinology
* Frontiers in Energy Research
* Frontiers in Environmental Science
* Frontiers in Evolutionary Neuroscience
* Frontiers in Genetics
* Frontiers in Human Neuroscience
* Frontiers in ICT
* Frontiers in Immunology
* Frontiers in Integrative Neuroscience
* Frontiers in Laboratory Medicine
* Frontiers in Life Science
* Frontiers in Marine Science
* Frontiers in Materials
* Frontiers in Mechanical Engineering
* Frontiers in Medicine
* Frontiers in Microbiology
* Frontiers in Molecular Biosciences
* Frontiers in Molecular Neuroscience
* Frontiers in Neural Circuits
* Frontiers in Neuroanatomy
* Frontiers in Neuroendocrinology
* Frontiers in Neuroenergetics
* Frontiers in Neuroengineering
* Frontiers in Neuroinformatics
* Frontiers in Neurology
* Frontiers in Neurorobotics
* Frontiers in Neuroscience
* Frontiers in Nutrition
* Frontiers in Oncology
* Frontiers in Optics
* Frontiers in Pediatrics
* Frontiers in Pharmacology
* Frontiers in Physics
* Frontiers in Physiology
* Frontiers in Plant Science
* Frontiers in Psychiatry
* Frontiers in Psychology
* Frontiers in Public Health
* Frontiers in Research Metrics and Analytics
* Frontiers in Robotics and AI
* Frontiers in Sociology
* Frontiers in Surgery
* Frontiers in Synaptic Neuroscience
* Frontiers in Systems Neuroscience
* Frontiers in Veterinary Science
* Frontiers in Zoology
* Frontiers journals
* Frontiers medical journals
* Frontiers of Architectural Research
* Frontline Gastroenterology
* Fudan Journal of the Humanities and Social Sciences
* Fuel
* Fuel Processing Technology
* Functional & Integrative Genomics (Funct Integr Genomics)
* Functional Ecology
* Functional Linguistics
* Functional Plant Biology
* Fungal Biology
* Fungal Biology and Biotechnology
* Fungal Biology Reviews
* Fungal Diversity
* Fungal Ecology
* Fungal Genetics and Biology
* Fusion Engineering and Design
* Fusion Science and Technology (FST)
* Fuss und Sprunggelenk
* Future Business Journal
* Future Cardiology
* Future Cities and Environment
* Future Computing and Informatics Journal
* Future Dental Journal
* Future Generation Computer Systems
* Future Internet
* Future Journal of Pharmaceutical sciences
* Future Medicinal Chemistry
* Future Microbiology
* Future Neurology
* Future Oncology
* Future Science Group
* Future Science journals
* Future Virology
* Futures
* Fuzzy Information and Engineering
* Fuzzy Optimization and Decision Making (Fuzzy Optim Decis Making)
* Fuzzy Sets and Systems
* G3: Genes, Genomes, Genetics (G3)
* Gaceta Sanitaria (Spanish)
* Gait & Posture
* Galaxies
* Gallia (French)
* Gallia Préhistoire (French) (GP)
* Games
* Games and Economic Behavior
* Gastric Cancer
* Gastroenterología y Hepatología (Spanish)
* Gastroenterologie up2date
* Gastroenterology
* Gastrointestinal Endoscopy
* Gastrointestinal Endoscopy Clinics of North America (GEC)
* Gastrointestinal Intervention (GII)
* Gastrointestinal Tumors
* Geburtshilfe und Frauenheilkunde
* Gefässchirurgie (German) (Gefässchirurgie)
* Gefäßmedizin Scan
* Geistes- und Kulturwissenschaften (Heilmann) (German)
* Gels
* GEM - International Journal on Geomathematics (Int J Geomath)
* Gender and Education
* Gender Issues (Gend. Issues)
* Gender Medicine
* Gender, Place & Culture
* Gene
* Gene Expression Patterns
* Gene Reports
* Gene Therapy
* Genealogy
* General and Comparative Endocrinology
* General Hospital Psychiatry
* General Relativity and Gravitation (Gen Relativ Gravit)
* General Thoracic and Cardiovascular Surgery (Gen Thorac Cardiovasc Surg)
* Genes
* Genes & Cancer
* Genes & Development
* Genes & Diseases
* Genes & Genomics (Genes Genom)
* Genes & Immunity
* Genes & Nutrition (Genes Nutr)
* Genes and Environment
* Genes to Cells (Genes Cells)
* Genes, Brain and Behavior
* Genèses: Sciences sociales et histoire (French)
* Genetic Programming and Evolvable Machines (Genet Program Evolvable Mach)
* Genetic Resources and Crop Evolution (Genet Resour Crop Evol)
* Genetica
* Genetics
* Genetics and Molecular Biology
* Genetics in Medicine (GIM)
* Genetics Selection Evolution
* Genome
* Genome Announcements
* Genome Biology
* Genome Biology and Evolution
* Genome Medicine
* Genome Research
* Genomic Medicine, Biomarkers, and Health Sciences
* Genomics
* Genomics Data
* Genomics, Proteomics & Bioinformatics
* Geo-Marine Letters (Geo-Mar Lett)
* Geoarchaeology
* Geobiology
* Geobios
* Geocarto International
* Geochemical Perspectives Letters
* Geochemical Transactions
* Geochemistry, Geophysics, Geosystems
* Geochemistry: Exploration, Environment, Analysis
* Geochimica et Cosmochimica Acta
* Geochronometria
* Geoderma
* Geoderma Regional
* Geodesy and Geodynamics
* Geodinamica Acta
* Geoenvironmental Disasters
* Geoforum
* Geografie Sborník ČGS
* Geografisk Tidsskrift-Danish Journal of Geography
* Geographica Helvetica
* Geoheritage
* GeoInformatica (Geoinformatica)
* GeoJournal
* Geological Magazine
* Geological Society of America Bulletin (GSA Bulletin)
* Geological Society, London, Memoirs
* Geological Society, London, Special Publications
* Geology
* Geology of the Intermountain West
* Geomatics, Natural Hazards and Risk
* Geomechanics and Geophysics for Geo-Energy and Geo-Resources
* Geomechanics for Energy and the Environment
* Geometriae Dedicata (Geom Dedicata)
* Geomorphology
* Geophysical Research Letters
* Geopolitics
* GeoResJ
* Georg-August-Universität Göttingen - Institut für Ethnologie und Ethnologische Sammlung (German)
* Georisk: Assessment and Management of Risk for Engineered Systems and Geohazards
* Geoscience Letters
* Geosciences
* Geoscientific Instrumentation, Methods and Data Systems
* Geoscientific Instrumentation, Methods and Data Systems Discussions
* Geoscientific Model Development
* Geoscientific Model Development Discussions
* Geosphere
* Geosystem Engineering
* Geotechnical and Geological Engineering (Geotech Geol Eng)
* Geotextiles and Geomembranes
* Geothermal Energy
* Geothermics
* Geriatric Mental Health Care
* Geriatric Nursing
* Geriatrics
* German Council of Economic Experts (GCEE)
* Gerontology
* GeroPsych: The Journal of Gerontopsychology and Geriatric Psychiatry
* Gesellschaft für Bildung und Forschung in Europa - Harvard (German) (GBFE)
* Gesellschaft fur Popularmusikforschung (German) (GfPM)
* Gesunde Pflanzen (German) (Gesunde Pflanzen)
* Gewerblicher Rechtsschutz und Urheberrecht (German) (GRUR)
* Gezinstherapie Wereldwijd (Dutch)
* GigaScience
* GIScience & Remote Sensing
* Glass Structures & Engineering
* GLIA
* Global and Planetary Change
* Global Biogeochemical Cycles
* Global Business Perspectives (J of International Network of Bus and Manag)
* Global Change Biology (GCB)
* Global Crime
* Global Discourse
* Global Ecology and Biogeography
* Global Ecology and Conservation
* Global Economics and Management Review
* Global Environmental Change
* Global Finance Journal
* Global Food Security
* Global Heart
* Global Journal of Flexible Systems Management (Glob J Flex Syst Manag)
* Global Public Health
* Global Social Welfare
* Globalisation, Societies and Education
* Globalization and Health
* Glossa
* Glycoconjugate Journal (Glycoconj J)
* GM Crops and Food: Biotechnology in Agriculture and the Food Chain
* GMS Medizin - Bibliothek - Information
* Gold Bulletin (Gold Bull)
* Gondwana Research
* Government Information Quarterly
* GPS Solutions (GPS Solut)
* Graefe's Archive for Clinical and Experimental Ophthalmology (Graefes Arch Clin Exp Ophthalmol)
* Granular Computing
* Granular Matter
* Graphical Models
* Graphs and Combinatorics
* Grasas y Aceites
* Green Chemistry
* Green Energy & Environment
* Green Letters
* Greenhouse Gas Measurement and Management
* Groundwater for Sustainable Development
* Group Decision and Negotiation (Group Decis Negot)
* Group Dynamics: Theory, Research, and Practice
* Growth Hormone & IGF Research
* Grundwasser (German) (Grundwasser)
* Gruppe. Interaktion. Organisation. Zeitschrift für Angewandte Organisationspsychologie (German) (Gruppendyn Organisationsberat)
* GSA Today
* Guide des références pour la rédaction juridique 7e édition (Guide Lluelles, French - Canada) (Guide Lluelles v7)
* Guide des références pour la rédaction juridique 7e édition (Notes complètes) (Guide Lluelles, no Ibid., French - Canada)
* Gut
* Gut Microbes
* Gut Pathogens
* Gynäkologische Endokrinologie (German) (Gynäkologische Endokrinologie)
* Gynecologic and Obstetric Investigation
* Gynecologic Oncology
* Gynecologic Oncology Reports
* Gynecologic Oncology Research and Practice
* Gynecological Surgery (Gynecol Surg)
* Gynécologie Obstétrique et Fertilité
* Gynécologie Obstétrique Fertilité & Sénologie
* Gynecology and Minimally Invasive Therapy
* h bioscience
* Habitat International
* Haematologica
* Hague Journal on the Rule of Law
* Hainan Medical University Journal Publisher (HMUJP)
* Hamburg School of Food Science (diploma, German) (Diplom-LC-UHH)
* HaMiPla - Handchirurgie - Mikrochirurgie - Plastische Chirurgie
* HAND
* Hand Surgery and Rehabilitation
* Handbook of Clinical Neurology
* Handchirurgie Scan
* HardwareX
* Harm Reduction Journal
* Harmful Algae
* Harvard Educational Review
* Harvard reference format 1 (deprecated)
* Haute école de gestion de Genève - ISO-690 (English)
* Haute Ecole pédagogique Fribourg (French) (HEPFR)
* hautnah (German)
* Hawai'i Journal of Medicine & Public Health
* Hawaii International Conference on System Sciences Proceedings (HICSS Proceedings)
* HBRC Journal
* Head & Face Medicine
* Head and Neck Pathology (Head and Neck Pathol)
* Headache
* Health & Justice
* Health & Social Care in the Community
* Health and Human Rights Journal (HHR)
* Health and Place
* Health and Quality of Life Outcomes
* Health and Technology (Health Technol.)
* Health Care Analysis (Health Care Anal)
* Health Care Management Science (Health Care Manag Sci)
* Health Economics
* Health Economics Review
* Health Economics, Policy and Law
* Health Education Research
* Health Information Science and Systems
* Health policy
* Health Policy and Planning
* Health Policy and Technology
* Health Professions Education
* Health Psychology
* Health Psychology and Behavioral Medicine: an Open Access Journal
* Health Psychology Review
* Health Reform Observer - Observatoire des Réformes de Santé
* Health Research Policy and Systems
* Health SA Gesondheid
* Health Services and Delivery Research
* Health Services and Outcomes Research Methodology (Health Serv Outcomes Res Method)
* Health Services Research
* Health Technology Assessment
* Health, Risk & Society
* Healthcare
* Healthcare Management Forum
* Healthcare: The Journal of Delivery Science and Innovation
* Hearing Research
* Heart
* Heart & Lung
* Heart and Vessels (Heart Vessels)
* Heart Asia
* Heart Failure Clinics (HFC)
* Heart Failure Reviews (Heart Fail Rev)
* Heart Rhythm
* Heart, Lung and Circulation
* Heat and Mass Transfer (Heat Mass Transfer)
* HEC Forum
* Heidelberg University - Faculty of Medicine (Universität Heidelberg - Medizinische Fakultät Heidelberg)
* HeilberufeScience (German) (HBScience)
* Helgoland Marine Research (Helgol Mar Res)
* Heliyon
* Hellenic Journal of Cardiology
* Hellenic Journal of Surgery
* Hematology/Oncology and Stem Cell Therapy
* Hematology/Oncology Clinics of North America (HOC)
* Henoch
* Hepatic Oncology
* Hepatobiliary & Pancreatic Diseases International
* Hepatology
* Hepatology International (Hepatol Int)
* Hepatology, Medicine and Policy
* Hereditary Cancer in Clinical Practice
* Hereditas
* Heredity
* Heritage Science
* Hernia
* Herpetologica
* Herz (German)
* Herzschrittmachertherapie + Elektrophysiologie (German) (Herzschrittmachertherapie Elektrophysiologie)
* High Ability Studies
* High Altitude Medicine & Biology
* High Blood Pressure & Cardiovascular Prevention (High Blood Press. Cardiovasc. Prev.)
* High Energy Density Physics
* High Pressure Research
* Higher Education (High Educ)
* Higher-Order and Symbolic Computation (Higher-Order Symb Comput)
* Hiob Ludolf Centre for Ethiopian Studies (HLCES (Hamburg))
* Hiob Ludolf Centre for Ethiopian Studies (long names) (HLCES (Hamburg) long names)
* Hiob Ludolf Centre for Ethiopian Studies (with URL/DOI) (HLCES (Hamburg))
* Hipertensión y Riesgo Vascular (Spanish) (HIPERT)
* Hippocampus
* Hispanic American Historical Review
* Histochemistry and Cell Biology (Histochem Cell Biol)
* Histoire & Mesure (French)
* Histoire@Politique. Politique, culture, société (French)
* Histopathology
* Historia Mathematica
* Historical Social Research (HSR)
* History and Anthropology
* History and Philosophy of the Life Sciences
* History and Theory
* History Australia (RHAH)
* History of Geo- and Space Sciences
* History of Political Economy
* History of Psychology
* History of the Human Sciences
* HIV & AIDS Review
* HKIE Transactions
* HMD Praxis der Wirtschaftsinformatik (German)
* HNO (German) (HNO)
* Hochschule der Medien Stuttgart (German) (HdM Stuttgart)
* Hochschule für Wirtschaft und Recht Berlin (German) (HWR Berlin)
* Hochschule München - Fakultät für Angewandte Sozialwissenschaften (German) (MUAS)
* Hochschule Pforzheim - Fakultät für Wirtschaft und Recht (German)
* Homeopathy
* HOMO
* Hong Kong Journal of Occupational Therapy
* Hong Kong Journal of Ophthalmology
* Hong Kong Journal of Radiology
* Hong Kong Medical Journal
* Hong Kong Physiotherapy Journal
* Hormigón y Acero
* Hormone and Metabolic Research
* Hormone Research in Paediatrics
* Hormones and Behavior
* Hormones and Cancer (HORM CANC)
* Horticulturae
* Horticultural Plant Journal
* Horticulture Research
* Hospital Chronicles (Nosokomiaka Chronica)
* Hospital Pharmacy
* Housing Policy Debate
* Housing, Theory and Society
* Huisarts en Wetenschap
* Human Brain Mapping
* Human Cell
* Human Development
* Human Gene Therapy (HGT)
* Human Gene Therapy Clinical Development
* Human Gene Therapy Methods
* Human Genetics (Hum Genet)
* Human Genomics
* Human Heredity
* Human Immunology
* Human Microbiome Journal
* Human Molecular Genetics
* Human Movement Science
* Human Mutation
* Human Nature (Hum Nat)
* Human Pathology
* Human Pathology: Case Reports
* Human Relations
* Human Reproduction
* Human Reproduction Update
* Human Resource Development International
* Human Resource Management Journal
* Human Resource Management Review
* Human Resources for Health
* Human Studies (Hum Stud)
* Human Vaccines & Immunotherapeutics
* Human-centric Computing and Information Sciences
* Human-Wildlife Interactions
* Humanities
* Humboldt State University - Environmental Resources Engineering (hsu)
* Husserl Studies (Husserl Stud)
* Hydrobiologia
* Hydrogeology Journal (Hydrogeol J)
* Hydrological Processes
* Hydrological Sciences Journal
* Hydrology
* Hydrology and Earth System Sciences
* Hydrology and Earth System Sciences Discussions
* Hydrometallurgy
* Hyperfine Interactions (Hyperfine Interact)
* Hypertension Research
* Hypotheses in the Life Sciences (HyLS)
* I.B. Tauris (note)
* IATSS Research
* IBM Journal of Research and Development
* IBMS BoneKEy
* IBRO Reports
* Ibsen Studies
* Icarus
* ICES Journal of Marine Science
* ICT Express
* IDCases
* Időjárás - Quarterly Journal of the Hungarian Meteorological Service (Időjárás)
* IE Comunicaciones (IE Com)
* IEEE
* IEEE (with URL)
* IEEE Access
* IEEE Aerospace and Electronic Systems Magazine
* IEEE Annals of the History of Computing
* IEEE Antennas and Propagation Magazine
* IEEE Antennas and Wireless Propagation Letters
* IEEE Circuits and Systems Magazine
* IEEE Communications Letters
* IEEE Communications Magazine
* IEEE Communications Surveys & Tutorials
* IEEE Computational Intelligence Magazine
* IEEE Computer Graphics and Applications
* IEEE Consumer Electronics Magazine
* IEEE Control Systems
* IEEE Design & Test
* IEEE Electrical Insulation Magazine
* IEEE Electrification Magazine
* IEEE Electromagnetic Compatibility Magazine
* IEEE Electron Device Letters
* IEEE Embedded Systems Letters
* IEEE Engineering Management Review
* IEEE Geoscience and Remote Sensing Letters
* IEEE Geoscience and Remote Sensing Magazine
* IEEE Industrial Electronics Magazine
* IEEE Industry Applications Magazine
* IEEE Instrumentation & Measurement Magazine
* IEEE Intelligent Systems
* IEEE Intelligent Transportation Systems Magazine
* IEEE Internet Computing
* IEEE Internet of Things Journal
* IEEE Journal of Biomedical and Health Informatics
* IEEE Journal of Emerging and Selected Topics in Power Electronics
* IEEE Journal of Oceanic Engineering
* IEEE Journal of Photovoltaics
* IEEE Journal of Quantum Electronics
* IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing
* IEEE Journal of Selected Topics in Quantum Electronics
* IEEE Journal of Selected Topics in Signal Processing
* IEEE Journal of Solid-State Circuits
* IEEE Journal of the Electron Devices Society
* IEEE Journal of Translational Engineering in Health and Medicine
* IEEE Journal on Emerging and Selected Topics in Circuits and Systems
* IEEE Journal on Selected Areas in Communications
* IEEE Latin America Transactions
* IEEE Magnetics Letters
* IEEE Micro
* IEEE Microwave and Wireless Components Letters
* IEEE Microwave Magazine
* IEEE MultiMedia
* IEEE Nanotechnology Magazine
* IEEE Network
* IEEE Pervasive Computing
* IEEE Photonics Journal
* IEEE Photonics Technology Letters
* IEEE Potentials
* IEEE Power and Energy Magazine
* IEEE Pulse
* IEEE Reviews in Biomedical Engineering
* IEEE Revista Iberoamericana de Tecnologias del Aprendizaje
* IEEE Robotics & Automation Magazine
* IEEE Security & Privacy
* IEEE Sensors Journal
* IEEE Signal Processing Letters
* IEEE Signal Processing Magazine
* IEEE Software
* IEEE Solid-State Circuits Magazine
* IEEE Spectrum
* IEEE Systems Journal
* IEEE Technology and Society Magazine
* IEEE Transactions on Aerospace and Electronic Systems
* IEEE Transactions on Affective Computing
* IEEE Transactions on Antennas and Propagation
* IEEE Transactions on Applied Superconductivity
* IEEE Transactions on Automatic Control
* IEEE Transactions on Automation Science and Engineering
* IEEE Transactions on Autonomous Mental Development
* IEEE Transactions on Biomedical Circuits and Systems
* IEEE Transactions on Biomedical Engineering
* IEEE Transactions on Broadcasting
* IEEE Transactions on Circuits and Systems for Video Technology
* IEEE Transactions on Circuits and Systems I: Regular Papers
* IEEE Transactions on Circuits and Systems II: Express Briefs
* IEEE Transactions on Cloud Computing
* IEEE Transactions on Communications
* IEEE Transactions on Components, Packaging and Manufacturing Technology
* IEEE Transactions on Computational Intelligence and AI in Games
* IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems
* IEEE Transactions on Computers
* IEEE Transactions on Consumer Electronics
* IEEE Transactions on Control Systems Technology
* IEEE Transactions on Cybernetics
* IEEE Transactions on Dependable and Secure Computing
* IEEE Transactions on Device and Materials Reliability
* IEEE Transactions on Dielectrics and Electrical Insulation
* IEEE Transactions on Education
* IEEE Transactions on Electromagnetic Compatibility
* IEEE Transactions on Electron Devices
* IEEE Transactions on Emerging Topics in Computing
* IEEE Transactions on Energy Conversion
* IEEE Transactions on Engineering Management
* IEEE Transactions on Evolutionary Computation
* IEEE Transactions on Fuzzy Systems
* IEEE Transactions on Geoscience and Remote Sensing
* IEEE Transactions on Haptics
* IEEE Transactions on Human-Machine Systems
* IEEE Transactions on Image Processing
* IEEE Transactions on Industrial Electronics
* IEEE Transactions on Industrial Informatics
* IEEE Transactions on Industry Applications
* IEEE Transactions on Information Forensics and Security
* IEEE Transactions on Information Theory
* IEEE Transactions on Instrumentation and Measurement
* IEEE Transactions on Intelligent Transportation Systems
* IEEE Transactions on Knowledge and Data Engineering
* IEEE Transactions on Learning Technologies
* IEEE Transactions on Magnetics
* IEEE Transactions on Medical Imaging
* IEEE Transactions on Microwave Theory and Techniques
* IEEE Transactions on Mobile Computing
* IEEE Transactions on Multimedia
* IEEE Transactions on NanoBioscience
* IEEE Transactions on Nanotechnology
* IEEE Transactions on Network and Service Management
* IEEE Transactions on Neural Networks and Learning Systems
* IEEE Transactions on Neural Systems and Rehabilitation Engineering
* IEEE Transactions on Nuclear Science
* IEEE Transactions on Parallel and Distributed Systems
* IEEE Transactions on Pattern Analysis and Machine Intelligence
* IEEE Transactions on Plasma Science
* IEEE Transactions on Power Delivery
* IEEE Transactions on Power Electronics
* IEEE Transactions on Power Systems
* IEEE Transactions on Professional Communication
* IEEE Transactions on Reliability
* IEEE Transactions on Robotics
* IEEE Transactions on Semiconductor Manufacturing
* IEEE Transactions on Services Computing
* IEEE Transactions on Signal Processing
* IEEE Transactions on Smart Grid
* IEEE Transactions on Software Engineering
* IEEE Transactions on Sustainable Energy
* IEEE Transactions on Systems, Man, and Cybernetics: Systems
* IEEE Transactions on Terahertz Science and Technology
* IEEE Transactions on Ultrasonics, Ferroelectrics and Frequency Control
* IEEE Transactions on Vehicular Technology
* IEEE Transactions on Very Large Scale Integration Systems
* IEEE Transactions on Visualization and Computer Graphics
* IEEE Transactions on Wireless Communications
* IEEE Vehicular Technology Magazine
* IEEE Wireless Communications
* IEEE Wireless Communications Letters
* IEEE Women in Engineering Magazine
* IEEE/ACM Transactions on Audio, Speech, and Language Processing
* IEEE/ACM Transactions on Computational Biology and Bioinformatics
* IEEE/ACM Transactions on Networking
* IEEE/ASME Transactions on Mechatronics
* IEEE/OSA Journal of Optical Communications and Networking
* IEICE Transactions on Communications
* IEICE Transactions on Electronics
* IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences
* IEICE Transactions on Information and Systems
* IERI Procedia
* IET Biometrics
* IET Circuits, Devices & Systems
* IET Communications
* IET Computer Vision
* IET Computers & Digital Techniques
* IET Control Theory & Applications
* IET Electric Power Applications
* IET Electrical Systems in Transportation
* IET Generation, Transmission & Distribution
* IET Image Processing
* IET Information Security
* IET Intelligent Transport Systems
* IET Micro & Nano Letters
* IET Microwaves, Antennas & Propagation
* IET Nanobiotechnology
* IET Networks
* IET Optoelectronics
* IET Power Electronics
* IET Radar, Sonar & Navigation
* IET Renewable Power Generation
* IET Science, Measurement & Technology
* IET Signal Processing
* IET Software
* IET Synthetic Biology
* IET Systems Biology
* IET Wireless Sensor Systems
* IFAC Journal of Systems and Control
* iForest
* Igaku Toshokan (Japanese)
* IHJ Cardiovascular Case Reports
* IICA-CATIE (Spanish)
* IIMB Management Review
* IJC Heart & Vasculature
* IJC Metabolic & Endocrine
* Im Gespräch - Hefte der Martin Buber-Gesellschaft (German) (Im Gespräch)
* IMA Journal of Applied Mathematics
* IMA Journal of Management Mathematics
* IMA Journal of Mathematical Control and Information
* IMA Journal of Numerical Analysis
* Image and Vision Computing
* Imagerie de la Femme
* Imaging in Medicine
* Immigrants & Minorities
* Immunity
* Immunity & Ageing
* Immuno-analyse et biologie spécialisée
* Immunobiology
* Immunogenetics
* Immunologic Research (Immunol Res)
* Immunological Reviews
* Immunology & Cell Biology
* Immunology Letters
* Immunomics
* Immunotherapy
* Impact Assessment and Project Appraisal
* Imperial College London - Harvard
* Imperial College London - Vancouver
* Implementation Science
* In Analysis
* In Practice
* In Silico Cell and Tissue Science
* In Silico Pharmacology
* In Vitro Cellular & Developmental Biology - Animal
* In Vitro Cellular & Developmental Biology - Plant
* Indian Dermatology Online Journal (IDOJ)
* Indian Geotechnical Journal (Indian Geotech J)
* Indian Heart Journal
* Indian Journal of Anaesthesia
* Indian Journal of Cancer
* Indian Journal of Clinical Biochemistry (Ind J Clin Biochem)
* Indian Journal of Critical Care Medicine
* Indian Journal of Dentistry
* Indian Journal of Dermatology
* Indian Journal of Dermatology, Venereology and Leprology
* Indian Journal of Gastroenterology (Indian J Gastroenterol)
* Indian Journal of Gynecologic Oncology
* Indian Journal of Hematology and Blood Transfusion (Indian J Hematol Blood Transfus)
* Indian Journal of Human Genetics
* Indian Journal of Medical Informatics
* Indian Journal of Medical Microbiology
* Indian Journal of Medical Research
* Indian Journal of Medical Sciences
* Indian Journal of Medical Specialities
* Indian Journal of Microbiology (Indian J Microbiol)
* Indian Journal of Occupational & Environmental Medicine
* Indian Journal of Ophthalmology
* Indian Journal of Otolaryngology and Head & Neck Surgery (Indian J Otolaryngol Head Neck Surg)
* Indian Journal of Pharmacology
* Indian Journal of Physics (IJP)
* Indian Journal of Plant Physiology
* Indian Journal of Plastic Surgery
* Indian Journal of Rheumatology
* Indian Journal of Surgery (Indian J Surg)
* Indian Journal of Surgical Oncology (Indian J Surg Oncol)
* Indian Journal of Thoracic and Cardiovascular Surgery (Indian J Thorac Cardiovasc Surg)
* Indian Journal of Traditional Knowledge (IJTK)
* Indian Journal of Transplantation
* Indian Journal of Tuberculosis
* Indian Journal of Urology
* Indian Pacing and Electrophysiology Journal
* INDIANA
* Indoor Air
* Industrial & Engineering Chemistry Research (Ind. Eng. Chem. Res.)
* Industrial Crops & Products
* Industrial Marketing Management
* Infant Behavior and Development
* Infant Observation
* Infectio (Spanish) (INFECT)
* Infection
* Infection and Immunity (IAI)
* Infection Control & Hospital Epidemiology
* Infection, Disease & Health
* Infection, Genetics and Evolution
* Infectious Agents and Cancer
* Infectious Disease Clinics of North America (IDC)
* Infectious Disease Modelling
* Infectious Diseases and Therapy (Infect Dis Ther)
* Infectious Diseases of Poverty
* Inflammation
* Inflammation Research (Inflamm. Res.)
* Inflammatory Bowel Diseases
* Inflammopharmacology (Inflammopharmacol)
* Influenza and Other Respiratory Viruses
* infoclio.ch (German - Switzerland)
* infoclio.ch (petites majuscules, French)
* infoclio.ch (sans majuscules, French)
* Informatics
* Informatics in Medicine Unlocked
* Informatik-Spektrum (German) (Informatik Spektrum)
* Information
* Information & Communications Technology Law
* Information & Management
* Information and Computation
* Information and Organization
* Information and Software Technology
* Information Economics and Policy
* Information Fusion
* Information Processing and Management
* Information Processing in Agriculture
* Information Processing Letters
* Information Retrieval Journal (Inf Retrieval)
* Information Sciences
* Information Security Technical Report
* Information Systems
* Information Systems and e-Business Management (Inf Syst E-Bus Manage)
* Information Systems Frontiers (Inf Syst Front)
* Information Systems Journal (ISJ)
* Information Systems Research
* Information Technology & Tourism
* Information Technology and Management (Inf Technol Manag)
* Information Technology for Development
* Information, Communication & Society
* Informationspraxis (German)
* INFORMS Journal on Computing
* INFORMS Transactions on Education
* Infrared Physics and Technology
* Infrastructure Complexity
* Infrastructures
* Ingeniería Agrícola (Spanish) (IAgric)
* Injury
* Injury Epidemiology
* Injury Extra
* Injury Prevention
* Innovation and Development
* Innovation in Language Learning and Teaching
* Innovation: The European Journal of Social Science Research
* Innovations in Education and Teaching International
* Innovations in Systems and Software Engineering (Innovations Syst Softw Eng)
* Innovative Food Science and Emerging Technologies
* Innovative Higher Education (Innov High Educ)
* Innovative Infrastructure Solutions
* Inorganic Chemistry (Inorg. Chem.)
* Inorganic Chemistry Communications
* Inorganic Chemistry Frontiers
* Inorganica Chimica Acta
* Inorganics
* Insect Biochemistry and Molecular Biology
* Insectes Sociaux
* Insects
* Insights into Imaging (Insights Imaging)
* Insolvency Law Journal (Insolv LJ)
* Institut für Praxisforschung - Harvard (Bahr & Frackmann) (German)
* Institut national de la recherche scientifique - Sciences sociales (author-date, French)
* Institut national de santé publique du Québec - NAPP (French - Canada) (INSPQ-NAPP)
* Institut national de santé publique du Québec - TOPO (French - Canada) (INSPQ-TOPO)
* Institut Teknologi Bandung - Tesis Magister (ITB - Tesis/Disertasi)
* Institute for Operations Research and the Management Sciences (INFORMS)
* Institute of Mathematical Statistics journals (IMS)
* Institute of Mathematics and its Applications (IMA)
* Institute of Physics - Harvard (IOP)
* Institute of Physics (numeric) (IOP)
* Instituto de Pesquisa Econômica Aplicada - ABNT (Portuguese - Brazil) (ABNT-IPEA)
* Instituto de Pesquisas Tecnológicas (Portuguese - Brazil) (IPT)
* Instituto Superior de Teología de las Islas Canarias (Spanish) (Istic)
* Instructional Science (Instr Sci)
* Instruments
* Insurance Mathematics and Economics
* Integral Equations and Operator Theory (Integr. Equ. Oper. Theory)
* Integral Transforms and Special Functions
* Integrated Research Advances
* Integrated Science Publishing journals (ISP)
* Integrating Materials and Manufacturing Innovation
* Integration
* Integrative & Comparative Biology
* Integrative Biology
* Integrative Medicine International
* Integrative Medicine Research
* Integrative Psychological and Behavioral Science (Integr. psych. behav.)
* Intellectual Economics
* Intelligence
* Intelligent Buildings International
* Intelligent Industrial Systems
* Intelligent Service Robotics (Intel Serv Robotics)
* Intensive & Critical Care Nursing
* Intensive Care Medicine (Intensive Care Med)
* Intensive Care Medicine Experimental
* Intensivmedizin up2date
* Inter-Asia Cultural Studies
* Inter-Research Science Center (IRSC)
* INTER: Romanian Review for Theological and Religious Studies
* Interacting with Computers
* Interaction Design & Architecture(s) (IxD&A)
* Interactive Learning Environments
* Interbloc
* Interchange
* Intercultural Education
* Interdisciplinary Neurosurgery: Advanced Techniques and Case Management
* Interdisciplinary Sciences: Computational Life Sciences
* Interdisziplinäre Zeitschrift für Technologie und Lernen (German) (iTeL)
* Interface Focus
* Interfaces
* Intermetallics
* Internal and Emergency Medicine (Intern Emerg Med)
* International Advances in Economic Research (Int Adv Econ Res)
* International Affairs Forum
* International Aquatic Research
* International Archives of Allergy and Immunology
* International Archives of Medicine (Int Arch Med)
* International Archives of Occupational and Environmental Health (Int Arch Occup Environ Health)
* International Archives of Science and Technology
* International Atomic Energy Agency (IAEA)
* International Biodeterioration & Biodegradation
* International Brazilian Journal Of Urology (International Braz J Urol)
* International Breastfeeding Journal
* International Business Review
* International Cancer Conference Journal (Int Canc Conf J)
* International Communication of Chinese Culture
* International Communications in Heat and Mass Transfer
* International Comparative Jurisprudence
* International Conference on Human-Computer Interaction (HCII)
* International Conference on Information Systems Development (ISD Conference)
* International Critical Thought
* International Dairy Journal
* International Development Policy
* International Economic Journal
* International Economics
* International Economics and Economic Policy (Int Econ Econ Policy)
* International Emergency Nursing
* International Energy Agency - Organisation for Economic Co-operation and Development (IEA-OECD)
* International Entrepreneurship and Management Journal (Int Entrep Manag J)
* International Environmental Agreements: Politics, Law and Economics (Int Environ Agreements)
* International Gambling Studies
* International Immunopharmacology
* International Information and Library Review
* International Journal for Academic Development
* International Journal for Educational and Vocational Guidance (Int J Educ Vocat Guidance)
* International Journal for Educational Integrity
* International Journal for Equity in Health
* International Journal for Ion Mobility Spectrometry (Int. J. Ion Mobil. Spec.)
* International Journal for Numerical Methods in Biomedical Engineering
* International Journal for Parasitology
* International Journal for Parasitology: Drugs and Drug Resistance
* International Journal for Parasitology: Parasites and Wildlife
* International Journal for Philosophy of Religion (Int J Philos Relig)
* International Journal for the Advancement of Counselling (Int J Adv Counselling)
* International Journal for the Semiotics of Law - Revue internationale de Sémiotique juridique (Int J Semiot Law)
* International Journal of Accounting
* International Journal of Accounting Information Systems
* International Journal of Adhesion and Adhesives
* International Journal of Adipose Tissue and Stem Cells
* International Journal of Adolescence and Youth
* International Journal of Advanced Nuclear Reactor Design and Technology
* International Journal of Advanced Structural Engineering
* International Journal of Advances in Engineering Sciences and Applied Mathematics (Int J Adv Eng Sci Appl Math)
* International Journal of Africa Nursing Sciences
* International Journal of Ambient Energy
* International Journal of Antimicrobial Agents
* International Journal of Applied and Computational Mathematics
* International Journal of Applied Earth Observations and Geoinformation
* International Journal of Approximate Reasoning
* International Journal of Art Therapy
* International Journal of Artificial Intelligence in Education
* International Journal of Audiology
* International Journal of Behavioral Medicine (Int.J. Behav. Med.)
* International Journal of Behavioral Nutrition and Physical Activity
* International Journal of Bilingual Education and Bilingualism
* International Journal of Biochemistry and Cell Biology
* International Journal of Biodiversity Science, Ecosystem Services & Management
* International Journal of Biological Macromolecules
* International Journal of Biological Sciences
* International Journal of Biometeorology (Int J Biometeorol)
* International Journal of Bipolar Disorders
* International Journal of Cancer
* International Journal of Cardiology
* International Journal of Chemical and Analytical Science
* International Journal of Child Care and Education Policy
* International Journal of Child-Computer Interaction
* International Journal of Children's Spirituality
* International Journal of Circuit Theory and Applications
* International Journal of Climatology
* International Journal of Clinical and Health Psychology
* International Journal of Clinical Oncology (Int J Clin Oncol)
* International Journal of Clinical Pharmacy (Int J Clin Pharm)
* International Journal of Clinical Rheumatology
* International Journal of Coal Geology
* International Journal of Coal Science & Technology
* International Journal of Colorectal Disease (Int J Colorectal Dis)
* International Journal of Communication
* International Journal of Comparative and Applied Criminal Justice
* International Journal of Computational Fluid Dynamics
* International Journal of Computer Assisted Radiology and Surgery (Int J CARS)
* International Journal of Computer Vision (Int J Comput Vis)
* International Journal of Computer-Supported Collaborative Learning (Computer Supported Learning)
* International Journal of Concrete Structures and Materials
* International Journal of Control
* International Journal of Cross Cultural Management
* International Journal of Culture and Mental Health
* International Journal of Data Science and Analytics
* International Journal of Dental Science and Research
* International Journal of Design
* International Journal of Design Creativity and Innovation
* International Journal of Developmental Neuroscience
* International Journal of Dharma Studies
* International Journal of Diabetes in Developing Countries (Int J Diabetes Dev Ctries)
* International Journal of Diabetes Mellitus
* International Journal of Digital Earth
* International Journal of Disability, Development and Education
* International Journal of Disaster Risk Reduction
* International Journal of Disaster Risk Science
* International Journal of Drug Policy
* International Journal of Dynamics and Control
* International Journal of Early Childhood (IJEC)
* International Journal of Early Years Education
* International Journal of Earth Sciences (Int J Earth Sci (Geol Rundsch))
* International Journal of Education and Research
* International Journal of Educational Development
* International Journal of Educational Research
* International Journal of Educational Technology in Higher Education
* International Journal of Electrical Power and Energy Systems
* International Journal of Electronic Commerce
* International Journal of Electronics
* International Journal of Electronics Letters
* International Journal of Emergency Medicine
* International Journal of Endocrine Oncology
* International Journal of Energy and Environmental Engineering
* International Journal of Engineering Science
* International Journal of Environmental Health Research
* International Journal of Environmental Research and Public Health
* International Journal of Environmental Science and Technology (Int. J. Environ. Sci. Technol.)
* International Journal of Epidemiology
* International Journal of Epilepsy
* International Journal of Ethics Education
* International Journal of Exercise Science (IJES)
* International Journal of Fashion Design, Technology and Education
* International Journal of Fatigue
* International Journal of Financial Studies
* International Journal of Food Contamination
* International Journal of Food Microbiology
* International Journal of Food Science & Technology
* International Journal of Forecasting
* International Journal of Forest Engineering
* International Journal of Fracture (Int J Fract)
* International Journal of Fuzzy Systems
* International Journal of Game Theory (Int J Game Theory)
* International Journal of Gastronomy and Food Science
* International Journal of General Systems
* International Journal of Geo-Engineering
* International Journal of Geomechanics
* International Journal of Geosynthetics and Ground Engineering
* International Journal of Geriatric Psychiatry (JGP)
* International Journal of Gerontology
* International Journal of Greenhouse Gas Control
* International Journal of Gynecology and Obstetrics
* International Journal of Health Economics and Management
* International Journal of Health Geographics
* International Journal of Health Promotion and Education
* International Journal of Heat and Fluid Flow
* International Journal of Heat and Mass Transfer
* International Journal of Hematologic Oncology
* International Journal of Hematology (Int J Hematol)
* International Journal of Hospitality Management
* International Journal of Housing Policy
* International Journal of Human - Computer Studies
* International Journal of Humanoid Robotics (IJHR)
* International Journal of Hydrogen Energy
* International Journal of Hygiene and Environmental Health
* International Journal of Impact Engineering
* International Journal of Implant Dentistry
* International Journal of Impotence Research
* International Journal of Inclusive Education
* International Journal of Industrial Chemistry
* International Journal of Industrial Ergonomics
* International Journal of Industrial Organization
* International Journal of Infectious Diseases
* International Journal of Information Management
* International Journal of Information Security (Int. J. Inf. Secur.)
* International Journal of Injury Control and Safety Promotion
* International Journal of Innovation Studies
* International Journal of Intelligent Transportation Systems Research (Int. J. ITS Res.)
* International Journal of Intercultural Relations
* International Journal of Jungian Studies
* International Journal of Language & Communication Disorders (IJLCD)
* International Journal of Law and Psychiatry
* International Journal of Law, Crime and Justice
* International Journal of Leadership in Education
* International Journal of Legal Medicine (Int J Legal Med)
* International Journal of Lexicography (IJL)
* International Journal of Lifelong Education
* International Journal of Lightweight Materials and Manufacture
* International Journal of Logistics Research and Applications
* International Journal of Machine Learning and Cybernetics (Int. J. Mach. Learn. & Cyber.)
* International Journal of Machine Tools and Manufacture
* International Journal of Management Reviews (IJMR)
* International Journal of Management Science and Engineering Management
* International Journal of Marine Energy
* International Journal of Mass Spectrometry
* International Journal of Material Forming (Int J Mater Form)
* International Journal of Mathematical Education in Science and Technology
* International Journal of Mechanical and Materials Engineering
* International Journal of Mechanical Sciences
* International Journal of Mechanics and Materials in Design (Int J Mech Mater Des)
* International Journal of Medical Informatics
* International Journal of Medical Microbiology
* International Journal of Medical Sciences
* International Journal of Mental Health and Addiction (Int J Ment Health Addiction)
* International Journal of Mental Health Promotion
* International Journal of Mental Health Systems
* International Journal of Mineral Processing
* International Journal of Mining Science and Technology
* International Journal of Molecular Medicine
* International Journal of Molecular Sciences
* International Journal of Multilingualism
* International Journal of Multimedia Information Retrieval (Int J Multimed Info Retr)
* International Journal of Multiphase Flow
* International Journal of Mycobacteriology
* International Journal of Naval Architecture and Ocean Engineering
* International Journal of Neonatal Screening
* International Journal of Non-Linear Mechanics
* International Journal of Nuclear Security
* International Journal of Nursing Practice
* International Journal of Nursing Sciences
* International Journal of Nursing Studies
* International Journal of Obesity
* International Journal of Obesity Supplements
* International Journal of Obstetric Anesthesia (IJOA)
* International Journal of Occupational Medicine and Environmental Health
* International Journal of Odonatology
* International Journal of Oncology
* International Journal of Oral and Maxillofacial Surgery (IJOM)
* International Journal of Oral Science
* International Journal of Orthopaedic and Trauma Nursing
* International Journal of Osteoarchaeology
* International Journal of Osteopathic Medicine
* International Journal of Paleopathology
* International Journal of Parallel Programming (Int J Parallel Prog)
* International Journal of Pavement Engineering
* International Journal of Pavement Research and Technology
* International Journal of Pediatric Endocrinology
* International Journal of Pediatric Otorhinolaryngology
* International Journal of Pediatric Otorhinolaryngology Case Reports
* International Journal of Pediatric Otorhinolaryngology Extra
* International Journal of Pediatrics and Adolescent Medicine
* International Journal of Peptide Research and Therapeutics (Int J Pept Res Ther)
* International Journal of Pest Management
* International Journal of Pharmaceutics
* International Journal of Pharmacy Practice
* International Journal of Philosophy and Theology
* International Journal of Plant Sciences (IJPS)
* International Journal of Plasticity
* International Journal of Plastics Technology (Int J Plast Technol)
* International Journal of Play
* International Journal of Play Therapy
* International Journal of Politics, Culture, and Society (Int J Polit Cult Soc)
* International Journal of Polymeric Materials and Polymeric Biomaterials
* International Journal of Pressure Vessels and Piping
* International Journal of Primatology (Int J Primatol)
* International Journal of Production Economics
* International Journal of Production Research
* International Journal of Project Management
* International Journal of Psychology
* International Journal of Psychophysiology
* International Journal of Public Health (Int J Public Health)
* International Journal of Qualitative Studies in Education
* International Journal of Quality Innovation
* International Journal of Quantum Chemistry
* International Journal of Radiation Biology
* International Journal of Radiation Oncology, Biology, Physics
* International Journal of Rail Transportation
* International Journal of Recycling of Organic Waste in Agriculture
* International Journal of Refractory Metals and Hard Materials
* International Journal of Refrigeration
* International Journal of Remote Sensing
* International Journal of Research & Method in Education
* International Journal of Research in Marketing
* International Journal of Research in Undergraduate Mathematics Education
* International Journal of Retina and Vitreous
* International Journal of Rock Mechanics and Mining Sciences
* International Journal of Science and Mathematics Education (Int J of Sci and Math Educ)
* International Journal of Science Education
* International Journal of Science Education, Part B
* International Journal of Sediment Research
* International Journal of Simulation Modelling
* International Journal of Social Research Methodology
* International Journal of Social Robotics (Int J of Soc Robotics)
* International Journal of Solids and Structures
* International Journal of Spatial Data Infrastructures Research (IJSDIR)
* International Journal of Speech Technology (Int J Speech Technol)
* International Journal of Spine Surgery
* International Journal of Sport and Exercise Psychology
* International Journal of Sport Medicine
* International Journal of STD & AIDS
* International Journal of STEM Education
* international journal of stomatology & occlusion medicine (J. Stomat. Occ. Med.)
* International Journal of Stress Management
* International Journal of Surgery
* International Journal of Surgery Case Reports
* International Journal of Surgery Open
* International Journal of Surgery Protocols
* International Journal of Sustainable Built Environment
* International Journal of Sustainable Development & World Ecology
* International Journal of Sustainable Energy
* International Journal of System Assurance Engineering and Management (Int J Syst Assur Eng Manag)
* International Journal of Systematic and Evolutionary Microbiology
* International Journal of Technology and Design Education (Int J Technol Des Educ)
* International Journal of the Cardiovascular Academy
* International Journal of the Economics of Business
* International Journal of Theoretical Physics (Int J Theor Phys)
* International Journal of Thermal Sciences
* International Journal of Thermophysics (Int J Thermophys)
* International Journal of Transportation Science and Technology
* International Journal of Turbomachinery, Propulsion and Power
* International Journal of Urban and Regional Research (IJURR)
* International Journal of Urban Sciences
* International Journal of Urban Sustainable Development
* International Journal of Veterinary Science and Medicine
* International Journal of Water Resources Development
* International Journal of Wildland Fire
* International Journal of Women's Dermatology
* International Journal on Digital Libraries (Int J Digit Libr)
* International Journal on Document Analysis and Recognition (IJDAR)
* International Journal on Interactive Design and Manufacturing (Int J Interact Des Manuf)
* International Journal on Software Tools for Technology Transfer (Int J Softw Tools Technol Transfer)
* International Labour Organization
* International Microbiology
* International Nano Letters
* International Ophthalmology (Int Ophthalmol)
* International Organization
* International Orthodontics
* International Orthopaedics (International Orthopaedics (SICOT))
* International Perspectives in Psychology: Research, Practice, Consultation
* International Pig Veterinary Society Congress Proceedings (IPVS)
* International Political Sociology
* International Research in Geographical and Environmental Education
* International Review of Applied Economics
* International Review of Economics (Int Rev Econ)
* International Review of Economics and Finance
* International Review of Economics Education
* International Review of Education (Int Rev Educ)
* International Review of Financial Analysis
* International Review of Law & Economics
* International Review of Law, Computers & Technology
* International Review of Sport and Exercise Psychology
* International Review of the Red Cross
* International Review on Public and Nonprofit Marketing (Int Rev Public Nonprofit Mark)
* International Soil and Water Conservation Research
* International Strategic Management Review
* International Studies Association
* International Studies in Catholic Education
* International Studies in Sociology of Education
* International Studies in the Philosophy of Science
* International Studies Perspectives
* International Studies Quarterly
* International Studies Review
* International Surgery
* International Tax and Public Finance (Int Tax Public Finance)
* International Transactions on Systems Science and Applications
* International Union of Crystallography journals (IUCr)
* International Urogynecology Journal (Int Urogynecol J)
* International Urology and Nephrology (Int Urol Nephrol)
* Internet Interventions
* Internet of Things
* Interventional Cardiology
* Interventional Neurology
* Intervirology
* IntraVital
* Intrinsically Disordered Proteins
* Inventiones mathematicae (Invent. math.)
* Inventions
* Inverse Problems
* Inverse Problems in Science and Engineering
* Invertebrate Biology
* Invertebrate Neuroscience (Invert Neurosci)
* Invertebrate Systematics
* Investigaciones de Historia Económica
* Investigational New Drugs (Invest New Drugs)
* Investigative Genetics
* Investigative Ophthalmology & Visual Science
* Investigative Radiology
* InVisu
* IOK - Informationen aus Orthodontie & Kieferorthopädie
* Ionics
* IOP Conference Series: Earth and Environmental Science
* IOP Conference Series: Materials Science and Engineering
* IOS Press (books)
* Iranian Journal of Allergy, Asthma, and Immunology
* Iranian Journal of Basic Medical Sciences (IJBMS)
* Iranian Journal of Pharmaceutical Research (IJPR)
* Iranian Polymer Journal (Iran Polym J)
* IRBM
* IRBM News
* Irish Educational Studies
* Irish Historical Studies (IHS)
* Irish Journal of Medical Science (Ir J Med Sci)
* Irish Journal of Psychological Medicine
* Irish Studies Review
* Irish Veterinary Journal
* Irrigation Science (Irrig Sci)
* ISA Transactions
* Isabella Stewart Gardner Museum
* iScience
* Islam and Christian-Muslim Relations
* Islets
* ISNAD (IAS)
* ISO-690 (author-date, Czech)
* ISO-690 (author-date, English)
* ISO-690 (author-date, French)
* ISO-690 (author-date, no abstract, French)
* ISO-690 (author-date, Slovak)
* ISO-690 (author-date, Spanish)
* ISO-690 (full note, Slovak)
* ISO-690 (note, no abstract, French)
* ISO-690 (note, without bibliography, Czech)
* ISO-690 (numeric, brackets, Czech)
* ISO-690 (numeric, English)
* ISO-690 (numeric, French)
* ISO-690 (numeric, Lithuanian)
* ISO-690 (numeric, parentheses, Czech)
* ISO-690 (numeric, Slovak)
* Isotopes in Environmental and Health Studies
* ISPRS International Journal of Geo-Information
* ISPRS Journal of Photogrammetry and Remote Sensing
* Israel Journal of Ecology & Evolution
* Israel Journal of Health Policy Research
* Israel Journal of Plant Sciences
* Israel Medical Association Journal (IMAJ)
* Issues in Environmental Science and Technology
* IT Professional
* Italian Economic Journal
* Italian Journal of Agronomy (IJA)
* Italian Journal of Pediatrics
* Ithaque (French - Canada)
* IUCrJ
* Ius Ecclesiae (IusEcc)
* IZA Journal of European Labor Studies
* IZA Journal of Labor & Development
* IZA Journal of Labor Economics
* IZA Journal of Labor Policy
* IZA Journal of Migration
* Izvestiya: Mathematics
* JA Clinical Reports
* JAAD Case Reports
* JAAPA (Journal of the American Academy of Physician Assistants) (JAAPA)
* JACC: Cardiovascular Imaging (JCMG)
* Jahrbuch der Österreichischen Byzantinischen Gesellschaft
* Jahrbuch für evangelikale Theologie (German) (JETh)
* Jahresbericht der Deutschen Mathematiker-Vereinigung (Jahresber. Dtsch. Math. Ver.)
* JAK-STAT
* JAMA (The Journal of the American Medical Association) (JAMA)
* JAMA Dermatology
* JAMIA
* Japan & The World Economy
* Japan Journal of Industrial and Applied Mathematics (Japan J. Indust. Appl. Math.)
* Japanese Dental Science Review
* Japanese Journal of Ophthalmology (Jpn J Ophthalmol)
* Japanese Journal of Radiology (Jpn J Radiol)
* Javnost - The Public
* JBIC Journal of Biological Inorganic Chemistry (J Biol Inorg Chem)
* JCC Open
* Jeugdbeleid (Dutch)
* JGZ Tijdschrift voor jeugdgezondheidszorg (Dutch)
* JMM Case Reports
* JMV-Journal de Médecine Vasculaire
* Joint Bone Spine
* JOM
* Jornal de Pediatria
* Joule
* Journal Club AINS
* Journal d'imagerie diagnostique et interventionnelle
* Journal de Chirurgie Viscérale
* Journal de Gynécologie Obstétrique et Biologie de la Reproduction
* Journal de mathématiques pures et appliquées
* Journal de Mycologie Médicale
* Journal de pédiatrie et de puériculture
* Journal de Radiologie diagnostique et interventionnelle
* Journal de réadaptation médicale
* Journal de Thérapie Comportementale et Cognitive
* Journal de Traumatologie du Sport
* Journal des Anti-infectieux
* Journal des Maladies Vasculaires
* Journal Européen des Urgences et de Réanimation
* Journal for General Philosophy of Science (J Gen Philos Sci)
* Journal for ImmunoTherapy of Cancer
* Journal for Labour Market Research (J Labour Market Res)
* Journal for Nature Conservation
* Journal for the History of Astronomy
* Journal for Veterinary Medicine, Biotechnology and Biosafety
* Journal Français d'Ophtalmologie
* Journal für Ästhetische Chirurgie (German) (Journal Ästhetische Chirurgie)
* Journal für Kunstgeschichte
* Journal für Mathematik-Didaktik (German) (J Math Didakt)
* Journal für Verbraucherschutz und Lebensmittelsicherheit (German) (J. Verbr. Lebensm.)
* Journal of Abnormal Child Psychology (J Abnorm Child Psychol)
* Journal of Abnormal Psychology
* Journal of Academic Ethics (J Acad Ethics)
* Journal of Accounting and Economics
* Journal of Accounting and Public Policy
* Journal of Accounting Education
* Journal of Accounting Literature
* Journal of Acute Disease (JAD)
* Journal of Acute Medicine
* Journal of Adhesion Science and Technology
* Journal of Adolescence
* Journal of Adolescent Health
* Journal of Adult Development (J Adult Dev)
* Journal of Advanced Research
* Journal of Advances in Modeling Earth Systems
* Journal of Adventure Education & Outdoor Learning
* Journal of Aerosol Medicine and Pulmonary Drug Delivery (JAMP )
* Journal of Aerosol Science
* Journal of Aerospace Engineering
* Journal of Aerospace Information Systems
* Journal of Affective Disorders
* Journal of African American Studies (J Afr Am St)
* Journal of African Cultural Studies
* Journal of African Earth Sciences
* Journal of African Trade
* Journal of Aging Studies
* Journal of Agricultural and Applied Economics (JAAE)
* Journal of Agricultural and Environmental Ethics (J Agric Environ Ethics)
* Journal of Agricultural and Food Chemistry (J. Agric. Food Chem.)
* Journal of Agricultural Safety and Health
* Journal of Air Transport Management
* Journal of Aircraft
* Journal of Algebra
* Journal of Algebraic Combinatorics (J Algebr Comb)
* Journal of Alloys and Compounds
* Journal of Alzheimer's Disease
* Journal of Ambient Intelligence and Humanized Computing (J Ambient Intell Human Comput)
* Journal of American Association for Pediatric Ophthalmology and Strabismus (Journal of AAPOS)
* Journal of Analytical and Applied Pyrolysis
* Journal of Analytical Atomic Spectrometry
* Journal of Analytical Science and Technology
* Journal of Analytical Toxicology
* Journal of Anesthesia (J Anesth)
* Journal of Anesthesia History
* Journal of Animal Ecology
* Journal of Animal Physiology and Animal Nutrition (JAPAN)
* Journal of Animal Science (JAS)
* Journal of Animal Science and Biotechnology
* Journal of Animal Science and Technology
* Journal of Anthropological Archaeology
* Journal of Antimicrobial Chemotherapy
* Journal of Anxiety Disorders
* Journal of Applied Animal Research
* Journal of Applied Animal Science
* Journal of Applied Biomedicine
* Journal of Applied Clinical Medical Physics
* Journal of Applied Crystallography
* Journal of Applied Developmental Psychology
* Journal of Applied Ecology
* Journal of Applied Electrochemistry (J Appl Electrochem)
* Journal of Applied Entomology (J Appl Entomol)
* Journal of Applied Genetics (J Appl Genetics)
* Journal of Applied Geophysics
* Journal of Applied Logic
* Journal of Applied Mathematics and Computing (J. Appl. Math. Comput.)
* Journal of Applied Mechanics
* Journal of Applied Meteorology and Climatology
* Journal of Applied Non-Classical Logics
* Journal of Applied Pharmaceutical Research (JOAPR)
* Journal of Applied Philosophy
* Journal of Applied Phycology (J Appl Phycol)
* Journal of Applied Physics
* Journal of Applied Physiology
* Journal of Applied Polymer Science
* Journal of Applied Psychology
* Journal of Applied Remote Sensing
* Journal of Applied Research and Technology
* Journal of Applied Research in Memory and Cognition
* Journal of Applied Research on Medicinal and Aromatic Plants
* Journal of Applied Volcanology
* Journal of Applied Water Engineering and Research
* Journal of Aquatic Animal Health
* Journal of Archaeological Method and Theory (J Archaeol Method Theory)
* Journal of Archaeological Research
* Journal of Archaeological Science
* Journal of Archaeological Science: Reports
* Journal of Architectural Engineering
* Journal of Arid Environments
* Journal of Arrhythmia
* Journal of Arthroscopy and Joint Surgery
* Journal of Artificial Organs (J Artif Organs)
* Journal of Asia-Pacific Entomology
* Journal of Asian Earth Sciences
* Journal of Asian Economics
* Journal of Asian Natural Products Research
* Journal of Assisted Reproduction and Genetics (J Assist Reprod Genet)
* Journal of Astronomical Telescopes, Instruments, and Systems
* Journal of Atmospheric and Oceanic Technology
* Journal of Atmospheric and Solar-Terrestrial Physics
* Journal of Atmospheric Chemistry (J Atmos Chem)
* Journal of Atrial Fibrillation (JAFIB)
* Journal of Australian Strength & Conditioning (JASC)
* Journal of Autism and Developmental Disorders (J Autism Dev Disord)
* Journal of Autoimmunity
* Journal of Automated Reasoning (J Autom Reasoning)
* Journal of Avian Biology
* Journal of Ayurveda and Integrative Medicine
* Journal of Bacteriology (JB)
* Journal of Baltic Studies
* Journal of Banking and Finance
* Journal of Banking and Finance Law and Practice (JBFLP)
* Journal of Basic Microbiology
* Journal of Behavior Therapy and Experimental Psychiatry
* Journal of Behavior, Health & Social Issues
* Journal of Behavioral and Experimental Economics
* Journal of Behavioral and Experimental Finance
* Journal of Behavioral Education (J Behav Educ)
* Journal of Behavioral Medicine (J Behav Med)
* Journal of Beliefs & Values
* Journal of Big Data
* Journal of Bio- and Tribo-Corrosion
* Journal of Bioeconomics (J Bioecon)
* Journal of Bioenergetics and Biomembranes (J Bioenerg Biomembr)
* Journal of Biogeography
* Journal of Biological Education
* Journal of Biological Engineering
* Journal of Biological Physics (J Biol Phys)
* Journal of Biological Regulators & Homeostatic Agents (JBRHA)
* Journal of Biological Research-Thessaloniki
* Journal of Biomaterials Science, Polymer Edition
* Journal of Biomechanical Engineering
* Journal of Biomechanics
* Journal of Biomedical and Therapeutic Sciences
* Journal of Biomedical Informatics
* Journal of Biomedical Materials Research Part A (J Biomed Mater Res A)
* Journal of Biomedical Optics
* Journal of Biomedical Science
* Journal of Biomedical Semantics
* Journal of Biomolecular NMR (J Biomol NMR)
* Journal of Biomolecular Screening (JBS)
* Journal of Biomolecular Structure and Dynamics
* Journal of Biosafety and Biosecurity
* Journal of Biotechnology
* Journal of Bodywork & Movement Therapies
* Journal of Bone and Mineral Metabolism (J Bone Miner Metab)
* Journal of Bone and Mineral Research (JBMR)
* Journal of Bone Oncology
* Journal of Brachial Plexus and Peripheral Nerve Injury (J Brachial Plexus Peripher Nerve Inj)
* Journal of Breath Research
* Journal of Bridge Engineering
* Journal of Building Engineering
* Journal of Building Pathology and Rehabilitation
* Journal of Building Performance Simulation
* Journal of Burn Care & Research (JBCR)
* Journal of Business & Economic Statistics (JBES)
* Journal of Business and Psychology (J Bus Psychol)
* Journal of Business Economics (J Bus Econ)
* Journal of Business Ethics (J Bus Ethics)
* Journal of Business Logistics (JBL)
* Journal of Business Research
* Journal of Business Venturing
* Journal of Business Venturing Insights
* Journal of Cachexia, Sarcopenia and Muscle (JCSM)
* Journal of Cancer Education (J Canc Educ)
* Journal of Cancer Policy
* Journal of Cancer Research and Clinical Oncology (J Cancer Res Clin Oncol)
* Journal of Cancer Research and Practice
* Journal of Cancer Research and Therapeutics
* Journal of Cancer Survivorship (J Cancer Surviv)
* Journal of Cardiology
* Journal of Cardiology Cases
* Journal of Cardiothoracic and Vascular Anesthesia
* Journal of Cardiothoracic Surgery
* Journal of Cardiovascular Computed Tomography
* Journal of Cardiovascular Development and Disease
* Journal of Cardiovascular Disease Research
* Journal of Cardiovascular Magnetic Resonance
* Journal of Cardiovascular Pharmacology & Therapeutics
* Journal of Cardiovascular Translational Research (J. of Cardiovasc. Trans. Res.)
* Journal of Catalysis
* Journal of Cataract & Refractive Surgery
* Journal of Cell Communication and Signaling (J. Cell Commun. Signal.)
* Journal of Cell Science
* Journal of Cellular and Molecular Medicine (JCMM)
* Journal of Cellular Immunotherapy
* Journal of Cereal Science
* Journal of Cerebral Blood Flow & Metabolism
* Journal of Change Management
* Journal of Chemical & Engineering Data (J. Chem. Eng. Data)
* Journal of Chemical Biology (J Chem Biol)
* Journal of Chemical Crystallography (J Chem Crystallogr)
* Journal of Chemical Ecology
* Journal of Chemical Education (J. Chem. Educ.)
* Journal of Chemical Information and Modeling (J. Chem. Inf. Model.)
* Journal of Chemical Neuroanatomy
* Journal of Chemical Theory and Computation (J. Chem. Theory Comput.)
* Journal of Cheminformatics
* Journal of Chemistry and Chemical Engineering
* Journal of Chemometrics
* Journal of Chemotherapy
* Journal of Child & Adolescent Trauma
* Journal of Child and Adolescent Psychopharmacology
* Journal of Child and Family Studies (J Child Fam Stud)
* Journal of Children and Media
* Journal of Children and Poverty
* Journal of Children's Orthopaedics (J Child Orthop)
* Journal of Chinese Economic and Business Studies
* Journal of Chinese Management
* Journal of Chinese Political Science (J OF CHIN POLIT SCI)
* Journal of Chinese Studies
* Journal of Chiropractic Humanities
* Journal of Chiropractic Medicine
* Journal of Choice Modelling
* Journal of Chromatography A
* Journal of Chromatography B
* Journal of Civil Litigation and Practice (JCivLP)
* Journal of Civil Structural Health Monitoring (J Civil Struct Health Monit)
* Journal of Cleaner Production
* Journal of Climate
* Journal of Clinical & Translational Endocrinology
* Journal of Clinical and Experimental Hepatology
* Journal of Clinical and Experimental Neuropsychology
* Journal of Clinical and Translational Endocrinology: Case Reports
* Journal of Clinical Anesthesia
* Journal of Clinical Epidemiology
* Journal of Clinical Gastroenterology
* Journal of Clinical Immunology (J Clin Immunol)
* Journal of Clinical Lipidology
* Journal of Clinical Medicine
* Journal of Clinical Microbiology (JCM)
* Journal of Clinical Monitoring and Computing (J Clin Monit Comput)
* Journal of Clinical Movement Disorders
* Journal of Clinical Neurophysiology (JCNP)
* Journal of Clinical Neuroscience
* Journal of Clinical Oncology
* Journal of Clinical Orthopaedics and Trauma
* Journal of Clinical Pathology
* Journal of Clinical Psychology in Medical Settings (J Clin Psychol Med Settings)
* Journal of Clinical Rheumatology (JCR)
* Journal of Clinical Sleep Medicine
* Journal of Clinical Tuberculosis and Other Mycobacterial Diseases
* Journal of Clinical Virology
* Journal of Cloud Computing
* Journal of Co-operative Organization and Management
* Journal of CO2 Utilization
* Journal of Coastal Conservation (J Coast Conserv)
* Journal of Coastal Life Medicine (JCLM)
* Journal of Cognitive Psychology
* Journal of Cold Regions Engineering
* Journal of Colloid And Interface Science
* Journal of Combinatorial Optimization (J Comb Optim)
* Journal of Combinatorial Theory, Series A
* Journal of Combinatorics
* Journal of Commodity Markets
* Journal of Common Market Studies (JCMS)
* Journal of Communication Disorders
* Journal of Communications and Networks
* Journal of Community Genetics (J Community Genet)
* Journal of Community Health (J Community Health)
* Journal of Comparative Asian Development
* Journal of Comparative Economics
* Journal of Comparative Effectiveness Research
* Journal of Comparative Physiology A (J Comp Physiol A)
* Journal of Comparative Physiology B (J Comp Physiol B)
* Journal of Comparative Psychology
* Journal of Compassionate Health Care
* Journal of Competitiveness
* Journal of Complexity
* Journal of Composites for Construction
* Journal of Composites Science
* Journal of Computational and Applied Mathematics
* Journal of Computational and Graphical Statistics (JCGS)
* Journal of Computational and Nonlinear Dynamics
* Journal of Computational Chemistry (JCC)
* Journal of Computational Design and Engineering
* Journal of Computational Electronics (J Comput Electron)
* Journal of Computational Neuroscience (J Comput Neurosci)
* Journal of Computational Physics
* Journal of Computational Science
* Journal of Computational Surgery
* Journal of Computer and System Sciences
* Journal of Computer Applications in Archaeology (JCAA)
* Journal of Computer Information Systems (JCIS)
* Journal of Computer Virology and Hacking Techniques (J Comput Virol)
* Journal of Computer-Aided Molecular Design (J Comput Aided Mol Des)
* Journal of Computers in Education
* Journal of Computing and information Science in Engineering
* Journal of Computing in Civil Engineering
* Journal of Computing in Higher Education (J Comput High Educ)
* Journal of Congenital Cardiology
* Journal of Construction Engineering and Management
* Journal of Constructional Steel Research
* Journal of Consulting and Clinical Psychology
* Journal of Consumer Policy (J Consum Policy)
* Journal of Consumer Psychology
* Journal of Consumer Research
* Journal of Contaminant Hydrology
* Journal of Contemporary Accounting & Economics
* Journal of Contemporary African Studies
* Journal of Contemporary Asia
* Journal of Contemporary European Studies
* Journal of Contemporary Psychotherapy (J Contemp Psychother)
* Journal of Contextual Behavioral Science
* Journal of Control, Automation and Electrical Systems
* Journal of Controlled Release
* Journal of Corporate Finance
* Journal of Cosmology and Astroparticle Physics
* Journal of Counseling Psychology
* Journal of Criminal Justice
* Journal of Criminal Justice Education
* Journal of Critical Care
* Journal of Crohn's and Colitis (CROHNS)
* Journal of Crohn's and Colitis Supplements (CROSUP)
* Journal of Cross-Cultural Gerontology (J Cross Cult Gerontol)
* Journal of Cryptographic Engineering (J Cryptogr Eng)
* Journal of Crystal Growth
* Journal of Cultural Economics (J Cult Econ)
* Journal of Cultural Economy
* Journal of Cultural Heritage
* Journal of Current Ophthalmology
* Journal of Curriculum Studies
* Journal of Cystic Fibrosis
* Journal of Dairy Science (JDS)
* Journal of Data and Information Quality (JDIQ)
* Journal of Decision Systems
* Journal of Dental Education
* Journal of Dental Research
* Journal of Dental Sciences
* Journal of Dentistry
* Journal of Dermatological Science
* Journal of Dermatological Science Supplement
* Journal of Dermatology & Dermatologic Surgery
* Journal of Destination Marketing & Management
* Journal of Development Economics
* Journal of Development Effectiveness
* Journal of Development Studies
* Journal of Developmental and Life-Course Criminology
* Journal of Developmental and Physical Disabilities (J Dev Phys Disabil)
* Journal of Developmental Biology
* Journal of Diabetes & Metabolic Disorders
* Journal of Diabetes and Its Complications
* Journal of Differential Equations
* Journal of Discrete Algorithms
* Journal of Disease Cause and Control
* Journal of Display Technology
* Journal of Diversity in Higher Education
* Journal of Drug Delivery Science and Technology
* Journal of Dynamic Behavior of Materials
* Journal of Dynamic Systems, Measurement, and Control
* Journal of Dynamical and Control Systems
* Journal of Dynamics and Differential Equations (J Dyn Diff Equat)
* Journal of East Asian Linguistics (J East Asian Linguist)
* Journal of Eastern African Studies
* Journal of Eating Disorders
* Journal of Echocardiography (J Echocardiogr)
* Journal of Ecology
* Journal of Econometrics
* Journal of Economic Behavior and Organization
* Journal of Economic Dynamics and Control
* Journal of Economic Entomology
* Journal of Economic Growth (J Econ Growth)
* Journal of Economic Interaction and Coordination (J Econ Interact Coord)
* Journal of Economic Methodology
* Journal of Economic Policy Reform
* Journal of Economic Psychology
* Journal of Economic Structures
* Journal of Economic Theory
* Journal of Economics (J Econ)
* Journal of Economics and Business
* Journal of Economics and Finance (J Econ Finan)
* Journal of Economics, Finance and Administrative Science
* Journal of Ecotourism
* Journal of Education and Work
* Journal of Education for Teaching
* Journal of Education Policy
* Journal of Educational and Behavioral Statistics
* Journal of Educational Change (J Educ Change)
* Journal of Educational Evaluation for Health Professions
* Journal of Educational Psychology
* Journal of Elasticity (J Elast)
* Journal of Elections, Public Opinion & Parties
* Journal of Electrical Systems and Information Technology
* Journal of Electroanalytical Chemistry
* Journal of Electrocardiology
* Journal of Electroceramics (J Electroceram)
* Journal of Electromagnetic Waves and Applications
* Journal of Electromyography and Kinesiology
* Journal of Electron Spectroscopy and Related Phenomena
* Journal of Electronic Imaging
* Journal of Electronic Materials (Journal of Elec Materi)
* Journal of Electronic Packaging
* Journal of Electronic Testing (J Electron Test)
* Journal of Electrostatics
* Journal of Emergency Nursing
* Journal of Empirical Finance
* Journal of Endocrinological Investigation
* Journal of Endocrinology
* Journal of Endodontics (JOEN)
* Journal of Energy Chemistry
* Journal of Energy Engineering
* Journal of Energy Resources Technology
* Journal of Energy Storage
* Journal of Engineering and Technology Management
* Journal of Engineering for Gas Turbines and Power
* Journal of Engineering Materials and Technology
* Journal of Engineering Mathematics (J Eng Math)
* Journal of Engineering Mechanics
* Journal of English for Academic Purposes
* Journal of Environmental Chemical Engineering
* Journal of Environmental Economics and Management
* Journal of Environmental Economics and Policy
* Journal of Environmental Engineering
* Journal of Environmental Health Science and Engineering
* Journal of Environmental Management
* Journal of Environmental Planning and Management
* Journal of Environmental Policy & Planning
* Journal of Environmental Psychology
* Journal of Environmental Quality
* Journal of Environmental Radioactivity
* Journal of Environmental Science and Health, Part A
* Journal of Environmental Science and Health, Part B
* Journal of Environmental Sciences
* Journal of Environmental Studies and Sciences (J Environ Stud Sci)
* Journal of Epidemiology
* Journal of Epidemiology and Community Health
* Journal of Epidemiology and Global Health
* Journal of Equine Veterinary Science
* Journal of Ethnic and Migration Studies
* Journal of Ethnic Foods
* Journal of Ethnobiology and Ethnomedicine
* Journal of Ethnopharmacology
* Journal of Ethology (J Ethol)
* Journal of EuCornea
* Journal of Eurasian Studies
* Journal of European Public Policy (RJPP)
* Journal of Evolution and Health (Jevohealth)
* Journal of Evolutionary Biology
* Journal of Evolutionary Economics (J Evol Econ)
* Journal of Exercise Science & Fitness
* Journal of Experimental & Clinical Assisted Reproduction
* Journal of Experimental & Clinical Cancer Research
* Journal of Experimental & Theoretical Artificial Intelligence
* Journal of Experimental Algorithmics (JEA)
* Journal of Experimental Botany
* Journal of Experimental Child Psychology
* Journal of Experimental Criminology (J Exp Criminol)
* Journal of Experimental Marine Biology and Ecology
* Journal of Experimental Nanoscience
* Journal of Experimental Orthopaedics
* Journal of Experimental Psychology: Animal Learning and Cognition
* Journal of Experimental Psychology: Applied
* Journal of Experimental Psychology: General
* Journal of Experimental Psychology: Human Perception and Performance
* Journal of Experimental Psychology: Learning, Memory, and Cognition
* Journal of Experimental Social Psychology
* Journal of Experimental Zoology
* Journal of Exposure Science and Environmental Epidemiology
* Journal of Failure Analysis and Prevention (J Fail. Anal. and Preven.)
* Journal of Family and Economic Issues (J Fam Econ Iss)
* Journal of Family Business Strategy
* Journal of Family Planning and Reproductive Health Care
* Journal of Family Psychology
* Journal of Family Violence (J Fam Viol)
* Journal of Fetal Medicine
* Journal of Field Ornithology
* Journal of Finance
* Journal of Financial Economics
* Journal of Financial Intermediation
* Journal of Financial Markets
* Journal of Financial Services Research (J Financ Serv Res)
* Journal of Financial Stability
* Journal of Fish Biology
* Journal of Fish Diseases
* Journal of Fluency Disorders
* Journal of Fluids and Structures
* Journal of Fluids Engineering
* Journal of Fluorescence (J Fluoresc)
* Journal of Fluorine Chemistry
* Journal of Food and Drug Analysis
* Journal of Food Composition and Analysis
* Journal of Food Engineering
* Journal of Food Measurement and Characterization (Food Measure)
* Journal of Food Protection
* Journal of Food Science and Technology (J Food Sci Technol)
* Journal of Foot and Ankle Research
* Journal of Forensic and Legal Medicine
* Journal of Forensic Psychiatry & Psychology
* Journal of Forensic Radiology and Imaging
* Journal of Forensic Sciences
* Journal of Forest Economics
* Journal of Forest Research (J For Res)
* Journal of Forestry Research
* Journal of Fourier Analysis and Applications (J Fourier Anal Appl)
* Journal of Frailty & Aging
* Journal of Freshwater Ecology
* Journal of Frugal Innovation
* Journal of Fuel Cell Science and Technology
* Journal of Functional Analysis
* Journal of Functional Biomaterials
* Journal of Functional Foods
* Journal of Functional Morphology and Kinesiology
* Journal of Fungi
* Journal of Further and Higher Education
* Journal of Fusion Energy (J Fusion Energ)
* Journal of Gambling Studies (J Gambl Stud)
* Journal of Gastroenterology (J Gastroenterol)
* Journal of Gastroenterology and Hepatology
* Journal of Gastrointestinal and Liver Diseases
* Journal of Gastrointestinal Cancer (J Gastrointest Canc)
* Journal of Gender Studies
* Journal of General Internal Medicine
* Journal of General Plant Pathology (J Gen Plant Pathol)
* Journal of General Virology
* Journal of Genetic Counseling (J Genet Counsel)
* Journal of Genetic Engineering and Biotechnology
* Journal of Genetics and Genomics
* Journal of Geochemical Exploration
* Journal of Geodesy (J Geod)
* Journal of Geodynamics
* Journal of Geographical Systems (J Geogr Syst)
* Journal of Geography in Higher Education
* Journal of Geometry (J. Geom.)
* Journal of Geometry and Physics
* Journal of Geophysical Research
* Journal of Geophysical Research: Atmospheres
* Journal of Geophysical Research: Biogeosciences
* Journal of Geophysical Research: Earth Surface
* Journal of Geophysical Research: Oceans
* Journal of Geophysical Research: Planets
* Journal of Geophysical Research: Solid Earth
* Journal of Geophysical Research: Space Physics
* Journal of Geophysics and Engineering
* Journal of Geosciences (J Geosci)
* Journal of Geotechnical and Geoenvironmental Engineering
* Journal of Geriatric Oncology
* Journal of Geriatric Psychiatry and Neurology
* Journal of Gerontological Nursing
* Journal of Ginseng Research
* Journal of Glaciology
* Journal of Glaucoma
* Journal of Global Antimicrobial Resistance
* Journal of Global Entrepreneurship Research
* Journal of Global Fashion Marketing
* Journal of Global Optimization (J Glob Optim)
* Journal of Global Scholars of Marketing Science
* Journal of Graphic Novels and Comics
* Journal of Great Lakes Research
* Journal of Grid Computing (J Grid Computing)
* Journal of Guidance, Control, and Dynamics
* Journal of Gynecologic Oncology
* Journal of Gynecology Obstetrics and Human Reproduction
* Journal of Hainan Medical University (JHMU)
* Journal of Hand and Microsurgery (J Hand Microsurg)
* Journal of Hand Therapy
* Journal of Happiness Studies (J Happiness Stud)
* Journal of Hazardous Materials
* Journal of Hazardous, Toxic, and Radioactive Waste
* Journal of Health and Social Behavior
* Journal of Health Economics
* Journal of Health, Population and Nutrition
* Journal of Hearing Science
* Journal of Heat Transfer
* Journal of Hematology & Oncology
* Journal of Hematopathology (J Hematopathol)
* Journal of Hepatology
* Journal of Herbal Medicine
* Journal of Heritage Tourism
* Journal of Heuristics (J Heuristics)
* Journal of High Technology Management Research
* Journal of Highway and Transportation Research and Development
* Journal of Hip Preservation Surgery
* Journal of Historical Geography
* Journal of Historical Linguistics (JHL)
* Journal of Homotopy and Related Structures (J. Homotopy Relat. Struct.)
* Journal of Hospital Infection
* Journal of Hospital Total Quality Management
* Journal of Hospitality and Tourism Management
* Journal of Hospitality, Leisure, Sport & Tourism Education
* Journal of Housing and the Built Environment (J Hous and the Built Environ)
* Journal of Housing Economics
* Journal of Human Evolution
* Journal of Human Hypertension
* Journal of Human Rights and Social Work
* Journal of Hydraulic Engineering
* Journal of Hydro-environment Research
* Journal of Hydrologic Engineering
* Journal of Hydrology
* Journal of Hydrology: Regional Studies
* Journal of Hydrometeorology
* Journal of Hypertension
* Journal of Iberian and Latin American Studies
* Journal of Imaging
* Journal of Immigrant and Minority Health (J Immigrant Minority Health)
* Journal of Immunological Methods
* Journal of Immunology and Regenerative Medicine
* Journal of Inclusion Phenomena and Macrocyclic Chemistry (J Incl Phenom Macrocycl Chem)
* Journal of Indian Association for Child and Adolescent Mental Health
* Journal of Indian Association of Pediatric Surgeons
* Journal of Indian College of Cardiology
* Journal of Indian Council of Philosophical Research
* Journal of Indian Philosophy (J Indian Philos)
* Journal of Individual Differences
* Journal of Industrial and Engineering Chemistry (JIEC)
* Journal of Industrial Ecology
* Journal of Industrial Engineering International
* Journal of Industrial Information Integration
* Journal of Industrial Microbiology & Biotechnology (J Ind Microbiol Biotechnol)
* Journal of Industry, Competition and Trade (J Ind Compet Trade)
* Journal of Inequalities and Applications
* Journal of Infection (YJINF)
* Journal of Infection and Chemotherapy
* Journal of Infection and Public Health
* Journal of Infectious Diseases
* Journal of Inflammation
* Journal of Information Security and Applications
* Journal of Information Technology (JIT)
* Journal of Informetrics
* Journal of Infrastructure Systems
* Journal of Inherited Metabolic Disease (J Inherit Metab Dis)
* Journal of Innate Immunity
* Journal of Innovation & Knowledge
* Journal of Innovation and Entrepreneurship
* Journal of Innovation in Digital Ecosystems
* Journal of Inorganic and Organometallic Polymers and Materials (J Inorg Organomet Polym)
* Journal of Inorganic Biochemistry
* Journal of Insect Behavior (J Insect Behav)
* Journal of Insect Conservation (J Insect Conserv)
* Journal of Insect Physiology
* Journal of Institute of Medicine
* Journal of Institutional and Theoretical Economics (JITE)
* Journal of Instrumentation
* Journal of Integrated OMICS (JIOMICS)
* Journal of Integrated Science and Technology
* Journal of Integrative Environmental Sciences
* Journal of Integrative Medicine
* Journal of Intellectual & Developmental Disability
* Journal of Intelligence
* Journal of Intelligent & Robotic Systems (J Intell Robot Syst)
* Journal of Intelligent Information Systems (J Intell Inf Syst)
* Journal of Intelligent Manufacturing (J Intell Manuf)
* Journal of Intensive Care
* Journal of Interaction Science
* Journal of Interactive Marketing
* Journal of Intercultural Communication Research
* Journal of Internal Medicine
* Journal of International Accounting, Auditing and Taxation
* Journal of International and Comparative Social Policy
* Journal of International Business Studies (JIBS)
* Journal of International Economic Law
* Journal of International Economics
* Journal of International Entrepreneurship (J Int Entrep)
* Journal of International Financial Markets, Institutions & Money
* Journal of International Humanitarian Action
* Journal of International Management
* Journal of International Marketing (JIM)
* Journal of International Migration and Integration (Int. Migration & Integration)
* Journal of International Money and Finance
* Journal of International Relations and Development (JIRD)
* Journal of Internet Services and Applications
* Journal of Interprofessional Education & Practice
* Journal of Intervention and Statebuilding
* Journal of Interventional Cardiac Electrophysiology (J Interv Card Electrophysiol)
* Journal of Invasive and Interventional Cardiology
* Journal of Invertebrate Pathology
* Journal of Investigative Dermatology (J Invest Dermatol)
* Journal of Investigative Dermatology Symposium Proceedings
* Journal of Irrigation and Drainage Engineering
* Journal of Israeli History
* Journal of Judicial Administration (JJA)
* Journal of King Saud University - Computer and Information Sciences
* Journal of King Saud University - Engineering Sciences
* Journal of King Saud University - Languages and Translation
* Journal of King Saud University - Science
* Journal of Knee Surgery
* Journal of Korean Medical Science
* Journal of Korean Neurosurgical Society (J Korean Neurosurg Soc)
* Journal of Labor Research (J Labor Res)
* Journal of Laboratory Automation (JALA)
* Journal of Laboratory Physicians
* Journal of Land Use Science
* Journal of Landscape Ecology
* Journal of Latin American Cultural Studies
* Journal of Latina/o Psychology
* Journal of Law and Medicine (JLM)
* Journal of Legal Affairs and Dispute Resolution in Engineering and Construction
* Journal of Lightwave Technology
* Journal of Limnology
* Journal of Lipid Research
* Journal of Location Based Services
* Journal of Logic and Algebraic Programming
* Journal of Logic, Language and Information (J of Log Lang and Inf)
* Journal of Logical and Algebraic Methods in Programming
* Journal of Loss Prevention in the Process Industries
* Journal of Low Power Electronics and Applications
* Journal of Low Temperature Physics (J Low Temp Phys)
* Journal of Luminescence
* Journal of Macroeconomics
* Journal of Magnetic Resonance
* Journal Of Magnetic Resonance Imaging (JMRI)
* Journal of Magnetism and Magnetic Materials
* Journal of Mammalogy
* Journal of Mammary Gland Biology and Neoplasia (J Mammary Gland Biol Neoplasia)
* Journal of Management
* Journal of Management & Governance (J Manag Gov)
* Journal of Management Control (J Manag Control)
* Journal of Management in Engineering
* Journal of Management Information Systems (JMIS)
* Journal of Management Studies (JMS)
* Journal of Managerial Psychology
* Journal of Manipulative and Physiological Therapeutics
* Journal of Manufacturing and Materials Processing
* Journal of Manufacturing Processes
* Journal of Manufacturing Science and Engineering
* Journal of Manufacturing Systems
* Journal of Maps
* Journal of Marine and Island Cultures
* Journal of Marine Science and Engineering
* Journal of Marine Science and Technology (J Mar Sci Technol)
* Journal of Marine Systems
* Journal of Maritime Archaeology (J Mari Arch)
* Journal of Marketing (JM)
* Journal of Marketing Communications
* Journal of Marketing for Higher Education
* Journal of Marketing Management
* Journal of Marketing Research (JMR)
* Journal of Material Cycles and Waste Management (J Mater Cycles Waste Manag)
* Journal of Materials Chemistry A
* Journal of Materials Chemistry B
* Journal of Materials Chemistry C
* Journal of Materials Engineering and Performance (J. of Materi Eng and Perform)
* Journal of Materials in Civil Engineering
* Journal of Materials NanoScience
* Journal of Materials Processing Tech.
* Journal of Materials Research (J. Mater. Res.)
* Journal of Materials Research and Technology
* Journal of Materials Science (J Mater Sci)
* Journal of Materials Science & Technology
* Journal of Materials Science: Materials in Electronics (J Mater Sci: Mater Electron)
* Journal of Materials Science: Materials in Medicine (J Mater Sci: Mater Med)
* Journal of Materiomics
* Journal of Mathematical Behavior
* Journal of Mathematical Biology (J. Math. Biol.)
* Journal of Mathematical Chemistry (J Math Chem)
* Journal of Mathematical Economics
* Journal of Mathematical Fluid Mechanics (J. Math. Fluid Mech.)
* Journal of Mathematical Imaging and Vision (J Math Imaging Vis)
* Journal of Mathematical Physics
* Journal of Mathematical Psychology
* Journal of Mathematics and Music
* Journal of Mathematics in Industry
* Journal of Mathematics Teacher Education (J Math Teacher Educ)
* Journal of Maxillofacial and Oral Surgery (J. Maxillofac. Oral Surg.)
* Journal of Mechanical Design
* Journal of Mechanical Science and Technology
* Journal of Mechanisms and Robotics
* Journal of Media Psychology: Theories, Methods, and Applications
* Journal of Medical and Biological Engineering
* Journal of Medical Case Reports
* Journal of Medical Devices
* Journal of Medical Entomology
* Journal of Medical Ethics
* Journal of Medical Genetics
* Journal of Medical Imaging
* Journal of Medical Imaging and Radiation Oncology
* Journal of Medical Imaging and Radiation Sciences
* Journal of Medical Internet Research (JMIR)
* Journal of Medical Microbiology
* Journal of Medical Physics
* Journal of Medical Toxicology (J. Med. Toxicol.)
* Journal of Medical Ultrasonics (J Med Ultrasonics)
* Journal of Medical Ultrasound
* Journal of Medicinal Chemistry (J. Med. Chem.)
* Journal of Medicine and the Person (J Med Pers)
* Journal of Membrane Science
* Journal of Memory and Language
* Journal of Men's Health
* Journal of Micro and Nano-Manufacturing
* Journal of Micro-Bio Robotics (J Micro-Bio Robot)
* Journal of Micro/Nanolithography, MEMS, and MOEMS
* Journal of Microbiological Methods
* Journal of Microbiology & Biology Education (JMBE)
* Journal of Microbiology, Immunology and Infection
* Journal of Microelectromechanical Systems
* Journal of Micromechanics and Microengineering
* Journal of Micropalaeontology
* Journal of Microscopy and Ultrastructure
* Journal of Midwifery & Women's Health
* Journal of Minimal Access Surgery
* Journal of Minimally Invasive Gynecology (JMIG)
* Journal of Modern Italian Studies
* Journal of Modern Jewish Studies
* Journal of Modern Power Systems and Clean Energy
* Journal of Modern Transportation
* Journal of Molecular and Cellular Cardiology
* Journal of Molecular Biology
* Journal of Molecular Catalysis. A, Chemical
* Journal of Molecular Catalysis. B, Enzymatic
* Journal of Molecular Cell Biology (JMCB)
* Journal of Molecular Endocrinology
* Journal of Molecular Evolution (J Mol Evol)
* Journal of Molecular Graphics and Modelling
* Journal of Molecular Histology (J Mol Hist)
* Journal of Molecular Liquids
* Journal of Molecular Medicine (J Mol Med)
* Journal of Molecular Microbiology and Biotechnology
* Journal of Molecular Modeling (J Mol Model)
* Journal of Molecular Neuroscience (J Mol Neurosci)
* Journal of Molecular Psychiatry
* Journal of Molecular Recognition (JMR)
* Journal of Molecular Signaling
* Journal of Molecular Spectroscopy
* Journal of Molecular Structure
* Journal of Monetary Economics
* Journal of Moral Education
* Journal of Morphology
* Journal of Multilingual and Multicultural Development
* Journal of Multinational Financial Management
* Journal of Muscle Research and Cell Motility (J Muscle Res Cell Motil)
* Journal of Music Technology and Education (JMTE)
* Journal of Nanobiotechnology
* Journal of Nanomechanics and Micromechanics
* Journal of Nanoparticle Research (J Nanopart Res)
* Journal of Nanophotonics
* Journal of Nanoscience and Nanotechnology
* Journal of Nanostructure in Chemistry
* Journal of Nanotechnology in Engineering and Medicine
* Journal of Natural Gas Geoscience
* Journal of Natural Gas Science and Engineering
* Journal of Natural History
* Journal of Natural Medicines (J Nat Med)
* Journal of Natural Products (J. Nat. Prod.)
* Journal of Natural Resources Policy Research
* Journal of Negative Results in BioMedicine
* Journal of Neolithic Archaeology (JNA)
* Journal of Neonatal Nursing
* Journal of Nephrology
* Journal of Network and Computer Applications
* Journal of Network and Systems Management (J Netw Syst Manage)
* Journal of Neural Engineering
* Journal of Neural Transmission (J Neural Transm)
* Journal of Neuro-Oncology (J Neurooncol)
* Journal of Neurochemistry (JoN)
* Journal of Neurodevelopmental Disorders
* Journal of NeuroEngineering and Rehabilitation
* Journal of Neuroimmune Pharmacology (J Neuroimmune Pharmacol)
* Journal of Neuroimmunology
* Journal of Neuroinflammation
* Journal of NeuroInterventional surgery
* Journal of Neurolinguistics
* Journal of Neurological Disorders (JND)
* Journal of Neurology (J Neurol)
* Journal of Neurology, Neurosurgery, and Psychiatry
* Journal of Neuropathology & Experimental Neurology
* Journal of Neurophysiology
* Journal of Neuropsychology
* Journal of Neuroradiology
* Journal of Neuroscience and Neuroengineering
* Journal of Neuroscience Methods
* Journal of Neuroscience, Psychology, and Economics
* Journal of Neurosurgery
* Journal of Neurosurgery: Pediatrics
* Journal of Neurosurgery: Spine
* Journal of Neurotrauma
* Journal of NeuroVirology (J. Neurovirol.)
* Journal of New Music Research
* Journal of Non-Crystalline Solids
* Journal of Non-Newtonian Fluid Mechanics
* Journal of Nondestructive Evaluation (J Nondestruct Eval)
* Journal of Nonlinear Science (J Nonlinear Sci)
* Journal of Nonverbal Behavior (J Nonverbal Behav)
* Journal of Northeast Agricultural University
* Journal of Nuclear Cardiology (J. Nucl. Cardiol.)
* Journal of Nuclear Materials
* Journal of Nuclear Medicine Technology
* Journal of Nuclear Science and Technology
* Journal of Nursing Education
* Journal of Nursing Regulation
* Journal of Nutrigenetics and Nutrigenomics
* Journal of Nutrition
* Journal of Nutrition & Intermediary Metabolism
* Journal of Nutrition Education and Behavior
* Journal of Obsessive-Compulsive and Related Disorders
* Journal of Obstetric, Gynecologic & Neonatal Nursing
* Journal of Occupational and Organizational Psychology
* Journal of Occupational Health Psychology
* Journal of Occupational Medicine and Toxicology
* Journal of Occupational Rehabilitation (J Occup Rehabil)
* Journal of Occupational Science
* Journal of Ocean Engineering and Marine Energy
* Journal of Ocean Engineering and Science
* Journal of Oceanography (J Oceanogr)
* Journal of Ocular Pharmacology and Therapeutics
* Journal of Offshore Mechanics and Arctic Engineering
* Journal of Oncological Sciences
* Journal of Open Innovation: Technology, Market, and Complexity
* Journal of Operations Management
* Journal of Ophthalmic Inflammation and Infection
* Journal of Optics
* Journal of Optics - official publication of the Optical Society of India (J Opt)
* Journal of Optimization Theory and Applications (J Optim Theory Appl)
* Journal of Optometry
* Journal of Oral and Maxillofacial Surgery
* Journal of Oral and Maxillofacial Surgery, Medicine, and Pathology
* Journal of Oral Biology and Craniofacial Research
* Journal of Oral Biosciences
* Journal of Organometallic Chemistry
* Journal of Ornithology (J Ornithol)
* Journal of Orofacial Orthopedics / Fortschritte der Kieferorthopädie
* Journal of Orthopaedic & Sports Physical Therapy (JOSPT)
* Journal of Orthopaedic Research
* Journal of Orthopaedic Science
* Journal of Orthopaedic Surgery and Research
* Journal of Orthopaedic Translation
* Journal of Orthopaedic Trauma
* Journal of Orthopaedics
* Journal of Orthopaedics and Traumatology (J Orthopaed Traumatol)
* Journal of Orthopaedics, Trauma and Rehabilitation (JOTR)
* Journal of Otolaryngology - Head & Neck Surgery
* Journal of Otology
* Journal of Otorhinolaryngology, Hearing and Balance Medicine
* Journal of Outdoor Activities
* Journal of Outdoor Recreation and Tourism
* Journal of Ovarian Research
* Journal of Paediatrics and Child Health
* Journal of Palaeogeography
* Journal of Paleolimnology (J Paleolimnol)
* Journal of Paleontology
* Journal of Palliative Medicine
* Journal of Parallel and Distributed Computing
* Journal of Parasitic Diseases (J Parasit Dis)
* Journal of Patient Safety & Infection Control
* Journal of Peace Education
* Journal of Peace Research
* Journal of Pediatric and Adolescent Gynecology
* Journal of Pediatric Health Care
* Journal of Pediatric Neuropsychology
* Journal of Pediatric Neurosciences
* Journal of Pediatric Nursing
* Journal of Pediatric Ophthalmology & Strabismus
* Journal of Pediatric Surgery
* Journal of Pediatric Surgery Case Reports
* Journal of Pediatric Urology
* Journal of Peptide Science (J. Pept. Sci.)
* Journal of Performance of Constructed Facilities
* Journal of PeriAnesthesia Nursing
* Journal of Perinatal Medicine
* Journal of Perinatology
* Journal of Periodontal Research
* Journal of Periodontology
* Journal of Personality and Social Psychology
* Journal of Personalized Medicine
* Journal of Personnel Psychology
* Journal of Pest Science (J Pest Sci)
* Journal of Petroleum Exploration and Production Technology (J Petrol Explor Prod Technol)
* Journal of Petroleum Science and Engineering
* Journal of Petrology
* Journal of Pharmaceutical Analysis
* Journal of Pharmaceutical and Biomedical Analysis
* Journal of Pharmaceutical Health Care and Sciences
* Journal of Pharmaceutical Innovation (J Pharm Innov)
* Journal of Pharmaceutical Investigation
* Journal of Pharmaceutical Policy and Practice
* Journal of Pharmaceutical Sciences
* Journal of Pharmacokinetics and Pharmacodynamics (J Pharmacokinet Pharmacodyn)
* Journal of Pharmacological and Toxicological Methods
* Journal of Pharmacological Sciences
* Journal of Pharmacology & Pharmacotherapeutics
* Journal of Pharmacy and Pharmacology (JPP)
* Journal of Pharmacy Practice and Research
* Journal of Pharmacy Research
* Journal of Phase Equilibria and Diffusion (J. Phase Equilib. Diffus.)
* Journal of Philosophical Logic (J Philos Logic)
* Journal of Phonetics
* Journal of Photochemistry & Photobiology, A: Chemistry
* Journal of Photochemistry & Photobiology, B: Biology
* Journal of Photochemistry & Photobiology, C: Photochemistry Reviews
* Journal of Photonics for Energy
* Journal of Phycology (J. Phycol.)
* Journal of Physical and Chemical Reference Data
* Journal of Physical Oceanography
* Journal of Physical Therapy Science
* Journal of Physics A: Mathematical and Theoretical
* Journal of Physics and Chemistry of Solids
* Journal of Physics B: Atomic, Molecular and Optical Physics
* Journal of Physics D: Applied Physics
* Journal of Physics G: Nuclear and Particle Physics
* Journal of Physics: Condensed Matter
* Journal of Physics: Conference Series
* Journal of Physiological Anthropology
* Journal of Physiology - Paris
* Journal of Physiology and Biochemistry (J Physiol Biochem)
* Journal of Physiotherapy
* Journal of Pierre Fauchard Academy
* Journal of Pipeline Systems Engineering and Practice
* Journal of Plant Biochemistry and Biotechnology (J. Plant Biochem. Biotechnol.)
* Journal of Plant Ecology (JPE)
* Journal of Plant Growth Regulation (J Plant Growth Regul)
* Journal of Plant Interactions
* Journal of Plant Nutrition and Soil Science (JPNSS)
* Journal of Plant Physiology
* Journal of Plant Research (J Plant Res)
* Journal of Plastic, Reconstructive & Aesthetic Surgery
* Journal of Poetry Therapy
* Journal of Police and Criminal Psychology (J Police Crim Psych)
* Journal of Policing, Intelligence and Counter Terrorism
* Journal of Policy Modeling
* Journal of Policy Research in Tourism, Leisure and Events
* Journal of Political Philosophy
* Journal of Pollination Ecology
* Journal of Polymer Research (J Polym Res)
* Journal of Polymer Science Part A: Polymer Chemistry
* Journal of Polymer Science Part B: Polymer Physics
* Journal of Polymers and the Environment (J Polym Environ)
* Journal of Population Ageing (Population Ageing)
* Journal of Population Economics (J Popul Econ)
* Journal of Population Research (J Pop Research)
* Journal of Porous Materials (J Porous Mater)
* Journal of Porphyrins and Phthalocyanines (JPP)
* Journal of Postcolonial Writing
* Journal of Postgraduate Medicine
* Journal of Power Sources
* Journal of Pragmatics
* Journal of Pressure Vessel Technology
* Journal of Primary Health Care
* Journal of Process Control
* Journal of Product Innovation Management (JPIM)
* Journal of Productivity Analysis (J Prod Anal)
* Journal of Professional Issues in Engineering Education and Practice
* Journal of Professional Nursing
* Journal of Property Research
* Journal of Propulsion and Power
* Journal of Prosthodontic Research
* Journal of Proteome Research (J. Proteome Res.)
* Journal of Proteomics
* Journal of Pseudo-Differential Operators and Applications (J. Pseudo-Differ. Oper. Appl.)
* Journal of Psychiatric and Mental Health Nursing
* Journal of Psychiatric Research
* Journal of Psychiatry & Neuroscience (JPN)
* Journal of Psycholinguistic Research (J Psycholinguist Res)
* Journal of Psychopathology and Behavioral Assessment (J Psychopathol Behav Assess)
* Journal of Psychophysiology
* Journal of Psychosocial Nursing and Mental Health Services
* Journal of Psychosocial Rehabilitation and Mental Health
* Journal of Psychosomatic Research
* Journal of Psychotherapy Integration
* Journal of Public Economics
* Journal of Public Health (J Public Health)
* Journal of Public Policy & Marketing
* Journal of Purchasing and Supply Management
* Journal of Pure and Applied Algebra
* Journal of Quantitative Criminology (J Quant Criminol)
* Journal of Quantitative Economics
* Journal of Quantitative Spectroscopy and Radiative Transfer
* Journal of Racial and Ethnic Health Disparities
* Journal of Radiation Oncology (J Radiat Oncol)
* Journal of Radiation Research
* Journal of Radiation Research and Applied Sciences
* Journal of Radioanalytical and Nuclear Chemistry (J Radioanal Nucl Chem)
* Journal of Radiological Protection
* Journal of Radiology Nursing
* Journal of Rail Transport Planning & Management
* Journal of Raman Spectroscopy
* Journal of Rare Earths
* Journal of Rational-Emotive & Cognitive-Behavior Therapy (J Rat-Emo Cognitive-Behav Ther)
* Journal of Real-Time Image Processing (J Real-Time Image Proc)
* Journal of Reconstructive Microsurgery (J Reconstr Microsurg)
* Journal of Refractive Surgery
* Journal of Regulatory Economics (J Regul Econ)
* Journal of Rehabilitation Research & Development (JRRD)
* Journal of Reliable Intelligent Environments
* Journal of Religion and Health (J Relig Health)
* Journal of Religious Education
* Journal of Remanufacturing
* Journal of Renewable and Sustainable Energy
* Journal of Reproductive and Infant Psychology
* Journal of Reproductive Health and Medicine
* Journal of Reproductive Immunology
* Journal of Research in Personality
* Journal of Research in Science Teaching
* Journal of Retailing
* Journal of Retailing and Consumer Services
* Journal of Rheumatology
* Journal of Risk and Financial Management
* Journal of Risk and Uncertainty (J Risk Uncertain)
* Journal of Risk Research
* Journal of Robotic Surgery (J Robotic Surg)
* Journal of Rock Mechanics and Geotechnical Engineering
* Journal of Roman Archaeology (A)
* Journal of Roman Archaeology (B)
* Journal of Rural Mental Health
* Journal of Rural Studies
* Journal of Safety Research
* Journal of Saudi Chemical Society
* Journal of Scheduling (J Sched)
* Journal of School Psychology
* Journal of Science and Medicine in Sport (JSAMS)
* Journal of Science Education and Technology (J Sci Educ Technol)
* Journal of Science: Advanced Materials and Devices
* Journal of Scientific Computing (J Sci Comput)
* Journal of Sea Research
* Journal of Second Language Writing
* Journal of Seismology (J Seismol)
* Journal of Semiconductors
* Journal of Sensor and Actuator Networks
* Journal of Sensors and Sensor Systems
* Journal of Separation Science
* Journal of Sexual Aggression
* Journal of Shipping and Trade
* Journal of Shoulder and Elbow Surgery
* Journal of Signal Processing Systems (J Sign Process Syst)
* Journal of Simulation
* Journal of Sleep Research
* Journal of Small Business & Entrepreneurship
* Journal of Social and Economic Development
* Journal of Social Archaeology
* Journal of Social Philosophy
* Journal of Socio-Economics
* Journal of Software Engineering Research and Development
* Journal of Soil and Water Conservation (JSWC)
* Journal of Soils and Sediments (J Soils Sediments)
* Journal of Sol-Gel Science and Technology (J Sol-Gel Sci Technol)
* Journal of Solar Energy Engineering
* Journal of Solid State Chemistry
* Journal of Solid State Electrochemistry (J Solid State Electrochem)
* Journal of Solid State Lighting
* Journal of Solution Chemistry (J Solution Chem)
* Journal of Sound and Vibration
* Journal of South American Earth Sciences
* Journal of Spacecraft and Rockets
* Journal of Sport & Tourism
* Journal of Sport and Health Science (JSHS)
* Journal of Sports Sciences
* Journal of Statistical Computation and Simulation
* Journal of Statistical Distributions and Applications
* Journal of Statistical Mechanics: Theory and Experiment
* Journal of Statistical Physics (J Stat Phys)
* Journal of Statistical Planning and Inference
* Journal of Steroid Biochemistry and Molecular Biology
* Journal of Stomatology oral and Maxillofacial Surgery
* Journal of Stored Products Research
* Journal of Strategic Information Systems
* Journal of Strategic Marketing
* Journal of Strength and Conditioning Research
* Journal of Structural and Functional Genomics (J Struct Funct Genomics)
* Journal of Structural Biology
* Journal of Structural Engineering
* Journal of Structural Geology
* Journal of Studies on Alcohol and Drugs
* Journal of Substance Abuse Treatment
* Journal of Sulfur Chemistry
* Journal of Superconductivity and Novel Magnetism (J Supercond Nov Magn)
* Journal of Surfactants and Detergents (J Surfact Deterg)
* Journal of Surgical Education
* Journal of Surgical Research
* Journal of Surveying Engineering
* Journal of Sustainable Cement-Based Materials
* Journal of Sustainable Finance & Investment
* Journal of Sustainable Metallurgy
* Journal of Sustainable Mining
* Journal of Sustainable Tourism
* Journal of Sustainable Water in the Built Environment
* Journal of Symbolic Computation
* Journal of Synchrotron Radiation
* Journal of Systematic Palaeontology
* Journal of Systems Architecture
* Journal of Systems Engineering and Electronics
* Journal of Taibah University for Science
* Journal of Terramechanics
* Journal of the Academy of Marketing Science (J. of the Acad. Mark. Sci.)
* Journal of the Academy of Nutrition and Dietetics
* Journal of the ACM (JACM)
* Journal of the Air & Waste Management Association (JAWMA)
* Journal of the American Academy of Audiology (JAAA)
* Journal of the American Academy of Dermatology
* Journal of the American Academy of Orthopaedic Surgeons (JAAOS)
* Journal of the American Association of Laboratory Animal Science (JAALAS)
* Journal of the American Board of Family Medicine
* Journal of the American Ceramic Society
* Journal of the American Chemical Society (J. Am. Chem. Soc.)
* Journal of the American College of Cardiology (JACC)
* Journal of the American College of Clinical Wound Specialists
* Journal of the American College of Radiology
* Journal of the American College of Surgeons (JACS)
* Journal of the American Heart Association (JAHA)
* Journal of the American Oil Chemists' Society (J Am Oil Chem Soc)
* Journal of the American Pharmacists Association
* Journal of The American Society for Mass Spectrometry
* Journal of the American Society of Brewing Chemists (Journal of the ASBC)
* Journal of the American Society of Cytopathology
* Journal of the American Society of Echocardiography
* Journal of the American Society of Nephrology
* Journal of the American Statistical Association (JASA)
* Journal of the American Veterinary Medical Association
* Journal of the American Water Resources Association (JAWRA)
* Journal of the Anatomical Society of India
* Journal of the Asia Pacific Economy
* Journal of the Association for Information Science and Technology (JASIST)
* Journal of the Association for Information Systems (JAIS)
* Journal of the Association for Research in Otolaryngology (JARO)
* Journal of the Association for Vascular Access
* Journal of the Association of Arab Universities for Basic and Applied Sciences
* Journal of the Association of Environmental and Resource Economists (JAERE)
* Journal of the Atmospheric Sciences
* Journal of the Brazilian Chemical Society (JBCS)
* Journal of the Brazilian Computer Society (J Braz Comput Soc)
* Journal of the Brazilian Society of Mechanical Sciences and Engineering (J Braz. Soc. Mech. Sci. Eng.)
* Journal of the Canadian Chiropractic Association
* Journal of the Chinese Advanced Materials Society
* Journal of the Chinese Institute of Engineers
* Journal of the College of Physicians and Surgeons Pakistan
* Journal of the Economic Science Association
* Journal of the Egyptian Mathematical Society
* Journal of the Egyptian National Cancer Institute
* Journal of the Egyptian Public Health Association
* Journal of the Egyptian Society of Cardio-Thoracic Surgery
* Journal of The Electrochemical Society (JES)
* Journal of the Energy Institute
* Journal of the European Ceramic Society
* Journal of the Formosan Medical Association
* Journal of the Franklin Institute
* Journal of the Geological Society
* Journal of the History of Collections
* Journal of the Indian Academy of Wood Science (J Indian Acad Wood Sci)
* Journal of the Indian Ocean Region
* Journal of the Indian Society for Probability and Statistics
* Journal of the Indian Society of Pedodontics & Preventive Dentistry
* Journal of the Indian Society of Remote Sensing (J Indian Soc Remote Sens)
* Journal of The Institution of Engineers: Series A (J. Inst. Eng. India Ser. A)
* Journal of The Institution of Engineers: Series B (J. Inst. Eng. India Ser. B)
* Journal of The Institution of Engineers: Series C (J. Inst. Eng. India Ser. C)
* Journal of The Institution of Engineers: Series D (J. Inst. Eng. India Ser. D)
* Journal of The Institution of Engineers: Series E (J. Inst. Eng. India Ser. E)
* Journal of the International AIDS Society
* Journal of the International Society of Sports Nutrition
* Journal of the Iranian Chemical Society (J IRAN CHEM SOC)
* Journal of The Japanese and International Economies
* Journal of the Knowledge Economy (J Knowl Econ)
* Journal of the Korean Society for Applied Biological Chemistry
* Journal of the Korean Society of Civil Engineers
* Journal of the Korean Statistical Society
* Journal of the Marine Biological Association of the United Kingdom (JMBA)
* Journal of the Mechanical Behavior of Biomedical Materials
* Journal of the Mechanics and Physics of Solids
* Journal of the Medical Library Association
* Journal of the National Cancer Institute (JNCI)
* Journal of the National Medical Association
* Journal of the Neurological Sciences
* Journal of the Nigerian Mathematical Society
* Journal of the Operations Research Society of China
* Journal of the Philosophy of Sport
* Journal of the Royal Anthropological Institute (JRAI)
* Journal of the Royal Army Medical Corps
* Journal of the Royal Society Interface
* Journal of the Royal Society of Medicine
* Journal of the Saudi Heart Association
* Journal of the Saudi Society of Agricultural Sciences
* Journal of the Saudi Society of Dermatology & Dermatologic Surgery
* Journal of the Society of Archivists
* Journal of the South African Veterinary Association (JSAVA)
* Journal of the Taiwan Institute of Chemical Engineers
* Journal of The Textile Institute
* Journal of the Warburg and Courtauld Institutes
* Journal of the World Federation of Orthodontists
* Journal of Theoretical and Applied Physics
* Journal of Theoretical and Philosophical Psychology
* Journal of Theoretical Biology
* Journal of Theoretical Probability (J Theor Probab)
* Journal of Therapeutic Ultrasound
* Journal of Thermal Analysis and Calorimetry
* Journal of Thermal Biology
* Journal of Thermal Science and Engineering Applications
* Journal of Thermal Spray Technology (J Therm Spray Tech)
* Journal of Thermophysics and Heat Transfer
* Journal of Thoracic Oncology
* Journal of Threat Assessment and Management
* Journal of Thrombosis and Haemostasis
* Journal of Thrombosis and Thrombolysis (J Thromb Thrombolysis)
* Journal of Tissue Viability
* Journal of Tourism and Cultural Change
* Journal of Trace Elements in Medicine and Biology
* Journal of Traditional and Complementary Medicine
* Journal of Traditional Chinese Medical Sciences
* Journal of Traditional Chinese Medicine
* Journal of Traffic and Transportation Engineering
* Journal of Translational Medicine
* Journal of Transport & Health
* Journal of Transport Geography
* Journal of Transportation Engineering
* Journal of Transportation Security (J Transp Secur)
* Journal of Trauma Management & Outcomes
* Journal of Tribology
* Journal of Tropical Ecology
* Journal of Tropical Life Science (J Trop. Life. Science)
* Journal of Trust Management
* Journal of Trust Research
* Journal of Turbomachinery
* Journal of Uncertainty Analysis and Applications
* Journal of Unconventional Oil and Gas Resources
* Journal of Universal Computer Science (J.UCS)
* Journal of Unmanned Vehicle Systems
* Journal of Urban and Environmental Engineering
* Journal of Urban Design
* Journal of Urban Economics
* Journal of Urban Health (J Urban Health)
* Journal of Urban Management
* Journal of Urban Planning and Development
* Journal of Urbanism: International Research on Placemaking and Urban Sustainability
* Journal of Vacuum Science & Technology A: Vacuum, Surfaces, and Films
* Journal of Vacuum Science & Technology B: Microelectronics and Nanometer Structures
* Journal of Vascular Research
* Journal of Vascular Surgery
* Journal of Vascular Surgery Cases and Innovative Techniques
* Journal of Vegetation Science
* Journal of Venomous Animals and Toxins including Tropical Diseases
* Journal of Vertebrate Paleontology
* Journal of Veterinary Behavior
* Journal of Veterinary Cardiology
* Journal of Veterinary Diagnostic Investigation (JVDI)
* Journal of Veterinary Internal Medicine
* Journal of Vibration and Acoustics
* Journal of Virological Methods
* Journal of Virology (JVI)
* Journal of Visceral Surgery
* Journal of Vision
* Journal of Visual Communication and Image Representation
* Journal of Visual Languages and Computing
* Journal of Visualization (J Vis)
* Journal of Visualized Experiments (JoVE)
* Journal of Vocational Behavior
* Journal of Vocational Education & Training
* Journal of Voice
* Journal of Volcanology and Geothermal Research
* Journal of Water Process Engineering
* Journal of Water Resources Planning and Management
* Journal of Water Sanitation and Hygiene for Development (JWaSHDev)
* Journal of Waterway, Port, Coastal, and Ocean Engineering
* Journal of Web Semantics
* Journal of Wildlife Diseases
* Journal of Wind Engineering & Industrial Aerodynamics
* Journal of Wine Research
* Journal of Wood Science (J Wood Sci)
* Journal of World Business
* Journal of World Prehistory (J World Prehist)
* Journal of World Systems Research
* Journal of Wound, Ostomy and Continence Nursing
* Journal of Young Pharmacists
* Journal of Youth and Adolescence (J Youth Adolescence)
* Journal of Youth Studies
* Journal of Zoo and Wildlife Medicine
* Journal of Zoo Biology (JZB)
* Journal of Zoology
* Journal on Computing and Cultural Heritage (JOCCH)
* Journal on Data Semantics (J Data Semant)
* Journal on Efficiency and Responsibility in Education and Science (ERIES)
* Journal on Multimodal User Interfaces (J Multimodal User Interfaces)
* Journalism Practice
* Journalism Studies
* Journalistica (Danish)
* JPRAS Open
* Juristische Schulung (German) (JuS)
* Juristische Zitierweise (Stüber) (German)
* Juristische Zitierweise Schweizer (Ryser Büschi et al.) (German - Switzerland)
* Jurnal Pangan dan Agroindustri (Indonesian) (JPA)
* Justice Quarterly
* Kaohsiung Journal of Medical Sciences
* Karbala International Journal of Modern Science
* Kardiologie up2date
* Karger journals
* Karger journals (author-date)
* Kasetsart Journal of Social Sciences
* KI - Künstliche Intelligenz (Künstl Intell)
* Kidney & Blood Pressure Research
* Kidney Disease and Transplantation
* Kidney International
* Kidney International Supplements
* Kidney Research and Clinical Practice (KRCP)
* Kind & Adolescent (Dutch)
* Kindheit und Entwicklung
* Kinésithérapie, la revue
* King's College London - Harvard
* Klinische Monatsblätter für Augenheilkunde
* Klinische Neurophysiologie
* Klinische Pädiatrie
* Knee Surgery, Sports Traumatology, Arthroscopy (KSSTA)
* Knowledge and Information Systems (Knowl Inf Syst)
* Knowledge-Based Systems
* Kölner Zeitschrift für Soziologie und Sozialpsychologie (German) (KZfSS)
* Kommunikation und Recht (German) (K&R)
* KONTAKT
* Korean Journal of Anesthesiology (KJA)
* Korean Social Science Journal
* Krankenhaushygiene up2date
* Kritische Ausgabe (German)
* KSCE Journal of Civil Engineering
* KTH Royal Institute of Technology - School of Computer Science and Communication (KTH - CSC - Degree Projects)
* KTH Royal Institute of Technology - School of Computer Science and Communication (Swedish) (KTH - CSC - Exjobb (Swedish))
* L'aide-soignante
* L'Anthropologie
* L'Encéphale
* L'Endocrinologo (Italian)
* L'Évolution psychiatrique
* L'homme – Revue française d'anthropologie
* L’Année sociologique (French) (AS)
* La Presse Médicale
* La radiologia medica
* La Revue d'Homéopathie
* La revue de l'infirmière
* La revue de médecine interne
* La revue de médecine légale
* La revue de santé scolaire et universitaire
* La Revue Gestion et Organisation
* La Revue Sage-Femme
* La Rivista Italiana della Medicina di Laboratorio - Italian Journal of Laboratory Medicine (Italian)
* Lab Animal
* Lab on a Chip
* Labor History
* Laboratory Investigation
* Labour Economics
* Läkartidningen
* Land
* Land Degradation & Development (LDD)
* Land Use Policy
* Landes Bioscience Journals
* Landscape and Ecological Engineering (Landscape Ecol Eng)
* Landscape and Urban Planning
* Landscape Ecology (Landscape Ecol)
* Landscape Research
* Landslides
* Langenbeck's Archives of Surgery (Langenbecks Arch Surg)
* Langmuir
* Language
* Language and Cognitive Processes
* Language and Communication
* Language and Education
* Language and Intercultural Communication
* Language Awareness
* Language in Society
* Language Policy (Lang Policy)
* Language Resources and Evaluation (Lang Resources & Evaluation)
* Language Sciences
* Language Testing in Asia
* Language, Culture and Curriculum
* Languages
* Laparoscopic, Endoscopic and Robotic Surgery
* Large-scale Assessments in Education
* Laryngo-Rhino-Otologie
* Laser & Photonics Reviews
* Laser Physics
* Laser Physics Letters
* Lasers in Manufacturing and Materials Processing
* Lasers in Medical Science (Lasers Med Sci)
* Laterality: Asymmetries of Body, Brain and Cognition
* Latin American and Caribbean Ethnic Studies
* Latin American Economic Review
* Latin American Perspectives (LAP)
* Latin American Research Review
* Law & Society Review
* Law and Critique (Law Critique)
* Law and Human Behavior
* Laws
* LCGC
* Le Mouvement Social (French)
* Le Pharmacien Hospitalier et Clinicien
* Le Praticien en anesthésie réanimation
* Le tapuscrit (École des hautes études en sciences sociales) (author-date, French) (Tapuscrit-EHESS)
* Le tapuscrit (École des hautes études en sciences sociales) (note, French) (Tapuscrit-EHESS)
* Leadership and Management in Engineering
* Learning & Memory
* Learning and Individual Differences
* Learning and Instruction
* Learning and Motivation
* Learning Environments Research (Learning Environ Res)
* Learning, Culture and Social Interaction
* Learning, Media and Technology
* Leeds Beckett University - Harvard
* Leeds Metropolitan University - Harvard
* Legal and Criminological Psychology
* Legal Medicine
* Leiden Journal of International Law (LJIL)
* Leidraad voor juridische auteurs (Dutch) (Leidraad)
* Leisure Studies
* Leisure/Loisir
* Leprosy Review
* Les Journées de la Recherche Avicole (French)
* Les Journées de la Recherche Porcine (French)
* Lethaia
* Lettera Matematica
* Letters in Applied Microbiology (LAM)
* Letters in Mathematical Physics (Lett Math Phys)
* Letters in Spatial and Resource Sciences (Lett Spat Resour Sci)
* Lettres et Sciences Humaines (biblio et notes, French)
* Leukemia
* Leukemia Research
* Leukemia Research Reports
* Leukemia Supplements
* Leviathan (German)
* Lexicography
* LexisNexis Québec (Guide Lluelles, no Ibid., French - Canada) (LexisNexis Québec)
* Library and Information Science Research
* Library Collections, Acquisitions and Technical Services
* Life
* Life Sciences
* Life Sciences in Space Research
* Life Sciences, Society and Policy
* Lifetime Data Analysis (Lifetime Data Anal)
* Light: Science & Applications
* Limnetica
* Limnologica
* Limnology
* Limnology and Oceanography
* Lindbergia
* Linear Algebra and Its Applications
* Linear and Multilinear Algebra
* Lingua
* Lingua Sinica
* Linguistics and Education
* Linguistics and Philosophy (Linguist and Philos)
* Lipids
* Lipids in Health and Disease
* Liquid Crystals
* Liquid Crystals Reviews
* Liquid Crystals Today
* List Forum für Wirtschafts- und Finanzpolitik (German)
* LITHOS
* Lithosphere
* Liver Cancer
* Liver International
* Liver Research
* Liverpool Law Review (Liverpool Law Rev)
* Livestock Science
* LO SCALPELLO-OTODI Educational (Italian)
* Local Environment
* Local Government Law Journal (LGLJ)
* Logica Universalis (Log. Univers.)
* Logistics
* Logistics Research (Logist. Res.)
* Loisir et Société / Society and Leisure
* London Metropolitan University - Harvard
* London South Bank University - Harvard (harvard-lsbu)
* London South Bank University (numeric) (lsbu-numeric)
* Long Range Planning
* Longevity Sciences and Medicine
* Low Temperature Physics
* Lubricants
* Lund University School of Economics and Management (LUSEM)
* Lung
* Lung Cancer
* Lung Cancer Management
* Lung India
* Lupus Science & Medicine
* LWT
* mAbs
* Macedonian Journal of Medical Sciences
* Machine Learning (Mach Learn)
* Machine Translation
* Machine Vision and Applications
* Machines
* Macromolecular Reaction Engineering
* Macromolecules
* Magister
* Magnetic Resonance Imaging
* Magnetic Resonance in Medicine
* Magnetic Resonance Materials in Physics, Biology and Medicine (Magn Reson Mater Phy)
* Magnetochemistry
* Maison de l'Orient et de la Méditerranée (French)
* Malaria Journal
* Mammal Research
* Mammal Review
* Mammalian Biology
* Mammalian Genome (Mamm Genome)
* Management & Avenir (French)
* Management Accounting Research
* Management international (MI)
* Management International Review (Manag Int Rev)
* Management Review Quarterly
* Management Science
* Managing Leisure
* Manchester Business School - Harvard
* Manchester Metropolitan University - Harvard
* Manchester University Press monographs
* Månedsskrift for almen praksis (Danish)
* Manual Therapy
* Manuel canadien de la référence juridique 7e édition (Guide McGill, French - Canada) (Guide McGill FR v7)
* Manuelle Medizin (German) (Manuelle Medizin)
* Manufacturing & Service Operations Management
* Manufacturing Letters
* Manuscripta Mathematica (manuscripta math.)
* Marine & Freshwater Research
* Marine and Coastal Fisheries
* Marine and Freshwater Behaviour and Physiology
* Marine and Petroleum Geology
* Marine Biodiversity (Mar Biodiv)
* Marine Biodiversity Records
* Marine Biology (Mar Biol)
* Marine Biotechnology (Mar Biotechnol)
* Marine Chemistry
* Marine Drugs
* Marine Ecology Progress Series
* Marine Environmental Research
* Marine Genomics
* Marine Geology
* Marine Geophysical Research (Mar Geophys Res)
* Marine Micropaleontology
* Marine Policy
* Marine Pollution Bulletin
* Marine Structures
* Marine Systems & Ocean Technology
* Maritime Policy & Management
* Maritime Studies
* Marketing Letters (Mark Lett)
* Mastozoologia Neotropical
* Materialia
* Materials
* Materials & Design
* Materials and Structures (Mater Struct)
* Materials Characterization
* Materials Chemistry and Physics
* Materials Discovery
* Materials for Renewable and Sustainable Energy (Mater Renew Sustain Energy)
* Materials Horizons
* Materials Letters
* Materials Research Bulletin
* Materials Research Letters
* Materials Science & Engineering A
* Materials Science & Engineering B
* Materials Science & Engineering C
* Materials Science & Engineering R
* Materials Science in Semiconductor Processing
* Materials Technology
* Materials Today
* Materials Today Chemistry
* Materials Today Communications
* Materials Today Energy
* Materials Today Nano
* Materials Today Physics
* Materials Today: Proceedings
* Maternal and Child Health Journal (Matern Child Health J)
* Maternal Health, Neonatology and Perinatology
* Mathematical and Computational Applications
* Mathematical and Computer Modelling
* Mathematical Biosciences
* Mathematical Geosciences (Math Geosci)
* Mathematical Medicine and Biology
* Mathematical Methods of Operations Research (Math Meth Oper Res)
* Mathematical Physics, Analysis and Geometry (Math Phys Anal Geom)
* Mathematical Programming (Math. Program.)
* Mathematical Programming Computation (Math. Prog. Comp.)
* Mathematical Sciences
* Mathematical Social Sciences
* Mathematics
* Mathematics and Computers in Simulation (MATCOM)
* Mathematics and Financial Economics (Math Finan Econ)
* Mathematics Education Research Journal (Math Ed Res J)
* Mathematics in Computer Science (Math.Comput.Sci.)
* Mathematics of Control, Signals, and Systems (Math. Control Signals Syst.)
* Mathematics-in-Industry Case Studies
* Mathematische Annalen (Math. Ann.)
* Mathematische Semesterberichte (German) (Math Semesterber)
* Mathematische Zeitschrift (Math. Z.)
* Matrix Biology
* Matter and Radiation at Extremes
* Maturitas
* Maxillofacial Plastic and Reconstructive Surgery
* Mayo Clinic Proceedings
* Mayo Clinic Proceedings: Innovations, Quality & Outcomes
* mBio
* McDonald Institute Monographs
* Measurement
* Measurement Science and Technology
* Meat Science
* Meccanica
* Mechanical Sciences
* Mechanical Systems and Signal Processing
* Mechanics of Advanced Materials and Modern Processes
* Mechanics of Materials
* Mechanics of Time-Dependent Materials (Mech Time-Depend Mater)
* Mechanics Research Communications
* Mechanism and Machine Theory
* Mechanisms of Ageing and Development
* Mechanisms of Development
* Mechatronics
* MedChemComm
* Médecine du Sommeil
* Médecine et Droit
* Médecine et Maladies Infectieuses
* Médecine Intensive Réanimation
* Médecine Nucléaire
* Médecine Palliative Soins de Support - Accompagnement - Ethique
* médecine/sciences
* Media, Culture & Society
* Medical & Biological Engineering & Computing (Med Biol Eng Comput)
* Medical Acupuncture
* Medical Care
* Medical Dosimetry (MDO)
* Medical Education
* Medical Engineering and Physics
* Medical Epigenetics
* Medical Gas Research
* Medical History
* Medical Humanities
* Medical Hypotheses
* Medical Image Analysis
* Medical Journal Armed Forces India
* Medical Microbiology and Immunology (Med Microbiol Immunol)
* Medical Molecular Morphology (Med Mol Morphol)
* Medical Mycology Case Reports
* Medical Oncology (Med Oncol)
* Medical Photonics
* Medical Physics
* Medical Principles and Practice
* Medical Science Educator
* Medical Sciences
* Medicina
* Medicina Clínica (Spanish)
* Medicina Fluminensis
* Medicina Intensiva (Spanish)
* Medicina Reproductiva y Embriología Clínica
* Medicinal Chemistry Research (Med Chem Res)
* Medicinal Research Reviews
* Medicine
* Medicine & Science in Sports & Exercise (MSSE)
* Medicine Studies
* Medicine, Conflict and Survival
* Medicine, Health Care and Philosophy (Med Health Care and Philos)
* Medicines
* Medicinskiy Akademicheskiy Zhurnal
* Mediterranean Journal of Mathematics
* Mediterranean Journal of Nutrition and Metabolism (Mediterr J Nutr Metab)
* Mediterranean Politics (fMed)
* medizinische genetik (German) (medizinische genetik)
* Medizinische Klinik - Intensivmedizin und Notfallmedizin (German) (Medizinische Klinik Intensivmedizin Notfallmedizin)
* Mélanges de l'Ecole française de Rome - Antiquité (French)
* Mélanges de l'Ecole française de Rome - Italie et Méditerranée modernes et contemporaines (French)
* Mélanges de l'Ecole française de Rome - Moyen Âge (French)
* Melanoma Management
* Melbourne Polytechnic - Harvard
* Melbourne School of Theology (MST)
* Membranes
* Memetic Computing (Memetic Comp.)
* memo - Magazine of European Medical Oncology (memo)
* Memórias do Instituto Oswaldo Cruz
* Memory
* Mental Health & Prevention
* Mental Health and Physical Activity
* Mental Health and Substance Use
* Mental Health, Religion & Culture
* Mentoring & Tutoring: Partnership in Learning
* Mercatus Center
* Meta Gene
* Metabolic Brain Disease (Metab Brain Dis)
* Metabolic Engineering
* Metabolic Engineering Communications
* Metabolism
* Metabolites
* Metabolomics
* Metacognition and Learning (Metacognition Learning)
* Metal Powder Report
* Metallography, Microstructure, and Analysis (Metallogr. Microstruct. Anal.)
* Metallomics
* Metallurgical and Materials Transactions
* Metallurgical and Materials Transactions A (Metall and Mat Trans A)
* Metallurgical and Materials Transactions B (Metall and Materi Trans B)
* Metallurgical and Materials Transactions E
* Metals
* Metamaterials
* Metascience
* Meteoritics & Planetary Science
* Meteorological Applications (Meteorol. Appl.)
* Meteorological Monographs
* Meteorology and Atmospheric Physics (Meteorol Atmos Phys)
* Methodology and Computing in Applied Probability (Methodol Comput Appl Probab)
* Methodology: European Journal of Research Methods for the Behavioral and Social Sciences
* Methods
* Methods and Applications in Fluorescence
* Methods and Protocols
* Methods in Ecology and Evolution
* Methods in Oceanography
* Methods of Information in Medicine
* MethodsX
* Métiers de la petite enfance
* Metrika
* Metrologia
* Métropolitiques (French)
* Micro and Nano Systems Letters
* Microarrays
* Microbes and Infection
* Microbial Biotechnology
* Microbial Cell (MIC)
* Microbial Cell Factories
* Microbial Drug Resistance
* Microbial Ecology (Microb Ecol)
* Microbial Genomics
* Microbial Pathogenesis
* Microbial Risk Analysis
* Microbiological Research
* Microbiology
* Microbiology and Molecular Biology Reviews (MMBR)
* Microbiology Australia
* Microbiology Society
* Microbiology Spectrum
* Microbiome
* Microchemical Journal
* Microchimica Acta (Microchim Acta)
* Microelectronic Engineering
* Microelectronics Journal
* Microelectronics Reliability
* Microfluidics and Nanofluidics (Microfluid Nanofluid)
* Microgravity Science and Technology (Microgravity Sci. Technol.)
* Micromachines
* Micron
* Microorganisms
* Microporous and Mesoporous Materials
* Microprocessors and Microsystems
* Microscopy and Microanalysis
* Microsystem Technologies (Microsyst Technol)
* Microvascular Research
* Middle East Critique
* Middle East Fertility Society Journal
* Midwifery
* Migration and Development
* Milan Journal of Mathematics (Milan J. Math.)
* Military Medical Research
* Military Medicine
* Military Psychology
* Mimesis Edizioni (Italian)
* Mind & Language
* Mind & Society (Mind Soc)
* Mindfulness
* Mindfulness & Compassion
* Minds and Machines (Minds & Machines)
* Mine Water and the Environment (Mine Water Environ)
* Mineral Economics (Miner Econ)
* Mineralium Deposita (Miner Deposita)
* Mineralogical Magazine
* Mineralogy and Petrology (Miner Petrol)
* Minerals
* Minerals Engineering
* Minerva
* Minerva Medica
* MIS Quarterly (MISQ)
* Mitigation and Adaptation Strategies for Global Change (Mitig Adapt Strateg Glob Change)
* Mitochondrion
* Mitteilungen Klosterneuburg
* Mobile DNA
* Mobile Genetic Elements
* Mobile Networks and Applications (Mobile Netw Appl)
* Mobilities
* Modeling Earth Systems and Environment
* Modelling and Simulation in Materials Science and Engineering
* Modern Electronic Materials
* Modern Humanities Research Association 3rd edition (author-date) (MHRA)
* Modern Humanities Research Association 3rd edition (note with bibliography) (MHRA)
* Modern Italy
* Modern Language Association 6th edition (note) (MLA)
* Modern Language Association 7th edition (MLA)
* Modern Language Association 7th edition (underline) (MLA)
* Modern Language Association 7th edition (with URL) (MLA)
* Modern Language Association 8th edition (MLA)
* Modern Language Review
* Modern Pathology
* Modern Phytomorphology (ModPhytomorphol)
* Mohr Siebeck - Recht (German - Austria)
* Molbank
* Molecular & Biochemical Parasitology
* Molecular & Cellular Proteomics
* Molecular and Cellular Biochemistry (Mol Cell Biochem)
* Molecular and Cellular Biology (MCB)
* Molecular and Cellular Endocrinology
* Molecular and Cellular Neuroscience
* Molecular and Cellular Pediatrics
* Molecular and Cellular Probes
* Molecular and Cellular Therapies
* Molecular and Clinical Oncology
* Molecular Aspects of Medicine
* Molecular Astrophysics
* Molecular Autism
* Molecular Biology and Evolution
* Molecular Biology of the Cell (MBoC)
* Molecular Biology Reports (Mol Biol Rep)
* Molecular BioSystems
* Molecular Biotechnology (Mol Biotechnol)
* Molecular Brain
* Molecular Breeding (Mol Breeding)
* Molecular Cancer
* Molecular Cancer Research
* Molecular Cancer Therapeutics
* Molecular Catalysis
* Molecular Cell
* Molecular Cytogenetics
* Molecular Diagnosis & Therapy (Mol Diagn Ther)
* Molecular Diversity (Mol Divers)
* Molecular Ecology
* Molecular Endocrinology
* Molecular Genetics and Genomics (Mol Genet Genomics)
* Molecular Genetics and Metabolism
* Molecular Genetics and Metabolism Reports
* Molecular Imaging and Biology (Mol Imaging Biol)
* Molecular Immunology
* Molecular Medicine Reports
* Molecular Metabolism (MOLMET)
* Molecular Microbiology
* Molecular Neurobiology (Mol Neurobiol)
* Molecular Neurodegeneration
* Molecular Nutrition & Food Research
* Molecular Oncology
* Molecular Pain
* Molecular Pharmaceutics (Mol. Pharm.)
* Molecular Pharmacology
* Molecular Phylogenetics and Evolution
* Molecular Plant
* Molecular Plant Pathology
* Molecular Plant-Microbe Interactions (MPMI)
* Molecular Psychiatry
* Molecular Psychiatry (letters to the editor)
* Molecular Simulation
* Molecular Systems Biology
* Molecular Systems Design & Engineering
* Molecular Therapy
* Molecular Therapy - Methods & Clinical Development
* Molecular Therapy - Nucleic Acids
* Molecular Therapy - Oncolytics
* Molecular Vision
* Molecules
* Monash Bioethics Review
* Monash University - Harvard
* Monatshefte für Chemie - Chemical Monthly (Monatsh Chem)
* Monatshefte für Mathematik (Monatsh Math)
* Monatsschrift Kinderheilkunde (German) (Monatsschrift Kinderheilkunde)
* Mondes en développement (French) (MED)
* Monthly Weather Review
* Moore Theological College
* Moorlands College
* Morphologie
* Morphology
* MorphoMuseuM (M3)
* Mortality
* Motivation and Emotion (Motiv Emot)
* Motricité cérébrale
* Mount Sinai Journal of Medicine
* Movement Ecology
* mSphere
* mSystems
* Mucosal Immunology
* Multibody System Dynamics (Multibody Syst Dyn)
* Multidimensional Systems and Signal Processing (Multidim Syst Sign Process)
* Multidisciplinary Digital Publishing Institute (MDPI)
* Multidisciplinary Respiratory Medicine
* Multilingual Education
* Multimedia Systems
* Multimedia Tools and Applications (Multimed Tools Appl)
* Multimodal Technologies and Interaction
* Multiple Sclerosis and Demyelinating Disorders
* Multiple Sclerosis and Related Disorders
* Multiple Sclerosis Journal
* Musculoskeletal Science and Practice
* MUSCULOSKELETAL SURGERY (Musculoskelet Surg)
* Museum Management and Curatorship
* Music Education Research
* Music Theory Spectrum
* Mutagenesis (Mutage)
* Mutation Research - Fundamental and Molecular Mechanisms of Mutagenesis
* Mutation Research - Genetic Toxicology and Environmental Mutagenesis
* Mutation Research-Reviews in Mutation Research
* mUX: The Journal of Mobile User Experience
* Mycologia
* Mycological Progress (Mycol Progress)
* Mycology
* Mycopathologia
* Mycorrhiza
* Mycoscience
* Mycotoxin Research (Mycotoxin Res)
* Myrmecological News
* Nano Biomedicine and Engineering
* Nano Communication Networks
* Nano Convergence
* Nano Energy
* Nano Letters (Nano Lett.)
* Nano Today
* Nano-Micro Letters
* Nano-Structures & Nano-Objects
* NanoEthics (Nanoethics)
* NanoImpact
* Nanomaterials
* Nanomedicine
* Nanoscale
* Nanoscale Horizons
* Nanoscale Research Letters
* Nanoscience Methods
* Nanotechnology
* Nanotechnology for Environmental Engineering
* National Academy Science Letters (Natl. Acad. Sci. Lett.)
* National Archives of Australia
* National Identities
* National Institute of Health Research (NIHR)
* National Institute of Technology Karnataka (NITK)
* National Library of Medicine (NLM)
* National Library of Medicine (brackets, no "et al.") (NLM)
* National Library of Medicine (grant proposals with PMCID/PMID) (NLM)
* National Medical Journal of China
* National Natural Science Foundation of China (Chinese) (NSFC)
* National Science Foundation (grant proposals) (NSF)
* National University of Singapore - Department of Geography - Harvard (NUS-Geography)
* Nationalities Papers
* Natur und Landschaft (German)
* Natural Computing (Nat Comput)
* Natural Gas Industry B
* Natural Hazards (Nat Hazards)
* Natural Hazards and Earth System Sciences
* Natural Hazards and Earth System Sciences Discussions
* Natural Hazards Review
* Natural Language & Linguistic Theory (Nat Lang Linguist Theory)
* Natural Language Semantics (Nat Lang Semantics)
* Natural Product Reports
* Natural Product Research
* Natural Products and Bioprospecting
* Natural Resources Research (Nat Resour Res)
* Nature
* Nature (no "et al.")
* Nature (no superscript)
* Nature Biotechnology
* Nature Cell Biology
* Nature Chemical Biology
* Nature Chemistry
* Nature Climate Change
* Nature Communications
* Nature Digest
* Nature Genetics
* Nature Geoscience
* Nature Immunology
* Nature Materials
* Nature Medicine
* Nature Methods
* Nature Nanotechnology
* Nature Neuroscience
* Nature Neuroscience (brief communications)
* Nature Photonics
* Nature Physics
* Nature Protocols
* Nature Publishing Group - Vancouver
* Nature Reviews Cancer
* Nature Reviews Cardiology
* Nature Reviews Clinical Oncology
* Nature Reviews Drug Discovery
* Nature Reviews Endocrinology
* Nature Reviews Gastroenterology & Hepatology
* Nature Reviews Genetics
* Nature Reviews Immunology
* Nature Reviews Microbiology
* Nature Reviews Molecular Cell Biology
* Nature Reviews Nephrology
* Nature Reviews Neurology
* Nature Reviews Neuroscience
* Nature Reviews Rheumatology
* Nature Reviews Urology
* Nature Structural & Molecular Biology
* Natures Sciences Sociétés (NSS)
* Naunyn-Schmiedeberg's Archives of Pharmacology (Naunyn-Schmiedeberg's Arch Pharmacol)
* Navigation
* NCCR Mediality. Medienwandel - Medienwechsel - Medienwissen (German) (NCCR Mediality)
* NDT and E International
* Nederlands Tijdschrift Voor Geneeskunde (Dutch)
* Nefrología Latinoamericana
* Negative Results (Neg Res)
* NeHeT (French)
* Neohelicon
* Neonatologie Scan
* Neonatology
* Neophilologus
* Neotropical Entomology (Neotrop Entomol)
* Nephrologie et Thérapeutique
* Nephrology
* Nephrology Dialysis Transplantation
* Nephron
* Nephron Clinical Practice
* Nephron Experimental Nephrology
* Nephron Extra
* Nephron Physiology
* Netherlands Heart Journal (Neth Heart J)
* Netherlands International Law Review
* NETNOMICS: Economic Research and Electronic Networking (Netnomics)
* Network Modeling Analysis in Health Informatics and Bioinformatics (Netw Model Anal Health Inform Bioinforma)
* Networks and Spatial Economics (Netw Spat Econ)
* Neue Juristische Wochenschrift (German) (NJW (Articles))
* Neumología y Cirugía de Tórax
* Neural Computing and Applications (Neural Comput & Applic)
* Neural Development
* Neural Networks
* Neural Plasticity (Neural Plast)
* Neural Processing Letters (Neural Process Lett)
* Neuro-Oncology
* Neurobiology of Aging
* Neurobiology of Disease
* Neurobiology of Learning and Memory
* Neurobiology of Pain
* Neurobiology of Sleep and Circadian Rhythms
* Neurobiology of Stress
* Neurocase
* Neurochemical Research (Neurochem Res)
* Neurochemistry International
* Neurochirurgie
* Neurocomputing
* Neurocritical Care (Neurocrit Care)
* Neurodegenerative Disease Management
* Neurodegenerative Diseases
* Neuroendocrinology
* Neuroendocrinology Letters (NEL)
* Neuroepidemiology
* Neuroepigenetics
* Neuroethics
* Neuroforum (German)
* neurogenetics (Neurogenetics)
* NeuroImage
* NeuroImage: Clinical
* Neuroimaging Clinics of North America (NIC)
* Neuroimmunomodulation
* Neuroinformatics (Neuroinform)
* Neurología (Spanish) (NRL)
* Neurología Argentina (Spanish) (NEUARG)
* Neurologia i Neurochirurgia Polska
* Neurological Sciences (Neurol Sci)
* Neurology
* Neurology and Therapy (Neurol Ther)
* Neurology India
* Neurology International Open
* Neurology, Psychiatry and Brain Research
* NeuroMetals
* NeuroMolecular Medicine (Neuromol Med)
* Neuromuscular Disorders
* Neuron
* Neuropathology
* Neuropeptides
* Neuropharmacology
* Neurophotonics
* Neurophysiologie Clinique
* Neuropraxis (Dutch)
* Neuropsychiatric Electrophysiology
* neuropsychiatrie (German) (Neuropsychiatr)
* Neuropsychiatrie de l'enfance et de l'adolescence
* Neuropsychiatry
* Neuropsychobiology
* Neuropsychologia
* Neuropsychological Rehabilitation
* Neuropsychology
* Neuropsychology Review (Neuropsychol Rev)
* Neuropsychopharmacology
* Neuroradiologie Scan
* Neuroradiology
* Neurorehabilitation and Neural Repair
* NeuroReport
* Neuroscience
* Neuroscience and Biobehavioral Reviews
* Neuroscience Letters
* Neuroscience Research
* Neurosignals
* Neurosurgery
* Neurosurgery Clinics of North America (NEC)
* Neurosurgical Focus
* Neurosurgical Review (Neurosurg Rev)
* Neurotoxicity Research (Neurotox Res)
* Neurotoxicology
* Neurotoxicology and Teratology
* Neurourology and Urodynamics
* Neurovascular Imaging
* New Astronomy
* New Astronomy Reviews
* New BIOTECHNOLOGY
* New Forests
* New Genetics and Society
* New Hart's Rules: The Oxford Style Guide
* New Horizons in Clinical Case Reports
* New Horizons in Translational Medicine
* New Ideas in Psychology
* New Journal of Chemistry
* New Journal of Physics
* New Microbes and New Infections
* New Negatives in Plant Science
* New Phytologist
* New Review of Film and Television Studies
* New Solutions
* New Testament Studies
* New Writing
* New Zealand Dental Journal
* New Zealand Economic Papers
* New Zealand Journal of Educational Studies
* New Zealand Journal of Forestry Science
* New Zealand Journal of Medical Laboratory Science
* New Zealand Plant Protection
* New Zealand Veterinary Journal
* Newborn and Infant Nursing Reviews
* Newcastle University - Harvard
* NFS Journal
* Nigerian Food Journal
* Nigerian Journal of Genetics
* Nigerian Journal of Pharmaceutical Sciences
* Nigerian Journal Of Physiological Sciences
* Nigerian Medical Journal
* Nitric Oxide
* NJAS - Wageningen Journal of Life Sciences
* Non-Coding RNA
* Non-coding RNA Research
* Nonlinear Analysis
* Nonlinear Analysis: Hybrid Systems
* Nonlinear Analysis: Real World Applications
* Nonlinear Differential Equations and Applications NoDEA (Nonlinear Differ. Equ. Appl.)
* Nonlinear Dynamics (Nonlinear Dyn)
* Nonlinear Processes in Geophysics
* Nonlinear Processes in Geophysics Discussions
* Nonlinearity
* Nordic Journal of Botany
* Nordic Journal of Music Therapy
* Nordic Psychology
* Nordic Pulp & Paper Research Journal (Nord. Pulp Paper Res. J.)
* Nordic Social Work Research
* Norma Portuguesa 405 (Portuguese) (NP 405)
* North American Journal of Aquaculture
* North American Journal of Economics and Finance
* North American Journal of Fisheries Management
* North Carolina Medical Journal
* North-West University - Harvard (NWU)
* Northeastern Naturalist
* Northern Territory Law Journal and Reports (NTLJ)
* Notfall +  Rettungsmedizin (German) (Notfall Rettungsmedizin)
* Notfallmedizin up2date
* Nottingham Trent University Library - Harvard (NTU Library - Harvard)
* Nowa Audiofonologia (Polish) (Now Audiofonol)
* NPG Asia Materials
* NPG Neurologie - Psychiatrie - Gériatrie
* NRIAG Journal of Astronomy and Geophysics
* Nuclear and Particle Physics Proceedings
* Nuclear Energy and Technology
* Nuclear Engineering and Design
* Nuclear Engineering and Technology
* Nuclear Fusion
* Nuclear Inst. and Methods in Physics Research, A
* Nuclear Inst. and Methods in Physics Research, B
* Nuclear Materials and Energy
* Nuclear Medicine and Biology
* Nuclear Medicine and Molecular Imaging (Nucl Med Mol Imaging)
* Nuclear Physics, Section A
* Nuclear Physics, Section B
* Nuclear Receptor Signaling (NRS)
* Nuclear Science and Engineering (NSE)
* Nuclear Technology (NT)
* Nucleic Acids Research
* Nucleic Acids Research - Web Server Issue
* Nucleus
* Numerical Algorithms (Numer Algor)
* Numerische Mathematik (Numer. Math.)
* Nurse Education in Practice
* Nurse Education Today
* Nurse Leader
* Nursing for Women's Health
* Nursing Inquiry
* Nursing Outlook
* NursingPlus Open
* Nutrient Cycling in Agroecosystems (Nutr Cycl Agroecosyst)
* Nutrients
* Nutrition
* Nutrition & Metabolism
* Nutrition and Diabetes
* Nutrition clinique et métabolisme
* Nutrition Journal
* Nutrition Research
* Nutrition Reviews
* Nutrition, Metabolism and Cardiovascular Diseases
* o-bib (German)
* O.W. Barth Verlag (German)
* Obafemi Awolowo University - Faculty of Technology (OAU Tech)
* Obere Extremität (German) (Obere Extremität)
* Obesity
* Obesity Facts
* Obesity Medicine
* Obesity Research & Clinical Practice
* Obesity Surgery (OBES SURG)
* Obstetrics & Gynecology Science (Obstet Gynecol Sci)
* Occupation, Participation and Health
* Occupational and Environmental Medicine
* Occupational Medicine
* Ocean and Coastal Management
* Ocean Dynamics
* Ocean Engineering
* Ocean Modelling
* Ocean Science
* Ocean Science Discussions
* Oceanography
* Oceanologia
* Ocular Immunology & Inflammation
* Ocular Oncology and Pathology
* Odontology
* Oecologia
* Oecologia Australis (OA)
* Oikos
* Omega
* Oncogene
* Oncogenesis
* OncoImmunology
* Oncology
* Oncology and Therapy
* Oncology Letters
* Oncology Reports
* Oncology Research and Treatment
* Oncology Signaling
* Oncoscience
* Oncotarget
* Onderstepoort Journal of Veterinary Research
* One Health
* Online Currents (OLC)
* Online Social Networks and Media
* OP Journal
* Open Biology
* Open Economies Review (Open Econ Rev)
* Open Geospatial Data, Software and Standards
* Open Heart
* Open Learning: The Journal of Open, Distance and e-Learning
* OpenNano
* Operational Research (Oper Res Int J)
* Operations Management Research (Oper Manag Res)
* Operations Research
* Operations Research for Health Care
* Operations Research Letters
* Operations Research Perspectives
* Operative Dentistry
* Operative Orthopädie und Traumatologie (German) (Operative Orthopädie Traumatologie)
* Ophthalmic & Physiological Optics
* Ophthalmic Epidemiology
* Ophthalmic Genetics
* Ophthalmic Plastic and Reconstructive Surgery (OPRS)
* Ophthalmic Research
* Ophthalmic Surgery, Lasers & Imaging Retina
* Ophthalmologica
* Ophthalmologica Extra
* Ophthalmology
* Ophthalmology and Therapy (Ophthalmol Ther)
* Ophthalmology Retina
* OPSEARCH
* Optical and Quantum Electronics (Opt Quant Electron)
* Optical Engineering
* Optical Fiber Technology
* Optical Materials
* Optical Materials Express
* Optical Nanoscopy
* Optical Review
* Optical Switching and Networking
* Optics and Laser Technology
* Optics and Lasers in Engineering
* Optics Communications
* Optics Express
* Optik
* Optimization
* Optimization and Engineering (Optim Eng)
* Optimization Letters (Optim Lett)
* Opto-Electronics Review
* Optometry & Vision Science
* OR Spectrum
* Oral and Maxillofacial Surgery (Oral Maxillofac Surg)
* Oral and Maxillofacial Surgery Cases
* Oral Diseases
* Oral Oncology
* Oral Radiology (Oral Radiol)
* Oral Surgery, Oral Medicine, Oral Pathology and Oral Radiology
* Order
* Ore Geology Reviews
* Organic & Biomolecular Chemistry
* Organic Agriculture (Org. Agr.)
* Organic Chemistry Frontiers
* Organic Electronics
* Organic Geochemistry
* Organic Letters (Org. Lett.)
* Organic Process Research & Development (Org. Process Res. Dev.)
* Organisationsberatung, Supervision, Coaching (German) (Organisationsberat Superv Coach)
* Organisms Diversity & Evolution (Org Divers Evol)
* Organization
* Organization Science
* Organization Studies
* Organizational Behavior and Human Decision Processes
* Organogenesis
* Organometallics
* Oriental Pharmacy and Experimental Medicine (Orient Pharm Exp Med)
* Origins of Life and Evolution of Biospheres (Orig Life Evol Biosph)
* ORL
* Ornitología Neotropical
* Orphanet Journal of Rare Diseases
* Ortho Magazine
* Orthodontic Waves
* Orthopädie und Unfallchirurgie up2date
* Orthopaedics & Traumatology: Surgery & Research
* Orthopedic Clinics of North America (OCL)
* Orthopedics
* Oryx
* OSCOLA (Oxford University Standard for Citation of Legal Authorities) (OSCOLA)
* OSCOLA (Oxford University Standard for Citation of Legal Authorities) (no Ibid.) (OSCOLA)
* Osteoarthritis and Cartilage
* Osteoporosis and Sarcopenia
* Osteoporosis International (Osteoporos Int)
* Österreichische Zeitschrift für Politikwissenschaft (German - Austria) (OEZP)
* Österreichische Zeitschrift für Soziologie (German) (Österreich Z Soziol)
* Ostrava Journal of English Philology
* Otolaryngologia Polska
* Otolaryngology - Head and Neck Surgery
* Otolaryngology Case Reports
* Otto-von-Guericke-Universität Magdeburg - Medizinische Fakultät (numeric)
* Oxford Art Journal
* Oxford Brookes University - Faculty of Health and Life Sciences - Harvard
* Oxford Centre for Mission Studies - Harvard (OCMS)
* Oxford German Studies
* Oxford Review of Education
* Oxford Studies in Ancient Philosophy
* Oxford Studies on the Roman Economy
* Oxford University Press HUMSOC (Oxford HUMSOC)
* Oxford University Press SciMed (author-date)
* Oxford University Press SciMed (numeric)
* Oxidation of Metals
* Oxymag
* Pacific Journal of Mathematics for Industry
* Pacific Science Review
* Pacific Science Review A: Natural Science and Engineering
* Pacific Science Review B: Humanities and Social Sciences
* Pacific-Basin Finance Journal
* Pädagogische Hochschule Fachhochschule Nordwestschweiz (German - Switzerland) (Schreibberatung PH FHNW (Empfehlungen))
* Pädagogische Hochschule Heidelberg (German) (PH Heidelberg)
* Pädagogische Hochschule Vorarlberg (German) (PH Vorarlberg)
* Paddy and Water Environment (Paddy Water Environ)
* Pädiatrie & Pädologie (German)
* Pädiatrie up2date
* Paediatric and Perinatal Epidemiology (PPE)
* Paediatric Respiratory Reviews
* PAIN
* Pain and Therapy (Pain Ther)
* Pain Management
* Pain Management Nursing
* Pakistan Journal of Medical Research
* Pakistan Journal of Otolaryngology, Head and Neck Surgery
* Pakistan Veterinary Journal (PKV)
* Palaeobiodiversity and Palaeoenvironments (Palaeobio Palaeoenv)
* Palaeogeography, Palaeoclimatology, Palaeoecology
* Palaeontographica Abteilung B: Palaeobotany - Palaeophytology
* Palaeontologia Electronica
* Palaeontology
* Palaeovertebrata
* Palaeoworld
* Palaios
* Paläontologische Zeitschrift (Paläontol Z)
* Paleobiology
* Paleoceanography
* Palynology
* Pancreatology
* Papillomavirus Research
* Parallel Computing
* Parasite Epidemiology and Control
* Parasites & Vectors
* Parasitology
* Parasitology International
* Parasitology Research (Parasitol Res)
* Parkinsonism and Related Disorders
* Particle and Fibre Toxicology
* Particuology
* Past & Present
* Pastoral Care in Education
* Pastoral Psychology (Pastoral Psychol)
* Pastoralism
* Pathobiology
* Pathogenesis
* Pathogens
* Pathogens and Disease
* Pathology
* Pathology - Research and Practice
* Pathology & Oncology Research (Pathol. Oncol. Res.)
* Pathology International
* Pathophysiology
* Patient Education and Counseling
* Patient Safety in Surgery
* Pattern Analysis and Applications (Pattern Anal Applic)
* Pattern Recognition
* Pattern Recognition Letters
* Peace and Conflict: Journal of Peace Psychology
* Pedagogická orientace
* Pedagogies: An International Journal
* Pedagogy, Culture & Society
* Pediatria Polska
* Pediatric Allergy and Immunology
* Pediatric Anesthesia
* Pediatric Annals
* Pediatric Blood & Cancer
* Pediatric Cardiology (Pediatr Cardiol)
* Pediatric Critical Care Medicine
* Pediatric Dental Journal
* Pediatric Dentistry Case Reports
* Pediatric Drugs (Pediatr Drugs)
* Pediatric Hematology Oncology Journal
* Pediatric Infectious Disease
* Pediatric Nephrology (Pediatr Nephrol)
* Pediatric Neurology
* Pediatric Neurosurgery
* Pediatric Physical Therapy
* Pediatric Radiology (Pediatr Radiol)
* Pediatric Research
* Pediatric Rheumatology
* Pediatric Surgery International (Pediatr Surg Int)
* Pediatrics
* Pediatrics International
* Pedobiologia - Journal of Soil Ecology
* Peer-to-Peer Networking and Applications (Peer-to-Peer Netw. Appl.)
* PeerJ
* Peptides
* Perfectionnement en Pédiatrie
* Performance Enhancement & Health
* Performance Evaluation
* Periodica Mathematica Hungarica
* Periodicum Biologorum
* Periodontology 2000
* Perioperative Care and Operating Room Management
* Perioperative Medicine
* Permafrost and Periglacial Processes
* Person-Centered & Experiential Psychotherapies
* Personal and Ubiquitous Computing (Pers Ubiquit Comput)
* Personality and Individual Differences
* Personality Disorders: Theory, Research, and Treatment
* Personalized Medicine
* Personalized Medicine in Psychiatry
* Personalized Medicine Universe
* Perspectives
* Perspectives in Ecology and Conservation
* Perspectives in Medicine
* Perspectives in Plant Ecology, Evolution and Systematics
* Perspectives in Science
* Perspectives on Medical Education (Perspect Med Educ)
* Perspectives on Politics
* Perspectives on Sexual and Reproductive Health
* Perspectives: Policy and Practice in Higher Education
* Pervasive and Mobile Computing
* Pest Management Science (PMS)
* Pesticide Biochemistry and Physiology
* Petit Chicago (author-date, French - Canada) (Petit Chicago)
* Petroleum
* Petroleum Geoscience
* Petroleum Research
* Petroleum Science
* Pflügers Archiv - European Journal of Physiology (Pflugers Arch - Eur J Physiol)
* Pharmaceutical Bioprocessing
* Pharmaceutical Medicine (Pharm Med)
* Pharmaceutical Methods
* Pharmaceutical Patent Analyst
* Pharmaceutical Research (Pharm Res)
* Pharmaceuticals
* Pharmaceutics
* Pharmaceutisch Weekblad (Dutch)
* PharmacoEconomics
* PharmacoEconomics Italian Research Articles (Pharmacoecon. Ital. Res. Artic.)
* PharmacoEconomics Spanish Research Articles (Spanish) (Pharmacoecon. Span. Res. Artic.)
* Pharmacoepidemiology and Drug Safety
* Pharmacogenomics
* Pharmacognosy Journal
* Pharmacognosy Magazine
* Pharmacognosy Reviews
* Pharmacological Reports
* Pharmacological Research
* Pharmacological Reviews
* Pharmacology
* Pharmacology and Therapeutics
* Pharmacology, Biochemistry and Behavior
* Pharmacopsychiatry
* Pharmacotherapy
* Pharmacy
* Pharmacy Today
* PharmaNutrition
* Phase Transitions
* Phenomenology and the Cognitive Sciences (Phenom Cogn Sci)
* Philippika (German)
* Philippine Political Science Journal
* Philosophia
* Philosophia Scientiæ
* Philosophical Explorations
* Philosophical Psychology
* Philosophical Studies (Philos Stud)
* Philosophical Transactions of the Royal Society A
* Philosophical Transactions of the Royal Society B
* Philosophies
* Philosophiques (French)
* Philosophy & Technology (Philos. Technol.)
* Philosophy of Management
* Philosophy, Ethics, and Humanities in Medicine
* Photoacoustics
* Photochemical & Photobiological Sciences
* Photodiagnosis and Photodynamic Therapy
* Photonic Network Communications (Photon Netw Commun)
* Photonics
* Photosynthesis Research (Photosynth Res)
* Phycological Research (Phycol. Res.)
* Phyllomedusa
* Physica A: Statistical Mechanics and its Applications
* Physica B: Physics of Condensed Matter
* Physica C: Superconductivity and its applications
* Physica D: Nonlinear Phenomena
* Physica E: Low-dimensional Systems and Nanostructures
* Physica Medica
* Physica Scripta
* Physical Biology
* Physical Chemistry Chemical Physics
* Physical Communication
* Physical Education and Sport Pedagogy
* Physical Review A
* Physical Review B
* Physical Review C
* Physical Review D
* Physical Review E
* Physical Review Letters
* Physical Therapy in Sport
* Physics and Chemistry of Liquids
* Physics and Chemistry of Minerals (Phys Chem Minerals)
* Physics and Chemistry of the Earth
* Physics and Imaging in Radiation Oncology
* Physics Education
* Physics in Medicine
* Physics in Medicine and Biology
* Physics Letters A
* Physics Letters B
* Physics of Fluids
* Physics of Life Reviews
* Physics of Plasmas
* Physics of the Dark Universe
* Physics of the Earth and Planetary Interiors
* Physics Reports
* Physics-Uspekhi
* Physikalische Medizin, Rehabilitationsmedizin, Kurortmedizin
* Physiological and Biochemical Zoology
* Physiological and Molecular Plant Pathology
* Physiological Genomics
* Physiological Measurement
* Physiological Reviews
* Physiology
* Physiology & Behavior
* Physiology and Molecular Biology of Plants (Physiol Mol Biol Plants)
* Physiotherapy
* Phytochemistry
* Phytochemistry Letters
* Phytochemistry Reviews (Phytochem Rev)
* Phytomedicine
* Phytoparasitica
* Phytopathology
* PiD - Psychotherapie im Dialog
* Pilot and Feasibility Studies
* Pisa University Press
* Pituitary
* Placenta
* Planetary and Space Science
* Planetary Science
* Planning Perspectives
* Planning Practice & Research (PPR)
* Planning Theory & Practice
* Plant & Cell Physiology
* Plant and Soil (Plant Soil)
* Plant Biology
* Plant Biotechnology Journal (PBJ)
* Plant Biotechnology Reports (Plant Biotechnol Rep)
* Plant Cell Reports (Plant Cell Rep)
* Plant Cell, Tissue and Organ Culture (Plant Cell Tiss Organ Cult)
* Plant Disease
* Plant Diversity
* Plant Ecology (Plant Ecol)
* Plant Foods for Human Nutrition (Plant Foods Hum Nutr)
* Plant Gene
* Plant Growth Regulation (Plant Growth Regul)
* Plant Methods
* Plant Molecular Biology (Plant Mol Biol)
* Plant Molecular Biology Reporter (Plant Mol Biol Rep)
* Plant Pathology
* Plant Physiology
* Plant Physiology and Biochemistry
* Plant Reproduction (Plant Reprod)
* Plant Science
* Plant Signaling & Behavior
* Plant Systematics and Evolution
* Plant, Cell & Environment
* Planta
* Planta Medica
* Planta Medica International Open
* Plants
* Plasma Chemistry and Plasma Processing (Plasma Chem Plasma Process)
* Plasma Physics and Controlled Fusion
* Plasma Science and Technology
* Plasma Sources Science and Technology
* Plasmid
* Plasmonics
* Plastic and Reconstructive Surgery
* Plastic and Reconstructive Surgery - Global open.
* PLOS Biology
* PLOS Computational Biology
* PLOS Genetics
* PLOS Medicine
* PLOS Neglected Tropical Diseases
* PLOS ONE
* PLOS Pathogens
* PM&R
* Pneumologie
* Podosophia (Dutch)
* Podzemná voda (Slovak)
* Poetics
* Polar Biology (Polar Biol)
* Polar Science
* Police Practice and Research
* Policy and Society
* Policy Sciences (Policy Sci)
* Policy Studies
* Polish Annals of Medicine
* Polish Journal of Applied Psychology
* Polish Legal (Polish)
* Political Behavior (Polit Behav)
* Political Geography
* Political Studies
* Politics, Groups, and Identities
* Politikon
* Politische Vierteljahresschrift (German) (PVS)
* Polski Przegląd Otorynolaryngologiczny
* Polyhedron
* Polymer
* Polymer Bulletin (Polym. Bull.)
* Polymer Chemistry
* Polymer Degradation and Stability
* Polymer Journal
* Polymer Reviews
* Polymer Testing
* Polymers
* Pontifical Athenaeum Regina Apostolorum
* Pontifical Biblical Institute
* Pontifical Gregorian University (English)
* Pontifical Gregorian University (French)
* Pontifical Gregorian University (German)
* Pontifical Gregorian University (Italian)
* Pontifical Gregorian University (Spanish)
* Pontificia Universidad Católica del Ecuador (Spanish) - Harvard (Harvard PUCE)
* Population (English) (Population-E)
* Population (French) (Population-F)
* Population and Environment (Popul Environ)
* Population Ecology (Popul Ecol)
* Population Health Metrics
* Population Research and Policy Review (Popul Res Policy Rev)
* Population, Space and Place
* Porcine Health Management
* Portuguese Economic Journal (Port Econ J)
* Portuguese Studies
* Positivity
* Post-Soviet Affairs
* Postępy Higieny i Medycyny Doświadczalnej (Polish) (PHiMD)
* Postępy Psychiatrii i Neurologii
* Postgraduate Medical Journal
* Postgraduate Medicine
* Postharvest Biology and Technology
* Potato Research (Potato Res.)
* Potential Analysis (Potential Anal)
* Poultry Science
* Pour réussir (note, French - Canada)
* Powder Technology
* PPmP - Psychotherapie - Psychosomatik - Medizinische Psychologie
* Practical Laboratory Medicine
* Practical Neurology
* Practical Radiation Oncology
* Practice
* Practice Periodical on Structural Design and Construction
* Pratique médicale et chirurgicale de l'animal de compagnie
* Pratique Neurologique - FMC
* Pratiques en nutrition
* Pratiques psychologiques
* Prävention und Gesundheitsförderung (German) (Prävention Gesundheitsförderung)
* Precambrian Research
* Precision Agriculture (Precision Agric)
* Precision Engineering
* Pregnancy Hypertension: An International Journal of Women's Cardiovascular Health
* Prehospital Emergency Care (PEC)
* Preslia - The Journal of the Czech Botanical Society (Preslia)
* Presses universitaires de Paris Nanterre (note, French) (PU Paris Nanterre)
* Presses Universitaires de Rennes - Archéologie et Culture (French)
* Presses Universitaires de Rennes (French)
* Prevention Science (Prev Sci)
* Preventive Medicine
* Preventive Veterinary Medicine
* Primary Care Diabetes
* Primary Care: Clinics in Office Practice (POP)
* Primate Biology
* Primates
* Prion
* Probabilistic Engineering Mechanics
* Probability Theory and Related Fields (Probab. Theory Relat. Fields)
* Probiotics and Antimicrobial Proteins (Probiotics & Antimicro. Prot.)
* Procedia Early Career Research
* Procedia Economics and Finance
* Procedia Manufacturing
* Procedia Materials Science
* Procedia Structural Integrity
* Proceedings
* Proceedings of the Geologists' Association
* Proceedings of the IEEE
* Proceedings of the National Academy of Sciences of the United States of America (PNAS)
* Proceedings of the National Academy of Sciences, India Section A: Physical Sciences (Proc. Natl. Acad. Sci., India, Sect. A Phys. Sci.)
* Proceedings of the National Academy of Sciences, India Section B: Biological Sciences (Proc. Natl. Acad. Sci., India, Sect. B Biol. Sci.)
* Proceedings of the Royal Society A
* Proceedings of the Royal Society B
* Proceedings of the Yorkshire Geological Society
* Proceedings of the Zoological Society (Proc Zool Soc)
* Process Biochemistry
* Process Safety and Environmental Protection
* Processes
* Production & Manufacturing Research
* Production Engineering (Prod. Eng. Res. Devel.)
* Production Planning & Control
* Professional Psychology: Research and Practice
* Programme Grants for Applied Research
* Progrès en Urologie
* Progrès en Urologie - FMC
* Progress in Additive Manufacturing
* Progress in Aerospace Sciences
* Progress in Artificial Intelligence (Prog Artif Intell)
* Progress in Biomaterials
* Progress in Biophysics and Molecular Biology
* Progress in Cardiovascular Diseases
* Progress in Crystal Growth and Characterization of Materials
* Progress in Earth and Planetary Science
* Progress in Energy and Combustion Science
* Progress in Histochemistry and Cytochemistry
* Progress in Lipid Research
* Progress in Materials Science
* Progress in Neurobiology
* Progress in Neuropsychopharmacology & Biological Psychiatry
* Progress in Nuclear Energy
* Progress in Nuclear Magnetic Resonance Spectroscopy
* Progress in Oceanography
* Progress in Organic Coatings
* Progress in Orthodontics
* Progress in Particle and Nuclear Physics
* Progress in Pediatric Cardiology
* Progress in Planning
* Progress in Polymer Science
* Progress in Quantum Electronics
* Progress in Retinal and Eye Research
* Progress in Solid State Chemistry
* Progress in Surface Science
* ProInflow (note, Czech)
* Property Law Review (Prop L Rev)
* Propulsion and Power Research
* PROSPECTS (Prospects)
* Prostaglandins and Other Lipid Mediators
* Prostaglandins, Leukotrienes and Essential Fatty Acids
* Prostate Cancer and Prostatic Diseases
* Prostate International
* Protein & Cell
* Protein Engineering Design and Selection (PEDS)
* Protein Expression and Purification
* Protein Science
* Proteome Science
* Proteomes
* PROTEOMICS
* Protoplasma
* PS: Political Science & Politics
* Psicología Educativa
* Psych up2date
* Psychiatric Annals
* Psychiatric Clinics of North America (PSC)
* Psychiatric Rehabilitation Journal
* Psychiatric Services
* Psychiatrische Praxis
* Psychiatry and Clinical Neurosciences
* Psychiatry Research
* Psychiatry Research: Neuroimaging
* Psychoanalytic Psychology
* Psychoanalytic Psychotherapy
* Psychodynamic Practice
* Psychological Assessment
* Psychological Bulletin
* Psychological Injury and Law (Psychol. Inj. and Law)
* Psychological Medicine
* Psychological Methods
* Psychological Research
* Psychological Review
* Psychological Services
* Psychological Studies (Psychol Stud)
* Psychological Trauma: Theory, Research, Practice, and Policy
* Psychologie française
* Psychology & Health
* Psychology & Sexuality
* Psychology and Aging
* Psychology and Psychotherapy: Theory, Research and Practice
* Psychology of Addictive Behaviors
* Psychology of Aesthetics, Creativity, and the Arts
* Psychology of Consciousness: Theory, Research, and Practice
* Psychology of Men & Masculinity
* Psychology of Popular Media Culture
* Psychology of Religion and Spirituality
* Psychology of Sexual Orientation and Gender Diversity
* Psychology of Sport & Exercise
* Psychology of Violence
* Psychology of Well-Being
* Psychology, Crime & Law
* Psychology, Health & Medicine
* Psychology, Public Policy, and Law
* Psychometrika
* Psychomusicology: Music, Mind, and Brain
* Psychoneuroendocrinology
* Psychopathology
* Psychopharmacology
* psychopraxis. neuropraxis (German)
* Psychosis
* Psychosocial Intervention
* Psychosomatic Medicine
* Psychosomatics (PSYM)
* Psychotherapeut (German) (Psychotherapeut)
* Psychotherapie Forum (German)
* Psychotherapy
* Psychotherapy and Psychosomatics
* Psychotherapy Research
* Public Choice
* Public Health
* Public Health Forum
* Public Health Genomics
* Public Health Nutrition
* Public Health Research
* Public Health Reviews
* Public Law Review (PLR)
* Public Library of Science (PLOS)
* Public Organization Review (Public Organiz Rev)
* Public Relations Review
* Public Transport (Public Transp)
* Publications
* Publishing Research Quarterly (Pub Res Q)
* Publizistik (German) (Publizistik)
* Puerto Rico Health Sciences Journal
* Pulmonary Pharmacology & Therapeutics
* Pulmonary Therapy
* Pulse
* Purinergic Signalling
* QJM: An International Journal of Medicine
* Quaderni degli Avogadro Colloquia
* Quaderni Italiani di Psichiatria
* Quaderni Materialisti (Italian)
* Qualitative Psychology
* Qualitative Sociology (Qual Sociol)
* Qualitative Theory of Dynamical Systems (Qual. Theory Dyn. Syst.)
* Quality & Quantity (Qual Quant)
* Quality of Life Research (Qual Life Res)
* Quantitative Marketing and Economics (Quant Mark Econ)
* Quantum Beam Science
* Quantum Electronics
* Quantum Information Processing (Quantum Inf Process)
* Quantum Studies: Mathematics and Foundations
* Quarterly Journal of Engineering Geology and Hydrogeology
* Quarterly Journal of Speech
* Quarterly Review of Economics and Finance
* Quaternary Geochronology
* Quaternary International
* Quaternary Research
* Quaternary Science Reviews
* Queueing Systems (Queueing Syst)
* R&D Management
* Race and Social Problems (Race Soc Probl)
* Race Ethnicity and Education
* Radiation and Environmental Biophysics (Radiat Environ Biophys)
* Radiation Measurements
* Radiation Oncology
* Radiation Physics and Chemistry
* Radio Science
* Radiochimica Acta
* RadioGraphics
* Radiography (RADI)
* Radiología
* Radiologic Clinics of North America (RCL)
* Radiological Physics and Technology (Radiol Phys Technol)
* Radiologie up2date
* Radiology
* Radiology Case Reports
* Radiology of Infectious Diseases
* Radiopaedia.org
* Radiopraxis
* Radiotherapy and Oncology
* Raffles Bulletin of Zoology (RBZ)
* RAI Revista de Administração e Inovação
* Rangeland Ecology & Management
* Rapid Communications in Mass Spectrometry (Rapid Commun Mass Spectrom)
* Rare Diseases
* Rare Metals (Rare Met.)
* RAUSP Management Journal
* REACH
* Reaction Chemistry & Engineering
* Reaction Kinetics, Mechanisms and Catalysis (Reac Kinet Mech Cat)
* Reactive and Functional Polymers
* Reading and Writing (Read Writ)
* Real-Time Systems (Real-Time Syst)
* Recent Patents on Drug Delivery & Formulation
* Recherches en Sciences de Gestion (French)
* Rechtsmedizin (German) (Rechtsmedizin)
* Recycling
* Redox Biology
* Reflective Practice
* REGE - Revista de Gestão
* Regenerative Engineering and Translational Medicine
* Regenerative Medicine
* Regenerative Medicine Research
* Regenerative Therapy
* Regional Environmental Change (Reg Environ Change)
* Regional Science and Urban Economics
* Regional Studies in Marine Science
* Regulatory Peptides
* Regulatory Toxicology and Pharmacology
* Rehabilitation Psychology
* Reinforced Plastics
* Reliability Engineering and System Safety
* Religion in the Roman Empire (RRE)
* Religions
* Remote Sensing
* Remote Sensing Applications: Society and Environment
* Remote Sensing of Environment
* Renal Replacement Therapy
* Rendiconti del Circolo Matematico di Palermo (Rend. Circ. Mat. Palermo)
* Rendiconti Lincei (Rend. Fis. Acc. Lincei)
* Renewable Agriculture and Food Systems
* Renewable and Sustainable Energy Reviews
* Renewable Energy
* Renewable Energy Focus
* Renewables: Wind, Water, and Solar
* Reports of Practical Oncology and Radiotherapy (RPOR)
* Reports on Progress in Physics
* Reproduction
* Reproduction in Domestic Animals (Reprod. Domest. Anim.)
* Reproduction, Fertility and Development (Reprod. Fertil. Dev.)
* Reproductive Biology
* Reproductive Biology and Endocrinology
* Reproductive Biomedicine & Society Online
* Reproductive BioMedicine Online
* Reproductive Health
* Reproductive Medicine and Biology (Reprod Med Biol)
* Reproductive Toxicology
* Requirements Engineering (Requirements Eng)
* Res Publica
* Research and Practice in Technology Enhanced Learning
* Research Evaluation
* Research in Accounting Regulation
* Research in Astronomy and Astrophysics
* Research in Autism Spectrum Disorders
* Research in Dance Education
* Research in Developmental Disabilities
* Research in Drama Education: The Journal of Applied Theatre and Performance
* Research in Economics
* Research in Engineering Design (Res Eng Design)
* Research in Gerontological Nursing
* Research in Higher Education (Res High Educ)
* Research in International Business and Finance
* Research in Mathematics Education
* Research in Microbiology
* Research in Number Theory
* Research in Organizational Behavior
* Research in Post-Compulsory Education
* Research in Science & Technological Education
* Research in Science Education (Res Sci Educ)
* Research in Social and Administrative Pharmacy
* Research in Social Stratification and Mobility
* Research in the Mathematical Sciences
* Research in Transportation Business & Management
* Research in Transportation Economics
* Research in Veterinary Science
* Research Integrity and Peer Review
* Research Involvement and Engagement
* Research on Biomedical Engineering (RBE)
* Research on Chemical Intermediates (Res Chem Intermed)
* Research Papers in Education
* Research Policy
* Resource and Energy Economics
* Resource-Efficient Technologies
* Resources
* Resources Policy
* Resources, Conservation & Recycling
* Respiration
* Respiratory Investigation
* Respiratory Medicine
* Respiratory Medicine Case Reports
* Respiratory Physiology & Neurobiology
* Respiratory Research
* Restoration Ecology
* Results in Immunology
* Results in Mathematics (Results. Math.)
* Results in Pharma Sciences
* Results in Physics
* Resuscitation
* Rethinking History
* Retina
* Retrovirology
* retten!
* Reumatología Clinica (Spanish)
* Review Journal of Autism and Developmental Disorders
* Review of Accounting Studies (Rev Account Stud)
* Review of African Political Economy
* Review of Communication
* Review of Derivatives Research (Rev Deriv Res)
* Review of Development Finance
* Review of Economic Design (Rev Econ Design)
* Review of Economic Dynamics
* Review of Economic Perspectives (Národohospodárský obzor)
* Review of Economics of the Household (Rev Econ Household)
* Review of Educational Research
* Review of Financial Economics
* Review of General Psychology
* Review of Industrial Organization (Rev Ind Organ)
* Review of International Studies
* Review of Managerial Science (Rev Manag Sci)
* Review of Palaeobotany and Palynology
* Review of Philosophy and Psychology (Rev.Phil.Psych.)
* Review of Quantitative Finance and Accounting (Rev Quant Finan Acc)
* Review of Regional Research (Jahrb Reg wiss)
* Review of Religious Research (Rev Relig Res)
* Review of Research in Education
* Review of Scientific Instruments
* Review of World Economics (Rev World Econ)
* Reviews in Endocrine and Metabolic Disorders (Rev Endocr Metab Disord)
* Reviews in Environmental Science and Bio/Technology (Rev Environ Sci Biotechnol)
* Reviews in Fish Biology and Fisheries (Rev Fish Biol Fisheries)
* Reviews in Physics
* Reviews in Vascular Medicine
* Reviews of Environmental Contamination and Toxicology (Rev Environ Contam Toxicol)
* Reviews of Geophysics
* Reviews of Modern Physics (with titles)
* Revista Argentina de Antropologia Biologica (Spanish)
* Revista Argentina de Cirugía (Spanish)
* Revista Brasileira de Ciência do Solo (Portuguese - Brazil) (RBCS)
* Revista Brasileira de Ciências do Esporte
* Revista Brasileira de Entomologia
* Revista Brasileira de Farmacognosia
* Revista Brasileira de Reumatologia (Brazilian Journal of Rheumatology)
* Revista Chilena de Derecho y Tecnología (Spanish - Chile) (RChDT)
* Revista Chilena de Historia Natural
* Revista Chilena de Pediatría (Spanish)
* Revista Ciencias Técnicas Agropecuarias (Spanish) (rcta)
* Revista Clínica Española (Spanish)
* Revista Cubana de Alimentación y Nutrición (Spanish)
* Revista Cubana de Cirugía (Spanish)
* Revista Cubana de Endocrinología (Spanish)
* Revista Cubana de Enfermería (Spanish)
* Revista Cubana de Estomatología (Spanish)
* Revista Cubana de Farmacia (Spanish)
* Revista Cubana de Hematología, Inmunología y Hemoterapia (Spanish)
* Revista Cubana de Higiene y Epidemiología (Spanish)
* Revista Cubana de Investigaciones Biomédicas (Spanish)
* Revista Cubana de Medicina (Spanish)
* Revista Cubana de Medicina General Integral (Spanish)
* Revista Cubana de Medicina Militar (Spanish)
* Revista Cubana de Medicina Tropical (Spanish)
* Revista Cubana de Obstetricia y Ginecología (Spanish)
* Revista Cubana de Oftalmologia (Spanish)
* Revista Cubana de Ortopedia y Traumatología (Spanish)
* Revista Cubana de Pediatría (Spanish)
* Revista Cubana de Salud Pública (Spanish)
* Revista Cuicuilco (Spanish - Mexico)
* Revista da Sociedade Brasileira de Medicina Tropical (RSBMT)
* Revista de Administração
* Revista de Biología Tropical (International Journal of Tropical Biology and Conservation)
* Revista de Contabilidad
* Revista de Filología Española (Spanish) (RFE parentético)
* Revista de Gastroenterología de México (Spanish)
* Revista de la educación superior
* Revista de la Real Academia de Ciencias Exactas, Físicas y Naturales. Serie A. Matemáticas (RACSAM)
* Revista de Logopedia, Foniatría y Audiología
* Revista de Psicodidáctica
* Revista de Psicología del Trabajo y de las Organizaciones
* Revista de Psiquiatría y Salud Mental (Spanish)
* Revista del Laboratorio Clínico (Spanish)
* Revista Española de Anestesiología y Reanimación (Spanish)
* Revista Española de Cardiología
* Revista Española de Salud Pública (Spanish)
* Revista FAVE - Sección Ciencias Agrarias (Spanish) (FAVE)
* Revista Iberoamericana de Psicología y Salud
* Revista Internacional de Métodos Numéricos para Cálculo y Diseño en Ingeniería
* Revista Latinoamericana de Metalurgia y Materiales (RLMM)
* Revista Latinoamericana de Psicología
* Revista Latinoamericana de Recursos Naturales (Rev. Lat. Rec. Nat.)
* Revista Matemática Complutense (Rev Mat Complut)
* Revista Médica Clínica Las Condes
* Revista Médica de Chile (Spanish)
* Revista Médica del Instituto Mexicano del Seguro Social (Spanish)
* Revista Mexicana de Biodiversidad
* Revista Mexicana de Trastornos Alimentarios
* Revista Nóesis
* Revista Panamericana de Salud Pública (Pan American Journal of Public Health)
* Revista Portuguesa de Arqueologia (RPA)
* Revista Portuguesa de Cardiologia
* Revista Virtual de Química (Portuguese - Brazil) (RVq)
* Revue Archéologique (French)
* Revue archéologique du Centre de la France (French) (RACF)
* Revue d'élevage et de médecine vétérinaire des pays tropicaux (French) (Rev.Elev.Med.Vet.Pays.Trop.)
* Revue d'Epidemiologie et de Santé Publique
* Revue d'histoire moderne et contemporaine (French)
* Revue d'Oncologie Hématologie Pédiatrique
* Revue de Chirurgie Orthopedique et Traumatologique
* Revue de Médecine Vétérinaire (French)
* Revue de micropaléontologie
* Revue de Pneumologie clinique
* Revue de Qumrân
* Revue de Stomatologie, de Chirurgie Maxillo-faciale et de Chirurgie Orale
* Revue des Maladies Respiratoires
* Revue des Nouvelles Technologies de l'Information (French) (RNTI)
* Revue du podologue
* Revue du rhumatisme
* Revue du Rhumatisme monographies
* Revue européenne de psychologie appliquée
* Revue Européenne des Migrations Internationales (REMI)
* Revue Française d'Allergologie
* Revue française de sociologie (English) (RFS-EN)
* Revue française de sociologie (French) (RFS)
* Revue Francophone d'Orthoptie
* Revue francophone internationale de recherche infirmière
* Revue Neurologique
* Revue vétérinaire Clinique
* Rheologica Acta (Rheol Acta)
* rheuma plus (German)
* Rheumatology
* Rheumatology and Therapy
* Rheumatology International (Rheumatol Int)
* Rhizosphere
* Rhodora
* RIBAGUA - Revista Iberoamericana del Agua
* Rice
* Ricerche di Matematica (Ricerche mat.)
* Risk Analysis
* Risks
* RNA
* RNA Biology
* Road Materials and Pavement Design
* Robert Gordon University - Harvard
* ROBOMECH Journal
* Robotics
* Robotics and Autonomous Systems
* Robotics and Biomimetics
* Robotics and Computer Integrated Manufacturing
* Rock Mechanics and Rock Engineering (Rock Mech Rock Eng)
* RöFo: Fortschritte auf dem Gebiet der Röntgenstrahlen und bildgebenden Verfahren (RöFo)
* Romanian Humanities (Romanian)
* Rorschachiana
* ROSE School
* Royal Society of Chemistry
* Royal Society of Chemistry (with titles)
* Royal Society Open Science
* RSC Advances
* RTF Scan
* Russian Chemical Reviews
* Russian Geology and Geophysics
* Russian GOST R 7.0.5-2008 (numeric, sorted alphabetically, Russian) (GOST R 7.0.5-2008 (numeric, sorted alphabetically))
* Russian GOST R 7.0.5-2008 (numeric)
* Russian GOST R 7.0.5-2008 (Russian)
* Russian Journal of Communication
* Russian Linguistics (Russ Linguist)
* Russian Mathematical Surveys
* Safety
* Safety and Health at Work
* Safety in Health
* Safety Science
* SAGE - Harvard
* SAGE - Vancouver
* SAGE - Vancouver (brackets)
* Salud Colectiva (Spanish)
* Salud Pública de México
* Samples (German)
* Sanidad Militar
* São Paulo Journal of Mathematical Sciences
* Sascha Foerster - Geisteswissenschaft (German) (zoteroSF)
* Saudi Journal of Biological Sciences
* Saudi Pharmaceutical Journal
* Sbornik: Mathematics
* Scandinavian Journal of Disability Research
* Scandinavian Journal of Educational Research
* Scandinavian Journal of Forest Research
* Scandinavian Journal of Hospitality and Tourism
* Scandinavian Journal of Infectious Diseases
* Scandinavian Journal of Management
* Scandinavian Journal of Medicine & Science in Sports (Scand J Med Sci Sports)
* Scandinavian Journal of Pain
* Scandinavian Journal of Public Health
* Scandinavian Journal of Rheumatology
* Scandinavian Journal of Trauma, Resuscitation and Emergency Medicine
* Scandinavian Journal of Work, Environment & Health
* Scandinavian Political Studies
* Schizophrenia Research
* Schizophrenia Research: Cognition
* School Effectiveness and School Improvement
* School Leadership & Management
* School Mental Health
* School Psychology Quarterly
* Schweizerische Zeitschrift für Ganzheitsmedizin
* Science
* Science (without titles)
* Science & Education (Sci & Educ)
* Science & Justice
* Science Advances
* Science and Engineering Ethics (Sci Eng Ethics)
* Science and Technology for the Built Environment (STBE)
* Science and Technology of Advanced Materials
* Science Bulletin
* SCIENCE CHINA Life Sciences
* Science et Sports
* Science Foundation in China
* Science of Computer Programming
* Science of the Total Environment
* Science Translational Medicine
* ScienceAsia (SciAs)
* Scientia Agriculturae Bohemica (SAB)
* Scientia Horticulturae
* Scientia Pharmaceutica
* Scientific Drilling
* Scientific Phone Apps and Mobile Devices
* Scientific Reports
* Scientific Review Engineering and Environmental Sciences (Przegląd Naukowy Inżynieria i Kształtowanie Środowiska) (SREES)
* Scientometrics
* Scoliosis
* Scottish Journal of Geology
* Scrinium (SCRI)
* Scripta Materialia
* Securitas Vialis (Spanish) (Securitas Vialis)
* Security Informatics
* Sedimentary Geology
* Seed Science Research
* Seizure: European Journal of Epilepsy
* Selçuk Tıp Dergisi (Medical Journal of Selçuk)
* Selecta Mathematica (Sel. Math. New Ser.)
* Self and Identity
* Semiconductor Science and Technology
* Semigroup Forum
* Séminaire Saint-Sulpice - Ecole Théologie (French) (SSSET)
* Seminars in Arthritis and Rheumatism
* Seminars in Arthroplasty
* Seminars in Cancer Biology
* Seminars in Cell and Developmental Biology
* Seminars in Colon and Rectal Surgery
* Seminars in Diagnostic Pathology
* Seminars in Fetal and Neonatal Medicine
* Seminars in Immunology
* Seminars in Immunopathology (Semin Immunopathol)
* Seminars in Oncology Nursing
* Seminars in Orthodontics
* Seminars in Pediatric Neurology
* Seminars in Pediatric Surgery
* Seminars in Perinatology
* Seminars in Spine Surgery
* Seminars in Vascular Surgery
* Senologie
* Sensing and Bio-Sensing Research
* Sensing and Imaging (Sens Imaging)
* Sensors
* Sensors & Actuators: A. Physical
* Sensors & Actuators: B. Chemical
* Separation and Purification Technology
* Separations
* Serials Review
* SERIEs
* Service Business (Serv Bus)
* Service Médical de l'Assurance Maladie (French)
* Service Oriented Computing and Applications (SOCA)
* Service Science
* Set-Valued and Variational Analysis (Set-Valued Var. Anal)
* Sex Education
* Sex Roles
* Sexologies
* Sexual & Reproductive Healthcare
* Sexual and Relationship Therapy
* Sexual Development
* Sexual Health
* Sexual Medicine
* Sexual Medicine Reviews
* Sexuality & Culture
* Sexuality and Disability (Sex Disabil)
* Sexuality Research and Social Policy (Sex Res Soc Policy)
* Sexually Transmitted Diseases
* Sexually Transmitted Infections
* Shakespeare
* Shape Memory and Superelasticity
* Sheffield Hallam University - History
* Ships and Offshore Structures
* Shock Waves
* Signal Processing
* Signal Processing: Image Communication
* Signal, Image and Video Processing (SIViP)
* Signals
* Silicon
* Simulation Modelling Practice and Theory
* Singapore Dental Journal
* Sinusitis
* SIST02 (Japanese)
* Skeletal Muscle
* Skeletal Radiology (Skeletal Radiol)
* Skin Pharmacology and Physiology
* Slavonic & East European Review
* SLEEP
* Sleep and Biological Rhythms
* Sleep and Breathing (Sleep Breath)
* Sleep Health: Journal of the National Sleep Foundation
* Sleep Medicine
* Sleep Medicine Reviews
* Sleep Science
* Small
* Small Business Economics (Small Bus Econ)
* Small GTPases
* Small Ruminant Research
* Small Wars & Insurgencies
* Small-scale Forestry
* Smart Health
* Smart Learning Environments
* Smart Materials and Structures
* Smart Water
* Smithsonian Institution Scholarly Press - Botany (author-date) (SISP)
* Smithsonian Institution Scholarly Press (author-date) (SISP)
* Soccer & Society
* Social and Environmental Accountability Journal
* Social and Natural Sciences Journal
* Social Choice and Welfare (Soc Choice Welf)
* Social Cognitive and Affective Neuroscience (SCAN)
* Social Dynamics
* Social Identities
* Social Indicators Research (Soc Indic Res)
* Social Influence
* Social Justice Research (Soc Just Res)
* Social Movement Studies
* Social Network Analysis and Mining (Soc. Netw. Anal. Min.)
* Social Networks
* Social Neuroscience
* Social Psychiatry and Psychiatric Epidemiology (Soc Psychiatry Psychiatr Epidemiol)
* Social Psychology
* Social Psychology of Education (Soc Psychol Educ)
* Social Psychology Quarterly
* Social Science & Medicine
* Social Science Research
* Social Sciences
* Social Semiotics
* Social Studies of Science
* Social Work Education
* Sociedade Brasileira de Computação
* Société Archéologique de Bordeaux (French) (SAB)
* Société Nationale des Groupements Techniques Vétérinaires (French) (SNGTV)
* Societies
* Society and Mental Health
* Society for American Archaeology
* Society for Historical Archaeology
* Society for Laboratory Automation and Screening (SLAS)
* Society of Automotive Engineers Technical Papers (numeric) (SAE Technical Papers)
* Society of Biblical Literature 2nd edition (full note)
* Socio-Economic Planning Sciences
* Socio-Economic Review
* Sociological Methodology
* Sociological Theory
* Sociologie du travail
* Sociology
* Sociology of Education
* Sociology of Health & Illness (Sociol Health Ill)
* Södertörns högskola - Harvard (SH (Harvard))
* Södertörns högskola - Harvard (with Ibid.) (SH - Harvard (Ibid.))
* Soft Computing (Soft Comput)
* Soft Matter
* Software & Systems Modeling (Softw Syst Model)
* Software Quality Journal (Software Qual J)
* SoftwareX
* SOIL
* Soil & Tillage Research
* Soil Biology and Biochemistry
* SOIL Discussions
* Soil Dynamics and Earthquake Engineering
* Soil Processes
* Soil Research
* Soil Science and Plant Nutrition
* Soil Science Society of America Journal
* Soils and Foundations
* Soins
* Soins Aides-soignantes
* Soins Cadres
* Soins Gérontologie
* Soins Pédiatrie/Puériculture
* Soins Psychiatrie
* Solar Energy
* Solar Energy Materials and Solar Cells
* Solid Earth
* Solid Earth Discussions
* Solid Earth Sciences
* Solid State Communications
* Solid State Electronics
* Solid State Ionics
* Solid State Nuclear Magnetic Resonance
* Solid State Sciences
* Solutions
* Somnologie - Schlafforschung und Schlafmedizin (German) (Somnologie Schlafforschung Schlafmedizin)
* Sophia (SOPHIA)
* Source Code for Biology and Medicine
* South African Geographical Journal
* South African Journal of Animal Science
* South African Journal of Botany
* South African Journal of Chemical Engineering
* South African Journal of Enology and Viticulture (SAJEV)
* South African Journal of Geology (Geol. South Africa)
* South African Medical Journal
* South African Theological Seminary (SATS)
* South Asian Diaspora
* South Asian History and Culture
* Southampton Solent University - Harvard
* Southern Cross University - Harvard
* Soziale Passagen (German) (Soz Passagen)
* Soziale Probleme (German)
* Soziale Welt (German)
* Sozialpädagogisches Institut Berlin - Walter May (German) (SPI)
* Sozialwissenschaften (Heilmann) (German)
* Soziologie (German)
* Space Policy
* Space Science Reviews (Space Sci Rev)
* Space Weather
* Spandidos Publications
* Spanish Journal of Marketing - ESIC
* Spanish Legal (Spanish)
* Spatial and Spatio-temporal Epidemiology
* Spatial Demography
* Spatial Statistics
* Special Care in Dentistry
* Spectrochimica Acta Part A: Molecular and Biomolecular Spectroscopy
* Spectrochimica Acta Part B: Atomic Spectroscopy
* Spectroscopy Letters (Spectrosc Lett)
* Speculum
* Speech Communication
* Spektrum der Augenheilkunde (German) (Spektrum Augenheilkd.)
* Spermatogenesis
* SPIE BiOS
* SPIE Conference Proceedings
* SPIE journals
* Spinal Cord
* Spine
* Spine Deformity
* SPIP - Cite plugin
* Spirituality in Clinical Practice
* Sport Management Review
* Sport Sciences for Health (Sport Sci Health)
* Sport, Education and Society
* Sport, Exercise, and Performance Psychology
* Sports
* Sports Biomechanics
* Sports Coaching Review
* Sports Engineering (Sports Eng)
* Sports Medicine (Sports Med)
* Sports Medicine - Open
* Sports Medicine International open
* Sports Technology
* Sportverletzung - Sportschaden
* Sportwissenschaft (German) (Sportwiss)
* Sprache - Stimme - Gehör
* Springer - Basic (author-date, no "et al.")
* Springer - Basic (author-date)
* Springer - Basic (note)
* Springer - Basic (numeric, brackets, no "et al.", alphabetical)
* Springer - Basic (numeric, brackets, no "et al.")
* Springer - Basic (numeric, brackets)
* Springer - Fachzeitschriften Medizin Psychologie (German)
* Springer - Humanities (author-date)
* Springer - Humanities (numeric, brackets)
* Springer - Lecture Notes in Computer Science (Springer LNCS)
* Springer - Lecture Notes in Computer Science (sorted alphabetically) (Springer LNCS)
* Springer - MathPhys (author-date)
* Springer - MathPhys (numeric, brackets)
* Springer - Physics (author-date)
* Springer - Physics (numeric, brackets)
* Springer - SocPsych (author-date)
* Springer - SocPsych (numeric, brackets)
* Springer - Vancouver
* Springer - Vancouver (author-date)
* Springer - Vancouver (brackets)
* Springer Science Reviews
* Springer VS (author-date, German)
* SpringerPlus
* SpringerProtocols
* SSM - Population Health
* St Patrick's College
* St. Petersburg Polytechnical University Journal: Physics and Mathematics
* Staffordshire University - Harvard
* Standards in Genomic Sciences
* Standort (German) (Standort)
* Statistical Inference for Stochastic Processes (Stat Inference Stoch Process)
* Statistical Methods & Applications (Stat Methods Appl)
* Statistical Papers (Stat Papers)
* Statistics
* Statistics and Computing (Stat Comput)
* Statistics and Probability Letters
* Statistics in Biopharmaceutical Research (SBR)
* Statistics in Biosciences (Stat Biosci)
* Statistika: Statistics and Economy Journal
* Stavební obzor (Czech)
* Stellenbosch University - Harvard
* Stem Cell Reports
* Stem Cell Research
* Stem Cell Research & Therapy
* Stem Cell Reviews and Reports (Stem Cell Rev and Rep)
* Stem Cells
* Stem Cells and Development
* Stem Cells Translational Medicine (Stem Cells Transl Med)
* Stephan Mueller Special Publication Series
* Stereotactic and Functional Neurosurgery
* Steroids
* Stochastic Environmental Research and Risk Assessment (Stoch Environ Res Risk Assess)
* Stochastic Partial Differential Equations: Analysis and Computations (Stoch PDE: Anal Comp)
* Stomatologie (German) (Stomatologie)
* Stomatološki vjesnik (Stomatological Review)
* Strahlentherapie und Onkologie
* Strategic Management Journal
* Strategic Organization
* Strategies in Trauma and Limb Reconstruction (Strat Traum Limb Recon)
* Strategy Science
* Stroke
* Structural and Multidisciplinary Optimization (Struct Multidisc Optim)
* Structural Change and Economic Dynamics
* Structural Chemistry (Struct Chem)
* Structural Control and Health Monitoring (Struct. Control Health Monit.)
* Structural Safety
* Structure
* Structures
* Student BMJ
* Studia BAS (Polish)
* Studia Theologica - Nordic Journal of Theology
* Studies in Communication Sciences
* Studies in Comparative International Development (St Comp Int Dev)
* Studies in Continuing Education
* Studies in East European Thought (Stud East Eur Thought)
* Studies in Educational Evaluation
* Studies in History and Philosophy of Biol & Biomed Sci
* Studies in History and Philosophy of Modern Physics
* Studies in History and Philosophy of Science
* Studies in Philosophy and Education (Stud Philos Educ)
* Studies in Science Education
* Studii Teologice
* Studying Teacher Education
* Style Manual - Australian Government (author-date)
* Substance Abuse Treatment, Prevention, and Policy
* Suchttherapie
* Sugar Tech
* Suma de Negocios
* Suma Psicológica
* Sunway College Johor Bahru - Harvard (SYCJB)
* Suomen Lääkärilehti (Finnish Medical Journal) (Finnish)
* Superconductor Science and Technology
* Superlattices and Microstructures
* Supportive Care in Cancer (Support Care Cancer)
* Surface & Coatings Technology
* Surface Science
* Surface Science Reports
* Surface Topography: Metrology and Properties
* Surfaces and Interfaces
* Surgery
* Surgery for Obesity and Related Diseases
* Surgery Today (Surg Today)
* Surgical and Radiologic Anatomy (Surg Radiol Anat)
* Surgical Case Reports
* Surgical Clinics of North America (SUC)
* Surgical Endoscopy (Surg Endosc)
* Surgical Neurology International
* Surgical Oncology
* Surgical Pathology Clinics (PATH)
* Survey of Ophthalmology
* Surveys in Geophysics (Surv Geophys)
* Surveys in Operations Research and Management Science
* Sustainability
* Sustainability of Water Quality and Ecology
* Sustainability Science (Sustain Sci)
* Sustainable Chemical Processes
* Sustainable Chemistry and Pharmacy
* Sustainable Cities and Society
* Sustainable Computing: Informatics and Systems
* Sustainable Energy & Fuels
* Sustainable Energy Technologies and Assessments
* Sustainable Energy, Grids and Networks
* Sustainable Environment Research
* Sustainable Materials and Technologies
* Sustainable Production and Consumption
* Sustainable Water Resources Management
* Svensk exegetisk årsbok (full note) (SEÅ)
* Swarm and Evolutionary Computation
* Swarm Intelligence (Swarm Intell)
* Swedish Legal (Swedish)
* Swinburne University of Technology - Harvard
* Swiss Journal of Geosciences (Swiss J Geosci)
* Swiss Journal of Palaeontology (Swiss J Palaeontol)
* Swiss Journal of Psychology
* Swiss Medical Weekly
* Symbiosis
* Symmetry
* Synergy
* Synthese
* Synthetic and Systems Biotechnology
* Synthetic Metals
* System
* Systematic and Applied Microbiology (SYAPM)
* Systematic Biology
* Systematic Parasitology (Syst Parasitol)
* Systematic Reviews
* Systemic Practice and Action Research (Syst Pract Action Res)
* Systems
* Systems & Control Letters
* Systems and Synthetic Biology (Syst Synth Biol)
* Systems Biomedicine
* Systems Science & Control Engineering: An Open Access Journal
* Tábula (Spanish)
* Taiwan Journal of Ophthalmology
* Taiwanese Journal of Obstetrics & Gynecology
* Talanta
* Tandlægebladet (Danish Dental Journal)
* Tanta Dental Journal
* Targeted Oncology (Targ Oncol)
* Taxon
* Taylor & Francis - APA (TF-APA)
* Taylor & Francis - Chicago F
* Taylor & Francis - Chicago Manual of Style (author-date)
* Taylor & Francis - Chicago Manual of Style (note)
* Taylor & Francis - Council of Science Editors (author-date) (TF-CSE)
* Taylor & Francis - Harvard V
* Taylor & Francis - Harvard X
* Taylor & Francis - National Library of Medicine (TF-NLM)
* Taylor & Francis - Numeric Q
* Teacher Development
* Teachers and Teaching
* Teaching and Learning in Nursing
* Teaching and Teacher Education
* Teaching Education
* Teaching in Higher Education
* Teaching Mathematics and its Applications
* Teaching Sociology
* Technical Innovations & Patient Support in Radiation Oncology
* Techniques in Coloproctology (Tech Coloproctol)
* Techniques in Gastrointestinal Endoscopy
* Techniques in Regional Anesthesia and Pain Management
* Technische Universität Dresden - Betriebswirtschaftslehre/Logistik (author-date) (TUD BWL/Logistik (author-date))
* Technische Universität Dresden - Erziehungswissenschaften (author-date) (TUD Erziehungswissenschaften (author-date))
* Technische Universität Dresden - Finanzwirtschaft und Finanzdienstleistungen (author-date, with short titles) (TUD Betriebswirtschaftslehre (author-date, with short titles))
* Technische Universität Dresden - Finanzwirtschaft und Finanzdienstleistungen (author-date) (TUD Betriebswirtschaftslehre (author-date))
* Technische Universität Dresden - Finanzwirtschaft und Finanzdienstleistungen (note) (TUD Betriebswirtschaftslehre (note))
* Technische Universität Dresden - Historische Musikwissenschaft (note, German) (TUD Historische Musikwissenschaft (note, German))
* Technische Universität Dresden - Kunstgeschichte (note, German) (TUD Kunstgeschichte (note, German))
* Technische Universität Dresden - Medienwissenschaft und Neuere Deutsche Literatur (note, German) (TUD Germanistik (note, German))
* Technische Universität Dresden - Medizin (TUD Medizin)
* Technische Universität Dresden - Wirtschaftswissenschaften (German) (TUD WiWi)
* Technische Universität München - Controlling (German) (TUM Controlling)
* Technische Universität München - Unternehmensführung (German) (TUM Unternehmensführung)
* Technische Universität Wien (dissertation) (German) (TU Wien)
* Technological Forecasting & Social Change
* Technologies
* Technology and Economics of Smart Grids and Sustainable Energy
* Technology in Society
* Technology, Innovation and Education
* Technology, Knowledge and Learning (Tech Know Learn)
* Technology, Pedagogy and Education
* Technometrics
* Technovation
* Tectonics
* Tectonophysics
* TÉKHNE - Review of Applied Management Studies
* Telecommunication Systems (Telecommun Syst)
* Telecommunications Policy
* Telematics and Informatics
* Teologia Catalunya
* Terra Nova
* Tertiary Education and Management
* TEST
* Tetrahedron
* Tetrahedron Letters
* Textiles and Clothing Sustainability
* TGM Wien Diplomarbeit (German)
* The AAPS Journal (AAPS J)
* The Academy of Management Annals
* The Accounting Review
* The American Journal of Cardiology
* The American Journal of Clinical Nutrition
* The American Journal of Gastroenterology (AJG)
* The American Journal of Human Genetics
* The American Journal of Medicine
* The American Journal of Pathology
* The American Journal of Psychiatry (AJP)
* The American Journal of Sports Medicine
* The American Journal of Surgery
* The American Journal of the Medical Sciences
* The American Journal of Tropical Medicine and Hygiene
* The American Midland Naturalist
* The American Naturalist
* The American Sociologist (Am Soc)
* The American Statistician (TAS)
* The American Surgeon
* The Analysis of Verbal Behavior
* The Annals of Pharmacotherapy
* The Annals of Regional Science (Ann Reg Sci)
* The Annals of Thoracic Surgery
* The Arts in Psychotherapy
* The Asia Pacific Journal of Anthropology
* The Asia-Pacific Education Researcher
* The Asian Journal of Shipping and Logistics
* The Astronomical Journal
* The Astronomy and Astrophysics Review (Astron Astrophys Rev)
* The Astrophysical Journal
* The Astrophysical Journal Letters
* The Astrophysical Journal Supplement Series
* The Auk
* The Australian Educational Researcher (Aust. Educ. Res.)
* The Australian Law Journal (ALJ)
* The Australian Library Journal
* The Behavior Analyst
* The Biological Bulletin (Biol.Bull.)
* The Bone & Joint Journal (BJJ)
* The Breast
* The British Accounting Review
* The British Journal for the Philosophy of Science (BJPS)
* The British Journal of Cardiology
* The British Journal of Psychiatry (BJP)
* The British Journal of Sociology
* The Canadian Geographer (Le Géographe canadien) (TCG)
* The Canadian Journal of Chemical Engineering
* The Canadian Journal of Hospital Pharmacy
* The Canadian Journal of Psychiatry (CIP)
* The Canadian Veterinary Journal
* The Cell Surface
* The Central African Journal of Medicine
* The Cerebellum (Cerebellum)
* The Ceylon Journal of Medical Science
* The Ceylon Medical Journal
* The Chemical Society of Japan
* The Clinical Neuropsychologist
* The Company of Biologists
* The Computer Games Journal
* The Condor
* The Crop Journal
* The Cryosphere
* The Cryosphere Discussions
* The Design Journal
* The Egyptian Heart Journal
* The Egyptian Journal of Aquatic Research
* The Egyptian Journal of Critical Care Medicine
* The Egyptian Journal of Radiology and Nuclear Medicine
* The Egyptian Journal of Remote Sensing and Space Sciences
* The Egyptian Rheumatologist
* The Electricity Journal
* The EMBO Journal
* The European Journal of Finance
* The European Journal of Health Economics (Eur J Health Econ)
* The European Journal of Psychology Applied to Legal Context
* The European Journal of the History of Economic Thought
* The European Physical Journal C (Eur. Phys. J. C)
* The Extractive Industries and Society
* The FASEB Journal (FASEB)
* The FEBS Journal
* The Foot
* The Geological Society of America (GSA)
* The Geological Society of London
* The Hastings Center Report (HCR)
* The Historical Journal
* The History of the Family
* The Holocene
* The IES Journal Part A: Civil & Structural Engineering
* The Indian Journal of Neurotrauma
* The Indian Journal of Pediatrics (Indian J Pediatr)
* The Institute of Electronics, Information and Communication Engineers (電子情報通信学会) (IEICE)
* The Institution of Engineering and Technology (IET)
* The International Journal of Advanced Manufacturing Technology (Int J Adv Manuf Technol)
* The International Journal of Cardiovascular Imaging (Int J Cardiovasc Imaging)
* The International Journal of Developmental Biology (IJDB)
* The International Journal of Life Cycle Assessment (Int J Life Cycle Assess)
* The International Journal of Management Education
* The International Journal of Psychiatry in Medicine
* The International Journal of Psychoanalysis
* The International Journal of the History of Sport
* The International Review of Retail, Distribution and Consumer Research
* The International Sports Law Journal
* The Internet and Higher Education
* The Irish Journal of Psychology
* The ISME Journal
* The Joint Commission Journal on Quality and Patient Safety
* The Journal for Nurse Practitioners
* The Journal of Academic Librarianship
* The Journal of Adhesive Dentistry (J Adhes Dent)
* The Journal of Agricultural Education and Extension
* The Journal of Agricultural Science
* The Journal of Allergy and Clinical Immunology
* The Journal of Antibiotics
* The Journal of Arthroplasty
* The Journal of Basic & Applied Zoology
* The Journal of Biological Chemistry (JBC)
* The Journal of Bone & Joint Surgery
* The Journal of Cardiovascular Surgery
* The Journal of Cell Biology
* The Journal of Chemical Physics
* The Journal of Chemical Thermodynamics
* The Journal of Chinese Sociology
* The Journal of Clinical Endocrinology & Metabolism
* The Journal of Clinical Investigation
* The Journal of Clinical Psychiatry
* The Journal of Comparative Germanic Linguistics (J Comp German Linguistics)
* The Journal of Comparative Neurology
* The Journal of Continuing Education in Nursing
* The Journal of Economic Asymmetries
* The Journal of Economic Inequality (J Econ Inequal)
* The Journal of Egyptian Archaeology (JEA)
* The Journal of Eukaryotic Microbiology
* The Journal of Evidence-Based Dental Practice
* The Journal of Experimental Biology
* The Journal of Experimental Medicine
* The Journal of Finance and Data Science
* The Journal of Foot & Ankle Surgery (JFAS)
* The Journal of General Physiology
* The Journal of Geometric Analysis (J Geom Anal)
* The Journal of Hand Surgery
* The Journal of Headache and Pain
* The Journal of Heart and Lung Transplantation
* The Journal of Hellenic Studies
* The Journal of Immunology
* The Journal of Imperial and Commonwealth History
* The Journal of Indian Prosthodontic Society
* The Journal of Infection in Developing Countries (JIDC)
* The Journal of International Trade & Economic Development
* The Journal of Juristic Papyrology
* The Journal of Legal Pluralism and Unofficial Law
* The Journal of Mathematical Neuroscience
* The Journal of Medieval and Early Modern Studies
* The Journal of Modern History (JMH)
* The Journal of Molecular Diagnostics (JMD)
* The Journal of Neuropsychiatry and Clinical Neurosciences
* The Journal of Neuroscience
* The Journal of North African Studies
* The Journal of Nuclear Medicine (JNM)
* The Journal of Nutritional Biochemistry
* The Journal of Obstetrics and Gynecology of India (J Obstet Gynecol India)
* The Journal of Organic Chemistry (J. Org. Chem.)
* The Journal of Pain (J Pain)
* The Journal of Parasitology
* The Journal of Pathology
* The Journal of Peasant Studies
* The Journal of Pediatrics
* The Journal of Pharmacology and Experimental Therapeutics
* The Journal of Pharmacy Technology
* The Journal of Physical Chemistry A (J. Phys. Chem. A)
* The Journal of Physical Chemistry B (J. Phys. Chem. B)
* The Journal of Physical Chemistry C (J. Phys. Chem. C)
* The Journal of Physical Chemistry Letters (J. Phys. Chem. Lett.)
* The Journal of Physiological Sciences (J Physiol Sci)
* The Journal of Physiology
* The Journal of Positive Psychology
* The Journal of Primary Prevention (J Primary Prevent)
* The Journal of Prosthetic Dentistry
* The Journal of Pure and Applied Chemistry Research (JPACR)
* The Journal of Real Estate Finance and Economics (J Real Estate Finan Econ)
* The Journal of Roman Studies (JRS)
* The Journal of Sexual Medicine
* The Journal of Social Studies Research
* The Journal of Space Safety Engineering
* The Journal of Supercomputing (J Supercomput)
* The Journal of Supercritical Fluids
* The Journal of Systems & Software
* The Journal of Technology Transfer (J Technol Transf)
* The Journal of the Acoustical Society of America
* The Journal of the American Dental Association
* The Journal of the American Osteopathic Association
* The Journal of the Astronautical Sciences
* The Journal of the Economics of Ageing
* The Journal of the Torrey Botanical Society
* The Journal of Thoracic and Cardiovascular Surgery
* The Journal of Urology
* The Journal of Value Inquiry
* The Journal of Veterinary Medical Science (J. Vet. Med. Sci.)
* The Journal of Wildlife Management
* The Journals of Gerontology, Series A: Biological Sciences and Medical Sciences
* The Knee
* The Korean Journal of Pathology
* The Lancet
* The Lancet Infectious Diseases
* The Lancet Neurology
* The Lancet Oncology
* The Leadership Quarterly
* The Library
* The Lichenologist
* The Malaysian Journal of Pathology
* The Medical Journal of Australia
* The National Medical Journal of India
* The Netherlands Journal of Medicine
* The Neuroscientist
* The New England Journal of Medicine (NEJM)
* The New Iraqi Journal of Medicine
* The New Zealand Medical Journal
* The Nucleus (Nucleus)
* The Ocular Surface
* The Oncologist
* The Open University - A251 - Arts Course
* The Open University - Harvard
* The Open University - M801 - Research Project and Dissertation
* The Open University (numeric, superscript)
* The Open University (numeric)
* The Optical Society (OSA)
* The Pan African Medical Journal (PAMJ)
* The Patient - Patient-Centered Outcomes Research (Patient)
* The Pharmacogenomics Journal
* The Physician and Sportsmedicine
* The Plant Cell
* The Plant Genome
* The Plant Journal
* The Primary Care Companion for CNS Disorders
* The Protein Journal (Protein J)
* The Psychological Record
* The Psychologist-Manager Journal
* The Quarterly Journal of Experimental Psychology
* The Queensland Lawyer (Qld Lawyer)
* The Ramanujan Journal (Ramanujan J)
* The Rangeland Journal
* The Review of Austrian Economics (Rev Austrian Econ)
* The Review of Black Political Economy (Rev Black Polit Econ)
* The Review of Faith & International Affairs
* The Review of Financial Studies
* The Review of International Organizations (Rev Int Organ)
* The Rockefeller University Press
* The Saudi Dental Journal
* The Saudi Journal for Dental Research (SJDR)
* The Scandinavian Journal of Clinical & Laboratory Investigation
* The Scandinavian Psychoanalytic Review
* The Science of Nature (Naturwissenschaften)
* The Seventeenth Century
* The Sixties
* The Social Science Journal
* The Spanish Review of Financial Economics
* The Spine Journal
* The Surgeon
* The Tort Law Review (Tort L Rev)
* The Ulster Medical Journal
* The University of Melbourne - Harvard
* The University of New South Wales - Oxford (UNSW)
* The University of Northampton - Harvard
* The University of Sheffield - School of East Asian Studies - Harvard
* The University of Sheffield - Town and Regional Planning - Harvard
* The University of Sydney - Harvard
* The University of Western Australia - Harvard
* The University of Winchester - Harvard
* The Urban Review (Urban Rev)
* The Vaccine Companion
* The Veterinary Journal
* The Visual Computer (Vis Comput)
* The VLDB Journal
* The World Journal of Biological Psychiatry
* Theologie und Philosophie (German) (ThPh)
* Theologisches Seminar Adelshofen - Harvard (German) (TSA)
* Theoretical and Applied Climatology (Theor Appl Climatol)
* Theoretical and Applied Fracture Mechanics
* Theoretical and Applied Genetics (Theor Appl Genet)
* Theoretical and Applied Mechanics Letters
* Theoretical and Computational Fluid Dynamics (Theor. Comput. Fluid Dyn.)
* Theoretical and Experimental Plant Physiology
* Theoretical Biology and Medical Modelling
* Theoretical Chemistry Accounts (Theor Chem Acc)
* Theoretical Computer Science
* Theoretical Ecology (Theor Ecol)
* Theoretical Issues in Ergonomics Science
* Theoretical Medicine and Bioethics (Theor Med Bioeth)
* Theoretical Population Biology
* Theory and Decision (Theory Decis)
* Theory and Society (Theor Soc)
* Theory in Biosciences (Theory Biosci.)
* Theory of Computing Systems (Theory Comput Syst)
* Theory, Culture & Society
* Therapeutic Advances in Neurological Disorders
* Therapeutic Delivery
* Thérapie
* Theriogenology
* Thermal Science and Engineering Progress
* Thermochimica Acta
* Thieme-German (German)
* Thin Solid Films
* Thin-Walled Structures
* Thinking & Reasoning
* Thinking Skills and Creativity
* Thomson Reuters - Legal, Tax & Accounting Australia
* Thorax
* Thrombosis and Haemostasis
* Thrombosis Journal
* Thrombosis Research
* Thyroid
* Thyroid Research
* Ticks and Tick-borne Diseases
* Tidsskrift for Den norske legeforening
* Tijdschrift voor economische en sociale geografie
* Tijdschrift voor Gerontologie en Geriatrie (Dutch)
* Tijdschrift voor Nucleaire Geneeskunde
* Tijdschrift voor Psychotherapie (Dutch)
* Tijdschrift voor Urologie (Dutch)
* Tissue and Cell
* Tissue Barriers
* Tissue Engineering
* Tobacco Control
* Tobacco Induced Diseases
* TOP
* Topics in Catalysis (Top Catal)
* Topics in Current Chemistry
* Topoi
* Topology and its Applications
* Tourism Management
* Tourism Management Perspectives
* Tourism Planning & Development
* Toxicological & Environmental Chemistry
* Toxicological Sciences
* Toxicologie Analytique et Clinique
* Toxicology
* Toxicology and Applied Pharmacology
* Toxicology in Vitro
* Toxicology Letters
* Toxicology Reports
* Toxicology Research
* Toxicon
* Toxics
* Toxins
* Tracés: Revue de Sciences Humaines (French)
* Traffic
* Traffic Injury Prevention
* Training and Education in Professional Psychology
* Transactions of A. Razmadze Mathematical Institute
* Transactions of Mathematics and its Applications
* Transactions of the American Fisheries Society
* Transactions of the American Philological Association (TAPA)
* Transactions of the ASABE
* Transactions of the Materials Research Society of Japan (Trans. Mater. Res. Soc. Japan)
* Transboundary and Emerging Diseases
* Transcription
* Transfusion
* Transfusion and Apheresis Science
* Transfusion clinique et biologique
* Transfusion Medicine and Hemotherapy
* Transfusion Medicine Reviews
* Transfusionsmedizin
* Transgenic Research (Transgenic Res)
* Transition Metal Chemistry (Transition Met Chem)
* Translation
* Translation Studies
* Translational Andrology and Urology
* Translational Behavioral Medicine (Behav. Med. Pract. Policy Res.)
* Translational Medicine in Diabetes, Lipids and Cardiovascular Prevention
* Translational Medicine of Aging
* Translational Neurodegeneration
* Translational Proteomics
* Translational Psychiatry
* Translational Research
* Translational Research in Anatomy
* Translational Stroke Research (Transl. Stroke Res.)
* Transnational Environmental Law (TEL)
* Transplant Immunology
* Transplantation
* Transplantation Proceedings
* Transplantation Reports
* Transplantation Research
* Transplantation Reviews
* Transport in Porous Media (Transp Porous Med)
* Transport Policy
* Transport Reviews
* Transportation
* Transportation Geotechnics
* Transportation in Developing Economies
* Transportation Infrastructure Geotechnology
* Transportation Planning and Technology
* Transportation Research Part A
* Transportation Research Part B
* Transportation Research Part C
* Transportation Research Part D
* Transportation Research Part E
* Transportation Research Part F: Psychology and Behaviour
* Transportation Research Procedia
* Transportation Research Record: Journal of the Transportation Research Board (TRR)
* Transportation Science
* Transportmetrica A: Transport Science
* Transportmetrica B: Transport Dynamics
* Trauma Case Reports
* Trauma und Berufskrankheit (German) (Trauma Berufskrankheit)
* Traumatology: An International Journal
* Travel Behaviour and Society
* Travel Medicine and Infectious Disease
* Tree Genetics & Genomes
* Tree Physiology
* Trees
* Trends in Anaesthesia and Critical Care
* Trends in Analytical Chemistry
* Trends in Biochemical Sciences
* Trends in Biotechnology
* Trends in Cardiovascular Medicine
* Trends in Cell Biology
* Trends in Cognitive Sciences
* Trends in Ecology & Evolution
* Trends in Endocrinology & Metabolism
* Trends in Environmental Analytical Chemistry
* Trends in Food Science & Technology
* Trends in Genetics
* Trends in Immunology
* Trends in Microbiology
* Trends in Molecular Medicine
* Trends in Neuroscience and Education
* Trends in Neurosciences
* Trends in Organized Crime (Trends Organ Crim)
* Trends in Parasitology
* Trends in Pharmacological Sciences
* Trends in Plant Science
* Trends journals
* Trials
* Triangle (French)
* Tribology International
* Tribology Letters (Tribol Lett)
* Triple Helix
* Tropical Animal Health and Production
* Tropical Diseases, Travel Medicine and Vaccines
* Tropical Doctor
* Tropical Gastroenterology
* Tropical Medicine and Infectious Disease
* Tropical Plant Biology (Tropical Plant Biol.)
* Tropical Plant Pathology
* Tsaqafah
* Tsinghua Science and Technology
* Tuberculosis
* Tumor Biology (Tumor Biol.)
* TumorDiagnostik & Therapie
* Tunnelling and Underground Space Technology incorporating Trenchless Technology Research
* Turabian 8th edition (full note)
* Turabian Style (author-date)
* Turkish Journal of Emergency Medicine
* Turkish Studies
* Twentieth-Century Music
* Tzu Chi Medical Journal
* U Schyłku Starożytności (Polish) (USS)
* U.S. Geological Survey
* Ugeskrift for Læger (Danish)
* Ultramicroscopy
* Ultrasonics
* Ultrasonics - Sonochemistry
* Ultrasound in Medicine and Biology
* Ultrasound in Obstetrics & Gynecology
* Ultrasound International Open
* Uludağ Üniversitesi - Sosyal Bilimler Enstitüsü - İlahiyat Fakültesi (full note, Turkish)
* Uludağ Üniversitesi - Sosyal Bilimler Enstitüsü - İlahiyat Fakültesi (full note, with Ibid., Turkish)
* Uludağ Üniversitesi - Sosyal Bilimler Enstitüsü (author-date, Turkish)
* Uludağ Üniversitesi - Sosyal Bilimler Enstitüsü (full note, Turkish)
* Uludağ Üniversitesi - Sosyal Bilimler Enstitüsü (full note, with Ibid., Turkish)
* Ulusal Travma ve Acil Cerrahi Dergisi (Turkish Journal of Trauma & Emergency Surgery)
* UMK Procedia
* Underground Space
* Undersea & Hyperbaric Medicine Journal
* Unified style sheet for linguistics journals
* United Nations Conference on Trade and Development (UNCTAD)
* United Nations Framework Convention on Climate Change (UNFCCC)
* Universal Access in the Information Society (Univ Access Inf Soc)
* Universe
* Universidad Autónoma de Ciudad Juárez - Estilo Latino Humanístico
* Universidad Evangélica del Paraguay (Spanish)
* Universidade de São Paulo - Faculdade de Medicina Veterinária e Zootecnia - ABNT (Portuguese - Brazil) (ABNT-FMVZ-USP)
* Universidade de São Paulo - Instituto de Matemática e Estatística (USP-IME)
* Universidade Estadual do Oeste do Paraná - Programa Institucional de Bolsas de Iniciação Científica (Portuguese - Brazil) (PIBIC)
* Universidade Federal de Juiz de Fora (Portuguese - Brazil) (UFJF)
* Universidade Federal de Minas Gerais - Faculdade de Ciências Econômicas - ABNT (autoria abreviada) (Portuguese - Brazil) (ABNT-FACE/UFMG)
* Universidade Federal de Minas Gerais - Faculdade de Ciências Econômicas - ABNT (autoria completa) (Portuguese - Brazil) (ABNT-FACE/UFMG)
* Universidade Federal de Sergipe - ABNT (Portuguese - Brazil) (ABTN-UFS)
* Universidade Federal do Estado do Rio de Janeiro - Educação Infantil e Políticas Públicas - ABNT (Portuguese - Brazil) (UNIRIO-EIPP-ABNT)
* Universidade Federal do Paraná - ABNT (Portuguese - Brazil) (ABNT-UFPR)
* Universidade Federal do Rio Grande do Sul - SBUFRGS - ABNT (autoria abreviada) (Portuguese - Brazil) (SBUFRGS-ABNT)
* Universidade Federal do Rio Grande do Sul - SBUFRGS - ABNT (autoria completa) (Portuguese - Brazil) (SBUFRGS-ABNT)
* Università Cattolica del Sacro Cuore (note, Italian)
* Università Pontificia Salesiana (UPS)
* Università Pontificia Salesiana (English) (UPS-en)
* Università Pontificia Salesiana (French) (UPS-fr)
* Università Pontificia Salesiana (Italian) (UPS-it)
* Università Pontificia Salesiana (Portuguese - Brazil) (UPS-pt-BR)
* Università Pontificia Salesiana (Spanish) (UPS-es)
* Universitas Negeri Semarang - Fakultas Matematika dan Ilmu Pengetahuan Alam (Indonesian) (UNNES-FMIPA)
* Universitas Negeri Yogyakarta - Program Pascasarjana (Indonesian) (UNY-PPS)
* Universität Bremen - Institut für Politikwissenschaft (German) (IfP Uni Bremen)
* Universität Heidelberg - Historisches Seminar (German)
* Universität Mainz - Geographisches Institut (German)
* Universität zu Köln - Seminar für ABWL und Finanzierungslehre (German)
* Universitätsmedizin Göttingen (German) (UMG)
* Université Catholique de Louvain - Histoire (French) (UCL)
* Université de Liège - Droit (French) (ULiège - Droit)
* Université de Liège - Histoire (French) (ULg)
* Université de Montréal - APA (French - Canada) (UdeM APA FR)
* Université de Picardie Jules Verne (Amiens) - Thèse de UFR de Médecine
* Université de Sherbrooke - Département de géomatique (French - Canada)
* Université de Sherbrooke - Faculté d'éducation (French - Canada)
* Université du Québec à Montréal - Département d’histoire (French - Canada) (UQAM - histoire)
* Université du Québec à Montréal (French - Canada) (UQAM)
* Université Laval - Département d'information et de communication (French - Canada)
* Université Laval - Département des sciences historiques (French - Canada)
* Université Laval - Faculté de théologie et de sciences religieuses (French - Canada) (Ftsr Univ. Laval)
* Université libre de Bruxelles - Histoire (French) (ULB-Hist)
* Universiteit Utrecht - Onderzoeksgids Geschiedenis (Dutch) (UU Geschiedenis)
* Universitetet i Oslo - Rettsvitenskap (Norwegian - Bokmål) (UiO-rettsvitenskap)
* Universiti Kebangsaan Malaysia (Malay) (UKM)
* Universiti Teknologi Malaysia - Harvard
* Universiti Tunku Abdul Rahman - Harvard
* University College Dublin - School of History & Archives
* University College Lillebælt - APA (Danish)
* University College Lillebælt - Harvard (Danish)
* University College Lillebælt - Vancouver (English)
* University for the Creative Arts - Harvard (UCA)
* University for the Creative Arts (figures and illustrations) (uca-illustrations)
* University of Abertay Dundee - Harvard
* University of Bath - Harvard
* University of Birmingham - Harvard
* University of Bologna - Liberal Arts College (Università di Bologna - Facoltà di Lettere e Filosofia) (Italian)
* University of Brighton School of Environment & Technology - Harvard
* University of Cambridge - Faculty of History
* University of Cape Town - Harvard
* University of Exeter - Geography - Harvard
* University of Gloucestershire - Harvard
* University of Gothenburg - APA (Swedish legislations) (GU - APA - Swedish legislations)
* University of Greenwich - Harvard (UoG Harvard)
* University of Helsinki - Faculty of Theology (Finnish)
* University of Kent - Harvard
* University of Leeds - Harvard
* University of Limerick (Cite it Right) - Harvard
* University of Lincoln - Harvard
* University of New England, Australia (note)
* University of South Australia 2011 - Harvard (UniSA)
* University of South Australia 2013 - Harvard (UniSA)
* University of Sunderland - Harvard
* University of Technology Sydney - Harvard (Harvard UTS)
* University of the West of England (Bristol) - Harvard (UWE Bristol)
* University of the West of Scotland - Harvard
* University of Westminster - Harvard
* University of Wolverhampton - Harvard
* University of Worcester - Harvard
* University of York - American Psychological Association 6th edition (UoY APA)
* University of York - Chicago Manual of Style 16th edition (UoY Chicago)
* University of York - Harvard (UoY Harvard)
* University of York - Harvard - Archaeology (UoY Harvard Archaeology)
* University of York - Harvard - Environment (UoY Harvard Environment)
* University of York - IEEE
* University of York - Modern Humanities Research Association 3rd edition (UoY MHRA)
* University of York - Modern Language Association 8th edition (UoY MLA)
* University of York - OSCOLA (UoY OSCOLA)
* University of York - Vancouver
* University of Zabol (English) (UOZ)
* University of Zabol (Persian) (UOZ (Fa))
* Updates in Surgery (Updates Surg)
* Uppsala universitet - Historia (UU.Hist)
* Uppsala universitet, Institutionen för biologisk grundutbildning (IBG Uppsala)
* Urban Climate
* Urban Ecosystems (Urban Ecosyst)
* Urban Forestry & Urban Greening
* Urban Forum
* Urban Habitats
* Urban Rail Transit
* Urban Research & Practice
* Urban Science
* Urban Studies
* Urolithiasis
* Urologia Internationalis
* Urologic Oncology: Seminars and Original Investigations
* Urological Science (UROLS)
* Urology
* Urology Case Reports
* USDA Forest Service - Pacific Northwest Research Station (USFS PNWRS)
* User Modeling and User-Adapted Interaction (UMUAI)
* Utah Geological Survey
* Utilities Policy
* uwf UmweltWirtschaftsForum (German) (uwf)
* Vaccine
* Vaccine Reports
* Vaccines
* Vacuum
* Vadose Zone Journal
* Value in Health
* Value in Health Regional Issues
* Vancouver
* Vancouver (author-date)
* Vancouver (brackets, no "et al.")
* Vancouver (brackets, only year in date, no issue numbers)
* Vancouver (brackets)
* Vancouver (French - Canada)
* Vancouver (superscript, brackets, only year in date)
* Vancouver (superscript, only year in date, no issue numbers)
* Vancouver (superscript)
* Vascular Cell
* Vascular Medicine
* Vascular Pharmacology
* Vegetation History and Archaeobotany (Veget Hist Archaeobot)
* Vehicle System Dynamics
* Vehicular Communications
* Venture Capital
* Verhaltenstherapie
* Verslaving (Dutch)
* Veterinary and Animal Science
* Veterinary Immunology and Immunopathology
* Veterinary Medicine Austria (Wiener Tierärztliche Monatsschrift) (WTM)
* Veterinary Microbiology
* Veterinary Parasitology
* Veterinary Parasitology: Regional Studies and Reports
* Veterinary Pathology
* Veterinary Quarterly
* Veterinary Radiology & Ultrasound
* Veterinary Record
* Veterinary Record Case Reports
* Veterinary Record Open
* Veterinary Research
* Veterinary Research Communications (Vet Res Commun)
* Veterinary Sciences
* Vibrational Spectroscopy
* Victoria University - Harvard (VU)
* Video Journal and Encyclopedia of GI Endoscopy
* Video Journal of Education and Pedagogy
* Vienna Legal
* Vietnam Journal of Computer Science
* Vietnam Journal of Mathematics
* Vietnam Ministry of Education and Training (English) (BGDDT_TA)
* Vietnam Ministry of Education and Training (Vietnamese) (BGDDT_TV)
* Vigiliae Christianae (VC)
* Vilnius Gediminas Technical University (Lithuanian) (VGTU)
* Vingtième Siècle. Revue d'histoire (French)
* Virchows Archiv (Virchows Arch)
* Virology
* Virology Journal
* Virology Reports
* Virtual and Physical Prototyping
* Virtual Reality
* Virulence
* Virus Genes
* Virus Research
* VirusDisease
* Viruses
* Vision
* Vision Research
* Visual Cognition
* Visual Informatics
* Visual Journal of Emergency Medicine
* Visual Neuroscience
* Visual Studies
* Visualization in Engineering
* Viszeralmedizin
* Vita Latina (auteurs anciens, French) (VL (text. anc.))
* Vita Latina (French) (VL)
* Vocation sage-femme
* Vocations and Learning
* Vodohospodářské technicko-ekonomické informace (Czech) (VTEI)
* Vodohospodářské technicko-ekonomické informace (English) (VTEI)
* VOLUNTAS: International Journal of Voluntary and Nonprofit Organizations (Voluntas)
* Vox Sanguinis
* Vulnerable Children and Youth Studies
* Waste and Biomass Valorization (Waste Biomass Valor)
* Waste Management
* Water
* Water Alternatives (WA)
* Water Conservation Science and Engineering
* Water Environment Research
* Water History (Water Hist)
* Water International
* Water Research
* Water Resources and Economics
* Water Resources and Industry
* Water resources and rural development
* Water Resources Management (Water Resour Manage)
* Water Resources Research
* Water SA
* Water Science
* Water Science & Technology
* Water Science and Engineering
* Water Security
* Water-Energy Nexus
* Water, Air, & Soil Pollution (Water Air Soil Pollut)
* Waterbirds
* Wave Motion
* Waves in Random and Complex Media
* Wear
* Weather and Climate Extremes
* Weather and Forecasting
* Weather, Climate, and Society
* Web Ecology
* Webbia
* Weed Science
* Weed Science Society of America (WSSA)
* Weed Technology
* Welding in the World (Weld World)
* Welding International
* West European Politics
* West Virginia Medical Journal
* Western Pacific Surveillance and Response
* Westfälische Wilhelms-Universität Münster - Medizinische Fakultät (German) (WWU)
* Wetlands
* Wetlands Ecology and Management (Wetlands Ecol Manage)
* Wheaton College - Ph.D. in Biblical and Theological Studies
* WHO Regional Office for Europe - Harvard
* WHO Regional Office for Europe (numeric)
* WHO South-East Asia Journal of Public Health
* Wiener klinische Wochenschrift (Wien Klin Wochenschr)
* Wiener klinische Wochenschrift Education (German) (Wien. Klin. Wochenschr. Educ)
* Wiener klinisches Magazin (German)
* Wiener Medizinische Wochenschrift (German) (Wien Med Wochenschr)
* Wilderness & Environmental Medicine
* Wildlife Biology
* Wildlife Research
* Wiley-VCH books
* Wine Economics and Policy
* Wireless Communications and Mobile Computing (WCMC)
* Wireless Networks (Wireless Netw)
* Wireless Personal Communications (Wireless Pers Commun)
* Wirtschaftsuniversität Wien - Handel und Marketing (German - Austria) (WU H&M)
* Wirtschaftsuniversität Wien - Wirtschaftspädagogik (German - Austria) (WU Wipäd)
* Wirtschaftsuniversität Wien (author-date)
* wissen kompakt (German) (wissen kompakt)
* Wissenschaftlicher Industrielogistik-Dialog (German - Austria) (WilD)
* WMU Journal of Maritime Affairs (WMU J Marit Affairs)
* Woman - Psychosomatic Gynaecology and Obstetrics
* Women & Performance: a journal of feminist theory
* Women's Health
* Women's Health Issues
* Women's Midlife Health
* Women's Studies International Forum
* Wood Science and Technology (Wood Sci Technol)
* Work & Stress
* Workplace Health & Safety
* Workplace Review (WR)
* World Allergy Organization Journal
* World Applied Sciences Journal (WASJ)
* World Archaeology
* World Congress on Engineering Asset Management 2010 (WCEAM)
* World Development
* World Development Perspectives
* World Journal of Acupuncture - Moxibustion
* World Journal of Emergency Surgery
* World Journal of Gastroenterology (World J Gastro)
* World Journal of Microbiology and Biotechnology (World J Microbiol Biotechnol)
* World Journal of Otorhinolaryngology-Head and Neck Surgery
* World Journal of Surgery (World J Surg)
* World Journal of Surgical Oncology
* World Journal of Urology (World J Urol)
* World Medical Journal
* World Mycotoxin Journal
* World Neurosurgery
* World Organisation for Animal Health - Scientific and Technical Review (OIE - Sci. Tech. Rev.)
* World Patent Information
* World Politics
* World Psychiatry
* World Wide Web
* World's Poultry Science Journal (WPSJ)
* Worm
* Wound Medicine
* Writing Systems Research
* Xenotransplantation
* Yakugaku Zasshi (Journal of the Pharmaceutical Society of Japan)
* Yakuzai Ekigaku (Japanese Journal of Pharmacoepidemiology)
* Yale Journal of Biology and Medicine
* Yearbook of English Studies
* Yeast
* York St John University - Harvard (Harvard-YSJU)
* Zagazig University Medical Journal
* Zahnmedizin up2date
* Zastosowania Komputerów w Elektrotechnice (ZKwE)
* ZDM (ZDM Mathematics Education)
* Zdravniški Vestnik (Slovenian Medical Journal) (Vdrav Vestn)
* Zeitschrift für Allgemeinmedizin (ZFA)
* Zeitschrift für angewandte Mathematik und Physik (Z. Angew. Math. Phys.)
* Zeitschrift für Außen- und Sicherheitspolitik (German) (Z Außen Sicherheitspolit)
* Zeitschrift für Bildungsforschung (German) (Z f Bildungsforsch)
* Zeitschrift für deutsche Philologie (German) (ZfdPh)
* Zeitschrift für Didaktik der Naturwissenschaften (German)
* Zeitschrift für die gesamte Versicherungswissenschaft (German) (ZVersWiss)
* Zeitschrift für die Geschichte des Oberrheins (German)
* Zeitschrift für Energiewirtschaft (German) (Z Energiewirtsch)
* Zeitschrift für Epileptologie (German) (Zeitschrift Epileptologie)
* Zeitschrift für Erziehungswissenschaft (German) (Z Erziehungswiss)
* Zeitschrift für Gastroenterologie
* Zeitschrift für Geburtshilfe und Neonatologie
* Zeitschrift für Gerontologie und Geriatrie (German) (Zeitschrift Gerontologie Geriatrie)
* Zeitschrift für Herz-,Thorax- und Gefäßchirurgie (German) (Zeitschrift Herz Thorax- Gefäßchirurgie)
* Zeitschrift für Immobilienökonomie (German)
* Zeitschrift für Internationale Beziehungen (German) (ZIB)
* Zeitschrift für Kunstgeschichte (ZfK)
* Zeitschrift für Medienwissenschaft (German) (zfm)
* Zeitschrift für Orthopädie und Unfallchirurgie
* Zeitschrift für Ostmitteleuropa-Forschung (German) (ZfO)
* Zeitschrift für Pädagogik (German) (ZfPäd)
* Zeitschrift für Palliativmedizin
* Zeitschrift für Politikwissenschaft
* Zeitschrift für Psychodrama und Soziometrie (German) (Z Psychodrama Soziometr)
* Zeitschrift für Psychologie
* Zeitschrift für Qualitative Forschung (German) (ZQF)
* Zeitschrift für Religionswissenschaft (author-date) (ZfR (author-date))
* Zeitschrift für Religionswissenschaft (note) (ZfR (note))
* Zeitschrift für Rheumatologie (German) (Zeitschrift Rheumatologie)
* Zeitschrift für Sexualforschung
* Zeitschrift für Soziologie (German) (ZfS)
* Zeitschrift für Theologie und Kirche (German) (ZThK)
* Zeitschrift für Vergleichende Politikwissenschaft (German) (Z Vgl Polit Wiss)
* Zeitschrift für Weiterbildungsforschung - Report (German)
* Zentralblatt für Arbeitsmedizin, Arbeitsschutz und Ergonomie (German) (Zentralblatt Arbeitsmedizin Arbeitsschutz Ergonomie)
* Zentralblatt für Chirurgie
* Zeszyty Naukowe WCO, Letters in Oncology Science
* Zeszyty Prawnicze BAS (Polish)
* ZooKeys
* Zoological Journal of the Linnean Society (ZJLS)
* Zoological Letters
* Zoological Studies
* Zoologischer Anzeiger
* Zoology
* Zoology and Ecology
* Zoology in the Middle East
* Zoomorphology
* Zootaxa
* Zwitscher-Maschine
* ZWR - Das Deutsche Zahnärzteblatt
* Российский физиологический журнал им. И.М. Сеченова (Russian)
* Успехи геронтологии (Russian)

