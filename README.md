

# Vision
In an Agile way, develop a robust web application that will serve as the CodeKenya website, while decomposing the development process into a commercializable syllabus.

## Principles of Agile

### Define User Stories with Acceptance Criteria
- **What to do:** Break down features into user stories with clear acceptance criteria to ensure each functionality meets the intended purpose.
- **Example:** A user story might be, "As a prospective student, I want to view a list of available programs so that I can select one that aligns with my goals." The acceptance criteria could specify that the list should load within 2 seconds, display program details, and have a filter by location.

### Prioritize Features in the Product Backlog
- **What to do:** Order features in the backlog based on user value and project goals, ensuring the most critical features are developed first.
- **Example:** Prioritize the homepage and program listing pages before building additional features like blogs or student portals to ensure users get the essential content.

### Iterate in Sprints
- **What to do:** Break down the project into sprints (usually 1-4 weeks), each focused on completing a set of user stories.
- **Example:** In the first sprint, focus on building a basic version of the homepage and program page, then collect feedback to enhance it in the next sprint.

### Daily Standups
- **What to do:** Hold daily meetings with the team to discuss progress, blockers, and planned work for the day.
- **Example:** During a standup, a developer might mention they’re waiting on a design for the "About Us" page, allowing the designer to prioritize it.

### Regular Feedback Loops with Stakeholders
- **What to do:** Involve stakeholders in sprint reviews or demos to gather feedback and make adjustments.
- **Example:** After a sprint, showcase the program listing page to stakeholders, gather feedback on the layout and information presented, and incorporate suggested changes in the next sprint.

### Continuous Testing and Integration
- **What to do:** Regularly test features as they’re developed, catching bugs early through automated testing and CI/CD pipelines.
- **Example:** Implement tests for each user story, such as verifying that the application form correctly saves user inputs and flags invalid entries.

### Retrospectives for Continuous Improvement
- **What to do:** Hold retrospectives at the end of each sprint to discuss what went well, what could improve, and what changes to make.
- **Example:** After the first sprint, the team realizes that unclear user story details led to rework, so they decide to include acceptance criteria reviews in sprint planning.

### Allow for Scope Changes and Reprioritization
- **What to do:** Be open to changing the backlog priorities as user feedback and market insights emerge.
- **Example:** After gathering feedback, the team learns that users want more details on internship opportunities, so they prioritize building an internship page earlier than planned.

### Deliver Incremental Releases
- **What to do:** Release usable parts of the application incrementally to gain real user feedback early and often.
- **Example:** Release the core pages—home, programs, and admissions—while still developing secondary features like the blog or contact pages, allowing prospective students to browse the primary content right away.

### Documentation of Agile Processes and Decisions
- **What to do:** Maintain lightweight, regularly updated documentation on the project’s goals, user stories, sprint progress, and decisions.
- **Example:** Document each sprint’s objectives, completed user stories, and any adjustments to the backlog, helping team members understand the project’s evolving direction without lengthy documentation.

---

### Weekly Meeting Agenda
1. Our weekly standup.
2. Hold retrospectives.
3. Plan the next sprint.

## Roles
- **Raydon Muregi** - Writer, Scrum Master, QA & Developer
- **Gabriel Okemwa** - Product Owner & Developer
- **Francis Eyanae** - Writer, Tester & Developer
- **Lewis Kanyi** - UX/UI & Developer

---

## Product Backlog

### Frontend

**Home Page:**
- Hero section with a compelling headline and call-to-action.
- Overview of our programs and offerings (SWE, Cybersecurity).
- Testimonials or success stories section from past participants.

**Programs:**
- Detailed descriptions of available programs (e.g., Management Consulting, Data Science, Investment Banking, Digital Marketing).
- Curriculum outlines and learning outcomes.
- Information on instructors and their backgrounds.

**Navbar:**
- Dropdown with Bootcamp offerings, Locations (Nairobi), Internship, and About.
- Apply pipeline with simulated forms with simple essay questions until successful application.
- Display name: CodeKenya.

**Locations:**
- Information about study locations (e.g., Nairobi, Online) with stock images for the initial design.
- Details on application status, session dates, accommodation, local attractions, and cultural experiences.

**Internships:**
- Overview of internship opportunities and partner companies (templates).
- Success stories section (e.g., Raydon’s story).

**About Us:**
- Company mission, vision, and values.
- Leadership team profiles.
- Company history and milestones.

**Admissions:**
- Application process and requirements.
- Tuition fees and financial aid information.
- Important dates and deadlines.

**Student Life:**
- Information on extracurricular activities and events.
- Community engagement and networking opportunities.
- Alumni network and support.

**Blog/News:**
- Articles on industry trends, student experiences, and company updates.
- Success stories and case studies.

**Contact Us:**
- Chatbot with live users or AI.
- Location maps and addresses.
- “Let’s meet” option: enter email to chat with an admissions member.
- Social media links.

**User Account Management:**
- Student portal for application tracking and course materials.
- Profile management for students and instructors.
- Profile with alumni filters and recordings ready for purchase.

**Responsive Design:**
- Ensure the website is mobile-friendly and accessible across devices.

*PSA:* Always refer to [iXperience](https://www.ixperience.co/) for inspiration.

### CI/CD
- Plan a first release and release incrementally.

---

## Sprint 1 of 8
- Meet and make introductions.
- Create the repository.


# Next.js Project

This is a Next.js project bootstrapped with `create-next-app`.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses `next/font` to automatically optimize and load *Geist*, a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - Learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - An interactive Next.js tutorial.
- [Next.js GitHub Repository](https://github.com/vercel/next.js) - Your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the Vercel Platform from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
