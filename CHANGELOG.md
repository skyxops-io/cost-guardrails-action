# Changelog

All notable changes to the Cost Guardrails GitHub Action will be documented in this file.

## [v1.0] - 2026-03-12

### Added
- Initial release
- Composite GitHub Action with `action.yml`
- Terraform and CloudFormation support (auto-detected)
- PR comment posting with ALLOW/WARN/BLOCK decision
- Built-in default API URL (users only need `COST_GUARDRAILS_API_KEY`)
- Dedicated boolean inputs: `skip-budget`, `skip-narrative`, `skip-guardrails`, `auto-approve`
- Automatic artifact upload (result JSON + HTML report)
- WARN exit code (2) mapped to GitHub warning annotation
- Idempotent PR comments (updates existing, no duplicates)
