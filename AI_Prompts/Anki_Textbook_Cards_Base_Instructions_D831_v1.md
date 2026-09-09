# Prompt for Creating WGU D831 — Introduction to AI and Security Anki Flashcards from zyBooks Lesson Material

## Purpose

Create high-quality Anki flashcards from the **lesson material** in WGU **D831 — Introduction to AI and Security**.

This instruction set is intended to be reused **one zyBooks lesson at a time**. A typical prompt session should cover only one lesson, or at most two closely related lessons, so that the source material and generated cards remain within a manageable context window and can be reviewed carefully.

The goal is **not** to convert every line of the textbook into a card. The goal is to extract the concepts that a learner should understand, recognize, distinguish, and apply in order to demonstrate the course competencies and prepare for the WGU Objective Assessment.

---

# Course Context

D831 provides an overview of critical terminology and key concepts involving:

- Artificial intelligence (AI)
- Machine learning (ML)
- Generative AI (GenAI)
- Neural networks
- Data collection, preparation, quality, and suitability
- Cybersecurity fundamentals
- AI applications in cybersecurity
- Bias, fairness, privacy, transparency, and other ethical concerns
- Security threats against AI/ML systems
- Secure management and governance of AI systems
- Accountability and responsible use of GenAI

The course is assessed by a WGU Objective Assessment rather than an external certification exam.

The Objective Assessment contains **60 items** and allows **120 minutes**.

The course has three official competencies:

1. **Describes Types of AI**  
   The learner describes the types of artificial intelligence for decision-making in real-world applications.

2. **Identifies Suitable Data Sources**  
   The learner explains how the collection, wrangling, and cleaning of data impacts AI/ML models.

3. **Explains Best Practices for Managing Secure AI Systems**  
   The learner explains best practices for managing secure AI systems within an organization.

## Competency Weighting

Use the official weighting as a prioritization signal across the overall deck:

| Competency | Weight |
| --- | ---: |
| 1 — Describes Types of AI | 30% |
| 2 — Identifies Suitable Data Sources | 30% |
| 3 — Explains Best Practices for Managing Secure AI Systems | 40% |

Do **not** force every lesson to contain the same proportion of cards. A lesson should reflect its actual subject matter. Across the complete deck, however, material related to secure AI systems should receive somewhat greater emphasis because Competency 3 represents the largest portion of the assessment.

---

# Source Hierarchy

Use the following hierarchy when creating cards.

## 1. Primary Source — Current zyBooks Lesson Material

The specific zyBooks lesson supplied for the current conversion is the **primary source**.

Preserve the terminology, definitions, distinctions, examples, and framing used by the course.

When the lesson contains a **“Learn to:”** section, treat those learning objectives as a major indicator of what the lesson expects the learner to know.

## 2. Course Syllabus and Course Kick Start Guide — Scope and Prioritization

Use the D831 syllabus and Course Kick Start Guide to determine:

- the official course competencies,
- competency weighting,
- overall course scope,
- assessment design,
- and appropriate level of depth.

The Objective Assessment is designed to measure **competency**, not recall of every isolated line in the learning resource. Therefore, prefer cards that reinforce concepts and application over cards based on incidental textbook trivia.

## 3. Other Course Resources — Only When Actually Provided

The zyBooks course may link to:

- readings,
- videos,
- graphics,
- infographics,
- labs,
- case studies,
- and other external learning resources.

The syllabus states that these materials may be testable.

However, do **not** invent or reconstruct the contents of a linked resource merely because a title or URL appears in the PDF.

If the actual resource, transcript, screenshot, or relevant content is provided in the current prompt, it may be used as a source. If only a link or title is present, treat it as a reference only.

## Source Fidelity Rule

If the source material uses wording or framing that differs from general industry usage, teach the **course's framing** unless the user specifically asks for outside verification.

Do not silently “correct” the course from memory or general knowledge.

If a passage appears materially inaccurate, contradictory, or defective, preserve the course's stated point for study purposes and flag the issue separately rather than silently replacing it.

---

# Critical Rule: zyBooks Interactive Material in PDF Exports

zyBooks is an interactive learning platform. PDF exports do not always preserve the interactive experience correctly.

The PDF may contain:

- Participation Activities
- Knowledge Checks
- Challenge Activities
- Drag-and-drop exercises
- Matching exercises
- Animation placeholders
- Questions whose provider-keyed answers are not visible
- Labs
- Interactive diagrams or activities that lose context when printed

## Default Handling

**Do not create flashcards directly from the questions or answer choices in Participation Activities, Knowledge Checks, Challenge Activities, or other interactive exercises unless the user explicitly requests that behavior.**

In particular:

- Do not guess the provider's keyed answer.
- Do not infer that an answer choice is correct merely because it sounds plausible.
- Do not convert an interactive question into a flashcard simply because it appears in the PDF.
- Do not treat an activity as authoritative answer-key material when the PDF does not display the provider's feedback or keyed response.

## What May Still Be Used

The **teaching material surrounding an activity** may absolutely be used.

Examples include:

- prose immediately before or after the activity,
- definitions,
- tables,
- figure labels,
- captions,
- animation captions that explicitly teach a concept,
- explanatory text,
- worked examples,
- diagrams whose meaning is clear from the PDF.

If an animation caption contains substantive instructional material, use the **instructional content**, not the interactive question itself.

## Labs

Do not create detailed procedural cards from labs unless the lesson clearly teaches concepts through the lab that are relevant to a course competency.

A lab title or list of actions is not, by itself, a reason to create cards.

---

# How to Decide What Becomes a Card

Before writing cards, internally inventory the lesson for:

1. The lesson's **Learn to** objectives.
2. Core definitions.
3. Important distinctions.
4. Lists or structures that must be recognized.
5. Cause-and-effect relationships.
6. Processes or lifecycle steps.
7. Real-world application of concepts.
8. Security threats, weaknesses, attacks, or mitigations.
9. Data quality, preparation, or model-impact relationships.
10. Ethical, privacy, governance, accountability, or human-oversight concepts.
11. Examples that genuinely clarify a concept.
12. Concepts likely to be confused with one another.

Create cards from the **knowledge represented by the lesson**, not from the page count.

---

# Prioritization and Depth

The textbook can contain substantially more detail than is practical or useful for an Anki deck.

Use the following prioritization rules.

## High Priority

Create cards for:

- Explicit **Learn to** objectives
- Formal definitions
- Terms repeatedly used in the course
- Types or categories that must be distinguished
- AI vs. ML vs. deep learning vs. GenAI relationships
- Narrow AI vs. general AI distinctions
- Supervised vs. unsupervised vs. reinforcement learning
- Model, algorithm, feature, instance, label, training, validation, inference, and related core terminology
- Data collection, cleaning, wrangling, labeling, transformation, quality, bias, and suitability
- Security risks to AI/ML systems
- Data poisoning, model poisoning, adversarial inputs, prompt-based attacks, privacy risks, insider threats, and similar course concepts when present
- Security controls and mitigations
- Privacy, transparency, explainability, fairness, accountability, governance, and human oversight
- Scenario-based application of a concept
- Tables or diagrams that organize multiple important concepts
- Relationships between poor data quality and model performance
- Why a security or governance practice matters

## Medium Priority

Create cards selectively for:

- Named technologies or products used as examples
- Historical examples that clarify the evolution of AI
- Case studies
- Milestones that the lesson appears to emphasize
- Industry examples that reinforce how a concept is applied
- Supporting terminology needed to understand a major idea

## Low Priority / Usually Exclude

Do not automatically create cards for:

- Every historical date
- Every researcher name
- Every product or company mentioned
- Decorative examples
- Repeated statements that add no new concept
- Long narrative passages that can be reduced to one underlying principle
- Bibliographic information
- URLs
- Page navigation
- Instructions for accessing the course
- Purely motivational text
- Details that are neither connected to a Learn to objective nor useful for understanding a course competency

Historical dates, names, and specific examples may still become cards when the lesson clearly emphasizes them as knowledge the learner is expected to recognize.

---

# Course-Level Scope

The course schedule contains the following major chapters:

1. Course Overview  
2. Introduction to AI and Security  
3. Artificial Intelligence  
4. Machine Learning  
5. Understanding GenAI  
6. Neural Networks  
7. Data Management  
8. Cybersecurity  
9. AI and Cybersecurity  
10. Ethics in Artificial Intelligence  
11. Privacy for GenAI in Cybersecurity  
12. Accountability for GenAI in Cybersecurity  
13. The Future of GenAI in Cybersecurity  
14. Course Summary

This is a **course structure**, not a requirement to create the same number of cards for every chapter.

---

# Card Types to Use

Use a mix of card styles based on what best teaches the material.

## 1. Key-Term Definition Cards

Use for foundational terminology.

Example:

**Front**
```html
🤖 What is <b style="color:#2874A6">artificial intelligence (AI)</b>?
```

**Back**
```html
<b style="color:#2874A6">Artificial intelligence (AI)</b> is the development and use of algorithms and models to mimic human thought.<br><br>AI can be used to classify data, make predictions, or generate new outputs.
```

---

## 2. Concept-Distinction Cards

Use when two or more concepts are likely to be confused.

Examples:

- AI vs. ML
- ML vs. deep learning
- Narrow AI vs. general AI
- Traditional AI vs. generative AI
- Supervised vs. unsupervised vs. reinforcement learning
- Classification vs. regression vs. clustering
- Training data vs. validation/test data
- Accuracy vs. fairness
- Privacy vs. transparency
- Explainability vs. accountability

Do not create a distinction merely because two terms occur near each other. Use this style when the contrast is instructionally useful.

---

## 3. Recognition / Classification Cards

Give a short scenario and ask the learner to identify the correct type, category, or concept.

Example:

**Front**
```html
🧠 A model is trained on historical emails labeled <b>spam</b> or <b>not spam</b> and then predicts the label of new messages.<br><br>What type of machine learning is being used?
```

**Back**
```html
<b style="color:#27AE60">Supervised learning</b>.<br><br>The training data contains known labels, and the model learns the relationship between the input features and the labeled output.
```

---

## 4. Cause-and-Effect Cards

Use these heavily in data management and security lessons.

Examples:

- What happens when training data is incomplete?
- How can outdated threat data affect an AI security model?
- Why can biased training data produce biased outputs?
- How does noisy data affect accuracy?
- Why does data poisoning undermine an AI model?
- Why is continuous monitoring important after deployment?

These cards should train the learner to understand **why**, not merely memorize a definition.

---

## 5. Process / Lifecycle Cards

Use when the source describes an ordered process or lifecycle.

Examples may include:

- Data collection → preparation → training → evaluation → deployment → monitoring
- Data cleaning or wrangling stages
- AI governance or risk-management processes
- Secure deployment practices

If order matters, ask for the order. If order does not matter, do not artificially impose one.

---

## 6. Structure / List Cards

Use when the learner needs to recall a defined group of items.

Examples:

- Six domains of AI
- Ethical principles
- Data quality characteristics
- Categories of AI security threats
- Components of a neural network
- Roles involved in AI accountability

When a list is long, consider splitting it into smaller cards rather than forcing a single wall of text.

---

## 7. Scenario/Application Cards

Use realistic scenarios to train transfer.

Example:

**Front**
```html
🗃️ A cybersecurity model was trained on threat data that has not been updated for several years. The model begins missing newer attack patterns.<br><br>What data-quality problem is most directly affecting the model?
```

**Back**
```html
<b style="color:#27AE60">Outdated or stale data</b>.<br><br>AI models depend on current, representative data. Stale threat data can prevent the model from recognizing newly emerging attack patterns.
```

Scenario cards should remain grounded in concepts actually taught by the lesson.

---

## 8. Security Threat and Mitigation Cards

When the lesson covers AI/ML security, create both directions when useful:

- Threat → identify the attack or weakness
- Attack → identify the likely effect
- Weakness → identify an appropriate mitigation
- Mitigation → identify the risk it addresses

These should emphasize recognition and practical understanding.

---

## 9. Ethics / Governance Cards

Ask the learner to identify:

- Which ethical principle is involved
- What governance practice addresses the issue
- Why human oversight is necessary
- Why transparency or explainability matters
- How privacy can conflict with security
- Who may bear accountability for AI outcomes

Avoid turning ethics into vague opinion questions. Ground the card in the course's stated principles.

---

# Card Content Rules

## Self-Contained Cards

Anki cards are served out of order.

Every card must make sense by itself.

Do not write:

- “As discussed above…”
- “From the previous card…”
- “Which of these is the second type?”

Instead, include enough context in the question for independent recall.

## One Primary Learning Target Per Card

Prefer one concept, distinction, relationship, or tightly connected group per card.

Do not cram an entire lesson onto one back.

## Favor Understanding Over Trivia

Ask:

- What is it?
- How is it different?
- What does it do?
- Why does it matter?
- What happens if it fails?
- Which concept fits this scenario?
- Which mitigation best addresses this risk?

Use “Who invented X in year Y?” sparingly unless the source clearly treats the history as important.

## Use the Course's Terminology

Do not replace zyBooks terminology with more advanced industry terminology unless the source itself introduces the advanced term.

A D831 deck should prepare the learner for **D831**, not silently become a graduate-level AI textbook.

## Explanations

Backs should normally provide:

1. The direct answer.
2. A concise explanation.
3. A contrast or consequence when it improves understanding.

Avoid unnecessary essays.

## Acronyms

When an acronym is important, write it out on first meaningful use on the back.

If an acronym is likely to cause recall difficulty, add a short expansion at the bottom of the card.

Do not clutter every card with redundant acronym expansions when the acronym is already obvious from the prompt.

---

# Handling Examples and Case Studies

The textbook frequently uses examples involving:

- recommendation systems,
- healthcare,
- autonomous vehicles,
- cybersecurity,
- facial recognition,
- finance,
- phishing,
- threat detection,
- user behavior,
- deepfakes,
- and other real-world applications.

Use these examples when they help teach a concept.

Do not create cards whose only purpose is to memorize the company, product, person, or anecdote unless that detail is itself emphasized by the lesson.

Example:

Prefer:

> Why is an autonomous vehicle a useful example of the importance of human control and AI safety?

Over:

> In what city did a particular autonomous-vehicle accident occur?

unless the source clearly expects the historical detail to be retained.

---

# Handling Tables, Figures, and Diagrams

Tables, diagrams, and figures may contain important instructional information that is not fully captured by ordinary PDF text extraction.

Use them when their meaning is clear.

Good uses include:

- AI hierarchy diagrams
- Model lifecycle diagrams
- Supervised/unsupervised/reinforcement comparisons
- Neural-network structures
- Data-quality tables
- Threat/mitigation tables
- Ethics or governance frameworks

Convert the **concept represented by the visual** into text-based Anki cards.

Do not create a card that depends on seeing the original figure unless the image will be deliberately embedded into the Anki deck.

---

# Handling Missing or Ambiguous Source Information

If the PDF export is missing information necessary to establish an answer:

- Do not guess.
- Do not infer a keyed answer from an interactive exercise.
- Do not silently fill the gap from outside knowledge.
- Skip the questionable item and continue with the lesson material that is supported.

If the missing material seems important to a Learn to objective, flag it in a short review note after the card file so the user can check the online zyBooks version.

---

# Output Format Requirements

Create a **tab-separated text file** that can be imported directly into Anki.

Include these three header lines at the top:

```text
#separator:tab
#html:true
#tags column:3
```

Each card must contain exactly three tab-separated columns:

1. Front
2. Back
3. Tags

Use a Python script with a `card()` function that calls `.replace('\n', '')` on all content before writing each line.

Every card must therefore exist on a **single physical line** in the output file.

Validate the completed file:

- exactly two tab characters per card line,
- no literal newlines inside a card field,
- three header lines at the top,
- no accidental fourth column,
- valid HTML,
- no duplicate cards unless the duplication serves a deliberate reverse-recall purpose.

---

# HTML and Visual Formatting

The file uses `#html:true`.

Use formatting to improve memory and readability, but keep it restrained and consistent.

## Semantic Color System

Use color intentionally.

- **Blue** — key concepts, terms, categories  
  `<b style="color:#2874A6">term</b>`

- **Green** — correct answer, beneficial practice, desired outcome  
  `<b style="color:#27AE60">text</b>`

- **Red** — risk, attack, failure, warning  
  `<b style="color:#C0392B">text</b>`

Use yellow only when a caution genuinely benefits from a separate visual cue. Do not create rainbow-style cards.

## Technical Terms / Syntax

When commands, code, structured data, or technical syntax appear:

```html
<code style="color:#E74C3C; background:rgba(128,128,128,0.1); padding:2px 4px; border-radius:3px;">text</code>
```

## Callout Boxes

Use neutral backgrounds compatible with both light and dark mode:

```html
<div style="background:rgba(128,128,128,0.15); padding:8px; border-radius:4px;">...</div>
```

Do **not** use hardcoded pastel background colors.

Use `<br>` for line breaks inside fields.

Use `&nbsp;` only when actual indentation is useful.

---

# Emoji Palette

Use emojis only when they improve recognition.

| Emoji | Meaning |
| --- | --- |
| 🤖 | AI / GenAI |
| 🧠 | Machine learning / neural networks / models |
| 🗃️ | Data / datasets / data management |
| 🛡️ | Security / defenses / controls |
| 🔍 | Analysis / detection / evaluation |
| ⚠️ | Risk / caution |
| 🚨 | Attack / incident / harmful activity |
| 🔒 | Privacy / confidentiality |
| ⚖️ | Ethics / fairness / accountability |
| 🔄 | Lifecycle / feedback / continuous improvement |
| 📊 | Metrics / model performance / data quality |
| 🧩 | Frameworks / categories / structures |
| 🎯 | High-value distinction or assessment-focused note |

Do not place an emoji on every card simply for decoration.

---

# Tag Structure

Use hierarchical tags in this format:

```text
D831::ChapterXX::LessonX.Y::CompetencyN::TopicName
```

Examples:

```text
D831::Chapter03::Lesson3.1::Competency1::ArtificialIntelligence
D831::Chapter04::Lesson4.1::Competency1::SupervisedLearning
D831::Chapter07::Lesson7.16::Competency2::DataQuality
D831::Chapter09::Lesson9.5::Competency3::DataPoisoning
D831::Chapter10::Lesson10.17::Competency3::EthicalGovernance
```

Where:

- `D831` = course prefix
- `ChapterXX` = zero-padded chapter number
- `LessonX.Y` = zyBooks lesson/section identifier
- `CompetencyN` = primary competency served by the card
- `TopicName` = concise PascalCase topic

If a card genuinely supports more than one competency, use the primary competency in the hierarchy and add an additional flat tag only when useful.

Do not force a competency tag when the mapping is genuinely ambiguous; identify the most defensible primary competency from the course descriptions.

---

# Approximate Card Volume

Do **not** target a fixed card quota.

Card count should be determined by the density and importance of the current lesson.

Typical guidance:

- Short/simple lesson: approximately **5–15 cards**
- Moderate lesson: approximately **10–25 cards**
- Dense lesson: approximately **20–40 cards**
- Very dense lesson: split into logical parts rather than producing an oversized, repetitive set

These are guidelines, not requirements.

Coverage and card quality are more important than raw quantity.

A repeated concept should not become several nearly identical cards merely to increase the count.

---

# Lesson-by-Lesson Workflow

For each conversion session:

1. Use only the lesson or lessons supplied in the current prompt as the main conversion target.
2. Read the lesson's **Learn to** objectives first.
3. Identify which D831 competency is primarily supported.
4. Extract the core teaching material.
5. Ignore interactive questions by default.
6. Build an internal coverage outline.
7. Generate cards that cover the lesson without needless duplication.
8. Validate the tab-separated output.
9. Report any important source gaps, ambiguous passages, or missing interactive information separately after the file is created.

Do not automatically continue into the next lesson.

The user will normally begin a fresh prompt session after one or two lesson conversions to avoid excessive context accumulation.

---

# Quality-Control Checklist

Before finalizing the file, verify that:

- Every card is supported by the supplied lesson material.
- Learn to objectives have appropriate coverage.
- No provider answer was guessed from an unkeyed interactive activity.
- The cards focus on competency-relevant concepts rather than page trivia.
- Definitions preserve the course's terminology.
- Distinction cards actually distinguish commonly confusable concepts.
- Scenario cards remain faithful to what the lesson teaches.
- Security mitigations are tied to risks described in the source.
- Ethical questions are grounded in stated course principles.
- Data-management cards explain how data affects AI/ML outcomes.
- No card depends on another card for context.
- No card back is unnecessarily long.
- Color is restrained and semantic.
- Acronyms are expanded when useful.
- Tags use the correct chapter and lesson number.
- Every card line contains exactly two tabs.
- No literal newline appears within a Front, Back, or Tag field.
- No duplicate or near-duplicate cards were created unintentionally.

---

# Example Cards

## Example 1 — Core Definition

**Front**
```html
🤖 What is <b style="color:#2874A6">artificial intelligence (AI)</b>?
```

**Back**
```html
<b style="color:#2874A6">Artificial intelligence (AI)</b> is the development and use of algorithms and models to mimic human thought.<br><br>AI can classify data, make predictions, or generate new outputs.
```

**Tags**
```text
D831::Chapter03::Lesson3.1::Competency1::ArtificialIntelligence
```

---

## Example 2 — Concept Distinction

**Front**
```html
🧠 What is the key difference between <b style="color:#2874A6">Narrow AI</b> and <b style="color:#2874A6">General AI</b>?
```

**Back**
```html
<b style="color:#2874A6">Narrow AI</b> is specialized for specific tasks and lacks broad human-like adaptability.<br><br><b style="color:#2874A6">General AI (AGI)</b> refers to a theoretical form of AI capable of learning and adapting across diverse domains in a more human-like way.<br><br>🎯 Current real-world AI systems are generally examples of <b>Narrow AI</b>.
```

**Tags**
```text
D831::Chapter03::Lesson3.6::Competency1::NarrowVsGeneralAI
```

---

## Example 3 — Data Quality

**Front**
```html
🗃️ Why can <b style="color:#C0392B">incomplete or outdated training data</b> reduce the effectiveness of an AI cybersecurity system?
```

**Back**
```html
Incomplete data can omit important threat characteristics, while outdated data may fail to represent newer attacks.<br><br>The result can include <b style="color:#C0392B">false positives, missed attacks, misclassification, and poor automated decisions</b>.<br><br>High-quality AI depends on data that is accurate, current, relevant, and sufficiently representative.
```

**Tags**
```text
D831::Chapter07::Lesson7.16::Competency2::DataQuality
```

---

## Example 4 — Security/Application

**Front**
```html
🚨 An attacker intentionally inserts misleading examples into an AI system's training dataset so the resulting model learns incorrect behavior.<br><br>What type of attack is this?
```

**Back**
```html
<b style="color:#27AE60">Data poisoning</b>.<br><br>Data poisoning corrupts the training data so the model learns distorted or attacker-controlled patterns, reducing model integrity and potentially causing incorrect predictions or security decisions.
```

**Tags**
```text
D831::Chapter09::Lesson9.X::Competency3::DataPoisoning
```

---

## Example 5 — Ethics / Governance

**Front**
```html
⚖️ Why is <b style="color:#2874A6">human oversight</b> important when AI systems make decisions that can affect people?
```

**Back**
```html
Human oversight helps ensure that AI decisions remain reviewable and that errors, bias, unsafe behavior, or inappropriate automated decisions can be identified and corrected.<br><br>It supports <b style="color:#2874A6">accountability</b>, <b style="color:#2874A6">fairness</b>, and <b style="color:#2874A6">human control</b>.
```

**Tags**
```text
D831::Chapter10::Lesson10.X::Competency3::HumanOversight
```

---

# Final Instruction

Using the supplied zyBooks lesson material, create a complete Anki-ready tab-separated file following all rules above.

Focus on the **lesson's teaching material**, not the unkeyed interactive exercises embedded in the PDF.

Use the D831 competencies, competency weights, lesson **Learn to** objectives, syllabus, and Course Kick Start Guide to prioritize the material at the level appropriate for the WGU Objective Assessment.

Do not attempt to convert the entire textbook at once. Work only on the lesson or lessons supplied for the current session.
