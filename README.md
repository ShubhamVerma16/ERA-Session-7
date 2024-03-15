# ERA-Session-7

## Model 1:
### Target: 
* Target: Achieve the 99.4 accuracy with initial skeltal structure and within 15 epochs.
### Results:
* Parameters: 63.79k
* Best Train Accuracy: 99.93
* Best Test Accuracy: 99.24 (15th Epoch)
### Analysis:
* High number of parameters Model is over-fitting.

## Model 2:
### Target: 
* Achieve the 99.4 accuracy with updated skeltal structure and within 15 epochs. The model size is reduced and batch normalization and dropout is added. 
### Results:
* Parameters: 10.97k
* Best Train Accuracy: 99.29
* Best Test Accuracy: 98.89 (14th Epoch)
### Analysis:
* Batch normalization adds 180 as per the architecure parametres, dropouts dont add any extra parameter. THe models looks slightly beeter as it is not overfitting. The model starts soff with underfitting which is a good sign but comes down to the mentioned accuracy. The differnece is accuracy is 0.13 whic hmeans slight overfit, but a better model.

## Model 3: 
### Target: 
* Achieve the 99.4 accuracy with provided skeltal structure and within 15 epochs.
### Results:
* Parameters: 10.97k
* Best Train Accuracy: 98.41
* Best Test Accuracy: 99.07 (15th Epoch)
### Analysis:
* Lesser number of parmaeters with drop outs added after each cov layer. The model underfits so we have a gap to get to the atrget accuracy. 

## Model 4: 
### Target: 
* Achieve the 99.4 accuracy with updated skeltal structure and within 15 epochs. The model size is reduced and GAP is added.
### Results:
* Parameters: 6.07k
* Best Train Accuracy: 97.00
* Best Test Accuracy: 97.71 (15th Epoch)
### Analysis:
* The model started with lesser accuracy as the number of parmaters were reduced.the model is mostly overfitting. 

## Model 5:
### Target: 
* Achieve the 99.4 accuracy with updated skeltal structure and within 15 epochs. The model size is increased by adding more capacity.
### Results:
* Parameters: 7.8k
* Best Train Accuracy: 97.41
* Best Test Accuracy: 98.85 (14th Epoch)
### Analysis:
* We found that model is underfitting consistently.

## Model 6:
### Target: 
* Achieve the 99.4 accuracy with provided skeltal structure and within 15 epochs. The model was trained with varying lr and schduler rates.
### Results:
* Parameters: 6.91k
* Best Train Accuracy: 99.24
* Best Test Accuracy: 99.45 (9th Epoch)
### Analysis:
* Consistent underfitting of the model at the start. Achieved good test accuracy and consistent target test accuracy required.
