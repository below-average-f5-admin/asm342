Lab 4.4: Modifying settings using Python 
-------------------------------------------

Task 1 - Using Python to move attack signatures out of staging 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This script uses PATCH to update each attack signature in a policy and move it out of staging.

Run the following script to disable staging on all signatures in the "python1" policy

.. code-block:: bash
        
        python3 /home/f5student/agility2018/python/Module4Lab4-ex1-takeAllSigsOutOfStaging.py

|

Wait until the script is finished, this will take several minutes.

Navigate to Security->Application Security->Attack Signatures, ensure the python1 policy is the "Current edited security policy"

Ensure the Staging column is set to "No" for the Attack Signatures. Looking at the first page is sufficient.

The instructor will talk through the script after all students have completed this task. Feel free to open the script to analyze it and run any of the curl commands to guide the student to the flow.
