# loiSearcher
Quick python script to search LOIs for user-specified words, returns LOIs with most occurrences of that word. Tested with python 3.7.4 and OS X 10.15.6, not tested with other set-ups. Probably will not work well if searching for special characters.

# Instructions
- Run the python script from the folder containing the pickled LOI text. 
- Specify the frontier (e.g. "NF", 'NF', or NF for neutrino frontier). If the user-inputted frontier does not match one of the choices, all frontiers are searched.
- Enter the word to search. The LOIs with the most occurrences of that word are returned, along with their frontier.

# Modifications
- Change ```nResultsToShow``` to display more or fewer results.
- Change ```nPreviewChars``` to display more or fewer preview characters of the LOI text
- Change ```caseSensitive``` to 1 for case-sensitive search, anything else and case is ignored.