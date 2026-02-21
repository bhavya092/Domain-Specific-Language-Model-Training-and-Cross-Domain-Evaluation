# Domain-Specific-Language-Model-Training-and-Cross-Domain-Evaluation

Code base for the following:

Ran controlled ablation studies on GPT-style decoder-only LMs (NanoGPT), evaluating zero-/few-shot across 20+
prompts & 10+ checkpoints; observed 30–50% coherence degradation under cross-domain prompting, exposing limits.
Analyzed model confidence and interpretability via softmax entropy & Grad-CAM, identifying 2–3× probability mass
concentration on domain-specific tokens and token-importance shifts, highlighting overconfidence and calibration failures.
