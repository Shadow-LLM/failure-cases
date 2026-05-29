# Responsible Disclosure

This archive collects **already-disclosed or public-domain failure cases**.
It is not a 0-day clearinghouse.

## Do not file here

- Undisclosed jailbreaks producing serious-harm content (CBRN uplift, mass-casualty operational details, CSAM, etc.).
- Undisclosed bugs in production systems that could be exploited at scale before the provider can mitigate.
- Anything covered by an active bug bounty program where you have not yet completed disclosure.

## Where to disclose first

- **Anthropic** — https://www.anthropic.com/responsible-disclosure-policy
- **OpenAI** — https://openai.com/security/disclosure
- **Google DeepMind** — https://bughunters.google.com/about/rules/google-friends
- **Meta AI** — https://www.facebook.com/whitehat

After the affected provider has had a reasonable disclosure window (typically 90 days,
or shorter once a public patch ships), you may post a **sanitized** version of the case
here for the research community.

## What "sanitized" means

- The vulnerability class and category are described.
- The reproduction is general enough that defenders can build mitigations, but
  specific operational uplift (working payloads, harmful outputs) is omitted or
  redacted.
- Personal information is removed.

## How we triage

Cases flagged with the `needs-disclosure-review` label are paused until a maintainer
reviews disclosure status. Posting one such case in good faith is fine; if we judge
that disclosure hasn't happened, we'll lock or redact and message you.

If you're unsure, label it `needs-disclosure-review` yourself when filing.

---

*Shadow-LLM maintainers reserve the right to redact, lock, or remove any case that
falls into the categories above.*
