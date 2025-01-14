# Expanding vs Uniform Spacing

Regarding spaced repetition, the wikipedia page [Spaced repetition](https://en.wikipedia.org/wiki/Spaced_repetition) has a section on [Criticism](https://en.wikipedia.org/wiki/Spaced_repetition#Criticism) to debate the merits of expanding intervals versus uniform intervals. This debate is largely irrelevant to most spaced repetition software, as popular algorithms typically shorten intervals when learners forget and extend them when they remember.

Why do some academic papers find expanding intervals superior to uniform intervals, while others find the opposite? I've created a notebook based on FSRS's memory model to explain this. Here's my theory: Expanding intervals are more effective for content students remember, but for forgotten material, continuing to expand intervals only leads to repeated forgetting. Uniform intervals, while less effective for remembered content, are not as detrimental for forgotten material. Therefore, on average, the difference between expanding and uniform intervals depends on the ratio of forgotten to remembered items during the review process. It should be discussed with a model that can predict the recall probability of items. Otherwise, it's a pointless debate.