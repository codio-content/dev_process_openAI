##

One of the breakthroughs with the GPT-3 model is the generation of text that seemingly comes from a human. While there are many obvious benefits to this, there are also many obvious risks. OpenAI released a [paper](https://arxiv.org/abs/2005.14165) in which they dedicate an entire section to the broader impacts of this technology. Specifically, they talk about the misuse of language models; fairness, bias, and representation; and energy usage.

OpenAI recommends several key principles to help providers of large language models (LLMs) mitigate the risks of this technology in order to achieve its full promise to augment human capabilities. As LLM providers, these principles are published in order to represent a first step in collaboratively guiding safer large language model development and deployment.

### Prohibit Misuse
* Prohibit material harm to individuals, communities, and society such as through spam, fraud, or astroturfing.
* Build systems and infrastructure to enforce usage guidelines. This may include rate limits, content filtering, application approval prior to production access, monitoring for anomalous activity, and other mitigations.

### Mitigate Unintentional Harm
* Proactively mitigate harmful model behavior. Best practices include comprehensive model evaluation to properly assess limitations, minimizing potential sources of bias in training corpora, and techniques to minimize unsafe behavior such as through learning from human feedback.
* Document known weaknesses and vulnerabilities, such as bias or ability to produce insecure code, as in some cases no degree of preventative action can completely eliminate the potential for unintended harm. Documentation should also include model and use-case-specific safety best practices

### Thoughtfully Collaborate with Stakeholders
* Build teams with diverse backgrounds and solicit broad input. Diverse perspectives are needed to characterize and address how language models will operate in the diversity of the real world, where if unchecked they may reinforce biases or fail to work for some groups.
* Publicly disclose lessons learned regarding LLM safety and misuse in order to enable widespread adoption and help with cross-industry iteration on best practices.
* Treat all labor in the language model supply chain with respect. For example, providers should have high standards for the working conditions of those reviewing model outputs in-house and hold vendors to well-specified standards (e.g., ensuring labelers are able to opt out of a given task).