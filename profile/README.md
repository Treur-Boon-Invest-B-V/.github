# Treur Boon Invest B.V.

Welcome to the GitHub organisation for **Treur Boon Invest B.V.**

> ⚠️ *Note: Treur Boon Invest is the parent/legal entity; its primary public-facing product is the Fondsenhuis platform. Many of the projects you’ll see in this org relate to Fondsenhuis, its infrastructure, and future expansions.*

---

## Projects & Focus

### Fondsenhuis  
**Fondsenhuis** is our flagship platform: a modern web portal connecting Dutch investors with talented domestic fund managers.

We are transitioning Fondsenhuis from a WordPress-based site to a **SvelteKit** codebase to gain:

- Full control over frontend behavior, routing, and performance  
- Better modularization of content and data  
- Stronger integration with APIs, dynamic rendering, and micro-frontend options  

This organisation hosts the repositories, infrastructure-as-code, shared libraries, and tooling that support that transition.

---


## Goals & Principles

- **Modularity & Maintainability** – Keep code organized so features, services, and teams can evolve independently  
- **Security & Compliance** – Given the financial context, guard 
  against XSS, CSRF, data leaks; apply role-based access control, proper logging, and encryption  
- **Performance & UX** – Fast load times, performant interactions, responsive and accessible design  
- **Testability & CI/CD** – Automated tests (unit, integration), continuous deployment pipelines  
- **Scalability & Observability** – Infrastructure built for growth, with logging, metrics, and error monitoring  

---

## Legal & Structural Context

- **Treur Boon Invest B.V.** is the legal/holding entity under which we operate. It is registered at **Amstel 62, Amsterdam, NL** and has LEI **984500403BD6F43DAA21**. 
- **Fondsenhuis** is the core business and public product.  
- We maintain this separation (parent vs product entity) for regulatory, licensing, and compliance reasons, allowing flexibility to host additional regulated subsidiaries in the future.

---

## Contributing & Governance

- Pull requests should follow our code style, include tests, and reference the relevant issue  
- Use labels to signal your intent (e.g. `feature`, `bug`, `refactor`)  
- Maintain transparency — link tickets, document configuration changes, and keep architecture decisions updated  
- Code reviews: at least one approval from a domain expert  

---

## Contact & Support

For questions, architectural decisions, or access permissions, reach out to the core dev team at dev@treurbooninvest.nl
