# Choice-Prediction-Model
The Steinmetz dataset dataset explores the spatial distribution of neuronal activity associated with vision, choice, action, and behavioral engagement in mice. The researchers used Neuropixels probes to record from approximately 30,000 neurons across 42 brain regions while mice performed a visual discrimination task.

**Research Goal:**
Using this dataset, we aim to predict how mice brain makes a decison and understand the relative significance of the brain regions involved in the process 

**Research Question:**\
Is logistic regression a suitable model for predicting behavioral choice as a binary output based on neuronal data from the Steinmetz dataset? To what extent are the thalamus and midbrain regions implicated in contributing to choice?

**Results:**\
Identifying Neural Correlations: Our analysis has revealed a significant correlation between neural firing patterns in the midbrain and thalamus. This correlation highlights the intricate relationship between these two regions and hints at their coordinated involvement in processing sensory information.

Enhancing Model Performance: Our investigation into training models for distinct brain regions has yielded intriguing insights. Notably, we observed that training a model on brain regions specific to an individual session led to notably higher accuracy compared to a model trained on combined brain regions across all sessions. This finding underscores the importance of session-specific neural nuances in improving the predictive capabilities of our models.

**Limitations:**
Variability across sessions, sub-region data may be more specific, and loss of information averaging neuron data across sessions. 
