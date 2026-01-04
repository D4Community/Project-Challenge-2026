# 🔗 Short URL Service

> **Assigned to:** Daksh Kumar  
> **Difficulty:** Intermediate  
> **Estimated Time:** 6-8 hours (1-2 hours/day for 4 days)  
> **Deadline:** January 10, 2026

---

## 📌 Project Overview

Build a URL shortening service like bit.ly! Users can submit a long URL and get a short link back. When someone visits the short link, they get redirected to the original URL. Track click counts for each link.

### Features:
- Shorten any URL to a short code
- Redirect short URLs to original
- Track click count for each URL
- Show all shortened URLs with stats
- Custom short codes (optional)

---

## 🎯 What You'll Learn

| You Already Know | You Will Learn |
|------------------|----------------|
| Python | Base62 encoding |
| Flask basics | URL redirection |
| SQL databases | SQLAlchemy ORM |

---

## ✅ Tasks

- [ ] Set up Flask project with SQLAlchemy
- [ ] Create database model (original_url, short_code, clicks, created_at)
- [ ] Implement short code generation (Base62 or random string)
- [ ] Create API endpoint to shorten URL (POST /shorten)
- [ ] Create redirect route (GET /:shortcode)
- [ ] Increment click count on each redirect
- [ ] Create endpoint to get URL stats (GET /stats/:shortcode)
- [ ] Build a simple HTML frontend for the service
- [ ] Deploy on Render

---

## 🌟 Bonus Challenges

- [ ] **+5 points:** Allow custom short codes (user-defined)
- [ ] **+10 points:** Add expiry date for URLs
- [ ] **+10 points:** Show click analytics (clicks over time chart)
- [ ] **+5 points:** Add QR code generation for short URLs

---

## 📦 Deliverables

1. Working URL shortener with redirect
2. Click tracking working
3. Deployed live link
4. Code pushed to GitHub

---

**Good luck! 🚀**
