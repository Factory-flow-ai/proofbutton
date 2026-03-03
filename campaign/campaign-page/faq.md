# ProofButton Comprehensive FAQ

20+ frequently asked questions covering all aspects of ProofButton from technology to fulfillment.

---

## How It Works Questions

### Q: How does ProofButton power itself without batteries?

**A:** ProofButton uses kinetic energy harvesting—a patented mechanism inside the button captures the mechanical energy from you pressing it and converts it into electrical power. Think of it like a wind-up toy, except it powers itself with every press. The energy is then used to send a wireless signal to your smart home. No batteries, ever.

---

### Q: Do I really never need to replace the battery?

**A:** Correct. Never. The button powers itself kinetically with every press. As long as your finger can press the button, it will work. We've tested the mechanism for 500,000+ presses, which is 100+ years of daily use. The kinetic mechanism has a 5-year warranty.

---

### Q: What happens if the kinetic power runs out mid-press?

**A:** It won't. The kinetic mechanism harvests energy continuously as you press. If somehow the wireless transmission doesn't complete (extremely rare), pressing again instantly triggers it. The mechanism doesn't "run out" like a battery—it works based on the physical press, not stored charge.

---

### Q: How long does each ProofButton last?

**A:** Based on our testing and similar kinetic technology (watch movements, mechanical clickers), we estimate 5+ years of reliable daily use. We warranty the hardware for 5 years against manufacturing defects. The wireless component should last similarly. After 5+ years, the button may wear, but it should still function. Compare to traditional smart buttons that need battery replacement every 1-2 years.

---

### Q: Is the button weatherproof?

**A:** Yes, ProofButton is IP67 equivalent weatherproof, meaning it can handle:
- Splashes and light rain
- Brief submersion (not extended underwater)
- Dust and dirt (sealed against most particles)
- Safe for indoor/outdoor use

This makes it suitable for kitchens, bathrooms, garages, or even exterior mounting (with proper housing).

---

## Smart Home Integration Questions

### Q: What smart home systems does it work with?

**A:** Currently shipped with:
- **Alexa** (native integration)
- **Google Home** (native, included at $50K stretch goal)
- **Home Assistant** (native, full featured)
- **Matter** (planned, stretch goal at $75K)
- **Apple HomeKit** (via Matter, stretch goal)
- **IFTTT** (100+ service integrations)

We design for open protocols, not vendor lock-in. If your system isn't listed, ask—we likely support it via IFTTT or have plans to.

---

### Q: Do I need the hub?

**A:** Short answer: Recommended but not always required.

**With Hub (Recommended):**
- Faster response time (local automation)
- More reliable (Zigbee > Bluetooth)
- Larger range (100+ feet through walls)
- Works everywhere in your home
- Enables advanced automations
- Required for Home Assistant integration

**Without Hub (WiFi version, future):**
- Direct WiFi connection
- Larger range (anywhere you have WiFi)
- Slightly slower setup

For most users, the hub is worth it. It costs $30-35 and enables everything ProofButton can do.

---

### Q: Can I use ProofButton without smart home?

**A:** Yes, ProofButton still works as a standalone button, but you lose the "smart" part. You'll:
- Feel the kinetic press (satisfying)
- Hear the wireless signal send (confirmation)
- But no automation triggered (no hub = no connected action)

The real value comes from smart home integration. A non-connected button is just a button. We recommend the hub.

---

### Q: What's the range of the wireless signal?

**A:** Depends on the connection method:

**Zigbee (via hub):** 50-100+ feet through walls. Zigbee uses mesh networking, so if you have other Zigbee devices, the network extends further.

**WiFi (direct, future):** Unlimited range anywhere you have WiFi, even remotely.

**Bluetooth (legacy, not primary):** 100 feet open space, 30-50 feet through walls.

For most homes, Zigbee range covers everything. For large homes or multiple floors, place the hub centrally.

---

### Q: Can I customize what happens when I press it?

**A:** Absolutely. The button press triggers an event. What happens next is entirely up to you:

**Examples:**
- Turn on lights
- Start a scene
- Send a notification
- Log to a spreadsheet
- Post to Discord
- Trigger a full automation sequence
- Anything your smart home system supports

In Home Assistant, you can create unlimited automations. In Alexa, you can set up routines. IFTTT gives you 100+ options. The button is the trigger—you control the action.

---

## Customization Questions

### Q: Can I customize the face of my button?

**A:** Yes, completely. You can:
- Upload your own image or graphic
- Use your name or custom text
- Choose colors and design
- Select from pre-made templates
- Add emojis or symbols

During BackerKit (post-campaign), you submit your design. We print it on the button face. Every button is unique.

---

### Q: What if I want to change the design later?

**A:** You have a few options:

1. **Order extra custom faces** during BackerKit ($12 per set of 2 designs)
2. **Swap designs later** by printing a custom sticker (we can provide templates)
3. **Design it differently in Version 2** when you upgrade

The custom face is printed directly on the button, so changing it requires a new button. Plan accordingly.

---

### Q: Do you offer engraving?

**A:** Yes, engraving is available on the aluminum housing (not the face). Options:
- Your name or initials
- Short message (< 20 characters)
- Logo (custom branding for corporate orders)

Engraving is free for early backers, available as add-on later.

---

## Technical Questions

### Q: Is it safe for kids?

**A:** Yes. ProofButton is designed for safety:
- Small, non-toxic components
- No sharp edges (aluminum is smooth)
- No small parts to choke on
- No electrical hazard (kinetic, low voltage)
- Water resistant (safe for bathroom use)
- Durable (designed for heavy use)

We recommend supervision for young children (under 5), but it's safe for school-age kids and up. Many parents back ProofButton specifically for helping kids with homework accountability.

---

### Q: What about privacy? Does ProofButton collect data?

**A:** Privacy is a core value for ProofButton:

**What we DON'T do:**
- Don't track your location
- Don't sell data
- Don't profile you
- Don't require registration (optional)

**What we DO:**
- Local-first automations (data stays in your home)
- Optional cloud sync (your choice)
- Anonymous analytics (ping = button pressed, nothing more)
- Transparent about data use (read our privacy policy)

If you use Home Assistant hub, everything stays local—Jared never sees your data. Even with cloud features, we treat your data like it's our own (because it's your home).

---

### Q: Is it secure? Can someone hack it?

**A:** ProofButton security includes:

- **Wireless encryption** (Zigbee uses AES-128 encryption, same as banking)
- **Local control** (HA hub = no internet required, can't be hacked remotely)
- **Regular updates** (firmware updates fix security issues)
- **No cloud lock-in** (doesn't depend on ProofButton's servers to work)

Like all connected devices, no system is 100% hack-proof, but ProofButton is designed with security in mind. Local automation via Home Assistant is the most secure option.

---

### Q: What happens to ProofButton if your company shuts down?

**A:** ProofButton continues working. Here's why:

- **Local automations work forever** (HA doesn't require ProofButton servers)
- **Wireless protocol is open** (Zigbee is industry standard, not proprietary)
- **No cloud dependency** (optional, not required)
- **Source code will be open** (commitment to transparency)

Even if ProofButton Inc. disappears tomorrow, your button still works with Home Assistant and local automations. This is by design.

---

## Shipping & Fulfillment Questions

### Q: When will my ProofButton ship?

**A:** Expected timeline:
- Campaign closes: [DATE]
- BackerKit survey: 2 weeks after close
- Production: 4-6 months after BackerKit closes
- Fulfillment: 1-2 months after production completes
- **Expected delivery: 10-14 months after campaign launch**

This is conservative. We may deliver faster, but we won't rush and compromise quality.

---

### Q: Do you ship internationally?

**A:** Yes, to 100+ countries. Shipping costs vary:

- **USA:** $4-6 (included in base price)
- **Canada/Mexico:** +$5
- **Europe/UK:** +$12
- **Australia/NZ:** +$18
- **Rest of World:** +$20

Shipping time: 7-21 business days depending on destination. You choose your country during BackerKit survey.

---

### Q: What's the shipping policy for damaged/lost packages?

**A:** We've got you covered:

- **Damaged in transit:** We file a claim with the carrier and send you a replacement
- **Lost in transit:** We track with the carrier and resend if undeliverable
- **Never received:** Contact us within 30 days, we'll track and reship

This is why tracking numbers are crucial. Keep them for 6 months post-delivery.

---

## Refunds & Returns Questions

### Q: Can I get a refund?

**A:** Kickstarter policy: Refunds aren't available after your pledge is accepted. However:

**Before campaign launches:** Cancel your pledge (get full refund)

**After campaign launches:** No refunds available (standard Kickstarter policy)

**Why?** Once funded, we lock in manufacturing, so refunds would impact fulfillment for everyone.

---

### Q: What if ProofButton doesn't work when it arrives?

**A:** We offer a 1-year hardware warranty:

- **Not working:** Send it back (prepaid label), we send replacement
- **Defective:** Same replacement process
- **DOA (Dead on Arrival):** Contact us, instant replacement shipped

We stand behind the product. If it's broken, we fix it (or replace it).

---

### Q: What's your return policy?

**A:** Post-fulfillment:

**Within 30 days of delivery:**
- Return for refund (you pay return shipping)
- We test unit
- Refund issued if defective OR unopened/unused

**After 30 days:**
- Returns for store credit only (applies to future purchases)
- Or repair service (estimated $20-50 depending on issue)

We're reasonable. If something's wrong, we make it right.

---

## Product Version & Future Questions

### Q: Is this Version 1 or final product?

**A:** This is Version 1.0, designed to be excellent and future-proof, but not the final product ever.

**What that means:**
- Core functionality is final (kinetic, wireless, accountability focus)
- Hardware won't change (you keep your button)
- Software/features will improve (firmware updates)
- Version 2 may have new form factors (wall switch, remote, etc.)
- Your V1 button will be supported long-term

We're not selling a beta. We're selling a finished product that will improve with time.

---

### Q: What's the roadmap for Version 2?

**A:** We have big plans, contingent on campaign success:

**Likely (6-12 months post-launch):**
- Wireless WiFi version (no hub required)
- Additional smart home integrations
- Dedicated app improvements
- Community features

**Possible (12-24 months):**
- Wall switch version (flush-mount kinetic switch)
- Detachable remote button
- Sensor ecosystem (temperature, motion, door sensors)
- Designer app (custom face marketplace)

**No commitments yet—depends on campaign performance and community feedback.**

---

### Q: Do I need to upgrade to a newer version later?

**A:** No. Your V1 button will work for 5+ years without upgrades. New versions will be opt-in (you don't have to buy Version 2). Your original button continues working and improving via firmware updates.

---

## Billing & Pledge Questions

### Q: What if the actual cost is higher than estimated?

**A:** We locked in manufacturing quotes before launching. If costs increase, we absorb them (not passing to backers). If costs are lower, we keep the margin (standard practice).

**What you see is what you pay.** No surprise charges at fulfillment.

---

### Q: Can I change my pledge level after backing?

**A:** Yes, during the campaign (while it's live):
1. Click your pledge amount
2. Change to new amount
3. Confirm

After campaign closes, pledges are final (no changes via Kickstarter, but you can message Jared if there's an issue).

---

### Q: What if I want to add more units to my order?

**A:** You can:

1. **During campaign:** Increase your pledge amount to buy multiples
2. **After campaign:** Add items via BackerKit survey (add-ons section)
3. **After fulfillment:** We'll have a store and community shop

Early bird pricing only applies to the tier you select—add-ons are full price later.

---

## Support & Community Questions

### Q: How do I get help if something goes wrong?

**A:** Multiple support channels:

- **Email:** support@proofbutton.com (24-hour response time)
- **Community Discord:** Help from other users
- **Reddit:** r/proofbutton (when it exists)
- **GitHub:** For HA integration issues
- **Social media:** Jared checks Twitter/Instagram daily

Premium tier backers get priority support (2-hour response).

---

### Q: Will there be a community or user group?

**A:** Yes, we're building community:

- **Discord server:** Private community for backers
- **Subreddit:** r/proofbutton (once campaign launches)
- **GitHub:** Open-source integration guides
- **Social media:** @proofbutton on Instagram, Twitter

We'll have monthly check-ins, share user stories, and crowdsource ideas for new features.

---

### Q: Can I participate in development/feedback?

**A:** Absolutely. Post-campaign:

- **Beta testing:** Test new features before general release
- **Feature voting:** Community votes on which features to prioritize
- **Integration ideas:** Suggest new smart home integrations
- **Use case sharing:** Share how YOU use ProofButton (content creation opportunity)

Your feedback shapes ProofButton's future.

---

## Comparison Questions

### Q: How is ProofButton different from Flic Button?

**A:** Main differences:

| Feature | ProofButton | Flic |
|---------|-----------|------|
| **Battery** | Never (kinetic) | Annual ($5/year) |
| **HA Integration** | Native, official | Community workaround |
| **Price** | $49 | $25 |
| **Lifespan** | 5+ years | 2-3 years |
| **Privacy** | Local-first option | Cloud-dependent |

**Simple version:** Flic is cheap and casual. ProofButton is serious, reliable, and designed for accountability.

---

### Q: How is ProofButton different from SmartThings Button?

**A:** Main differences:

- **ProofButton:** Works with everything (Alexa, Google, HA, Matter). No hub required (works with optional hub). Kinetic power.
- **SmartThings Button:** Works with Samsung ecosystem primarily. Requires SmartThings hub ($30). Battery-dependent.

**Simple version:** SmartThings is for Samsung users. ProofButton is for everyone.

---

## Other Questions

### Q: Can I use ProofButton commercially?

**A:** Yes, bulk orders have special pricing and support:

- **10-25 units:** 20% discount
- **26-50 units:** 25% discount
- **51+ units:** 30% discount
- Custom branding available
- Dedicated account manager

Use cases: Fitness studios, offices, therapy practices, schools, etc. Contact support@proofbutton.com for enterprise inquiries.

---

### Q: What makes ProofButton different philosophically?

**A:** Most smart home products ask: "What convenience can we add?"

ProofButton asks: "How can we help people actually finish what they start?"

We're designing for accountability and behavior change, not just automation. The button is a tool for commitment. That's the difference.

---

## FAQ Summary

**If you remember one thing:** ProofButton is a battery-free wireless button designed for accountability. It works with your smart home, never needs replacing, and enables you to finish what you start.

**Questions not answered here?** Email support@proofbutton.com or ask in community channels. We read everything.

---

## Last Question: Why should I back ProofButton?

**Because:**
1. **Battery-free is real** - Never replace a battery again (this alone is worth it)
2. **HA community approved** - Built for people who care about smart home done right
3. **Designed with you** - Kickstarter backers shape the product
4. **Accountability matters** - This isn't just a gadget, it's a tool for change
5. **Jared is building this** - One founder, transparent, authentic
6. **The future is smart** - Matter support, roadmap shows vision for years to come
7. **It actually works** - 18 months of development, 500,000+ test presses, real users testing

Back ProofButton if you're tired of:
- Replacing batteries
- Smart home that doesn't actually help
- Accountability reminders that don't work
- Generic buttons that feel like everyone else's

This is for people who want to finish what they start.

---

**Ready to press the button? Back ProofButton on Kickstarter.**

[LINK TO KICKSTARTER CAMPAIGN]
