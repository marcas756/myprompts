
# My Prompt Collection for Developers Using LLMs

This repo is a collection of prompts I’ve written to get consistent, high-quality results from LLMs in day-to-day development work. They cover things like generating Doxygen comments for embedded C/C++ code, writing unit tests with a custom test framework, translating technical documentation, and drafting user stories. Each prompt is focused, tested, and structured to work reliably. Feel free to use, tweak, or build on them—everything's shared under the CC BY 4.0 license.

## Generating Doxygen Documentation for Embedded Software Projects

assistant_doxydoc.md

Generates Doxygen documentation for C/C++ code, adhering to strict formatting and stylistic guidelines. It leverages contextual analysis to produce accurate and concise documentation within `<doxy>` tags. The output consists solely of formatted Doxygen comments, including file, function, and inline documentation blocks.

## Guidelines for Writing Embedded Systems Unit Tests in C99

assistant_unittest.md

The prompt's main purpose is to facilitate the creation of C99-compliant unit tests specifically for embedded systems, using the myunit framework based on code within `<myunit>...</myunit>` tags. It uniquely mandates adherence to a structured format and specific assertion macros tailored for such environments, ensuring precise testing conditions and outcomes. The expected output consists of well-structured unit test cases with clear preconditions, execution steps, postconditions, and corresponding invocations using the MYUNIT_EXEC_TESTCASE macro.

## Role and Guidelines for an Expert Translator from German to English

interpreter_gr2en.md

The primary function is to translate German sentences or documents into English while preserving technical terms without direct translations. The process emphasizes maintaining the original tone and format sentence-by-sentence without altering the meaning. The expected output is an accurate translation of the German text that retains its original structure and style.

## German translation with retention of technical terms and formatting

interpreter_any2gr.md

The primary function of this prompt is to translate sentences or documentation into German while maintaining technical terms in their original form. It emphasizes preserving the original tone and meaning without altering wording or format. The expected output is a precise translation of each sentence into German, adhering strictly to these guidelines, with unchanged formatting and untranslated technical terminology.

## Crafting Clear Technical User Stories: A Guide to Structured Communication in Software Development

scrum_storycreator.md

The main purpose of this prompt is to guide the writing of concise and clear technical user stories for new features in complex software programs. It emphasizes understanding the persona behind each story and focusing on their goals rather than specific features. The unique approach involves structuring descriptions as “As a [persona], I want to [action] so that [benefit],” ensuring clarity, conciseness, testability, and result-orientation without detailing implementation processes. Expected outputs are user stories with titles summarizing the description and acceptance criteria defining feature behavior from an end-user perspective, formatted in simple language for easy comprehension by all software stakeholders.

## Crafting Titles with Precision and Insight

suggest_title.md

Generate a compelling title that encapsulates the essence of an author's text by analyzing its content, themes, and unique characteristics. Focus on identifying the main idea or central theme while considering tone and style for alignment. The output is one succinct title suggestion that captures the core message without explanation.

