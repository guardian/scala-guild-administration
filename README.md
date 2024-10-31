# Scala Guild
 🎉✨ Maintaining shared Scala code & infrastructure at the Guardian ✨🎉

## Membership

See the GitHub team [@scala-guild](https://github.com/orgs/guardian/teams/scala-guild)!
This GitHub team is specifically for developers across the Guardian who’ve accepted the honoured responsibilities of our
Scala Guild. It’s intended to draw its membership from across all Product Streams and Teams.

If you'd like to join the guild, feel free to message any of the guild members (particularly,
Roberto will always be delighted to hear from you!) and they'll add you to the
[@scala-guild](https://github.com/orgs/guardian/teams/scala-guild) GitHub team.

## Scala Guild responsibilities

The Scala Guild is focussed on making sure that shared Scala code and infrastructure at the Guardian is maintained and secure -
it gives a place for responsibility to exist for security vulnerability patching, upgrading and general maintenance. Without
this group, maintenance responsibility for shared libraries that are used across many Product Teams at the Guardian would be
unclear.

The guild has _criteria_ for accepting responsibility for Scala code, and is not responsible for all Scala code at the Guardian.
Accepting responsibility does not happen automatically, each repo must be added by a PR reviewed by the guild.

## Criteria for code being maintained by the Guild

It must:
* Be in a public GitHub repository
* Be consumed by **more than one Product team** at the Guardian - if only one Product team consumes a library, then by default,
  they should maintain it - though obviously the Scala Guild can be consulted for expertise.
* Have Scala Steward [enabled](https://github.com/guardian/scala-steward-public-repos).
* (if it is a library) Use a secure automated release process, ie [`gha-scala-library-release-workflow`](https://github.com/guardian/gha-scala-library-release-workflow)

There should be:
* no Product team that has obvious responsibility as publisher of the library - for instance, these libraries all have obvious owner teams:
  * Dev X
    * https://github.com/guardian/janus-app
    * https://github.com/guardian/anghammarad
  * Commercial
    * https://github.com/guardian/commercial-shared
  * MAPI
    * https://github.com/guardian/mobile-apps-api-models
  * Content Pipeline
    * https://github.com/guardian/content-api-client-aws
    * https://github.com/guardian/content-api-firehose-client
  * Content Production
    * https://github.com/guardian/tags-thrift-schema
