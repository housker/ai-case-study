# Crowdstrike

## Overview and Origin

* **Name:** Crowdstrike

* **Field:** Cybersecurity

* **Incorporated:** 2011

* **Founders:** George Kurtz, Dmitri Alperovitch, Gregg Marston

* **How did the idea for the company come about?** Those who would become the founding team of Crowdstrike (George Kurtz, Hyacinth Diehl, Dmitri Alperovitch, Sven Krasser) first met after Secure Computing acquired CipherTrust. They'd gain further experience at companies like McAfee (acquired by Intel), but that initial interaction sparked a redefinition of the problem and a vision to provide an adversary-focused solution - uniting varied domains from OS to at-scale data pipelines to ML - that could effectively address even nation state actors.

* **Funding:** After reaching a valuation of over $3 billion and raising $480 million in Series C, D, and E funding, Crowdstrike had their IPO in June 2019 and is now a publicly traded company with revenue of over $2.24 billion[^1]

## Business Activities

* **What problem is the company solving?** Security breaches

* **Target market:** Large enterprises as well as small and medium-sized businesses[^2] 

* **Competitive advantage:** Crowdstrike was cloud-native from the beginning, meaning security telemetry could be correlated by large ML models on the cloud.[^3] This was a huge advantage over traditional antivirus software which compared known malware signatures to files downloaded onto a machine. Today, 71% of attacks are malware-free,[^4] all of which would not have been detected by traditional methods.

### Technologies currently in use:
* Charlotte AI, a generative AI assistant for security analysts[^5]
*  AI-powered Indicators of Attack (IOAs), models which can detect sequences of events indicative of an cyber attack in-progress. This was formerly something only highly trained security analysts were capable of identifying.[^6]
* ML malware classification, specifically in static file analysis, behavioral analysis of the cyber kill chain, forensic analysis, and sandbox malware analysis.[^7]    

## Landscape

### Trends and innovations in cyber over the past 5 &ndash; 10 years
Threat actors have expanded their attack surface, which now includes endpoints, web applications, email, containers, networks, and firewalls - to name a small subset - and can impact all points within a supply chain, including the laptops of our post-pandemic remote workforce, and the networks of data centers to which formerly on-premises concerns have now been transitioned. For example, the SolarWinds attack of 2020 consisted of a backdoor injected into an Orion IT update which was downloaded by 18,000 customers. Because the attack surface is so large and complex, centralized models for both decision-making and physical asset protection are no longer tenable.[^8] Decentralized decision-making gives rise to managed services for detection and response, threat hunting, and incident response and advisory. Decentralized asset protection gives rise to products such as Extended Detection and Response (XDR), Next-Generation Antivirus (NGAV), Identity and Access Management (IAM), and many more which are utilizing ML/AI technologies integrated with threat intelligence to provide targeted observability.

### Competitors
* Microsoft
* Sophos
* SentinelOne
* Trend Micro
* Malwarebytes
* Palo Alto Networks
* Cisco
* Bitdefender[^9]
* Fortinet
* Trellix
* Stellar Cyber[^10]

With regards to LLM-style AI, Crowdstrike's Charlotte AI finds competition with Microsoft Copilot and SentinelOne Purple AI. Snyk is a competitor for Crowdstrike's cloud security solution.

## Results

### What has been the business impact of this company so far?
Crowdstrike aims to be the “SalesForce of cybersecurity” with a platform third parties can develop on and products like Falcon Foundry users can customize their workflows with. Their AI technologies have the "potential to drastically improve analyst experience if integrated into analyst workflows.”[^11]

### Core success metrics
Crowdstrike holds at least 93 patents.[^12] Revenue is up 35% year-over-year to $786 million. Net cash from operations is $273.5 million. Free cash flow is $239 million. Crowdstrike ended Q3 2023 with $3.17 billion in cash, equivalents and short-term investments.[^13] 
> "CrowdStrike's record third quarter exceeded expectations, delivering new milestones across the business: net new ARR growth accelerated to a record $223 million and ending ARR surpassed $3 billion, making CrowdStrike the fastest and only pure play cybersecurity software vendor in history to achieve this milestone."
> -- <cite>George Kurtz, CEO of CrowdStrike</cite>[^14]

### Crowdstrike's performance relative to competitors
Forrester has named Crowdstrike a leader in Endpoint Detection and Response.[^15]
Gartner has named Crowdstrike a leader for Endpoint Protection Platforms, just ahead of SentinelOne and behind Microsoft.[^16]

## Recommendations

Firstly, XDR is a growing field. It allows analysts and models to gain a more complete picture by drawing off of data produced by specialized software that was once siloed. There is much work to be done in building up connectors between the unstandardized APIs of third parties. However, similar to the way Google standardized much of the internet by crawling and scraping web pages with considerable variability in their structures, in their dominance, they are now driving the structure of those web pages through algorithms that define SEO. Crowdstrike, in its function as a marketplace and platform for third parties, should seek a similar goal.

Additionally, as with the widespread adoption of any new technology (e.g., IoT connected devices and remote keyless entry) comes a larger attack surface and an underestimated potential for exploitation. Generative AI is no different.[^17] Crowdstrike might consider developing products specifically tailored to protecting the sensitive, proprietary, and personal identifiable information that is inevitably getting fed into them. Developing products that can secure ML pipelines may complement Crowdstrike's existing product offerings, especially since the acquisition of Bionic, whose specialty is code-to-runtime Application Security Posture Management (ASPM).[^18] This is an idea borrowed from Protect AI.[^19]

Lastly, generative AI is beginning to be used by adversaries to create malware.[^20] Unskilled threat actors are able to perform more sophisticated attacks, but so far AI has not produced novel tactics or techniques. Right now, these attacks are not much different from existing attacks, and existing methods will have no problem detecting them. This may remain so for months or perhaps decades, but researchers may want to be prepared for the day when AI can be used to generate novel attacks. Should that become the case, ML models could conceivably be trained on exploits generated by AI. By training ML models on generative AI malware, Crowdstrike can develop defenses in anticipation of vulnerabilities that have yet to be discovered. Preemptively training models on malware not yet observed in the wild could protect organizations from some of the most dangerous and difficult to avoid attacks, and lead to more accurate models in general. An AI red team could supplement pen testing, and might also be useful in detecting zero days.

## Works Cited
[^1]: [Crowdstrike. (2023, Nov, 29). In _Wikipedia_](https://en.wikipedia.org/wiki/CrowdStrike)

[^2]: ["SMB Endpoint Security Vendor Scorecard 2021: Analysys Mason has identified five vendors as leaders"](https://www.analysysmason.com/contentassets/a32b688b15b64de5ae839859e6af69ac/analysys_mason_endpoint_security_scorecard_article_nov2021_ren04.pdf) 

[^3]: ["The Force Multiplier of Correlating Your Security Telemetry"](https://www.crowdstrike.com/blog/the-force-multiplier-of-correlating-your-security-telemetry/)

[^4]: ["CrowdStrike 2023 Global Threat Report"](https://www.crowdstrike.com/global-threat-report/)

[^5]: ["AI-native protection"](https://www.crowdstrike.com/falcon-platform/artificial-intelligence-and-machine-learning/)

[^6]: ["Introducing AI-Powered Indicators of Attack: Predict and Stop Threats Faster Than Ever"](https://www.crowdstrike.com/blog/introducing-ai-powered-indicators-of-attack-ioas/)

[^7]: ["MACHINE LEARNING (ML) & CYBERSECURITY HOW IS ML USED IN CYBERSECURITY?"](https://www.crowdstrike.com/cybersecurity-101/machine-learning-cybersecurity/)

[^8]: ["7 Top Trends in Cybersecurity for 2022"](https://www.gartner.com/en/articles/7-top-trends-in-cybersecurity-for-2022)

[^9]: ["Crowdstrike Alternatives"](https://www.gartner.com/reviews/market/endpoint-protection-platforms/vendor/crowdstrike/alternatives)

[^10]: ["Competitors and Alternatives to Cortex XDR"](https://www.gartner.com/reviews/market/endpoint-detection-and-response-solutions/vendor/palo-alto-networks/product/cortex-xdr/alternatives)

[^11]: [Allie Mellen, principal analyst for Security and Risk with Forrester, as quoted in "Fal.Con 2023: CrowdStrike Surges Ahead With Groundbreaking Innovations." Forbes](https://www.forbes.com/sites/tonybradley/2023/09/21/falcon-2023-crowdstrike-surges-ahead-with-groundbreaking-innovations/?sh=17a856367247)

[^12]: ["Patents Assigned to CROWDSTRIKE, INC."](https://patents.justia.com/assignee/crowdstrike-inc)

[^13]: ["CrowdStrike Reports Third Quarter Fiscal Year 2024 Financial Results"](https://www.businesswire.com/news/home/20231128922324/en/CrowdStrike-Reports-Third-Quarter-Fiscal-Year-2024-Financial-Results/)

[^14]: ["CrowdStrike Q3 Earnings: EPS Beat, Revenue Up 35%, Record Cash Flow, Strong Guidance And More"](https://www.msn.com/en-us/money/news/crowdstrike-q3-earnings-eps-beat-revenue-up-35-record-cash-flow-strong-guidance-and-more/ar-AA1kGCxg)

[^15]: ["The Forrester Wave™: Endpoint Detection And Response Providers, Q2 2022"](https://reprints2.forrester.com/#/assets/2/482/RES176332/report)

[^16]: [" 2022 Gartner® Magic Quadrant™ for Endpoint Protection Platforms"](https://www.crowdstrike.com/resources/reports/gartner-mq/)

[^17]: ["ChatGPT's training data can be exposed via a "divergence attack"](https://stackdiary.com/chatgpts-training-data-can-be-exposed-via-a-divergence-attack/?utm_source=tldrai)

[^18]: ["CrowdStrike to Acquire Bionic to Extend Cloud Security Leadership with Industry’s Most Complete Code-to-Runtime Cybersecurity Platform"](https://www.crowdstrike.com/press-releases/crowdstrike-to-acquire-bionic-to-extend-cloud-security-leadership/)

[^19]: ["AI Zero Days: Why we need MLSecOps, now."](https://protectai.com/blog/what-is-an-ai-zeroday)

[^20]: ["FBI: Hackers Are Having a Field Day With Open-Source AI Programs"](https://www.pcmag.com/news/fbi-hackers-are-having-a-field-day-with-open-source-ai-programs)