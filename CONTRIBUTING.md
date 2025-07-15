# Contributing to AetherMind-Workspace

We welcome contributions aligned with the AetherMind Institutional Protocol.

## ✅ Contribution Steps

1. **Fork this repository** and create a feature branch.
2. Ensure your branch passes:
   - `python -m build_process_engine.lifecycle discover --dry-run`
   - `python -m build_process_engine.lifecycle verify --dry-run`
   - `python -m build_process_engine.lifecycle package --dry-run`
3. Document your changes in the Pull Request with clear rationale.
4. Address all CI/CD feedback before requesting review.

## ✅ Compliance Requirements

- All secrets must be injected via `ctx.params.*`
- No hardcoded paths or credentials.
- All lifecycle outputs must populate `ctx.artifacts`
- Notify @ProfessorCEWard for any architectural decisions.

---

*Built for Institutional Deployment — Ward’s Way Enterprises*
