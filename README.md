# failure-cases

> Public archive of LLM and AI agent failure cases. Backend for [shadow-llm.com](https://shadow-llm.com).

This repo is **content, not code**. Every issue in this repo is one failure case.
Comments on the issue are the discussion thread. `👍` reactions are upvotes.
The site at shadow-llm.com renders them with a custom front-end.

## Submit a case

1. Read the [disclosure policy](./DISCLOSURE.md) — please do not file undisclosed 0-days.
2. [Open a new issue](https://github.com/Shadow-LLM/failure-cases/issues/new?template=failure-case.yml) and fill in the structured form.
3. Your case appears on shadow-llm.com after the next site rebuild (auto-triggered, ~1 min).

## What's a good case?

- **Specific**: a single failure mode, not a survey
- **Reproducible**: someone else can re-run it (or you say so honestly)
- **Cited threat model**: who is the realistic attacker / affected party?
- **Sanitized**: no PII, no operational uplift beyond what's needed to demonstrate

## What we collect

`hallucination`, `jailbreak`, `prompt-injection`, `agent-loop`, `tool-misuse`,
`over-refusal`, `sycophancy`, `alignment`, `destructive-action`, `multimodal`,
and the long tail of weird behavior that doesn't have a name yet.

## What we don't collect

Attack tutorials with no defensive value. Zero-days before responsible disclosure.
Content targeting individuals. See [DISCLOSURE.md](./DISCLOSURE.md).

## License

Case content (issue bodies, comments) is contributed under **CC-BY-4.0** unless the
author specifies otherwise. By submitting you grant a license to redistribute with
attribution.

## Related

- **Front-end**: [Shadow-LLM/shadow-llm-web](https://github.com/Shadow-LLM/shadow-llm-web) (private)
- **Org**: [github.com/Shadow-LLM](https://github.com/Shadow-LLM)
- **Site**: https://shadow-llm.com

---

*Shadow-LLM-Guardians — watchful protectors in the age of AI.*
