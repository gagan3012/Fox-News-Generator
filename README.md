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

### Sample Results: 

#### Query: 

Seldom has such an amateur armchair diagnosis been so easy as when ex-President Donald Trump and the Fox News switchboard reconnected on Wednesday for a conversation about

#### Result:

Seldom has such an amateur armchair diagnosis been so easy as when ex-President Donald Trump and the Fox News switchboard reconnected on Wednesday for a conversation about the economy,” said Elizabeth Trudeau, president of the Federation for American Immigration Reform. “I suspect they’re just trying to find a way to make Trump look bad. ” The controversy is unfolding amid a series of leaked emails showing the   Trump aides discussing the possibility of a “  ” in immigration policy. The emails show Trump aides discussing a plan to “immediately deport” illegal immigrants living in the United States. The plan was to “make it easier for illegal immigrants living in the United States to obtain work permits,” according to one email, which was obtained by FoxNews. com. The plan was to “immediately deport” illegal immigrants living in the United States. Trump has called for a temporary ban on legal immigration to prevent “criminals” from entering the country. Trump has called for a temporary ban on legal immigration to prevent “criminals” from entering the country. The latest headlines on the 2016 elections from the biggest name in politics. See Latest Coverage → The plan was floated in May 2015. Trump’s campaign had argued that a temporary ban would allow him to deport millions of illegal immigrants living in the U. S. “I like it,” Trump said at the time. Trump later said he would consider such a plan, but said he would not make the decision until the country has normalized relations with the U. S. “I don’t want to do it,” Trump said during a campaign rally in South Carolina. “I don’t want to do it right now. ” The latest headlines on the 2016 elections from the biggest name in politics. See Latest Coverage → Trump’s campaign manager Kellyanne Conway on Wednesday called for a temporary ban on legal immigration to prevent “criminals” from entering the country. The Associated Press contributed to this report.

