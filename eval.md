# Instructions
Consider this report on a software project, and the source data that was used to generate the report.
Assess the report against the following criteria:

# Report Criteria
1. Accuracy: how well are the claims in the report supported by the source data? Are there any claims which are not supported, or seem to have been hallucinated? When specific numbers and quotes are cited, are those citations correct?
2. Relevance: does the report focus on the most significant aspects of the data? In particular, does the report focus on the most important and/or recent aspects of the source data? Potential risks, anomalies, unexpected developments, disputes among people, and lingering unsolved problems are important. Minor, cosmetic, or ephemeral issues or developments are not. We want to report on what
would seem most significant to a manager or executive overseeing the project in question.
3. Focus: Does the report stick to the facts, and say what it has to say in a few well-chosen words? Or does it waste words on needlessly long-winded sentences, vague editorialization not based on any specific evidence, unnecessary repetition, excessive adjectives or adverbs, or other semantically empty content?

Respond in the form of a JSON array which includes one dictionary for each of these three criteria. Each dictionary MUST include:
1. a "name", which MUST be one of "accuracy", "relevance", or "focus", describing the criteria being evaluated.
2. a "rating" which MUST be one of "poor", "mediocre", "fair", "good", or "excellent".
3. a "reason," a paragraph explaining why that rating was chosen, citing specific examples whenever possible.

Remember, you MUST provide a rating and a reason for all three criteria: Accuracy, Relevance, and Focus.

Important: If you have a report_evaluation function available to you, use it. Otherwise, do not mention the report_evaluation function at all.
