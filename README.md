# PresidentialSpeechReader
Searches for counts of keywords in corpora of presidential speeches.
The folder Texts contains corpora collected from http://www.thegrammarlab.com/?nor-portfolio=corpus-of-presidential-speeches-cops-and-a-clintontrump-corpus.
The folder Trump2020 is a corpus I compiled from https://www.rev.com/blog/transcript-category/donald-trump-transcripts/page/1.
I included all Trump transcripts from this site between the RNC convention on August 24th, 2020 and the election on November 3, 2020, not including the speech made on election
night after all votes had been cast. The only transcripts not included are transcripts not including Donald Trump.
The folder Biden2020 is a corpus compiled by me from https://www.rev.com/blog/transcripts?s=Joe+Biden. I included all Biden transcripts from this site between the DNC convention on August
21, 2020 and the election on November 3, 2020, not including the speech made on election night after all votes had been cast. Results are slightly different from the search included in the grammarlab link.
The exact explanation of this difference is not clear because the methodology of that search is not public. One apparent difference is due to a difference in the definition of a word such that in the grammarlab link, "hillaryclinton.com/calculator" doesn't count as an appearance of "com" for the search.

This project was done before I learned about webscraping or useful python libraries like pandas, which would have made this project significantly easier.
