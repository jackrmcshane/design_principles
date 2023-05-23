# Notes from day 2
## Lecture Notes/Thoughts

softmax for multiclass -> converts network output to a PROBABILITY DISTRIBUTION for the classes

sparsity is important to regularization of the network


catastrophic forgetting -> important concept/phenomenon


using sigmoid in hidden layers can cause saturation, hurting ability to learn. This is why something like ReLU is used instead.




do you have to maintain the same st



does the same structure have to be preserved between models, the distributied and the combined

use with training different networks on different classification tasks and combining for classifying all


(You were talking about dynamic network architectures for individual networks) are the aggregation methods for federated learning static (ie the resulting architecture is the same regardless of ditributed models' performances) or does the resulting architecture change/vary based on the performance of the different distributed models or is does it vary based on what pathways from different models are strongest (ie certain core features are more important than others) (has this kind of thing been pursued?)
