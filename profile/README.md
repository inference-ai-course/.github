# Machine Learning Engineer in the Generative AI Era

Welcome to the official repository for the **Machine Learning Engineer in the Generative AI Era** course series!

This class is designed for hands-on, open-source practice with the latest tools in Large Language Models (LLMs), agentic AI, and data engineering. All lectures, code, and homework are here:

👉 **[MLE_in_Gen_AI_Course](https://github.com/inference-ai-course/MLE_in_Gen_AI-Course)**

## Homework Submission:
Follow the instructions in the course repository: [Course link](https://github.com/inference-ai-course/MLE_in_Gen_AI-Course) 
Submit your homework by creating your own branch in the designated homework repository.

How to create your branch:

 • Create a new branch from the main branch.
 
 • Name it using your name or NetID (e.g., scott-lai or ql123).
 
 • Commit your work to this branch and open a pull request for review.

```
# Create your branch
git checkout -b "First-Last"  # Example: Scott-Lai

# Check changes
git status

# Stage changes
git add <file-name>           # Add specific file
# or
git add .                     # Add all changes

# Commit changes
git commit -m "Describe your change"

# Push branch
git push --set-upstream origin "First-Last"

# Open a Pull Request (PR)
# Use the link shown after push, or open a PR on GitHub.

# PR must include (in Markdown):
## Description
- What did you change or add?

## What I Learned
- Key takeaways from this homework.

## Bugs/Issues
- What problems or errors you encountered.

## Learn More
- Topics you want to explore further.
```

**[Homework1](https://github.com/inference-ai-course/Homework1-Submission)**,
**[Homework2](https://github.com/inference-ai-course/Homework2-Submission)**,
**[Homework3](https://github.com/inference-ai-course/Homework3-Submission)**,
**[Homework4](https://github.com/inference-ai-course/Homework4-Submission)**,
**[Homework5](https://github.com/inference-ai-course/Homework5-Submission)**,
**[Homework6](https://github.com/inference-ai-course/Homework6-Submission)**,
**[Homework7](https://github.com/inference-ai-course/Homework7-Submission)**,
**[Homework8](https://github.com/inference-ai-course/Homework8-Submission)**,
**[Homework9](https://github.com/inference-ai-course/Homework9-Submission)**,
**[Homework10](https://github.com/inference-ai-course/Homework10-Submission)**

## Project Submission:

For the Projects submission, please following the save steps as homework submission. 

**[project1](https://github.com/inference-ai-course/Project1-submission)**,
**[project2](https://github.com/inference-ai-course/Project2-submission)**,
**[project3](https://github.com/inference-ai-course/Project3-submission)**


---

## 📚 Course Structure

The course spans  **10 weeks** , guiding you through foundational topics in LLMs and culminating in building your own research agent.

### Week-by-Week Breakdown

| Week | Topic                                    | Themes & Activities                                           |
| ---- | ---------------------------------------- | ------------------------------------------------------------- |
| 1    | Intro to LLMs & Prompt Engineering       | GenAI & agents, LLM capabilities, CO-STAR, structured outputs |
| 2    | LLM Architecture & Training Lifecycle    | Transformers, SFT, DPO/PPO, hallucinations, inference         |
| 3    | Pretraining Data Collection & Extraction | Web scraping, OCR, ASR, data cleaning/filtering               |
| 4    | Retrieval-Augmented Generation (RAG)     | Embeddings, chunking, vector DBs, LangChain, RAG workflows    |
| 5    | Supervised Fine-Tuning (SFT) I           | Full vs. LoRA finetuning, ChatML, Deepspeed, TRL              |
| 6    | Supervised Fine-Tuning (SFT) II          | Synthetic data, LLM-as-judge, ablation studies                |
| 7    | Model Alignment                          | RLHF, DPO/PPO, reward models, preference labeling             |
| 8    | Hallucination, Jailbreak, Ethics         | Safety alignment, jailbreaking, hallucination prevention      |
| 9    | Voice Agent (Multimodal AI)              | GPT-4o real-time, ASR/TTS, audio pipelines                    |
| 10   | Capstone: Agent & Project Demos          | Agents, function calls, MCP protocol, end-to-end workflow     |

For detailed lecture topics and slides, check the  **[Lecture Materials folder](https://github.com/inference-ai-course/MLE_in_Gen_AI_Course)** .

---

## 📝 Homework & Assignments

* Each week has a hands-on **homework assignment** posted in this repo.
* Homework tasks are designed to reinforce the lecture, using the newest open-source models and libraries (see `homework/` and `lecture_code/` directories).

**Homework Submission Workflow:**

1. **Create your own private repo by fork** (recommended: `MLE_HW_<yourname>`).
2. Complete all homework assignments in  **one single repo** .
3. When you finish each homework, **push your work** to your repo.
4. Create a pull request from your own forked repo. [What is Pull Request (PR)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
5. **Submit the link of Pull Request** via the Canvas Assignments section.
6. For each project milestone (see below), **create a new repo** and submit the link via Canvas.

---

## 🚀 Projects

**Course Project:**

Your project is to build a personalized research agent, applying all you’ve learned:

* Week 1: Project kickoff, define your agent’s goal
* Week 4: Project Insight I (peer/TA review of your idea)
* Week 7: Project Insight II (finalize scope and direction)
* Week 10: Final project demo—showcase your agent!

**Project Rules:**

* **All code must be in your own GitHub repo.**
* Submit your **project repo link** via Canvas when prompted.
* All submissions must be your own work—collaboration for discussion and Q&A is encouraged, but code must be original.

---

## 🗂️ Repo Structure

* `lecture_slides/` — PDF and PPTX slides for each week
* `lecture_code/` — Code walkthroughs and demo notebooks for lectures
* `homework/` — Homework assignment descriptions and starter code
* `project_guidelines.md` — Tips and requirements for the course project

---

## 📣 Community

* **Join the course Discord:** For Q&A, code sharing, project brainstorming, and peer support.
* **Peer Feedback:** Comment on at least two peers’ project ideas (via Discord or Canvas discussion).
* **MCP & Open Tools:** You’ll set up and experiment with tools like MCP (Model Context Protocol) and the latest open-source agents (LangChain, vLLM, etc).

---

## 🛠️ Submission Rules & Best Practices

* **Homework:**
  * Complete all tasks in one repo.
  * Submit via Canvas—**paste your GitHub repo link** for each week’s assignment.
* **Project:**
  * Each project phase (insight, final demo) requires a **separate repo** submission via Canvas.
* **Repo Organization:**
  * Use clear folders, commit messages, and documentation.
  * Cite all outside resources and credit all collaborators.

---

## 🔗 Useful Resources

* [Course Repo (Lectures, Code, Homework)](https://github.com/inference-ai-course/MLE_in_Gen_AI_Course)
* [HuggingFace Model Hub](https://huggingface.co/)
* [LangChain Documentation](https://docs.langchain.com/)
* [vLLM Docs](https://docs.vllm.ai/en/latest/)
* [MCP Protocol GitHub](https://github.com/modelcontextprotocol/servers)

---

## 📝 Example Submission Flow

```markdown
# Example: Homework Submission

1. Create a repo: `MLE_HW_johndoe`
2. Complete and commit all homework notebooks and scripts.
3. Push to GitHub `git push origin main`.
4. Create PR from `MLE_HW_johndoe:main` into `MLE_in_Gen_AI-Course:main`.
5. Submit the link of PR on Canvas, [example link](https://github.com/inference-ai-course/MLE_in_Gen_AI-Course/pull/7).

# Example: Project Submission

1. Create a new repo: `MLE_Project_johndoe`
2. Add project code, readme, and demo notebooks.
3. Push to GitHub.
4. Submit: https://github.com/johndoe/MLE_Project_johndoe via Canvas.
```

---

## 📅 Course Schedule At a Glance

| Milestone          | When?       | What?                                |
| ------------------ | ----------- | ------------------------------------ |
| Project Kickoff    | Week 1      | Start brainstorming, join Discord    |
| Project Insight I  | Week 4 (TA) | Share idea, peer/TA feedback         |
| Project Insight II | Week 7 (TA) | Lock in final project direction      |
| Final Presentation | Week 10     | Demo, submit repo, share reflections |

---

Questions? Post in Discord or open an issue in the main repo!
