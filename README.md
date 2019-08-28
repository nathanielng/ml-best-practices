# Best Practices in Machine Learning

## The Big Picture

1. **Impact**: what will be the business value or impact of a good model? how would stakeholders be positively impacted and is there a convincing story? what is the business objective? (e.g. is it user satisfaction, accuracy, or something else). should I aim for just a model or an end-to-end solution?
   - have I identified all relevant stakeholders?
   - at what stage of the process should I involve each of the relevant stakeholders?
2. **Trust**: how will the model be validated and how will I convince stakeholders that the model can be trusted?
3. **Approach**:
   - what are the questions I am asking, and am I asking the right questions?
   - do I have the right approach? am I starting with a preconceived idea and just looking to find data that will support my case? am I p-hacking?

## Ethics, Security, Complaince

1. **Ethics**: could there any ethical impact if the model is deployed, or if the data (or model) is leaked?
2. **Compliance**: are there any relevant regulations that need to be complied with? for example, is any form of personal data involved?
3. **Security**: is data security and/or encryption an important consideration?

## Data

### Data Acquisition & Accessibility

- how accessible is the dataset? and how much will it cost to acquire new data points? is any part of the data behind paywalls, or controlled by external parties reluctant to provide access to the data? could the situation change (for the better or for the worse) at any point in time during the lifetime of the project?

### Data Completeness

- how representative is the data of the entire population?
- could there be any missing features (variables) that
  could change the conclusions of the analysis (and are therefore needed for the model)?
- is the sample size sufficient for the number of features being trained on
  (what is the ratio of the number of data points to the number of features)?
  Could data sparsity be an issue in any particular part of the dataset?

### Errors & Inconsistencies
- are there any errors or inconsistencies in the dataset? are there any measurement errors, bias in the dataset?

### Metadata
- is there sufficient documentation on the dataset - how the data was acquired, a description of the column headers, any codes in the dataset, what are the units of the numerical data columns, etc

