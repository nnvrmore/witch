# Witch

Your coding agent runtime.

Witch is an early prototype of an open-source coding-agent runtime for explicit
loops, typed tools, deterministic checks, and inspectable traces.

## Status

Witch is in bootstrap mode. The planned first slice is a local ChatGPT-like loop
with a narrow provider gateway and read-only `read` and `grep` tools.

The intended CLI entrypoint is:

```sh
witch craft
```

That command is not usable until the Rust project and CLI scaffold land.

## Current Scope

The first prototype is focused on:

- a buildable Rust project
- simple CI and local checks
- one provider request path
- a local chat loop
- read-only file inspection tools

Not in scope yet:

- final DSL or public APIs
- write/edit tools
- subagents
- permissions UI
- trace debugger UI
- hosted services
- team features

## License

Witch is licensed under the MIT License.
