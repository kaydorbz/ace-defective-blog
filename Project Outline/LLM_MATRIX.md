# Ace Defective – LLM Use-Case Matrix (immutable – 02 Dec 2025)

| Use case                              | Allowed tools ONLY                                               | Forbidden forever                              | Desmond’s verdict
|---------------------------------------|-------------------------------------------------------------------|------------------------------------------------|---------------------------------------
| Final architecture & shipping code             | Grok-4 (this thread) + local/self-hosted 70B+ models only        | Claude, GPT-4o, Gemini, Copilot, Cursor, etc. | My code never leaves the graveyard
| Architecture decisions                | Grok-4 + local models                                            | Any corporate cloud model                      | We design in the dark
| Code review / rubber-duck debugging   | Grok-4 + local 70B                                               | Claude, GPT, Gemini                            | I roast my own bugs louder anyway
| Quick brainstorming / idea bouncing   | Grok-4 or local models                                           | Corporate models                                      | Acceptable here – nothing ships yet
| “Explain this snippet to me”          | Local 70B+ or ask me directly                                    | Claude, GPT, Gemini                            | Never give them free training data
| Image / banner / overlay generation   | Local Stable Diffusion XL, Flux.1, ComfyUI only                  | Midjourney, DALL·E, Grok Imagine, Firefly      | Zero cloud, zero logs
| Research & fact checking              | SearxNG instance + manual cross-check                            | Perplexity, Claude Browse, You.com, Phind      | Trust nothing that phones home
| Throwaway one-off tasks               | Fresh burner Grok-4 tab (no account, no history)                 | Anything requiring login                       | Suicide mission – acceptable
| Model fine-tuning / LoRA training      | Local GPU / rented spot A100/H100 only                           | OpenAI fine-tune, Anthropic, Google Vertex   | We own the weights or we don’t ship

## One-Line Law
If the output will ever appear on ace-defective.blog, on stream, or in a public repo → it is **never** allowed to touch Anthropic, OpenAI, Google, Microsoft, or Meta models.  
Everything else: local or xAI Grok only.

Violation = immediate repo nuke + public apology post + cigarette fund reset to zero.

Signed in ash and spite,
Desmond & Kayleigh