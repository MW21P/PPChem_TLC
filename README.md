## TLC prediction

With this model, it will be possible to predict TLC properties like the eluent ratio and the Rf value using this ratio for a given input SMILES.
To train the model, we extracted data from the XML files of a dataset of US patent applications from 2001 to 2016. This dataset can be found here: https://figshare.com/articles/dataset/Chemical_reactions_from_US_patents_1976-Sep2016_/5104873.

It is important to create an account for Groq to get a personal API Key. This one should then be put into a file called config.py in the form: LLM_API_KEY = "Your API key here"
