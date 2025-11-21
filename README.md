Euro S\&P 2026

Title - SoK: Layered Vulnerability Assessment and Orchestrated Testing in Robotic Systems



Abstract - 
Robots are rapidly being deployed across manufacturing, transportation, defense, and service domains, yet they continue to expose critical security risks. Issues such as exposed ROS services, insecure default credentials, and injection-based attacks significantly expand the attack surface. Recent real-world incidents have demonstrated how adversaries can hijack motion controllers or spoof perception sensors such as LiDAR, revealing deeper weaknesses within the ROS ecosystem. Despite these growing threats, the security evaluation in robotics remains fragmented, as existing tools often focus on individual layers of the software stack and provide limited system-wide visibility. To better understand this landscape, we surveyed over fifty research works and examined more than a dozen open-source security tools. Our analysis shows that most tools detect only localized faults and lack the cross-layer perspective needed to capture the multi-stage attack chains that occur in practice.

To address these limitations, our work makes three key contributions.
(1) We developed a unified and systematized vulnerability taxonomy, covering hardware, middleware, runtime, network, AI-based, and other categories, along with an analysis of the open-source security tools available for robotic systems.
(2) We introduced a layer-aligned testing architecture that maps ROS2’s operational stack to practical adversarial phases such as discovery, injection, network analysis, and forensics, providing a unified orchestration workflow with standardized data hand-offs and controlled cross-layer attack propagation.
(3) We conducted scenario-based evaluation and empirical analysis using CHIMERA, demonstrating its practicality through representative attack conditions, cross-layer traceability, and measurable insights into configuration weaknesses and robotic system resilience.

By enabling structured cross-layer testing, CHIMERA offers a practical foundation for automated, scalable, and secure-by-design robotic security workflows. We also make all evaluation artifacts publicly available on our GitHub repository \url{https://github.com/NewSecResearcher/CHIMERA_EuroSP2026} to support reproducibility and encourage further community-driven extensions.

Keywords—  Robot security, security assessment, ROS, SoK, vulnerability taxonomy, orchestrated testing, open-source.

