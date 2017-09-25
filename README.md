# Text analysis on the meetings of the Dutch governing body the Tweede Kamer

A personal exercise in text analysis.

Every word uttered during official meetings of the Tweede Kamer is written down and neatly published on webpages such as [this one](https://zoek.officielebekendmakingen.nl/h-tk-20132014-108-4.html). Luckily, there's a nice RSS feed listing all of these URLs. The text is well formatted and thus easy to scrape. It even says which party the current speaker belongs to. As an exercise, I tried classifying which statement was made by which party using your run-of-the-mill bag-of-words TF-IDF approach with a support vector machine classifier. Precision and recall scores are reported for each class. I've also shown the top 10 words with the highest coefficient for each party as a way of identifying words that are associated strongly with that party.

It's a quick thing with little to no annotation. Don't expect it to make much sense unless you're familiar with implementing these techniques in Python.
