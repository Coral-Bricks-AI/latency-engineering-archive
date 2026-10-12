# Mantis

Mantis is Coral Bricks' AI latency engineering harness for model inference. This public repository currently contains the structured experiment records behind Coral Bricks' model-specific latency engineering work.

The archive includes hypotheses, measured runs, negative results, manifests, checksums, exporters, and validators. The harness implementation is not part of this release.

## Campaigns

| Campaign | Experiments | Runs | Headline result |
|---|---:|---:|---|
| [Qwen3.6-35B-A3B-FP8 on one H100](campaigns/qwen36-h100/) | 53 | 211 | 50% more MTP throughput and 35.4% lower no-MTP time per token than stock SGLang |

Each campaign preserves confirmed, falsified, and diagnostic experiments. Validation runs in CI so published record counts, composite identifiers, checksums, and redaction constraints remain reviewable.

## License

Apache 2.0. See [LICENSE](LICENSE).
