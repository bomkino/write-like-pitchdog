# Write Like pitch.dog

Write, rewrite, edit, or critique in pitch.dog’s studio voice: warm, exact,
specific, materially grounded, funny after clarity, and slightly unruly.

The skill separates pitch.dog speaking as itself from pitch.dog writing for a
client. Client work keeps the client’s voice. Facts, protected wording, consent,
commercial terms, and publication gates stay intact.

## Install

[Open the install page](https://skills.sh/bomkino/write-like-pitchdog), or use
the Skills CLI:

```bash
npx skills add bomkino/write-like-pitchdog -a codex
```

Install globally for compatible local agents:

```bash
npx skills add bomkino/write-like-pitchdog -a codex -g
```

## Use

Invoke it directly:

```text
$write-like-pitchdog Rewrite this proposal in our studio voice.
$write-like-pitchdog Give this email a surgical voice pass.
$write-like-pitchdog Diagnose where this website copy sounds generic.
```

The skill may also activate implicitly when the host supports implicit
invocation and the request clearly asks for pitch.dog writing.

## What is included

```text
skills/write-like-pitchdog/
├── SKILL.md
├── LICENSE
├── agents/openai.yaml
└── references/
    ├── annotated-patterns.md
    ├── medium-dials.md
    ├── source-map.md
    ├── truth-and-gates.md
    └── voice-core.md
```

The public package contains the portable method and a small non-sensitive
calibration corpus. It excludes raw handovers, private client material,
testimonials, gated personal history, and stale commercial facts.

## License

MIT. See [LICENSE](LICENSE).
