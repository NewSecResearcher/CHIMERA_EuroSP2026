Euro S\&P 2026



SoK: Layered Vulnerability Assessment and Orchestrated Testing in ROS and Robotic Systems



Abstract - Robots are rapidly being adopted in manufacturing, transportation, defense, and service domains, yet they continue to expose critical security risks such as exposed ROS services, insecure default credentials, injection-based attacks, etc. that broaden the attack surface. Recent real-world incidents have shown how adversaries can hijack motion controllers or spoof perception sensors such as LiDAR or other weaknesses within the ROS ecosystem to further amplify these threats. Compounding this challenge, security evaluation in robotics remains fragmented, with existing tools focusing on isolated layers of the software stack rather than providing system-wide insights. To map this landscape, we surveyed more than fifty research works, classifying vulnerabilities across hardware, middleware, network, AI-based, and application layers, and cataloged over a dozen open-source security tools that can be used for the security evaluation of robots. Our analysis highlight a core limitation that the existing tools provide limited cross-layer visibility and detect only localized faults, failing to capture multi-stage attack chains that adversaries exploit in practice.



To address these limitations, our work makes three key contributions:

(1) We provide a unified, systematic vulnerability taxonomy that categorizes threats across emerging and active areas like hardware, middleware, runtime, network, AI-based, etc.

(2) We introduce a layer-aligned testing architecture that maps ROS2’s system stack to practical adversarial phases like discovery, enumeration, injection, network analysis, forensics, etc.

(3) We propose CHIMERA, a novel orchestrated framework that chains open-source tools into reproducible, end-to-end robotic security assessments, enabling cross-layer attack emulation and thus expanding the analytical coverage.



By enabling structured cross-layer testing, CHIMERA provides a practical foundation for future automated, scalable, and secure-

by-design robotic security workflows.

Keywords—  robot security, ROS2, ROS1, SoK, vulnerability taxonomy, toolchain, security assessment, multi-layer attack analysis, open-source.

