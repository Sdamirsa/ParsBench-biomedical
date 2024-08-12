# ParsBench-biomedical
This repository contains multiple-choice questions and real-world scenarios for benchmarking large language models in Persian (Farsi) and English. The content is designed to evaluate the performance and capabilities of various language models across these two languages.

# Introduction and Motivation

Multiple-choice questions (MCQs) have been widely used for benchmarking large language models (LLMs). However, real-world use of LLMs differs as human-machine interaction is dynamic, and the truth is not embedded within a single option. This issue is more pronounced in medicine, where even the treatment and diagnosis of a patient can have multiple answers, ranging from correct to relatively correct, incorrect, or contradictory. The motivation behind ParsBench-biomedical is to translate an MCQ dataset (MedQA) into Persian, as well as create a real-world dataset for benchmarking LLMs within clinical settings in both English and Persian languages.

# Catalogue

## ParsBench-biomedical-MedQA-Persian
MedQA is a pioneering free-form multiple-choice open-domain question answering dataset focused on medical problems, derived from professional medical board exams. This multilingual dataset encompasses English, simplified Chinese, and traditional Chinese, containing thousands of questions in each language. We will create a random sample of this dataset and translate it into Farsi using our team.

## ParsBench-biomedical-RWCQ
Real World Clinical Query (RWCQ) is a dataset of scenarios and cases (inpatient and outpatient). Each scenario consists of background information (description of the scenario or case), 5 real-world questions from a clinician (MD level), and a set of 4 answers provided by 4 independent MDs using references and validated guidelines. The dataset is available in both English and Persian. The reason for including 4 independent correct answers is to capture the relativity of answers in medical science. Future uses can employ LLM-based validation or embedding models to calculate the performance of LLMs on this dataset. The motivation behind this dataset is to (1) create real-world clinical queries at an MD-level physician standard, and (2) attempt to address the relativity in correct answers to these open questions.

# Team of Contributors
...loading


<detail>
<summary>To-do</summary>

- [ ] Project Outline and Design

- [ ] Preparing the data
    - [ ] Sampling MedQA
    - [ ] Creating batches (N=35) for team members

- [ ] Create the guide
    - [ ] Translation of MedQA
    - [ ] Creating scenarios
    - [ ] Answering scenarios

- [ ] Streamlit apps
    - [ ] Create the streamlit app for translation and revision
    - [ ] Create the streamlit app for RWCQ
    - [ ] Create the streamlit app for answering to RWCQ

- [ ] Assign batches and scenarios to contributors
    - [ ] Zahra Shojaian --> Case (Surgery)
    - [ ] Soheilipour --> Mix 
    - [ ] Maryam Masodi --> Mix (neurology)
    - [ ] Poya --> Mix (Orthopedics)
    - [ ] Alrieza --> Trasnlation
    - [ ] Reza --> Mix
    - [ ] Elias --> Mix (ENT & Orthopedics)
    - [ ] Elham --> Case (Internal medicine)
    - [ ] Nariman --> building the streamlit app
    

</detail>
