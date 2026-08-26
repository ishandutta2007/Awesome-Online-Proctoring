# Awesome-Online-Proctoring

## Top Online Proctoring Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Remote Exam Integrity, AI & Live Proctoring, Browser Lockdown, Identity Verification & Session Recording*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Online Proctoring**. These systems monitor remote exam takers through webcam, microphone, screen recording, browser lockdown, identity checks, and behavioral analytics to uphold assessment integrity for higher education, certification, and corporate testing.



**Examples** include Proctorio, Honorlock, Examity, ProctorU, Mettl Secure Browser, Respondus Monitor, Mercer Mettl, Talview, Inspera Proctoring, and Smowl (the category leaders).



**Open-source emphasis**: Fully featured commercial-grade proctoring platforms are limited in pure open source. Strong building blocks exist in secure browsers, computer-vision cheating detection prototypes, and full-stack exam platforms with video monitoring. This section is expanded with the most relevant open projects.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Starting Pricing | Free Tier / Free Trial Limits |
|:---|:---|:---|:---|
| **[Proctorio](https://proctorio.com/)** | Automated online proctoring offering browser lockdown, recording, identity verification, and review workflows. | ~$8 – $15 / student / year (or $10 / single exam; $20 / course unlimited student-pay) | No free plan; No self-serve trial (custom guided institutional demo available on request) |
| **[Honorlock](https://honorlock.com/)** | AI-powered proctoring with on-demand live proctor pop-in support, balancing automation with human oversight. | ~$8.24 – $10 / exam (or ~$15 – $25 / student / year institutional rate) | No free plan; No self-serve trial (scheduled interactive demo available on request) |
| **[Examity](https://www.examity.com/)** | Multi-tier proctoring (automated, record-and-review, live) for high-stakes testing with exception workflows. | ~$3.75 – $5 / exam (Automated tier); ~$14 – $20 / exam (Live proctoring tier) | No free plan; No self-serve trial (institutional pilot/demo available on request) |
| **[ProctorU (Meazure Learning)](https://www.meazurelearning.com/)** | Live human proctoring with real-time intervention for high-stakes certification and licensing exams. | ~$12.60 – $15 / first hour per exam (+ $7.75 / additional hour) | No free plan; No self-serve trial (institutional platform demo available on request) |
| **[Mercer Mettl](https://mettl.com/)** | Comprehensive assessment & proctoring suite with Mettl Secure Browser, 3-point AI proctoring, and live feed. | ~$2 – $5 / candidate assessment (or ~$2,000 / year base platform tier) | Free trial available with up to 5–10 sample test candidate assessments upon demo sign-up |
| **[Respondus Monitor](https://web.respondus.com/)** | LMS-integrated automated proctoring companion to LockDown Browser using student webcams to record exams. | $4,950 / year flat fee (base tier for 1,000 seats; ~$4.95/seat) or $15 / student / year | 200 free seats/year included with LockDown Browser license; 2-month unlimited institutional free pilot |
| **[Talview](https://www.talview.com/)** | AI-led remote proctoring and assessment platform supporting video interviews, secure browsers, and integrity monitoring. | ~$25,000 / year (enterprise platform tier) or ~$10 – $15 / candidate assessment | No free plan; No self-serve trial (personalized solution demo available on request) |
| **[Inspera Proctoring](https://www.inspera.com/)** | End-to-end digital exam proctoring ecosystem supporting recorded, record-and-review, and live human proctors. | ~$10 – $30 / student / year (or tiered per-candidate rate based on proctoring model) | No free plan; 6-month institutional pilot programs offered for qualifying universities / demo on request |
| **[Smowl](https://smowl.net/)** | Online proctoring with continuous identity verification and automated biometric anomaly detection. | ~$2 – $3 / exam (activity-based license) or ~$10 – $20 / student / year (unlimited exams) | Free trial includes 25 complimentary test proctoring licenses |



## Open-Source GitHub Projects

- **[Safe Exam Browser (SEB)](https://safeexambrowser.org/)**  

  Free, open-source secure browser that locks down the exam environment, restricts applications and websites, and is widely used as a foundation for proctored assessments.



- **[OpenProctor](https://github.com/kamlendras/OpenProctor)**  

  Open-source online proctoring software built with Next.js and TypeScript, providing real-time monitoring and a secure exam environment.



- **[AI-powered exam cheating detection systems](https://github.com/)**  

  Computer-vision projects that detect face presence, multiple faces, eye/gaze movement, talking, and prohibited objects during online exams with real-time alerts.



- **[Proctoring-AI and vision/audio monitors](https://github.com/)**  

  Open prototypes that combine webcam-based eye tracking, mouth movement detection, and audio analysis for automated proctoring signals.



- **[ExamPro (Frappe)](https://github.com/lebmatter/exampro)**  

  Proctored exam application for the Frappe framework with video proctoring, live monitoring, recording, and auto-termination features.



- **[Full-stack proctored exam platforms](https://github.com/)**  

  MERN and similar open projects that combine exam delivery, authentication, real-time monitoring dashboards, and session recording.



- **[CLIP-based and multimedia surveillance proctors](https://github.com/)**  

  Research implementations using modern vision models for automated online exam monitoring and suspicious-activity classification.



- **[Browser lockdown and anti-cheating helpers](https://github.com/)**  

  Open tools that detect tab switching, copy-paste, multi-monitor setups, and other common integrity violations.



- **[Local face-detection and event-logging clients](https://github.com/)**  

  Browser-side or lightweight client projects that run face and gaze detectors locally and stream flagged events to a backend for review.



- **[Session recording and review dashboards](https://github.com/)**  

  Open components for capturing webcam/screen streams and presenting flagged segments to human reviewers.



### Additional Strong Open-Source Options

- Combining Safe Exam Browser with open LMS platforms (Moodle, Open edX) for a lower-cost integrity stack.

- MediaPipe / OpenCV based face and landmark pipelines customized for proctoring rules.

- Self-hosted recording storage and access-controlled review interfaces.

- Privacy-preserving designs that keep raw video local and only transmit anomaly events.

- Research datasets and benchmarks for evaluating online proctoring detectors.



**Frameworks for building custom systems**: Use **Safe Exam Browser** (or equivalent lockdown) as the client environment, add open computer-vision detectors for face/gaze/object signals, stream events (not necessarily continuous video) to a self-hosted backend, and provide a review dashboard for instructors. Pair with an open LMS for exam content and scheduling. This approach offers full data ownership and lower cost — suitable for institutions with development capacity or strong privacy requirements — while commercial platforms still dominate for large-scale live proctoring, identity verification services, legal defensibility, and 24/7 operational support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Online proctoring involves continuous collection of biometric and behavioral data and raises significant privacy, equity, and accessibility concerns. Open-source tools provide transparency but still require careful legal review, informed consent, bias testing, and accommodation policies before production use. Always comply with applicable privacy laws (GDPR, FERPA, etc.) and institutional ethics guidelines.

- Automated flags are probabilistic and can produce false positives; human review and clear appeal processes are essential, especially for high-stakes assessments.



---

**Made for educators, assessment teams, and institutions seeking more transparent approaches to exam integrity.**

Let's make online proctoring more open, privacy-aware, and accountable.
