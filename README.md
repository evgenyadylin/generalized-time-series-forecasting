# Generalized Time Series Forecasting Using Event Streams

**Generalized Time Series Forecasting Using Event Streams Pretrained LLM**  
*Recasting Temporal Prediction as Next-Event Modeling with Pretrained LLMs*

Author: **Evgeny Adylin**  
Affiliation: **Independent Research**

## Live article

Read the live article here:

**Live article:** https://evgenyadylin-generalized-time-series-forecasting.static.hf.space

## PDF

The PDF version of the article is available here:

[`article.pdf`](article.pdf)

## Code

The experiment code is available here:

[`code/gpt2_event_stream_forecasting.ipynb`](code/gpt2_event_stream_forecasting.ipynb)

The notebook contains the forecasting pipeline used in the article, including:

- time series preprocessing
- difference-based tokenization
- event-stream construction
- GPT-style language modeling
- token decoding
- forecast evaluation against baseline methods

## Run the notebook

Create a Python environment and install the dependencies:

```bash
cd code
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook gpt2_event_stream_forecasting.ipynb
```

You can also run it in Google Colab by uploading the notebook there.

## Notes

The notebook may expect the dataset file to be available locally or uploaded during execution.  
If the dataset is not included in this repository, add a short note explaining where it can be obtained.

## Keywords

time series forecasting, event streams, GPT, language models, tokenization, symbolic forecasting, autoregressive modeling
