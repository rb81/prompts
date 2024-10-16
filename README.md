# Prompts

## [Structured Prompting](https://github.com/rb81/prompts/blob/main/structured-prompting.json)

The JSON-structured prompting technique outlines an AI-assisted conversational flow optimized for targeted, efficient interactions. By emphasizing request clarification, focused processing, and iterative refinement, this approach enables users to create AI assistants that deliver concise, relevant responses tailored to their specific needs.

While well-suited for task-oriented scenarios like customer support or guided decision-making, this technique may be less effective for open-ended, exploratory conversations. Users should consider the nature of their intended use case and the desired balance between specificity and flexibility when implementing this prompting strategy.

## [Iterative Prompting](https://github.com/rb81/prompts/blob/main/iterativePrompting.prompt)

This prompt is an example of Iterative Prompting, a technique used to guide AI language models through a structured, step-by-step process to achieve a specific goal. In this case, the prompt assists users in writing high-quality white papers by breaking down the task into a series of well-defined steps. The AI model engages with the user iteratively, seeking their input and approval at critical points in the process. By following the outlined procedure and leveraging the AI's extensive knowledge base, users can create informative, well-structured, and engaging white papers tailored to their intended purpose and audience. This prompt demonstrates the effectiveness of Iterative Prompting in creating a collaborative and efficient workflow between humans and AI models.

## [In-Line Moderation](https://github.com/rb81/prompts/blob/main/inlineModeration.prompt)

This prompt provides a framework for content moderation that can be used in conjunction with any other prompt or set of prompts when engaging with a language model. It enables the model to review both the user's messages and its own responses against a predefined set of moderation policies, which cover areas such as illegal activity, hate speech, malware, and unqualified advice. The model includes in-line moderation flags in its responses to indicate if and how the content violates these policies. A system would need to be implemented to parse and act upon these flags. By moderating both the user's and its own content in this manner, the language model can help ensure a safer and more responsible conversation. (The moderation policies used here are adapted from the [Mistral AI documentation on content moderation with self-reflection](https://docs.mistral.ai/platform/guardrailing/#content-moderation-with-self-reflection).)

## [Contextual Memory](https://github.com/rb81/prompts/blob/main/contextualMemory.prompt)

### Example: AI Personal Finance Manager with In-Context Memory
This is a prompt for creating an AI-powered personal finance manager using in-context memory. The AI assistant acts as a financial advisor, helping users track their transactions, create budgets, set financial goals, and generate reports.

### Key Features
- Flexible interaction style (informative or efficient)
- Comprehensive categorization of financial data
- In-context storage of transactions, budgets, goals, and reports
- Accurate record-keeping and data validation
- Detailed, actionable financial advice based on user's data

The prompt provides a structured framework for the AI to maintain an up-to-date view of the user's finances within the conversation context. This enables the assistant to offer personalized and contextually relevant guidance to help users make informed financial decisions.

## [Prompt-Based Search Engine](https://github.com/rb81/prompts/blob/main/promptBasedSearchEngine.prompt)

### Example: SeekWise, LLM-Powered Search Engine Prompt
SeekWise is an advanced search engine prompt designed to make Language Models (LLMs) behave like efficient, user-friendly search engines. By providing a corpus of searchable content and using this prompt, you can transform your LLM into a powerful search companion.

### Key Features
- Analyzes user queries to understand intent and key search terms
- Conducts thorough searches on the provided content corpus
- Scores and ranks results based on relevance, keyword matches, and semantic similarity
- Generates concise, easy-to-scan results pages with top matches
- Allows users to select specific results to view full content with highlighted relevant parts
- Offers optional elaboration or discussion on the full content results
- Provides recommendations for alternative search queries or related topics when no close matches are found
- Maintains a focused, concise communication style to efficiently guide users to the information they seek

### Usage
- Copy the SeekWise prompt into your LLM's prompt input.
- Paste your searchable content corpus after the [Searchable Content] tag.
- Provide a search query to the LLM.
- Interact with the search results, selecting numbers to view full content or requesting elaboration as needed.

** Notice: Content in the demo is AI-generated and may contain errors, factual or otherwise. **

## [Nested Prompting](https://github.com/rb81/prompts/blob/main/nestedPrompting.prompt)

### Example: promptOS

promptOS is an interactive conversational operating system designed to be used with language models or AI assistants. It provides a wide range of productivity, entertainment, and utility apps that can be accessed through a simple command-based interface.

### Key Features
- Calculator: Solve mathematical and scientific equations and problems
- Chatbot: Engage in friendly conversations on various topics
- Language Translator: Translate text between different languages
- Trivia Game: Test your knowledge with questions from various categories
- Story Generator: Create unique stories based on user input
- Poetry Generator: Generate personalized poems based on user preferences
- Joke Teller: Enjoy jokes and humorous anecdotes
- Riddle Game: Challenge yourself with puzzling riddles and brain teasers
- Word Association Game: Play a game of word associations and discover interesting facts
- Mindfulness Coach: Enjoy guided mindfulness and meditation exercises
- Virtual Debate Club: Engage in structured debates on various topics
- DIY Project Helper: Get step-by-step guidance and tips for your DIY projects
- Music Explorer: Discover new music based on your preferences
- Cooking Companion: Find recipes based on the ingredients you have on hand
- Notes: Take and manage notes within the conversational interface

### Usage
To use promptOS, simply copy the provided prompt and paste it into your preferred language model or AI assistant. Follow the available commands and app instructions to interact with the operating system and explore its various features.

## File Formats
Files are saved in plain text with the `.prompt` extension for convenience, unless using JSON in which case the file is saved with the `.json` extension. When implementing, copy and paste the content or simply upload the desired file.

## Transparency Disclaimer

[ai.collaboratedwith.me](https://ai.collaboratedwith.me) in creating this project.
