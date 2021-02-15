# VAIL_2021
This is my work in Artificial Intelligence for the 2021 VAIL Program by SureStart 

# Reflections

2/8/21: DAY 1!
I am very excited to learn how to know when we apply which kind of AI model to solve problems the most effectively. I also hope to learn more about acquiring data, cleaning and organizing it and udnerstanding which features are important to be considered. I also want to be able to apply the knowledge I learn to a VQE Quantum algorithm project soon!

2/9/21: DAY 2!

1) What is the difference between supervised and unsupervised learning?
Supervised learning requires a labeled data set that the model is trained on. Unsupervised learning works by identifying cluster patterns on unlabeled data.

2) Describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries. Scikit learn is not built to load, model, or visualize data, and that's why these external libraries are needed. 

2/10/21: DAY 3!

1) What are “Tensors” and what are they used for in Machine Learning?
Tensors are multidimensional data arrays. They're necessary for ML because data is almost always multi-dimensional, especially in DL. You'd think an image would have 3D (width, height, & depth/color) but samplesize would be the 4th dimension since data sets can be so large. Vectors are tensors with rank 1. The 3D Cartesian coordinate system has 3 basises so it would be a tensor with rank 3. A scalar is a tensor with rank 0, (no direction, only magnitude). The combination of components and basis vectors in a tensor together are the same no matter what reference point. Tensor visualization: https://hackernoon.com/photos/4HK5qyMbWfetPhAavzyTZrEb90N2-gr23tjy
Helpful references: 
https://towardsdatascience.com/quick-ml-concepts-tensors-eb1330d7760f
https://hackernoon.com/learning-ai-if-you-suck-at-math-p4-tensors-illustrated-with-cats-27f0002c9b32

2) What did you notice about the computations that you ran in the TensorFlow
programs (i.e. interactive models) in the tutorial

The result doesn't actually get calculated. In order to actually calculate and see the result, it is necessary to run the code in an interactive Session.
