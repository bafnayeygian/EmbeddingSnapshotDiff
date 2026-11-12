# EmbeddingSnapshotDiff

Compare embedding snapshots by IDs, dimensions, vector norms, cosine similarity, and missing records to catch indexing regressions.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/EmbeddingSnapshotDiff.git
cd EmbeddingSnapshotDiff
python -m pip install .
```

## Usage

```bash
embedding-snapshot-diff --help
```

## Development

```bash
python -m unittest discover -s tests -v
```
