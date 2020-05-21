# Grid Optimization

From a general guideline.

**INPUT**: Set of available weapons, optimization key, constraints.
**OUTPUT**: Optimal grid with respect to optimization key.

## Weapon format.

## Optimization Key

*TODO: Formula like optimization keys instead of the current simple one.*

Right now, passes in a bunch of flags.

- *On-Element*. Applies seraphic modifier.
- *Expected-Crit*. Adds in expected critical damage from weapon grids only. **Notice that since crit triggers are additive damage wise, this means damage is slightly lower when there are other crit sources.**
- *HP-Percentage*. Calculates w.r.t a HP in mind. Used for enmity/stamina.
