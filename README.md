# Hate Speech Detection on Nigerian Twitter

Data and models for paper: ["NaijaHate: Evaluating Hate Speech Detection on Nigerian Twitter Using Representative Data"](https://arxiv.org/abs/2403.19260).

All of the resources for this project are centralized in this :hugs: [collection](https://huggingface.co/collections/worldbank/naijahate-667e6913f73cb80e7d96040a). 

## Data

The complete NaijaHate dataset can be found on :hugs: under [this link](https://huggingface.co/datasets/manueltonneau/NaijaHate).

## Models

The NaijaXLM-T pre-trained model can be found on :hugs: under [this link](https://huggingface.co/manueltonneau/naija-xlm-twitter-base).

The NaijaXLM-T model finetuned on NaijaHate for hate speech detection can be found on :hugs: under [this link](https://huggingface.co/worldbank/naija-xlm-twitter-base-hate). 

## Citation

If you find our work useful, please cite:

```
@inproceedings{tonneau-etal-2024-naijahate,
    title = "{N}aija{H}ate: Evaluating Hate Speech Detection on {N}igerian {T}witter Using Representative Data",
    author = "Tonneau, Manuel  and
      Quinta De Castro, Pedro  and
      Lasri, Karim  and
      Farouq, Ibrahim  and
      Subramanian, Lakshmi  and
      Orozco-Olvera, Victor  and
      Fraiberger, Samuel",
    editor = "Ku, Lun-Wei  and
      Martins, Andre  and
      Srikumar, Vivek",
    booktitle = "Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.acl-long.488",
    doi = "10.18653/v1/2024.acl-long.488",
    pages = "9020--9040",
    abstract = "To address the global issue of online hate, hate speech detection (HSD) systems are typically developed on datasets from the United States, thereby failing to generalize to English dialects from the Majority World. Furthermore, HSD models are often evaluated on non-representative samples, raising concerns about overestimating model performance in real-world settings. In this work, we introduce NaijaHate, the first dataset annotated for HSD which contains a representative sample of Nigerian tweets. We demonstrate that HSD evaluated on biased datasets traditionally used in the literature consistently overestimates real-world performance by at least two-fold. We then propose NaijaXLM-T, a pretrained model tailored to the Nigerian Twitter context, and establish the key role played by domain-adaptive pretraining and finetuning in maximizing HSD performance. Finally, owing to the modest performance of HSD systems in real-world conditions, we find that content moderators would need to review about ten thousand Nigerian tweets flagged as hateful daily to moderate 60{\%} of all hateful content, highlighting the challenges of moderating hate speech at scale as social media usage continues to grow globally. Taken together, these results pave the way towards robust HSD systems and a better protection of social media users from hateful content in low-resource settings.",
}

```

