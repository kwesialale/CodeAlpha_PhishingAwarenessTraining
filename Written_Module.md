# Phishing Awareness Training - Written Module
## CodeAlpha Cybersecurity Internship - Task 2

---

## Section 1: What Is Phishing?

**Phishing** is a type of online scam where a criminal pretends to be a trustworthy person or organization, a bank, a coworker, a delivery company, a government agency, in order to trick someone into giving up sensitive information (like passwords or bank details) or installing harmful software. The name comes from "fishing": the scammer casts bait (a fake message) and waits for someone to "bite" (click a link, open a file, or reply with personal details).

**The key thing to understand:** phishing does not usually work by breaking through computer security. It works by manipulating a *person*, using urgency, fear, trust, or curiosity to get them to act before they think it through.

### How big is this problem, really?

- In the United States, the **FBI's Internet Crime Complaint Center** (**IC3** - the FBI's official unit for tracking internet-based crime reports) received **193,407 phishing and spoofing complaints in 2024**, more than any other type of internet crime reported that year. (FBI IC3 2024 Internet Crime Report)
- The **Anti-Phishing Working Group** (**APWG** - a global coalition of banks, tech companies, and law enforcement that tracks phishing worldwide) recorded **1,003,924 phishing attacks in the first quarter of 2025 alone**, the highest quarterly total since late 2023. (APWG Phishing Activity Trends Report, Q1 2025)
- **Business Email Compromise** (**BEC** - a scam where a criminal impersonates a real business contact, usually to redirect a wire payment) attacks requested an average of **$83,099 per attack in Q2 2025**, according to data cited in the APWG report. (APWG Q2 2025 Report)

---

## Section 2: How to Recognize a Phishing Email

### 2.1 The sender's address doesn't quite match

Scammers often use a **lookalike domain**, a web address deliberately spelled to look almost identical to a real one. For example: `amazan.com` instead of `amazon.com`, or `yourb4nk.com` (using the number 4 in place of the letter "a") instead of `yourbank.com`. The display name might say "Microsoft Support," but the actual email address underneath could be something completely unrelated.

**Important update:** "bad spelling" is no longer a reliable warning sign. Criminals now use **AI (Artificial Intelligence)** tools to write fluent, grammatically perfect messages in multiple languages, so this old advice doesn't hold up as well as it used to.

### 2.2 Urgency and fear

Messages like *"Your account will be suspended in 24 hours"* or *"Immediate action required"* are designed to make you panic and act before thinking. This emotional pressure is one of the most consistent warning signs across all phishing attempts.

### 2.3 Requests for sensitive information

**Legitimate banks, companies, and government agencies will never ask for your password, PIN, or one-time passcode (OTP - a temporary code sent to confirm your identity) by email, text, or phone call.** If you're ever asked for one of these, it's a scam.

### 2.4 Suspicious links and attachments

- Shortened links (like `bit.ly/xyz123`) hide the real destination website.
- Hover your mouse over a link (without clicking) to see the actual web address it leads to, shown at the bottom of your browser window.
- Unexpected file attachments, even from people you know, can contain malware (malicious software).

### 2.5 Generic greetings

"Dear Customer" or "Dear User" instead of your actual name is a common sign that a message was sent to thousands of people at once, not written specifically for you.

---

## Section 3: How to Recognize a Fake Website

- **Check the web address carefully.** Scammers use tricks like extra words (`paypal-account-verify.com`) or hidden subdomains (`paypal.com.secure-login.xyz`, where the real domain is actually `secure-login.xyz`, not PayPal at all).
- **HTTPS and the padlock icon do NOT guarantee safety.** HTTPS just means your connection to the website is encrypted, it says nothing about whether the website itself is trustworthy. Scammers can and do get padlock icons on fake sites.
- **Look for poor design, broken images, or missing "About Us"/"Contact" pages** - signs of a site built quickly for a scam rather than a real business.
- **Type known website addresses directly into your browser**, or use a saved bookmark, rather than clicking search engine ads, the FBI has specifically warned about criminals buying fake search ads that mimic real company websites.

---

## Section 4: Social Engineering Tactics

**Social engineering** is the general term for manipulating people (rather than computers) into giving up information or access. Pretexting relies on a false identity or story; baiting relies on offering something enticing.

| Tactic | What it means |
|---|---|
| **Pretexting** | Inventing a false identity or story to earn trust, e.g., someone claiming to be "IT support" who needs to "verify" your password |
| **Baiting** | Offering something desirable in exchange for information, a fake gift card survey, a too-good job offer asking for banking details |
| **Vishing** (Voice phishing) | Phone-call-based scams. AI voice-cloning now makes it possible for scammers to convincingly imitate a specific person's voice, such as a boss or family member |
| **Smishing** (SMS phishing) | Phishing sent by text message |
| **Business Email Compromise (BEC)** | Impersonating or hijacking a real business email account to redirect a payment or steal funds |

### AI is changing this space quickly

According to Microsoft's **Digital Defense Report 2025** (Microsoft's annual global threat intelligence report):
- **AI-generated fake identities grew 195% globally** in the past year.
- **"ClickFix"** - a technique where a fake pop-up tricks a user into copying and pasting a malicious command into their own computer, became the single most common way attackers gained initial access, showing up in **47% of cases** Microsoft's incident responders investigated.
- **AI-crafted phishing emails now achieve a 54% click-through rate, 4.5 times more effective than traditional phishing - and can make an attack up to 50 times more profitable.**

---

## Section 5: Real-World Examples

### Global Example: The $100 Million Google & Facebook Scam (2013-2015)

Between 2013 and 2015, a Lithuanian man named **Evaldas Rimasauskas** set up a fake company impersonating **Quanta Computer**, a real Taiwan-based hardware supplier that both Google and Facebook actually did business with. He sent convincing fake invoices, contracts, and emails to accounting staff at both companies, who wired payments believing they were paying a legitimate supplier. By the time it was caught, **Google had paid out $23 million and Facebook had paid $99 million, over $100 million combined.** Rimasauskas was extradited to the U.S. and pleaded guilty in 2019. Facebook recovered most of its funds; this remains one of the largest publicly confirmed phishing/BEC cases in history. (U.S. Department of Justice, via NBC News and CNBC court reporting, 2019)

**Why this example matters:** it shows that phishing isn't just a threat to individuals or small businesses, even two of the world's largest technology companies, with enormous security resources, were successfully deceived, because the attack targeted people and processes rather than technical systems.

### Nigeria Example: The $60 Million "Mike" BEC Network (2016)

In 2016, INTERPOL and Nigeria's **Economic and Financial Crimes Commission** (**EFCC** - Nigeria's federal agency responsible for investigating financial crimes) jointly arrested a 40-year-old Nigerian man known as "Mike" in Port Harcourt. He led a network of at least 40 people across Nigeria, Malaysia, and South Africa that compromised business email accounts and ran BEC scams totaling **more than $60 million** from victims in Australia, Canada, India, Malaysia, Romania, South Africa, Thailand, and the U.S. including one company that alone paid out $15.4 million. (INTERPOL official press statement, 2016)

*(Note: this case is from 2016, it is real and well-documented, but should not be presented as a recent event.)*

### Current Nigeria Example: "DeepLoad" Malware Warning

Nigeria's **National Information Technology Development Agency** (**NITDA** - the government agency responsible for regulating and securing Nigeria's IT sector) issued an active warning about "DeepLoad," an AI-enhanced malware spread through fake website error messages that trick users into pasting a malicious command into their own computer. It targeted Nigerian banks, government agencies (including the EFCC and the Corporate Affairs Commission), and individuals, and can steal banking logins, mobile money credentials, and stored passwords. This is a form of **baiting**, the fake error message is the bait that gets someone to run the harmful command themselves. (NITDA public advisory, via Premium Times Nigeria)

---

## Section 6: Best Practices

1. **Never share passwords, PINs, or one-time passcodes** with anyone by email, text, or phone, no legitimate organization will ever ask for these.
2. **Verify independently.** If a message claims to be from your bank, call the number printed on your card, never the number given in the suspicious message itself.
3. **Hover before you click**, and type known website addresses directly into your browser instead of clicking links or search ads.
4. **Enable multi-factor authentication (MFA)** - a second layer of login security beyond just a password, on every account that offers it.
5. **Keep software updated** and use a unique password for each account.
6. **If you think you've been scammed:** disconnect that specific device from the internet right away. This stops further data from leaving it, but doesn't undo the compromise, you still need to change your passwords from a different, secure device and report it immediately to your bank and to the relevant authority.

### How to report in Nigeria specifically

- **EFCC** - report financial fraud and BEC scams at efcc.gov.ng
- **NITDA** - report data privacy breaches and malware threats at nitda.gov.ng
- **Nigeria Police Force Cybercrime Unit** - report general cybercrime, including hacking and impersonation
- **Your bank's fraud hotline** - report unauthorized transactions immediately

---

## Section 7: Interactive Quiz

**Q1.** An email from `security@yourb4nk.com` says your account will be suspended in 24 hours unless you click a link to verify your identity. What should you do?
*Answer: Delete it. The domain "yourb4nk.com" uses a "4" instead of an "a", a classic lookalike domain. Don't click anything. Call your bank directly using the number on your card, never the number in the message.*

**Q2.** What is the most reliable sign of a phishing email today?
*Answer: A sense of urgency and threatened consequences, not spelling mistakes, since AI now writes flawless phishing emails too.*

**Q3.** What is "pretexting"?
*Answer: Creating a false identity or story to gain someone's trust.*

**Q4.** A colleague's email is hacked, and you get a message from their real account asking you to urgently wire money to a "new vendor." What is this called?
*Answer: Business Email Compromise (BEC).*

**Q5.** True or False: a padlock icon and "https://" in a web address always mean a website is safe.
*Answer: False - it only means the connection is encrypted, not that the site is trustworthy.*

**Q6.** You think you just entered your banking password on a fake website. What's the right first step?
*Answer: Change your passwords immediately from a different, secure device, then contact your bank and report the incident.*

---

## Section 8: Key Takeaways

1. Phishing succeeds by exploiting emotions, urgency, fear, trust. Not by hacking software.
2. AI has made old advice like "check for bad grammar" unreliable; check the sender's actual address and the message's intent instead.
3. Always verify requests through a separate, trusted channel, never the contact info given in the suspicious message.
4. No legitimate organization will ever ask for your password or OTP directly.
5. Even the largest, best-resourced companies (Google, Facebook) have fallen for phishing, everyone is a potential target.

---

## References

- FBI Internet Crime Complaint Center (IC3). 2024 Internet Crime Report. ic3.gov
- Anti-Phishing Working Group (APWG). Phishing Activity Trends Reports, Q1-Q2 2025. apwg.org
- Microsoft. Digital Defense Report 2025. microsoft.com/security
- INTERPOL. Press statement on the 2016 Nigerian BEC network arrest. interpol.int
- U.S. Department of Justice; NBC News; CNBC. Rimasauskas wire fraud case reporting (2017-2019).
- NITDA (National Information Technology Development Agency, Nigeria). DeepLoad malware advisory. Via Premium Times Nigeria.
