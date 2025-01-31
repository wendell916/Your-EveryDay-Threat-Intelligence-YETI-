# Your-EveryDay-Threat-Intelligence-YETI-
Installation and configuration of YETI


# What is YETI
YETI (Your Everyday Threat Intelligence) is an open-source platform which designed to help security analysts and teams manage, enrich, and operationalize threat intelligence.It provides a centralized repository where users can collect, organize, and analyze information about cyber threats, such as malware, adversaries, attack techniques, indicators of compromise (IOCs), and more. Yeti, first introduced in 2017, continues to grow and evolve, maintaining steady development compared to other threat intelligence platforms. 

# Features of YETI
* Threat Data Management: Organize and manage threat intelligence data, including indicators of compromise (IOCs), TTPs, and forensic artifacts.
* Observable Search and Correlation: Perform bulk searches on observables to identify threats and link related entities for a deeper understanding.
* Forensic Artifact Management: Store and manage forensic artifacts such as DFIQ objects, Sigma rules, and Yara rules for effective detection and analysis.
* Threat Intelligence Enrichment: Enhance threat data with automatic enrichment from various sources and integrations.
* Collaboration and Sharing: Share intelligence with teams and integrate with other threat intelligence platforms for collaborative defense.
* Customizable Workflows: Support for custom data sources, analytics, and automation for tailored intelligence operations.
* Export and Interoperability: Export data in multiple formats like STIX and MISP, ensuring compatibility with other security tools.

# Requirements
 * An ubuntu server
 * Docker
 * git
   
# Installation
````````
git clone https://github.com/yeti-platform/yeti-docker
cd yeti-docker/prod
docker compose up
````````

Create an admin user 
```````
docker compose run --rm api create-user USERNAME PASSWORD --admin
```````

Access the gui interface
```````````
http://ip-address:80
```````````
Use the credentials created to access the gui

# Configuration
Under the threat section section enable some feeds of your choice



 
