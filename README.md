# DynamicAccounts
This describes the idea of a software that autonomously handles client-side user account security on any website.

## What
DynamicAccounts would allow anyone to use the software to continuously monitor the safety and security of their online accounts.

#### Overview of abilities:

- Email and password managment (like keychain, bitwarden, etc)
- Autonomously changing linked passwords
- Autonomously changing linked email addresses
- Deletion of accounts
- Monitoring data breaches
- Responding to data breaches
- Dynamic email addresses


## Who
The software would be completely open-source, peer-reviewed, and independently audited. 
Anyone who can prove themselves trustworthy and also has a skillset related to the software would be allowed to contribute.


## Where
The user would have a few implementation options for DynamicAccounts:

  1. Use the DynamicAccount servers located in data respecting countries
  2. Locally deploy the software onto the user's own server
  3. As a P2P between the user's devices

DynamicAccounts would be available for use on macOS, iOS, Windows, Android, and Linux-based operating systems.


## When
As this is just an idea there is no "when"... as of yet.

## How
#### Base Functionality
The software would first and foremost act like your average password manager, auto-completion of login details on websites, applications, etc. The unique ability the software offers is explained below.

An AI would be trained to understand a broad range of programming languages, with a focused training on account related code. The objective of this training would be to teach the AI how to login, delete accounts, and pass whatever login challenges the AI receieves (with the obvious exception of reCAPTCHA).

Once the AI has been trained - and all other required functionality is coded - the user would give the software their login details for which ever websites/applications that user uses. All login details would be using 4096-bit encryption.

By enabling access to an account, the software (if the account allows) would be able to change passwords, emails, and other account details as needed, as well as being able to quickly delete the account if wanted by the user.

#### Data Breaches
The software would actively monitor data breaches on sources like [https://haveibeenpwned.com/](https://haveibeenpwned.com/). In the event that an account is linked to a data breach the software would immediately change the password and/or email if the software is given access, otherwise the software would immediately alert the user of the data breach.

#### Dynamic Email Addresses
DynamicAccounts would also offer an optional email address cloaking ability. 

When signing up for a service the software would generate a new email address for that particular service which would look similar to a hash code (e.g. 3g2upl4pq6kufc4m@dynaaccounts.ch). The software would forward any emails received by the hash-email to the users actual email. Any response from the user to the service would be sent to the hash-email and then directed to the service.

If the service linked to the hash-email allows, the software will change the linked hash-email and delete the old hash-email. Since there are 1.06 x 10^56 possible 36-character alphanumeric email addresses it is not necessary to recover deleted email addresses for later use by another user.

## Privacy
It is likely possible for no information about the user to be stored anywhere other than the user's devices. More thought would be required to figure this out, and would be bound to change during development of the software.
























