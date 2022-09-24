# Overview

This is a prototype of an event organization application so anyone can create and host meetings and events.  It is a zkApp written on the Mina blockchain.  It is designed for 3 users: event attendees, event organizers, and venue owner/manager/promoters.  Yes, we openly would love to destroy the existing ecoystem of how events get organized by billionaire companies, and let people manage their fees, let organizers and proters keep more control, and enable some new use cases that only blockchain can support.  Nope, it's not for doing e-commerce at this point, just a concept for creating events, checking in at events, verifying identity of the event ticket holder, and managing historical data around events.

- rev1 : 9/24/2022 original document

## Definitions

- event
- attendee
- organizer
- venue
- promoter
- manager
- owner
- seat
- timezone
- date
- capacity
- seating capacity

## References

- Web App Figma UI spec : TODO
- Prototype FSD: N/A ... this is the description in this document
- Mina Protocol spec: TBD
- zkApps spec: TBD
 
## Platform Requirements

- Written to the latest zkApps specification (VERSION??)
- Web Based
- Has a pathway to eventually support a web3 style app for iOS

## Milestone I Requirements  

Highlights for this release:

* App runs on a mobile web browser or a desktop webkit based web browser (Chrome only)
* App allows event organizers to publish new events publicly or privately
* App allows event space owners/managers/promoters to publish details about their event space, including availability for events (assumed money is handled outside of the app for rental)
* App allows prospective event attendees to find public events and sign up for these events
* App allows event organizers to checkin event attendees at the event
* App allows event organizers to view past event history or their own events
* App allows event attendees to view event attendance history


TODO: Finish this section below
- 1.0 App Displays a Splash Screen when launching (UI Spec: Splash v1)
    - 1.0.1 The app should display a standard splash screen when the web page is loading
    - 1.0.2 The splash screen should display momentarily on startup (standard splash functionality) and then go to home screen view
- 1.1 App utilizes a hamburger menu for navigation (UI Spec: Home v1)
    - 1.1.1 App shows a hamuberger menu that opens and expands to display navigation menu items:
    - 1.1.2 Navigation menu items are: Home, Settings, About
- 1.2 App has a Home Screen View as the initial screen displayed
    - 1.2.1 TODO
- 1.3 App has an Event Detail view
    - 1.3.1 TODO
- 1.4 TBD
- 1.5 App has a Settings view
    - 1.5.1 The app settings view has only one option: Torn on/off audible alerts.  This doesn't do anything yet
- 1.6 App has an about menu
    - 1.6.1 The app about menu shows the app version and build information, and app logo





## Milestone II Requirements

Highlights for this release:

* App runs on Android
* App runs on iOS

## Milestone III Requirements

Highlights for this release:

* Decentralized
* Available in App Stores

