# Day 3 – Role-Based Prompting

## What is Role-Based Prompting?

Role-Based Prompting is a prompt engineering technique where we assign a specific role or persona to an AI before asking a question.

Examples:

* Founder
* Software Engineer
* Product Manager
* HR Manager
* Marketer

The AI then responds from the perspective of that role, providing more focused and specialized answers.

---

## Why Role-Based Prompting Matters

Without a role, AI usually provides general answers.

With a role, AI adapts its thinking, priorities, and expertise to match the assigned persona, producing more relevant and actionable insights.

---

## Experiment

### 1. Without Role Prompt

#### Prompt

How can I make Varnam Neithal, a digital platform for handloom weavers, successful in rural Tamil Nadu?

#### Output Summary

* Solve weavers' real pain points.
* Provide Tamil-first design.
* Build trust through SHGs and cooperatives.
* Support low-bandwidth and offline usage.
* Offer fair pricing and faster payments.
* Improve logistics and government partnerships.

#### Observation

The response was broad and covered multiple aspects such as operations, trust, technology, logistics, and community building.

---

### 2. Founder Persona

#### Prompt

You are a startup founder who has successfully built multiple rural technology startups.

How can I make Varnam Neithal, a digital platform for handloom weavers, successful in rural Tamil Nadu?

Focus on:

* Business model
* Revenue generation
* Scaling strategy
* Investor attraction

#### Output Summary

* Create a marketplace + SaaS hybrid business model.
* Generate revenue through commissions, subscriptions, and B2B sales.
* Focus on corporate gifting opportunities.
* Scale cluster-by-cluster.
* Build proprietary designs and certifications.
* Use impact metrics to attract investors.

#### Observation

The Founder persona focused on business growth, revenue generation, customer acquisition, scaling, and investor readiness.

---

### 3. Developer Persona

#### Prompt

You are a senior software engineer experienced in building rural digital platforms.

How can I make Varnam Neithal, a digital platform for handloom weavers, successful in rural Tamil Nadu?

Focus on:

* Technical architecture
* Offline functionality
* Mobile accessibility
* Security

#### Output Summary

* Build an offline-first platform.
* Use Progressive Web Apps (PWA).
* Support Tamil language throughout the application.
* Optimize for low-end Android devices.
* Implement secure OTP-based authentication.
* Protect payment and user data using encryption.
* Integrate WhatsApp for easier adoption.

#### Observation

The Developer persona focused on technical implementation, offline synchronization, accessibility, security, and system architecture.

---

## Biggest Observation

The same question produced completely different answers depending on the assigned role.

Without a role:

* General recommendations.

Founder role:

* Focused on revenue, scaling, business growth, and investment.

Developer role:

* Focused on architecture, offline support, mobile usability, and security.

This demonstrated how Role-Based Prompting can generate expert-level insights from different professional perspectives.

---

## Key Learnings

1. Role-Based Prompting improves the quality of AI responses.
2. Different roles provide different viewpoints for the same problem.
3. It helps in decision-making by allowing multiple expert perspectives.
4. It is useful for startup planning, software development, marketing, and product design.
5. AI becomes more specialized and actionable when given a clear role.

---

## Claude Usage Counter

Installed and explored the Claude Usage Counter Chrome Extension.

### Screenshot

<img width="1254" height="1254" alt="ChatGPT Image Jun 3, 2026, 10_28_40 PM" src="https://github.com/user-attachments/assets/3d1a109d-e10f-4c03-9b62-9fbfb4b0fbb5" />

---

## Conclusion

Role-Based Prompting is one of the most effective prompt engineering techniques. By assigning a role, AI can generate focused, expert-level responses that are more relevant and useful than generic answers.
