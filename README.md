# awesome-single-cell-foundation

## Why creating a repo focusing on single cell foundation models?

The evolution of single-cell biology is intersecting with the advancements of artificial intelligence and machine learning. The rise of foundation models, especially large language networks, suggests potential deeper insights into cellular mechanisms. Anticipating a future where a foundational cell model integrates molecular, spatial, and morphometric details offers a promising avenue for holistic biological understanding. This convergence of technology and biology brings forth exciting opportunities to enhance our knowledge of cellular states and their implications in health and disease.

**Quote from Fabian Theis:** As modern language models enable text generation as answer to a query, we will be able to query a cellular foundation model about unseen, new cell states across health and disease.



## Single cell RNA sequencing (scRNA-seq)

- **SCHYENA**: FOUNDATION MODEL FOR FULL-LENGTH SINGLE-CELL RNA-SEQ ANALYSIS IN BRAIN [paper](https://arxiv.org/pdf/2310.02713.pdf), [code](https://github.com/scHyena2023/scHyena)

- **GeneCompass**: Deciphering Universal Gene Regulatory Mechanisms with Knowledge-Informed Cross-Species Foundation Model [paper](https://www.biorxiv.org/content/10.1101/2023.09.26.559542v1), [code](https://github.com/xCompass-AI/GeneCompass)

- **Geneformer**: Transfer learning enables predictions in network biology [paper](https://www.nature.com/articles/s41586-023-06139-9), [code](https://huggingface.co/ctheodoris/Geneformer)

- **scGPT**: Towards Building a Foundation Model for Single-Cell Multi-omics Using Generative AI [paper](https://www.biorxiv.org/content/10.1101/2023.04.30.538439v1), [code](https://github.com/bowang-lab/scGPT)

- **scBert**: scBERT as a large-scale pretrained deep language model for cell type annotation of single-cell RNA-seq data [paper](https://www.nature.com/articles/s42256-022-00534-z), [code](https://github.com/TencentAILabHealthcare/scBERT)

- **scFoundation**: Large Scale Foundation Model on Single-cell Transcriptomics [paper](https://www.biorxiv.org/content/10.1101/2023.05.29.542705v3), [code](https://github.com/biomap-research/scFoundation)

- **tGPT**: Generative pretraining from large-scale transcriptomes for single-cell deciphering [paper](https://www.sciencedirect.com/science/article/pii/S2589004223006132), [code](https://github.com/deeplearningplus/tGPT)

- **CellLM**: Large-Scale Cell Representation Learning via Divide-and-Conquer Contrastive Learning [paper](https://arxiv.org/pdf/2306.04371.pdf), [code](https://github.com/PharMolix/OpenBioMed/blob/main/README.md)

- **Exceiver**: A single-cell gene expression language model [paper](https://arxiv.org/pdf/2210.14330.pdf), [code](https://github.com/keiserlab/exceiver)

- **scTranslator**: Training on large-scale RNA data to impute protein abundance [paper](https://t.co/DHRtCmzaGK), [code](https://t.co/TC0OCOc0q7)

- **SCimilarity**: Scalable querying of human cell atlases via a foundational model reveals commonalities across fibrosis-associated macrophages [paper](https://www.biorxiv.org/content/10.1101/2023.07.18.549537v3), [code](https://github.com/Genentech/scimilarity)



## Spatially-resolved Transcriptomic (SRT)

- **CellPLM**: Pre-training of Cell Language Model Beyond Single Cells [paper](https://www.biorxiv.org/content/10.1101/2023.10.03.560734v1.full.pdf), [code](https://github.com/OmicsML/CellPLM)


## Paired  scATAC-seq and scRNA-seq

- **GET**: a foundation model of transcription across human cell types [paper](https://www.biorxiv.org/content/10.1101/2023.09.24.559168v1.full), [code](https://github.com/GET-Foundation)



## Multi-modality (Incorporating Text)

- **BioTranslator**: Multilingual translation for zero-shot biomedical classification using BioTranslator [paper](https://www.nature.com/articles/s41467-023-36476-2), [code](https://github.com/HanwenXuTHU/BioTranslatorProject)

- **GENEPT**: A SIMPLE BUT HARD-TO-BEAT FOUNDATION MODEL FOR GENES AND CELLS BUILT FROM CHATGPT [paper](https://www.biorxiv.org/content/10.1101/2023.10.16.562533v1), [code](https://github.com/yiqunchen/GenePT)

- **BioMedGPT**: Open Multimodal Generative Pre-trained Transformer for BioMedicine [paper](https://arxiv.org/abs/2308.09442), [code](https://github.com/PharMolix/OpenBioMed)

## Biomedical Test Only

- **BioLinkBERT**: Pretraining Language Models with Document Links [paper](https://arxiv.org/pdf/2203.15827.pdf), [code](https://github.com/michiyasunaga/LinkBERT)

- **BioGPT**: generative pre-trained transformer for biomedical text generation and mining [paper](https://arxiv.org/pdf/2210.10341.pdf), [code](https://github.com/microsoft/BioGPT)

- **BioBERT**: a pre-trained biomedical language representation model for biomedical text mining [paper](https://arxiv.org/pdf/1901.08746.pdf), [code](https://github.com/dmis-lab/biobert)

- **PubMedBERT**: Domain-specific language model pretraining for biomedical natural language processing [paper](https://arxiv.org/pdf/2007.15779.pdf), [code](https://huggingface.co/microsoft/BiomedNLP-PubMedBERT-base-uncased-abstract)


# Single modality other than Single Cell

## Protein Sequence Only

- **ESM-2**: Language models of protein sequences at the scale of evolution enable accurate structure prediction [paper](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1.full.pdf), [code](https://github.com/facebookresearch/esm)

- **Prottrans**: Toward understanding the language of life through self-supervised learning [paper](https://arxiv.org/abs/2007.06225), [code](https://github.com/agemagician/ProtTrans)


- **ProGEN**: Large language models generate functional protein sequences across diverse families [paper](https://www.nature.com/articles/s41587-022-01618-2), [code](https://github.com/salesforce/progen)

- **ProtGPT2**: ProtGPT2 is a deep unsupervised language model for protein design [paper](https://www.biorxiv.org/content/10.1101/2022.03.09.483666v1), [code](https://huggingface.co/nferruz/ProtGPT2)

- **ZymCTRL**: a conditional language model for the controllable generation of artificial enzymes [paper](https://www.mlsb.io/papers_2022/ZymCTRL_a_conditional_language_model_for_the_controllable_generation_of_artificial_enzymes.pdf), [code](https://huggingface.co/AI4PD/ZymCTRL)

## DNA Sequence Only

- **GPN**: DNA language models are powerful predictors of genome-wide variant effects [paper](https://www.pnas.org/doi/10.1073/pnas.2311219120), [code](https://github.com/songlab-cal/gpn)

- **Enformer***: Effective gene expression prediction from sequence by integrating long-range interactions [paper](https://www.biorxiv.org/content/10.1101/2021.04.07.438649v1), [code](https://github.com/deepmind/deepmind-research/tree/master/enformer)

- **DNABERT**: pre-trained Bidirectional Encoder Representations from Transformers model for DNA-language in genome [paper](https://www.biorxiv.org/content/10.1101/2020.09.17.301879v1), [code](https://github.com/jerryji1993/DNABERT)

- **Nucleotide Transformer**: The nucleotide transformer: Building and evaluating robust foundation models for human genomics [paper](https://www.biorxiv.org/content/10.1101/2023.01.11.523679v1), [code](https://github.com/instadeepai/nucleotide-transformer)

- **Hyenadna**: Long-range genomic sequence modeling at single nucleotide resolution [paper](https://arxiv.org/pdf/2306.15794), [code](https://github.com/HazyResearch/hyena-dna)

- **GenSLMs**: Genome-scale language models reveal sars-cov-2 evolutionary dynamics [paper](https://www.biorxiv.org/content/10.1101/2022.10.10.511571v1), [code](https://github.com/ramanathanlab/genslm)

- **gLM**: Genomic language model predicts protein co-regulation and function[paper](https://www.biorxiv.org/content/10.1101/2023.04.07.536042v2), [code](https://github.com/y-hwang/gLM)


## RNA Sequence only
- **RNA-FM**: Interpretable RNA Foundation Model from Unannotated Data for Highly Accurate RNA Structure and Function Predictions [paper](https://arxiv.org/pdf/2204.00300.pdf), [code](https://github.com/ml4bio/RNA-FM)

# Benchmarking

- Assessing the limits of zero-shot foundation models in single-cell biology [paper](https://www.biorxiv.org/content/10.1101/2023.10.16.561085v1.full.pdf), [code](https://github.com/microsoft/zero-shot-scfoundation)


- **scEval**: Evaluating the Utilities of Large Language Models in Single-cell Data Analysis [paper](https://www.biorxiv.org/content/10.1101/2023.09.08.555192v3.full.pdf), [code](https://github.com/HelloWorldLTY/scEval)