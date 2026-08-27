class HarishT:
    def __init__(self):
        self.name = "Harish T"
        self.location = "Chennai, India"
        self.degree = "B.E. Computer Science, Anna University"
        self.role = "Aspiring Cyber Security Apprentice"

        self.stack = [
            "Splunk (SIEM)", "Wireshark", "Suricata (IDS)",
            "Nessus", "OpenVAS", "Nmap", "Burp Suite"
        ]

        self.currently_learning = [
            "Advanced SOC Operations",
            "Cloud Security (AWS/Azure)",
            "Zero Trust Architecture"
        ]

        self.fun_fact = "I turn vulnerable machines into root-cause reports."

    def motto(self):
        return "Detect. Investigate. Document. Repeat."


me = HarishT()
print(me.motto())
