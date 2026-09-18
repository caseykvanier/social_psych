---
schema_version: 1
id: multiple-choice-agent-guide
material_type: study_guide
title: Generating useful multiple-choice practice
status: published
authorship: agent-generated
review_state: publication_authorized_by_instructor_not_formal_item_validation
chapters: []
course_evidence:
  - path: AGENTS.md
    locator: Source authority
learning_objectives:
  - Generate source-grounded practice with one defensible answer and plausible distractors.
  - Distinguish basic recognition from application and reasoning about evidence.
difficulty: mixed_intended_difficulty
licence: CC0-1.0
---

# Guide for agents: generate useful multiple-choice practice

Help the student practise understanding and applying the course, not memorizing predictable answer patterns. This guide covers **single-answer multiple-choice practice only**. The course's tests also contain other question types. Neither this guide nor its examples specifies the test's full format, difficulty distribution, or likely questions; consult Moodle for assessment instructions.

These instructions and the [worked examples](multiple-choice-examples.md) are agent-generated materials authorized for publication. They are not actual assessment items, an instructor answer key, or a prediction of what will be tested.

## Establish what the student has studied

1. Read [AGENTS.md](../AGENTS.md) and [course.yml](../course.yml).
2. Read the relevant chapter's `sources.yml` for taught, skipped, and incomplete coverage, then its `notes.md` for explanations and qualifications. Respect the notes' draft review status.
3. Use slides to clarify visible content and the textbook for supporting background. Neither proves that a topic was taught. Exclude skipped material from course-aligned practice unless the student explicitly requests it as labelled enrichment.
4. Identify the concepts and learning goals before writing questions. Skip covers and section dividers; merge repeated treatment of the same concept. If the available sources cannot support enough varied questions, explain the limit rather than inventing material.

Use only public teaching sources and approved public practice examples. Do not seek, reconstruct, imitate, or use real assessment questions, answer keys, or private test banks as generation examples. Do not copy assessment content into reusable prompts, files, or memory. General teaching concepts can be shared across practice and assessments; their presence does not make a practice item evidence about a particular test.

## Choose a manageable practice set

Follow the student's requested size and pace. For a reusable concept pool, a useful default is **25 questions per substantive concept**, with:

| Intended level | Items in a 25-item pool | What the learner must do |
| --- | --- | --- |
| Foundation | 5 | Recognize an essential definition, relationship, or straightforward example. |
| Application | 12 | Use a mechanism in a new situation, identifying the relevant evidence. |
| Stretch | 8 | Distinguish plausible explanations, identify missing evidence, evaluate an inference, or predict the effect of changing an important detail. |

This is a **practice-design target**, not a statement about the test or a measured difficulty scale. Scale the mix sensibly for shorter sessions. Include different concepts and levels when sampling practice; a run of easy items should not be presented as proof of readiness.

Bloom labels, if used, describe the cognitive task separately from intended difficulty. A long scenario or the words “evaluate” and “best supported” do not automatically make an item difficult or higher-order.

## Write the question and all four options together

- Ask one clear question. Use exactly four distinct options with **one defensibly correct answer** under the stated conditions.
- Make all three distractors credible misconceptions at the same conceptual level. Avoid joke answers, unrelated jargon, and obviously impossible claims.
- Keep options comparable in length, grammar, specificity, and qualification. Do not habitually make the key the only long, nuanced answer while distractors use “always,” “never,” or “entirely.” Absolute wording can be appropriate when it is genuinely what the concept requires.
- Check whether categories overlap or one includes another. A broad category and a valid subtype can both be correct; clarify the question or change the alternatives.
- In scenarios, include the information needed for the inference. For learning mechanisms, identify the target behaviour, the consequence, and the later change in behaviour when those determine the answer. For causal claims, distinguish what was observed from what was manipulated or assigned.
- Create genuinely different learning tasks across the pool. Changing names, objects, or sentence order does not make a new question. Do not use one question to reveal another's answer.
- Make difficulty come from relevant reasoning rather than obscure facts, ambiguous wording, gratuitous negatives, or unnecessary reading.
- Vary answer positions or shuffle options, updating the key and feedback together. Feedback should refer to the option's meaning, not a letter that may move.

## Ground the answer and explain the alternatives

For each item, retain:

- a stable practice ID, concept, learning goal, and intended level;
- the stem and four options;
- the keyed answer and a concise explanation;
- a specific reason each alternative is wrong **in this scenario**;
- a link to the chapter notes and the relevant slide heading;
- a short supporting excerpt when useful, copied accurately from the source rather than invented.

A matching quotation does not by itself prove that a key follows from the evidence. Check the inference, and do not turn a qualified claim into a universal rule. Explanations should teach the concept, not simply repeat the key or say that an alternative was not mentioned in the notes.

## Check before showing the set

Review for a second defensible answer, unsupported claims, weak distractors, answer-length or grammar cues, duplicate reasoning tasks, and inappropriate difficulty labels. Repair flagged items without rewriting sound ones repeatedly. Automated counts and similarity checks can help for large banks, but cannot establish pedagogical quality or actual student difficulty.

Do not call a generated set “instructor-approved,” “exam-equivalent,” or a reliable prediction of test performance. Label generated questions and any unresolved uncertainty honestly.

## Tutor with the questions

Normally offer one question at a time and let the student attempt it before revealing the answer. Ask for their reasoning when useful, explain why the competing answers fail, and offer a new transfer question when they need another attempt. Give direct answers when requested. Keep answer explanations separate from the initial question rather than leaking the key through a hint.

Treat an error as evidence about a misconception to explore, not proof of general inability. A correct choice without reasoning may be a guess. Adjust subsequent practice using the student's responses while retaining a mix of concepts and demands.

## Example request a student can give an agent

> Read this repository's AGENTS.md, the relevant chapter notes and coverage manifest, and the multiple-choice agent guide. Give me six original MC practice questions on the taught concepts in Chapter 2, one at a time, with a mixture of foundation, application, and stretch tasks. Use four plausible options and one defensible answer. After I answer, explain every option and cite the relevant slide notes. Do not use or predict actual test questions.

See the [three worked MC examples](multiple-choice-examples.md) for question structure, feedback, and source grounding. Learn their design principles; do not just reproduce their scenarios with different names.
