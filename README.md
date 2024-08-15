# Multi-Agentic workflow for Multi-modal AI usecase
Understanding and implementing the multi-agentic workflow for multi-modal AI usecases

__________________________________________

# AgentCoder architecture

![](https://github.com/joshir199/Multi-Agentic-workflow-for-Multi-modal-AI-usecase/blob/main/multi-agent%20coder%20workflow.png)

------------------------------------------------->      Image from AgentCoder paper

It uses 3 agents to complete the overall task as per above workflow.

1. The Programmer Agent  : It is powered by LLMs and responsible for code generation based on required problem statement.
2. The Test Designer Agent : It is powered by LLMs other than above and responsible for designing & generating test cases independently for required problem statement.
3. The Test Executor Agent : It is implemented by Prython script interacting with local environment. It is responsible for executing test cases against the code generated and provide feedback.

