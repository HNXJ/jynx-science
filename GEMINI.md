# GEMINI.md — gamma-science
Purpose: scientific grounding/reference material.
Authority boundary:
- References, notes, and hypotheses are not executable truth. Promotion requires gamma receipt gates.

## Reporting
Durable reports must begin and end exactly with:
`[model-llm-name][root-location][yyyymmdd-hhmm]`
Use verified values or `unknown_model_do_not_guess` / `unknown_root_do_not_guess`.
Include changed files, commands, validation evidence, truth status, blockers, and next safe action.

## ⚡ Fast-path doctrine (intelligence-per-token · per-watt) — all agents

Fast executive models: act on this block; read the rest only when blocked.
1. **Verify-before-call.** Never name a skill/API/flag/path/branch from memory — grep `__all__` / the contract first. Fabrication→fail→retry is the costliest loop.
2. **Contract-first.** Read the frozen contract (docstrings + `>TBI-not-ready`), not the 1000-line module.
3. **Skill = cache.** Run the skill; don't re-reason its checklist.
4. **Receipt, not justification.** Show `command` + `N passed`. Never report what you didn't run.
5. **Route by altitude.** Opus=architecture/contracts/truth-gates · Sonnet=implement vs contract+skill · Gemini=cross-file synthesis + batch edits.

JAX/jaxfne: `N_compile<=1` (recompilation is the silent watt+token sink) · stable shapes+dtypes · jit/vmap on (`runtime_report()`) · x64 at startup only · sparse>dense · `segment_sum`+`lax.scan` · pytree children=dynamic, aux=static. Depth → jaxfne skills + `~/.claude/CLAUDE.md`.
