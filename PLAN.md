# 8-Week Developer Learning Plan

Start: 2026-10-15
Goal: 2026-12-09

How to tick a topic: change `[ ]` to `[x]`, then click **Commit changes**. The website updates in about a minute.

## Week 1: Project stories + Git
Word: pipeline = a series of steps where the output of one step goes into the next.
Learn: [Learn Git Branching](https://learngitbranching.js.org)
Speak: Explain one of your projects to a non-technical person.
Speak: What is the difference between Git and GitHub?

- [ ] **Tell me about yourself:** a 60-second answer (see the English section)
- [ ] **Project stories:** for each main project, the problem, the tech, one challenge and the result
- [ ] **Data pipeline project:** draw the flow on paper and explain why each step exists
- [ ] **Pareto / ABC analysis:** how a few items can make most of the volume
- [ ] **Team story:** one real example of a problem you solved with a team
- [ ] **Git basics:** repository, commit, branch, merge, clone, pull, push
- [ ] **GitHub:** pull request, README, GitHub Pages

## Week 2: Web basics
Word: semantic = related to meaning. Semantic HTML tells the browser what each part of the page means.
Learn: Udemy - Complete Web Development (HTML, CSS, Tailwind sections)
Learn: [MDN Learn Web Development](https://developer.mozilla.org/en-US/docs/Learn_web_development)
Speak: What is the box model?
Speak: Flexbox or Grid: when do you use each?

- [ ] **HTML5:** semantic tags (header, nav, main, section, footer), forms, and why semantic tags help SEO and screen readers
- [ ] **CSS3:** box model, Flexbox, Grid, position, units (px, rem, %, vh)
- [ ] **Responsive design:** media queries, mobile-first
- [ ] **Tailwind CSS:** utility classes, and why use it instead of normal CSS
- [ ] **Bootstrap:** the 12-column grid system
- [ ] **JavaScript basics:** let and const, data types, functions, arrays, objects, loops

## Week 3: JavaScript deep dive + TypeScript
Word: asynchronous = not waiting in line; the code keeps running while it waits for something slow.
Learn: [javascript.info](https://javascript.info)
Learn: [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
Speak: What is async/await?
Speak: Why use TypeScript instead of JavaScript?

- [ ] **ES6+:** arrow functions, destructuring, spread, template literals, import and export
- [ ] **DOM:** select elements, handle events (click, submit)
- [ ] **Async JavaScript:** callbacks, promises, async/await, the fetch API
- [ ] **JSON:** what it is, JSON.parse and JSON.stringify
- [ ] **Interview topics:** scope, closures, hoisting, the `this` keyword
- [ ] **TypeScript:** types, interfaces, and why TypeScript catches errors early

## Week 4: React, Next.js, PWA, SEO
Word: render = to build the page and show it on screen.
Learn: [react.dev/learn](https://react.dev/learn)
Learn: [nextjs.org/learn](https://nextjs.org/learn)
Learn: [web.dev Learn PWA](https://web.dev/learn/pwa)
Learn: [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
Speak: What is the difference between props and state?
Speak: Why Next.js instead of plain React?

- [ ] **React:** components, props, state, JSX
- [ ] **Hooks:** useState, useEffect, and when useEffect runs
- [ ] **React patterns:** lists and keys, conditional rendering, forms
- [ ] **Next.js App Router:** pages, layouts, routing by folders
- [ ] **Next.js rendering:** server vs client components, SSR vs static pages (SSG)
- [ ] **Framer Motion:** a basic animation with motion.div
- [ ] **PWA:** manifest file, service worker, "install app"
- [ ] **SEO:** title and meta description, sitemap.xml, robots.txt, Google Search Console

## Week 5: Backend + databases
Word: authorization = permission to do something. After login, it decides which pages a user can open.
Learn: Udemy - Complete Web Development (Node, Express, MongoDB sections)
Learn: [SQLBolt](https://sqlbolt.com)
Learn: [Node.js Learn](https://nodejs.org/en/learn)
Speak: What is a REST API?
Speak: Authentication vs authorization?
Speak: SQL or NoSQL?

- [ ] **Node.js:** JavaScript on the server, npm, package.json
- [ ] **Express.js:** routes, middleware, request and response
- [ ] **REST API:** GET, POST, PUT/PATCH, DELETE, and status codes 200, 201, 400, 401, 403, 404, 500
- [ ] **CORS:** what it is and why the browser blocks some requests
- [ ] **Auth:** authentication vs authorization, sessions vs JWT, RBAC (role-based access control)
- [ ] **SQL:** SELECT, WHERE, ORDER BY, GROUP BY, JOIN, primary key, foreign key
- [ ] **PostgreSQL, MySQL, MongoDB:** SQL vs NoSQL, and when to use which

## Week 6: Deployment, cloud + Python
Word: automate = make a task run by itself, with no manual work.
Learn: [GitHub Actions docs](https://docs.github.com/en/actions)
Learn: Udemy - Generative & Agentic AI with Python (Python sections)
Speak: Explain a GitHub Actions workflow step by step.
Speak: When do you use Requests and when Selenium?

- [ ] **CI/CD:** continuous integration and continuous deployment, in simple words
- [ ] **GitHub Actions:** workflow YAML file, triggers (push, schedule), jobs, steps, secrets
- [ ] **Cron:** how "every 30 minutes" is written (`*/30 * * * *`)
- [ ] **Deployment:** GitHub Pages vs Vercel, environment variables
- [ ] **DNS:** domain, A record, CNAME, TXT
- [ ] **AWS basics:** EC2 (a server), S3 (file storage), what "the cloud" means
- [ ] **Python basics:** variables, lists, dictionaries, functions, loops, pip
- [ ] **Web scraping:** Requests, BeautifulSoup, Selenium, and respecting robots.txt

## Week 7: Data + UI/UX
Word: insight = a clear, useful understanding found in data.
Learn: [Microsoft Learn - Power BI](https://learn.microsoft.com/en-us/training/powerplatform/power-bi)
Learn: [Figma Help Center](https://help.figma.com)
Speak: How do you find the most important items in a big dataset?
Speak: What is the difference between a wireframe and a prototype?

- [ ] **Advanced Excel:** XLOOKUP/VLOOKUP, IF, SUMIFS, COUNTIFS, pivot tables, data validation, conditional formatting
- [ ] **Google Sheets:** the same formulas, plus sharing and IMPORTRANGE
- [ ] **Data cleaning:** remove duplicates, fix formats, find missing values
- [ ] **Pricing and inventory analysis:** ABC/Pareto, fast vs slow-moving stock, margin vs markup
- [ ] **Power BI:** import data, make a chart, build a dashboard, add a filter (slicer)
- [ ] **UI/UX:** wireframe vs prototype vs final design, user-centred design, contrast, spacing, hierarchy
- [ ] **Figma:** frames, auto layout, components, prototype links

## Week 8: AI concepts + mock interviews
Word: leverage = to use something to get a better result.
Learn: Udemy - Generative & Agentic AI with Python (prompting, RAG, agents sections)
Learn: [Claude prompt engineering guide](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview)
Speak: What is RAG and why is it useful?
Speak: What is an AI agent?

- [ ] **LLM basics:** what a large language model is, tokens, context window
- [ ] **Prompt engineering:** zero-shot, few-shot, chain-of-thought, role prompts
- [ ] **Embeddings + vector database:** meaning stored as numbers, search by similarity
- [ ] **RAG:** retrieval-augmented generation, giving the AI your own documents
- [ ] **AI agents:** an LLM that can use tools and take several steps
- [ ] **LangChain and LangGraph:** what each one is for, in one sentence
- [ ] **FastAPI:** a Python framework for building APIs
- [ ] **MCP (Model Context Protocol):** a standard way to connect AI to tools and data
- [ ] **PHP, Elixir, Java, C, C++:** revise the basics for one day each
- [ ] **3 full mock interviews**

## English practice
Word: candid = honest and open.
Speak: Use the 3-sentence rule: what it is, why it is used, where you used it.
Speak: Use STAR for stories: Situation, Task, Action, Result.
Speak: Tell me about yourself: name and role, degree, 2 projects with numbers, what you are learning, what you want next.

- [ ] **Tell me about yourself:** record it 3 times and keep the best version
- [ ] **STAR stories:** record one for each of your 4 biggest projects
- [ ] **Words of the week:** use each of the 8 words in your own sentence
- [ ] **Sunday mock interviews:** one every week
