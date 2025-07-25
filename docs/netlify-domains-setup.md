---
title: Netlify and domain setup
cSpell:ignore: caniszczyk
---

# Netlify and domain setup

## Netlify

If a project already has its own Netlify instance, ask them to add
[@caniszczyk][] and [@nate-double-u][] as administrators. As a part of project
onboarding, any billing information should be taken care of. If it isn't, ask
them to open a [CNCF service desk][] ticket.

If a project does not have a website, or is migrating from using GitHub pages to
Netlify, create a new site for them under the CNCF Projects netlify instance.

### Netlify maintainers

- Ensure that [@caniszczyk][] and [@nate-double-u][] are owners.
- Contact the project and ask for **at least two** maintainers for Netlify. You
  will need their GitHub usernames. Add them either as Collaborators to specific
  sites (if in the CNCF Projects Netlify team) or as Collaborators for the
  Netlify team.

## Domains

If a project has a pre-existing domain, this should be transferred to the CNCF
during their onboarding process. To transfer a domain, please open an [LF
support desk][] ticket (Project Support Services → Domains & DNS → Transfer
Domain(s)).

If a project is new and does not have a domain name, they should open a [CNCF
service desk][] ticket to arrange for one.

In most cases, we prefer to manage domains for project websites using Netlify
DNS.

### Netlify DNS domains

When using Netlify DNS, we delegate the domain from another provider to Netlify
DNS. Read [Netlify DNS](https://docs.netlify.com/domains-https/netlify-dns/) for
more.

### Alias domains and projects with multiple domain names

Some projects have more than one domain name and want all of them to point to
their website. In this case, read
[Multiple Domains](https://docs.netlify.com/domains-https/custom-domains/multiple-domains/)
for more information, and ask them to open a [CNCF service desk][] ticket.

### Domains that don't point to Netlify websites

Occasionally projects have domain names that don't point to websites. These are
used for, among other things, email addresses.

Issues related to these should be forwarded on to Linux Foundation IT staff.

[@caniszczyk]: https://github.com/caniszczyk
[@nate-double-u]: https://github.com/nate-double-u
[CNCF service desk]: https://servicedesk.cncf.io/
[LF support desk]: https://support.linuxfoundation.org/
