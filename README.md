# 🌻SunflowerCon🌻
### International Cybersecurity Incidents for In-House CTI Analysts✌️🕊️ 
Real talk about international cybersecurity incidents for in-house CTI Analysts. Involved in incident support? Yes, No, or Maybe. I’ll share some tips that you might find useful. 
#StandWithUkraine 

- This talk is geared towards people that are newer-ish to cybersecurity, a CTI role, or even people looking to break into the industry. 

###### `TIP`: KEEP UP WITH INTL. INCIDENT CYBER-RELATED NEWS

#### `STEP ONE`:
- Check in with your manager regarding how you can support the incident
  - If you want to get involved, share that with your manager!

#### `STEP TWO`: PICK YOUR PATH
- Involed in Incident at Org - NO
- Involed in Incident at Org - YES

## Involed in Incident at Org - NO
1. Create or find a high fidelity Twitter List [@ddale8 Ukraine List](https://twitter.com/i/lists/1494327296383021062), [@ch33r10 UA List](https://twitter.com/i/lists/1482117927356801024)
2. Look out for any dumps related to the incident, Attempt to get them (safely) & search for mention of org/industry vertical/critical third parties
3. Keep up with new developments or changes to the situation (Ex: Log4j multiple CVEs, UA cyber threats)
4. Look for mention of targeting or issues for industry vertical
5. Look for mention of issues or compromise related to known third parties or orgs that it would be reasonable to have an association with
6. Look for technology or similar vulnerability in your org
7. Practice finding specific procedures/TTPs that can be used by HUNT/SOC/PURPLE/RED
8. Practice pivoting on the IOCs
9. Use the intl incidents to learn what the more reputable sources are
10. Practice your collection strategy and methodology (Keep in mind the [Intelligence Lifecycle](https://irp.fas.org/cia/product/facttell/intcycle.htm))


###### `TIP`: WATCH EVERYTHING THE SENIOR PERSON DOES DURING THE INCIDENT & TAKE NOTES

## Involed in Incident at Org - YES
`IMPORTANT`: ASK **YOUR MANAGER** BEFORE YOU TRY THIS & GET THEIR APPROVAL

Perform 1 thru 10 above PLUS:

**Track the Intl. Incident in a centralized location where everyone on the security team can view it!**   

Ex: Curated Intel [Ukraine Cyber Operations](https://github.com/curated-intel/Ukraine-Cyber-Operations/blob/main/README.md)
- Track timeline of events
  - Cyber timeline
    - Cyber-related news reporting
  - Non-Cyber Event timeline (if necessary) 
    - General awareness reporting - especially concerning new developments
      - EX: RU invasion of UA
  - Track actions the org has taken related to the Intl. Incident (SOC, HUNT, CTI, Detection Eningeering, RED, Purple, DFIR, etc)
- Track threat reports released
- Track new malware variants released 
- Track Actor(s)
  - TTPs
    - Focus on procedures that HUNT/SOC/Purple can use to build detections, perform adversary emulation exercises, or hunt in the environment
  - Document attack paths
  - Track how actors are compromising orgs, including tooling related to the vulnerability or incident
  - Track vulnerabilities actors are using to compromise organizations
    - Review your organization's posture to the vulnerabilities
- Collect any IOCs shared to run through your org's process (vet the IOCs)
- Track any preparation/mitigation/remediation suggestions shared by reputable sources like SANS 
  - Ex: Mick Douglas' ([@bettersafetynet](https://twitter.com/bettersafetynet)) suggestions for UA-RU Thread [Defending against RU cyber ops](https://twitter.com/bettersafetynet/status/1496496087741480960) 
- Collect any detection or hunt ideas/opportunities shared
- Track meetings you/your team attended with notes
- Track additional considerations
  - Ex: Belarus helping out RU. 



###### `TIP`: LOOK FOR ORIGINAL SOURCE: EX: LOG4J ISSUE MANAGEMENT - [LINK](https://issues.apache.org/jira/projects/LOG4J2/issues/LOG4J2-3419?filter=allopenissues)

## Caveats
- Remain vigilant
- Avoid stating something is a fact 
  - Use estimate language, where possible [Estimative Language](https://www.cia.gov/static/0aae8f84700a256abf63f7aad73b0a7d/Words-of-Estimative-Probability.pdf) by Sherman Kent 
- **QUESTION EVERYTHING** ... Especially information shared that you easily *AGREE* with - [Critical Thinking Thread](https://twitter.com/ErrataRob/status/1499156783058857993?s=20&t=cdRszWPtXqi48OQ7JHYy3Q) by [@ErrataRob](https://twitter.com/ErrataRob)
  - Don't believe everything you read (yes, even this)! 
    - Try it out yourself and seek the original context/content, if possible. 
      - Ex: Original technical write up in a news story
- Question: 
  - Data dumps (they can be altered) 
  - Videos/Audio [SANS Deep Fake Resource](https://www.sans.org/newsletters/ouch/learn-a-new-survival-skill-spotting-deepfakes/) by [@KerryTNews]( https://twitter.com/KerryTNews) 
  - Claims  
    - Ex: Warning about people making claims of hacking Satellites in RU - [Link](https://twitter.com/kevincollier/status/1499028981647093762?s=20&t=TzfkuL6RTno5rCNUuJKaDw) by [@kevincollier](https://twitter.com/kevincollier)
  - Information sources
    - Include a rating for the information source's credibility (`LOW`, `MEDIUM`, `HIGH`) 
    - Include the information source type (`PRIMARY`, `SECONDARY`, etc.) 
      - Ex: Analysis of Competing Hypotheses for WannaCry [Link](https://www.digitalshadows.com/blog-and-research/wannacry-an-analysis-of-competing-hypotheses/) by Rafael Amado at Digital Shadows   

<sub>Citation for the adapted table below: Mary Blankenship (2020). How Misinformation Spreads Through Twitter. UNLV.</sub> [Link](https://digitalscholarship.unlv.edu/cgi/viewcontent.cgi?article=1006&context=brookings_capstone_studentpapers)

| Mis-information | Dis-information | Mal-information |
| --- | --- | --- | 
| False information, No intention to harm, Ex: [Snake Island](https://twitter.com/YaBoiBru/status/1497598394893746182) | False information, Intention to harm, Ex: [RU Info Attacks](https://twitter.com/Ukraine/status/1497599276901441547?s=20&t=cdRszWPtXqi48OQ7JHYy3Q) | Genuine information, Intention to harm, (Includes leaks, harassment, hate speech), Ex: [@ContiLeaks](https://twitter.com/ContiLeaks) |


My Fav Info: [Ukrainian soldiers with cats](https://twitter.com/David_Leavitt/status/1497778728776060928?s=20&t=VVRPF43wAo1tqCLMVTl1mw)



## Prepare Before the NEXT ONE! 
- VM [REMnux](https://www.sans.org/tools/remnux/) OR [FLARE VM](https://github.com/mandiant/flare-vm)
- VPN that lets you download files in a reasonable time
- Join Vetted Intel Sharing Groups
- Set Up Accounts
  - Get Shodan account [Shodan](https://www.shodan.io/)
  - Sock Accounts
- Set up RSS Feed for Collection Purposes - FREE option [Feedbro](https://nodetics.com/feedbro/)

<br></br>
<hr></hr>

###### FOR THE LAWYERS

<sub>The opinions expressed in this Github repo are those of the individual account, in their individual capacity, and not necessarily those of the employers. Mention of any vendors, services, products, or otherwise does not endorse them as a vendor. This content and any related discussions are solely the views, opinions, and experiences of the participants and should not be presumed to reflect the opinion or the official position of any employers of the participants. Examples and views provided herein, including strategies, goals, targets, and indicators are for illustrative purposes only and should not be regarded as representative of the participants' employers or respective portfolios. To the extent that this participation, discussion, and interview outlines a general technology direction, the participants' employers have no obligation to pursue any such approach or to develop or use any functionality mentioned herein. Any suggested technology strategy or possible future developments are subject to change at the employers' sole discretion without notice. Content in this presentation is the intellectual property of the applicable creators and may be protected under the copyright laws of the United States and/or other countries. All trademarks are the property of their respective owners and are used for informational purposes only.</sub>
