# Degrees and Majors Directory Redesign

**Project Focus:** Accessibility, usability, information architecture, semantic HTML, and content maintainability

## Project Background

The University of Houston-Downtown's Degrees and Majors webpage serves as a directory of undergraduate and graduate programs offered across the university's four colleges.

The original page used a three-column grid of image-based cards to display degree programs. Each card included a program title and an expandable section containing additional information, such as program descriptions, courses, career options, and links.

After identifying usability concerns with this approach, I reviewed how other nearby universities, including the University of Houston, organized their degree directories.

I raised my concerns during a team meeting and was subsequently assigned to redesign the page.

## The Challenge

The original design presented a large number of degree programs through individual image cards with expandable information panels.

Although visually elaborate, this approach complicated what should have been a straightforward navigation task: helping prospective and current students locate an academic program.

The page also duplicated substantial program information that could be accessed through dedicated degree pages.

The challenge was to simplify the directory, reduce unnecessary interaction, and make degree programs easier to locate without sacrificing essential information.

## Accessibility and Usability Issues Identified

### 1. Unnecessary Interaction Barriers

The original page used expandable cards to present program information.

Visitors were required to interact with individual cards to access additional details and navigation options, introducing extra steps into a task that primarily involved finding and selecting a degree program.

The redesign replaced these expandable interfaces with directly visible text links.

### 2. Excessive Visual Complexity and Cognitive Load

Dozens of program photographs appeared throughout the page, arranged in repeating three-column grids.

While the images provided visual decoration, many did not convey information necessary to distinguish one degree program from another.

The combination of images, program labels, dropdown indicators, and expandable content increased visual complexity and the effort required to scan the directory.

Removing the image-card interface allowed program names to become the primary focus.

### 3. Information Hierarchy and Discoverability

The original layout emphasized individual cards rather than the relationships between programs.

Students seeking a particular degree had to scan a large collection of similarly formatted cards, with relatively small program labels beneath the images.

The redesign organized programs by college and credential category, using headings and bulleted lists to establish a clearer structure.

### Content Duplication and Audience Relevance

The original directory attempted to reproduce much of the information already available on individual degree program pages, including program descriptions, sample courses, career opportunities, and Classification of Instructional Programs (CIP) codes.

This approach increased the volume of content visitors had to navigate before reaching the dedicated program pages.

It also introduced unnecessary duplication, potentially increasing the effort required to keep program information accurate and consistent across multiple locations.

Some information, such as CIP codes, served administrative purposes but offered limited immediate value to prospective students using the directory to explore academic options.

The redesign established a clearer distinction between the directory and the individual degree pages: the directory helps visitors locate programs, while the degree pages provide detailed information about those programs.

### 5. Navigation and Accessibility Considerations

The original expandable-card design introduced additional interactive controls that were not necessary for the directory's primary function.

Although the visual evidence alone does not establish specific WCAG violations, the design raised questions about keyboard navigation, focus management, and the accessibility of expandable content.

Replacing the cards with native HTML headings, unordered lists, and hyperlinks reduced reliance on custom interactive behavior and provided a more straightforward semantic structure.

## My Role and Approach

I initiated the discussion about redesigning the Degrees and Majors directory after identifying concerns with its usability and information presentation.

Before proposing an alternative, I reviewed degree directories at other universities, including the University of Houston, to evaluate simpler approaches to organizing academic programs.

Following the team discussion, I was assigned to implement the redesign.

Rather than replacing the existing cards with another complex component, I used standard HTML elements within OmniCMS:

- **Headings** to identify colleges and degree categories.
- **Unordered lists (`<ul>`)** to group related academic programs.
- **Descriptive hyperlinks** to direct visitors to individual degree pages.

The redesign removed the image-card grid and expandable information panels, allowing users to browse programs without additional interaction.

I also organized the directory by college and credential type, including undergraduate degrees, graduate programs, and certificates where applicable.

## Results

The redesigned page provides a simpler, text-based directory that prioritizes access to academic programs.

Key improvements include:

- **Direct access to programs:** Degree links are visible without expanding individual cards.
- **Reduced visual clutter:** Removed dozens of program images that were not essential to the directory's purpose.
- **Clearer organization:** Grouped programs under college and credential headings.
- **Simplified interaction:** Replaced expandable cards with conventional hyperlinks.
- **Semantic HTML:** Used native headings, lists, and links rather than a custom interactive interface.
- **Reduced content duplication:** Moved the directory's emphasis away from detailed program descriptions and toward dedicated degree pages.
- **Simpler maintenance:** Program listings can be updated without maintaining associated images and expandable content.

These are design and implementation improvements; no formal user-testing results or measured accessibility outcomes are claimed.

## Lessons Learned

This project reinforced that accessibility and usability improvements do not always require complex technical solutions.

The original design offered extensive visual presentation and interactive features, but those elements did not necessarily support the primary purpose of the page.

By focusing on what visitors needed to accomplish, I was able to replace a complicated interface with a simpler, more predictable structure.

The project also demonstrated the value of independently identifying usability concerns, researching alternative approaches, and communicating recommendations before implementing a redesign.

Ultimately, the most appropriate solution was not a more sophisticated component. It was a clearer information hierarchy supported by native HTML.

## Before and After Documentation

The following PDF captures document the original directory and redesigned webpage.

- Before: Original Degrees and Majors Directory
- After: Redesigned Degrees and Majors Directory

*These PDFs serve as visual documentation of the webpage changes, not as examples of PDF accessibility remediation.*


