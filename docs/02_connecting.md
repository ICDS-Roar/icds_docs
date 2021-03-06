---
title: Connecting to ICDS Compute Resources
---

The Roar systems are available for all users with Penn State access. Non-Penn 
State members who are collaborating with Penn State researchers are able to get 
a Penn State SLIM access account and then sign up for a Roar account.

### 2.1 Setting up a Roar Account

To apply for an ICDS account, please complete our new user form.

Please note: Each non-faculty member signing up for an account must have a 
sponsor (specified by a PSU ID. If the PSU ID is not known, please use the 
[Penn State directory](http://www.work.psu.edu/ldap/) to locate it). This is 
typically the adviser or course instructor.

The sponsor will get an email stating they were listed as a sponsor. The faculty 
member can respond to the iAsk center ([<span class="cmtt-10">iAsk@ics.psu.edu</span>]
(mailto:iAsk@ics.psu.edu)) with either explicit approval or a denial. If no 
denial is given, the student or staff member will be granted implicit approval 
after two business days. Faculty members can send an email with multiple users 
if they will be sponsoring multiple accounts, such as for a class project. 

After an account has been approved, it can take up to twenty-four hours before 
the system updates and the user is able to login.  

#### 2.1.1 Accounts for Outside Collaborators

Users who do not have Penn State ID but are collaborators from other institutions need to acquire a Penn State SLIM account before they sign up for a Roar account and Duo. To request SLIM account, please follow these [instructions](https://www.icds.psu.edu/computing-services/account-setup/).  

You will need to wait for your SLIM access account to be created before you can proceed to request your Roar account or sign up for two-factor authentication.

#### 2.1.2 Adding an existing user to an existing SLA

To gain access to an allocation or a group storage, have the PI send an email to the i-ASK Center ([iask@ics.psu.edu](mailto:iask@ics.psu.edu)) stating the user IDs (ex. abc123) and the allocation(s) and group storage(s) you wish to add them to. Explicit permission must be granted before access is granted.

The users who have access to an allocation are placed in an allocation group. Users can see all of the groups they are in by using the `id` command.

### 2.2 Connecting to Roar

Roar is a heterogeneous cluster that consists of multiple node-types connected to a common file system. The primary portions are ACI-b, the batch portion of the cluster; ACI-i, the interactive portion; and the data-manager nodes.

**ACI-b**, the batch portion of Roar, is used to submit jobs to dedicated resources 
and is connected to by using a Secure SHell (SSH) connection.

**ACI-i** provides a set of interactive cores that are configured as common GUI interactive systems. ACI-i is a shared resource where users are placed on an interactive node with other users. ACI-i is accessable via our web-based Open OnDemand portal.

Often ACI-i is used to develop and test small scale test cases due to the ability to use a graphical user interface. Once the model has been developed, it can be submitted as a job to ACI-b to take advantage of the greater computational resources available on ACI-b.  

#### 2.2.1 Connecting to ACI-i

ACI-i, or interactive sessions on Roar, can be accessed by visiting [http://portal.aci.ics.psu.edu/](portal.aci.ics.psu.edu/) in your web browser and
logging in with your ICDS credentials.

#### 2.2.2 Connecting to ACI-b

ACI-b, the batch portion of Roar, is used to submit jobs to dedicated resources 
and has the host name:

`submit.aci.ics.psu.edu`

For users with Linux or MacOS systems, you can use the built in terminal to connect. 

For Windows users, you may need to install an SSH client. Suggested clients include:
- [PuTTY](https://www.putty.org/)
- [MoabXTerm](https://mobaxterm.mobatek.net/)



