![Reference Architecture Wiki Logo](logo.png "Reference Architecture Wiki")
---
> **Note**: This is a work in progress, you are welcome to contribute and suggest changes, please follow the [contribution guidelines](.github/CONTRIBUTING.md)

## Why

Security is everyone's responsibility, by including security mindfulness early
in the development process, concerns are identified and remediated ideally
before they are put into production. This avoids the costly (both in terms of
time and money) refactoring of a project later in the development cycle.
Moreover, our customers expect the Confidentiality, Identity and Availability
of our products and services to be an intrinsic value.

## What

The following sections and placeholder articles are the the bare minimum your project should consider as part of it's "Secure by Design" development, more to be added, and updated throughout the drafting period.

## How
First and foremost, application security is a relatively new discipline, the
humility and wisdom to ask for help is a great start. There's a lot of moving
parts and new threats are a given. Connecting with your outcome team's assigned @security resource can help you overcome some initial hurdles.


## Who
As mentioned above, security is everyone's responsibility our customers are
dependent upon our decision making to ensure the custody of their data. The
@security team is here to help with guidance, find answers  and to coach on secure practices.

## Security Concepts 
- [Confidentiality, Integrity, Availability](security/cia.md)
- [Least Privilege/Least Access](security/least-privilege.md)
### Threats
- [OWASP Top 10](security/owasp-top-ten.md)
- [Information Disclosure](security/info-disclosure.md)



## Security Concerns and Practices within Development Phases

This reference is segmented by phase, covering security
concerns from  project inception, through to post production phase with a
special call out recognizing the new Continuous Integration (CI) / Continuous
Deployment/Delivery (CD) methodology  that's leveraged within our organization.

#### Inception Phase 
- [OWASP Application Security Verfification Standard](security/ASVS.md)
- [Privacy Impact Assessment](security/pia.md)
- [Security Architecture Engagement Request](security/pia.md)
- [Evil User Stories](security/evil-user.md)
- [Threat Modeling](security/threat-modeling.md)


#### Code Development Phase

##### Development Process
- [Linting](security/linting.md)
- [RCS Secrets](security/rcs-secrets.md)

#####  Best Practices
- [General Best Practices](security/best-practices/general.md)
- [React.JS](security/best-practices/react.md)
- [Express.JS](security/best-practices/express.md)

##### Web Application Security Controls
- [Browser Security Controls](security/browser-controls.md)
- [Server Side Controls](security/server-side-controls.md)


#### Testing Phase
- [Test Driven Security Testing](security/tdst.md)
#### Continuous Delivery/Deployment Phase
- [Jenkins](security/jenkins.md)
#### Post Deployment Phase
- [Vulnerabilty Management Program](security/vuln-management.md)

```