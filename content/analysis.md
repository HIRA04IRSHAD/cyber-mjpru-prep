# PYQ analysis: what MJPRU actually asks

Three MJPRU Cyber Security papers analysed: the 2025-26 end-sem, Mid-1 2025 and Mid-2 2025. No older papers are available (see [All past papers](#pyqs)), so this analysis leans on one more fact: **MJPRU teachers reuse their own mid-sem questions in the end-sem**, and the syllabus is short enough that the same 15 topics must come again.

::: tip The one-line summary
Of the 8 mid-sem questions, **4 came back in the end-sem almost word for word** (cyber security + CIA model, one-way hashing, DSA, cyber law and copyright) and **2 more came back as close variants** (Playfair → substitution vs transposition; e-mail policy → need for security policies). Every end-sem question came from a syllabus line. If you can write the 16 parts of the 2025-26 paper, plus the syllabus topics it skipped, you are ready.
:::

## Topic frequency (how many of the 3 papers asked it)

| Rank | Topic | Unit | Asked in | Count | Chance this year |
|---|---|---|---|---|---|
| 1 | **Cyber security + CIA model** | 1 | End Q1(b), Mid-1 Q2 (same words) | 2 / 3 | Very high |
| 2 | **One-way hash function with one algorithm (MD5/SHA)** | 3 | End Q4(b), Mid-2 Q1 | 2 | Very high |
| 3 | **Digital signature and DSA** | 3 | End Q5(b), Mid-2 Q2 | 2 | Very high |
| 4 | **Cyber law, IT Act 2000, copyright** | 5 | End Q8(i)(ii), Mid-2 Q4 | 2 | Very high |
| 5 | **Classical ciphers: Playfair; substitution vs transposition** | 3 | End Q4(a), Mid-1 Q4 | 2 | Very high |
| 6 | **Security policies: need, e-mail, web** | 4 | End Q7(a)(b), Mid-2 Q3 | 2 | Very high |
| 7 | **Information system: types, development (SDLC)** | 1 | End Q1(a), Mid-1 Q1 | 2 | High |
| 8 | **Components / aspects of information security** | 2 | End Q2(b), Mid-1 Q3 | 2 | High |
| 9 | **X.800 security services and mechanisms** | 2 | End Q3(a) | 1 | High (core Stallings topic) |
| 10 | **Security attacks: passive and active** | 2 | End Q3(b) | 1 | High |
| 11 | **Public key cryptography + RSA with an example** | 3 | End Q5(a) | 1 | High |
| 12 | **Digital watermarking (full 14 marks)** | 3 | End Q6 | 1 | High |
| 13 | Ethical and professional issues | 1 | End Q2(a) | 1 | Medium-high |
| 14 | ISO standards (ISO 27001) and IPR | 5 | End Q8(iii) | 1 | Medium-high |
| 15 | 3DES with two keys | (not in syllabus) | End Q8(iv) | 1 | Low |
| — | **Not yet asked:** need of information security, business need, security model (Stallings / McCumber), cryptanalysis, XOR and one-time pad, arbitrated and adjudicated protocols, policy review process, corporate and sample policies, patent law, software licences | 1–5 | never | 0 | Medium: the syllabus is short, so expect 2–3 of these |

```mermaid
flowchart LR
  A[Unit 1<br/>~19% of marks] --- B[Unit 2<br/>~19%]
  B --- C[Unit 3<br/>~37%]
  C --- D[Unit 4<br/>~12.5%]
  D --- E[Unit 5<br/>~12.5%]
```

## Unit-wise weight (2025-26 end-sem, 16 parts of 7 marks)

| Unit | Questions | Marks (of 112 on paper) |
|---|---|---|
| Unit 1 · Information systems & security | Q1(a), Q1(b), Q2(a) | 21 |
| Unit 2 · Security model, attacks, X.800 | Q2(b), Q3(a), Q3(b) | 21 |
| Unit 3 · Cryptography & signatures | Q4(a), Q4(b), Q5(a), Q5(b), Q6 | 42 |
| Unit 4 · Security policies | Q7(a), Q7(b) | 14 |
| Unit 5 · Standards & cyber law | Q8 (short notes) | 14 |

You need only 5 of 8 questions. **Units 1, 2 and 3 together gave 6 of the 8 questions**, so those three units done well are enough to choose 5 comfortably; Units 4 and 5 are one question each and are easy marks.

## The two "worked example" questions

Cyber Security has no long numericals, but two questions expect a worked example. Practise both by hand:

1. **Playfair cipher** (Mid-1): build the 5×5 key square, split the plaintext into digraphs, apply the three rules. A 7-mark answer needs a full worked example.
2. **RSA** (End Q5a): choose p and q, compute n, φ(n), e, d, then encrypt and decrypt a small number. Use p = 3, q = 11 or p = 17, q = 11 (both worked in [Unit 3](#unit3)).

Substitution vs transposition (End Q4a) also needs one small example of each, such as Caesar and rail fence.

## Repeat-question patterns

- **"What is X? Explain/Describe Y in details"** is the standard template: part one is the definition (half a page), part two the body (3–4 pages).
- **"How many types of …?"** appears three times (types of IS, aspects, attacks). Start these answers with the number and a tree diagram: "There are two types of security attacks: passive and active", then the diagram, then each type.
- **The mid papers preview the end-sem.** Mid-2 questions (hashing, DSA, cyber law) all came back. Expect the 2026-27 mids to work the same way: when your Mid-2 paper comes, treat every question on it as a likely end-sem question.
- **Short notes (Q8)** are "any two of four". Prepare half-page notes on IT Act 2000, cyber law, copyright, patent, ISO 27001, IPR and software licences.

## Predicted end-sem 2026-27 (most likely 8 questions)

| Q | (a) | (b) |
|---|---|---|
| 1 | Types of information system (pyramid) | Cyber security and the CIA model |
| 2 | Development of information system (SDLC) OR need / business need of information security | Ethical and professional issues |
| 3 | Information security model / components of information security | Aspects; security attacks (passive and active) |
| 4 | X.800 security services and mechanisms | Substitution vs transposition / Playfair with an example |
| 5 | One-way hash function (MD5 or SHA-1) | Public key cryptography and RSA with an example |
| 6 | Digital signature and DSA | Digital watermarking: characteristics and types |
| 7 | Need for security policies; e-mail security policy | WWW policy / web security; policy review process |
| 8 | Short notes: IT Act 2000, cyber law, copyright, patent, ISO 27001, IPR, software licence | |

**Mock Paper 1** on this site is built on this prediction.
