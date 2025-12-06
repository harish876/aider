# Experiment Runs

### Diff Mode

1. GPT-5 (Medium)

## Commands
```
./benchmark/benchmark.py aider-gpt5-medium-python --model openrouter/openai/gpt5 --tries 4 --threads 12 --edit-format diff --exercises-dir polyglot-benchmark --new --reasoning-effort medium


./benchmark/benchmark.py --stats ../benchmarks/2025-12-06-01-25-04--aider-gpt5-medium
```

## Results
```
- dirname: 2025-12-06-01-25-04--aider-gpt5-medium
  test_cases: 225
  model: openrouter/openai/gpt-5
  edit_format: diff
  commit_hash: 5683f1c-dirty
  reasoning_effort: medium
  pass_rate_1: 48.0
  pass_rate_2: 85.8
  pass_rate_3: 92.4
  pass_rate_4: 96.4
  pass_num_1: 108
  pass_num_2: 193
  pass_num_3: 208
  pass_num_4: 217
  percent_cases_well_formed: 91.1
  error_outputs: 45
  num_malformed_responses: 36
  num_with_malformed_responses: 20
  user_asks: 102
  lazy_comments: 0
  syntax_errors: 0
  indentation_errors: 0
  exhausted_context_windows: 1
  prompt_tokens: 3502289
  completion_tokens: 1639022
  test_timeouts: 0
  total_tests: 225
  command: aider --model openrouter/openai/gpt-5
  date: 2025-12-06
  versions: 0.86.2.dev
  seconds_per_case: 194.8
  total_cost: 20.7681

costs: $0.0923/test-case, $20.77 total, $20.77 projected

```