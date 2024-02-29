# Analysing the PAD-UFES-20 dataset 

## Overview of the dataset contents 

The provided data is from a Brazilian nonprofit program that provides free skin lesion treatment. Collected along with the Programa de Assistência Dermatológica e Cirurgica (PAD) at Universidade Federal do Espírito Santo (UFES-Brazil). 

The entire dataset consists of 2,298 samples, of which our sample subset contains 127 samples. The samples are of a clinical image, alongside up to 26 clinical features related to the image as well as some more general patient information for the person whose skin contains the lesion.2 There are occasionally multiple images related to the same lesion, as well as multiple images that relate to the same person. This makes it important to differentiate a sample in this dataset as being representative of an image, as opposed to a sample being a specified patient, or even just a specific lesion belonging to a patient. 

There are seven types of lesions presented in the dataset: Basal Cell Carcinoma (BCC), Squamous Cell Carcinoma (SCC), Actinic Keratosis (ACK), Seborrheic Keratosis (SEK), Bowen’s disease (BOD), Melanoma (MEL), and Nevus (NEV). The clinical definition considers Bowen’s disease as an early type of skin cancer, which may develop into an SCC if left alone. Therefore, we consider BOD as SCC in situ, and thus the dataset clusters them together. This results in six different skin lesions in the dataset; three skin cancers (BSS, MEL, and SCC) and three skin diseases (ACK, NEV, and SEK) 

Due to the method of clinical diagnosis, the skin cancers generally being biopsy proven, whilst the skin diseases being diagnosed through consensus of clinical experts; 58% of the samples in the dataset are biopsy proven.1 

## Background to the diagnoses presented


## Critique of data

## References
