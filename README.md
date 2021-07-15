# Neural_Network_Charity_Analysis
## Project Overview
In the following project, we implemented a neural network with the tensor flow library to determine whether organizations would be successful if they received funding from a hypothetical charitable organization. We specifically created a binary classifier considering we are only interested in predicting successful or unsuccessful outcomes. We used a dataset with over 30,000 organizations where we applied the neural network workflow, which requires us to preprocess the data by encoding categorical variables, reducing the noise from variables, and dropping columns if necessary. From there, we compiled, trained, and evaluated the model. 

## Resources
- Python 3.7.6
  - Pandas
  - Scikit-learn
  - TensorFlow
- Jupyter Notebook

## Results
- Target Variable:
  - Success outcome column

- Features
  - Application type
  - Affilation
  - Government organization classification
  - Use case for funding
  - Organization type
  - Status of organization
  - Income classification
  - Special considerations for application
  - Funding amount requested

- The following columns were removed since they are only used for identification purposes
  - EIN
  - NAME
