---
permalink: /portfolio/ghost-recon-breakpoint
title: "Tom Clancy's Ghost Recon Breakpoint"
excerpt: "Ubisoft Paris - Ubisoft"
identifier: project
order: 1
website: https://www.ubisoft.com/fr-fr/game/ghost-recon/breakpoint
header:
    teaser: https://cdn.cloudflare.steamstatic.com/steam/apps/2231380/capsule_616x353.jpg?t=1697654010
    overlay_image: /assets/images/covers/breakpoint.jpg
sidebar:
  - title: "Role"
    text: "Network Programmer (Internship)"
  - title: "Studio"
    text: "[**Ubisoft Paris**](https://paris.ubisoft.com/fr/)"
  - title: "Date"
    text: "Feb 2019 - July 2019"
  - title: "Technologies"
    text: "Anvil (internal engine), C++, C#, Perforce, JIRA"
  - title: "Platforms"
    text: "PC - PS4 - Xbox One - Stadia"
---

**Ghost Recon Breakpoint** by Ubisoft is an open-world tactical shooter set in the fictional archipelago of Auroa, where players assume the role of a Ghost operative stranded behind enemy lines. The game emphasizes survival, stealth, and strategic combat against a rogue faction of former Ghosts. With both solo and co-op modes, it offers a rich narrative and dynamic gameplay in diverse environments.
{: .notice--info}


<iframe width="560" height="315" src="https://www.youtube.com/embed/BLWt9MQLVgU?si=gx0BHxIzelAqvoa3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

I had the pleasure of working on this project as an intern in the **network team**. Our primary responsibility was to ensure that all necessary network functionalities (such as **replication and RPC**) were in place so the gameplay team could seamlessly integrate multiplayer features. Given that Ghost Recon Breakpoint is a vast open-world co-op game with PvP modes, our team of nearly ten people was dedicated to managing this crucial aspect.

This internship was a fantastic opportunity for me to dive into the video game industry and enhance my knowledge of **C++** and **networking**.

## Responsibilities

### Network programming
- Automatic real-time test scenarios to test replication, change of network object's ownership and client migration
- Network health test system (ping, latency, packet loss, ...)
- Stress test system for the "pvp server"

### Online services programming
- Adding remote logs and setup of a remote dashboard
- Adding kill switch for some network features (network health for example) piloted by the remote dashboard

### Debug
- Various small bug fixes and small improvements on the network engine
