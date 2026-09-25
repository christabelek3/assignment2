# 5400 Assignment 2

## 1B
I would be more likely to guess that Johnson authored a paper because there are many more labeled Johnson writings than Kennedy-labeled writings

## 1C
Analysing the texts, I found that Johnson's texts tend to be longer. I also found that Johnson tends to open with "THE PRESIDENT" often. Also while Johnson's texts often  include "president", "mr", "think" and "vietnam",  Kennedy's texts tend to lean toward "new", "free", "freedom", "tax" etc.

# 1E
Prior (Kennedy) = 0.353
Prior (Johnson) = 0.647

Likelihood matrix shape: (2, 24390)

When I varied the alpha values, higher values reduced my accuracy, while lower values performed slightly better. However, the accuracy did not improve much beyond what was achieved with alpha = 0.1.

# 1F
Kennedy = 0 and Johnson = 1
actual test labels [0, 0, 0, 1, 1, 0, 1, 1, 1, 0]
predicted labels   [0, 0, 0, 1, 0, 0, 0, 1, 1, 0]
80% accuracy

# 2
The scikit-learn classifier does a better job of predicting the classes, with an accuracy of 90% compared with 80% for my implementation.

# 3A
My algorithm metrics (alpha = 0.1)
 Accuracy: 0.8 
 F1  0.75
Scikit learn NB metrics
 Accuracy: 0.9 
 F1  0.89

# 3B
Looking at the confusion matrices, both classifiers performed perfectly when classifying Kennedy's documents (class 0), but the scikit-learn implementation was better at identifying Johnson's documents (class 1).
