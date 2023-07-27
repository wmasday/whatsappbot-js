
# Whatsappbot-JS

WhatsappBOT | Send Message On Whatsapp With Javascript



## Installation

Install whatsappbot-js with npm

```bash
  cd whatsappbot-js
  npm install
  npm start

  Scan QRCode in Whatsapp Device
```
    
## Usage/Examples

```bash
client.on("message", (message) => {
  if (message.body === "!receipt") {
    return message.reply("send response");
  }
});

[!] Note : Set 'message.body' to a specific
    message as a bot trigger and 'message.reply'
    to send message.
```
