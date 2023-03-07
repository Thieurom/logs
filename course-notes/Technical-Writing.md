# Technical Writing

In the last month, I've set out to learn to improve my technical writing. My team at Nimble carefully chose the materials for members who want to improve technical documentation skills; plan and author technical documents.

Overall, there're three online courses. One is in video format; the other two are reading materials. This document summarizes all the key points and best practices in the materials. I considered this document a practical exercise for what I've learned.

## Table of contents
- [1. Technical Writing One](#1-technical-writing-one)
- [2. Technical Writing Two](#2-technical-writing-two)
- [3. Technical Writing: Documentation on Software Projects](#3-technical-writing-documentation-on-software-projects)
	- [3.1 The Writing Process](#31-the-writing-process)
	- [3.2 Writing Tips and Best Practices](#32-writing-tips-and-best-practices)
	- [3.3 Layout and Design](#33-layout-and-design)
	- [3.4 Deliverables](#34-deliverables)
- [4. Summary](#4-summary)

## 1. Technical Writing One
This course is a part of [Google's Technical Writing Courses](https://developers.google.com/tech-writing/one). It teaches you the fundamentals of technical writing.
#### Use terminology correctly and consistently
- Learn to recognize terms that might be unfamiliar to the target audience. If the term already exists, link to a good existing explanation. If the document is introducing the term, define the term.
- After first referring to the term, you use the same term consistently throughout the document.
- When using an unfamiliar acronym, spell out the full term and then put the acronym in parentheses.
#### Prefer active voice to passive voice
- Use active voice most of the time because the active voice is (generally) shorter, clearer, and straight to the point.
#### Write clear and short sentences
- Choose precise, strong, specific verbs to engage and educate readers.
- Remove or replace **"There is"** or **"There are"** with a better subject to strengthen the sentence and make it clearer.
- Focus each sentence on a single idea, thought, or concept. Try to break long sentences into a series of shorter, single-idea sentences.
- When you see the conjunction **or** in a long sentence, consider refactoring that sentence into a [bulleted list](#create-helpful-lists).
- Eliminate or reduce unnecessary, wordy phrases with shorter words. A few suggestions like, you can replace "at this point in time" with "now"; or "determine the location of" with just simple as "find", etc.
#### Create helpful lists
- There're three types of lists in technical writing: bulleted, numbered and embedded. The first step to making a list helpful is choosing the correct type of list. Use a **bulleted list** for _unordered_ items; use a **numbered list** for _ordered_ items; and avoid **embedded lists** by converting them into either bulleted or numbered ones.
- Keep list items parallel. All items in a parallel list match along the following parameters:
	- grammar
	- logical category
	- capitalization
	- punctuation
- Start all items in a numbered list with imperative verbs.
- If the list item is a sentence, use sentence capitalization and punctuation. Otherwise, do not use sentence capitalization and punctuation.
#### Build cohesive paragraphs
- Focus writing energy on making great opening sentences.
- A paragraph should represent an independent unit of logic. Focus each paragraph on a single topic. Don't describe what will happen in a future topic or what happened in a past topic.
- Long paragraphs are visually intimidating. Consider dividing them into two or more separate paragraphs. Don't make short, like one-sentence paragraphs.

#### Provide the information that the audience needs
- Define the audience:
	- Identify the audience's role(s).
	- Consider the audience's *proximity* to the knowledge and the time.
- List things the target audience needs to learn to accomplish goals.
- Create explanations that satisfy the audience's curiosity:
	- [Match vocabulary to the audience.](#use-terminology-correctly-and-consistently)
	- Prefer simple words over complex words; avoid obsolete or overly-complex English words.
	- Keep writing culturally neutral.
#### Organize a document
- Define the document's scope. Even better, define its non-scope–the topics not covered.
- Explicitly define the document's audience, including their role and any prerequisite knowledge or experience.
- Summarize key points at the start.
## 2. Technical Writing Two
This course is a part of [Google's Technical Writing Courses](https://developers.google.com/tech-writing/one). It focuses on several intermediate topics in technical writing.
#### Self-edit our document
- Adopt an existing style guide or write our own. [Google Developer Documentation Style Guide](https://developers.google.com/style) is a good source.
- Try to read the draft from the audience's point of view. It can be helpful to outline a persona for the audience. you can then review the draft with our persona in mind.
- To check if our writing is conversational, read it out loud.
- Come back to the draft after an hour (or two or three) and try to read it with fresh eyes.
- Ask someone to review our document.
#### Organize large documents
- Determine whether to write a single, large document, or a set of documents.
- Some techniques for planning a long document:
	- Starting with a structured, high-level outline can help us group topics and determine where more detail is needed. The outline allows us to move topics around before getting down to writing.
	- Provide an introduction to the document, including what it covers, what it doesn't, and what prior knowledge you expect readers to have.
- Provide navigation so readers can find what they are looking for and the information they need to get unstuck.
#### Illustrating
- It is helpful to write the caption _before_ creating the illustration. Then, create the illustration that best represents the caption.
- Don't put more than one paragraph's worth of information in a single diagram. Try to organize complex systems into subsystems to reduce visual clutter.
#### Add good sample code
- The sample code should be correct, meaning it should meet the following criteria:
	- Build without errors.
	- Perform the task it claims to perform.
	- Bes as production-ready as possible.
	- Follow language-specific conventions.
- Sample code should be short, including only essential components.
- Sample code should be easier to read and understand.
## 3. Technical Writing: Documentation on Software Projects
This is a paid online course on [Pluralsight](https://www.pluralsight.com/courses/technical-writing-software-documentation).
> This course covers the fundamentals of writing effective software documentation. Whether you need to document requirements, architecture/design, code, test plans, or manuals for end users, this course gives you tips and best practices to do it all.

### 3.1 The Writing Process

![](../.github/images/Pluralsight-TechnicalWriting.png?raw=true)
<p align="center"><i>(Image extracted from the course)</i></p>

#### The Planning phase
This phase is where you identify the purpose of the document, the [audience](#provide-the-information-that-the-audience-needs) for whom you're writing, and the delivery.
- The purpose is the reason that the document exists.
- Analyze your audience by asking the following questions:
	- Who will be reading the document (demographics)?
	- What do they already know?
	- Why are they going to be reading it?
	- In what environment will they be reading it?
	- What is their state of mind?
	- What do they NEED to know?
- What's the best way to deliver the information to the audience?
#### The Research phase
After you've completed the planning phase, and understand your purpose, audience, and delivery, it's time to move on to the research part of the writing process.
This is the part where you get the information out of the heads of the software creators (then put it into the heads of the users). There're three primary ways to do this:
- Interview Subject Matter Experts (SMEs)
- Review existing documentation
- Use the software
SME is one of the best ways to get the information you need. You want to get as much as you can from the people who have the information.
#### The Writing phase
You've done the preparation and planning, done your research, and interviewed your SMEs; it's time to get it on paper.
- Organize and order your ideas using lists and categories.
- Write the first draft. Don't worry too much about grammar, formatting, word choice, spelling, or those types of things.
- Review and revise your work. During this step, you want to ask yourself:
	- Does the document fulfill its purpose?
	- Is anything missing?
	- Can anything be taken out?
	- What questions will the reader have? And answer them.
	- Is the writing easy to understand?
	- Also, check for sentence and paragraph structure, grammar, word choice, and spelling.
#### The Reviewing/Editing phase
The purpose of this phase is to adjust and reorganize the content so that it makes sense, flows better, and is easy for the reader to understand. The editing for styling happens here when a peer reviewer or editor reviews the document to ensure it jives with the style guide. This phase also checks for grammar and punctuation. And finally, it should also incorporate test results from usability testing.

Tips for reviewing and editing:
- Have someone else do it.
- Just walk away from it; read it out loud; print it out, or change margins.
- Edit with a knife–try to cut down on content and the number of pages.
#### The Launch phase
It's time to ship! Here's a brief checklist of things that happen during the launch phase:
- Handle translations, if applicable.
- Bundle up final deliverables.
- Coordinate with the development team and other writers to release.
- Create a plan for updates.
### 3.2 Writing Tips and Best Practices
#### Accuracy
Accuracy means the careful conforming to truth or fact. The three aspects of accuracy in the documentation:
- Document accuracy
	- Contains proper coverage of topics in appropriate detail.
	- Focuses clearly on a problem or solution.
	- Solves a theoretical or practical problem.
- Stylistic accuracy
	- Careful use of language to express meaning.
	- Words are used precisely.
	- Paragraph and sentence structure describe and analyze topics effectively.
- Technical accuracy
	- Grounded in technically accurate understanding and representation of the subject.
	- Depends on the writer's conceptual mastery of the subject.
	- Data is analyzed and shaped with minimum distortion.

Here are some tips to increase the accuracy of your documentation:
- Consult with your Subject Matter Experts (SMEs), as mentioned in [[#The Research phase|the Research phase]].
- Conduct usability testing of the document.
- Proofread every page; ideally, have another person proofread as well.
#### Clarity
Clarity makes for ease of understanding. Here are how you can increase accuracy in your documentation.

At the document level, you can promote structural clarity by using the following elements:
- abstracts
- introductions
- statements of purpose
- tables of contents
- problem statements
- graphs
- tables
- descriptive titles and headings

Looking at stylistic clarity, here are a few tips for that:
- Be specific. Try to quantify. Try to put metrics around things.
- Be active (in voice). Avoid using the passive voice, as the active voice is much more clear.
- Be strong and say what you mean.

Finally, we have the contextual clarity of a document. This means putting things in context and giving the big picture. Tips for this include:
- State the purpose of the document.
- Let the readers know what precedes the document.
- Let the readers know how this document relates to others.
#### Conciseness
A concise document conveys only the needed material, especially in technical writing.

To increase conciseness:
- Have a clear focus from the start.
- Eliminate material and words not necessary to support your claims.
- Use visuals than words.
#### Tone
Tone can be defined as the attitude of a writer toward a subject or an audience, and the audience should determine that tone.
- Be conversational. Write the way you talk.
- Show some personality in your writing.
#### Tense
Here we're talking about verb forms that indicate time distinctions. It's most common to use the present tense in technical writing. The other tense you might use is the future tense. But regardless of which tense you choose, make sure you stay consistent. Mixing tenses can be confusing and can throw your reader off.
#### Grammar, Spelling, and Terminology
Some commonly misused words:
- "their", "they're", and "there"
- "its" and "it's"
- "affect" and "effect"
- "set up" versus "setup"
- "back up" versus "back up"
- "log in" versus "login"
- "i.e." versus "e.g."
### 3.3 Layout and Design
You may not expect this part in technical writing, but it's a very important part of making your documents easy to read and use.
#### Typography
According to [Wikipedia](https://en.wikipedia.org/wiki/Typography):
> **Typography** is the art and technique of arranging type to make written language legible, readable and appealing when displayed

There are many different categories of typography, but the following four categories should cover 99% of what you'll be dealing with:
- **Serif fonts**. They are typically considered to be classic, traditional, and embellished. These fonts are good for printed materials, headings, and font sizes of 12 or more.
- **Sans Serif fonts**. They are seen as more modern, minimalist, and clean compared to serif fonts. These fonts are good for use on the web, even on low-resolution screens, and look professional and clean.
- **Script fonts**. They are more fluid in their stroke and often resemble handwriting, particularly cursive handwriting. Use these fonts in very limited amounts, if at all.
- **Decorative fonts**. Characteristics of these fonts are fun, unique, and expressive. These fonts are difficult to read when used for paragraphs or full sentences of text. Use these fonts in very limited amounts, if at all.

Some guidelines you can go with typography:
- Communication and clarity are most important.
- Keep contrast high.
- Limit the number of fonts that you use, and be consistent in their use.
- On the web, use web-safe fonts.
- Use a size 10 font or larger.
- Use APP CAPS sparingly.
- Design for copy-and-paste.
#### Design Principles
Fundamentals design principles can be applied to writing documentation.
- **Alignment**. Left, right, or centered alignment can create strength and cohesion in a design.
- **Proximity**, or how close one element is to another, implies a relationship or a lack thereof.
- **Contrast**
- **Whitespace**, or the lack of text and graphics, is a simple but powerful way to draw attention to certain elements and let a document breathe.

Some specific elements you can use in your documents:
- **Table of Contents**. Include this for documents of ten pages or longer.
- **Revision history** allows readers to identify who made changes, when they were made, and what they were. Some tips:
	- Provide descriptive details about what changes were made and who had input.
	- Update the history each time the document is revised.
- **Headers and Footers** are also important so readers can easily identify sections, page numbers, dates, etc. Possible information to include:
	- Page number: a multipage-document should always include this
	- Section or subsection topic
	- Date the document was written
	- Document name
	- Document path
	- Copyright information
- **Lists and bullet points**. They enhance scannability, great for listing steps and sequences, and generally make complex information easier to absorb.
	- Include only one step or piece of information per bullet point.
	- Begin each list item the same way.
	- Capitalize the first word of each bullet.
	- Use numbers to show the sequence.
	- Use bullets when you do not wish to show sequence or rank.
- **Captions**, to highlight or describe a visual, are typically placed below figures and above tables.
- **Glossary** for looking up terms and definitions.
	- Use language the reader will understand.
	- Arrange terms alphabetically, dictionary style.
	- Place it at the end of the document.

It's also common to use a variety of visuals in a document to make the information easier to understand and move through.
- Screenshots
- Icons and symbols
- Tables
- Graphs
- Charts
### 3.4 Deliverables
#### 3.4.1 Requirements
Tips for writing clear requirements:

**Do**
- Use terms consistently.
- Define terms in a glossary.
- Use active voice.
- Consider boundary values (e.g., *"less than or equal to"**).
- Avoid negation.

**Don't**
- Design the system (component names, types of controls, database fields).
- Use vague terms (user-friendly, efficient, high-performance, approximately, several).
- Speculate (usually, often, typically).
- Express possibilities (could, ought to, probably).
- Ramble.

We have three styles of requirements.

**User Story**
- One or more sentences in everyday or business language that capture what a user needs to do.
- The format: As a \<**type of user**\>, I want \<**some goal**\> so that \<**some reason**\>
- Brief, bite-size, understandable by users and developers, require little maintenance, iterative, and easy to estimate effort.
- The limitations are they can be vague, open to interpretation, incomplete, and lack performance or non-functional details.
User stories are commonly used with acceptance criteria. These define the boundaries of the user story and how you can verify that a story is complete or working as intended.

**Traditional (Text-based)**
- One or more sentences specify high-level functionality for the business or stakeholders.
- The format: \<**Subject doing the action**\>\<**auxiliary verb**\>\<**capability or functionality to be provided**\>\<**criterion that limits or further explains requirement** (optional component)\>
- It can be used to capture complete requirements early in the project.
- Its limitation is that it may need more detail for implementation.

**Use Cases**
- A list of actions or event steps, typically defining interactions between an actor and a system, to achieve a goal.
- Robust and comprehensive, up-front research can be beneficial long term and requires the identification of alternative scenarios and error cases.
#### 3.4.2 Design/Architecture
The Software Design Document (SDD) gives the project team overall guidance on what and how to build software. Its sections are:
- **Introduction**
	- Purpose
	- Scope
	- Intended audience
	- Design goals and rationale
- **System Architecture**
	- A high-level overview of the functionality and responsibilities of the system.
	- Describe high-level components and how they work together.
	- Diagrams, flowcharts, models, scenarios, and high-level use cases show system behavior or structure.
- **Detailed System Design**
	- Describe in detail the functionality and responsibilities of each component of the system.
	- Use class diagrams and sequence diagrams to show relationships and flows.
- **Data Design**
	- Describe data structures, databases, and storage units and their relationships.
	- Entity Relationship Diagram (ERD) to show structure and relationships.
- **User Interface**
	- Describe functionality from the user's perspective.
	- Wireframes or mockups of what the UI will look like.
	- Describe the controls and their behaviors.
	- Supported orientations and dimensions.
- **Glossary/Appendix**
#### 3.4.3 Code Documentation
**Code Comment**
- **How NOT to use comments in code**
	- To state something obvious or redundant
	- To explain poorly-written or poorly-designed code
	- To _sort of_ delete code
- **How TO use comments in code**
	- High-level comments
	- Generally useful at the class level
	- TODO, HACK, and UNDONE flags

**API Documentation**

What you should include in your API documentation:
- Reference documentation
- Overview and concepts
- Tutorials/training
- Installation/getting-started/troubleshooting documentation
- SDK tools documentation
- License information

**README files**

A file (usually .txt) that helps users/other developers know how to do things with your software.

What does a good README file look like?
- Date
- Software name and version number
- Short description of the software
- Installation requirements and instructions
- Copyright and licensing information
- Contact information for the developer or distributor
#### 3.4.4 Test Plans and Test Cases
**Test Plan**

Outlines the strategy of testing software to ensure it meets the design specifications and requirements.

A typical test plan might include the following:
  - Introduction
  - Test strategy
  - Execution strategy
  - Test management process
  - Test environment
- The document is not meant to describe how to test but to outline the approach to testing.

**Test cases**

Sets of steps required to test software functionality. A collection of test cases make up a test scenario.

Characteristics of a good test case:
  - Anyone can execute it.
  - All necessary details are included.
  - Strong, descriptive title.
  - Consistent naming conventions.
  - Legible and easy to understand.
  - Reusable.
#### 3.4.5 End-user Documentation
There're three kinds of documents we're mentioning here: User Guides, Quick Reference Guides, and Release Notes.

**User Guides**

A user guide helps the end user understand and use the system.

An example of a user guide:
- Table of contents
- Overview
- Getting started
- Tutorials
- Troubleshooting
- Frequently-asked questions (FAQs)
- Support
- Glossary
- Index

**Quick Reference Guides**

The idea of the quick reference is to distill key information from the user guide and summarize it into a short document, preferably one page.

Useful elements for Quick Reference Guides:
- Diagrams
- Reference tables
- Steps
- Graphics/infographics

**Release Notes**

Documents the differences between two versions of the same software (e.g., v1 and v2).

A typical release note might include the following:
- Release date
- Product version
- Previous product version
- New features
- Enhancements
- Resolved issues
- Known issues
- Frequently Asked Questions (FAQs)
## 4. Summary
The materials from these courses help you improve your technical writing as a software engineer. You are starting with fundamentals like how to use terminology consistently and how to formulate cohesive paragraphs. Then move to intermediate topics like defining your audience, organizing large documents, and breaking down the writing process into distinct phases. And finally, examine common documents in software projects, including requirements, the design or architecture document, code documentation, test plans and test cases, and end-user documentation.