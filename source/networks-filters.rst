Networks:: Filters
==================

The Palo Alto firewall is a modern day filtering device and provides many different tools to provide a curated computing experience.

**Postive Reinforcement Filtering**

The device operates by identifying and classifying all network traffic. There is basically a white list of known applications allowed on the SGS network. All other apps are silently dropped.

**QOS/Bandwidth Shaping**

The device allows for limiting portions of the upstream internet feed to rate limit usage.

For example, access to Youtube is limited to 20% of the available Internet feed to all students.

**Context Based Filtering**

The devices categorized URL traffic into different contexts.

There is staggered filtering applied to all users based on context and age of users.

- All users, porn, hate, illegal, malware, ads, p2p sites blocked
- 8th grade students, social media, streaming, ToS >= 18  blocked
- 5th-7th grade, Terms of Service >= 13 blocked

**Virus/Malware Scanning**

The device protects all users from spyware, malware, viruses, etc.

**Global Protect**

The device provides off campus filtering and protection as well ( currently not-deployed )

**Legal Compliance**

The device allows for MITM SSL decryption and analysis. In practice, this breaks HSTS enabled TLS sites ( GMail )
