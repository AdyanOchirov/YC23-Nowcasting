# YandexCup23-Nowcasting
 
Everything except for train and test data that is required to recreate my final prediction.

"notebooks" - Each notebook trains a model that outputs its predictions in "individual_predictions" folder after every epoch. I used only last 5 of each. Notebooks are very similar but slightly differ in dataset and model code.

"ensemble.ipunb" - Notebook that takes individual predictions and stitches them into the final one.

"individual_predictions" - Empty folder for predictions. Needs to be created.

"data" - Empty folder for "train" folder with train files and "2022-test-public.hdf5" test file. Needs to be crated.
