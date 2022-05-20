# Regularly Backup Important Data and Systems

([Back](#guidelines))

## Objective

Perform offline back-ups of systems that contain important data and ensure that recovery mechanisms effectively and efficiently restore these systems from back-ups.

## Description

- Carefully plan, implement, and test a data backup and restoration strategy for important files/data and systems that can be restored in the event of an incident.
- Securely store back-ups in an encrypted state and restrict access to them to only those who must access them for testing or restoration activities.
- Make multiple copies of files using different backup solutions and storage locations (e.g., in a different data center or cloud tenancy).
- Ensure that backups are only connected to known clean devices before starting recovery.
- Scan backups for malware before restoring files in the case that ransomware may have been replicated to backups before being discovered.

## References

Treasury Board of Canada Secretariat (TBS)

1. Directive on Service and Digital (DSD), [Appendix G: Enterprise IT Service Standards](https://www.gcpedia.gc.ca/gcwiki/images/2/2a/Appendix_G_-_Standard_on_Enterprise_IT_Service_Common_Updates_-_20210924.pdf) (Appendix G) [- System Management Configuration Requirements (6 and 7)](https://www.gcpedia.gc.ca/gcwiki/images/1/1e/System_Management_Configuration_Requirements.pdf)
2. Directive on Security Management (DSM) [Appendix B](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32611&section=procedure&p=B#appB) (B.2.3.7.5 and B.2.3.10),
3. [DSM Appendix C](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32611&section=procedure&p=C#appC) (C.2.3.2), and
4. [DSM Appendix D](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32611#appD) (D.2.2.3 and D2.2.2.6)

Canadian Centre for Cyber Security (CCCS)

1. [Ransomware Playbook (ITSM.00.099)](https://cyber.gc.ca/en/guidance/ransomware-playbook-itsm00099) (2.1.1, 2.1.2, 2.1.3 and 3.1.2.2)
2. [Tips for Backing up Your Information (ITSAP.40.002)](https://www.cyber.gc.ca/en/guidance/tips-backing-your-information-itsap40002)
3. [Departmental IT Security Risk Management Activities (ITSG-33)](https://www.cyber.gc.ca/sites/default/files/publications/itsg33-ann1-eng.pdf)

## Related Security Controls (ITSG-33)

CP-6, CP-6(1), CP-9, CP-9(1), CP-9(3), CP-9(5), CP-9(6), SC‑13, SC‑28, SC‑28(1), SC‑28(2)
