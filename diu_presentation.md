---
marp: true
theme: balor
style: |
  :root {
    --color-gold: #d4b358;
    --color-teal: #00826a;
    --color-green: #1f8b4c;
    --color-dark-green: #0a3821;
    --color-black: #000000;
    --color-dark-bg: #1a1a1a;
    --color-darker-bg: #0f0f0f;
    --color-border: #d4b358;
    --color-text: #ffffff;
    --color-text-secondary: #cccccc;
  }
  section {
    background-color: var(--color-dark-bg);
    color: var(--color-text);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    border: 3px solid var(--color-border);
    margin: 0.5rem;
    padding: 3rem;
    line-height: 1.5;
    font-size: 18px;
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 80vh;
  }
  h1, h2, h3 {
    color: var(--color-gold);
    text-align: center;
    text-shadow: none;
    margin-bottom: 2rem;
    font-weight: 600;
  }
  h1 {
    font-size: 3.5rem;
    margin-bottom: 3rem;
    font-weight: 700;
  }
  h2 {
    font-size: 2.8rem;
    margin-bottom: 2.5rem;
    font-weight: 600;
  }
  h3 {
    font-size: 2.2rem;
    margin-bottom: 2rem;
    font-weight: 600;
  }
  p, li {
    font-size: 20px;
    margin-bottom: 1rem;
    color: var(--color-text);
    line-height: 1.6;
  }
  section.title {
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: linear-gradient(135deg, var(--color-darker-bg) 0%, var(--color-dark-bg) 100%);
  }
  img[alt~="logo"] {
    width: 400px;
    margin-bottom: 3rem;
    border: 2px solid var(--color-gold);
    border-radius: 8px;
  }
  strong, b {
    color: var(--color-gold) !important;
    font-weight: 600 !important;
    font-size: 1.1em;
  }
  .highlight {
    color: var(--color-gold);
    font-weight: 600;
    font-size: 1.3em;
  }
  .two-column {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
    margin: 2rem 0;
  }
  .three-column {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 2rem;
    margin: 2rem 0;
  }
  .card {
    border: 2px solid var(--color-gold);
    border-radius: 8px;
    padding: 2rem;
    margin: 1.5rem 0;
    background: rgba(212, 179, 88, 0.08);
    box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    font-size: 18px;
  }
  .large-card {
    border: 2px solid var(--color-gold);
    border-radius: 8px;
    padding: 3rem;
    margin: 2rem 0;
    background: rgba(212, 179, 88, 0.08);
    box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    font-size: 22px;
    text-align: center;
  }
  .pitch-text {
    font-size: 24px;
    line-height: 1.5;
    text-align: center;
    margin: 2rem 0;
  }
  .pitch-highlight {
    font-size: 28px;
    color: var(--color-gold);
    font-weight: 600;
    text-align: center;
    margin: 2rem 0;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    margin: 2rem 0;
    background: rgba(0,0,0,0.3);
    border-radius: 8px;
    overflow: hidden;
    font-size: 16px;
    border: 2px solid var(--color-gold);
  }
  th, td {
    border: 1px solid var(--color-gold);
    padding: 1rem;
    text-align: left;
    vertical-align: top;
  }
  th {
    background: var(--color-gold);
    color: var(--color-dark-bg);
    font-weight: 600;
    font-size: 1.1em;
  }
  td {
    color: var(--color-text);
  }
  .tech-stack {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.5rem;
    margin: 2rem 0;
  }
  .tech-item {
    border: 2px solid var(--color-gold);
    border-radius: 6px;
    padding: 1.5rem;
    text-align: center;
    background: rgba(212, 179, 88, 0.08);
    color: var(--color-text);
    font-size: 16px;
  }
  .flow-diagram {
    display: grid;
    grid-template-columns: 1fr auto 1fr;
    gap: 2rem;
    align-items: center;
    margin: 3rem 0;
  }
  .flow-step {
    border: 2px solid var(--color-gold);
    border-radius: 8px;
    padding: 2rem;
    text-align: center;
    background: rgba(212, 179, 88, 0.08);
    color: var(--color-text);
    font-size: 16px;
  }
  .flow-arrow {
    color: var(--color-gold);
    font-size: 2rem;
    text-align: center;
    font-weight: bold;
  }
  ul {
    margin: 1.5rem 0;
    padding-left: 2rem;
  }
  li {
    margin-bottom: 0.8rem;
    color: var(--color-text);
    font-size: 18px;
  }
  em, i {
    color: var(--color-text-secondary);
    font-style: italic;
  }
  .compact {
    margin: 1rem 0;
    color: var(--color-text-secondary);
    font-size: 1em;
  }
  .small-text {
    font-size: 16px;
  }
  .extra-small {
    font-size: 14px;
  }
  .section-divider {
    height: 2px;
    background: linear-gradient(90deg, transparent, var(--color-gold), transparent);
    margin: 3rem 0;
  }

---

<!-- _class: title -->

![logo](balor_defense.png)

# DIU Dual-Use University Accelerator Challenge
## Balor Defense Systems

**Revolutionizing Defense Technology Through Dual-Use Innovation**

---

<!-- _class: title -->

<!-- This slide is intentionally left blank for pacing or transitions. -->

---

## Who We Are

<div class="pitch-text">
We are a **pre-revenue company** hoping to break into the defense field with multiple projects cultivated by **Purdue University students**
</div>

<div class="two-column">
<div class="card">
**Cian:** Computer Engineering: Founder of the Purdue National Defense Society, DCTC cohort 1, founder of Balor
</div>
<div class="card">
**Aditya:** Aerospace Engineering: Lead Engineer of the NDS CUAS team, Cofounder of Balor, Systems Engineer intern at Leonardo DRS (CUAS and Tank APS), hypersonic research for Stratolaunch
</div>
</div>

<div class="two-column">
<div class="card">
**Michael:** Computer Engineer: Automation intern at Nucor, CV expert, Targeting lead for NDS CUAS
</div>
<div class="card">
**Zach:** Computer Science: Lead of Cybersecurity team, Sandia Boy Wonder, Software Engineer intern at Northrop, Security Researcher
</div>
</div>

---

## Who We Are

<div class="large-card">
**Company Description:** CIAN WRITES. Unfortunately, they recommend talking about how new the company is, what you can produce now (very little), and what you plan to produce (a lot)
</div>

<div class="two-column">
<div class="card">
**Michael Lamiman**
Honors Computer Engineering
Automation intern at Nucor, CV expert, Targeting lead for NDS CUAS
</div>
<div class="card">
**Zachary Kirkeby**
Computer Science
Software Engineer Intern at Northrop Grumman, Security and RF expert, Cybersecurity Lead for NDS
</div>
</div>

---

## DOD Mission Needs

<div class="pitch-highlight">Deepen our Understanding and Awareness of Unmanned Systems Trends and Threat</div>

<div class="pitch-text">
How can we gain a greater understanding of unmanned systems and their deployment, threats, and use cases?
</div>

<div class="pitch-highlight">Defend Against Unmanned Systems Threats to U.S. Interests</div>

<div class="pitch-text">
How can we improve our active and passive defenses by clarifying, streamlining, and delegating responses?
</div>

<div class="card">
We focus on tackling these specific DOD Mission Needs

**Note:** Sourced from DOD Strategy Fact Sheet on Countering Unmanned Systems
</div>

---

## Executive Summary

<div class="large-card">
A two part system combining a full band Radio Frequency Scanner and a Turret Mounted CV system, integrated with an Edge AI and networked with short range communications
</div>

<div class="pitch-text">
This system is man portable, and can be deployed by individual personnel on the battlefield or in the civilian world, and immediately begin collecting data on the UAS systems in the area
</div>

<div class="card">
**The Process:**
- Radio Frequency Scanners perform initial detection, and determines target direction, heading, and collects communication data
- Computer Vision System then points at, and collects in-depth visual data on the target
- Edge AI uses the collected data to recommend individual system response, and communicate with other units to create a cohesive, live view of the operating space
</div>

---

## Computer Vision - Core Functionality in CUAS

<div class="pitch-highlight">CV's Role in Integrated Drone Defense</div>

<div class="pitch-text">
Computer Vision serves as the intelligent core of the proposed Counter-UAS (CUAS) system, transforming raw sensor data into actionable intelligence for threat assessment and response.
</div>

<div class="two-column">
<div class="card">
**Input:** Live video feed from a turret-mounted camera, directed by RF scanner data (target direction, velocity, direction of travel).

**Objective:** Rapid, accurate, and autonomous identification, tracking, and characterization of airborne targets to enable effective defensive measures.
</div>
<div class="card">
**Integration:** Seamlessly integrates with RF detection for initial cueing and subsequent weapon system recommendations.

**Output:** Real-time data streams including target classification, threat assessment, tracking parameters, and recommended interdiction strategies.
</div>
</div>

---

## Computer Vision - Target Identification & Tracking

<div class="pitch-highlight">Precision Detection and Classification</div>

<div class="pitch-text">
The CV model performs multi-class classification and robust tracking to differentiate legitimate airborne objects from potential threats, ensuring minimal false positives.
</div>

<div class="two-column">
<div class="card">
**Primary Identification:**
- **UAV:** Classifies various system types (quadcopters, fixed-wing, custom builds)
- **Non-UAV:** Identifies common benign airborne objects (birds, civilian aircraft, balloons, debris)
</div>
<div class="card">
**Tracking Capabilities:**
- **Persistent Tracking:** Maintains lock on detected targets despite challenging environmental conditions
- **Kinetic State Estimation:** Determines precise real-time position, velocity, and acceleration vectors
- **Trajectory Prediction:** Predicts future path of the target based on observed movement patterns
</div>
</div>

<div class="card">
**Technology Foundation:**
- Utilizes advanced deep learning architectures (e.g., CNNs, Transformers) trained on diverse datasets
- Employs object detection (e.g., YOLO, Faster R-CNN) and multi-object tracking (e.g., DeepSORT) algorithms
- Leverages edge computing for low-latency processing directly on or near the turret
</div>

---

## Full Band Radio Frequency Scanner

<div class="large-card">
Baseline noise exists everywhere across a range of channels. Monitoring provides a baseline of "typical" noise
</div>

<div class="pitch-text">
Increased behavior can be correlated to movements, deployments, etc
</div>

<div class="card">
Drones and surveillance tech operate on a range of bands, Mil Comms operate on a range, as do civilian technologies. Analysis of the bands and the activity can provide insight to actions about to occur, or ongoing ops
</div>

<div class="pitch-text">
Pattern of Life analysis, drone behaviors/locations, unauthorized/anomalous transmissions
</div>

---

## Full Band Radio Frequency Scanner

<div class="pitch-highlight">Beamforming and triangulation techniques</div>

<div class="pitch-text">
Can handle trajectory/velocity with specialized antenna clusters
</div>

<div class="card">
**TALK ABOUT COMMON COMMUNICATION TYPES AND HOW WE CAN DETECT THEM (i.e. burst communications, encrypted, etc.)**
</div>

<div class="tech-stack">
<div class="tech-item">
**Continuous** - constant signal, easiest to capture
</div>
<div class="tech-item">
**Burst:** sporadic floods of signal
</div>
<div class="tech-item">
**Frequency hopping:** rapid changes in bands
</div>
<div class="tech-item">
**Spreads:** divided over a range of bands
</div>
<div class="tech-item">
**Encrypted:** an above method using RSA, AES, etc
</div>
</div>

<div class="pitch-highlight">Hopping, encrypted, and burst are hallmarks of military activity</div>

---

## Edge AI: Intelligent Fusion for CUAS

<div class="large-card">
**Key Message:** Our Edge AI system provides robust, end-to-end pipeline for multi-modal analysis by intelligently integrating data from RF scanners and turret-mounted Computer Vision (CV) cameras, enabling precise target identification, real-time threat assessment, and coordinated response for Counter-UAS (CUAS) operations.
</div>

<div class="two-column">
<div class="card">
**Radio Frequency (RF) Analysis & AI-Enhanced Intelligence:**

Initial Detection: RF scanners detect targets, determining direction, heading, and collecting communication data, providing comprehensive dynamic coverage of the airspace.

AI Enhancements: Edge AI actively processes RF data for Trend Analysis, Noise Injection & Spoofing Detection, and Discrete Pattern Recognition to provide early warning and precise cues as well as aiding in establishing a pattern of life for observed entities.
</div>
<div class="card">
**Computer Vision (CV) Analysis & Detailed Visual Assessment:**

Guided Precision: RF data precisely points the turret-mounted CV system towards the target.

Visual Intelligence: Edge AI's CV models analyze live video for target identification (e.g., drone type, bird), real-time tracking (position, velocity), and trajectory prediction.
</div>
</div>

---

## Edge AI Integration, Recommendation & Networked Operations

<div class="flow-diagram">
<div class="flow-step">
**Multi-Modal Fusion:** Edge AI fuses intelligence from both RF (e.g., trend, spoofing, patterns) and CV (e.g., visual ID, tracking, behavior) for a comprehensive understanding.
</div>
<div class="flow-arrow">→</div>
<div class="flow-step">
**Actionable Insights:** Determines threat level (e.g., approaching high, leaving low) and recommends suitable weapon responses and actions (e.g., kinetic, laser, missile).
</div>
</div>

<div class="card">
**Situational Awareness:** Leverages short-range communications to network with other units, sharing processed data for a cohesive, live operational picture.
</div>

<div class="pitch-highlight">Comprehensive RF and CV Analysis on the Edge</div>

---

## Usage Example - Military

<div class="card">
<table>
<tr>
<th>Scenario</th>
<th>Response</th>
</tr>
<tr>
<td>Unarmed, slow, unencrypted data</td>
<td>Directed Energy/Electronic Warfare</td>
</tr>
<tr>
<td>Quick, attack trajectory encrypted comms</td>
<td>Kinetic Destroy</td>
</tr>
<tr>
<td>Armed, advanced, faraway</td>
<td>Guided Missile</td>
</tr>
</table>
</div>

<div class="two-column">
<div class="card">
**Collected Information**
</div>
<div class="card">
**Response Recommendation**
</div>
</div>

---

## Usage Example - Civilian

<div class="card">
<table>
<tr>
<th>Scenario</th>
<th>Response</th>
</tr>
<tr>
<td>Unencrypted data, low UAV count, non-hostile trajectory near public events (i.e. stadium)</td>
<td>No response</td>
</tr>
<tr>
<td>Suspicious noise on unusual frequencies, coordinated movements near high value targets (i.e. political rally)</td>
<td>Notify response personnel, recommend increased alertness level</td>
</tr>
</table>
</div>

---

## How we meet DOD Needs

<div class="pitch-highlight">Deepen our Understanding and Awareness of Unmanned Systems Trends and Threat</div>

<div class="pitch-text">
RF Scanners and CV can collect a wealth of relevant information:
</div>

<div class="card">
- **Deployment methods and trends:** How are these systems fielded?
- **Patterns between communications and attacks:** What radio signals are precursors to attacks?
- **Location specific data:** Are certain frequency bands being used in one area but not another? Are certain locations more prone to recon or kamikaze systems?
</div>

<div class="pitch-highlight">Defend Against Unmanned Systems Threats to U.S. Interests</div>

<div class="pitch-text">
How can we improve our active and passive defenses by clarifying, streamlining, and delegating responses?
</div>

<div class="card">
- **Clarification:** Based on data, more effective rules can be established
- **Streamlining:** Threat categorization and response recommendation can be carried out by computers instead of human personnel, speeding up response time
- **Delegation:** The system provides personnel with all the relevant information, delegating all but the final decision away from personnel.
</div>

<div class="pitch-text">
We focus on tackling these specific DOD Mission Needs
</div>

---

## Prototyping Feasibility

<div class="three-column">
<div class="card">
The primary technologies (Radio Frequency/Computer Vision) are well developed and field tested with a wealth of existing options on scanners and cameras to choose from
</div>
<div class="card">
Primary development will occur in gathering existing data sets and training the Edge AI, meaning large quantity of work can be done without equipment
</div>
<div class="card">
Components can be studied without purchase, allowing for rapid restructuring. Physical devices are only needed for system integration and testing.
</div>
</div>

<div class="large-card">
Usage of entirely off-the-shelf components means straightforward production, no need for advanced manufacturing facilities, allowing for easy scaling
</div>

---

## Feedback Adaptability

<div class="two-column">
<div class="card">
The usage of an Edge AI allows for different data collection methods to easily be integrated
</div>
<div class="card">
On DIU recommendation, technologies like radar, acoustic detection, etc. can easily be integrated by changing the training data and format for the edge AI system
</div>
</div>

<div class="large-card">
**ADD MORE, THIS IS A REQUIRED CAPABILITY (MICHAEL AND ZACH)**
</div>

<div class="tech-stack">
<div class="tech-item">
Edge AI can identify discrete patterns, identifying subtle hops and jamming techniques
</div>
<div class="tech-item">
Edge ai optimizes targeting, classification, and anomaly detection
</div>
</div>

---

## Thank You

![logo](balor_defense.png)

### Questions & Discussion

<div class="card">
**Contact Information:**
- Email: [email]
- Phone: [phone]
- Website: [website]
</div>

<div class="card">
**Follow-up:** We're excited to discuss partnership opportunities and next steps!
</div> 