# **“Quantitative Structure-Activity Relationship in Cancer”**

## **Introduction:**

Quantitative Structure-Activity Relationship (QSAR) model, as the name implicates, uses mathematical frameworks to correlate structure with the activity of compounds. The output of this step is machine-readable and is used to predict the activity of new compounds. By definition, a QSAR is a computational model that is used to predict the activity of compounds by analyzing the relationship between the structure and activity of known compounds. By knowing the activity of unknown compounds, we can develop new drugs against diseases, such as cancer.

## **Cancer:**

Cancer is a heterogenous disease that spreads through cell proliferation and metastasis. The mode of action of drugs against cancer is primarily by attacking the mutated proteins expressed in a type of cancer, that is responsible for cell proliferation. Developing novel drugs for effective control of cell proliferation and metastasis is important.

## **Importance of computer-aided drug discovery:**

Traditional drug discovery typically takes 10-15 years and around 2 billion USD to become available in the market <!--[if supportFields]><span style='mso-element:
 field-begin'></span><span style='mso-ansi-language:EN-US'><span
 style='mso-spacerun:yes'> </span></span><span lang=EN-US style='mso-ansi-language:
 EN-US'>CITATION Hug11 \l 1033 </span><span style='mso-element:field-separator'></span><![endif]-->(Hughes JP, 2011)<!--[if supportFields]><span
 style='mso-element:field-end'></span><![endif]-->. Integration of computational technologies in the drug discovery process can save us from spending a great amount of money and time. QSAR is primarily used in the preclinical phase of drug discovery that filters compounds with optimized pharmacokinetic profile, and with the potential to produce therapeutic effect before entering the clinical phase.

## **Steps in a QSAR model:**

The QSAR is composed of following steps:

### 1. **Data collection:** 
Compound data is retrieved from chemical database, such as, ChEMBL. The data includes structural information, and biological activities (IC50 or KD50, bioassay type etc.

### 2. **Filtration:** 
This data is then filtered using only those parameters that we need such as, choosing assay type as “binding” and activity type only “IC50”.

### 3. **Descriptor calculation:** 
Descriptors are numerical values that are used to describe the properties of compounds such as atom count, connectivity, auto correlation, molecular weight etc. Descriptors can be 2D (topological, arrangement of atoms) and 3D (geometrical, obtained from 3D coordinates of atoms). <!--[if supportFields]><span style='mso-element:field-begin'></span><span
 style='mso-ansi-language:EN-US'><span style='mso-spacerun:yes'> </span></span><span
 lang=EN-US style='mso-ansi-language:EN-US'>CITATION Dan16 \l 1033 </span><span
 style='mso-element:field-separator'></span><![endif]-->(Danishuddin, 2016,)<!--[if supportFields]><span
 style='mso-element:field-end'></span><![endif]-->

### 4. **Molecular Fingerprints:** 
Encoded in a binary digit format, fingerprints are used to label a compound’s structural properties. These fingerprints for each molecule are generated in this step.&#x20;

### 5. **Machine learning employment:** 
Machine learning algorithms, such as, linear regression, random forest, support vector machines, or neural networks are developed using the data to correlate these descriptors with biological activities. A predictive model is thus created on the calculated descriptors to predict the activity of new compounds by learning from the known ones.

## **Example:**

One notable example of development of a QSAR model is by <!--[if supportFields]><span style='mso-element:
 field-begin'></span><span style='mso-ansi-language:EN-US'><span
 style='mso-spacerun:yes'> </span></span><span lang=EN-US style='mso-ansi-language:
 EN-US'>CITATION Suv181 \l 1033 </span><span style='mso-element:field-separator'></span><![endif]-->(Suvannang, 2018)<!--[if supportFields]><span
 style='mso-element:field-end'></span><![endif]-->. A large scale QSAR study aiding in the development of potent inhibitors against estrogen receptor alpha was conducted. They used molecular fingerprints as a descriptor type because of its ability to extensively label structural properties of compounds using mathematical values. Their QSAR model can be used as a filter to screen potent compounds against ER-alpha receptors in breast cancer.

## **Conclusion:**

QSAR is a robust tool in cancer drug discovery that enables the prediction of compound activity and development of new therapeutic agents. The main benefit of using QSAR is that it employs computational power for a vast chemical data, thus reducing time and cost associated with drug development.


## **References:**

1. Danishuddin, A. U. (2016). Descriptors and their selection methods in QSAR analysis: paradigm for drug design. _Drug Discovery Today_.

2. Hughes, J. P., Rees, S. (2011). Principles of early drug discovery. _Br J Pharmacol_.

3. Suvannang, N. P. (2018). Probing the origin of estrogen receptor alpha inhibition via large-scale QSAR study. _RSC Advances_.
 

 

 
