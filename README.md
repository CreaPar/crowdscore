# Crowd Score: A Method for the Evaluation of Jokes using Large Language Model AI Voters as Judges

This paper presents a novel method for the evaluation of jokes using a crowd of AI voters as judges. We assume that machines, like humans, can judge the creativity of artefacts, using their own intrinsic evaluation metrics. To validate this, we propose the Crowd Score, a method to assess creative artefacts with large language models (LLMs) by inducing different personalities on them and aggregating their votes into a single score. We apply this method to assess the funniness of 52 jokes from a humour dataset, using four AI voters with different humour types: affiliative, self-enhancing, aggressive and self-defeating. Our results show that few-shot prompting leads to better results than zero-shot for the voting question, and that zero-shot personality induction can significantly influence the funniness rating of certain jokes. The Crowd Score is very close to the score for few-shot without the crowd, which could indicate that this particular crowd, and respectively Crowd Score, represents the average of the existing voters. We believe that our method can be applied to other creative domains and could help the adoption of a flexible and accurate standard approach to compare different work in the Computational Creativity community.

The Jupyter Notebook to conduct the experiments is available in this repository. If you like to reference this paper, please refer to:

Fabrício Góes, Zisen Zhou, Piotr Sawicki, Marek Grzes and Daniel G. Brown, "Crowd Score: A Method for the Evaluation of Jokes using Large Language Model AI Voters as Judges", Arxiv, 2022.

If you use the same dataset, please reference:

J. Toplyn, “Witscript 2: A system for generating improvised jokes without wordplay,” in Proceedings of the International Conference on Computational Creativity 2022, A. G. de Silva Garza, T. Veale, W. Aguilar, and R. P. y Pérez, Eds. Association for Computational Creativity (ACC), 2022, pp. 22–31.
