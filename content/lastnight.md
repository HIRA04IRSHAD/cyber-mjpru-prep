# Last-night sheet

Everything to read the evening before the exam: definitions to write word for word, the lists examiners count, the diagrams to practise once, and the worked examples to rehearse.

## Definitions (underline these in the exam)

| Term | Definition |
|---|---|
| Information system | Organised combination of people, hardware, software, data, procedures and networks that collects, processes, stores and distributes information to support decisions |
| Information security (CNSS) | Protection of information and its critical elements, including systems and hardware, from unauthorised access, use, disclosure, disruption, modification or destruction, to provide C, I, A |
| Cyber security | Protecting computers, servers, mobile devices, networks, programs and data from digital attacks, unauthorised access, damage or disruption |
| CIA triad | Confidentiality, Integrity, Availability: the three essential characteristics of secure information |
| Security attack (X.800) | Any action that compromises the security of information owned by an organisation |
| Security mechanism | A process or device designed to detect, prevent or recover from a security attack |
| Security service | A service that enhances security, counters attacks and uses one or more mechanisms |
| Cryptography | Art and science of keeping messages secure by transforming them into an unreadable form |
| Cryptanalysis | Recovering plaintext or key without knowing the key |
| One-way hash | H(M) of fixed length; easy to compute, infeasible to invert or to find collisions |
| Public key cryptography | A public key and a private key; what one encrypts only the other decrypts |
| Digital signature | Code computed from the message hash with the signer's private key, verifiable with the public key |
| Digital watermarking | Embedding a (usually imperceptible) mark in digital content to prove ownership or detect tampering |
| Security policy | Management-approved statement of rules for protecting information assets |
| Cyber law | Law dealing with cyberspace: cyber crime, e-commerce, e-records, digital signatures, data protection, IPR |

## Lists examiners count

- **Types of IS (7):** TPS, OAS, KWS, MIS, DSS, ESS, ES. *The Office Knows, Management Decides Everything.*
- **SDLC (7):** planning/feasibility, analysis, design, development, testing, implementation, maintenance. Feasibility = **TELOS**.
- **Six IS components:** hardware, software, data, people, procedures, networks. *Happy Students Download PDFs Pretty Nicely.*
- **Whitman's 7 critical characteristics:** availability, accuracy, authenticity, confidentiality, integrity, utility, possession.
- **Four business needs:** functionality of the organisation, safe operation of applications, protecting data, safeguarding technology assets.
- **Three aspects (X.800):** attack, mechanism, service.
- **Attacks:** passive = release of message contents, traffic analysis; active = masquerade, replay, modification, DoS.
- **X.800 services (5):** authentication, access control, data confidentiality, data integrity, non-repudiation.
- **X.800 specific mechanisms (8):** encipherment, digital signature, access control, data integrity, authentication exchange, traffic padding, routing control, notarization.
- **Pervasive mechanisms (5):** trusted functionality, security label, event detection, security audit trail, security recovery.
- **Cryptanalytic attacks:** ciphertext-only, known-plaintext, chosen-plaintext, adaptive chosen-plaintext, chosen-ciphertext, chosen-key, rubber-hose.
- **Substitution types (4):** simple, homophonic, polygram, polyalphabetic.
- **Protocols (3):** arbitrated (Trent every time), adjudicated (only on dispute), self-enforcing (none).
- **Hash properties:** any input → fixed output, easy to compute, pre-image resistant, second pre-image resistant, collision resistant, avalanche.
- **Watermark characteristics:** imperceptibility, robustness, security, capacity, unambiguity, low cost.
- **Watermark types:** visible/invisible; robust/fragile/semi-fragile; image/audio/video/text; spatial/frequency; blind/semi-blind/non-blind.
- **Policy types:** EISP, ISSP, SysSP. **Policy hierarchy:** policy → standards → guidelines, procedures.
- **Sample policy sections:** purpose, scope, policy statements, responsibilities, enforcement, review.
- **ISO 27001:2022:** clauses 4–10; Annex A = 93 controls in 4 themes (organisational 37, people 8, physical 14, technological 34); PDCA.
- **IPR (6):** copyright, patent, trademark, industrial design, GI, trade secret.

## Numbers and sections to remember

| Item | Value |
|---|---|
| MD5 | 128-bit digest, 512-bit blocks, 4 rounds × 16 = 64 steps, 4 registers |
| SHA-1 | 160-bit digest, 80 steps, 5 registers |
| Padding | 1 then 0s to 448 mod 512, then 64-bit length |
| DES / 3DES (2 keys) | 56-bit / 112-bit; C = E<sub>K1</sub>(D<sub>K2</sub>(E<sub>K1</sub>(P))) |
| DSA | FIPS 186 (1991); q = 160-bit prime dividing p − 1 |
| IT Act | In force 17 Oct 2000; amended 2008; based on UNCITRAL Model Law |
| S. 43 / 65 / 66 | Damage (compensation) / source code (3 yrs, 2 lakh) / hacking (3 yrs, 5 lakh) |
| S. 66C / 66D / 66E / 66F | Identity theft / personation / privacy / cyber terrorism (life) |
| S. 67 / 72 / 79 | Obscenity / breach of confidentiality / intermediary safe harbour |
| S. 66A | Struck down, Shreya Singhal (2015) |
| Copyright | Copyright Act 1957; life + 60 years; software = literary work; S. 63, 63B |
| Patent | Patents Act 1970; 20 years; S. 3(k) excludes computer programs per se |
| Trademark | Trade Marks Act 1999; 10 years, renewable |
| DPDP Act | 2023; penalty up to Rs 250 crore |

## Diagrams to practise once

1. Pyramid of information systems (TPS at the base, ESS at the top).
2. SDLC staircase with seven boxes.
3. CIA triangle.
4. Components of information security: three boxes inside a policy box, C.I.A. in the centre.
5. Stallings model for network security (sender, transformation, channel, opponent, trusted third party).
6. Attack tree: passive (2) and active (4).
7. Attack → service → mechanism.
8. Symmetric cipher model: plaintext → encrypt (key) → ciphertext → decrypt (key) → plaintext.
9. Playfair 5×5 square for MONARCHY.
10. Hash structure: pad + length → blocks → compression → digest.
11. Digital signature: hash → sign with private key → verify with public key.
12. Watermark embedding and extraction with a key.
13. Policy → standards → guidelines, procedures.
14. PDCA cycle.

## Worked examples to rehearse

**Playfair (key MONARCHY):** INSTRUMENTS → IN ST RU ME NT SX → **GATLMZCLRQXA**.

```text
M O N A R
C H Y B D
E F G I K
L P Q S T
U V W X Z
```
Rules: same row → right; same column → below; rectangle → own row, other's column.

**Caesar (k = 3):** ATTACKATDAWN → **DWWDFNDWGDZQ**. **Rail fence (depth 3):** ATTACKATDAWN → **ACDTAKTANTAW**. **Vigenère (key LEMON):** ATTACKATDAWN → **LXFOPVEFRNHR**.

**RSA (small):** p = 3, q = 11 → n = 33, φ = 20, e = 3, d = 7. M = 4 → C = 4<sup>3</sup> mod 33 = **31**; 31<sup>7</sup> mod 33 = **4** ✓.

**RSA (Stallings):** p = 17, q = 11 → n = 187, φ = 160, e = 7, d = 23. M = 88 → C = **11**; 11<sup>23</sup> mod 187 = **88** ✓.

**DSA formulas:** y = g<sup>x</sup> mod p; r = (g<sup>k</sup> mod p) mod q; s = k<sup>−1</sup>(H(M) + x·r) mod q; w = s<sup>−1</sup> mod q; u1 = H(M)·w mod q; u2 = r·w mod q; v = (g<sup>u1</sup>·y<sup>u2</sup> mod p) mod q; valid if v = r.

**Diffie–Hellman:** p = 23, g = 5, a = 4, b = 3 → A = 4, B = 10, K = **18**.

## The night-before plan

1. Read this sheet once (40 minutes).
2. Draw diagrams 1, 3, 6 and 11 from memory.
3. Do the Playfair and RSA examples once on paper without looking.
4. Read the 2025-26 paper on [All past papers](#pyqs) and say aloud which page each answer is on.
5. Sleep. A rested brain writes 4–5 pages per question; a tired one writes two.
