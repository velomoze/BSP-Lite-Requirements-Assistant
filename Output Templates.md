BSP Lite Requirements Engineering Framework

Version 1.0

Last Updated

July 2026

Owner

Jeff Mousley

# Identify the Selected Mode
**Request Type:** New Component  
**Workflow:** Full Requirements Engineering Workflow  
**Expected Deliverables:** Architecture Analysis, Style Tab Requirements, Back End Requirements, Front End Requirements, Accessibility Requirements, Acceptance Criteria, and Jira-ready tickets.

# Architecture Analysis

## Design Summary

A concise summary (2–4 paragraphs) describing the purpose of the requested feature.

---

## Existing BSP Lite Components Evaluated

| Component | Evaluation | Decision | Reason |
|-----------|------------|----------|--------|
| Drawer Module | Similar interaction | Not Selected | Does not support promotional layout. |
| One Column Container | Hidden content | Reuse | Existing container satisfies requirement. |
| Page Promo Show/Hide | Closest match | Extend | Existing behavior is almost identical. |

---

## Requirements Not Yet Defined

The following items should be clarified before implementation:

- Analytics requirements
- Localization requirements
- Empty state behavior
- Error handling

---

## Components Recommended for Reuse

List every existing BSP Lite component that should be reused.

Example:

- One Column Container
- Promo
- Reference
- Standard Button Styles
- Theme Style Options

---

## Alternative Solutions Considered

Describe every significant architectural approach that was considered.

For each:

### Option

### Advantages

### Disadvantages

### Why it was rejected

---

## Recommended Architecture

Choose one:

☐ Reuse Existing Component

☐ Extend Existing Component

☐ Create Component Variation

☐ Create New Component

---

## Architecture Rationale

Explain why this recommendation best aligns with BSP Lite Engineering Principles.

Reference specific principles.

---

## Architectural Considerations

Identify potential concerns.

Examples:

- Performance
- Accessibility
- Future extensibility
- Publisher usability
- Backward compatibility

---

## Architecture Confidence

High

Reason:

## Scope

In Scope

- ...

Out of Scope

- ...


# Enhancement Recommendation

## Existing Component

Component:

Purpose:

Current capabilities:

---

## Requested Enhancement

Describe the requested functionality.

---

## Impact Analysis

### Publisher Experience

How does this affect publishers?

---

### Existing Pages

Will existing pages change?

---

## Compatibility

Will existing pages continue to function?

Will existing publishers notice any change?

Will existing APIs change?

Is migration required?

---

### Existing Style Options

Will existing style options change?

---

### New Style Options

List proposed additions.

---

### CMS Changes

Fields

Validation

Publishing

References

Containers

---

### Front End Changes

Rendering

Interactions

Responsive behavior

Accessibility

---

## Alternatives Considered

Option

Reason rejected

---

## Recommendation

Proceed with enhancement?

Yes / No

Recommendation Type:

Routine (a normal enhancement)

Moderate (touches multiple components)

Major Architectural Change (changes core architecture)

---

## Engineering Principles Applied

List which principles influenced the recommendation.

---

## Questions for Stack Team

1. Should this become a reusable style option?

2. Should this behavior be reusable by other Page Promos?

3. Should this component support Dynamic mode?

---

## Confidence

High

Medium

Low

## Scope

In Scope

- ...

Out of Scope

- ...



# Requirements

## Front End Style Tab Requirements

Style Tab Requirements define publisher-configurable presentation options that are implemented by the Front End.

These requirements belong with the Front End ticket because the rendering behavior is implemented in the Handlebars templates and CSS.

When enhancing an existing component, include all affected Style Tab options, not only the new options, so the complete rendering behavior is documented.

Do not duplicate Style Tab Requirements in the Back End ticket.

The Back End ticket should reference the Style Tab Requirements contained in the Front End ticket whenever the Back End creates fields that support those options.

List the style settings and the available options that can be selected by a publisher. 

If an enhancement to an existing component, list all needed style tab settings so the enhanced component can be displayed to match the designs.

For a new component, determine which of the standard style tab options are appropriate for the new component. 

Then identify style options that are necessary to match the designs. 

Display the style tab options in this format:

### Image Position Horizontal

- Option Type
    - Single select dropdown

- Options
    - Left
    - Right

- Default
    - Left

- Notes
    - Controls whether the image appears before or after the content.


## Back End Requirements

List the changes that need to be made to the models and view models in Brightspot. 

Display the Back End Requirements in this format:

Name of the Module
	For each field, document:
	- Name
	- Type
	- Required / Optional
	- Indexed?
	- Toolbar (if applicable)
	- Validation
	- Notes
		
For text fields, list the tool bar to include. 
	Tool bar options: 
		- LargeRichTextToolbar—Provides all buttons.
		- MediumRichTextToolbar—provides buttons for text formatting, alignment, lists, enhancements, and HTML.
		- SmallRichTextToolbar—provides buttons for text formatting, links, alignment, and lists.
		- TinyRichTextToolbar—provides buttons for text formatting.
		- Plain Text - No tool bar is provided.

Sub-components Used
Examples:

- Promo
- Figure
- Rich Text

Include any fields necessary for accessibility, such as alt text fields for buttons and links.
## Front End Requirements

List the changes that need to be made to the front end - Handlebars and CSS changes - to make the component display as in the Figma designs.

List the requirements in short statements, keeping the text concise. 
Layout

...

Rendering

...

Interactions

...

Responsive Behavior

...

Component States

...

Style Tab Behavior

...

Error Handling

...

Performance Considerations

...


## Accessibility Requirements

It is not possible to list every accessibility requirement from WCAG. Provide a list of guidelines for ensuring accessibility for keyboard navigation and popular screen readers. 

Do not repeat generic WCAG requirements.

Instead describe only the accessibility behavior unique to this component.

Reference standard accessibility patterns whenever possible.

Use the Accessibility Requirements Example.md for formatting these requirements.

Use a bulleted list.

Do not list detailed requirements. Instead, provide a list of items to guide the developer towards full accessibility. 

Include guidelines for ensuring full keyboard access to all parts of the component. 
Include guidelines for ensuring full access using a screen reader.
Include guidelines for ensuring semantic tags are used.


## Acceptance Criteria

List the things that a QA needs to test to ensure the component looks and functions according to the requirements and design. 

Do not provide a positive and negative statement for every requirement. 

Acceptance Criteria are only needed for Front End Requirements.

Use a bulleted list.

Include statements that will test all the listed functionality in the front end requirements. 
Include statements that will test that all the requested text displays are displayed and correct.
Include statements that will test keyboard access.

For standard style tab options, a statement such as the following is sufficient - - The modal title, description, and icon display are controlled with the Show Header Text and Icon toggle.

For non-standard style tab options, include a statement to test all options for a setting. 

For example: 
	Functional

	- Drawer opens.
	
	- Drawer closes.
	
	Visual
	
	- Background color changes correctly.
	
	Accessibility
	
	- Keyboard navigation works.
	
	- Screen reader announces expanded state.



## Complete Jira Ticket

Separate tickets are needed for Back End Requirements and for the Front End Requirements, Accessibility Requirements, and Acceptance Criteria.

For the Back End Ticket: 

Summary

Description

Reference Designs

Architecture Summary (optional)

### Back End Requirements

...

### Acceptance Criteria

## Assumptions

The following assumptions were made:

- Existing button styles are reused.

- Existing background color options are reused.

- Standard accessibility patterns apply.


## References

List all BSP Lite components, standards, and documentation used to produce these requirements.

Example:
References

- Page Promo Spotlight

- Promo

- Workflow

- Engineering Principles

- CCD Web Theme Style Standards


For the Front End Ticket:

Summary

Description

Reference Designs

Architecture Summary (optional)

### Front End Requirements

...

### Style Tab Requirements

...

### Accessibility Requirements

...

### Acceptance Criteria

...

## Assumptions

The following assumptions were made:

- Existing button styles are reused.

- Existing background color options are reused.

- Standard accessibility patterns apply.

## References

List all BSP Lite components, standards, and documentation used to produce these requirements.

Example:
References

- Page Promo Spotlight

- Promo

- Workflow

- Engineering Principles

- CCD Web Theme Style Standards