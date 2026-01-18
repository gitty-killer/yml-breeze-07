# yml-breeze-07

A small Python tool that computes text statistics for breeze.

## Objective
- Provide quick text metrics for breeze documents.
- Report top word frequencies for fast inspection.

## Use cases
- Validate breeze drafts for repeated terms before review.
- Summarize breeze notes when preparing reports.

## Usage
python textstats.py data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Testing
- run `bash scripts/verify.sh`

## Notes
- Only ASCII letters and digits are treated as word characters.
