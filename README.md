Dual Quaternion Skinning Deformer for Unreal Engine 5.1.

How to use:
Enable Deformer Graph plugin.
Download zip file and extract to C:\Program Files\Epic Games\UE_5.1\Engine\Plugins\Animation\DeformerGraph\Content\Deformers.
Assign a deformer to the skeletal mesh (Skeletal Mesh Editor / AssetDetails / Deformer).

Limitations:
Scale not supported! Not compatible with Metahumans, also UnlimitedBoneInfluences must be set to false.
Recomputed normals doesn't work too.

The blended version use vertex colors to blend Linear and Dual Quaternion (0 = DQ  1 = LB).
