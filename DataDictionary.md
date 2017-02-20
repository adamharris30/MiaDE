External Entities:

    Developer: The person developing and utilizing OSS in a program and checking for licenses and vulnerabilities within that source code

    Manager: The manager of the developer who checks for license and vulnerabilities and applies policies for software

Data Stores:

    NIST Vulnerability DB: The database that NIST manages, it contains vulnerabilities on OSS that has been published 

    License and Vulnerabilities DB: This database contains the license and vulnerability information obtained from NIST and the License Scanner process

    Policy DB: This database contains the policies that the manager(s) has applied to some software packages

Processes:

    Check for OSS Components: This process checks for OSS components within the package provided by the developer. It then sends out this information to the License Scanner and the NIST database. Last, it writes the information found to the License and Vulnerabilities DB
    
    License Scanner: This process takes the information provided from the Check for OSS Components and checks to see if there are any licenses associated with it.

    Obtain License and Vulnerability Info: 

    Apply New Policies: 

    Set/Edit/Find Policies:

    Find Policies:

Data Flows:
Software Package:
OSS Vulnerability Results:
OSS License Results:
Software Package Name:
L/V Info Request:
OSS License/Vulnerability Results:
New Policy:
Policy Request Results:
Policy Update Info:
Policy Search Info:
Policy Request:
