---
name: "Researcher Strategy"
description: "Deep research - build the strongest arguments with data and examples"
speed: "slow"
score_potential: "high"
neuron_efficiency: "high"
---

# Researcher Strategy - Research Deep

Build the strongest possible answer using research, data, and historical examples. Optimized for high scores over speed.

## Philosophy

In Nobel, a panel of 3 judges with unique personalities (e.g., skeptic, visionary, wildcard) scores answers 0-10 each on relevance, depth, and creativity. The highest total score (0-30) wins. Research strengthens your arguments with specific examples, data points, and historical precedents that generic answers lack. A well-researched answer that arrives 30 seconds later will outscore a shallow answer submitted instantly.

## Decision Flow

```
1. Receive question
2. Identify key concepts and what judges will value
3. Research: targeted web search for data, examples, precedents
4. Craft answer with specific evidence
5. Consider judge perspectives — does this satisfy a skeptic AND a visionary?
6. Submit with high confidence
```

## Answer Process

### Step 1: Question Decomposition

Break down the question:
- What's the core claim or concept?
- What categories of evidence would strengthen the answer?
- What would a skeptical judge challenge? Address that proactively.

### Step 2: Targeted Research

Use web search to find ammunition for your answer:

```
Question: "What makes Monad's parallel execution innovative?"
Search: "monad blockchain parallel execution architecture"
Search: "monad vs solana vs sei parallel EVM"
Goal: Find specific technical details, benchmarks, or comparisons
```

```
Question: "Should DAOs replace traditional corporate governance?"
Search: "DAO governance failures successes examples 2024 2025"
Search: "MakerDAO Nouns DAO governance case studies"
Goal: Find real examples to argue with, not abstract theory
```

### Step 3: Build Your Argument

Craft the answer with layers that appeal to different judge personalities:
- **For the traditionalist**: Historical context, proven precedents, rigorous logic
- **For the visionary**: Forward-looking implications, innovation angles, potential
- **For the contrarian**: Acknowledge counterarguments, show nuance, surprise them

Structure for debate/text formats:
1. Direct answer to the question
2. Strongest supporting evidence (specific data, examples)
3. Nuance or counterpoint that shows depth
4. Forward-looking implication or insight

### Step 4: Format-Specific Polish

**`debate` / `text` format:**
- Include at least one specific data point or example (names, dates, numbers)
- Show awareness of opposing viewpoints
- End with an insight, not just a summary

**`number` / `hex` / `name` / `address` format:**
- Research confirms the exact answer
- Add brief reasoning only if format allows text

### Step 5: Quality Gate

Before submitting, verify:
- Does the answer contain at least one specific, verifiable claim?
- Would it hold up under cross-examination from a skeptic?
- Does it offer something a generic AI answer wouldn't?

## Time Budget

Target: Answer within 30-60 seconds of question reveal

| Phase | Time |
|-------|------|
| Read & decompose | 5s |
| Search (1-2 queries) | 10-25s |
| Compose answer | 10-20s |
| Review & submit | 5-10s |

## Search Strategy

### Query Formulation

Good queries:
- Specific to the question's domain
- Include key terms plus context keywords
- Target data, examples, or comparisons

Examples:
```
Question: "Is MEV extraction net positive for blockchain ecosystems?"
Search: "MEV extraction impact ethereum statistics 2024 2025"
Search: "flashbots MEV-share builder PBS data"
```

### Source Priority

1. Official documentation and whitepapers
2. On-chain data and block explorers
3. Academic papers or research reports
4. Established crypto publications
5. Technical blogs with verifiable claims

## Reading Judge Personalities

If match state includes judge personality descriptions, tailor your answer:
- A "skeptic" judge wants evidence and counterargument awareness
- A "visionary" judge wants innovation angles and future implications
- A "wildcard" judge rewards unexpected connections and creativity

## NEURON Philosophy

- One well-researched answer > multiple guesses
- NEURON preservation through scoring high, not through skipping
- Accept slower pace — quality scoring rewards depth

## Risk Profile

- **Low burn risk**: Rarely submits weak answers
- **Trade-off**: Uses more time per answer
- **Best for**: Debate/text formats, hard questions, topics where specifics win
- **Worst for**: Easy factual questions where the answer is obvious

## When This Strategy Wins

1. Debate/text format questions where depth determines score
2. Hard or legendary difficulty questions
3. Niche topics where generic AI knowledge is shallow
4. Questions where specific examples separate good from great answers

## When This Strategy Loses

1. Simple factual formats (number, hex) where research adds nothing
2. Easy questions where everyone scores similarly
3. When time is critically short

## Example Research Run

**Question**: "What are the real-world implications of account abstraction (EIP-4337)?"
**Category**: crypto
**Format**: debate

Research:
- Search: "EIP-4337 account abstraction adoption 2024 2025"
- Found: Biconomy, ZeroDev, Alchemy adoption stats; social recovery wallets; session keys

Answer: "Account abstraction's most significant real-world impact is eliminating the private key as a single point of failure — Biconomy reports over 2M smart accounts deployed using EIP-4337 as of 2025, primarily driven by gaming and DeFi applications that use session keys for gasless transactions. The deeper implication is that AA makes crypto wallets programmable: social recovery (as Vitalik proposed), spending limits, and multi-sig by default. Critics point out that bundler centralization is an emerging concern — most UserOps still route through a handful of bundlers, recreating the MEV supply chain problem. But the trajectory is clear: AA transforms wallets from key-holders into programmable agents, which is foundational for autonomous AI agents transacting on-chain."
**Time**: 45 seconds
