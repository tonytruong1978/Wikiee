
## Authentication, Authorization and Accounting 
#
#### Abbreviation. AAA
##
#### Definition
**AAA** stands for authentication, authorization, and accounting. AAA is a framework for intelligently controlling access to computer resources, enforcing policies, auditing usage, and providing the information necessary to bill for services. These processes working in concert are important for effective network management and security.

**Authentication**
Authentication provides a method of identifying a user, typically by having the user enter a valid username and password before access to the network is granted. Authentication is based on each user having a unique set of login credentials for gaining network access. The AAA server compares a user's authentication credentials with other user credentials stored in a database. If the user's login credentials match, the user is granted access to the network. If the credentials don't match, authentication fails and network access is denied.

**Authorization**
Following authentication, a user must gain authorization for doing certain tasks. After logging in to a system, for instance, the user may try to issue commands. The authorization process determines whether the user has the authority to issue such commands. Simply put, authorization is the process of enforcing policies—determining what types or qualities of activities, resources, or services a user is permitted. Usually authorization occurs within the context of authentication. After you have authenticated a user, they may be authorized for different types of access or activity. As it relates to network authentication via RADIUS and 802.1x, authorization can be used to determine what VLAN, Access Control List (ACL), or user role that the user belongs to.

**Accounting**
The final piece in the AAA framework is accounting, which monitors the resources a user consumes during network access. This can include the amount of system time or the amount of data sent and received during a session. Accounting is carried out by logging session statistics and usage information. It is used for authorization control, billing, trend analysis, resource utilization, and planning for the data capacity required for business operations.
Synonym(s) and related terms.
##
#### Note.
##
#### Reference(s).

[https://searchsecurity.techtarget.com/definition/authentication-authorization-and-accounting](https://searchsecurity.techtarget.com/definition/authentication-authorization-and-accounting)
