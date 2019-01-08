The field of Machine Learning owes much for its success to the ability of its
algorithms to automatically discover patterns in data. However, these algorithms 
are still written by hand, despite them being similar in their core element, 
i.e. the usage of past gradients as a means of locally updating their
search for optima. This commonality naturally leads to the debate of whether
one could learn those algorithms, instead of designing them manually, i.e.,
can we learn the optimal parameters of an optimization algorithm that we
would like to use for a machine learning problem? Should these “learned” al-
gorithms perform better than their manually-designed counterparts, it could
assist in lessening the time spent for hyperparameter tuning among ML practitioners 
and researchers alike, while also clearing the way for more generalized approaches 
in cases where an optimizer is needed. However, although recent approaches in the 
field of optimizer learning or, as it is commonly dubbed, in the field of 
meta-learning have resulted in learned optimizers that outperform their standard 
variants in tasks they have been trained on, they have showcased limited examples 
of their generalization capabilities, i.e. their ability to perform well in tasks 
outside of their training regime. The goal of the thesis is to explore the 
generalization capabilities of this form of meta-learning that usually comes 
in the form of a recurrent neural network optimizer, thus attempting to extend 
previous studies on learning optimization algorithms.

The thesis also involves an implementation of the relevant experiments in
PyTorch, a recently introduced deep learning framework that is widely popular
throughout the research community and the code will be open-sourced in order 
to facilitate further contributions towards answering this research question.
