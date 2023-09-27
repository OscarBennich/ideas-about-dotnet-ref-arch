# ideas-about-dotnet-ref-arch
A collection of my ideas, examples, and resources regarding architecture and tech choices for a full-stack enterprise-level .NET Web Application.

---

# Back-end
.NET Core C# (.NET 6/7/8)

## Why C#?
- Popular (Top 7 on GitHub repositories if you discount non-programming languages like Dockerfiles and Makefiles)

![image](https://github.com/OscarBennich/ideas-about-dotnet-ref-arch/assets/26872957/9f44b3f0-d5d0-42e7-8804-a5e1c0d9230f)
https://innovationgraph.github.com/global-metrics/programming-languages

- Open-source
- Cross-platform
- Strongly typed
- Compiled
- Actively developed
- Performant (ASP.NET Core composite score is #7 / 141 frameworks tested on [TechEmpower.com](https://www.techempower.com/benchmarks/#section=data-r21&hw=ph&test=composite))

![image](https://github.com/OscarBennich/ideas-about-dotnet-ref-arch/assets/26872957/61afb960-4b8c-4b4d-b6ee-19c5f8dfbe2b)

## Database
### MySQL
## ORM
### EF Core
### Dapper
## Useful libraries
### MediatR

## API
- Minimal APIs? [Goodbye controllers, hello Minimal APIs - Nick Chapsas - NDC London 2022](https://www.youtube.com/watch?v=hPpvlKLeYYA)

# Front-end
- Protyping tool for colors and fonts: [Realtime Colors](https://www.realtimecolors.com/?colors=000000-ffffff-8fb3ff-ebf1ff-d41d6d)
## Server-Side Rendering (SSR) vs. Client-Side Rendering (CSR)
### Server-Side Rendering
#### ASP.NET MVC
### Client-Side Rendering
#### How to handle Authentication & Authorization?
#### Frameworks
##### Blazor
- [What is the Future of Blazor? Should I Learn Blazor?](https://www.youtube.com/watch?v=OUUlO8fQOfE)
- [Running Blazor in production, lessons learned - Jimmy Engström - NDC London 2023](https://www.youtube.com/watch?v=bZdYpYQb958)
## SPA vs. MPA
### Razor views vs. Razor pages

## JavaScript
### JavaScript vs. TypeScript
- TypeScript resource: [Matt Pocock](https://www.youtube.com/@mattpocockuk/videos)
### Frontend Frameworks
### Svelte
- [Understanding Svelte (vs React)](https://www.youtube.com/watch?v=lYYGhm7p74Q)
#### React
- [React+TypeScript Cheatsheets](https://github.com/typescript-cheatsheets/react)
#### Meta-framework?
### Component library?

# Deployment
## Azure

# Architecture
## CQRS
- [Martin Fowler](https://martinfowler.com/bliki/CQRS.html)
- [Microsoft Learn](https://learn.microsoft.com/en-us/azure/architecture/patterns/cqrs)
- [TechTarget](https://www.techtarget.com/searchapparchitecture/definition/CQRS-command-query-responsibility-segregation)
  
## Talks & Presentations
- [Modular Monoliths • Simon Brown • GOTO 2018](https://www.youtube.com/watch?v=5OjqD-ow8GE)
  - [17:45](https://youtu.be/5OjqD-ow8GE?t=1065): Example of adding a feature in a system without clear encapsulation/structure, controllers calling repositories, etc...
  - [18:50](https://youtu.be/5OjqD-ow8GE?t=1130): If previous example is left unchecked, what happens? References between everything...
  - [19:31](https://youtu.be/5OjqD-ow8GE?t=1171): "Big Ball of Mud", "Its organization [...] is dictated more by expediency than design"
  - [29:24](https://youtu.be/5OjqD-ow8GE?t=1764): The effects of an overuse of the "public" keyword
  - [34:47](https://youtu.be/5OjqD-ow8GE?t=2087): Using encapsulation to minimize dependencies
  - [39:52](https://youtu.be/5OjqD-ow8GE?t=2392): "When you change something here, a whole bunch of stuff here breaks and you don't know why [...]"
  - [40:03](https://youtu.be/5OjqD-ow8GE?t=2403): Good architecture/good structure/high modularity enables fast development
  - [42:14](https://youtu.be/5OjqD-ow8GE?t=2534) / [44:47](https://youtu.be/5OjqD-ow8GE?t=2687): Start with a Modular Monolith THEN (maybe) move into Microservices
## Articles
## Books

# Testing
## Useful libraries
## Strategy

# Version-control (git)
## Branching strategy
## Merge strategy
## Thoughts about commit messages
