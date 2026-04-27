# VR-AR-MR
# Virtual, Augmented, & Mixed Reality — Course Portfolio

## Name  
Elshaddai Melaku  

## Course  
Virtual, Augmented, & Mixed Reality  

## Term  
Spring 2026  

## Instructor  
Dr. Jillian Aurisano 


## About Me
I am a dedicated Computer Science major and MBA candidate with a passion for community building and data science. I am interested in leveraging tech and AI to drive positive change, especially related to creating ethical, accessible, and inclusive solutions. I am excited to continue learning and make a meaningful impact in the tech industry and beyond.


---

## About This Portfolio

This page serves as a living portfolio documenting my projects, assignments, and learning progress throughout the *Virtual, Augmented, & Mixed Reality* course.

The goal of this portfolio is to:
- Showcase project development and final outcomes  
- Document design decisions, experimentation, and iteration  
- Reflect on technical, creative, and conceptual learning  
- Provide a centralized place to share course work publicly  

---

## Tools & Platforms Used

This portfolio may include work created using:
- Unity  
- XR Interaction Toolkit  
- AR / VR headsets or simulators  
- 3D assets, images, and screen recordings  
- External video hosting (YouTube or Vimeo), when applicable  

---

## Project & Assignment Index

# AR Project 1: Napa Valley AR Knick-Knack

## Description
This project is an **Augmented Reality knick-knack** built using Unity and Vuforia. The application displays a small 3D vineyard-themed scene on top of a tracked merge cube when viewed through a webcam.

The project represents **Napa Valley, California**, which I visited last summer for my sister’s bachelorette trip. When the cube is detected, the AR scene appears on top of it. Each face of the cube also displays useful information such as the location name, the current weather, the local time, and a personal memory caption.

---

## Repository
**GitHub Repository:**  
[VR-Project-1](https://github.com/melakueb/VR-Project-1)

## Demo Video
[Demo on Kaltura](https://uc.mediaspace.kaltura.com/media/1_fvrndbp5)

---

## Artifacts

### Scene Overview
![Scene](https://github.com/melakueb/VR-Project-1/blob/main/images/scene.png)
This screenshot shows the AR knick-knack scene appearing on top of the merge cube when detected by the webcam. Each side of the cube displays readable information using world-space UI text panels.

Cube faces include:

- **Location Name**
- **Current Weather**
- **Local Time**
- **Memory Caption**

### 3D Models Used

#### Models from External Sources

| Model | Source |
|------|------|
| Green Bush | [Link for Bush](https://www.fab.com/listings/581e1057-ee3e-4c64-bf85-4ea5a3194a0c)|
![Bush](https://github.com/melakueb/VR-Project-1/blob/main/images/bush.png)
| PSX Old House | [Link for House](https://www.fab.com/listings/88a25b2a-9dc1-4e5d-8aca-746e1fff91fb)|
![House](https://github.com/melakueb/VR-Project-1/blob/main/images/house.png)
| Wine Barrel | [Link for Barrel](https://www.fab.com/listings/e629a77a-566b-4ddb-96e0-9a314e3ea5f6)|
![Barrel](https://github.com/melakueb/VR-Project-1/blob/main/images/barrel.png)

#### Models Created by Me

| Model | Creation Method |
|------|------|
| Grapes | Generated using Meshy AI and modified in Blender |
![Grapes](https://github.com/melakueb/VR-Project-1/blob/main/images/grapes.png)
| Wine Glass | Created in Blender following a tutorial |
![Scene](https://github.com/melakueb/VR-Project-1/blob/main/images/wine.png)

Wine glass tutorial used:  
[How to create a wine glass in 1 Minute in Blender Tutorial](https://www.youtube.com/watch?v=4edZZAm-qdQ&msockid=484f7d551e8411f1b36e82125a28847f)

### Ambient Sound

The AR scene includes background ambience to create a relaxing countryside atmosphere.

**Audio Source:**  
[Countryside ambience – Chosic MP3](https://www.chosic.com/download-audio/54552/)

---

## Motivation
The inspiration for this AR knick-knack was **Napa Valley, California**, which I visited last summer during my sister’s bachelorette trip. The vineyards and countryside scenery made it a memorable place.

The goal of the project was to recreate a small representation of that memory using augmented reality. Similar to a physical souvenir, the AR knick-knack represents a personal experience that could be placed on a desk or shelf in a virtual environment.

---

## Design
The knick-knack design represents a small **vineyard scene** placed on top of the merge cube.

The scene includes:

- A small house
- A bush representing vineyard vegetation
- A wine barrel
- Grapes
- A wine glass

These objects were chosen because they are commonly associated with vineyards and wine culture in Napa Valley.

Three models were sourced from online asset libraries, while two were created manually. The grapes were generated using **Meshy AI** and then edited in Blender. The wine glass was modeled in Blender by following a short tutorial.

The cube itself also includes **four informational faces**, implemented using world-space UI panels:

- **Location Name:** Napa Valley, California  
- **Weather:** Current temperature retrieved from a weather API  
- **Local Time:** Time in Napa Valley’s time zone  
- **Memory Caption:** A reminder of the trip  

The UI panels were designed with readability in mind by using:

- centered text
- bold fonts
- high contrast colors
- a background panel behind the text

---

## Process
This project was built using several tools and technologies:

- **Unity**
- **Vuforia Engine**
- **C# scripting**
- **Blender**
- **Meshy AI**

The merge cube images were used as a **multi-target tracker** through Vuforia so that the cube can be recognized from multiple angles.

The scene hierarchy was structured so that all AR objects are children of the cube tracker:

Two main scripts were written in C#:

### Weather Script
Retrieves the current temperature using the **Open-Meteo weather API** and updates the weather display periodically.

### Time Script
Displays the local time for Napa Valley using Pacific Time.

The cube face panels were implemented using **TextMeshPro world-space UI**, which allows readable text in AR environments.

---

## Challenges and Future Work

One of the main challenges was learning to work with **Blender**, since I had limited experience with 3D modeling. Creating the wine glass and grapes required following a tutorial and experimenting with modeling tools.

Another challenge was integrating **API data into Unity**, especially retrieving and updating weather data for display on the cube.

If I continued developing this project, I would expand the vineyard scene to make it more realistic. Currently, the environment contains only a few objects, but future improvements could include:

- adding rows of vines instead of a single bush
- creating more detailed vineyard scenery
- adding animated environmental elements
---

## Use of AI and Collaboration

AI tools were used in several parts of the project.

**Cursor IDE** was used while writing C# scripts for features such as weather retrieval and time display.

**Meshy AI** was used to help generate the grape model, which was then modified in Blender.
AI assistance was also used to troubleshoot Unity setup issues and help understand how to integrate APIs with AR elements.

Classmates were also helpful in discussing debugging approaches with the MergeCubes.

---

# VR Partner Presentation: VR Surgical Simulation Suite (VR3S)
[Partner Portfolio Link](https://sites.google.com/view/fareenak-portfolio/project-page)
Fareena Khan & Elshaddai Melaku

_What is the purpose of this VR/AR/MR application?_
We chose Cincinnati Children’s Hospital’s Virtual Reality Surgical Simulation (VR3S). It is a real world use of VR with real impact. Instead of using VR for gaming or entertainment, this system is being used to help surgeons plan surgeries for babies born with congenital heart defects. It combines medicine, 3D modeling, multiplayer VR, and global collaboration into one system. It basically creates a digital twin of a patient’s heart, and surgeons can step inside it in VR before the real surgery even happens. The project even won Unity’s 2024 Unity for Humanity Grant.
Who are the users that this VR/AR/MR application was made for?  Experts, general public, children, patients, mechanics, athletes+trainers...?  
While surgeons are the main users it can also help patients, parents, trainees, global medical teams, and medical students.
Features/Tasks: What can people do using the VR/AR/MR application?  Show some examples with images and/or videos? 
Using VR3S, surgeons can take CT or MRI scans and turn them into a 3D digital twin of the patient’s heart, which they can then explore in virtual reality. Instead of only looking at flat 2D scan slices, they are able to rotate the heart, zoom in on different structures, and even step inside the anatomy in VR to better understand the exact shape of the defect.
One of the most advanced features is the ability to place virtual valves, baffles, and other medical devices directly into the heart model so surgeons can test different surgical approaches before the real procedure. The system also supports multiuser collaboration, which means surgeons in different countries can join the same virtual space and work together on a case in real time. On top of that, the platform includes real-time multilingual translation, which makes global collaboration much easier and supports the project’s larger goal of improving heart surgery outcomes worldwide.

_Comment on the design and implementation choices_
The design and implementation choices for this project strongly support its goal of improving surgical planning and collaboration. Using Unity is an effective choice because it supports real-time 3D rendering, multiplayer networking, and immersive interaction, all of which are essential for a VR-based medical application. Important actions such as launching a VR session, sharing a case, editing sessions, and uploading models are clearly labeled and easy to locate. The case creation screen is especially strong from a UX standpoint because it organizes the workflow into clear sections, such as preview, 3D model files, and save actions, making the process intuitive for users navigating complex medical data. These design choices are effective because surgeons need an interface that is fast to learn and easy to use in high-stakes environments. The real-time rendering of patient anatomy, combined with a structured and user-friendly interface, allows medical teams to review cases and plan surgeries efficiently.
Technology- what device is used for this application to achieve VR/AR/MR experiences?  Is this a good choice and are there any downsides?
The project uses a Unity based VR environment to create an immersive experience accessed through VR headset. They leverage cross-sectional imaging by inputting data from CT or MRI scans to create 3D renders from them. This allows for surgeons to experience patient anatomy in a 3D space, which can help improve their ability to understand how to move forward more efficiently. In addition, the platform supports multiplayer networking and Azure service integration, which enables real-time collaboration between medical teams across different locations and supports secure cloud-based data management. The main downsides to using tech like this is the cost to access VR hardware, install compatible software, train personnel, and ensure patient data security. These barriers make the tech less accessible to smaller hospitals and hospitals with less resources, which conflicts with one of the goals of the project being trying to make the system available globally. 
Visual experience- how are visuals presented to the user?  is realism a goal?  Does this application achieve its goals? 
Realism is definitely a major goal to a project like this, as it must prioritize medical accuracy and spatial precision. The digital 3D render must reflect the exact patient anatomy since the goal is to leverage the render to plan surgical procedures for the patient. One Project Lead shared that the platform successfully achieved this, and that surgeons are able to explore the heart of a patient at every angle and interact with it real time.

_Interaction- how can users interact with the content?  Are these interactions effective?_
Users use VR headsets to view and controllers to navigate, and they can collaborate with others. They can manipulate the 3D heart model by rotating, moving it around, zooming, viewing internal structures, and placing surgical plans onto the anatomy. These actions are effective in achieving the goal of viewing patient anatomy and planning surgery ahead of time. The collaborative component is also very effective in that it allows experts from different hospitals and locations to work together on the same patient case. 

_What are the limitations of this design- what can't someone do with this VR/AR/MR application?  What are its limitations?  What should the developers of this tool do next?_ 
Right now, VR3S is only really useful in hospitals that already have access to high-quality CT or MRI imaging, since the entire experience depends on creating an accurate 3D digital twin of the patient’s heart. It also depends on hospitals having VR headsets, reliable internet for global collaboration, and staff who are trained to use the system effectively. Another limitation is that the platform is still focused mostly on congenital heart surgery, so its use cases are narrower than other medical simulation tools.
We think the next best step for the developers would be to make lower-cost versions so hospitals around the world can access the same technology. It would also be helpful to show and improve real-time blood flow and tissue simulation, since that would make the planning even more realistic. It would also be really useful to expand the system into other types of surgeries, improve haptic feedback, and create easier training modes for medical students and residents.

_Links:_
[Cincinnati Children’s Virtual Reality Project Wins Humanity Grant from Software Development Platform Giant](https://www.cincinnatichildrens.org/news/release/2024/unity-grant)
[VR3S Overview](https://www.youtube.com/watch?v=ItE_NS9wFx8)
[VR Surgical Simulation Suite (VR3S) | Andy DiLallo](https://www.andydilallo.com/vr3s/)

---
# VR Project 2: Langsam 418 ++
## Description
The goal of the Langsam 418 space is to support collaborative work and interactive teaching.  The large display and collaborative software is part of this vision.  VR is an excellent tool for envisioning an interactive space.   Your job is to augment this room with additional appropriate models, sounds, lights, interactives, that will help me (and others) envision new ways to use this space for meetings/teaching and to interact with information.  

## Repository
**GitHub Repository:** 
[Langsam418 Group Repo](https://github.com/kellannd/langsam418-vr)
Developed by: Kelly Deal, Elshaddai Melaku, Ikran Warsame, Fareena Khan

## Design
**Room Overview:**
We revamped our classroom into a stress free learning space with warm colors, comfy seating, and fun gaming elements. It's designed to feel welcoming and flexible which is perfect for studying solo or hanging out with others.

**Visual Elements:**
The room has comfortable bean bags and chairs, arcade games, a turntable with vinyl record playing 70's music, plants, and everyday objects like coffee cups and laptops. The soft, warm lighting keeps the vibe relaxed, calm, and inviting.

**How We Built It:**
We grabbed assets from Meshy.AI for the fun and more unique stuff (pinball, bean bags), CGTrader for props and furniture, and AvatarSDK for custom avatars. This let us fill the space with quality assets that all looked cohesive.

## Accomplishments by Level
**Level 1:** Furnished the room with comfortable seating (couches & bean bags), warm lighting, and ambient sounds (pinball, music playing from the turntable).

<img src="media/table-chairs.png" alt="Tables and chairs" width="372" /> <img src="media/turntable-and-beanbags.png" alt="Turntable and bean bags" width="300" />

**Level 2:** Added interactive objects (coffee cups, laptops, notebooks, pencils, plants) with physics and collision detection.

<img src="media/interactable-items.png" alt="Interactable items" width="300" />

**Level 3:** Added four custom avatars of ourselves with idle animations (characters dancing) and interactions (they wave as you walk up to them). The large display has a static image but it also has a moving screensaver as you walk up to it.

<img src="media/avatars-dancing.png" alt="Avatars dancing" width="300" />

**Level 3 Bonus:** Created custom avatar characters that look like us using AvatarSDK.com.
| Fareena | Elshaddai | Ikran | Kelly |
|----------|----------|----------|----------|
| <img width="251" height="331" alt="image" src="https://github.com/user-attachments/assets/b6b267e0-e638-409e-ab42-94b05366d0ea" />| <img width="250" height="310" alt="image" src="https://github.com/user-attachments/assets/1e4ec728-9dea-4ec4-926e-ad1ef0732f9f" /> | <img width="245" height="263" alt="image" src="https://github.com/user-attachments/assets/c9650498-ad81-4e1d-8173-c41934e1ac06" />| <img width="205" height="314" alt="image" src="https://github.com/user-attachments/assets/b2fc3805-a3ce-4a29-86d5-4e1631025a23" />|

**Level 4:** Approaching the pinball machine plays sound, the laptop opens as you near it, the turntable's music grows louder or softer with your distance, and walking up to the avatars makes them stop dancing and wave.

<img src="media/pinball-machine.png" alt="Pinball machine" width="300" />

**Level 5:** Added a spinning disco ball with fun lighting effects.

<img src="media/disco-ball.png" alt="Disco ball" width="300" />

**Credits**
- **[Meshy.AI](https://www.meshy.ai):** Orange bean bag, turntable
- **[CGTrader](https://www.cgtrader.com):** [pencil](https://www.cgtrader.com/free-3d-models/various/various-models/3d-red-pencil-realistic-model), [notebook](https://www.cgtrader.com/free-3d-models/interior/office-interior/notebook-abf827d7-3bbe-435d-a130-a24fb41229dc), [coffee cup](https://www.cgtrader.com/free-3d-models/food/beverage/coffee-cup-ee824c70-b899-425c-b1a7-703e8fe3559b), [tables](https://www.cgtrader.com/free-3d-models/furniture/table/and-tradition-in-between-sk6-table)
- **[Poly Haven](https://polyhaven.com):** [cactus](https://polyhaven.com/a/potted_plant_04), [potted plant](https://polyhaven.com/a/potted_plant_02)
- **[Sketchfab](https://polyhaven.com):** [pinball machine](https://sketchfab.com/3d-models/pinball-machine-cc2a49ca2ad14910abce89b5a78bb09f), [chairs](https://sketchfab.com/3d-models/vintage-office-chair-09259d92dd1c489698199cde905fe837)
- **[Unity Asset Store](https://assetstore.unity.com/):** [side table](https://assetstore.unity.com/packages/3d/props/furniture/free-minimalist-table-189610), [font](https://assetstore.unity.com/packages/2d/fonts/bubble-font-free-version-24987)
- **[AvatarSDK.com](https://avatarsdk.com):** Custom characters
- **[Mixamo.com](https://www.mixamo.com/#/):** Character Animations

**Sounds:**
- **Pinball:** https://youtu.be/gdjx1Dbxpro?si=X661oeg6W-eNQMAY
- **Dancing Queen:** https://youtu.be/h3KJD9G80dc?si=JisPuD0CwySlWxZ6

## Process
- Clone & open in Unity 6.3 LTS (6000.3.1f1)
- Load `SampleScene.unity` and press Play
- Main scripts: `Music.cs`, `Pinball.cs`, `Wave.cs`, `laptop.cs`, `hinge.cs`, `Rotate.cs`, `ShowText.cs`
- Tech: Unity, C#, [Mixamo](https://www.mixamo.com), [Meta Quest 3](https://www.meta.com/quest/quest-3)

The project is a Unity 6.3 LTS scene built for the Meta Quest 3, using OpenXR and the Meta XR SDK for headset and controller input. The entire experience lives in a single scene (`SampleScene.unity`) with all interactions driven by small, focused C# scripts under `Assets/` and `Assets/Scripts/`.

Each interactive object has its own behavior:

- `Music.cs` and `Pinball.cs` adjust audio volume based on the player's distance to the object, fading sound in as you approach and out as you walk away.
- `laptop.cs` swaps between an open and closed laptop model when the player enters or leaves a trigger range.
- `Wave.cs` drives the avatar's animator, switching from a dance loop to a wave when the player gets close.
- `hinge.cs`, `Rotate.cs`, and `ShowText.cs` handle smaller interactions like rotating props and surfacing labels.
- The scripts use the same proximity-based pattern, comparing the player's headset position (CenterEyeAnchor) against each object's transform, which keeps the logic simple and consistent across the room.

## Challenges & Future Work
- It was hard to connect MetaQuest to Unity because there was a lot of bugs when installing, setting it up, and dealing with storage issues.
- Some computers were more compatible than others, and had an easier time rendering and connecting the environment to Unity.
- A teammember couldn't work with the simulator due to having MacOS Intel.
- We initially struggled with connecting the MetaQuest controllers to Unity.
- We had a difficult time asynchronously working on the project since there wasn't an efficient way to share work or have a smooth version control system setup when it comes to Unity, and it slowed down development efficiency and put burden on one of the team members more than the others which felt unfair.
- As we neared the end of the project and we had a ton of assets in Unity that made our programs crash continious and we had a lot of trouble getting the controllers to work.
- In the future we'd continue adding more unique assets and add more AR elements to make the scenes more realistic and fun to interact with.
- We'd love to add multiplayer so people can hang out in the room together.
- A working pinball machine you can actually play, and a turntable where you can swap records.
- A day/night toggle so the room can shift between chill study mode and disco mode.

## AI & Collaboration
Minimal AI usage besides for asset creation - mostly developed manually.

## Demo Video
[Link to demo](https://drive.google.com/file/d/1CcVdJR8fiT5L79GzELgUpgX1q9ONDaav/view?usp=sharing)




