# SafeMesh · Harmony Innovation Summit 2026, Prague

**Format:** 3 minutes, 2 slides. **Audience:** senior management from Huawei HQ (Consumer BG Software Engineering), most likely Chinese, listening in English as a second language.
**Deck:** `Harmony Innovation Summit 2026 - SafeMesh.pptx`. The speech below is also in the speaker notes.

The script is about 300 words. Spoken slowly with pauses, that's about 2:40, which leaves you a small safety margin.

---

## Slide 1: the problem and what SafeMesh is (≈1:30)

<!-- notes:slide1 -->

> Good morning. Thank you very much for this invitation, and congratulations to all the teams.
>
> My name is Tomasz, and I represent Carrotly, a team of creative engineers from Kraków, in Poland. At the HackYeah hackathon we built SafeMesh, and it won second place in the Huawei challenge.
>
> Imagine a crisis in your city: a flood, a blackout, or a drone strike. The cell towers go down, and your phone shows only one thing: "no service". In a critical situation without clear guidance, people panic, rumours spread, and everything quickly turns into chaos. This is exactly when we need a reliable emergency alert system. But today, government alerts mostly come through the mobile network. Without towers, they cannot arrive.
>
> SafeMesh solves this. It is one native HarmonyOS app, built in twenty-four hours, with three ideas that only work together. Signed alerts, checked on the phone with the Crypto Architecture Kit. A phone-to-phone relay, with a NearLink Kit adapter. And an offline map with protective points near the user's location.

<!-- /notes -->

_Pause after "no service". When you name the three ideas, point at the phone: the verified alert, "Connected · NearLink", then the map._

## Slide 2: how it works and what's next (≈1:10)

<!-- notes:slide2 -->

> Here is how it works. An official issuer sends a digitally signed warning to the devices in range, using NearLink. Phone A receives it and passes it on to the devices in its own range, like phone B. Then B passes it further to C. Every phone checks the signature by itself. If someone changes even one bit of the message, the signature breaks, and the phone rejects it and drops it from the network. C was never near the source, yet it still gets a warning it can trust.
>
> Our next step would be to extend SafeMesh beyond NearLink, to Bluetooth and Wi-Fi, and to test NearLink on real phones. We would be very happy to do it together with Huawei.
>
> The network can fail. The warning still arrives.
>
> Thank you very much.

<!-- /notes -->

_Point at the diagram as you say "Phone A… B… C". The closing line matches the text on the slide; say it slowly. After "Thank you very much", stop, smile and give a small nod. Don't add anything else._

---

## Delivery

- **Speak slowly,** slower than feels natural. Short sentences and simple words help listeners who work in a second language.
- **Pause** after: "no service", "SafeMesh solves this", "a warning it can trust", and before "The network can fail".
- **Numbers:** say "twenty-four hours", not "24h". "NearLink" is fine; it's Huawei's own name. You can also say "Xīngshǎn" (星闪) once, if you're confident with the pronunciation.
- **Thank them first, then the most senior person.** Greet the most senior person first if you're introduced or shake hands.
- **Rehearse with a timer** at least 3 times, out loud and standing. Cut sentences if you go over 3:00. It's better to finish early.

## Making Carrotly known (without selling)

The pitch already does the quiet work:

- **Your intro names the company and city** ("I represent Carrotly, a team of creative engineers from Kraków").
- **Slide 2 shows "Team Carrotly, Kraków, Poland"**, and the QR code goes to `github.com/carrotly-technologies-2026/SafeMesh`, so the company name is in the link too.
- **The only "ask"** is a natural, project-level one: testing on real NearLink phones together with Huawei. That's a reason for them to talk to you afterwards, without asking for contracts.

After the ceremony:

- **Business cards:** hand them over and receive theirs **with both hands**. Look at the card you receive for a moment before putting it away.
- **Gadgets:** give them at the end, never during the formal part, and keep them modest. Avoid sets of four, which are unlucky in Chinese culture, and avoid clocks.
- **One-line answer when someone asks "What does Carrotly do?":** "We're a software team from Kraków. We build mobile and web apps, and now HarmonyOS. SafeMesh shows how fast we can go from an idea to a working native app."
- **Follow up** by email within 1–2 days: thank them, attach the deck, mention the NearLink test idea, and add your contact details.

## If someone asks a question

- **Has it been tested on real phones?** "Not yet. The emulators have no radio, so the NearLink adapter is tested with mocks. The physical test is our next step, and we have a written test plan."
- **Who would send the alerts?** "Authorised public-safety organisations, like crisis teams or fire brigades. In the prototype it's an exercise issuer, not the real government system."
- **What if the issuer's key is stolen?** "Then fake alerts could be signed. A real deployment needs secure key storage and key rotation. That is on our roadmap."
- **Why NearLink?** "It is HarmonyOS's own short-range radio, built into new Huawei phones. The transport sits behind one interface, so Bluetooth and Wi-Fi are our next step."
- **If you don't understand a question:** "Sorry, could you repeat the question, please?" It's completely fine to ask.

## Before Friday, 9 October

- [ ] Review both slides and this speech, and tell me what to change.
- [ ] Check the Chinese lines on the slides with a native speaker if you can: "网络中断时，预警依然送达" (_When the network goes down, the warning still arrives_) and "原生鸿蒙应用 · 支持星闪近距离通信" (_Native HarmonyOS app · supports NearLink short-range communication_).
- [ ] Send the `.pptx` to Jarek, JiaYi MA and Wang Kai, all in one reply.
