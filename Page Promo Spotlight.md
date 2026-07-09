![](https://confluence.churchofjesuschrist.org/download/attachments/338985009/image-2026-5-19_9-55-4.png?version=1&modificationDate=1779206104580&api=v2)

![](https://confluence.churchofjesuschrist.org/download/thumbnails/338985009/image-2026-5-19_9-55-41.png?version=1&modificationDate=1779206141137&api=v2)

  

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
- Component Width 
    - Single select dropdown
    - Options are Read (672px), Pop (1024px), and Plus (1600px)
    - Default is Pop
- Image Aspect Ratio
    - Single select dropdown
    - Options are 4x1 (shortest), 2.4x1 (short), 16x9 (normal), 4x3 (tall), 1x1 (taller), 3x4 (tallest), Original
    - Default is 16x9 (normal) 
- Image Position Vertical
    - Single select dropdown
    - Options are Top and Bottom
    - Default is Top
- Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
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
- Background Color Top Padding
    
    - Single select dropdown
        
    - Options are 0px, 8px, 16px, 32px, and 64px
        
    - Default value is 32px
        
- Background Color Bottom Padding
    
    - Single select dropdown
        
    - Options are 0px, 8px, 16px, 32px, and 64px
        
    - Default value is 32px 
        

  

### States

Button Hover: Primary button background changes color, cursor turns into hand pointer. Secondary button only has the cursor turned into hand pointer.

  

### Front End Functional Requirements

- Only the button is the click target.