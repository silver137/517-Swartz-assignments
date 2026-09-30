# Document Analysis

The common document I will be using is a **business card**.

Business cards are compact professional documents designed to communicate a professional's identity, role, and provide a point of contact at a glance. It's overall structure is a quite predictable hierarchy:

1) Name
2) Professional Role and Position
3) Organisational Affiliation
4) Method of Contact

The **method of contact** is commonly an email, phone number, website, or even a QR code. 

The simplicity of this hierarchy reflects the situational genre the business card addresses; brief professional encounters. 

The card allows for several **roles and relationships** to form. Professional-professional, client-service provider, prospective employer-employee, and various others, all based in credibility and accessibility.

**Genre sections** typically include identity blocks, role blocks, contact blocks, and potentially a branding block (a logo, colour scheme, or specific fonts)

**Genre elements** include name, title (of role), phone, email, website, and layout conventions. 

There is special emphasis on clarity, minimalism, legibility/readability, and ensuring the card is reliable. Because of the size and function, the parameters are well defined and tight so that it can serve as an accurate and **portable professional identifier**.

## Genre Structure
The sections and elements used will be as follows
- Identity Block: name, company
- Role Block: job title
- Contact Block: phone, email, website,
- Branding Block: logo, colour scheme

## Implementation Reflection
My XML, DTD, and CSS translate the conventions of a business card into structural, visual rules. The DTD defines the required sections of the genre (identity, role, contact, branding) and restricts each to the elements typically found on a business card (name, title, email, logo). This enforces the genre’s emphasis on clarity and minimalism.

The XML file creates the real content following the predictable hierarchy. Allowing me to present information for quick scanning.

The CSS creates the visual realisation of the genre. It applies typography, spacing, and branding, as well as providing the physical dimensions of a standard business card.

## Issues
1) I could not load the UNC Logo. Not sure if it's just that Live Server is choosing not to load it or if I've somehow written my link wrong (but I think it's right), or some other issue I don't even know about, but I couldn't load it.
2) I also, could not get the navy background to exist just within the border of the card. I tried. So hard. Can't figure it out. Again, maybe this is just how Live Server is loading it, but I genuinely do not understand how to fix it. 