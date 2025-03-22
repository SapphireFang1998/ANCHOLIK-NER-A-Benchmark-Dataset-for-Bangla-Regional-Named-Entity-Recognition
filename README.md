# ANCHOLIK-NER: A Benchmark Dataset for Bangla Regional Named Entity Recognition

## Abstract
ANCHOLIK-NER is a linguistically diverse dataset for Named Entity Recognition (NER) in Bangla regional dialects, capturing variations across Sylhet, Chittagong, Barishal, Noakhali, and Mymensingh. The dataset has around 17,405 sentences, 3,481 sentences per region. The data was collected from two publicly available datasets and through web scraping from various online newspapers, articles. To ensure high-quality annotations, the BIO tagging scheme was employed, and professional annotators with expertise in regional dialects carried out the labeling process. The dataset is structured into separate subsets for each region and is available in CSV format. Each entry contains textual data along with identified named entities and their corresponding annotations. Named entities are categorized into ten distinct classes: Person, Location, Organization, Food, Animal, Colour, Role, Relation, Object, and Miscellaneous. This dataset serves as a valuable resource for developing and evaluating NER models for Bangla dialectal variations, contributing to regional language processing and low-resource NLP applications. It can be utilized to enhance NER systems in Bangla dialects, improve regional language understanding, and support applications in machine translation, information retrieval, and conversational AI.

## Table of Contents
- [Data Availability](#data-availability)
- [Research Article Availability](#research-article-availability)
- [Named Entity Categories](#named-entity-categories)
- [Overview of Dataset](#overview-of-dataset)
- [Contact Information](#contact-information)
- [Citation of Dataset](#citation-of-dataset)
- [Citation of Research Article](#citation-of-research-article)
- [License](#license)

## Data Availability
The "ANCHOLIK-NER" dataset, available in CSV formats, is now publicly accessible in Mendeley Data. This dataset provides users with a valuable opportunity for flexible exploration and utilization in various research and analysis endeavors. You can explore and download the dataset at the following link: <a href="https://data.mendeley.com/datasets/gbkszkt8z3/1">ANCHOLIK-NER Dataset</a>. Feel free to leverage this resource for your research, experiments or any other analytical purposes. If you have any questions or need further assistance with the dataset, don't hesitate to reach out.

## Research Article Availability
A preprint of this research article is now publicly accessible in arXiv. You can read and download the article at the following link: <a href="https://arxiv.org/abs/2502.11198">**"ANCHOLIK-NER: A Benchmark Dataset for Bangla Regional Named Entity Recognition"**</a>. Feel free to leverage this resource for your research, experiments or any other analytical purposes.

## Named Entity Categories
The dataset includes the following named entity categories, each annotated using the BIO scheme:
- Location (LOC): B-LOC, I-LOC
- Person (PER): B-PER, I-PER
- Organization (ORG): B-ORG, I-ORG
- FOOD (FOOD): B-FOOD, I-FOOD
- Animal (ANI): B-ANI, I-ANI
- Colour (COL): B-COL, I-COL
- ROLE (ROLE): B-ROLE, I-ROLE
- Relationship (REL): B-REL, I-REL
- Object (OBJ): B-OBJ, I-OBJ
- Miscellaneous: O
    
## Overview of Dataset
### Total instances of Named Entity Types in three Regions

| Named Entity Type  | Barishal | Sylhet | Chittagong | Noakhali | Mymensingh | Total Instances |
|--------------------|----------|--------|------------|----------|------------|-----------------|
|    Person (PER)    |    39    |   38   |     39     |    39    |     39     |       194       |
|   Location (LOC)   |    540   |  544   |    538     |   361    |    362     |      1840       |
| Organization (ORG) |    143   |  146   |    144     |   141    |    140     |       700       |
|    Food (FOOD)     |    310   |  308   |    308     |   303    |    312     |      1541       |
|    Animal (ANI)    |    56    |   55   |     56     |    57    |     57     |       284       |
|    Colour (COL)    |    161   |  167   |    160     |   164    |    163     |       816       |
|    Role (ROLE)     |    117   |  110   |    112     |   111    |    113     |       554       |
|   Relation (REL)   |    664   |  660   |    662     |   376    |    676     |      3386       |
|    Object (OBJ)    |    348   |  345   |    345     |   350    |    349     |      1747       |
| Miscellaneous (O)  |   17773  | 18590  |   18025    |  17957   |   17943    |     90755       |

## Contact Information

For any questions or further inquiries, please feel free to reach out:

- **Bidyarthi Paul**
  - Email: [bidyarthipaul01@gmail.com](mailto:bidyarthipaul01@gmail.com)

- **Faika Fairuj Preotee**
  - Email: [faikafairuj2001@gmail.com](mailto:faikafairuj2001@gmail.com)

- **Shuvashis Sarkar**
  - Email: [shuvashisofficial@gmail.com](mailto:shuvashisofficial@gmail.com)

- **Shamim Rahim Refat**
  - Email: [n.a.refat2000@gmail.com](mailto:n.a.refat2000@gmail.com)

- **Shifat Islam**
  - Email: [tashreef.muhammad@gmail.com](mailto:shifat.islam.buet@gmail.com)
  
- **Tashreef Muhammad**
  - Email: [tashreef.muhammad@gmail.com](mailto:tashreef.muhammad@gmail.com)
    
## Citation of Dataset
If you find the dataset helpful, please consider citing our dataset:

```plaintext
Paul, Bidyarthi; Preotee, Faika Fairuj; 
shuvo, shuvashis; Refat, Shamim Rahim; 
Islam, Shifat; Muhammad, Tashreef; 
Hoque, Mohammad Ashraful; Manzoor, 
Shahriar (2025), “ANCHOLIK-NER: A 
Benchmark Dataset for Bangla Regional 
Named Entity Recognition”, Mendeley 
Data, V2, doi: 10.17632/gbkszkt8z3.2
```

## Citation of Research Article
If you find the research work helpful, please consider citing our paper:

```bibtex
@article{paul2025ancholik,
  title={ANCHOLIK-NER: A Benchmark Dataset for Bangla Regional Named Entity Recognition},
  author={Paul, Bidyarthi and Preotee, Faika Fairuj and Sarker, Shuvashis and Refat, Shamim Rahim and Islam, Shifat and Muhammad, Tashreef and Hoque, Mohammad Ashraful and Manzoor, Shahriar},
  journal={arXiv preprint arXiv:2502.11198},
  year={2025}
}
```

## License
[MIT License](LICENSE)
