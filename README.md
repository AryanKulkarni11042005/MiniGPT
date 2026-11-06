### MiniGPT


| Item | Value |
| :--- | :--- |
| **Dataset** | TinyStories (HF roneneldan/TinyStories) |
| **Tokenizer** | Byte-level BPE, vocab 4096, retrained from GPT-2’s |
| **Train** | 2,119,719 stories → 485.8M tokens (972 MB) |
| **Val** | 21,990 stories → 4.88M tokens (9.8 MB) |
| **Avg tokens/story** | ~229 |

Target is 10-12M parameter model