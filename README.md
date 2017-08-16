# Copy-Paste at the Swiss Supreme Court

The judges have worked on 77'000 appeals from 2007 up until
July 2017. Many attorney claim that judges and law clerks are increasingly
copy-pasting elements from previous verdicts. This analysis using Python
analyses whether this is true or not.

The 77'000 verdicts, the data bases of the analyses, can be downloaded
[here](https://dl.dropboxusercontent.com/u/61999762/txt_files.zip). Make sure
the data folder is in the same folder you rund the jupyter notebook in.

The Swiss Supreme court is divided into four sections of law:
1. Sozialrechtliche Abteilungen I & II
2. Öffentlichrechtliche Abteilungen I & II
3. Zivilrechltiche Abteilungen I & II
4. Strafrechtliche Abteilung

And each appeals in each section are in German, French and Italian. Italian
I excluded, are there are only a few thousand of decisions. Splitting them into
the various section does not allow for enough text to analyse.

The following iPython Notebooks contain 14 analyses: Each section in French and
German.
