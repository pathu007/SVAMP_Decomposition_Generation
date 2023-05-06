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


