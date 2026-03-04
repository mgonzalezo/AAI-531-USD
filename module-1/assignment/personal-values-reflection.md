# Assignment 1: Personal Core Values Reflection

- Course: AAI-531-IN1 - Ethics in Artificial Intelligence
- Module: 1
- Student: Marco Antonio Gonzalez
- Date: March 4, 2026

---

## How My Core Values Affect My Work and Career Choices

After reviewing the Core Values Inventory and reflecting on the Personal Core Values video, I have identified three core values that fundamentally shape my work as a Senior Software Engineer in telecommunications: **transparency**, **integrity**, and **social responsibility**. These values profoundly influence not only what projects I choose to work on but also how I approach technical decisions, vendor relationships, and the long-term implications of the AI-RAN and 6G technologies I help develop.

**Transparency** drives my preference for open-source solutions and open standards in network infrastructure. In an industry dominated by proprietary platforms from vendors like NVIDIA and Wind River, I consistently advocate for architectures that prioritize interoperability and explainability. I actively advocate for upstream open source projects that anyone can contribute to, rather than private or proprietary solutions that limit community participation and scrutiny. This value shapes my technical contributions to O-RAN Alliance specifications, where I push for clear documentation of AI model behaviors and decision-making processes in radio resource management.

**Integrity** means I cannot compromise on technical truth, even when business pressures suggest otherwise. When evaluating AI-RAN solutions, I insist on honest performance benchmarks rather than cherry-picked metrics that favor specific vendors. This sometimes creates tension with sales teams and vendor partners, but I believe our operators and ultimately end-users deserve accurate information about what these systems can and cannot do.

**Social responsibility** compels me to consider the broader impact of the technologies I build. As we develop 6G systems with AI at their core, I am acutely aware that these networks will become critical infrastructure affecting billions of people. This value drives me to question not just whether we *can* implement a feature, but whether we *should* - considering energy consumption, digital divide implications, and potential for misuse. I advocate strongly for upstream open source projects where diverse stakeholders can participate, audit, and improve the code, ensuring that critical telecommunications infrastructure serves the public interest rather than remaining locked behind proprietary walls accessible only to well-funded corporations.

## Example: Conflict Between Values and Business Pressure

Last year, I encountered a significant ethical dilemma while working on an AI-powered network slicing solution for 5G-Advanced that would later inform our 6G strategy. Our company was partnering with a major chip vendor to develop AI models that would dynamically allocate network resources based on user profiles and predicted traffic patterns. The vendor proposed implementing behavioral prediction algorithms that would analyze individual user patterns - including location history, application usage, and temporal behaviors - to optimize network performance.

While the technical performance was impressive (reducing latency by 23% and improving throughput by 31% in trials), the solution deeply conflicted with my values of **transparency** and **social responsibility**. The AI models operated as black boxes, and users would have no visibility into how their data was being analyzed or how network resources were being allocated based on their predicted behaviors. Furthermore, the system could potentially enable differential service quality based on profiling, creating a technological infrastructure for discriminatory practices.

This situation created internal conflict because:
- **Professionally**, the solution represented cutting-edge AI-RAN technology that would position our company competitively
- **Personally**, it violated my core values around user privacy, algorithmic transparency, and equitable access to infrastructure
- **Organizationally**, there was significant pressure from leadership to move forward quickly to meet market windows

## Resolution and Actions Taken

I chose to address this dilemma through a multi-pronged approach informed by my values:

1. **Technical Alternative**: I worked with a small team to develop a privacy-preserving alternative using federated learning and differential privacy techniques. This approach maintained much of the performance benefit (19% latency reduction, 27% throughput improvement) while keeping user data localized and adding mathematical privacy guarantees.

2. **Documentation and Advocacy**: I prepared a detailed technical memo outlining the privacy risks, potential regulatory conflicts (particularly with GDPR and emerging AI regulations), and long-term reputational risks. I presented this to both technical leadership and our legal/compliance team.

3. **Standards Engagement**: I brought concerns about user profiling in AI-RAN to the O-RAN Alliance working groups, advocating for privacy requirements in future specifications.

## How My Actions Were Received

Initially, my concerns were met with resistance from program management, who viewed the privacy-preserving approach as unnecessary complexity that would delay deployment. However, the reception changed significantly when:

- Our legal team confirmed that the original approach would face serious regulatory challenges in European markets
- A competitor faced public backlash for a similar profiling-based network optimization system
- The technical alternative I proposed actually reduced vendor lock-in by not requiring proprietary user analytics infrastructure

Ultimately, my manager and the VP of Engineering supported the privacy-preserving approach. The VP specifically noted that "sometimes the engineer in the room has to be the conscience of the project." While the project timeline extended by two months, we deployed a solution aligned with both our values and emerging regulatory frameworks.

This experience reinforced my belief that core values aren't obstacles to technical excellence - they're essential guides that help us build sustainable, responsible technology. In AI-driven telecommunications infrastructure, where our architectural decisions will impact billions of users for decades, allowing our values to inform our technical choices isn't just ethical; it's professionally responsible.

---

## References

Personal Core Values. (2023, August 16). *Markkula Center for Applied Ethics* [Video]. YouTube. https://www.youtube.com/watch?v=bFSwpGWtjYI

Markkula Center for Applied Ethics. (n.d.). *Core values inventory*. Santa Clara University.
