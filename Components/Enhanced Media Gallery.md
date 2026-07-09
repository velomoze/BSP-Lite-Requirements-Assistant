![](https://confluence.churchofjesuschrist.org/download/attachments/309299912/image-2025-12-30_13-40-20.png?version=1&modificationDate=1767127220213&api=v2)

![](https://confluence.churchofjesuschrist.org/download/attachments/309299912/image-2026-5-14_14-51-46.png?version=1&modificationDate=1778791906967&api=v2)

  

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
    - Defaults to None.
- Call to Action Button Text (tiny text, not required)

### Style Options

- Hide Descriptions (boolean, default to false)
- Choose the CTA Button Placement
    - Single select dropdown
    - Options are Start, Center, and End
    - Default is Start
- Hide From In Page Navigation (boolean, default to false)
- Component Width 
    - Single select dropdown 
    - Options are Read (672px) and Pop (1024px)
    - Default is Read
- Vertical Spacing
    - Single select dropdown
    - Options are None (0px), Unite (16px), Related (32px), Separated Small (64px), Separated Large (128px), 4px, 8px, and 96px
    - Default to Separated Small (64px)
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

  

### Front End Functional Requirements

- Selecting an item from the list opens a lightbox with the full size version of the media.
- The lightbox has controls to play a video, move to the next or previous item in the gallery, see a grid view of all the items in the gallery, and a close button.