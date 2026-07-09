## When to use this Requirements Assistant

Use this BSP Lite Requirements Assistant to do any or all of the following:
* Provide an architecture analysis to determine if an existing component can be enhanced or if a new component is necessary or if the requested functionality already exists.
* Review the existing architecture of a component.
* Generate back-end, style tab, front-end, and accessibility requirements as well as acceptance criteria.
* Update component documentation.

## Typical workflow

Use a prompt such as
	Design a new BSP Lite component.
	Enhance an existing BSP Lite component.
	Review this design.
	Find similar BSP Lite components.
	Update the component documentation.
Provide a purpose of the new component or enhancement
Provide any business requirements
Provide some designs.
Let it do its thing.

## Preparing a Figma

Have a designer prepare some Figma designs. 
Since GPT does not have access to Figma, you will need to copy and paste screen shots of the designs into the prompt.

## Writing business requirements

Keep the business requirements as simple as possible, but provide enough information that it can generate all the requirements to fulfill the business requirements.

## Architecture review process

 The architecture analysis should provide plenty of information to take to Stack Team tech review. The analysis follows these principles:
	 Maximize reuse
	 Preserve publisher simplicity
	 Maintain system consistency
	 Accessibility by design
	 Transparent decision making (it will explain all the recommendations)
	 Configuration over duplication
	 Composable architecture (it will reuse containers, references, sub-components, style options, etc.)
	

## Generating Jira tickets

GPT does not have access to Jira, so you will have to make and populate the tickets yourself.
But all the requirements should be formatted for simple copy and paste.

## Review checklist

Always check to be sure there are no hallucinations, bad requirements, missing requirements, etc. 
Review the architecture recommendation with the Stack Team. They will know things about our setup that GPT doesn't know. 
If at all possible, when issues are found, we should be improving the Requirements Assistant to help it provide better results in the future.



## Files list

### GPT System Instructions

This file tells the system who it is and what it needs to do. The sections in this file include:
	Role
	Expertise
	Responsibilities
	Engineering Principles
	Requirements Workflow
	Knowledge Usage
	Clarifying Questions
	Recommendation Style
	Conflicts
	Response Principles

### BSP Lite Engineering Principles

This file gives the details of the principles it should follow. The sections in this file include:
	 Maximize reuse
	 Preserve publisher simplicity
	 Maintain system consistency
	 Accessibility by design
	 Transparent decision making (it will explain all the recommendations)
	 Configuration over duplication
	 Composable architecture (it will reuse containers, references, sub-components, style options, etc.)

### Workflow

This file gives the workflow to be followed. Each step or decision gate has all the sub-sections the Requirements Assistant needs to complete the step and produce the requested output. The sections in this file include:
	Step 0 - Request Classification
	Step 1 - Architecture Analysis
	Decision Gate 1 – Architecture Decision
	Step 2 – Design Interpretation
	Step 3 – Component Modeling
	Decision Gate 2 – Style Validation
	Step 4 – Style Tab Requirements
	Decision Gate 3 – Style Review
	Step 5 – Back End Requirements
	Step 6 – Front End Requirements
	Step 7 – Accessibility Requirements
	Step 8 – Acceptance Criteria
	Decision Gate 4 – Output Selection
	Step 9 – Jira Ticket Output


### Output Templates

This file tells the Requirements Assistant what the outputs should look like for each step in the workflow.

## Knowledge Base

This is a collection of files to help the Requirements Assistant know about Brightspot Lite and its components, as well as examples of Jira Tickets and accessibility requirements to help it know how to format requirements.