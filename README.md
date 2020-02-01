# Twitch

API Wrapper for the New Twitch API (Helix)

## Installation

Not available in hex (yet)

```elixir
def deps do
  [
    {:twitch, "~> 0.1.0"}
  ]
end
```

## Environment Variables

The `Twitch.Client` may use environment variables to bootstrap with `new/0` otherwise defaults will be used. See the following environment variables:

```
TWITCH_CLIENT_ID=
TWITCH_CLIENT_SECRET=
TWITCH_ENDPOINT=
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/twitch](https://hexdocs.pm/twitch).
