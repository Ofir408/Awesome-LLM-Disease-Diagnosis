# Awesome-LLM-Disease-Diagnosis
"Large Language Models for Disease Diagnosis: A Scoping Review" (npj Artificial Intelligence 2025)



# RAG


## Disease diagnosis


| Title                                                                                                                 | Published Year | Journal                                 | Task                     | Input Data Modality               | LLM Technique Type                            |
|-----------------------------------------------------------------------------------------------------------------------|----------------|-----------------------------------------|--------------------------|------------------------------------|-----------------------------------------------|
| Optimization of hepatological clinical guidelines interpretation by large language models: a retrieval augmented generation-based framework | 2024           | npj Digital Medicine                   | Disease diagnosis        | Text                               | RAG (corpus)                                  |
| Explanatory argumentation in natural language for correct and incorrect medical diagnoses                             | 2024           | Journal of Biomedical Semantics        | Disease diagnosis        | Text, Image                        | RAG (database)                                |
| ECG Semantic Integrator (ESI): A Foundation ECG Model Pretrained with LLM-Enhanced Cardiological Text                 | 2024           | arXiv                                  | Disease diagnosis        | Time series, Text                  | RAG (corpus)                                  |
| Beyond Direct Diagnosis: LLM-based Multi-Specialist Agent Consultation for Automatic Diagnosis                        | 2024           | arXiv                                  | Disease diagnosis        | Text                               | RAG (database)                                |
| Diagnosis Assistant for Liver Cancer Utilizing a Large Language Model with Three Types of Knowledge                   | 2024           | arXiv                                  | Disease diagnosis        | Image, Text                        | RAG (database), Prompt (CoT)                 |
| Guiding clinical reasoning with large language models via knowledge seeds                                             | 2024           | arXiv                                  | Disease diagnosis        | Text                               | RAG (knowledge graph)                         |
| Large Language Model-informed ECG Dual Attention Network for Heart Failure Risk Prediction                            | 2024           | arXiv                                  | Disease diagnosis        | Time series, Text                  | RAG (database)                                |
| Dermacen Analytica: A Novel Methodology Integrating Multi-Modal Large Language Models with Machine Learning in tele-dermatology | 2024           | arXiv                                  | Disease diagnosis        | Image, Text                        | RAG (database)                                |
| Autonomous artificial intelligence agents for clinical decision making in oncology                                   | 2024           | arXiv                                  | Disease diagnosis        | Text                               | RAG (database)                                |
| medIKAL: Integrating Knowledge Graphs as Assistants of LLMs for Enhanced Clinical Diagnosis on EMRs                   | 2024           | arXiv                                  | Disease diagnosis        | Graph, Text                        | RAG (knowledge graph)                         |
| A 360º View for Large Language Models: Early Detection of Amblyopia in Children using Multi-View Eye Movement Recordings. | 2024           | Artificial Intelligence in Medicine    | Disease diagnosis        | Image                              | RAG (corpus), Prompt (few-shot)              |
| Empowering PET Imaging Reporting with Retrieval-Augmented Large Language Models and Reading Reports Database: A Pilot Single Center Study | 2024           | medRxiv                                | Disease diagnosis        | Text                               | RAG (database)                                |
| EMERGE: Integrating RAG for Improved Multimodal EHR Predictive Modeling                                               | 2024           | arXiv                                  | Disease diagnosis        | Text, Time series, Graph           | RAG (corpus), RAG (knowledge graph)          |
| Large Language Models and Medical Knowledge Grounding for Diagnosis Prediction                                        | 2023           | medRxiv                                | Differential diagnosis    | Text, Graph                        | RAG (knowledge graph)                         |
| Generative Large Language Models are autonomous practitioners of evidence-based medicine                              | 2024           | arXiv                                  | Disease diagnosis        | Text                               | RAG (corpus)                                  |
| Enhancing Large Language Models for Clinical Decision Support by Incorporating Clinical Practice Guidelines           | 2024           | arXiv                                  | Disease diagnosis        | Text                               | RAG (corpus)                                  |



## Conversational diagnosis

| Title                                                                                                               | Published Year | Journal             | Task                 | Input Data Modality | LLM Technique Type |
|---------------------------------------------------------------------------------------------------------------------|----------------|---------------------|----------------------|---------------------|--------------------|
| Heterogeneous Knowledge Grounding for Medical Question Answering with Retrieval Augmented Large Language Model     | 2024           | WWW                 | Text-based Med QA    | Text                | RAG (database)     |
| Development of a Liver Disease-Specific Large Language Model Chat Interface using Retrieval Augmented Generation    | 2024           | Hepatology          | Text-based Med QA    | Text                | RAG (corpus)       |
| GPT-agents based on medical guidelines can improve the responsiveness and explainability of outcomes for traumatic brain injury rehabilitation | 2024           | Scientific Reports  | Text-based Med QA    | Text                | RAG (corpus)       |
| Mindmap: Knowledge graph prompting sparks graph of thoughts in large language models                                | 2023           | arXiv               | Text-based Med QA    | Text                | RAG (knowledge graph) |
| Improving accuracy of GPT-3/4 results on biomedical data using a retrieval-augmented language model                 | 2023           | arXiv               | Text-based QA        | Text                | RAG (database)     |
| Development of a Liver Disease-Specific Large Language Model Chat Interface using Retrieval Augmented Generation    | 2023           | Hepatology          | Text-based QA        | Text                | RAG (corpus)       |
| A Context-based Chatbot Surpasses Trained Radiologists and Generic ChatGPT in Following the ACR Appropriateness Guidelines | 2023           | Radiology           | Text-based Med QA    | Text                | RAG (database)     |






# Pre-training


## Disease diagnosis

| Title                                                                                                         | Published Year | Journal                                   | Task                               | Input Data Modality                     | LLM Technique Type                     |
|---------------------------------------------------------------------------------------------------------------|----------------|-------------------------------------------|------------------------------------|------------------------------------------|----------------------------------------|
| Human-Algorithmic Interaction Using a Large Language Model-Augmented Artificial Intelligence Clinical Decision Support System | 2024           | ACM CHI                                  | Disease diagnosis                 | Text                                     | Pre-training                           |
| A medical multimodal large language model for future pandemics                                               | 2023           | npj Digital Medicine                     | Disease diagnosis                 | Image, Text                              | Pre-training, Fine-tune (supervised FT) |
| A large language model for electronic health records                                                         | 2022           | npj Digital Medicine                     | Clinical natural language processing | Text                                     | Pre-training, Fine-tune (supervised FT) |
| Towards accurate differential diagnosis with large language models                                           | 2023           | arXiv                                    | Differential diagnosis             | Text                                     | Fine-tune (supervised FT), Pre-training |
| Stone needle: A general multimodal large-scale model framework towards healthcare                            | 2023           | arXiv                                    | Multimodal healthcare integration | Text, Image, Video, Audio                | Pre-training, Fine-tune (supervised FT) |
| Towards generalist foundation model for radiology                                                            | 2023           | arXiv                                    | Disease diagnosis                 | Image, Text                              | Pre-training                           |
| A generalist vision–language foundation model for diverse biomedical tasks                                   | 2023           | Nature Medicine                          | Multi-modal disease diagnosis      | Image, Text                              | Pre-training, Fine-tune (supervised FT) |
| Clinicalmamba: A generative clinical language model on longitudinal clinical notes                           | 2024           | arXiv                                    | Disease diagnosis                 | Text                                     | Pre-training                           |
| Decomposing Disease Descriptions for Enhanced Pathology Detection: A Multi-Aspect Vision-Language Pre-training Framework | 2024           | Proceedings of the …                     | Disease diagnosis                 | Image, Text                              | Pre-training                           |
| Mica: Towards explainable skin lesion diagnosis via multi-level image-concept alignment                      | 2024           | Proceedings of the AAAI Conference on Artificial … | Disease diagnosis                 | Image, Text                              | Fine-tune (supervised FT), Pre-training |
| A visual–language foundation model for pathology image analysis using medical Twitter                        | 2023           | Nature Medicine                          | Multi-modal disease diagnosis      | Image, Text                              | Pre-training, Fine-tune (supervised FT) |
| A visual-language foundation model for computational pathology                                               | 2024           | Nature Medicine                          | Disease diagnosis                 | Text, Image                              | Pre-training, Fine-tune (supervised FT) |



## Conversational diagnosis

| Title                                                                                      | Published Year | Journal | Task             | Input Data Modality | LLM Technique Type                   |
|--------------------------------------------------------------------------------------------|----------------|---------|------------------|---------------------|--------------------------------------|
| Biomistral: A collection of open-source pretrained large language models for medical domains | 2024           | arXiv   | Text-based Med QA | Text                | Pre-training, Fine-tune (supervised FT) |




## Risk prediction

| Title                                                                                                      | Published Year | Journal | Task                                      | Input Data Modality       | LLM Technique Type                     |
|------------------------------------------------------------------------------------------------------------|----------------|---------|------------------------------------------|----------------------------|----------------------------------------|
| Large Language Multimodal Models for New-Onset Type 2 Diabetes Prediction using Five-Year Cohort Electronic Health Records | 2024           | arXiv   | Chronic Disease Prediction              | Text, Tabular              | Pre-training                           |
| From Supervised to Generative: A Novel Paradigm for Tabular Deep Learning with Large Language Models      | 2024           | KDD     | Disease Classification, Risk Prediction | Tabular                   | Fine-tune (supervised FT), Pre-training |
| Large Language Multimodal Models for 5-Year Chronic Disease Cohort Prediction Using EHR Data              | 2024           | arXiv   | Risk Prediction                         | Text, Tabular              | Pre-training                           |



