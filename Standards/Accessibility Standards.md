This example is for a component that opens a modal popup that floats over the page and displays secondary content.

### Accessibility Requirements

- The modal container **must be programmatically identified as a dialog** using:
    
    - Native `<dialog>` element **OR**
        
    - `role="dialog"` (or `role="alertdialog"` when appropriate)
        
- The modal **must have an accessible name**, provided by:
    
    - `aria-labelledby` referencing a visible modal heading, or
        
    - `aria-label` if a visible heading is not present
        
- If descriptive text is present, it **must be associated** using `aria-describedby`
    
- If a modal pattern is used (blocking background interaction), `aria-modal="true"` **must be applied** (or native dialog behavior used)
    
- Modal content **must not rely on visual cues alone** to convey its purpose or instructions
    

- When the modal opens:
    
    - Keyboard focus **must move into the modal automatically**
        
    - Initial focus **must land on the first meaningful interactive element** or the modal heading
        
- While the modal is open:
    
    - Focus **must be trapped within the modal**
        
    - Users **must not be able to tab to background page content**
        
- When the modal closes:
    
    - Focus **must return to the element that triggered the modal** (CTA or page promo)
        
- The modal **must not create a keyboard trap**:
    
    - Users must always be able to exit the modal using keyboard controls
        

- The modal **must provide a visible, keyboard‑accessible Close control**
    
- The Close control:
    
    - Must be reachable via keyboard
        
    - Must have an accessible name (e.g., “Close dialog”)
        
- The modal **must close when the Escape key is pressed**, unless Escape would cause loss of data (then provide clear alternatives)
    
- If clicking the overlay closes the modal:
    
    - This behavior **must be optional** and not the only dismissal method
        

- When the modal is open:
    
    - Background content **must not be focusable**
        
    - Background content **must not be exposed to assistive technologies**
        
- This can be achieved via:
    
    - Native `<dialog>` behavior, **or**
        
    - `aria-modal="true"` with proper focus management (no `aria-hidden` misuse)
        
- Page scrolling behind the modal **must be disabled** to prevent disorientation
    

- All interactive elements inside the modal **must display a visible focus indicator**
    
- Focus indicators:
    
    - Must meet contrast requirements
        
    - Must not be removed or suppressed without an accessible alternative
        
- Focus must never be visually hidden by modal chrome or overlays
