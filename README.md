# Awesome Genetic Engineering [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

_A curated[^curation_details] list of awesome resources on genetic engineering[^definition_genetic_engineering]._

[^definition_genetic_engineering]: (from Wikipedia, see citation at the bottom) **Genetic engineering**, also called **genetic modification** or **genetic manipulation**, is the modification and manipulation of an organism's [genes](https://en.wikipedia.org/wiki/Gene "Gene") using [technology](https://en.wikipedia.org/wiki/Technology "Technology"). It is a set of [technologies](https://en.wikipedia.org/wiki/Genetic_engineering_techniques "Genetic engineering techniques") used to change the genetic makeup of cells, including the transfer of genes within and across species boundaries to produce improved or novel [organisms](https://en.wikipedia.org/wiki/Organisms "Organisms"). New [DNA](https://en.wikipedia.org/wiki/DNA "DNA") is obtained by either isolating and copying the genetic material of interest using [recombinant DNA](https://en.wikipedia.org/wiki/Recombinant_DNA "Recombinant DNA") methods or by [artificially synthesising](https://en.wikipedia.org/wiki/Artificial_gene_synthesis "Artificial gene synthesis") the DNA. A construct is usually created and used to insert this DNA into the host organism. The first recombinant DNA molecule was made by [Paul Berg](https://en.wikipedia.org/wiki/Paul_Berg "Paul Berg") in 1972 by combining DNA from the monkey virus [SV40](https://en.wikipedia.org/wiki/SV40 "SV40") with the [lambda virus](https://en.wikipedia.org/wiki/Lambda_phage "Lambda phage"). As well as inserting [genes](https://en.wikipedia.org/wiki/Gene "Gene"), the process can be used to remove, or "[knock out](https://en.wikipedia.org/wiki/Gene_knockout "Gene knockout")", genes. The new DNA can either be inserted randomly or [targeted](https://en.wikipedia.org/wiki/Gene_targeting "Gene targeting") to a specific part of the [genome](https://en.wikipedia.org/wiki/Genome "Genome"). [[1](https://en.wikipedia.org/wiki/Genetic_engineering#cite_note-1)] CITATION: Wikipedia contributors. "Genetic engineering." Wikipedia. Last modified September 30, 2025. Accessed October 24, 2025. <https://en.wikipedia.org/wiki/Genetic_engineering>.

![](./assets/genetic_engineering.jpg) [^image_attribution]

[^image_attribution]: This file is licensed under the [Creative Commons](https://en.wikipedia.org/wiki/en:Creative_Commons "w:en:Creative Commons") [Attribution-Share Alike 3.0 Unported](https://creativecommons.org/licenses/by-sa/3.0/deed.en "creativecommons:by-sa/3.0/deed.en") license. Image Changed Made: None. Image Link: <https://commons.wikimedia.org/wiki/File:Rat_hippocampus_stained_with_antibody_to_NeuN_(green),_myelin_basic_protein_(red)_and_DNA_(blue).jpg>. Image Description: "This is a section of adult rat hippocampus stained with antibody to the neuronal nucleus and perikaryal antibody [NeuN](https://en.wikipedia.org/wiki/NeuN "en:NeuN") (a.k.a. Fox3) in green and antibody to myelin basic protein (MBP) in red. The MBP reveals neuronal axons while the NeuN antibody reveals neurons but not non neuronal cells. The fluorescent blue DNA stain [DAPI](https://en.wikipedia.org/wiki/DAPI "en:DAPI") was used to stain nuclei on neurons and non-neuronal cells. Antibodies and imaging courtesy of [EnCor Biotechnology Inc](https://en.wikipedia.org/wiki/EnCor_Biotechnology_Inc "en:EnCor Biotechnology Inc").".

[^curation_details]: This list follows specific scoping guidelines. **CRISPR Tools & Databases** covers CRISPR array databases, guide RNA design tools, and anti-CRISPR resources. **Design & Analysis Software** features open-source platforms and computational prediction tools. **Protocols & Methods** includes comprehensive protocol collections and key editing methods. **Synthetic Biology Resources** covers plasmid repositories, courses, journals, and communities. **Organizations & Networks** lists research institutes and biotech companies. **Educational Resources** includes books and video lectures. **Commercial Suppliers** covers CRISPR reagents and synthetic DNA providers. **Regulatory & Ethics** features governance guidelines and ethical frameworks.

## Contents

- [CRISPR Tools & Databases](#crispr-tools--databases)
- [Design & Analysis Software](#design--analysis-software)
- [Protocols & Methods](#protocols--methods)
- [Synthetic Biology Resources](#synthetic-biology-resources)
- [Organizations & Networks](#organizations--networks)
- [Educational Resources](#educational-resources)
- [Commercial Suppliers](#commercial-suppliers)
- [Regulatory & Ethics](#regulatory--ethics)
- [People](#people)
- [Related Awesome Lists](#related-awesome-lists)

## CRISPR Tools & Databases

### CRISPR Array & Cas Gene Databases

1. [CRISPRCasdb](https://crisprcas.i2bc.paris-saclay.fr): 36,605 full prokaryote genomes with CRISPR and Cas gene data.
2. [CRISPRdetect](https://github.com/davidchyou/CRISPRDetect): Web tool for automatic CRISPR array detection and prediction.
3. [CRISPRidentify](https://github.com/BackofenLab/CRISPRidentify): Machine learning tool to distinguish genuine CRISPR arrays from false positives.
4. [CRISPRloci](https://github.com/TulsaBioinformaticsToolsmith/CRISPRloci): Enhanced CRISPR array identification with data-driven filtering.

### Guide RNA Design Tools

1. [CRISPOR](http://crispor.tefor.net): Versatile platform for guide RNA design with off-target scoring and locus visualization (multiple species).
2. [CHOPCHOP](https://chopchop.cbu.uib.no): Web tool for guide RNA design across genome-editing nucleases.
3. [Benchling CRISPR Tool](https://www.benchling.com/crispr): Cloud-based guide RNA design with collaboration features.
4. [Cas-Designer](http://www.rgenome.net/cas-designer/): gRNA design for Cas9, Cas12a, and base editors.
5. [IDT CRISPR Design Tool](https://www.idtdna.com/site/order/designtool/index/CRISPR_SEQUENCE): Free design tool from Integrated DNA Technologies.

### Anti-CRISPR Resources

1. [anti-CRISPRdb](http://guolab.whu.edu.cn/anti-CRISPRdb/): Database of anti-CRISPR proteins (Acr) with sequences, coding regions, and taxonomy.
2. [AcrDB](http://bcb.unl.edu/AcrDB): 39,799 Acr-Aca operons across 7,000+ RefSeq genomes.
3. [CASANOVA](https://www.nature.com/articles/s41589-019-0421-6): Optogenetic control of CRISPR editing using anti-CRISPR proteins.

## Design & Analysis Software

### Open Source Platforms

1. [Addgene CRISPR Resources](https://www.addgene.org/guides/crispr/): Comprehensive guide with plasmid repositories and protocols.
2. [Synthego ICE Analysis](https://ice.synthego.com): Free CRISPR analysis tool for Sanger sequencing data.
3. [CRISPResso2](https://github.com/pinellolab/CRISPResso2): Analysis of genome editing outcomes from sequencing data.

### Computational Prediction

1. [Elevation](https://github.com/mshen/predict-activity): Machine learning prediction of CRISPR/Cas9 activity.
2. [DeepCRISPR](https://github.com/bm2-lab/DeepCRISPR): Deep learning for gRNA efficacy prediction.

## Protocols & Methods

### Comprehensive Protocol Collections

1. [Addgene CRISPR Protocols](https://www.addgene.org/protocols/crispr/): Detailed wet-lab protocols for CRISPR experiments.
2. [IDT Alt-R CRISPR Protocols](https://www.idtdna.com/protocols): Lipofection and electroporation protocols for mammalian cells, user methods for model organisms (zebrafish, C. elegans, mice, iPSCs).
3. [NEB CRISPR Protocol Library](https://www.neb.com/tools-and-resources/feature-articles/crispr-cas9-and-targeted-genome-editing-a-new-era-in-molecular-biology): Protocols for Cas9 nucleases and NHEJ/HDR pathways.
4. [Springer Nature CRISPR Protocols](https://experiments.springernature.com/techniques/crispr): Peer-reviewed protocols for human iPSCs, mammalian cells, and knock-ins.

### Key Methods

- **NHEJ (Non-Homologous End Joining)**: Error-prone repair causing indels for gene knockouts.
- **HDR (Homology-Directed Repair)**: Precise edits using donor DNA templates with homology arms.
- **Base Editing**: Direct C→T or A→G conversion without DSBs.
- **Prime Editing**: "Search and replace" genome editing without donor DNA or DSBs.

### Model Organism-Specific

1. [Human iPSC CRISPR Protocol](https://currentprotocols.onlinelibrary.wiley.com/doi/10.1002/cpcb.8): Optimized for pluripotent stem cells.

## Synthetic Biology Resources

### Plasmid Repositories

1. [Addgene Synthetic Biology Collection](https://www.addgene.org/synthetic-biology/): 10,000+ plasmids for cloning, genetic circuits, metabolic engineering.
2. [Registry of Standard Biological Parts (BioBricks)](http://parts.igem.org): 20,000+ standardized biological parts (iGEM Foundation).
3. [JBEI Public Registry](https://public-registry.jbei.org): Joint BioEnergy Institute part registry.

### Online Courses & Education

1. [edX Principles of Synthetic Biology](https://www.edx.org/course/principles-of-synthetic-biology): Free online course from MIT.
2. [OpenWetWare](https://openwetware.org): Collaborative wiki for protocols and educational resources.

### Journals

1. [ACS Synthetic Biology](https://pubs.acs.org/journal/asbcd6): American Chemical Society journal.
2. [Synthetic Biology (Oxford)](https://academic.oup.com/synbio): Open access journal.

### Communities

1. [iGEM (International Genetically Engineered Machine)](https://igem.org): Annual synthetic biology competition for students.
2. [SynBioBeta](https://synbiobeta.com): Synthetic biology industry network.

## Organizations & Networks

1. [The CRISPR/Cas9 Consortium](https://www.broadinstitute.org/research-highlights-crispr): Broad Institute research collaborative.
2. [Innovative Genomics Institute (IGI)](https://innovativegenomics.org): UC Berkeley/UCSF center for genome engineering.
3. [CRISPR Therapeutics](https://crisprtx.com): Clinical-stage biotech company (CAR-T therapies).
4. [Caribou Biosciences](https://cariboubio.com): CRISPR therapeutic platform company.

## Educational Resources

### Books

1. [A Crack in Creation](https://www.amazon.com/Crack-Creation-Editing-Unthinkable-Evolution/dp/0544716949): Jennifer Doudna and Samuel Sternberg on the CRISPR discovery story.
2. [Editing Humanity](https://www.amazon.com/Editing-Humanity-Kevin-Davies/dp/1639362975): Kevin Davies on the ethics and future of gene editing.
3. [Synthetic Biology: A Primer (Revised Edition)](https://www.amazon.com/Synthetic-Biology-Primer-Revised/dp/1783268794): Academic introduction to synthetic biology.

### Video Lectures

1. [iBiology CRISPR Lectures](https://www.ibiology.org/genetics-and-gene-regulation/crispr/): Free lecture series featuring Jennifer Doudna, Feng Zhang.
2. [Broad Institute CRISPR Videos](https://www.youtube.com/user/BroadInstitute): Educational videos on genome editing.

## Commercial Suppliers

### CRISPR Reagents

1. [Synthego](https://www.synthego.com): Synthetic guide RNAs and Cas9 proteins.
2. [IDT (Integrated DNA Technologies)](https://www.idtdna.com/pages/products/crispr-genome-editing): Alt-R CRISPR System (gRNAs, Cas9, transfection).
3. [Addgene](https://www.addgene.org): Non-profit plasmid repository (deposited by researchers).
4. [Thermo Fisher Scientific](https://www.thermofisher.com/us/en/home/life-science/genome-editing.html): TrueCut Cas9 and GeneArt CRISPR systems.
5. [GenScript](https://www.genscript.com/crispr-cas9-genome-editing.html): Custom CRISPR services and reagents.

### Synthetic DNA & Gene Synthesis

1. [Twist Bioscience](https://www.twistbioscience.com): High-throughput DNA synthesis.
2. [IDT gBlocks](https://www.idtdna.com/pages/products/genes-and-gene-fragments/double-stranded-dna-fragments/gblocks-gene-fragments): Synthetic dsDNA fragments (125-3,000 bp).
3. [GenScript Gene Synthesis](https://www.genscript.com/gene_synthesis.html): Custom gene and plasmid construction.

## Regulatory & Ethics

1. [NIH Guidelines for Research Involving Recombinant DNA](https://osp.od.nih.gov/biotechnology/nih-guidelines/): U.S. federal regulations.
2. [FDA Cellular & Gene Therapy Guidance](https://www.fda.gov/vaccines-blood-biologics/cellular-gene-therapy-products): Clinical translation pathways.
3. [WHO Human Genome Editing Governance](https://www.who.int/groups/expert-advisory-committee-on-developing-global-standards-for-governance-and-oversight-of-human-genome-editing): International governance framework.

## People

- [Jennifer Doudna](https://github.com/Doudna-lab) - UC Berkeley / Innovative Genomics Institute. Co-inventor of CRISPR-Cas9 gene editing. 2020 Nobel Prize in Chemistry.
- [Feng Zhang](https://github.com/fengzhanglab) - Broad Institute of MIT and Harvard. First to demonstrate CRISPR-Cas9 editing in mammalian cells (2013).
- [Emmanuelle Charpentier](https://www.emmanuelle-charpentier.org/) - Max Planck Unit for the Science of Pathogens. Co-discovered the CRISPR-Cas9 mechanism. 2020 Nobel Prize in Chemistry.
- [David Liu](https://www.liugroup.us/) - Broad Institute / Harvard University. Invented base editing and prime editing for precise genome modification without double-strand breaks.
- [Neville Sanjana](https://github.com/sanjanalab) - New York Genome Center / NYU. Developed genome-scale CRISPR screening approaches and pooled library design tools.
- [Patrick Hsu](https://github.com/hsulab-arc) - Arc Institute / UC Berkeley. Discovered programmable recombinases (bridge RNAs) and led development of Evo genomic AI models.
- [Le Cong](https://github.com/cong-lab) - Stanford University. Co-first author on one of the first CRISPR-Cas9 human cell editing papers. Developed CRISPR-GPT.
- [John Doench](https://www.broadinstitute.org/bios/john-doench) - Broad Institute. Created CRISPick sgRNA design portal and genome-wide CRISPR screening libraries.

## Related Awesome Lists

- [Awesome Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics) - Bioinformatics libraries and software.
- [Awesome CRISPR](https://github.com/davidliwei/awesome-CRISPR) - Software, websites, and databases for genome engineering.
- [Awesome Synthetic Biology](https://github.com/websemantics/awesome-synthetic-biology) - Synthetic biology and genetic engineering projects and resources.
- [Awesome Computational Biology](https://github.com/inoue0426/awesome-computational-biology) - Computational biology resources.
- [Awesome Deep Learning in Biology](https://github.com/gokceneraslan/awesome-deepbio) - Deep learning applications in computational biology.
- [Awesome Preimplantation Genetic Diagnosis](https://github.com/O957/awesome-preimplantation-genetic-diagnosis) - Genetic testing and diagnosis of embryos.

## Contributing

Notice anything missing that would be a good fit? If interested in contributing, please see the [contributing file](./CONTRIBUTING.md) for further direction.

## Code of Conduct

Please see the [code of conduct](./CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [O957](https://github.com/O957) has waived all copyright and related or neighboring rights to this work.
