**Pre class work**

[In "Explore"](https://sle-collaboration.minervaproject.com/?id=e1633514-a30f-4b1c-b0d5-b0cf6c37ea49&userId=10860&name=Daiana+Besterekova&avatar=https%3A//s3.amazonaws.com/picasso.fixtures/Daiana_Besterekova_10860_2022-10-30T00%3A03%3A26.272Z&iframed=1&readOnly=0&isInstructor=0&enableSavingIndicators=1&signature=edd992c6ff1a3b073f297dc8edab1c5aaaf78bb404d6b52c1b0f97b438feef25#)


**Summary** 

I found Abdullah's question about adding the bias and decreasing the slope to reduce outliers really intriguing. However, what would happen if our test data followed the same training data pattern? Why are we penalizing the training set for the tradeoff? However, we do not really know what our test data is like, and we add parameters to address the uncertainty. But then we have the technique called k-folds, which solves the problem by reducing the lambda and goes over many lambda values to find the optimal one (Alina made this comment, and it is mentioned in the pre-class work video).

In the breakout debrief, students increased the number of Gaussians for 365 for the RBF model and discussed the reasons behind it. As Polina explained, it might happen because the model is more fitted to the training data with more parameters, and it will fail to be appropriate for the test data. Additionally, as we have more Gaussians, we consider the noise present in the data as a feature of the data. So we overfit to the cycle of temperatures as the noise will be used in the training process. Also, the model might consider the data as having a linear relationship by considering the training data. But the test data (the years above the training data) might not follow the same temperature pattern. Therefore, the exercise demonstrates the complexity behind building an accurate and appropriate model.  


**Recommendations** 

["L1 and L2 Regularization Methods" by Towards Data Science](https://towardsdatascience.com/understanding-l1-and-l2-regularization-93918a5ac8d0#:~:text=In%20practice%2C%20in%20the%20regularized,function%20differentiates%20l1%20from%20l2.) - This article provides a practical introduction to Lasso and Ridge regression, including their differences, advantages, and limitations. It also includes examples and code snippets in Python.

["Understanding L1 and L2 Regularization in Machine Learning" by Analytics Vidhya](https://www.analyticsvidhya.com/blog/2022/08/regularization-in-machine-learning/#:~:text=We%20learned%20about%20the%20L1,to%20find%20the%20optimal%20hyperparameters.) - This article provides a comprehensive overview of Lasso and Ridge regression, including their motivation, mathematical formulation, and application in real-world problems. It also includes examples and code snippets in R and Python.
