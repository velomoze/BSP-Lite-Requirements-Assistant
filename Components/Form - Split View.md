![](https://confluence.churchofjesuschrist.org/download/attachments/338985470/image-2026-5-20_13-0-6.png?version=1&modificationDate=1779303606253&api=v2)

![](https://confluence.churchofjesuschrist.org/download/attachments/338985470/image-2026-5-20_13-0-34.png?version=1&modificationDate=1779303634343&api=v2)

### Sub-components Used

None.

  

### Fields

- Internal Name (plain text, required)
- Title (tiny text, required)
- Description (medium text, not required)
- Items (dropdown select, required)
    - Options are: 
        - Captcha Field
        - Choice Field
        - Data Input
        - Dynamic Hidden Field
        - File Upload Field
        - Group
        - Hidden Field
        - Lookup Hidden Field
        - Missionary Address Field
        - Missionary Country Choice Field
        - Missionary Email Field
        - Missionary Phone Number Field
        - Text Field
        - Text Only Field
- Legal Notices (multi-select drop down, not required)
    - Options are Messaging Terms, Privacy Policy, Rights and Use, Accessibility Policy, and reCAPTCHA
- Actions (dropdown select, required)
    - Options are Data Collection Action, Email Action, External JSON Submit Action, External Missionary JSON Submit Action, and External Submit Action
- Cta Button Text Override (small text, not required)
- Cta Button Description (small text, not required)
- Background Image (search select, not required)
- Success Message (small text, not required)
- Error Message (small text, not required)

  

Captcha Field

- Label (tiny text, required)
- Description (medium text, not required)
- Style tab option: Invisible Captcha (boolean, default is false)

Choice Field

- Label (tiny text, required)
- Description (medium text, not required)
- Type (single select dropdown, required)
    - Options are Dropdown, Checkboxes, and Radio Buttons
        - Dropdown fields:
            - Allow Multiple? (boolean, default is false)
            - Placeholder (plain text)
            - Required? (boolean, default is false)
        - Checkboxes fields:
            - Label (small text, required)
            - Style Options:
                - Number of columns for this field set
                    - Single select dropdown
                    - Options are Full Width, 50/50, 33/33/33, 50/25/25, 25/25/50, and 25/25/25/25.
                    - Default is Full Width
                - Hide Title (boolean, default is false)
                - Display Group as Drawer (boolean, default is false)
                - Render Drawer as Expanded (boolean, default is false)
        - Radio Button fields:
            - Label (small text, required)
            - Style Options:
                - Number of columns for this field set
                    - Single select dropdown
                    - Options are Full Width, 50/50, 33/33/33, 50/25/25, 25/25/50, and 25/25/25/25.
                    - Default is Full Width
                - Hide Title (boolean, default is false)
                - Display Group as Drawer (boolean, default is false)
                - Render Drawer as Expanded (boolean, default is false)

Date Input field

- Label (tiny text, required)
- Description (medium text, not required)
- Required (boolean, default is false)

Dynamic Hidden Field

- Name (plain text, required)
- Dynamic Source
    - Single select dropdown
    - Options are Document.Referrer, HTTP Cookie, Query Parameter, and Transaction ID
    - Default is Document.Referrer

File Upload Field

- Label (tiny text, required)
- Description (medium text, not required)
- Allowed File Types
    - Multi-add search dropdown
    - Options are Image, Video, Audio, and Any File Type
- Allow Multiple? (boolean, default is false)
- Required? (boolean, default is false)

Group Fields

- Title (tiny text, not required)
- Description (medium text, not required)
- Items 
    - Single select dropdown
    - Options are all the field types listed above.
    - Multiple fields can be added to a group.
- Style Options:
    - Number of columns for this field set
        - Single select dropdown
        - Options are Full Width, 50/50, 33/33/33, 50/25/25, 25/25/50, and 25/25/25/25.
        - Default is Full Width
    - Hide Title (boolean, default is false)
    - Display Group as Drawer (boolean, default is false)
    - Render Drawer as Expanded (boolean, default is false)

Hidden Field

- Name (plain text, required)
- Value (plain text, not required)

Lookup Hidden Field

- Option Type
    - Single select dropdown
    - Options must match option type specified in Field Lookup Configuration in the site settings
- Choice
    - Single select dropdown
    - Options are populated from another system specified in the Field Lookup Configuration

Missionary Address Field

- Label (tiny text, required)
- Description (medium text, not required)
- Placeholder (plain text, not required)
- Required? (boolean, default is false)

Missionary Country Choice Field

- Label (tiny text, required)
- Description (medium text, not required)
- Placeholder (plain text, not required)
- Required? (boolean, default is false)

Missionary Email Field

- Label (tiny text, required)
- Description (medium text, not required)
- Legal Checkboxes (Add one or more checkboxes, not required)
    - Label (small text, required)
- Placeholder (plain text, not required)
- Required? (boolean, default is false)

Missionary Phone Number Field

- Label (tiny text, required)
- Description (medium text, not required)
- Legal Checkboxes (Add one or more checkboxes, not required)
    - Label (small text, required)
- Placeholder (plain text, not required)
- Required? (boolean, default is false)

Text Field

- Label (tiny text, required)
- Description (medium text, not required)
- Type (single select dropdown, required)
    - Options are Short Text, Address, Email, Long Text, Phone Number
    - Default is Short Text
    - Address has option: Use My Location? (boolean, default is false)
    - Email has option: External Validation URL (plain text, not required) and option: Legal Checkboxes (add one or more checkboxes, not required)
- Placeholder (plain text, not required)
- Required? (boolean, default is false)

Text Only Field

- Internal Label (tiny text, required)
- Rich Text (small text, required)

  

  

### Style Tab

- Hide Title (boolean, default is false)
- Title style
    - Single select drop down
    - Options are H2 and H3
    - Default is H2
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
    - Options are Read (768px), Pop (1024px), Plus (1600px), and Edge (100%)
    - Default is Read (768)
- Choose the CTA Button Placement
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- Hide from In Page Navigation (boolean, default is false)
- Hide Field Labels (boolean, default is false)
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
        
- CTA Button Color
    - Single select dropdown
    - Options are Primary Blue, Christmas Red, Easter Purple, and Missionary Orange
    - Default is Primary Blue
- Text Alignment
    - Single select dropdown
    - Options are Start, Center, End
    - Default is Start
- Image Position Horizontal
    - Single select dropdown
    - Options are Left and Right
    - Default is Left.

  

### States

Error: The field with missing or bad data is highlighted in red and a message appears below the field in red text.

Successfully submitted: the form is replaced with the Success Message.

Active field: Blinking cursor in the field. Placeholder text is replaced once the user begins typing.

  

### Front End Requirements

- Legal notices appear as links below all the fields on the form.
- Default button text is "Submit".
- Missionary fields are used only for missionary forms.
- Submission actions:
    - External Submit Action - enter a url where the data is sent the the user is redirected to that url when submitted. The data is sent as comma delimited data.
    - Email Action - the publisher enters an email address to send the data to. The publisher formats the Subject and email body fields using variables.
    - External JSON Submit Action - same as External Submit Action but the data is in JSON format.
    - External Missionary JSON Submit Action - Submits directly to the Missionary API endpoints. Data is in JSON format.
    - Data Collection Action - doesn't have any fields. Needs a database setup and a connection to the database.