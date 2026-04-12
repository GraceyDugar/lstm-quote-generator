# LSTM Quote Generator

Character-level LSTM trained from scratch on philosophical texts 
(Marcus Aurelius, Epictetus, Sun Tzu) to generate aphoristic prose.

## Results
- Final Loss: 1.4124
- Final Perplexity: 4.11
- Trained on 1,034,103 characters

## What I built
- Character level LSTM from scratch in PyTorch
- Custom training loop with perplexity tracking
- Temperature sampling for controlling creativity
- Multi source philosophical corpus pipeline

## Tech Stack
- Python
- PyTorch
- Google Colab (T4 GPU)

## Temperature Sampling
- 0.5 = focused, structured output
- 0.8 = balanced creativity
- 1.2 = wild, experimental output