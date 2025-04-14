# README

Created by: Jackson Bayer
Created time: April 13, 2025 2:13 PM
Category: Informational

# Netrunnr

A companion used by the GM and player in tandem to make netrunning more seamless and enjoyable for both parties. Rules on how netrunning functions are subject to change due to making netrunning make more sense on a desktop environment. Some terms will change, as well as many aspects of how netrunning is performed, but the difficulty RNG elements that make netrunning fun will stay at its core. This way, it requires more skill from the player.

---

## The Net Architect Creator

Every server/personal computer will have their own set of default files. It is up to the GM to add any additional folders, security measures, and other custom goodies that they may use to make the server more or less difficult to break into.

### How does it work?

- First, a menu pops up asking if this is a server or a personal computer:
    - **Servers** are large databases that you first fight through for control of the net architecture.
    - **Personal computers** are detectable after you have achieved Root access to the server (using scan).
- It will then auto-generate the server/personal computer with all of its files.
- It will prompt to create users, at least one with Root Access.
- After the users have been created, it is now time to make security protocols. This can take the form of the following:
    - ICE / Black ICE
    - Daemons
    - Another Netrunner with:
        - Cyberdeck
        - Programs
        - HP
    - **ICE Reaction Profiles**: Assign behavior templates to ICE, such as "Aggressive," "Stealthy," or "Targeted," to diversify system defenses.
- It will then ask the creator if you want to make custom file locations to hide different documents within public or hidden files (designated by a “.” before the name, will be hidden until the user is granted Root access).
    - **Honeyfiles**: Option to add fake files designed to lure netrunners; accessing them triggers alerts or activates ICE.
    - **File and Folder Security Levels**: Assign security levels (Low, Medium, High) to files and folders, affecting access difficulty and required decryption efforts.
    - **Encrypted Drives or Partitions**: Designate certain areas as encrypted, requiring separate decryption keys or methods to access.
    - **Log File System**: Implement logging mechanisms that track netrunner activities; failure to manage logs can lead to detection.
    - **Offline Storage Devices**: Include data stored on external devices that must be retrieved in meatspace.
    - **NPC Digital Assistants / AI Custodians**: Introduce virtual entities that interact with netrunners, requiring social engineering or technical bypassing.
    - **Manual Override Nodes**: Create nodes that necessitate real-world physical actions or coordination with team members in meat space to access.
    - **Node Dependency Chains**: Establish dependencies between nodes, requiring specific access sequences to progress through the network.
- Additional features to enhance the network architecture:
    - **Timed Scripts / Auto-Triggers**: Implement timers that activate specific events (e.g., ICE deployment, data wipes) upon certain triggers or after set durations.
    - **Redundant Nodes / Dead Ends**: Include decoy nodes that mimic legitimate structures but serve no functional purpose, adding complexity to network navigation.
    - **Environment Tags**: Label systems with tags like "Corporate," "Criminal," or "Public Access," influencing default security configurations and file structures.
    - **Network Type Selector**: Specify network types (e.g., LAN, WAN, Air-Gapped), affecting available commands and access methods.
    - **Security Patches / Update Cycles**: Simulate system updates that can alter security measures over time, impacting netrunner strategies.
    - **System Clock Manipulation**: Allow netrunners to alter system time, potentially affecting timers, logs, and scheduled events.

---

## Net Runner Companion

A terminal-based tool designed for players to engage in netrunning within Cyberpunk RED, adapted for a desktop environment. This companion emphasizes player skill, strategic decision-making, and immersive hacking experiences, while maintaining the core elements that make netrunning enjoyable.

## How does it work?

- Upon launching the program, the player is presented with a terminal interface simulating a cyberdeck environment.
- The interface allows the player to:
    - **Scan** for accessible networks and devices.
    - **Jack in** to detected networks, initiating a netrun session.
    - **Navigate** through network nodes, each representing different system components.
    - **Execute programs** loaded onto their cyberdeck to interact with the network.
    - **Monitor system responses**, including ICE activation and trace attempts.
- The player's actions and decisions are subject to:
    - **Difficulty checks**, incorporating RNG elements to simulate hacking challenges.
    - **Time constraints**, adding urgency to decision-making.
    - **GM interventions**, allowing the Game Master to influence events in real-time.

## Features

- **Custom Program Creation**: Players can develop unique programs to assist in netrunning, subject to GM approval.
- **Program Management**: Load, unload, and manage programs on the cyberdeck, considering memory constraints and strategic needs.
- **Real-Time Synchronization**: Seamless integration with the GM's Net Architect Creator, ensuring consistent network states.
- **Logging and Footprint Tracking**: Monitor actions taken during a netrun, with potential consequences for leaving traces.
- **Dynamic Network Interaction**: Engage with various network elements, including:
    - **ICE / Black ICE**: Encounter and counteract security programs designed to hinder intruders.
    - **Daemons**: Interact with autonomous programs that manage network functions.
    - **Hidden Files and Nodes**: Discover concealed elements within the network, requiring advanced scanning and decryption techniques.
    - **Honeyfiles**: Be wary of decoy files intended to trap or mislead intruders.
    - **Encrypted Partitions**: Decrypt secured areas to access valuable data.
    - **System Logs**: Analyze and manipulate logs to cover tracks or gather intelligence.
    - **AI Custodians**: Navigate interactions with virtual entities overseeing network operations.
    - **Manual Override Nodes**: Coordinate with team members for physical interactions affecting the network.
    - **Node Dependency Chains**: Understand and exploit relationships between network nodes to progress effectively.

## Gameplay Mechanics

- **Interface Actions**: Utilize a set of actions to interact with the network, such as:
    - **Pathfinder**: Map out the network structure.
    - **Backdoor**: Bypass security measures.
    - **Control**: Take command of networked devices.
    - **Slide**: Evade detection or ICE.
    - **Zap**: Attack or disable ICE and other threats.
- **Program Types**: Equip the cyberdeck with various program categories, including:
    - **Attackers**: Offensive programs to combat ICE and enemy netrunners.
    - **Boosters**: Enhance specific actions or provide temporary advantages.
    - **Defenders**: Protect the netrunner from damage or detection.
    - **Utilities**: Offer miscellaneous functions, such as data analysis or system manipulation.
- **Program Slot Management**: Strategically allocate limited program slots on the cyberdeck to balance capabilities.
- **Footprint Score**: Accumulate a score based on actions taken, influencing the likelihood of detection and countermeasures.
- **Trace and Countermeasures**: Risk triggering system defenses if the footprint score becomes too high, leading to potential consequences.

## Integration with GM Tools

- **Network Synchronization**: Maintain real-time updates between the player's netrunning session and the GM's network architecture.
- **GM Notifications**: Alert the GM to significant player actions, such as accessing sensitive files or triggering security measures.
- **Custom Content Approval**: Facilitate the GM's review and approval of player-created programs and modifications.
- **Session Logging**: Record netrunning sessions for post-game analysis or narrative development.

---

## Net Architecture Monitoring System (NAMS)

A terminal-based interface empowering the GM to oversee, manipulate, and narrate netrunning sessions in real-time. NAMS provides comprehensive control over network architectures, security protocols, and player interactions, ensuring a dynamic and engaging gameplay experience.

## Core Functions

### 1. **Real-Time Network Visualization**

- Display the current state of the network architecture, including:
    - Node hierarchy and connections
    - Active security measures (e.g., ICE, Daemons)
    - Netrunner's location and actions within the network

### 2. **Security Protocol Management**

- Monitor and control security elements:
    - Activate or deactivate ICE and Daemons
    - Adjust security levels of files and nodes
    - Implement timed triggers and auto-responses

### 3. **Player Interaction Oversight**

- Receive notifications of netrunner actions:
    - Access attempts on files or nodes
    - Program executions
    - Movement within the network
- Approve or deny custom program usage
- Introduce dynamic events or challenges

### 4. **Data Logging and Session Recording**

- Maintain logs of:
    - Netrunner actions and outcomes
    - Security responses and changes
    - GM interventions and decisions
- Export session data for review or narrative development

---

## Advanced Features

### 5. **Dynamic Network Modification**

- Alter network architecture during a session:
    - Add or remove nodes
    - Change node dependencies
    - Introduce new security measures or vulnerabilities

### 6. **Environmental Simulation**

- Assign environment tags to networks (e.g., Corporate, Criminal)
- Simulate effects of environmental factors on network behavior and security

### 7. **Trace and Alert Systems**

- Monitor netrunner footprint scores
- Configure thresholds for triggering alerts or countermeasures
- Simulate trace progress and consequences

### 8. **Integration with Net Runner Companion**

- Synchronize network state with the player's interface
- Facilitate seamless communication and data exchange
- Ensure consistency between GM and player perspectives

---

## User Interface Components

### 9. **Dashboard Overview**

- Summarize key information:
    - Active netrunners and their statuses
    - Security alerts and system integrity
    - Recent actions and events

### 10. **Node Detail Panels**

- Provide in-depth information on individual nodes:
    - Security settings and access logs
    - Connected devices and files
    - Active programs and processes

### 11. **Command Console**

- Execute commands to:
    - Modify network structures
    - Control security elements
    - Communicate with players

### 12. **Notification Center**

- Display real-time alerts and messages
- Track pending approvals and decisions
