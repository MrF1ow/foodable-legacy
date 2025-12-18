# Foodable

Foodable is a food-focused application aimed at reducing friction in healthy, budget-conscious meal planning by connecting recipes, groceries, pricing, and delivery into a single workflow.

This repository currently contains **one of two implementations** of Foodable:

- **Foodable — Remastered** (active development)
- **Foodable — Legacy** (original production prototype)

Both are intentionally preserved.

## 🚧 Foodable — Remastered (In Development)

**Status:** Active rebuild  
**Focus:** Performance, correctness, maintainability, long-term scalability

Foodable is currently being **rebuilt from the ground up** with a backend-first architecture and a tighter scope. The remaster exists to correct architectural complexity and operational overhead that accumulated in the original implementation.

### Key Characteristics
- Backend-first design
- Strong relational data modeling
- Reduced dependency and runtime complexity
- Designed for future mobile and multi-client support

**Note**: The current repository is private. If you’re interested in contributing to the remastered version of Foodable, please reach out via email at ethanflowdev@gmail.com

## 🧪 Foodable — Legacy (Original Implementation)

**Status:** Feature-complete prototype  
**Focus:** AI-assisted food discovery and experimentation

The legacy version represents the **original full-stack implementation**, including AI-driven recommendations, vector search, and a richer—but heavier—tooling stack. It remains in the repository for reference, learning, and historical context.

### Key Characteristics
- AI-powered recommendations
- Vector search with embeddings
- Rich frontend experimentation
- Production deployment experience

### Tech Stack
- **Frontend:** Next.js + Tailwind CSS  
- **Backend:** Node.js  
- **Database:** MongoDB Atlas (Vector Search)  
- **Auth:** Clerk.js  
- **State Management**: Zustand + Tanstack Query
- **AI Model**: OpenAI

### Running Application
This application relies on multiple external services, which is one of the primary reasons it is being rebuilt. If you would like to run the application locally, please contact ethanflowdev@gmail.com for setup details.

## Why the Rewrite Exists

The legacy system worked—but it was **too complex for what the product actually needs**.

The remaster prioritizes:
- Predictable performance
- Simpler mental models
- Fewer moving parts
- Easier long-term ownership

This is not a pivot away from ambition; it’s a correction toward **sustainability**.

## License & Contributions

This project is under active development. Contribution guidelines will be formalized once the remastered API stabilizes.
