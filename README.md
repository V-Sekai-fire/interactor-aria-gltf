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

MIT, as the SPDX headers and the Mix package metadata declare. There is no LICENSE file, and the vendored solver reference inside the inverse-kinematics application keeps its own licence.
