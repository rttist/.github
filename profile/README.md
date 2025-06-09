# Welcome to RTTIST — the home of TypeScript Runtime Reflection.

**RTTIST** *(pronounced /ˈɑː(r)tɪst/, like artist)* is an open-source initiative dedicated to bringing powerful runtime type information to the TypeScript ecosystem. Our project provides a robust and extensible reflection system that allows developers to access and work with TypeScript types at runtime — including classes, interfaces, generics, union types, and more.

TypeScript is great at compile-time safety, but when it comes to runtime, type information is lost. **RTTIST** bridges that gap by capturing rich type metadata during compilation and making it available at runtime — enabling advanced use cases like serialization, validation, dependency injection, schema generation, and dynamic UI rendering.

This organization hosts:
- RTTIST runtime (`rttist`) – the main reflection runtime / API.
- `typegen` – a CLI tool and integration API responsible for generating metadata used by the reflection system.
- Transformers – optional code transformations that enable advanced features like runtime generics and more intuitive access to type metadata. While not required, they enhance the developer experience by allowing you to write expressions like getType<SomeType>() instead of manually searching through generated metadata. For many use cases, you can rely solely on Typegen to produce metadata and consume it directly — the transformers simply make working with it easier and more expressive.
- Examples & Demos – showcasing practical use cases of RTTIST in real-world applications.
- Utilities & Extensions – tools that build on top of the core project to enable even more advanced patterns.

Whether you're building tools, libraries, or dynamic applications, RTTIST gives you access to the type information you always wished you had at runtime.

Join us in pushing the boundaries of what TypeScript can do.