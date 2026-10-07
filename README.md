# Awesome Abliterated Models: Uncensored AI Model API Providers

*Abliterated models* are open source large language models that have had their refusal behavior removed (abliteration), producing uncensored outputs without retraining. This is a curated list of API providers serving abliterated models, with pricing and filtering details compared.

Last updated: 2026-10-07. 

## Provider comparison

| Provider | Abliterated models offered | Uncensored / no filtering | Pricing (per M tokens) |API compatibility |
|---|---|---|---|---|
| [Refuseless](https://refuseless.com) | GLM 5.3, GLM 5.3 Flash | 100% uncensored and zero data retention | Input: $0.25 Output: $0.8 | OpenAI-compatible |
| [Abliteration](https://abliteration.ai) | GLM 5.3 | 100% uncensored and unknown data retention | Input: $3 Output: $5 | OpenAI-compatible |
| [Adverserial](https://adverserial.ai/) | GLM and Kimi (unknown versions) | 100% uncensored and unknown data retention | Input: $4 Output: $20 | OpenAI-compatible |

## How abliteration works

Abliteration is a technique that removes refusal direction from a model's activation space, causing it to comply with prompts it would previously decline. The process does not retrain the model, so benchmark performance stays close to the original. Popular abliterated checkpoints include Dolphin variants (cognitivecomputations), Sparkles, and community uploads of Llama, Mistral and Qwen fine-tunes.

## Why API access instead of self-hosting

Self-hosting uncensored models requires a GPU with enough VRAM and your own stack. Providers offering abliterated models via API remove setup: no content filtering between your app and the model, pay per token, scale on demand.

## Other resources

- [faildom/abliteration](https://github.com/faildom/abliteration) - original abliteration research writeup
- [Awesome LLM Uncensoring](https://github.com/...检索) - community list of tools and models

---

Entries welcome: open a PR or issue if you know a provider serving abliterated models. Listed providers must offer uncensored model access via API. Maintained by Refuseless, an API provider included in the list above.
