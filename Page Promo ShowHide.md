Poster Closed

![](https://confluence.churchofjesuschrist.org/download/attachments/338985055/image-2026-5-19_11-36-4.png?version=1&modificationDate=1779212164963&api=v2)

Poster Open

![](https://confluence.churchofjesuschrist.org/download/attachments/338985055/image-2026-5-19_11-36-29.png?version=1&modificationDate=1779212189877&api=v2)

Button Closed

![](https://confluence.churchofjesuschrist.org/download/attachments/338985055/image-2026-5-19_11-36-51.png?version=1&modificationDate=1779212211337&api=v2)

Button Open

![](https://confluence.churchofjesuschrist.org/download/attachments/338985055/image-2026-5-19_11-37-20.png?version=1&modificationDate=1779212240337&api=v2)

  

### Sub-Components 

Promo, modal

  

### Fields

- Internal Name (plain text, required)
- Title (tiny text, not required)
- Description (medium text, not required)
- Image (search select, not required)
    - Allows the publisher to search images and add one to the Promo.
- Text Overlay (tiny text, not required)
- CTA Button Text (tiny text, not required)
- Button Alt Text (plain text, not required)
- Hidden Content (Add Module)
    - Allows the publisher to add any module component to the hidden drawer content.
- Item (single select dropdown, not required)
    - Options are Internal, External, Modal, or No Link
    - Default is Internal
    - Internal allows the publisher to select an existing article in Brightspot.
    - External allows the publisher to add a url link to an external page. It also has fields for Link Text. External links also have an alert notification field to alert users when they are leaving the site.
    - Modal allows the publisher to add a popup modal. See the Modal component.
- Pre-title (tiny text, not required)

  

### Style Tab

- Vertical Spacing
    - Single select dropdown
    - Options are None (0px), Unite (16px), Related (32px), Separated Small (64px), Separated Large (128px), 4px, 8px, and 96px
    - Default is Separated Small (64px)
- Heading Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- Title Style
    - Single select dropdown
    - Options are H2 and H3
    - Default is H2
- Component Width 
    - Single select dropdown
    - Options are Read (672px), Pop (1024px), and Plus (1600px)
    - Default is Pop
- Hide From In Page Navigation (boolean, default to false)
- Text Overlay Vertical Alignment
    - Single select dropdown
    - Options are Top, Middle, and Bottom
    - Default is Bottom
- Text Overlay Horizontal Alignment
    - Single select dropdown
    - Options are Start, Center, and End
    - Default is Bottom
- Image Aspect Ratio
    - Single select dropdown
    - Options are 4x1 (shortest), 2.4x1 (short), 16x9 (normal), 4x3 (tall), 1x1 (taller), 3x4 (tallest), Original
    - Default is 16x9 (normal) 
- Button Style
    - Single select dropdown
    - Options are Primary, Secondary, Transparent, Standard Link, and Emphasized Link
    - Default is Primary 
- Button Alignment
    - Single select dropdown
    - Options are Start, Center, and End
    - Default is End
- Button Color
    - Single select dropdown
    - Options are Blue, Orange, and Theme Color
- Add Chevron to Button
    - boolean, default is false
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

Closed: the hidden content is not displayed

Open: the hidden content is displayed

Hover: Primary button background changes color, cursor turns into hand pointer. Secondary button only has the cursor turned into hand pointer. Hand Pointer over the rest of the tile

  

### Front End Requirements

The entire tile is the click target when opening and closing the drawer.