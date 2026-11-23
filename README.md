# Charalampos Nadiotis

**Robotics engineer in Cyprus · BSc Computer Science student at Frederick University**

I work on how robots behave when their sensors or communication links give them incomplete information. On rovers and underwater vehicles, my work has included bringing up embedded controllers, testing motor response and calibrating underwater cameras. I plan to pursue a PhD in distributed autonomy systems. I’m especially interested in how marine robots can coordinate when they can exchange only occasional updates.

[PELAOS Tech portfolio](https://n0711.github.io/pelaos-tech/) · [LinkedIn](https://www.linkedin.com/in/nadiotis/)

## Research projects

| Project | Research question | Evidence in the repository |
| --- | --- | --- |
| [ROS3-Limassol](https://github.com/n0711/ROS3-Limassol) | When did telemetry stop reaching the receiver, and when did it resume? | Records receiver observations and replays them offline. A [single-host ArduPilot Rover simulation](https://github.com/n0711/ROS3-Limassol/blob/main/robotics/ros3_limassol/docs/SITL.md) exercises the receiver during scripted outages. |
| [VERA-MOT](https://github.com/n0711/vera-mot) | When can a tracker trust a vehicle’s appearance to reconnect its track after an occlusion? | The frozen BoT-SORT baseline without re-identification covers 20 UAVDT test sequences. In synthetic tests, the tracker uses crop quality to decide when to match by appearance and when to update its memory. Its effect on vehicle identity metrics on UAVDT remains open. |
| [BSc thesis](https://github.com/n0711/bsc_thesis_2027) | How does changing one symbol affect a prompt’s score, and how well can search recover the best prompt within a fixed budget? | Across 1,200 synthetic runs, the experiments compare random search and coordinate search under equal scoring budgets. Exhaustive enumeration gives the exact optimum for each prompt length. The repository includes the XeLaTeX dissertation and reproduction commands. |

ROS3-Limassol is an experimental OpenPELAOS project. Christos Paparistodemou proposed the original idea. I lead the project and authored the paper.

## Robotics and field experience

At Frederick University’s Robotics & Automation Systems Lab, I worked on rover and ROV integration, underwater imaging, data acquisition and deployment preparation. I also served as a scientific committee member and robotics competition judge for Robotex Cyprus and WRO Cyprus.

- [USV flight-controller emulator](https://github.com/n0711/usv-sitl-flight-controller-emulator) · An ArduRover software-in-the-loop setup that lets developers exercise a telemetry interface before connecting a physical controller.
- [MAVLink ground-station lab](https://github.com/n0711/mavlink_gcs_lab) · A receive-only Flutter and Rust prototype for inspecting live links and comparing saved ArduPilot parameters.

## Software and community projects

| Project | What I built |
| --- | --- |
| [LearnTwin](https://github.com/n0711/LearnTwin) | A browser-based workspace for tracking degree credits, assignments, thesis milestones and PhD applications, with local records and JSON backups. |
| [RioTuner](https://n0711.github.io/pelaos-tech/riotuner/) | An offline Android tuner for string instruments. |
| [cysk8clips](https://cysk8clips.com) | A community site documenting Cyprus skateboarding through videos, local spots and event coverage. |
| [Skillshare-Local](https://github.com/n0711/Skillshare-Local) | A PHP marketplace connecting local instructors and learners. |

## Work with me

Through [PELAOS Tech](https://n0711.github.io/pelaos-tech/), I build websites, software and automations. For a project enquiry or a research collaboration, [message me on LinkedIn](https://www.linkedin.com/in/nadiotis/) with what you’re working on.

Outside engineering, I skateboard, surf and play guitar.

[Support my work](https://revolut.me/nadiotis)
