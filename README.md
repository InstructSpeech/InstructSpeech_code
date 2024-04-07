# InstructSpeech

To all reviewers, ACs, and PCs:

We thank all reviewers for the valuable suggestions with their effort and time. Your comments have improved our work. Here we summarize our effort in addressing reviewers' concerns, and please refer to the responses to each reviewer for more details.

**[Extensive experimental comparison and evaluation with baseline models.]**

- Per the reviewers' suggestions, we include comparison studies with several baselines on the benchmark zero-shot TTS tasks in speaker transferring. InstructSpeech achieves superior results by training on an extensive and diverse set of tasks at the scale of around 100K hours, including both speech editing and speech processing tasks to enhance its capabilities. 

- Per the reviewers' suggestions, we include comparison studies with external cascaded models on free-form speech editing. The decomposition to multiple sub-tasks significantly tackles the challenges of accurately locating and manipulating the target context following the user's instruction, enabling InstructSpeech to reach the answer in a step-by-step thought process without relying on external models.

- In response to the reviewer's question, we further include subjective evaluation in semantic content editing by respectively scoring MOS and SMOS. It indicates that raters prefer our model synthesis against baselines in terms of speech intelligibility and style similarity, which is consistent with the objective evaluation results.

**[More detailed explanations on model design.]**

- In response to the reviewer's question, we decompose free-form semantic editing into multiple sub-tasks and prompt InstructSpeech in a step-by-step process, replacing CoT with ``multi-step reasoning''.

- In response to the reviewer's question, we edit phone sequences instead of words following speech editing systems for a fair comparison.

- As shown in our responses, we present the high accuracy of emotion and style classifiers which serve as metrics to evaluate similarity.

- For the training dataset, we present the construction of LibriTTS-style dataset and explain the energy editing scale as well as duration change flexibility.

**[More precise definitions and presentation.]**

- As shown in our responses, we provide more precise definitions for different text encoders and adaptation prompts.

- Per the reviewers' suggestions, we include a discussion on parallel codebook patterns and related works (AudioBox and VoiceBox).

- Per the reviewers' suggestions, we explain Algorithm 1 and refine citations or typos for a more precise presentation.



**In the meanwhile, we revise the manuscript according to the comments and suggestions of reviewers. In this rebuttal phase, we have tried to address them carefully, and we sincerely hope you can consider increasing your score if you find our reply solves your concern. We are always happy to have a further discussion and answer more questions raised by you.**
