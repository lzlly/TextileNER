# TextileNER: A Named Entity Recognition Dataset for the Textile Domain
# Overview

TextileNER is a domain-specific Named Entity Recognition (NER) dataset designed for the textile domain. The dataset contains annotated Chinese texts covering various real-world scenarios such as textile manufacturing, garment production, fashion descriptions, and industrial processes.

TextileNER aims to support research on domain-adaptive NER models.

Language: # Chinese

Domain: # Textile

Task: # Named Entity Recognition (NER)

Annotation Scheme: # BIOES

Total Sentences: # 4,811

Total Characters: # ~241K

Entity Types: # 19

Annotation Format

# TextileNER adopts the BIOES tagging scheme, where:

B: Beginning of an entity

I: Inside an entity

E: End of an entity

S: Single-character entity

O: Outside any entity

The dataset is organized at the character level, and each line corresponds to one character and its label:

<img width="708" height="576" alt="image" src="https://github.com/user-attachments/assets/fcace6bc-92b9-4f63-80cf-7cfa65824dd1" />

Sentences are separated by an empty line.

# Dataset Splits

The dataset is divided into three subsets:
<img width="1580" height="456" alt="image" src="https://github.com/user-attachments/assets/08461b79-e211-428c-adc0-2efaedf6a874" />

# Entity Types
TextileNER defines 19 entity types, covering key semantic concepts in the textile and fashion domain.
<img width="740" height="1234" alt="image" src="https://github.com/user-attachments/assets/f075918c-29c1-4271-8b02-d7b40a0aaa7e" />



# File Structure
<img width="456" height="386" alt="image" src="https://github.com/user-attachments/assets/288974a6-8611-4379-990b-27eeb4223b63" />


Each file follows the same character-level BIOES format.

# Use Cases
TextileNER can be used for:
Training and evaluating NER models in vertical domains
Domain adaptation of pre-trained language models
Knowledge graph construction for textile industry
Intelligent fashion recommendation systems
Industrial text mining and information extraction

# License
This dataset is released for research and academic purposes.

# Contact
For questions, issues, or collaborations, please open an issue on GitHub or contact the authors via the repository page.
