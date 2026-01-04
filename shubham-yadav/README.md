# 📊 Real-time Poll Battle

> **Assigned to:** Shubham Yadav  
> **Difficulty:** Advanced  
> **Estimated Time:** 6-8 hours (1-2 hours/day for 4 days)  
> **Deadline:** January 10, 2026

---

## 📌 Project Overview

Build a real-time polling application where users can create polls and watch votes update live across all connected clients. Perfect for live events, classrooms, or team decisions!

### Features:
- Create polls with multiple options
- Share poll via unique link
- Vote on polls (one vote per browser)
- Real-time vote count updates
- Live animated bar chart of results
- Poll expiry option

---

## 🎯 What You'll Learn

| You Already Know | You Will Learn |
|------------------|----------------|
| Full MERN Stack | WebSocket rooms (Socket.io) |
| REST APIs | Real-time state synchronization |
| MongoDB | Optimistic UI updates |

---

## ✅ Tasks

- [ ] Set up Express + MongoDB backend
- [ ] Create poll model (question, options, votes, expiry)
- [ ] Implement Socket.io with room-based architecture
- [ ] Each poll = one Socket room
- [ ] When user votes, broadcast updated results to room
- [ ] Build React frontend with poll creation form
- [ ] Build poll voting page with live updating bars
- [ ] Use browser fingerprint/localStorage to prevent double voting
- [ ] Add animated vote bars (CSS transitions)
- [ ] Deploy backend on Render, frontend on Vercel

---

## 🌟 Bonus Challenges

- [ ] **+10 points:** Add poll expiry with countdown timer
- [ ] **+10 points:** Show "X people viewing this poll" live counter
- [ ] **+5 points:** Add confetti animation when voting
- [ ] **+5 points:** Generate shareable result images

---

## 📦 Deliverables

1. Working poll app with real-time updates
2. Multiple users can vote and see live results
3. Deployed live links (frontend + backend)
4. Code pushed to GitHub

---

**Good luck! 🚀**
