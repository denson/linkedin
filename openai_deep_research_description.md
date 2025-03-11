OpenAI’s Deep Research is an advanced, agentic tool built into ChatGPT Pro that automates complex, multi-step research tasks. It leverages a specialized version of OpenAI’s o3 model—optimized for extended “reasoning” and web browsing—to gather, analyze, and synthesize information from diverse sources (text, images, PDFs, etc.) into a comprehensive, well-cited report.

### What It Does

- **Multi-Step Research:** Unlike standard ChatGPT sessions that deliver quick responses, Deep Research takes several minutes (typically 5–30 minutes) to produce detailed analyses. It performs iterative web searches, reads and interprets multiple documents, and cross-references data to extract nuanced insights.
- **Iterative Clarification:** Before diving into a task, the tool asks follow-up questions to clarify the user’s request. This helps shape a focused research plan and leads to more accurate, tailored outputs.
- **Structured Reporting:** The final output is a coherent report complete with sections, tables, graphs, and in-line citations. This structure makes it easy to verify sources and ensures the research is both thorough and transparent.
- **Tool-Assisted Analysis:** Deep Research can execute Python code in a sandboxed environment for data analysis or visualization, allowing it to process numerical data or create graphical summaries as needed.

### How It Works

- **Advanced Reasoning & Chain-of-Thought:** At its core, Deep Research uses an internal chain-of-thought mechanism—honed through reinforcement learning on browsing tasks—to “think” through complex queries. Although this chain-of-thought is hidden from users, it underpins the model’s ability to self-correct and refine its output iteratively.  
  citeturn0search6

- **Web Browsing & Data Aggregation:** The system is trained on specialized browsing datasets. It navigates the web in real time, clicking through multiple pages and consulting a wide variety of online sources to compile information that is often beyond its static training data.  
  citeturn0search0

- **Iterative Refinement:** Deep Research is designed to improve its answers through a multi-round process. Initially, it drafts an outline or plan, then uses additional tool calls and iterative feedback to enhance its analysis and fill in any gaps, much like a human researcher revising a draft.
  citeturn0search1

- **Safety & Verification Measures:** With integrated safeguards, the model checks for disallowed or unreliable content, and it provides citations so that every claim can be traced back to its source. This process minimizes hallucinations and enhances the trustworthiness of the report.
  citeturn0search6

### Informing an LLM for Iterative Improvement

When using Deep Research as part of an iterative improvement plan, consider structuring your prompts to:

1. **Clarify Objectives:** Start by outlining what you need—be specific about the questions to answer, the data required, and any preferred formats (e.g., detailed report, summary, tables).
2. **Request a Research Blueprint:** Ask for an initial research plan or outline using a smaller, faster model to save on resources, then feed that into Deep Research for deeper analysis.
3. **Iterate with Feedback:** Incorporate feedback loops where the model refines its output after presenting an initial draft. Specify that you need clarifications or additional details in subsequent rounds.
4. **Ensure Citations and Verification:** Emphasize the need for inline citations and source verification to make the final output reliable.

By using these strategies, you can leverage Deep Research to conduct highly detailed and iterative investigations, turning complex research tasks into manageable, step-by-step processes.

This summary should provide a solid foundation for an LLM tasked with writing a prompt/plan that harnesses Deep Research for iterative improvements.
