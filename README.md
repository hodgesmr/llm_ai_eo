# Using Language Models to Explore the AI Executive Order

![LLM AI EO](llm_ai_eo_header.jpg)

On October 30th, 2023, President Biden signed the [Executive Order on the Safe, Secure, and Trustworthy Development and Use of Artificial Intelligence](https://www.whitehouse.gov/briefing-room/presidential-actions/2023/10/30/executive-order-on-the-safe-secure-and-trustworthy-development-and-use-of-artificial-intelligence/). The order itself is quite sweeping and touches many government departments and agencies, with a focus on harnessing AI's potential and defending against harms and risks.

In this Notebook, we'll deploy language models to rapidly discover information from the Order. For the easiest setup, I recommend trying this out in a Google Colab notebook. Click the button below to get started!

<a target="_blank" href="https://colab.research.google.com/github/hodgesmr/llm_ai_eo/blob/main/llm_ai_eo.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Many of the strategies presented here are extensions from Simon Willison's work in his blog post, [Embedding paragraphs from my blog with E5-large-v2](https://til.simonwillison.net/llms/embed-paragraphs). Simon also maintains a handly command line utility for working with various LLM models, aptly named [LLM](https://llm.datasette.io/en/stable/). While Simon's writing largely focuses on the CLI capabilities of the tool (and the usefully opinionated integrations with SQLite), I prefer working with Pandas Dataframes. He're I'll show how to use the LLM library in that fashion.

## License

All code is provided under the [BSD 3-Clause license](https://github.com/hodgesmr/llm_ai_eo/blob/main/LICENSE).

## A Matt Hodges project

This project is maintained by [@MattHodges](https://mastodon.social/@MattHodges).

_Please use it for good, not evil._
