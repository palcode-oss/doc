![The PalCode Logo](https://i.ibb.co/wQGx00G/Pal-Code-logo.png)

# PalCode

Thanks for visiting PalCode's open-source repositories! Here's an outline of them:

![An outline of PalCode's repositories](https://i.ibb.co/sv19z7h/PalCode.png)

* https://github.com/palcode-oss/palcode.dev
* https://github.com/palcode-oss/api
* https://github.com/palcode-oss/runner
* https://github.com/palcode-oss/sockets
* https://github.com/palcode-oss/images
* https://github.com/palcode-oss/container-init

That's all there is to PalCode — all development takes place on GitHub, and we never keep any code from the public.

Theoretically, you should also be able to set this environment up on self-hosted infrastructure (or on a public cloud like GCP or AWS). A complete guide on how to do this will be written soon.

## Contributing
If you'd like to make a contribution, please fork the relevant repository and open a pull request in it when you're ready to merge. Some repositories may have additional contributing policies — if so, please follow them.

### Bugs and feature requests
To report a bug or request a feature, simply [create a new issue in this repository](https://github.com/palcode-oss/doc/issues/new). To keep issue tracking streamlined, we only use this repository for issue tracking, and all other repositories have issue-tracking disabled. A maintainer will triage your issue and decide which repositories it affects.

### Security disclosures
If you suspect that a vulnerability in PalCode's source code or infrastructure could be affecting current users, please make a responsible disclosure by emailing [security@palcode.dev](mailto:security@palcode.dev).

Someone will reply to your email within 48 hours having triaged the vulnerability and identified any particular versions that are affected. If your vulnerability is accepted (i.e. we determine that it does indeed affect some of our users), we will:

* Release a patch as quickly as possible
    * Initially, this patch won't include details about the vulnerability
    * PalCode's own cloud-hosted infrastructure will be upgraded to this patch as soon as it is released.
* Decide on a date to publicly disclose the vulnerability and ask self-hosted users of PalCode to upgrade before then. Public disclosures are available through [this page](https://github.com/palcode-oss/doc/security/advisories).
* Consider requesting and assigning a CVE ID, depending on whether the necessary criteria are met.

If, on the other hand, your vulnerability is rejected, we'll provide you with as much detail as possible as to why this is the case.

Don't attempt to carry out exploits on PalCode's cloud infrastructure — you must always act in accordance with relevant legislation, and we will report suspected attacks to authorities.

Unfortunately, PalCode is currently too small to offer a bug bounty program.
