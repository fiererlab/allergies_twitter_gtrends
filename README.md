# allergies_twitter_gtrends
Content for "Internet-based surveillance to track the prevalence of seasonal allergies across the US."

## Data
### California HHS Data
This data was provided by California's Department of Health Care Access and Information and has been further anonomized beyond what was provided.

### Twitter
Tweet IDs are provided as the full Tweet contents cannot be provided as per Twitter's data sharing agreement; however, the full body (text, location, etc.) can reconstructed from those IDs.

### Google Trends
Trends data is provided as it is used in the code.

## Code
### Language Model
The model for selecting seasonal allergy-related Tweets is not provided as as it is approvimatly 500MB; please contact me if you need it.

### California
A pared-down version of the code for the correlation and cointegration testing in California is provided.

### Nationwide
A pared-down version of the code for visualizing seasonal allergies in the United States is provided.

### Environment
An image of the complete development environment can be downloaded from Docker; however, it requires Tensorflow, Torch, and CUDA. A second version without those packages will be made available. A requirements.txt is also provided; however, this project was done in Docker so any recreation in Anaconda or another environment manager is not supported.
