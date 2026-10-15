# Preparation

This course uses a **flipped classroom** format: you learn the basics with short videos and readings *before* each session, and we use the sessions for discussion, applying what you learned and working on your team project. The preparation below gets your laptop ready and gives you a first impression of how we work.

**Estimated workload:** about 3.5 hours (videos and reading ≈ 1.5 h, setup and first notebook ≈ 2 h)

**Guiding question:** _What patterns do you see in the pedestrian traffic of Kiel's main shopping street, and what would a shop owner there want to know?_

### After the preparation you will ...

* have a working setup on your own laptop: GitHub account, VS Code (or Cursor), Git, uv and a coding agent,
* know what a coding agent is and how it differs from a chat assistant like ChatGPT,
* be able to _read_ basic Python code (values, variables, lists, function calls, if/else, for loops) well enough to follow what the agent is doing.

### Before the first course session, you should ...

You need **your own laptop** (Windows, macOS or Linux) on which you can install software, and you should bring it to every session.

* [x] **Create accounts** for [GitHub](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github), [Claude](https://claude.ai/), [ChatGPT](https://chatgpt.com/) and [DeepLearning.AI](https://learn.deeplearning.ai/) (free; you do not need a Pro subscription for this course).<br>
* [x] **Install the software** on your laptop:
  * [VS Code](https://code.visualstudio.com/) or alternatively [Cursor](https://cursor.com/download) (both are largely identical), each with the extensions **Python** and **Jupyter**
  * [Git](https://git-scm.com/downloads)
  * [uv](https://docs.astral.sh/uv/getting-started/installation/), which manages Python and all packages for you, so you do **not** need to install Python separately.<br>
* [x] **Get access to a coding agent** – we strongly recommend a Claude Pro subscription for Claude Code (see [Choosing your coding agent](#choosing-your-coding-agent) below).<br>
* [x] **Set up the course environment with the agent:**
  1. Get the [course resources repository](https://github.com/opencampus-sh/intro-to-data-science-and-ml) onto your laptop ("cloning"). The easiest way: in VS Code, click _Clone Git Repository…_ on the welcome page, paste `https://github.com/opencampus-sh/intro-to-data-science-and-ml` and choose a folder. Alternatively, open an empty folder in VS Code and ask your agent: _"Clone https://github.com/opencampus-sh/intro-to-data-science-and-ml into this folder and open it."_ Then open the cloned folder in VS Code.
  2. Paste the setup prompt from the repository's [README](https://github.com/opencampus-sh/intro-to-data-science-and-ml#2-let-the-agent-set-up-the-environment) into the agent. The agent sets up the environment with `uv`, opens the example notebook and runs it.
  3. Keep the agent's command approval switched on and open only the project folder in VS Code, so the agent cannot change anything else on your computer.<br>
* [x] **Explore the example notebook** _"Pedestrians in Kiel's Holstenstraße"_: run it, let the agent explain it to you step by step and write down
  1. one pattern you notice in the data, and
  2. one question a shop owner in the street might ask.

  We will discuss both in the first session.<br>
* [x] **Watch the videos** listed below (≈ 63 minutes). If you have questions about the videos, you can post them in the Element course room (you find the link to the room on the course page on [EduHub](https://edu.opencampus.sh) after logging in).

{% hint style="warning" %}
**Setup not working?** Laptops without admin rights, Chromebooks or very old machines can open the course resources repository in a [GitHub Codespace](https://docs.github.com/en/codespaces/developing-in-a-codespace/creating-a-codespace-for-a-repository) instead, which gives you an identical environment in the browser. If you get stuck, post your question or problem in the **Element chat room of the course** (link on the course page on EduHub) – please do this before the first session so we can start right away.
{% endhint %}

### Choosing your coding agent

A coding agent does more than a chat assistant: it reads the files in your project, plans the steps, writes and runs code, looks at errors and fixes them – and asks for your approval before it executes commands. You are free to choose which agent you use; the course materials and tasks work with all three main options:

{% tabs %}
{% tab title="Claude Code (recommended)" %}
**[Claude Code](https://www.anthropic.com/claude-code)** by Anthropic runs as an extension in VS Code (or Cursor) and in the terminal.

* **Access:** included in the **Claude Pro** subscription for **$20 per month** (or $17 per month with annual billing). The free Claude plan does **not** include Claude Code.
* **Why we recommend it:**
  * The agentic coding videos of this course use Claude Code, so you can follow them one to one.
  * It is the tool the instructors use themselves, so they can help you most directly with tool-specific questions.
  * Free plans of the other tools have tight usage limits that you will hit during the project weeks – exactly when you need the agent most.
* **Tip:** a monthly subscription can be cancelled at any time, so you only need to pay for the months of the course (about three months).
{% endtab %}

{% tab title="Codex" %}
**[Codex](https://openai.com/codex/)** by OpenAI runs as a VS Code extension, in the terminal (Codex CLI) and in the ChatGPT app.

* **Free option:** Codex is included with limited usage in the **free ChatGPT plan**, so the ChatGPT account you create anyway is enough to try it.
* **Limits:** usage is capped within a rolling 5-hour window and only a limited set of models is available. Once you reach the limit, you have to wait or upgrade.
* **Paid options:** ChatGPT Go (about $8 per month) gives somewhat more usage, ChatGPT Plus ($20 per month) considerably more.
{% endtab %}

{% tab title="Cursor" %}
**[Cursor](https://cursor.com/)** is an editor based on VS Code with a built-in agent. If you use Cursor, you do not need to install VS Code.

* **Free option:** the **Hobby** plan is free and includes a limited number of agent requests and tab completions. New accounts usually start with a short trial of the Pro features.
* **Limits:** the free agent requests are typically used up quickly once you work on a real project.
* **Paid option:** Cursor Pro costs $20 per month. Cursor has offered free access for students with a verified university email in the past – check [Cursor's website](https://cursor.com/students) for the current conditions.
{% endtab %}
{% endtabs %}

{% hint style="info" %}
If you start with a free plan, you can complete the preparation and the first weeks with it. We strongly recommend switching to a subscription by week 3 at the latest, when the team project starts. Prices are as of October 2026 and may change.
{% endhint %}

### Videos and materials

**Working with a coding agent**

| Lesson / material | Source | Min |
| --- | --- | --- |
| [uv: Getting started](https://docs.astral.sh/uv/getting-started/) (reading) | uv documentation | 10 |
| [Introduction](https://learn.deeplearning.ai/courses/claude-code-a-highly-agentic-coding-assistant/lesson/66b35/introduction) | Claude Code course | 4 |
| [What is Claude Code?](https://learn.deeplearning.ai/courses/claude-code-a-highly-agentic-coding-assistant/lesson/rrigm/what-is-claude-code%3F) | Claude Code course | 8 |
| [Setup & Codebase Understanding](https://learn.deeplearning.ai/courses/claude-code-a-highly-agentic-coding-assistant/lesson/kkth2/setup-%26-codebase-understanding) | Claude Code course | 13 |

_The videos use Claude Code. If you use Codex or Cursor, the concepts transfer directly; only the commands and menus differ._

**Reading Python code**

| Lesson / material | Source | Min |
| --- | --- | --- |
| [Generative AI in this course](https://learn.deeplearning.ai/specializations/data-analytics/lesson/oi9mu/generative-ai-in-this-course) | Python for Data Analytics, M1 | 2 |
| [Navigating the Jupyter notebook environment](https://learn.deeplearning.ai/specializations/data-analytics/lesson/oxy8o/navigating-the-jupyter-notebook-environment) | Python for Data Analytics, M1 | 3 |
| [Types and expressions](https://learn.deeplearning.ai/specializations/data-analytics/lesson/srr9w/types-and-expressions) | Python for Data Analytics, M1 | 3 |
| [Storing information: variables](https://learn.deeplearning.ai/specializations/data-analytics/lesson/gr436/storing-information%3A-variables) | Python for Data Analytics, M1 | 4 |
| [Creating lists](https://learn.deeplearning.ai/specializations/data-analytics/lesson/hgkuj/creating-lists) | Python for Data Analytics, M1 | 4 |
| [Taking action: calling functions](https://learn.deeplearning.ai/specializations/data-analytics/lesson/whbua/taking-action%3A-calling-functions) | Python for Data Analytics, M1 | 5 |
| [Branching code: if & else](https://learn.deeplearning.ai/specializations/data-analytics/lesson/vrh43/branching-code%3A-if-%26-else) | Python for Data Analytics, M1 | 3 |
| [Repeating actions: for loops](https://learn.deeplearning.ai/specializations/data-analytics/lesson/fm2to/repeating-actions%3A-for-loops) | Python for Data Analytics, M1 | 4 |
| **Total** | | **63** |

### Optional: Python track

If you want to learn to write and review code yourself, the first two weeks of the course are the best time for it, since the workload is still light:

* **Python track for beginners:** the remaining videos of [Python for Data Analytics, Module 1](https://learn.deeplearning.ai/specializations/data-analytics/) (≈ 55 min) plus the two "Air quality in New York City" code labs (≈ 2 h), about 5 hours in total.
* **Alternative:** [AI Python for Beginners](https://learn.deeplearning.ai/courses/ai-python-for-beginners) by Andrew Ng (≈ 11.5 h).
* **Never written any code?** [Build with Andrew](https://learn.deeplearning.ai/courses/build-with-andrew) (≈ 1 h) is a gentle first start.
