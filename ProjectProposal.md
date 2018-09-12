# Project Proposal
**CSCI - 8420:  Assurance Army**

Aaron Kirby, Krishna Teja Ayinala, Sindhura Bonthu          

**Security needs in intended threat environment:** *Kirby*


**Motivation for selecting this project:** *Krishna*

The primary constarints we had to identify the scope while choosing a project are: </br>
(a)the language a project is developed on,</br>
(b)the possibility of  security issues,</br>
(c)the current hit rate and scope of the project.

Refering to the first constraint (a), 
Nuxeo platform,  is a project developed using Java. Every person in the team is more or less comfortable with Java. The server side code is Java. Tool support is widely available for Java.

Refering to the second constraint (b),
The project offers security for the documents and the content.There are various kinds of permissions to stakeholders(User-level permissions/ Group-level permissions) either to read, edit or both. There is authentication. We believe this kind of permissions and authentications provide us a chance to assure the security of content.

Refering to the third constraint (c),
The project is active, with decent number of pull requests, releases and commits. The project accepts contribution. The project has very detailed documentation, which helps us as a guide throuh out the project. 

**Open source project description:** *Krishna*

(What is Nuxeo Platform)</br>
Nuxeo platform is an open source project, which provides content management platform for building business applications. It provides software artifacts and tools that allow to build, operate and maintain advanced content management applications. It is an open development model with great documentation and great visibility on product evolutions that enables you to quickly reach a high level of expertise.

Main components of the Nuxeo platform are:</br>
Nuxeo Server: It is the most important asset, which embeds a fully featured repository, a content transformation grid and a workflow engine.</br> 
Nuxeo Web UI: It is a flexible content browser that facilitates perform all provided features.</br>
Nuxeo Drive: It facilitates to map Nuxeo repository's content to a desktop file system.</br>
Build, QA and perform analysing tooling: It uses all the open source tools to build, maintain and test the software artifacts.</br>
Nuxeo Studio and Nuxeo CLI: Nuxeo Studio is an online application where we can perform content modelling, business logic and UI design.  Nuxeo CLI is a command line tool for helping developers bootstrap their custom modules.</br>

Features:</br>
a)If you need a headless scalable document repository with rich apis and data structures.</br>
b)If you need a turnkey application for managing assets (description, validation, publishing) with still ability to strongly customize it.</br>
c)If you want to build a custom UI upon the repository and want to benefit from our rich library of UI elements to accelerate the development of your project.  </br>

Technical Overview(Languages used & platform):</br>
Languages and configuration: Most of the server side code is written in java.  The Web UI is written in JavaScript.Application can be configured using Nuxeo Studio, an online development environment. The Nuxeo's 

Contributors & Activity: </br>
It has 88  active contributors. The project is active with 36,317 commits, 526 releases and with the fork count of 161.

Use and popularity:</br>
More than 500 brands so far are increasingly choosing Nuxeo platform to drive digital assets, enterprise content, and insights into the feature, across multiple domains like: Aerospace, Defense & Security, Retail, Business Services, Government, etc.. more information on use at: https://www.nuxeo.com/customers/  .  Nuxeo is names a Visionary by Gartner at 2017 Gartner Magic Quadrant for Content Services Platforms.

Documentation sources: </br>
The detailed doumentation to the Nuxeo platform is available at: https://doc.nuxeo.com/

**License, procedures for making contributions, and contributor agreements:** *Kirby*

All code committed in Nuxeo repositories must be licensed under the Apache License, Version 2.0, or a compatible license (LGPL 2.1, Eclipse, CDDL) if importing code with a third-party copyright. 

https://doc.nuxeo.com/corg/copyright-and-license-headers/

This page lists the .txt files that detail the licenses and contributor agreements. Most of the source code, other than what was opensourced, is copyright Nuxeo and contributors.

https://github.com/nuxeo/nuxeo/tree/master/licenses

This documentation spells out all of the procedures, testing, formatting, and other rules involved in writing code and submitting a pull request.

https://doc.nuxeo.com/corg/coding-and-design-guidelines/

This is the part of the documentation specifically pertaining to pull requests.

https://doc.nuxeo.com/corg/code-review-guidelines/

**Security features in the software:** *Sindhura*

Authentication - Nuxeo platform requires users to create an account and login. The password has some regex conditions in order to ensure the complexity. It also provides access to anonymous users whose access can be restricted to few folders and perform few actions as specified (User Permissions).
Apart from login page, Nuxeo enables user authentication using the following protocols:
Nuxeo Built-in protocols:
Basic Authentication, Token Authentication, OAuth2, Trusted, Kerberos, CAS/CAS 2.0, NTLM
Add-Ons:
SAML 2.0, Nuxeo Duo Web Two-Factor Authentication, OpenID
Sensitive Configuration Data Encryption – Nuxeo provides the advantage to encrypt the sensitive data to avoid clear data in the configuration files. The encryption can be done in any of the following ways: the key generated by server, custom secret key, key from key store, using ciphering algorithms (AES, DES). The passwords can be stored in the bit-format rather than the string-format.
Avoids Brute Force – The crypto container is self-destroyed on the first decryption attempt with the wrong password and the server will immediately lose all the sensitive data if some hosted code tries to crack encrypted key.


**Summary of security related history:** *Sindhura*

Github:  https://github.com/kteja-ayinala/SW-Assurance-Term-Project

Version Control System: https://github.com/kteja-ayinala/SW-Assurance-Term-Project/projects

Reference: Project link: https://github.com/nuxeo