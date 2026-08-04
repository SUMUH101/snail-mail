## 1. Project

**Snail Mail**

A web application that replicates the experience of mailing handwritten letters through digital means.

## 2. Vision

Snail Mail is a communication platform designed for conversations worth slowing down for. It recreates the rituals of handwritten correspondence, giving friends, families, and long-distance couples a space to express themselves with greater thought, care, and intention than everyday messaging allows.

## 3. Problem

There are few digital spaces designed for people who want communication itself to be a deliberate, creative activity rather than simply the fastest way to exchange information. Existing messaging platforms priortize efficiency over reflection, making it difficult to treat communication as a meaningful hobby or shared experience. This is especially true for friends, families, and long-distance couples who often want interactions that feel more personal and memorable than a quick text message or email.

## 4. Solution
Snail Mail provides a digital space where communication is designed to be experienced rather than consumed. Users compose letters on virtual stationery, personalise them with envelopes and stamps, and send them through a simulated postal system that introduces intentional delays before delivery. By combining skeuomorphic design with immersive interactions, the platform transforms communication from a quick exchange of information into a thoughtful, memorable experience.

## 5. Product Principles
- Simplicity over complexity
- Delight over efficiency
- Slow is a feature
- Every interaction should feel tactile
- Minimize distractions
- Encourage thoughtful communication
- Intentional friction adds value
- Every feature should preserve the app's cozy atmosphere
- Recreate not only the appearance of physical mail, but the experience of sending and receiving it.
  
## 6. Target Audience
**Primary Audience**

People who want a more meaningful way to stay connected across distance, including:
- Long-distance couples
- Families living apart
- Friends separated by distance
- Pen pals

These users value thoughtful communication and are looking for an alternative to the immediacy of texting and email.

**Secondary Audience**

People who enjoy slower, intentional hobbies and experiences, such as:
- Journaling
- Letter writing
- Reading
- Book clubs
- Scrapbooking
- Drawing
- Cozy games

These users are likely to appreciate the product's atmosphere, customization, and emphasis on ritual.

## 7. Ideal User Experience
Jackson lives several states away from his sister, and they mostly keep in touch through short text messages. Wanting to send something more thoughtful, he opens Snail Mail and chooses a piece of stationery that reminds him of her. He writes about his week, folds the letter, seals it in an envelope, applies a stamp, and drops it into the mailbox.

Over the next few days, he occasionally checks the letter's progress as it makes its way to her. When it finally arrives, his sister admires the carefully chosen stationery, envelope, stamp, and seal before opening it. As soft jazz plays in the background, she settles in to read his letter, appreciating both the message and the care that went into creating it. Inspired by the experience, she writes and sends a letter of her own.

The exchange feels deliberate, personal, and worth the wait.

## 8. Core User Flow
Home

↓

Compose Letter

↓

Write Letter

↓

Customize

↓

Fold Letter

↓

Envelope

↓

Stamp

↓

Mail

↓

Tracking

↓

Delivered

↓

Read Letter

## 9. MVP
- Authentication
- Letter Writing
- Delivery
- Reading

## 10. Future Features

**1. Personalization**
- Additional stationery collections
- Seasonal stationery
- Sticker packs
- Wax seals
- Fountain pen styles
- Ink effects
- Custom handwriting (or Custom handwriting uploads)
- Inner envelope liners
- Vintage stamps
- Music themes
  
**2. Collectibles & Progression**
   
- Stamp collection album
- Rare collectible stamps
- Postal milestones
- Unlockable stationery
- Mailbox upgrades

**3. Social Features**

- Pen pal matching
- Friend lists
- Mail clubs
- Book club integration
- Holiday exchanges
- Community events

**4. Immersion**
   
- Ambient sounds
- Dynamic weather (reflecting real-world conditions via a weather API)
- Ambient environments (coffee shop, fireplace, rainy window, library, etc.)
- Ink drying animations
- Post office backgrounds
- Seasonal themes
- Correspondence Eras (Classic Postal, Medieval, Victorian)
- Opening animations
- Mailbox animations

**5. Communication**

- Birthday reminders
- Collaborative letters
- Photo attachments
- Pressed flower keepsakes (digital)
- Memory scrapbook

**6. Physical Integration**

- Printable PDFs
- QR code linking physical letters to digital memories
- NFC greeting cards
- Hybrid physical/digital letters

**7. Miscellaneous**

*Memory Shelf*

Instead of an inbox, completed conversations become books on a shelf. You open the shelf and browse years of correspondence.

*Shared Scrapbook*

Every exchanged letter automatically becomes part of a scrapbook between two people. Over years it becomes a relationship archive.

*Weather on Delivery*

Letters can include delivery details based on real-world conditions, such as "Delivered during the first snowfall" or "Delivered on a rainy afternoon." These small details help anchor letters to a specific moment in time, making them feel more memorable.

*Postal Route*

Replace the standard "Sent" status with an animated postal route, showing the letter travelling through sorting facilities and post offices before reaching its destination.

*Memory Box*

Keep tickets, photos, dried flowers (digitally), doodles, and little keepsakes inside conversations.

*Correspondence History*

Selecting a friend displays a timeline of your shared correspondence, allowing users to revisit important moments over the course of the relationship.

First Letter

↓

12 Exchanges

↓

Christmas Card

↓

Birthday Letter

↓

Vacation Postcard

↓

Today

## 11. Success Criteria

The MVP is considered successful if a user can:

- Create an account.
- Write a letter.
- Personalize the letter using stationery, envelopes, and stamps.
- Mail the letter through the simulated postal system.
- Track its delivery.
- Receive and open a delivered letter.
- Reply to a received letter.
- Complete the entire experience without external guidance.

The product should successfully recreate the core rituals of handwritten correspondence while remaining intuitive and enjoyable to use.

## 12. Technical Scope

### Frontend
- React
- TypeScript
- Tailwind CSS
- Framer Motion (animations)

### Backend
- Node.js
- Express.js

### Database
- PostgreSQL

### Authentication
- Clerk

### Email Service
- Resend

### File Storage
- Supabase Storage (or AWS S3)

### Hosting
- Vercel (Frontend)
- Railway / Render (Backend & Database)

### Third-Party APIs
- Weather API (contextual weather and delivery ambience)

## 13. Risks / Unknowns

- How long should delivery times be?
- Should delivery speed vary based on stamp type?
- Should recipients be required to create an account before reading letters?
- How should unread mail be presented to encourage anticipation rather than anxiety?
- How should abusive or spam accounts be handled?
- Should users be able to cancel a letter before it has been "mailed"?
- How much customization is enough before it becomes overwhelming?
- How should the platform balance immersion with usability?
- Which animations genuinely improve the experience, and which become repetitive?

## 14. Out of Scope (Feature Graveyard)

| Feature | Reason |
|---------|--------|
| Instant messaging | Undermines intentional communication. |
| Read receipts | Creates pressure to respond immediately. |
| Typing indicators | Encourage real-time conversation over reflection. |
| Infinite scrolling feed | Distracts from the correspondence experience. |
| Time capsule letters | Better served by dedicated products and shifts the focus away from interpersonal correspondence. |
| AI-generated letters | Reduces the authenticity and intentionality of personal expression. |

## 15. Milestones
- [ ] Product Brief
- [ ] Wireframes & User Flows
- [ ] High-Fidelity Figma Prototype
- [ ] Frontend MVP
- [ ] Backend & Database
- [ ] Letter Delivery System
- [ ] User Testing
- [ ] MVP Launch


## 16. Future Vision

Snail Mail aims to become more than a messaging platform, as it also aspires to be a digital home for meaningful interactions. As the platform evolves, it will continue exploring new ways to preserve the rituals of handwritten communication through immersive themes, collectibles,  and rich audiovisual experiences. Every addition should strengthen the feeling that writing a letter is a deliberate act of care rather than simply another form of messaging.

Ultimately, Snail Mail seeks to make meaningful communication a hobby, an experience, and a lasting keepsake rather than a disposable exchange of information.

## 17. Emotional Experience
    
| Feature/Stage |	Desired Feeling |
|:--------------:|:--------------:|
| Opening the app | Calm |
| Choosing stationery | Creative |
| Writing |	Reflective |
| Sealing the envelope |	Satisfying |
| Mailing |	Commitment |
| Waiting |	Anticipation |
| Receiving |	Excitement |
| Reading	| Nostalgia |
| Responding | Connection | 
