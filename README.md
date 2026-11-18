# ELISA-1
An open-source autonomous AI robot companion with proactive intelligence, natural conversation and independent navigation.
🤖 ELISA-1

An Autonomous AI Robot Companion

An open-source robotics project by La Bestia 3D

Designed and developed in Alicante, Spain 🇪🇸

⸻

🌟 Our Vision

What if a robot could do more than simply follow commands?

ELISA-1 is an ambitious open-source project to develop a fully autonomous, mobile AI robot companion.

Our goal is not to build another remote-controlled robot, a chatbot on wheels, or a complicated humanoid.

We want to create an intelligent companion capable of observing its surroundings, understanding context, remembering relevant information, engaging in natural conversations, and taking meaningful initiative.

ELISA should not constantly wait for instructions.

She should be able to recognize situations, make suggestions, navigate independently, and interact naturally with the people around her.

The ultimate goal: a robot that feels like a helpful presence in everyday life.

ELISA-1 is currently in the early design and research phase.

This repository will document the journey from initial concept to a functioning autonomous robot.

⸻

🧠 Artificial Intelligence & Autonomy

Intelligence is at the heart of ELISA-1.

We envision a system combining conversational AI, environmental awareness, memory, reasoning, and autonomous decision-making.

Planned AI Capabilities

* Natural, context-aware conversations.
* Speech recognition and voice interaction.
* Recognition of familiar people and pets.
* Long-term memory of relevant information.
* Understanding daily routines and preferences.
* Environmental and situational awareness.
* Independent information gathering.
* Proactive suggestions and interactions.
* Autonomous task planning.
* Context-sensitive decision-making.

Beyond Simple Commands

Imagine ELISA noticing that the family dog might need a walk.

Instead of automatically suggesting going outside, she checks the current weather conditions.

If severe thunderstorms or flooding warnings are active, she adapts her recommendation.

This illustrates an important design principle:

ELISA should consider context before suggesting or performing actions.

The system will combine AI reasoning with explicit safety rules and clearly defined permissions.

Physical safety must never depend solely on an AI language model.

⸻

🤖 Physical Design

ELISA-1 will feature a custom-designed, primarily 3D-printed body.

Our design inspiration includes compact service robots and the iconic R2-D2 astromech concept.

Rather than building a humanoid robot with complicated facial mechanisms, we prefer a simple, expressive design.

Preliminary Specifications

Feature	Design Goal
Height	Approximately 60 cm
Weight	Target: 15 kg maximum
Body	Custom 3D-printed enclosure
Mobility	Wheels or rubber tracks
Head	Rotating dome
Vision	Visible camera system
Expression	Programmable LED lighting
Audio	Microphones and speakers
Navigation	Autonomous indoor navigation
Obstacle avoidance	Multiple sensor technologies
Charging	Automatic docking station
Transport	Optional small cargo tray
Connectivity	Wi-Fi and local network
Computing	Embedded computer with optional external AI processing

These specifications are preliminary and may change during development.

Expressive LED Communication

Instead of complex facial expressions, ELISA will communicate her current state through programmable lighting.

Possible states include:

* 🔵 Listening
* 🟢 Ready or acknowledged
* 🟡 Processing
* 🟣 Speaking
* 🔴 Warning or error
* ⚪ Standby

A rotating dome will allow ELISA to direct her camera toward people and objects.

The combination of dome movement, lighting, and natural speech should give ELISA a recognizable personality without unnecessary mechanical complexity.

⸻

🛞 Autonomous Mobility

ELISA must be capable of navigating independently through a home.

Planned Features

* Indoor mapping and localization.
* Autonomous route planning.
* Obstacle detection and avoidance.
* Navigation toward people or destinations.
* Recognition of restricted areas.
* Safe movement around people and pets.
* Automatic return to a charging station.
* Recovery from navigation errors.

We are currently evaluating two propulsion concepts:

1. Differential-drive wheels

Potential advantages include efficiency, simplicity, accurate odometry, and lower noise.

2. Rubber tracks

Potential advantages include stability, traction, and the ability to handle certain floor transitions.

Noise, energy consumption, floor protection, mechanical complexity, and positioning accuracy will influence the final decision.

Navigation Technology

Technologies under consideration include:

* ROS 2
* LiDAR
* Wheel encoders
* Cameras
* Distance sensors
* Bumper sensors
* SLAM-based mapping and localization

Safety-critical motor control will remain independent of cloud-based AI services.

⸻

🔋 Automatic Charging

One of our key objectives is autonomous charging.

ELISA should recognize when her battery is running low and return to her charging station without human intervention.

We aim to develop a simple, reliable docking solution.

Possible technologies include:

* Visual docking markers such as AprilTags.
* Short-range positioning sensors.
* Mechanical alignment guides.
* Spring-loaded charging contacts.
* Charging verification and battery protection.

Reliability and electrical safety will take priority over mechanical complexity.

⸻

📦 Optional Cargo Transport

A small transport platform or drawer is being considered.

This could allow ELISA to carry lightweight objects between locations.

For example, someone could place a phone or another small object on ELISA’s platform and ask her to deliver it to another person.

This approach offers useful functionality without requiring complex robotic arms.

The final design will depend on weight, stability, and available internal space.

⸻

🏗️ Hardware Architecture

Our preliminary architecture separates the robot into three main systems.

1. Mobility & Safety

Responsible for:

* Motor control
* Encoder feedback
* Battery monitoring
* Emergency stopping
* Low-level sensor processing
* Safe movement

An ESP32 or similar microcontroller is being considered.

2. Perception & Navigation

Responsible for:

* Camera processing
* LiDAR processing
* Mapping
* Localization
* Path planning
* Obstacle avoidance

A Raspberry Pi or comparable embedded computer is being evaluated.

3. AI & Interaction

Responsible for:

* Conversational intelligence
* Speech recognition
* Speech synthesis
* Memory
* Context interpretation
* Proactive behavior
* Task planning

We are considering a hybrid architecture combining local processing with external AI services.

Essential safety and navigation functions should remain operational without an internet connection.

⸻

🖨️ 3D Printing & Mechanical Design

The mechanical structure will be developed using custom 3D-printed components.

Our primary printer is a Bambu Lab H2D.

Design priorities include:

* Modular construction.
* Accessible electronics.
* Replaceable mechanical components.
* Lightweight structural design.
* Practical assembly and maintenance.
* Easy integration of future upgrades.

Where practical, printable design files will be shared with the community.

The exact CAD tools, materials, and mechanical design have not yet been finalized.

⸻

🧪 Development Roadmap

Phase 0 — Research & Concept Design

Status: In progress

* Define the project vision.
* Establish preliminary design goals.
* Create the public GitHub repository.
* Evaluate similar open-source robotics projects.
* Select the propulsion system.
* Finalize the initial hardware architecture.
* Establish a preliminary budget.

Phase 1 — Mobile Platform

* Design the chassis.
* Select motors and motor drivers.
* Integrate battery and power distribution.
* Implement basic movement.
* Test stability and floor compatibility.
* Implement essential safety functions.

Phase 2 — Autonomous Navigation

* Integrate navigation sensors.
* Create an indoor map.
* Implement localization.
* Implement autonomous route planning.
* Test obstacle avoidance.
* Implement recovery behavior.

Phase 3 — Dome & Interaction

* Design the rotating dome.
* Integrate the camera.
* Install programmable LEDs.
* Integrate microphones and speakers.
* Implement dome orientation control.

Phase 4 — Conversational AI

* Integrate speech recognition.
* Integrate speech synthesis.
* Implement natural conversations.
* Develop persistent memory.
* Add person recognition.
* Integrate relevant external information sources.

Phase 5 — Proactive Autonomy

* Develop a context-awareness system.
* Implement proactive suggestions.
* Introduce permission-based autonomous actions.
* Connect perception, memory, and reasoning.
* Test behavior in realistic household scenarios.

Phase 6 — Autonomous Charging

* Design the docking station.
* Implement docking localization.
* Develop final alignment.
* Integrate safe charging electronics.
* Test automatic charging and recovery.

Phase 7 — Optional Extensions

* Cargo platform or drawer.
* Additional sensors.
* Smart-home integration.
* Advanced interaction features.

The roadmap is flexible. Some development phases may overlap.

⸻

💰 Preliminary Budget

Our initial hardware budget target is approximately:

€900–€1,500

This is an early planning estimate, not a verified bill of materials.

The budget covers the main mechanical, electronic, sensing, computing, and power components.

It does not include development labor, recurring AI service costs, or every possible future upgrade.

A detailed bill of materials will be published as component selections are confirmed.

⸻

🔍 Open Engineering Challenges

We welcome technical feedback on several important design questions.

Mobility

What is the most practical drive system for a compact indoor robot weighing up to 15 kg?

Navigation

Which combination of sensors provides reliable indoor navigation without unnecessary cost or complexity?

Docking

What is the simplest reliable approach to automatic charging?

AI Architecture

How should local control, conversational AI, memory, and proactive decision-making be separated?

Safety

How can autonomous initiative be implemented while maintaining predictable and safe physical behavior?

Mechanical Design

How can we balance stability, modularity, internal space, and low weight?

These questions will be discussed through GitHub Issues as the project progresses.

⸻

🚀 Related Project — R2-D2 Build

Before starting the main ELISA-1 construction, we will assemble a separate R2-D2-inspired 3D-printing project.

This build will provide practical experience with:

* Multi-part 3D printing.
* Mechanical assembly.
* Dome construction.
* Electronics integration, where applicable.
* Finishing and detailing.

The R2-D2 build is a separate project and is not the technical foundation of ELISA-1.

However, lessons learned during construction may influence ELISA’s mechanical design.

We plan to document this build separately under La Bestia 3D.

⸻

🤝 Community & Collaboration

We welcome ideas, feedback, questions, and collaboration!

ELISA-1 is an independent maker project, and we believe open-source collaboration can make it better.

Whether you have experience with robotics, ROS 2, embedded electronics, 3D printing, computer vision, or artificial intelligence, your input is welcome.

You can contribute by:

* Opening an Issue with suggestions or questions.
* Sharing relevant technical experience.
* Proposing improvements.
* Reporting problems.
* Submitting Pull Requests as the project develops.

Constructive criticism and alternative approaches are encouraged.

Please keep discussions respectful, practical, and focused on the project.

⸻

📜 License

The repository is currently published under the MIT License.

Licensing for future hardware designs, CAD files, and third-party components will be reviewed as those materials are added.

⸻

👨‍🔧 About the Project

ELISA-1 is developed by La Bestia 3D, based in Alicante, Spain.

This is an independent hobby robotics project combining a passion for technology, artificial intelligence, engineering, and 3D printing.

We are starting with an idea, an ambitious set of goals, and the determination to learn along the way.

No commercial product or completed robot is being claimed at this stage.

Development progress, experiments, successes, and failures will be documented openly.

⸻

🤖 ELISA-1

Not just a robot that follows instructions.

A companion that observes, learns, reasons, and takes initiative.

The journey starts here.

La Bestia 3D — Spain 🇪🇸
