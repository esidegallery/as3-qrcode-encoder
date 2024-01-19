AS3 QR Code encoder is an adaptation of qrencode open source C library to as3 language. This library allow you to generate a qr code from your application (Flex, Flash, AIR) on offline mode.

# Usage
```
var qr:QRCode = new QRCode();
qr.encode("String to encode");
var bitmap:Bitmap = new Bitmap(qr.bitmapData);
```

The project is under MIT License. 