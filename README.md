# Utilizing-BioBERT-for-PICO-Evidence-Summarization
# <div style="padding:20px;color:#f0f2f0;margin:0;font-size:80%;text-align:center;display:fill;border-radius:5px;background-color:#1a0a36;overflow:hidden">Utilizing BioBERT for PICO Evidence Summarization for Medical Literature  related to Heart Disease</div>
<br>

<img src="https://raw.githubusercontent.com/Owaiskhan9654/Utilizing-BioBERT-for-PICO-Evidence-Summarization/main/Logo%20Medical%20Literature%20%20related%20to%20heart%20disease.JPG">


- In this work, I have utilized the dataset from the paper published in IEEE Journal of Biomedical and Health Informatics
 [Aceso: PICO-Guided Evidence Summarization on Medical Literature](https://ieeexplore.ieee.org/document/905650)

- There are other sets of PICO datasets utilized in there work but I have utilized only Heart Disease Medical Literature sentences**. 

- Dataset have been processed and proper Tags labelling has been done before utiizing the Data in this notebook 

- Each sentence in a given clinical publication is classified into four labels: **P, I/C, O and N**. 

- Here combination of the element C with the element I has been done in this dataset, because a “comparison” usually concerns with one or more ”intervention” in an randomized controlled trial (RCT). These two elements are usually intertwined and indistinguishable at the sentence level. 

- The label N stands for sentences that are not relevant to the evidence.

<br>

<img src="https://camo.githubusercontent.com/dd842f7b0be57140e68b2ab9cb007992acd131c48284eaf6b1aca758bfea358b/68747470733a2f2f692e696d6775722e636f6d2f52557469567a482e706e67">

> I have integrated W&B for visualizations and logging artifacts!
> 
> [PICO Evidence Summarization](https://wandb.ai/bminelytics-research-lab/BIOBERT%20NER%20on%20CORD19?workspace=user-owaiskhan9515)


> 
> - To get the API key, create an account in the [website](https://wandb.ai/site) .
> - Use secrets to use API Keys more securely 
