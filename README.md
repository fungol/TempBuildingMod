# TempBuildingMod
Public repository for files related to the TempBuildingMod for ARK: Survival Evolved

Base Classes:
EngramEntryBase replaces Engram parent BP and defaults level to 0 and
costs to 0
GreenTranslucent_Lit the transparent green texture
NRTranslucent_Lit the transparent red texture
StructureBaseBP replaces in world structure blueprint and sets some
defaults (including overriding the meshes texture to be the
GreenTranslucent_Lit, and the Destroyed Mesh base class)
NRStructureBaseBP same as StructureBaseBP but uses NRTranslucent_Lit
(Red) and the NRDestroyedMeshBase
DestroyedMeshBase colors destroyed meshes green (uses
GreenTranslucent_Lit)
NRDestroyedMeshBase same as DestroyedMeshBase but uses the red texture
PrimalItemStructureBaseBP new parent class for Primal Items.  Sets a
bunch of defaults including folder location.
NRPrimalItemStructureBase same as PrimalItemStructureBaseBP but has the
NR folder location
