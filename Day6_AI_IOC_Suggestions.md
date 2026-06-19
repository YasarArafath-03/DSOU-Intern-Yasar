# Day 6 AI IOC Suggestions

IOC 1: Multiple 4625 failed login events  
→ Location: Windows Security logs  
→ Reason: detects brute force attack  

IOC 2: Pattern 4625 → 4624  
→ Location: Event Viewer / SIEM  
→ Reason: shows possible successful compromise  

IOC 3: Logon Type 10 spikes  
→ Location: Security logs  
→ Reason: detects RDP remote login abuse  

Best IOC:
Correlation between failed and successful login attempts
