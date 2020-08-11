---
layout: post
title:  "Nanoparticle Based Gene Therapy For Neurodegenerative Diseases"
date:   2020-08-11 15:00:00 +0800
author: "Yi-Hsuan (Andy) Chen, Chia-En (Calvin) Wong"

---

> I grew a strong interest in nanomedicine in 2018 and took class called **Translational Nanomedicine** with [Dr. Chia-En Wong](https://www.facebook.com/Calvin.C.E.Wong) and we and spent some time researching in this field and compiling this mini-review to document what we've learnt. 

> **Disclaminar:**
> This mini-review was written as a course project in 2018, which may containe errors and outdated references. 



* Do not remove this line (it will not be displayed)
{:toc}


## Introduction

Neurodegenerative diseases are a heterogenous group of disorders including many debilitating, incurable diseases and their prevalences are rapidly rising[1]. These disorders include Alzheimer's disease, Huntington’s disease, Parkinson's disease (PD), and vascular dementia following stroke as well. Despite the wide variety of disease presentations among these disorders from cognitive impairment, memory deficits, to motor disturbances, common features at cellular levels such as neuronal apoptosis in the central nervous system are observed [2]. However, current treatments and medication could only help to relief symptoms and to delay disease progression. There is still an urgent need to develop new and more effective curative strategies.

By introducing genes or regulatory entities to correct or to compensate functional aberrance derived from disease causing genes, gene therapy has shed a light in treating neurodegenerative disorders and might reverse certain previously incurable diseases [3][4]. Gene therapy is carried out by delivering genetic materials or substances that alter target gene(s) expressing or change their sequence contents into the desired cells. It therefore contains the content cargo, a vector, and an approach to be effectively delivered and activated at the desired locale. The cargos to be delivered may include nucleic acids, proteins or other entities. Plasmid DNA carrying gene expression vectors, RNAs such as siRNA, ribozyme, microRNAs are functional nucleic acids that modulate specific gene expression directly or indirectly. Proteins such as CRISPR/Cas9, Cas12 in combination with guiding nucleic acids to serve as genome editing machinery are rapidly growing to be a promising tool for gene therapy. Besides, artificial targeting light activated nano scissors (ATLANS) has been developed to perform precision gene scission in bacteria, mammalian cells, and small animal such as C. Elegans [5]. These functional components are able to either change the gene expression level, or to correct the abnormal gene sequence in the target cells6

The delivery of genetic materials into the target site has long been a critical issue in gene therapy. Among different tissues, gene delivery to the central nervous system is especially challenging since the CNS is well isolated and protected by the blood brain barrier (BBB), a highly selective barrier separating the CNS cells and microenvironment from the systemic circulation. It plays important roles in regulating the permeability of the cargo to be delivered into CNS[6]. Since the permeability strongly affects the bioavailability in the CNS thereby therapeutic efficacy, different delivery systems including viral and non-viral vectors were proposed

Among various non-viral vectors, nanoparticles with the size ranging from 1 nm to 100 nm were discovered to show significant advantages in gene delivery to the CNS[7][8]. The nanoscale size of nanoparticles enables their effective permeation through a wide range of biological barriers. The surface chemistry and ligands conjugation further improve the selectivity of target-specific binding and intracellular delivery to the desired tissues and cells[9]. Having these unique properties, the applications of nanoparticles in gene therapy, especially CNS targeting, for neurodegenerative disorders are increasing with significant progression over the past decade.

In this article, we reviewed and summarized the design, applications development, and critical problems encountered, as well as future trend and potentials of nanoparticles in the CNS gene therapy for neurodegenerative diseases.

## Neurodegenerative diseases

Neurodegenerative diseases are a heterogeneous group of disorders characterized by the progressive decline of the function of the central nervous system as well as the progressive loss of neurons in the brain and/or the spinal cord. These disorders have become to affect more and more people globally because of their high prevalence and in part because of the increase in the aging population in many societies globally[10] Being more prevalent in elderly individuals, neurodegenerative diseases have become an increasing cause of morbidity and mortality. Among the neurodegenerative diseases, Alzheimer’s disease is the most prevalent that affects an estimated 24 millions people around the world[1] Such statistics might even be underestimated due to under-diagnosis resulting from the subtle symptoms in early-stage disease.

Clinical symptoms of neurodegenerative diseases can vary from cognitive and memory decline, behavioral and personality change, to motor deficits and movement disorders [11]. While neurodegenerative disease patients may have heterogeneous clinical presentations and a wide spectra of underlying mechanism, certain overlapping features and pathophysiology do exist among these disorders. Particularly, the pathological characteristics of neuronal loss accompanied by abnormal protein inclusions and gliosis in the central nervous system are commonly observed [12][13].

Despite the different pathogenic hypothesis proposed for different neurodegenerative disorders, some common mechanisms play important roles. One of the common phenomena prior to neurodegeneration is neuroinflammation[14]. Neurons harbor innate immune sensors such as toll-like-receptors(TRLs) and nucleotide-binding oligomerization domain-like receptors (NOD-like receptors). These innate immune receptors are able to trigger downstream signaling cascades involving neurogenesis, neurite retraction, autophagy, and neuronal apoptosis in response to injury, aging, and cellular stress. [10][15] Once the intrinsic injuries and abnormalities are detected, neurons in the CNS release ions, ATPs, growth factors, cytokines, and neurotransmitters to signal neighboring cells including astrocytes and microglia.[16] When these stress signals are broadcasted, the activated microglia may produce immune mediators including cytokines, chemokines,and complement proteins, which may induce neurotoxicity. For example, TNF-α was reported to be involved in the neuronal loss in the substantia nigra associated with pathogenesis of PD, while blockage of TNF-α was able to alleviate the neuronal loss in a mouse model of PD[17][18]In addition, astrocyte also respond to the neuronal stress signals by producing various immune mediators and by initiating astrogliosis.

Currently, there are no curative treatment to neurodegenerative diseases. Current clinical management practice by either medications or non-medication were aim symptoms relief and delaying disease progression. Many non-medication modalities such as cognitive training through multimodal exercise and cognitive-behavior training CBT have been used to alleviate the disease progression. [19] Conventional medications approved for neurodegenerative diseases treatment often target at disease-associated neurotransmission pathways. These drugs include acetylcholinesterase inhibitors for Alzheimer’s disease, dopaminergic agonists and anti-dyskinesics for Parkinson’s disease, and vesicular monoamine transporter 2 inhibitors for Huntington’s disease. [20][21] Beside convention medications, monoclonal antibodies targeting interleukin-2 receptor and CD52 were used for multiple sclerosis to block the immune-mediated disease progression.[22][23] In addition, gene therapy has also been developed to treat neurodegenerative diseases. For example, nusinersen, a survival motor neuron-2 (SMN2)-directed antisense oligonucleotide was the first approved medication for spinal muscular atrophy[24][25]. More other gene therapy modalities were under development and various stages of clinical trials. These innovative therapeutic designs may provide a new paradigm shift in the treatment strategy of neurodegenerative diseases in the near future.

## Gene Therapy

Gene therapy is aimed to introduce genetic materials or genetically modified cells to correct abnormal genes and/or to compensate abnormal gene functions. The introduced genes can vary from genes that are normally present but mutated in the patient to genes producing specific protein with certain function[26][27]. Aside from introducing the proteins to rescue the deficit phenotypes, gene therapy techniques involving alteration of their intrinsic gene expression thus to transiently or permanently restore the physiological functions. The way to achieve a successful gene therapy could be introducing a new gene, modification of gene expression at epigenetic level, or direct genome editing to correct mutated sequences responsible for a disease via CRISPR or other methods[28]. For neurodegenerative diseases, many of the above mentioned modalities although may have the potential to reverse the pathogenesis or to alleviate the clinical symptoms, were further complicated by the challenging delivery routes limited by the BBB.

### Plasmid DNA

For the delivery of genetic materials into cells, the most well developed and straightforward approach is the direct gene transfer with plasmid DNA(pDNA). Most non-viral vectors use plasmid DNA as the carrier of cDNA of the target gene. The pDNA is a bacteria origin circular double strand DNA that can be produced and amplified from bacterial culture. The composition of pDNA includes the cDNA of the desired therapeutic gene and the expression modulation element such as promoter and enhancer, which are responsible for precision control of the final protein expression levels to achieve therapeutic efficacy.[29][30][31] Beside the target gene expression construct, the pDNA may also include an insert fragment to enable replication and antibiotic selection in cloning. In comparison to viral vectors, there are certain advantages for pDNA based gene therapy. First, pDNA elicits less immune responses compared to commonly used viruses such as retrovirus, adenovirus, and adeno-associated-virus, which also significantly reduced the risk of severe immunoreaction in readministration.[32][33] Next, the cells transfected with pDNA usually produce endogenous proteins with correct folding and post-translational modifications.

The methods for pDNA delivery are quite diverse. Direct delivery of naked pDNA can be performed by local injection to the soft tissues such as liver and muscle. Naked pDNA can also be delivered locally by airway into the respiratory tract of lung. Besides direct delivery, pDNA can also be delivered by physical and chemical methods such as lipids/lipoplexes, electroporation, gene gun and nanoparticles.

### RNAi

RNA interference provides sequence specific post-transcriptional gene expression silencing mediated by small double strand RNAs called small interfering RNA(siRNA) that is usually 20 to 24 base pairs. The siRNA can form RNA-induced silencing complex（RISC) in the cytoplasm, where the double strand siRNA is unwounded to form single strand RNA. The antisense ssRNA can scan and bind to complementary mRNA. Once the mRNA is bound by ssRNA, mRNA cleavage is induced and gene expression is silenced post-transcriptionally.[34], [35] [36]

Gene therapy utilizing RNAi has the advantage of highly sequence specific gene modulation while the major obstacle hampering the successful clinical application remains the need for effective and safe delivery methods for systemic and targeted RNAi delivery in patients. The delivery of siRNA can be generally categorized into viral vector and non viral vector. Viral delivery of RNAi machinery can be achieved by viral expression of short hairpin RNA(shRNA), in which the two complementary target-specific RNA strands are covalently linked with a RNA hairpin, forming structures mimicking nuclear processed miRNAs and as able to engage RNAi. In addition, due to the small length of RNAi, viral vectors with smallest capacity so that even adeno-associated-virus(AAV) is also applicable.[37][38]

On the other hand, nonviral delivery of siRNA includes various conjugates such as siRNA-cholesterol complex targeting the liver and siRNA-peptide complex targeting the brain. Nanoparticles formed by polymers were also utilized to deliver siRNA.[39][40][41]
However, a major question lies in the uncertainties about the therapeutic window, including the toxicities commonly associated with lipid-nucleic acid complexes. Another major limitation to the use of siRNAs is their short half-life thus limiting effective intracellular siRNA concentrations and subsequent silencing effects. It usually declined within 2 weeks. Thus, chronic diseases such as neurodegenerative disorders will either require repetitive siRNA administration or long-term endogenous expression of the RNAis.

### Genome editing apparatus

Different from previously discussed gene therapy strategies where the introduced genetic material serve their function independently from the chromosomal DNA. Genome editing aims to directly modify the gene sequence in the chromosome and targeted nucleases or photonic DNA scissors are often utilized as tool for genome editing. The clustered regularly interspaced short palindromic repeats (CRISPR) associated nuclease 9(CRISPR/Cas9) is a revolutionary tool for gene editing. Originally as the bacterial immunity mechanism against foreign invading nucleotides, in which the invading DNA is incorporated into the CRISPR locus and forthur processed into CRISPR RNA (crRNA). Together with the trans-activating CRISPR RNA (tracrRNA), the crRNA forms a ribonucleoprotein complex with the endonuclease Cas9 cleaving the targeted invading DNA. Previous study had simplified the system by fusing the sequence specific crRNA to the tracrRNA to create a single guide RNA (sgRNA), which is sequence specific to the crRNA target and recruits the Cas9 nuclease to create site-specific double-strand breaks. In combination with a desired synthetic repair DNA template, the double-strand break can be repaired by homology-directed repair (HDR) enabling the introduction of any desired base-pair changes.[42][43][44]
The CRISPR/Cas9 and its power in genome editing is also utilized in gene therapy, viral vector such as adeno-associated virus has been applied to deliver CRISPR/Cas9 system. The major advantage of CRISPR/Cas9 over previous zinc finger nucleases (ZNFs) and transcription activator-like effector nucleases (TALENs) is the simplicity of CRISPR/Cas9. Instead of engineering the sequence-specific DNA-binding proteins, the guide RNA is easy and fast to synthesize, and can be designed differently in accordance to different target genes. However, there are still challenges remained. one of the major hurdles is the off-target effects that may resulted in unpredictable consequences.[45][46][43][47]
Beside naturally derived enzyme based gene editing tools, artificial gene editing apparatus has also been reported to down regulate target genes. 

## Strategies in gene therapy delivery for neurodegenerative diseases via engineered nanoparticles

There are four major challenges in the delivery of gene therapy to the diseased sites in the brain: the route of delivery, the blood brain barrier, the specific targeting to the diseased cells, and the intracellular activation of the gene therapy machinery.

The first challenge faced in systemic delivery of genetic materials is the route of therapeutics delivery. For intravenous delivery through circulation system, the bare genetic material such as DNA, siRNA, antisense oligonucleotide are prone to the degraded by nucleases in the blood. [48] [49] There are no available effective DNase or RNase inhibitors to be used safely to prevent the exogenously injected therapeutic nucleic acids from degradation. [50] The degraded genetic materials could be recognized by the innate immune system and may trigger adverse immune response to cause systemic inflammation in some cases. [51] Besides, for small bare therapeutic genetic materials with a typical strand length around 22 bases (∼7 kDa), the therapeutic genetic materials may undergo rapid excretion from the kidney.[52] The immunogenicity of the delivery vector is also an important consideration. For example, viral vector was one of the most popular alternative to load therapeutic genetic materials for systemic delivery. Around 70% of gene therapy clinical trials used modified virus such as adeno-adenovirus, retroviruses or lentivirus. However, the high immunogenicity of viral vectors significantly compromised their efficacy and stability for in vivo applications. 

The second consideration is the Blood brain barrier (BBB), which isolates central nervous system from blood circulation. BBB is a very highly selective barrier that plays an important role in regulating the permeability of CNS delivery. It affects the bioavailability of the therapeutics in the CNS. Many promising experimental agents proven to be effective in the labs kept showing disappointing results in the following clinical trials due to their limited CNS delivery including insufficient crossing of drug through BBB [53]. For example, Tarenflurbil is an AD treatment candidate that showed efficacy in the AD animal model, but failed to cross human BBB thus leading to failure in subsequent clinical trials. [54] Failing in later development stage has become a significant trait for CNS drugs due to compromised entry to the target lesion in the CNS. [55] Thus, understanding the physiology of BBB is important for designing new drug formulations with high BBB permeability and has emerged as one critical jobs for successful gene delivery as well.

Third, specific targeting to the diseased tissues and the genes to be modified remains a considerable challenge especially upon crossing BBB. The specificity and adequate accumulation and distribution of genetic modifying materials are required for safe and efficacious gene therapy. Low specific accumulation implies excessive amount of administration of vectors and elevated risks of the off-target effect. For example, the RNA materials such as siRNA have no specificity for brain tissues, thus more dosage would be needed to achieve adequate therapeutic efficacy. Also, the risk of insertional mutagenesis resulting from placing a foreign DNA fragment into the unpredictable sites may raise great concerns in later disease development when using certain viral vectors. [56]

Fourth, the barriers of intracellular trafficking also influence the successful rate of gene therapy. RNA molecules should be delivered to the cytosol and DNA molecules should be delivered to the nucleus. Intracellular trafficking barriers may include cellular internalization, endosomal escape, cytosolic transportation, and nuclear import (for DNA molecules).[57] Most delivery system for genetic materials undergoes cellular internalization. However, the poor endocytosis rate and passive diffusion of RNA and DNA molecules crossing the cell membrane greatly limit their delivery efficiency. [58] [59] Low endosomal escape rate and the degradation of genetic material inside the endosome also pose a hurdle following the cellular internalization. [60] After the endosomal escape, the DNA still needs to travel certain distance to enter the nucleus. Thus, an intact microtubule network is required for efficient cytosolic transportation. [61] However, the cytosol of the cell is a crowded environment containing various cytoskeleton filament. Studies shows the actin filaments will restrict the mobility of the plasmid and interfere their transportation to nucleus. [62] Finally, to achieve successful transfection, DNA molecules need to cross the nuclear pore complex and enter the nucleus. [63]
Nanoparticle-based gene therapy

The nanoparticles are organic or inorganic particles of the size around 1 nm to 1000 nm. As the advancement of nanotechnology, the applications of nanoparticles to medicine have been carried out for decades. The unique properties of nanoparticle such as the size and the surface functionality provide robust ways to enhance the efficiency of site-specific drug delivery. The specific size of nanoparticles enables them to penetrate a wide range of biological barriers but can avoid nanoparticles from being filtrated by kidney. The design of surface ligands and the surface charge can enhance the target-specific binding and properly unanoparticleacking of genetic material. Also, conjugation with nanoparticle can protect genetic material from degradation in the delivery process. [9] Recently, different types of nanoparticle has been developed for the genetic material delivery including polymeric material (micelle, polymersome, nanogel, dendrimer) [64][65], gold nanoparticles [66], silica nanoparticles.[67] [68], liposome [69], lipid nanoparticles [70] and, recently, exosome[71] and DNA nanostructure-based nanoparticle [72] With the conjugation of nanocarriers, the potential of gene therapy to treat neurodegenerative diseases can leap to the next level.

### Overcoming the biological hurdles in the circulation system

Degradation, glomerular filtration, and immune clearance are three major factors eliminating the genetic materials in the circulatory system. Modification of DNA/RNA to form nanoparticle or conjugation with other nanoparticle can prevent the degradation of plasma nuclease. For example, Ponnuswamy and colleagues shows modification DNA with PEGylated oligo-lysine co-polymer can significantly stabilize the DNA nanostructure against nuclease degradation by ~1,000-fold. [73] Also, another example given by Zou shows combining siRNA with chimaeric polymersomes delivery platform can extend the half-life of siRNA in blood circulation from 8 min to 1.8h. [74]. The small size of DNA/RNA molecules enable them to pass through the pore of frenestrated endothelium of the glomerular (~10 nm) in kidney. Encapsulation or conjugation with nanoparticle around 10-200 nm can increase the size of the DNA/RNA molecules, preventing them from filtering out by glomerular filtration and increasing the concentration in the bloodstream. [75] The naked DNA and viral vectors have shown stronger immunogenicity than the nanoparticles. However, he bloodstream is a very complex physiological environment containing many types of protein. Rapid adsorption of proteins to the surface of nanoparticle has been reported. This opsonization of the nanoparticles can alter the functionalities of nanoparticle and induce the clearance by reticuloendothelial system in the spleen and liver. Surface modification with PEG is a common way to stop the opsonization. The surface of PEGlyated nanoparticles creates high level of hydration by the hydrophilic polyether backbone preventing protein adsorption on typically hydrophobic polymer surfaces by means of steric repulsion. [76] Other solutions include coating with zwitterionic molecules (such as polysaccharides) or hyaluronic acid-coated chitosan also generate hydrophilic surface to stop opsonization. [77] [78] Furthermore, cell membrane-camouflaged nanoparticles emerge as new approach to minimize the opsonization. Erythrocyte-mimicking nanoparticles coated with RBC membrane shows superior circulation time and bioavailbility compared to the PEGlyated nanoparticles. [79]

### Increasing the permeability of the blood brain barrier

The BBB is a diffusion barrier presents in the cerebral endothelial cells. Recent studies in the past few years shows BBB is not only a diffusional barrier between vessel and brain, but a complex and dynamic interface supplies the need of CNS and mediate the communication between CNS and peripheral tissue. [6] The main structural characteristic of BBB is the tightly connected endothelial cells sealed by tight junctions (TJ) and adherens junction (AJ). TJ and AJ are transmembrane and cytoplasmic protein complex connecting to actin, regulating the permeability of the paracellular junctions of endothelial cells, surrounding astrocyte end-feet and pericytes support the structure and regulate the microenvironment to maintain normal physiological function of BBB. [80] Paracellular and transcellular pathway are two common route for drug delivery. The paracellular pathway occurs through the passage between endothelial cells, which is dependent on the concentration gradient of the substance and regulated by the TJ. The compositional and conformational changes of TJ regulate the efficiency of paracellular passage. [81] The changes of TJ is modulated by various signaling pathway including G-proteins, serine-, threonine- and tyrosine-kinases, extra and intracellular calcium levels, cAMP levels, proteases and cytokines. [82] The transcellular pathway passes the molecules directly through the endothelial cells. The transcellular transport can be carried out by passive diffusion, carrier-mediated diffusion, and transcytosis.[83] The small lipid-soluble or gas molecules can passively diffuse through the cell membrane and cross the endothelium. Small hydrophilic molecules such as amino acid and glucose need to bind with carrier protein expressed by the endothelial cells. For larger hydrophilic molecules such as peptide, protein, and drugs, transcytosis is needed for the transportation. The transcytosis can be carried out by two different mechanism, specific receptor-mediated transcytosis (RMT) and less specific adsorptive-mediated transcytosis (AMT). In RMT, circulating molecules bind to specific receptor (eg. transferrin receptor, insulin receptor, low density lipoprotein receptor) on the apical cell membrane (vessel side) and endocytosis forms intracellular vesicles containing the molecules. Through the intracellular trafficking, the vesicles are guided to the basolateral cell membrane (brain side) and release the content into the target region. [84] AMT involves the interaction of cationic proteins with negatively charged domains on the apical cell membrane and subsequent transcytosis.

Two types of methods are used to enhance the BBB penetration of nanoparticles: physical disturbance of BBB and conjugation of ligands of receptors on BBB to nanoparticles. The physical method target to open TJs between endothelial cells or induced local inflammation to allow local permeabilization. Focused ultrasound (FUS) is most prevail among the physical methods to disrupt the TJs. Magnetic resonance image guided focused ultrasound (MR-FUS) provide precise, safe and non-invasive opening of BBB. The sound wave activates ultrasound contrast agent microbubbles (MBs) in stable cavitation and the mechanical force exerting on the BBB opens the TJs allows the targeted delivery of nanoparticle with size up to 100 nm [85] The interrupted barrier function will be restored within 4~6 hr and the safety of FUS also have been confirmed in several large animal models [86] Mead and colleagues combined MR-FUS and brain-penetrating nanoparticle (BPN) to deliver glial cell-line derived neurotrophic factor (GDNF) gene to the striatum of the 6-OHDA-induced rat model of PD. The GDNF protein expression was elicited in striatum and the effective concentration maintained up to 12 weeks. Also, the GDNF expression of the off-target major organs such as liver, spleen, heart, kidney, and lung were not elevated significantly. [87] However, the high-frequency ultrasound has drawbacks such as thermal damage during the sonication and limited transducing depth from extracorporeal devices. Recently, low-frequency shockwave are applied for better penetration across cranial bone and reducing the thermal damage. Kung and his coworkers showed focused shockwave can effectively open the BBB and enhance transfection of plasmid DNA in small mouse model. The low-frequency shockwave provides shorter treatment time, deeper penetration, and greater ease of crossing the skull. [88]
The chemical method heavily relies on the RMT to cross BBB. During the past decades, several ligands have been discovered to enhance RMT. The most commonly used receptors such as lactoferrin receptor (LR) [89][90], transferrin receptor (TR) [91], insulin receptor (IR), low-density lipoprotein receptor (LDLR). The corresponding ligands can be proteins, peptide, or monoclonal antibody. The application and designing of these ligand in enhancing the RMT have been discussed in several reviews. [92][8] For those traditional ligands/receptors, one significant drawback hinders the application in crossing BBB is their ubiquitous expression in human body, which raises the concern about the off-target effects.

### Enhancing the deliver specificity to the brain

After crossing BBB, the specific targeting to the diseased regions required to avoid the off-target effect. Without further modification, the genetic material will spread out and accumulate in the whole brain due to the non-specificity. Thus, modification of nanoparticle with certain peptide or other motifs that can localize specific region is a possible method to circumvent this issue. Cell penetrating peptide (CPP) and Rabies Virus Glycoprotein 29 (RVG29) peptide are widely used in siRNA delivery. [68] Recently, You and colleagues also adopted RVG29 as their strategy of specific targeting. They synthezed a RVG29-conjugated monomethoxy- poly(ethylene glycol) (mPEG)-poly(lactic-co-glycolic acid) (PLGA) nanoparticle to target the Parkinsonian mice brian. By the intravenous injection, the result showed the notably strong accumulation of the conjugated nanoparticles than the free form drug in diseased regions (striatum and substantia nigra). [93] Also, Zhang and colleague conjugated two peptides TGN and QSH on the PEG-PLA nanoparticles to achieve enhanced and precise targeted delivery to amyloid plaque in the brains of AD model mice. [94]

### Optimizing intracellular delivery and transfection

Efficient entering the cell membrane and successful genetic material unanoparticleacking is two important factors that affect the rate of successful transfection. Four barriers are needed to be tackled including cellular internalization, endosomal escape, cytosolic transportation, and nuclear import.

Engineering the physical and chemical properties can enhance the cellular internalization rate. The nanoparticles can be internalized through phagocytosis, clathrin-mediated endocytosis, caveolae-mediated endocytosis, and macropinocytosis. Physical properties include size, shape, and surface charge (zeta potential). Due to the nature of lipid bilayer cell membrane, the small nanoparticles have higher probability crossing by passive uptake.The optimal size of nanoparticle for maximum efficiency of endocytosis is around 30-50 nm. [95] The shape of nanoparticles also plays an important role. For example, the Au nanorod has higher efficiency of cellular internalization than Au nanosphere. [96] The theoretical basis of this effect can be shown by molecular dynamic simulation in the investigation of difference in cellular uptake between prickly and round nanodiamond nanoparticles, the result suggests that the different uptake rate is associated with energy barrier during membrane curvature generation when engulfing by the cell membrane. [97] Electrostatic interaction with the cell membrane is characterized by the zeta potential of nanoparticles, which is also very critical in affecting the cellular internalization. The positively charged nanoparticles have larger numbers of adhered and internalized particles than negatively charged nanoparticles after the 2-h incubation by 2.5 to 3.5 and 10 to 40 times respectively. Also, the longer the incubation, the correlation between internalization amount and zeta potential becomes stronger. [98] Chemical conjugation with ligands interacting with cell membrane (such as transferrin, RGD peptide, lactose, mannose, anti-CD3 antibody, OV-TL16, PSMA-specific monoclonal antibody J591, HER-2 antibody, GRP-78-targeting peptide, folic acid) is also a feasible way to facilitate the cellular internalization. [57]

Escaping from the endosome without significant degradation is another important factor in designing the nanoparticle-based gene delivery. After the internalization of the nanocarrier, the pH value of the endosome will gradually decrease from pH 7.0 to pH 5.0 and finally fuse with lysosome. Lysosome contains lower pH value and enzymes that will rapidly degrade DNA/RNA on the nanocarrier. Thus, effective escape from endosome before the the fusion with lysosome and the degradation of DNA/RNA is critical concern in designing nanoparticle-based carrier. The complete mechanism of endosomal escape of nanoparticle is not fully understood. Four possible pathways are proposed including proton-sponge effect, membrane fusion, peptide-pore formation, and polymer-induced disruption. The detailed mechanisms and designing strategies of nanoparticles to tackle have been discussed in other comprehensive reviews. [99] [100] [101]

Two more barriers are needed to be overcame in the delivery of DNA. To achieve successful transfection, the escaped nanocarrier need to cross the cytosol and enter the nucleus. The mechanism of the cytosolic transportation have not been elucidated yet. Past studies associated the movement of nanoparticle-based nanocarrier is associated with the microtubule of the cytoskeleton.[100] Liu and colleagues applied DNA-decorated gold (fPlas-gold) nanoparticles as dually emissive fluorescent and plasmonic probe to study the intracellular movement of the nanocarriers. Under the fluorescent microscopy, two types of fPlas-gold nanoparticles, fast with directed and slow with undirected motility, are observed. The fast-directed motility type nanoparticles are associated with microtubule transport. More evidence found by using pharmacological inhibitors support the observation. They treat the cell with cytochalasin B that can depolymerizes actin and it did not affect the intracellular mobility of the fPlas-gold nanoparticles; whereas treatment with nocodazole that depolymerizes microtubules greatly reduced the mobility. [102] Crossing nucleus membrane and entering the nucleus are the last barriers for DNA delivery. The nucleus membrane is a bilayer lipid membrane with channels formed by nucleus pore complex (NPC); it mediates the transport of molecules between nucleus and cytosol. Though the detailed mechanism of nuclear transport has not been understood, the consensus associated it with the NPC. Different designs of nanoparticle-based delivery have been developed during the past decade. [103].[104] Conjugation nanoparticles with nuclear localization signal (NLS) is one of the most widely used design. NLS is a small amino acid sequence that tags the protein and interacts with the protein called importin on NPC to import the protein. Mout and colleague engineered a Cas9 protein with the cationic arginine gold nanoparticles (ArgNP) and also inserted a NLS on the nanoparticles. The result achieve ~90% cytoplasmic/nuclear delivery efficiency and ~30% genome editing efficiency. [105] The detailed mechanism of nuclear import and other modification to enhance the nuclear import efficiency are described extensively by other authors.[100] [103] [106] [104]

## Application of nanoparticle in gene therapy of neurodegenerative disease

### Alzheimer’s disease

Alzheimer’s disease(AD) is the most prevalent type of dementia. The early clinical manifestation is selective memory impairment, which is followed by impaired executive function, behavioral disturbance, and motor symptoms including apraxia.

The pathogenic mechanism of AD has not been fully understood yet, current studies had shown that the amyloid-β (Aβ), a major hallmark of AD, has played a major role in the disease mechanism.[107][108]
Aβ is generated by the cleavage of amyloid precursor protein (APP) by a complex family of enzymes (γ-­secretases and β-­secretases), which include presenilin 1 and presenilin 2 encoded by PSEN1 and PSEN2 respectively. [109][110]
Among all the AD patients, most have the sporadic form with a late onset at 80-90 ,which is related to the failed clearance of the Aβ and a large number of genetic risk factors for sporadic disease have been identified. On the other hand, a minor proportion (<1%) of patients have the early-onset familial Alzheimer’s disease with mean onset age of 45. In this subgroup, pathogenetic mutations were found in the genes that are related to the production of amyloid-β including PS1, PS2 and APP and these mutations result in overproduction and formation of Aβ and amyloid plaques. [108][111][112] Different forms of gene therapy methods including viral and non-viral vectors have been applied for treating Alzheimer’s disease. Nanoparticles are also used as vector for gene delivery.

For example, Rassu at el. designed a delivery system to delivery BACE1 siRNA via nose-to-brain transportation, where the BACE1 siRNA forms a complex with a rabies virus-derived glycoprotein RVG-9R to increase the transcellular pathway in neurons. The siRNA complexes are delivered by solid lipid nanoparticles via nasal delivery and both the olfactory and trigeminal nerve pathway. [113] Mouse model was applied to evaluate the therapeutic effect of nanoparticle based gene therapy. Liu at el. developed a multifunctional nanocarrier to achieve co-delivery of gene and peptide. The nanoparticle carrier was based on PEGylated dendrigraft poly-l-lysines, where the dendritic amine-rich positive charged structure of the nanoparticle serve as reaction sites for plasmed and drug loading. Non-coding RNA plasmid was delivered by the nanoparticles via systemic administration to the transgenic AD mice. After the administration, down-regulation of the key enzyme in amyloid-β formation was observed. Additionally, reduction of neurofibrillary tangles is also observed after co-delivery of the therapeutic peptide into brain. The behavioral experiments are also performed and memory loss rescue in AD mice was also observed. [114]

In another study conducted by Doolaanea at el. ,nanoparticle based co-delivery of plasmid DNA(pDNA) and a potential therapeutic agent nigella sativa oil(NSO) was proposed as a treatment of AD. Poly lactic-co-glycolic acid (PLGA) nanoparticles was used to encapsulate nigella sativa oil and pDNA was loaded by absorption. The nanoparticle system exhibits a burst-release property. Murine neuroblastoma (N2a) cell line was used to assess the efficacy of the NSO-pDNA-PLGA nanoparticles. Green fluorescence protein(GFP) expressing pDNA and NSO containing PLGA nanoparticles were used to transfect the N2A cells, neurite outgrowth was measured and suggested the potential therapeutic effect of NSO and GFP fluorescence was measured to access the transfection efficiency, where the result showed successful delivery of the plasmid DNA. [115]

Nanoparticle gene delivery based cell therapy was also proposed. Zhang at el. utilized complex synthesized PCB-based poly(2-hydroxyethyl methacrylate)-RA-poly(carboxybetaine) cell penetrating peptide (PHEMA-RA-PCB-CPP) polymers to construct traceable, simple-component nanoparticles. The nanoparticles were used to deliver retinal acid in combination with SOX9 siRNA to ex vivo cultured neural stem cells(NSCs) and the NSCs are transplanted in to AD mouse to examine the potential therapeutic effect. Their result showed that there were successful inhibition of SOX9 expression as well as the therapeutic outcome of decreased neuronal loss and improved performance in Morris water maze (MWM) experiment. In addition, the traceable nanoparticles can also be used to monitor the transplantation site, as well as the migration of NSCs. [116]

### Parkinson’s disease

Parkinson’s disease (PD) is the second prevalent neurodegenerative disease. The clinical features include rigidity, resting tremor, and motor function impairment, including freezing and bradykinesia. The pathophysiology of the PD is characterized by the loss of the dopaminergic neurons in the substantia nigra of the striatum and formation of the Lewy body inclusion in the remaining neurons. The primary component of the Lewy body inclusion is the protein α-synuclein. The level of the α-synuclein deposition in the neurons depends on the genetic variations of individual patients. Several genes have been identified to be related to the synucleinopathy. For example, the SNCA, Parkin gene have been found to have positive associations with the increased expression of α-synuclein and the risk of PD. [117]

One common strategy of treating PD is transfection of the genes of the neuroprotective factors that can protect neuronal death in PD. For example, glial cell line derived neurotrophic factors (GDNF) is a common target of treating PD. [118] Yurek at. el., utilized compacted DNA nanoparticles consisting of single copy of plasmid DNA encoding GDNF and polyethylene glycol conjugated 30-mer lysine polymers. The nanoparticles were administered by direct stereotactic microinjection to the striatum of the mouse model of Parkinson’s disease and the result showed increased number of surviving dopaminergic cells, increased density of DA fiber terminals, as well as motor function recovery. [119][120] Mead and colleagues combined MRI-guided focused ultrasound (MR-FUS) and brain-penetrating nanoparticle (BPN) to deliver GDNF gene. The FUS caused transient opening of the BBB allows the passage of nanoparticle and induce widespread and uniform expression of GDNF in the stritium of the 6-OHDA-induced rat model of PD. The number of the dopaminergic neurons were restored and the locomotor function was significant improved in the rate model. [87]

Another poly-L-lysine based nanoparticle was also utilized. Huang and coworkers used cationic, monodispersed poly-L-lysine-based dendrimer conjugated with a peptide angiopep via hydrophilic polyethylene glycol to deliver plasmid DNA of human GDNF. Angiopep was applied as a ligand specifically binding to low-density lipoprotein receptor-related protein (LRP) which is overexpressed on blood-brain barrier to enhance BBB penetration. The effect of the nanoparticle were tested by multiple intravenous administrations into rotenone treated rat model of PD and the result showed improved locomotor activity and apparent recovery of dopaminergic neurons.
Reducing α-synuclein expression in neurons is another approach to treat PD. Niu at. el. used magnetic Fe3O4 nanoparticles coated with oleic acid molecules as a nanocarrier. N-isopropylacrylamide derivative (NIPAm-AA) was photo-immobilized onto the oleic acid molecules, and shRNA (short hairpin RNA) was absorbed. Nerve growth factor (NGF) was also absorbed to NIPAm-AA to specifically promote uptake via NGF receptor-mediated endocytosis of the target cell.The results showed decreased α-synuclein level as well as improve PD motor dysfunction in PD mouse model. [121] Another RNAi example given by Helmschrodt and coworkers is that they combined α-synuclein targeting siRNA with polyethylenimine (PEI) that has high transfection rate of siRNA in vivo. The PEI conjugated siRNA was injected into the lateral ventricle of mice overexpressing α-synuclein (Thy1-aSyn mice). Five days after injection, α-synuclein mRNA expression in the striatum was reduced by 65%, accompanied by reduction of α-synuclein by 50%. Furthermore, the toxicity on the cells, side effects and immunogenicity in the mouse brain were minimal. [122]

### Huntington’s disease

Huntington’s disease (HD) is a genetic related progressive neurodegenerative disease characterized by the involuntary choreatic movements, psychiatric and behavioral disturbance and dementia. HD affects approximately 5-10 in 100000 people in Europe, Australasian and American populations. The complete pathophysiology of the HD is not fully understood. Current studies suggest the neural toxicity comes from the mutant huntingtin protein, which is related to an autosomal dominant inherited gene mutation. The mutations in the HTT gene encoding huntingtin, which is located on chromosome 4p16.3 containing uninterrupted CAG trinucleotide repeats in the first exon of HTT. Normal alleles contain up to 35 CAG repeats, whereas HD patients carry expansions of 36 or more repeat. The mutation is transmitted in an autosomal dominant fashion. The mutant huntingtin is excitotoxic and will lead to progressive loss of neurons and compromise of neural function primary in the striatum. The medium spiny neuron (MSN) is a group of neuron that are vulnerable to the mutant huntingtin protein. MSNs involve multiple pathways in the brain that controls the movement, perform decision making, and making goal planning behaviors. [123] The loss of MSNs will result in the neurological dysfunction in HD patients. There is also a strong inverse correlation between the length of the repeats and the age of onset of symptoms.

Reducing the synthesis of mutant huntingtin protein becomes one of the popular therapeutic paradigm recently. The post-transcriptional gene silencing by antisense oligonucleotide (ASO) and RNAi mechanisms such as siRNA, shRNA is widely studied.[124] [125] Several clinical trial using ASO to treat HD have been initiated since 2017. [126] Recent development of CRISPR-Cas9 genome editing technique also showed promising results that can ameliorates the neurotoxicity in mouse model. [127]

With the advance of the nanotechnology, the effective delivery and minimal off-target effect can be achieved. Alterman and co-workers showed modification of siRNA with hydrophobic teg-Chol (tetraethylene glycol cholesterol) (hsiRNA) can enhance membrane binding and cellular internalization in primary neurons. The hsiRNA induced concentration-dependent silencing and reduced both mutant huntingtin mRNA levels and mutant huntingtin protein levels by as much as 70 and 85%, respectively. Direct injection of hsiRNA into the striatum of mouse model also effectively silences the mutant huntingtin protein with minimal cytotoxicity and immune response. [128] Exosome is a small endogenous intracellular for transferring lipids, proteins, and nucleotides. Didiot and colleagues loaded exosome with hydrophobically-modified siRNA for mutant huntingtin mRNA by co-incubation. The hsiRNA loaded exosome were efficiently internalized by mouse primary cortical neurons and promoted dose dependent silencing of Huntingtin mRNA and protein. Unilateral injection for hsiRNA loaded exosome can induce bilateral distribution of hsiRNA in both striatal and cortical regions with significant silencing mutant huntingtin mRNA, whereas there is only local accumulation in the injection site without exosome. [129] Another oligosacharide-based polymer, modified amphiphilic β-cyclodextrins (CDs), were used to delivery. Godinho and coworkers encapsulated mutant huntingtin targeting siRNA in CDs for both in vitro and in vivo test. The CD-siRNA nanoparticles reduced the expression of mutant huntingtin gene in both rat striatal cell lines and human HD primary fibroblasts. Sustained knockdown effect were shown in R6/2 mouse model of HD after single injection and alleviation of motor symptoms were observed after repetitive injections. [130]

### Stroke

Stroke, also known as cerebral vascular accidents, refers to the condition of insufficient blood supply to the brain, resulting in oxygen deprivation and subsequent neuronal damage as well as functional deficits. In recent years, stroke is among the top ten cause of death in epidemiological statistics. The etiology of stroke can be generally classified into two categories: ischemic stroke, a condition resulting from cerebrovascular obstruction and hemorrhagic stroke, where ruptured vessel lead to blood infiltrating into brain tissue. It is reported that approximately 795,000 people in the United States each year suffered from stroke, 610 000 of these are first attacks, and 185 000 are recurrent attacks. Among all cases of cerebral vascular accidents, 87% are ischemic and 13% are hemorrhagic strokes. And in 2015, about 6.3 million people died of a stroke.[131] The underlying pathogenic mechanism of ischemic brain injury after cerebral malperfusion is that the temporary lack of oxygen and nutrients in the brain causes excitotoxicity and damage to the blood-brain barrier (BBB) during reperfusion causes neuroinflammation. In addition, the activation of microglial cells in the brain and leukocyte infiltration, can result in rapid necrosis of brain tissue in the hypoxic core region and subsequent apoptosis of the penumbra neurons [132].

Antiplatelet and anticoagulant such as Aspirin, Clopidogrel, Dipyridamole, Dabigatran, Pentoxifylline and Piracetam are often used to prevent recurrent stroke and the current initial therapy following a stroke is fibrinolysis and endovascular intervention[133]. In contrast to conventional therapy which mainly salvage the damage brain, gene therapy provides a new potential towards functional recovery and tissue regeneration.

For example, Wang et al. combined gene therapy and cell therapy using polyethyleneimine coated superparamagnetic iron oxide nanoparticles to deliver siRNA to transplanted endothelial progenitor cells. In addition the superparamagnetic nanoparticles also server as the tool for cell tracking. The result showed that hif-prolyl hydroxylase 2 (PHD2) silencing could enhance the migration and survival ability of EPCs and the animal experiments also showed that mice treated with siPHD2-EPCs had reduced vascular infarct volume, increased angiogenesis, and recovery of brain function after ischemic stroke. [134]

Mahajan and coworkers targeted the protein matrix metalloproteinase-9 (MMP-9)that increases the BBB permeability during stroke thus playing an important role in the pathogenesis of brain damage. In the study, gold nano-rods (GNRs) were used and MMP-9 siRNA was electrostatically bound to the nanoparticle to form a nanoplex. Their result showed successful suppression of MMP-9 expression as well as increased expression of tight junction molecules in brain microvascular endothelial cells.[135]

Caspase-3 is another potential target in preventing brain damage and functional deficit in stroke, since it’s critical role in the pathway of programmed cell death. Al-Jamal at. el. used functionalized carbon nanotubes as delivery vector to deliver plasmid DNA encoding caspase-3 siRNA. The nanoparticles are administered by peri-lesional, stereotactic injection. They proved that the Internalization of the nanoparticle by neurons in vivo was successful. And the animal study using middle cerebral artery occlusion(MCAO) mouse showed that the nanoparticle-based gene therapy promoted functional preservation.[136]

The complement system also plays a central role in microglial neurotoxicity following cerebral ischemia/reperfusion injury. Wang et al. targeted component C3, by nanoparticles loaded with C3 siRNA to inhibit microglial neurotoxicity. Their result showed that nanoparticles successfully delivered C3-siRNA from the blood into ischemic penumbra across the BBB and the nanoparticle-based gene therapy resulted in decreased complement subunit C3b deposition on neurons as well as reduced microglia-mediated neuronal apoptosis.[137]

## Conclusion

The influence of neurodegenerative disease to the human grows as the average life expectancy increases. Since the human genome sequencing project initiated, our understanding of the pathophysiology of neurodegenerative disease advanced to the molecular level. Thus, gene therapy comes out as a new therapeutic paradigm of treating neurodegenerative diseases. However, several barriers of human bodies including circulation system, blood-brain barrier, cellular internalization, endosomal escape and nucleus import limit the efficacy of gene therapy. The immunogenicity, carcinogenicity and off-target effects of the viral vectors used in gene therapy are other challenges that hinders the use of gene therapy in neurodegenerative disease. As the advance of nanotechnology, the potential of nanoparticle-based vector has been shown in many in vitro and preclinical studies. The wide flexibility of surface functionality of the nanoparticle-based vectors provides superior properties to traditional viral vectors. Prolonged circulation time, enhanced transfection rate, reduced immunogenicity, and reduced carcinogenicity in animal models were shown in recent papers.

## Challenges to overcome and future perspectives

However, translation of nanoparticle-based gene therapy from in vitro and animal models to clinical use is still very challenging. Toxicity and immunogenicity are the major concern. Despite the studies have shown positive results in animal models, it is uncertain whether these results can be applied to humans due to the difference in physiological function between human and animal. Though high transfection rate and significant repression of mutant genes are shown in vitro and in animal models, these properties may not be replicate in human because there are more barrier in gene delivery to human.

To achieve optimal effect of nanoparticle-based therapy in human, the molecular event in gene delivery should be further elucidated. The BBB penetrating, endosomal escape, intracellular trafficking, and nucleus import are the key steps to maximum the transfection. In order to better study the therapeutic effects of nanoparticle-based gene therapy, advanced animal models and tissue-engineered models are necessary. Moreover, computer simulations of biodistribution, kinetic and design of nanoparticles will assist to optimize the delivery efficiency.

Though the nanoparticle-based vectors can overcome many biological barriers of gene delivery, the other major barrier preventing the successful treatment of neurodegenerative diseases is the basic understanding of the molecular mechanism of the genes in the initiation and progression of the diseases. Identification and validation of new potential therapeutic genes can lead to more efficacious results. Also, better understanding of the etiology of neurodegenerative disease can lead to early diagnosis, which nanoparticle-based gene therapy can be utilized before the symptoms and total lost of the target cells.

Thus, future development of nanoparticle-based gene therapy of neurodegenerative diseases should not only focus on designing nanoparticle platform to overcoming biological barriers but also gain more understanding of the disease pathogenesis. Combining the advance in wet and dry lab design of nanoparticle-based gene therapy will be a important strategy to translate nanoparticle-based gene therapy of neurodegenerative disease into clinical use.


Cite as:
```
@article{chen2020nanoparticles,
  title   = "Nanoparticle Based Gene Therapy For Neurodegenerative Diseases",
  author  = "Chen, Yi-Hsuan, Wong, Chia-En",
  journal = "https://andyyhchen.github.io/",
  year    = "2020",
  url     = "https://andyyhchen.github.io/2020/08/11/nano-based-gene-therapy-for-nd.html"
}
```




## References

[1] M. G. Erkkinen, M.-O. Kim, and M. D. Geschwind, “Clinical Neurology and Epidemiology of the Major Neurodegenerative Diseases.,” Cold Spring Harb. Perspect. Biol., vol. 10, no. 4, Apr. 2018.

[2] D. M. Skovronsky, V. M.-Y. Lee, and J. Q. Trojanowski, “Neurodegenerative diseases: new concepts of pathogenesis and their therapeutic implications.,” Annu. Rev. Pathol., vol. 1, pp. 151–170, 2006.

[3] D. M. O’Connor and N. M. Boulis, “Gene therapy for neurodegenerative diseases.,” Trends Mol. Med., vol. 21, no. 8, pp. 504–512, Aug. 2015.

[4] L. Naldini, “Gene therapy returns to centre stage.,” Nature, vol. 526, no. 7573, pp. 351–360, Oct. 2015.

[5] T.-L. Tsai et al., “The down regulation of target genes by photo activated DNA nanoscissors.,” Biomaterials, vol. 31, no. 25, pp. 6545–6554, Sep. 2010.

[6] W. A. Banks, “From blood-brain barrier to blood-brain interface: new opportunities for CNS drug delivery.,” Nat. Rev. Drug Discov., vol. 15, no. 4, pp. 275–292, Apr. 2016.

[7] J. H. Kang, J. Cho, and Y. T. Ko, “Investigation on the effect of nanoparticle size on the blood-brain tumour barrier permeability by in situ perfusion via internal carotid artery in mice.,” J. drug Target., vol. 27, no. 1, pp. 103–110, Jan. 2019.

[8] C. Saraiva, C. Praça, R. Ferreira, T. Santos, L. Ferreira, and L. Bernardino, “Nanoparticle-mediated brain drug delivery: Overcoming blood-brain barrier to treat neurodegenerative diseases.,” J. Control. Release : Off. J. Control. Release Soc., vol. 235, pp. 34–47, Aug. 2016.

[9] V. P. Torchilin, “Multifunctional, stimuli-sensitive nanoparticulate systems for drug delivery,” Nat. Rev. Drug Discov., vol. 13, no. 11, pp. 813–827, 2014.

[10] T. Wyss-Coray, “Ageing, neurodegeneration and brain rejuvenation.,” Nature, vol. 539, no. 7628, pp. 180–186, Nov. 2016.

[11] B. J. Kelley, B. F. Boeve, and K. A. Josephs, “Young-onset dementia: demographic and etiologic characteristics of 235 patients.,” Arch. Neurol., vol. 65, no. 11, pp. 1502–1508, Nov. 2008.

[12] A. Imamura, Z. Wszolek, and R. Uitti, “Neurodegenerative overlap syndrome: Parkinsonism and motor neuron disorder.,” Mov. Disord. : Off. J. Mov. Disord. Soc., vol. 22, no. 1, pp. 151–152, Jan. 2007.

[13] A. Zabłocka, “[Alzheimer’s disease as neurodegenerative disorder].,” Postepy Hig. Med. doswiadczalnej, vol. 60, pp. 209–216, 2006.

[14] R. M. Ransohoff, “How neuroinflammation contributes to neurodegeneration.,” Sci., vol. 353, no. 6301, pp. 777–783, Aug. 2016.

[15] I. Ceballos-Picot, “Oxidative Stress in Neuronal Death and Apoptosis,” in The Role of Oxidative Stress in Neuronal Death, Springer Berlin Heidelberg, 1997, pp. 39–82.

[16] L.-W. Chen, “Astrocyte, reactive astrocytes and self-regulative apoptosis in the neuroinflammation,” Neuroimmunol. Neuroinflammation, vol. 3, no. 7, Jul. 2016.

[17] M. Sastre et al., “Neuroinflammation in Alzheimer’s, Parkinson’s and Huntington’s Diseases,” in Neuroinflammation and CNS Disorders: Woodroofe/Neuroinflammation, John Wiley & Sons, Ltd, 2014, pp. 111–150.

[18] N. Woodroofe and S. Amor, Eds., Neuroinflammation and CNS Disorders: Woodroofe/Neuroinflammation. John Wiley & Sons, Ltd, 2014.

[19] D. A. Wajda, A. Mirelman, J. M. Hausdorff, and J. J. Sosnoff, “Intervention modalities for targeting cognitive-motor interference in individuals with neurodegenerative disease: a systematic review.,” Expert Rev. Neurother., vol. 17, no. 3, pp. 251–261, Mar. 2017.

[20] S. Salloway, “Current and Future Treatments for Alzheimer’s Disease,” CNS Spectrums, vol. 14, no. S7, Aug. 2009.

[21] J. Jankovic and L. G. Aguilar, “Current approaches to the treatment of Parkinson’s disease.,” Neuropsychiatr. Dis. Treat., vol. 4, no. 4, pp. 743–757, Aug. 2008.

[22] T. Ruck, S. Bittner, H. Wiendl, and S. G. Meuth, “Alemtuzumab in Multiple Sclerosis: Mechanism of Action and Beyond.,” Int. J. Mol. Sci., vol. 16, no. 7, pp. 16414–16439, Jul. 2015.

[23] J. W. Rose, H. E. Watt, A. T. White, and N. G. Carlson, “Treatment of multiple sclerosis with an anti-interleukin-2 receptor monoclonal antibody.,” Ann. Neurol., vol. 56, no. 6, pp. 864–867, Dec. 2004.

[24] C. A. Chiriboga, “Nusinersen for the treatment of spinal muscular atrophy.,” Expert Rev. Neurother., vol. 17, no. 10, pp. 955–962, Oct. 2017.

[25] “Nusinersen (Spinraza) for spinal muscular atrophy.,” Med. Lett. drugs Ther., vol. 59, no. 1517, pp. 50–52, Mar. 2017.

[26] D. L. Sokol and A. M. Gewirtz, “Gene therapy: basic concepts and recent advances.,” Crit. Rev. Eukaryot. gene Expr., vol. 6, no. 1, pp. 29–57, 1996.

[27] P. Tolstoshey, “Gene Therapy, Concepts, Current Trials and Future Directions,” Annu. Rev. Pharmacol. Toxicol., vol. 33, no. 1, Apr. 1993.

[28] K. Roemer and T. Friedmann, “Concepts and strategies for human gene therapy.,” Eur. J. Biochem., vol. 208, no. 2, pp. 211–225, Sep. 1992.

[29] M. Shimamura and R. Morishita, “Naked plasmid DNA for gene therapy.,” Curr. gene Ther., vol. 11, no. 6, p. 433, Dec. 2011.

[30] S. R. Bathula and L. Huang, “Gene Therapy with Plasmid DNA,” in Burger’s Medicinal Chemistry and Drug Discovery, John Wiley & Sons, Inc., 2010.

[31] R. Banerjee and L. Huang, “Plasmid DNA-Mediated Gene Therapy,” in Burger’s Medicinal Chemistry and Drug Discovery, John Wiley & Sons, Inc., 2003.

[32] F. Sousa, L. Passarinha, and J. A. Queiroz, “Biomedical application of plasmid DNA in gene therapy: a new challenge for chromatography.,” Biotechnol. & Genet. Eng. Rev., vol. 26, pp. 83–116, 2010.

[33] T. Murakami and Y. Sunada, “Plasmid DNA Gene Therapy by Electroporation: Principles and Recent Advances,” Curr. Gene Ther., vol. 11, no. 6, Dec. 2011.

[34] D. Kim and J. Rossi, “RNAi mechanisms and applications.,” BioTechniques, vol. 44, no. 5, pp. 613–616, Apr. 2008.

[35] J. Chery, “RNA therapeutics: RNAi and antisense mechanisms and clinical applications.,” Postdoc J. : J. Postdr. Res. Postdr. Aff., vol. 4, no. 7, pp. 35–50, Jul. 2016.

[36] D. Grimm and M. A. Kay, “RNAi and gene therapy: a mutual attraction.,” Hematol. Am. Soc. Hematol. Educ. Program, pp. 473–481, 2007.

[37] J. Y. Yoo et al., “VEGF-specific Short Hairpin RNA–expressing Oncolytic Adenovirus Elicits Potent Inhibition of Angiogenesis and Tumor Growth,” Mol. Ther., vol. 15, no. 2, Feb. 2007.

[38] B. R. Cullen, “Viruses and RNA interference: issues and controversies.,” J. Virol., vol. 88, no. 22, pp. 12934–12936, Nov. 2014.

[39] V. Bitko, A. Musiyenko, O. Shulyayeva, and S. Barik, “Inhibition of respiratory viruses by nasally administered siRNA.,” Nat. Med., vol. 11, no. 1, pp. 50–55, Jan. 2005.

[40] J. Zhou, K.-T. Shum, J. C. Burnett, and J. J. Rossi, “Nanoparticle-Based Delivery of RNAi Therapeutics: Progress and Challenges.,” Pharm., vol. 6, no. 1, pp. 85–107, 2013.

[41] T. S. Zatsepin, Y. V. Kotelevtsev, and V. Koteliansky, “Lipid nanoparticles for targeted siRNA delivery - going from bench to bedside.,” Int. J. nanomedicine, vol. 11, pp. 3077–3086, Jul. 2016.

[42] H. Wang, M. La Russa, and L. S. Qi, “CRISPR/Cas9 in Genome Editing and Beyond.,” Annu. Rev. Biochem., vol. 85, pp. 227–264, Jun. 2016.

[43] P. D. Hsu, E. S. Lander, and F. Zhang, “Development and Applications of CRISPR-Cas9 for Genome Engineering,” Cell, vol. 157, pp. 1262–1278, Jun. 2014.

[44] J. D. Sander and J. K. Joung, “CRISPR-Cas systems for editing, regulating and targeting genomes.,” Nat. Biotechnol., vol. 32, no. 4, pp. 347–355, Apr. 2014.

[45] W.-J. Dai, L.-Y. Zhu, Z.-Y. Yan, Y. Xu, Q.-L. Wang, and X.-J. Lu, “CRISPR-Cas9 for in vivo Gene Therapy: Promise and Hurdles.,” Mol. Ther. Nucleic acids, vol. 5, p. e349, 2016.

[46] N. Savić and G. Schwank, “Advances in therapeutic CRISPR/Cas9 genome editing.,” Transl. Res. : J. Lab. Clin. Med., vol. 168, pp. 15–21, Feb. 2016.

[47] P. Mali et al., “RNA-guided human genome engineering via Cas9,” Science, vol. 339, pp. 823–826, 2013.

[48] H. J. Kim, A. Kim, K. Miyata, and K. Kataoka, “Recent progress in development of siRNA delivery vehicles for cancer therapy.,” Adv. drug Deliv. Rev., vol. 104, pp. 61–77, Sep. 2016.

[49] S. Han, R. I. Mahato, Y. K. Sung, and S. W. Kim, “Development of biomaterials for gene therapy.,” Mol. Ther. : J. Am. Soc. Gene Ther., vol. 2, no. 4, pp. 302–317, Oct. 2000.

[50] “Gene Transfer with Naked DNA,” Mol. Ther., vol. 1, no. 5, May 2000.

[51] K. Miyake, T. Shibata, U. Ohto, and T. Shimizu, “Emerging roles of the processing of nucleic acids and Toll-like receptors in innate immune responses to nucleic acids.,” J. Leukoc. Biol., vol. 101, no. 1, pp. 135–142, Jan. 2017.

[52] D. M. Dykxhoorn, D. Palliser, and J. Lieberman, “The silent treatment: siRNAs as small molecule drugs.,” Gene Ther., vol. 13, no. 6, pp. 541–552, Mar. 2006.

[53] T. Siegal, “Which drug or drug delivery system can change clinical practice for brain tumor therapy?,” Neuro-oncology, vol. 15, no. 6, pp. 656–669, Jun. 2013.

[54] J. Cummings, “Lessons Learned from Alzheimer Disease: Clinical Trials with Negative Outcomes.,” Clin. Transl. Sci., vol. 11, no. 2, pp. 147–152, Mar. 2018.

[55] A. S. Kesselheim, T. J. Hwang, and J. M. Franklin, “Two decades of new drug development for central nervous system disorders.,” Nat. Rev. Drug Discov., vol. 14, no. 12, pp. 815–816, Dec. 2015.

[56] E. Check, “Regulators split on gene therapy as patient shows signs of cancer.,” Nature, vol. 419, no. 6907, pp. 545–546, Oct. 2002.

[57] W.-F. Lai and W.-T. Wong, “Design of Polymeric Gene Carriers for Effective Intracellular Delivery.,” Trends Biotechnol., vol. 36, no. 7, pp. 713–728, Jul. 2018.

[58] R. Kanasty, J. R. Dorkin, A. Vegas, and D. Anderson, “Delivery materials for siRNA therapeutics.,” Nat. Mater., vol. 12, no. 11, pp. 967–977, Nov. 2013.

[59] H. Wang, Y. Jiang, H. Peng, Y. Chen, P. Zhu, and Y. Huang, “Recent progress in microRNA delivery for cancer therapy by non-viral synthetic vectors.,” Adv. drug Deliv. Rev., vol. 81, pp. 142–160, Jan. 2015.

[60] T. Seternes, T. C. Tonheim, M. Løvoll, J. Bøgwald, and R. A. Dalmo, “Specific endocytosis and degradation of naked DNA in the endocardial cells of cod (Gadus morhua L.).,” J. Exp. Biol., vol. 210, no. Pt 12, pp. 2091–2103, Jun. 2007.

[61] E. E. Vaughan and D. A. Dean, “Intracellular Trafficking of Plasmids during Transfection Is Mediated by Microtubules,” Mol. Ther., vol. 13, no. 2, Feb. 2006.

[62] E. Dauty, “Actin Cytoskeleton as the Principal Determinant of Size-dependent DNA Mobility in Cytoplasm: A NEW BARRIER FOR NON-VIRAL GENE DELIVERY,” J. Biol. Chem., vol. 280, no. 9, Dec. 2004.

[63] M. A. E. M. van der Aa, E. Mastrobattista, R. S. Oosting, W. E. Hennink, G. A. Koning, and D. J. A. Crommelin, “The nuclear pore complex: the gateway to successful nonviral gene delivery.,” Pharm. Res., vol. 23, no. 3, pp. 447–459, Mar. 2006.

[64] D. W. Pack, A. S. Hoffman, S. Pun, and P. S. Stayton, “Design and development of polymers for gene delivery,” Nat Rev Drug Discov, vol. 4, no. 7, pp. 581–93, 2005.

[65] M. Wang, H. Liu, L. Li, and Y. Cheng, “A fluorinated dendrimer achieves excellent gene transfection efficacy at extremely low nitrogen to phosphorus ratios.,” Nat. Commun., vol. 5, p. 3053, 2014.

[66] E.-Y. Kim, R. Schulz, P. Swantek, K. Kunstman, M. H. Malim, and S. M. Wolinsky, “Gold nanoparticle-mediated gene delivery induces widespread changes in the expression of innate immunity genes.,” Gene Ther., vol. 19, no. 3, pp. 347–353, Mar. 2012.

[67] Y. Zhou et al., “Mesoporous silica nanoparticles for drug and gene delivery.,” Acta Pharm. Sin. B, vol. 8, no. 2, pp. 165–177, Mar. 2018.

[68] M. Zheng, W. Tao, Y. Zou, O. C. Farokhzad, and B. Shi, “Nanotechnology-Based Strategies for siRNA Brain Delivery for Disease Therapy.,” Trends Biotechnol., vol. 36, no. 5, pp. 562–575, May 2018.

[69] C. Zylberberg, K. Gaskill, S. Pasley, and S. Matosevic, “Engineering liposomal nanoparticles for targeted gene therapy.,” Gene Ther., vol. 24, no. 8, pp. 441–452, Aug. 2017.

[70] R. L. Ball, K. A. Hajj, J. Vizelman, P. Bajaj, and K. A. Whitehead, “Lipid Nanoparticle Formulations for Enhanced Co-delivery of siRNA and mRNA.,” Nano Lett., vol. 18, no. 6, pp. 3814–3822, Jun. 2018.

[71] X. Luan, K. Sansanaphongpricha, I. Myers, H. Chen, H. Yuan, and D. Sun, “Engineering exosomes as refined biological nanoplatforms for drug delivery.,” Acta Pharmacol. Sin., vol. 38, no. 6, pp. 754–763, Jun. 2017.

[72] H. Lee et al., “Molecularly self-assembled nucleic acid nanoparticles for targeted in vivo siRNA delivery.,” Nat. Nanotechnol., vol. 7, no. 6, pp. 389–393, Jun. 2012.

[73] N. Ponnuswamy et al., “Oligolysine-based coating protects DNA nanostructures from low-salt denaturation and nuclease degradation.,” Nat. Commun., vol. 8, p. 15654, May 2017.

[74] Y. Zou et al., “Virus-Mimicking Chimaeric Polymersomes Boost Targeted Cancer siRNA Therapy In Vivo.,” Adv. Mater., vol. 29, no. 42, Nov. 2017.

[75] H. Yin, R. L. Kanasty, A. A. Eltoukhy, A. J. Vegas, J. R. Dorkin, and D. G. Anderson, “Non-viral vectors for gene-based therapy.,” Nat. Rev. Genet., vol. 15, no. 8, pp. 541–555, Aug. 2014.

[76] S. Schöttler et al., “Protein adsorption is required for stealth effect of poly(ethylene glycol)- and poly(phosphoester)-coated nanocarriers.,” Nat. Nanotechnol., vol. 11, no. 4, pp. 372–377, Apr. 2016.

[77] Z. Amoozgar and Y. Yeo, “Recent advances in stealth coating of nanoparticle drug delivery systems,” Wiley Interdiscip. Rev. Nanomedicine Nanobiotechnology, vol. 4, no. 2, pp. 219–233, 2012.

[78] A. Almalik et al., “Hyaluronic Acid Coated Chitosan Nanoparticles Reduced the Immunogenicity of the Formed Protein Corona.,” Sci. reports, vol. 7, no. 1, p. 10542, Sep. 2017.

[79] C.-M. J. Hu, L. Zhang, S. Aryal, C. Cheung, R. H. Fang, and L. Zhang, “Erythrocyte membrane-camouflaged polymeric nanoparticles as a biomimetic delivery platform.,” Proc. Natl. Acad. Sci. United States Am., vol. 108, no. 27, pp. 10980–10985, Jul. 2011.

[80] P. Ballabh, A. Braun, and M. Nedergaard, “The blood-brain barrier: an overview: structure, regulation, and clinical implications.,” Neurobiol. Dis., vol. 16, no. 1, pp. 1–13, Jun. 2004.

[81] N. J. Abbott, A. A. K. Patabendige, D. E. M. Dolman, S. R. Yusof, and D. J. Begley, “Structure and function of the blood–brain barrier,” Neurobiol. Dis., vol. 37, no. 1, Jan. 2010.

[82] H. Wolburg and A. Lippoldt, “Tight junctions of the blood-brain barrier: development, composition and regulation.,” Vasc. Pharmacol., vol. 38, no. 6, pp. 323–337, Jun. 2002.

[83] N. J. Abbott, A. A. K. Patabendige, D. E. M. Dolman, S. R. Yusof, and D. J. Begley, “Structure and function of the blood-brain barrier.,” Neurobiol. Dis., vol. 37, no. 1, pp. 13–25, Jan. 2010.

[84] J. M. Lajoie and E. V. Shusta, “Targeting receptor-mediated transport for delivery of biologics across the blood-brain barrier.,” Annu. Rev. Pharmacol. Toxicol., vol. 55, pp. 613–631, Oct. 2015.

[85] K. F. Timbie, B. P. Mead, and R. J. Price, “Drug and gene delivery across the blood-brain barrier with focused ultrasound.,” J. Control. Release : Off. J. Control. Release Soc., vol. 219, pp. 61–75, Dec. 2015.

[86] N. McDannold, C. D. Arvanitis, N. Vykhodtseva, and M. S. Livingstone, “Temporary disruption of the blood-brain barrier by use of ultrasound and microbubbles: safety and efficacy evaluation in rhesus macaques.,” Cancer Res., vol. 72, no. 14, pp. 3652–3663, Jul. 2012.

[87] B. P. Mead et al., “Novel Focused Ultrasound Gene Therapy Approach Noninvasively Restores Dopaminergic Neuron Function in a Rat Parkinson’s Disease Model.,” Nano Lett., vol. 17, no. 6, pp. 3533–3542, Jun. 2017.

[88] Y. Kung et al., “Focused shockwave induced blood-brain barrier opening and transfection.,” Sci. reports, vol. 8, no. 1, p. 2218, Feb. 2018.

[89] S. Kumari, S. M. Ahsan, J. M. Kumar, A. K. Kondapi, and N. M. Rao, “Overcoming blood brain barrier with a dual purpose Temozolomide loaded Lactoferrin nanoparticles for combating glioma (SERP-17-12433).,” Sci. reports, vol. 7, no. 1, p. 6602, Jul. 2017.

[90] H. Li et al., “Lactoferrin functionalized PEG-PLGA nanoparticles of shikonin for brain targeting therapy of glioma.,” Int. J. Biol. Macromol., vol. 107, no. Pt A, pp. 204–211, Mar. 2018.

[91] K. B. Johnsen et al., “Targeting transferrin receptors at the blood-brain barrier improves the uptake of immunoliposomes and subsequent cargo transport into the brain parenchyma.,” Sci. reports, vol. 7, no. 1, p. 10396, Sep. 2017.

[92] I. Mäger et al., “Targeting blood-brain-barrier transcytosis - perspectives for drug delivery.,” Neuropharmacology, vol. 120, pp. 4–7, Jul. 2017.

[93] L. You et al., “Targeted Brain Delivery of Rabies Virus Glycoprotein 29-Modified Deferoxamine-Loaded Nanoparticles Reverses Functional Deficits in Parkinsonian Mice.,” ACS nano, vol. 12, no. 5, pp. 4123–4139, May 2018.

[94] C. Zhang et al., “Dual-functional nanoparticles targeting amyloid plaques in the brains of Alzheimer’s disease mice.,” Biomaterials, vol. 35, no. 1, pp. 456–465, Jan. 2014.

[95] L. Shang, K. Nienhaus, and G. U. Nienhaus, “Engineered nanoparticles interacting with cells: size matters.,” J. nanobiotechnology, vol. 12, p. 5, Feb. 2014.

[96] Arnida, M. M. Janát-Amsbury, A. Ray, C. M. Peterson, and H. Ghandehari, “Geometry and surface characteristics of gold nanoparticles influence their biodistribution and uptake by macrophages.,” Eur. J. Pharm. Biopharm. : Off. J. Arbeitsgemeinschaft fur Pharm. Verfahrenstechnik e.V, vol. 77, no. 3, pp. 417–423, Apr. 2011.

[97] B. Zhang et al., “Anchored but not internalized: shape dependent endocytosis of nanodiamond.,” Sci. reports, vol. 7, p. 46462, Apr. 2017.

[98] N. Kato and R. Kondo, “Cellular internalization of polycation-coated microparticles and its dependence on their zeta potential,” Jpn. J. Appl. Phys., vol. 57, no. 3S2, Mar. 2018.

[99] L. I. Selby, C. M. Cortez-Jugo, G. K. Such, and A. P. R. Johnston, “Nanoescapology: progress toward understanding the endosomal escape of polymeric nanoparticles.,” Wiley Interdiscip. Rev. Nanomedicine nanobiotechnology, vol. 9, no. 5, Sep. 2017.

[100] B. Shi et al., “Challenges in DNA Delivery and Recent Advances in Multifunctional Polymeric DNA Delivery Systems.,” Biomacromolecules, vol. 18, no. 8, pp. 2231–2246, Aug. 2017.

[101] M. Dominska and D. M. Dykxhoorn, “Breaking down the barriers: siRNA delivery and endosome escape.,” J. cell Sci., vol. 123, no. Pt 8, pp. 1183–1189, Apr. 2010.

[102] M. Liu et al., “Real-time visualization of clustering and intracellular transport of gold nanoparticles by correlative imaging.,” Nat. Commun., vol. 8, p. 15646, May 2017.

[103] A. P. Lam and D. A. Dean, “Progress and prospects: nuclear import of nonviral vectors.,” Gene Ther., vol. 17, no. 4, pp. 439–447, Apr. 2010.

[104] L. D. Cervia, C.-C. Chang, L. Wang, M. Mao, and F. Yuan, “Enhancing Electrotransfection Efficiency Through Improvement in Nuclear Entry of Plasmid DNA,” Biophys. J., vol. 114, no. 3, Feb. 2018.

[105] R. Mout and V. M. Rotello, “Cytosolic and Nuclear Delivery of CRISPR/Cas9-ribonucleoprotein for Gene Editing Using Arginine Functionalized Gold Nanoparticles.,” Bio-protocol, vol. 7, no. 20, Oct. 2017.

[106] A. B. Hill, M. Chen, C.-K. Chen, B. A. Pfeifer, and C. H. Jones, “Overcoming Gene-Delivery Hurdles: Physiological Considerations for Nonviral Vectors.,” Trends Biotechnol., vol. 34, no. 2, pp. 91–105, Feb. 2016.

[107] C. L. Masters, R. Bateman, K. Blennow, C. C. Rowe, R. A. Sperling, and J. L. Cummings, “Alzheimer’s disease.,” Nat. Rev. Dis. Prim., vol. 1, p. 15056, Oct. 2015.

[108] J. Wang, B. J. Gu, C. L. Masters, and Y.-J. Wang, “A systemic view of Alzheimer disease - insights from amyloid-β metabolism beyond the brain.,” Nat. Rev. Neurol., vol. 13, no. 10, pp. 612–623, Sep. 2017.

[109] M. P. Murphy and H. LeVine, “Alzheimer’s disease and the amyloid-beta peptide.,” J. Alzheimer’s Dis. : JAD, vol. 19, no. 1, pp. 311–323, 2010.

[110] R. J. O’Brien and P. C. Wong, “Amyloid precursor protein processing and Alzheimer’s disease.,” Annu. Rev. Neurosci., vol. 34, pp. 185–204, 2011.

[111] A. Kumar, A. Singh, and Ekavali, “A review on Alzheimer’s disease pathophysiology and its management: an update,” Pharmacol. Reports, vol. 67, no. 2, pp. 195–203, Apr. 2015.

[112] D. J. Selkoe and J. Hardy, “The amyloid hypothesis of Alzheimer’s disease at 25 years.,” EMBO Mol. Med., vol. 8, no. 6, pp. 595–608, Jun. 2016.

[113] G. Rassu et al., “Nose-to-brain delivery of BACE1 siRNA loaded in solid lipid nanoparticles for Alzheimer’s therapy.,” Colloids surfaces. B, Biointerfaces, vol. 152, pp. 296–301, Apr. 2017.

[114] Y. Liu et al., “Brain-targeted co-delivery of therapeutic gene and peptide by multifunctional nanoparticles in Alzheimer’s disease mice.,” Biomaterials, vol. 80, pp. 33–45, Feb. 2016.

[115] A. A. Doolaanea, N. ’Izzati Mansor, N. H. Mohd Nor, and F. Mohamed, “Co-encapsulation of Nigella sativa oil and plasmid DNA for enhanced gene therapy of Alzheimer’s disease.,” J. Microencapsul., vol. 33, no. 2, pp. 114–126, Mar. 2016.

[116] R. Zhang, Y. Li, B. Hu, Z. Lu, J. Zhang, and X. Zhang, “Traceable Nanoparticle Delivery of Small Interfering RNA and Retinoic Acid with Temporally Release Ability to Control Neural Stem Cell Differentiation for Alzheimer’s Disease Therapy.,” Adv. Mater., vol. 28, no. 30, pp. 6345–6352, Aug. 2016.

[117] C. Klein and A. Westenberger, “Genetics of Parkinson’s disease.,” Cold Spring Harb. Perspect. Med., vol. 2, no. 1, p. a008888, Jan. 2012.

[118] N. K. Patel and S. S. Gill, “GDNF delivery for Parkinson’s disease.,” Acta Neurochir. Suppl., vol. 97, no. Pt 2, pp. 135–154, 2007.

[119] D. Kirik, C. Rosenblad, and A. Björklund, “Characterization of behavioral and neurodegenerative changes following partial lesions of the nigrostriatal dopamine system induced by intrastriatal 6-hydroxydopamine in the rat.,” Exp. Neurol., vol. 152, no. 2, pp. 259–277, Aug. 1998.

[120] D. Yurek, U. Hasselrot, O. Sesenoglu-Laird, L. Padegimas, and M. Cooper, “Intracerebral injections of DNA nanoparticles encoding for a therapeutic gene provide partial neuroprotection in an animal model of neurodegeneration.,” Nanomedicine : nanotechnology, Biol. Med., vol. 13, no. 7, pp. 2209–2217, Oct. 2017.

[121] S. Niu et al., “Inhibition by Multifunctional Magnetic Nanoparticles Loaded with Alpha-Synuclein RNAi Plasmid in a Parkinson’s Disease Model.,” Theranostics, vol. 7, no. 2, pp. 344–356, Jan. 2017.

[122] C. Helmschrodt et al., “Polyethylenimine Nanoparticle-Mediated siRNA Delivery to Reduce α-Synuclein Expression in a Model of Parkinson’s Disease.,” Mol. Ther. Nucleic acids, vol. 9, pp. 57–68, Dec. 2017.

[123] T. Macpherson, M. Morita, and T. Hikida, “Striatal direct and indirect pathways control decision-making behavior.,” Front. Psychol., vol. 5, p. 1301, Nov. 2014.

[124] H. B. Kordasiewicz et al., “Sustained therapeutic reversal of Huntington’s disease by transient repression of huntingtin synthesis.,” Neuron, vol. 74, no. 6, pp. 1031–1044, Jun. 2012.

[125] S. Aguiar, B. van der Gaag, and F. A. B. Cortese, “RNAi mechanisms in Huntington’s disease therapy: siRNA versus shRNA.,” Transl. Neurodegener., vol. 6, p. 30, Nov. 2017.

[126] L. Drew, “How the gene behind Huntington’s disease could be neutralized.,” Nature, vol. 557, no. 7707, pp. S39–S41, May 2018.

[127] S. Yang et al., “CRISPR/Cas9-mediated gene editing ameliorates neurotoxicity in mouse model of Huntington’s disease.,” J. Clin. Investig., vol. 127, no. 7, pp. 2719–2724, Jun. 2017.

[128] J. F. Alterman et al., “Hydrophobically Modified siRNAs Silence Huntingtin mRNA in Primary Neurons and Mouse Brain.,” Mol. Ther. Nucleic acids, vol. 4, p. e266, Dec. 2015.

[129] M.-C. Didiot et al., “Exosome-mediated Delivery of Hydrophobically Modified siRNA for Huntingtin mRNA Silencing.,” Mol. Ther. : J. Am. Soc. Gene Ther., vol. 24, no. 10, pp. 1836–1847, Oct. 2016.

[130] B. M. D. C. Godinho, J. R. Ogier, R. Darcy, C. M. O’Driscoll, and J. F. Cryan, “Self-assembling modified β-cyclodextrin nanoparticles as neuronal siRNA delivery vectors: focus on Huntington’s disease.,” Mol. Pharm., vol. 10, no. 2, pp. 640–649, Feb. 2013.

[131] “Correction to: Heart Disease and Stroke Statistics-2018 Update: A Report From the American Heart Association.,” Circulation, vol. 137, no. 12, p. e493, Mar. 2018.

[132] S.-D. Chen, D.-I. Yang, T.-K. Lin, F.-Z. Shaw, C.-W. Liou, and Y.-C. Chuang, “Roles of oxidative stress, apoptosis, PGC-1α and mitochondrial biogenesis in cerebral ischemia.,” Int. J. Mol. Sci., vol. 12, no. 10, pp. 7199–7215, Oct. 2011.

[133] M. Lee, K.-S. Hong, and J. L. Saver, “Efficacy of intra-arterial fibrinolysis for acute ischemic stroke: meta-analysis of randomized controlled trials.,” Stroke, vol. 41, no. 5, pp. 932–937, May 2010.

[134] Y. Tang et al., “MRI/SPECT/Fluorescent Tri-Modal Probe for Evaluating the Homing and Therapeutic Efficacy of Transplanted Mesenchymal Stem Cells in a Rat Ischemic Stroke Model.,” Adv. Funct. Mater., vol. 25, no. 7, pp. 1024–1034, Feb. 2015.

[135] S. D. Mahajan et al., “Suppression of MMP-9 expression in brain microvascular endothelial cells (BMVEC) using a gold nanorod (GNR)-siRNA nanoplex.,” Immunol. Investig., vol. 41, no. 4, pp. 337–355, Aug. 2012.

[136] K. T. Al-Jamal et al., “Functional motor recovery from brain ischemic insult by carbon nanotube-mediated siRNA silencing.,” Proc. Natl. Acad. Sci. United States Am., vol. 108, no. 27, pp. 10952–10957, Jul. 2011.

[137] Y. Wang, S.-Y. Li, S. Shen, and J. Wang, “Protecting neurons from cerebral ischemia/reperfusion injury via nanoparticle-mediated delivery of an siRNA to inhibit microglial neurotoxicity.,” Biomaterials, vol. 161, pp. 95–105, Apr. 2018.