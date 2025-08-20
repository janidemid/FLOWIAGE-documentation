# 1.Import your model to UnrealEngine. I recomend importing it's materials as instances of "defaultTreeMaterial" like shown below:
<img width="242" height="473" alt="2" src="https://github.com/user-attachments/assets/20436b84-798f-4850-8d9f-8464297fd362" />
<img width="501" height="300" alt="Снимок экрана 2025-08-20 205349" src="https://github.com/user-attachments/assets/a7686524-51c9-4c29-bfd6-e5c9620c9680" />

# 2.create child blueprint of "BP_TreeBase" 
<img width="297" height="465" alt="Снимок экрана 2025-08-20 194923" src="https://github.com/user-attachments/assets/b80d06ca-41c9-4df5-92e5-545d7c78b2c8" />

# 3.Open blueprint, set mainMesh's mesh to your tree mesh and disable hiden in game in Defaults of your bluprint
<img width="635" height="718" alt="Снимок экрана 2025-08-20 195036" src="https://github.com/user-attachments/assets/7a82a9e3-d009-4c59-be40-35babcccd61d" />

##

<img width="538" height="520" alt="Снимок экрана 2025-08-20 195124" src="https://github.com/user-attachments/assets/d6e244a3-faa1-4cbf-84fd-55487f02a832" />

##

<img width="538" height="460" alt="Снимок экрана 2025-08-20 195213" src="https://github.com/user-attachments/assets/05dc5b50-c67e-4657-9a9d-eff73bcf0aa7" />

##

<img width="608" height="890" alt="Снимок экрана 2025-08-20 195254" src="https://github.com/user-attachments/assets/1c9fc6ff-aa11-440b-ba59-7b853a269977" />

##

<img width="578" height="253" alt="Снимок экрана 2025-08-20 201540" src="https://github.com/user-attachments/assets/6e549376-b7f3-4dff-9702-7ef4bcfba78a" />

# 4.Create a child actor component and set it's class to BP_Deformer
<img width="510" height="425" alt="Снимок экрана 2025-08-20 195318" src="https://github.com/user-attachments/assets/49924b71-aa2b-45e2-8cdb-6fa9e3774463" />

 ##

<img width="510" height="318" alt="Снимок экрана 2025-08-20 195411" src="https://github.com/user-attachments/assets/f9b13b00-c73e-4d6f-8fa5-df33d57d069d" />

# 5.Set it's parameters like this:
<img width="562" height="635" alt="Снимок экрана 2025-08-20 200402" src="https://github.com/user-attachments/assets/de5f6a3c-2ba4-41c8-a0ec-1a51e580f875" />

## set falloff and mass based on your tree's size and physics

# 6.Place this deformer so it covers one bigger branch of your tree
<img width="808" height="440" alt="Снимок экрана 2025-08-20 200035" src="https://github.com/user-attachments/assets/5bcb2d18-6b2a-42e7-abcb-7278d01fe3c9" />

# 7.Clone this deformer till they covers most of your tree's top
<img width="874" height="462" alt="Снимок экрана 2025-08-20 200220" src="https://github.com/user-attachments/assets/e00aa829-49db-4adb-a2f2-d039b79fa6d3" />

# 8.Add automated constraint. by now Simulating should give this:

<img width="1160" height="400" alt="Снимок экрана 2025-08-20 201507" src="https://github.com/user-attachments/assets/af5eeec9-a88e-4553-9331-b53b691c1f33" />

https://github.com/user-attachments/assets/4850d05a-c7ff-4749-a9e0-1ecaf2ae0567


# 9. Set it's variables or add constraints manualy to get RealisticPhysics
<img width="821" height="404" alt="Снимок экрана 2025-08-20 203340" src="https://github.com/user-attachments/assets/486ba312-2e20-4f0a-b782-2f5dbd944e10" />


https://github.com/user-attachments/assets/d12206a7-b744-4eb7-be46-9eda181265af


# 10.Set your materials up by eather filling defaultTreeMaterial's parramteres or inserting collectionDeformation function to your tree's materials like shown below
<img width="1097" height="982" alt="Снимок экрана 2025-08-20 203543" src="https://github.com/user-attachments/assets/e406a41a-3871-4b44-8876-1f57099f9792" />

## OR:

https://github.com/user-attachments/assets/4a53edb4-14fa-41c5-9150-aeac7239cb55



# Enjoy the result!


https://github.com/user-attachments/assets/cd9a4d07-1e43-4c88-bf26-a88bf66c78e2

