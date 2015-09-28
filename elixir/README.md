Elixir
======

Formalizing some notes on elixir.

### Mix
- Start new project with `mix new <project_name>`
  *Will create new directory*
- Compile a project with `mix compile`
- Run test with `mix test`, runs all `test/<filename>_test.exs`
- Run specific test with `mix test test/<filename>_test.exs:<line_number>`
  *Will be given as helper notice on failing test*
- Start a application with `iex -S mix`
  -S flag find an execute script
-

### Functions
function capturing

defining functions can be done in oneline with
- `fn -> HashDict.new end`
Which is equivalent to
- `&HashDict.new/0`
But not
- `&HashDict.new()`

### Pin Operator
The pin operator ^ can be used when there is no interest in rebinding a variable but rather in matching against its value prior to the match:

```elixir
iex> x = 1
1
iex> ^x = 2
** (MatchError) no match of right hand side value: 2
```

### GenServer
Gen servers can handle `calls` and `casts`. A call is synchronous and must respond. A cast is asyncronous and the server won't send a response.

### Processes
Create a dummy pid.

This can be done from a charachter list or by using the erlang `:c`(convenience) module. The first number of a pid must be 0 otherwise creation will fail with the following error.

```
(ArgumentError) argument error
    :erlang.list_to_pid('<1.2.3>')
```

This shows that the convenience module uses `list_to_pid/1`

```elixir
:erlang.list_to_pid('<0.255.0>') == :c.pid(0,255,0)
# => true
```

### Testing
Interesting behaviour for [setup macros](http://elixir-lang.org/getting-started/mix-otp/agent.html)
