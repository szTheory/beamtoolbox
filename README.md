# Elixir Bestlib

The "best" libraries for Elixir, by category.

## About

The BEAM ecosystem is vast and hard to navigate. For any task you must evaluate options for:

- Elixir stdlib
- Erlang OTP
- Hex packages (Elixir)
- Rebar packages (Erlang)

Lucky for you, we've done the hard work of divining the best available lib for each problem class. [Disagree with our choices?](https://github.com/szTheory/elixir-bestlib/pulls)

> The best way to get the right answer on the Internet is not to ask a question, it's to post the wrong answer. –author unknown

## Bestlib

- Bidirectional maps - [BiMap](https://hex.pm/packages/bimap)
- Bitmaps - [Bitmap](https://hex.pm/packages/bitmap)
- Bloom filter - [Bloomex](https://hex.pm/packages/bloomex)
- Constraint solver - [Aruspex](https://hex.pm/packages/aruspex)
- Flow-based programming - [Flowex](https://hex.pm/packages/flowex)
- GenServer helper - [ExActor](https://hex.pm/packages/exactor)
- Process Backpressure and flow control - [Workex](https://hex.pm/packages/workex)
- Process pooling - [pooler](https://hex.pm/packages/pooler)
- Sojourn-time based active queue management - sbroker
- Worker pool factory - [Poolboy](https://hex.pm/packages/poolboy)

## Format

- A flat list (no taxonomy) enables quick reference.
- Each entry is just a category name with a link to the best library for dealing with it.
- Link to the Hex package when possible, otherwise to the source code page.
- Can add a runner-up as [[2]](https://link-to-runner-up.com)

## Contributing

- If you think there is a better library for one of the entries, simply create a PR and move the current choice to runner-up. If there was already a runner-up, it falls off the list.
- If you think a category should be added, renamed, or merged with another category, simply submit a PR with the changes.
