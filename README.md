# VPN for Privacy and Security 
A hands-on project to set up and verify a Virtual Private Network (VPN) connection using the ProtonVPN free tier.

## Project Overview
The objective of this task was to gain practical experience with VPNs, a critical tool for modern digital privacy. This project involved setting up a free VPN service, establishing a secure connection to a remote server in the United States, and verifying that the VPN was successfully encrypting traffic and masking my IP address. The exercise provides a foundational understanding of how VPNs protect user data from surveillance and enhance online anonymity.

## Setup and Verification Process
* **Account & Installation:** Signed up for a free ProtonVPN account and installed the native Windows client.
* **Secure Connection:** Used the "Quick Connect" feature to automatically establish an encrypted tunnel to the fastest available free server.
* **IP Address Verification:** Confirmed that the VPN was active by observing the new public IP address (**87.249.134.135**) assigned by the VPN server, which effectively masked my real IP and location.
* **Status Confirmation:** The application dashboard confirmed a **"Protected"** status, indicating that all traffic was being routed through a secure tunnel using the modern **WireGuard** protocol.

## Key Concepts & Learnings
* **Encryption in Transit:** I learned that a VPN's primary security feature is its ability to encrypt all data leaving my device. This makes my online activity unreadable to my Internet Service Provider (ISP) or anyone monitoring the local network.
* **IP Masking and Geolocation:** This exercise clearly demonstrated how a VPN replaces a user's real IP address with that of the VPN server. My location appeared to be in the United States, which is the mechanism used to protect privacy and bypass geographic content restrictions.
* **Tunneling Protocols (The "How"):** I saw that VPNs rely on established tunneling protocols to function. My connection used **WireGuard**, a fast and secure modern protocol, which handles the creation of the private tunnel over the public internet.
* **Privacy as a Proactive Choice:** Using a VPN is a conscious step toward taking control of one's digital privacy, rather than passively allowing data to be monitored by third parties.

## Files in This Repository
* **`README.md`**: This detailed project report.
* **`setup_report.md`**: A document detailing the setup steps and defining key VPN concepts.
* **`vpn_connection_status.png`**: A screenshot showing the active and protected ProtonVPN connection to a US server.
