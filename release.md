## Types of Releases

### Major Release

This typically happens once per year and is tied to a marketing event in June.  These releases usually contain larger, more wide-ranging changesets and high-value new features.  They are accompanied by a large marketing effort and require the most work and preparation of all release types.

Major releases rev the first digit in our 3-digit versioning scheme x.y.z -> x+1.0.0

### Minor Release

Minor releases happen every other month on even-numbered months (except December when we implement a release freeze and then release the minor release at the start of January).  These releases usually contain backwards-compatible new features as well as bug fixes and security enhancements (security enhancements being security updates for security issues that are not critical enough to warrant an unplanned release).  They are accompanied by GTM materials such as blog posts, training materials, etc. and there is an extensive release process including multiple departments.

Minor releases rev the second digit in our 3-digit versioning scheme x.y.z -> x.y+1.0

### Patch Release

Patch releases are planned to happen every other month on odd-numbered months however they also constitute all our unplanned release types.  These releases typically only include bug fixes and security enhancements for planned releases, and bug fixes and security fixes (security updates that trigger an out of schedule release) for unplanned releases.  They do not require any GTM materials to accompany them and so are faster to release, generally we only support change logs with this type of release.

Patch release rev the third digit in out 3-digit versioning scheme x.y.z -> x.y.z+1

### Private Release

Private releases are releases which are only accessible by our contracted customers and not available to the public. Private releases are published so that they are accessible via an obfuscated and unique download page. Each privately released version will have its own page and will not be accessible via the grafana.com/downloads page.  Any release type above (major, minor, patch) can be released privately based on the context of the situation at the time.

#### Planned

Planned private releases occur on the 2nd Tuesday of each month if there is a reason to have a private release for that month.  The rationale for a planned private release is when we have security fixes that are not critical enough to trigger an unplanned release but critical enough such that they pose a risk to our partner companies whom require the protection of a 2 week embargo period before we release the fixes publicly (see Vulnerability SLOs for details).  After we publish a planned private release we wait 2 weeks before publishing the same release publicly on the 4th Tuesday of the month.

#### Unplaned

These occur when we are affected by a security vulnerability that cannot wait until the normally scheduled time to do a planned private release (2nd Tuesday of the month).  In these cases we proceed as described above except that the release can happen on any day.  The 2 week embargo period is honored in this case as well. 

### Public Release

Public releases are those which are published to grafana.com/downloads and are available to contracted customers and the public alike.  

#### Planned

Public releases are planned on the 4th Tuesday of each month.  On occasion this can be delayed if we have had to produce a private release within a 2 week window prior to the public release and we determine it is beneficial to postpone the public release to the end of the embargo period rather than releasing twice (once form the planned release and once to publicly release the private release).

#### Unplaned

These can occur in the case of a critical security fix (e.g. a 0-day) or if there are functional problems with a previous release of Grafana that risk our reputation and need to be resolved asap.  In this case we perform a public release as normal on any day, we don’t not have to wait for the 4th Tuesday of the month, and we publish the release publicly for everyone to have access to.

### Security Release

Security releases are unplanned in nature.  These occur when we have critical or maximum severity security issues (e.g. 0-day) that put Grafana Labs or our customers at severe risk.  In this case we stop the line and produce a release with the security fix as quickly as possible.  This release is then published publicly for all GL customers to be able to consume asap.  There is no embargo period.

## NOTES

2023/10/23 - Grafana Release Build Ride along

  - Look at release day plan
  - Look at release day checklist
  - Fairly dull and empty
  - Keep track of the release state
  - Build the release guide
  - Follow directions