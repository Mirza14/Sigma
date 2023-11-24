# Sigma
Sigma is an open-source generic signature language used to write detection rules applicable across different SIEM solutions.

# Sigma Learning Objectives:
Introduction to the Sigma rule language.
Learn about Sigma Rule writing syntax and conversion to various SIEM query languages.
Navigate through writing rules for various detections on Windows Event Logs.
Practice writing Sigma rules for an interactive case.

# Sigma Use Cases:
To make detection methods and signatures shareable alongside IOCs and Yara rules.
To write SIEM searches that avoid vendor lock-in.
To share signatures with threat intelligence communities.
To write custom detection rules for malicious behaviour based on specific conditions.

# Sigma Development Process:
Sigma Rule Format: Generic structured log descriptions written in YAML.
Sigma Converter: A set of python scripts that will process the rules on the backend and perform custom field matching based on specified SIEM query language.
Machine Query: Resulting search query to filter out alerts during investigations. The query will be based on the specified SIEM.

