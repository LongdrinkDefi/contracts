## Longdrink Finance's Security Process

This document describes the Security Process for Longdrink Finance, including vulnerability disclosures and its [Bug Bounty program](#bug-bounty-program). We are committed to conduct our Security Process in a professional and civil manner. Public shaming, under-reporting, or misrepresentation of vulnerabilities will not be tolerated.

To submit a finding, please follow the steps outlined in receiving disclosures [section](#receiving-disclosures).

## Responsible Disclosure Standard

Longdrink Finance follows a community [standard](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#the-standard) for responsible disclosure in cryptocurrency and related software. This document is a public commitment to
following the standard.

This standard provides detailed information for:

- [Initial Contact](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#initial-contact): how to establish initial contact with Longdrink Finance's security team.
- [Giving Details](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#giving-details): what details to include with your vulnerability disclosure after having received a response to your initial contact.
- [Setting Dates](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#setting-dates): how to agree on timelines for releasing updates and making details of the issue public.

Any expected deviations and necessary clarifications around the standard are explained in the following sections.

## Receiving Disclosures

Longdrink Finance is committed to working with researchers who submit security vulnerability notifications to us, to resolve those issues on an appropriate timeline, and to perform a coordinated release, giving credit to the reporter if they would so like.

Please submit issues to **all** of the following main points of contact for
security related issues according to the
[initial contact](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#initial-contact)
and [giving details](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#giving-details)
guidelines.

For all security related issues, Longdrink Finance has two main points of contact:

| Contact | Public key | Email |
| --- | --- | --- |
| 0xBartender | [PGP](https://gist.github.com/bartenderdev/e3c001f73e4621f2b86091a89aface4d) | bartenderdev at protonmail.com |
| 0xSouschef | [PGP](https://gist.github.com/0xsouschef/02feb5a4a166e602c8d1e6053f604cbe) | 0xsouschef at protonmail.com |

Include all contacts in your communication, PGP encrypted to all parties.

## Sending Disclosures

In the case where we become aware of security issues affecting other projects that has never affected Longdrink Finance, our intention is to inform those projects of security issues on a best effort basis.

In the case where we fix a security issue in Longdrink Finance that also affects the following neighboring projects, our intention is to engage in responsible disclosures with them as described in the adopted [standard](https://github.com/RD-Crypto-Spec/Responsible-Disclosure), subject to the deviations described in the deviations [section](#deviations-from-the-standard) of this document.

## Bilateral Responsible Disclosure Agreements

_Longdrink Finance does not currently have any established bilateral disclosure agreements._

## Bug Bounty Program

Longdrink Finance has a Bug Bounty program to encourage security researchers to spend time studying the protocol in order to uncover vulnerabilities. We believe these researchers should get fairly compensated for their time and effort, and acknowledged for their valuable contributions.

### Rules

1. Bug has not been publicly disclosed.
2. Vulnerabilities that have been previously submitted by another contributor or already known by the Longdrink Finance development team are not eligible for rewards.
3. The size of the bounty payout depends on the assessment of the severity of the exploit. Please refer to the rewards [section](#rewards) below for additional details.
4. Bugs must be reproducible in order for us to verify the vulnerability.
5. Rewards and the validity of bugs are determined by the Longdrink Finance security team and any payouts are made at their sole discretion.
6. Terms and conditions of the Bug Bounty program can be changed at any time at the discretion of Longdrink Finance.
7. Details of any valid bugs may be shared with complementary protocols utilized in the Longdrink Finance ecosystem in order to promote ecosystem cohesion and safety.

### Classifications

- **Severe:** Highly likely to have a material impact on availability, integrity, and/or loss of funds.
- **High:** Likely to have impact on availability, integrity, and/or loss of funds.
- **Medium:** Possible to have an impact on availability, integrity, and/or loss of funds.
- **Low:** Unlikely to have a meaningful impact on availability, integrity, and/or loss of funds.

### Rewards

- **Severe:** 10,000-25,000 BUSD
- **High:** 2,500-10,000 BUSD
- **Medium:** 500-2,500 BUSD
- **Low:** 100-500 BUSD

Actual payouts are determined by classifying the vulnerability based on its impact and likelihood to be exploited successfully, as well as the process working with the disclosing security researcher. The rewards represent the _maximum_ that will be paid out for a disclosure.

Rewards are paid out in [LONG](https://bscscan.com/address/0x5317fA16f8603bE9C461DeF5D5A1Bf28DfE42d55).

### Scope

The scope of the Bug Bounty program spans smart contracts utilized in the Longdrink Finance ecosystem. This mainly includes the contracts listed at:

- https://github.com/LongdrinkDefi/contracts


Note: Other contracts, outside of the ones mentioned above, might be considered on a case by case basis. Please reach out to the Longdrink Finance development team for clarification.

### Bug Bounty FAQ

**Q:** Is there a time limit for the Bug Bounty program?\
**A:** No. The Bug Bounty program currently has no end date, but this can be changed at any time at the discretion of Longdrink Finance.

**Q:** How big is the Bug Bounty program?\
**A:** There is currently a rolling \$50,000 bounty for bugs. This amount may be changed by a Longdrink Finance governance vote.

**Q:** How are bounties paid out?\
**A:** Rewards are paid out in BUSD.

**Q:** Can I submit bugs anonymously and still receive payment?\
**A:** Yes. If you wish to remain anonymous you can do so and still be eligible for rewards as long as they are for valid bugs. Rewards will be sent to the valid BSC address that you provide.

**Q:** Can I donate my reward to charity?\
**A:** Yes. You may donate your reward to a charity of your choosing, or to a gitcoin grant.

## Deviations from the Standard

The standard describes reporters of vulnerabilities including full details of an issue, in order to reproduce it. This is necessary for instance in the case of an external researcher both demonstrating and proving that there really is a security issue, and that security issue really has the impact that they say it
has - allowing the development team to accurately prioritize and resolve the issue.

In the case of a counterfeiting or fund-stealing bug affecting Longdrink Finance, however, we might decide not to include those details with our reports to partners ahead of coordinated release, as long as we are sure that they are not vulnerable.


## Credits

This document was inspired by [Yearn's security policy](https://github.com/yearn/yearn-security/blob/master/SECURITY.md).
