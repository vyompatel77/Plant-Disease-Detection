Abstract- Potato is one of the most widely grown crop around
the world and is a part of the staple diet for almost every
household. Cultivation of such a crop requires proper care,
especially when diseases are considered. The traditional
method to identify such diseases is purely based on
observation by experts in the field like farmers. This
approach however can lead to large losses due to the inability
to properly identify a crop disease with high accuracy. This
research aims to change the way we identify such disease to
make it more accurate and our cultivation and treatment
processes more efficient. There are many diseases that a
potato crop can suffer from. This study is on a disease
detection model using SVM and Random Forest. Random
Forest has been used in two ways a single stage model and a
two stage model. Our initial dataset was of 2152 images
which included early blight diseased leaves, late blight
diseased leaves and healthy leaves of a potato. The work
began with feature extraction using LBP (Local Binary
Patterns) and Colour Histograms and then solving the
problem of class imbalance using SMOTE. Further we
applied our SVM and Random Forest models along with K Cross Validation where we kept K=10 to address the problem
of overfitting on the generated dataset which is a mixture of
synthetic (SMOTE) and real images. Our Random Forest
models showed higher accuracies compared to SVM. Single
stage Random Forest showed a 99.13% of average accuracy
while the two stage model showed 99.9% in stage one where
we separate only the healthy and diseased leaves and stage
two showed an average accuracy of 99.15% Meanwhile our
SVM model only showed an average accuracy of 98.06%.
