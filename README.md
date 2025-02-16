# ANCHOLIK-NER: A Benchmark Dataset for Bangla Regional Named Entity Recognition

## Abstract
"ANCHOLIK-NER" is a linguistically diverse dataset for Named Entity Recognition (NER) in Bangla regional dialects, capturing variations across Sylhet, Chittagong, and Barishal. The dataset has around 10,443 sentences, 3,481 sentences per region. The data was collected from two publicly available datasets and through web scraping from various online newspapers, articles. To ensure high-quality annotations, the BIO tagging scheme was employed, and professional annotators with expertise in regional dialects carried out the labeling process. The dataset is structured into separate subsets for each region and is available both in CSV format. Each entry contains textual data along with identified named entities and their corresponding annotations. Named entities are categorized into ten distinct classes: Person, Location, Organization, Food, Animal, Colour, Role, Relation, Object, and Miscellaneous. This dataset serves as a valuable resource for developing and evaluating NER models for Bangla dialectal variations, contributing to regional language processing and low-resource NLP applications. It can be utilized to enhance NER systems in Bangla dialects, improve regional language understanding, and support applications in machine translation, information retrieval, and conversational AI.

## Table of Contents
- [Data Availability](#data-availability)
- [Named Entity Categories](#named-entity-categories)
- [Overview of Dataset](#overview-of-dataset)
- [Contact Information](#contact-information)
- [Citation of Dataset](#citation-of-dataset)
- [License](#license)

## Data Availability
The "ANCHOLIK-NER" dataset, available in CSV formats, is now publicly accessible. This dataset provides users with a valuable opportunity for flexible exploration and utilization in various research and analysis endeavors. You can explore and download the dataset at the following link: <a href="https://data.mendeley.com/datasets/gbkszkt8z3/1">ANCHOLIK-NER Dataset</a>. Feel free to leverage this resource for your research, experiments, or any other analytical purposes. If you have any questions or need further assistance with the dataset, don't hesitate to reach out.

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

| Named Entity Type  | Barishal | Sylhet | Chittagong | Total Instances |
|--------------------|----------|--------|------------|-----------------|
|    Person (PER)    |    39    |   38   |     39     |       116       |
|   Location (LOC)   |    540   |  544   |    538     |      1622       |
| Organization (ORG) |    143   |  146   |    144     |       433       |
|    Food (FOOD)     |    310   |  308   |    308     |       926       |
|    Animal (ANI)    |    56    |   55   |     56     |       167       |
|    Colour (COL)    |    161   |  167   |    160     |       488       |
|    Role (ROLE)     |    117   |  110   |    112     |       339       |
|   Relation (REL)   |    664   |  660   |    662     |      1986       |
|    Object (OBJ)    |    348   |  345   |    345     |      1038       |
| Miscellaneous (O)  |   17773  | 18590  |   18025    |      54388      |

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
Paul, Bidyarthi; Preotee, Faika Fairuj; Refat, Shamim Rahim; shuvo, shuvashis; Islam, Shifat; Muhammad, Tashreef (2025), “ANCHOLIK-NER: A Benchmark Dataset for Bangla Regional Named Entity Recognition”, Mendeley Data, V1, doi: 10.17632/gbkszkt8z3.1

## License
[MIT License](LICENSE)
