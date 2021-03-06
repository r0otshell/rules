[![Build Status](https://travis-ci.org/Yara-Rules/rules.svg)](https://travis-ci.org/Yara-Rules/rules)

# Project

This project covers the need of a group of IT Security Researchers to have a single repository where different Yara signatures are compiled, classified and kept as up to date as possible, and began as an open source community for collecting Yara rules. Our Yara ruleset is under the GNU-GPLv2 license and open to any user or organization, as long as you use it under this license.

Yara is becoming increasingly used, but knowledge about the tool and its usage is dispersed across many different places. The Yara Rules project aims to be the meeting point for Yara users by gathering together a ruleset as complete as possible thusly providing users a quick way to get Yara ready for usage.

We hope this project is useful for the Security Community and all Yara Users, and are looking forward to your feedback. Join this community by subscribing to our mailing list.

# Contribute

If you’re interested in sharing your Yara rules with us and the Security Community, you can join our mailing list, send a message to our Twitter account or send a pull request here.

Twitter account: https://twitter.com/yararules

Mailing list : http://list.yararules.com/mailman/listinfo/yararules.com.signatures

# Requirements

Yara **version 3.0** or higher is required for most of our rules to work. This is mainly due to the use of the "pe" module introduced in that version. 

You can check your installed version with `yara -v`

Packages available in Ubuntu 14.04 LTS default repositories are too old.  You can alternatively install from source or use the packages available in the [Remnux repository](https://launchpad.net/~remnux/+archive/ubuntu/stable).

Also, you will need [Androguard Module](https://github.com/Koodous/androguard-yara) if you want to use the rules in the 'mobile_malware' category.

# Categories

## Anti-debug/Anti-VM

In this section you will find Yara Rules aimed toward the detection of anti-debug and anti-virtualization techniques used by malware to evade automated analysis.

## CVE_Rules

In this section you will find Yara Rules specialised toward the identification of specific Common Vulnerabilities and Exposures (CVEs)

## Crypto

In this section you will find Yara rules aimed toward the detection and existence of cryptographic algorithims.

## Exploit Kits

In this section you will find Yara rules aimed toward the detection and existence of Exploit Kits.

## Malicious Documents

In this section you will find Yara Rules to be used with documents to find if they have been crafted to leverage malicious code.

## Malware 

In this section you will find Yara rules specialised toward the identification of well-known malware.

## Packers

In this section you will find Yara Rules aimed to detect well-known sofware packers, that can be used by malware to hide itself.

## Webshells

In this section you will find Yara rules specialised toward the identification of well-known webshells.

## Email

In this section you will find Yara rules specialised toward the identification of malicious e-mails.

## Malware Mobile

In this section you will find Yara rules specialised toward the indentification of well-known mobile malware.

Many rules in this section use the Androguard module developed by the people over at https://koodous.com/. 

You can get it, along with installation instructions, at https://github.com/Koodous/androguard-yara

# Contact 

Webpage: http://yararules.com

Twitter account: https://twitter.com/yararules

Mail list : http://list.yararules.com/mailman/listinfo/yararules.com.signatures
