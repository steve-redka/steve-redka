## Stepan Redka
- cogitofallacy@gmail.com
- Telegram: https://web.telegram.org/k/#@thirtythreelemons

Backend developer (Ruby on Rails) with over 4 years of commercial experience in the development of microservices and high-load web services. Specializes in architecture design and refactoring, integrating external APIs, testing (RSpec/Minitest), CI/CD, and performance optimization.
From 2022 to 2025, while working at Yandex Crowd, actively developed open-source projects in Ruby/Rails and JavaScript (CLI utilities, Rails engines, browser add-ons).

## Skills


- **Languages and Frameworks**: Ruby (4+ years), Ruby on Rails, JavaScript (ES6+), React, CoffeeScript, Lua
- **Testing**: RSpec, Minitest, Jest, Capybara
- **Databases and Cache**: PostgreSQL, Redis, SQL, SQLite
- **Queues and Integrations**: RabbitMQ, Active Job, REST API
- **Infrastructure and Tools**: Docker, Docker Compose, Git, Linux
- **AI / LLM**: OpenAI & Yandex GPT APIs, LLM tool/function calling, RAG with pgvector embeddings, semantic search, prompt engineering, token/cost tracking; keras, pandas, numpy, stable diffusion, automatic1111
- **Engineering Practices**: OOP, SOLID, microservice architecture, event-driven architecture, caching, logging, CI/CD, code review, refactoring, deployment automation

## Job experience

**Full-stack developer**
~ Food expert
~ 02.2026 - 07.2026
- Enterprise Franchise Management Platform
- Developed and maintained a multi-tenant SaaS platform for franchise management, comprising four independently deployed services: two React 18/TypeScript frontends and two Node.js/Express backends. Designed and implemented tenant-isolated data access patterns to ensure strict data segregation across franchise owners and individual client locations using PostgreSQL, hardening tenant boundaries by closing permission-bypass gaps. Reduced background-job database load by ~60–70% through query batching and parallelized external-API collection.
- Built and maintained asynchronous background processing pipelines using BullMQ and Redis for tasks including third-party restaurant management system integration (iiko) and automated review aggregation via web scraping (Puppeteer). Integrated AWS services (S3 for file storage, SES for transactional email) and implemented rich text content management using EditorJS across both frontend and backend systems.
- Implemented frontend state management with Zustand and server-state synchronization via React Query. Built responsive, data-dense UI with Ant Design and TailwindCSS, handling complex layout constraints to prevent overflow in table-heavy views. Contributed to an integrated knowledge base module with its own dedicated frontend and backend, enabling franchise operators to manage and distribute operational documentation across their networks.
- Built an AI subsystem for the platform: a provider-agnostic LLM layer (OpenAI and Yandex GPT) with per-request token and cost tracking, a function-calling "intent" agent that translates natural-language questions into parallel queries across ~18 analytics tools, and BullMQ-backed asynchronous report-generation pipelines with multi-step report chains. Added retrieval-augmented semantic search over customer reviews using pgvector embeddings, and an LLM-based review auto-categorization pipeline running in background workers.

**Open Source Developer (Ruby / Ruby on Rails)**
~ 2012 - present
- Developed and maintain a CLI utility for working with Bitcoin RPC API (Ruby): sending transactions, key management, basic logging, and unit tests.
- Implemented a fullstack engine for finding tabletop games (Rails + PostgreSQL, Turbo Streams): profiles, requests, schedules, notifications, and authorization.
- Improved the open-source utility rails-diff: added new CLI flags, filtering, refactored service objects, and tested core logic (RSpec).

**Assessor/AI Trainer with Coding Knowledge** 
~ Yandex Crowd
~ Dec 2021 - present

- Evaluated ML model solutions in backend, frontend, DevOps, ML, and mobile tasks based on specified quality criteria.
- Analyzed and fixed code in Python, JavaScript, C/C++: checked logic correctness, readability, and functionality.
- Developed reference solutions and detailed comments, helping enhance the quality of model responses.
- Concurrently developed my own open-source projects in Ruby/Rails and JavaScript (see "Open Source" section).

**Ruby Developer** 
~ Jetruby
~ Dec 2019 - Jun 2020
- Designed and implemented a Ruby SDK for working with the CDN API Uploadcare: authorization, resource management, configuration, and content updating.
- Improved library architecture and public API interfaces, making the SDK predictable and convenient for integration.
- Covered key modules with unit tests (RSpec, Minitest) and set up automated test runs in CI, reducing the number of regression errors.

**Ruby Developer** 
~ Rambler
~ Dec 2018 - Aug 2019
- Developed and maintained high-load microservices on Ruby on Rails using Redis (caching, distributed operations).
- Optimized CRM modules (Refinery, ActiveAdmin) and inter-service interactions, reducing average response time for critical endpoints (O(n^2) -> O(n)).
- Conducted architectural refactoring: decomposed monolithic modules, improved data structure and API contracts between services.
- Implemented engineering practices: code review, testing critical sections, logging, and deployment automation.

**Ruby on Rails Developer** 
~ 8pcode
~ Dec 2017 - Sep 2018
- Developed a real estate management system on Ruby on Rails + PostgreSQL: domain model, CRUD interfaces, business logic.
- Set up CI/CD pipelines (build, tests, deployment), reducing the time to deliver new features to production.
- Implemented internationalization (i18n) in the customer loyalty system and revamped the view structure, simplifying the addition of new locales.
- Participated in designing the database schema and optimizing SQL queries to enhance performance.

**System Administrator / Editor**
~ Mrakopedia
~ Mar 2011 - Jul 2014
- Deployed and administered high-load MediaWiki projects on Linux servers: setup, optimization, monitoring.
- Configured network infrastructure and integrations, ensuring stable operation of websites under load.
- Automated routine operations (scripts, templates), reducing labor costs for content maintenance.

## Open Source

**Bitcoin-CLI**
~ Project Author
~ 2025

CLI utility for working with Bitcoin RPC API (Ruby)

- Implemented commands for sending transactions, retrieving balances, and managing keys via Bitcoin RPC API.
- Added modular tests, increasing reliability and ease of debugging when working with the blockchain.

**DMFinder**
~ Project Author
~ 2024-2025

Engine for a service that finds tabletop games (Ruby on Rails, PostgreSQL, Turbo Streams)
- Developed a fullstack platform for searching and organizing game sessions: player and master profiles, requests, schedules.
- Implemented real-time updates using Turbo Streams, a notification system, and authorization.
- Designed the domain model (Rails + PostgreSQL) and covered key business logic with tests.

**rails-diff**
~ Contributor
~ 2025
- Extended the CLI interface: added new flags and more flexible file filtering.
- Conducted refactoring of service objects, isolating stable structures and a unified interface.
- Covered key business logic with tests (RSpec) and improved documentation, making it easier for new users to get started.

**Yang-favorite-task-checker**
~ Author
~ 2024-present

- Developed a user browser add-on in JavaScript for monitoring new tasks in real-time.
- Implemented DOM change observation, event filtering, and notifications when suitable tasks appear.

**Hermes / Cross-Faction Translation**
~ Project Author
~ 2024

Reverse-engineered a game's cross-faction chat obfuscation and built an end-to-end toolchain (Lua + Ruby) to translate messages between factions

- Identified the per-faction chat scrambling as a monoalphabetic substitution cipher and recovered the substitution tables via a known-plaintext attack on aligned chat logs.
- Built a Ruby data pipeline — probe-text generators covering targeted UTF-32 ranges and a dictionary extractor — plus a throttle-aware in-game Lua addon to collect the data.
- Shipped a packaged Lua addon (slash commands, longest-match tokenizer, fallback substitutions, length validation, live preview) with README, CONTRIBUTING, CI, and a CurseForge release.

**Gemcraft FW Secret Code Calculator**
~ Project Author
~ 2024

Reverse-engineered a game's hidden access-code scheme and built a deployed web calculator that reconstructs it (Next.js, React, TailwindCSS)

- Reverse-engineered the code structure as an overlapping-fragment reconstruction problem: short achievement codes chain head→middle→tail with a 2-character overlap to form the full secret code.
- Implemented the chaining/filtering algorithm in JavaScript and covered it with Jest tests using real in-game achievement-to-code fixtures (TDD).
- Built and deployed the tool as a Next.js/React/Tailwind front-end with a live-recalculating input.
