# TransitAlert changelog

Every TransitAlert update since the first commit on 13 April 2026: 286 entries, up to version 1.103.225. The same notes are in the app at [transit-alert.com/changelog](https://transit-alert.com/changelog).

## Every week and month

| When | Updates |
| --- | --- |
| [22–30 November 2026](changelog/2026-11-22.md) | 82 |
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
