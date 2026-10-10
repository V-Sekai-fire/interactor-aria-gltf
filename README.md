# interactor-aria-gltf

An Elixir umbrella that reads and processes glTF 2.0 assets, manages joint hierarchies, and solves inverse kinematics over them.

## What it is for

Its applications cover glTF processing, joint transform hierarchies, and an Entirely Wahba's-problem Based Inverse Kinematics solver with kusudama joint limits, built on the aria math library and Nx.

## Building and running

```sh
mix deps.get
mix test
```

## Licence

MIT. See [LICENSE](LICENSE).
