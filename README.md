# Study Buddy for KIIT University

Study Buddy is aimed at enhancing the university experience for students. This practical prototype harnesses advanced natural language processing methodologies, notably DistilBERT, seamlessly integrated with GPT, to furnish dependable responses to commonplace inquiries. By virtue of its training on our university's dataset, it stands poised to offer precise information to both current and prospective students. Whether one seeks elucidation on course particulars or endeavors to explore campus resources, it stands as a reliable aid. It is designed to help the students bid farewell to protracted web searches and to welcome concise responses tailored to the distinct needs of our university community.

## Project Status

This project is still under development and this repository is updated as soon as any change is made to refine the model. Please note that due to limited resources, several potential integrations and improvements could not be implemented. I acknowledge that access to certain APIs and resources would greatly enhance Study Buddy's capabilities. I intend to explore these possibilities in the future, and the project can be further improved with additional investment. 

## Integrated Model

To train the integrated model :
1. Clone this repository into your local machine using
   ```bash
       git clone https://github.com/mansheelagarwal/StuddyBuddy.git
2. Install the requirements via the requirements_studybuddy.txt file provided
3. To train this model for your dataset :
   ```python
      from model import CustomModel

      # Instantiate the CustomModel class
      model = CustomModel()

      # Train the model
      model.train(num_epochs=10)

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

   
   






