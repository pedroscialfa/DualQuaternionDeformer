Dual Quaternion Skinning Deformer for Unreal Engine 5.3.

How to use:
Enable Deformer Graph plugin.
Download zip file and extract to C:\Program Files\Epic Games\UE_5.3\Engine\Plugins\Animation\DeformerGraph\Content\Deformers.
Assign a deformer to the skeletal mesh (Skeletal Mesh Editor / AssetDetails / Deformer).
If the deformer doesn't work try to recompile it.

Limitations:
Scale not supported! Not compatible with Metahumans, also UnlimitedBoneInfluences must be set to false.
Recomputed normals doesn't work too.

The blended version use vertex colors to blend Linear and Dual Quaternion (0 = DQ  1 = LB).
