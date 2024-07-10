# QR Code Generator
 it will generate random qr-code by just writing text, name or giving url

 Api i used for qr code i copied from site called:
https://goqr.me/api/

There you will be able to see "Call the URL" and by copying this "https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=" and adding it into js it will be possible to generate random qr-code. Just make sure to get rid of "=Example" written at the end.
_____________________________________________________________________________________________________________________________________________

Animation was added for more comfortable use. If nothing is written in Text or URL then it will shake the box and focus will be on the box.
For this i used this in CSS:

.error{
    animation: shake 0.1s linear 10;
}
@keyframes shake{
    0%{
        transform: translateX(0);
    }
    25%{
        transform: translateX(-2px);
    }
    50%{
        transform: translateX(0);
    }
    75%{
        transform: translateX(2px);
    }
    100%{
        transform: translateX(0);
    }
    
}

And in JS added if, else conditions which will be visible in innerhtml's js. 
