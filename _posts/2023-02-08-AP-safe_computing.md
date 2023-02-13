---
toc: true
comments: false
layout: post
title: Big Idea 5.6 Safe Computing
description: This tech talk discusses safe computing
permalink: /safe
categories: [5.D, 5.E]
type: ap
week: 22
---

# Safe Computing

### Personal Identifiable Information (PII)
As we create a Web Site and post information we are adding to the Searchable PII.  However, there is a dichotomy as a site ***like LinkedIn is a place where we want to be known for our accomplishments***.  But be aware, the person that looks at your LinkedIn will, **most likely**, look at things like TikTok, Instagram or Facebook.  

### PII considerations
* Things that will be known by everyone:  Name, Email (suggest a junk email), Picture, High School attended, College Attended, Properties you own, State-City of residence, all State-City of previous residence, Credit Reports, ... 
* Gray area items, more cautious: Birth date, Place of Birth, Street Address, Phone Number, Maiden names of Mother and Grandmother, Drivers License Number, ...
* Things that you should strive to keep absolutely secret: Credentials for Access, Two-Factor Authentication on Financial accounts, Social Security Number, Tax records, ...

### Beware, Establish practices for your own Safety
* ***Multi-factor authentication*** often requires you to enter a code that has been texted or emailed to you.   Other types of authentication are biometrics (finger print or facial recognition).
* ***Malware*** is often sent in attachments to things in email.  Often they request you to click on an attachment and it starts the process of adding a virus to your computer.
* ***Phishing*** is where unknown sources try to entice you into a response, like click here and receive $500.  Often such systems impersonate someone like Amazon asking for login information.  Be careful to look closely at source of email (ie amzn.com vs amazon.com).

### Factors to Increase Security of System (**recommend** Watch 5.6 Video 2)
* Most of my financials or critical systems use **Multi Factor authentication**
* Biometrics is something that is used secure systems, fingerprints or facial recognition
* ***Symmetric*** encryption is a type of encryption where only ***one key (a secret key)*** is used to both encrypt and decrypt electronic information.
* ***Asymmetric cryptography***, also known as public-key cryptography, is a process that uses a pair of related keys -- ***one public key and one private key*** -- to encrypt and decrypt a message and protect it from unauthorized access or use.
* SSL Uses both Asymmetric and Symmetric Encryption

### Nefarious Uses of Internet
* A Virus or Malware compromise security, they are opposite of increasing security.  
* Phishing is a way to get a Virus on your machine, or a way to get you to input PII.
* After a Virus or being compromised by Phishing it is advised to review all of you PII vulnerabilities.

## Blog Post Reflection:
1. Describe PII you have seen on project in CompSci Principles.
     I have seen multiple projects that ask for some sort of personal information through the creation of accounts.
2. What are your feelings about PII and your personal exposure?
     I believe that PII are an important aspect of our internet activities. Most of our web services rely on such PII’s for providing us with the best quality and experience.
3. Describe good and bad passwords?  What is another step that is used to assist in authentication.
     Good passwords typically have certain safety measures, such as a set minimum password length, a mix of numbers and letters, mixed-cases for alphabetical characters, as well as other special symbols.
4. Try to describe Symmetric and Asymmetric encryption.  
     In symmetric encryption, only one secret key is used to encrypt and decrypt encrypted content. In asymmetric encryption public and private keys are used in order to encrypt and decrypt.
5. Provide an example of encryption we used in AWS deployment.
     Encryption that we used in AWS deployment is SSL encryption, which uses a mix of both symmetric and asymmetric encryption methods. We have also previously generated RSA keys too for our SSH deployment keys when we set up the project.
6. Describe a phishing scheme you have learned about ***the hard way***.  Describe some other phishing techniques.
     I have never been phished, but I have gotten many emails claiming to be from big businesses, or people in need that can give me a large sum of money after I send them $50 or something along those lines. Mainly, these techniques impersonate someone else to gain the victim's trust.