ai4network (AI4NET) - IETF 120 Side Meeting
An IETF side meeting for the discussion of AI and its applicability to the network.

Meeting Time: Tuesday 23 JULY 13:00 – 15:30 (PST) Meeting Location: Prince of Wales/Oxford
Remote Participation: https://ietf.webex.com/meet/ietfsidemeeting2
Etherpad: https://etherpad.wikimedia.org/p/ai4network-ietf120
Chairs: Daniel King (d.king@lancaster.ac.uk) and Cheng Li (c.l@huawei.com)

Agenda: https://github.com/danielkinguk/ai4network/blob/main/ietf120/agenda.md
Introduction and intent. Time: 13:00 to 13:05

All slides are availible via: https://drive.google.com/drive/folders/1MLbLCv_oPnLrwnNo3BgUkKub3J-qxbVD?usp=sharing

1. Research Challenges in Coupling Artificial Intelligence and Network Management
Time 13:05 to 13:30 Presenter: Jerome François - University of Luxembourg and Inria

- Creation of a wiki to track IETF work that relates to AI/ML
- Creating meta data for training data sets that might be used for related IETF work
- Tracking data sets that have been used for IETF technologies and related technology

2. An Architecture for a Network Anomaly Detection Framework
Time: 13:30 to 13:55 Presenter: Thomas Graf – Swisscom (Schweiz) AG

[Mike]What is the AI excatly in the presentation? It looks like data collection and processing?
[Thomas] Network are deterministic. Customers somewhat. We are using unsipervised machine learning for profiling and symbolic artificial intelligence based on network modelling for detecting outliers. Already had a PoC for 18 months in production network enviroment. 

[Alexander Clemm] TBD Delineation from Incident Management Systems (and TTS) - could you not consider an anomaly an incident and apply those existing types of system instead - what is different?
[Alexander Clemm] Why you put the data in the YANG Model? instead of OSS system? (for annotation data / data added by a user or an application) (Due to time limitation, move to the chat discussion)


3. ICSS: Intent-Based Cloud Security System with Interface to Network Security Functions (I2NSF
Time: 13:55 to 14:20 Presenter: Paul (Jaehoon) Jeong - SKKU

[From the room]What is new here? What is the advantage of this solution? 
[Jeong] New YANG Model design, high level and low level YANG models. This is a automatic closed-loop solution.
[From the room] I failed to see where is AI in the solution, it seems this is a typical solution.
[Jeong] We collect the data using new YANG model, with the data, we use some automatic algorithms to solve the problem, using some AI/ML to processing the data(TB checked)
[Jeong]The main goal is to use the YANG model data, and use it to provide some intelligent functions.


4. Leveraging Large Language Models for Enhanced Network Security: A Framework
Time: 14:20 to 14:45 Presentor: Juan Deng
[Daniel KING]What work can we do in the IETF to help your implementation? we can discuss this in the last topic.

5. The role of AI in the control and management of Transport Networks
Time: 14:45 - 15:10 Presenter: Oscar Dios Gonzalez - Telefonica
[Oscar] Introduce the benefits of using AI in transport network, including use cases, etc.

6. Open Discussion a) Utilising AI in Network Operations b) How can machine learning improve network operations? c) What work might there be for the IETF?
Time: 15:10 - 15:30 Presenter: Daniel King (Lancaster University) and Cheng Li (Huawei)
[some interesting pointers for possible use of AI:
    1. Microsoft presented three use cases for AI in networks (ingress selection, egress traffic routing, and incident reporting) in the ANRW session today
    2. Frameworks to understand the behaviour of AI techniques in possibly central network functions, such as using AI (reinforcement learning) in congestion control. Here, Parisis et al published at Infocom 2024 such framework.]

In summary, the meeting focused on the applicability of AI to networking, specifically in the context of security, and discussed challenges, ongoing work, and the role of the IETF in facilitating its use.

- The meeting is focused on the applicability of AI to networking, with a central focus on security.
- The goal is to identify the role of the IETF in using AI for networking and to determine any gaps or challenges.
- There is a need for more diverse and high-quality data sets for AI applications in networking.
- Security and optimization are key areas where AI can be applied, but there are challenges to address.
- Network anomaly detection system automates network monitoring and detects anomalies in real-time.
