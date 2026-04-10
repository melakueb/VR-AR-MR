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
