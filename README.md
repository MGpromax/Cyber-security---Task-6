# Cyber Security Internship — Task 6: Password Strength Evaluation

Objective: Create strong passwords, evaluate their strength with a password checker, and summarize best practices and learnings.

Contents in this repo
- procedure.txt — step-by-step instructions to create and test passwords
- passwords.txt — example passwords across complexity levels with notes
- interview-qa.txt — concise answers to likely interview questions

How this was evaluated
- Tool: Online password strength checker (e.g., https://passwordmeter.com/). Do NOT test real passwords you intend to use.
- Method: Generated multiple passwords with varying length/complexity, noted feedback (uppercase, lowercase, digits, symbols, and length), and summarized best practices.

Results summary (by pattern/type)
- Simple dictionary words (e.g., “password”, “sunshine”): Weak. Flagged for being common and easily guessed/dictionary-cracked.
- Common pattern with a number/symbol (e.g., “Password1”, “P@ssw0rd!”): Medium at best. Predictable structure lowers true strength.
- Random mixed characters (e.g., 16+ chars from A–Z, a–z, 0–9, symbols): Strong–Very Strong. High entropy; resists brute force longer.
- Passphrases (4–6 random words, separators): Strong if words are random, uncommon, and length is sufficient. Easier to remember.

Key takeaways / best practices
- Prefer length: 14–16+ characters for accounts; more for critical ones.
- Use randomness: avoid dictionary words, seasons/years, keyboard patterns, substitutions like 0→o.
- Mix character sets: upper, lower, digits, and symbols — or use 5–7 truly random words.
- Unique per site: never reuse passwords. A breach in one place shouldn’t affect others.
- Use a password manager: generate/store strong unique passwords. Enable MFA wherever possible.
- Don’t test real passwords on web checkers: use examples or locally generated test strings only.

How to reproduce
1) Open passwordmeter.com (or any reputable checker like Bitwarden, 1Password, or NordPass checkers) in a private window.
2) Use the examples from passwords.txt for testing (or generate your own throwaway samples).
3) Record the tool’s score and feedback (length, variety, sequences, dictionary words, repeats).
4) Compare how length and randomness improve reported strength.

Interview prep
- See interview-qa.txt for concise Q&A covering strength factors, attack types, passphrases, MFA, and common mistakes.

Notes & ethics
- Never submit or test real passwords. Examples provided here are for demonstration only — do not reuse them.
- Actual security also depends on the site’s hashing, salting, and rate-limiting. Strong passwords + MFA + unique per site is the winning combo.

