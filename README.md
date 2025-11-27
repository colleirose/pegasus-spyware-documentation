# pegasus-spyware-documentation
Internal NSO Group documentation and technical notes for the Pegasus spyware. These were publicly produced as evidence in WhatsApp Inc. v. NSO Group Technologies Limited, 4:19-cv-07123, (N.D. Cal.) Many were originally placed under seal but unsealed later as the defendants had failed to show why the evidence should remain sealed.

A lot of documents in this case are duplicates, unhelpful, or lumped together. They will be organized as much as possible as I have the time.

Note that these documents ONLY concern what was relevant to proving the claims of an attack on the WhatsApp Android application. They don't cover other attack vectors, and they don't date past the time when WhatsApp was attacked. However, some statements in the documents do confirm that, *at the time of the WhatsApp attack*, NSO Group had not found or at least not looked for exploits in several other messaging applications. The documents also provide a significant amount of information on the UI and capabilities of Pegasus and how the company performs its research and development.

You can browse the case filings yourself at https://www.courtlistener.com/docket/16395340/whatsapp-inc-v-nso-group-technologies-limited/?filed_after=&filed_before=&entry_gte=&entry_lte=&order_by=desc (sorted descending because most of the interesting things were only unsealed recently).

## Interesting observations
- On page 14 of `documents/internal communications and docs/nso/internal NSO communications/Document 677-3.pdf`, we see the following communication:
> Still waiting for confirmation but it could be a really big one with the President of Brazil; will keep updated as it happens.
> 
> [...]
> 
> Good morning from Brasilia team,
> 
> Sent a zero click from Sales 6 ID 625 at 08:09; received first WA call at 08:37 - no joined call.
> 
> Received second WA call at 07:41hs - no joined call. Installation status FAILED DUE TO INTERACTION. Device not touched. Cheers

[We know that Brazilian servers have been used to host Pegasus spyware](https://citizenlab.ca/research/hide-and-seek-tracking-nso-groups-pegasus-spyware-to-operations-in-45-countries/). We know that that [the Bosnaro administration acquired spyware from a different organization](https://apnews.com/article/brazil-bolsonaro-spying-c6666d710c7c8a8365777a1279f7f298), and interestingly, it appears these conversations took place about four months after Bosnaro became president.

- On page 99 of `documents/internal communications and docs/nso/internal NSO communications/Document 677-2.pdf`, we see the following conversation:
> Hello █████ the NSA executive cannot meet with us next week, but agreed to the following week, 16-20 April. Should be able to confirm a date today or tomorrow. I will also have another meeting or two that week, one with the former CTO of Dell, ██████████ who you met, who is now with company, Intelligent Decisions. They will be a new reseller partner but he wants to explore a hosted Phantom solution that would be managed in one of their secure data centers.

While I'm aware that it's been confirmed that the FBI sought to acquire Pegasus (which the same document discusses), I'm not sure if there's ever been confirmaton on whether the NSA has. If they have, this could actually quite strongly cut against the idea that the NSA already has access to everything, has broken all encryption, etc.