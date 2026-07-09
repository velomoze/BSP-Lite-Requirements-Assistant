![](https://confluence.churchofjesuschrist.org/download/attachments/309299860/image-2025-12-30_13-18-21.png?version=1&modificationDate=1767125901787&api=v2)

![](https://confluence.churchofjesuschrist.org/download/attachments/309299860/image-2026-5-15_9-51-1.png?version=1&modificationDate=1778860261287&api=v2)

### Sub-components used

Promo, Modal

### Fields

- Item (single select dropdown, not required)
    - Options are Internal, External, Modal, or No Link
    - Default is Internal
    - Internal allows the publisher to select an existing article in Brightspot.
    - External allows the publisher to add a url link to an external page. It also has fields for Link Text. External links also have an alert notification field to alert users when they are leaving the site.
    - Modal allows the publisher to add a popup modal. See the Modal component.
- Pre-title (tiny text, not required)
- Title (tiny text, not required)
- Kicker (medium text, not required)
- CTA Button Text Override (tiny text, not required)
- Image Override (search select, not required)
    - Allows the publisher to search images and add one to the Promo.

### Style Options

- Vertical Spacing
    - Single select dropdown
        - Options are None (0px), Unite (16px), Related (32px), Separated Small (64px), Separated Large (128px), 4px, 8px, and 96px
    - Default is Separated Small (64px)
- Hide From In Page Navigation (boolean, default to false)
- Image Aspect Ratio
    - Single select dropdown
    - Options are 4x1 (shortest), 2.4x1 (short), 16x9 (normal), 4x3 (tall), 1x1 (taller), 3x4 (tallest), Original
    - Default is 16x9 (normal) 
- Component Width 
    - Single select dropdown
    - Options are Read (672px), Pop (1024px), and Plus (1600px)
    - Default is Pop
- Hide Category (boolean, default to false)
- Should this module show the byline? (boolean, default to false)
    - This style option is not used in the Web Theme
- Set the color for the overlay
    - Single select dropdown
    - Options are 
        - White
        - Blue
        - Green
        - Red
        - Yellow
        - Light Gray
        - Dark Gray
        - CHD-Only Light Green
        - CHD-Only Gray
        - CHD-Only Orange
        - CHD-Only Brown
    - Default is White
- Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start

  

### States

Button Hover: Primary button background changes color, cursor turns into hand pointer. Secondary button only has the cursor turned into hand pointer.

  

### Front End Functional Requirements

- Only the button is the click target.