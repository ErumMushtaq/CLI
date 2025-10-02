# Conditional LoRA Inject (CLI)

**Conditional LoRA Inject (CLI)** is a novel method for behavior steering in large language models (LLMs) using **LoRA-based adapters**, selectively activated based on the model's own **internal activations**.

Rather than using external classifiers or manual rules, CLI leverages **model internals as guardrails** — using internal representations to detect when and where behavior steering should be applied.

---

## Key Features

- 🧠 **Adative Latent Guardrails**: Use the model’s own hidden states, attention patterns, or representation probes to decide when to inject LoRA adapters.
- 🎯 **Targeted Steering**: Apply behavior modulation only when specific internal patterns or concepts are active.
- 🔁 **Non-destructive**: No need to overwrite or fine-tune the full model. All changes are modular and reversible.
- ⚙️ **Plug-and-Play**: Compatible with Hugging Face .

---