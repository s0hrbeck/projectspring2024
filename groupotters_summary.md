# Analysing the PAD-UFES-20 dataset 

## Overview of the dataset contents 

The provided data is from a Brazilian nonprofit program that provides free skin lesion treatment. Collected along with the Programa de Assistência Dermatológica e Cirurgica (PAD) at Universidade Federal do Espírito Santo (UFES-Brazil). 

The entire dataset consists of 2,298 samples, of which our sample subset contains 127 samples. The samples are of a clinical image, alongside up to 26 clinical features related to the image as well as some more general patient information for the person whose skin contains the lesion.2 There are occasionally multiple images related to the same lesion, as well as multiple images that relate to the same person. This makes it important to differentiate a sample in this dataset as being representative of an image, as opposed to a sample being a specified patient, or even just a specific lesion belonging to a patient. 

There are seven types of lesions presented in the dataset: Basal Cell Carcinoma (BCC), Squamous Cell Carcinoma (SCC), Actinic Keratosis (ACK), Seborrheic Keratosis (SEK), Bowen’s disease (BOD), Melanoma (MEL), and Nevus (NEV). The clinical definition considers Bowen’s disease as an early type of skin cancer, which may develop into an SCC if left alone. Therefore, we consider BOD as SCC in situ, and thus the dataset clusters them together. This results in six different skin lesions in the dataset; three skin cancers (BSS, MEL, and SCC) and three skin diseases (ACK, NEV, and SEK) 

Due to the method of clinical diagnosis, the skin cancers generally being biopsy proven, whilst the skin diseases being diagnosed through consensus of clinical experts; 58% of the samples in the dataset are biopsy proven.1 

## Background to the diagnoses presented

The presented diagnoses have been split into two groups: skin cancers and skin diseases.

The three skin diseases are: Actinic Keratosis (ACK), Seborrheic Keratosis (SEK), and Nevus (NEV). These tend to be diagnosed through consensus of a group of dermatologists.1

ACK is also known as solar keratosis, due to its main cause coming from UV-induced DNA damage to the skin. They are the most common lesions with potential to become malignant, in rare cases progressing to SCC. ACK is mostly seen in fair-skinned people (Fitzpatrick types I and II). Due to it being a precursor to SCC, they can share histological features (making a purely visual diagnosis more difficult)3

SEK, also referred to as Seborrheic warts, are common, benign hyperkeratotic skin lesions. Cause isn’t fully understood, they may arise from sun exposure given the typical distribution of presentations, as well as possible genetic inheritance or mutations. SEK is extremely common, 90% in patients over the age of 60. Warts tend to appear in plural rather than individually. Pigmentation is often in stark contrast to skin tone, usually presenting as deeply pigmented, but can be paler. The borders of lesions tend to be clearly defined. There is largely little or no clinical danger from SEK lesions, other than functional discomfort or dermatological dislike. MEL can arise from SEK, but this is rare.4

NEV are extremely common and can be divided into many subtypes and groups. Some types are so prevalent, that they are often not considered to be an abnormality. The most common are Intradermal naevi, more commonly known as moles. Naevi tend to have a similar level of pigmentation to the surrounding skin, can be raised from the surface of the skin to various degrees, and most commonly stay below 1cm in diameter. They may be associated with hair growth, particularly with advanced aged. They are generally only clinically investigated when a differential diagnosis is suspected.5

## Critique of data

## References

1. Pacheco, Andre G. C.; Lima, Gustavo R.; Salomão, Amanda S.; Krohling, Breno; Biral, Igor P.; de Angelo, Gabriel G. ; Alves Jr, Fábio  C. R. ; Esgario, José G. M.; Simora, Alana C. ; Castro, Pedro B. C. ; Rodrigues, Felipe B.; Frasson, Patricia H. L. ; Krohling, Renato A.; Knidel, Helder ; Santos, Maria C. S. ; Espírito Santo, Rachel B.; Macedo, Telma L. S. G.; Canuto, Tania R. P. ; de Barros, Luíz F. S. (2020), “PAD-UFES-20: a skin lesion dataset composed of patient data and clinical images collected from smartphones”, Mendeley Data, V1, doi: 10.17632/zr7vgbcyr2.1 

2. Andre G.C. Pacheco, Renato A. Krohling, The impact of patient clinical information on automated skin cancer detection, Computers in Biology and Medicine, Volume 116, 2020, 103545, ISSN 0010-4825, https://doi.org/10.1016/j.compbiomed.2019.103545.

3.	https://patient.info/doctor/actinic-keratosis-pro

4.	https://patient.info/doctor/seborrhoeic-wart

5.	https://patient.info/doctor/intradermal-and-compound-naevi
