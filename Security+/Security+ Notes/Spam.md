# Spam
The term "spam" is internet slang that refers to unsolicited commercial email (UCE) or unsolicited bulk email (UBE). Some people refer to this kind of communication as junk email to equate it with the paper junk mail that comes through the US Mail. Unsolicited email most often contains advertisements for services or products, but very few reputable marketers use UCE to advertise
The most commonly seen spam includes:

-   [[Phishing]](https://kb.iu.edu/d/arsf) scams, a very popular and dangerous form of email fraud
-   Foreign bank scams or advance fee fraud schemes
-   Pyramid schemes, including multilevel marketing (MLM)
-   Other "Get Rich Quick" or "Make Money Fast" (MMF) schemes
-   Quack health products and remedies
-   Ads for pornographic websites
-   Offers of software for collecting email addresses and sending UCE
-   Offers of bulk emailing services for sending UCE
-   Chain letters (see [About chain mail](https://kb.iu.edu/d/aexs))
-   Illegally pirated software ("Warez")

Spam is a significant technology issue:
-	Security concerns, resource utilization, storage costs, managing the spam
## SPIM(Spam over Instant Messaging)
Spam sent through SMS

## Mitigations
- Unsolicited email
	- Stop it at the gateway before it reaches the  user
	- Onsite or Cloud Based
![[Pasted image 20210613215222.png]]
- Allowed list
	- Only recieve email from trusted senders
- SMTP standards checking
	- Block anything that doesn't follow RFC standards
- rDNS - Reverse DNS
	- Block email where the sender's domain doesn't match the IP address
- Tarpitting
	- Intentionally slow down the server conversation
- Recipient filtering
	- Block all email not addressed to a valid recipient email address 