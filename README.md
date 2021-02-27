# Generating Right Wing News Using GPT2

### I have built a custom model for it using data from Kaggle 

Creating a new finetuned model using data from FOX news

### My model can be accessed at: gagan3012/Fox-News-Generator

Check the BenchmarkTest notebook for results

Find the model at [gagan3012/Fox-News-Generator](https://huggingface.co/gagan3012/Fox-News-Generator)

```
from transformers import AutoTokenizer, AutoModelWithLMHead

tokenizer = AutoTokenizer.from_pretrained("gagan3012/Fox-News-Generator")

model = AutoModelWithLMHead.from_pretrained("gagan3012/Fox-News-Generator")
```
