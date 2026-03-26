# Claude Code Template for Spring Boot Application

> **Credits:** This repository is forked from [piomin/claude-ai-spring-boot](https://github.com/piomin/claude-ai-spring-boot) by [Piotr Minkowski](https://github.com/piomin). The only changes in this fork concern the use of **Lombok** to reduce boilerplate code.

This template provides a structured starting point for Spring Boot applications, optimized for Claude AI's code completion capabilities. It includes essential configurations and best practices to streamline development and enhance productivity.

The idea behind this template is that you can just clone this repository and use it to generate the app you want with Claude Code.

NOTE: Microsoft CoPilot also uses and reads skills and agents.

```shell
.
├── .claude
│   ├── agents
│   │   ├── code-reviewer.md
│   │   ├── devops-engineer.md
│   │   ├── docker-expert.md
│   │   ├── java-architect.md
│   │   ├── kubernetes-specialist.md
│   │   ├── security-engineer.md
│   │   ├── spring-boot-engineer.md
│   │   └── test-automator.md
│   ├── settings.local.json
│   └── skills
│       ├── README.md
│       ├── api-contract-review
│       │   └── SKILL.md
│       ├── clean-code
│       │   └── SKILL.md
│       ├── design-patterns
│       │   └── SKILL.md
│       ├── java-architect
│       │   ├── SKILL.md
│       │   └── references
│       │       ├── jpa-optimization.md
│       │       ├── reactive-webflux.md
│       │       ├── spring-boot-setup.md
│       │       ├── spring-security.md
│       │       └── testing-patterns.md
│       ├── java-code-review
│       │   └── SKILL.md
│       ├── jpa-patterns
│       │   └── SKILL.md
│       ├── logging-patterns
│       │   └── SKILL.md
│       ├── spring-boot-engineer
│       │   ├── SKILL.md
│       │   └── references
│       │       ├── cloud.md
│       │       ├── data.md
│       │       ├── security.md
│       │       ├── testing.md
│       │       └── web.md
│       └── spring-boot-patterns
│           └── SKILL.md
├── CLAUDE.md
├── README.md
└── pom.xml
```

You can find the detailed explanation and description of this template in Piotr Minkowski's post [Claude Code Template for Spring Boot](https://piotrminkowski.com/2026/03/24/claude-code-template-for-spring-boot/).

## Credits

This repository is based on the original work by [Piotr Minkowski](https://github.com/piomin). The original repository can be found at [https://github.com/piomin/claude-ai-spring-boot](https://github.com/piomin/claude-ai-spring-boot).