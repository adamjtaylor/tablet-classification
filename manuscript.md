---
title: Complementary classification of solid oral dosage forms in ambient conditions by desorption electrospray ionization mass spectrometry and transmission Raman spectroscopy
keywords:
- desorption electrospray ionization mass spectrometry
- transmission Raman spectroscopy
- solid oral dosage form
- classification
lang: en-US
date-meta: '2021-10-18'
author-meta:
- Adam J Taylor
- Dimitrios Tsikritsis
- Alex Dexter
- Amy Burton
- Josephine Bunch
- Natalie Belsey
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="Complementary classification of solid oral dosage forms in ambient conditions by desorption electrospray ionization mass spectrometry and transmission Raman spectroscopy" />
  <meta name="citation_title" content="Complementary classification of solid oral dosage forms in ambient conditions by desorption electrospray ionization mass spectrometry and transmission Raman spectroscopy" />
  <meta property="og:title" content="Complementary classification of solid oral dosage forms in ambient conditions by desorption electrospray ionization mass spectrometry and transmission Raman spectroscopy" />
  <meta property="twitter:title" content="Complementary classification of solid oral dosage forms in ambient conditions by desorption electrospray ionization mass spectrometry and transmission Raman spectroscopy" />
  <meta name="dc.date" content="2021-10-18" />
  <meta name="citation_publication_date" content="2021-10-18" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Adam J Taylor" />
  <meta name="citation_author_institution" content="National Physical Laboratory, Teddington, UK" />
  <meta name="citation_author_institution" content="Current affiliation: Sage Bionetworks, Seattle, WA, USA" />
  <meta name="citation_author" content="Dimitrios Tsikritsis" />
  <meta name="citation_author_institution" content="National Physical Laboratory, Teddington, UK" />
  <meta name="citation_author" content="Alex Dexter" />
  <meta name="citation_author_institution" content="National Physical Laboratory, Teddington, UK" />
  <meta name="citation_author" content="Amy Burton" />
  <meta name="citation_author_institution" content="National Physical Laboratory, Teddington, UK" />
  <meta name="citation_author_institution" content="Current affiliation: GlaxoSmithKline, Stevenage, UK" />
  <meta name="citation_author" content="Josephine Bunch" />
  <meta name="citation_author_institution" content="National Physical Laboratory, Teddington, UK" />
  <meta name="citation_author_institution" content="Imperial College London, London, UK" />
  <meta name="citation_author_institution" content="The Rosalind Frankilin Insitute, Harwell, UK" />
  <meta name="citation_author" content="Natalie Belsey" />
  <meta name="citation_author_institution" content="National Physical Laboratory, Teddington, UK" />
  <link rel="canonical" href="https://adamjtaylor.github.io/tablet-classification/" />
  <meta property="og:url" content="https://adamjtaylor.github.io/tablet-classification/" />
  <meta property="twitter:url" content="https://adamjtaylor.github.io/tablet-classification/" />
  <meta name="citation_fulltext_html_url" content="https://adamjtaylor.github.io/tablet-classification/" />
  <meta name="citation_pdf_url" content="https://adamjtaylor.github.io/tablet-classification/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://adamjtaylor.github.io/tablet-classification/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://adamjtaylor.github.io/tablet-classification/v/84b83cd6ae7e945e129cff035d81e6adfe5c7a01/" />
  <meta name="manubot_html_url_versioned" content="https://adamjtaylor.github.io/tablet-classification/v/84b83cd6ae7e945e129cff035d81e6adfe5c7a01/" />
  <meta name="manubot_pdf_url_versioned" content="https://adamjtaylor.github.io/tablet-classification/v/84b83cd6ae7e945e129cff035d81e6adfe5c7a01/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...








## Authors



+ **Adam J Taylor**<br><br>
  <small>
     National Physical Laboratory, Teddington, UK; Current affiliation: Sage Bionetworks, Seattle, WA, USA
  </small>

+ **Dimitrios Tsikritsis**<br><br>
  <small>
     National Physical Laboratory, Teddington, UK
  </small>

+ **Alex Dexter**<br><br>
  <small>
     National Physical Laboratory, Teddington, UK
  </small>

+ **Amy Burton**<br><br>
  <small>
     National Physical Laboratory, Teddington, UK; Current affiliation: GlaxoSmithKline, Stevenage, UK
  </small>

+ **Josephine Bunch**<br><br>
  <small>
     National Physical Laboratory, Teddington, UK; Imperial College London, London, UK; The Rosalind Frankilin Insitute, Harwell, UK
  </small>

+ **Natalie Belsey**<br><br>
  <small>
     National Physical Laboratory, Teddington, UK
  </small>



## Abstract {.page_break_before}

Discrepancies or defects in active ingredients, excipients and coatings that form solid oral dosage forms can both impact product quality and provide hallmarks of off-brand or counterfeit products. There is therefore a need for rapid and continuous analytical techniques that can assess and classify product differences of intact samples at- or near the production line, or in analytical labs, ideally without resorting to product dissolution.  

Here we test the ability of two rapid ambient chemical characterization methods to discriminate between solid dosage forms: desorption electrospray ionization mass spectrometry and transmission Raman spectroscopy. These two techniques are highly complementary, offering greater sensitivity to the analysis of the surface and the tablet bulk, respectively. The data sets generated were then used to test a variety of classification algorithms including linear discriminate analysis, tree-based methods, a simple neural network, and support vector machines (SVM). The highest performing algorithms for DESI-MSI were the SVM, with an additional performance boost when used with a polynomial kernel. For transmission Raman data, a linear discriminant analysis (LDA) model was found to be the most effective. 


## Introduction
Inconsistencies in active ingredients, excipients, the thickness and integrity of coatings and the presence of impurities in solid oral dosage forms all negatively affect their performance. 
Inferior quality attributes can be useful to identify off-brand or counterfeit products. 
There is a need for rapid and continuous analytical techniques that can assess and classify product differences of intact samples at- or near the production line, or in analytical labs, ideally without resorting to product dissolution [@doi:10.1016/j.xphs.2016.11.011]. 
Rapid measurement tools are particularly important to enable continuous monitoring, necessary to support the change from batch to continuous manufacturing. 
Analytical methods are required to monitor both the actives, coatings and consistency of the product: For example, in addition to the total API content, insight is also needed on degradation products, impurities, (co-) crystallinity/presence of polymorphs, and content uniformity. 
The ability to monitor tablet coating thickness and integrity is of great importance, particularly for functional coatings, such gastro-resistance, which would be compromised by insufficient thickness, or the occurrence of cracks in the film [@doi:10.1016/j.ijpharm.2013.01.062]. 

Quantitative analysis of pharmaceutical tablets is routinely performed by HPLC which offers accurate and sensitive measurements of the active ingredient(s) and excipients, in addition to the presence of any contaminants. 
However, solution-based analytical methods are destructive and labor-intensive.  

Mass spectrometric methods can provide unlabeled identification, both of expected ingredients in known samples and of contaminants or components of unknown formulations. 
Ambient ionization mass spectrometry approaches including DESI (desorption electrospray ionisation) and DART (direct analysis in real time) facilitate the desorption and ionization from the surface of samples at atmospheric conditions, without dissolution or additional sample preparation. 
They are therefore potentially useful tools for rapid assessment of solid oral dosage forms 

Optical spectroscopy techniques offer rapid, non-destructive analysis, including polymorphic identification [@doi:10.1039/c0an00352b], and are also able to measure insoluble ingredients. 
They have consequently been exploited for in-line process analytical testing and as quality control tools [@doi:10.1016/j.xphs.2016.11.011]. 
For example, infra-red-based techniques (FTIR and DESI [@doi:10.1007/s00216-006-0950-z]; and NIR and Mid-IR spectroscopy classification of MDMA containing tablets [@doi:10.1016/j.talanta.2018.11.027].
Near infrared is the most commonly used process analytical tool [@doi:10.1016/j.xphs.2016.11.011], however Raman spectroscopy provides complementary information and has grown in popularity in recent years, since it provides more distinct spectral features, and is better-suited to analysis in aqueous environments owing to the relatively weak strength of the Raman O-H band. 
Technological advancements have facilitated miniaturization, increased speed and reduced cost, resulting in more widespread implementation [@doi:10.1016/j.addr.2015.04.003]. 

### Ambient ionisation mass spectrometry of tablets

Desorption electrospray ionization uses a charged electrospray of organic solvent which, when directed at the sample surface in proximity to the mass spectrometry inlet, desorbs ions from the sample which may be taken up into a mass spectrometer [@doi:10.1126/science.1104404]. 
As this process takes place at ambient pressure and with a flexible geometry, the technique is suited for the analysis of a wide range of samples including explosives on surfaces [@doi:10.1039/b418697d], fingerprints [@doi:10.1039/c5an00112a], plants [@doi:10.1002/jms.2010] and tissues [@doi:10.1007/s00216-019-02151-z; @doi:10.1016/j.bbalip.2011.05.006].

One of the early descriptions of DESI-MSI was in the profiling of tablets [@doi:10.1021/ac050989d]. 
Chen et al demonstrated the use of DESI-MS to profile tablets containing loratadine, folic acid, acetaminophen (paracetamol), aspirin, melatonin or caffeine. 
Optimization of DESI parameters including voltage, solvent delivery and capillary temperature facilitated analysis at up to three scans per second.  
Subsequent studies using DESI-MS of tablets have focused on targeted analysis for active ingredients. For example, the identification MDMA and amphetamine derivatives in ecstasy tablets [@doi:10.1002/rcm.2280], counterfeit artesunate antimalarial tablets [@doi:10.1007/s00216-006-0950-z; @doi:10.1016/j.jasms.2007.11.016] and antiviral capsules [@doi:10.1039/b809471c].

For ambient mass spectrometry to be deployable in the field for counterfeiting applications, or in manufacturing environments for QA/QC, the mass spectrometer must be compact. 
Several designs for small field-deployable mass spectrometers have been demonstrated with DESI MS sources [@doi:10.1039/b517357d; @doi:10.1021/acs.analchem.9b00520].

Each of these applications has targeted expected components of the tablet of interest, predominantly active ingredients or excipients. 
However, in manufacturing QA/QC and counterfeit-detection applications, additional information on unexpected changes in active or excipient source or quality, as well as the introduction of contaminants may be of importance. 
Untargeted multivariate and machine learning approaches are therefore of interest to determine differences between samples using all spectral information. 

Classification approaches for mass spectrometry applications are proving powerful in a range of applications. The two most widespread applications of classification in mass spectrometry are in disease diagnosis and determination of bacterial type [@doi:10.1016/j.aca.2014.03.039]. 
A range of classification algorithms have been applied to mass spectrometry and spectroscopy data. PLS-DA is most commonly reported, although a range of algorithms including neural networks, and support vector machines [@doi:10.1007/s00521-016-2736-3] have been reported. 
Several publications have evaluated different classification algorithms but unsurprisingly the optimal algorithm depends greatly on the nature of the input data. A summary of classification and other data analysis for proteomics can be found here [@doi:10.1016/j.csbj.2020.07.009] and for metabolomics here [@doi:10.1007/s11306-017-1242-7]. 
Classification approaches are becoming more accessible through modeling tools with consistent grammar and data structure, and their integration into mass spectrometry software [ScilsLab,Waters software] [@doi:10.1007/s11306-017-1242-7]. 

Notably, classification of rapid evaporative ionization MS enables real-time classification of tissue types during surgery [@doi:10.1038/s41416-018-0048-3]. 
Classification of REIMS data has also found applications in food security [@doi:10.1021/acs.jafc.6b01041] and bacterial speciation [@doi:10.1021/ac5046752]. 
Classification approaches have also been widely employed in mass spectrometry imaging data, particularly in the classification of cancerous tissue [@doi:10.1186/s13058-017-0845-2].

### Raman spectroscopy analysis of tablets

Raman spectroscopy exploits the inelastic scattering of light by the sample to reveal valuable chemical and structural information. Information can be obtained from the sample in a non-destructive manner, making it a popular process analytical technology tool. 
Raman spectroscopy can be performed in a variety of sampling configurations/geometries, the most appropriate depending on the application. 
Confocal Raman microscopy can provide detailed chemical mapping with high spatial resolution, however this is generally reserved for forensic investigation rather than continuous monitoring, since it requires lengthy acquisition times. 
Sub-sampling issues associated with conventional backscattered Raman can be overcome by strategies such as sample rotation in conjunction with spectral averaging, or simultaneous wide angle illumination [@doi:10.1039/C3AN36843B].  

Matousek et al demonstrated the ability of transmission Raman spectroscopy to probe deep into turbid materials such as pharmaceutical tablets and provide information on their bulk properties [@doi:10.1366/000370206779321463; @doi:10.1016/j.jpba.2010.10.029]. 
In contrast to conventional backscattered Raman, in transmission Raman spectroscopy the beam passes through the full thickness of the tablet, sampling a much larger volume of the material, and consequently provides more representative sampling [@doi:10.1366/000370207782597085].
 Although Raman scattering intensity is linear with concentration within the same confocal plane, transmission Raman signal intensity is slightly biased towards the bulk of the tablet relative to the exterior due to internal scattering [@doi:10.1366/11-06259]. 
 In contrast, DESI-MSI sampling is biased towards the surface/coating composition. Therefore, in combination, these two techniques should provide a powerful toolkit with which to assess compositional differences between pharmaceutical tablet formulations.  

Raman spectra of complex mixtures such as solid dosage forms often have complicated spectra with overlapping peaks. 
For this reason, multivariate techniques are often applied to help identify the components of interest and changes in chemistry. 
The selection and use of unsupervised and/or supervised techniques on Raman spectra rely on factors such as prior knowledge of the raw component spectra, and the quantity and complexity of the spectra [@doi:10.1016/j.trac.2020.116157].

As with mass spectrometry, classification of Raman spectroscopy data has been primarily focused on disease diagnostics [@doi:10.1002/jrs.882; @doi:10.1002/jbio.200810024; @doi:10.1155/2016/1603609] and bacterial analysis [@doi:10.1002/bip.20448; @doi:10.1002/jrs.5343]. Other noteworthy examples of the use of classification in Raman spectroscopy include differentiation of narcotics [@doi:10.1520/JFS15244J], pharmaceuticals [@doi:10.1016/j.talanta.2010.01.046], [@doi:10.1016/j.jpba.2006.01.033], and counterfeit tablets [@doi:10.1002/jrs.1621]. 

There have been relatively few comparisons of different classification methods for Raman spectroscopy data. 
Zheng et al. compared SVM, LDA and k-nearest neighbours (KNN) methods to classify renin hypertension from Raman data from serum [@doi:10.1016/j.saa.2019.02.063]. 
They found that SVM and LDA performed similarly, and both outperformed the KNN algorithm.  Partial least squares (PLS) and PLS discriminant analysis are also commonly used methods in characterizing tablets, however care is required depending on the data quantity and the pre-preprocessing performed  [@doi:10.1002/cem.2609]. 
Qun et al. tested the classification of expired drugs using PLS-DA, SVM and KNN, and reported that SVM gave the strongest performance [@doi:10.1016/j.jpba.2014.01.027].
ransson et al tested the performance of multivariate methods including PLS, classical least squares (CLS) and multivariate curve resolution (MCR) for classification of pharmaceutical tablets [@doi:10.1002/cem.1330]. 


### Objective
In this study we set out to explore the potential of DESI-MSI and transmission Raman spectroscopy to distinguish commercially available pharmaceutical tablets with similar or different formulations. 
Pairing DESI with transmission Raman spectroscopy was of particular interest due to their complementarity and relative abilities to sensitively probe the surface vs the bulk of the tablets. 
Classification of tablets based on both active ingredients and excipients has the potential to be used for in-line quality control measures during pharmaceutical manufacturing, and for rapid counterfeit testing. 
As such we have tested a range of classification algorithms on their capability to differentiate these tablets using a range of pre-processing methods to determine the best approaches to use in different applications. 

## Experimnental

### Samples

Samples were selected from commercially available of-the-shelf products and purchased from a local supplier. Their names, active ingredients, listed excipients and MHRA product license numbers are included in Table @tbl:samples.


| Type | Product name | Active ingredients| Listed excipients | MHRA licence |
|:-----|:------------:|:------------------:|:----------------:|:------------:|
| A | Anadin Extra Tablets | 300 mg Aspirin, 200 mg Paracetamol, 45 mg Caffeine | Maize starch, microcrystalline cellulose (E460), hydrogenated vegetable oil, hydroxypropyl methylcellulose (E464), polyethylene glycol, pregelatinised starch and povidone  | PL 00165/5013R |
| B | Tesco Paracetamol Extra Tablets | 500 mg Paracetamol, 65 mg Caffeine |tarch, povidone k-30, povidone k-90, croscarmellose sodium, talc, stearic acid and magnesium stearate | PL 08977/0025 |
| C | Tesco Paracetamol Tablets | 500 mg Paracetamol | Potato Starch, pregelatinised starch, magnesium stearate, povidone, stearic acid and talc | PL 08977/0014 |
| D | Tesco Extra Power Pain Control Tablets | 300 mg Aspirin, 200 mg Paracetamol, 45 mg Caffeine | Povidone, hydroxypropylcellulose, stearic acid, microcrystalline cellulose, maize starch, pregelatinised starch, hydroxypropyl methylcellulose 5cPs, hydroxypropyl methylcellulose 15cPs, macrogol 4000 | PL 29831/0164 

Table: Details of the tablet types analysed. Letter codes for each type are used throughout
{#tbl:samples}

### DESI MS

DESI-MS measurements were performed on a Synapt G2-Si Q-IM-ToF mass spectrometer (Waters Corp). The instrument was operated in ‘resolution mode’. The ion mobility cell was not used. Positive ion mode spectra were collected with a scan time of 1 second across a mass range of m/z 50 to m/z 1200. The instrument was fitted with a prototype DESI source (Waters Corp), with the sprayer configured for electroflow focusing with a fused silica capillary sitting approximately 1 mm behind a 200 µm steel orifice. Methanol with 5% water by volume was delivered at 2 µl/m by a pressure pump (Dolomite). Nitrogen gas was delivered at 0.2 MPa. The spray voltage was set at 5 kV. A heated inlet capillary was set to a calibrated temperature of 400°C using a PID (Waters Research Centre, Hungary). Tablets were sampled by holding the tablet 1-2 mm away from the DESI spray head using plastic tweezers. For training data, acquisition was started with the tablet already under the spray head, such that only data from the tablet surface was acquired, while validation data was collected continuously. 

### Transmission Raman spectroscopy 

Transmission Raman spectra were acquired using a Renishaw InVia Qontor Raman microscope equipped with a 830 nm excitation source fibre-coupled to an InVia transmission Raman accessory (Renishaw plc, Wotton-under-Edge, Gloucestershire), in a temperature controlled environment. Light was collected in transmission with the x5 air objective lens (0.12 NA, N-PLAN, Leica). Tablets were carefully placed onto a flat silicon sample support with a hole just smaller than the tablet dimensions, so that the excitation beam was able to pass through the tablet but not the sample support. Six tablets were analysed of each type in pseudo-random order. Three measurement replicates were acquired, each complete data set was collected on three separate days.  

For all tablets, extended spectra were acquired using Renishaw Wire (version 5.3) software for the spectral range of 50 to 1800 cm^-1^, with an acquisition time of 30 seconds, and 5 accumulations. Laser power was set to 100% which has been measured at the sample to be approximately 117 mW. An internal silicon calibration reference spectrum was acquired each day to correct the Raman shift of the data.

### Data analysis 

All data were analyzed in R version 3.6.2 (2019-12-12) "Dark and Stormy Night" and RStudio Server version 1.2.5019. Analysis was conducted using the tidyverse [@doi:10.21105/joss.01686] and tidymodels [@https://www.tidymodels.org] metapackages. Raman data preprocessing was conducted in MATLAB 2020a. All analysis was performed on a Linux workstation (Intel Core i9-7900X CPU with 10 cores @ 3.30 GHz, 128G RAM, Ubuntu 16.04.6 LTS. 

### DESI preprocessing 

For model development and comparison, data were converted from Waters raw format to mzML format using ProteoWizard MSConvert version 3.0.19239-0ae547798. These were read into R using the mzR package. All spectra were re-binned onto the same mass axis with a bin width of m/z 0.01. A mean spectrum of all training data was peak picked using the findPeaks function from the prcma package with a peak intensity threshold of three times the median intensity of the spectrum. 1217 peaks were found. Each spectrum was then individually integrated across the found peak widths to form a datacube. Each scan of the validation dataset was similarly integrated across the peak widths from the training dataset. Reduced peak datacubes were generated by filtering for the top n most intense peaks. Down-binning to simulate reduced mass resolving power was performed by rounding m/z values and summing intensities within each rounded m/z bin. 

### Transmission Raman spectroscopy preprocessing 

Cosmic ray removal was performed automatically by Renishaw Wire (version 5.3) and spectra exported to .txt format. The Raman spectra were baseline corrected using the msbackadj() Matlab function. The baseline was estimated within multiple shifted windows of width 20 separation units, then a spline approximation was used to regress the varying baseline to the window points. The estimated baseline for each spectrum was then subtracted from the corresponding original. The background subtracted spectra were read in R for subsequent processing and analysis. The data were normalized to total spectrum intensity and the Raman shift recalibrated using the weighted-mean centroid to the 520.7 cm-1 peak from the daily Si wafer sample spectrum as a reference. Extended spectra were truncated to a wavenumber range between 250 cm-1 and 1700 cm-1. Due to the limited number of wavenumber bins and the challenges of peak-picking Raman data, the continuous data were taken forward for classification. 

### Classification 

Spectra were collated into a 10-fold cross validation 1 with 10 repeats in a 4/1/5 (train/test/total) split.  To remove highly co-variate polymer peak sequences leading to overfitting, highly correlating variables (Pearson correlation > 0.9) were removed from DESI MSI data. Data were centered around the arithmetic mean and scaled to have a standard deviation of one. Underrepresented classes (for DESI MSI, the background class) were up sampled. Each training fold was applied to a range of classification algorithms using the tidymodels package. All models were implemented with their default parameters beyond setting to classification mode. The functions, engines and default parameters used for each model are provided in supplementary table 1. These models were then used to predict each testing fold. For each fold the F1 score was calculated. For DESI MSI the algorithm with the highest F1 score, a support vector machine with a polynomial kernel was selected for further model tuning on a single 4/1/5 validation split of the training data. For transmission Raman data a LDA model was selected. A final model was fitted on all the training data. These models were used to predict the test independent test sets. Cosine similarity between spectra were calculated using the cosine function from the coop package [@https://cran.r-project.org/package=coop]. Considering the angle between vectors, rather than magnitude, cosine similarity provides a useful and robust measure of spectral similarity for highly multivariate datasets [@doi:10.1021/acs.analchem.6b02139] 

## Results and discussion

### Acquisition of DESI-MS spectra from tablets

Rich mass spectra were rapidly obtained from each tablet type when held under the DESI sprayer and MS inlet capillary (Figure 1A). DESI-MS spectra from tablet types A and D are dominated by repeating polymeric peaks above *m/z* ~700, indicating the presence of a polymer film coating while spectra from tablet types B and C are less complex, being dominated by  peaks below *m/z* 700. The maximum intensity of the spectra collected in the absence of a tablet (“background”) is lower than for spectra where a tablet is presence. 

The polymeric peak sequences observed in tablet type A and D above *m/z* 700 are distinct from one another with several different peak sequences are observed (Figure 1B). Tablet types A and D both exhibit a clear sequence of peaks spaced by *m/z* ~44 the a signally charged unit difference from \[C~2~H~4~O]^+^. For both tablet types peaks above *m/z* 1000 are most intense. In tablet type A this predominantly consists of isotope clusters separated by *m/z* ~14.68, with peaks separated by *m/z* 0.33, indicating a 3+ charge state of the loss of \[C2H4O]. Conversely, in tablet type D the isotope clusters are separated by *m/z* ~11.01 with peak spacing of *m/z* ~0.25, indicating a 4+ charge state and the loss of \[C~2~H~4~O]. This indicates that while both are coated with a PEG-based polymer, the molecular weight or coating application may differ between the brand name and generic product. 

All three active ingredients were annotated from a mean spectrum within 15 ppm mass accuracy. Boxplots of single scan intensity show distinct differences in active intensity between types (Figure 1C, 1D, 1E). Caffeine is present in tablet types A, B and D and absent from type C. Median intensity is highest for the uncoated tablet type B. Intensity for tablet type C is similar to that in the background. While aspirin is present in tablet types A and D, the detected intensity in type B is high. This may represent an isobaric compound also present in type B or carry over from sampling tablet type A. Paracetamol is present in, and detected in all table types, although is most intense in tablets without a film-coating (types B and C) which may otherwise mask signal from the underlying bulk material. Variance for all actives and tablet types was high, indicating the need for consistent sampling procedures and robust classification approaches. 

### Acquisition of Transmission Raman spectra from tablets 

Mean transmission Raman spectra for each tablet type (Figure 1F) show very similar profiles for tablet types A and D (the film coated aspirin, paracetamol, and caffeine tablets) and between types B (paracetamol and caffeine and C (paracetamol only). Peaks characteristic of each active ingredient are observed (Caffeine: 555 cm^-1^, Paracetamol: 858 cm^-1^, Aspirin: 1192 cm^-1^) [@doi:10.1016/j.vibspec.2007.12.016; @doi:10.3390/pharmaceutics6040651; @doi:10.1016/j.molstruc.2014.10.079]. However, no clear differences between tablets A and D were observed. As expected based on the tablet composition, the predominant spectral features relate to the actives rather than from the coating ingredients. 

![
**Representative spectra from DESI MS and transmission Raman spectroscopy analysis of solid-oral dosage forms**
(A-C) DESI MS results. (A) Mean spectra for tablet types A, B, C & D and background. (B) Mean spectra for tablet types A (teal) and D (pink) for mass range *m/z* 1065 to *m/z* 1090. (C-E) Boxplots for peaks assigned as caffeine (C), aspirin (D) and paracetamol (E) for each tablet type and background. (F-L) Transmission Raman spectroscopy results. (F) Mean spectra for tablet type A-D from training data. Peaks for the active ingredients shown in G-L are highlighted with a vertical line.  (G-L) Mean spectra and (J-L) boxplots for peaks annotated as active ingredients (G & J)  Caffeine, 541 cm^-1^, (H & K) Paracetamol, 847 cm^-1^, and (I & L) Aspirin, 1181 cm^-1^). Boxplots show median (horizontal line), interquartile range (box) and range excluding outliers (whiskers). Points show single scan intensities. 
](https://github.com/adamjtaylor/tablet-classification/raw/main/content/figures/fig1.png "Figure 1"){#fig:spectra}

### Relative spectral similarity

It is notable that for both DESI MS and Transmission Raman data assessment of active ingredients or film coating, or excipients alone cannot robustly separate all tablet types. We can objectively assess the relative overall spectral similarity between and within tablet types by calculating the cosine distance of each spectrum of the same modality from one another. The cosine similarity matrix for DESI MS (Figure 2A) reveals that the highest cosine similarities are between spectra from tablet type D (D vs. D, 0.97 +/- 0.03) and between spectra from tablet type A (A vs. A, 0.96 +/- 0.02). The low standard deviation of cosine similarity within these tablet types indicates the highly reproducible spectra achieved from these samples. Tablet types C and D have a lower mean cosine similarity and higher variance of similarity within their respective tablet types (B vs. B, 0.77 +/- 0.08. C vs. C 0.85 +/- 0.12). Tablet types B and C are relatively alike, with cosine similarity of 0.71. Conversely, tablet types A and D, are relatively dissimilar to one another (0.45 +/- 0.03). 

For Transmission Raman spectroscopy, high cosine similarity is observed within tablet types (all greater than 0.97), However, spectral similarity between tablets A & D is notably higher than for DESI MSI (0.97 +/- 0.01). This is also seen in the high similarity between tables B and C (0.99 +/- 0.01), where the only visible spectral difference is for Caffeine, (541, cm^-1^, present in B, absent in C). All other peaks are visibly identical contributing to the high similarity value. 

The visible differences between mean spectra and differences in cosine similarities suggest that this DESI MSI may be amenable for the training of classification algorithms to classify unseen data, but that transmission Raman spectroscopy may be more challenging. 

![
**Relative spectral similarity and classification performance comparision**
(top row) Cosine similarity matrix for each scan of the training dataset from (A) DESI MS or (B) transmission Raman spectroscopy. (middle row) Cross validation F1 measures for (B) DESI MS and (E) transmission Raman spectroscopy. Bars and labels show mean +/- 1 SD for 10-folds with 10 repeats. (bottom row) Confusion matrix for the test set for (A) DESI MSI classified by a SFM with polynomial kernel or (F) transmission Raman Spectroscopy classified LDA. Colour and labels show proportion of correct classifications. 
](https://github.com/adamjtaylor/tablet-classification/raw/main/content/figures/fig2.png "Figure 2"){#fig:similarity width="75%"}

### Assessment of different classification algorithms

A wide range of classification algorithms are available and have been demonstrated for classification of spectrometric and spectroscopic data. Here we assessed a range of classification algorithms including linear discriminate analysis, tree-based methods, a simple neural network, and support vector machines. A 10-fold cross-validation enables the variance of each algorithm to be assessed. Figure 2B and 2E shows the F1 score of each algorithm for cross-validation for DESI MS and Transmission Raman. The F1 score summarizes the precision and recall of the model with equal weights.  

For DESI MSI All tested algorithms performed well with mean F1 scores above 0.88. 4 algorithms provide a mean F1 score above 0.95, these include the two tree-based methods, random forest and boosted tree. However, the two highest performing algorithms are the support vector machines. The use of a SVM with a polynomial kernel provides a F1 score of 0.992 on the cross-validation training set.

For transmission Raman data a linear discriminant analysis (LDA) model is most robust yielding a F1 measure greater than 0.95. Random forest, naïve Bayes and nearest neighbor models also performed well with F1 measures greater than 0.9 a similar level of performance. LDA cross validation was rapid, with the naïve Bayes model having the longest run time (Figure S1b). Unlike for DESI MS, here a SVM with a polynomial kernel performed less well with a F1 measure of 0.876. 

The best performing models for each analytical technique (DESI: SVM-poly, Transmission Raman: LDA) were therefore taken forward for further exploration and testing. While not a limitation in a the relatively small datasets demonstrated here it is worth noting the range of training times required for 10-fold cross validation with 10 replicates, ranging from ~100 s for Transmission Raman with a boosted tree to ~500 s for DESI MS with naive Bayes (Figure S1). While a search grid for SVM hyperparameters (degree, cost and scale factor) was assessed, the default parameters proved optimal (Supplementary information B, Fig S3). There are no hyperparameters for the LDA. 

### Test set classification performance

#### DESI MS

As a support vector machine with a polynomial kernel provided the highest classification performance in the cross-validation of the training set, a model based on this algorithm was trained using the entire training set. This model preserved 410 variables. This model was used to predict tablet type from each scan of an independent test set. The test set was acquired 1 week after the training set was collected, with the instrument in active use and recalibrated in the intervening period. In the test set, tablets not seen in the training set, but from the same type and batch were held under the DESI source for approximately 5 seconds. Scans were individually annotated for known tablet type based on known acquisition order and in reference to the total ion chromatogram (Figure S3a).  

The trained SVM model was then used to predict the classification of each scan (Figure S3b). The classification algorithm performed well on the test set with an F1 score of 0.956. A confusion matrix for the ground truth vs. the predicted class (Figure 2C) shows the shows that most misclassifications are between the background and each tablet type. Selected correctly predicted spectra (Figure S3e) show notable characteristics, particularly in the polymer peak envelopes seen for tablet types A and D. A misclassification for one tablet type with another only occurs once (Scan 440, Figure S3f), where a scan labelled as tablet type D is misclassified as tablet type A. The spectrum shows two peaks characteristic of the background and a polymer envelope dissimilar to either tablet type demonstrating that classification performance is weak at the start and end of tablet sampling as the tablet is withdrawn from the source. Highlighting misclassifications on the total ion chromatogram (Figure S3c), shows that most misclassifications occur at the end of a tablet being presented to the mass spectrometer. Selected spectra from scans incorrectly predicted as background (Figure S3f, scans 184 and 380) shows base peaks at *m/z* 217.11 and 309.10 which are also seen in the mean spectra of the background (Figure S1a), highlighting the importance of accurate ground truth annotation in the assessment of classification models. 

#### Transmission Raman  

LDA trained on the whole Transmission Raman training set was used to classify an independently acquired test set of transmission Raman data from 24 tablets from the same batch. Classification performance was strong with an F1 score of 0.965 when using LDA (Figure 2F. Here classification is correct for tablet types B and C and A, which are classified correctly despite their high cosine similarity. However, in three cases tablet D misclassified as type A, and in one case type A misclassified as type D. This is somewhat unsurprising as they contain the same active ingredients and amounts, but differ in their film coating, as demonstrated by the notably different polymer profiles seen in the DESI-MS data. 

### Variable importance

#### DESI MS

When assessing the classification performance of algorithms on multidimensional data it is useful to assess the variables that the model has placed importance on. Unlike some classification algorithms such as tree-based methods, support vector machines do not inherently provide a measure of variable importance. We therefore calculated a variance-based variable importance using a feature importance ranking measure (FIRM) approach (2 refs), based on quantifying the relative flatness of each feature. Most variables are seen to have relatively low importance to the model (importance < 0.05), although several variables are prominent in a spectrum of variable importance (Figure 3A). The 30 variables with the highest importance were selected and boxplots of their single scan intensity per tablet type plotted (Figure S5B). Several of these import variables show high intensity for a single class over all others. These include peaks characteristic of the background (*m/z* 588.42 & *m/z* 309.20), tablet type B (*m/z* 693.18, *m/z* 164.13). Other important variables may be of greater intensity in two types (e/g *m/z* 821.8 in A and D, *m/z* 445.04 and B and C), or be present in all but one tablet type (e.g *m/z* 1013.59). 

Considering the importance of each variable and the relative intensity in each class enables and understanding of how the SVM charts a path to accurately divide the classes in multivariate space. 

![
**Variable importance for selected classification models**
(A) FIRM variable importance for SVM-poly classification of DESI MS data. 5 peaks with highest importance are highlighted. (B) Scaling values for each discriminant from LDA of transmission Raman data. Highest absolute loading variables are highlighted with red circles. (B) Boxplots showing LDA scores for the spectra from the transmission Raman training set.
](https://github.com/adamjtaylor/tablet-classification/raw/main/content/figures/fig3.png "Figure 3"){#fig:variable-importance width="75%"}


#### Transmission Raman spectroscopy 

The variable importance of the LDA model was assessed by inspection of the LDA scaling values per wavenumber and component (Figure 3B and S5) and the LDA scores of the training set (Figure 3C). LD1 (proportion of trace: 98.8%) provides wide separation of coated tablet types A and D from uncoated tablets B and C. LD2 (proportion of trace: 0.9 %) broadly separates types C and D from one another. LD3 (proportion of trace: 0.2%) provides some separation between types A and D, although this separation is less distinct.  

LDA scaling spectra highlight key features in the transmission Raman spectra that contribute to the classification. Features with a broad range of Raman shifts contribute to each component. Most of the LDA scaling spectral features are consistent with key active ingredient Raman peaks. For example, the highest scoring peak in LD1 occurs at 1159 cm-1 which corresponds to aspirin C-H ring bending [@doi:10.1016/j.molstruc.2014.10.079]. LD1 provides separation of tablet types A and D from B and C, and since A and D contain aspirin and B and C do not, strong weighting on wavenumbers consistent with aspirin Raman peaks would be expected. Several other LDA scaling spectral features are consistent with aspirin peak positions, such as 380, 786 and 1221 cm-1. Other LDA scaling spectral features are consistent with Raman peaks of several ingredients, for example 1555 cm-1 (LD3) which could correspond with spectral features present in all three active ingredients, paracetamol, aspirin, and caffeine, which have peaks centered at 1560, 1557, and 1554 cm-1 respectively [@doi:10.1016/j.vibspec.2007.12.016; @doi:10.3390/pharmaceutics6040651; @doi:10.1016/j.molstruc.2014.10.079].

### Repeatability and reproducibility of DESI MS 

In the same acquisition as the test set, tablets of type A (Anadin Extra) from a different manufacturing batch number as that analyzed in the training and test sets were profiled. The SVM model correctly classified 51 of 54 scans annotated as the tablet as being of type A (Supplementary figure S5). The three disagreements were between background and tablet type. 

Spectral similarity between acquisitions date and tablet batch was assessed by cosine distance (Figure 5). Cosine distance between both date of acquisition and manufacturing batches were highly similar (Cosine distance >0.9) to the cosine distance of spectra within each data or batch. This suggests that sampling variance is higher than the variance between date of acquisition or manufacturing batch. In this work tablets were held manually, using tweezers. Sample variance may be reduced using a sample mounting system or guide to hold tablets in the same geometry respective to the DESI sprayer during acquisition. 

Additional analysis (Supplementary information A) comparing DESI MSI cross-validation classification performance with reduced peak numbers (Figure S2A) and simulated lower mass resolving power (S2B) further demonstrate the robustness of classification performance for DESI MSI, and its potential application on compact mass spectrometers at-line or in the field. 

## Conclusions

DESI mass spectrometry and transmission Raman spectroscopy are effective methods to acquire characteristic spectral information from solid oral dosage forms containing information about active ingredients and tablet coating components. 
These tools provide complementary information: transmission Raman is slightly biased in sensitivity towards the bulk of the tablet, whereas DESI-MS provides sensitive analysis of the surface coating. 
A range of machine learning algorithms were found to be capable of classifying tablet type with high precision and recall. 
Of these, support vector machines showed the strongest performance for DESI-MSI, while LDA was the most effective for transmission Raman data.  

DESI-based classification was primarily based on differences in the tablet coatings, whereas transmission Raman was more sensitive to differences in the active pharmaceutical ingredients due to their higher total content. 
Therefore, it may be advantageous to combine these two complementary analytical methods. 
Raman spectroscopy’s non-destructive nature makes it potentially more suitable for in-line analysis than DESI-MS, the destructive nature, even if minimally, of which makes it unsuitable for tablets remaining in the supply chain. 
Classification performance was retained on datasets of reduced peak number and simulated reduced mass resolving power, indicating the robustness of this approach and its potential applicability to compact mass spectrometers suitable for deployment in counterfeiting, QA/QC, or production line environments.  



## Acknowledgements 

The authors thank Ariadna Gonzalez and Caterina Minelli (NPL) for helpful discussion and guidance throughout the project. This work was funded by the UK Government’s Department for Business, Energy, and Industrial Strategy (BEIS), and the National Measurement System as part of NPL’s internal cross-theme project “Innovative Medicines Manufacturing.”  

## Contributions 

AT, JB and NB conceived and planned the experiments. AT and AB acquired DESI MS data. NB acquired transmission Raman spectroscopy data. AT performed preprocessing of DESI MS data. DT performed preprocessing of transmission Raman data. AT performed the classification and variable importance analysis. AT, DT, NB and JB interpreted the results. AT, AD, DT, JB and NB wrote the manuscript. All authors discussed the results contributed to the final manuscript.

## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>


## Supplementary information {.page_break_before}

### Notes

#### Note A. Reducing peaks and down binning data for DESI MS 
Given the notable spectra differences observed for DESI MS, it is unsurprising that strong classification performance is achieved. In this model comparison we included all detected peaks in the algorithm (although some will be removed automatically as they correlate strongly with other variables. To assess the number of features required to maintain good classification performance we performed 10-fold cross validation using an SVM with a polynomial kernel and default parameters (degree: 1, cost: 0.1, scale factor: 1) on datasets in which fewer peaks were selected (from top 1200 to top 5 peaks). F1 metric was seen to be maintained above 0.97 (Figure S2B), but starts to drop off below 100 peaks, with 5 peaks providing a mean F1 score of 0.61 with a greatly increased variance. 

Potential applications of tablet classification may demand the mass spectrometer to be located outside of an analytical chemistry laboratory, either at-line in a manufacturing environment, in an on-site QA/QC lab, on in the field. In these applications the use of a Q-ToF mass spectrometer may not be suitable due to size or cost. Compact, field-deployable mass spectrometers such as ion traps or single quadrupoles may offer reduced mass resolving power. To simulate reduced instrument performance, data were down binned at increasing bin width. No reduction in classification performance is observed when binning at 1 Dalton, simulating single quadrupole mass resolving power (Figure S2B). Classification performance is maintained even at 2 Dalton binning, indicating the applicability of this approach to low mass resolving power data from compact or portable mass spectrometers. 

#### Note B. Model tuning
The hyperparameters of the SVM were tuned on the validation split of the training set over a regular grid with five levels of degree (1 to 5), cost (0.001 to 1) and scale factor (0.001 to 1). All variables and 0.01 Da binning. The F1 measure of each combination is shown in Figure S3. First-degree (linear) and third-degree polynomials with cost and scale factors above 0.001 show high F1 score (all = 1.0) for the validation split. As the default SVM parameters in the kernlab implementation are within this range (degree: 1, cost: 1, scale factor: 1) they were selected to fit a final model using the whole training set. 

For Transmission Raman data the best performing classification approach, a linear discriminant analysis, as implemented by the MASS package has no parameters to optimize beyond the prior which was here set to the equal type probability. This would influence the suitability of the LDA for applications in cases such as defect or counterfeit detection where class probability is expected to be unbalanced with an unknown prior. 

### Figures {.page_break_before}

![
Timings for 10-fold cross validation with 10 replicates for selected classification algorithms for DESI MS (red) and transmission Raman spectroscopy (teal) training data.
](https://github.com/adamjtaylor/tablet-classification/raw/main/content/figures/fig_timing.png "S1"){#fig:timing tag="S1" width="62%"}

![
Exploration of reduced peak number (A) and down-binning (B) for DESI MS classification.  
](https://github.com/adamjtaylor/tablet-classification/raw/main/content/figures/fig_npeaks_downbin.png "S2"){#fig:downbin tag="S2" width="62%"}

![
Model tuning grid for SVM-polynomial kernel for DESI MS data. 
](https://github.com/adamjtaylor/tablet-classification/raw/main/content/figures/fig_tuning.png "S3"){#fig:tuning tag="S3" width="75%"}

![
**Classification of an independent test set of tablets by DESI MS and an SVM**  
 (a) Total ion chromatogram (TIC) plot showing the ground truth labelling per scan for four sampling events per tablet type. Labelling was performed manually in reference to known sampling order and TIC. (b) TIC plot showing tablet type predicted by the SVM for each scan. (c) TIC plot highlighting prediction accuracy per scan (correct: green circles, incorrect: pink triangles). (d) Confusion matrix for each scan of the test set, classified by the SVM. Colour and labels show proportion of correct classifications. (e-f) Spectra for selected scans (labelled in c) that are correctly (e). or incorrectly classified (f).](https://github.com/adamjtaylor/tablet-classification/raw/main/content/figures/fig_desi_validation_supplementary.png "S4"){#fig:tuning tag="S4" width="75%"}

![
Cosine similarity matrix for DESI MS sampling of tablet type A from two batches on two days of analysis.
](https://github.com/adamjtaylor/tablet-classification/raw/main/content/figures/fig_repliacate_similarity.png "S5"){#fig:replicate_similarity tag="S5" width="50%"}

![
Variable importance plot for SVM with polynomial kernel trained on DESI MS data. Peaks with the 30 highest variable importance are highlighted by a black dot). (b) Boxplots for peaks with the 30 highest variable importance values (Line: median, box: Q2 & Q4, whiskers: range excluding outliers, points: single scan intensities).
](https://github.com/adamjtaylor/tablet-classification/raw/main/content/figures/fig_desi_importance.png "S6"){#fig:desi_vip tag="S6" width="75%"}

![
(a) Spectra of LDA scaling values for each discriminant. Selected variables are highlighted with red circles. Boxplots showing LDA scores for the spectra contained in the training set. (c & d) Boxplots of transmission Raman intensity for the wavenumber bins with the two highest (c) and lowest (d) scaling values per discriminant. Boxplots show mean (bar), first and third quartiles (bar) and range between the lowest and highest values no further than 1.5 times the IQR from the box. Points show individual observations. 
](https://github.com/adamjtaylor/tablet-classification/raw/main/content/figures/fig_tr_importance.png "S7"){#fig:tr_vip tag="S7" width="75%"}
