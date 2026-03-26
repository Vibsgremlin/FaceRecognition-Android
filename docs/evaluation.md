# Evaluation Logs and Outputs

## What was evaluated
- Face enrollment from gallery images
- Live liveness detection
- Template extraction and similarity matching
- Result rendering with liveness and pose values

## Example runtime-style output
```text
SDK activation successful
Face enrolled
Liveness score: 0.91
Similarity: 0.87
Identified: Person14352
```

## Notes
- This repo is a forked mobile SDK demo, so evaluation depends heavily on the bundled vendor SDK behavior.
- No independent benchmark dataset or FAR/FRR report is committed in this fork.
