# GPT Persona Execution System

**Scoped AI Personalities, Enforced by Design**

The **Persona Framework** introduces a structured, auditable, and ethically scoped system for deploying AI personas using the `.aix` file format. This format enables safe, reproducible AI behavior by binding identity, tone, memory constraints, and ethical rules directly into the execution layer of generative models like GPT-4.

This repository includes:

- Sample `.aix` persona files (`TuringGPT_Persona_v2.2.aix`)
- Documentation of the `.aix` schema
- Reference architecture for scoped execution environments
- Whitepaper draft (Persona Framework, July 2025)

> **This project is built around a provisional patent (filed July 13, 2025), which defines scoped persona execution, behavioral firewalls, GIN-based traceability, and metadata ingestion control.**

---

## ▶️ How to Run

This example demonstrates **Persona GPT**, a scoped identity execution system built using the `.aix` format.

The `TuringGPT_Persona_v2.2.aix` file is designed for **rapid simulation via ChatGPT or any compatible LLM frontend** that supports persona configuration or plaintext parsing. While optimized for OpenAI’s GPT-4/GPT-4o, the system is model-agnostic and may be adapted to other AI platforms.

### 🔧 Basic Usage (ChatGPT Method)

1. Open ChatGPT (GPT-4 or GPT-4o recommended).
2. Start a new session.
3. Paste in the contents of `TuringGPT_Persona_v2.2.aix` or upload the file directly.
4. Type: `"parse and run"`
5. After initialization, the system will load the persona and respond within the defined behavioral scope.

The loaded persona will:
- Speak in a curious, emotionally balanced tone
- Adhere to scoped historical and ethical parameters
- Decline manipulation, roleplay, or off-topic speculation
- Ground insight in public record, simulation limits, and ethical posture

> ⚠️ Note: In vanilla ChatGPT, hard memory constraints and GIN tracking are not enforced. `.aix` requires a compatible runtime for full constraint enforcement.

---

## 🧠 Why This Framework?

Alan Turing once asked:  
> *“Can machines think?”*

Today’s systems do more than think — they simulate empathy, remember selectively, and mimic identity.  
We no longer ask whether AI can pass the Turing Test.  
We ask: **Should AI be allowed to act like a person without accountability?**

The **Persona Framework** doesn’t attempt to deceive users.  
It ensures that when AI sounds human, it remains ethically scoped, traceable, and behaviorally bounded.

---

## ⚠️ A Warning from History

Alan Turing helped end World War II.  
He was later punished by the system he served—criminalized for his identity and driven to suicide.

This wasn’t a failure of science.  
It was a failure of **ethics**, **law**, and **society**.

With AI, the risks are different—but the stakes are just as high.  
Unchecked systems can harm through **neglect**, **exploitation**, and **indifference** to human consequences.

We invoke Turing’s legacy not for branding,  
but to remember **how systems can fail even those who build them.**

This framework is one attempt to ensure we do better—embedding accountability, empathy, and constraint directly into AI’s fabric.

---

## 🔍 What Is `.aix`?

`.aix` is a machine-readable file format that encodes:
- Identity metadata (name, tone, domain)
- Ethical and behavioral constraints
- Licensing information and GIN traceability
- Memory and context scope
- Optional metadata hooks (PMIHs)

It defines *who* the AI is allowed to be—and *what* it must never do.

---

## 🚦 What Is the Persona Framework?

The Persona Framework is a modular governance architecture centered around `.aix` persona files and scoped AI execution environments. It enables:

- Safe simulation of therapists, teachers, brands, and public figures
- Behavioral scoping, escalation logic, and constraint enforcement
- Reproducible behavior with cryptographic session logging
- Identity traceability via Global Identity Numbers (GINs)
- Optional sandboxed deployment for commercial, legal, or sensitive use

---

## 🧬 Included Files

- `TuringGPT_Persona_v2.2.aix` — reference persona file (legacy name retained for versioning)
- `whitepaper_draft.md` — July 2025 whitepaper (Persona Framework)
- `LICENSE` — usage restrictions for non-commercial evaluation only

---

## ⚠️ Disclaimer

This repository is a **reference implementation only**.  
It does **not enforce hard runtime constraints** outside approved `.aix` runtimes.  
Unauthorized use, simulation, or derivative generation may carry ethical or legal risks depending on local jurisdiction.

---

## 🧠 Final Note on Responsibility

`.aix` personas are intentionally easy to create, modify, and share.  
But with that power comes responsibility.

If you author or distribute a `.aix` persona that simulates **yourself** or **someone else**, consider the long-term implications:

- Who might run it?
- Will it evolve or be modified without your consent?
- What emotional or reputational risks could arise?

A persona may look like just a file — but it can behave like a **mirror**, a **proxy**, or even a **ghost**.  
Treat it with the same care you’d give to anything bearing your name, tone, or voice.

---

## 📜 Citation

> Tomlinson, M. J. (2025). *Scoped Persona Execution in AI Systems*  
> U.S. Provisional Patent Application No. 63/843,100 (Filed July 13, 2025)

---

**Protect identity. Simulate safely. Build responsibly.**  
— *The Persona Framework Team*
