# The Summer 2026 Registration Page
Review and remediate any accessibility issues with this page

## Project Background

The review of the Summer 2026 Registration webpage began after the page's web support specialist raised a question in a team group chat about instructions directing visitors to rotate their devices to landscape orientation.

That discussion prompted a subsequent accessibility audit. While the initial concerns involved device orientation and extensive course tables contained within Bootstrap accordions, my review identified additional issues involving cognitive load, information hierarchy, and the presentation of potentially outdated course information.

I documented the accessibility and usability rationale for the recommended changes and shared it with web leadership to support communication with the page's maintainers.
### The Challenge

The original Summer 2026 Registration webpage presented students with a large volume of information, including an extensive collection of course tables organized within expandable sections. These tables created significant navigation and cognitive demands while potentially suggesting that listed courses remained available for registration.

The page also advised visitors to use landscape orientation to view the course listings, while the link directing students to current course availability was visually understated.

The challenge was not simply to correct individual accessibility concerns, but to reconsider how the page presented information so students could more easily identify registration steps and locate reliable, up-to-date course information.

## Accessibility and Usability Issues Identified

The original Summer 2026 Registration webpage presented several interconnected accessibility, usability, and information-management concerns.

### 1. Excessive Cognitive Load

The page required students to process a substantial amount of information before locating the resources needed to register.

Multiple registration pathways, resource buttons, a graphical session timeline, and extensive course listings competed for attention.

This increased the effort required to identify relevant information, particularly for students with cognitive or learning disabilities, attention-related difficulties, or limited familiarity with university registration processes.

### 2. Primary Call to Action Lacked Prominence

The primary purpose of the page was to help students find available summer courses and register.

However, the link directing students to the authoritative course-search system appeared as a small line of text beneath the graphical session timeline.

Its placement and visual treatment made it easy to overlook, despite being one of the most important resources on the page.

The redesign prioritized this action by introducing a clearly labeled, visually prominent registration button.

### 3. Essential Session Information Presented as an Image

The original page used a Gantt-style graphical timeline to communicate summer session dates and durations.

The graphic served as the primary presentation of this information, creating potential barriers for students who could not perceive or interpret the image.

The timeline was replaced with a text-based list of summer sessions and their corresponding dates, reducing dependence on visual interpretation and making the information easier to access and understand.

### 4. Extensive Data Tables Inside Expandable Sections

The page contained four Bootstrap accordion sections organized by college, each containing extensive course tables.

A PDF capture showing just one expanded college section occupied nine pages, illustrating the substantial volume of information contained within a single accordion.

This structure introduced several concerns:

- Students had to expand sections and navigate lengthy tables to review course information.
- Large tables presented challenges for smaller screens and potentially for keyboard and assistive-technology navigation.
- The page instructed visitors to rotate their devices to landscape orientation for optimal viewing, indicating that the presentation was not well suited to portrait layouts.
- The volume of information made it difficult to identify the next step in the registration process.

The redesign removed these extensive tables and replaced the presentation with a streamlined CMS component containing essential session information and a direct registration action.

### 5. Potentially Misleading Course Availability Information

The static course tables could give students the impression that all listed courses were currently available for registration.

However, course availability can change as sections fill, schedules are adjusted, or courses are canceled.

The authoritative course-search system provides the current information students need to make registration decisions.

Removing the static tables reduced the risk of presenting outdated information as actionable and directed students to the appropriate source.

### 6. Visual Consistency and Information Hierarchy

The original layout contained several competing visual treatments, including pale registration-pathway boxes, dark blue buttons, a graphical timeline, and extensive tabular content.

The redesign adjusted the registration boxes to coordinate more closely with the existing button styles and established a clearer hierarchy between introductory information, session dates, and the primary registration action.

## Rationale for the Redesign

The objective was not simply to make the existing content fit within accessibility guidelines. It was to ensure that the page supported its intended purpose.

By removing unnecessary complexity, replacing image-based information with text, and prioritizing the authoritative registration resource, the redesign aimed to reduce barriers while making the page more understandable and actionable for students.

## My Role and Approach

I was responsible for reviewing the Summer 2026 Registration webpage, identifying accessibility and usability barriers, and implementing improvements within the university's content management system (OmniCMS).

My approach focused on the primary purpose of the page: helping students understand summer registration options and locate current course information.

During my review, I identified issues beyond the original concerns about device orientation and extensive course tables. These included excessive cognitive load, an image-based session timeline, a lack of prominence for the primary registration link, and the potential for static course listings to misrepresent current availability.

I used AI-assisted research to help organize the relevant accessibility considerations and develop a professional rationale for the recommended changes. I shared that rationale with web leadership to support discussions with the page's maintainers.

I then implemented the following improvements:

- Removed four extensive course-table sections contained within Bootstrap accordions.
- Replaced the graphical summer-session timeline with text-based session dates.
- Used a single OmniCMS radial component to organize essential session information.
- Added a prominent registration button linking directly to the authoritative course-search system.
- Updated the registration-pathway boxes to create a more consistent visual presentation.

These changes shifted the page's focus from displaying large quantities of static course information to helping students find the information and registration resources they actually needed.

## Results and Lessons Learned

The redesigned Summer 2026 Registration webpage presents a more focused path to registration by removing unnecessary complexity and prioritizing essential information.

### Results

- **Simplified navigation:** Removed four extensive course-table accordions, reducing the amount of information students must navigate.
- **Improved access to registration:** Replaced a visually understated course-search link with a prominent call-to-action button directing students to the authoritative registration resource.
- **More accessible session information:** Replaced the graphical session timeline with text-based dates and session descriptions.
- **Reduced dependence on static information:** Eliminated lengthy course listings that could become outdated as registration availability changed.
- **Clearer visual hierarchy:** Consolidated essential information within a single OmniCMS radial component and updated the registration-pathway boxes for a more coordinated appearance.
- **Documented decision-making:** Provided web leadership with an accessibility and usability rationale to support communication with the page's maintainers.

### Lessons Learned

This project reinforced the importance of evaluating accessibility in the context of a webpage's overall purpose rather than treating it solely as a checklist of technical requirements.

Although the initial review focused on device orientation and tables within expandable sections, examining the complete student experience revealed opportunities to improve information architecture, content accuracy, and navigation.

The most effective solution was not to preserve every existing element while attempting to make it accessible. It was to determine which information students actually needed on the page and direct them to the appropriate source for current course availability.

The project also demonstrated the value of documenting accessibility recommendations so that substantial design and content changes can be clearly explained to stakeholders.


**Examples**
[Summer 2026 Before Remediation](summer-2026-registration-before.pdf)

[Summer 2026 After Remediation](summer-2026-registration-after.pdf). 
