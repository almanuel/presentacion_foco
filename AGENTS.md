# Repository Guidelines

## Project Structure & Scope

This repository currently contains the planning brief for the **Agenda Informática Nacional** presentation. The primary source is `reqs.md`, written in Spanish, which defines the political framing, narrative sequence, visual identity, event format, and slide-level requirements. There is no application source code, asset directory, build configuration, or test suite yet.

Keep future work organized by purpose. For example, place presentation source in `slides/`, reusable images in `assets/`, and exported deliverables in `dist/`. Do not edit generated exports by hand; update their source instead.

## Development & Validation

No build, development, lint, or test commands are configured at present. Before introducing tooling, document its commands here and in a project README. For content changes, validate the result against `reqs.md`, especially:

- the 10–12 slide narrative and its open, participatory framing;
- exact event details: **28 de noviembre** and **Cero + Infinito**;
- the intended institutional, contemporary, technological visual tone.

If presentation tooling is added, provide a repeatable export command and verify that generated files open correctly before committing.

## Content, Style & Naming

Preserve Spanish as the working language unless a deliverable explicitly requires otherwise. Keep slide copy short, direct, and politically inclusive; avoid presenting the agenda as already closed. Use the vocabulary and constraints in `reqs.md` rather than inventing a competing tone.

Use lowercase, hyphen-separated names for new files and directories, such as `slides/agenda-comun.md` or `assets/cero-infinito-patio.jpg`. Prefer descriptive names over generic labels such as `final-v2`.

## Testing Guidelines

There is no automated test framework. Treat review as a content and visual QA pass: confirm factual details, readable hierarchy, the morning-to-closure convergence, and that imagery has appropriate use rights. When code or automation is introduced, add focused tests alongside it and document how to run them.

## Commits & Pull Requests

Git history is not available in this workspace, so no repository-specific commit convention can be inferred. Use concise imperative commits, for example `docs: refine event narrative` or `feat: add slide export script`.

Pull requests should explain the intended change, identify affected slides or files, link any relevant issue, and include screenshots or a PDF preview for visual changes. Note any deviation from `reqs.md` and why it is needed.
