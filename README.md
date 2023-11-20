## Setup
```
plz debug //foo:foo_test
```

## Expected Behaviour
Delve spins up.
```
Type 'help' for list of commands.
(dlv)
```

## Actual Behaviour
`plz` exits with an error.
```
Building [0/1, 0.0s]:
  CPU use:   0.0%  I/O:   0.0%  Mem use:   0.0%
11:47:27.211 CRITICAL: Attempted to add ///third_party/go/github.com_go-delve_delve//cmd/dlv:dlv as a dependency of itself.
```
