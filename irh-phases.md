#  Incident Response Phases

![](https://raw.githubusercontent.com/gh1mau/IRH/main/img/irh-phases.png)

<details>
<summary><h3>Preparation</h3></summary>
Incident response methodologies typically emphasize preparation not only establishing an incident response capability so that the organization is ready to respond to incidents, but also preventing incidents by ensuring that systems, networks, and applications are sufficiently secure.

|  Prepare to Handle Incident |  Incident Handler Communications and Facilities |
| ------------ | ------------ |
|  -[ ]  Contact Information |  - Team Members 
|

</details>



<details>
<summary><h3>Incident Identification</h3></summary>
The team should be able to effectively detect deviations from normal operations in organizational systems and identify if those deviations represent actual security incidents.

When a potential incident is discovered, the team should immediately collect additional evidence, decide on the type and severity of the incident, and document everything they are doing. Documentation should answer “Who, What, Where, Why, and How” questions to allow the attackers to be prosecuted in court at a later stage.
</details>

<details>
<summary><h3>Containment</h3></summary>
Once the team identifies a security incident, the immediate goal is to contain the incident and prevent further damage from occurring. This involves:

- **Short-term containment** - this can be as simple as isolating a network segment that  is under attack or taking down production servers that have been hacked and are diverting traffic to backup servers.
- **Long-term containment** - applying temporary fixes to affected systems to allow them to be used in production, while rebuilding clean systems, preparing to bring them online in the recovery stage.
</details>

<details>
<summary><h3>Cleansing and Eradication</h3></summary>
The team must identify the root cause of the attack, remove malware or threats, and prevent similar attacks in the future. For example, if a weak authentication mechanism was the entry point for the attack, it should be replaced with strong authentication; if a vulnerability was exploited, it should be immediately patched.
</details>

<details>
<summary><h3>Recovery</h3></summary>
The team brings affected production systems back online carefully, to ensure another incident doesn’t take place. Important decisions at this stage are from which time and date to restore operations, how to test and verify that affected systems are back to normal, and how long to monitor the systems to ensure activity is back to normal.
</details>

<details>
<summary><h3>Lesson Learned and Follow-Up</h3></summary>
The team brings affected production systems back online carefully, to ensure another incident doesn’t take place. Important decisions at this stage are from which time and date to restore operations, how to test and verify that affected systems are back to normal, and how long to monitor the systems to ensure activity is back to normal.
</details>






