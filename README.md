# Dependency Dialogue Act Corpus

***

## 📜 Overview

This repository contains the data release for paper: **In Search of the Lost Arch: The Dependency Dialogue Acts Corpus**. This dataset was created for **research purpose only**. Please contact the original data source owners for more use cases.

### Dataset Statistics

| Source                  | Pulley K12 | Sensor Immersion K12 | TEAMS | STAC |
| -------------------------- | :---: | :---: | :---: | :---: |
| Source Type          | Spoken | Spoken | Spoken | Written |
| # of Dialogues  | 1 | 26 | 4 | 2 |
| Total # of Slash Units | 1123 | 4765 | 1922 | 1267 |
| Avg. # of Speakers | 7.0 | 4.58 | 3.0 | 3.5 |
| Avg. Edge Dist. | 1.26 | 1.31 | 1.48 | 2.46 |
| Release Terms | IRB required | IRB required | GNU-GPL CC | BY-NC-SA 4.0 |
| Scenario | Physics Class | Engineering Class | In-Person Board Game | Online Board Game |
| Multimodal Access | transcript | video access | audio access | chat log |
| Demographics info | K12 students | K12 students | adults | N/A |

***

## 🔑 Data Access

The dataset is divided into two parts: a publicly accessible subset and a limited-access subset that contains IRB controlled dialogues.

**Public Data**: The public portion of the dataset can be downloaded directly from this repository and please credit the original work of the source data. We provide their citation link for your reference.

**Limited-Access Data**: Due to privacy concerns, a portion of this dataset requires an application and is subject to a data use agreement. To request access, please follow these steps:

1.  Complete and Submit the **Data Access Application Form**: `[https://docs.google.com/forms/d/14OTgBotdVicGrYGcvkxa_iOXJ9daWJeX01mxAIkWB18/viewform?edit_requested=true]`
2.  Email the data controller at **[Thomas Breideband][thomas.breideband@colorado.edu]**.
3.  Upon approval, you will receive the data through secured channels.

For any questions regarding data access, please contact the data controller directly.

***

## 🛠️ Resources

Here are some helpful resources for working with our dataset:

* **Annotation Tool**: The tool used for DDA annotation can be found here: `https://dda.colorado.edu/v2/`. This is pure web based tool and we do NOT host or store your data on our server. The responsibility of maintaining the annotation progress is on the user solely by saving checkpoint files locally.

* **Codebook**: A detailed codebook describing all variables, fields, and annotation labels is available here: `https://nsf-isat.github.io/dda-codebook/`

***

## 📝 Citation

If you use this dataset in your research, please cite our work.

```bibtex
@inproceedings{
  # to be released soon
}
```

TEAMS corpus:
```bibtex
@inproceedings{litman-etal-2016-teams,
    title = "The Teams Corpus and Entrainment in Multi-Party Spoken Dialogues",
    author = "Litman, Diane  and
      Paletz, Susannah  and
      Rahimi, Zahra  and
      Allegretti, Stefani  and
      Rice, Caitlin",
    editor = "Su, Jian  and
      Duh, Kevin  and
      Carreras, Xavier",
    booktitle = "Proceedings of the 2016 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2016",
    address = "Austin, Texas",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/D16-1149/",
    doi = "10.18653/v1/D16-1149",
    pages = "1421--1431"
}
```

STAC corpus:
```
@inproceedings{asher-etal-2016-discourse,
    title = "Discourse Structure and Dialogue Acts in Multiparty Dialogue: the {STAC} Corpus",
    author = "Asher, Nicholas  and
      Hunter, Julie  and
      Morey, Mathieu  and
      Farah, Benamara  and
      Afantenos, Stergos",
    editor = "Calzolari, Nicoletta  and
      Choukri, Khalid  and
      Declerck, Thierry  and
      Goggi, Sara  and
      Grobelnik, Marko  and
      Maegaard, Bente  and
      Mariani, Joseph  and
      Mazo, Helene  and
      Moreno, Asuncion  and
      Odijk, Jan  and
      Piperidis, Stelios",
    booktitle = "Proceedings of the Tenth International Conference on Language Resources and Evaluation ({LREC}'16)",
    month = may,
    year = "2016",
    address = "Portoro{\v{z}}, Slovenia",
    publisher = "European Language Resources Association (ELRA)",
    url = "https://aclanthology.org/L16-1432/",
    pages = "2721--2727"
}
```