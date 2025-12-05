# Forking this repository

This repo is designed as a pattern you can reuse for other products.

To adapt it:

1. Click **Fork** in the GitHub UI and choose your destination.
2. Search/replace references to **Valant Behavioral Health EHR** and `valant` with your product name and identifiers.
3. Update:
   - `facts/` with your canonical product facts.
   - `ai/` with your prompt library.
   - `data/` with your YAML or JSON data.
   - `schemas/` with your JSON-LD.
4. Review all guardrails and legal language with your own team.

Pull requests to this original repo will be closed without merging. Please use your fork as the canonical version for your product.
