# SVAMP_Decomposition_Generation

## Building Question Decomposition Unit using Large Language Models (LLMs)


### **Abstract**: 

Natural Language Processing has seen lots of breakthroughs in the last few
years, most of these advancements are related to transformers and how
multi-headed self-attention networks can show their magic while working with
language. However, Capabilities of these systems have improved far more than
before, still there are some tasks which do not surmise under language generation
tasks based on normal methods. For example, Teaching a language model to
generate logical/ mathematical reasoning to discover the answer to a problem. As
we can infer, It cannot be learned directly using few prompts or even the examples,
even with GPT-3. Now, to get over these limitations of LLMs and make the learning
successful, new approaches have been tried and implemented, after going through
couple of existing prompting methods, new method has been developed to generate
logical extension of the text and used that to teach GPT-3 to decompose the
question into smaller parts and solve this parts one after other to reach the final
answer. To achieve final results LLM BART has been fine-tuned with GPT-3
generated synthetic dataset of decomposed questions. Our approach allowed the
BART model to successfully learn the task.



### To See, Fine-tuned BART live in action, [click here](https://colab.research.google.com/drive/1ltIIQpP-pvqpIRzQSjLqs98u3WWRh1vI?usp=share_link).


### References:

1) Pruthvi Patel, Swaroop Mishra, Mihir Parmar and Chitta Baral. 2022. Is a
Question Decomposition Unit All We Need? arXiv:2205.1253.
2) Tushar Khot, Daniel Khashabi, Kyle Richardson, Peter Clark and Ashish
Sabharwal. 2021. Text Modular Networks: Learning to Decompose Tasks in
the Language of Existing Models. arXiv:2009.0075.
3) Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi
Wang, Dale Schuurmans, Claire Cui, Olivier Bousquet, Quoc Le and Ed Chi.
2022. Least-to-Most Prompting Enables Complex Reasoning in Large
Language Models. arXiv:2250.10625.
4) Pengfei Liu, Weizhe Yuan, Jinlan Fu, Zhengbao Jiang, Hiroaki Hayashi and
Graham Neubig. 2021. Pre-train, Prompt, and Predict. arXiv:2107.13586.
