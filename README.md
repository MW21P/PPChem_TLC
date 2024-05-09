## Rf prediction for Thin-Layer-Chromatography (TLC)

While "cooking" organic reactions in the lab, chemists often help themselves by using TLCs to trace the progress of the reaction. This often requires a bit of trial-and-error as the ideal conditions for a nice Rf spot are empirical. And then there is also the question, which of all those blurry spots is the right product. 
With this model, we aim to simplify chemist's lives by predicting the Rf value based on the product to expect and on the conditions used for the TLC. 
Our model was trained using extracted data from the XML files of US patent applications from 2001 to 2016. This dataset can be found here: https://figshare.com/articles/dataset/Chemical_reactions_from_US_patents_1976-Sep2016_/5104873.

If you want to conduct everything from the start again, it is crucial to create an account for Groq (the LLM API we used), which should then be put into the config.py file.
