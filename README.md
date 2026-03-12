# Induction Head Circuit Analysis in Phi-2

Mechanistic interpretability study of Microsoft's Phi-2 (2.7B) using TransformerLens.

## What this is
Investigating whether induction head circuits exist in Phi-2 and how they compare to GPT-2. Part of the BlueDot Impact Technical AI Safety Project Sprint.

## Key findings so far
- Phi-2 has induction heads ✓
- Dominant head: Layer 3, Head 13 (score: 0.6232)
- Phi-2 forms induction circuits at 9.4% depth vs GPT-2's 41.7%

## Tools
- TransformerLens
- Google Colab (T4 GPU)
- Python

## Status
🔬 Week 1 complete — active research in progress

## Author
Merea Tehillah Mwenda · 2026
