# QR-code-generator
This is a simple QR code generator built using HTML, CSS, and JavaScript. 

The code creates:

- An input field where the user can enter text or a URL  
- A button to generate the QR code

When the button is clicked, the `generateQR()` function is called, which:

1. Checks if the input field is not empty
    - If it is **not empty**, the function generates a QR code using the entered text or URL and displays it in an `<img>` element
    - If the input field **is empty**, the function
        - Adds an `error` class to the input field
        - Removes the `error` class after 1 second
        
2. Uses CSS to style the elements and make the image element visible when a QR code is generated
