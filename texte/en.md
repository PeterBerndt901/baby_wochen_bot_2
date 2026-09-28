# Texts for the Baby Weekly Bot (English)

This file is the English translation of `de.md`. The same rules apply:
- Every section starts with a heading with two hash signs (`## `). **Headings stay in German** (`## Woche 5 · …`, `## Termine Woche 8`, `## Oberfläche`, `## Willkommen`, `## Saison …`). Only the title after the dot is translated.
- In `## Oberfläche`, the keys to the left of the colon must not be changed, only the text on the right. `\n` creates a line break; placeholders such as `{n}` or `{url}` must stay.
- `**bold**` is shown in bold in Telegram.
- Everything above the first heading (this paragraph) is ignored by the bot.

Translation note: German health-system terms (U-check-ups, STIKO, Elterngeld, 116 117 …) are kept and briefly explained, because families in Germany encounter exactly these terms at the doctor's and on forms. Please have the translation reviewed by a native speaker with a medical or midwifery background.

The sources are listed in `de.md`.

## Willkommen

Hello! I'm your Baby Weekly Bot. From now on, I'll get in touch once a week, on the day of the week your baby was born. You'll receive what is typically happening in your baby's development right now, how well the science supports it, a small idea for everyday life, and reminders about upcoming check-ups (U-Untersuchungen) and vaccinations.

**Three things first:**

**1. Every child has their own pace.** When I write that something happens "now", I mean: around this time, for many children. The normal range is often huge. Walking independently, for example, ranges from just over 8 to almost 18 months (WHO study). The milestone lists I quote (US health authority CDC, 2022) describe what about 75% of children can do at a given age. So one in four children isn't there yet, and that is normal.

**2. When not to wait:** if your baby loses skills they already had, or if you have a persistent bad feeling. Physically: a fever of 38 °C or more in the first three months, hardly drinking, unusually floppy or hard to wake, laboured breathing → see a paediatrician the same day. At night and at weekends, the on-call medical service can be reached on 116 117; in an emergency, call 112.

**3. I'm just a bot** and can't reply. I don't replace your midwife or paediatric practice.

**On the evidence**, I always add how certain something is: "well established" (several good studies or reviews), "single study", "mixed evidence" (studies contradict each other) or "experience-based, barely studied" (plausible, but not scientifically tested).

## Oberfläche

sprache_name: 🇬🇧 English
bot_beschreibung: A short weekly message about your baby's development in the first year: what's happening now, how well the evidence supports it, everyday ideas and upcoming check-ups in Germany. Free and ad-free. Tap "Start" below.
bot_kurzbeschreibung: Weekly updates on your baby's development in the first year.
frage_sprache: 🌍 Please choose your language.
datenschutz: Welcome! A quick note on privacy before we start: I only store your chat ID, your chosen language, your baby's date of birth and, if you provide it, the original due date. That's all the bot needs. You can delete everything at any time with /delete.\n\nFull details (in German): {url}
knopf_einverstanden: ✅ I agree
frage_geburtsdatum: When was your baby born? Please write the date like this: 14.08.2026
datum_ungueltig: Sorry, I couldn't read that date. Please write it like this: 14.08.2026
datum_zukunft: That date is in the future. The bot starts at birth. Come back once your baby has arrived!
datum_zu_alt: Your baby is already older than one year. This bot only covers the first year. Congratulations on this milestone!
frage_frueh: Was your baby born more than three weeks before the due date?
knopf_ja: Yes
knopf_nein: No
frage_et: What was the original due date? Please write it like this: 14.08.2026
et_ungueltig: The due date has to be after the date of birth and no more than 20 weeks later. Please check the date again.
fertig: All set! From now on you'll get a message every {wochentag} morning. Use /help to see what else I can do.
geaendert: Your details have been updated. Here is the message for the current week.
wochentage: Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday
kopf_woche0: 👶 **Your baby is in their first week**
kopf_woche1: 👶 **Your baby is now 1 week old**
kopf_wochen: 👶 **Your baby is now {n} weeks old**
korrigiert: Corrected age: {k} weeks. The development information is based on this.
vor_et: Days remaining until the original due date: {tage}. Development information starts from the due date; until then you'll receive appointments and health notes only.
termine_titel: 📅 **Appointments & health**
hilfe: Here's how to use me:\n/week – show this week's message again\n/change – change the date of birth\n/language – change language\n/pause – pause messages\n/resume – resume messages\n/delete – delete all your data\n\nI'm a bot and unfortunately can't answer questions. If you're worried about your baby, contact your midwife or paediatric practice; at night and at weekends call the on-call medical service on 116 117, and in an emergency call 112.
befehl_week: This week's message
befehl_change: Change date of birth
befehl_language: Change language
befehl_pause: Pause messages
befehl_resume: Resume messages
befehl_delete: Delete all data
befehl_help: Help
schon_angemeldet: You're already signed up. Use /week to see the current message again or /change to change the date of birth.
nicht_angemeldet: You're not signed up yet. Send /start to begin.
pausiert: Messages are paused. Send /resume to continue.
fortgesetzt: Welcome back! Your next message will arrive on {wochentag} as usual.
loeschen_frage: Really delete all your data? You won't receive any more messages afterwards.
knopf_loeschen: 🗑️ Yes, delete everything
knopf_abbrechen: Cancel
geloescht: All your data has been deleted. All the best to you! You can start again at any time with /start.
abgebrochen: Nothing has changed.
sprache_gewechselt: The language is now English.
unbekannt: I'm a bot and unfortunately can't reply to messages. Use /help to see what I can do.
abschluss: Your baby's first year is complete, and so is this bot's journey with you. Thank you for being part of it!

## Woche 0 · Arriving

The first week of life is mostly about adjusting: breathing, circulation, digestion and temperature control are working without the placenta for the very first time. It is normal for newborns to lose some weight in the first few days. Most regain their birth weight within 10 to 14 days, and your midwife will keep an eye on it.

The senses are at different stages. Hearing already works well, and newborns demonstrably recognise their mother's voice, which they know from the womb. Vision, on the other hand, is still very blurry. It works best at a distance of about 20 to 30 centimetres, almost exactly the distance to your face during breastfeeding or bottle-feeding.

Much of what your baby does now consists of inborn reflexes: rooting and sucking, gripping your finger tightly, startling with arms flung wide at a sudden noise (Moro reflex). These reflexes fade over the coming months and make way for deliberate movements.

⚠️ **Safe sleep** (well established, applies to the whole first year): always on the back, in the parents' bedroom, in a baby sleeping bag rather than under a blanket, on a firm mattress without pillows, bumpers or cuddly toys, smoke-free and not too warm (about 16 to 18 °C). It is also recommended not to fall asleep together with your baby on a sofa or in an armchair, because your baby can slip into a gap between the cushions and your body or end up in a position where breathing becomes difficult. This is one of the most clearly established risks (well established). Cuddling your baby while you're awake, or relaxing on the sofa with your baby in a carrier or on your tummy, is not a problem. If you notice your eyes closing, put your baby in their bed or go to bed together. That's the safer choice.

🔬 **Own cot or family bed?** Experts disagree on this, and we want to be open about it. Official German bodies (BIÖG, DGKJ) primarily recommend a separate cot or a bedside crib in the parents' bedroom. Many breastfeeding and sleep researchers take a more differentiated view: sleeping together makes night-time breastfeeding much easier, and breastfeeding roughly halves the risk of sudden infant death syndrome (SIDS). In analyses of British studies (Blair and colleagues), sharing a bed was dangerous mainly when other risk factors were present. Without them, no measurable increase in risk was found. Other researchers (e.g. Tappin, Mitchell and colleagues) still see a small residual risk, especially for babies under three months (mixed evidence).

⚠️ All sides agree on when sharing a bed is **clearly more dangerous** (well established): when someone in the bed smokes or smoked during pregnancy, after alcohol, drugs or sedating medication, when you are utterly exhausted, when your baby was born prematurely or with a very low birth weight, or when your baby is not breastfed.

**If you share a bed:** a firm mattress with no gap to the wall, baby on their back next to the breastfeeding mother and not between the parents, in their own sleeping bag with no adult duvet or pillows nearby, no siblings or pets in the bed. A bedside crib combines closeness with a separate sleep space. Decide consciously what suits you, and feel free to talk it over with your midwife.

💡 Nothing more is needed right now: closeness, skin contact, your face and your voice. "Stimulation programmes" are unnecessary at this age.

📚 **What else is going on**

• **Feeding & eating:** In the first weeks, babies usually feed 8 to 12 times in 24 hours, often irregularly. Early hunger cues are rooting with the mouth, lip smacking and bringing a hand to the mouth. Crying is a rather late signal.
• **Nappies & potty:** The first stool (meconium) is black-green and sticky. Over the first few days it turns greenish and then, with breast milk, mustard yellow.
• **Growth:** Healthy full-term newborns usually weigh between 2.5 and 4 kilograms and are around 50 centimetres long. Birth measurements mainly reflect conditions in the womb and say less about later size.

🧸 **What you can do now**

• **Tuning in:** Respond to your baby's signals, i.e. hunger, tiredness and the need for closeness. According to current research, comforting quickly does not spoil a baby.
• **Play idea:** Skin contact, your face at 20 to 30 cm, talking or humming softly. No further "programme" is needed.
• **Worth buying?** Nothing for stimulation. What matters is a safe place to sleep, a sleeping bag in the right size and an infant car seat.

## Woche 1 · Rhythm? Not yet.

Newborns sleep a lot, roughly 14 to 17 hours a day, but in short stretches spread across day and night. An internal clock with a day-night rhythm only develops over the coming weeks and months. So if your baby is awake just as often at night as during the day, that's not a mistake, it's biology.

**Newborn jaundice** is common in these days. It usually starts on the second or third day and is generally harmless. You should have it checked by a doctor if your baby becomes very yellow, if the yellow colour increases after the first week, or if your baby is unusually sleepy and feeds poorly.

⚠️ Take a look at the **stool colour chart** in the yellow child health booklet (gelbes Kinderuntersuchungsheft). Very pale, clay-coloured or greyish-white stool can indicate a rare but urgent disease of the bile ducts. In that case, see a paediatrician promptly.

💡 Daylight and everyday sounds during the day, dim light and little entertainment at night: this helps the internal clock to settle.

📚 **What else is going on**

• **Relationships:** Bonding doesn't happen in a short window right after birth. The idea of a crucial "imprinting phase" has not been confirmed. If the start was bumpy, for example after a caesarean or a hospital stay, the bond still grows over weeks and months of everyday life.
• **Nappies & potty:** From around day five, five to six or more properly wet nappies a day are a good sign that your baby is drinking enough. The urine should be pale.
• **Movement:** The wriggly, flowing whole-body movements of newborns are called "general movements". Their quality is so telling that specialists use them for the early detection of movement disorders.

🧸 **What you can do now**

• **Tuning in:** Learn your baby's "language": yawning, looking away, fidgeting or arching often mean "that's enough for now" (experience-based, barely studied).
• **Worth buying?** A wrap or baby carrier is handy for closeness with your hands free. Make sure the face is uncovered, the chin isn't resting on the chest, and your baby sits upright and close to your body.

## Woche 2 · Evening marathon feeds

Many babies now have phases, usually in the evening, when they seem to want to feed for hours, sleep briefly and feed again ("cluster feeding"). This is common and not a sign that there isn't enough milk. Whether your baby is getting enough is better shown by wet nappies, weight gain and a contented impression in between. Your midwife can judge this well.

🔬 **Growth spurts?** You often hear about fixed growth-spurt weeks. Measurement studies do show that babies grow in jumps rather than evenly. But when a spurt comes cannot be predicted by fixed weeks.

**And you?** A low mood with lots of crying in the first days after birth ("baby blues") is very common and usually passes after a few days. If the low mood lasts longer than about two weeks or is very strong, it may be postnatal depression. It affects about 10 to 15% of mothers, fathers can be affected too, and it is very treatable. In that case, talk to your midwife, GP or gynaecologist. Information (in German) is available at schatten-und-licht.de

💡 Accepting help is not a luxury: have meals brought to you, limit visitors, sleep whenever you can.

📚 **What else is going on**

• **Language:** Newborns cry with the melody of the language around them. In one study (Mampe and colleagues, 2009), German newborns had more falling and French newborns more rising cry melodies. Language learning begins in the womb.
• **Growth:** Once birth weight has been regained, babies often gain 150 to 250 grams per week in the first months. Individual weeks can be well above or below that.
• **Nappies & potty:** Breast-milk stool is yellow, soft to runny and at first often comes after almost every feed. With formula it is usually firmer and browner.

🧸 **What you can do now**

• **Play idea:** Sing! Which songs doesn't matter, and singing out of tune is fine too. Babies prefer a familiar voice to perfect music.
• **Tuning in:** For long feeding evenings: set up a comfortable spot, keep water and a snack within reach for yourself, put on a series or an audiobook. Your wellbeing counts too.

## Woche 3 · Faces are the most exciting thing

Even newborns prefer to look at face-like patterns: two dots above and one below. Now their gaze becomes longer and more focused. Many babies fix on your face and follow briefly when you move slowly.

🔬 **An example of why putting things in context matters:** In 1977, researchers reported that newborns imitate you when you stick out your tongue. This was in textbooks for decades. A large study from 2016 with over 100 babies, however, could not confirm the effect. Whether newborns really imitate is an open question today.

💡 Try it anyway: face at 20 to 30 cm, tongue out, mouth open, smile, and then wait. Whether your baby copies you or not, they find you fascinating.

📚 **What else is going on**

• **Crying:** Many parents hope to tell from the sound whether their baby is hungry or has a tummy ache. Studies show this works only to a limited extent. The context is more helpful: when did your baby last feed, sleep, get changed?
• **Feeding & eating:** A baby who is breastfed or formula-fed doesn't need water or tea, not even in hot weather. Milk fully covers their fluid needs.
• **Relationships:** The second parent also quickly becomes a familiar person. Skin contact, carrying, bathing and nappy changes are good opportunities, regardless of who does the feeding.

🧸 **What you can do now**

• **Play idea:** Slowly move your face or a high-contrast cloth from one side to the other so your baby can follow with their eyes. One to two minutes is enough.
• **Worth buying?** Black-and-white contrast cards do no harm, but they have no proven benefit for development (experience-based, barely studied). Your face is more interesting.
• **Tuning in:** If your baby looks away, that isn't a lack of interest but a break. Wait until they seek eye contact again on their own.

## Woche 4 · Tummy time

Sleep on the back, play on the tummy: that's the rule of thumb. Lying on their tummy, babies practise lifting their head and strengthen their neck, shoulders and back. Tummy time also helps prevent a flattened back of the head, which can develop from lots of time on the back.

For babies who can't yet move around on their own, the WHO recommends at least 30 minutes on the tummy spread over the day, while awake and supervised. Lots of mini-sessions are perfectly fine.

Many babies protest at first. That's normal, and one or two minutes are plenty to begin with.

💡 The easiest way to start: lie back in a half-reclined position and place your baby tummy-down on your chest. Your face is the best motivation to lift the head.

📚 **What else is going on**

• **Sleep:** The Zurich longitudinal studies (Iglowstein, Largo and colleagues, 2003) show how different sleep needs are. Even among the middle half of the children, there was a difference of two and a half hours at six months. So your baby may need considerably more or less sleep than others.
• **Play:** At this age, playing mainly means looking, listening, discovering faces. Babies show when they've had enough, for example by looking away, yawning or fussing. Then a break helps.
• **Growth:** The head is growing particularly fast now, by about two centimetres a month in the first months. That's why head circumference is measured at every U-check-up.

🧸 **What you can do now**

• **Play idea:** Tummy time doesn't only happen on the floor: on your chest, across your thighs or in the "tiger in the tree" hold while carrying your baby around.
• **Everyday objects:** A rolled-up towel under the chest makes lifting the head easier for some babies, only under supervision, of course (experience-based, barely studied).
• **Worth buying?** A play gym or play mat is nice, but not necessary. A blanket on the floor is enough.

## Woche 5 · Lots of crying: what's normal?

In these weeks, babies cry and fuss the most on average. A large analysis of 28 studies with around 8,700 babies (Wolke and colleagues, 2017) found that in the first six weeks it averages about two hours a day, with an enormous range from half an hour to over five hours. After about eight to nine weeks it clearly decreases; by three months it has roughly halved on average.

🔬 **And the "leaps"?** The book "The Wonder Weeks" (German: „Oje, ich wachse!") places the first developmental leap here. Unsettled phases are real. That they come in fixed weeks for all babies, however, was only studied in small groups and is not reliably proven. The large analysis above, for example, found no uniform crying peak in exactly the same week.

⚠️ **Never shake a baby.** Even brief shaking can cause life-threatening brain injuries. If you notice you're reaching your limit: put your baby safely in their bed, step outside briefly, breathe, call someone. Support is available at crying clinics (Schreiambulanz; your paediatric practice knows where) and on the free parents' helpline Elterntelefon on 0800 111 0 550 (in German).

💡 Less is often more: carrying, dim light, steady white noise or humming, rather than constantly trying something new.

📚 **What else is going on**

• **Feeding & eating:** Many babies spit up a little milk after feeding. That's harmless as long as your baby gains weight well. You should have it checked if your baby vomits forcefully after feeds, if the vomit is greenish or bloody, or if your baby isn't gaining weight.
• **Relationships:** Lots of crying in the first weeks is not a sign that you're doing something wrong. How much a baby cries depends mainly on the baby.
• **Movement:** When your baby turns their head to one side while lying on their back, they often stretch out the arm on that side and bend the other ("fencing position"). This reflex usually disappears over the coming months.

🧸 **What you can do now**

• **Tuning in:** A tried-and-tested order when your baby cries: first check the basic needs (hunger, nappy, too warm or cold), then reduce stimulation, carry, rock steadily, hum (experience-based, barely studied). Not every bout of crying can be stopped, and staying with your baby is comfort too.
• **Fact check colic:** Anti-wind drops (simethicone) work no better than placebo according to studies. For breastfed babies with colic there are indications that a specific probiotic (L. reuteri DSM 17938) reduces crying, but not for formula-fed babies (mixed evidence). Please discuss this with your paediatric practice. There is no good evidence for osteopathy, chiropractic or baby massage against colic.
• **Fact check carrying:** In one study (Hunziker and Barr, 1986), babies who were carried a lot more cried considerably less. Two later studies did not find this effect (mixed evidence). Carrying does no harm, though.
• **Worth buying?** If you use a white-noise machine, keep it quiet and not right next to the head. Swaddling is controversial: if at all, only on the back, with hips free to move, and no longer once your baby might be able to roll (experience-based, barely studied).

## Woche 6 · The first real smile

Sometime in these weeks it usually happens: your baby looks at you and smiles. Not in their sleep, not by chance, but in response to your face or your voice. Most babies show this "social smile" by around two months of age.

Along with it come the first sounds that aren't crying: little cooing and throaty sounds. Babies are starting to respond when spoken to.

🔬 For research, the smile is a turning point: from now on, the relationship is visibly mutual.

💡 Smile back, talk, and then pause. Your baby needs time to "answer".

📚 **What else is going on**

• **Nappies & potty:** In breastfed babies, bowel movements often become less frequent after about six weeks. Anything from several times a day to once every seven to ten days is normal, as long as the stool is soft and the baby is thriving. In formula-fed babies, long gaps and hard stools are more of a reason to ask.
• **Sleep:** According to studies, a dummy (pacifier) at sleep time lowers the risk of sudden infant death. For breastfed babies, it's best offered only once breastfeeding is well established, and not forced if your baby doesn't want it.
• **Language:** The first cooing sounds are mainly vowels such as "aah" and "ooh". Consonants come later.

🧸 **What you can do now**

• **Play idea:** Smile dialogue: smile, wait, smile back. Babies love little surprises such as wide eyes or an "Oh!", but in small doses.
• **Tuning in:** Copy your baby's sounds and facial expressions. This "mirroring" shows them that they are seen.

## Woche 7 · Little conversations

Back-and-forth exchanges are already happening: you speak, your baby looks and coos, you answer. Specialists call this "proto-conversation", the structure of a conversation long before there are words.

🔬 **The still-face experiment** (Tronick, 1978): when mothers suddenly stare blankly and motionlessly during play, babies just a few months old first try to "bring them back" with smiles and sounds, and then become distressed. So babies expect a response. Important: everyday interruptions do no harm. What matters is that contact is re-established again and again.

💡 The typical high-pitched, melodic way of talking to babies is not nonsense. Babies demonstrably prefer to listen to it, and it supports language learning.

📚 **What else is going on**

• **Play:** Babies turn towards new things and look at familiar things for less time. Researchers use exactly this to find out what babies can tell apart. For you, this means: variety is good, but in small doses.
• **Growth:** In the yellow booklet, weight, length and head circumference are entered on percentile curves. The 50th percentile is the average; anything between the 3rd and 97th is considered the normal range. More important than the position is that your child roughly follows their own curve.
• **Feeding & eating:** With the bottle too, feed on demand and respect signs of fullness, such as turning the head away or sucking more slowly. First infant formula ("Pre" or "1") can be given throughout the first year; follow-on formula is not necessary according to the German network Gesund ins Leben.

🧸 **What you can do now**

• **Play idea:** Nappy-change commentary: describe what you're doing ("Here comes the fresh nappy") and leave pauses for "answers".
• **Fact check Mozart:** The famous "Mozart effect" comes from a study with university students, was short-lived and could hardly be replicated. There is no evidence that classical music makes babies smarter (well established). Music is still lovely, ideally with your own voice.

## Woche 8 · Two months: a little review

What most babies (about 75%) can do at two months, according to the CDC milestone lists (2022):

• calms down when spoken to or picked up
• looks at faces and smiles when smiled at
• makes sounds other than crying and reacts to loud noises
• follows you with their eyes and looks at a toy for several seconds
• briefly lifts their head when on their tummy, moves arms and legs, briefly opens their hands

**How to read this:** 75% means one in four babies can't do some of these yet. A single missing item is not an alarm signal, but a good topic for the next U-check-up. It's different if a baby loses skills they already had securely. Please have that checked by a doctor promptly.

📚 **What else is going on**

• **Relationships:** Babies differ in temperament from the very beginning, for example in how active, sensitive to stimuli or adaptable they are. The researchers Thomas and Chess coined the term "goodness of fit" for this: what matters is less a "right" temperament than how well child and environment fit together.
• **Nappies & potty:** A sore, red bottom is common. Frequent changes, fresh air on the bottom and a zinc cream help. If the redness has a sharp edge with small dots around it, it may be a fungal infection. Then see a paediatrician.

🧸 **What you can do now**

• **Tuning in:** Adjust stimulation to temperament: calm babies often need a little more invitation to play, sensitive ones rather less hustle and bustle (experience-based, barely studied).
• **Everyday objects:** Light grasping toys or rattles that won't hurt your baby if they drop them on their face.
• **Worth buying?** Toys must carry a CE mark. The GS mark ("geprüfte Sicherheit", tested safety) is voluntary and an additional reference point.

## Woche 9 · Discovering hands

Your baby is discovering that they have hands. Many babies now look at them for a long time, move their fingers in front of their eyes and put them in their mouth. The inborn grasp reflex is fading, and the hands are more often loosely open. That's the prerequisite for grasping deliberately later on.

The mouth is an important tool here. At this age, lips and tongue are the most sensitive touch organs a baby has.

💡 Put a light rattle or a fabric ring in your baby's hand. They still hold it rather by chance, but they're learning what their hand can do.

📚 **What else is going on**

• **Language:** Even newborns can tell apart languages with different rhythms, such as English and Japanese. The melody of speech is the first thing babies learn about their language.
• **Sleep:** During the day there is usually no fixed rhythm yet, but several naps of different lengths. More regular sleep times develop over the coming months.
• **Feeding & eating:** How much a baby drinks varies from feed to feed and from day to day. Healthy babies regulate their needs well by themselves. What matters is the development over weeks, not the individual feed.

🧸 **What you can do now**

• **Play idea:** Finger rhymes and gently bringing hands together: clapping hands in front of the chest, tapping fingers one by one.
• **Everyday objects:** A light fabric ring, a flannel, strips of fabric to hold. No long ribbons or cords.
• **Fact check breastfeeding:** Breastfeeding demonstrably protects against some infections. Whether it also increases intelligence is disputed: the large PROBIT study found an advantage at six and a half years but no longer at 16, and sibling comparisons find hardly any differences (mixed evidence). If you don't or can't breastfeed, you don't need to worry about your child's development.

## Woche 10 · The world gets more colourful

Vision is making big progress now. By about three months, babies already distinguish colours largely like adults, and around this time depth perception begins too: the brain learns to combine the images from both eyes into a three-dimensional impression. Babies now follow moving things more smoothly with their eyes.

🔬 Babies are still far from seeing as sharply as adults, though. Visual acuity continues to mature over the first years of life.

💡 Expensive contrast cards aren't necessary. Outside there's plenty to see: leaves in the wind, light and shadow, faces.

📚 **What else is going on**

• **Relationships:** Babies don't only bond with one person. In a classic study (Schaffer and Emerson, 1964), most children had several attachment figures by 18 months. They bonded most strongly with the people who responded sensitively to their signals and played with them, not necessarily with those who did most of the feeding and changing.
• **Movement:** In the coming weeks, many babies bring their hands together in front of their chest and look at them. The middle of the body becomes a meeting point for hands and eyes.
• **Nappies & potty:** Babies wee very often; the bladder still empties automatically. Conscious control is still years away.

🧸 **What you can do now**

• **Play idea:** Visual tracking: move a toy slowly back and forth. Or play shadow games with your hand on the wall.
• **Tuning in:** The best vision training is outdoors: trees, clouds, moving leaves.
• **Worth buying?** A mobile is fine if it's securely attached and out of reach. It isn't necessary.

## Woche 11 · It's getting calmer (mostly)

Good news for many families: after eight to nine weeks, crying decreases noticeably on average. At the same time, the day-night rhythm develops. From around the third month, the body increasingly produces the sleep hormone melatonin in a daily rhythm, and longer stretches of sleep at night become more common.

If, on the other hand, your baby continues to cry a lot, talk to your paediatric practice. Not because something must be "wrong", but because support is available, for example at crying clinics (Schreiambulanz). Have it checked immediately if crying comes with fever, poor feeding or vomiting, or if the crying sounds very different from usual.

💡 When things calm down, deliberately give yourselves breaks. Parents need to recover from the first weeks too.

📚 **What else is going on**

• **Play:** Babies play with their own bodies: hands, feet, voice. That is real play, because they repeat movements because they enjoy them.
• **Growth:** Many babies have doubled their birth weight by around four to six months and roughly tripled it by one year. Length increases by about half in the first year. These are rough guidelines with a wide spread.
• **Feeding & eating:** Night feeds are normal at this age. When a baby can manage the night without a feed varies greatly from child to child.

🧸 **What you can do now**

• **Play idea:** Body games: gently "cycling" the legs, blowing on the feet, bringing the hands to the face.
• **Tuning in:** As things calm down, a consistent evening routine can begin, even if it doesn't always work yet (experience-based, barely studied).

## Woche 12 · Heads up!

Head control is improving. Many babies now prop themselves up on their forearms when on their tummy and hold their head up longer. By about four months, most babies hold their head steady when held upright.

At the same time, inborn reflexes are disappearing. The Moro reflex (startling with arms flung wide) typically fades between three and six months. It's a sign that the cerebrum is increasingly taking control.

💡 During tummy time, put an interesting toy or a shatterproof mirror in front of your baby. Then lifting the head is worth it.

📚 **What else is going on**

• **Crying:** Babies who cry a lot are often overtired too. Some families find a steady daily rhythm helpful, with sleep opportunities offered deliberately before the baby is completely wound up.
• **Relationships:** The smile is becoming more targeted. Familiar people now often get a more radiant smile than strangers.
• **Nappies & potty:** Stool looks very different depending on diet. Greenish stool is usually harmless in an otherwise healthy, contented baby. The only important warning remains very pale, clay-coloured stool.

🧸 **What you can do now**

• **Play idea:** Grasping offers: hold a light fabric ring in front of your baby's hands so they hit it while wriggling and eventually hold on to it.
• **Fact check sticky mittens:** In experiments (Needham, 2002; Libertus, 2016), three-month-old babies were given mittens with Velcro to which light toys stuck. After two weeks of ten minutes a day, they explored objects more, and this was still measurable a year later (single study). Transferred to everyday life: creating opportunities for successful grasping probably helps.
• **Fact check head shape:** A flattened back of the head is common. Tummy time, changing head positions and talking to your baby from both sides help. A randomised study (van Wijk, 2014) found no advantage of helmet therapy over the natural course in healthy babies aged five to six months, but many side effects (single study). If your baby turns their head almost only to one side, have it checked at your paediatric practice.

## Woche 13 · Three months: cooing and chuckling

Your baby is getting chattier. The CDC describes cooing sounds such as "ooh" and "aah" and first chuckles when you make them laugh for most babies at around four months. Many babies now answer with sounds when spoken to and turn their head towards your voice.

🔬 At this age, laughing is above all a social signal and mostly happens in exchange with others. Real "humour", laughing at surprising and silly things, comes later.

⚠️ **A quick reminder about safe sleep:** The risk of sudden infant death is highest between the second and fourth month. So once more, the essentials: on the back, sleeping bag, firm surface without pillows or cuddly toys, smoke-free, not too warm, baby in the parents' bedroom. Whether in their own cot, a bedside crib or the family bed: experts disagree on this (mixed evidence). Sharing a bed is clearly dangerous, however, after smoking, alcohol, drugs or sedating medication, with premature babies, and on a sofa or in an armchair (well established).

💡 Copy your baby's sounds and wait for the answer. Such back-and-forth games are real preparation for language.

📚 **What else is going on**

• **Movement:** Sitting can't be practised yet. But carried upright, many babies already hold their head and look around curiously.
• **Sleep:** Longer stretches of sleep at night are becoming more common, but hardly any baby "sleeps through" yet. In studies, this usually means only six hours at a stretch.
• **Growth:** After the first three months, babies usually gain less per week than at the beginning. Growth slows down gradually over the whole first year.

🧸 **What you can do now**

• **Play idea:** Laughing games: gentle blowing, "I'm going to get you!", nose to nose. Stop before your baby gets overexcited.
• **Worth buying?** Nothing. You are the favourite toy right now.

## Woche 14 · First swiping, then grasping

Babies start to swipe at things deliberately, still clumsily at first, more a sweep with the whole arm. Within the next weeks, this turns into real grasping. Whatever is grabbed goes into the mouth. That's how babies explore shape, material and taste.

⚠️ From now on: anything within reach can end up in the mouth. Rule of thumb: anything that fits through a toilet-paper roll can be swallowed. Particularly dangerous are **button batteries**, which can cause severe burns within hours, and strong **magnets**. If you suspect your baby has swallowed something, get medical help immediately; in an emergency, call 112.

💡 Hold toys so that your baby has to stretch for them instead of putting them straight into their hand.

📚 **What else is going on**

• **Play:** Babies now play with everything they can grab: shaking, turning, putting in the mouth. Different materials (wood, fabric, silicone) are more exciting than lots of similar toys.
• **Feeding & eating:** During breastfeeding or bottle-feeding, many babies are now easily distracted, look around and drink restlessly. That's because the world is becoming more interesting. A quiet spot with little stimulation helps.
• **Language:** Babies laugh and squeal more and try out how loud they can be.

🧸 **What you can do now**

• **Everyday objects:** From the kitchen: wooden spoons, a silicone spatula, a fabric bag with a knot. No plastic bags, nothing breakable and nothing that fits through a toilet-paper roll.
• **Play idea:** When your baby is on their tummy, place a toy just out of reach so stretching is worth it.
• **Worth buying?** A few grasping toys made of different materials are enough. A study with toddlers (Dauch, 2018) found that they played longer and more varied with few toys than with many (single study). This hasn't been studied for babies, but "fewer, and rotated" is a good rule of thumb.

## Woche 15 · Careful on the changing table

Many babies roll over for the first time between four and six months, usually from tummy to back first. This often happens completely by surprise, for the baby too.

⚠️ Falls from the changing table, sofa or bed are among the most common accidents at this age. So: always keep one hand on your baby, or change them on the floor.

For sleep, continue to always put your baby down on their back. If they roll onto their tummy on their own and can also roll back, they may stay that way.

💡 Lots of time on a blanket on the floor gives room to experiment, more than a bouncer or car seat.

📚 **What else is going on**

• **Relationships:** Babies now clearly recognise who belongs to the family and greet familiar people with beaming smiles and kicking legs.
• **Sleep:** Sleep aids such as breastfeeding, carrying or rocking are completely normal at this age. How you handle it is up to your family.
• **Growth:** When weighing at home, scales, time of day and nappy contents vary a lot. Single measurements say little. For healthy babies, the U-check-ups are usually enough.

🧸 **What you can do now**

• **Play idea:** Encourage rolling: hold a toy to the side of your baby so that they turn their gaze and body after it.
• **Tuning in:** Play on the floor rather than on the sofa or bed. That way nothing can happen if your baby suddenly rolls.

## Woche 16 · Their own name

🔬 In a well-known experiment (Mandel and colleagues, 1995), babies of about four and a half months listened longer when their own name was called than when similar-sounding names were. So they already recognise this sound pattern, probably because they hear it so often.

According to the CDC, most babies only respond reliably to their own name, i.e. look when called, at around nine months. Recognising and responding are two different steps.

💡 Tell your baby what you're doing, while changing, cooking, dressing. How much parents talk directly to their child is linked in studies to later language development.

📚 **What else is going on**

• **Movement:** In the coming weeks, many babies lying on their back reach for their knees and feet. Feet are a great toy.
• **Crying:** After the third month, babies cry less often without an obvious reason. Crying becomes more targeted: out of frustration, boredom or tiredness.
• **Nappies & potty:** A baby who goes red, strains and groans during a bowel movement is not automatically constipated. The interplay of abdominal muscles and pelvic floor has to be learned first. What matters is whether the stool is soft.

🧸 **What you can do now**

• **Play idea:** Include your baby's name in songs and rhymes.
• **Fact check word count:** The famous "30-million-word gap" (Hart and Risley, 1995) is based on a small sample and is disputed. Newer studies (e.g. Romeo, 2018) suggest that genuine back-and-forth matters more than the sheer number of words (mixed evidence). So it's not about talking non-stop, but about interacting.
• **Everyday objects:** Picture books with photos of baby faces are often particularly exciting now.

## Woche 17 · Four months and the question of solids

For a long time, the rule in Germany was: introduce solids no earlier than the start of the 5th month and no later than the start of the 7th month. Since February 2026, Germany has had its first S3 guideline on breastfeeding duration. It recommends exclusively or predominantly breastfeeding full-term babies until the end of the sixth month of life, in line with the WHO. Solids are then added from the start of the 7th month, i.e. in about nine weeks. Until then, breast milk or infant formula is completely sufficient.

🔬 **How certain is this?** The guideline is based on observational studies in which children who were fully breastfed for six months had, for example, fewer middle-ear infections and gastrointestinal infections. The guideline itself rates the evidence as low to very low. Two professional societies, the nutritional medicine society (DGEM) and the professional association of paediatricians (BVKJ), therefore disagreed and still consider 4 to 6 months appropriate, partly with regard to allergies and iron supply (mixed evidence). The guideline explicitly stresses that no one should be pressured, neither to breastfeed nor to wean nor to start solids early. If there are allergies in the family or your baby is formula-fed, it's best to discuss the timing with your paediatric practice.

How you'll know later that your baby is ready (signs of readiness):

• sits upright with a little support and holds their head steady
• shows visible interest in your food
• opens their mouth when a spoon approaches
• no longer reflexively pushes food out with their tongue

Incidentally, according to the CDC, most babies can do the following at four months: smile on their own to get attention, chuckle, coo, turn their head towards a voice, hold their head steady, hold a toy, bring their hands to their mouth and prop themselves up on their forearms when on their tummy.

📚 **What else is going on**

• **Growth:** Breastfed children often grow somewhat more slowly in the second half of the first year than formula-fed children. That's why the WHO growth charts are based on breastfed children.

🧸 **What you can do now**

• **Tuning in:** Let your baby join family meals on your lap: watching, smelling, belonging.
• **Worth buying?** Only get a high chair once your baby sits upright with little help. Until then, your lap is the best place. For purées, a soft, flat baby spoon is enough. Home-made and jars are both fine.

## Woche 18 · Sleep: what's actually normal?

For babies between four and twelve months, the American Academy of Sleep Medicine (AASM) states about 12 to 16 hours of sleep in 24 hours, naps included, with large individual differences.

🔬 **The "4-month sleep regression"** is a popular term. It's true that sleep actually changes in these months: sleep cycles become more adult-like, and brief waking between cycles becomes more noticeable. But that all babies suddenly sleep worse at a fixed age is not well established.

Waking at night is the rule at this age, not the exception.

💡 A short evening routine that's always the same (for example nappy, sleeping bag, song, lights out) gives orientation.

📚 **What else is going on**

• **Language:** Babies now turn towards sounds and locate them more and more precisely.
• **Feeding & eating:** Great interest in your food is not on its own a sign of readiness for solids. Many babies follow every bite with their eyes long before they're ready.
• **Movement:** On their tummy, many babies now push up on their hands and lift their chest. Some "fly", lifting arms and legs off the floor at the same time.

🧸 **What you can do now**

• **Tuning in:** Recognise tiredness cues early, such as rubbing eyes, yawning or a glazed look, and put your baby to bed before they get overtired (experience-based, barely studied).
• **Worth buying?** A sleeping bag in the right size and thickness for the room temperature. A night light or baby monitor is a matter of taste; neither is necessary.

## Woche 19 · I can make things happen!

Your baby is discovering cause and effect: when I shake the rattle, it makes a noise. When I laugh, Dad laughs back.

🔬 In classic experiments by the psychologist Carolyn Rovee-Collier, three-month-old babies had a ribbon tied to their leg that was connected to a mobile. They quickly learned to move the mobile by kicking, and still remembered it days later. So babies learn early on that they can make things happen themselves.

💡 Toys that respond (rustle, jingle, move) are especially exciting now. But the most responsive toy of all is you.

📚 **What else is going on**

• **Crying:** Babies now also cry when something doesn't work, for example when a toy rolls out of reach. Frustration drives learning, as long as you help when it gets too much.
• **Growth:** The head is now growing more slowly, about one centimetre a month.
• **Nappies & potty:** Some families watch for their baby's signals before weeing and hold them over a potty ("elimination communication"). That's possible, but according to the Zurich studies (Largo and Stützle, 1977) it doesn't speed up later toilet training. Early potty training there only had short-term effects on bowel movements and none on bladder control.

🧸 **What you can do now**

• **Play idea:** Anything that responds to an action: crinkly paper (baking paper), a rattle, a well-sealed and taped-up plastic bottle with rice. Always under supervision.
• **Tuning in:** React visibly to what your baby does. That's how they learn: "I can make things happen."
• **Worth buying?** Electronic toys with buttons, lights and music aren't necessary. More on this in a few weeks.

## Woche 20 · Learning to read feelings

In the coming months, babies get better and better at telling feelings apart: friendly and angry voices, laughing and sad faces. Many now laugh really loudly.

According to the CDC, most babies like looking at themselves in the mirror at six months. But recognising themselves in it comes much later, in tests usually from about 18 months.

💡 A shatterproof mirror on the floor is an exciting play partner during tummy time.

📚 **What else is going on**

• **Sleep:** At six months, children in the Zurich studies slept a good 14 hours in 24 hours on average, with a wide range.
• **Movement:** Many babies now also roll from back to tummy. Caution on raised surfaces still applies.
• **Feeding & eating:** Iron is particularly important for solids, because the iron stores from pregnancy run low in the second half of the year. That's why the first purée contains meat or, for vegetarians, iron-rich grains such as oats or millet together with fruit or vegetables containing vitamin C.

🧸 **What you can do now**

• **Play idea:** Sing when your baby gets fussy. In one study (Corbeil and colleagues, 2016), babies aged six to nine months stayed calm about twice as long with singing as with speech (single study).
• **Everyday objects:** A shatterproof mirror at eye level on the floor.
• **Tuning in:** Put feelings into words: "Oh, that gave you a fright." Your baby doesn't understand the words yet, but understands the tone.

## Woche 21 · Squealing, blowing raspberries, babbling

Your baby is experimenting with their voice: squealing, humming, blowing raspberries. That isn't nonsense but voice training. Babies are finding out everything their larynx, tongue and lips can do. According to the CDC, most babies "chat" with you in sounds, taking turns, at six months.

💡 Join in! Blow raspberries back, squeal, wait for the answer. Silliness is educationally valuable here.

📚 **What else is going on**

• **Relationships:** Babies start to anticipate the high point of games. If you play a tickling game the same way several times, they're already delighted before it starts.
• **Play:** Toys move from hand to hand and into the mouth. Babies now turn and look at objects more systematically.

🧸 **What you can do now**

• **Play idea:** Sound ping-pong: your baby squeals, you squeal back, pause. Blow raspberries on the tummy.
• **Fact check baby massage:** Many babies enjoy massages. A Cochrane review (2013), however, found no robust evidence of benefits for development, sleep or crying in healthy babies, partly because many studies were methodologically weak (mixed evidence). So: go ahead if it does you both good.
• **Worth buying?** Baby classes such as PEKiP, baby massage or baby swimming have hardly been studied for their effect on development. Their value probably lies more in contact with other parents and shared experiences (experience-based, barely studied).

## Woche 22 · Drooling, teeth and fever

Many babies now drool a lot. That's mainly because saliva production increases at this age, and it isn't automatically a sign of teeth. The first tooth usually comes sometime between about 6 and 12 months. Some babies have one earlier, some only after their first birthday.

🔬 Studies show: teething can make babies fussy and raise their temperature slightly, but it doesn't cause a real fever. If your baby is really ill, please don't put it down to teething.

💡 A chilled (not frozen) teething ring can help. Paediatricians advise against amber necklaces because of the risk of strangulation and choking.

📚 **What else is going on**

• **Sleep:** Many babies now manage with two to three naps.
• **Language:** Babies understand melody before words. In one study (Fernald, 1993), five-month-old babies responded to approving and prohibiting speech melodies with matching facial expressions, even in foreign languages.

🧸 **What you can do now**

• **Everyday objects:** "The same thing, but different": offer a spoon made of wood, metal and silicone one after the other. Babies compare weight, temperature and sound.
• **Worth buying?** A teething ring that can be chilled is enough. Teething gels containing anaesthetics are not recommended for babies; if in doubt, ask at the pharmacy or your paediatric practice.

## Woche 23 · Sitting takes learning

Many babies now prop themselves up with their hands while sitting; the CDC lists this for six months. Sitting independently comes a little later. The large WHO study with children from five countries found a normal window of 3.8 to 9.2 months for sitting without support.

🔬 Interesting: in this study, sitting had the narrowest time window of all milestones examined. For standing and walking independently, almost ten months lie between the earliest and the latest healthy children.

💡 You don't have to "practise" sitting by sitting your baby up. Plenty of free movement time on the floor trains exactly the muscles needed.

📚 **What else is going on**

• **Play:** When your baby sits with support, both hands are free. Now exploring with two hands becomes possible.
• **Feeding & eating:** For eating, your baby should sit upright and well supported, for example on your lap or in a high chair with a seat insert, and not half-lying in a bouncer.

🧸 **What you can do now**

• **Play idea:** Sitting between your legs, offer toys sometimes on the left, sometimes on the right. That way your baby practises balance without toppling over.
• **Everyday objects:** A "treasure basket": a flat basket with three or four everyday objects of different materials, such as a wooden spoon, a metal bowl, a large pine cone, a cloth. The concept comes from early-years education (experience-based, barely studied). Nothing smaller than roughly a child's fist.
• **Worth buying?** Sitting rings and baby seats aren't necessary. Physiotherapists usually advise against sitting babies up for long before they can do it themselves (experience-based, barely studied).

## Woche 24 · Little language geniuses

🔬 Babies are born as "citizens of the world". In the first months, they can distinguish speech sounds from all languages, even ones adults can no longer hear. Between about 6 and 12 months, they specialise in the language or languages they hear and lose sensitivity to foreign sounds (Werker and Tees, 1984). The brain adapts to its own environment.

If you speak several languages at home: multilingualism doesn't confuse babies and isn't a cause of language disorders.

💡 Speak to your baby in the language you feel most comfortable in. Real people are irreplaceable here. In studies, babies learned foreign speech sounds from a person in the room, but hardly at all from the same person on video.

📚 **What else is going on**

• **Crying:** If a baby still cries a lot after the third month or sleeps very badly, specialists speak of a regulation disorder. Good places to turn to are crying clinics (Schreiambulanz) and Frühe Hilfen (local early-support services), which advise the whole family.
• **Movement:** Many babies now love pushing themselves up to stand on your lap and bouncing. That's fun and strength training in one.

🧸 **What you can do now**

• **Play idea:** Picture-book time: point, name, wait. A meta-analysis (Dowdall, 2020) found that looking at picture books together promotes language in children aged one to six (well established). It's less studied in babies, but a good start for a habit.
• **Worth buying?** Board books with clear pictures or photos. The local library often has a baby corner.

## Woche 25 · Out of sight, out of mind?

🔬 A classic of developmental psychology: Jean Piaget believed that babies only know from about eight months that things continue to exist when they can't be seen ("object permanence"). Later experiments by Renée Baillargeon suggested that babies as young as three to five months look surprised when a hidden object disappears in an "impossible" way. How much babies really understand here is still debated today.

What is certain: according to the CDC, most babies actively search for hidden things, such as a dropped spoon, at around nine months.

💡 Peekaboo games are great fun now: cloth in front of your face, and… there you are!

📚 **What else is going on**

• **Feeding & eating:** When solids start soon: the first spoonfuls of purée often come straight back out. That's not rejection; the tongue first has to learn to move purée to the back. New tastes often need 8 to 10 tries before they're accepted.
• **Growth:** Size and weight at birth mainly reflect conditions in the womb. So in the first 12 to 18 months, many children move onto a different percentile curve that better matches their genetic make-up. Small babies catch up, big ones grow somewhat more slowly.

🧸 **What you can do now**

• **Play idea:** Peekaboo variations: put a cloth over a toy, hide the toy halfway under the blanket, hide yourself behind the curtain.
• **Tuning in:** Plan to be relaxed about starting solids: offer new things again and again, without pressure, even if the face scrunches up at first.

## Woche 26 · Half a year!

What most babies (about 75%) can do at six months, according to the CDC:

• recognises familiar people, laughs, likes looking at themselves in the mirror
• "chats" by taking turns with sounds, blows raspberries, squeals
• puts things in the mouth to explore them and reaches for toys
• closes their mouth when they don't want any more food
• rolls from tummy to back and pushes up on straight arms when on their tummy

🔬 **Sleeping through?** A study of almost 400 babies (Pennestri and colleagues, 2018) found: at six months, 38% did not yet sleep six hours at a stretch and 57% did not sleep eight hours. This was not linked to their development or to their mothers' mood. Waking at night is normal at this age.

**Solids:** According to the new S3 guideline (2026), now, at the start of the 7th month, is the recommended time to start. If you started earlier on the advice of your paediatric practice, that's fine too. If your baby shows no interest in food at all in the coming weeks, mention it to your paediatrician.

📚 **What else is going on**

• **Nappies & potty:** With solids, stool changes: it becomes firmer, browner and smells stronger. Undigested bits, for example of carrot, are normal.

🧸 **What you can do now**

• **Play idea:** Half-year tidy-up: put away half of the toys and swap them every one or two weeks. That keeps things new, but it isn't proven for babies (experience-based, barely studied).
• **Worth buying?** A small open cup and bibs. Nothing more is needed to start solids.

## Woche 27 · Learning to eat

Solids are more than nutrition. Your baby is learning tastes, textures, chewing and swallowing. The classic sequence recommended by the German network Gesund ins Leben: first a vegetable-potato-meat purée at lunchtime, about a month later a milk-cereal purée in the evening, and another month later a cereal-fruit purée in the afternoon. Soft finger-food pieces ("baby-led weaning") are an alternative or addition.

You don't need to avoid allergenic foods such as well-cooked egg or fish. Leaving them out doesn't protect against allergies.

⚠️ **Off-limits in the first year:** honey (risk of infant botulism) and added salt and sugar. Cow's milk as a drink only from about one year; in purée it's fine. **Choking hazards** include whole nuts, whole grapes or cherry tomatoes (cut into quarters!) and hard raw pieces of carrot or apple.

🔬 Gagging is part of learning to eat. It's a protective reflex and it's noisy. Real choking, on the other hand, is often silent. So always eat at the table and stay with your baby.

💡 Offer water from a cup with purée meals.

📚 **What else is going on**

• **Sleep:** Babies don't automatically sleep better with solids. In a large British study, starting solids earlier led to only just over a quarter of an hour more night sleep.

🧸 **What you can do now**

• **Tuning in:** Respect signs of fullness: turning the head away, closing the mouth, pushing the spoon away. No "aeroplane" and no tricks. Professional societies recommend this "responsive feeding", because healthy babies regulate their amount well by themselves.
• **Fact check baby-led weaning:** A large study from New Zealand (BLISS) found that adapted baby-led weaning (soft, large pieces, iron-rich food at every meal) did not increase the risk of choking. It didn't find an advantage for weight either (single study). Purées, finger food or a mix of both are all fine.
• **Worth buying?** A high chair with a footrest. Stable feet make sitting and chewing easier for many children (experience-based, barely studied).

## Woche 28 · Stranger anxiety is on its way

Between about six and ten months, many babies start to be wary of strangers. They look at unfamiliar people sceptically, cling to you or cry when someone unfamiliar wants to pick them up. According to the CDC, most babies show this behaviour at nine months.

🔬 Stranger anxiety isn't a step backwards, it's a developmental step. Your baby can now clearly tell familiar and unfamiliar people apart, and they have built a bond with you. How strong it is varies greatly. Some babies hardly show it at all.

💡 Don't just hand your baby over. Let visitors approach slowly while your baby is safe with you.

📚 **What else is going on**

• **Play:** Babies now drop things on purpose and watch where they land. Repetition is the key: what happens the same way twenty times is understood.
• **Feeding & eating:** Drinking from an open cup can be practised now, with lots of spills at first. An open cup is better for teeth and mouth development than constant sucking on a bottle or sippy cup.

🧸 **What you can do now**

• **Tuning in:** Introduce new people slowly: let babysitters or grandparents get to know your baby while you're there.
• **Play idea:** Allow dropping: let things fall from the high chair into a bowl, pick them up, start again.

## Woche 29 · On the move

Many babies are becoming mobile now, in very different ways: commando crawling, spinning in circles, rolling, bottom shuffling. For crawling on hands and knees, the WHO study found a normal window of 5.2 to 13.5 months. A small proportion of healthy children never crawl and still walk completely normally later.

⚠️ **Time for childproofing.** It's best to go through your home once on your knees: stair gates, cleaning products and medicines high up and locked away, sockets, loose cables, poisonous plants. If you suspect poisoning, call the poison control centre for your federal state (for northern Germany: Giftnotruf Nord on 0551 19240); in an emergency, call 112.

💡 A first-aid course for babies gives you an enormous sense of security. Many midwives and aid organisations offer them.

📚 **What else is going on**

• **Sleep:** New movements are often "practised" at night. Some babies sit up half-asleep or crawl around the cot. Studies did find more night waking around the start of crawling, usually temporary.
• **Relationships:** Mobile babies move away, look back and return. Attachment research calls this the "secure base": because you're there, they dare to go exploring.

🧸 **What you can do now**

• **Play idea:** A small obstacle course of cushions and blankets on the floor. Place toys just out of reach.
• **Worth buying?** Now safety equipment is worthwhile, but only what you really need: stair gates, possibly socket and corner protectors, cupboard locks for cleaning products.

## Woche 30 · Baby walkers? Better not.

When babies become more mobile, it's tempting to help them with a sit-in baby walker. Paediatricians advise against it. Many accidents happen with these devices, especially falls down stairs, and they don't help babies learn to walk.

The same goes for door bouncers and long periods in bouncers: short is okay, but moving on the floor is most valuable for motor development.

💡 Barefoot or in non-slip socks on the floor: that's the best training equipment.

📚 **What else is going on**

• **Sleep:** Whether you use gentle sleep programmes or not is a family decision. An Australian long-term study (Price and colleagues, 2012) found neither harm nor benefit for the children five years later.
• **Nappies & potty:** Constipation becomes more common with solids. Hard, pellet-like stools and pain during bowel movements are a reason to talk to your paediatric practice. Fibre-rich purées, for example with pear, and enough fluids often help.

🧸 **What you can do now**

• **Play idea:** A tunnel made from a large cardboard box (without staples) or crawling under the table.
• **Everyday objects:** Boxes, cushions, a mattress on the floor as a climbing mountain.

## Woche 31 · Ba-ba-ba, da-da-da

Many babies now start babbling in syllables: chains of consonant and vowel such as "ba-ba-ba" or "da-da-da". Specialists call this canonical babbling. These syllables later become the first words.

🔬 This milestone is remarkably reliable: most babies start between 6 and 10 months. Research led by the linguist D. Kimbrough Oller showed that starting only after 10 months can point to later language difficulties or a hearing impairment. If your baby isn't babbling in syllables by about ten months, have their hearing checked, even if the newborn hearing screening was normal.

💡 Babble back, sing, do finger rhymes. By the way, "mamama" is usually not yet a word for mum. That comes later.

📚 **What else is going on**

• **Growth:** In the second half of the first year, many babies become slimmer. Body mass index peaks around the 9th month and then falls until preschool age. So the "baby fat" disappears all by itself.

🧸 **What you can do now**

• **Play idea:** Syllable ping-pong: "Ba-ba?" "Ba-ba!" Plus knee-bouncing rhymes and finger rhymes.
• **Fact check baby signing:** In the first randomised study on this (Kirk and colleagues, 2013), children whose parents used baby signs did not speak earlier or more. The mothers, however, responded more sensitively to non-verbal signals (single study). If you enjoy it: go ahead, but it doesn't work as a language booster.

## Woche 32 · From raking to pincer grip

Fine motor skills continue to develop. Small things are first pulled in with the whole hand, as if "raking" (typical at nine months according to the CDC). Gradually the pincer grip with thumb and index finger develops, which most children master at around one year.

Also typical: passing things from one hand to the other and banging two objects together. Wonderfully loud!

💡 Soft finger-food pieces (steamed carrot, banana) are fine-motor training and a meal at the same time. ⚠️ Be especially consistent about clearing away small parts now.

📚 **What else is going on**

• **Sleep:** Most babies now nap twice a day, in the morning and in the afternoon.
• **Crying:** Crying is increasingly directed at you. Babies look at you while crying and often calm down as soon as you come into view.

🧸 **What you can do now**

• **Play idea:** Throwing things into containers with a large opening: balls into a bucket, blocks into a box.
• **Everyday objects:** Soft cooked peas or sweetcorn on the tray are perfect pincer-grip training; eating happens under supervision.

## Woche 33 · Pulling up and holding on

Many babies now pull themselves up on furniture, cot bars or your legs. For standing with support, the WHO study found a normal window of 4.8 to 11.4 months.

⚠️ Anything that can be climbed will be. Fix shelves and chests of drawers to the wall, because toppling furniture causes serious accidents. Don't put hot drinks at the edge of the table and avoid hanging tablecloths. Scalds are among the most common serious injuries in babies and toddlers.

💡 A few stable, low pieces of furniture next to each other make an ideal practice area.

📚 **What else is going on**

• **Language:** Gestures come before words: raising arms, shaking the head, waving. Children who use many gestures early tend to have a larger vocabulary later in studies.
• **Feeding & eating:** Appetite now varies more. Some days babies eat a lot, other days hardly anything. Over several days it usually evens out.

🧸 **What you can do now**

• **Play idea:** Make music: a pot and a wooden spoon as a drum, rattles, singing together and bouncing along.
• **Fact check music classes:** In a Canadian study (Gerry and colleagues, 2012), babies who actively made music with their parents for half a year from six months showed certain gestures earlier and smiled more than babies who only listened to music (single study). What mattered was joining in together, not the class itself.

## Woche 34 · Protesting goodbyes

Many babies now protest when you leave the room. They cry, crawl after you or are hard to put down. The CDC lists "reacts when you leave" as a milestone at nine months. This separation protest often increases into the second year of life.

🔬 Behind it lies a cognitive achievement. Your baby now knows that you continue to exist when you're gone, but can't yet estimate when you'll be back.

💡 Say goodbye briefly and clearly instead of sneaking away. That makes your return predictable, which builds trust. It also helps if daycare settling-in is coming up soon.

📚 **What else is going on**

• **Sleep:** Separation protest often shows at bedtime and at night too. It's a temporary developmental topic and not a sign that you've done something wrong.
• **Nappies & potty:** Nappy changes turn into wrestling matches, because mobile babies want to get away. Changing on the floor, a special toy just for changing, or a song can help.

🧸 **What you can do now**

• **Play idea:** Practise separation through play: step behind the door briefly, "Here I am again!" That makes leaving and coming back predictable (experience-based, barely studied).
• **Tuning in:** A short goodbye ritual that's always the same, such as a kiss, a wave and a sentence, makes separations easier.

## Woche 35 · Looking where you look

A big step in the coming months is "joint attention". Your baby increasingly follows your gaze or pointing finger and looks back at you to make sure you're seeing the same thing. In studies, this develops mainly between about 9 and 15 months.

🔬 Joint attention is considered an important foundation for language learning. Babies learn words particularly well when the adult names what the child is looking at.

💡 Follow your baby's gaze and name what they see: "A dog! The dog is barking."

📚 **What else is going on**

• **Movement:** The Zurich studies led by Remo Largo described very different paths to walking: besides crawling, also commando crawling, rolling or bottom shuffling. Children who bottom-shuffle often walk independently somewhat later, but otherwise develop normally.
• **Play:** Babies now explore how things belong together: lid on the box, spoon in the cup. This combining of objects usually begins between about 9 and 18 months.

🧸 **What you can do now**

• **Play idea:** Pointing walk: at the window or outside, point at things, name them and wait to see whether your baby looks.
• **Everyday objects:** Stacking cups, tins with lids, a pot with a lid.
• **Fact check learning to read:** Programmes that supposedly teach babies to read showed no effect in a controlled study (Neuman and colleagues, 2014). The parents, however, were convinced their child was learning to read (single study).

## Woche 36 · Understanding comes before speaking

🔬 Babies understand much more than they can say. In one study (Bergelson and Swingley, 2012), babies as young as 6 to 9 months looked more often at the matching picture when hearing simple words such as "apple" or "nose". So first words are understood long before the first word is spoken.

Many babies now respond to familiar words and routines. "Where's Daddy?", and the head turns.

💡 Look at picture books together. It's not about reading the text aloud, but about pointing, naming and waiting.

📚 **What else is going on**

• **Feeding & eating:** Eating with a spoon takes practice. Two spoons help: one for your baby, one for you.
• **Growth:** Bow legs and flat feet are normal in babies. The arch of the foot only develops over the next few years.

🧸 **What you can do now**

• **Play idea:** Ask in the picture book: "Where's the dog?", and then wait until your baby looks or points.
• **Worth buying?** Board books, fabric books and touch-and-feel books. Swapping with other parents or the library are inexpensive alternatives.

## Woche 37 · Searching in the wrong place

🔬 A famous phenomenon at this age is the "A-not-B error". If you hide a toy under cloth A several times, the baby finds it there. If you then hide it clearly visibly under cloth B, the baby still searches under A. This shows that working memory and control over practised actions are still maturing. These abilities are linked to the development of the frontal lobe and improve towards the end of the first year.

💡 Hiding games under cups or cloths are ideal now. Feel free to test whether your baby falls for the A-not-B error.

📚 **What else is going on**

• **Relationships:** A cuddly toy or comforter becomes important for many children now or in the second year, as a piece of familiarity when you're not there. In the first year, however, it shouldn't be in the cot yet.
• **Nappies & potty:** Nappies will be needed for a long time yet. In the Zurich studies, the proportion of children reliably dry day and night was about 20% at two years and about 90% at four years.

🧸 **What you can do now**

• **Play idea:** Cup game: hide a toy under one of two upside-down cups and let your baby search.
• **Everyday objects:** Two or three cups, cloths, a favourite toy.

## Woche 38 · A glance at you: is this dangerous?

When your baby sees something new, such as a loud vacuum cleaner or an unfamiliar dog, they increasingly look at you first. Research calls this "social referencing".

🔬 In a well-known experiment (Sorce and colleagues, 1985), one-year-old babies crawled across an apparent drop on a glass plate when their mother looked happy, but hardly ever when she looked fearful. So babies use your facial expression as information.

💡 Your calm is contagious. If you comment on something new in a friendly way, your baby will dare more.

📚 **What else is going on**

• **Language:** Many babies now understand simple requests in context, such as "Give me the ball" when you hold out your hand.

🧸 **What you can do now**

• **Play idea:** "Give me" game: hold out your hand, "Thank you!", give it back, "Here you go!"
• **Tuning in:** Meet new things in a friendly and curious way. Your facial expression shows your baby whether it's safe.

## Woche 39 · Nine months: a review

What most babies (about 75%) can do at nine months, according to the CDC:

• is shy or fearful with strangers and reacts when you leave
• shows different facial expressions (happy, sad, angry, surprised)
• looks when their name is called and laughs at peekaboo
• babbles syllables such as "mamama" and "bababa" and lifts their arms to be picked up
• looks for things that drop out of sight and bangs two things together
• sits up on their own, sits without support and passes things from one hand to the other

As always: individual missing items are no cause for concern, but good questions for the U6 check-up. If your baby doesn't respond to their name **and** isn't babbling in syllables, have it looked at promptly. Among other things, their hearing should be checked.

🧸 **What you can do now**

• **Play idea:** Rotate toys and bring old favourites back out. Your baby often discovers them anew.
• **Worth buying?** Useful for the coming months: stacking cups, a soft ball, board books. The household provides the rest.

## Woche 40 · Delayed imitation

Your baby is becoming an imitator: waving, clapping, "pat-a-cake". According to the CDC, most children join in with such games at one year.

🔬 Babies can even imitate actions with a delay. In experiments by Andrew Meltzoff, nine-month-old babies imitated a new action with a toy 24 hours after seeing it. That shows an astonishing memory.

💡 Demonstrate simple actions clearly: lid on the tin, ball in the box, waving goodbye.

📚 **What else is going on**

• **Feeding & eating:** How much children eat varies greatly and is linked to growth and activity. In studies, pressure ("One more spoonful!") tends to make children enjoy eating less.

🧸 **What you can do now**

• **Play idea:** Demonstrate everyday actions: brushing hair, stirring with a spoon, feeding teddy.
• **Everyday objects:** Real, harmless everyday objects are often more fascinating than toy versions (experience-based, barely studied). No old mobile phones or remote controls with batteries within reach.

## Woche 41 · Pointing

Over the coming months, one of the most important gestures arrives: pointing with the index finger. At first usually to get something ("I want that!"), a little later also to share something ("Look, a bird!"). The CDC lists pointing to get help as a milestone at 15 months and pointing to show something interesting at 18 months.

🔬 Sharing-pointing is particularly exciting because it shows: your child wants you to see the same thing they see. It's one of the foundations of language and social understanding.

💡 Respond to every pointing gesture: look, name it, marvel together.

📚 **What else is going on**

• **Sleep:** Most children still need two naps now. Many switch to one sometime between 12 and 18 months.

🧸 **What you can do now**

• **Play idea:** A photo album with family photos: "Where's Grandma?" Point, name, marvel.
• **Tuning in:** Respond to every pointing gesture, even if you're busy, at least with a look and a word.

## Woche 42 · Along the furniture

Many babies now edge sideways along the sofa and table ("cruising"). For walking with support, the WHO study found a normal window of 5.9 to 13.7 months.

Your baby doesn't need shoes for this. Barefoot, they feel the floor best, and the foot muscles get trained. Shoes only make sense once your child walks outside.

💡 Push-along toys without a seat, such as a sturdy walker wagon with a handle (ideally with a brake), are fine. That's something different from sit-in baby walkers.

📚 **What else is going on**

• **Relationships:** Other babies become interesting: babies look at each other, smile and touch each other. Real playing together comes much later.
• **Growth:** With more movement, many babies gain weight more slowly. That's normal and not a sign that they're eating too little.

🧸 **What you can do now**

• **Play idea:** Spread toys along the sofa so that your baby cruises along to reach them.
• **Worth buying?** First-walker shoes aren't needed. Indoors, barefoot or non-slip socks are best (experience-based, barely studied). A push-along walker with a brake is optional.

## Woche 43 · Joining the family table

According to the German network Gesund ins Leben, from about the 10th month babies can gradually move on to family food: soft-cooked pieces, bread, mild family dishes, just less salty and spicy. Many babies now want to feed themselves, with their hands and with a spoon.

🔬 Feeding themselves is motor and sensory training. That it gets messy is part of learning.

⚠️ Still: no honey before the first birthday, cut round firm foods (grapes, cherry tomatoes) into quarters, no whole nuts.

💡 Eat together. Babies are more likely to try new things when they see you eating them too.

📚 **What else is going on**

• **Language:** Shared meals offer lots to talk about: naming, commenting, asking "More?" and waiting for the answer.

🧸 **What you can do now**

• **Tuning in:** Eat together at the table, the same foods, just adapted (softer, less salt).
• **Everyday objects:** Their own spoon, a small open cup, a bowl with a suction base.

## Woche 44 · Understanding "no" and doing it anyway

According to the CDC, most children understand "no" at one year and pause briefly. But not more than that. The ability to suppress an impulse develops over the coming years. So when your baby crawls to the socket for the tenth time, that's not defiance but their developmental stage.

The popular game "I'm throwing the spoon off the high chair" is research too: what happens when I let go? And does the spoon come back?

💡 Designing the environment works better than lots of prohibitions. Put away what isn't allowed and offer alternatives.

📚 **What else is going on**

• **Relationships:** Boundaries and bonding aren't mutually exclusive. Redirecting in a friendly and consistent way gives children security, even if they protest in the moment.

🧸 **What you can do now**

• **Tuning in:** Redirect instead of saying no a lot: "That's Mummy's phone, here's your tin." Set up "yes zones" where everything is allowed.
• **Play idea:** Allow throwing where possible: soft balls into a basket.

## Woche 45 · First words in sight

The first real words come around the first birthday for many children, with a wide range: some earlier, many considerably later. According to the CDC, most children say "mama" or "dada" (or another special name) to the right person at one year. "Woof-woof" or "yum" count as words too, if they always mean the same thing.

💡 **Expand instead of correcting:** If your child says "Ba!" for the ball, answer "Yes, the ball! The red ball is rolling." That way they hear the right word without being corrected.

📚 **What else is going on**

• **Movement:** Some babies now crawl up stairs. Going down is harder: backwards, on the tummy, feet first. This can be practised under supervision.
• **Nappies & potty:** Some children already show that they notice a full nappy. But becoming dry is mainly a matter of maturation. In the Zurich studies (Largo and colleagues), it could not be sped up by early or intensive training.

🧸 **What you can do now**

• **Play idea:** Animal-sounds game: "What does the dog say?" And songs with pauses in which your child can fill in.
• **Worth buying?** Talking toys aren't necessary. In one study (Sosa, 2016), parents talked less with their children when playing with electronic toys than with books or traditional toys (single study).

## Woche 46 · And screens?

The WHO recommends no screen time for children under one year. The reason is less that screens are "toxic" and more that they take up time in which babies learn: movement, play, conversation.

🔬 Babies learn considerably less from videos than from real people; research calls this the "video deficit". Studies also show that parents talk less with their children when a TV is on in the background.

Video calls with Grandma and Grandpa are something different, because a real person responds to the child. The American Academy of Pediatrics (AAP) considers them unproblematic even in the first year.

💡 No guilty conscience, but if possible: TV off when your baby is playing in the room.

📚 **What else is going on**

• **Play:** Simple toys lead to more conversation. In one study (Sosa, 2016), parents talked less with their children when playing with electronic toys than with books or traditional toys.

🧸 **What you can do now**

• **Play idea:** Instead of a screen while you cook: a kitchen drawer with pots, lids and wooden spoons that your child is allowed to empty.
• **Fact check learning videos:** In one study (DeLoache and colleagues, 2010), children aged 12 to 18 months didn't learn more words from a popular learning DVD than without it. They learned most when parents used the words in everyday life. Parents who liked the DVD overestimated the learning effect (single study).

## Woche 47 · In, out, in again

Your baby is becoming a sorter: putting things in boxes, taking them out again, starting over. According to the CDC, most children put objects into a container at one year. Behind this are important concepts like "inside" and "outside", and the experience that things reappear.

💡 The best toys are often in the kitchen: a bowl, a few wooden spoons, plastic tubs with lids.

📚 **What else is going on**

• **Sleep:** Night sleep lengthens only a little in the first year, in the Zurich studies from about 11 to almost 12 hours. It's mainly daytime sleep that decreases.
• **Feeding & eating:** From about one year, cow's milk is possible as a drink, but in moderation, because too much milk inhibits the absorption of iron from food.

🧸 **What you can do now**

• **Play idea:** In-and-out games: a tin with a slot in the lid and large wooden discs or beer mats to post.
• **Everyday objects:** A "released" drawer or box that your child may empty at any time.

## Woche 48 · Standing alone, first steps?

Some babies can already stand alone briefly, some take their first steps, many still need months. The WHO study found a normal window of 8.2 to 17.6 months for walking independently, in healthy children.

🔬 Walking early doesn't mean smarter. A Swiss long-term study (Jenni and colleagues, 2013) found no link between the age at first independent walking and later intelligence or coordination at school age.

💡 "Walking practice" holding both hands isn't necessary. Children who pull themselves up and let go at their own pace find their balance on their own.

📚 **What else is going on**

• **Growth:** In the WHO study, body size was hardly related to the age at which milestones were reached. Taller children were only a few days earlier.

🧸 **What you can do now**

• **Play idea:** Put a toy on top of a low piece of furniture; that encourages pulling up and standing. "Walking" holding hands only if your child wants to.
• **Worth buying?** Still no shoes for learning to walk indoors. Shoes only once your child walks outside.

## Woche 49 · Big feelings, few tools

Frustration is becoming more frequent. Your child wants more than they can manage: build the tower, reach the shelf, have the remote control. Children learn to regulate their feelings over years, and at first together with you. You calm, name and comfort, and your child gradually takes over.

🔬 The worry that responding promptly "spoils" babies is unfounded according to current research. Reliably responding to needs is considered the foundation of secure attachment.

💡 Name feelings: "You're angry because the tower fell down." Your child doesn't understand that literally yet, but learns that feelings have names and can be endured.

📚 **What else is going on**

• **Feeding & eating:** Towards the end of the first year, many children become more sceptical of new foods. Offering them repeatedly without pressure is the best strategy.

🧸 **What you can do now**

• **Tuning in:** When frustration hits: be there briefly, name the feeling, help rather than immediately taking over the whole task.
• **Play idea:** Copy feeling faces in the mirror or a book: happy, sad, surprised.

## Woche 50 · Back and forth

Games with turn-taking are becoming possible now: rolling a ball back and forth, giving an object and taking it back ("Thank you!", "Here you go!"). Your baby understands that a game has rules and roles.

🔬 Such back-and-forth games train the same things as a conversation: paying attention to each other, waiting, responding. How much of this back-and-forth children experience is linked in studies to their language development.

💡 Roll a ball to your baby and wait to see whether it comes back. And if not: crawling away with the ball is an answer too.

📚 **What else is going on**

• **Movement:** The hands are becoming more skilful: turning pages in a board book, soon stacking two blocks too.

🧸 **What you can do now**

• **Play idea:** Roll a ball back and forth, give and take things, build a tower and knock it down in turns.
• **Everyday objects:** A large, soft ball and a few light blocks.

## Woche 51 · A year of brain development

🔬 Your baby's brain has roughly doubled in volume in the first year of life. It never grows this fast again (Knickmeyer and colleagues, 2008). Above all, a great many new connections between nerve cells form, and those that are used a lot are strengthened.

When you look back: a newborn with reflexes has become a child who recognises you, "talks" to you, pursues goals, moves around and makes jokes.

💡 A good moment to look at old photos and realise how much you've achieved this year.

🧸 **What you can do now**

• **Play idea:** A small photo book of the first year to look at together: "Who's that?"
• **Tuning in:** Take time for yourselves too. A year with a baby is an enormous achievement.

## Woche 52 · One year!

Congratulations, a whole year! 🎂 What most children (about 75%) can do at one year, according to the CDC:

• plays games such as "pat-a-cake" and waves bye-bye
• says "mama", "dada" or another special name to the right person
• understands "no" and pauses briefly
• looks for things you hide in front of them and puts things into a container
• pulls up to stand and walks holding on to furniture
• drinks from an open cup that you hold and picks things up between thumb and index finger

Remember: walking independently, lots of words or pointing may still come considerably later.

That was the last weekly message. Thank you for letting me accompany you through the first year, and all the best for everything to come!

🧸 **What you can do now**

• **Worth buying?** For the birthday, better few presents, and bring the rest out gradually later (experience-based, barely studied). Books and shared time with Grandma and Grandpa are often the best presents.
• **Tuning in:** Celebrate briefly and in a small group. Too much hustle and bustle overwhelms many one-year-olds.

## Termine Woche 0

• **U2** (3rd to 10th day of life), often still in hospital. Your baby receives the second dose of vitamin K. Newborn blood screening and hearing screening are usually done in the first days of life. Ask if anything is missing.
• **Vitamin D:** The daily vitamin D dose (usually as a tablet, often combined with fluoride) starts in the first week of life and continues until the second early summer your baby experiences. Which product suits you is something to clarify with your paediatric practice or midwife.
• **RSV protection:** If your baby is born during the RSV season (usually October to March), STIKO (the German Standing Committee on Vaccination) recommends an antibody (nirsevimab) as soon as possible after birth, ideally before discharge or at the U2.
• If you haven't done so yet: look for a paediatric practice. Many only take on a limited number of new patients.

## Termine Woche 1

• **Paperwork with deadlines:** Elterngeld (parental allowance) is only paid retroactively for the last three months of life before the month of application, Kindergeld (child benefit) for six months. So don't wait too long. You usually need the birth certificate from the registry office (Standesamt) for this.
• Your baby must be registered with your health insurance (family insurance, Familienversicherung).

## Termine Woche 2

• **Book the U3:** The U3 takes place in the 4th to 5th week of life. It includes a hip ultrasound, the third dose of vitamin K and a conversation about upcoming vaccinations.

## Termine Woche 5

• **Rotavirus vaccination:** This oral vaccine is possible from 6 weeks of age (2 or 3 doses depending on the vaccine). Start as early as possible, because the vaccination series must be completed by a certain age. It's best to book an appointment now.

## Termine Woche 8

• **Vaccinations at 2 months** (STIKO): the six-in-one vaccine (tetanus, diphtheria, whooping cough, Hib, polio, hepatitis B), pneumococcal and meningococcal B, plus the next rotavirus dose if applicable.
• **U4** (3rd to 4th month of life). It can often be combined with a vaccination appointment.

## Termine Woche 12

• Only if your baby was born prematurely: STIKO recommends an additional dose of the six-in-one and pneumococcal vaccines at 3 months for premature babies.

## Termine Woche 17

• **Vaccinations at 4 months:** the second dose each of the six-in-one, pneumococcal and meningococcal B vaccines.

## Termine Woche 21

• **Book the U5** (6th to 7th month of life). Topics include movement, vision, nutrition and dental care.
• **Early dental check-ups:** Health insurance covers check-ups at the dentist from the 6th month of life.

## Termine Woche 26

• **First tooth?** For some babies now, for others only in months. As soon as it's there: start brushing and clarify the fluoride question. Either continue with tablets containing vitamin D **and** fluoride, then brush without fluoride toothpaste. Or vitamin D without fluoride, then brush with a rice-grain-sized amount of children's toothpaste with 1000 ppm fluoride. Don't combine both. This is the joint recommendation of paediatricians and dentists in Germany since 2021.

## Termine Woche 38

• **Book the U6** (10th to 12th month of life).

## Termine Woche 47

• **Vaccinations at 11 months:** the third dose of the six-in-one and pneumococcal vaccines, and the first dose against measles, mumps, rubella and chickenpox. The vaccinations may be spread over several appointments. If your child starts daycare earlier, the measles vaccination is possible from 9 months. Proof of measles protection is required by law for daycare in Germany.

## Termine Woche 52

• **Meningococcal B:** third dose at 12 months. At 15 months, the second dose against measles, mumps, rubella and chickenpox follows.
• **Vitamin D** continues until the second early summer your baby experiences.
• **Brushing teeth:** From 12 months, a rice-grain-sized amount of toothpaste with 1000 ppm fluoride twice a day is recommended for all children. Fluoride tablets are then no longer given.
• The next check-up, the **U7**, is at 21 to 24 months.

## Saison rsv · Monate 9, 10 · bis Woche 30

**RSV season is coming.** STIKO recommends that babies born between April and September receive a one-off antibody (nirsevimab) in autumn before their first RSV season. In young babies, RSV is one of the most common reasons for hospital admission due to respiratory infections. Ask your paediatric practice if this hasn't come up yet. They will also clarify whether it's needed in your case.

## Saison sommer · Monate 5, 6, 7, 8 · bis Woche 52

**Summer with a baby:** Babies in their first year shouldn't be in direct sunlight. Shade, light covering clothing and a sun hat are better. In hot weather, breastfeed or offer the bottle more often, and water too once solids have started. Never cover the pram with a cloth, because heat builds up underneath. And never leave your baby alone in the car.
