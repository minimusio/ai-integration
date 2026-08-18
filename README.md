# Minimus AI Integration

Plugins that teach AI coding tools — **Claude Code**, **OpenAI Codex**, and **Cursor** —
to build and migrate Dockerfiles and Kubernetes manifests using hardened
[Minimus](https://www.minimus.io) images by default.

The plugin bundles two skills:

- `minimus-dockerfile` — harden and migrate Dockerfiles onto Minimus distroless images.
- `minimus-k8s` — write and migrate Kubernetes manifests onto Minimus images.

## Install

**Claude Code**

```
/plugin marketplace add minimusio/ai-integration
/plugin install minimus@minimusio
```

**OpenAI Codex**

Run `/plugins`, choose **Add Marketplace** → `minimusio/ai-integration`, then install the `minimus` plugin.

**Cursor**

Run `npx skills add minimusio/ai-integration -g -a cursor -s minimus-dockerfile -s minimus-k8s -y`.
