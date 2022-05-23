---
id: version-0.6.12-installation
title: Installation
original_id: installation
---

All of the artifacts below are available for both **JVM and Scala.js**.

Note, that artifacts that use Cats Effect 3 are published under a different version to those published for Cats Effect 2 (minor version bump), because they're binary incompatible.

|Effect types|Cats Effect 2 <br/><br/> Weaver version: `0.6.12`|Cats Effect 3.3.12 <br/><br/> Weaver version: `0.7.12`|
|---|---|---|
|Cats-Effect|✅ Scala 2.12, 2.13, 3.0.2|✅ Scala 2.12, 2.13, 3.0.2|
|Monix|✅ Scala 2.12, 2.13, 3.0.2|❌|
|Monix BIO|✅ Scala 2.12, 2.13, 3.0.2|❌|
|ZIO|✅ Scala 2.12, 2.13|✅ Scala 2.12, 2.13|

|Integrations|Cats Effect 2 <br/><br/> Weaver version: `0.6.12`|Cats Effect 3.3.12 <br/><br/> Weaver version: `0.7.12`|
|---|---|---|
|Discipline law testing|✅ Scala 2.12, 2.13, 3.0.2|✅ Scala 2.12, 2.13, 3.0.2|
|ScalaCheck|✅ Scala 2.12, 2.13, 3.0.2|✅ Scala 2.12, 2.13, 3.0.2|
|Specs2 matchers|✅ Scala 2.12, 2.13|✅ Scala 2.12, 2.13|


Weaver offers effect-type specific test frameworks. The Build setup depends on
the effect-type library you've elected to use (or test against).

Refer yourself to the library specific pages to get the correct configuration.

- [cats](cats_effect_usage.md)
- [monix](monix_usage.md)
- [monix-bio](monix_bio_usage.md)
- [zio](zio_usage.md)
