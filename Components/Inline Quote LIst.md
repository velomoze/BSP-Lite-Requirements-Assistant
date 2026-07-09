![](https://confluence.churchofjesuschrist.org/download/attachments/309300322/image-2025-12-31_13-31-54.png?version=1&modificationDate=1767213114427&api=v2)

![](https://confluence.churchofjesuschrist.org/download/attachments/309300322/image-2026-5-14_15-48-2.png?version=1&modificationDate=1778795282787&api=v2)

### Sub-components used

Quote

  

### Fields

- Title (tiny text, not required)
- Items (single select dropdown, required)
    - Options are Basic and Advanced
    - Default is Basic
    - Basic allows the publisher to select an internal link to an article in Brightspot, an external link to a url, and a modal popup.
    - Advanced allows the publisher to create a Quote.
- Add Item (search select, required)
- Call to Action (single select dropdown, not required)
    - Options are None, External Reference, Internal Reference, Modal, and Site Search
    - Defaults to None.
- Call to Action Button Text (tiny text, not required)

### Style Options

- Vertical Spacing
    - Single select dropdown
    - Options are None (0px), Unite (16px), Related (32px), Separated Small (64px), Separated Large (128px), 4px, 8px, and 96px
    - Default is Separated Small (64px)
- Heading Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- Component Width 
    - Single select dropdown
    - Options are Read (672px), Pop (1024px), and Plus (1600px)
    - Default is Read
- Image Shape
    - Single select dropdown
    - Options are Circle and Square
    - Default is Circle
- Image Highlight Color
    - Single select dropdown
    - Options are White, Blue, Orange (MS Only)
    - Default is Blue
- Hide From In Page Navigation (boolean, default to false)
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
        
- Change Primary Text Color to Primary Inverse Text color (boolean, default to false)
- Hide Image Labels (boolean, default to false)

  

### States

Selected: image is circled with the highlight color, image is clear. Other images are shaded. Image label is bold.

  

### Front End Functional Requirements

- Selecting an image from the list will display the quote and attribution for that item. 
- If there are more items than will fit in the width of the component, the list turns into a carousel.