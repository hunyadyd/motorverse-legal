# Points for legal review

Open questions and assumptions in the draft Privacy Policy and Terms of Service. Please check each before the documents are finalised.

## Placeholders to fill in

Search the pages for `[`. Besides the operator details (`[Company name Kft.]`, `[Registered office]`, `[Company registration number]`, `[Tax number]`) and `[Backend/hosting provider]`, two more need a value:

- **Publication date** (`[date of publication]` / `[közzététel dátuma]`).
- **How long backups are kept after an account is deleted.** The draft suggests 30 days.

## Points to review

1. **Written for launch.** The documents describe the app as it will work with a backend. Today all data stays on the user's phone, so the hosting provider, backups and server-side security described in the policy aren't in use yet.
2. **Data beyond the original brief.** The privacy policy also covers four things the app handles:
   - the saved Face ID login (email and password in the iPhone's Keychain, on the device only);
   - Car of the Month entries (a car photo and caption) and votes;
   - "my car is missing from the list" reports;
   - feature-idea votes.
3. **DSA trader information (Art. 30).** Business accounts must provide name, address, phone number, email, trade register number and tax number, and self-certify that they only offer products that comply with EU law. The app collects these fields at registration and in Account settings (added alongside this list), but has **no self-certification step yet**. The terms also say we *check* the details; confirm what checking is required, and the self-certification wording and where the app should ask for it.
4. **Parental consent.** The terms require parental or guardian consent for buyers and sellers under 18, on top of the 16+ minimum age.
5. **Retention periods.** The 2-year retention for support emails and for abuse reports is a suggestion.
6. **Consumer dispute resolution.** The terms point consumers to the conciliation board (békéltető testület). The EU online dispute resolution platform shut down in July 2025, so it isn't mentioned.
7. **Menu paths in the Hungarian pages.** ~~The app's interface is English-only for now, so the Hungarian texts quote the English menu paths.~~ Resolved: the app is now in Hungarian and English (it follows the App language setting), so the Hungarian privacy policy and terms quote the Hungarian menus (e.g. "Profil → Beállítások → Fiók → Fiók törlése", confirmed by typing TÖRLÉS, or DELETE with the app in English).
8. **Not indexed while in draft.** Every page asks search engines not to index it. Remove the tag from each page when the documents are final.
9. **6-month retention of trader information (DSA Art. 30(5)).** When a Business account ends (the account is deleted, or switched to Personal), the app's backend copies the trader information to a separate archive that no user can read, and deletes it automatically after 6 months. Both privacy policies now say so (section 5, and section 6 for deletion). Please confirm:
   - **What's archived.** Only the Art. 30(1) points the app collects: (a) name, address, phone number and email, (d) trade register number, (e) the self-certification. The **tax number** isn't in Art. 30, so it's deleted straight away (point 3 above lists it among the DSA fields; please check that too).
   - **When the 6 months start.** We count from account deletion or the switch to Personal. Is that "the end of the contractual relationship"?
   - **Whether we must keep it at all.** Art. 29 exempts platforms that are micro or small enterprises from Art. 30. We keep the information anyway, as if the exemption didn't apply. Is that the right call, and is the legal basis still "legal obligation" (Art. 6(1)(c)) if we're exempt?
   - **Disclosure.** The archive is only disclosed where the law requires (Art. 30(6)). There's no in-app access.
   - **Not collected yet:** (b) an ID document and (c) payment account details. Art. 30(1) requires both before a trader may sell.
10. **Listing photos and videos, and profile photos, are publicly reachable by link.** They're stored with our hosting provider as files with long random web addresses (a "public bucket"). Anyone who has a file's address can open it without signing in; the addresses can't be guessed and aren't listed anywhere, but a shared link works for whoever receives it. The rest of the data (profiles, listings, chats) stays visible to signed-in users only. We chose this because the files load much faster and are cached; the alternative is links that expire after a short time. Both privacy policies now say so (section 4). Please confirm:
    - **Whether this is acceptable** for photos people upload themselves, given that they may show number plates, faces or the inside of someone's home or garage. Should the app warn about that when adding photos, or should number plates be blurred?
    - **Whether section 4 explains it clearly enough**, and whether it also belongs under section 9 (Security).
11. **30-day deletion of sold listings' photos and videos.** When a seller marks a listing as sold, other users can still see it for 30 days (for example in their saved listings), with its photos and videos. After 30 days a daily job deletes the photos and videos (so in practice within 30–31 days), and the listing is then visible only to the seller, without them. Photos removed from a listing, deleted listings and replaced profile photos are deleted at once, or by the same daily job within 2 days. Both privacy policies now list these periods (section 5). Please confirm:
    - **The 30 days**, and whether the policy should say "within 31 days" rather than "30 days after the sale".
    - **Whether the sold listing's text** (title, description, price, location) should also be deleted at some point rather than kept until the seller deletes it or their account. Today it stays.
12. **Saved listings are now stored on the server.** Until now, the listings a user saved (the heart) were kept only on their phone. They're now stored with our hosting provider: which listing, when it was saved, the price at that moment, and the lower price we last told the user about (so each price drop is notified once). Only the user can see their saved listings; sellers aren't told who saved theirs. The record is kept until the user removes it, the seller deletes the listing, or the user deletes their account; a listing sold more than 30 days ago no longer shows in Saved, but the record stays until then. Both privacy policies now cover this (sections 2, 3, 4, 5 and 6). Please confirm:
    - **The legal basis**, performance of a contract (Art. 6(1)(b)), for keeping the saved price to send price-drop notifications the user turned on.
    - **Whether the saved record of a listing sold over 30 days ago** should be deleted rather than kept until one of the events above.
