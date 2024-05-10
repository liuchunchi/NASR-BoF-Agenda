# Name: Network Attestation for Secure Routing (NASR)
## Description 

Traffic signing and encryption has been insofar the primary method to ensure data confidentiality, integrity and authenticity. However, an increasing amount of attacks, vulnerabilities, and new emerging requirements are deeming the data security provided by such methods insufficient.

Clients with high security and privacy requirements are not anymore satisfied with pure encryption-based data security measures in the application or transport layer that do not allow any control over the underlay networks. Clients now require their data to exclusively traverse the network through trusted devices, trusted operating environments, trusted links and trusted services, avoiding any exposure to insecure or untrusted devices. Hence, how to establish routing trustworthiness and transparency so as to achieve predictable forwarding behaviors becomes the main challenge. 

The goal of Network Attestation for Secure Routing WG is to address the challenges associated with routing data on top of trusted devices, trusted operating environments, trusted links and trusted services only, so as to achieve transparent and predictable forwarding behavior. Verifiable operational correctness proofs should also be given to serve as a trusted evidence for visualization, internal inspection and external auditing.

RATS (Remote Attestation Procedures) working group has provided a framework and approaches to assess and establish the trustworthiness of a single device. Several individual submissions are also offering part of the solution to achieve NASR goal. However, a comprehensive framework that allows network/path trust appraisal, attestation, trust-aware routing or packet steering, and provide verifiable proof of forwarding, remains elusive. 

NASR BoF was previously discussed as NASR Side Meeting at [IETF 119](https://github.com/liuchunchi/nasr_side_meeting) and Path Validation Side Meeting at [IETF 118](https://github.com/liuchunchi/nasr_side_meeting/tree/afeecf7f3ac5a5a796e3e7c9eae14d7a4a41c757/IETF%20118%20Path%20Validation%20Side%20Meeting%20Archive).

## Required Details
- Status: Non-WG Forming
- Responsible AD: TBD
- BOF proponents: Chunchi (Peter) Liu liuchunchi@huawei.com, Diego Lopez diego.r.lopez@telefonica.com, Meiling Chen chenmeiling@chinamobile.com, Michael Richardson mcr@sandelman.ca (confirmed until now)

- BOF Chairs: Luigi Iannone (ggx@gigix.net), Michael Richardson (mcr@sandelman.ca), Henk Birkholz (henk.birkholz@ietf.contact),... (Or others that ADs recommend)
- Number of people expected to attend: ~100
- Length of session (1 or 2 hours): 2 hours
- Conflicts (whole Areas and/or WGs)
   - Chair Conflicts: RATS, LISP, OPSAWG, IOTOPS
   - Technology Overlap: RATS, SAVNET, IDR, SIDROPS
   - Key Participant Conflict: OAUTH, SCITT, SPRING, RTGWG

## Information for IAB/IESG

The proponents believe that a new working group is required, but the request is for a non-WG forming BoF. However, the proponents, with the help of interested persons, are already actively working on various items, namely on a draft charter text, a proposed architecture document and other potential deliverables. Discussion on the progress on these items will be part of the agenda.

Due to the similarities between RATS and NASR, mainly related to the notions of trust, and also NASR's dependency on RATS outputs, NASR will work closely with RATS working group for collaboration and consultation. NASR will also take consideration of useful works from concluded working groups, such as I2NSF, SFC. NASR will also closely collaborate with:

- Other IETF Working Groups that address topics related to attestation and routing security, including but not limited to, RATS, SAVNET, SIDROPS, IDR, SPRING.
- Other IRTF Research Groups that provide research inputs and reviews, such as PANRG, CFRG.

## Agenda
   - To be updated

## Links to the mailing list, draft charter if any, relevant Internet-Drafts, etc.
   - Mailing List: https://www.ietf.org/mailman/listinfo/nasr
   - Draft charter: https://github.com/liuchunchi/NASR-charter
   - Ongoing Internet-Drafts:
      - NASR Use Cases, Problem Statement and Requirements:
         - https://datatracker.ietf.org/doc/draft-liu-nasr-requirements/
      - NASR Architecture: Design ongoing
   - Relevant Internet-Drafts:
      - https://datatracker.ietf.org/doc/draft-ietf-rats-ar4si/
      - https://datatracker.ietf.org/doc/draft-ietf-rats-corim/
      - https://datatracker.ietf.org/doc/draft-lopez-opsawg-yang-provenance/
      - https://datatracker.ietf.org/doc/draft-voit-rats-trustworthy-path-routing/
      - https://datatracker.ietf.org/doc/draft-ietf-sfc-proof-of-transit/
      - https://datatracker.ietf.org/doc/draft-liu-vcpot/

## Previous Discussions
   - Path Validation Side Meeting @[IETF 118](https://github.com/liuchunchi/nasr_side_meeting/tree/afeecf7f3ac5a5a796e3e7c9eae14d7a4a41c757/IETF%20118%20Path%20Validation%20Side%20Meeting%20Archive).
   - NASR Side Meeting @[IETF 119](https://github.com/liuchunchi/nasr_side_meeting)
   - First Chartering Team Meeting, 4.17 [Minutes](https://mailarchive.ietf.org/arch/msg/nasr/P1qOcLGKzFE9izLwtpKB-Crsg9M/)
   - Second Chartering Team Meeting, 5.15, Upcoming
   - Interim Meeting, 6.12, Upcoming
