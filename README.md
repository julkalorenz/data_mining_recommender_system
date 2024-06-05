# DATA MINING PROJECT
## Movie Recommender System 

### Collaborators
* [Julia Lorenz](https://github.com/julkalorenz)
* [Jakub Kubiak](https://github.com/Coderbeep)
* [Krzysztof Skrobała](https://github.com/shhhQuiettt)
* [Wojciech Bogacz](https://github.com/wojbog)
* [Mateusz Nowicki](https://github.com/MateuszN949)


### Description
**Movie Recommender System**  is an innovative project aimed at enhancing user experience by predicting movie ratings based on individual preferences. Leveraging a dataset containing diverse movie attributes and user ratings, the project employs advanced machine learning techniques to develop a predictive model.

The culmination of this endeavor is encapsulated in a detailed report, documenting the methodology, findings, and insights gained throughout the project's lifecycle.

Additionally, a scientist poster succinctly summarizes the key aspects of the project, serving as a visual aid to communicate its objectives, methodologies, and outcomes effectively.

### Dataset
The dataset utilized for training the predictive model is readily available through a provided link.

* [MovieLens dataset](https://grouplens.org/datasets/movielens/latest/)

### Model Testing Instruction
`final_notebook.ipynb` - file where we split the ratings into test and training datasets, generate and train our model, and test it
`model_predictor.ipynb` - to use our predictor on our already trained model.

### How to use our model?
#### Training and testing
To **train and test** the model, run the `final_notebook.ipynb`.
#### Only testing
To **skip**  the **training** process and only **test** the model, run the `model_predictor.ipynb` and follow instructions in the commented out cell. The predictor utilizes the training results avaliable in `model_data` directory.
#### Using custom data
To use the model with custom test pairs, put them into csv file `test_data/tests.csv` and run the `model_predictor.ipynb`.



