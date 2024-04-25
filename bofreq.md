# Name: Network Attestation for Secure Routing (NASR)
## Description 

Traffic signing and encryption has been insofar the primary method to ensure data confidentiality, integrity and authenticity. However, an increasing amount of attacks, vulnerabilities, and new emerging requirements are deeming the data security provided by such methods insufficient.

Clients with high security and privacy requirements are not anymore satisfied with pure encryption-based data security measures in the application or transport layer that do not allow any control over the underlay networks. Clients now require their data to traverse exclusively through trusted devices, trusted operating environments, trusted links and trusted services, avoiding any exposure to insecure or untrusted devices. Hence, how to establish routing trustworthiness and transparency so as to achieve predictable forwarding behaviors becomes the main challenge. 

The goal of Network Attestation for Secure Routing WG is to address the challenges associated with routing data on top of trusted devices, trusted operating environments, trusted links and trusted services only, so as to achieve transparent and predictable forwarding behavior. Verifiable operational correctness proofs should also be given to serve as a trusted evidence for visualization, internal inspection and external auditing.

NASR BoF was previously discussed as NASR Side Meeting at [IETF 119](https://github.com/liuchunchi/nasr_side_meeting) and Path Validation Side Meeting at [IETF 118](https://github.com/liuchunchi/nasr_side_meeting/tree/afeecf7f3ac5a5a796e3e7c9eae14d7a4a41c757/IETF%20118%20Path%20Validation%20Side%20Meeting%20Archive).

## Required Details
- Status: Non-WG Forming
- Responsible AD: TBD
- BOF proponents: Chunchi (Peter) Liu liuchunchi@huawei.com, Diego Lopez diego.r.lopez@telefonica.com, Meiling Chen chenmeiling@chinamobile.com, Michael Richardson mcr@sandelman.ca
- BOF Chairs: TBD
- Number of people expected to attend: ~100
- Length of session (1 or 2 hours): 2 hours
- Conflicts (whole Areas and/or WGs)
   - Chair Conflicts: RATS
   - Technology Overlap: SAVNET, IDR, SIDROPS
   - Key Participant Conflict: TBD

## Information for IAB/IESG

RATS (Remote Attestation Procedures) working group has provided a framework and approaches to assess and establish the trustworthiness of a single device. Several individual submissions are also offering part of the solution to achieve NASR goal. However, a comprehensive framework that allows network trust appraisal, trust-aware routing or packet steering, and provide verifiable proof of forwarding, remains elusive. 

The proponents believe that a new working group is required, but our request is for a non-WG forming BOF. Despite this we are actively working on draft charter text, proposed architecture and other potential deliverables as much as possible before and at this BOF.

## Agenda
   - TBD

## Links to the mailing list, draft charter if any, relevant Internet-Drafts, etc.
   - Mailing List: https://www.ietf.org/mailman/listinfo/nasr
   - Draft charter: https://github.com/liuchunchi/NASR-charter
   - Relevant Internet-Drafts:
      - NASR Use Cases, Problem Statement and Requirements:
         - https://datatracker.ietf.org/doc/draft-liu-nasr-requirements/
