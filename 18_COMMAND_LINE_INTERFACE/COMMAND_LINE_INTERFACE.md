# Command Line Interface — RESIDENCECMS

**Upstream:** https://github.com/Coderberg/ResidenceCMS

## Anticloud CLI

```bash
# Install
pip install anticloud-residencecms

# Run offline with PAX inference
anticloud-residencecms --offline --pax-local

# Run with AIOSS logging
anticloud-residencecms --aioss-log ./ledger.jsonl

# Single binary (after build)
./residencecms --config config.yaml
```

## Options

| Flag | Description |
| --- | --- |
| `--offline` | Disable all network calls |
| `--pax-local` | Use local PAX inference at 127.0.0.1:11434 |
| `--aioss-log PATH` | Write AIOSS audit chain to PATH |
| `--encrypt` | Enable AES-256 at rest for output files |
| `--gpu` | Force GPU inference |
| `--cpu` | Force CPU inference |
| `--config PATH` | Load configuration from YAML file |
