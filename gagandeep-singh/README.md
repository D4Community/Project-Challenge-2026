# 🤷 Dev Excuse Generator API

> **Assigned to:** Gagandeep Singh  
> **Difficulty:** Intermediate  
> **Estimated Time:** 6-8 hours (1-2 hours/day for 4 days)  
> **Deadline:** January 10, 2026

---

## 📌 Project Overview

Build a REST API that returns random funny developer excuses! Create both the API and a simple frontend to display excuses. Perfect for when your code doesn't work! 😄

### Example API Response:
```json
{
  "excuse": "It works on my machine",
  "category": "classic",
  "id": 42
}
```

### Example Excuses:
- "It works on my machine"
- "That's a feature, not a bug"
- "It must be a caching issue"
- "The requirements changed"
- "Works fine in development"

---

## 🎯 What You'll Learn

| You Already Know | You Will Learn |
|------------------|----------------|
| React | Building REST APIs with Express |
| Java/SQL basics | API design & endpoints |
| Basic backend | Deploying Node.js apps |

---

## ✅ Tasks

- [ ] Set up Express.js project
- [ ] Create a JSON file with 50+ developer excuses
- [ ] Add categories (classic, blame-others, technical, deadline)
- [ ] Build these API endpoints:
  - GET /api/excuse - random excuse
  - GET /api/excuse/:id - specific excuse
  - GET /api/excuse/category/:cat - random from category
  - GET /api/excuses - all excuses
- [ ] Add proper error handling and status codes
- [ ] Add CORS for frontend access
- [ ] Build simple React frontend to display excuses
- [ ] Add "Get New Excuse" button
- [ ] Deploy API on Render, Frontend on Vercel

---

## 🌟 Bonus Challenges

- [ ] **+5 points:** Add POST endpoint to submit new excuses
- [ ] **+10 points:** Add share to Twitter button with excuse
- [ ] **+10 points:** Add daily excuse feature (same excuse all day)
- [ ] **+5 points:** Add excuse rating system (upvote/downvote)

---

## 📦 Deliverables

1. Working REST API with all endpoints
2. Simple frontend consuming the API
3. Both deployed live
4. Code pushed to GitHub
5. API documentation in README

---

**Good luck! 🚀**
