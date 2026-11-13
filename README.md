# base-terrain-feature-wheat

The `Wheat` terrain feature: a special resource a square can hold.

For example: Civ2's Wheat, found on Plains.

This package only declares the class: it has no `main` and registers nothing, so installing it changes no game.
A game's rules register it and give it its yields.

```ts
import Wheat from '@civ-clone/base-terrain-feature-wheat/Wheat';
import { instance as availableTerrainFeatureRegistryInstance } from '@civ-clone/core-terrain-feature/AvailableTerrainFeatureRegistry';

availableTerrainFeatureRegistryInstance.register(Wheat);
```

Part of the Civ2 work (civ-clone/web-renderer#1008).
