[Original Questions](https://docs.google.com/document/d/1qYG7Dyy9NqSq9x2F-kccgUy_Rsxiv5hKbqVe5z6LURE/edit?tab=t.0#heading=h.fke682cxqkxr)

## Week 1: AI Past, Present and Future
### 1.2 Forecasting AI Advancements

Which of the following is NOT a reason that forecasting AI capabilities can be useful?
* [ ] To help predict when specific AI capabilities will arise
* [ ] To stimulate further research into AI safety
* [x] To predict the exact architecture of future AI systems
* [ ] To allow policymakers to make informed decisions about AI regulation
* [ ] To mitigate potential risks from advanced AI systems

What is one limitation of using the Turing Test as a measure of artificial general intelligence (AGI)?
* [x] It focuses only on evaluating a narrow range of linguistic tasks
* [ ] Modern non-AGI systems likely already pass versions of it
* [ ] Humans cannot pass it
* [ ] It was designed for older AI systems that are unlike today’s

What is the clearest advantage of using "transformative AI" as a definition compared to AGI?
* [ ] The transformer architecture is the dominant deep learning architecture.
* [x] The concept of a societal transition is easier to understand than general intelligence
* [ ] It focuses on clear real-world impacts rather than intrinsic system properties
* [ ] The technological revolutions provide historical precedents, but not so much for AGI
* [ ] It avoids anthropomorphizing AI systems

[Quiz Reading] According to Alexander 2022 summarizing Cotra 2020, why might FLOP alone not fundamentally drive the development of human-level AI?
* [ ] The quality of FLOP can vary significantly between different models
* [ ] The relationship between compute power (in FLOP) and AI development is not yet fully understood
* [x] Understanding how to create machines that fundamentally think is as vital as compute power
* [ ] FLOP are becoming less common in measuring AI development

What does the "foom" debate refer to?
* [ ] Whether or not TAI is possible
* [ ] If scale is all you need to reach AGI
* [x] Whether AI will be able to quickly self-improve
* [ ] The chance of catastrophe from TAI-like systems

How do "scaling laws" help enable predicting future AI capabilities?
* [x] To strongly relate training loss and computational resources
* [ ] They provide theoretical upper bounds on AI model sizes
* [ ] They model how hardware efficiency improves over time
* [ ] They help identify new algorithms and architectures

What phenomenon poses a challenge to predicting capabilities from scaling laws?
* [ ] Hardware efficiency improvements
* [ ] Algorithmic innovations
* [ ] AI itself improving AI development
* [ ] Emergent abilities
* [x] All of these answers

What approach did the Broken Neural Scaling Laws paper use to try to address the challenge of emergent abilities?
* [ ] Fitting piecewise functions to capture scaling law discontinuities
* [ ] Using easier synthetic tasks to smooth out performance jumps
* [ ] Measuring model internal representations instead of just behaviors
* [x] Focusing on model scaling laws rather than task performance
* [ ] Switching to less brittle versions of performance metrics

Approximately how many FLOP were likely used to train AI systems like GPT-4?
* [ ] 10^8
* [ ] 10^12
* [ ] 10^20
* [x] 10^26
* [ ] 10^30

According to the EpochAI survey, how do judgment-based AI forecasts tend to compare to model-based AI forecasts?
* [ ] Judgments and models are about the same
* [x] Judgments tend to have longer forecasts than models
* [ ] Models tend to have longer forecasts than judgments 
* [ ] Models tend to have less uncertainty in their forecasts than judgments 

[Free Response] Let’s forecast some specific capabilities! 
Reflect on the current state of AI and where it’s going, and write one concrete prediction of something you think AI systems will be capable of that they aren’t yet AND another prediction of what you think they won’t be capable of by the end of this quarter (the final lecture). You won’t be graded on the accuracy of your predictions, though you should aim to be accurate.

Concrete predictions that we can compare at the end of the class.

2/11/25 prediction:
(+) better emotional intelligence
(-) AGI

## Week 2: Outer Alignment - Specifying our Goals
### 2.1 Outer Alignment: Reward Misspecification

What is reward in reinforcement learning?
* [ ] The learning rate used to update the knowledge of the agent.
* [ ] The error calculation between the expected and actual results.
* [ ] A scalar feedback signal that indicates the success of an agent's action in a particular state.
* [x] The process of selecting actions to maximize future rewards.
* [ ] The initial state from which the agent begins its learning journey in an environment.

What is reward misspecification?
* [ ] It is the term used for incorrect computation of the reward received by an agent after taking an action in a state.
* [x] It refers to when the designed reward function in a reinforcement learning system does not accurately represent the true objectives, leading the agent to undesired behavior.
* [ ] It refers to a situation where the agent is unable to receive any reward from the environment.
* [ ] It is the delay between the agent’s action and the corresponding reward signal received.

What is specification gaming / reward hacking?
* [ ] It refers to a situation where the rewards are delayed, causing the agent to be unable to learn efficiently.
* [ ] It is the process of fine-tuning the rewards to improve the learning efficiency of the agent.
* [ ] It refers to the distribution of rewards evenly across all actions to avoid bias in learning.
* [ ] It refers to a scenario where an agent shares its rewards with other agents to enhance cooperative learning
* [x] It refers to an agent finding and exploiting loopholes in the reward function to gain rewards without achieving the intended objective.

What is not an example of sparse or delayed rewards in reinforcement learning?
* [ ] Finding a hidden treasure after exploring various paths in a game.
* [ ] Achieving a high score after solving a puzzle.
* [ ] Winning a race in a video game.
* [x] Experiencing a reduction in health in a video game when being hit by an enemy.


What is AI alignment?
* [ ] It is the process of aligning the artificial intelligence algorithm’s code with software engineering best practices.
* [ ] It refers to the synchronization of multiple AI models to work in unison to solve a complex problem.
* [x] It is the challenge of ensuring that artificial intelligence systems robustly and verifiably align with human values, goals, and safety requirements.
* [ ] It refers to the alignment of data points in a dataset used to train an AI model.
* [ ] It refers to the alignment of an AI’s computational capacity with the required processing power.

Which fact is true about RLHF?
* [x] It involves learning policies from human feedback rather than traditional reward signals, aiding in overcoming issues like reward misspecification.
* [ ] It doesn’t use reinforcement learning techniques for training the agent.
* [ ] It always requires a model of the environment to work efficiently.
* [ ] It is a learning method where human feedback is irrelevant and not used in any part of the learning process.
* [ ] It demands that human feedback is provided in real-time, without any delay.

[Quiz Reading] According to (Worley 2019), what is Goodhardt’s curse?
A well-known methodology for enhancing the performance and efficiency of artificial intelligence by utilizing optimization algorithms.
* [x] The phenomenon when optimizing for a measure of success results in increased likelihood of failure to hit the desired target as a result of the measure ceasing to be a good measure.
* [ ] A theoretical concept in AI alignment referring to the automatic alignment of AI systems with human values through iterative processes.
* [ ] The situation where the optimization of an AI system’s capabilities leads to a substantial decrease in its performance due to excessive computational complexity.
* [ ] The term used to describe a situation when AI systems continuously improve their ability to make predictions, leading to unprecedented advancements in technology.

[Quiz Reading] What was the methodology to aligning language models to follow instructions in (Lowe and Leike 2022)?
* [ ] They collect a dataset of human-written demonstrations, collect a dataset of human-labeled comparisons between two model outputs, and fine-tune the GPT-3 policy using the DDPG algorithm.
* [x] They collect a dataset of human-written demonstrations, use it to train supervised learning baselines, and use the PPO algorithm to maximize the reward predicted by a reward model trained on a dataset of human-labeled comparisons.
* [ ] They collect a dataset of human-written demonstrations, train a reward model on this dataset, and then use this model to make predictions about labeler preferences.
* [ ] They use human-written demonstrations to train supervised learning baselines, collect a dataset of human-labeled comparisons between two model outputs, and then use the DDPG algorithm to fine-tune their GPT-3 policy.

[Quiz Reading] Which limitation was not listed for their approach to aligning language models to follow instructions in (Lowe and Leike 2022)?
* [x] InstructGPT models still generate toxic or biased outputs, make up facts, and generate sexual and violent content without explicit prompting.
* [ ] The models might become more susceptible to misuse if instructed to produce unsafe outputs.
* [ ] The models are working towards refusing certain instructions to mitigate misuse.
* [ ] InstructGPT is trained to follow instructions only in Spanish, showing a bias towards the cultural values of Spanish-speaking people.
* [ ] The models may need to weight the preferences of minority groups more heavily when generating certain text.

[Free Response] How would you define “human preferences”? Alternatively, What should always be guaranteed for humans to be happy?

Human preferences may be what a user of chatbot/LLM's intended goal is as well as be helpful, honest and harmless (Anthropic).

For humans to be happy-- fundamental human rights are practiced (U.S. Constitution)
