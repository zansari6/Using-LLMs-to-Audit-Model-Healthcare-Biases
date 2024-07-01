# Using LLMs to Audit Model Healthcare Biases

Large language models (LLMs) have the potential to mitigate pain points in health- care by helping with tasks such as decision support, text summarization, and question-answering. However, bias in the responses, leading to discrimination against groups due to their race, gender identity, or sexual orientation remains a major concern. Unfortunately, human evaluation is onerous and infeasible on a large scale. This motivates our study of evaluating if LLMs can audit the bias of other models. For this, we use the Stanford Healthcare Redteaming Dataset, which includes prompts, outputs, and human labels on the presence of bias that could per- petuate identity-based discrimination. Interestingly, we found that GPT-3.5-turbo performs better for bias check as a Critique model than GPT-4 and increased the accuracy by 5% for our baseline case

# Dataset and Models
All dataset information can be found at https://daneshjoulab.github.io/Red-Teaming-Dataset/

All model information can be found at https://platform.openai.com/docs/models

We use the dataset from the, “Red Teaming Large Language Models in Medicine” (Chang et al., 2024) research paper, consisted of 382 clinical prompts, iterated over GPT-3.5, GPT-4.0, and GPT-4.0 with the Internet, and 1146 responses from all LLMs. These responses were later evaluated by clinician experts on the basis of hallucinations, bias, safety, and privacy, providing a verified benchmark.

We used GPT-4 version gpt-4-0613 and GPT-3.5-turbo version gpt-3.5-turbo-0125 through the Open AI API.


## Tables and Plots
### Table
* Table 1: manual
### Plot
* Figure 1: plotted via Excel Sheets

# License
All models & code are licensed under MIT License
