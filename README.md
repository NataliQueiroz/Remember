# Remember

A macOS application that uses Apple's Foundation Models framework to help users organize, summarize, and retrieve information from their personal notes.

## About

Remember is a native macOS application designed to improve the way users interact with their personal knowledge bases.

The application allows users to import Markdown notes from their Obsidian vaults and interact with their content using Generative AI.

By integrating Apple's Foundation Models framework, Remember explores how Large Language Models (LLMs) can support information retrieval, summarization, and organization through natural language interactions.

## Features

- **Obsidian Vault Import:** Import Markdown files from a local Obsidian vault.
- **Note Processing:** Load and process Markdown content within the application.
- **AI Integration:** Interact with Apple's Foundation Models framework.
- **Natural Language Interaction:** Ask questions about imported notes.
- **Content Summarization:** Generate summaries from note content.


## Technologies

| Technology | Purpose |
|---|---|
| Swift | Main programming language |
| SwiftUI | Native macOS user interface |
| Foundation Models | On-device language model integration |
| LanguageModelSession | Model interaction and session management |
| Markdown | Note content format |
| Xcode | Development environment |

## Architecture

The application follows a modular structure, separating the user interface, file management, Markdown processing, and AI integration.

Main components:

- **NotesImportView:** Interface for selecting and importing an Obsidian vault.
- **NotesImportViewModel:** Manages the note import flow and application state.
- **FileSystemService:** Handles local file discovery and loading.
- **MarkdownParser:** Processes Markdown content.
- **LanguageModelService:** Manages interactions with Apple's Foundation Models framework through LanguageModelSession.

## My Contribution

Remember was developed collaboratively as a proof of concept.

My main contribution was implementing the `LanguageModelService` and integrating Apple's Foundation Models framework into the application.

My responsibilities included:

- Implementing model sessions using `LanguageModelSession`.
- Defining custom instructions to guide model behavior.
- Integrating the language model service into the application architecture.
- Connecting AI capabilities to the imported Markdown content.

## Project Status

Remember is a functional proof of concept.

The application supports Obsidian vault import and interactions with Apple's Foundation Models. Some features and improvements are still under development.

## Requirements

- macOS version compatible with Apple's Foundation Models framework.
- Xcode version supporting the Foundation Models framework.
- A Mac compatible with Apple Intelligence and the required model capabilities.

## Acknowledgements

Developed collaboratively as part of an exploration of Generative AI and native Apple application development.
