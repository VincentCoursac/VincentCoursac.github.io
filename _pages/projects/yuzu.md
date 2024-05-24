---
permalink: /portfolio/yuzu
title: "Yuzu"
excerpt: "Yuzu SAS - Co-Founder"
identifier: project
order: 4
website: https://yuzu.hr
header:
    teaser: https://yuzu.hr/_ipx/w_1228/images/about/slide-1.webp
    overlay_image: /assets/images/covers/yuzu.jpg
sidebar:
  - title: "Role"
    text: "Chief Technical Officer"
  - title: "Date"
    text: "Aug 2022 - Mar 2024"
  - title: "Technologies"
    text: "Unreal Engine 5, C++, C#, Python, NodeJS, PHP, MongoDB, MySQL, AWS, Perforce, Git, JIRA"
  - title: "Platforms"
    text: "Cloud Gaming (in-house solution)"
---

**Yuzu** is a gamified HR assessment tool designed to evaluate candidates' soft skills through immersive video game scenarios. It combines neuroscience and game design to create realistic assessments that measure abilities such as communication, problem-solving, and empathy. This innovative platform helps reduce cognitive biases in hiring decisions and enhances the candidate experience, making it accessible and engaging for users. Yuzu's assessments are developed in collaboration with the **Lorraine Laboratory of Psychology and Neuroscience**, ensuring their scientific validity and reliability​
{: .notice--info}


<div style = "text-align:center">
  <iframe width="800" height="450" src="https://yuzu.hr/videos/landing-video.webm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

**Yuzu** was a truly unique experience for me, as it wasn't just a programming job, but also an entrepreneurial adventure in a start-up that I co-founded.

In the **summer of 2022**, while I was stepping down from the Skull & Bones project at Ubisoft (as the Paris team's mandate was nearing completion), a friend approached me with an exciting opportunity to co-found Yuzu. The concept behind the project was straightforward: to create a **video game** that could assess player behavior and deduce **soft skills** from it. The chance to become the CTO of a start-up and work with **Unreal Engine 5** was irresistible, so along with my two partners, we founded Yuzu.

![yuzu team at CES]({{ '/' | absolute_url }}/assets/images/projects/yuzu_ces.png){: width="800" .align-center}
<p style = "text-align:center;margin-top:-0.8em;font-style:italic">My partners, Jérome Dinet and me at the CES of Las Vegas (2023) at the Yuzu booth</p>

Everything was different here; there was no existing code base, no clear direction, and no team - **everything had to be built from the ground up!** It was an intense but incredibly rewarding experience. This venture allowed me to hone my skills not only in Unreal Engine but also in web programming, cloud gaming, and various managerial aspects such as recruitment and team leadership.
Speaking of recruitment, I managed to assemble a diverse team, including:

- Narrative designer
- Environment artist
- Character artist
- Animator
- UI/UX designer
- Front-end developper
- Back-end developer
- Unreal Engine developer
- Technical designer
- QA tester

![yuzu team]({{ '/' | absolute_url }}/assets/images/projects/yuzu_team.jpg){: width="800" .align-center}
<p style = "text-align:center;margin-top:-0.8em;font-style:italic">Yuzu team in December 2022</p>

Yuzu is a web-based solution for recruiters, enabling them to create dashboards where they invite candidates to take assessments. Once a candidate is invited, they receive an email prompting them to create their Yuzu candidate account and begin their assessment. The game is launched directly in their browser using our cloud gaming solution, based on Epic Games' Pixel Streaming. The player's behavior is tracked in real-time during their game session, and their results are compiled upon completion. Both the recruiter and the candidate then have access to these results on their respective platforms.

![diagram]({{ '/' | absolute_url }}/assets/images/projects/yuzu_archi.png){: width="800" .align-center}

To build this infrastructure, we utilized various technologies, including VueJS, NodeJS, PHP, Python, Unreal Engine 5, and more.

To ensure the scientific validity of our scenarios, we collaborated with 2LPN (Laboratoire Lorrain de Psychologie et Neurosciences de la Dynamique des Comportements), a laboratory specializing in psychology and cognitive sciences. We worked closely with Jérome Dinet, the laboratory director at the time, who helped us establish evaluation protocols based on current scientific knowledge and set up test benches to ensure our solution produced results as accurate as those obtained using recognized methods. You can find a scientific paper co-signed by Jérome and me detailing one of the evaluation mechanisms we implemented and its results: A Gamified Sorting Test to Assess Cognitive Flexibility in Personnel Selection: A Pilot Study.

![a test bench]({{ '/' | absolute_url }}/assets/images/projects/yuzu_benchs.webp){: width="800" .align-center}
<p style = "text-align:center;margin-top:-0.8em;font-style:italic">Jerome Dinet and a and a "cobaye" during one of our test benches</p>

## Responsibilities

Making an exhaustive list of all my responsibilities at Yuzu is going to prove impossible, as being in charge of the company's technical management implies a lot of things. But to give you an idea: 

### Developing our game
#### Gameplay programming and architecture
- Making overall game architecture
- 3C (first person controller, footsteps, ...)
- Interaction system
- Dialogue systems (NPC and "talkie walkie")
- Quest/objectives system
- Modular NPC backend and behavior (look at, animations, etc.)
- Spline guide system to help player to find the target location
- Modular scenario system, launching specific sequence of level based on recruiter needs and player progress
- Soft skills assessment related gameplay features (mini games, ui, ...)
- Game ui integration
- Remote logs integrations and debug systems
- CI/CD with Jenkins (allowing to send builds directly to AWS)

#### Game/Narrative/Level/Technical design
- Co-conception of assessment related scenarios in collaboration with 2LPN
- Co-conception of game narrative topics (story, dialogues, quests, ...)
- Integration of all these elements in the engine
- In game cinematics
- Sound design integrations

### Developing our web infrastructure
- Architecture and implementation of the SaaS API in PHP
- MySQL database design
- NodeJS real time API
- Internal dashboard with Angular
- Various slack integrations for internal purpose
- DevOps

### Developing our cloud solution
- PixelStreaming custom front-end
- C# game cloud instance manager

### Management and leadership
- Managing a team of artists and developers
- Producing with JIRA
- Relationship with external providers
- Participation in external events (CES for example)