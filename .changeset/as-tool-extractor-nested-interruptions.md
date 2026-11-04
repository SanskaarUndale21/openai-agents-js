---
'@openai/agents-core': patch
---

fix: keep nested approvals from `Agent.asTool()` when a `customOutputExtractor` is set by skipping the extractor until the nested run completes (#2099).
