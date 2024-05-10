# LLM Tutorial: Transformers for Chemistry and Materials Science

<div>
    <img src="_static/transformer_chem.jpeg", width=300, class='center'>
</div>

## Setup 

### Install dependencies

```bash
pip install -r requirements.txt
```

### Compute resources
For parts of this tutorial, you will need to have access to a GPU, TPU, or Apple Silicon. This is because we will train small language models, and it will not be feasible to train them on a CPU. 

If you do not have access, to a GPU, you can consider the following options:

- [**Google Colab**](https://colab.google/): You can use Google Colab, which provides free access to a GPU. The downsides is that in the free tier, you cannot let it run in the background. 

- [**Kaggle**](https://www.kaggle.com/code/scratchpad/notebook7d02979da8/edit): You can use Kaggle, which provides free access to a GPU. 

- [**Lightning studio**](https://lightning.ai//): You can use Lightning Studio, which provides some free GPU hours. However, you need to wait for your account to be validated 

In addition, the major cloud providers provide free credits to students: 

- [Google Vertex AI](https://cloud.google.com/generative-ai-studio) - A suite of AI and machine learning APIs provided by Google Cloud. $150 credits upon signup
- [Azure AI Studio](https://azure.microsoft.com/en-us/products/ai-studio) - A collection of AI services and APIs offered by Microsoft Azure. Students start with $100 free Azure credits 

## Notebooks

| Notebook | Description | Colab |
|----------|-------------|-------|
| [llm-from-scratch.ipynb](llm-from-scratch.ipynb) | Building an LLM that generates molecules from scratch | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lewtun/llm-tutorial/blob/main/llm-from-scratch.ipynb) |
| [llm-agent.ipynb](llm-agent.ipynb) | Building a tool-augmented LLM agent | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lewtun/llm-tutorial/blob/main/llm-agent.ipynb) |


## Further reading

These tutorials are based on blog post originally published on [Kevin Jablonka's blog](https://kjablonka.com/index.html#category=llm).

## Acknowledgements

This work was supported by the Carl Zeiss Foundation. 
