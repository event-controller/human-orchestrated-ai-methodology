# Human-Orchestrated AI Inquiry and Framework Development

## An Adaptive, Data-Centered Methodology for Investigation, Synthesis, Critical Examination, and Learning

**Version:** 1.0  
**Consolidated:** October 26, 2026  
**Status:** Descriptive methodological framework  
**Basis:** The *Iterative Representation Framework for AI Reasoning*, *HOMMM Framework v2*, and subsequent explanations and corrections of actual practice.

> **Central principle:** The AI model is not the methodology. The human selects the intellectual operation, supplies and examines information, directs the transformation of that information, evaluates the result, and decides what happens next.

---

## Abstract

This framework documents a personal method of working with multiple AI systems to investigate subjects, develop understanding, construct portable frameworks, examine weaknesses, preserve intellectual work, and generate better questions. It combines an operational architecture for using AI resources with an iterative method for transforming information into more useful representations.

The approach is **human-orchestrated, data-centered, adversarial, adaptive, and provider-agnostic**. A model is chosen for the work to be done, not because a predetermined sequence requires it. The human maintains responsibility for intent, interpretation, information quality, error diagnosis, and the decision to continue, revise, branch, or finish.

The resulting artifacts serve several purposes: they are project outputs, transferable reasoning states, versioned records, and tools for developing the human's own understanding. Separate frameworks can later be compared, not necessarily to merge them, but to discover relationships and formulate broader yet more precise questions in other investigations.

This document is a **description of the reported methodology**, not a claim that it has been experimentally proven superior to other workflows. It can help explain the likely process behind an older artifact without pretending to reconstruct undocumented decisions.

---

# Part I — Foundations

## 1. The Unit of Work Is the Reasoning Operation

A single prompt is not expected to perform every part of a complex investigation. Different intellectual operations can be separated, sequenced, repeated, or omitted:

- obtain or examine information;
- explore a concept and establish understanding;
- formulate and refine questions;
- externalize a conversation into a framework;
- expand, restructure, or synthesize the artifact;
- examine assumptions, contradictions, mathematical claims, or omissions;
- verify important claims by appropriate means;
- preserve a version, reopen an inquiry, or connect other projects.

The human first considers **what needs to happen intellectually**, then which available AI environment is appropriate. Consequently, two projects may use substantially different routes while following the same methodology.

The iterative principle inherited from the *Iterative Representation Framework* is:

> **Explore → Externalize → Structure → Critique → Verify → Consolidate → Re-open → Explore**

This is a map of possible transformations, **not a mandatory checklist or fixed pipeline**. An uncomplicated project may need only framework construction and a single review; a complex one may require many cycles.

## 2. A Computational, Information-Centered Philosophy of AI

AI is approached operationally as a **computer and computational instrument** available through a chat interface. The description of a *statistical engine attached to a database* expresses a philosophical and practical mental model, drawing on the statistical and probabilistic language used in explanations of language models. It is not intended as a literal technical specification of every model's architecture.

Two functions are central:

1. **Information access:** investigate concepts, interrogate available information, gather context, and examine what is known or missing.
2. **Information manipulation and synthesis:** reorganize data, develop relationships, reason over material, construct frameworks, and generate further questions.

The emphasis is **data-centered**. When a result is unreliable, an initial line of investigation is whether the necessary information was missing, outdated, incorrect, overloaded, insufficiently relevant, poorly represented, or lost from the effective conversational context. The aim is to identify a mechanism that can be acted upon rather than explain every failure by saying that a model is simply bad.

This preference does **not** require the claim that every hallucination or error is a retrieval failure. Errors of interpretation, inference, execution, and generation can occur too. The practical question is which mechanism best explains the observed failure and what intervention is justified.

## 3. Adversarial Epistemology: Criticism as Data

The human takes an adversarial stance toward **their own** interpretations and methods, not merely toward AI outputs. Negative feedback, disagreement, and criticism can identify information worth investigating.

Critique operates on two levels:

- **Artifact-level correction:** What is mistaken, unsupported, inconsistent, omitted, or inadequately expressed in this project?
- **Method-level correction:** What in the investigative process allowed that weakness to appear or survive, and can the process be adjusted to narrow the scope of similar failures in future work?

Criticism is neither automatically correct nor automatically hostile. It is evidence or a hypothesis to examine. Agreement among models is also not conclusive evidence of truth: models may share sources, premises, or errors. Disagreement can be productive when it reveals an assumption or interpretive difference.

The framework therefore separates three questions:

1. **Fidelity:** Did the system understand and represent the intended question or design?
2. **Coherence:** Do the statements and arguments remain internally consistent?
3. **Grounding:** Are the relevant premises and claims justified by evidence or appropriate tests?

A document can succeed at one while failing at another.

## 4. Conceptual Understanding Before Further Construction

When an unfamiliar concept is important to the investigation, the human may temporarily stop progressing the main project and investigate that concept until they acquire a sufficient working understanding to continue.

The practice is:

> **Encounter a conceptual gap → investigate it → establish a working grasp → return with better questions.**

This is not a claim of complete mastery. It is a method of avoiding unnecessary reasoning built upon terms that have not yet been understood.

## 5. Logic as Constraint-Guided Investigation

In practical use, a problem is understood through its initial information, desired end state, and the logical constraints and relationships connecting them. The human reads AI responses carefully to determine whether intermediate reasoning preserves the intended meaning and constraints.

This includes comparing a new response with statements made two or three turns earlier to detect:

- changes in definitions or scope;
- dropped requirements or context;
- unsupported increases in certainty;
- contradictions between earlier and later claims;
- syntactic or contextual shifts that alter the original question.

Individual prompts may be written, reconsidered, and revised several times before submission. **Prompt precision matters**, but it operates inside a larger workflow rather than substituting for that workflow.

Keeping the discussion aligned with the intended project does not mean shielding its premises from challenge. Misunderstanding the project and correctly criticizing it are different events and call for different responses.

---

# Part II — Human Orchestration and AI Resources

## 6. The Human Is the Central Orchestrator

The human determines the subject, aims, required depth, evidence standards, next operation, model choice, interpretation of feedback, and state of the project.

The human also holds the project outside individual AI conversations by maintaining its documents and versions. Models can assist with reasoning and representation, but **no single model is treated as the authoritative keeper of the project's intellectual state**.

This builds upon the human-orchestrated principle in *HOMMM* while allowing the actual routing to be more flexible than the original architecture's diagrams might suggest.

## 7. Adaptive, Provider-Agnostic Model Selection

Model choice is contextual. Relevant considerations include:

- the immediate intellectual operation;
- task difficulty, consequences, and desired depth;
- information access and tool availability;
- long-document handling and response length;
- observed analytical behavior, conversational personality, and epistemic tendencies;
- formatting, code execution, and file-production capabilities;
- cost, remaining usage, and the value of preserving a limited resource;
- personal experience and familiarity with the interface.

Six systems have become frequent choices through use, rather than through a claim that they are uniquely best:

| System | Reported uses and preferences |
|---|---|
| **Gemini** | Concept exploration, extended questioning, general information work, and lower-stakes everyday queries; commonly accessed through its app. |
| **DeepSeek** | Developing, expanding, and revising substantial frameworks; valued for long responses in the user's experience. |
| **ChatGPT** | Detailed examination of assumptions, overclaims, contradictions, and other weaknesses; continued refinement when appropriate. |
| **Claude** | Noticing subtle issues, writing or running code where supported, converting or producing `.md` and `.docx` files, and document finishing work. |
| **Grok** | Gathering and parsing online material and searching for conceptual overlap between a framework and existing ideas. |
| **Qwen** | Analyzing individual documents, checking mathematical and syntactic consistency or self-contradiction, comprehensively exploring frameworks, and synthesizing multiple large documents to generate questions. |

**Genspark** is an occasional intensive review resource. A high-thinking configuration may be used for a substantial one-off examination while preserving usage availability in other systems.

These are **experienced preferences, not exclusive model assignments or independently validated rankings**. The same model can serve several operations, and the same operation can be performed by several models.

Other available alternatives include Kimi, Mistral, Meta AI, Perplexity, and others. In a hypothetical substitution, Meta could serve some roles associated with Gemini, Mistral with DeepSeek, Kimi with analysis and refinement, and Perplexity with online research. The user has tried some of these alternatives and regards several as strong options. **The methodology is intended to survive substitution of providers**, although actual performance and available features may differ.

## 8. Resource Proportionality

Not every question needs a frontier model's most intensive settings or a multi-model review.

A routine, low-consequence question may be handled by one readily available model. A consequential claim or complex synthesis may justify deeper examination, external verification, or specialized tools. Resource limits matter: it can be sensible to allocate a one-off analysis to Genspark rather than use an allowance in Claude that may be needed for later file work.

The decision rule is:

> **Use the resources justified by the problem, while retaining the option to escalate when the result requires it.**

This is an allocation principle, not a fixed formula. A model's highest thinking setting should not by itself be interpreted as guaranteed accuracy or complete verification.

## 9. Native Interfaces and Practical Portability

The observed workflow often uses consumer-facing apps, browser tabs, bookmarks, copy-and-paste, and externally saved files. It need not depend on APIs or an automated orchestration layer.

Native interfaces can be valuable where they expose tools or production features that matter to a particular task. The broader bookmark collection maintains optional capabilities, even though actual use concentrates on a smaller, familiar group.

The **available toolkit** and the **habitually used toolkit** should not be confused. Likewise, habitual preference does not prove superiority.

---

# Part III — The Adaptive Project Cycle

## 10. Initiation and Concept Exploration

A project may begin with a preexisting idea or with a topic selected for investigation. The human examines surrounding concepts, asks questions, reads carefully, and develops additional questions as the subject becomes clearer.

The direction is **guided but not fully predetermined**: the intended design is maintained, while the logic and findings of the inquiry can reveal useful new paths. The human checks throughout whether the AI actually understands and responds to the questions being asked.

If necessary, an unfamiliar concept becomes a temporary sub-investigation before the main thread resumes.

## 11. Framework Externalization

After sufficient exploration, the human may ask the AI for a **framework**. In practice, this particular instruction has been useful for transforming a long conversation into a structured, transferable document rather than merely a chronological recap.

The AI response may be copied into a `.md`, `.txt`, or other file and saved outside the conversation. The requested framework may organize definitions, assumptions, claims, relationships, evidence, uncertainties, and questions, depending on the project.

The resulting document is a **portable reasoning artifact**. It is not assumed to preserve everything perfectly: consolidation can omit context, strengthen an originally tentative claim, or impose coherence on unsettled information. Where important, these losses should be examined.

## 12. Transfer, Context Preparation, and Development

The saved artifact may be introduced into another AI system. In one reported pattern, the human first asks a few focused questions in the receiving conversation to establish the relevant conceptual direction, then supplies the framework for examination or expansion.

The receiving system may challenge the framework, explore implications, reorganize sections, or develop a substantially longer document. The choice depends on the project's needs and the receiving environment's strengths.

**Context preparation** and **artifact transfer** are distinct operations. Their combination may help guide the next examination, although a benefit should not be assumed in every case.

## 13. Critical Examination, Verification, and Feedback

At any stage, an artifact can be sent for focused scrutiny. Possible examinations include:

- unstated assumptions and overclaims;
- internal contradiction and changes in terminology;
- mathematical or syntactic inconsistencies;
- missing dependencies or unexplained reasoning steps;
- evidence gaps and factual claims needing source inspection;
- overlooked alternatives or conceptual overlap with existing work;
- whether the artifact remains faithful to the intended project.

The human interprets findings and decides which warrant further investigation. Feedback may return to the main development conversation or be used in another environment. A separate conversation may be created solely to examine one issue, with any useful insights carried back afterward.

No criticism is automatically incorporated. A correction should address an actual problem, not merely make the document more persuasive or polished.

## 14. Versioned Storage and Project Continuity

Framework replies and later versions are saved in the human's own storage. Earlier versions remain available, and the latest version can be shown to any suitable AI.

This establishes continuity outside one chat thread or provider. It supports:

- recovery of earlier states;
- further development without rebuilding the entire original conversation;
- isolated examination without automatically replacing the main document;
- reuse of a framework in other projects;
- comparison of earlier and later representations.

Version preservation does not, by itself, record why every change was made. Unless such explanations were separately captured, later accounts of those decisions remain partly inferential.

## 15. Completion Is Context-Dependent

A project may involve hours or days of work, or be satisfactorily finished through one model plus a brief second examination. There is no universal number of iterations, models, or pages.

The human decides when the artifact is sufficient **for its current purpose**. Completion is not a declaration of permanent truth or immunity from future revision.

A project can also be reopened when a new question, contradictory evidence, or related framework makes further work useful.

---

# Part IV — Learning Across Artifacts

## 16. Frameworks as Learning Instruments

Frameworks are not only final deliverables. They are objects through which the human learns more about a subject.

An individual framework can be explored further after completion. Several frameworks can also be examined together—for example, by using Qwen to look for relationships, distinctions, shared assumptions, tensions, or implications.

The purpose of combination is **not necessarily to produce one large master framework**. It may simply be to improve the human's grasp of the material. A newly recognized relationship can generate a more informed question for a different project.

This produces two forms of iteration:

1. **Within-project:** improve and examine a developing artifact.
2. **Across-project:** use relationships among stored artifacts to improve understanding and generate questions elsewhere.

The effect sought is not just more questions, but questions that can be **broader in conceptual reach while more specific in what they ask**.

## 17. Three Interacting Learning Loops

### A. Artifact loop

**Develop → externalize → inspect → correct → preserve or reopen.**

The focus is the quality and usefulness of a particular intellectual artifact.

### B. Human-understanding loop

**Encounter an idea → investigate → represent → compare → understand differently → ask better questions.**

The focus is growth in the human's ability to interrogate the subject. A framework may remain unchanged while understanding improves.

### C. Method-correction loop

**Observe a failure → diagnose plausible mechanisms → revise an investigative habit → watch for recurrence or new failure modes.**

The focus is on improving how work is conducted. An error in an artifact can therefore become feedback about the methodology itself.

These loops interact but should not be collapsed into one. **An improved document, improved understanding, and an improved method are three different possible outcomes.**

---

# Part V — Safeguards and Limits

## 18. A Mechanistic Failure-Analysis Lens

When something goes wrong, possible explanations are examined rather than assuming a single cause:

| Possible mechanism | Diagnostic question | Potential response |
|---|---|---|
| Missing or outdated information | Did the system have adequate, current facts? | Retrieve or inspect better evidence. |
| Irrelevant or excessive context | Did important information become obscured? | Narrow, restructure, or consolidate context. |
| Representation or compression loss | Did a framework change the status or meaning of a claim? | Compare versions and restore uncertainty or dependencies. |
| Interpretation drift | Did the model stop answering the intended question? | Clarify wording and restore constraints. |
| Invalid inference | Does the conclusion actually follow from the premises? | Reconstruct and challenge the reasoning. |
| Unsupported agreement | Are multiple models repeating the same premise? | Seek independent evidence or an alternative framing. |
| Task execution failure | Did the output violate an explicit requirement? | Recheck the result against requirements or use a more suitable tool. |

The table is a **diagnostic aid**, not a verified taxonomy assigning measured causes to all AI failures.

## 19. Avoiding Polished Error and Framework Lock-In

Structured outputs can make a mistaken premise look increasingly convincing. Repeated refinement may improve internal coherence without improving correspondence to reality.

Therefore:

- challenge the premises, not only the presentation;
- preserve distinctions between established claims, evidence-supported claims, hypotheses, disputes, and open questions;
- occasionally ask whether the framework itself is the wrong representation;
- use external evidence or deterministic tools when the claim requires them;
- do not treat model consensus, long reasoning, or polished writing as proof.

The objective is useful representation **without concealing unresolved uncertainty**.

## 20. Match Verification to the Claim

Different assertions call for different checks:

| Claim type | Appropriate check |
|---|---|
| Numerical or mathematical | Independent calculation, code, or formal derivation where feasible |
| Structured or syntactic | Parser, validator, test, or programmatic inspection |
| Source-based | Original source, date, context, and corroboration |
| Logical | Reconstruction of premises, dependencies, and conclusions |
| Empirical | External observations and relevant evidence |
| Conceptual | Alternative interpretation, independent reconstruction, counterexamples |

AI critique can help locate a problem; it does not automatically supply independent verification of the answer.

---

# Part VI — Examples, Retrospection, and Scope

## 21. Illustrative Routes Through the Method

These are **examples described in conversation**, not required pipelines.

### Route A — Extended conceptual project

1. Investigate a topic in Gemini, questioning it until the intended subject and emerging ideas are sufficiently clear.
2. Ask for a framework and save the resulting document.
3. Introduce relevant questions, then the artifact, to DeepSeek for comprehensive development.
4. Ask ChatGPT to examine assumptions, overclaims, and weaknesses.
5. Bring useful findings back for further revision; use other tools or Claude for additional examination or finishing work if justified.
6. Preserve the resulting version.

### Route B — Information-intensive project

1. Gather and parse online information with Grok or another suitable research tool.
2. Transfer the material to a development environment such as DeepSeek.
3. Construct and examine a framework, using additional systems only if needed.
4. Save the artifact.

### Route C — Compact project

1. Develop a framework directly with DeepSeek or another suitable model.
2. Conduct one targeted examination, potentially in Genspark at a high-thinking setting.
3. Correct any meaningful issues and mark the document complete for its purpose.

### Route D — Revisit and connect prior work

1. Select one or more previously saved frameworks.
2. Examine them in Qwen or another capable model for implications, internal issues, or relationships.
3. Use what was learned to form more informed questions about the same or different projects.
4. Revise documents only if the investigation warrants it.

## 22. What the Method Can Explain About Older Projects

Because the workflow is context-dependent, this document is best treated as a **methodological record**, not a universal project log.

For an artifact created six months ago, the framework can explain:

- the general reasons for investigating, structuring, and externalizing information;
- why the work might have been transferred between AI environments;
- why it may contain definitions, relationships, critiques, or revisions;
- how external storage made it reusable and examinable later;
- the kinds of reasoning and error-correction operations that were available.

It can also support **qualified hypotheses** about how a particular structure may have emerged.

It cannot establish without additional records:

- which model wrote a specific sentence or section;
- the exact prompt sequence and timing;
- which checks were actually performed;
- what evidence was consulted at a particular moment;
- why one specific revision or conclusion was accepted;
- whether the current workflow was identical six months earlier.

For retrospective use, distinguish **documented history**, **recollection**, **inference from the general method**, and **unknowns**. Never turn a plausible explanation into a claimed historical fact.

## 23. Relationship to the Two Foundational Documents

### HOMMM Framework v2

HOMMM contributed the view of the human as an active orchestrator of an accessible multi-model environment: routing information, preserving direct access to useful interfaces, and resisting dependence on one provider.

The present account refines earlier, stronger formulations. Multiple-model agreement is **not** treated as automatically yielding objective truth; model families are **substitutable where suitable**; the system is not guaranteed full resilience if a provider changes; and the practical workflow need not use every part of the model collection.

### The Iterative Representation Framework for AI Reasoning

This document contributed the shift from a single prompt toward **successive transformations of a reasoning state**, together with critique, verification, loss-aware consolidation, causal traceability, and deliberate re-opening of settled-looking frameworks.

The present account locates those operations inside a more explicitly human-directed practice, with attention to model selection, resource usage, stored artifacts, cross-project learning, and method correction.

Neither earlier document is replaced as a historical record; this framework synthesizes the later clarification of how the method is actually used.

## 24. Evidence Status and What Remains Open

**Established by self-report in this account:** The user employs multiple AI systems, often uses frameworks as transfer artifacts, maintains files and versions, checks outputs against intended meaning, values criticism, chooses models adaptively, and uses stored work to generate further questions.

**Reasonable interpretation:** These practices form a coherent human-orchestrated methodology with interacting artifact, understanding, and method-improvement loops.

**Not established here:** Relative effectiveness versus alternative workflows, comparative model performance under controlled conditions, a numerical failure reduction, or the exact history of undocumented past projects.

These limits are not defects to hide. They express the same adversarial discipline that the methodology seeks to practice.

---

# Part VII — Compact Description

## 25. How I Describe My AI Workflow

> I use AI as a set of computational tools for accessing, examining, and synthesizing information. I start with a problem or idea, explore the underlying concepts, and check that I understand them before developing the work further. I guide the conversation closely, reviewing whether the AI has preserved my intended meaning and the logical constraints of the task.
>
> When the investigation has developed sufficiently, I often ask for a framework. That produces a structured document I can save, version, transfer between AI systems, and examine separately from the conversation that generated it. I choose models according to the task, their observed behavior and available capabilities, and the resources I want to preserve. I do not follow a compulsory model sequence.
>
> I treat criticism and errors as information. I examine weaknesses in the artifact and, when useful, the method that produced them. Sometimes I refine a project extensively; sometimes a single review is enough. I also revisit or compare completed frameworks to deepen my own understanding and generate more informed questions for other projects.
>
> The models and tools are interchangeable where appropriate. What remains consistent is my control over the questions, information, reasoning process, artifacts, and decision to continue or stop.

---

## Core Principle

> **Do not optimize merely for the next AI answer. Organize information, computation, criticism, and preserved representations so that the human can develop better artifacts, better understanding, and better questions—while remaining open to correction.**
