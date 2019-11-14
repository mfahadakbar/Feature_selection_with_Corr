# Multicollinearity:
This has been an issue for some Machien Learnng models, although some machine learning algorithyms are not affected by multicollinearity, at the least , reducing redundent features will make the model less expensive interms of computational power.

This function looks to reduce feature space  based on correlation between features and at the same time , looking at the correlation between features and target variable

A simple rule of thumb is , say your feature A and B are highly correlated , then we need to drop on of the features. We will drop the feature (say feature B)  that has the :
  
  1) More avergae correlation with all other varibales in the rest of the data set
  2) Less correlation with Target , then the other Variable
  
Although i found it useful , yet simply running this code may not be effient alone, because it does not consider the impact of feature interaction alone. I am developing another comprehensive preprocessing function that will tkate care of this issue. I will post that late on. For now, it is better to use this code once you have doen your feature enginering / feature interactions

Also, this is supposed to work for regression and two class clasiification problems

In the end , please llet me know if there are any glitches, room for improvements (i am pretty sure that there are ) etc, afterall , we all learn from eachother :-)

Thanks
Fahad
