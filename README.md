# Prove Before Done

[![Validate skill](https://github.com/khaichonggg/prove-before-done/actions/workflows/validate.yml/badge.svg)](https://github.com/khaichonggg/prove-before-done/actions/workflows/validate.yml)

An evidence-first Agent Skill that verifies implementation, debugging, automation, migration, and delivery work before reporting success.

## Use it for

- mapping completion claims to direct evidence
- running the smallest meaningful verification for each claim
- distinguishing implemented, tested, published, and working states
- reporting proven, partial, unproven, or blocked outcomes honestly

## Install

Clone or copy this repository into a supported skill directory:

```text
<project>/.agents/skills/prove-before-done/
```

For GitHub Copilot project skills:

```text
<project>/.github/skills/prove-before-done/
```

## Example prompt

```text
Use $prove-before-done to verify this fix before calling it complete.
```

## Validate

```bash
python tests/validate_skill.py
python -m unittest discover -s tests -v
```

## License

Licensed under the [PolyForm Noncommercial License 1.0.0](LICENSE), for noncommercial use only.
