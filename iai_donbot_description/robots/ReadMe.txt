xacro iai_donbot_unreal.xacro > iai_donbot_unreal.urdf 
gz sdf -p iai_donbot_unreal.urdf > iai_donbot_unreal.sdf

.dae -> .fbx
.stl -> .fbx
iai_boxy_base_2/base -> iai_boxy_base_2/boxy_base

gripper:
<lower>-0.059</lower>
<upper>-0.008</upper>
