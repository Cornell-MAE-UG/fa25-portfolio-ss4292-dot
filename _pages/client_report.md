---
layout: default
title: Client Pitch
permalink: /client-report/
---
## Client Pitch

[Download my client reprt]({{ "assets/T2_ Spotted Then Stopped Client Report.pdf" | relative_url }}) in PDF format.


**Context and Problem Statement**
Due to limitations in the labour force, New York vineyard operators use mechanical harvesters rather than hand-picking grapes. This allows Spotted Lanternflies (SLF) to frequently enter harvester bins and contaminate the yield. A Cornell–Penn State study found that 60% of lanternflies on vines end up in harvester bins, and current standards require rejection if even 1–2 adult insects are found per 1 kg sample. This leads farmers to invest a season's worth of resources in a crop, only for it to be rejected due to late-stage contamination. Addressing this issue reduces uncertainty in harvest outcomes, allowing farmers to plan and allocate resources with greater confidence. It will also invariably lead to higher profits as fewer crops will be rejected due to contamination.

Significantly disturbing the vine to remove SLF's proves a problem when harvesting, as ripe grapes detach very easily, potentially resulting in losses if directly exposed to excessive forces. Thus, we have tailored our design to vertical shoot positioning trellis systems, which have long vines, with grapes growing above a set level, allowing us to target the vine without disturbing the grapes.


**Final Prototype and Application**
Our prototype consists of two motorized brushes that mount onto the front of a harvester. As the harvester travels through the field, it removes SLF from the vine moments before the grapes are harvested, ensuring no lanternflies contaminate the crop. Each attachment is modular in design, with key features being the shaft and the strip brushes. Shafts have been 3D printed with slots to hold strip brushes in place, allowing the quick and easy replacement of brushes without compromising on the snugness of fit. Shafts are also split into two parts, allowing farmers to adjust for different vine dimensions by simply changing the length of the brushes fitted in the shaft. The shafts are suspended by a top and bottom bracket, which attach to the front of the harvester.

In practice, farmers will determine the required brush length based on vine dimensions and how low-hanging the grapes are. The brushes should only contact the vine and therefore not disturb the grapes growing above. The farmer will then insert them into the shaft and mount the modules onto the harvester. As the harvester travels through the vines, the motorized brushes sweep in an outward direction, ensuring all SLF are directed away from the harvesting bins. While the prototype motors are powered by a mains supply, a deployed system would draw power directly from the harvester’s onboard electrical system.

**Conclusion and Recommendation**
From testing our prototype, it displays clear potential for solving the subproblem we have identified. One primary success criteria we judged our design on was its ability to remove objects from vine-like structures. In our functionality test, it removes up to 80% of sticky notes and 70% of paper clips - two objects with similar length scales and resistance to removal as SLF. Another success criteria we judged our design on was how easy the shaft and brushes were to assemble. In the assembly test, it took 41 seconds to replace the brushes and around 4.5 minutes to mount them on the brackets. Since mounting on the brackets will only have to be done once per harvest, we have judged this to be a reasonable amount of time and therefore meets the success criteria. Alongside meeting our success criteria, our design is very financially viable. It requires only a one-time setup, attaching it to the front of the harvester, and from there, the only upkeep would be brush replacement, which, due to the modularity of our design, is very quick and simple. Likewise, vineyard owners would only have to purchase one of these per harvester and replace brushes as needed.

Despite our primary success criteria being met, we believe our prototype requires further development before field testing. One major aspect of our current design is missing is a mounting system for the harvester. For future iterations of our design, we would make a metal frame to attach the arms to the harvester and also make the shaft and arms out of a lightweight, weather-resistant material. This would make our design more structurally robust and able to withstand the higher loads experienced on high-powered machinery. Once these adjustments have been made, we would be able to perform field tests to validate our lab results under real conditions. 

Overall, we recommend our design to continue to be developed, with improvements primarily focusing on the mounting system and also structural integrity. After these have been implemented, field tests should be conducted.

**Testing and Results**
To test the validity of our success, we completed: a functional test, an assembly test, and a rupture test.

*Functional test:*
For the functional test we passed a tube through rotating brushes with different types of attachments, modeling the lantern flies. The attachments were differentiated by how strongly they stuck to the vine to evaluate different grip strengths. We also examined which orientation of brush rotation would be most effective in removing the most attachments. For the 3 different attachments, we found that outwards rotation was the most effective; therefore, this is what we used for our final design and what we recommend for harvesters. 

*Assembly test:*
For our assembly test, we wanted to make sure that the modular aspect of the design was highlighted. We completed the test by doing three timed trials of replacing brushes and mounting the brushes onto the bracket. We found that replacing brushes took an average of 41 seconds, showing how time-effective this design is as this is the only part of the design that will need to be replaced in the long term. This passed our success criteria as we were able to replace the brushes in under a minute. Additionally, we found that the average time for the brushes to be mounted onto the bracket was around 4.5 minutes.

*Rupture test:*
Our last test was to assess the effect of the brushes on low-hanging grapes. We found that the larger the exposure of the grapes to the brushes, the more grapes were harmed. We completed this to test the results on vines without vertical shoot positioning. We decided that this design would work better on vineyards that do use it, which is around 78% of New York vineyards. We also came to the conclusion that the grapes lost due to rupture are negligible compared to the yield lost due to contamination.  

**Prototype and Testing Details**
Each of the 2 modules consists of: 1 shaft, 6 replaceable nylon brushes, 1 12V motor, 6 screws, 4 nuts, 1 top arm, 1 bottom arm, 2 wires, 1 adaptor, and 1 bearing. 

The system is assembled in a top-down sequence for easier installation. First, the motor is mounted to the top bracket and secured with nuts. The motor wiring is routed through the center of the top bracket and exits out the back for connection. For the second module, the wires are swapped so the motor spins in the opposite direction.

Next, the six nylon brushes are inserted into the slots of the central shaft. The bearing is press-fit into the bottom bracket to support rotation. The shaft is then inserted through the bearing and connected to the motor shaft above, allowing the system to rotate.

Finally, the top and bottom brackets are aligned, and the full assembly is secured to the backboard with screws. This process is repeated for the second module. This ensures proper alignment of the rotating components while allowing for easy brush replacement.

*Functional testing:* Initial brushes were too short and did not make consistent contact. Increasing the brush length (~3") improved performance.

*Assembly testing:* Brush insertion was difficult at first. Redesigning the shaft with larger slots made assembly faster and more reliable.

*Torque testing:* The initial motor was not strong enough due to friction. Loads were added to estimate the required torque, which helped the selection of the 12V motor.

**Appendix**

Bill of Materials:
| Item | Quantity | Total Cost |
| -------- | -------- | -------- |
| 1 inch brushes | 12 brushes | $42.35 |
| 3 inch brushes| 12 brushes | $50.00 |
| Bearings| 2 bearings | $64.00 |
| Filament (estimate) | 947.6 grams| $47.38 |
| Motors| 2 motors | $145.28|

References:

“Grapevines May Only Need Help to Survive Heavy Spotted Lanternfly Infestations | Penn State University.” 2017. Psu.edu. 2017. https://www.psu.edu/news/research/story/grapevines-may-only-need-help-survive-heavy-spotted-lanternfly-infestations.

Wright, Amy Beth. 2026. “The Science behind Vertical Shoot Positioning in Vineyards | SevenFifty Daily.” SevenFifty Daily. March 23, 2026. https://daily.sevenfifty.com/the-science-behind-vertical-shoot-positioning-in-vineyards/.

