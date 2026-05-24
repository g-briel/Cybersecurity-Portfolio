# Python Automation: Access Control List (ACL) Management

## Project Description
This project demonstrates the practical application of Python to automate access control maintenance. In enterprise security, managing lists of permitted IP addresses (Allow Lists) is crucial for enforcing network boundaries. 

I developed a Python script that automates the removal of restricted or compromised IP addresses from an active 'allow_list.txt' file. Instead of manually editing text files, this script programmatically audits the file, filters out unauthorized assets, and updates the permissions dynamically.

## Skills Demonstrated
* **File Operations ('with open'):** Safely handling file I/O operations using both read ('"r"') and write ('"w"') modes to prevent file corruption.
* **Data Parsing:** Transforming unstructured file strings into manipulated list structures using '.split()' and reconstructing them back into file-ready strings using '.join()'.
* **Control Flow & Logic:** Leveraging 'for' loops and 'if' conditional statements to iterate through live datasets and selectively remove targeted security elements.

## How It Works
1. **Ingestion:** The script opens the target 'allow_list.txt' file and reads its contents into memory as a single string.
2. **Parsing:** The string data is split into a list of individual IP addresses.
3. **Filtering:** The script loops through the list. If an IP address matches an entry inside a predefined 'remove_list' (representing flagged or decommissioned assets), it is instantly stripped from the active list.
4. **Commitment:** The updated list is joined back into a standard string format and rewritten to the original text file, successfully updating the network access rules.
