## ![](https://confluence.churchofjesuschrist.org/download/attachments/338985335/image-2026-5-20_9-32-24.png?version=1&modificationDate=1779291144873&api=v2)

![](https://confluence.churchofjesuschrist.org/download/thumbnails/338985335/image-2026-5-20_9-32-53.png?version=1&modificationDate=1779291173597&api=v2)

  

### Sub-components used

Promo

### Fields

- Title (tiny text, not required)
- Description (tiny text, not required)
- Items (single select dropdown, required)
    - Options are Basic, Advanced, and Dynamic
    - Default is Basic
    - Basic allows the publisher to select an internal link to an article in Brightspot, an external link to a url, and a modal popup.
    - Advanced allows the publisher to create a Promo.
    - Dynamic allows the publisher to create a query to find the articles to display in the list.
- Add Item (search select, required)
- Call to Action (single select dropdown, not required)
    - Options are None, External Reference, Internal Reference, Modal, and Site Search
    - Defaults is None
- Call to Action Button Text (tiny text, not required)

### Style Options

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
- Vertical Spacing
    - Single select dropdown.
    - Options are None (0px), Unite (16px), Related (32px), Separated Small (64px), Separated Large (128px), 4px, 8px, and 96px
    - Default is Separated Small (64px)
- Heading Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- Component Width 
    - Single select dropdown. 
    - Options are Read (672px), and Pop (1024px)
    - Default is Pop
- Image Aspect Ratio
    - Single select dropdown
    - Options are 16x9 (wide) and 3x4 (tall)
    - Default is 3x4 (tall)
- Text Alignment
    - Single select dropdown. 
    - Options are Start, Center, End
    - Default is Start
- Hide Image (boolean, default to false)

  

### States

Button Hover: Primary button background changes color, cursor turns into hand pointer. Secondary button only has the cursor turned into hand pointer.

  

### Front End Functional Requirements

- Button is to download the attached file, not a link to a page.