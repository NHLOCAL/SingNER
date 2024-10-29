# SingNER - AI Models for Singles Sorter

**SingNER** is a repository dedicated to the release and management of advanced AI models, integrated within the "Singles Sorter" software. These models serve to enhance the accuracy and depth of Hebrew musical text processing, focusing on identifying and classifying music-related entities.

## Models

### **singer_ner_he**
An NER (Named Entity Recognition) model designed to identify singer names from Hebrew song titles. This model has been meticulously trained to detect singer names within song titles, especially in cases where the singer's name is missing from the existing list or database. This capability significantly expands recognition accuracy, even in rare and challenging scenarios, ensuring that entities such as singer names are captured and processed accurately.

### **music_entity_clf**
A classification model that categorizes text strings into music-related categories, including singer names, album names, song titles, or other content. This model works alongside the NER model, enhancing its precision by providing an additional layer of validation and verification. This classification is particularly useful for error reduction, ensuring that the NER model avoids misidentifications. Furthermore, this model aids in accurately identifying and sorting albums, a feature intended for future expansion.

## Model Collaboration
Both models, **singer_ner_he** and **music_entity_clf**, are designed to operate in tandem, offering a robust solution for identifying and classifying Hebrew musical texts. Together, they provide a high level of accuracy, allowing for precise parsing of music-related content, and enabling the "Singles Sorter" software to manage and optimize music file metadata effectively.

## Link to Main Software
For further details on the main software application, visit the [Singles Sorter repository](https://github.com/NHLOCAL/Singles-Sorter/).