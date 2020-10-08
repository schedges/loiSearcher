# loiSearcher.py
## Usage: 
```python loiSearcher.py```

## Summary
Quick python script to search LOIs for user-specified words, returns LOIs with most occurrences of that word/phrase. Tested with python 3.7.4 and OS X 10.15.6, not tested with other set-ups. Probably will not work well if searching for special characters. The LOIs were downloaded from: [https://www.snowmass21.org/docs/files/?dir=summaries] on 10/7/2020.

I'm also including the script I ran to generate the pickled list, you should not need to run this since the LOIs.pickle file is included in the repository.

# Instructions
- Run the python script from the folder containing the pickled LOI text (```LOIs.pickle```). 
- Specify the frontier (acceptable formats: "NF", 'NF', or NF). If the user-inputted frontier does not match one of the choices, all frontiers are searched.
- Enter the word or phrase to search. The LOIs with the most occurrences of that word/phrase are returned, along with their frontier.

# Modifications
- Change ```nResultsToShow``` to display more or fewer results.
- Change ```nPreviewChars``` to display more or fewer preview characters of the LOI text.
- Change ```caseSensitive``` to 1 for case-sensitive search, anything else and case is ignored.
