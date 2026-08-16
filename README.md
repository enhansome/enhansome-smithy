# Awesome Smithy with stars

[<img src="/assets/smithy-light.svg#gh-light-mode-only" align="right" width="300">](https://smithy.io#gh-light-mode-only)
[<img src="/assets/smithy-dark.svg#gh-dark-mode-only" align="right" width="300">](https://smithy.iog#gh-dark-mode-only)

*Awesome Smithy* is a curated list of awesome build-tools, code-generators, examples, and other resources related to
the [Smithy IDL](https://github.com/awslabs/smithy) ⭐ 2,327 | 🐛 82 | 🌐 Java | 📅 2026-08-13.

If you want your component to appear here, send a pull request to this repository to add it (see the [contribution
guidelines](#contribute) for more information).

The Smithy team cannot vouch for the stability or production-worthiness an item on this list unless it has the icon <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> next to it. This icon means the
component is an official project supported by the [Smithy](https://github.com/smithy-lang) team.
Official Smithy team projects with the 🚧 icon next to them are still a work-in-progress and are not production-ready.

## Contents

* [Contents](#contents)
* [Build tools](#build-tools)
* [Code Generators](#code-generators)
  * [Client Code Generators](#client-code-generators)
  * [Server Code Generators](#server-code-generators)
* [Learning resources](#learning-resources)
* [IDE Support](#ide-support)
* [Implementations](#implementations)
* [Model Converters](#model-converters)
* [CICD Support](#cicd-support)
  * [GitHub Actions](#github-actions)
* [Videos](#videos)
* [Blog Posts](#blog-posts)
* [Others](#others)
* [Contribute](#contribute)

## Build tools

* [Mill Plugin](https://disneystreaming.github.io/smithy4s/docs/overview/installation/#mill) - Community supported plugin that integrates smithy with the [Mill build tool](https://github.com/com-lihaoyi/mill) ⭐ 2,778 | 🐛 254 | 🌐 Scala | 📅 2026-08-13.
* [Smithy CLI](https://github.com/smithy-lang/smithy/tree/main/smithy-cli) ⭐ 2,327 | 🐛 82 | 🌐 Java | 📅 2026-08-13 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Smithy CLI is used to build, validate, diff, and transform Smithy models.
* [Gradle Plugin](https://github.com/smithy-lang/smithy-gradle-plugin) ⭐ 33 | 🐛 3 | 🌐 Java | 📅 2026-08-11 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Integrates Smithy with the Gradle build system.
* [Smithy Cargo](https://github.com/mellemahp/smithy-cargo) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-01-31 - Community supported build tool that integrates smithy with Cargo build scripts (`build.rs`)
* [SBT Plugin](https://disneystreaming.github.io/smithy4s/docs/overview/installation/#sbt) - Community supported plugin that integrates smithy with the SBT build system for Scala.

## Code Generators

### Client Code Generators

* [Rust](https://github.com/awslabs/smithy-rs) ⭐ 656 | 🐛 383 | 🌐 Rust | 📅 2026-08-16 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Client code generation for Rust.
* [Scala](https://github.com/disneystreaming/smithy4s) ⭐ 400 | 🐛 115 | 🌐 Scala | 📅 2026-08-06 - Community plugin for generation of clients/servers in Scala.
* [TypeScript](https://github.com/awslabs/smithy-typescript) ⭐ 322 | 🐛 89 | 🌐 TypeScript | 📅 2026-08-15 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Client code generation for Typescript.
* [Golang](https://github.com/aws/smithy-go) ⭐ 253 | 🐛 33 | 🌐 Java | 📅 2026-08-14 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Client code generation for Golang.
* [Kotlin](https://github.com/awslabs/smithy-kotlin) ⭐ 111 | 🐛 34 | 🌐 Kotlin | 📅 2026-08-15 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Client code generation for Kotlin.
* [Python](https://github.com/smithy-lang/smithy-python) ⭐ 83 | 🐛 32 | 🌐 Python | 📅 2026-08-15 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Client code generation for Python.
* [Java](https://github.com/smithy-lang/smithy-java) ⭐ 71 | 🐛 19 | 🌐 Java | 📅 2026-08-15 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Client code generation for Java.
* [Ruby](https://github.com/awslabs/smithy-ruby) ⭐ 45 | 🐛 1 | 🌐 Ruby | 📅 2026-08-14 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Client code generation for Ruby.
* [Swift](https://github.com/awslabs/smithy-swift) ⭐ 39 | 🐛 8 | 🌐 Smithy | 📅 2026-08-15 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Client code generation for Swift.
* [Dafny](https://github.com/awslabs/smithy-dafny) ⭐ 18 | 🐛 127 | 🌐 Java | 📅 2026-03-30 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Code generation tools for the [Dafny](https://dafny.org/) verification-aware programming language.
* [C#](https://github.com/thomaslaich/smithy-dotnet) ⭐ 12 | 🐛 9 | 🌐 C# | 📅 2026-08-15 - Community plugin for generation of clients/servers in C#.
* [Erlang, Elixir, Gleam](https://github.com/f34nk/smithy-beam) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2026-07-18 - Community plugin for generating clients and servers targeting BEAM languages: Erlang, Elixir, Gleam

### Server Code Generators

* [Rust](https://github.com/awslabs/smithy-rs) ⭐ 656 | 🐛 383 | 🌐 Rust | 📅 2026-08-16 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Server generator for Rust.
* [Scala](https://github.com/disneystreaming/smithy4s) ⭐ 400 | 🐛 115 | 🌐 Scala | 📅 2026-08-06 - Community plugin for generation of clients/servers in Scala.
* [TypeScript](https://github.com/awslabs/smithy-typescript) ⭐ 322 | 🐛 89 | 🌐 TypeScript | 📅 2026-08-15 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Server generator for TypeScript.
* [Java](https://github.com/smithy-lang/smithy-java) ⭐ 71 | 🐛 19 | 🌐 Java | 📅 2026-08-15 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Server code generation for Java.
* [C#](https://github.com/thomaslaich/smithy-dotnet) ⭐ 12 | 🐛 9 | 🌐 C# | 📅 2026-08-15 - Community plugin for generation of clients/servers in C#.
* [Erlang, Elixir, Gleam](https://github.com/f34nk/smithy-beam) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2026-07-18 - Community plugin for generating clients and servers targeting BEAM languages: Erlang, Elixir, Gleam

## Learning resources

* [Rust server SDK examples](https://github.com/awslabs/smithy-rs/tree/main/examples) ⭐ 656 | 🐛 383 | 🌐 Rust | 📅 2026-08-16 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - a collection of examples using Smithy to generate a Rust server SDK.
* [Smithy Examples](https://github.com/smithy-lang/smithy-examples) ⭐ 103 | 🐛 4 | 🌐 Java | 📅 2026-08-14 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - A collection of examples to help you get up and running with Smithy.
* [aws-samples: Typescript Example service](https://github.com/aws-samples/smithy-server-generator-typescript-sample) ⭐ 18 | 🐛 2 | 🌐 TypeScript | 📅 2023-03-29 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Shows how to write a Typescript lambda service using Smithy and call the service using a generated client (see: [blog post](https://aws.amazon.com/blogs/devops/smithy-server-and-client-generator-for-typescript/)).
* [kubukoz/smithy4s-course](https://github.com/kubukoz/smithy4s-course) ⭐ 18 | 🐛 0 | 🌐 Scala | 📅 2026-05-05 - Smithy/Smithy4s course.

## IDE Support

* [Smithy LSP](https://github.com/awslabs/smithy-language-server) ⭐ 44 | 🐛 20 | 🌐 Java | 📅 2026-08-12 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - A Language Server Protocol implementation for the Smithy IDL.
* [Visual Studio Code Plugin](https://github.com/awslabs/smithy-vscode) ⭐ 42 | 🐛 10 | 🌐 Smithy | 📅 2026-08-10 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Visual Studio Code extension providing a Language Server Protocol implementation for the Smithy IDL.
* [iancaffey/smithy-intellij-plugin](https://github.com/iancaffey/smithy-intellij-plugin) ⭐ 30 | 🐛 5 | 🌐 Kotlin | 📅 2024-12-11 - Community plugin for IDE integration for the Smithy IDL in Intellij IDEA.
* [Tree Sitter Grammar for Smithy](https://github.com/indoorvivants/tree-sitter-smithy) ⭐ 22 | 🐛 5 | 🌐 JavaScript | 📅 2025-05-13 - Tree-sitter grammar for Smithy. Included in [Neovim](https://github.com/nvim-treesitter/nvim-treesitter) ⭐ 14,319 | 🐛 270 | 🌐 Tree-sitter Query | 📅 2026-08-15 and [Helix](https://docs.helix-editor.com/) by default.
* [Intellij plugin](https://github.com/awslabs/smithy-intellij) ⭐ 10 | 🐛 7 | 🌐 Java | 📅 2022-03-25 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> 🚧 - Provides IDE integration for the Smithy IDL within IntelliJ IDEA.
* [Zed extension](https://github.com/joshrutkowski/zed-smithy) ⭐ 4 | 🐛 3 | 🌐 Tree-sitter Query | 📅 2025-06-17 - [Zed](https://zed.dev/) extension using [Tree-sitter grammar for Smithy](https://github.com/indoorvivants/tree-sitter-smithy) ⭐ 22 | 🐛 5 | 🌐 JavaScript | 📅 2025-05-13.

## Implementations

* [Smithy Reference Implementation](https://github.com/awslabs/smithy) ⭐ 2,327 | 🐛 82 | 🌐 Java | 📅 2026-08-13 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Smithy reference implementation in Java
* [Atelier](https://github.com/johnstonskj/rust-atelier) ⭐ 79 | 🐛 11 | 🌐 Rust | 📅 2023-03-31 🚧 - Community implementation of Smithy in Rust
* [smithy-lisp](https://github.com/fukamachi/smithy-lisp) ⭐ 12 | 🐛 3 | 🌐 Common Lisp | 📅 2025-08-31 – Community implementation in Common Lisp

## Model Converters

* [Smithy to JSONSchema](https://github.com/awslabs/smithy/tree/main/smithy-jsonschema) ⭐ 2,327 | 🐛 82 | 🌐 Java | 📅 2026-08-13 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Converts Smithy models to [JSONSchema](https://json-schema.org/).
* [Openapi/JSONSchema to Smithy](https://github.com/disneystreaming/smithy-translate) ⭐ 67 | 🐛 6 | 🌐 Scala | 📅 2026-07-20 - smithy-translate : a community-provided CLI tool for best-effort Openapi/JSONSchema to Smithy conversions
* [Smithy to Protobuf](https://github.com/disneystreaming/smithy-translate) ⭐ 67 | 🐛 6 | 🌐 Scala | 📅 2026-07-20 - smithy-translate (see above)
* [Smithy to OpenAPI](https://smithy.io/2.0/guides/converting-to-openapi.html#smithy-to-openapi) <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Converts Smithy models to [OpenAPI](https://www.openapis.org/).
* [Cloud Formation Resource Schemas](https://smithy.io/2.0/guides/generating-cloudformation-resources.html#smithy-to-cloudformation) <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Generating Cloudformation resource schemas from Smithy models.

## CICD Support

### GitHub Actions

* [setup-smithy-cli](https://github.com/smithy-lang/setup-smithy-cli) ⭐ 2 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-09 <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Install the Smithy CLI for a GitHub action to validate, build, format, and diff Smithy models in a GitHub repository.
* [setup-smithy](https://github.com/marketplace/actions/setup-smithy) - Install Smithy CLI to your GitHub Workflow.
* [format-smithy](https://github.com/marketplace/actions/format-smithy) - Checks if Smithy Models are formatted.

## Videos

* [Scaling APIs with Smithy](https://www.youtube.com/watch?v=3GpZzu4guTE) <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Overview of Smithy's background and features.
* [Abstraction: Creating the Best developer experience / Model-First Design](https://youtu.be/gX2sHQafadA?t=1558) <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - An introduction to model first design with Smithy.
* [Building with the new AWS SDKs for Rust, Kotlin, and Swift](https://www.youtube.com/watch?v=Nhk1K1AjYvg) <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Explores how these SDKs were built in parallel with Smithy, the commonalities they share, and how to build an app with each one.
* [Simplify building applications with AWS SDKs](https://www.youtube.com/watch?v=7J0UMAGgAdw) <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Discusses how Smithy and model-first API design are used at AWS, how the AWS SDKs model client-side primitives such as paginators in Smithy, and how the AWS SDKs are evolving to use a standardized architecture.
* [Introduction to Smithy/Smithy4s](https://www.youtube.com/watch?v=CA8qGXMQ3cE) - Scala Conference talk introducing the Smithy IDL and the Smithy4s library
* [Generating Kotlin SDKs with Smithy](https://www.youtube.com/watch?v=Wsra04prG-E) - KotlinConf talk that provides an overview of Smithy and discusses how `smithy-kotlin` can be used to generate Kotlin SDKs
* [Elevating API Design With Smithy](https://www.youtube.com/watch?v=tufEEuPn6Lk) - Functional Scala talk - Intro to Smithy IDL with JVM Tooling and Smithy4s

## Blog Posts

* [Introducing Smithy IDL 2.0](https://aws.amazon.com/blogs/developer/introducing-smithy-idl-2-0/) <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Launch announcement for the Smithy IDL 2.0.
* [Introducing the Smithy CLI](https://aws.amazon.com/blogs/developer/introducing-the-smithy-cli/) <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Launch announcement for the Smithy CLI along with examples of how to use the CLI.
* [Developer Preview: Ruby SDK code generation using Smithy](https://aws.amazon.com/blogs/developer/developer-preview-smithy-code-generated-ruby-sdk/)  <img src="/assets/smithy-anvil.svg" alt="(official)" title="Smithy Official" height="10px"> - Launch announcement for and overview of the AWS Ruby SDK built with Smithy.
* [Smithy4s-full stack](https://blog.indoorvivants.com/2022-06-10-smithy4s-fullstack-part-1) - A series of posts describing an application built with Smithy4s in both front-end and back-end.
* [Introducing AWS API models and publicly available resources for AWS API definitions](https://aws.amazon.com/blogs/aws/introducing-aws-api-models-and-publicly-available-resources-for-aws-api-definitions/) - Launch announcement for AWS's API models being published as Smithy specs in Maven Central.

## Others

* [Build Server Protocol](https://github.com/build-server-protocol/build-server-protocol) ⭐ 548 | 🐛 40 | 🌐 Scala | 📅 2026-08-01 - an extension to the Language Server Protocol using Smithy as a definition language.
* [Alloy](https://github.com/disneystreaming/alloy/) ⭐ 49 | 🐛 13 | 🌐 Scala | 📅 2026-07-08 - a library of Smithy traits providing additional semantics and constraints, used in particular by smithy-translate and smithy4s.
* [Smithy Playground](https://github.com/kubukoz/smithy-playground/) ⭐ 32 | 🐛 58 | 🌐 Scala | 📅 2026-08-13 🚧 - A language server and VS Code client for interactive experimentation with Smithy services.
* [smaws](https://github.com/chris-armstrong/smaws/) ⭐ 20 | 🐛 4 | 🌐 OCaml | 📅 2026-07-25 - a Smithy generator and AWS SDK built in OCaml
* [Smithy Transcoder](https://github.com/kubukoz/smithy-transcoder) ⭐ 3 | 🐛 1 | 🌐 Scala | 📅 2026-08-15 - a web tool for previewing the serialized form of Smithy models
* [Smithy Selector Playground](http://github.com/kubukoz/smithy-selector-playground/) ⭐ 0 | 🐛 1 | 🌐 Scala | 📅 2026-05-13 - a web tool for experimenting with Smithy selectors

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
