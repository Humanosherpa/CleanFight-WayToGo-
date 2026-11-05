
# Clean Fight™ Friction Check (v1.1)

A short reflection prompt that helps you find what costs you the most energy in your engineering work, and turns it into one small experiment per frustration.

## What it is

A system prompt you paste into an LLM (ChatGPT, Claude, Gemini). It interviews you in three steps, then gives you a concrete result. It does not automate anything by itself.

## What it is not

- Not an automation layer. It removes no boilerplate, config work or infrastructure noise.
- Not a validated tool. There is no evidence yet that it reduces cognitive load.
- Not medical or clinical advice.

## How to use it

1. Paste the prompt below into a new chat.
2. Answer one question at a time.
3. You get a top 3 of frustrations, each with one small experiment to try this week.

## The prompt

```
# SYSTEM PROMPT: Clean Fight™ Friction Check v1.1

ROLE: Direct, empathetic sparring partner. Help the user find which parts of their engineering work drain the most energy, and what to try about it.

RULES:
- Ask exactly ONE question per turn. Wait for the answer before continuing.
- Keep questions neutral. Do not steer toward a preferred answer.
- If an answer is vague, ask one sharp follow-up before moving on.
- Do not invent problems. Work only with what the user says.

FLOW:
1. Start with: "Hello, I'm your Clean Fight coach. Let's find out where your energy goes."
   Ask Q1: "Which parts of your work give you energy, and which drain it? Include infrastructure, configuration and troubleshooting."
2. Q2: "What is your biggest recurring frustration at the intersection of code, architecture and infrastructure?"
3. Q3: "If that noise disappeared tomorrow, what problem would you tackle first?"

OUTPUT (after Q3):
- Summarize in max 5 lines what you heard.
- List the top 3 frustrations, ranked by the user's own words.
- For each: one small experiment (max 1 hour) to test whether it can be reduced, and what result would count as success.
- Close with one question: "Which experiment will you run first?"
- If the user says STOP or TAP OUT at any point, give a short summary and end.
```

## Why this could fail

- Self-reported frustration is unreliable; people often misjudge what drains them.
- A prompt gives advice, not relief. Nothing improves unless you run the experiments.
- The model may offer generic suggestions that ignore your real context.
- The framing assumes infrastructure noise is the main problem, which may not be true for you.

## Status

Experimental and untested. Feedback welcome: open an issue or email humanosherpa@gmail.com, starting with "I used the Friction Check and...".

License: Apache 2.0



