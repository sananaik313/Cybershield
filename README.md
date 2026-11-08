# Cyber Shield

**An interactive scam simulator for digital financial safety in India.**

Cyber Shield is a web-based educational game that trains people to recognise and avoid online financial scams. It is designed especially for senior citizens, rural communities and new internet users. Instead of reading a long cyber-safety document, players learn by playing: they see realistic simulated messages and must decide whether to report them or trust them.

**Play the game:** https://YOUR-USERNAME.github.io/cyber-shield/

## How it works

1. The player enters a name and chooses a quick round (5 messages) or a full round (10 messages).
2. The player starts with **100 Trust Points**.
3. A simulated phone screen shows a message, such as an SMS about an unpaid electricity bill or a WhatsApp message about a lottery win.
4. The player taps **Report / Block** or **Trust / Proceed**.
5. The game gives instant feedback. If a scam fools the player, **25 Trust Points** are lost. The red flags are highlighted on the message, with a plain explanation of each and a tip on what to do.
6. At the end, the player sees a final score, the Trust Points left and a safety rating.

| Rating | Correct answers |
|---|---|
| Cyber Expert | 90% or more |
| Getting Sharper | 60% to 89% |
| Highly Vulnerable | Below 60% |

## Scenarios included

The game has 10 messages: 7 scams and 3 genuine messages.

**Scams**
- Electricity bill threat SMS
- KBC lottery WhatsApp message
- Wrong UPI payment refund request
- KYC update app (.apk) SMS
- "Digital arrest" video call threat
- Work-from-home job with a registration fee
- Scan a QR code to "receive" money

**Genuine messages**
- Bank pension credit alert
- Electricity bill notice
- Clinic appointment reminder

All phone numbers are masked, and the banks and offices shown are made up.

## Features

- Runs fully in the browser. No installation, server or database is needed.
- No personal data leaves the device.
- Large text, high contrast and big buttons for easy use by elderly people.
- Works on phones and computers, in light and dark mode.
- Mixes genuine messages with scams, so players learn what a real message looks like.
- Saves the count of rounds played and the scams that fooled the player, on the same device only.

## Built with

- HTML
- CSS
- JavaScript (no libraries)

## Project structure

The whole game is a single file, `index.html`.

- **Data layer:** a JavaScript array stores each message with its sender, text, whether it is a scam, its red flags and a tip.
- **Logic layer:** functions build a round, check the player's choice, update the Trust Points and work out the rating.
- **View layer:** HTML and CSS show each screen without reloading the page.

## Run it on your computer

Download `index.html` and open it in any web browser.

## Future work

- Hindi and Marathi versions
- Voice option that reads each message aloud
- Shared online database to see which scams fool the most people
- More scenarios, such as fake courier messages and loan-app threats
- Mobile app version

## If you are scammed

Call the National Cyber Crime Helpline **1930** or report at [cybercrime.gov.in](https://cybercrime.gov.in). Inform your bank at once. A quick report gives the best chance of stopping a transfer.

## Author

Created by **Sana Naik**, First Year Computer Engineering, Shri Anandrao Abitkar College of Engineering, Pal.
