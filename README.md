# Documentation & Usability Improvement Work flow For WORM | EIP-7503 
 📑 Documentation & Usability Improvement Report

				

### 1. Current state

- **Instructions are hidden in the Makefile.** New contributors must guess the correct steps and already understand GNU Make and system dependencies.
- **README is too thin.** It only says “install stuff, run make,” with no context, purpose, or examples.
- **No supporting policies.** There is no [`CONTRIBUTING.md`](http://CONTRIBUTING.md) or [`SECURITY.md`](http://SECURITY.md), so collaboration and security handling are unclear.

### 2. What’s the flaw (the real problem)

- **High barrier to entry:** newcomers cannot reliably set up or verify the project.
- **Low trust for a crypto project:** if users cannot understand and reproduce the process, they may assume risk.
- **More mistakes:** unclear steps lead to inconsistent builds and wrong results.
- **No safe path for security issues:** vulnerabilities may be reported in public or not reported at all.

---

### 3. Recommended improvements

### A) [README.md](http://README.md) (make it the entry point)

Include these sections:

- **What this project does (rationale):** what the setup is for and why it exists.
- **Quick start:** clear commands a beginner can copy and run.
- **Prerequisites:** OS support and exact dependencies.
- **Verification:** how to confirm the output is correct.
- **Trusted setup (simple explanation):** what it means and why it matters here.
- **Contributing + security (short links):** point to [`CONTRIBUTING.md`](http://CONTRIBUTING.md) and [`SECURITY.md`](http://SECURITY.md).

### B) [CONTRIBUTING.md](http://CONTRIBUTING.md) (how people should contribute)

Keep it short and clear:

- How to create a branch and open a PR
- Coding and testing expectations
- When to update docs

### C) [SECURITY.md](http://SECURITY.md) (how to report security issues)

Keep it direct:

- Where to report a vulnerability
- What information to include
- What is considered “in scope”

---

### 4. GitHub integration (automatic benefits)

- [`README.md`](http://README.md) becomes the landing page.
- [`CONTRIBUTING.md`](http://CONTRIBUTING.md) shows up when someone opens a pull request.
- [`SECURITY.md`](http://SECURITY.md) shows up in GitHub’s “Report a vulnerability” flow.

---

### 5. Why this matters (crypto = trust)

Clear docs reduce mistakes and increase confidence. A trusted setup process must be understandable and reproducible, not a black box.

✅ **Outcome:** The repo becomes transparent, contributor-friendly, and security-conscious
