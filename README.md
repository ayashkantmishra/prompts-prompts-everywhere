# prompts-prompts-everywhere

A small, opinionated collection of LLM prompts for academic research — built around the
day-to-day workflow of a Software Engineering PhD, but general enough for any field.

The prompts move through the natural arc of a research task:

> **learn a topic → read the literature → brainstorm ideas → evaluate ideas → write it up**

Each prompt is a plain `.txt` file. Copy the contents into your assistant of choice
(Claude, ChatGPT, etc.), fill in the bracketed placeholders, and go.

## Contents

| Stage | Prompt | Use it when you want to… |
|-------|--------|--------------------------|
| Learn | [Topic Learnig Prompt.txt](Topic%20Learnig%20Prompt.txt) | Get a structured, ground-up explanation of an unfamiliar topic (intuition first, then formalism). |
| Learn | [Topic Learnign Prompt Short.txt](Topic%20Learnign%20Prompt%20Short.txt) | Same, but a lightweight one-shot version for quick lookups. |
| Read | [Paper Reading Prompt.txt](Paper%20Reading%20Prompt.txt) | Dissect a paper — contributions, method, assumptions, limitations, and how it relates to your work. |
| Ideate | [Research Brainstorm Prompt.txt](Research%20Brainstorm%20Prompt.txt) | Generate and pressure-test research directions in depth. |
| Ideate | [Research Brain Storm Prompt - Short.txt](Research%20Brain%20Storm%20Prompt%20-%20Short.txt) | Fast divergent idea generation. |
| Evaluate | [Research Idea Evaluation Prompt.txt](Research%20Idea%20Evaluation%20Prompt.txt) | Stress-test an idea for novelty, feasibility, and contribution. |
| Evaluate | [Resaerch Idea Evaluation Prompts - Short.txt](Resaerch%20Idea%20Evaluation%20Prompts%20-%20Short.txt) | Quick sanity check on an idea. |
| Write | [Writing Helper Prompt.txt](Writing%20Helper%20Prompt.txt) | Draft, tighten, or restructure academic prose without losing your voice. |
| General | [Handy Research Oriented Prompts.txt](Handy%20Research%20Oriented%20Prompts.txt) | Grab-bag of smaller utility prompts for everyday research tasks. |

## How to use

1. Open the prompt file for your current task.
2. Replace any `[bracketed]` placeholders with your specifics (topic, paper, idea, draft).
3. Paste into your LLM. Iterate — most of these are written to support a back-and-forth,
   not a single answer.

**Tip:** the "Short" variants trade depth for speed. Reach for the full version when the
output actually matters; use the short one for quick passes.

## Contributing

These are living prompts — refine them as you find what works. PRs that improve clarity,
add placeholders, or share new prompts are welcome.

## License

MIT 
