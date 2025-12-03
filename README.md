# Final Project
Bare repo for you to begin your final project
 
## Installation and Running

1. **Clone the repository:**
   ```bash
   git clone https://github.com/neilllatham/final-project-neilllatham.git
   cd final-project-neilllatham/nestey-marketing-site
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```

4. **Open in browser:**
   - Navigate to `http://localhost:4321` (or whichever port is displayed in the terminal)

5. **Build for production:**
   ```bash
   npm run build
   ```

**Live site:** https://nestey.co (or https://tangerine-basbousa-ef5995.netlify.app)

## How requirements are met
Meets all structural requirements — includes multiple pages, a clear navigation bar, consistent header/footer, and a complete site architecture.

Uses proper semantic HTML — correct use of headings, sections, nav, article, figure components, and accessible markup.

Implements a reusable layout system — shared header, footer, global styles, and Astro layouts ensure consistency across every page.

Demonstrates strong CSS layout skills — responsive grid/flexbox, spacing, typography, and brand colors fully implemented.

Includes a compelling homepage hero section — clear messaging, strong visuals, and CTAs aligned to project requirements.

Uses multimedia appropriately — optimized images, SVGs, and branded bird-formation graphics with meaningful alt text.

Adds interactivity where required — navigation links, hover states, and UI behaviors implemented with clean JavaScript.

Organized file structure — assets, pages, CSS, components, and /public/data JSON kept clean and modular.

Fully responsive — site adapts gracefully to desktop, tablet, and mobile breakpoints per CS-12 expectations.

Accessible design — heading hierarchy, color contrast, alt text, and keyboard-friendly navigation are implemented.

Incorporates Ollama for natural language AI interactions — the marketing site includes an AI prompt interface powered by a local Ollama model, demonstrating modern conversational capabilities.

Uses JavaScript business logic to integrate AI functionality — client-side JS collects user prompts, sends them to Ollama, and returns generated responses, creating a realistic conversational demo.

Uses a JSON data file as a realtime data source — /public/data/demo.json feeds live HR-like employee data into the AI demo, enabling context-aware responses that reflect real system behavior.

## 5-Planes approach
The Nestey marketing site meets the Five-Plane approach by grounding its strategy in a clear brand vision, defining a focused feature scope, building a logical content structure, using consistent page layouts, and delivering a polished, modern surface design. The site goes beyond a traditional static project by incorporating an interactive AI demo powered by Ollama, JavaScript business logic, and JSON-based realtime data, showcasing a next-generation HR experience and demonstrating advanced technical execution for my CS-12 final

### Strategy
The strategy for the Nestey marketing site is to clearly communicate the value of Nestey as a next-generation, AI-powered HR experience. The site’s purpose is to introduce the brand, tell the Nestey story, explain the product in simple language, and demonstrate how conversational AI can change the way employees interact with HR information.
Key strategy elements include:

Position Nestey as modern, simple, and emotionally approachable.

Differentiate from complex, outdated HR systems like Workday.

Highlight AI and natural-language interaction as a core innovation.

Build trust with clear messaging, brand story, and consistent visual identity.

Provide clear exploration paths for prospective users: features, goals, benefits, AI, about, and contact.

### Scope
The scope defines exactly what is in the marketing site. Content and functionality are intentionally scoped to demonstrate my design, technical skill, and AI integration.
The Nestey site includes:

Multi-page structure: Home, Product Features, Goals, Benefits, AI, About, Contact.

Conversational AI demo powered by Ollama as part of the AI page.

JSON-driven HR demo data (demo.json) to simulate real employee info.

JavaScript logic to communicate with the Ollama model and provide dynamic responses.

Static content describing features like goal setting, time off, benefits, and org chart.

Brand story explaining the meaning of the "Nest" and teamwork theme.
Out of scope: real authentication, real database, full application functionality (reserved for the full-stack Nestey build).

### Structure
The structure defines how users move through the site and how information is organized.
For Nestey:

A top navigation bar offers clear, consistent access to all major pages.

The homepage introduces value quickly with strong hero messaging and supporting visuals.

Each product feature page flows top-to-bottom with clear sections and calls to action.

The AI page structures the conversational demo at the center, surrounded by explanation panels.

The About page uses narrative structure: Who we are → What Nestey represents → Why it matters.

Information is organized hierarchically for readability and easy scanning.

JSON data and JavaScript interact behind the scenes but don't interrupt user flow.

### Skeleton
The skeleton defines layout, wireframes, and the placement of elements. Nestey’s skeleton includes:

Repeatable header and footer for consistent navigation.

Hero section featuring main tagline, subtext, and call-to-action.

Visual hierarchy using spacing, headings, and sections.

Grid- and flex-based layouts for responsive content flow.

Placement of images (birds-in-formation, branded visuals) to guide the user’s eye.

AI UI consists of text input, prompt container, and response display area.

JSON-fed example data is referenced in the AI experience but not exposed as clutter.

Layout components (like page wrappers) ensure visual consistency across all pages.

### Surface
The surface plane is the polished visual design that users see. For Nestey:

Clean, modern, HR-tech aesthetic.

Brand-consistent visual theme inspired by birds flying in formation—representing unity, alignment, and shared goals.

Refined typography, color palette, and spacing choices to match contemporary SaaS marketing design.

Imagery that blends professionalism with warmth—simple, airy, and welcoming.

Iconography and graphics that reinforce ease-of-use and clarity.

AI interface styled to look conversational, intuitive, and emotionally approachable.

Responsive visual behavior ensuring every page looks good on phone, tablet, and desktop.