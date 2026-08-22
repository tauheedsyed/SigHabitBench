# SigHabitBench

Do large language models know how proteins regulate each other, or just what
each protein *usually* does?

**Status:** in development

## The question

Most proteins have a dominant behaviour — some mostly activate their partners,
some mostly inhibit. This benchmark asks whether LLMs recall specific
interactions, or fall back on the protein's general reputation.

The test: interactions where a protein does the *opposite* of its usual
behaviour, matched against interactions where it does the usual thing.

## Layout

- data/processed/ — benchmark items
- 
otebooks/ — analysis, numbered in run order
- src/ — shared code
- 
esults/ — raw model responses
- igures/ — figures

## Setup

1. \pip install -r requirements.txt\
2. Copy \.env.example\ to \.env\ and add your API keys
3. Run notebooks in numerical order

## Data

Built on [OmniPath](https://omnipathdb.org/). Snapshot checksums in
\data/raw/snapshot_manifest.json\.

## Licence

MIT (code) / CC-BY-4.0 (data)
