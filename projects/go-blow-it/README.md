# goblow.it

- **Track(s):** Public Goods + User Onboarding
- **Team/Contributors:** Coco the dog (life coach), [Manu](https://github.com/frosimanuel) (developer), [Peter](https://github.com/petermlyon) (developer), and [Paulo](https://github.com/paulofonseca1987) (designer).
![hacking goblow.it](https://i.ibb.co/Y7PqFmp0/43e92bb8-a194-45dc-903b-00bd18b1acc0.jpg)
- **Repository:** [Github repository](https://github.com/paulofonseca1987/goblow.it/tree/main/projects/go-blow-it)
- **User Flows:** [FigJam](https://www.figma.com/board/96V8WgvzTCaZWilTGMU1JR/blow-it?node-id=0-1&t=aiJEr5h2Ui0i59rD-1)
- **Design:** [Figma](https://www.figma.com/design/e3VXYvyal2h3qjdLCWQyk3/blow-it?node-id=0-1&t=VpCj1SNxeQZLXEhC-1)
- **Video:** [Youtube](https://www.youtube.com/watch?v=xvFZjo5PgG0)
- **Live App:** [goblow.it](https://goblow.it)

## Description (TL;DR)
[goblow.it](https://goblow.it) empowers whistleblowers to anonymously and securely report verifiably true Telegram messages—such as evidence of misconduct, corruption, or unethical behavior—directly to the public, all while keeping the whistleblowers identity private and fully anonymous. Users can submit a contextual report along with a zkTLS proof of the veracity of the Telegram message and receive public or private donations from anyone that cares to support their whistleblowing efforts.

## Problem
What should you do if you receive a message on Telegram (either in a DM on in a private group chat), that is abusive, incriminating, or indicative of criminal intent?

Show it to someone else?
Report it to the authorities?
Or just simply take a screenshot of it?

We can probably all agree that it is a very natural human behavior to take a screenshot of a weird/suspicious/incriminating conversation or message, just to have it as insurance, for your future self. The issue is that a screenshot is not a good and verifiable piece evidence in this day and age, given that anyone can easily fabricate a screenshot with any content whatsoever.

Also, if you report it to the authorities, you risk them confiscating your phone and access all of your other messages in there.

If you show it to someone else, you risk making them unwilling witnesses to a potential crime.

None of these options are good.

## Solution
With goblow.it you can forward any Telegram message to the Blow It! telegram bot and get a zkTLS proof that guarantees that the author, content, and timestamp of that message (at the time it was forwarded), is in fact verifiably true since that information was indeed transmitted by Telegram's servers. Then, you can publish that message publicly and anonymously, with a private and shielded wallet that can receive public or private donations from people that would like to compensate the whistleblower that leaked that verifiably true Telegram message.

## Technology Stack
We are using [TLS Notary](https://tlsnotary.org) for the zkTLS proofs, [Railgun](https://railgun.org) for the shielded and private wallets, Next.js on Vercel for the web app, Cloudflare for DNS, and a small Hetzner server for hosting everything.

## Privacy Impact
[How does this improve privacy?]

## Real-World Use Cases
[Who would use this and how?]

## Business Logic
[Sustainability/monetization considerations]

## What's Next
[Future development plans]