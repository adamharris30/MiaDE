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

    Obtain License and Vulnerability Info: This process checks to see if there is any existing license and vulerability info within the License and Vulnerabilities DB. If there is it will provide the results back to the requesting party.

    Apply New Policies: This process is used by managers to put new policies into the Policy DB

    Set/Edit/Find Policies: This process does a handful of things. 1) A manager can find existing policies in the Policy DB. It sends information to the Find Policies process and then sends the results back to the manager. 2) If a manager wants to edit an existing policy, he/she will submit what policy he/she is looking for. This process then sends the information to the Find Policies process which finds the correct policy. Then, this process will update the policy based on what the manager provided, and then write it to the Policy DB

    Find Policies: This process takes the information provided from the Set/Edit/Find Policies process and searches within the Policy DB to see if that policy exits, and then returns the results.

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
