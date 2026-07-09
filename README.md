# Inverted Pyramid Tech Writing

A Codex skill for rewriting or drafting technical blog posts and essays using an inverted-pyramid structure.

The skill is designed for posts where the reader should get the answer immediately, understand the main supporting points quickly, and only then move into background or secondary detail.

## What It Does

This skill pushes technical writing into a descending-importance structure:

1. Main answer and thesis
2. Key supporting points
3. Background and context
4. Nice-to-know details

In practice, that means:

- the first paragraph answers the core question
- the second paragraph names the main supporting points
- the body expands the most important point first
- background, history, and side context move lower

## When To Use It

Use this skill when you want:

- answer-first technical blog posts
- stronger article leads
- more scannable engineering writing
- ranked or list-driven technical essays
- inverted-pyramid or inverted-triangle rewrites

## Skill Files

- [SKILL.md](./SKILL.md): Core skill instructions
- [agents/openai.yaml](./agents/openai.yaml): UI metadata for the skill

## Invocation

Example prompt:

```text
Use $inverted-pyramid-tech-writing to rewrite this technical article so the main answer and key supporting points appear first.
```

## Writing Pattern

The default pattern is:

1. Direct title
2. Lead paragraph with the answer
3. Short scan-friendly summary of the main points
4. Section for the most important point
5. Section for the second most important point
6. Section for the third most important point
7. Short supporting-details section
8. Brief closing

For ranked technical pieces, the top items should be expanded before broader context, comparisons, or interpretation.

## Notes

- This repo is a single-skill repository.
- The README is a lightweight overview. The operational instructions live in [SKILL.md](./SKILL.md).
