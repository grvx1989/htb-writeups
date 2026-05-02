# Responder

Hands-on lab focused on network poisoning, credential capture, and abuse of misconfigured name resolution protocols.

## Methodology
1. Network Enumeration (identify broadcast traffic / target scope)
2. Poisoning Attack (LLMNR/NBT-NS spoofing with Responder)
3. Credential Capture (NTLMv2 hashes)
4. Offline Analysis / Cracking (hash identification & password recovery)
5. Access Validation
   
## Key Concepts
1. LLMNR / NBT-NS Poisoning
2. Man-in-the-Middle (MITM)
3. NTLM Authentication
4. Hash Capture & Cracking

## Tools Used
Responder
Hashcat / John the Ripper
Wireshark (optional analysis)
Outcome

Captured NTLMv2 hashes via network poisoning and leveraged them to obtain valid credentials, demonstrating how insecure name resolution can lead to credential compromise.

























