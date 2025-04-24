<h1>CS 6959 Project</h1>
<h2>Arionna Winn, u1117614</h2>
<h3>Paper: <a href="https://dl.acm.org/doi/abs/10.14778/3685800.3685854">DiversiNews: Enriching News Consumption with Relevant Yet Diverse News Articles Retrieval</a></h3>

The DiversiNews folder is the cloned repo from <a href="https://github.com/dukesun99/DiversiNews">DiversiNews GitHub</a> except for two files in the NewsSpectrum folder: articles.json and domains.json. These files initially were supposed to be populated with
data using git lfs, but when I tried to get the data, I only got an error that git lfs was not enabled for the repo. So instead, I had ChatGPT generate some dummy data that is now in those files.

I utilized DiversiNews's backend implementation. My frontend implementation is the frontend.ipynb file (it's a Jupyter notebook that uses ipywidgets).

I initally tried to implement the backend myself, however I found that the algorithms were too difficult to implement, so instead I used DiversiNews's backend and implemented the frontend.
