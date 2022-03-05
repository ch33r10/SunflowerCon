<p align='center'>
<a href="https://twitter.com/Ch33r10"><img height="30" src="https://github.com/ch33r10/BlackHatAsia2020/blob/master/img/twitter%20blue%20logo.png"></a>
 <a href="https://www.linkedin.com/in/xena-olsen/"><img height="30" src="https://github.com/ch33r10/BlackHatAsia2020/blob/master/img/linkedin%20logo.png"></a>
</p>

# 🌻SunflowerCon🌻
### International Cybersecurity Incidents for In-House CTI Analysts✌️🕊️ 
Real talk about international cybersecurity incidents for in-house CTI Analysts. Involved in incident support? Yes, No, or Maybe. I’ll share some tips that you might find useful. 
#StandWithUkraine 

- This talk is geared towards: people newer-ish to cybersecurity, Jr. CTI Analysts, people breaking into the industry, & ideas for CTI Managers.

###### `TIP`: KEEP UP WITH INTL. INCIDENT CYBER-RELATED NEWS

### `STEP ONE`:
- Check in with your manager regarding how you can support the incident
  - If you want to get involved, share that with your manager!

### `STEP TWO`: 
**PICK YOUR PATH**
- Involved in Incident at Org - NO
- Involved in Incident at Org - YES

## Involved in Incident at Org - NO
1. Create or find a high fidelity Twitter List [@ddale8 Ukraine List](https://twitter.com/i/lists/1494327296383021062), [@ch33r10 UA List](https://twitter.com/i/lists/1482117927356801024)
2. Look out for any dumps related to the incident, attempt to get them (safely) & search for mention of org/industry vertical/critical third parties
3. Keep up with new developments/changes to the situation (Ex: Log4j multiple CVEs, UA cyber threats)
4. Look for mention of targeting/issues for industry vertical
5. Look for mention of issues/compromises related to known third parties or orgs that it would be reasonable to have an association with
6. Look for technology or similar vulnerability in your org if mentioned/related to incident
7. Practice finding specific procedures/TTPs that can be used by HUNT/SOC/PURPLE/RED
8. Practice pivoting on the IOCs
9. What are different GOV/GOV-related entities saying about it (Ex: CISA, FBI, CERTS, NCSC, etc.)
10. Use the intl incidents to learn what the more reputable sources are
11. Practice your collection strategy and methodology (Keep in mind the [Intelligence Lifecycle](https://www.recordedfuture.com/threat-intelligence-lifecycle-phases/))


###### `TIP`: WATCH EVERYTHING THE SENIOR PERSON DOES DURING THE INCIDENT & TAKE NOTES

## Involved in Incident at Org - YES
`IMPORTANT`: ASK **YOUR MANAGER** BEFORE YOU TRY THIS & GET THEIR APPROVAL. ENSURE RELEVANCY TO YOUR ORG & THAT IT WARRANTS THIS LABOR INTENSIVE PROJECT

### 🌞TRACK THE INTERNATIONAL INCIDENT IN A CENTRALIZED LOCATION FOR THE SECURITY TEAM WHERE EVERYONE CAN VIEW IT IN REAL-TIME!🌞

###### `TIP`: USE THE INTELLIGENCE LIFECYCLE AS A REPEATABLE METHODOLOGY TO TRACK THE INTERNATIONAL INCIDENT & PLAN CTI TEAM WORKLOADS - [Intelligence Lifecycle](https://www.recordedfuture.com/threat-intelligence-lifecycle-phases/)

#### `PLANNING & DIRECTION`:

- Manager: Talk with the other team leads at the org for their Priority Intelligence Requirements (PIRs) 
  - Ask what they need for deliverables, support, or other from CTI & their preferred format
  - Ask when & how they want updates 
  - Ask frequency of the updates
    - Ex: Security Leadership needs to know the actor's capabilities, likelihood, vulnerabilities, potential impact, etc. 
    - Ex: DFIR/SOC needs to know the attack path/TTPs and its changes, etc.
    - Ex: Detection Engineering needs detection-related technical context, etc. 
    - Ex: RED needs consolidated red-related info, etc. (Ex: log4j pentester tools on GitHub & procedures to re-create attacks)
    - Ex: HUNT needs actor behavioral information/attack-related information or changes to TTPs, etc. 
    - Ex: CTI needs to curate vetted IOCs, pivot to find additional infrastructure, track associated actors/payloads, create/deploy yararules, extract/research TTPs, intent/opportunity/capability of actor, etc.
-  Obtaining the PIRs prioritizes and buckets collection efforts. 

#### `COLLECTION`:

###### `TIP`: GREAT PUBLIC COLLECTION EXAMPLE YOU CAN REPURPOSE FOR YOUR ORG BASED ON YOUR PIRS (Build a template before you need it) [Curated Intel Ukraine Cyber Operations](https://github.com/curated-intel/Ukraine-Cyber-Operations/blob/main/README.md)

- Perform 1-11 above that pertain to PIRs and your collection strategy 
  - *Manager Tip: If you don't have a collection strategy or collection management...this could be something to add to the CTI team roadmap/program goals* 
- Track timeline of events
  - Cyber timeline
    - Cyber-related news reporting
  - Non-Cyber Event timeline (if necessary) 
    - General awareness reporting - especially concerning new developments
      - EX: RU invasion of UA
  - Track actions the org has taken related to the Intl. Incident (SOC, HUNT, CTI, Detection Engineering, RED, Purple, DFIR, etc.)
- Track threat reports released
- Track what GOV/GOV-related entities share about it or advise (Ex: CISA, FBI, CERTS, NCSC, etc.)
- Track new malware variants released 
- Track Actor(s)
  - TTPs
    - Focus on procedures that HUNT/SOC/Purple can use to build detections, perform adversary emulation exercises, or hunt in the environment
  - Document attack paths
  - Track how actors are compromising orgs, including tooling related to the vulnerability or incident
- Track vulnerabilities related to the intl incident
  - Review your organization's posture to the vulnerabilities
- Track software/products related to the incident (Ex: UA-related Kitsoft, Solarwinds, Log4j, etc)
 -  Review your organization's posture to the software/products
- Track any preparation/mitigation/remediation suggestions shared by reputable sources like SANS or others
  - Ex: Mick Douglas' ([@bettersafetynet](https://twitter.com/bettersafetynet)) suggestions for UA-RU Thread [Defending against RU cyber ops](https://twitter.com/bettersafetynet/status/1496496087741480960) 
- Collect any IOCs shared to run through your org's process (vet the IOCs)
- Collect YaraRules shared
- Collect any detection or hunt ideas/opportunities shared
- Track meetings you/your team attended with notes
- Track additional considerations
  - Ex: Belarus helping out RU. 

###### `TIP`: LOOK FOR ORIGINAL SOURCE: EX: LOG4J ISSUE MANAGEMENT - [LINK](https://issues.apache.org/jira/projects/LOG4J2/issues/LOG4J2-3419?filter=allopenissues)

#### `PROCESSING`

- **VERIFY ALL SOURCES**
- Avoid stating something is a fact (If it isn't a fact)
  - Use estimate language, where possible [Estimative Language](https://www.cia.gov/static/0aae8f84700a256abf63f7aad73b0a7d/Words-of-Estimative-Probability.pdf) by Sherman Kent 
- **QUESTION EVERYTHING** ... Especially information shared that you easily *AGREE* with - [Critical Thinking Thread](https://twitter.com/ErrataRob/status/1499156783058857993?s=20&t=cdRszWPtXqi48OQ7JHYy3Q) by [@ErrataRob](https://twitter.com/ErrataRob)
  - Don't believe everything you read (yes, even this)! 
    - Try it out yourself and seek the original context/content, if possible. 
      - Ex: Original technical write up in a news story
- Question: 
  - Data dumps (they can be altered) 
  - Videos/Audio/Images 
    - [SANS Deep Fake Resource](https://www.sans.org/newsletters/ouch/learn-a-new-survival-skill-spotting-deepfakes/) by [@KerryTNews]( https://twitter.com/KerryTNews)
    - [First Draft Basic Toolkit](https://start.me/p/vjv80b/first-draft-basic-toolkit): Resources to verify content, such as reverse image search ([RevEye Reverse Image Search Chrome Extension](https://chrome.google.com/webstore/detail/reveye-reverse-image-sear/keaaclcjhehbbapnphnmpiklalfhelgf)), exif/metadata, geolocation, video verification, etc. 
  - Claims  
    - Ex: Warning about people making claims of hacking Satellites in RU - [Link](https://twitter.com/kevincollier/status/1499028981647093762?s=20&t=TzfkuL6RTno5rCNUuJKaDw) by [@kevincollier](https://twitter.com/kevincollier)
  - Information sources
    - Include a rating for the information source's credibility (`LOW`, `MEDIUM`, `HIGH`) 
    - Include the information source type (`PRIMARY`, `SECONDARY`, etc.) 
      - Ex: Analysis of Competing Hypotheses for WannaCry - [Link](https://www.digitalshadows.com/blog-and-research/wannacry-an-analysis-of-competing-hypotheses/) by Rafael Amado at Digital Shadows   

*VERIFICATION*

| Provenance | Source | Date | Location | Motivation | 
| --- | --- | --- | --- | --- |
| Where did the content originate? Is this the first version? | Who created the original content? The poster isn't necessarily the content creator. | Upload time can be different to the time something was captured. | If the content is geotagged, does the location make sense? Have you independently verified the location? | What motivated the source to create the content? |

<sub>Citation for the adapted table below: First Draft News (2021). Verification: The Five Pillars of Visual Verification. </sub> [Link](https://twitter.com/firstdraftnews/status/1498086048349392897?s=20&t=tS1hYukA0UTrWdZaZkGRaw)

**ADDITIONAL CTI VERIFICATION CONSIDERATIONS**
- Financial or "other" sponsorship of the source (Ex: Pay4Play type things)
- Sensationalism of the source (marketing, FUD, vendor affiliation, clout chasing, etc.)
- Track record of source (Ex: J. Scott)
- & More

*MIS/DIS/MAL-INFORMATION*

| Mis-information | Dis-information | Mal-information |
| --- | --- | --- | 
| False information, No intention to harm, Ex: [Ghost](https://www.military.com/daily-news/2022/03/02/ukraines-fighter-ace-ghost-of-kyiv-may-be-myth-its-lethal-war-morale.html) of Kyiv, [Snake Island](https://twitter.com/YaBoiBru/status/1497598394893746182), UA farmer has more [tanks](https://twitter.com/peterwsinger/status/1500092217611984902?s=20&t=bIslbnve7lOLazTaJ6aB1Q) than entire US Marine Corps | False information, Intention to harm, Ex: [RU Info Attacks](https://twitter.com/Ukraine/status/1497599276901441547?s=20&t=cdRszWPtXqi48OQ7JHYy3Q) | Genuine information, Intention to harm, (Includes leaks, harassment, hate speech), Ex: [@ContiLeaks](https://twitter.com/ContiLeaks) |

<sub>Citation for the adapted table below: Mary Blankenship (2020). How Misinformation Spreads Through Twitter. UNLV.</sub> [Link](https://digitalscholarship.unlv.edu/cgi/viewcontent.cgi?article=1006&context=brookings_capstone_studentpapers)


My Fav Info Ops ;) 
- [Ukrainian soldiers with cats](https://twitter.com/David_Leavitt/status/1497778728776060928?s=20&t=VVRPF43wAo1tqCLMVTl1mw)
- [Spicy UA Posters](https://twitter.com/Mo_Abbas_Tweets/status/1499809125991129088?s=20&t=bIslbnve7lOLazTaJ6aB1Q)
- [Tactical Pickles](https://twitter.com/TsybulskaLiubov/status/1500075457798189057?s=20&t=bIslbnve7lOLazTaJ6aB1Q)
- [Time Magazine Cover](https://twitter.com/Ukraine/status/1499280918900625409?s=20&t=bIslbnve7lOLazTaJ6aB1Q) - "Life Will Win Over Death. Light Will Win Over Darkness" ~ Volodymyr Zelensky, President of Ukraine 
- [Happy Stalin's Death Day!](https://twitter.com/Ukraine/status/1500016881310355462?s=20&t=bIslbnve7lOLazTaJ6aB1Q)
- [What a Wonderful World](https://twitter.com/Journotopia/status/1500093818699456527?s=20&t=bIslbnve7lOLazTaJ6aB1Q)
- [Epic Trolling](https://twitter.com/Ukraine/status/1498547251949588482?s=20&t=bIslbnve7lOLazTaJ6aB1Q)
- [Sunflower Seeds](https://youtu.be/PJJ8zmcBH2A)
- [Ukrainian moves mine with cigarette](https://twitter.com/travisakers/status/1497943065629179904?s=20&t=bIslbnve7lOLazTaJ6aB1Q)
- [Zelensky Selfie Video](https://twitter.com/SaoSasha/status/1497311531041640450?s=20&t=bIslbnve7lOLazTaJ6aB1Q) - "We're all here" ~ Volodymyr Zelensky

#### `ANALYSIS`

- Managers can prioritize/assign PIRs by Analyst skillset and growth opportunities
  - Actor-centric CTI analyst focus on Actor-related analysis/Diamond Model etc.
  - TTP-centric CTI analyst focus on TTP-related PIRs, such as procedures for SOC/DFIR/HUNT/RED/Detection Engineering
  - Red-skilled CTI analyst can help with testing and developing custom signatures
  - Etc...
    - Ex: CTI TEAM ON BEASTMODE - WannaCry: Reverse engineer-skilled CTI Analyst found the killswitch before it was shared publicly
 
#### `DISSEMINATION`

- Ensure the PIR deliverables are simple
  - **REMEMBER: Stay Vigilant - There are other threats than the international cybersecurity incident that you need to "worry" about.** 

#### `FEEDBACK`

- Get feedback from stakeholders during the incident and course correct on the spot
- After the incident: 
  - Check in with other team leaders to see what worked/didn't work
  - Do a "huddle" with the CTI team
    - Use incidents to roadmap skill building & practice areas


## Prepare Before the NEXT ONE! 
- VM [REMnux](https://www.sans.org/tools/remnux/) OR [FLARE VM](https://github.com/mandiant/flare-vm)
- VPN that lets you download files in a reasonable time
- Join Vetted Intel Sharing Groups
- Set Up Accounts
  - Get [Shodan](https://www.shodan.io/) Account
  - Sock Accounts
- Set up RSS Feed for Collection Purposes - FREE option [Feedbro](https://nodetics.com/feedbro/)
- & More!!!!!!!!!!!

## Additional Resources
- [Working with Traumatic Imagery](https://dartcenter.org/content/working-with-traumatic-imagery) by Data Center for Journalism & Trauma
- [First Draft News Misinformation Training](https://firstdraftnews.org/training/)
- [First Draft News Social Media Account Verification](https://twitter.com/firstdraftnews/status/1498086053004992513?s=20&t=tS1hYukA0UTrWdZaZkGRaw)

<br></br>
![ig post](https://github.com/ch33r10/SunflowerCon/blob/main/heartukraine/standwithua.png)
<br></br>
<hr></hr>

###### FOR THE LAWYERS

<sub>The opinions expressed in this Github repo are those of the individual account, in their individual capacity, and not necessarily those of the employers. Mention of any vendors, services, products, or otherwise does not endorse them as a vendor. This content and any related discussions are solely the views, opinions, and experiences of the participants and should not be presumed to reflect the opinion or the official position of any employers of the participants. Examples and views provided herein, including strategies, goals, targets, and indicators are for illustrative purposes only and should not be regarded as representative of the participants' employers or respective portfolios. To the extent that this participation, discussion, and interview outlines a general technology direction, the participants' employers have no obligation to pursue any such approach or to develop or use any functionality mentioned herein. Any suggested technology strategy or possible future developments are subject to change at the employers' sole discretion without notice. Content in this presentation is the intellectual property of the applicable creators and may be protected under the copyright laws of the United States and/or other countries. All trademarks are the property of their respective owners and are used for informational purposes only.</sub>
