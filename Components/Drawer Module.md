![](https://confluence.churchofjesuschrist.org/download/attachments/309300327/image-2025-12-31_13-45-45.png?version=1&modificationDate=1767213946020&api=v2)

![](https://confluence.churchofjesuschrist.org/download/attachments/309300327/image-2025-12-31_13-46-7.png?version=1&modificationDate=1767213967357&api=v2)

  

### Sub-components used

Rich Text, Figure, Video, List

  

### Fields

- Title (tiny text, not required)
- Description (tiny text, not required)
- Drawer Content (single select dropdown, not required)
    
    - Options are None, Drawer, FAQ, Enhanced Drawer, and Notes.
        
    - Default to None
    - Drawer fields:
        - Label (small text, required)
        - Body (large text, required)
    - FAQ fields:
        - Question (small text, required)
        - Answer (large text, required)
    - Notes fields:
        - Label (small text, required)
        - Body (large text, required)
    - Enhanced Drawer fields:
        - Label (small text, required)
        - Module (single select dropdown, required)
            - Options are Figure, Rich Text, Video, and List
            - Default to Figure
            - Each option displays the fields of that component, including the Styles tab for that component.
- Call to Action (single select dropdown, not required)
    - Options are None, External Reference, Internal Reference, Modal, and Site Search
    - Defaults to None.
- Call to Action Button Text (tiny text, not required)

  

### Style Options

- Component Width 
    - Single select dropdown
    - Options are Read (672px), Pop (1024px), Plus (1600px), Edge (Full Screen)
    - Default is Read
- Vertical Spacing
    - Single select dropdown.
    - Options are None (0px), Unite (16px), Related (32px), Separated Small (64px), Separated Large (128px), 4px, 8px, and 96px
    - Default is Separated Small (64px)
- Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- Choose the CTA Button Placement
    - Single select dropdown
    - Options are Start, Center, and End
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
        
- Hide Descriptions (boolean, default to false)

  

Each item in the drawer has its own Style Options.

- Check to expand this item by default (boolean, default to false)
- Drawer Item Label Alignment 
    - Single select dropdown
    - Options are Start, Center, and End
    - Default to Start

  

### States

Closed: chevron points down.

Closed Hover: drawer label is underlined and chevron turns black.

Open: chevron points up and drawer contents are displayed.

Open Hover: gray background around the drawer label.

  

### Front End Functional Requirements