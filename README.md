The QuiverMutation.ipynb notebook is to simplify calcualtions with quiver mutations. This has more details about what quiver mutation is for people not familiar with these things.

It has functions to:

* Apply a single mutation.
* Apply a sequence of mutations.
* Obtain equivalent quivers to a given quiver, up to a given distance away.
* Check if two given quivers are equivalent, up to relabelling, and up to a given distance (they may still be equivalent, but only if we use more mutations).
* Check if a quiver is periodic.


The MutationAndTYSystems.ipynb notebook is for (ultimately) generating T- and Y-systems from periodic quivers. It also allows us to identify these. We can:

* Apply mutations and sequences of mutations to quivers
* Given two quivers, search for mutation sequences that can be applied to the first to give the second (allowing for possible relabelling of these quivers)
* Search for mutation sequences that fix a quiver (up to permutation), proving periodicity
* Given a mutation sequence that fixes a quiver (not up to permutation), generate T- and Y-systems
* Given a mutate sequence that fixes a quiver (up to permutation), generate reduced T- and Y-systems
