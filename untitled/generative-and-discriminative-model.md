# Generative & Discriminative Model

In generative approaches for prediction tasks, one models a joint distribution on inputs and outputs and parameters are typically estimated using a likelihood-based criterion.

A generative model is a model for randomly generating observable data, typically given some hidden parameters. It specifies a joint probability distribution over observation and label sequences.

Generative models contrast with discriminative models, in that a generative model is a full probabilistic model of all variables, whereas a discriminative model provides a model only for the target variable\(s\) conditional on the observed variables. Thus a generative model can be used, for example, to simulate \(i.e. generate\) values of any variable in the model, whereas a discriminative model allows only sampling of the target variables conditional on the observed quantities. Despite the fact that discriminative models **do not need to model the distribution** of the observed variables, they cannot generally express more complex relationships between the observed and target variables.

Algorithms under the generative framework try to find a statistical model that best represents the data. The predictions are then based on the likelihood scores derived from the model.

In discriminative approaches, one directly models the mapping from inputs to outputs \(either as a conditional distribution or simply as a prediction function\); parameters are estimated by optimizing objectives related to various loss functions. Discriminative approaches have shown better performance given enough data, as they are better tailored to the prediction task and appear more robust to model misspecification. 

The fundamental difference between discriminative models and generative models is:

* Discriminative models learn the \(hard or soft\) boundary between classes.
* Generative models model the distribution of individual classes.

