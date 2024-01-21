## AICS course project

The code of this repository is part of the Artificial Intelligence Cognitive Systems master course project at the University of Gothenburg.

**Rquirements:** All the requirements for running this project can be found in `Code\requirements.txt`.

(i) All the code written for this project can be found in the `Code\` folder. `data_processing.ipynb` contains all the code written for acquiring the nouns, the approximate semantic neighbours, and the corresponding images. `model.ipynb` contains the dataset class created and all the code written for defining the models, and training and testing them on the task of distinguishing between concrete and abstract nouns. The `Data\` folder contains all the datasets created for this project, `merged_dataset.csv` is the file that is used to train and test the models. The `images\` folder contains all the images that were downloaded for this project. Finally, `Notes\` contains the learning diary and the notes taken while working on this project.

(ii) The code can be run as is in the `.ipynb` files. In order to recreate the datasets in the `Data\` folder the Brysbaert (2014) rankings dataset for concreteness and abstractness is required and can be found here: [brysbaert_dataset](https://link.springer.com/article/10.3758/s13428-013-0403-5#Sec10). It has to be noted that the nouns were extracted in a random manner, so running the `data_processing.ipynb` file again will result in different datasets.

(iii) The work process consisted of the following steps: 1. noun extraction for 3 different categories: concrete, middle, abstract, based on the ratings in the Brysbaert dataset, 2. dataset creation, 3. defining models, 4. evaluate models on the collected data, 5. train and reevaluate models on the collected data.

For more information about the project, please look at the `paper.pdf` file.
