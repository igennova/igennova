# Lalit Negi

Backend engineer. I build real-time systems, AI pipelines, and open-source infrastructure.

## Experience

**Google Summer of Code 2025** — OWASP Foundation  
Built a WebRTC video engine, live leaderboard with Redis and WebSockets, and a CTF-style security simulation lab.

**AI Engineer** — PUCH AI  
Built a multi-tool LLM agent with Redis + Lua rate limiting stable for 10k+ users; unified image/video generation into a single inference layer.

**Backend Developer** — Persist Venture  
Architected an AI-powered media pipeline using FastAPI and PostgreSQL.

## Projects

**[Distributed Vector Search Engine](https://github.com/igennova/Distributed-Vector-Search-Engine)** — ANN search from scratch  
HNSW nearest-neighbor search built from scratch (0.93 recall@10 at 2.5× lower latency vs exact). Sharded across gRPC services with a scatter-gather coordinator; cut 4-shard latency 3.5× (5.6 → 1.6 ms) after profiling GIL contention. Python + gRPC + NumPy.

**[WeMakeVideos](https://quotesnap-alpha.vercel.app/)** — AI text-to-video SaaS (demo landing)  
End-to-end prompt → script → voice → scenes → render workflow built with Next.js + TypeScript + Remotion. Public demo showcases the landing + product preview; full app walkthrough available on request.

**[ZeroCostShorts](https://github.com/igennova/ZeroCost-Shorts)** — Automated AI video pipeline (76★)  
Fully autonomous pipeline (LLM → TTS → image gen → FFmpeg render → YouTube upload) running daily via GitHub Actions at ~$0/day. Forked by others for their own workflows.

**[LeetFight](https://leetfight.xyz)**  
Real-time 1v1 coding arena. Players compete on the same problem simultaneously with live code sync, instant judging, and an ELO rating system. 180+ active users, sub-50ms WebSocket latency.

## Open Source Contributions
* @PostHog ( [Link](https://github.com/PostHog/posthog/issues?q=is%3Apr%20is%3Amerged%20author%3Aigennova) )
* @antiwork ( [Link](https://github.com/antiwork/gumroad/issues?q=is%3Apr%20is%3Amerged%20author%3Aigennova) )
* @antiwork/gumboard ( [Link](https://github.com/antiwork/gumboard/issues?q=is%3Apr%20is%3Amerged%20author%3Aigennova) )
* @antiwork (bounty PRs via @devwill2) ( [Link](https://github.com/antiwork/gumroad/issues?q=is%3Apr%20is%3Amerged%20author%3Adevwill2) )
* @OWASP-BLT ( [Link](https://github.com/OWASP-BLT/BLT/issues?q=is%3Apr%20is%3Amerged%20author%3Aigennova) )
* @openml ( [Link](https://github.com/openml/server-api/pulls?q=is%3Apr+author%3Aigennova+is%3Aclosed) )
* @getnao ( [Link](https://github.com/getnao/nao/pulls?q=is%3Apr+author%3Aigennova+is%3Aclosed) )
* @PalisadoesFoundation ( [Link](https://github.com/PalisadoesFoundation/talawa-api/pulls?q=is%3Apr+author%3Aigennova+is%3Amerged) )

### Fun Projects
**[text-to-video-engine](https://text-to-video-1wr1.onrender.com/)** — AI video generation  
**[seedhe-maut-player](https://seedhe-maut-three.vercel.app/)** — Custom music player  
**[anime-predictor](https://anime-predictor-ulob.vercel.app/)** — LeetCode to anime matcher  
**[doc-o-drop](https://doc-o-drop.vercel.app/)** — AI health and wellness platform

## Stack
- Backend & APIs: FastAPI, Node.js, Django, REST, WebSockets, WebRTC, gRPC
- Frontend: Next.js
- Databases & Caching: PostgreSQL, Redis (with Lua scripting)
- Queue & Jobs: BullMQ
- DevOps & Infra: Docker, AWS (Lambda), CI/CD
- Languages: TypeScript, Python, C++
- Concepts: System Design, Scalable Systems, Microservices
- Other: Remotion, FFmpeg, Supabase

## Highlights
- $20,000+ in open-source bounties
- GSoC 2025 contributor at OWASP
- Multiple hackathons won
- LeetCode 1815 

---

Open to collaborating on backend systems, real-time infrastructure, and AI pipelines.

[luckynegi1025@gmail.com](mailto:luckynegi1025@gmail.com) · [Portfolio](https://luckynegi.in)
