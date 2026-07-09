## ![](https://confluence.churchofjesuschrist.org/download/attachments/309299846/image-2025-12-30_13-15-57.png?version=1&modificationDate=1767125757810&api=v2)

![](https://confluence.churchofjesuschrist.org/download/attachments/309299846/image-2026-5-15_9-54-12.png?version=1&modificationDate=1778860452863&api=v2)

  

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
- Invert Button Colors (boolean, default to false)
    - This isn't used. Buttons and Links have style options of their own to change the button style.
- Title style
    - Single select dropdown
    - Options are H2 and H3
    - Default is H2
- Hide Title (boolean, default to false)
- Hide Kicker (boolean, default to false)
- Component Width 
    - Single select dropdown
    - Options are Pop (1024px) and Plus (1600px)
    - Default is Pop
- Component Aspect Ratio
    - Single select dropdown
    - Options are 4x1 (shortest), 2.4x1 (short), 16x9 (normal), 4x3 (tall), 1x1 (taller), 3x4 (tallest), Original
    - Default is 16x9 (normal) 
- Image Position Horizontal
    - Single select dropdown
    - Options are Left and Right
    - Default is Left
- Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- Choose font style for title
    - Single select dropdown
    - Options are Standard (Zoram) and Formal (McKay)
    - Default is Formal (McKay)
- Hide Light Rays (boolean, default to false)
- Background Color
    - Single select dropdown
    - Options are
        - White
        - Light Gray
        - Blue (MS Use Only)
            
        - Dark Blue (MS Use Only)
            
        - Light Yellow (MS Use Only)
            
        - Medium Gray (MS Use Only)
            
        - Dark Gray (MS Use Only)
            
    - Default is White
- Change Primary Text Color to Primary Inverse Text color (set in theme colors) (boolean, default to false)
- Split Percentage
    - Single select dropdown
    - Options are 50x50 and 60x40
    - Default to 60x40

  

### States

Button Hover: Primary button background changes color, cursor turns into hand pointer. Secondary button only has the cursor turned into hand pointer.

  

### Front End Functional Requirements

- Only the button is the click target.