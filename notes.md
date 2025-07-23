# Notes

I'll try to implement stuff in tinygrad so that it can be converted into a c program later.
Will have to see how that works. If not, I'll just write it in c.

[Here](http://prize.hutter1.net/hfaq.htm#specomp) it says that the top compressors
would have components that apply to language modeling or learning in general instead of 
it being specific to enwik9. There needs to be a clear understanding of which stuff 
is transferable. 

Is there any practical use of these compressors? Can one create a useful language model 
from them? Can they be run on a gpu? Can we train on the internet using these compressors?
There has to be an attempt to make practical use of these compressors or the techniques 
present in them. There needs to be a bridge between this and the overall NLP field. 


[Continual learning](https://arxiv.org/pdf/2306.13812) from rich sutton. Is a useful idea here.
Since the learning would have to be online. [This](https://openreview.net/pdf?id=Hygi7xStvS) paper
also includes useful techniques like revisiting past data. The paper uses enwik8. The FAQ [here](http://prize.hutter1.net/hfaq.htm#largenn)
says that NNs are too slow for enwik9 for now. 

Intuitively I feel that NNs should be the solution to the hutter prize. We just gotta make them
run fast and learn quickly. Techniques that allow the NNs to learn quickly and run fast is what we want
to go for.

In [cmix](https://www.byronknoll.com/cmix.html), there is a dictionary for enwik9. Would that be 
helpful for an NN as well. Is the dictionary the ideal way to have maximum compression of the symbols?
Would [BPE](https://huggingface.co/learn/llm-course/en/chapter6/5) or something work here? 

Techniques that help NNs, run fast and learn quickly. Continual learning is one of them. 
Pruing, Quantization help too. Learning rate tricks. Should look into [llama2.c](https://github.com/karpathy/llama2.c).

NNs require more data to learn better. A way to improve an NN's performance is to get more and better data. 
Here we don't really have more data. 




