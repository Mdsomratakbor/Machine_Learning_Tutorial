### ML label vs feature

**Label**
`A label represents an output value,`

**Feature**
`A feature is an input value that describes the characteristics of such labels in datasets`

### Examples

`When ML models are used in real life, experts present input data with features to the computer. For example, in a factory, a conveyor belt moves a lot of tomatoes. The ML model captures the features of tomatoes by employing computer vision tools. If the model recognizes such tomato features as its color which is brown or black the label "rotten" is assigned to the fruit, if the color is red, yellow, or orange it means that the tomato is fresh. It is worth mentioning that this is a simplified approximated description of the process.`

`The features have to be uploaded to the computer system as input so that the ML algorithms can generate a label as an output. This is the difference between ML labels and features. The more and better the labeled training dataset was, the better the model will predict labels by features.`


### Targets in ML and their differences from labels and features

`A couple of terms that are often interchangeable in ML are target vs label. A target is a dataset variable to be predicted by an ML model. This is the variable that describes the outcome of the process. Broadly speaking, the terms label and target may be used interchangeably. However, the label is more common within classification algorithms than within regression ones. Target is the final output an ML model is trying to predict. It can be categorical or continuous.`

`The label represents the true outcome of the target. As mentioned earlier the labels are assigned to the training dataset but when the ML model is ready it is fed with unlabeled data. The label has a known or correct value, but finding the target variable is the main task of the ML model. As the model is trained, experts try to train the model in the best and highest quality way possible so that the targets are closest to the labels. However, predictions on the target variables will most likely never be one hundred percent perfectly correct but will strive toward that goal as they are trained and errors are corrected.`

`As for the difference between features and targets in ML, this should be obvious by now. As we have already found out, the target is often referred to as a synonym for a label, since there is essentially not much difference between the two terms. The label has a precisely known value, while the target is the variable the model is trying to predict. Under ideal conditions, label and target would be the same thing. The features describe the label, so they should also describe the target. If the output of the ML model indicates that the target and features do not match, then there must have been an error somewhere in the ML model that needs to be fixed for it to give correct predictions.`
