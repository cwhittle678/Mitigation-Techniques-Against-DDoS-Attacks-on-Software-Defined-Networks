The final Master's Thesis document can be found at the following URL in the University of Massachusetts' library: 

[Master's Thesis - C.S.Whittle](https://umassd.primo.exlibrisgroup.com/discovery/delivery/01MA_DM_INST:umassd_library/12123188050001301?lang=en&viewerServiceCode=AlmaViewer)


ABSTRACT:

With the rise of devices integrated with computer networks, coined as the Internet-of-Things (IoT), it was only a matter of time before cyber criminals found new ways to cripple critical communication-based infrastructures. A common type of attack that has been around for years, adopting itself for vast variances, is the infamous denial-of-service (DoS) attack. These attacks strategically halt network services by injecting heavy traffic, directly stalling the availability of a system for legitimate users. This can cause companies to lose millions of dollars in revenue and even open the system up to new vulnerabilities. Due to the criticality of a rapid and effective upgrade to security, many companies and engineers have designed systems to detect and/or mitigate possible incoming attacks. The introduction of virtualized and programmable networks, named software defined networks (SDNs), advances modern communication applications with performance flexibility while enhancing security-based controls. Many solutions focused on keeping track of the potential damage caused by each individual IP (packet filtering approaches). As cyber criminals evolved, they looked to become sneakier and harder to detect. Expanding upon the attack format of DoS attacks, the distributed denial-of-service (DDoS) attack emerged. This format utilized a coordinated army of interconnected devices to disguise the attack as random/normal traffic.

This work investigates mitigation techniques against DDoS attacks on SDNs. An SDN is setup with Mininet, a Linux-based network emulator, to create a virtual internet testbed for experiments. An arms race iterates on the SDN testbed between offense launching botnet DDoS attacks with progressive sophistications, and defense deploying SDN controls with emerging technologies from other faucets of cyber engineering. The investigation focuses on the TCP SYN flood attack that exploits vulnerabilities in the three-way TCP handshake protocol to lock up a host from serving new users. The Defensive strategy starts with a common packet filtering-based design from the literature to mitigate attacks. Utilizing machine learning and smart algorithms, SDNs actively monitors all possible traffic as a collective dataset to detect DDoS attacks in real time. A constant upgrade to stronger defenses is necessary, as cyber/network security is an ongoing front where attackers always have the element of surprise.

The defense further invests on entropy methods to improve early detection of DDoS attacks within the testbed environment. Entropy allows SDNs to learn the expected normal traffic patterns for a network as a whole using real time mathematical calculations, so that the SDN controllers can sense the distributed attack vectors building up before they overwhelm the network. The work reveals the vulnerabilities of SDNs to stealthy DDoS attacks and demonstrates the effectiveness of deploying entropy in SDN controllers for detection and mitigation purposes. Future work includes provisions to use these entropy detection methods as part of a larger system to redirect traffic and protect networks dynamically in real time.
