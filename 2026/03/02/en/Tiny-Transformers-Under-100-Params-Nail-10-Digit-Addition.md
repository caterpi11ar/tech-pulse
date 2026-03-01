# Tiny Transformers Under 100 Params Nail 10-Digit Addition With 100% Accuracy

The AI industry has a size obsession. This paper quietly undermines it.

## What Happened

A paper shared on r/MachineLearning went viral this week: researchers trained a Transformer with fewer than 100 parameters that achieves 100% accuracy on 10-digit addition. The project, called AdderBoard, is fully open-source.

For context: GPT-2 has 117 million parameters. GPT-4 is estimated to have over a trillion. This model is so small you could theoretically compute its forward pass by hand.

## Why It Matters

This hits at the central debate in AI right now: how much of intelligence is scale, and how much is architecture?

The scaling law era gave us a simple answer — more parameters, more data, more compute, smarter AI. That story has been incredibly profitable for chip companies and cloud providers. But it's also become an article of faith rather than a law of nature.

This research suggests that for structured tasks, design and training methodology matter more than raw size. A well-crafted small model can outperform a bloated large one on the right task.

There's also the interpretability angle. With 100 parameters, you can actually *look inside* the model and understand what each weight is doing. That's impossible at GPT-4 scale — and it's a genuine scientific advantage.

## My Take

This won't dethrone large models. But it's a useful corrective to the hype cycle. The assumption that "bigger is always better" is partly a product of commercial incentives — the people selling compute want you to believe you need more of it.

Small model research matters because it isolates what intelligence actually requires, stripped of statistical brute force. That's valuable regardless of whether it ever scales.

## What to Watch

- Can AdderBoard extend to multiplication or symbolic reasoning?
- Will this inspire more work on purpose-built, task-specific small models?
- Could insights from tiny interpretable models inform better large model designs?

Sources: [AdderBoard GitHub](https://github.com/anadim/AdderBoard) · [r/MachineLearning thread](https://www.reddit.com/r/MachineLearning/comments/1rhjjba)
