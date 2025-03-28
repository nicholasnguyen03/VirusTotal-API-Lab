In this lab, I explored how antivirus software detects malware using file signatures. 
On my Ubuntu VM, I downloaded safe EICAR test files using wget, then analyzed them using the VirusTotal CLI and API.
After creating a VirusTotal account and retrieving my API key, I configured the vt-cli tool. I used sha1sum to generate hashes for each test file, then ran vt file <hash> to check if the files were recognized as malicious.
This process helped me understand how antivirus tools use hashes to identify known threats without scanning the actual file content. It also showed how even minor changes in a file create completely different hashes.
Overall, I learned how signature-based detection works and how to use VirusTotal to analyze suspicious files efficiently from the command line.
