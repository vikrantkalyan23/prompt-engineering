# Prompt Engineering — Complete learning roadmap



Basic to Advanced | LLMs • RAG • Tool Calling • Agents • Evaluation • Security • Production



A structured learning roadmap for developers and AI/ML practitioners



## How to Use This 



Follow the modules sequentially. Build small exercises after each module and a production-style LLM application after the advanced modules. The syllabus moves from prompt fundamentals to modern LLM application engineering.



## Learning Outcomes



Understand how LLMs process prompts, tokens, context, and instructions.



Design clear, reliable prompts for text, coding, extraction, classification, and analysis.



Use zero-shot, one-shot, few-shot, role, structured, and decomposition techniques.



Build prompt templates and multi-step LLM workflows.



Design RAG prompts using retrieval, grounding, citations, and context management.



Use structured outputs, function/tool calling, and external systems safely.



Understand prompt injection, data leakage, jailbreaks, and LLM security.



Create evaluation datasets, metrics, regression tests, and prompt versions.



Optimize prompts for quality, latency, cost, and maintainability.



Design agentic workflows with planning, tools, memory, and human-in-the-loop controls.



## At a Glance



Module 1: AI/LLM Foundations



Module 2: Prompt Engineering Fundamentals



Module 3: Prompt Anatomy and Design



Module 4: Core Prompting Techniques



Module 5: Few-Shot and Pattern-Based Prompting



Module 6: Reasoning, Decomposition, and Verification



Module 7: Structured Outputs and Data Extraction



Module 8: Prompt Templates and Production Design



Module 9: Context Engineering



Module 10: RAG Prompt Engineering



Module 11: Tool and Function Calling



Module 12: Agents and Agentic Workflows



Module 13: Prompt Security



Module 14: Prompt Evaluation



Module 15: Optimization, Cost, and Performance



Module 16: PromptOps and Production



Module 17: Advanced LLM Application Patterns



Module 18: Capstone Projects



# Module 1 — AI and LLM Foundations



Learn the concepts needed to understand why prompts affect model behavior.



Artificial Intelligence, Machine Learning, Deep Learning, Generative AI



What is an LLM and what problems does it solve?



Pre-training, instruction tuning, alignment, and inference



Transformer architecture at a conceptual level



Attention and self-attention



Tokens and tokenization



Context window and context length



Parameters and model scale



Next-token prediction



Temperature, top-p, and sampling concepts



Deterministic vs stochastic generation



Model limitations and hallucinations



Knowledge cutoff vs live/current information



Why prompting changes model behavior



# Module 2 — Prompt Engineering Fundamentals



Understand prompt engineering as the design of instructions and context for a target behavior.



Definition and purpose of prompt engineering



Prompt engineering vs prompt writing



Prompt engineering vs fine-tuning



Prompt engineering vs RAG



When prompting is enough



When to use RAG



When to use tools



When to fine-tune



Task definition and objective clarity



Audience definition



Constraints and requirements



Expected output specification



Quality criteria



Assumptions and ambiguity management



# Module 3 — Prompt Anatomy and Design



Learn the reusable components of professional prompts.



Role / persona



Objective / task



Context



Input data



Constraints



Examples



Output format



Quality criteria



Tone and style



Delimiters



Instruction hierarchy



Positive instructions



Negative constraints



Explicit success criteria



Fallback behavior



Clarification rules



# Module 4 — Core Prompting Techniques



Master the most commonly used prompt patterns.



Zero-shot prompting



One-shot prompting



Few-shot prompting



Instruction prompting



Role prompting



Contextual prompting



Task decomposition



Step-by-step task specification



Prompt chaining



Iterative prompting



Critique and revision loops



Self-check / verification prompts



Comparison prompts



Transformation prompts



Summarization prompts



Classification prompts



Generation prompts



Extraction prompts



# Module 5 — Few-Shot and Pattern-Based Prompting



Learn how examples control formatting, classification, and domain-specific behavior.



Choosing good examples



Positive examples



Negative examples



Edge-case examples



Example diversity



Example ordering



Example consistency



Input/output demonstrations



Classification examples



Information extraction examples



Code transformation examples



Style transfer examples



Few-shot limitations



Example contamination and ambiguity



Dynamic example selection



# Module 6 — Reasoning, Decomposition, and Verification



Learn practical approaches for difficult reasoning tasks without depending on hidden chain-of-thought.



Complex vs simple task identification



Task decomposition



Intermediate artifacts



Plan-then-execute workflows



Generate-then-verify workflows



Critique-and-revise workflows



Self-consistency concepts



Multiple candidate generation



Evidence-based answers



Assumption extraction



Calculation verification



Unit and constraint checking



Test-case driven prompting



When to use an external calculator/tool



Limits of model reasoning



# Module 7 — Structured Outputs and Data Extraction



Learn how to turn free-form model output into reliable application data.



Why structured output matters



JSON output



JSON Schema



Typed objects



Enums



Arrays and nested structures



Required vs optional fields



Schema validation



Parsing failures



Retry strategies



Extraction from documents



Entity extraction



Classification schemas



Normalization



Output sanitization



Application-level validation



# Module 8 — Prompt Templates and Production Design



Move from one-off prompts to reusable application prompts.



Static prompts vs dynamic prompts



Prompt templates



Template variables



Conditional prompt sections



Reusable system instructions



Prompt composition



Prompt versioning



Environment-specific prompts



Prompt configuration



Prompt registries



Template testing



Prompt naming conventions



Prompt documentation



Backward compatibility



Prompt change management



# Module 9 — Context Engineering



Learn how to decide what information the model should receive and how it should be organized.



Context engineering vs prompt engineering



Context selection



Context relevance



Context ordering



Context prioritization



Conversation history



Long-context management



Context compression



Summarization memory



Sliding-window history



State management



User profile context



Task state



Tool results as context



Avoiding context pollution



Context budget management



# Module 10 — RAG Prompt Engineering



Design prompts for grounded answers using external knowledge.



What is Retrieval-Augmented Generation?



RAG architecture



Document ingestion



Chunking



Embeddings



Vector databases



Semantic search



Keyword / hybrid search



Metadata filtering



Retrieval top-k



Reranking



Context assembly



Grounded answering



Citation prompting



Source attribution



Unknown-answer behavior



Context relevance instructions



RAG hallucination control



RAG evaluation



RAG failure analysis



# Module 11 — Tool and Function Calling



Learn how prompts coordinate LLMs with external tools and APIs.



Why tools are needed



Tool descriptions



Function schemas



Tool arguments



Tool selection



Tool result handling



Multiple tools



Tool routing



Database tools



Search tools



Calculator tools



HTTP/API tools



Email/calendar tools



Error handling



Tool authorization



Least-privilege tool access



Human approval for sensitive actions



Tool output validation



# Module 12 — Agents and Agentic Workflows



Learn how prompting evolves into multi-step autonomous workflows.



What is an AI agent?



Agent vs chatbot



Agent loop



Planning



Execution



Observation



Reflection



Tool use



State and memory



Task decomposition



Multi-agent patterns



Supervisor agents



Router agents



Specialist agents



Human-in-the-loop



Approval gates



Agent termination conditions



Agent failure recovery



Agent evaluation



Agent safety



# Module 13 — Prompt Security



Learn the security risks specific to LLM applications.



Prompt injection



Direct prompt injection



Indirect prompt injection



Jailbreaks



Instruction conflicts



Untrusted retrieved content



Untrusted tool output



Data exfiltration



Sensitive information leakage



System prompt leakage



Tool abuse



Excessive agency



Authorization boundaries



Least privilege



Input validation



Output validation



Content filtering



Sandboxing



Rate limiting



Audit logging



Security testing



# Module 14 — Prompt Evaluation



Learn how to measure prompt quality rather than relying on intuition.



Why prompt evaluation matters



Golden datasets



Representative test cases



Edge cases



Adversarial test cases



Expected outputs



Human evaluation



Automated evaluation



LLM-as-judge concepts



Exact-match evaluation



Semantic similarity



Classification metrics



Format compliance



Groundedness



Faithfulness



Hallucination rate



Safety evaluation



Regression testing



A/B testing



Evaluation dashboards



# Module 15 — Optimization, Cost, and Performance



Optimize prompts and workflows for production constraints.



Token economics



Input vs output tokens



Prompt length optimization



Context compression



Caching



Prompt caching concepts



Model selection



Latency optimization



Parallel calls



Batching



Streaming



Retry strategy



Timeouts



Fallback models



Cost-quality tradeoffs



Accuracy-quality tradeoffs



Prompt complexity vs performance



Reducing unnecessary tool calls



# Module 16 — PromptOps and Production



Treat prompts as software assets that require lifecycle management.



Prompt version control



Prompt changelogs



Prompt ownership



Prompt review



Prompt testing in CI/CD



Regression suites



Observability



Tracing



Latency monitoring



Token usage monitoring



Cost monitoring



Error monitoring



Feedback collection



Production failure analysis



Rollback strategies



Environment management



Secrets and configuration



Model/provider abstraction



# Module 17 — Advanced LLM Application Patterns



Study advanced architectures used in real AI products.



Router architectures



Model routing



Small model + large model patterns



Generate-verify pipelines



Classifier + generator pipelines



RAG + tools



Structured extraction + database storage



Human-in-the-loop systems



Memory architectures



Long-running workflows



Event-driven LLM workflows



Multi-agent systems



Workflow orchestration



Guardrails



Policy enforcement



Fallback and recovery



AI observability



Multi-tenant prompt architecture



# Module 18 — Hands-On Projects



## Project 1 — Prompt Playground



Build a small UI/API that lets users compare multiple prompt versions and outputs.



## Project 2 — Sentiment Analyzer



Create prompts for positive/negative/neutral classification and structured JSON output.



## Project 3 — Resume Analyzer



Extract skills, experience, education, and missing information into a validated schema.



## Project 4 — SQL Assistant



Convert natural language to SQL with schema context, constraints, and validation.



## Project 5 — Code Review Assistant



Review code against correctness, security, performance, and style criteria.



## Project 6 — RAG Chatbot



Build a document Q&A system with retrieval, grounding, citations, and unknown-answer behavior.



## Project 7 — Tool-Calling Assistant



Create an assistant that calls calculator, database, search, or API tools.



## Project 8 — Prompt Evaluation System



Create a golden dataset and automated regression suite for prompt versions.



## Project 9 — Secure AI Assistant



Implement prompt-injection defenses, authorization, tool restrictions, logging, and validation.



## Project 10 — Agentic Developer Assistant



Build a controlled multi-step agent that plans tasks, uses tools, validates results, and stops safely.



## Professional Prompt Design Framework



Use the following R-T-C-C-E-O framework as a practical starting point:



R — Role: Who should the model act as?



T — Task: What exactly should it do?



C — Context: What information does it need?



C — Constraints: What rules or restrictions apply?



E — Examples: What examples demonstrate the desired behavior?



O — Output: What exact structure or format is required?



ROLE:

You are a senior backend architect.



TASK:

Design a scalable authentication system.



CONTEXT:

Multi-tenant SaaS using NestJS, PostgreSQL, TypeORM, Redis and JWT.



CONSTRAINTS:

- Secure password hashing

- Tenant isolation

- Rate limiting

- Avoid unnecessary dependencies



OUTPUT:

1. Architecture

2. Database schema

3. API endpoints

4. Authentication flow

5. Security risks

6. Test strategy

7. Production considerations



## Final Prompt Engineering Checklist



- [ ] Is the objective clear?



- [ ] Is the task specific?



- [ ] Is enough relevant context provided?



- [ ] Is the audience defined?



- [ ] Are constraints explicit?



- [ ] Is the output format defined?



- [ ] Are examples required?



- [ ] Are instructions separated from data?



- [ ] Could the input contain malicious instructions?



- [ ] Does the model need external knowledge?



- [ ] Should RAG be used?



- [ ] Should a tool be used?



- [ ] How will the output be validated?



- [ ] How will quality be evaluated?



- [ ] Is the prompt unnecessarily long?



- [ ] Is cost acceptable?



- [ ] Is latency acceptable?



- [ ] Is there a fallback if the model fails?



- [ ] Is the prompt versioned and tested?



## Recommended Learning Sequence



Learn LLM fundamentals, tokens, context, sampling, and model limitations.



Master prompt anatomy: role, task, context, constraints, examples, output.



Practice zero-shot, one-shot, few-shot, classification, extraction, and transformation.



Learn decomposition, verification, and multi-step prompt workflows.



Master structured outputs and schema validation.



Learn context engineering and long-context management.



Build RAG systems with grounding and citations.



Learn tool/function calling and secure tool access.



Study agents, memory, planning, and human approval workflows.



Build prompt evaluation datasets and regression tests.



Learn prompt security and adversarial testing.



Optimize for cost, latency, quality, and reliability.



Implement PromptOps and production observability.



Complete the capstone projects.



## Key Principle



The goal of prompt engineering is not to create the longest prompt. The goal is to create the clearest, smallest, testable prompt or workflow that reliably produces the required result.