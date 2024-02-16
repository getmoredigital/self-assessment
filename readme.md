# Self-Assessment
I have found it difficult to accurately self assess one's familiarity and comfort with the many different aspects of programming. In so, I am enduvoring over a period of time to experiment with creating a tool for the task using an LLM+ to create a system that can help at least me have some sort of metric to guide my self-driven learning journey in software engineering.

Note: The system will be manual at first as it merges a UI system for the idea with a manually created self-evaluation taken from myself and senior colleagues.

## Starting Point
The system should be able to generate unique tests, which evalute for certian principles applied in that languge,library,framework,service etc. If not all principles are seen, it will continuely generate challanges, thus able to serve as a learning tool.

In order to chart progress. The system will generate a floating point score between 0-10, where 0 is no knowledge and 6 is expert knowledge. The system should be also be able to suggest areas to focus learning and micro-projects to work on for that level.

## Abilites
- [ ] Take in a subject target and gage appropriate format
- [ ] Generate unique tests
- [ ] Evaluate for certain principles
- [ ] Generate a floating point score
- [ ] Suggest areas to focus learning
- [ ] Suggest micro-projects to work on
- [ ] Generate a repository or report demostrating the principles tested

## Initital Areas
### Categories
- [ ] Programming Languages (E.g. Javascript, Python, C++)
- [ ] Topics (e.g. Machine Learning, Data Science, Career Readiness)
- [ ] Data (e.g. SQL, Regex, Graph, HTML, XML, JSON, YAML, TOML)
- [ ] Design (e.g. Css, SVG, Canvas, WebGL)

### Possible subcategories for Programming Languages
- [ ] Libraries (e.g. fp-ts, lodash, underscore, rxjs )
- [ ] Frameworks (e.g. React, Vue, Angular)
- [ ] Ecosystem (e.g. Node, NPM, Yarn, Webpack, Babel)

### Possible subcategories for Topics
- [ ] Services
- [ ] Applications

### Possible subcategories for Data
- [ ] Services
- [ ] Applications
- [ ] Tools

## Stack
Currently thinking:
- Go
- Data: Pocketbase or SQLite
- Local Server: No Framework, Gin, or Echo
- CLI: Bubble Tea & Lipgloss
- UI: Static, React or Vue
- Config: TOML
