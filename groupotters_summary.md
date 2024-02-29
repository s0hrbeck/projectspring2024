# Analysing the PAD-UFES-20 dataset 

## Overview of the dataset contents 

The provided data is from a Brazilian nonprofit program that provides free skin lesion treatment. Collected along with the Programa de Assistência Dermatológica e Cirurgica (PAD) at Universidade Federal do Espírito Santo (UFES-Brazil). 

The entire dataset consists of 2,298 samples, of which our sample subset contains 127 samples. The samples are of a clinical image, alongside up to 26 clinical features related to the image as well as some more general patient information for the person whose skin contains the lesion.<sup>2</sup> There are occasionally multiple images related to the same lesion, as well as multiple images that relate to the same person. This makes it important to differentiate a sample in this dataset as being representative of an image, as opposed to a sample being a specified patient, or even just a specific lesion belonging to a patient. 

There are seven types of lesions presented in the dataset: Basal Cell Carcinoma (BCC), Squamous Cell Carcinoma (SCC), Actinic Keratosis (ACK), Seborrheic Keratosis (SEK), Bowen’s disease (BOD), Melanoma (MEL), and Nevus (NEV). The clinical definition considers Bowen’s disease as an early type of skin cancer, which may develop into an SCC if left alone. Therefore, we consider BOD as SCC in situ, and thus the dataset clusters them together. This results in six different skin lesions in the dataset; three skin cancers (BSS, MEL, and SCC) and three skin diseases (ACK, NEV, and SEK) 

Due to the method of clinical diagnosis, the skin cancers generally being biopsy proven, whilst the skin diseases being diagnosed through consensus of clinical experts; 58% of the samples in the dataset are biopsy proven.<sup>1</sup> 

## Background to the diagnoses presented

The presented diagnoses have been split into two groups: skin cancers and skin diseases.

The three skin diseases are: Actinic Keratosis (ACK), Seborrheic Keratosis (SEK), and Nevus (NEV). These tend to be diagnosed through consensus of a group of dermatologists.<sup>1</sup>

ACK is also known as solar keratosis, due to its main cause coming from UV-induced DNA damage to the skin. They are the most common lesions with potential to become malignant, in rare cases progressing to SCC. ACK is mostly seen in fair-skinned people (Fitzpatrick types I and II). Due to it being a precursor to SCC, they can share histological features (making a purely visual diagnosis more difficult)<sup>3</sup>

SEK, also referred to as Seborrheic warts, are common, benign hyperkeratotic skin lesions. Cause isn’t fully understood, they may arise from sun exposure given the typical distribution of presentations, as well as possible genetic inheritance or mutations. SEK is extremely common, 90% in patients over the age of 60. Warts tend to appear in plural rather than individually. Pigmentation is often in stark contrast to skin tone, usually presenting as deeply pigmented, but can be paler. The borders of lesions tend to be clearly defined. There is largely little or no clinical danger from SEK lesions, other than functional discomfort or dermatological dislike. MEL can arise from SEK, but this is rare.<sup>4</sup>

NEV are extremely common and can be divided into many subtypes and groups. Some types are so prevalent, that they are often not considered to be an abnormality. The most common are Intradermal naevi, more commonly known as moles. Naevi tend to have a similar level of pigmentation to the surrounding skin, can be raised from the surface of the skin to various degrees, and most commonly stay below 1cm in diameter. They may be associated with hair growth, particularly with advanced aged. They are generally only clinically investigated when a differential diagnosis is suspected.<sup>5</sup>

The three skin cancers are: Basal Cell Carcinoma (BCC), Squamous Cell Carcinoma (SCC), and Melanoma (MEL). These are diagnosed via biopsy.<sup>1</sup> 

BCC is the most common type of carcinoma worldwide.<sup>6</sup> There are various risk factors, such as sun exposure, lighter skin types, increased age, and genetic predisposition etc. Lesions begin small, translucent, and have raised areas covered by small blood vessels. Later they can present in various ways. Nodular types are visually an exaggerated presentation of early BCC lesions commonly on the face. Superficial; which tend to present in plural, be larger and slowly grow over time. Morphoeic; usually found on the area in the face between the eyes and lips, characterised by thickened yellowish plaques. Pigmented; brown, blue or greyish in colour, seen more often in patients with darker skin tones. Basosquamous; as the name suggests, this type is a mix of BCC and SCC.<sup>7</sup> 

SCC is the second most common skin cancer (behind BCC). Incidence is higher in men, rises with age, and with ultraviolet radiation exposure. Lesions vary widely in clinical appearance, they can appear as a small nodule that enlarges, as the centre of the nodule becomes a pitted open wound, from which bleeding can occur.<sup>8</sup> 

MEL is difficult to visually differentiate from other lesions, which leads to biopsy proven diagnosis after clinician suspicion. MEL grows in areas of fresh skin, beginning in a similar fashion to the more common moles (benign melanocytic naevi). Melanomas can be characterised by their growth pattern, there are four clinical types of skin melanoma, which all show growth either laterally or vertically (or both) through the skin and surrounding tissue. Similarly to other lesions, MEL risk is increased by sun exposure, lighter skin types, and age amongst other factors. Clinical referral for biopsy is based on seven factors: change in size, shape and colour, size more than 7mm, inflammation, oozing and sensation changes.<sup>9</sup> 

## Critique of data

## References

1. Pacheco, Andre G. C.; Lima, Gustavo R.; Salomão, Amanda S.; Krohling, Breno; Biral, Igor P.; de Angelo, Gabriel G. ; Alves Jr, Fábio  C. R. ; Esgario, José G. M.; Simora, Alana C. ; Castro, Pedro B. C. ; Rodrigues, Felipe B.; Frasson, Patricia H. L. ; Krohling, Renato A.; Knidel, Helder ; Santos, Maria C. S. ; Espírito Santo, Rachel B.; Macedo, Telma L. S. G.; Canuto, Tania R. P. ; de Barros, Luíz F. S. (2020), “PAD-UFES-20: a skin lesion dataset composed of patient data and clinical images collected from smartphones”, Mendeley Data, V1, doi: 10.17632/zr7vgbcyr2.1 

2. Andre G.C. Pacheco, Renato A. Krohling, The impact of patient clinical information on automated skin cancer detection, Computers in Biology and Medicine, Volume 116, 2020, 103545, ISSN 0010-4825, https://doi.org/10.1016/j.compbiomed.2019.103545.

3.	https://patient.info/doctor/actinic-keratosis-pro

4.	https://patient.info/doctor/seborrhoeic-wart

5.	https://patient.info/doctor/intradermal-and-compound-naevi

6.	Dika E, Scarfì F, Ferracin M, Broseghini E, Marcelli E, Bortolani B, Campione E, Riefolo M, Ricci C, Lambertini M. Basal Cell Carcinoma: A Comprehensive Review. Int J Mol Sci. 2020 Aug 4;21(15):5572. doi: 10.3390/ijms21155572. PMID: 32759706; PMCID: PMC7432343.
   
7.	https://patient.info/doctor/basal-cell-carcinoma

8.	https://patient.info/doctor/squamous-cell-carcinoma-of-skin

9.	https://patient.info/doctor/malignant-melanoma-of-skin 
