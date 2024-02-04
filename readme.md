Segui todos os passos do tutorial disponibilizado.
https://microsoftlearning.github.io/AI-900-AIFundamentals/instructions/02-module-02.html

Na explicação faltou a parte do deploy abaixo:
  
  Deploy and test the model
  1. On the Model tab for the best model trained by your automated machine learning job, select Deploy and use the Web service option to deploy the model with the following settings:
    Name: predict-rentals
    Description: Predict cycle rentals
    Compute type: Azure Container Instance
    Enable authentication: Selected
  2. Wait for the deployment to start - this may take a few seconds. The Deploy status for the predict-rentals endpoint will be indicated in the main part of the page as Running.
  3. Wait for the Deploy status to change to Succeeded. This may take 5-10 minutes.
