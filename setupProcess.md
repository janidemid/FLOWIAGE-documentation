# 1.Import your model to UnrealEngine. Import it's materials as instances of "defaultTreeMaterial" like shown below

# 2.create child blueprint of "BP_TreeBase" 

# 3.Open blueprint, set mainMesh's mesh to your tree mesh and disable hiden in game in Defaults of your bluprint

# 4.Create a child actor component and set it's class to BP_Deformer

# 5.Set it's parameters like this:

## set fallow and mass based on your tree's size and physics

# 6.Place this deformer so it covers one bigger branch of your tree

# 7.Clone this deformer till they covers most of your tree's top

# 8.By now Simulating should give this:

# 9.Add automated constraint and set it's variables or add constraints manualy to get RealisticPhysics

# 10.Set your materials up by eather filling defaultTreeMaterial's parramteres or inserting collectionDeformation function to your tree's materials like shown below
