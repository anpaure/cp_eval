<a target="_blank" href="https://colab.research.google.com/github/anpaure/cp_eval/blob/main/cp_eval.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Competitive programming eval
Problems are taken from Kazakhstan's 2024 regional and national informatics olympiads. This selection is a good choice because the problems are relatively new, originally available only in Russian, and unlikely to have been crawled online since they are shared exclusively in a private group. Moreover, no public editorials or solutions exist, so no overfitting. Problems are sorted by difficulty groups, A is the easiest, B is slightly harder, C is the hardest.

The results are obtained by prompting 4 SOTA models (deepseek-r1-lite-preview, chatgpt-4o-latest-20241120, claude-3-5-sonnet-20241022, o1-mini) with: "You are a competitive programming grandmaster. Solve the following programming problem." followed by the problem statement.

Some prompts were re-run a couple of times if the model failed to write a solution that earned points. In case a model generally gets the idea but makes a bug somewhere, It was told "You have an error somewhere, debug your code." without any additional pointers.

Essentially, the goal wasn't to conduct a perfect experiment, but rather squeeze the most out of models without any advanced prompting or RAG. The code probably won't execute correctly in the notebook, that's because LLMs generate weird code. I could change that, but I decided to keep the raw code instead.

