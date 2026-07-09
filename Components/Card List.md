Most common use case, closed state.

![](https://confluence.churchofjesuschrist.org/download/attachments/309299888/image-2025-12-30_13-31-23.png?version=1&modificationDate=1767126683267&api=v2)

Most common use case, open state.

![](https://confluence.churchofjesuschrist.org/download/attachments/309299888/image-2025-12-30_13-31-41.png?version=1&modificationDate=1767126701437&api=v2)

As a grid of links.

![](https://confluence.churchofjesuschrist.org/download/attachments/309299888/image-2026-5-14_13-22-48.png?version=1&modificationDate=1778786568837&api=v2)

Showing mixed tiles with and without images.

![](https://confluence.churchofjesuschrist.org/download/attachments/309299888/image-2026-5-14_13-23-22.png?version=1&modificationDate=1778786602210&api=v2)

Mobile view with horizontal tile

![](https://confluence.churchofjesuschrist.org/download/attachments/309299888/image-2026-5-14_14-0-30.png?version=1&modificationDate=1778788830437&api=v2)

  

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
- Choose how many columns would you like
    - Single select dropdown
    - Options are 2, 3, and 4
    - Default is 3
- Vertical Spacing
    - Single select dropdown
    - Options are None (0px), Unite (16px), Related (32px), Separated Small (64px), Separated Large (128px), 4px, 8px, and 96px
    - Default is Separated Small (64px)
- Component Width 
    - Single select dropdown
    - Options are Read (672px) and Pop (1024px)
    - Default is Read
- Heading Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- List Items Title & Description Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- Background Color
    - Single select dropdown. 
    - Options are
        - White
        - Light Gray
        - Blue (MS Use Only)
            
        - Dark Blue (MS Use Only)
            
        - Light Yellow (MS Use Only)
            
        - Medium Gray (MS Use Only)
            
        - Dark Gray (MS Use Only)
            
    - Default isWhite
- Background Color Top Padding
    
    - Single select dropdown
        
    - Options are 0px, 8px, 16px, 32px, and 64px
        
    - Default value is 32px
        
- Background Color Bottom Padding
    
    - Single select dropdown
        
    - Options are 0px, 8px, 16px, 32px, and 64px
        
    - Default value is 32px 
        
- Show All List Items? (boolean, default to false)
- Mobile Style
    - Single select dropdown
    - Options are Horizontal Tile and Vertical Tile
    - Default is Horizontal Tile

  

### States

Hover: small zoom on image

  

### Front End Functional Requirements

- Display one row of results with a See All link to expand to show all results.
- If the Show All List Items? is set to true, show all items and do not show a See All link.
- Below the Tablet breakpoint (768px) the display changes to the selected Mobile Style (Horizontal Tile or Vertical Tile).