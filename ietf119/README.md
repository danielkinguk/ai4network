# ai4network
Applicability of AI in the Network

The AI4NET side meeting explores the multifaceted impact of AI in networks. Traditionally characterized by complex, monolithic infrastructures, networks are transitioning into agile, intelligent ecosystems. AI-driven technologies are becoming the linchpin for this transformation, offering unprecedented opportunities for enhancing network performance, optimizing resource allocation, ensuring security, and delivering superior user experiences.

-	Network performance optimization: AI can analyze network traffic patterns and identify areas where performance can be improved. This can be done by optimizing routing tables, adjusting bandwidth allocation, and identifying and resolving bottlenecks;
-	Network security: AI can detect and mitigate cyber threats, such as malware, phishing attacks, and denial-of-service attacks. AI can also be used to identify and protect vulnerable systems and devices;
-	Network automation: AI can be used to automate many of the tasks involved in managing and operating networks, such as provisioning new devices, configuring network settings, and responding to incidents. This can help to reduce costs and improve efficiency;
-	Network planning and forecasting: AI can analyze network data and trends to forecast future demand and plan for capacity upgrades. This can help to ensure that networks can meet users' needs without experiencing performance problems.

Overall, AI is a powerful tool that can be used to improve the performance, security, and efficiency of network resources and operations. As AI technology continues to develop, we can expect to see even more innovative and effective ways to use AI to benefit the development of the Internet.

We invite interested people to the side meeting to discuss requirements, use cases, and AI solutions to improve the network. Anyone is welcome to share their thoughts, including but not limited to, research work such as papers, demos, trial deployments, commercial implementation and existing deployments.

# IETF 118 Side Meeting
Meeting Time: WEDNESDAY 8 NOVEMBER 14:00 – 15:30 CET (13:00 – 14:30 GMT)
Meeting Location: Palmovka1/2

Remote Participation: https://ietf.webex.com/meet/ietfsidemeeting2

Etherpad: https://etherpad.wikimedia.org/p/ai4network-ietf118

Chairs: Weiqiang Cheng (chengweiqiang@chinamobile.com) and Daniel King (d.king@lancaster.ac.uk)

Session Materials: https://www.dropbox.com/scl/fi/tvbjllhhvua7043h7s8j9/ietf-118-ai4network.rar?rlkey=5758as7zg3zik53yv3ph3c69u&dl=0

### Agenda: 

#### 1. Data, AI and Cybersecurity - a possible cocktail?**
Presenter: Professor Marco, POLITO
     
Abstract: Modern Artificial Intelligence technologies, led by Deep Learning, have gained unprecedented momentum over the past decade. Following this wave of ``AI summer", the network research community has also embraced AI/ML algorithms to address many problems related to network operations, management and cybersecurity. In this talk I’ll present some of our recent results in applying AI-based solution to automatically process traffic traces and detect novel attacks, prevent cybersquatting attacks, support forensic investigations, and open new opportunities to protect users from possible abuses.

Slides: https://www.dropbox.com/scl/fi/tvbjllhhvua7043h7s8j9/ietf-118-ai4network.rar?rlkey=5758as7zg3zik53yv3ph3c69u&dl=0
 
#### 2. REDTE: Exploiting the Power of Reinforcement Learning for Fast Traffic Engineering in Wide Area Networks**
Presenter: Professor Dan Li, Tsinghua University
     
Abstract: Traffic bursts in Wide Area Networks (WANs) degrade user experience and increase network provider costs. Bursts usually happen in under a second, thus conventional burst mitigation methods all ignore the potential of Traffic Engineering (TE). However, our experiments indicate that, if the control loop latency of a TE system is sub-second, we can alleviate burst-induced congestion effectively using only TE. This is because TE-based methods can leverage network-wide tunnel-level information to make globally informed decisions (e.g., balancing traffic bursts among multiple paths). Our insight in reducing control loop latency is to let each router make local TE decisions, but this introduces the key challenge of minimizing performance loss compared to a centralized TE system. We design REDTE, a novel distributed TE system with a control loop latency of less than 100ms, while achieving performance comparable to a centralized TE system. REDTE’s innovation is the modeling of TE as a distributed multi-agent cooperative problem, and leverage the short inference time of machine learning to let each router make quick TE decisions solely based on local information. With a P4-capable switch platform, we implement real REDTE routers and deploy them on a real WAN testbed that spans six datacenters in six cities. Our evaluation reveals notable improvements compared to existing solutions: less than 100ms of control loop latency, a 20.0% reduction in maximum link utilization, and a 57.7% reduction in average queue length.
     
Slides: https://www.dropbox.com/scl/fi/tvbjllhhvua7043h7s8j9/ietf-118-ai4network.rar?rlkey=5758as7zg3zik53yv3ph3c69u&dl=0

#### 3. AI4ME: Network Challenges and Role of AI in Personalised Object Media at Scale**
Presenter: Rajiv Ramdhany, Senior R&D Engineer and Scientist, BBC
     
Abstract: The AI4ME project is building an infrastructure of object media experiences (personalised media) using edge computing resources to render customised real-time content to high-end audience devices. The project addresses the challenges of generating and delivering tailored object media by intelligently distributing the processing and data through the delivery network, making optimal use of AI-based resources in the cloud, and utilising edge-compute nodes to provide personalised media experiences to audiences across the globe.
     
Slides: https://www.dropbox.com/scl/fi/tvbjllhhvua7043h7s8j9/ietf-118-ai4network.rar?rlkey=5758as7zg3zik53yv3ph3c69u&dl=0

#### 4. AI Training Network Unique Requirements
Presenter: Gadi Singer , Traffic Management Network Architect at Broadcom Core Switch Group

Abstract: AI training clusters are evolving at an unprecedented pace, increasing in scale and bandwidth every few months. Innovation in the AI domain depends on training new, innovative AI models using large amounts of data.

The demand for huge amounts of data and large-scale GPU usage introduces new challenges to AI training networks. GPUs are an expensive resource, and ensuring that training GPUs are not idle and waiting for the network is essential for building an efficient AI training network.

In this presentation, I will discuss the unique requirements of AI training networks and how DNX network silicon architecture addresses those challenges.

Slides: https://www.dropbox.com/scl/fi/tvbjllhhvua7043h7s8j9/ietf-118-ai4network.rar?rlkey=5758as7zg3zik53yv3ph3c69u&dl=0
   
#### 5. Requirements of AI for Network & Practice in iBNG
Presenter: Weiqiang Cheng, China Mobile 

Abstract: AI large models being used in the network have become a focal point of interest for operators. This presentation will provide a brief overview of some of the requirements for AI in networks, particularly in the areas of AI for Network Operations, AI for Network Services, and AI for Network Security. Furthermore, we aim to illustrate how AI is utilized in the context of China Mobile's iBNG practice to enhance the performance, security, and value-added services in home broadband networks.

Slides: https://www.dropbox.com/scl/fi/tvbjllhhvua7043h7s8j9/ietf-118-ai4network.rar?rlkey=5758as7zg3zik53yv3ph3c69u&dl=0

