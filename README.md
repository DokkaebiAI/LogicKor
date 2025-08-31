```python
python generator.py --model Qwen/Qwen3-0.6B --gpu_devices 0 --model_len 4096
python evaluator.py -o ./generated/Qwen/Qwen3-0.6B -k sk-somethingsomething -t 30 # OpenAI API Key
python score.py -p ./evaluated/Qwen/Qwen3-0.6B/default.jsonl
```
