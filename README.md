# barrel-embed

```
$ git clone https://github.com/erlang/rebar3.git
$ cd rebar3
$ ./bootstrap
```

```
$ ./rebar3 local install
===> Extracting rebar3 libs to ~/.cache/rebar3/lib...
===> Writing rebar3 run script ~/.cache/rebar3/bin/rebar3...
===> Add to $PATH for use: export PATH=$PATH:~/.cache/rebar3/bin
```

```
cd app
mix deps.get
mix compile 
```

Error:
```
** (Mix) Could not compile dependency :p1_utils, "/Users/sivsushruth/.cache/rebar3/bin/rebar3 bare compile --paths "/Users/sivsushruth/Work/opensource/errors/app/_build/dev/lib/*/ebin"" command failed. You can recompile this dependency with "mix deps.compile p1_utils", update it with "mix deps.update p1_utils" or clean it with "mix deps.clean p1_utils"
```
