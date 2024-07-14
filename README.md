# allergies_twitter_gtrends
Content for "Internet-based surveillance to track the prevalence of seasonal allergies across the US."

## Data
### California HHS Data
This data was provided by California's Department of Health Care Access and Information and has been further anonymized beyond what was provided. All relevant codes were aggregated together per county, further obfuscating individual information, and then transformed based on population and averaged with a moving window. This data is embedded in other files and not provided separately.

### Twitter
Tweet IDs are provided as the full Tweet contents cannot be provided as per Twitter's data sharing agreement; however, the full body (text, location, etc.) can be reconstructed from those IDs. The code to retrieve the data is not provided.

### Google Trends
Trends data is provided as it is used in the code. The code to retrieve GT-E data is not provided.

### Other Data
Some other data, largely related to populations and county identification, was retrieved from the US Census Bureau.

## Code
### Language Model
The model for selecting seasonal allergy-related Tweets is not provided as it is approximately 500MB; please contact me if you need it.

### California
A pared-down version of the code for the correlation and cointegration testing in California is provided.

### Nationwide
A pared-down version of the code for visualizing seasonal allergies in the United States is provided.

### Environment
An image of the complete development environment can be downloaded from Docker; however, it requires Tensorflow, Torch, and CUDA. Contact me if you wish to run this code and are having difficulty either with the container, or if you are trying to set up your own environment.

```docker pull oliverae/allergy_t_g```
