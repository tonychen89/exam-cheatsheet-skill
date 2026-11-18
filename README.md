# Exam Cheat Sheet Skill

An agent skill for creating and reviewing exam-ready, course-grounded cheat sheets as editable Word documents.

## What it does

- Clarifies the exam format, permitted materials, language, and page limits without repeating information the user already supplied.
- Organises course-supported material for calculation, scenario analysis, classification, or mixed exams.
- Separates lecture evidence from explanatory examples and unverified assumptions, with traceability to source pages when available.
- Combines concise memory cues with answer-ready wording, adapting the languages to the student and exam.
- Checks representative questions, Word document structure, page limits, and visual layout when the environment supports rendering.

The skill is a set of instructions for a compatible agent; it is not a standalone application. The agent must have access to the user's chosen source materials and an appropriate Word document creation tool. Actual page rendering and print checks depend on the available environment and fonts.

## Usage

Place the `exam-cheatsheet` skill directory containing `SKILL.md` in a skills location recognised by your agent, or provide the file to an agent that can read skill instructions. Then describe your course materials, exam requirements and preferred output. The agent should ask only for important missing details.

Example request:

> Create a Word cheat sheet from my lecture slides and practice questions. The exam allows two double-sided A4 sheets and includes calculations and case analysis. Use Chinese memory cues and English answer prompts. Keep source references available for checking.

## Scope and verification

Course materials, exam papers, personal notes and generated student documents are not included in this repository. Review the generated content against your own materials and verify the final page layout and print result before use. No skill can guarantee exam coverage or marks.
