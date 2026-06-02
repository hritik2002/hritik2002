<h2>Hey, I'm Hritik 👋</h2>

Software Engineer at [Dream11](https://www.dream11.com/). I build things at scale during the day and dig into JavaScript internals at night.

Here's my [resume](https://www.hritik.me/resume) if you want the full picture.

---

## What I'm working on

**[WhyNotJS](https://github.com/hritik2002/whynotjs)** — a library I built while learning how `Proxy`, `Error.stack`, and `WeakMap` actually work. It wraps any plain JavaScript object and gives you a full audit trail: who changed this property, when, and from which file and line.

```ts
const user = track({ name: "Hritik" });

user.name = "John";  // ProfileForm.tsx:24
user.name = "Jane";  // UserSettings.tsx:87

why(user, "name");
// Changed 2 times
// 1. Hritik → John   ProfileForm.tsx:24   10:22 PM
// 2. John   → Jane   UserSettings.tsx:87  10:45 PM
```

React DevTools + Git blame, for plain objects.
→ [npm](https://www.npmjs.com/package/whynotjs) · [blog post](https://www.hritik.me/posts/17-whynotjs)

---

## About me

- Full stack engineer — JavaScript, Python, React, Node.js
- Interested in runtime internals, developer tooling, and building things that teach you something
- Built [Bhagavadgita.tech](https://www.bhagavadgita.tech) — because not every side project has to be SaaS
- Looking for collaborators on my current idea — reach out if you like building in public

---

## Tech

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

---

## Projects

| | |
|---|---|
| **[WhyNotJS](https://github.com/hritik2002/whynotjs)** | Proxy-based object change tracking with call-site attribution · [npm](https://www.npmjs.com/package/whynotjs) · [blog](https://www.hritik.me/posts/17-whynotjs) |
| **[Bhagavadgita.tech](https://www.bhagavadgita.tech)** | Clean reading experience for the Bhagavad Gita |
| **[Staygreen](https://staygreen.vercel.app/)** | — |
| **[review-code](https://github.com/hritik2002/review-code)** | AI-powered code review |
| **[Youtube transcriber-summarizer](https://github.com/hritik2002/youtube-transcriber-summarizer)** | Transcribe and summarize any YouTube video |

---

## Find me

[hritik.me](https://www.hritik.me) · [LinkedIn](https://linkedin.com/in/hritik2002) · [Twitter](https://twitter.com/Hritik_86) · [Stack Overflow](https://stackoverflow.com/users/15116207/hritik-sharma) · sharmahritik2002@gmail.com
