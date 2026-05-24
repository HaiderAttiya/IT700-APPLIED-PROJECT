# SmartHome Connect — Presentation Script
**IT7000 Applied Project | Bahrain Polytechnic**
**Total Duration: ~18 minutes | 4 Presenters | 13 Slides**
 
---
 
## Slide Allocation
 
| Presenter | Role | Slides | Minutes |
|---|---|---|---|
| Haider Aljamry | Project Manager | 1, 2, 4, 5 | ~4.5 min |
| Yosif Muhammed | Network Analyst & Documentation | 6, 7, 11 | ~4.5 min |
| Yassen Abbas | Network Designer | 8, 9, 10 | ~4.5 min |
| S. Adam Alkhabaz | Network Engineer | 3, 12, 13 | ~4.5 min |
 
---
 
---
 
# HAIDER ALJAMRY — Project Manager
**Slides 1, 2, 4, 5 | ~4.5 minutes**
 
---
 
## Slide 1 — Title Slide
⏱ *~1 minute*
 
Good afternoon, everyone. My name is Haider Aljamry, and I am the Project Manager for SmartHome Connect — our IT7000 Applied Project, developed here at Bahrain Polytechnic.
 
Joining me today are my teammates: Yosif Muhammed, our Network Analyst and documentation lead; Yassen Abbas, our Network Designer; and S. Adam Alkhabaz, our Network Engineer. Together, over the course of eight weeks, we designed, built, and tested a complete smart home network solution — and today, we're excited to walk you through everything we accomplished.
 
Let's get started.
 
---
 
## Slide 2 — Problem Statement
⏱ *~1.5 minutes*
 
Every great project starts with a real problem — and the world of home networking has several.
 
Home networks today often fail to deliver consistent coverage or fast enough speeds. Wi-Fi congestion is one of the biggest culprits, especially as more and more devices compete for bandwidth under the same roof. On top of that, most people never change their router's default settings — which opens serious cybersecurity vulnerabilities. And as smart home IoT devices become more common, the attack surface for potential data breaches grows even wider.
 
So what did we set out to do about it?
 
Our objectives were clear: design a structured network layout using routers, switches, and end devices; implement a robust IP addressing scheme for organized communication; secure the network through proper authentication and Wi-Fi configurations; ensure the network can support multiple modern devices without performance loss; and deliver high-speed connectivity across all home areas.
 
These weren't just technical goals — they were practical goals designed to solve real problems that real households face every day.
 
---
 
## Slide 4 — Project Phases & Timeline
⏱ *~1 minute*
 
Now let's look at how we planned and executed this project across eight weeks, from March 1st through April 25th, 2026.
 
We divided the project into four phases. Phase 1 was Planning — spanning the first two weeks of March — where we gathered requirements and conducted our initial network analysis. Phase 2 was Execution, running from March 15th to the 31st, where we developed our topology design and began device configuration. Phase 3 was Simulation, a focused testing sprint in early April using Cisco Packet Tracer to verify everything worked as intended. And Phase 4 was Closure — documentation, final review, and preparation for this very presentation.
 
Every phase had a clear deliverable, and as you'll see on the next slide, every single task was completed on schedule.
 
---
 
## Slide 5 — Project Timeline (Gantt)
⏱ *~1 minute*
 
Here's the detailed timeline view. Six key tasks, all completed — Project Planning, Network Analysis, Topology Design, IP Addressing, Packet Tracer Testing, and Final Documentation.
 
I'm particularly proud of this slide because every item carries a green checkmark. This didn't happen by accident. It happened because the team committed to weekly check-ins, maintained a shared task board, and held each other accountable throughout the entire lifecycle of the project.
 
Keeping a project like this on track — especially with simulation phases that are always unpredictable — requires discipline. And this team delivered.
 
I'll now hand over to Yosif, who will walk you through the project milestones, responsibilities, and risk management.
 
---
---
 
# YOSIF MUHAMMED — Network Analyst & Documentation
**Slides 6, 7, 11 | ~4.5 minutes**
 
---
 
## Slide 6 — Critical Path Milestones
⏱ *~1.5 minutes*
 
Thank you, Haider. My name is Yosif Muhammed, and as the network analyst and documentation lead, I was responsible for tracking our critical path and ensuring every milestone was clearly defined and met.
 
The critical path of our project ran through five key milestones. It began on March 3rd with the approval of our Project Charter — this officially launched the project and aligned the team on scope and objectives. On March 18th, we finalized our network topology, giving Yassen and Adam a locked-down blueprint to work from. By March 25th, our IP addressing scheme was fully set — a foundational step that everything else depended on. April 4th marked the successful verification of our Packet Tracer simulation — confirming that our design worked not just on paper, but in a live testing environment. And on April 25th, our Final Report was ready — complete, reviewed, and submitted.
 
Each of these milestones was a gate. Nothing moved forward until the previous gate was passed. That structure kept our project focused and prevented scope creep.
 
---
 
## Slide 7 — RACI Responsibility Matrix
⏱ *~1.5 minutes*
 
Understanding who does what — and who is accountable for what — is essential in any team project. This is what the RACI matrix captures.
 
Let me walk you through how responsibilities were distributed across the team.
 
Haider, as Project Manager, held Accountability across all major tasks — the final say rested with him. For Project Planning, he was both Responsible and Accountable.
 
I, as Network Analyst, was Responsible for Requirement Gathering, Network Analysis, and Testing & Simulation. I was Consulted on Topology Design, and kept Informed on other phases.
 
Yassen, our Network Designer, was Responsible for Topology Design — his core domain. He was Consulted on Planning and Analysis to ensure design decisions reflected real network requirements.
 
Adam, our Network Engineer, was Responsible for Device Configuration — the hands-on technical implementation. He was kept Informed throughout earlier phases so he was ready to execute the moment the designs were finalized.
 
This matrix wasn't just a document — it was a live working agreement that reduced confusion, eliminated overlap, and made sure every task had a clear owner.
 
---
 
## Slide 11 — Project Risks & Mitigation
⏱ *~1.5 minutes*
 
No project is without risk, and part of my role as analyst was to identify those risks early and document mitigation strategies for each one.
 
We identified four key risks. The first was configuration errors — mistakes made during router or switch setup that could break connectivity. Our mitigation was peer review combined with rigorous Packet Tracer testing before any configuration was considered final.
 
The second risk was time delays. We addressed this with weekly team meetings and active Gantt chart tracking, so any slippage was caught within days, not weeks.
 
Third was team coordination — with four people working across different areas, miscommunication is always a risk. We solved this with regular Discord calls and a shared task board that kept everyone aligned in real time.
 
The fourth risk was VLAN and IP conflicts — a very real technical risk when multiple people are configuring network segments independently. Again, Packet Tracer simulation was our safety net, allowing us to catch and resolve conflicts before they could affect the final design.
 
I'm pleased to report that all four risks were successfully managed. None of them derailed the project. Planning ahead made the difference.
 
I'll now pass to Yassen, who designed the network architecture you're about to see.
 
---
---
 
# YASSEN ABBAS — Network Designer
**Slides 8, 9, 10 | ~4.5 minutes**
 
---
 
## Slide 8 — Network Architecture
⏱ *~1.5 minutes*
 
Thank you, Yosif. My name is Yassen Abbas, and I was responsible for designing the network architecture of SmartHome Connect.
 
At the heart of the design is a Star Topology. Every device in the network connects through a central Cisco 2911 Router. This architectural choice gives us three key advantages: centralized management — all traffic flows through one point of control; easy troubleshooting — if a problem arises, you know exactly where to look; and isolated fault domains — a failure in one branch doesn't cascade to bring down the entire network.
 
Here's how the network is structured in practice. The Cisco 2911 Router acts as the gateway to the internet, managing all traffic routing between the home network and the outside world. A managed switch connects all wired devices — PCs and printers — providing fast, reliable, and stable connectivity. A wireless access point extends the network wirelessly, serving guest devices over a dedicated Wi-Fi network. And VLANs — which I'll detail in a moment — segment the network to separate private home traffic from guest traffic.
 
This architecture is scalable, secure, and purpose-built for a modern smart home environment.
 
---
 
## Slide 9 — IP Addressing Table
⏱ *~1.5 minutes*
 
With the topology designed, the next critical task was defining the IP addressing scheme — ensuring every device on the network had a clear, organized identity.
 
The Home Router sits at 192.168.1.1, serving as the gateway for all traffic. The Media Server, assigned to VLAN 10, uses a static IP of 192.168.1.5. The Printer, also on VLAN 10, is at 192.168.1.6 — statically assigned because shared resources need predictable, consistent addresses. PC-A uses DHCP, receiving its address dynamically from the VLAN 10 pool. And the Guest Laptop also uses DHCP, but it draws from VLAN 20 — the isolated guest network — with a gateway of 192.168.20.1.
 
This separation is deliberate and important. Static IPs for servers and shared devices ensure they are always reachable. DHCP for end-user devices reduces administrative overhead. And the VLAN gateway separation enforces traffic isolation at the network layer.
 
---
 
## Slide 10 — VLAN Segmentation
⏱ *~1.5 minutes*
 
VLAN segmentation is arguably the most important security feature in our entire design. Let me explain why we structured it this way.
 
We implemented three VLANs. VLAN 10 is the Private Home Network, operating on the 192.168.10.0/24 subnet. This is where all trusted devices live — PCs, printers, media servers, and smart home devices. Devices on VLAN 10 expect robust, stable connectivity, and they get it.
 
VLAN 20 is the Guest Access Network, on the 192.168.20.0/24 subnet. Guests connect here. They get internet access — but they are completely isolated from every device on VLAN 10. They cannot see your printer, cannot access your media server, and cannot reach any private device. This isn't just a convenience feature — it's a security boundary.
 
VLAN 99 is the Management VLAN, on the 192.168.99.0/24 subnet. This VLAN is reserved exclusively for administrators to access and configure the router and switch. It is invisible to regular users and adds a critical layer of control — even if an attacker somehow gains access to VLAN 10 or 20, they still cannot reach the management plane.
 
Together, these three VLANs create a segmented, layered network that is dramatically more secure than a flat, single-network design.
 
I'll now pass to Adam, who will cover our innovative features, results, and close the presentation.
 
---
---
 
# S. ADAM ALKHABAZ — Network Engineer
**Slides 3, 12, 13 | ~4.5 minutes**
 
---
 
## Slide 3 — Innovative Features
⏱ *~1.5 minutes*
 
Thank you, Yassen. My name is Adam Alkhabaz, and as the network engineer, I was responsible for implementing the technical features that make SmartHome Connect more than just a basic home network.
 
Our design incorporates four key innovations, all built on top of VLAN segmentation, ACLs, and Quality of Service — or QoS — for traffic prioritization.
 
First, Bandwidth Prioritization. Using QoS policies, we guarantee internet speed for critical devices — such as the media server or a work PC — so that even under heavy network load, priority devices always perform at their best. No more video calls dropping because someone started a large download.
 
Second, Guest Network Access. By isolating guest devices on VLAN 20, visitors can connect to the internet freely without any exposure to the private home network. Their traffic is segmented at the switch level, so the isolation is enforced in hardware — not just by a password.
 
Third, Device Monitoring. The network is configured to identify all connected devices. Any unknown device that appears on the network triggers a flag. This gives the homeowner full visibility and control — an essential feature in an era of smart home proliferation.
 
And fourth, Optimized Wi-Fi Coverage. Access point placement was carefully considered to ensure strong signal distribution across all areas of the home, eliminating dead zones and delivering consistent wireless performance everywhere.
 
---
 
## Slide 12 — Key Outcomes & Lessons Learned
⏱ *~1.5 minutes*
 
Now let's look at what we achieved — and what we learned along the way.
 
On the outcomes side: we successfully delivered a complete SmartHome Connect network design incorporating a Cisco 2911 router, managed switches, and a wireless access point. VLAN separation between home users on VLAN 10 and guest users on VLAN 20 was fully implemented and verified. Communication paths across the entire network were configured correctly and tested. The full simulation was completed successfully in Cisco Packet Tracer. And the final result is a network with improved performance, stronger coverage, and significantly enhanced security compared to a default home setup.
 
On the lessons learned side — and these are the insights I think are most valuable to carry forward: Strength-mapping team roles from the start minimized confusion and overlap. Regular Discord syncs caught technical bugs early, before they became serious problems. Shared documents kept all four of us informed and aligned, even when working on different components. Buffer time in simulation phases saved us — those phases always take longer than planned. And when disagreements arose, handling them respectfully kept team morale high and allowed us to move forward productively.
 
---
 
## Slide 13 — Thank You
⏱ *~1 minute*
 
On behalf of the entire SmartHome Connect team — Haider, Yosif, Yassen, and myself — thank you for your time and attention today.
 
This project gave us the opportunity to apply real networking concepts to a practical, meaningful scenario. We tackled real problems, made real design decisions, and built something we're genuinely proud of.
 
We are now happy to take any questions you may have — whether about our design choices, our configuration decisions, our VLAN structure, or anything else from the presentation.
 
Thank you.
 
---
 
## Summary
 
| Presenter | Slides | Approx. Time |
|---|---|---|
| Haider Aljamry | 1, 2, 4, 5 | ~4.5 min |
| Yosif Muhammed | 6, 7, 11 | ~4.5 min |
| Yassen Abbas | 8, 9, 10 | ~4.5 min |
| S. Adam Alkhabaz | 3, 12, 13 | ~4.5 min |
| **Total** | **13 slides** | **~18 minutes** |