# MailParser with iso-2022-jp support

Original project here: https://github.com/nodemailer/mailparser

## Install

```bat
npm install @kenjiuno/mailparser-with-iso2022jp
```

## Changes

Since [mailparser](https://github.com/nodemailer/mailparser),

Using [encoding-japanese](https://www.npmjs.com/package/encoding-japanese) for iso-2022-jp decoding.

### What's wrong with `mailparser-iconv-full2`

[mailparser-iconv-full2](https://www.npmjs.com/package/mailparser-iconv-full2) uses [Node.js Addons](https://nodejs.org/api/addons.html).

`@kenjiuno/mailparser-with-iso2022jp` is Node.js Addons free.

No native DLLs are included.
