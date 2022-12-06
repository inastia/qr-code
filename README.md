# QR Code

QR code generator in JavaScript

![QR Code Project Landscape View](/img/qrcode-landscape.png "Laptop View")
![QR Code Project Mobile View](/img/qrcode-mobile.png "Mobile View")

## Code sample

The following snippet generates a save button after the QR Code image becomes visible. 
First, it gets the save url and then creates the button itself. 

```
 setTimeout(() => {
   const saveUrl = qr.querySelector('img').src;
   createSaveBtn(saveUrl);
 }, 50);
```

It's part of an if statement that performs a simple url validation.

## Design 

This project was created using:

- Tailwind CSS
- Digital Color Meter on Mac
- Free illustration "QR Code" by https://www.manypixels.co

## Project Tip

If you can't find a CDN for the package you want to use, go to https://cdnjs.com/ and look it up there. 
That's how I found 'qrcodejs' CDN that I used for this project. 
