# Learning Log

A running record of my progress toward AI Solutioning — built while working through Anthropic's Claude Certified Architect – Foundations prep track and applying what I learn to real work.

---

## September 20, 2026 — AI Fluency: Framework and Foundations

**Source:** Claude Certified Architect – Foundations prep track (1 of 7)
**Verification:** https://academy.claude.com/verify/afd44619153aafc565b5b66e2a57f17c

### What it covered
Foundational framework for working effectively, efficiently, ethically, and safely with AI — the conceptual base before diving into Claude-specific tooling (Code, Agent SDK, API, MCP).

### Key takeaway
The 4Ds of AI Fluency — a framework for effective, ethical human-AI collaboration:

- **Delegation** — deciding what work goes to AI vs. stays human
  - *Problem Awareness*: clearly understanding your own goals before involving AI
  - *Platform Awareness*: knowing what a given AI system can and can't actually do
  - *Task Delegation*: dividing work to leverage human judgment and AI speed/scale together

- **Description** — communicating clearly to get useful results
  - *Product Description*: specifying the desired output (format, tone, length)
  - *Process Description*: guiding how the AI should approach the task
  - *Performance Description*: defining how the AI should behave during the interaction

- **Discernment** — evaluating AI outputs critically, not just accepting them
  - *Product Discernment*: judging the output itself for accuracy and quality
  - *Process Discernment*: evaluating the reasoning/steps behind the output
  - *Performance Discernment*: assessing whether the interaction style actually worked for you

- **Diligence** — taking responsibility for how AI is used
  - *Creation Diligence*: being thoughtful about which AI systems/tools you choose
  - *Transparency Diligence*: being honest about AI's role with anyone who needs to know
  - *Deployment Diligence*: taking accountability for verifying and vouching for outputs you use or share

### How it connects to my work
This gives me a reusable framework for any task I delegate to AI going forward:

- **Delegation**: Decide upfront which parts of a task are good candidates for AI drafting versus which need to stay human-owned (judgment calls, context only I have).
- **Description**: Output quality depends heavily on how well I describe the desired result, the approach, and the interaction style — not just the end ask.
- **Discernment**: Every AI-assisted output still needs review before it's used or shared — checking the reasoning behind it, not just the final result.
- **Diligence**: Being transparent about which parts of any shared work were AI-assisted, and owning the final result regardless of how it was produced.

---

## September 26, 2026 — Claude 101

**Source:** Claude Certified Architect – Foundations prep track (2 of 7)
**Verification:** https://academy.claude.com/verify/784fdfc319a66f57f49bee51da510bcc

### What it covered
Foundational concepts of Claude.ai Projects — self-contained workspaces with their own memory, knowledge base, and custom instructions, including how they scale and support team collaboration.

### Key takeaway
- **Projects** are self-contained workspaces with their own memory, chat history, knowledge base, and instructions — dedicated environments per workstream rather than one undifferentiated chat history.
- **Project knowledge** lets you upload reference documents once; Claude references them across every chat in that Project, eliminating repeated re-uploading.
- **Project instructions** set tone, expertise level, and response style at the Project level, applying automatically to every conversation inside it.
- **Automatic scaling**: as a knowledge base approaches context limits, Claude shifts to searching and retrieving only what's relevant — expanding effective capacity up to 10x without losing response quality.
- **Team collaboration** (Claude for Work): Projects can be shared so a whole team works from the same context, instructions, and accumulated knowledge.

### How it connects to my work
Gives me a model for setting up a persistent, configured workspace for any recurring task or topic — knowledge and instructions accumulate over time instead of being re-established in every new chat.

---