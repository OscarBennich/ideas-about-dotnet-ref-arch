# ideas-about-dotnet-ref-arch
A collection of my ideas, examples, and resources regarding architecture and tech choices for a full-stack enterprise-level .NET Web Application.

---
# Back-end
.NET Core C# (.NET 6/7/8)

## Database
### MySQL
## ORM
### EF Core
### Dapper
## Useful libraries
### MediatR

# Front-end
## SPA vs. MPA
## ASP .NET
### Razor views vs. Razor pages

## WASM (Blazor)

## JavaScript
### JavaScript vs. TypeScript
### Frontend Framework
#### React
- [React+TypeScript Cheatsheets](https://github.com/typescript-cheatsheets/react)
#### Meta-framework?
### Component library?

# Deployment
## Azure

# Architecture
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
