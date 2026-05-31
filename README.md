# QR Generator Project

## What this project does
This project creates a QR code from a link or text using AWS Lambda.

The QR image is saved in S3 and a link is generated.

---

## Input example
```json
{
  "text": "https://google.com"
}
 output a image like this base on nwhat you give in test event example of my qr code generator
https://my-qr-code-ran.s3.ap-south-1.amazonaws.com/2a587d65-8868-42d4-8c24-6e9e3dcce037.png
