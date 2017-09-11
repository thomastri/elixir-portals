# Portal
A small Elixir project that allows users to push data from one "portal" to another.
Portals can be on different computers (same network) and the objects will still interact.

Practiced with the following concepts
1. Atom IDE
2. Mix
3. Stacks in Elixir
4. Supervisors (continue the program after one node is shut down;
creates a clone of expected portal in our example)
5. Distributed transfers: open a "portal" on one terminal and modify /
access it from another terminal

Followed along with Jose Valim's tutorial:
http://howistart.org/posts/elixir/1/

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `portal` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:portal, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/portal](https://hexdocs.pm/portal).
