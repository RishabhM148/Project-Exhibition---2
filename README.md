# Project-Exhibition---2

# InfinityVault

![JAVA Version](https://img.shields.io/badge/java-8-ornge?style=for-the-badge&logo=java)
![OS](https://img.shields.io/badge/OS-GNU%2FLinux-red?style=for-the-badge&logo=linux)
![Platform](https://img.shields.io/badge/androidstudio-4.1+-green?style=for-the-badge&logo=androidstudio)


We made the decision to improve on two-factor authentication in light of updated security measures.
A mobile application that uses real-time OTPs and dynamic passwords to protect users' privacy across all of the apps on their devices.
This offers local consumers brand-new banking level services derived from open-sources.


## Demo
![app_demo](https://user-images.githubusercontent.com/15611424/178045423-067df4ec-1853-400e-9b5a-10154cb6fcc1.gif)

## Running the Application
### I. Login Phase

1. Setup the Project - 
Once you have the project’s code on your computer, you need toinstall its dependencies by moving into the project’s folder andtyping the following command: `npm install`

2. Configure the Application - 
allow you to assign phone numbers and/or links to external accounts for services like messenger, whatsApp, or viber so that you can send SMS or messages through the message and Dispatch API.

3. Configure the OTP Service- 
Once you have configure, you have to configure the OTP serviceside in order to make them communicate with each other.

4. Running OTP Service - 
It’s time to run your OTP service. If everything is OK, you shouldsee the message *“This is the OTP service”*.

5. Request OTP Service - 
The OTP service will generate an OTP composed of 5 digits and will send it to the specified Messenger identifier. If the user doesn’t read it within a given amount of time, the OTP will besent via SMS to the phone number.

6. Verifying the OTP Service - 
Regardless of the medium by which the message was received,the user should verify the OTP by submitting a `GET` request to the second `API`

## Know More at
```
https://www.canva.com/design/DAE1Cb78zEQ/olBTkJKiuZHt7czOkuU_Ww/view?utm_content=DAE1Cb78zEQ&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink
```

## Legal Disclaimer
The use of code contained in this repository, either in part or in its totality,
for engaging targets without prior mutual consent is illegal. **It is
the end user's responsibility to obey all applicable local, state and
federal laws.**

Developers assume **no liability** and are not
responsible for misuses or damages caused by any code contained
in this repository in any event that, accidentally or otherwise, it comes to
be utilized by a threat agent or unauthorized entity as a means to compromise
the security, privacy, confidentiality, integrity, and/or availability of
systems and their associated resources. In this context the term "compromise" is
henceforth understood as the leverage of exploitation of known or unknown vulnerabilities
present in said systems, including, but not limited to, the implementation of
security controls, human- or electronically-enabled.

The use of this code is **only** endorsed by the developers in those
circumstances directly related to **educational environments** or
**authorized penetration testing engagements** whose declared purpose is that
of finding and mitigating vulnerabilities in systems, limiting their exposure
to compromises and exploits employed by malicious agents as defined in their
respective threat models.
