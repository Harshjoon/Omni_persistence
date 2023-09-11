# Omni_persistence

Correlation between current and history data for history in 1,2,3... days. This is the baseline model for the space weather solar wind prediction model.

It has been observed that there is no unique correlation for the data it varies with the subset, therefore we have to calculate correlation on the exact subset of data that has been used to train the model. 

Also, correlation value changes significantly after oversampling, so we should not consider correlation of oversampled data.
