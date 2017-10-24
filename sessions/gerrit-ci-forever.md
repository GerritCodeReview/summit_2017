# Gerrit CI: How to keep logs forever on Jenkins

We use Jenkins for verifying Gerrit patch sets under multiple
configurations and conditions. The logfiles produced are a
golden source of information. To keep Jenkins healthy and responsive,
we needed to remove them all which sounded quite silly: would
you just burn your cash because your wallet is too small?

Using the Logstash plugin and correlating the logs with Gerrit
review data I have managed to keep everything and *forever*
enabling a much richer data analysis and materialize back
the logs with the same URL referenced in the Gerrit changes.

*[Luca Milanesio / Gerrit CI Build Engineer / GerritForge](../speakers.md#lmilanesio)*

Slides are available on [SlideShare](https://www.slideshare.net/lucamilanesio/how-to-keep-jenkins-logs-forever-without-performance-issues)

YouTube and transcript are available on [GitEnterprise.me](https://gitenterprise.me/2017/10/24/gerrit-user-summit-jenkins-forever/)
