<div align="center">

# Zynthetix

**Building AI from first principles.**

Language models and developer tools, engineered from the ground up.

</div>

---

## AL-1 — from-scratch language models

Our core research effort. Small language models built **atom by atom** — custom autograd, tokenizer, attention, training loop, and inference stack — to understand every layer of a modern LLM from the ground up, not glue frameworks together.

- **Modern-tiny architecture** — RoPE, RMSNorm, Grouped-Query Attention with QK-Norm, SwiGLU, weight-tied head, byte-level BPE.
- **Pure NumPy core** — hand-written reverse-mode autograd, optional CuPy GPU swap. No PyTorch, no JAX in the from-scratch line.
- **Verified, not vibed** — every op gradchecked, every stage gated (overfit, KV-cache logit-equivalence, checkpoint resume) before moving on.

**Model A** — a 3.87M-parameter from-scratch chat companion (pretrain → masked SFT → sampling → KV-cache → chat runtime), public on Hugging Face:

<div align="center">

[**huggingface.co/karthik-2905/model-a-scratch**](https://huggingface.co/karthik-2905/model-a-scratch)

</div>

---

## Developer tools

Alongside the research line, Zynthetix builds AI-assisted developer tooling — autonomous engineering agents, native macOS apps, and workflow cockpits — for engineers who want results, not complexity.

Most tooling is in private development. More detail as projects reach public release.

---

<div align="center">

[zynthetix.in](https://zynthetix.in) · Currently in active development

</div>
