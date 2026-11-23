# Charalampos Nadiotis

**What does a robot know when the radio goes quiet?**

I’m a robotics engineer in Cyprus and a computer science student at Frederick University. I’ve tested rover motors and calibrated underwater cameras. The question I want to take into a PhD in distributed autonomy systems is how marine robots can keep working together when they only hear from each other occasionally.

[PELAOS Tech](https://n0711.github.io/pelaos-tech/) · [LinkedIn](https://www.linkedin.com/in/nadiotis/)

## Three experiments you can explore

### Replay a telemetry outage

[ROS3-Limassol](https://github.com/n0711/ROS3-Limassol) records what reaches a robot’s telemetry receiver. In the [ArduPilot Rover simulation](https://github.com/n0711/ROS3-Limassol/blob/main/robotics/ros3_limassol/docs/SITL.md), you can interrupt the link, restore it, then replay the recording to see when the receiver marked the data stale and when it saw fresh telemetry again. The simulation runs on one host.

Christos Paparistodemou proposed the original idea. I lead this OpenPELAOS project and authored the paper.

### Follow a vehicle after it disappears from view

In UAV footage, a tracker has to decide whether the vehicle that reappears is the same one it lost. [VERA-MOT](https://github.com/n0711/vera-mot) tests whether image quality can help it decide which views to remember. The BoT-SORT baseline without re-identification covers **20 UAVDT test sequences**. The image-quality rule has passed synthetic tests. Its effect on identity tracking in UAVDT is still an open question.

### Change one symbol in a prompt

For my [BSc thesis](https://github.com/n0711/bsc_thesis_2027), I built a synthetic scoring problem small enough to try every possible prompt. That gives me the exact best score for each prompt length. Across **1,200 synthetic runs**, I measured how close random search and coordinate search could get with the same number of guesses.

## On the robotics bench

At Frederick University’s Robotics & Automation Systems Lab, I worked on rover and underwater vehicle integration, imaging, data acquisition and deployment preparation. Two projects you can try at a desk are the [USV flight-controller emulator](https://github.com/n0711/usv-sitl-flight-controller-emulator) for exercising telemetry in ArduRover simulation and the [MAVLink ground-station lab](https://github.com/n0711/mavlink_gcs_lab) for inspecting incoming messages and comparing saved parameters.

## Away from the bench

I play guitar, skateboard and surf. Two of those interests have their own projects here.

- [RioTuner](https://n0711.github.io/pelaos-tech/riotuner/) is my offline Android tuner for string instruments.
- [cysk8clips](https://cysk8clips.com) documents Cyprus skateboarding through local spots, video parts and event coverage.
- [LearnTwin](https://github.com/n0711/LearnTwin) keeps degree credits, assignments and thesis milestones in one place.
- [Skillshare-Local](https://github.com/n0711/Skillshare-Local) connects local instructors and learners.

I’ve also served on scientific committees and judged robotics competitions for Robotex Cyprus and WRO Cyprus.

## Work with me

I build websites, software and automations through PELAOS Tech. If you have a software project in mind or you’re researching how robots coordinate over unreliable links, I’d like to hear what you’re working on. [Message me on LinkedIn](https://www.linkedin.com/in/nadiotis/)

[Support my work](https://revolut.me/nadiotis)
