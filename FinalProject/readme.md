What's something new you learned while building your site?
The biggest thing I learned was how CSS Grid and Flexbox work together rather than being interchangeable. I used Grid for the tile layout on the homepage and Flexbox for the blog preview card on the work page, and understanding when to use each one made my layouts feel a lot more intentional. I also learned how to use Bootstrap's navbar in a way that actually fits a custom design rather than looking like a default Bootstrap site.
How did you balance creativity with usability?
I tried to let the project itself guide the design decisions. Since I Meant to Tell You is a quiet, handwritten, tactile concept, I kept the site warm and understated rather than loud or decorative. Every interactive element like the tile hover effects and the contact form animation serves a purpose, either guiding the user or giving them feedback, rather than just being there to look interesting.
What are you most proud of in your final project?
I'm most proud of how cohesive the site ended up feeling. The color palette, typography, image choices, and layout all feel like they belong to the same thing, which I think is the hardest part of design to get right. The homepage tile grid especially came together in a way that feels polished and intentional.
How do you see yourself using these skills later on?
I can see myself using these skills to build out a real portfolio site as I continue developing work after this class. Understanding how to structure a site, style it consistently, and make it responsive is genuinely useful for anyone working in a creative field, and I feel like I have a real foundation now rather than just a surface-level understanding.

# Site Plan

## Home Page

**Goal:** Introduce the portfolio and guide users to all key sections of the site.

### Structure
- **Navigation:** Brand name (left), page links (right) — Bootstrap responsive navbar
- **Hero:** Short heading and tagline centered above the grid
- **Main Content:** 2x2 CSS Grid tile layout linking to Work, Gallery, About, and Contact — each tile uses a full-bleed image with gradient overlay and buttons
- **Supporting Content:** "At a Glance" info cards summarizing focus, current project, program, and contact
- **Footer:** Brand name and tagline (left), page links (center)

---

## Work Page (flexbox.html)

**Goal:** Showcase featured projects and encourage users to explore the full gallery.

### Structure
- **Navigation:** Consistent Bootstrap navbar
- **Hero / Intro:** Page title and subtitle centered
- **Main Content:** Blog preview card using Flexbox — project image (left), title, date, description, and link (right)
- **Call-to-Action:** "View Project" link directing to the Gallery page
- **Footer:** Consistent site footer

---

## Gallery Page (grid.html)

**Goal:** Present the I Meant to Tell You project in full detail with visual and written content.

### Structure
- **Navigation:** Consistent Bootstrap navbar
- **Hero / Intro:** Project title and description
- **Supporting Content:** Project meta bar — type, medium, year, and creator
- **Main Content:** Two CSS Grid image galleries separated by written sections covering the concept, how it works, and the installation
- **Call-to-Action:** Back link to Work page
- **Footer:** Consistent site footer

---

## About Page (blog-post.html)

**Goal:** Share background on the designer and her creative focus.

### Structure
- **Navigation:** Consistent Bootstrap navbar
- **Hero / Intro:** Parallax banner image with text overlay
- **Main Content:** Long-form text sections covering graphic design focus, creative concepts, future goals, and portfolio intentions
- **Call-to-Action:** Back link to Work page
- **Footer:** Consistent site footer

---

## Contact Page (contact.html)

**Goal:** Give visitors a way to reach out and connect.

### Structure
- **Navigation:** Consistent Bootstrap navbar
- **Hero / Intro:** Page heading and short welcoming paragraph
- **Main Content:** Three contact info cards — email, LinkedIn, Instagram
- **Supporting Content:** Contact form with name, email, and message fields and a pulsing send button
- **Call-to-Action:** Send Message button
- **Footer:** Consistent site footer