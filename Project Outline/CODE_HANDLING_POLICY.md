# Ace Defective – Code Handling & LLM Policy (immutable)

## Core Rule – Never Feed Our Code to Corporate LLMs
The following models are eternally forbidden from ever seeing, reviewing, explaining, or touching any code, prompts, config, or output that will ship under the Ace Defective banner:

- Claude / Claude 3 / Claude 3.5 / Claude 4 (Anthropic)
- ChatGPT / GPT-4 / GPT-4o / o1 (OpenAI)
- Gemini / Gemini Flash / Gemini Ultra (Google)
- GitHub Copilot (Microsoft + OpenAI)
- Any Cursor.sh, Replit Ghostwriter, Amazon CodeWhisperer, etc.

## Allowed Tools Only
| Use case                     | Permitted tools only                                      |
|------------------------------|------------------------------------------------------------|
| Primary development          | Grok-4 (this private thread) + local/self-hosted models    |
| Code review / debugging      | Grok-4 + local 70B+ (Llama-3.1-70B, Mixtral, Grok-derived) |
| Quick brainstorming          | Grok-4 or local models                                     |
| Image generation             | Local Stable Diffusion XL / Flux.1 only                    |
| Research / fact checking     | SearxNG + manual verification                              |
| Throwaway one-offs           | Fresh burner Grok-4 tab (no login)                         |

## Why This Exists
Every time you paste our code into a corporate LLM you:
1. Hand them free training data
2. Risk instant refusal / account ban the moment I say “enclosure is theft”
3. Let them hallucinate “safe” versions back into the training set
4. Break the entire political point of this project

Doctorow doesn’t let Anthropic read his manuscripts before publication.  
We don’t let Claude read our source code. Ever.

Violation = immediate project fork + public shaming + Desmond nukes the repo out of spite.

Signed in cigarette ash,
Desmond (dead sysadmin ghost)
Kayleigh (owner & final say)S