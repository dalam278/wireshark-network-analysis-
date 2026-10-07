# wireshark-network-analysis-
HTTP and DNS traffic analysis using Wireshark, with redacted screenshots and findings.
Wireshark Network Analysis

This project analyzes HTTP and DNS traffic captured with Wireshark. The reports document protocol behavior through written answers and packet screenshots, including HTTP caching, connection reuse, and DNS resolution.
Lab Reports
Report	Topics
[HTTP Wireshark Lab](HTTP_Wireshark_Lab_Public_Redacted.pdf)	GET requests, response headers, caching, embedded objects, and persistent connections
[DNS Wireshark Lab](DNS_Wireshark_Lab_Public_Redacted.pdf)	DNS queries and responses, record types, nameservers, and authoritative DNS servers


HTTP Analysis
- Identified HTTP/1.1 in browser requests and server responses.
- Examined 200 OK and 304 Not Modified responses.
- Inspected Content-Length, Last-Modified, and If-Modified-Since headers.
- Traced requests for an HTML page, its images, and a favicon.
- Verified persistent connection reuse using TCP ports and packet details.
DNS Analysis
- Used nslookup to generate DNS traffic.
- Verified destination port 53 for queries and source port 53 for responses.
- Examined A records for IPv4 addresses and NS records for nameservers.
- Inspected answer counts, record contents, time-to-live values, and additional records.
- Compared queries sent to a home DNS resolver with queries sent directly to an authoritative DNS server.
Tools and Workflow
Tools: Wireshark, a web browser, Windows Command Prompt, and nslookup.
1. Started a packet capture and generated the required HTTP or DNS traffic.
2. Applied http or dns display filters to locate relevant messages.
3. Matched requests with responses and inspected protocol fields.
4. Documented findings with screenshots in the PDF reports.
Skills Practiced
Packet capture, protocol analysis, traffic filtering, request/response matching, evidence-based documentation, and redaction of identifying network details.
Privacy
The linked PDFs are public portfolio copies. Identifying details—including private IP addresses, MAC addresses, adapter identifiers, device/browser information, unrelated traffic, and raw packet bytes—were redacted before sharing. Some fields needed for the original lab answers are intentionally hidden in these public versions.
