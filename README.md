# DeepNeo
identification of immunogenic neoepitopes
## DeepNeo is a tool for predicting the immunogenicity of peptide-MHC pairs as well as physical peptide-MHC binding.

Neoantigen, or peptides containing somatic mutations that are presented by MHC molecules, are known to be important in immunity. However, most neoantigen predicting tools only consider binding of peptide and MHC molecule regardless of T cell reactivity. Although MHC binding is necessary, it is not sufficient to elicit T cell response. To bridge this gap, we built a model that captures the structural properties of immunogenic peptide-MHC complexes using preferential amino acid interactions. DeepNeo supports prediction for two species, human and mouse, for both MHC class I and MHC class II.


References : 

“Predicting clinical benefit of immunotherapy by antigenic or functional mutations affecting tumour immunogenicity” Nature Communications (2020)

“MHC II immunogenicity shapes the neoepitope landscape in human tumors” Nature Genetics (2023)

"DeepNeo: a webserver for predicting immunogenic neoantigens" Nucleic Acids Research (2023)


## Update:  

DeepNeo-v2 is now available! This repo provides source code only for DeepNeo-v1. We recommend using web server version.
Webserver for an updated version of DeepNeo is available at https://deepneo.net

*The webserver is currently undergoing maintenance. It will be available again on 6/6/2023

![alt text](deepneo-web.png)


## Download and install:

Please download this github repo.
The code can be run with Python=2.7 and Theano=1.0.4


