# TypeScript Mastery Roadmap

*My path to adding static types to JavaScript – catching errors before they happen*

**Status:** ⚪ Not Started  
**Started:** TBD  
**Target Completion:** TBD

---

## 📋 Mastery Checklist

### Part I: Foundations – Why TypeScript?
- [ ] [What is TypeScript? – Relation to JavaScript, compilation](/track-01-core/04-typescript/notes/01-what-is-ts.md)
- [ ] [Setting Up – `tsc`, `tsconfig.json`, editors](/track-01-core/04-typescript/notes/02-setup.md)
- [ ] [Basic Types – `string`, `number`, `boolean`, `null`, `undefined`](/track-01-core/04-typescript/notes/03-basic-types.md)
- [ ] [Type Inference – When types are automatic](/track-01-core/04-typescript/notes/04-inference.md)
- [ ] [Type Annotations – Explicit typing](/track-01-core/04-typescript/notes/05-annotations.md)
- [ ] [Compilation – Target ES versions, output](/track-01-core/04-typescript/notes/06-compilation.md)

**Project:** [First TypeScript Setup](/track-01-core/04-typescript/projects/01-first-setup/)

---

### Part II: Essential Types
- [ ] [Arrays – `type[]`, `Array<type>`](/track-01-core/04-typescript/notes/07-arrays.md)
- [ ] [Tuples – Fixed-length arrays with types](/track-01-core/04-typescript/notes/08-tuples.md)
- [ ] [Enums – Numeric, string, const enums](/track-01-core/04-typescript/notes/09-enums.md)
- [ ] [Any – When to use (and not use)](/track-01-core/04-typescript/notes/10-any.md)
- [ ] [Unknown – Type-safe alternative to any](/track-01-core/04-typescript/notes/11-unknown.md)
- [ ] [Void & Never – Return types](/track-01-core/04-typescript/notes/12-void-never.md)
- [ ] [Union Types – `|` operator](/track-01-core/04-typescript/notes/13-unions.md)
- [ ] [Intersection Types – `&` operator](/track-01-core/04-typescript/notes/14-intersections.md)
- [ ] [Literal Types – Specific values as types](/track-01-core/04-typescript/notes/15-literals.md)

**Project:** [Type System Playground](/track-01-core/04-typescript/projects/02-type-playground/)

---

### Part III: Functions
- [ ] [Function Types – Parameter and return types](/track-01-core/04-typescript/notes/16-function-types.md)
- [ ] [Optional Parameters – `?`](/track-01-core/04-typescript/notes/17-optional.md)
- [ ] [Default Parameters](/track-01-core/04-typescript/notes/18-default.md)
- [ ] [Rest Parameters – `...args`](/track-01-core/04-typescript/notes/19-rest.md)
- [ ] [Function Overloads – Multiple call signatures](/track-01-core/04-typescript/notes/20-overloads.md)
- [ ] [`this` Typing – Explicit this parameters](/track-01-core/04-typescript/notes/21-this.md)
- [ ] [Predicate Functions – Type guards](/track-01-core/04-typescript/notes/22-predicates.md)

**Project:** [Typed Function Library](/track-01-core/04-typescript/projects/03-function-library/)

---

### Part IV: Interfaces & Type Aliases
- [ ] [Interfaces – Object shapes](/track-01-core/04-typescript/notes/23-interfaces.md)
- [ ] [Type Aliases – `type` vs `interface`](/track-01-core/04-typescript/notes/24-type-aliases.md)
- [ ] [Optional Properties – `?` modifier](/track-01-core/04-typescript/notes/25-optional-props.md)
- [ ] [Readonly Properties – `readonly` modifier](/track-01-core/04-typescript/notes/26-readonly.md)
- [ ] [Extending Interfaces – `extends`](/track-01-core/04-typescript/notes/27-extending.md)
- [ ] [Intersection Types with Interfaces](/track-01-core/04-typescript/notes/28-intersection-interfaces.md)
- [ ] [Index Signatures – Dynamic properties](/track-01-core/04-typescript/notes/29-index-signatures.md)
- [ ] [Hybrid Types – Objects that are also functions](/track-01-core/04-typescript/notes/30-hybrid.md)

**Project:** [Domain Model Design](/track-01-core/04-typescript/projects/04-domain-model/)

---

### Part V: Classes
- [ ] [Class Basics – Properties, methods, constructors](/track-01-core/04-typescript/notes/31-class-basics.md)
- [ ] [Access Modifiers – `public`, `private`, `protected`](/track-01-core/04-typescript/notes/32-access-modifiers.md)
- [ ] [Readonly in Classes](/track-01-core/04-typescript/notes/33-class-readonly.md)
- [ ] [Parameter Properties – Constructor shorthand](/track-01-core/04-typescript/notes/34-parameter-properties.md)
- [ ] [Getters & Setters](/track-01-core/04-typescript/notes/35-accessors.md)
- [ ] [Static Members – Properties and methods](/track-01-core/04-typescript/notes/36-static.md)
- [ ] [Abstract Classes – Blueprints for inheritance](/track-01-core/04-typescript/notes/37-abstract.md)
- [ ] [Implements – Classes implementing interfaces](/track-01-core/04-typescript/notes/38-implements.md)

**Project:** [Class-Based Architecture](/track-01-core/04-typescript/projects/05-class-architecture/)

---

### Part VI: Generics
- [ ] [Generic Functions – Type parameters](/track-01-core/04-typescript/notes/39-generic-functions.md)
- [ ] [Generic Interfaces](/track-01-core/04-typescript/notes/40-generic-interfaces.md)
- [ ] [Generic Classes](/track-01-core/04-typescript/notes/41-generic-classes.md)
- [ ] [Generic Constraints – `extends`](/track-01-core/04-typescript/notes/42-constraints.md)
- [ ] [Default Type Parameters](/track-01-core/04-typescript/notes/43-default-generics.md)
- [ ] [Generic Utility Types – `Partial`, `Pick`, etc.](/track-01-core/04-typescript/notes/44-generic-utilities.md)
- [ ] [Conditional Types – `T extends U ? X : Y`](/track-01-core/04-typescript/notes/45-conditional.md)
- [ ] [Infer – Type inference in conditional types](/track-01-core/04-typescript/notes/46-infer.md)
- [ ] [Mapped Types – Transforming types](/track-01-core/04-typescript/notes/47-mapped.md)
- [ ] [Template Literal Types](/track-01-core/04-typescript/notes/48-template-literals.md)

**Project:** [Generic Utility Library](/track-01-core/04-typescript/projects/06-generic-library/)

---

### Part VII: Advanced Types
- [ ] [Type Guards – `typeof`, `instanceof`, custom guards](/track-01-core/04-typescript/notes/49-type-guards.md)
- [ ] [Discriminated Unions – Tagged union types](/track-01-core/04-typescript/notes/50-discriminated-unions.md)
- [ ] [Type Assertions – `as`, `<>`](/track-01-core/04-typescript/notes/51-assertions.md)
- [ ] [Const Assertions – `as const`](/track-01-core/04-typescript/notes/52-const-assertions.md)
- [ ] [Satisfies Operator – Type checking without widening](/track-01-core/04-typescript/notes/53-satisfies.md)
- [ ] [Recursive Types – Self-referential types](/track-01-core/04-typescript/notes/54-recursive.md)
- [ ] [Branded Types – Nominal typing simulation](/track-01-core/04-typescript/notes/55-branded.md)

**Project:** [Advanced Type Patterns](/track-01-core/04-typescript/projects/07-advanced-types/)

---

### Part VIII: Modules & Namespaces
- [ ] [ES Modules in TypeScript – `import`/`export`](/track-01-core/04-typescript/notes/56-modules.md)
- [ ] [Type-Only Imports – `import type`](/track-01-core/04-typescript/notes/57-type-imports.md)
- [ ] [Namespaces – Internal modules (legacy)](/track-01-core/04-typescript/notes/58-namespaces.md)
- [ ] [Module Resolution – Classic vs Node](/track-01-core/04-typescript/notes/59-resolution.md)
- [ ] [Ambient Modules – `declare module`](/track-01-core/04-typescript/notes/60-ambient.md)
- [ ] [Declaration Files – `.d.ts`](/track-01-core/04-typescript/notes/61-declaration-files.md)

**Project:** [Module Authoring](/track-01-core/04-typescript/projects/08-module-authoring/)

---

### Part IX: Configuration & Tooling
- [ ] [`tsconfig.json` Deep Dive – All options](/track-01-core/04-typescript/notes/62-tsconfig.md)
- [ ] [Compiler Options – `strict`, `target`, `module`, etc.](/track-01-core/04-typescript/notes/63-compiler-options.md)
- [ ] [Project References – Composite projects](/track-01-core/04-typescript/notes/64-project-references.md)
- [ ] [Build Tools – tsc, esbuild, swc](/track-01-core/04-typescript/notes/65-build-tools.md)
- [ ] [Integrating with Bundlers – Webpack, Vite](/track-01-core/04-typescript/notes/66-bundlers.md)
- [ ] [Linting – ESLint with TypeScript](/track-01-core/04-typescript/notes/67-linting.md)

**Project:** [Build Configuration Suite](/track-01-core/04-typescript/projects/09-build-config/)

---

### Part X: TypeScript with React
- [ ] [Typing Components – `React.FC` vs return type](/track-01-core/04-typescript/notes/68-react-components.md)
- [ ] [Props – Interface for component props](/track-01-core/04-typescript/notes/69-props.md)
- [ ] [State – `useState` with types](/track-01-core/04-typescript/notes/70-state.md)
- [ ] [Events – Typing event handlers](/track-01-core/04-typescript/notes/71-events.md)
- [ ] [Hooks – `useEffect`, `useRef`, custom hooks](/track-01-core/04-typescript/notes/72-hooks.md)
- [ ] [Context – Typing React Context](/track-01-core/04-typescript/notes/73-context.md)
- [ ] [Higher-Order Components – WithType](/track-01-core/04-typescript/notes/74-hoc.md)
- [ ] [Render Props – Typing children as function](/track-01-core/04-typescript/notes/75-render-props.md)

**Project:** [Typed React Application](/track-01-core/04-typescript/projects/10-react-app/)

---

### Part XI: TypeScript with Node.js
- [ ] [Node.js Types – `@types/node`](/track-01-core/04-typescript/notes/76-node-types.md)
- [ ] [Building a Server – Express with TypeScript](/track-01-core/04-typescript/notes/77-express.md)
- [ ] [Environment Variables – Typed configuration](/track-01-core/04-typescript/notes/78-env.md)
- [ ] [Database Integration – Prisma, TypeORM](/track-01-core/04-typescript/notes/79-database.md)
- [ ] [Error Handling – Typed errors](/track-01-core/04-typescript/notes/80-node-errors.md)

**Project:** [Typed Backend API](/track-01-core/04-typescript/projects/11-backend-api/)

---

### Part XII: Advanced Type Patterns
- [ ] [Builder Pattern – Fluent interfaces with types](/track-01-core/04-typescript/notes/81-builder.md)
- [ ] [Factory Pattern – Type-safe factories](/track-01-core/04-typescript/notes/82-factory.md)
- [ ] [Dependency Injection – With typed containers](/track-01-core/04-typescript/notes/83-di.md)
- [ ] [Event Emitters – Typed events](/track-01-core/04-typescript/notes/84-event-emitter.md)
- [ ] [Finite State Machines – Typed states](/track-01-core/04-typescript/notes/85-fsm.md)
- [ ] [Parser Combinators – Building parsers with types](/track-01-core/04-typescript/notes/86-parser.md)

**Project:** [Type-Safe Architecture Patterns](/track-01-core/04-typescript/projects/12-architecture-patterns/)

---

### Part XIII: Declaration Files & DefinitelyTyped
- [ ] [Writing `.d.ts` Files – Manual declarations](/track-01-core/04-typescript/notes/87-dts.md)
- [ ] [Augmenting Existing Types – Module augmentation](/track-01-core/04-typescript/notes/88-augmentation.md)
- [ ] [Global Types – Adding to `window`, etc.](/track-01-core/04-typescript/notes/89-global.md)
- [ ] [Contributing to DefinitelyTyped](/track-01-core/04-typescript/notes/90-definitely-typed.md)
- [ ] [Publishing Typed Packages](/track-01-core/04-typescript/notes/91-publishing.md)

**Project:** [TypeScript Type Definitions](/track-01-core/04-typescript/projects/13-type-definitions/)

---

### Part XIV: Performance & Optimization
- [ ] [Compilation Performance – Project references, incremental](/track-01-core/04-typescript/notes/92-compilation-performance.md)
- [ ] [Type Checking Performance – Optimizing complex types](/track-01-core/04-typescript/notes/93-type-performance.md)
- [ ] [Bundle Size – Impact of types on output](/track-01-core/04-typescript/notes/94-bundle-size.md)
- [ ] [Editor Performance – TS Server optimization](/track-01-core/04-typescript/notes/95-editor-performance.md)

**Project:** [Performance Audit](/track-01-core/04-typescript/projects/14-performance-audit/)

---

### Part XV: Migrating to TypeScript
- [ ] [Migration Strategies – Incremental adoption](/track-01-core/04-typescript/notes/96-migration-strategies.md)
- [ ] [Adding Types to JavaScript – JSDoc annotations](/track-01-core/04-typescript/notes/97-jsdoc.md)
- [ ] [Allow JS – Mixed JS/TS projects](/track-01-core/04-typescript/notes/98-allow-js.md)
- [ ] [Strict Mode Adoption – Gradual strictness](/track-01-core/04-typescript/notes/99-strict-mode.md)
- [ ] [Handling Third-Party Untyped Libraries](/track-01-core/04-typescript/notes/100-untyped-libraries.md)

**Project:** [Migration Case Study](/track-01-core/04-typescript/projects/15-migration-case-study/)

---

## 🎯 Capstone Project

After completing all sections, build: **[Production-Ready TypeScript Application](/track-01-core/04-typescript/projects/capstone/)**

A full-stack TypeScript application demonstrating everything learned:
- Strict type safety throughout
- Generic utilities
- Advanced type patterns
- Proper module organization
- React or Node.js integration
- Declaration files if publishing
- Performance-optimized types

---

## 📚 Resources

- [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/)
- [TypeScript Deep Dive](https://basarat.gitbook.io/typescript/)
- [Type Challenges](https://github.com/type-challenges/type-challenges)
- [Effective TypeScript (book)](https://effectivetypescript.com/)
- [TypeScript Weekly](https://typescript-weekly.com/)

---

## 🔗 Cross-Track Connections

| Concept | Connects To |
|---------|-------------|
| Basic types | [JavaScript fundamentals](/track-01-core/03-javascript/roadmap.md) |
| React with TypeScript | [Frontend frameworks](/track-07-specializations/01-frontend-frameworks/roadmap.md) |
| Node.js with TypeScript | [Backend development](/track-04-web-platforms/02-backend-api/roadmap.md) |
| Build tooling | [Development practices](/track-06-development-practices/03-build-tools/roadmap.md) |

---

## ✅ Progress Summary

| Section | Status | Completed |
|---------|--------|-----------|
| Part I: Foundations | ⚪ Not Started | 0/6 |
| Part II: Essential Types | ⚪ Not Started | 0/9 |
| Part III: Functions | ⚪ Not Started | 0/7 |
| Part IV: Interfaces & Type Aliases | ⚪ Not Started | 0/8 |
| Part V: Classes | ⚪ Not Started | 0/8 |
| Part VI: Generics | ⚪ Not Started | 0/10 |
| Part VII: Advanced Types | ⚪ Not Started | 0/7 |
| Part VIII: Modules & Namespaces | ⚪ Not Started | 0/6 |
| Part IX: Configuration & Tooling | ⚪ Not Started | 0/6 |
| Part X: React with TypeScript | ⚪ Not Started | 0/8 |
| Part XI: Node.js with TypeScript | ⚪ Not Started | 0/5 |
| Part XII: Advanced Type Patterns | ⚪ Not Started | 0/6 |
| Part XIII: Declaration Files | ⚪ Not Started | 0/5 |
| Part XIV: Performance | ⚪ Not Started | 0/4 |
| Part XV: Migration | ⚪ Not Started | 0/5 |

**Overall:** 0/100 topics (⚪ 0%)

---

## Next: [Track 01 Core README](/track-01-core/README.md)
