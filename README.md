class HarishT:
    def __init__(self):
        self.name = "Harish T"
        self.location = "Chennai, India"
        self.degree = "B.E. Computer Science, Anna University"
        self.role = "Certified SOC Analyst (CSA) | Aspiring Cybersecurity specialist"

        self.stack = [
            "Splunk (SIEM)", "Wireshark", "OpenVAS",
            "Nessus", "Metasploit", "Nmap", "Burp Suite"
        ]

        self.currently_learning = [
            "Advanced SOC Operations",
            "Cloud Security (AWS/Azure)",
            "Zero Trust Architecture",
            "Bug Bounty"
        ]

        self.fun_fact = "I turn vulnerable machines into root-cause reports."

    def motto(self):
        return "Detect. Investigate. Document. Repeat."


me = HarishT()
print(me.motto())
