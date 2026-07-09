- Created by  ![](https://confluence.churchofjesuschrist.org/download/attachments/49122102/user-avatar) [Jeff Mousley](https://confluence.churchofjesuschrist.org/display/~jmousley), last updated [just a moment ago](https://confluence.churchofjesuschrist.org/pages/diffpagesbyversion.action?pageId=268469075&selectedPageVersions=9&selectedPageVersions=10 "Show changes")  2 minute read

- [Common Standards for all New Components](https://confluence.churchofjesuschrist.org/spaces/CSP/pages/268469075/CCD+Web+Theme+Style+Tab+Standards#CCDWebThemeStyleTabStandards-CommonStandardsforallNewComponents)
    - [Style Tab](https://confluence.churchofjesuschrist.org/spaces/CSP/pages/268469075/CCD+Web+Theme+Style+Tab+Standards#CCDWebThemeStyleTabStandards-StyleTab)
    - [Standard Options for Images and videos](https://confluence.churchofjesuschrist.org/spaces/CSP/pages/268469075/CCD+Web+Theme+Style+Tab+Standards#CCDWebThemeStyleTabStandards-StandardOptionsforImagesandvideos)
    - [Standard Options for Lists](https://confluence.churchofjesuschrist.org/spaces/CSP/pages/268469075/CCD+Web+Theme+Style+Tab+Standards#CCDWebThemeStyleTabStandards-StandardOptionsforLists)
- [BSP Built In Breakpoints](https://confluence.churchofjesuschrist.org/spaces/CSP/pages/268469075/CCD+Web+Theme+Style+Tab+Standards#CCDWebThemeStyleTabStandards-BSPBuiltInBreakpoints)

  

## Common Standards for all New Components

Whenever we create a new component in CCD Web Theme, we need to ensure that the component has these minimum style tab options. 

### Style Tab

- Vertical Spacing
    - Single select dropdown. 
    - Options are None (0px), Unite (16px), Related (32px), Separated Small (64px), Separated Large (128px), 4px, 8px, 96px.
    - Default to Separated Small (64px).
- Heading Text Alignment
    - Single select dropdown. 
    - Options are Start, Center, End
    - Default to Start.
- Component Width (most components will be limited to specific widths)
    - Single select dropdown. 
    - Options are Read (672px), Pop (1024px), Plus (1600px), Edge (Full Screen)
    - Default to Pop. (Some components default to Read) 
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
        
    - Default to White. 
- Hide from In Page Navigation (boolean) Default to False
- Background Color Top Padding
    
    - Single select dropdown
        
    - Options are 0px, 8px, 16px, 32px, and 64px.
        
    - Default value is 32px (UX Design question)
        
- Background Color Bottom Padding
    
    - Single select dropdown
        
    - Options are 0px, 8px, 16px, 32px, and 64px.
        
    - Default value is 32px (UX Design question)
        

### Standard Options for Images and videos

- Select a size for the media
    - Single select dropdown. 
    - Options are Small (403px), Medium (538px), Large (672px)
    - Default to Medium. 
- Image Aspect Ratio
    - Single select dropdown. 
    - Options are 4x1 (shortest), 2.4x1 (short), 16x9 (normal), 4x3 (tall), 1x1 (taller), 3x4 (tallest), Original
    - Default to 16x9 (normal) 

### Standard Options for Lists

- Hide Descriptions (boolean)
- Choose the CTA Button Placement
    - Single select dropdown. 
    - Options are Start, Center, End
    - Default to Start.
- Choose how many columns would you like
    - Single select dropdown. 
    - Options are 2, 3, 4, 5, 6
    - Default to 3.
- Image Shape (not on all Lists)
    - Single select dropdown. 
    - Options are 16x9 (wider), 1x1 (circle), 1x1 (square), 
    - Default to 16x9 (wider) 
- List Items Title & Description Alignment
    - Single select dropdown. 
    - Options are Start, Center, End
    - Default to Start. 
- Hide Images (boolean)
- Prevent pagination controls from displaying on this list (boolean)
- Image Position Horizontal (not on all Lists)
    - Single Select dropdown.
    - Options are Left and Right
    - Default to Left.

  

## BSP Built In Breakpoints

568px; (mobile)

@md-width: 768px; (tablet)

@lg-width: 1024px; (landscape tablet / small desktop)

@hk-width: 1280px; // husky (bigger desktop/laptops)

@xl-width: 1440px; big screens