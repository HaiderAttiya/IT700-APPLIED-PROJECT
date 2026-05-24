# SmartHome Connect — Presentation Script
**IT7000 Applied Project | Bahrain Polytechnic**
**Total Duration: ~18 minutes | 4 Presenters | 13 Slides**

---

## Slide Allocation

| Presenter | Role | Slides | Minutes |
|---|---|---|---|
| Haider Aljamry | Project Manager | 1, 2, 3 | ~4.5 min |
| Yosif Muhammed | Network Analyst & Documentation | 4, 5, 6 | ~4.5 min |
| Yassen Abbas | Network Designer | 7, 8, 9, 10 | ~4.5 min |
| S. Adam Alkhabaz | Network Engineer | 11, 12, 13 | ~4.5 min |

---

# HAIDER ALJAMRY — Project Manager
**Slides 1, 2, 3 | ~4.5 minutes**

---

## Slide 1 — Title Slide
⏱ *~1 minute*

Good afternoon, everyone. My name is Haider Aljamry, and I am the Project Manager for SmartHome Connect — our IT7000 Applied Project, developed here at Bahrain Polytechnic.

Joining me today are my teammates: Yosif Muhammed, our Network Analyst and documentation lead; Yassen Abbas, our Network Designer; and S. Adam Alkhabaz, our Network Engineer. Together, over the course of eight weeks, we designed, built, and tested a complete smart home network solution — and today, we're excited to walk you through everything we accomplished.

Let's get started.

---

## Slide 2 — Problem Statement
⏱ *~2 minutes*

Every great project starts with a real problem — and the world of home networking has several.

Home networks today often fail to deliver consistent coverage or fast enough speeds. Wi-Fi congestion is one of the biggest culprits, especially as more and more devices compete for bandwidth under the same roof. On top of that, most people never change their router's default settings — which opens serious cybersecurity vulnerabilities. And as smart home IoT devices become more common, the attack surface for potential data breaches grows even wider. Networks also struggle to scale for the sheer number of modern devices a typical household now owns.

So what did we set out to do about it?

Our objectives were clear: design a structured network layout using routers, switches, and end devices; implement a robust IP addressing scheme for organized communication; secure the network through proper authentication and Wi-Fi configurations; ensure the network can support multiple modern devices without performance loss; and deliver high-speed connectivity across all home areas.

These weren't just technical goals — they were practical goals designed to solve real problems that real households face every day.

---

## Slide 3 — Innovative Features
⏱ *~1.5 minutes*

To address those problems, we built SmartHome Connect around four key innovative features — all implemented using VLAN segmentation, Access Control Lists, and Quality of Service for traffic prioritization.

First, Bandwidth Prioritization. Using QoS policies, we guarantee internet speed for critical devices — so that even under heavy network load, priority devices always perform at their best. No more video calls dropping because someone started a large download.

Second, Guest Network Access. A separate VLAN for visitors means guests can connect to the internet freely, while remaining completely isolated from private home devices and files.

Third, Device Monitoring. The network identifies all connected devices, and any unknown device is flagged immediately — giving the homeowner full visibility and control at all times.

And fourth, Optimized Wi-Fi Coverage. Access point placement was carefully planned to ensure strong signal distribution throughout all areas of the home, eliminating dead zones entirely.

I'll now hand over to Yosif, who will walk you through our project timeline and planning in detail.

---
---

# YOSIF MUHAMMED — Network Analyst & Documentation
**Slides 4, 5, 6 | ~4.5 minutes**

---

## Slide 4 — Project Phases & Timeline
⏱ *~1.5 minutes*

Thank you, Haider. My name is Yosif Muhammed, and as the network analyst and documentation lead, I managed our project planning, tracking, and milestone verification throughout the entire lifecycle.

Let me walk you through how we structured the project across eight weeks, from March 1st through April 25th, 2026.

We divided the project into four phases. Phase 1 was Planning — spanning the first two weeks of March — where we gathered requirements and conducted our initial network analysis. Phase 2 was Execution, from March 15th to the 31st, where we developed our topology design and began device configuration. Phase 3 was Simulation, a focused testing sprint in early April using Cisco Packet Tracer to verify everything worked as intended. And Phase 4 was Closure — documentation, final review, and preparation for this presentation.

Every phase had a clear deliverable, and as you'll see on the next slide, every single task was completed on schedule.

---

## Slide 5 — Project Timeline (Gantt)
⏱ *~1.5 minutes*

Here is the detailed Gantt view. Six key tasks, all completed — Project Planning, Network Analysis, Topology Design, IP Addressing, Packet Tracer Testing, and Final Documentation. Every item carries a green checkmark.

This didn't happen by accident. It happened because the team committed to weekly check-ins, maintained a shared task board, and held each other accountable throughout the project. Keeping a project like this on track — especially with simulation phases that are always unpredictable — requires discipline. And this team delivered.

One thing worth noting: the simulation phase required more time than originally estimated. We had built buffer time into our schedule specifically for this reason, and that buffer made all the difference in staying on track.

---

## Slide 6 — Critical Path Milestones
⏱ *~1.5 minutes*

Beyond the Gantt chart, we also tracked our critical path — the sequence of milestones that the entire project depended on.

It began on March 3rd with the approval of our Project Charter, which officially launched the project and aligned the team on scope and objectives. On March 18th, we finalized our network topology, giving Yassen and Adam a locked-down blueprint to work from. By March 25th, our IP addressing scheme was fully set — a foundational step that everything else depended on. April 4th marked the successful verification of our Packet Tracer simulation, confirming that our design worked not just on paper, but in a live testing environment. And on April 25th, our Final Report was ready — complete, reviewed, and submitted.

Each of these milestones was a gate. Nothing moved forward until the previous gate was passed. That structure kept our project focused and prevented scope creep throughout.

I'll now hand over to Yassen, who will take you through the full network design.

---
---

# YASSEN ABBAS — Network Designer
**Slides 7, 8, 9, 10 | ~4.5 minutes**

---

## Slide 7 — RACI Responsibility Matrix
⏱ *~1 minute*

Thank you, Yosif. My name is Yassen Abbas, and I was responsible for designing the network architecture of SmartHome Connect. But before I get into the design itself, let me briefly cover how responsibilities were distributed across the team using our RACI matrix.

Haider, as Project Manager, held Accountability across all major tasks. I, as Responsible for Topology Design, was Consulted on planning and analysis phases to ensure my designs reflected real network requirements. Yosif was Responsible for Requirement Gathering, Network Analysis, and Testing. Adam was Responsible for Device Configuration — the hands-on technical implementation. And everyone was kept Informed on phases outside their primary ownership.

This matrix eliminated confusion, reduced overlap, and ensured every task had a clear owner from day one.

---

## Slide 8 — Network Architecture
⏱ *~1.5 minutes*

Now, the design itself.

At the heart of SmartHome Connect is a Star Topology. Every device in the network connects through a central Cisco 2911 Router. This architectural choice gives us three key advantages: centralized management — all traffic flows through one point of control; easy troubleshooting — if a problem arises, you know exactly where to look; and isolated fault domains — a failure in one branch doesn't cascade to bring down the entire network.

Here's how it comes together in practice. The Cisco 2911 Router acts as the gateway to the internet, managing all routing between the home network and the outside world. A managed switch connects all wired devices — PCs and printers — providing fast, stable connectivity. A wireless access point extends the network wirelessly for guest devices. And VLANs, which I'll detail shortly, segment the network to separate private traffic from guest traffic cleanly and securely.

---

## Slide 9 — IP Addressing Table
⏱ *~1 minute*

With the topology designed, the next step was defining the IP addressing scheme — giving every device a clear, organized identity on the network.

The Home Router sits at 192.168.1.1, serving as the gateway for all traffic. The Media Server is statically assigned to 192.168.1.5 on VLAN 10. The Printer is at 192.168.1.6, also on VLAN 10 — statically assigned because shared resources need predictable, consistent addresses. PC-A uses DHCP, receiving its address dynamically from the VLAN 10 pool. And the Guest Laptop uses DHCP as well, but draws from VLAN 20, with a completely separate gateway at 192.168.20.1.

This separation is deliberate. Static IPs for servers and shared devices ensure they are always reachable. DHCP for end-user devices reduces administrative overhead. And the VLAN gateway separation enforces traffic isolation at the network layer.

---

## Slide 10 — VLAN Segmentation
⏱ *~1 minute*

VLAN segmentation is the most important security feature in the entire design. Let me explain the three VLANs we implemented.

VLAN 10 is the Private Home Network on the 192.168.10.0/24 subnet. This is where all trusted devices live — PCs, printers, media servers, and smart home devices. VLAN 20 is the Guest Access Network on 192.168.20.0/24. Guests get internet access, but are completely isolated from every device on VLAN 10 — they cannot see your printer, cannot reach your media server, and cannot access any private file. VLAN 99 is the Management VLAN on 192.168.99.0/24, reserved exclusively for administrators to configure routers and switches securely — invisible to regular users entirely.

Together, these three VLANs create a segmented, layered network that is dramatically more secure than a flat, single-network design.

I'll now hand over to Adam, who will cover our risk management, outcomes, and close the presentation.

---
---

# S. ADAM ALKHABAZ — Network Engineer
**Slides 11, 12, 13 | ~4.5 minutes**

---

## Slide 11 — Project Risks & Mitigation
⏱ *~1.5 minutes*

Thank you, Yassen. My name is Adam Alkhabaz, and as the network engineer I was responsible for the hands-on technical implementation of this project. I'll start by covering the risks we faced and how we managed them.

We identified four key risks. The first was configuration errors — mistakes during router or switch setup that could break connectivity. Our mitigation was peer review combined with rigorous Packet Tracer testing before any configuration was considered final.

The second was time delays. We addressed this with weekly team meetings and active Gantt chart tracking, so any slippage was caught within days, not weeks.

Third was team coordination — with four people working across different areas, miscommunication is always a risk. We solved this with regular Discord calls and a shared task board that kept everyone aligned in real time.

The fourth was VLAN and IP conflicts — a real technical risk when multiple people configure network segments independently. Packet Tracer simulation was our safety net, catching and resolving conflicts before they could affect the final design.

All four risks were successfully managed. None of them derailed the project. Planning ahead made the difference.

---

## Slide 12 — Key Outcomes & Lessons Learned
⏱ *~2 minutes*

Now let's look at what we achieved — and what we learned along the way.

On the outcomes side: we successfully delivered a complete SmartHome Connect network design incorporating a Cisco 2911 router, managed switches, and a wireless access point. VLAN separation between home users on VLAN 10 and guest users on VLAN 20 was fully implemented and verified. Communication paths across the entire network were configured correctly and tested. The full simulation was completed successfully in Cisco Packet Tracer. And the final result is a network with improved performance, stronger coverage, and significantly enhanced security compared to a default home setup.

On the lessons learned side: strength-mapping team roles from the start minimized confusion and overlap. Regular Discord syncs caught technical bugs early, before they became serious problems. Shared documents kept all four of us informed and aligned, even when working on different components. Buffer time in simulation phases saved us — those phases always take longer than planned. And when disagreements arose, handling them respectfully kept team morale high and allowed us to move forward productively.

---

## Slide 13 — Thank You
⏱ *~1 minute*

On behalf of the entire SmartHome Connect team — Haider, Yosif, Yassen, and myself — thank you for your time and attention today.

This project gave us the opportunity to apply real networking concepts to a practical, meaningful scenario. We tackled real problems, made real design decisions, and built something we are genuinely proud of.

We are now happy to take any questions you may have — whether about our design choices, our VLAN structure, our configuration decisions, or anything else from the presentation.

Thank you.

---

## Summary

| Presenter | Slides | Approx. Time |
|---|---|---|
| Haider Aljamry | 1, 2, 3 | ~4.5 min |
| Yosif Muhammed | 4, 5, 6 | ~4.5 min |
| Yassen Abbas | 7, 8, 9, 10 | ~4.5 min |
| S. Adam Alkhabaz | 11, 12, 13 | ~4.5 min |
| **Total** | **13 slides** | **~18 minutes** |
