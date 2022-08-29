# MTS ODK Importer

## Overview

MTS ODK Importer (MOI) is a OpenG2P module which will be an addon to [Odoo](https://www.odoo.com/).  MOI will help in fetching the tokenized data from the ODK Central by calling the [MOSIP Token Seeder](./) (MTS) and store the same in beneficiary registry. This will be an important module in deduplication process when OpenG2P system is using MOSIP as its id platform. &#x20;

Features of MOI

* Generates MOSIP token while fetching from the ODK
* Uses callback delivery type of MTS
* &#x20;Completely asynchronous execution
* OpenG2P can schedule a daily job to fetch the delta for the day
* A manual import feature will also be provided



<figure><img src="https://raw.githubusercontent.com/mosip/openg2p/main/docs/_images/mosip-token-seeder-odk-importer.png" alt=""><figcaption></figcaption></figure>

## Input

In OpenG2P, the user can configure for following fields to setup a interface with MTS.

* Odata url (svc)
* Base url (domain name)
* Version
* Project Id
* Form Id
* Email
* Password
* MTS authtoken api url
* Callback url
* Callback auth url
* Callback auth username
* Callback auth password



