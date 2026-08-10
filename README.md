RuleMind AI

RuleMind is a rule-based conversational AI designed to simulate intelligent behavior using a large collection of deterministic rules.

The project focuses on handling real-world human input, including typos, slang, abbreviations, repeated letters, and different ways of expressing the same idea. For example, inputs such as "How are you?", "How r u?", and "Hawww r u?" can be normalized and interpreted as the same intent.

The AI separates its language data from its core engine using "vocab.json". This allows vocabulary, patterns, intents, responses, aliases, and corrections to be expanded without modifying the main JavaScript code.

The goal of RuleMind is to build a large, flexible, and explainable rule-based AI that can appear highly intelligent while remaining completely deterministic.
