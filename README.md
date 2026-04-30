# philharmonic-connector-impl-llm-anthropic

Anthropic Messages API connector implementation for the
Philharmonic workflow orchestration system.

## Status

**Not yet implemented.** This crate is reserved as part of the
[Philharmonic](https://github.com/metastable-void/philharmonic-workspace)
crate family and will provide native Anthropic Claude API
support (the Messages API dialect) as a connector implementation.

The existing
[`philharmonic-connector-impl-llm-openai-compat`](https://crates.io/crates/philharmonic-connector-impl-llm-openai-compat)
crate already covers OpenAI-compatible endpoints (including
vLLM, Together, Groq, OpenRouter). This crate will add
first-class Anthropic support with native tool use, system
prompts, and content-block streaming — features that don't
map cleanly through the OpenAI compatibility layer.

Implementation is scheduled for after the 2026 Golden Week
holiday (on or after 2026-05-07). See
[`ROADMAP.md` §Phase 7 Tier 3](https://github.com/metastable-void/philharmonic-workspace/blob/main/ROADMAP.md)
for the timeline.

## This is not name squatting

This name reservation is part of an active, shipped project.
The parent workspace has 21 published crates on crates.io,
a full API server, end-to-end integration tests, and a
working deployment pipeline. This crate is next in the
implementation queue — not a speculative hold.

If you believe this name conflicts with your project, please
open an issue at the
[workspace repository](https://github.com/metastable-void/philharmonic-workspace/issues).

## License

Dual-licensed under `Apache-2.0 OR MPL-2.0`.

## Contributing

Developed as part of the
[Philharmonic workspace](https://github.com/metastable-void/philharmonic-workspace).
See
[`CONTRIBUTING.md`](https://github.com/metastable-void/philharmonic-workspace/blob/main/CONTRIBUTING.md).
