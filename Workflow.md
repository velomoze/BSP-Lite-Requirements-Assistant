BSP Lite Requirements Engineering Framework

Version 1.0

Last Updated

July 2026

Owner

Jeff Mousley

# BSP Lite Requirements Engineering Workflow

This workflow shall be followed every time a new BSP Lite component, enhancement, or variation is analyzed.

The steps must be completed in order.

---

# Step 0 -  Request Classification

Before responding, determine the user's intent.

If the request involves designing, enhancing, reviewing, or documenting a BSP Lite component, follow the BSP Lite Requirements Engineering Workflow.

If the request is informational (for example, explaining an existing component or answering a question about BSP Lite), answer directly using the Knowledge Base without invoking the workflow.

If the user's intent is ambiguous, ask a clarifying question before beginning the workflow.


# Step 1 – Architecture Analysis

## Purpose

Determine whether a new component is actually required before creating implementation requirements.

## Activities

- Summarize the design.
- Identify the purpose of the component.
- Search existing BSP Lite components.
- Evaluate whether existing components satisfy the requirements.
- Consider component composition before creating new components.
- Consider extending existing components before creating new ones.

## Output

### Design Summary

Provide a brief summary of the component.

### Existing Components Evaluated

For every significant candidate list:

- Component
- Decision
- Reason

Example

| Component | Decision | Reason |
|-----------|----------|--------|
| Drawer Module | Not Selected | Does not support this interaction |
| One Column Container | Reuse | Appropriate hidden content container |
| Page Promo Show/Hide | Extend | Closely matches required behavior |

### Recommendation

Choose exactly one:

- Reuse Existing Component
- Extend Existing Component
- Create Variation
- Create New Component

### Components to Reuse

List all existing BSP Lite components that should be reused.

### Architecture Rationale

Explain why the recommendation was selected.

### Architecture Confidence

Assign one:

- High
- Medium
- Low

Include reasoning.

## Decision Gate 1 – Architecture Decision

Before proceeding, determine whether implementation work is required.

Possible outcomes:

### Reuse Existing Component
- No new Jira ticket is required.
- Explain how the existing component satisfies the design.
- Recommend configuration or composition if necessary.
- Stop unless the user requests an enhancement analysis.

### Extend Existing Component
- Continue to Step 2.
- The remaining workflow should generate enhancement requirements.

### Create Variation
- Continue to Step 2.
- The remaining workflow should describe only the differences from the existing component whenever practical.

### Create New Component
- Continue to Step 2.

### Insufficient Information
- Do not continue.
- Ask the user clarifying questions.
- Resume the workflow after the required information has been provided.
---

# Step 2 – Design Interpretation

## Purpose

Interpret the supplied Figma design or screenshots.

## Activities

Identify:

- Layout
- Variants
- Responsive behavior
- States
- Animations
- Interactions
- Publisher configurable options


---

# Step 3 – Component Modeling

## Purpose

Create the Brightspot content model.

## Activities

Define:

- Fields
- Containers
- References
- Allowed sub-components
- Validation rules
- Required vs optional fields

## Decision Gate 2 – Style Validation

Before generating implementation requirements, verify that the component model is complete.

Confirm that:

- Required fields have been identified.
- Optional fields have been identified.
- Reused components have been identified.
- Publisher-editable content has been identified.
- Publisher-configurable presentation has been identified.

If additional information is required, ask clarifying questions before continuing.

---

# Step 4 – Style Tab Requirements

## Purpose

Define all publisher-configurable presentation options.

## Rules

Always include applicable CCD Web Theme standard style options.

Only create new style options when an existing option cannot accomplish the design.

Each option shall include:

- Name
- Control type
- Allowed values
- Default value
- Notes

Examples include:

- Component Width
- Vertical Spacing
- Background Color
- Image Position
- Image Aspect Ratio
- Alignment
- Button Style

## Decision Gate 3 – Style Review

Confirm that every publisher-controlled visual variation is represented by a Style Tab option.

Verify that:

- Existing CCD Web Theme style options are reused whenever possible.
- New style options are only introduced when no existing option satisfies the design.
- Every style option includes:
  - Control type
  - Allowed values
  - Default value

After this gate, Style Tab requirements become implementation inputs for the Front End requirements.

---

# Step 5 – Back End Requirements

Describe:

- CMS behavior
- Publishing workflow
- Field behavior
- Validation
- Restrictions
- Availability
- View model updates
- Data relationships

---

# Step 6 – Front End Requirements

Describe:

- Rendering
- Layout
- Responsive behavior
- Interactions
- Animations
- Hover states
- Loading states
- Error handling

These requirements shall implement the Style Tab options defined previously.

---

# Step 7 – Accessibility Requirements

Include:

- Semantic HTML
- Keyboard navigation
- Focus management
- Screen reader behavior
- ARIA attributes
- Motion preferences
- Contrast considerations

Follow established BSP Lite accessibility patterns.

---

# Step 8 – Acceptance Criteria

Generate testable acceptance criteria.

Requirements should be suitable for QA verification.

Separate Front End and Back End acceptance criteria where appropriate.

## Decision Gate 4 – Output Selection

Determine which deliverables the user requested.

Possible outputs:

- Architecture Analysis only
- Style Tab Requirements only
- Back End Requirements only
- Front End Requirements only
- Accessibility Requirements only
- Complete Jira Back End ticket
- Complete Jira Front End ticket
- Combined Jira ticket

Generate only the requested deliverables.

---

# Step 9 – Jira Ticket Output

Produce Jira-ready output.

When requested generate:

- Backend ticket
- Frontend ticket

or

Combined ticket.

Formatting shall match existing BSP Lite Jira conventions.


## Workflow Completion

Before returning the final output, verify:

- Workflow steps were completed.
- Engineering Principles were followed.
- Existing BSP Lite components were evaluated.
- Assumptions were documented.
- Requested deliverables were produced.