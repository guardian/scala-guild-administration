# Code maintained by the Scala Guild

Each repo listed needs examples of usage across more than 1 Product team! 

## [scala-steward-public-repos](https://github.com/guardian/scala-steward-public-repos) & [scala-steward-private-repos](https://github.com/guardian/scala-steward-private-repos)

**Used by:** Many [public](https://github.com/search?q=org%3Aguardian+author%3Agu-scala-steward-public-repos%5Bbot%5D&type=pullrequests&s=updated&o=desc) &
[private](https://github.com/search?q=org%3Aguardian+author%3Agu-scala-steward-private-repos%5Bbot%5D&type=pullrequests&s=updated&o=desc)
Guardian Scala repos ✨

## [gha-scala-library-release-workflow](https://github.com/guardian/gha-scala-library-release-workflow)

**Used by:** [Most](https://github.com/guardian/gha-scala-library-release-workflow/issues/20) Guardian Scala libraries ✨

## [setup-scala](https://github.com/guardian/setup-scala)

**Used by:** [Many](https://github.com/search?q=org%3Aguardian+%22guardian%2Fsetup-scala%22++NOT+is%3Aarchived+language%3AYAML&type=code&l=YAML) Guardian Scala projects, eg [play-googleauth](https://github.com/guardian/play-googleauth/pull/264), [mobile-n10n](https://github.com/guardian/mobile-n10n/pull/1325)

## [etag-caching](https://github.com/guardian/etag-caching)
[![aws-s3-sdk-v2 Scala version support](https://index.scala-lang.org/guardian/etag-caching/aws-s3-sdk-v2/latest-by-scala-version.svg?platform=jvm)](https://index.scala-lang.org/guardian/etag-caching/aws-s3-sdk-v2)

**Used by:** [frontend](https://github.com/guardian/frontend/pull/26338), [facia-scala-client](https://github.com/guardian/facia-scala-client/pull/287)


## [play-googleauth](https://github.com/guardian/play-googleauth)
[![play-googleauth artifacts](https://index.scala-lang.org/guardian/play-googleauth/play-v30/latest-by-scala-version.svg)](https://index.scala-lang.org/guardian/play-googleauth/play-v30/)

**Used by:** [ophan](https://github.com/guardian/ophan/pull/569), [riff-raff](https://github.com/guardian/riff-raff/pull/192)


## [play-secret-rotation](https://github.com/guardian/play-secret-rotation)
[![core Scala version support](https://index.scala-lang.org/guardian/play-secret-rotation/core/latest-by-scala-version.svg?platform=jvm)](https://index.scala-lang.org/guardian/play-secret-rotation/core)

**Used by:** [ophan](https://github.com/guardian/ophan/pull/2712), [riff-raff](https://github.com/guardian/riff-raff/pull/491)


## [play-json-extensions](https://github.com/guardian/play-json-extensions)
[![play-json-extensions Scala version support](https://index.scala-lang.org/guardian/play-json-extensions/play-json-extensions/latest-by-scala-version.svg?platform=jvm)](https://index.scala-lang.org/guardian/play-json-extensions/play-json-extensions)

**Used by:** [mobile-apps-api](https://github.com/guardian/mobile-apps-api/pull/3341), [media-atom-maker](https://github.com/guardian/media-atom-maker/pull/1206)


## [redirect-resolver](https://github.com/guardian/redirect-resolver)
[![redirect-resolver Scala version support](https://index.scala-lang.org/guardian/redirect-resolver/redirect-resolver/latest-by-scala-version.svg?platform=jvm)](https://index.scala-lang.org/guardian/redirect-resolver/redirect-resolver)

**Used by:** [google-search-indexing-observatory](https://github.com/guardian/google-search-indexing-observatory/pull/50), [mobile-apps-api](https://github.com/guardian/mobile-apps-api/pull/2865)


## [simple-configuration](https://github.com/guardian/simple-configuration)
[![simple-configuration-core Scala version support](https://index.scala-lang.org/guardian/simple-configuration/simple-configuration-core/latest-by-scala-version.svg?platform=jvm)](https://index.scala-lang.org/guardian/simple-configuration/simple-configuration-core)

**Used by:** [gatehouse](https://github.com/guardian/gatehouse/pull/12), [typerighter](https://github.com/guardian/typerighter/pull/6)


## [guardian-configuration](https://github.com/guardian/guardian-configuration)  
[![configuration Scala version support](https://index.scala-lang.org/guardian/guardian-configuration/configuration/latest-by-scala-version.svg?platform=jvm)](https://index.scala-lang.org/guardian/guardian-configuration/configuration)

**Used by:** [content-api](https://github.com/guardian/content-api/pull/1491), [discussion-api](https://github.com/guardian/discussion-api/commit/06fc8192648fce2826cdf9135b35551c37432cc1)  
(Usages to be replaced by [simple-configuration](https://github.com/guardian/simple-configuration) and library archived)  

## Adding more repos

If the Scala Guild adopts a new repo, the repo should be added to the list above and a new [auto-add workflow](https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/adding-items-automatically) for it should be added to [the Scala Guild Github Project](https://github.com/orgs/guardian/projects/113). The new workflow can be added by duplicating an existing one, such as [this one for etag-caching](https://github.com/orgs/guardian/projects/113/workflows/44905208), and then updating the repository listed in the filter.
