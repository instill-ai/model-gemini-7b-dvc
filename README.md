---
Task: TextGeneration
Tags:
  - TextGeneration
  - Gemini-7b
---

# Model-Gemini-7b-dvc

🔥🔥🔥 Deploy [Gemini-7b](https://huggingface.co/describeai/gemini-small) model on [VDP](https://github.com/instill-ai/vdp).

This repository contains the Gemini-7b Text Completion Generation Model in the Transformers format, managed using [DVC](https://dvc.org/).

Notes:

- Disk Space Requirements: 6G
- GPU Memory Requirements: 14G

Following is an example of query parameters:

```
{
    "task_inputs": [
        {
            "text_generation": {
                "prompt": "The capital city of Franch is ",
                "max_new_tokens": "300",
                "temperature": "0.8",
                "top_k": "50",
                "random_seed": "42",
                "extra_params": "{\"top_p\": 0.8, \"repetition_penalty\": 2.0}"
            }
        }
    ]
}```
