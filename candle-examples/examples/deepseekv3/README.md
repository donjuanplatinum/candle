# DeepSeek V3

An example for running the DeepSeek V3 family with Candle.

## Running the example

```bash
cargo run --example deepseekv3 --release --features metal -- \
  --prompt "Recursive fibonacci code in Rust:" \
  --which v3 \
  --sample-len 150
```

Override the model id if needed:

```bash
cargo run --example deepseekv3 --release -- \
  --prompt "你好，给我讲一个关于Rust的笑话。" \
  --model-id deepseek-ai/DeepSeek-V3-Chat \
  --sample-len 128
```
