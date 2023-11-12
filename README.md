# YandexCup23-Nowcasting
 
Everything except for train and test data that is required to recreate my final prediction(hopefully).

"notebooks" - Notebooks I used for prediction. I slightly changed them from the state they were during the run(changed a string) but it shouldn't matter. You'll need to edit the paths to training data. They output a prediction after every epoch. You only need last five from each, but I am not 100% sure that outputing only last five will not change output.

"individual_predictions" - Empty folder for predictions.

"ensemble.ipunb" - Notebook that takes individual predictions and stitches them into the final one.