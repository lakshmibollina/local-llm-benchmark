# Local LLM Benchmark

Small language models running fully offline — and the numbers to decide when to use them.

## What this shows

- **Offline doc Q&A** — a private version of document Q&A that never calls an API.
- **Model comparison** — Llama 3 3B, Llama 3 8B, Mistral 7B on the same hardware.

## Measured

| Model | Tokens/sec | Latency | Answer quality | RAM |
| --- | --- | --- | --- | --- |
| Llama 3 3B | — | — | — | — |
| Llama 3 8B | — | — | — | — |
| Mistral 7B | — | — | — | — |

*(Fill in after benchmarking.)*

## Also here

**Offline receipt/invoice extractor** — outputs validated JSON. Tracks valid-JSON rate, field accuracy, and speed per document.

## Run it

```bash
ollama pull llama3.2:3b
ollama pull llama3:8b
ollama pull mistral:7b
pip install -r requirements.txt
```
