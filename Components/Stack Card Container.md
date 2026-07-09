![](https://confluence.churchofjesuschrist.org/download/attachments/309300418/image-2026-5-20_13-37-52.png?version=1&modificationDate=1779305872267&api=v2)

![](https://confluence.churchofjesuschrist.org/download/attachments/309300418/image-2026-5-20_13-32-25.png?version=1&modificationDate=1779305545253&api=v2)

  

### Sub-components Used

None

  

### Fields

- Title (tiny text, required)
- Sub Title (tiny text, required)
- Card Stacks (Add Stack)
    - Stack:
        - Stack Title (tiny text, required)
        - Stack (Add Stack Card)
            - Title (tiny text, required)
            - Primary Image (search select, not required)
            - Body (small text, not required)
            - Action Text (plain text, not required)
- Flip All Cards Button Text (tiny text, not required)

  

### Style Tab

- Vertical Spacing
    - Single select dropdown
    - Options are None (0px), Unite (16px), Related (32px), Separated Small (64px), Separated Large (128px), 4px, 8px, and 96px
    - Default is Separated Small (64px)
- Hide Container Title (boolean, default is false)
- Hide List Title (boolean, default is false)
- Image Size
    - Single select dropdown
    - Options are Small (square icon) and Large (full width)
    - Default is Large (full width)
- Heading Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- Component Width 
    - Single select dropdown
    - Options are Read (672px), Pop (1024px), and Plus (1600px)
    - Default is Pop
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
        
- Animate this module on scroll? (boolean, default is false)
- Display a Button to Flip All Cards? (boolean, default is false)
- Choose Style for the Flip All Cards Button
    - Single select dropdown
    - Options are Primary and Secondary
    - Default is Secondary
- Show a back button on Cards? (Will disable randomization if selected) (boolean, default is false)
- Card Color
    - Single select dropdown
    - Options are White, Blue, Red, Purple, and Orange
    - Default is White
- Card Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- Card Minimum Height
    - Single select dropdown
    - Options are Dynamic, Large (350px), Medium (263px), and Small (120px)
    - Default is Large (350px)
- Randomize the Order of the Cards (does not work with back button) (boolean, default is false)
- Display Counter (only available in IPS headless Brightspot)
    - Boolean, default to false

### States

Hover: Image zoom, hand pointer cursor.

  

### Front End Requirements

- Selecting a tile will flip the card and show the next card. There can be many cards in each stack of tiles.
- When the Randomize the Order of the Cards is set to true, selecting a tile will randomly select one of the cards in the stack to display.
- Selecting the Flip All Cards button will flip all the stacks at once. Typically used in conjunction with the Randomize the Order of the Cards.
- Animate this module on scroll will flip all stacks when the component comes into the viewport.