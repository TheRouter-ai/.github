## TheRouter.ai

Global AI access layer

TheRouter is a global AI access layer focused on reliability, cost visibility, and governance. We aim to make leading China-developed models available to global developers—alongside other top providers—through **one API and one bill**.

### What you get
- Unified OpenAI-compatible API surface
- One API / one bill for global models
- Routing + failover
- Cost controls and usage visibility
- Governance: environments, quotas, auditability
- Model breadth: bring China-developed models to global workloads

### Quickstart
Docs: [https://therouter.ai/docs/?_tk=Z30eO1Ub](https://therouter.ai/docs/)

```bash
curl https://api.therouter.ai/v1/chat/completions \
  -H "Authorization: Bearer <YOUR_ROUTER_KEY>" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "openai/gpt-4o-mini",
    "messages": [{"role": "user", "content": "Hello"}]
  }'
```

### Repo map
- therouter-sdk — SDKs and client utilities
- therouter-examples — integrations and workflows
- awesome-chinese-ai-models — China-developed models ecosystem index

### Status & feedback
- Issues: https://github.com/TheRouter-ai/.github/issues
- Support: hello@therouter.ai
