# AI-Powered Resume Generator

Transform your markdown resume into professional LaTeX format using AI editors like Cursor or Claude Code. No more manual copy-paste or LaTeX syntax learning required!

## How It Works

1. **Write in Markdown** - Create your resume content in simple markdown format
2. **AI Crafting** - Use [NotebookLM](https://notebooklm.google.com/) to craft customized resume content
3. **AI Transformation** - Use AI editors (Cursor, Claude Code) to convert to LaTeX format
4. **PDF Generation** - Paste into [Overleaf](https://www.overleaf.com/) and download PDF

## Quick Start

1. **Clone Repository**
   ```bash
   git clone https://github.com/CreateWithLevi/resume.git
   ```

2. **Craft Content with NotebookLM**
   - Upload your experience/projects to [NotebookLM](https://notebooklm.google.com/)
   - Generate tailored resume content for specific roles

3. **Convert with AI Editor**
   - Open in AI editor (Cursor/Claude Code)
   - Ask: "Convert my markdown resume to the LaTeX template in source.tex"

4. **Generate PDF**
   - Copy the LaTeX output
   - Paste into [Overleaf](https://www.overleaf.com/)
   - Download your professional PDF

### Preview

> Switch themes by commenting and un-commenting the sections documented in the code

|            Light theme             |            Dark theme            |
| :--------------------------------: | :------------------------------: |
| ![Light theme](/light_preview.jpg) | ![Dark theme](/dark_preview.jpg) |

## Motivation

I created this template as a way of improving my modification system with Version Control and to have a single source of truth when making changes on it. Also added a version of the pdf in dark theme, so it might be useful for the people reading to select which theme to see. And finally i tried to use simple tips and recommendations from Google to ensure some quality of the structure and sections.

## Guidelines

A single-page, one-column resume for software developers (data scientist use case in my case). The different sections are clearly documented and custom commands are used to provide consistent formatting. The three main sections in the resume are education, experience, projects, certifications and personal publications.

### Tips and advice (from the video)

#### General

**Format:**

- Use simple and consistent design, font, sizing and spacing.
- Use black or dark, readable ink.
- Format as PDF.

**Content:**

- Include your contact information and email at the top.
- Don't have to include objective statements.
- Don't need to include references.

**Length:**

- Keep to one page for business and internship roles, and no longer than two pages for engineering and technical roles.
- Include what's relevant for the specific role.
- Use bullet points with consistent formatting and structure rather than long paragraphs.
- Check for typos.

**For technical and engineering candidates:**

- List programming languages at the top.
- List your Github profile or other prominent open source work.

**Section order for Student or recent graduate:**

- Education.
- Experience.
- Leadership and awards.
- Optional final section.

**Section order for Experienced industry professional**

- Experience.
- Leadership and awards.
- Education.

#### Education

- Include all post-secondary institutions you've attended, and all degrees and majors.
- Be sure your most recent education is listed first.
- Include your actual graduation date in the month-year format (for example May 2017 not Spring 2017).

**For current students and recent grads:**

- Include your anticipated graduation date in the month-year format.
- Include your cumulative grade point average.

#### Experience

- List everything in reverse chronological order with your most recent experience first.
- Include your employer, position, and dates employed for all jobs and internships in the month-year format.
- Bullet point descriptions should be concise and clear.
- Streamline bullet points that spill over onto the next line by only 1-2 words.
- Use action words like created, designated, debugged, negotiated, developed, managed, etc.
- List metrics and examples.
- Use data and comparisons or average to provide context.

**For technical and engineering candidates:**

- Include the programming language you used in bold for each project you include.

> **Framework for impact based descriptions**: Accomplished [X] as measured by [Y] by doing [Z].

**Example for technical and engineering candidates:**

- Increased server query response time by 15% by restructuring API.

**Example for business candidates:**

- Grew revenue from 15 small and medium business clients by 10% QoQ by mapping new software features as solutions to their business goals.

#### Leadership and awards

Also use the **Framework for impact based descriptions**. Examples:

- Selected as one of 230 participants nationwide for an 18-month professional development program for high-achieving Black and LatinX talent in tech based on leadership potential and academic success.

#### Optional final section

Also use the **Framework for impact based descriptions**.

- Include involvement in student groups especially if you have leadership position.

Some ideas:

- Publications.
- Papers.
- Patents.
- Conference presentations.
- Any other meaningful extracurricular activities or experiences.

## License

Format is MIT but all the resume data is owned by Levi Huang.

## Acknowledgments

- To [@sb2nov](https://github.com/sb2nov/) for the initial code!
- And to others contributors listed [here](https://github.com/sb2nov/resume/graphs/contributors)
