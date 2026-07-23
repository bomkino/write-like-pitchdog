# Write Like pitch.dog

Write, rewrite, edit, or critique in pitch.dog’s studio voice: warm, exact,
specific, materially grounded, funny after clarity, and slightly unruly.

The skill separates pitch.dog speaking as itself from pitch.dog writing for a
client. Client work keeps the client’s voice. Facts, protected wording, consent,
commercial terms, and publication gates stay intact.

## Install

[Open the install page](https://skills.sh/bomkino/write-like-pitchdog/write-like-pitchdog),
or use the Skills CLI:

```bash
npx skills add https://github.com/bomkino/write-like-pitchdog --skill write-like-pitchdog -a codex -y
```

Install globally for compatible local agents:

```bash
npx skills add https://github.com/bomkino/write-like-pitchdog --skill write-like-pitchdog -g -a codex -y
```

For a ChatGPT workspace, download
[`write-like-pitchdog-v1.0.0.zip`](https://github.com/bomkino/write-like-pitchdog/releases/download/v1.0.0/write-like-pitchdog-v1.0.0.zip),
then go to **Plugins → Skills → Create → Upload from your computer**. A GitHub
link is not a one-click ChatGPT installer. Personal Skills must currently be
added separately on desktop and web/mobile. See
[OpenAI’s Skills guide](https://help.openai.com/en/articles/20001066).

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
