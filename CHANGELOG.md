# TransitAlert changelog

Every TransitAlert update since the first commit on 13 April 2026: 383 entries, up to version 1.103.323. The same notes are in the app at [transit-alert.com/changelog](https://transit-alert.com/changelog).

## Every week and month

| When | Updates |
| --- | --- |
| [22–30 November 2026](changelog/2026-11-22.md) | 179 |
| [15–21 November 2026](changelog/2026-11-15.md) | 65 |
| [8–14 November 2026](changelog/2026-11-08.md) | 42 |
| [1–7 November 2026](changelog/2026-11-01.md) | 34 |
| [October 2026](changelog/2026-10.md) | 23 |
| [September 2026](changelog/2026-09.md) | 9 |
| [July 2026](changelog/2026-07.md) | 3 |
| [June 2026](changelog/2026-06.md) | 6 |
| [May 2026](changelog/2026-05.md) | 15 |
| [April 2026](changelog/2026-04.md) | 7 |

## 22–30 November 2026

### v1.103.323 · Lift outages in step-free trips, and a map that says where trains are going
<sub>28 November 2026</sub>

- Trip planner: a station with a lift out of service right now counts as not step-free when you sort by step-free, and any trip that boards, changes or gets off where a lift is out says so at the top, naming the station.
- Live map with a screen reader: each train, tram and bus now says where it's going and how late it is before its fleet numbers ("Train to Mernda, Mernda line, 3 min late, cars 107M…").
- Typing a station and pressing Enter now picks the top match, instead of needing an arrow key first.

### v1.103.322 · Near me: Flinders Street and Town Hall together
<sub>28 November 2026</sub>

- Flinders Street and Town Hall are joined underground, but at Flinders Street, Near me never showed Town Hall: 79 stops are within 800 m there, and the tram stops filled the list.
- Now stations linked underground always show together, one after the other, marked "Linked underground": Flinders Street with Town Hall, and Melbourne Central with State Library.

### v1.103.321 · No more "Forms" for a train that's running too late to
<sub>28 November 2026</sub>

- Reported at Flinders Street: a Lilydale train came in 4 minutes late and left as the 5:42 to Lilydale, but the app said it formed the 5:39 to Glen Waverley, which had already gone. The app took the timetable's plan as confirmed once that trip appeared in Metro's live feed.
- Now a train is only said to form its next trip when it can: if it gets in after that trip is due out, or Metro's live vehicle feed has a different train on it, the app says it's running late and will probably be put on another service, and to check the platform screen.
- A late train whose next trip is held back for it still shows as forming it.

### v1.103.320 · Departure boards read better with a screen reader
<sub>28 November 2026</sub>

- A station's board now says its name in the page title ("Flinders Street · Departure boards"), so VoiceOver, TalkBack and the app switcher tell you where you are.
- The station heading reads just "Flinders Street", not "Flinders Street Save stop": the Save and check-in buttons sit beside it.
- Each platform's table is named after its platform, so moving between tables says "Platform 1" instead of only "table, 4 columns".

### v1.103.319 · Your saved stops, even with no signal
<sub>28 November 2026</sub>

- In the iPhone and Android apps, opening TransitAlert with no signal now shows the next services from your saved stops, from the last time you had signal (marked with that time), instead of only "No connection". Cancelled services are struck through and timetable-only times are labelled.
- The app keeps that copy up to date every 5 minutes while it's open. Times more than 3 hours old aren't shown.
- Needs the next app update from the App Store or Google Play.

### v1.103.318 · Says so when you lose signal
<sub>28 November 2026</sub>

- Lose signal in a tunnel or at a quiet stop and a banner now says "No connection. Times shown are from 4:12 pm and aren't updating", so old times never look live. It clears by itself when you're back online.
- In the phone apps, opening TransitAlert with no signal shows a "No connection" screen that reopens the app as soon as you're back online, instead of a blank screen.
- iPhone Live Activities: a trip display that has run out now leaves the lock screen properly instead of lingering.

### v1.103.317 · "Just left" survives updates; plainer alert titles
<sub>28 November 2026</sub>

- When each train really left is now kept through app updates and restarts, so "Just left" no longer goes back to timetable times for an hour after every release.
- Disruption alerts read the way you'd say them: "Frankston line: station works" instead of "Frankston Line · Station works · Update", "back to normal" instead of a tick and "Resolved", and no emoji in titles.

### v1.103.316 · Sixteen new themes: neon, time travel, steam, freight and interstate
<sub>28 November 2026</sub>

- Three originals inspired by films and games, with our own names: Neon Nights (an 80s sunset of hot pink and teal), Time Circuits (brushed steel, amber readouts and flux blue) and Undercity (chem green and a pink glow from down below).
- Trains and trams: Hitachi (fluted 1970s stainless steel), W-class (heritage green and cream), City Circle (burgundy and gold), Beach tram, Steam (coal black, buffer-beam red and brass), Blue & Gold (the Victorian Railways streamliner), Freight (loco yellow and rust) and Airport Rail.
- Interstate: Harbour City (Sydney), River City (Brisbane), Swan River (Perth), Festival City (Adelaide) and Outback Crossing for the coast-to-coast trains. Unofficial, colours only.
- There are 47 themes now, so Settings → Theme has sections: Everyday, Trains, trams + freight, Retro eras, Interstate, Footy + Melbourne and Just for fun. Each new theme tints the map and was checked for readable contrast before it shipped.

### v1.103.315 · Fixes from your accessibility reports
<sub>28 November 2026</sub>

- A bus stop no longer shows the shelter, seat or tactile paving of a tram stop with the same name at the same corner (reported at Hawthorn Rd/North Rd, where Route 64 tram stops sit beside the 626 and 630 bus stops). Stop details now only come from the same kind of stop.
- Riders can now add what no dataset records. The first rider note is on a bus stop with no shelter: shade from a tree, a wall to lean on, and buses that usually pull up with the front door at the kerb. Notes are checked first and always shown as a rider's note, never as an official assessment.
- Bus stops without an official step-free assessment stay "not assessed": the app doesn't guess, as riders asked.

### v1.103.314 · "Just left" shows when a train really left
<sub>28 November 2026</sub>

- PTV stops sending a train's live time once it has left, so "Just left" could only show the timetable. TransitAlert now keeps the last live time Metro gave for each train at each station before it went, so you can see when it really left and whether it went early. Trains that left before the server last restarted still show their timetabled time.

### v1.103.313 · "Did it already go?" Trains that just left, and whether they went early
<sub>28 November 2026</sub>

- Departure boards now have a "Just left · last hour" list: each train with the time it really left and whether it went early, on time or late ("Left 1:29 pm · 2 min early"). A rider at South Yarra waited for an X'Trapolis 2.0 to Carrum that had already been through, and the app couldn't tell them.
- The map's recent services show the same thing instead of just "Departed".

### v1.103.312 · Footy colours and Melbourne moments themes, free
<sub>28 November 2026</sub>

- Ten new free themes in the colours of Victoria's AFL clubs: Black & White, Navy Blues, Red & Black sash, Brown & Gold, Red & Blue, Royal Blue & White, Yellow & Black sash, Red White & Black, Red White & Blue and Navy & White hoops. Each has its stripes, sash or hoops across the top of the screen. They're unofficial, colours only, with no logos.
- Three Melbourne moments: Grand Final (navy + premiership gold), Boxing Day Test (cricket whites on the green, with a red ball) and Melbourne Cup (racing green, gold + the roses).
- Every new theme was checked for readable contrast before it shipped. Pick one in Settings → Theme.

### v1.103.311 · Ride Journal: times right in daylight saving
<sub>28 November 2026</sub>

- Imported and hand-logged journeys keep the time you gave them all year round. An import of "6:15 pm" in November showed 7:15 pm, because daylight saving wasn't allowed for.

### v1.103.310 · Ride Journal: every journey you take, logged
<sub>28 November 2026</sub>

- New Ride Journal (menu → Ride Journal). Each journey is logged as from → to with the date, the line, the distance along the track, the stations you passed through, the train's number and your notes. No account needed: it stays on your phone, and if you sign in it follows your account to every device.
- Zero taps: when you finish a trip you started in TransitAlert, each train, tram and bus you rode goes into the journal by itself, with the real train number from the live feed. Ending a trip early logs only the rides you marked done.
- Log one by hand in seconds: start typing a station for every Melbourne Metro and V/Line station, plus train stations in NSW, Queensland, SA, WA and the ACT.
- Bring your spreadsheet: import a CSV with a date, where you got on and where you got off ("Date / From / To" or "Got on / Got off" both work), plus the time, train number and notes if you have them. Stations it can't match are kept and listed. Export the whole journal as a CSV any time.
- Stats (journeys, km by rail, stations collected, passed through, networks, lines and train numbers) and All Stations progress for every Metro line.

### v1.103.309 · "Best" and "Fastest" are separate sorts
<sub>28 November 2026</sub>

- Trip options open on "Best", the planner's balance of time, walking and changes. "Fastest" now sorts strictly by time, and an option whose first wait isn't known yet goes after the timed ones.

### v1.103.308 · Sort your trip options, and departure boards read clearly to screen readers
<sub>28 November 2026</sub>

- Trip options can now be sorted: Fastest, Fewest changes, Least walking, Shortest wait, Step-free, More train, More tram or More bus. Each only ranks on what's known. Waits use real departure times. Step-free uses each station's official step-free route, and a station without that data stays unknown, never step-free. Your choice stays in the trip link.
- Screen readers now read each departure as one clear sentence: "Belgrave line to Belgrave, platform 2, departs 1:42 pm, 3 minutes late, opens train details", and for trams and buses "Route 16 to Kew, departs 1:44 pm, on time, follow it on the map". Trains approaching a station start with where they're going and when, with the train type last.

### v1.103.307 · Accessibility: more tap targets fixed
<sub>28 November 2026</sub>

- More controls are now at least 24px tall: the map's refresh button, All/None in notification settings, Report links, Show all on Disruptions, Open full app on Glance, and links on station pages.
- Skip to main content now works on the Glance page too, and the map's heading sits inside its landmark.

### v1.103.306 · Accessibility: skip link, focus ring, contrast and bigger targets
<sub>28 November 2026</sub>

- "Skip to main content" is now the first thing keyboard and screen-reader users reach, and every button, link and tab shows a clear yellow ring when it has keyboard focus.
- The map page has a main heading and a "Live map" landmark for screen readers, and the planner's map is a "Route map" landmark, so you can jump straight to them.
- Links that were hard to read now pass contrast: "Full BOM warning" on the weather card, and "See disruptions" on Delays, which was dark blue on a dark page.
- Bigger tap targets: tram and bus markers on the map have extra tap room, checkboxes and radio buttons are 24px, and notice links in the planner are taller.

### v1.103.305 · Tram changes can include a short walk
<sub>28 November 2026</sub>

- Changing between trams or buses now allows a walk of up to 500 m between stops, two city blocks (it was 250 m). Tram 86 and tram 70 only share a stop at Docklands, so La Trobe Uni to the MCG went all the way out there and back, over 2 hours. It can now change in the city, Bourke St to Flinders St.

### v1.103.303 · Bus and tram legs use routes running now
<sub>28 November 2026</sub>

- When a trip starts or ends with a bus or tram, routes whose next service is more than 3 hours away are left out, so the planner picks one that's running. From Monash Clayton on a weekend it no longer builds the trip around the weekday-only 601.

### v1.103.302 · Trip plans don't lead with a service that isn't running today
<sub>28 November 2026</sub>

- Planning from Monash Clayton on a Saturday listed a trip "43 h 39 min" away first, as the fastest: it started with the 601 shuttle, which only runs on weekdays, so its first bus was Monday morning. A route whose first service is more than 2 hours after you want to leave now goes after the routes that run now.

### v1.103.301 · "Terminates early" only when it's known
<sub>28 November 2026</sub>

- Station boards say a train terminates early ("timetabled to Frankston") only when the app found that exact trip in the timetable. When it could only match a similar trip by its run number, that trip's end proves nothing, so the board no longer says it.

### v1.103.300 · Trips work when every train ends short
<sub>28 November 2026</sub>

- On weekends the Alamein line is a shuttle to Camberwell, so a trip like Alamein to Hurstbridge had no direct train to Parliament and the planner gave up with "We couldn't confirm every service". When every train on a stretch ends partway, the plan now tells you to change where they end (Camberwell) and finds the train onward.

### v1.103.299 · Tram and bus boards no longer lead with trams that have left
<sub>28 November 2026</sub>

- Busy tram and bus stops could list trams that had already left at the top of the board. At Flinders Street/Swanston St that was the first ten, 4 to 9 minutes gone. They now move to recent departures as soon as PTV drops them from its live list. A late tram or bus that PTV still lists keeps its place.
- An open train panel now checks every minute whether the train's next trip has been confirmed or cancelled (it was every 10 minutes), and the wording is shorter: "Timetabled to form the 10:12 to Frankston (not confirmed yet)" and "Next trip not known yet."

### v1.103.298 · No more guessing a train goes out of service
<sub>28 November 2026</sub>

- A train panel no longer says "then out of service" unless it's known. Metro's timetable only links a train's trips two at a time, so after most trips it doesn't say what the train does next. One Saturday morning, 41 of 75 trains were wrongly shown as going out of service. Now it says where it goes next isn't known yet.
- A train's next trip ("Forms the 9:04 to Frankston", "Then becomes an Alamein train") is shown as fact only once Metro's live feed has it running, about an hour before it leaves. Before that it's shown as the timetable plan, "not confirmed yet". If the live feed has it cancelled, it isn't shown.
- Buses and trams away from their route no longer say "probably out of service": they may be on a detour or between trips.

### v1.103.297 · Bug hunt: a calmer Live dot, fewer pointless changes, cleaner notices
<sub>28 November 2026</sub>

- The Live dot on the map is green again when everything's fine. The live feed's routine housekeeping notes kept it amber nearly all the time; now only a real problem changes it.
- Trip plans no longer tell you to get off and onto another train of the same line going the same way (Eaglemont to Essendon: "change to a Hurstbridge train at Ivanhoe"). When one train runs the whole way and is at most 5 minutes slower, you stay on it.
- Typos in PTV's disruption notices ("Roite 699", "not service stops") are corrected in the app, notifications and widgets.

### v1.103.296 · Refunded Premium is removed
<sub>28 November 2026</sub>

- If a Premium purchase is refunded, through the App Store or Google Play, Premium is removed from that account. A refunded purchase can't be restored again later. Premium stays if the account has another purchase or was given Premium by TransitAlert. If Apple reverses a refund, Premium comes back.

### v1.103.295 · Premium in the iPhone app, ready for the App Store
<sub>28 November 2026</sub>

- The iPhone app can sell Premium through Apple's in-app purchase once it's on the App Store: one payment, with Restore purchase on the Account page for a new phone. The server checks Apple's signature on every purchase before unlocking Premium, and one purchase unlocks one TransitAlert account, as on Google Play.
- Until Premium is on sale in the App Store, the iPhone app doesn't mention it.

### v1.103.294 · Bug hunt fixes
<sub>28 November 2026</sub>

- Resetting your settings now sticks when you're signed in. Before, account sync could bring the old settings straight back.
- A damaged saved item on one device can no longer stop syncing, or overwrite the good copy kept with your account.
- Bus screens no longer ask PTV about a trip using a timetable ID it can't read. That wasted request failed every time and slowed the screen down.

### v1.103.293 · Your saved stops, trips and settings follow your account
<sub>28 November 2026</sub>

- Signed in, your saved stops and stations, saved trips, settings and alert choices are now kept with your account. Delete the app, get a new phone, or sign in on a tablet, TV or computer, and they come back. Change them on one device and the others catch up within a few minutes. If two devices both changed something, nothing is lost: saved stops and trips from both are kept. Signed out, everything stays on the device as before.
- Alert choices that come from another device are applied to this device's notifications straight away, if notifications are on here.
- TransitAlert now counts devices: once a day each device sends a random ID and what kind of device it is (no name, email or location), so we know how many people use the iPhone app, Android app and website. The privacy policy explains it.

### v1.103.292 · Clearer cross-line bus notes, and iPhone app fixes
<sub>28 November 2026</sub>

- The note under a bus that runs between two different lines no longer says it "links the two lines", which sounded like the lines join up. It now says the lines don't meet and the bus goes across by road, so you can carry on by train from the other line.
- iPhone app (TestFlight soon): widgets and the lock-screen trip view now load properly. They were left out at startup.

### v1.103.291 · Replacement buses between two different lines make sense now
<sub>28 November 2026</sub>

- PTV's "Buses replace trains between Caulfield and Elsternwick" on the Sandringham line read like a mistake, because Caulfield isn't on that line. When a replacement bus links two stations on different lines, the card now says so under the headline: "Caulfield is on the Frankston and Pakenham lines, Elsternwick on the Sandringham line. The lines don't meet: this bus goes across by road so you can carry on by train from the other line." PTV's own text is unchanged.

### v1.103.290 · Block a traveller, and getting ready for the iPhone
<sub>28 November 2026</sub>

- You can now block another traveller from their profile, next to Report. You won't see each other on leaderboards, feeds, station collectors or sightings, follows between you are removed, and they can't follow you. Unblock from the same profile.
- iPhone app (coming to the App Store): iPhone only, ready for Apple's push notifications, and Premium-only screens say they aren't in the iPhone app yet.

### v1.103.289 · Walk it when the next tram or bus is ages away, and freight is free
<sub>27 November 2026</sub>

- On a started trip, if you miss a tram or bus and the next one is a long wait, the trip card tells you when walking to the stop you're riding to gets you there sooner: "Quicker to walk: Ormond in 13 min (1.0 km), there by 8:05, 9 min sooner." It uses your walking pace setting, and after 9 pm it only suggests walking when it saves 10 minutes or more.
- Freight is free: planned freight times are no longer part of Premium. Sign in with a free account to see them. They now show on the station page as well as the map.
- Freight times now show at Ararat and Violet Town, which ARTC's plan calls "Ararat Siding" and "Violet Town Siding".

### v1.103.288 · Live location while the app is open, and ready for the App Store
<sub>27 November 2026</sub>

- Once you've allowed location, TransitAlert keeps it up to date while the app is open, so nearby stops and your trip stay current without tapping the location button. It never asks on its own, uses normal accuracy to save battery, and stops when the app is in the background. Turn it off in Settings (Live location).
- iPhone app: the location permission message now says exactly what location is used for, and the app carries Apple's privacy manifest.

### v1.103.287 · Fixes from the jury
<sub>27 November 2026</sub>

- "At the stop now" needs a position under 90 seconds old, and a tram must be within 40 m (buses 120 m), so a tram a block away or a bus that left 4 minutes ago no longer says it's there.
- On a started trip, being near a train's station only counts once you're off the bus before it, so a train that leaves before your bus arrives isn't offered. Only the walk you're on uses your location; later walks keep their planned length, and Leave by uses the same numbers.
- Near me and the city walk links use your walking pace. The walk-link note no longer promises a step-free way nobody has checked. Coach and SkyBus bays can't get mixed up at a stop they share.

### v1.103.286 · Buses at your stop say so, and the city's underground walks on the map
<sub>27 November 2026</sub>

- A bus or tram that's at your stop by its live position says "At Berwick Station now", or at the start of its trip "Waiting at Berwick Station · leaves 8:45 pm", instead of "Next stop is yours · 70 m away". Trip reminders say when it leaves ("leaves Berwick Station in about 4 min") rather than calling a bus in its bay "4 min away".
- Map: the underground walks between Town Hall and Flinders Street, and State Library and Melbourne Central, show as a dotted line with the walking time. Tap it for the way through. The trip planner already uses both, either direction.
- A train's card says "via City Loop" when it's still to go round the Loop, worked out from the stops ahead, and never once it has.
- Near me: a V/Line that's pick-up only says so ("pick-up only, first drop-off Pakenham").

### v1.103.285 · Tap a bus bay's letter to open it
<sub>27 November 2026</sub>

- Map: at a bus interchange, tapping a bay's letter ("H") opens that bay's departures. Only the small dot under it used to respond, which was hard to hit; the dots are bigger now too.

### v1.103.284 · A calmer trip card, and a walking pace that fits you
<sub>27 November 2026</sub>

- New setting, in Settings and the trip planner: Walking pace. "Unhurried" allows more time to walk or wheel, and at least 4 minutes to change, so Leave by and Tight warnings fit anyone slower. Suggested by riders who use wheelchairs.
- On a started trip, the walk you're on shows how much is left from your phone's location ("240 m to go · about 3 min"), and the trains after it are timed from there.
- Finished legs fold into one line ("✓ Done: walk, Bus 630"), and only one note shows at a time, for the ride that's next.

### v1.103.283 · Your trip catches the train that's actually there
<sub>27 November 2026</sub>

- On a started trip, once you're off the bus (or your phone's location puts you at the stop), the next leg lists trains from now. On the Ormond platform at 7:26 with a City Loop train 3 min away, it was still waiting for the bus's planned 7:48 arrival and offered one 34 min away.
- The top of your trip says what's next: "Next train in 9 min at Caulfield · Platform 4", instead of "Scheduled · 6 legs".
- A leg you're already at says "You're at Caulfield: catch any of these". Trains going round the Loop say "City Loop" like the platform screens, and each one shows one countdown instead of a countdown and a separate wait.

### v1.103.282 · Station cards you can read on a phone
<sub>27 November 2026</sub>

- Near me at a station: each train's destination is back in full, with the platform and the time it leaves on a line underneath ("Platform 3 · leaves 7:24 pm"). In 1.103.281 the platform pushed the destination off the screen.
- Trains are split under "To the city" and "Away from the city".

### v1.103.281 · Near me at big stations: every line, its platform and the time
<sub>27 November 2026</sub>

- Near me at a station like Richmond: trains to the city first, then outbound, each in platform order with its platform shown, and the clock time beside the countdown so you can line up a connection. Every line gets a row, including the quiet ones.
- A train's badge is its own line. Sandringham trains running through from Werribee or Williamstown said "Werribee" at Richmond, and the card took the colour of whichever train was first, so Richmond looked like a Frankston line station.
- A train that has just come round the City Loop says "from the City Loop", not "via the City Loop" as if it was going there. A run that ends at Southern Cross says Southern Cross, not "City service".
- Richmond's board loaded in up to 20 seconds after a restart; it's now about 3.
- Stations show the car spaces, bike racks, Parkiteer cages, toilets and taxi rank PTV lists.
- Map: a tapped V/Line train's carriages sit at their real length along the track, instead of being spread over a couple of kilometres at city zoom. The V/Line track also no longer doubles back on itself in 13 places (Avenel–Euroa, Springhurst–Wangaratta, Bacchus Marsh–Melton, Lara–Wyndham Vale and on to Geelong), where trains jumped back and forth.

### v1.103.280 · Avalon Airport in the right spot
<sub>27 November 2026</sub>

- Searching for Avalon Airport now starts you at the SkyBus stop outside the terminal. The pin was 1.5 km away out on the airfield, so trip plans began with a long walk.
- Stations whose entrances and walkways aren't in PTV's data (Boronia, Union, and V/Line stations) now say so, instead of the route finder just not appearing.
- A rail replacement stop reads "Replacement bus", not "Plat Replacement bus".

### v1.103.279 · Coach and SkyBus bays
<sub>27 November 2026</sub>

- V/Line coaches show their bay where the timetable gives one (Geelong Station Bay 2, Bendigo Bay 1, Lilydale Bay I, Dandenong Bay 10/11) instead of just "Coach stop". Southern Cross coaches still say Coach Terminal: those bays are only on the terminal's screens.
- SkyBus shows its bay: at the Southern Cross terminal, Bay 75 for Melbourne Airport and Bay 74 for Avalon, and Box Hill Bay 4, Sunshine Bay 6 and the airport's T4 bay.
- Saved stops, the departure details and the PIDs no longer print "Plat Coach stop".

### v1.103.278 · Tram door sides at most stops, worked out for each direction
<sub>27 November 2026</sub>

- Trams: the door side now shows at most stops instead of about a quarter of them. PTV's live data gives a stop one position even when each direction has its own boarding point across the road, so the app had been comparing it against some other stop with the same number, and could say left one way and right the other at the same stop. It's now worked out nightly from the timetable, which keeps both boarding points.
- Stops where the tram turns a corner, and the few that work out as right-hand doors, show no side until they've been checked at the stop.

### v1.103.277 · Door sides at Flinders Street go by which way the train is moving
<sub>27 November 2026</sub>

- Flinders Street door sides now depend on which way the train moves through the station, not which line it's on. A Craigieburn train comes into the same platform from Southern Cross or round the Loop from Parliament, and the doors open on opposite sides; the old rules gave the wrong side for one of the two. Frankston and Sandringham trains leaving platforms 6 and 8 also get a door side now.
- North Melbourne works by direction on every platform, so Craigieburn trains on platform 4 get one. Alamein trains into Camberwell 1 too.
- V/Line trains at stations they share with Metro (Dandenong, Pakenham, Sunbury, Watergardens, Broadmeadows, Craigieburn, Flinders Street and more) use the same platform rules. Regional stations still show no door side until it's confirmed.

### v1.103.276 · Door sides both ways at North Melbourne and 450 more platforms, and ARTC's new freight plan
<sub>27 November 2026</sub>

- Door sides now work in both directions on a platform. North Melbourne only knew one way on most platforms (1 city-bound, 4 and 6 outbound, and 2 said left whichever way you were going). A platform is on one side of its track, so the other direction opens on the other side; that's now filled in at 450 platforms, which helps when a train is moved to another platform, runs the other way round the Loop, or uses one track during works.
- Freight due now uses ARTC's train plan of 15 November 2026, replacing the July one.

### v1.103.275 · Freight times say how old ARTC's plan is
<sub>27 November 2026</sub>

- Freight due shows the date of ARTC's train plan in plain words, and warns once the plan is over four months old, because ARTC has usually issued a newer one by then and some times may have changed.
- Passport badges lose their emoji labels: the tabs just say Stamps, Network, History and Regional.

### v1.103.274 · Lift alerts for your saved stations, and freight tracked by riders
<sub>27 November 2026</sub>

- New notification, on by default: "Lifts at my saved stations". If PTV lists a lift out of service at a train station you've saved, you get told, even if you don't follow that line. Asked for by riders who use wheelchairs.
- Freight due: when a rider posts a sighting of a planned freight train (like 6MP4 at Sunshine) in the last 6 hours, the card shows where it was seen, how late it's running, and when to expect it at this station. "Seen it? Post a sighting" now opens the Sightings form already filled in.
- Plainer wording on the Passport, Fleet PIDS and Heritage pages.

### v1.103.273 · Train signs say what the real ones say
<sub>27 November 2026</sub>

- The destination sign now reads like the train's: "UPFIELD" going to Upfield, "CITY LOOP" for a city train going round the Loop, "FLINDERS ST" for one going straight there. The X'Trapolis cab is just the cab and its sign, with no logos.

### v1.103.272 · X'Trapolis destination sign on the cab front
<sub>27 November 2026</sub>

- With train-fan details on, an X'Trapolis now shows its destination the way you see it pull in: amber sign in the top window of the cab. Rider idea from Lachlan.

### v1.103.271 · Lift status says when it's out of date
<sub>27 November 2026</sub>

- If TransitAlert hasn't been able to check PTV's lift notices for over 20 minutes (no signal, or PTV down), a station no longer says "No lift outages". It warns that the lift status couldn't be updated and to check before relying on it.

### v1.103.270 · Report a bus ramp you couldn't get over
<sub>27 November 2026</sub>

- "What's happening?" on a bus or tram has a new access report: "Ramp problem (couldn't board)". It warns the next wheelchair or pram user on that vehicle, alongside blocked wheelchair spaces and doors out of order. Suggested by a rider in a wheelchair.

### v1.103.269 · Bus depots checked against the operators' own lists
<sub>27 November 2026</sub>

- CDC depots now match CDC Victoria's list: Airport West (the former Tullamarine depot), Westmeadows, Truganina, Albion and Oakleigh South, plus Ballarat and Geelong.
- Dysons' depots (Reservoir, Bundoora, Bairnsdale) now read as Kinetic, which took them over on 2 October.
- Ventura's Seaford depot and McHarry's Breakwater depot added.

### v1.103.268 · Night works show their replacement stops on time
<sub>27 November 2026</sub>

- Replacement bus stops for night works now appear on the map right at the start time (7:45 pm, say). They only appeared once the disruption notice itself changed, which could be much later.
- Night works notices worded "until the last service every night" are read correctly too.

### v1.103.267 · Find any bus by its number or plate, running or not
<sub>27 November 2026</sub>

- Searching a bus fleet number now finds it even when it isn't running, and opens its history. It used to say nothing unless the bus was on the map right now.
- Numbers with a letter in front work ("T113"), and so do number plates ("6655AO"). "T113" used to show a train.

### v1.103.266 · Clearer train stop lists
<sub>27 November 2026</sub>

- A train's stop list now says "Previous stop" for the stop it last called at. "Last stop" read as if the train ended there.
- Camberwell platform 2: doors on the left for every city-bound train, not just Alamein trains.

### v1.103.265 · Replacement bus stops on the map during works
<sub>27 November 2026</sub>

- While buses replace trains, the map marks the official replacement bus stop (orange) at each station on that line. Tap one for the station's details.
- Night works ("from 7.45pm each night") only show the stops from that time until the last service, not all day.
- Notices don't say which stations are affected, so the whole line is marked: check the notice for your station.

### v1.103.264 · Bus depots, longer bus history, and train destination signs
<sub>27 November 2026</sub>

- Bus depots for Kinetic, CDC, Ventura, Transit Systems, Dysons, McHarry's and others (West Footscray, Sunshine West, North Fitzroy, Doncaster, Albion, Wyndham, Oakleigh, Dandenong, Lilydale and more). A bus stopped at one now reads "at Transit Systems West Footscray depot" in its history.
- Bus positions are kept for 14 days instead of 3. Each bus's trips were already kept for good.
- Maidstone tram depot added.
- Train fans: a train's details show its destination the way its own sign does ("UPFIELD" in amber on an X'Trapolis, white on an HCMT). Idea from a rider.

### v1.103.263 · Replacement coaches only show where they really stop
<sub>27 November 2026</sub>

- Evening Traralgon and Bairnsdale coaches (Sunday 29 November to Wednesday 2 December) no longer show at Clayton, Flinders Street, Richmond or Berwick. The official notice says they don't stop there, but the timetable data still listed them. Boards and the trip planner both follow the notice. Thanks to the rider on r/MelbourneTrains who spotted it.
- Coach-only stops (like Caulfield Station/Sir John Monash Dr) show their replacement coaches again. The board gave trains all the room and none was left for coaches, so the board was empty.
- Flinders Street is spelt right everywhere. PTV's data calls one coach stop "Flinder St"; it now reads "Flinders St".

### v1.103.262 · South Yarra 5 and 6, Brighton Beach 1
<sub>27 November 2026</sub>

- South Yarra 5: left to the city, right outbound. South Yarra 6: left outbound, right to the city. Worked out from the station's layout (side platforms 1 and 6, islands 2/3 and 4/5), which fits every platform already known there.
- Brighton Beach 1 (the island's other face from platform 2, not in regular use): right to the city, left toward Sandringham.

### v1.103.261 · Door sides for works and turnback platforms
<sub>27 November 2026</sub>

- Added both directions for the platforms trains use during works and turnbacks: platform 2 at Glen Huntly, Ormond, McKinnon, Bentleigh, Patterson and Moorabbin, Belgrave 1, Essendon 1, Werribee 3, Flinders Street 12 and 13, and Richmond 5 and 6.
- Southern Cross regional platforms 2, 3, 4, 5, 7, 8, 15 and 16 now show door sides on V/Line trains, including Gippsland trains that leave south through Flinders Street (their doors are on the other side).
- South Yarra 5 and 6 and Brighton Beach 1 are still blank: what we were told about them didn't match the platforms we already know.

### v1.103.260 · Door sides at Frankston, Hawthorn, Cheltenham, Macleod and West Footscray
<sub>27 November 2026</sub>

- Checked on the platform: Frankston 1 (right leaving for the city, left arriving), Hawthorn 3 (left, outbound), Cheltenham 2 (right, to the city), Macleod 3 (left, to the city) and West Footscray 2 (right, to the city through the tunnel).

### v1.103.259 · Door sides for 20 more platforms
<sub>27 November 2026</sub>

- Door sides added for Richmond 10, the third platforms at Glenferrie, Auburn, East Camberwell, Canterbury and Chatham, Jolimont-MCG 2, Watergardens 2, Westall 3, Laverton 2, and the end platforms at Sunbury, Craigieburn, Lilydale, East Pakenham, Cranbourne, Glen Waverley, Mernda and Werribee (leaving and arriving).
- These were worked out from where each platform sits beside the track, checked against the platforms already known (the method got 278 of 279 right) and against Union platform 3. Spotted one that's wrong? Report it and it'll be fixed.
- St Albans: both platforms' door sides were in the app but never showed, because the station was spelt "St. Albans". Fixed.

### v1.103.258 · Your trip on the map follows the tracks and the roads
<sub>27 November 2026</sub>

- A started trip's line on the map now follows the real railway, tram track and bus route, instead of jumping in straight lines from stop to stop. Express trains follow the track past the stations they skip.
- Trams and buses use their route's published line through your stops. Where that can't be matched, the old stop-to-stop line is still shown.
- Your trip's line is drawn above the railway lines, so a train leg no longer disappears under the line it runs on.
- Union platform 3: doors open on the left.

### v1.103.257 · Your trip offers the train that's actually next, and tapping a bus finds the right one
<sub>27 November 2026</sub>

- On a started trip, the next train you can make is the real next one. Running early used to hide every train before the one the plan first picked: at Richmond at 7:48 it offered the 8:04 Belgrave ("18 min connection wait") while a Belgrave express left in a minute. Once you've finished a leg, each change now uses the live board from now.
- Planning from your location while you're at the station (within 150 m) no longer adds a walk to the platform, so a train leaving in a minute or two isn't dropped as already gone.
- Tapping a bus on a stop board no longer jumps to a different bus on the same route: a nearby bus whose own times are more than 5 minutes off this trip's is now left alone, and the trip's estimated position is shown instead.
- Buses arriving to end their trip at a stop now show their fleet number ("#178") when the bus is in the fleet register.

### v1.103.256 · Estimated trams now say which tram they are
<sub>26 November 2026</sub>

- Trams with no GPS now show their fleet number and class ("D2 · 5003") from Yarra Trams' TramTracker, matched by route and arrival time at their next stop. Their position is still estimated, and still drawn faded.
- If TramTracker shows an estimated tram is really a tram already on the map from GPS, the duplicate estimate is removed.
- Stop names no longer show PTV's internal codes ("D14-Southern Cross Station" now reads "Southern Cross Station") in a tram's next stop and stop list.

### v1.103.255 · Estimated trams read properly
<sub>26 November 2026</sub>

- An estimated tram's card said "This train isn't sending GPS". It now says tram (or bus).
- Estimated trams no longer show a long trip code ("03-72--36-T5-...") as if it were their fleet number on the map.
- The card no longer has two Position rows: GPS now reads "Not sending · position estimated".

### v1.103.254 · Tram headings name the place
<sub>26 November 2026</sub>

- Trams and buses heading to a named place on a street corner now say where they're going: "To Victoria Harbour Docklands" instead of "To Victoria Harbour Docklands/Collins St". Two street names ("High St/Doncaster Rd") still stay whole.

### v1.103.253 · Disruptions in line colours
<sub>26 November 2026</sub>

- Disruption cards on the map show each affected line as a chip in its own colour (Mernda red, Frankston green, V/Line purple), so you can see at a glance if it's your line.
- A short disruption card no longer leaves a big empty gap over the map: the banner now fits the card you're looking at.
- Live map: right after an update, estimated trams now appear within a few seconds instead of up to 20.

### v1.103.252 · Tram door sides, and two station-sign themes
<sub>26 November 2026</sub>

- Trams: tap a tram on the map and its stop list now shows which side the doors open at each stop (Doors left / Doors right), worked out from where PTV's boarding points sit on each side of the road. Stops with a single shared platform stay blank rather than guessed.
- Trip planner: the door side at a tram's first stop was worked out backwards and could show the wrong side. Fixed.
- New theme: Metlink era. The 2000s platform signs, so page titles read like the white station sign with a line-colour stripe.
- New theme: Station signs. Today's charcoal station signage with a line-colour flag on every page title.

### v1.103.251 · No ghost trains off the map
<sub>26 November 2026</sub>

- Fleet, Meet a train, passing trains, alerts and station pages no longer count a train or tram that has just dropped out of the live feed. Only the live map keeps those briefly, faded, so they don't flicker.
- Platform display: a link to a lettered platform ("15B") keeps it selected in the platform picker instead of showing it blank.
- Platform display: V/Line-only stations (Geelong, Ballarat, Melton…) no longer ask for metro times they can't have.

### v1.103.250 · Trams without GPS on the map
<sub>26 November 2026</sub>

- Live map: some running trams send no GPS (on a bad night a whole route like the 64 could look empty). Those trams now appear where their live stop times place them, drawn faded and marked "Estimated from its live times, not GPS". Each one switches to its real position the moment it reports one.
- Estimates are never recorded as sightings, fleet history or on-board checks.

### v1.103.249 · Hidden trams go straight away
<sub>26 November 2026</sub>

- Live map: switching trams (or trains) off now removes them immediately, instead of leaving faded copies on the map for up to two and a half minutes.

### v1.103.248 · Tidier tram destinations
<sub>26 November 2026</sub>

- Live map: a tapped tram's label now reads its destination as a place ("Central Pier") instead of the raw timetable stop name with its internal code ("D2-Central Pier/Harbour Esp"), matching the rest of the map.

### v1.103.247 · Trams show where they're going
<sub>26 November 2026</sub>

- Live map: a tram's bubble and its details now name where the tram is heading (its terminus), instead of just "Route 59". The tram feed carries no destination of its own, so it's taken from the end of the tram's trip. The details card still prefers the published run destination when it has one.

### v1.103.246 · Trams look steadier on the map
<sub>26 November 2026</sub>

- Live map: trams no longer fade or flicker just because Yarra Trams' feed is slow. A tram's position is treated as live for a bit longer (its feed runs about a minute and a half behind by nature), and a tram that briefly drops out is held on the map longer before it's removed. Genuinely dead positions still fade.

### v1.103.245 · Trams stop flickering off the map
<sub>26 November 2026</sub>

- Live map: when the tram feed briefly drops a tram (a tunnel, a depot, a GPS blip), it now stays on the map at its last position, faded, for a short while instead of vanishing and popping back. Trams get the longest grace since Yarra Trams' feed is the patchiest; buses get none, since a bus leaving is usually just you panning the map.

### v1.103.244 · Open any V/Line station's platform display by name
<sub>26 November 2026</sub>

- Platform displays: typing or linking a V/Line station by its plain name now works (e.g. /pid?station=Geelong), not just the exact "Geelong Railway Station". Southern Cross still lists all 16 platforms.

### v1.103.243 · Platform displays now work for V/Line stations
<sub>26 November 2026</sub>

- Platform displays: you can now open a station screen for V/Line-only stations like Melton, Cobblebank, Ballarat, Geelong and Seymour, not just the shared city ones. They were missing from the picker and wouldn't load before.

### v1.103.242 · Alamein and Williamstown 3-car shuttles shown correctly
<sub>26 November 2026</sub>

- Trains: the Alamein and Williamstown shuttles genuinely run single 3-car X'Trapolis units, so they're now shown as 3-car there. Everywhere else a lone 3-car reading is still treated as a 6-car train with a dropped partner, as before.

### v1.103.241 · Half-reported trains no longer look like 3-car services
<sub>26 November 2026</sub>

- Trains: when the live feed reports only one 3-car unit of a Comeng, X'Trapolis 100 or Siemens, it's now shown as the 6-car train it really is, not a 3-car service (Melbourne doesn't run those as 3-car). The known car numbers are unchanged; we still borrow the partner's numbers from recent history when we can.

### v1.103.240 · Route 509 now shows its real operator, more bus power types filled
<sub>26 November 2026</sub>

- Buses: route 509 is now shown as Kinetic, not Dysons. Every registered bus seen on it over the last 45 days is Kinetic, matching the neighbouring 503-508 routes.
- Fleet: filled in the power type (diesel) for three buses that were missing it (Ventura 877 and 842, Kinetic 222).

### v1.103.239 · Top search result no longer hides behind the filters
<sub>26 November 2026</sub>

- Map search: on phones the results list now opens below the Saved/Filters/Trains row instead of starting underneath it, so the first station (and the filter chips) stay fully visible.

### v1.103.238 · Picking an address on a phone now sticks
<sub>26 November 2026</sub>

- Plan a trip: tapping an address or stop from the From/To suggestions on a phone now selects it reliably. The list no longer closed itself a split second before your tap landed.

### v1.103.237 · Search results no longer hide behind the keyboard
<sub>26 November 2026</sub>

- Map search: on phones, the results list is now capped to the space above the on-screen keyboard, so lower stations like Bunyip stay visible and tappable instead of sliding under the keyboard.

### v1.103.236 · Ballarat, Bendigo and Gippsland trains back on platform displays
<sub>26 November 2026</sub>

- Platform displays and boards: V/Line trains whose line name says "via" (Ballarat via Melton, Bendigo via Gisborne, Traralgon via Morwell, Seymour, Shepparton) were mistaken for coaches and left off. They now show on every platform at Southern Cross, with Geelong.
- Platform displays: a platform screen now says Loading while V/Line times are still coming in, rather than saying no trains are announced.

### v1.103.235 · Saved stops up front, every Southern Cross platform
<sub>26 November 2026</sub>

- Map: Saved stops now sit at the start of the button row, right after Home, instead of off the edge of the screen on phones.
- Map: Sydney and NSW trains moved out of the main row into Filters, under Other states. The Lines button is now called Filters, because it also has train types and search.
- Platform displays: Southern Cross lists all 16 platforms, not just the ones with a train in the next few minutes. Picking Platform 2 also shows trains on 2A and 2B, and if V/Line hasn't announced a platform yet the screen says so.

### v1.103.234 · City Loop trains explain themselves
<sub>26 November 2026</sub>

- Plan a trip: a train signed Flinders Street that goes round the City Loop now says so, like "It goes round the City Loop first, stopping at Parliament and Melbourne Central", so you know it's the right train for the Loop.

### v1.103.233 · Line colours on every step
<sub>26 November 2026</sub>

- Plan a trip: each train step now has a badge in the line's colour, so you can tell your trains apart at a glance.

### v1.103.232 · Know which platform at a change
<sub>26 November 2026</sub>

- Plan a trip: when you change trains, the steps now say which platform the next train leaves from and which one you arrive on, or that it's the same platform.
- Plan a trip: "Get off at" shows the platform you arrive on, and the missed-train line now reads plainly: "Miss it? The next trains are 7:16 am and 7:24 am."

### v1.103.231 · Stations say Station
<sub>26 November 2026</sub>

- Plan a trip: train stations are now named in full, like "Footscray Station" and "Get off at Sandringham Station", so a station can't be mistaken for the suburb or a tram or bus stop. This covers the From and To boxes, the search list, walking directions and trip alerts.
- Plan a trip: cross-city trains now read the way the sign does, like "Take the train towards Sandringham. It runs through the city, so it's a Williamstown line train until Flinders Street."

### v1.103.230 · Who makes TransitAlert
<sub>26 November 2026</sub>

- About: a new section on who makes TransitAlert (comengfreak, a Melbourne train fan and spotter) and where to follow along.
- Behind the scenes: search engines and AI assistants now get a clear summary of what TransitAlert is, who makes it and where to get it.

### v1.103.229 · Late buses and trams stay on the board
<sub>26 November 2026</sub>

- Departure boards: a bus or tram with no live time used to vanish a minute or two after its timetabled time, even when it was just running late and hadn't reached your stop yet. It now stays for up to 10 minutes, marked "Due".
- Notifications on the website now show the new app icon (they still had the old one).
- iPhone app: the launch screen shows the TransitAlert icon instead of a blank placeholder.

### v1.103.228 · The iPhone app takes shape
<sub>26 November 2026</sub>

- Coming to iPhone: a trip you follow becomes a Live Activity on the lock screen and in the Dynamic Island, with the next stop counting down, stops left and your arrival time, kept up to date by TransitAlert even while your phone is locked. A heads-up arrives when your stop is next.
- Also coming: home and lock screen widgets for your saved stops, a Line status widget, and an Apple Watch app with watch face complications.
- Behind the scenes: the trip display now carries the next stop's time, your arrival time and stops left, ready for those countdowns.

### v1.103.227 · Getting ready for iPhone notifications
<sub>26 November 2026</sub>

- Behind the scenes: the server can now send notifications straight to the iPhone app through Apple's push service, including time-sensitive alerts that get through Focus. It switches on once the App Store account is set up.

### v1.103.226 · Proper iPhone home screen icon and link previews
<sub>26 November 2026</sub>

- iPhone: "Add to Home Screen" now uses the full-bleed icon, so it no longer gets black corners.
- Sharing a TransitAlert link in iMessage, WhatsApp, Discord and the rest now shows a big preview card with the new icon, not a small square.
- Fleet: the search box is labelled for screen readers.
- Search engines now know about Sightings, Fleet PIDS and the ticket inspector guide.
- Behind the scenes: the iPhone app project is ready for its first TestFlight build (push notifications, app links and an automatic build setup).

### v1.103.225 · Housekeeping
<sub>26 November 2026</sub>

- Privacy policy: the date at the top now says when it last changed (24 November, when the cookie-free visit counter was added).
- Behind the scenes: Metro's alert feed sometimes names stops "1", "2" and "3", which aren't real stations. TransitAlert no longer asks PTV for their names every few minutes.

### v1.103.224 · Cleaner sky on the app icon
<sub>25 November 2026</sub>

- Icon: the sky's colour bands now blend with an even checker instead of a jagged edge.

### v1.103.223 · App icon touch-up
<sub>25 November 2026</sub>

- Icon: tidier overhead wiring, and the fence behind the track is now see-through chain mesh.

### v1.103.222 · New app icon
<sub>25 November 2026</sub>

- New icon: a hand-made pixel-art Comeng (430M) in place of the AI-generated one, with a squarer cab face, a pantograph up to the wire, a see-through fence and the suburbs behind. It's on the website, the home-screen app and the Android and iPhone builds.

### v1.103.221 · Platform display links by station name
<sub>24 November 2026</sub>

- Platform display: a link with the station's name (/pid?station=Richmond or flinders-street) now opens that station's screen, not the station picker.
- Bus fleet: 6 more buses identified from Bendigo, Latrobe Valley, Geelong and Transit Systems fleet lists.
- Behind the scenes: Cloudflare's cookie-free visit counter was being blocked by the site's own security settings. It now runs, and the privacy policy says so.

### v1.103.220 · V/Line trains stay on the map without GPS
<sub>24 November 2026</sub>

- Map: V/Line trains that are running but not sending GPS (their position feed drops out often, and some trains never report) used to vanish. They now show faded where their live times put them, along the real track, marked "Estimated". Only trains V/Line's live feed says are running are shown, so a cancelled train isn't drawn, and each one switches to its real position as soon as it reports.
- Showgrounds and Flemington Racecourse: special-event trains now show platform 1 when PTV leaves the platform blank. Both stations only have the one platform.
- Bus fleet: 14 more buses identified from the operators' published fleet lists, including Ventura's BYD electric 1623.

### v1.103.219 · Stop lists start at the right station
<sub>24 November 2026</sub>

- Departure boards: a train's stops were sometimes worked out from the station before yours (Glenroy's from Jacana, Northcote's from Merri) when stations are under a minute apart, which could throw off the Loop and express notes. They now start from your station.

### v1.103.218 · Cancellations that say which train, and go away
<sub>24 November 2026</sub>

- When PTV posts a cancellation without saying which train, TransitAlert names it from the live feed, even after that train's time has passed ("Cancelled earlier: the 7:42 am Mernda to Flinders Street").
- Those notices no longer hang around all day: once the cancelled trains have gone and nothing else on the line is cancelled, the notice is retired and the line goes back to good service.

### v1.103.217 · Reports only from riders on board
<sub>24 November 2026</sub>

- "What's happening?" reports now need you to actually be on that train, tram or bus: your phone takes two location readings about 15 seconds apart and they're checked against the service's live position. Your location is only used for that check and is never saved.
- Trains, trams and buses on the map now keep gliding between position updates instead of moving, stopping and moving again. Thanks to a rider for the feedback.
- Map labels read a train's cars in order, unit by unit (433M-1067T-434M + 518M-1126T-551M).

### v1.103.216 · "You are here" on the platform display
<sub>24 November 2026</sub>

- Platform display: the stop list now starts at the station you're at, marked "You are here", and shows every station the train runs straight through after it. Stations skipped right after yours used to go missing.
- Platform display: tell it which car your screen lines up with (You are at car 1–7) and the train diagram marks it, and warns when a shorter train stops short of you.
- Express trains now say what they skip ("Express: skips East Richmond") or the stretch they run without stopping ("Camberwell → Richmond"), instead of listing every stop.
- Stickers theme: three of the new stickers in page headers ("Go on. Delete the other one.", "The tram is NOT 2 mins away" and "I have never run for a train*"), bigger on desktop.

### v1.103.215 · PIDs end where the train ends
<sub>24 November 2026</sub>

- Platform display: a city-bound train signed to Flinders Street now lists its stops to Flinders Street. It used to carry on through Southern Cross to Parliament, which is the next service going round the Loop.

### v1.103.214 · A short link for stickers
<sub>24 November 2026</sub>

- transit-alert.com/s opens the app, for QR codes on stickers. Scans are counted only as an anonymous daily total, like page views.

### v1.103.213 · The real stickers
<sub>24 November 2026</sub>

- The Stickers theme now uses the actual TransitAlert stickers (square, round and holo) in page headers, with colours to match them: deep purple, magenta and the app icon's sky blue, and a holographic stripe across the top.

### v1.103.212 · Clearer old cancellation notices
<sub>24 November 2026</sub>

- When PTV's "Cancellation" notice doesn't name a train and nothing on that line is showing as cancelled, the notice now says so and when PTV posted it, so an old morning notice doesn't look like it's still happening.
- Stickers theme: smaller stickers on phones, so page titles keep their room.

### v1.103.211 · Disruptions that say something
<sub>24 November 2026</sub>

- When PTV posts a disruption that just says "Cancellation", TransitAlert now lists the trains the live feed shows as cancelled on that line, with times. If it can't tell, it says so and points you to the departure boards.
- "Full details on Transport Victoria" only shows when there's a real page about that disruption. It used to link to PTV's general updates page.

### v1.103.210 · Better themes, snow and stickers
<sub>24 November 2026</sub>

- Every theme has its own livery stripe across the top of the screen and an accent line under page titles: Connex blue, white and red, Comeng stainless and orange, Evie hazard stripes and more.
- Christmas now has gently falling snow. It never gets in the way of a tap, and it's off if your phone is set to reduce motion.
- New free theme: Stickers. Bright pink, yellow and blue, rounder corners, stuck-on shadows and a few stickers in page headers.
- Easier-to-read buttons in the Connex, Christmas and Retro regional themes.

### v1.103.209 · Ticket checks: know your rights
<sub>24 November 2026</sub>

- New page in the menu (More → Ticket checks: your rights): what authorised officers can and can't ask for, that you can ask to see their ID, that they can't search your bags, how to complain if you're treated badly, and how to ask for a review of a fine. Every point links to the official page it comes from.

### v1.103.208 · Through trains to Sandringham
<sub>24 November 2026</sub>

- Werribee and Williamstown line trains that run straight through to Sandringham now show Sandringham, with every stop, on departure boards and the Platform display. They used to stop at "Flinders Street". Trains that really end at Flinders Street still say so.

### v1.103.207 · No more few-second freezes
<sub>24 November 2026</sub>

- Fixed the app sometimes freezing for 1 to 9 seconds for everyone. Saving train history from the live map waited on another part of the app writing to the same file; now it saves every 30 seconds instead of on every map refresh, and never waits.

### v1.103.206 · Fewer map crashes on iPhone
<sub>24 November 2026</sub>

- Fixed a crash on iPhone ("The object can not be found here") when part of the map page was moved by something outside the app, like Safari's Translate or a map popup closing at the wrong moment.
- Crash reports now say which part of the screen broke (by its name in the code, nothing about you), so they can be fixed faster.

### v1.103.205 · Door sides at Box Hill and Blackburn
<sub>24 November 2026</sub>

- Box Hill platform 4 and Blackburn platform 3 now show which side the doors open (left going out, right going to the city). They're worked out from the platforms' positions on the map and checked against the door sides we already had for both stations.

### v1.103.204 · Loop trains say Flinders Street
<sub>24 November 2026</sub>

- City-bound trains that run round the City Loop now show "Flinders Street" instead of "City Loop service", with "Flinders Street first, then round the City Loop" underneath. Thanks to a rider at Clifton Hill for the feedback.

### v1.103.203 · Know which way it's going at Richmond
<sub>24 November 2026</sub>

- Departure boards now say how a city-bound train gets to Flinders Street: "City Loop first (next stop Parliament)", "Flinders Street first, then round the City Loop" or "Straight to Flinders Street".
- Express trains say where they run without stopping, like "Express: stops at Glenferrie, Camberwell, then all stations (skips 4)".
- City-bound trains starting part way along a shared line say which line they're on ("Lilydale line · from Ringwood"), and "a Alamein train" is now "an Alamein train".
- 6-car trains that change lines at Flinders Street (a Hurstbridge train becoming a Belgrave one) no longer show as 3 cars when the live feed drops the second set.
- Train panels have a "Wrong set or car count?" link right under the consist, so riders on board can tell us what's really there.

### v1.103.202 · Tidier boards in Hindi, Greek and French
<sub>24 November 2026</sub>

- The "Scheduled" status is shorter in Hindi, Greek and French, so it no longer runs out of its column on the departure board.
- transit-alert.com/play is a short link to TransitAlert on Google Play, easy to share.

### v1.103.201 · Seven more languages
<sub>24 November 2026</sub>

- Settings → Language now has 繁體中文, Tiếng Việt, Ελληνικά, Italiano, हिन्दी, Español and Français as well as English and 简体中文. The menu, departure boards, countdowns and train notes are translated; the rest of the app stays in English for now. Station and line names always match the signs.
- "5 min ago" now reads the right way round in every language ("il y a 5 min", "hace 5 min").

### v1.103.200 · Disruptions for widgets
<sub>24 November 2026</sub>

- Behind the scenes: the home-screen widget feed now carries the most serious disruption on your stop's lines, ready for the iPhone lock screen and line-status widgets. Saved stops use the same check, so both always agree.

### v1.103.199 · Getting ready for iPhone
<sub>24 November 2026</sub>

- Behind the scenes: the app now knows whether it's running on Android, iPhone or the web, so the coming iPhone app won't show Google Play buttons.

### v1.103.198 · Tell riders what's happening on board
<sub>24 November 2026</sub>

- "On this service now" has a What's happening? menu with more to report: running slow, plenty of seats, dirty or a spill, antisocial behaviour, smoking or vaping, a blocked wheelchair space or a door out of order, as well as stopped, crowded, incidents and broken aircon.

### v1.103.197 · On-time figures that keep counting
<sub>23 November 2026</sub>

- Fixed the new trip-by-trip "usually on time" figures, which weren't saving any trips. They now build up as trips finish, and routes switch over to them once there's enough history.

### v1.103.196 · Truer numbers
<sub>23 November 2026</sub>

- TransitAlert now times how long trains actually stand at each station. Where it differs from the timetable, the train's stop list says so ("2 min dwell · usually 40 sec").
- "Usually on time" figures now count each trip once, so a single long late run no longer drags a route's numbers down.

### v1.103.195 · V/Line coaches in the trip planner
<sub>23 November 2026</sub>

- The planner now uses V/Line coaches: Cowes, Inverloch and Phillip Island get a train to Dandenong and the coach, instead of no route at all.
- V/Line trips that end far from town, like Torquay, list the bus or coach that finishes the trip and the station it leaves from (bus 52 from Marshall, 53 from Geelong), with the first one after your train gets there.
- Fleet: follow a bus by its rego even if it hasn't run lately (one in the workshop, say), and get a push the first time it's back out.
- Fleet: searching a fleet number that more than one depot uses now says so, and suggests searching the rego.

### v1.103.194 · Straighter answers for far-flung trips
<sub>23 November 2026</sub>

- When no train or bus reaches your destination, the planner says so plainly instead of suggesting a walk of many kilometres (like Waurn Ponds to Torquay).
- "Or catch any of these" only lists rides in the next few hours, not a weekend bus days away.
- Fleet favourites say which two still alert you if you have more saved on a free account.

### v1.103.193 · Follow two for free
<sub>23 November 2026</sub>

- Free accounts can now follow two vehicles, like your favourite bus and your favourite train, with a push when each comes out.
- Fleet favourites explain that notifications need turning on once in TransitAlert, not just allowed in your phone's settings.
- Fleet favourites no longer say "0 Metro sets tracked so far".

### v1.103.192 · Better trips to places far from a train
<sub>23 November 2026</sub>

- Trips to places a long way from the trains, like Mount Martha, now look for a bus from each nearby line's station, so the 788 from Frankston is offered instead of an overnight wait and a 13 km walk.
- Fleet: search buses by fleet number (like T130 or 130), not just rego.

### v1.103.191 · Tidier stop boards
<sub>23 November 2026</sub>

- Tram and bus stop boards show a "Pick a time" button instead of an empty date box, and the picker opens already set to now.

### v1.103.190 · Buses show the trip they're on
<sub>23 November 2026</sub>

- Some bus companies list a bus against its upcoming trips too. TransitAlert now shows the trip the bus is actually running, rather than a later one, and no longer warns that it's linked to several services.

### v1.103.189 · Departure boards read clearly
<sub>23 November 2026</sub>

- Screen readers now pause between a departure's destination, its Express badge and the notes under it, instead of running them together.

### v1.103.188 · Clearer delay numbers
<sub>23 November 2026</sub>

- Delays right now reads "2 running 5+ min late · worst 13 min late" instead of "2 5+ min late · worst 13 min".
- Route names on Disruptions get their missing spaces back, like St Kilda (Fitzroy St).

### v1.103.187 · Cleaner trip planner search
<sub>23 November 2026</sub>

- Place search no longer offers places in New South Wales or the ACT that the network doesn't reach (towns just over the Murray still show).
- Tram stops in search just say "Tram stop", and screen readers no longer hear it twice.
- Screen readers now hear that stations like Flinders Street have both metro and V/Line trains.

### v1.103.186 · Fewer false live-data warnings
<sub>23 November 2026</sub>

- A train, tram or V/Line that has just reached the end of its trip no longer says its next stop is unavailable.
- Trams passing stops nobody is waiting at are no longer flagged as skipping stops.
- At a changeover, a vehicle now shows the trip it's starting rather than the one it just finished.

### v1.103.185 · Behind-the-scenes tools
<sub>23 November 2026</sub>

- New admin tools for keeping bus details accurate, including a list of buses on the road that still need their fleet details checked.

### v1.103.184 · Find every electric bus
<sub>23 November 2026</sub>

- Fleet → Buses: new power-type chips (Electric, Hybrid, Diesel, with live counts) filter the list, and work together with the operator chips, so you can see every electric Kinetic bus running right now.

### v1.103.183 · Power type for every bus
<sub>23 November 2026</sub>

- Fleet → Buses: every bus in the list now shows its power type (diesel, hybrid, electric) and model from the bus register. Only the first 50 buses were being looked up, so over a thousand showed nothing.

### v1.103.182 · Tidier bus list
<sub>23 November 2026</sub>

- Fleet → Buses: a bus whose engine type isn't known no longer says "Unknown"; it just shows the operator (and fleet number or model when known).

### v1.103.181 · Heritage fits your phone
<sub>23 November 2026</sub>

- Heritage: the Newport Railway Museum card was wider than a phone screen, so its right side (the address and some details) was cut off. It fits now.

### v1.103.180 · Readable Now tag
<sub>23 November 2026</sub>

- Train panel: the "Now" tag on the current trip is readable again on dark-coloured lines like Lilydale and Glen Waverley.

### v1.103.179 · Fleet PIDS fixes
<sub>23 November 2026</sub>

- Fleet PIDS on iPhone: the EDi Comeng sign (and the other LED signs) no longer runs off the right edge of the screen when the phone is upright.
- EDi Comeng sign: it no longer says "This train terminates at" a station that isn't the train's destination (it said Westona for a Werribee-line train whose trip data stopped early).
- If you've already started tapping when the update notes arrive, they now show as a small notice with a See button instead of a box over the map.

### v1.103.178 · Real station codes on train trips
<sub>23 November 2026</sub>

- Train panel: the small trip tags now use real station codes ("Up UFD→FSS", "Down FSS→CGB") instead of guessed ones like "U", "C" or "RIC" for Richmond. If a station has no known code, the tag is left off rather than guessed.

### v1.103.177 · A home for people coming from Instagram
<sub>23 November 2026</sub>

- New page at transit-alert.com/ig for the @transit.alert link in bio: open the live map with no sign-up, get the Android app, or add it to an iPhone, plus quick links to the things the reels show.

### v1.103.176 · Easier-to-read Big countdown
<sub>23 November 2026</sub>

- Platform display, Big countdown: the huge minutes number is now readable in dark line colours like Glen Waverley and Lilydale navy, and "Now" or "Cancelled" fit a phone screen.

### v1.103.175 · Make the platform display your own
<sub>23 November 2026</sub>

- Platform display: tap the screen (or press C on a keyboard) and choose Customise. Pick from seven looks, including two new ones: a split-flap departures board with flipping letters, and a Big countdown you can read across the room.
- Also in Customise: text size, 12- or 24-hour clock, colour (line colours, amber, green, white, red or blue), your own message scrolling along the bottom, and Copy link, so a TV opened with that link keeps the look. Your last look is remembered for next time.
- Make your own train (in Customise): type a destination, the stops (put - before stations it runs through), a stopping pattern, time, platform and line colour, and it shows first on the screen with the real trains after it. Only on your screen, never a real service.
- Fix: on a computer or TV the side menu no longer sits over the left of the display (it hid the departure time on the LED look). It now opens only from the menu button.
- Fix: the other looks said "No trains soon" while times were still loading; they now say Loading.

### v1.103.174 · Train services in plain words
<sub>23 November 2026</sub>

- Train panel and departure boards: a service now reads "The 9:37 am Sandringham service" instead of "The 09:37 S Service" (the made-up station codes are gone).
- A tram between trips (at a terminus) now says how far it is from the nearest train station, by name, instead of a bare "near Watsonia (2.6 km)" that read like a tram stop.

### v1.103.173 · Tidier alert cards
<sub>23 November 2026</sub>

- Disruptions: when an alert's label is long (like "Service Information"), its time no longer wraps onto a new line starting with a stray dot.

### v1.103.172 · Real problems before car park notices
<sub>23 November 2026</sub>

- Disruptions: tapping a line or route now lists cancellations, delays, buses replacing trains and police or weather notices first, even ones starting later today. Station notices go to the bottom, with lifts out of service first, then car park and other works. Before, an open-ended car park closure could sit above a cancellation coming up in an hour.

### v1.103.171 · Cleaner trip planner search
<sub>23 November 2026</sub>

- Plan a trip: a tram stop no longer shows up twice in the suggestions (once per direction), and a station already listed at the top isn't repeated as a place below it.
- The What's new card no longer pops up over you while you're typing; it waits for your next visit.

### v1.103.170 · Pin your routes on Delays
<sub>23 November 2026</sub>

- Delays right now: tap the star next to a line or route to keep it at the top. Pins are saved on this device, and a pinned route with nothing live stays on the list, dimmed.
- Delays right now opens on the tab you used last (trains, trams, buses or V/Line).

### v1.103.169 · Quiet nights for alerts
<sub>23 November 2026</sub>

- New in Smart notifications: Quiet nights. Turn it on and from 10 pm to 6 am only major disruptions and a trip you're tracking come through (the rest isn't saved for the morning).
- Near me: if location is blocked, there's now a link to find a stop on the map instead of a dead end.
- Glance: a first visit now explains what the page is for, with a button to find stops near you.
- Delays right now: "0 5+ min late" now reads "none running 5+ min late", and routes with only one vehicle live say why they're listed last.
- Fleet → Sprinter railcar leads with a one-line summary; the full rundown of the swaps is one tap away.

### v1.103.168 · Stony Point Sprinters, explained
<sub>23 November 2026</sub>

- Tapping a tram stop on the map no longer also pops up the tram routes list over the stop's panel.
- Fleet → Sprinter railcar now lists how the Stony Point Sprinters work, from riders' reports: two leased at a time, swapped on Thursday and Sunday nights, which trips run as single railcars, and the last reported pair (7003 and 7005), with a link to post the current pair as a sighting.

### v1.103.167 · Freight sightings where you need them
<sub>22 November 2026</sub>

- Freight cards for trains with no public times (the Apex quarry train, Long Island steel) now show riders' sightings at that station from the last 24 hours.
- "Seen it? Post a sighting" on those cards opens the Sightings form already filled in with the station and train, instead of the general feedback form.
- Fleet: the Stony Point Sprinter note now explains the swaps (Thursday and Sunday nights, via Southern Cross) and how the pair runs during the day, from riders' reports.

### v1.103.166 · Tram routes on the map
<sub>22 November 2026</sub>

- Zoom in to street level and the live map draws every tram route in its own colour, under the train lines. Tap a line to see which routes run along that street.
- Pick tram routes in the map filter and those routes show at any zoom, drawn bolder.
- Settings → Show tram routes turns them off.
- Freight: the Apex quarry train (Apex Quarry, Kilmore East to Westall) now has a card at Westall and Broadmeadows. It has no public timetable, so report sightings to help build a picture of when it runs.
- Fleet: picking the Sprinter railcar chip shows riders' tip that the Stony Point railcars usually swap on Thursday and Sunday nights.
- The loading-screen Sprinter is redrawn in today's V/Line purple and yellow, and tapping a tram line on the map is easier.

### v1.103.165 · Better loading screen, cleaner Fleet PIDS
<sub>22 November 2026</sub>

- Loading screen trams and buses redrawn properly: E-class in PTV green and lime, a lined W-class, and PTV-orange hybrid and electric buses.
- The loading screen stays up long enough to see on fast connections (up to 1 second on your first visit; tap to skip), then fades.
- Fleet PIDS: the customise section is gone; screens follow the live train or the example. A live train with no usable destination shows its line instead of "Destination unavailable".
- V/Line vehicles without a matched trip show their line instead of "Destination unavailable".
- Route stamps: on a tram or bus, open it on the map and tap "Stamp ride" (signed in). Your first ride on each route number is stamped in Passport under the new "Routes ridden" (GPS has to match the vehicle live).
- Heritage: the Mornington Railway (Tait 98G and Hitachi 1946T still run there) replaces the Newport Workshops card, and cards get drawings.

### v1.103.164 · What Premium gets you
<sub>22 November 2026</sub>

- Your account page now lists what Premium includes: spotter alerts for a set or a whole class, full vehicle history, passing-through trains, train numbers and workings, freight timetables, Fleet PIDS and 10 retro themes. It used to say Premium adds the Fleet page, which has been free since 1.103.161.
- Following a train is now free for one set or class, with a push when it comes out. Premium follows as many as you like; past your free one, the star explains that instead of lighting up and quietly going out.
- Evette (IEV120) no longer counts ordinary runs of Comeng sets 586 and 634 as Evette sightings.
- A vehicle's history no longer says "last seen" twice, and a trip seen only once reads "Seen near North Melbourne" instead of "near North Melbourne → near North Melbourne".
- Fleet no longer has a Premium badge in the menu.
- New free themes: Light mode, Christmas and Halloween (Movember is still there too). Settings → Theme.
- The beta app shows the train loading screen while it checks your beta access, instead of a grey placeholder.
- New setting: Comeng names. Show EDI and Alstom Comengs as SS and NS Comengs if that's what you call them.
- Fleet history, vehicle pages and train panels name the train type everywhere, not just "Set 586".
- New loading-screen trains, drawn properly: a Comeng in PTV colours most of the time, with X'Trapolis 100s, Siemens, HCMTs, the odd Hitachi, V/Line VLocitys, Sprinters and N class, E- and W-class trams, and hybrid and electric buses turning up too.
- Favourites name the train type, like "Alstom Comeng Set 586" or "G class Set 6", instead of just "Set 586".
- Fleet has nostalgia chips for retired trains: Hitachi, Harris, Tait and the old parcels vans. Tap one to see what's left of them and where.
- Heritage trains has a new "Where to see them" section: what's at the Newport Railway Museum (Harris, Hitachi and Swing Door cars, Heavy Harry and more) and what Elecrail keeps at Newport Workshops, including Hitachi 298M and parcels van 2CM.
- A train's panel shows how it's running and where it is straight under the title, and its earlier and next trips read in plain words ("Arrived from Frankston", "To Flinders Street") with the Up/Down code as a small tag.

### v1.103.163 · Cleaner map in the city
<sub>22 November 2026</sub>

- At city zoom each train is one marker again instead of a row of carriage boxes, so busy stations like Flinders Street stay readable. Zoom in close, or tap a train, to see its carriages.

### v1.103.162 · Clearer Premium message
<sub>22 November 2026</sub>

- Opening a vehicle's full history without Premium now says that's the Premium part and the live fleet list and search are free, instead of "Sign in to use Fleet".

### v1.103.161 · Share your journey, and Fleet for everyone
<sub>22 November 2026</sub>

- New Share journey button in Plan a trip. It sends "I'm coming from Federation Square to Monash University. Leaving 3:42 pm on the Pakenham line › Bus 733, getting in about 4:20 pm" with a link that opens the same trip live.
- Fleet is now free: every train, tram, bus and V/Line on the live list, search, stabled and off-feed. Each vehicle's full sighting history stays Premium.

### v1.103.160 · Only notices that touch your trip
<sub>22 November 2026</sub>

- The trip planner no longer shows a bus or tram stop closure on your trip when PTV says it's at a stop you're not using. A Clayton to Monash 733 trip showed a closure at Carroll Rd/Centre Rd. Notices that don't name their stops still show, so nothing gets missed.

### v1.103.159 · Your station first on Near me
<sub>22 November 2026</sub>

- Standing on a station's platforms, Near me now shows that station at the top. At Glen Huntly the tram and bus stops by the entrance were listed first because they measured closer than the middle of the platforms.

### v1.103.158 · Clearer disruption cards and departures
<sub>22 November 2026</sub>

- A planned disruption on the map now says when it was posted ("posted 30 Oct") instead of "updated 23 days ago", which looked like old live data. Recent edits still say "updated 20 min ago".
- Platform numbers on departure boards are bigger and bolder, and each departure has a little more space.

### v1.103.157 · Tidier train length buttons
<sub>22 November 2026</sub>

- On V/Line panels, the "Report length" buttons are just numbers (3 4 5 6 7), with "carriages" written once after them. On a phone the row ran off the edge of the screen.

### v1.103.156 · Smoother at busy times
<sub>22 November 2026</sub>

- The background bus U-turn check now pauses every 40 milliseconds to let the app answer you, instead of every 25 buses. At daytime bus numbers it was still freezing the app for up to 2 seconds.

### v1.103.155 · Where's that N class going next?
<sub>22 November 2026</sub>

- Tap an N class locomotive on the map to see its next working: "Usually the 6:08pm Southern Cross to Swan Hill", with today's time and how often it's held.
- V/Line station boards tag trains that are usually N class hauled.
- Both are worked out from the last six weeks of the live feed's own locomotive labels. V/Line doesn't publish locomotive rosters, so this is shown as "usually" or "likely", never as certain.

### v1.103.154 · V/Line trains keep moving
<sub>22 November 2026</sub>

- V/Line trains on the map are fresher. When V/Line's feed sent an update stamped older than the last one, the app threw the whole update away and kept showing positions about 2 minutes old. It now keeps each train's newest position.

### v1.103.153 · Your stop is next
<sub>22 November 2026</sub>

- Start a train trip in Plan a trip and you get a "Flinders Street is next" alert about 4 minutes before your stop, using the train's timetable and its latest delay.
- Long train rides (Southern Cross to Ballarat) stay watched until you arrive. Before, alerts stopped 30 minutes after the train left.
- The live trip notification on Android is now free for everyone who's signed in. It was Premium.

### v1.103.152 · No more "Now" on tram and bus boards
<sub>22 November 2026</sub>

- Tram and bus stop boards mark the service about to leave as "Departing" instead of "Now", and count it down as "<1 min" instead of a second "Now".

### v1.103.151 · Small fixes
<sub>22 November 2026</sub>

- Glance no longer hides the first stop's name behind the menu button.
- A tram stop opened from a link, like Flinders Street #13, now shows the stop's name instead of "Stop 2204".

### v1.103.150 · No more "Due" and "Now"
<sub>22 November 2026</sub>

- A bus, tram or train's stop list and panel show a stop it hasn't reached yet as "<1 min" instead of "Now".
- Once a stop's time has passed but the vehicle isn't there yet, they show the time it was expected ("7:47 am") instead of "Due", and the panel says "Expected" instead of "Was due".

### v1.103.149 · Tidier bus panels
<sub>22 November 2026</sub>

- Bus panels no longer show a "Boarding access" row that only said "Select a bus stop for published access details". Each stop's own board still has its access details.

### v1.103.148 · Bus headings name the place
<sub>22 November 2026</sub>

- A bus or tram panel now says "To Middle Brighton Station" instead of "To Middle Brighton Station/Male St". It does the same for shopping centres, hospitals, schools and the airport. Street corners like "High St/Doncaster Rd" stay whole.

### v1.103.147 · Cleaner bus boards
<sub>22 November 2026</sub>

- Each 250 bus now shows once. PTV also lists every 250 and 251 trip under a "250-251 combined" route, so Melbourne Central showed each bus twice.
- A bus or tram that reports its own running time now shows "On time" or "3 min late" on its panel, instead of "No live timing" whenever its next stop had no estimate.
- Bus station boards say "Board at the marked stop" once, not on every row (Box Hill said it 13 times).

### v1.103.146 · See what's coming later today
<sub>22 November 2026</sub>

- Every Metro line, tram, bus and V/Line route with changes starting later today shows a "Changes from 12pm" heads-up, even while it's still running normally.
- Routes with changes coming up sort ahead of the ones with nothing planned, and bus routes with a heads-up get their own row.
- The tram, bus and V/Line headers say "Changes later on 11 routes" instead of a plain "Good service".

### v1.103.145 · Heads-ups wait their turn
<sub>22 November 2026</sub>

- A notice like "Due to a rally from 12pm today, service changes affect city trams" now starts at noon. Posted just after midnight, it had marked 12 tram routes as disrupted all morning.

### v1.103.144 · Glance matches your saved stops
<sub>22 November 2026</sub>

- A saved bus interchange bay (Frankston Bay B) shows every route on Glance, the same as in Saved stops. Before, routes like the 782 went missing.
- Glance names the bay ("Bay B"), so two bays at the same interchange no longer look the same.
- A cancelled service stays on Glance with its timetabled time struck out, instead of quietly disappearing.

Older updates: pick one above, or go straight to [15–21 November 2026](changelog/2026-11-15.md).
