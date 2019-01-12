# Scala Resources

## Articles

* Experiences with using Freestyle library: https://blog.scalac.io/old-school-developer-goes-freestyle.html
* Using typedapi: https://typelevel.org/blog/2018/06/15/typedapi.html
* On Binding.Scala: https://blog.scalac.io/binding-scala.html
* Scala and event sourcing: https://blog.scalac.io/tags/CQRS/
* Introduction to Freestyle library/framework: https://www.youtube.com/watch?v=QOJKqD3rEJo
* Showcase of typeclasses in FP architectures: https://github.com/47deg/typeclasses-in-fp-architecture
* Hints on using Cats-Effect IO: https://www.reddit.com/r/scala/comments/7vste9/cats_effect_io_monad/
* The typelevel ecosystem: https://blog.scalac.io/typelevel-ecosystem.html
* Free monads and event sourcing: http://www.stephenzoio.com/free-monads-and-event-sourcing/
* Talk on using Slinky: https://www.youtube.com/watch?v=AkMVfy_86HY
* Slides on using Doobie: https://www.slideshare.net/normation/doobie-feedbacks-from-the-trenches-scalaio-2016
* Http4s, Doobie and Circe: https://www.slideshare.net/GaryCoady/http4s-doobie-and-circe-the-functional-web-stack
* Error handling in http4s: https://typelevel.org/blog/2018/08/25/http4s-error-handling-mtl.html
* Error handling in http4s, Part 2: https://typelevel.org/blog/2018/11/28/http4s-error-handling-mtl-2.html
* A tale of Semiring: https://typelevel.org/blog/2018/11/02/semirings.html
* An introduction to Cats-MTL: https://typelevel.org/blog/2018/10/06/intro-to-mtl.html
* Refactoring with monads: https://typelevel.org/blog/2018/08/07/refactoring-monads.html
* Testing with Specs2 and ScalaCheck: https://typelevel.org/blog/2018/07/12/testing-in-the-wild.html
* Optimizing Tagless Final: https://typelevel.org/blog/2017/12/27/optimizing-final-tagless.html
* Optimizing Tagless Final, Part 2: https://typelevel.org/blog/2018/06/27/optimizing-tagless-final-2.html
* Deriving clients and servers from typed APIs: https://typelevel.org/blog/2018/06/15/typedapi.html
* Shared state in functional programming: https://typelevel.org/blog/2018/06/07/shared-state-in-fp.html
* Tagless Final algebras and Streaming: https://typelevel.org/blog/2018/05/09/tagless-final-streaming.html
* Rethinking MonadError: https://typelevel.org/blog/2018/04/13/rethinking-monaderror.html
* Validated configuration with Ciris: https://typelevel.org/blog/2017/06/21/ciris.html
* Documentation for Cats-Effect IO: https://typelevel.org/cats-effect/datatypes/io.html
* Converting Scala Future to Monix Task: https://monix.io/blog/2018/11/08/tutorial-future-to-task.html

## Libraries:

### FP:

* Servant-style typed APIs: https://github.com/pheymann/typedapi
* Framework for building apps with free monads: https://github.com/frees-io/freestyle
* Efficient data access: https://github.com/47deg/fetch
* Macros for first class typeclass support: https://github.com/mpilquist/simulacrum
* Scalaz-Zio: https://github.com/scalaz/scalaz-zio
* Functional JDBC access: https://github.com/tpolecat/doobie
* Quickcheck in Scala: https://github.com/rickynils/scalacheck
* Combinators for binary data: https://github.com/scodec/scodec
* Purely functional layer on top of Finagle: https://github.com/finagle/finch
* Purely functional HTTP client: https://github.com/pepegar/hammock
* Command-line parser: https://github.com/bkirwi/decline
* JSON library powered by Cats: https://github.com/circe/circe
* Utilities for using the Tagless Final style: https://github.com/typelevel/cats-tagless
* Streaming gRPC over FS2: https://github.com/fiadliel/fs2-grpc
* Converting Scala Future to Scalaz Task: https://github.com/Verizon/delorean
* Streaming Kafka client: https://github.com/Spinoco/fs2-kafka
* Another one: https://github.com/ovotech/fs2-kafka
* Streaming RabbitMQ client: https://github.com/gvolpe/fs2-rabbit
* Streaming Redis client: https://github.com/gvolpe/fs2-redis
* Stream-based Scodec library: https://github.com/scodec/scodec-stream

### Data Access:

* Very robust ElasticSearch client: https://github.com/sksamuel/elastic4s
* Complete Cassandra client: https://github.com/outworkers/phantom
* Embedded quasiquoted SQL DSL: https://github.com/getquill/quill
* Reactive, nonblocking MongoDB client: https://github.com/ReactiveMongo/ReactiveMongo
* FS2-based Redis client (cats-friendly!): https://github.com/gvolpe/fs2-redis
* Nonblocking Redis client: https://github.com/scredis/scredis
* Slick (new versions look quite a bit nicer): https://github.com/slick/slick
* Opiniated RabbitMQ client: https://github.com/SpinGo/op-rabbit
* Persistence framework for SQL and NoSQL (support Cats IO?): http://longevityframework.org/

### Web:

* Outwatch, functional UI for Scala.js: https://github.com/OutWatch/outwatch
* Reactive data-bindings: https://github.com/ThoughtWorksInc/Binding.scala
* React wrapper: https://github.com/ahnfelt/react4s
* React apps in Scala: https://slinky.shadaj.me/
* Another React wrapper for ScalaJS (most popular?): https://github.com/japgolly/scalajs-react
* State management in immutable ScalaJS apps: https://github.com/suzaku-io/diode

### Utilities:

* Data transformations (for easy use of DDD concepts): https://github.com/scalalandio/chimney
* Generate type-safe ids: https://github.com/SystemFw/eidos
* Lens in Scala: https://github.com/julien-truffaut/Monocle
* Macro-dsl on top of Monocle: https://github.com/kenbot/goggles
* Alternate optics library: https://github.com/adamw/quicklens
* Sbt plugin for starting in-memory cassandra: https://github.com/47deg/sbt-embedded-cassandra
* WIP language server: https://github.com/scalameta/metals
* Type-safe enumerations: https://github.com/lloydmeta/enumeratum
* Scala code coverage: https://github.com/scoverage/scalac-scoverage-plugin
* Config loading: https://github.com/pureconfig/pureconfig
* Function UUIDs: https://christopherdavenport.github.io/fuuid/
* Crypto library: https://github.com/jmcardon/tsec
* Scala ProtoBuff compiler: https://github.com/scalapb/ScalaPB
* Scala Thrift code generator: http://twitter.github.io/scrooge/
* Macro that replaces DI solutions: https://github.com/adamw/macwire
* Scala linting tool: https://github.com/wartremover/wartremover
* Macro for creating RPC between Scala systems: https://github.com/lihaoyi/autowire
* Type-safe RPC: https://github.com/cornerman/sloth
* HTTP based RPC: https://github.com/julienrf/endpoints
* Complete rewrite of Thrift in Scala: https://twitter.github.io/scrooge/

## Example Applications:

* App with doobie, sangria and http4s: https://github.com/tpolecat/doobie-http4s-sangria-grapgql-example
* App with rho, doobie and DDD: https://github.com/lloydmeta/rhodddoobie
* App with http4s with slick: https://github.com/gribbet/http4s-slick-example
* App with http4s, slick, kafka and ES: https://github.com/gekomad/music-store
* App with shows use of tagless final: https://github.com/47deg/sample-tagless-final
* App with http4s, doobie in CQRS/ES system: https://github.com/LambdaFanatics/pure-cqrs-example
* App that mirrors classic pet-store with FP libs: https://github.com/pauljamescleary/scala-pet-store
* ScalaJS SPA that uses ScalaJS-React, Diode, etc.: https://github.com/ochrons/scalajs-spa-tutorial
* Using Freestyle RPC: https://github.com/frees-io/frees-rpc-workshop

## Exercises, Tutorials, Guides:

* Exercises divided by (very interesting!) subjects: https://www.scala-exercises.org/
* Learn FP by doing: https://github.com/dehun/learn-fp/
* The Type Astronaut's Guide to Shapeless: https://underscore.io/books/shapeless-guide/
* Scala with Cats: https://underscore.io/books/scala-with-cats/
* Functional Programming for Mortals (Book): https://leanpub.com/fpmortals/read
