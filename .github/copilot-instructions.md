# Tutoring Repository

## Purpose
This repository organizes all materials used for tutoring, including notes, problem sets, examples, resources, and answer keys.

The student has access to the repository and is expected to be able to view all of its contents.

## Repository Structure

```
tutoring/
├── README.md
├── notes/
│   ├── ...
├── problem-sets/
│   ├── ...
├── answer-keys/
│   ├── ...
└── resources/
    ├── ...
```

### `notes/`
Contains instructional notes and explanations for topics covered during tutoring.

Notes should:

- Explain concepts clearly and intuitively.
- Use examples when helpful.
- Focus on understanding rather than memorization.
- Be written in Markdown whenever practical.

### `problem-sets/`
Contains practice problems for the student.

Problem sets may be stored as Markdown or PDF files.

### `answer-keys/`
Contains the answers and solutions corresponding to the problem sets.

Answer keys should be organized so that they can be easily matched to their corresponding problem set.

For example:

```
problem-sets/
└── algebra-set-01.pdf

answer-keys/
└── algebra-set-01.pdf
```

### `resources/`
Contains additional material useful for tutoring, such as:

- Reference sheets
- Formula sheets
- Study guides
- Additional examples

## Git Workflow
Keep the Git workflow simple.

Use only the `main` branch. Do not create feature branches or use pull requests unless there is a specific reason to do so.

Changes should be committed directly to `main`.

Typical workflow:

```
git add .
git commit -m "Add factoring practice"
git push
```
Git is primarily being used to:

- Store the tutoring materials
- Keep the materials synchronized
- Maintain a history of changes
- Allow previous versions to be recovered if necessary

## Organization
Keep files organized by their purpose and topic.

Use descriptive filenames rather than generic names such as `document1.pdf` or `notes2.md`.

When possible, use consistent naming between problem sets and their answer keys.

## Writing Style
Instructional material should be:

- Clear
- Concise
- Student-friendly
- Direct
- Educational rather than overly formal
Prefer explaining **why** something works before relying on memorization.

When creating explanations or examples, prioritize understanding of the underlying concept.

## Important Rule
All content in this repository may be viewed by the student.

Do not add unrelated personal information, private credentials, or other information that should not be stored in a shared repository.
