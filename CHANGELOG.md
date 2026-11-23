# TransitAlert changelog

Every TransitAlert update, newest first: 262 entries, from the first commit on 13 April 2026 to version 1.103.201. The same notes appear in the app at [transit-alert.com/changelog](https://transit-alert.com/changelog).

## November 2026

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

### v1.103.143 · Tidier V/Line boards
<sub>21 November 2026</sub>

- V/Line boards say "Southern Cross" and "Waurn Ponds", not "Southern Cross Station", and station titles drop "Railway Station" ("Geelong").
- A cancelled train shows its timetabled time, struck out, instead of a countdown that looked like it was still coming.

### v1.103.142 · Smoother under load
<sub>21 November 2026</sub>

- Fixed a background job that could freeze TransitAlert for several seconds at a time (up to 9 s) while it checked buses for U-turns, so boards and maps no longer stall mid-load.

### v1.103.141 · Clearer bus and train panels
<sub>21 November 2026</sub>

- A bus no longer says "Next stop information is unavailable" right above the next stop it found.
- "Last known position" reads "about 80% of the way", "almost there" or "just left" instead of a bare percentage.

### v1.103.140 · No more early trains
<sub>21 November 2026</sub>

- A train's stop list no longer says "2 min early" at every stop to the end of the line while the train is running on time. Trains wait at timing points rather than leave early, so after the next stop the list shows timetable times.

### v1.103.139 · Where your train really came from
<sub>21 November 2026</sub>

- Metro trains don't start at Southern Cross or the Loop: PTV just starts the run there. Boards now show where the train really came from ("Sandringham, from Werribee"), or "via the City Loop" / "via Southern Cross" when that can't be told, instead of "from Parliament" or "from Southern Cross".
- Southern Cross: a coach's "Coach Terminal" lights up the coach terminal on the station layout, beside SkyBus at the north end. PTV doesn't publish coach bay numbers, so the bay is on the terminal's own screens.

### v1.103.138 · Cleaner boards, smarter plans
<sub>21 November 2026</sub>

- Platforms are now neat tappable pills, and where a train comes in from reads quietly ("Comes in on the Hurstbridge line") instead of in warning orange.
- Journey plans point out a sooner route: "Sooner: route 733 goes to Monash University too, leaving in 27 min", where the plan picked a bus 52 minutes away.
- "Walk 30 m to Dandenong station" instead of "from Dandenong Station to Dandenong station". Long waits read "1 h 43 min", not "103 min".
- A Metro train, tram or bus cancellation leaves the board 2½ hours after that trip left: Flinders Street still led with a 1:29pm cancellation at 7pm.
- Stop codes no longer leak into destinations ("7C-MCG Gates 4-7" is now "MCG Gates 4-7").

### v1.103.137 · Tap a platform
<sub>21 November 2026</sub>

- On any train or V/Line station board, tap a train's platform to see only what leaves from there. "Show all platforms" brings the rest back. Southern Cross still shows the platform on its station map.
- Fixed a crash ("Signal fault") that could hit when opening a station before the map had finished laying out.

### v1.103.136 · One train, one alert
<sub>20 November 2026</sub>

- A cancelled Metro Tunnel train no longer sends two alerts. PTV splits each one in two at Anzac and posts a notice per line, so riders got "East Pakenham service through the Metro Tunnel has been cancelled" and then "East Pakenham to Sunbury has been cancelled". Each device now hears about a train once in 3 hours, unless the news about it changes (late, then cancelled).

### v1.103.135 · Leaving Southern Cross, not arriving
<sub>20 November 2026</sub>

- A delayed coach or V/Line train leaving Southern Cross read backwards: "The 3:20pm Southern Cross to Barmah coach" was shown as "The Barmah coach due at Southern Cross at 3:20pm". It now reads as PTV wrote it.
- A notice about one late or cancelled trip leaves Disruptions six hours after that trip left (plus its delay), even when PTV keeps it up until 2am.

### v1.103.134 · Whose team it is
<sub>20 November 2026</sub>

- Notices written in PTV's own voice now say whose staff they mean: "Transport Victoria's Passenger Support team will be travelling along this route tonight", not "Our…", which read as if it were TransitAlert's.

### v1.103.133 · Transit Alert in your Discord
<sub>20 November 2026</sub>

- Run a Discord server? Add the Transit Alert bot from transit-alert.com/discord/add, then a server manager uses /alerts follow to post the lines they choose into a channel. It only asks to view channels, send messages and embed links, and never reads messages.

### v1.103.132 · Late coaches clear once they're in
<sub>20 November 2026</sub>

- A notice about one late V/Line train or coach ("due at Southern Cross at 3:20pm is delayed 60 minutes") leaves Disruptions once it has got in, instead of staying up until 2am.

### v1.103.131 · Tomorrow's notices, tomorrow
<sub>20 November 2026</sub>

- A live update about tomorrow ("Due to a rally from 5pm, Saturday 21 November…") is now listed as planned for then, not in force tonight.
- Staff and information notices ("Our Passenger Support team will be travelling along this route tonight") no longer mark tram routes as disrupted: Disruptions said 13 tram routes were disrupted when none were.

### v1.103.130 · Any tram that gets you there
<sub>20 November 2026</sub>

- Journey plans list the other routes making the same ride: Flinders Street to Melbourne University offered only route 16, with routes 1 and 67 leaving minutes later from the same stop. Same for buses (200 or 207).

### v1.103.129 · The side you tapped, first
<sub>20 November 2026</sub>

- A tram stop with a platform each side opens on the side you tapped: Melbourne University's north side showed under the south side's board.
- No more "Next tram 0": PTV's placeholder for a tram not yet allocated is treated as unknown.
- Tram numbers read the same everywhere, with their class (Z3 175, B2 2104), even before the tram shows on the map.
- Delays: "worst" only shows when a tram or bus really is 5+ minutes late.

### v1.103.128 · Arriving, on Near me too
<sub>20 November 2026</sub>

- Near me lists the trams and buses on their way to finish at a stop, and at an interchange which bay each one pulls into. Tap one to follow it on the map.

### v1.103.127 · Exact matches first
<sub>20 November 2026</sub>

- Search lists exact matches first: "901" showed five trains whose carriage numbers contain 901 before any 901 bus.

### v1.103.126 · Bus routes in search, anywhere
<sub>20 November 2026</sub>

- Searching a bus route like 788 while zoomed out said "Nothing matches". It now finds that route's buses wherever they are.
- Bus search results show each bus's fleet number as well as its rego, like "Route 788 · #1594 · BS10SL".

### v1.103.125 · See what's arriving
<sub>20 November 2026</sub>

- Tram and bus stop boards now show services arriving to end at that stop, not just ones departing, so a terminus or interchange bay no longer looks empty while trams and buses pull in.
- Tap an arriving tram or bus to follow it on the map.

### v1.103.124 · Saved bays that show every bus
<sub>20 November 2026</sub>

- A saved interchange bay could miss buses that leave from it (Frankston Bay B left out the 782). Saved bays now show every route from that bay.
- Tap a saved tram or bus stop on Departure boards to open its live board on the map.
- A shared or saved link to a bay now takes you to that bay, instead of listing every bay's buses.

### v1.103.123 · Tap a bus to see its times
<sub>20 November 2026</sub>

- On Near me, tapping a bus at an interchange opened Bay A and listed buses from every bay. It now opens the bay that bus leaves from, showing just that route.
- Every tram and bus on Near me can be tapped to open its stop's live departures.
- In a station's "Buses from here" list, tap a bay for all its departures or a route for just that route's times.
- An interchange on Near me lists its next buses in bay order (A, B, C…) so your bay is easy to find.

### v1.103.122 · Tidier bus bays
<sub>20 November 2026</sub>

- Broadmeadows station's bus bays no longer mix in the shopping centre's bays next door, so the 901 isn't listed at two different bays.
- Searching a bus number shows that number in the result, like "Route 788 · #1594".

### v1.103.121 · Which bay your bus leaves from
<sub>20 November 2026</sub>

- Journey plans now say which bay to wait at when your bus leaves from an interchange, like "Dandenong Station · Bay 7" for the 800.
- Train stations with a bus interchange list every bay and the buses that leave from it, under "Buses from here".

### v1.103.120 · Bus numbers found anywhere
<sub>20 November 2026</sub>

- Searching a bus number now finds the bus wherever it is, even when it's off screen or you're zoomed out.

### v1.103.119 · Find a bus by its number
<sub>20 November 2026</sub>

- Search now finds a bus by the fleet number painted on its side, like 1594, not just its number plate.

### v1.103.118 · Clearer Sydney notices
<sub>20 November 2026</sub>

- Sydney train notices titled just "Cancelled", "Running late" or "Starting from" now say which line and why, like "T4 Eastern Suburbs & Illawarra Line: Cancelled due to urgent train repairs".
- Some Sydney notices linked to Transport for NSW's developer website; they now open the public transportnsw.info page.
- Sydney departure boards no longer say a train runs "via" the station you're looking at.

### v1.103.117 · Behind the scenes
<sub>20 November 2026</sub>

- The anonymous page-view counts now include the platform display, status, SRL, Western Sydney Airport and sightings pages, which were all counted as "other".

### v1.103.116 · Search finds what you meant
<sub>20 November 2026</sub>

- Typing a station, like "Flinders St" or "Southern Cross", now puts the station first instead of a nearby tram stop.
- A street address like "1 Collins St" finds that address before tram stops with similar names, and "uni" is read as university.

### v1.103.115 · Know when favourites can't reach you
<sub>20 November 2026</sub>

- Fleet favourites now warn you when notifications are off on the device you're using, with a link to turn them on. Without them, nothing tells you when a favourite comes out.

### v1.103.114 · Quicker departure boards
<sub>20 November 2026</sub>

- Train departure boards no longer stall for 1.5 seconds while the timetable refreshes, which happened twice a day and after every update.
- The platform display picker has its own page title.

### v1.103.113 · Departure boards fit your phone
<sub>20 November 2026</sub>

- On a phone, the line filters on Departure boards are now one row you can swipe, not a small box with a row cut in half and Upfield, Werribee and Williamstown hidden underneath.
- The boards also use the tighter phone spacing and column widths they were meant to have.

### v1.103.112 · Stony Point platforms and more buses identified
<sub>20 November 2026</sub>

- Stony Point trains now show their platform: platform 3 at Frankston and platform 1 at the other stations on the line, from PTV's timetable. PTV's live departures leave it blank.
- 43 more buses now show their fleet number and model, and the Kinetic Scania hybrids (fleet 4000 to 4126) are marked as hybrid.

### v1.103.111 · Resolved alerts say what ended
<sub>20 November 2026</sub>

- A "Resolved" notification now names the disruption that ended, such as "The disruption from vandalism in the Wattleglen area has ended." Before, it only said "The earlier disruption has ended.", which was unclear when two alerts on your line came close together.

### v1.103.110 · No repeat works and fleet alerts
<sub>20 November 2026</sub>

- If you got the reminder before planned works, you are not told again when they start. The Werribee bus replacement on 19 Nov came as a reminder at 11:10pm and again at 11:55pm.
- A favourite train that drops out of the live feed for a while, but is still on the same trip, is not announced as "now running" a second time.

### v1.103.109 · No delay alerts for trains that already arrived
<sub>19 November 2026</sub>

- A delay notice about a train that has already got in isn't sent. PTV posted "the Wendouree service due at Southern Cross at 4:39pm is delayed by 20 min" at 6:10pm, and it went out.

### v1.103.108 · One incident, one notification
<sub>19 November 2026</sub>

- PTV's notice and the live feed often both report the same incident. You no longer get it twice: once as "Major disruption" and again minutes later as "Worse" with the same words, or two cards seconds apart.
- A real escalation (a longer delay, new wording) still comes through.

### v1.103.107 · Fleet alerts don't guess the line from a doubled-up trip
<sub>19 November 2026</sub>

- Favourite and rare-fleet notifications: when PTV's feed puts one trip on two trains at once, the notification no longer names a line from it. X'Trapolis 2.0 Set 5 at Caulfield was announced as "Cranbourne line" because it briefly got an HCMT's Cranbourne trip.

### v1.103.106 · Old one-train notices clear themselves
<sub>19 November 2026</sub>

- A train PTV says is "to terminate at" a station is now labelled "Cut short" and notified that way, like "will terminate at" already was.
- A notice about one train ("The 1:17pm Belgrave service…") leaves Disruptions six hours after that train left. PTV leaves them open, so a 1:17pm notice still showed as current at 10pm.
- No "resolved" notification when a one-train notice ends: the train was still cancelled or cut short.

### v1.103.105 · Single cancellations say Cancelled
<sub>19 November 2026</sub>

- Disruptions and station cards: a single cancelled train is now labelled "Cancelled" instead of "Cancelled or cut short".

### v1.103.104 · Cut-short trains labelled in the app
<sub>19 November 2026</sub>

- Disruptions and station cards: a train cut short is now labelled "Cut short" instead of being listed with cancellations, and the group heading reads "Cancelled or cut short".

### v1.103.103 · Cut-short trains aren't 'cancelled'
<sub>19 November 2026</sub>

- Notifications: a train cut short (like one that will terminate at Box Hill) was announced as "Service cancelled". It now says "Ends at Box Hill" or "Starts at Ringwood". Real cancellations still say cancelled.
- Train panel: the Previous and Next buttons fit on one line on phones.

### v1.103.102 · Readable Hide map button
<sub>19 November 2026</sub>

- Train panel: on the Belgrave and Lilydale lines in dark mode, the Hide map button was dark blue on dark grey and looked switched off. It's now easy to read on every line.

### v1.103.101 · Tap short trains on station boards
<sub>19 November 2026</sub>

- Station boards: tapping an extra train PTV added on the day (like a Blackburn short during a disruption) opened plain departure details instead of the train. It now opens the train, including before it has left its first station.
- Shared links to those trains keep following them too.

### v1.103.100 · Short trains show where they really end
<sub>19 November 2026</sub>

- Trains: during a disruption, a train cut short (like a Belgrave line train only running to Blackburn) showed its line's usual end instead. Extra trains PTV adds on the day now show where they actually finish, on the map and in the train panel.
- Those trains also show their train number again instead of a dash.

### v1.103.99 · Later buses say Scheduled
<sub>19 November 2026</sub>

- Bus boards: buses more than half an hour away said "Not live", as if something was wrong. They now say "Scheduled". "Not live" is kept for a bus that's due soon or under way without live data.

### v1.103.98 · Tram boards straight after an update
<sub>19 November 2026</sub>

- Tram stops: for the first half-minute after each update, tram departure boards could take 30 to 50 seconds to appear. They now show straight away; "Terminates early" labels fill in a moment later.

### v1.103.97 · Every sightings filter on phones
<sub>19 November 2026</sub>

- Sightings: on a phone the Tram and Other filters ran off the edge of the screen. The filters now wrap onto a second line so you can see and tap them all.

### v1.103.96 · Steadier live times
<sub>19 November 2026</sub>

- Behind the scenes: background tasks now give way to live times, so the map and boards pause less often while they run.

### v1.103.95 · Rare means rare
<sub>19 November 2026</sub>

- Rare sighting alerts now only fire for genuinely rare trains and trams (like G class, X'Trapolis 2.0 or the C2 Bumblebees). An everyday Comeng, Siemens or X'Trapolis running as a single 3-car set was being announced as rare, dozens of times a day.
- The platform display says you're offline when you are, instead of "No trains in the next while".

### v1.103.94 · Bus fleet numbers up front
<sub>19 November 2026</sub>

- Tap a bus and its fleet number now shows at the top of its panel ("742 Bus #1359") and on its map bubble, not just its rego. It was only in the details list before.

### v1.103.93 · Fixes from your reports
<sub>19 November 2026</sub>

- Bus boards: a bus that hasn't left its first stop yet now says "Not started yet" instead of "Not live", which read like something was wrong.
- A bus's stop list no longer borrows times from a trip that already finished. A 630 near Monash showed stops due half an hour earlier.
- Train names no longer turn silly at random ("X'Crapolis"). One of you thought the app was broken, fair enough.

### v1.103.92 · A tidier map
<sub>19 November 2026</sub>

- On phones, the map buttons now sit right on top of an open station or train panel instead of floating halfway up the map.
- The close button on a train's panel no longer sits over "Next train".
- The live-status chip, map buttons and disruption banner share one look, the banner uses the same warning colour as the rest of the app and grows with large text, and train, stop and station panels share the same heading and section-label styles.
- Keyboard users get a clear focus ring on every map button.

### v1.103.91 · Near you sits cleanly on phones
<sub>19 November 2026</sub>

- On phones, the "Near you" card from the location button now sits along the bottom of the screen like the other panels. The map buttons and live-status line used to show through around its edges on iPhones; they step aside while it's open.

### v1.103.90 · Tap a bus, get the bus
<sub>17 November 2026</sub>

- Tapping a bus on a stop's departure board now opens the actual bus on the map far more often (about 8 in 10, up from about 3 in 10). PTV numbers trips differently on its boards and in its live bus feed, so most taps used to fall back to an estimated position even when the bus was right there.
- When the bus can't be pinned down for sure (two of the same route side by side, or none nearby), you still get the estimate, clearly labelled.

### v1.103.89 · Smoother on the hour
<sub>17 November 2026</sub>

- Behind the scenes: background tasks that all started at the same moment every 10 minutes now start a moment apart, so live times don't pause while they get going.

### v1.103.88 · Trip card, boards and privacy fixes
<sub>17 November 2026</sub>

- Fewer freezes: loading the tram timetable no longer holds up everyone's live times for several seconds after an update.
- Trip card: once you've walked to the stop, the train or tram in front of you stays your service (it used to say you'd miss it). A late V/Line stays the one you saved, and a tram you lock from the map is followed properly.
- Journey planner: "leave by" times for trams and buses now come from the actual service, and tram-to-bus transfers try both sides of the road.
- Departure boards: the Near me home card separates trains by destination, boards keep the last times on screen (marked out of date) when a refresh fails or you're offline, and trams and buses that have left drop off.
- Notifications: turning notifications off and on keeps your repeating trips, and Settings shows when your phone has blocked them instead of saying "Saved".
- Privacy: your station check-ins appear on public profiles and leaderboards only after 24 hours, as promised. The privacy page now covers the Sightings board.
- Accessibility: search results are announced, the details panel takes focus and closes with Escape, screen readers no longer hear the live-status timer every few seconds, and the Android Back button works while a welcome card is showing.

### v1.103.87 · Smoother, steadier, easier to tap
<sub>16 November 2026</sub>

- Trains, trams and buses on the map are easier to tap with a finger, the disruption banner no longer covers search results or your trip card, and the map menu stays on screen when a station is open.
- Faster: the map no longer re-saves your train history on every update, map data isn't downloaded again on every open, and the Sydney map no longer waits on Transport for NSW at every refresh.
- Following a whole class: you can now follow a class even when none are running (like G class), coupled Metro trains no longer trigger a false "now running", and the running count is right.
- Alerts: times like 8.30pm read correctly, "workers" is no longer cut short, two different incidents with the same wording both reach you, repeated copies don't use up your daily alerts, and Arden never appears in "resolved" notices either.
- Near me: your home station's lines are now colour-coded like the stops below. Delays: routes running early no longer say "On time".
- Android app: your live trip notification stays put when the app refreshes in the background, a cancelled update no longer reopens every time you come back, Google Play errors are explained instead of silently doing nothing, and the home-screen widget opens your saved stops.

### v1.103.86 · Follow a whole class
<sub>16 November 2026</sub>

- Fleet (Premium): pick a class, like G class, X'Trapolis 2.0, HCMT, Siemens Nexas or C2 Bumblebee, and tap "Follow every…". You'll get a notification with the fleet number and where it is whenever one comes out (up to 6 a day per class).
- G class trams are now recognised everywhere, including the fleet tracker, favourites and rare sightings. Some were showing as "Tram class unconfirmed".
- E2 class trams (6051–6100) now show as E2, not just E class.
- "Share my trip" links now carry the trip itself, so whoever opens one follows that exact service, even if the train is re-coupled or its live id changes. Trains approaching a station link to their trip too.
- Your favourite trains and trams still each get their own alert, with the fleet number and location. The Favourites page now says correctly that this is after 30+ minutes stopped, not 24 hours.

### v1.103.85 · Room for the alerts that matter
<sub>15 November 2026</sub>

- You still get at most 12 alerts a day (cancellations and other critical alerts always come through). Minor alerts now stop at 8, so the last few are kept for major delays instead of being used up on small ones.

### v1.103.84 · Behind the scenes: finding the pauses
<sub>15 November 2026</sub>

- The server now notes how much of any pause was memory clean-up, to track down the occasional few-second freezes.

### v1.103.83 · No more Arden in alerts
<sub>15 November 2026</sub>

- Alerts and notifications never name Arden as where a train starts or ends, including altered, terminated and resuming trains. They name the real start or end, or say the Metro Tunnel.

### v1.103.82 · Tunnel trains named by where they really start
<sub>15 November 2026</sub>

- Cancellation and delay notifications for Metro Tunnel trains no longer say a train started at Arden or another tunnel station. They name where it really started, from the timetable (e.g. "The 6:26pm Sunbury to East Pakenham service has been cancelled").
- If the train can't be found at all, the notification says it was due through the Metro Tunnel instead of naming a tunnel station.

### v1.103.81 · Quicker answers to bad requests
<sub>15 November 2026</sub>

- Stop lookups, fare zones, tram stop access and estimated vehicle positions now check a request before anything else, so a broken one is answered straight away and never counts towards your allowance.

### v1.103.80 · Trains follow the curves
<sub>15 November 2026</sub>

- Trains on the map now turn with the railway as they move between updates, instead of sliding sideways round bends.
- Every V/Line train now sits on and moves along the drawn track, not only the ones shown as a row of carriages.
- A train that can't be matched to the same stretch of track between two updates now moves straight to its new spot on the railway instead of drifting across the bend.

### v1.103.79 · Shared links open in the Android app
<sub>15 November 2026</sub>

- On Android, tapping a TransitAlert link someone sent you (a trip to follow, a station, the fleet) now opens it in the TransitAlert app from Google Play, not the browser. Needs the app update.

### v1.103.78 · No more freezes while timetables load
<sub>14 November 2026</sub>

- The server no longer freezes for 2 to 3 seconds while it unpacks the train, tram and V/Line timetables (after a restart and twice a day). Live times keep answering throughout.

### v1.103.77 · Live times protected from overuse
<sub>14 November 2026</sub>

- Each visitor can make up to 300 requests a minute (the app uses about 10). Someone hammering the server can no longer use up the live-data allowance that everyone's train, tram and bus times depend on.

### v1.103.76 · Steadier airport buses
<sub>14 November 2026</sub>

- Western Sydney Airport buses: when Transport for NSW is busy or briefly down, the board keeps showing the last list (up to 10 minutes old) instead of "Airport bus times unavailable", and waits a minute before asking again.
- Sydney departures: a malformed request is now refused as such, rather than reported as the service being down.

### v1.103.75 · Sprinters on the fleet page, and the app keeps itself up to date
<sub>14 November 2026</sub>

- Fleet: the Stony Point line isn't electrified, so Metro runs it with diesel Sprinter railcars hired from V/Line. They now have their own "Sprinter railcar" chip on the Metro tab (instead of "Other"), show on the V/Line tab with the other Sprinters, and say "run by Metro" on their cards.
- Fleet: the Metro stabling and off-the-feed boards include the Stony Point Sprinter, and its Frankston sidings are listed as Metro's.
- The app updates itself: when a new version is out, an open copy reloads into it at a quiet moment (while it's in the background, as you come back to it, or after 5 minutes untouched), never while you're typing.
- Android (Google Play): the app downloads its own updates and installs them when you put it away, but never during a live trip. An app 3 or more days behind updates straight away.

### v1.103.74 · No more waiting on the tram timetable
<sub>14 November 2026</sub>

- Nearby stops answer straight away after the server restarts, instead of waiting about 30 seconds for the tram timetable to load (it timed out for some riders). Tram platform directions fill in on the next refresh.
- The tram timetable's twice-daily refresh no longer holds up tram boards and nearby stops: they keep using the previous copy until the new one is ready.
- An app left open across an update loads the new version quietly. It used to flash a "Signal fault" screen during that reload, and pages from the previous version can now still fetch their own files.

### v1.103.73 · Trains say what they are
<sub>14 November 2026</sub>

- Stony Point line: trains show as a Sprinter railcar (Metro runs the line with Sprinters hired from V/Line), "SPRINTER" on the map and "Sprinter (number not reported)" in the card, instead of "Live allocation unavailable". The feed never gives the Sprinter's number.
- Trip card for a train not on the map yet: when the train forming it is still finishing its previous trip, the card names its carriages instead of "Live allocation unavailable".

### v1.103.72 · Better Chinese, steadier fleet page, alerts that find every phone
<sub>14 November 2026</sub>

- 中文: departure times, delays, platforms and badges on departure lists are now in Chinese, the menu has no English rows left, clock times read 下午6:58, and "Now" says 现在 (it labels arrivals too).
- Notifications: a phone whose alert failed to send while others got it is tried again (up to 3 times in 30 minutes) while the alert is still current.
- Fleet: an "Other" chip shows the trains without their own (the Stony Point Sprinter, unallocated Metro trains), coupled VLocitys count with the VLocity chip, and trip history rows wrap properly on phones.
- Accessibility: the phone menu and the stamp celebration take keyboard and screen-reader focus and give it back when they close; the platform link in a departure row works with Space as well as Enter.
- Disruption banner: a card you dismissed stays dismissed even if the feed briefly drops it.
- Plan a trip: with a leave time already past, "Arrive in about…" is measured from now, not from that time.
- Live map: a vehicle position with no timestamp of its own is judged by the feed's, so an old one can't show as live.

### v1.103.71 · Southern Cross coaches, skipped stops, held handles
<sub>14 November 2026</sub>

- Southern Cross: the Regional Coaches list shows the coaches leaving the Coach Terminal (to Bendigo via Gisborne, Lara, Deakin University and more). It only ever looked at the station's train stop, where coaches never appear, so it was always empty.
- V/Line: a train the live feed says won't stop at a station (cut short with coaches beyond, or running express) shows as cancelled there, and Plan a trip no longer offers it to or from a stop it skips.
- Travellers: a handle you change away from stays yours for 30 days, so an old /travellers link can't be taken over by someone else.

### v1.103.70 · Privacy for travellers, local times interstate
<sub>14 November 2026</sub>

- Travellers: the friends feed and station pages show dates only, and nothing from the last 24 hours, so following someone can't show where they are right now.
- Passport: Back to Base, Full Circle, Station Revisit and Home Base can now be earned. They count across days (a station takes one check-in a day), so Station Revisit is checking in again at a station from an earlier day, and Back to Base is starting two Passport days in a row at the same station.
- Handles that sound official anywhere in the name (the_admin, real_ptv) are reserved, not just at the start.
- Departure boards: a platform picked at one station no longer carries over to the next.
- V/Line: a running train is no longer shown as cancelled because a different train with the same number was.
- XPT: a cancelled trip says so, and stops the train skips show no time.
- NSW TrainLink boards at Brisbane, Broken Hill and Perth show local times (AEST, ACDT, AWST) instead of Melbourne's.
- The Android beta download on the install page is now 1.103.69.

### v1.103.69 · Notifications you can count on, fairer fares
<sub>14 November 2026</sub>

- Notifications: a newer card for the same alert or trip (now cancelled, not just late) makes a sound again instead of silently replacing the old one.
- Notifications: Remind me reminders arrive even with "My tracked trip" switched off, works reminders are retried if a send fails, and the 12-a-day limit counts disruption alerts only, not trip, fleet or weather pushes.
- Notifications: signing out stops that account's favourite-vehicle alerts on this device straight away, and a fault on our side can no longer get everyone's notifications switched off.
- Notifications: an update to the app while alerts are going out no longer sends the same alert to everyone a second time.
- Email updates have a working one-click Unsubscribe button in Gmail and other mail apps.
- Fares: a touch-on after midnight gets at least two hours (a 2:30am train and 3:10am bus are one fare), trips only through overlap stops are labelled Zone 2 to match their price, and 2027 public holidays use the weekend cap.
- Plan a trip: tram and bus changes allow at least two minutes, a leave time a few minutes away is respected, a leave time in the past keeps refreshing, and swapping ends clears "Car left at".
- Beta is now for Premium members on the server too, not just in the app.
- Map: opening a train that isn't on the map yet no longer stops every other vehicle updating, the map stays put when the feed renames a train mid-trip, searching the same station again flies back to it, and an old or lowercase station link works or says it isn't found.
- Map: the Balaclava Rd/Hawthorn Rd tram platform shows its own departures (it showed North Rd's, 3 km away), and an empty map overnight no longer says the live feed is down.
- Platform display: with the first train cancelled, the screen shows the next running train with its own destination and stops, and the cancelled one stays listed below.
- Onboard screens stay on the current station until the train leaves it, and the Alstom screen keeps the terminus on its diagram at the last stop.
- Fleet: searching "Set 7" finds set 7, not Set 70 or Siemens 705; unidentified vehicles can't be starred; the live HCMT picker always shows the train the screen follows; train numbers on the X'Trapolis 2.0 tracker are Premium like everywhere else.
- Google Play: a payment that was still processing unlocks Premium automatically the next time you open the Premium page, before Google's 3-day refund.
- Error messages from the server are short and readable everywhere, never internal details.

### v1.103.68 · Every train opens its trip card, boards that hold steady
<sub>14 November 2026</sub>

- Map: tapping a train on a station's board opens its full trip card (stops, times, running late or early) even when the train isn't on the map yet, like one waiting at its terminus. It shows at the station as "Not reporting yet" and switches to the live train once it reports. The old plain details only appear when the trip isn't in the live feed at all.
- Departure boards: one failed refresh (a dropped signal for a moment) no longer wipes a working board. The times stay, with a note that they're not updating.
- Departure boards: moving to another tram or bus stop clears the route filter and chosen time, so a route 901 filter can't leave the next stop showing nothing with no way to clear it.
- A departure's detail sheet now follows the live board, so a cancellation or platform change shows there too.
- Station accessibility: platforms, step-free access and routes always belong to the station you're looking at, never the one before.
- Near me: an interchange where some bays failed to load stays on the list and says so, instead of vanishing.
- Sign-in: five wrong passwords now lock out the device that made them, not the account for everyone, so nobody can keep you locked out of your own account.
- Accounts: a session left idle longer than a week is always signed out, and a damaged cookie reads as signed out instead of breaking the page.
- Security: live accounts only accept changes from transit-alert.com pages, account responses are never cached, and sign-in tokens only pass with the exact signing method and key they were made with.
- Status page history is saved safely, so a restart mid-save can't wipe it. Settings says when the PTV check couldn't run instead of loading forever.

### v1.103.67 · Safer sign-ups, straighter disruption counts
<sub>14 November 2026</sub>

- Accounts: signing up again with an address that was never verified now cancels the earlier verification links, so an old link can't verify the account under someone else's password.
- Accounts: changing your password or deleting your account allows 5 password tries an hour, and a failed sign-in check now offers to try again instead of sending you to the login page.
- Rate limits lift when they say they will: requests refused for being over the limit no longer count towards it.
- Disruptions: a bus route's popup only lists that town's route (Geelong's 25, not Ballarat's), route counts only include the alerts that set the route's status, and a failed refresh no longer shows two different error messages.
- Disruptions: a delay that began before midnight says which day it started, not just "Since 11:00 pm".
- Rider reports: one connection can only add a few reports to the same service, so a single phone can't fake a crowd.
- Status page: feed ages count up between checks, and it says so if the checks themselves stop.
- Near me: a late location result no longer pulls you back to the page, and a home station with no live board says how to fix it.
- Travellers: a failed leaderboard load no longer also says "Be the first on the board". Settings asks before resetting every preference.
- Android widget: after restoring the app onto a new phone, each widget keeps the stop it was showing.

### v1.103.66 · Fairer status page, truer passport badges, steadier widget
<sub>14 November 2026</sub>

- Status page: each feed now has its own overnight quiet window (trains, trams and buses on weeknights, V/Line every night), so a feed that's dead at 5:30am counts against uptime instead of being let off as "no services overnight".
- Passport: early-bird, night-owl, weekend, return-visit and repeat-day badges now count every verified check-in, not just the first stamp at each station.
- Departure boards: a train signed "City (Flinders Street)" no longer shows as terminating early when it's timetabled to Flinders Street.
- Glance: countdowns follow your clock-time setting and round the same way as the rest of the app.
- Sightings: "today" stays right if the page is left open past midnight, and a sighting from the same weekday last week shows its date.
- Android widget: switching stops can no longer show the previous stop's departures or a stale error, each widget keeps its stop when you add or remove saved stops, and countdowns round down like the app.
- SRL page now says plainly that tunnel boring machine positions are estimates, and the empty Streaks filter is gone from the passport.

### v1.103.65 · HCMT screen keeps to its own lines
<sub>13 November 2026</sub>

- Fleet screens: the HCMT screen only ever shows stations on the Sunbury, Pakenham and Cranbourne lines, live or custom. A live destination or next stop anywhere else (Flemington Racecourse, say) shows as unavailable instead, in the screen, its menus and the train picker.

### v1.103.64 · Siemens Metro page to scale, quicker EDi Comeng sign, Sandringham pink
<sub>13 November 2026</sub>

- Fleet screens: the refurbished Siemens "Metro" and "Driver Announcement" pages now size their words to the strip, so "Metro" fills it like the real resting page instead of sitting small in a big blue box.
- Fleet screens: the EDi Comeng LED sign moves to its next page sooner, closer to the real sign. VLocity and Sprinter signs keep their pace.
- Disruptions: route chips now say how many disruptions a route has, not how many alerts.
- Fleet screens: the Alstom Comeng screen shows Sandringham, Werribee and Williamstown trains in their pink line colour again, not purple.

### v1.103.63 · HCMT saloon screen and Siemens blue pages
<sub>13 November 2026</sub>

- Fleet screens: the HCMT now shows its real saloon screen: a wide display in a rounded grey housing with the destination on a bar in the line's colour and "Stopping all stations" beneath, plus the blue hearing-loop "Announcement in progress" page.
- Fleet screens: the refurbished Siemens strip rests on its navy "Metro" page between messages, and a Driver announcement button shows its bright blue "Driver Announcement" page.

### v1.103.62 · Onboard screens fit your phone and hold still
<sub>13 November 2026</sub>

- Fleet screens: every onboard screen fits the width of your phone; the refurbished Siemens strip no longer pushes the page sideways, and station names on it no longer break mid-word.
- Fleet screens: nothing scrolls sideways any more. Long messages on the EDi Comeng, VLocity and Sprinter LED signs show a page at a time, and the station display's stopping pattern sits still on up to two lines.
- Alstom Comeng: Sandringham (and Werribee and Williamstown) are purple on this screen, as on the real train, not pink.

### v1.103.61 · VLocity sign is amber only
<sub>13 November 2026</sub>

- Fleet screens: the VLocity overhead sign is amber only, as on the trains; the blue option is gone.

### v1.103.60 · VLocity and Sprinter LED signs
<sub>13 November 2026</sub>

- Fleet screens: the V/Line VLocity is now its real overhead sign: one row of dot-matrix text in a pale ceiling housing, lit amber. It cycles a welcome, the destination and "Next station is ...", scrolling long messages.
- Fleet screens: the Sprinter gets the same kind of single-row amber LED sign, a little shorter.

### v1.103.59 · Alstom Comeng screen in the right line colour
<sub>13 November 2026</sub>

- Fleet screens: the Alstom Comeng onboard display draws its line diagram and "Now" station box in the train's own line colour (Frankston green, Sandringham pink, Cranbourne and Pakenham cyan) instead of purple on every line. The Burnley group's navy is lightened just enough to show up on the dark screen.

### v1.103.58 · Steadier app when PTV's timetables are slow or huge
<sub>13 November 2026</sub>

- Trams: stop accessibility and which way a tram stop's trams head work again. PTV's tram timetable grew too big to read in one go, and every retry slowed the whole app for everyone for up to half a minute.
- Timetables: when PTV's download server is slow, the V/Line, tram and bus timetables get time to finish downloading instead of being cut off after a minute.
- Behind the scenes: the bus tracking that spots mid-route U-turns does its work in a fraction of the time, and slowdowns are now logged with what was running so they can be tracked down.

### v1.103.57 · Coaches shown as coaches, and fewer phantom V/Line trains
<sub>13 November 2026</sub>

- Departures: a road coach PTV runs under a train route is shown as a coach. Traralgon's 11:03am and 7:40pm to Bairnsdale stop at Princes Highway bus stops but appeared as trains; a coach is only called one once its own stops show a road stop.
- Departures: PTV's copy of a train timed by its arrival (the Ararat train "7:52" at Ballarat, which leaves at 8:04) no longer shows as a second train, and city-bound trains that only let passengers off at Footscray or Sunshine no longer appear there as trains to board.
- Disruptions: works that run "each night" or "each day" only count during their hours. Werribee's "buses replace trains from 11.50pm to last service each night, 16 and 17 November" would have shown the line disrupted all Tuesday while trains ran, and Wallan's nightly stop closure showed at 11am.
- Disruptions: a planned "Service changes from …" notice is works even when it blames traffic (Route 48's Eastern Freeway weekend was pushed as a live delay a month ahead), a diversion with no works behind it is a delay rather than information, and "Unplanned Disruption" is no longer used as a headline.
- Notifications: works reminders reach you on the default settings (they needed Works & closures turned on too), and planned buses replacing trains get one. Titles for many lines read "Belgrave +4 Lines".
- Trip planner: the fewer-changes search works. Windsor to Willison now offers one change at the same 27 minutes as the two-change trip.
- Live map: every tram's next stop was blank, and Belgrave trains on newer trip ids lost their next stop and destination; both show again. Buses on routes 510 and 512 take their operator from their trip, as route 509 already did.
- Sydney disruptions: "&middot;" and invisible filler characters no longer show in notices.
- Departures: a V/Line board's "recent services" are the trains that actually left, with platforms, instead of PTV's copies (phantom "to Deer Park" rows and the same train twice).
- Trip planner: on a trip with a change, the first leg takes the train that gets there first, not the first to leave (Werribee's express over the 7:00 via the Altona Loop), so the next leg is searched from the right time.
- Disruptions: the same tram incident from PTV and from the live feed shows once. A Route 1 accident had a second card titled "Unplanned Disruption".
- Fleet: a lone 3-car train is only shown with a partner seen in the same 6-car on the same line within 45 minutes, and borrowed pairings no longer count as fresh sightings. A pairing used to keep renewing itself, so a parked set could look like it was running.
- Disruptions: "Buses replace trains … due to police activity" is filed under buses replacing trains rather than Police, and notices saying the problem "has now cleared", "good service has resumed" or trains "are running again" are treated as over.
- Sydney disruptions: a withdrawn strike ("bus services are expected to run as normal") is no longer ranked as a major disruption.
- Trip planner: outline times allow 7 minutes for a change at Flinders Street, Richmond and the other big stations, matching the timed plan.
- Notifications: regional bus routes picked in settings (Geelong, Ballarat, Bendigo, Latrobe and others, 91 routes) are saved on the server and alert you; they showed as saved but were dropped.
- Notifications: after the live feed or recorder has been down, starred vehicles are no longer all announced as "now running" at once, and a Metro-only outage is caught too. "First run in 1 hours" reads in minutes.
- Notifications: an unchanged severe weather warning that BOM re-issues is no longer pushed again each time.
- Platform displays: the big headline shows the next train that's running, not a cancelled one.
- Sydney: busy station boards reach twice as far ahead. Central's board stopped about 20 minutes out (Transport for NSW sends 40 departures at a time), so the next Blue Mountains, Central Coast & Newcastle or regional train was often missing; a second page is fetched when the first is full.
- Train details: stops the live feed says an altered train will skip are no longer listed as stops, so "Next stop" can't name a station it runs past.
- Fares: a Zone 2 to Zone 2 train trip through the city (Sunbury to Dandenong through the Metro Tunnel) is estimated as a Zone 1+2 fare, as myki charges it.
- Meeting someone: the trains checked are the nearest to the station, so at peak the next arrival isn't left out.
- Map: a selected bus that drops out of the feed no longer turns into another route's bus with the same run number, and searching a station lists only trains for that station ("Richmond" no longer brings up Mernda and Hurstbridge trains for North and West Richmond).
- Search: typing a tram or bus route number like 16 or 627 and pressing Enter no longer opens the Flinders Flyer.
- Premium: one Google Play purchase can't unlock two accounts at once, and a mangled stop link no longer breaks the map page.

### v1.103.56 · Truer V/Line boards, statuses and notifications
<sub>13 November 2026</sub>

- Departures: the Southern Cross V/Line board kept half its rows for coaches, and the only "coaches" PTV lists there are copies of trains under coach routes (Halls Gap, Daylesford, Corowa…) heading for railway stations. Past the stretch the timetable check covered, about 5:30pm, those copies got through, so at 9:30am the board showed ten trains to 10:16am and then jumped to 5:38pm. Those copies are now held back until they can be checked, and room the coaches don't use goes to trains: the board shows the next 20 trains.
- Departures: regional V/Line boards no longer list trains twice. PTV's times run a few minutes off V/Line's timetable, so Ballarat showed each Wendouree train at 10:01 and again at 10:04, Bendigo the Eaglehawk train at 11:58 and 12:03, and Bendigo's Echuca trains appeared again as "to Epsom" five minutes earlier.
- Disruptions: V/Line line cards no longer pick up coach routes that pass through their towns. A coach stop change on "Sydney - Adelaide via Albury" had Albury reading "Works", the Adelaide coach did the same to Bendigo, and the Apollo Bay coach to Geelong and Warrnambool, while their trains ran normally.
- Disruptions: when a bus notice's title lists routes PTV only partly attached, the rest are added. "Routes 411, 412 and 903: Permanent bus stop closure" came with route 903 only, so it never showed for 411 or 412; routes 400 and 409 had the same gap on other closures.
- Sydney disruptions: notices about a single train ("Running late", "Cancelled", "Now ending at Central") are dropped once they haven't been updated in 36 hours. Transport for NSW leaves them open-ended, so 44 from past months were still listed, back to a "Starting from Campbelltown" from September 2024, and 17 of them were ranked as major disruptions. Identical notices posted once per group of routes now show once, listing every route.
- Notifications: place names that start like a month keep their names. This morning's cancellation read "The 10:47am Ballarat to Mar service" (Maryborough); Marshall and anything starting "Jun" had the same risk. A dated window with a year ("from 8am to 4pm on Friday 13 November 2026") moves to the time line whole, instead of leaving "…selected bus stop 2026." behind.
- Notifications: an alert on two or three tram or bus routes names them ("Routes 96 & 109 · Delays") instead of "Route 96 +1 routes".
- Disruptions and notifications: a live delay, police or trespasser incident shows when it started ("Since 7:47am") rather than PTV's 11:59pm placeholder end, which read as an all-day delay. A cancelled train's notification no longer shows the notice's own hours ("6:53am–12:30pm") above "The 10:47am … will not run".

### v1.103.55 · Truer disruption times and statuses, two Comeng shunters
<sub>13 November 2026</sub>

- Disruptions: planned card top-up outages ("EFTPOS and Card payments will be unavailable for topping up") are station notices now, like car park closures. They're still listed, but no longer mark the line as having works, and they no longer send a works reminder or a normal-priority notification.
- Disruptions: when PTV's times for a notice are back to front or exactly 12 hours out, the times in its title are used instead. Trafalgar's "12am to 6am on Thursday 19 November" outage had been sent as starting at 12pm and ending six hours before it began, and the Wandong, Heathcote, Forest Hill, Preston, Wantirna, Somerville and Frankston notices had the same slip.
- Disruptions: a dated "Service changes from …" notice counts as planned works rather than information. The changes on tram routes 1, 3, 5, 6, 16, 64, 67 and 72 from 11pm Friday 4 December to Sunday 6 December had shown those routes with nothing wrong.
- Fleet: Comeng sets 485/486 and 535/536 are shown as out of passenger service. Neither has run a passenger trip in 60 days, and they're reported to be shunting the new X'Trapolis 2 trains at Newport.

### v1.103.54 · Four Comeng sets withdrawn
<sub>12 November 2026</sub>

- Fleet: Comeng sets 329/366, 369/370, 581/584 and 645/646 are now shown as withdrawn, being decommissioned at Craigieburn. 581/584 and 645/646 last ran together on 5 November (the 11:15am Craigieburn), 369/370 on 30 October, and 329/366 hasn't run since at least late September. Withdrawn sets no longer offer "notify me when it's back", and the in-service counts drop to match.

### v1.103.53 · Disruptions says when the trains are fine
<sub>12 November 2026</sub>

- Car park closures and entrance changes at stations no longer count as works on a line. On a normal evening the Disruptions page said "Works on 13 metro lines" while every train ran to timetable; now those lines show "Good service · station notice", and the notices are still listed under each line. The same applies to V/Line stations like Melton and Euroa.

### v1.103.52 · No more impossible delays
<sub>12 November 2026</sub>

- A bus, tram or Metro train shown as more than 90 minutes late is reporting an old trip, not running that late (a 612 bus on the road claimed to be 145 minutes late). The map and vehicle details now say "No live timing" for these instead, the same cut-off the Delays page already used. V/Line keeps up to three hours, as long country runs can really lose that much.

### v1.103.51 · Faster live map at busy times
<sub>12 November 2026</sub>

- The live map, Delays page and vehicle details stay quick at evening peak. Every request used to re-sort every stop of every bus, train and tram trip statewide, which at busy times froze the server for up to 40 seconds and made the tram and V/Line maps fail. Each live feed is now worked through once and shared.

### v1.103.50 · A home-screen widget, and clearer City Loop alerts
<sub>11 November 2026</sub>

- Fleet: about 1,780 more Melbourne and regional buses now show their fleet number, operator and model (the register grew from 397 to over 2,100, from the operators' published fleet lists). Routes 406, 407 and 501–544 are now shown as CDC Melbourne, which every registered bus seen on them belongs to. Geelong routes 1, 10, 12, 19, 20, 22–25 and 43 are run by CDC Geelong, not McHarry's, and its buses now say so.
- Fleet: buses on routes 400 and 900, which two operators share, now show the right one. Each trip's PTV contract number says who runs it, so about 2,000 more bus trips a month are labelled with their operator, even when the bus isn't registered yet. Every older register entry was checked against the operators' published fleet lists: fixed five buses under the wrong operator, five wrong fleet numbers, two wrong power types (BS05GX is a hybrid, BS11MG a diesel) and filled in 15 missing models.
- Alerts: works that finished months ago no longer show as current when PTV left them open but the title says when they ended ("Route 785: … to Sunday 26 July 2026", "Mernda Station: … to mid-August 2026"). Notices without a clear end date stay.
- Alerts: an old PTV notice titled "Thu 14, Sep: Metropolitan buses disrupted" (from 2023) now leads with what it's actually about: a 541 bus stop that's closed.
- Tram and bus boards lead with where the service is going ("St Kilda Beach", "Waterfront City Docklands") instead of PTV's terminus stop name ("Belford St/Acland St #139", "D11-Waterfront City/Docklands Dr"), on stop boards, saved stops, Glance and the service sheet. The stop it ends at is still shown underneath. Docklands stop names drop their "D1-" code.
- Departure boards load much faster when someone else just looked at the same stop, and keep showing the last good times if PTV briefly stops answering, instead of an error.
- Plan a trip to or from Melbourne Airport: searching "airport" now pins the terminals, and the planner offers the 901 bus to Broadmeadows and the Craigieburn line (it used to suggest a two-hour walk to Watergardens). A note points out SkyBus too, which is a separate ticket.
- Plan a trip from anywhere in Melbourne that's a long way from a train (more than 4 km) now looks for a bus or tram to the three nearest stations, instead of treating it as a country trip with no buses.
- Plan a trip from a city address now considers Flinders Street even when Loop stations are closer, so Frankston and Sandringham trains (and Night Network) are found: Bourke St Mall to Frankston at 1:30 am now takes the direct 2:09 am train and arrives an hour earlier.
- Plan a trip from a city address to a country town (Bourke St to Ballarat) now boards V/Line at Southern Cross. It used to try Flinders Street, which those trains don't use, and found nothing.
- Plan a trip now puts a direct tram or bus first when it is only a few minutes slower than a trip with changes or a long walk. Rod Laver Arena to Southern Cross now leads with tram 70 instead of a walk to the train. Each option still shows its real time.
- Opening the planner from a V/Line alert now fills in regional stations like Geelong, instead of sometimes leaving the destination blank.
- Name your saved stops: tap the pencil on a saved stop and call it Home, Work, School or anything you like. The name shows on the card, in Glance and on the widget.
- Remind me: tap any departure, then "5, 10 or 15 min before" for a push that follows the service's live time, so a late train reminds you later. Until then you're also told if it runs late, changes platform or is cancelled. It sits alongside a trip you've started instead of replacing it.
- Android app: a home-screen widget with the next four services from your saved stops: line colours, platform, express or stopping all, and how late each one is running. Tap ⇄ to flip between saved stops and ↻ to refresh. It counts down every minute while your screen is on and sleeps when it's off.
- A train that skips the City Loop is now shown as a change to its trip, not a cancellation, and its alert says "Not via the City Loop".
- Parliament, Melbourne Central and Flagstaff no longer read as where a train starts or ends: "The 5:10pm Parliament to Frankston service" becomes "The 5:10pm service from the city to Frankston".
- Trains split at any Metro Tunnel station, including State Library, show where they really run to, and a cancelled tunnel train never shows a tunnel station as its end.
- Alert titles no longer carry stray hidden characters or doubled spaces from the operator's text.
- Fleet: a train parked away from a station now reads "Stabled near Footscray (1.2 km)" instead of "Stabled at near Footscray".
- Near you in the city: tram poles at stops that share a number (Elizabeth St and La Trobe St are both #5 at Melbourne Central) now show their own stop name and routes, instead of a neighbour's name and no routes.
- Tram platform sides are judged against the stop's own platforms, not every stop with the same number across the CBD.
- Train stations near you list only their own lines: Flinders Street's metro stop no longer lists V/Line coaches, and its V/Line stop no longer lists metro lines.
- Status page: trams, buses and V/Line going quiet overnight when nothing is running no longer count as feed downtime (today's tram figure read 87.6% for that reason), and the live row says "No services overnight" instead of a warning.
- Fleet PIDS: a new Alstom Comeng display, recreated from footage of the real screen. It alternates "Now Elsternwick" / "To Sandringham Stopping all stations" with the purple line diagram and its "Next" tag, and follows a live Alstom Comeng when one is reporting.
- Alerts: buses diverting because of an incident, a fallen tree, traffic or a water leak are listed as disruptions instead of planned works & closures, and their push says "Diverting" rather than "Delays".

### v1.103.49 · Your train station is back near you
<sub>11 November 2026</sub>

- Near you on the map always includes the closest train station, tram stop and bus stop, so nearby bus stops no longer push the station off the list.
- It now looks up to 1 km away, so a station a short walk off still shows.
- Train rows show the line a train came from, then where it's going: at Huntingdale, "Pakenham · Watergardens" into the tunnel and "Sunbury · East Pakenham" out of it.
- Route badges on each card line up, so the places and times after them do too, and every train row says where it ends.
- A station's bus bays share one card, with the bay on each row.
- Train cards show V/Line and express trains running through without stopping, with their estimated pass time.

### v1.103.48 · Every line in its colour
<sub>11 November 2026</sub>

- On the Near you card, each route row now has a light wash and an edge in its line colour, and the stop's icon matches its next route.
- The next departure on each row stands out; later ones are quieter.
- The Android app goes straight from its navy launch screen to the loading train, without a dark flash in between.

### v1.103.47 · Buses near you, in colour
<sub>11 November 2026</sub>

- The map's location button now shows nearby trains, trams and buses by default. You can still pick Station or Trams only in Settings.
- Each route on the Near you card is shown in its own colour: Metro line colours, each tram route's colour, bus orange and V/Line purple.

### v1.103.46 · A proper TransitAlert icon, and a train while you wait
<sub>11 November 2026</sub>

- The Android app now uses the real TransitAlert train icon for both the Play and beta versions, instead of a placeholder.
- The launch screen is TransitAlert navy with the app icon, instead of a white placeholder.
- While the app loads you now see a Comeng running past the overhead, and if something goes wrong it stops at a red signal with clear ways to recover.
- Starts faster on older and budget Android phones: optional prompts and detail panels now load after the map appears.
- Metro departure details now show the service's run number.

### v1.103.45 · Movember, and a few surprises
<sub>9 November 2026</sub>

- New Movember theme in Settings: black and mo brown, with a moustache on the logo.
- Some visits are a little sillier than others. Keep an eye out.
- The Stony Point Sprinter now shows as stabled at Frankston overnight, instead of dropping off the board.
- Fixed the app showing an error after an update instead of loading the new version.

### v1.103.44 · Opens faster
<sub>9 November 2026</sub>

- Every page downloads about 125 KB less before it appears. The report form and release notes now load only when you open them.
- Clearer wording across the app, and a tidier journey planner on phones.

### v1.103.43 · Know which side of the road to wait on
<sub>9 November 2026</sub>

- Bus and tram steps in the journey planner now say which way the stop faces, for example "eastbound stop". Stops on both sides of a road often share one name.

### v1.103.42 · Every update, on one page
<sub>9 November 2026</sub>

- "What's new" in the menu now opens a page with every TransitAlert update, newest first, instead of a one-time pop-up.

### v1.103.41 · Cleaner train numbers, and rating from inside the app
<sub>9 November 2026</sub>

- X'Trapolis 2.0 and HCMT cars are shown by number only (8108-8208-8308), without an M or T they don't have.
- Sightings recognise Metro sets: posting 8108, 8008 or 9060 files it under Metro with the set it belongs to.
- Android app: "Rate on Google Play" opens Google's rating sheet right in the app (update the app from Google Play to get it).

### v1.103.40 · Tell us what's wrong, right where you see it
<sub>8 November 2026</sub>

- Station boards and Near me stops now have a "Something looks wrong?" link that fills in which stop or station you mean.
- After you've used TransitAlert on a few different days, it asks once whether it's useful, and what would make it better. Answers are anonymous and need no account. It asks again at most every 90 days.

### v1.103.39 · Calmer alerts
<sub>8 November 2026</sub>

- Disruption alerts are capped at 12 a day per phone. Critical alerts (major cancellations and suspensions) always come through.
- New alert sign-ups start with the lines through your home station, or ask you to pick your lines, instead of every line in Melbourne.
- The "disruption over" ping is now off by default for new sign-ups. Turn it on in Settings if you want it.
- Phones that stopped receiving alerts are now cleaned up and re-registered automatically the next time you open TransitAlert.

### v1.103.38 · Know your bay, and what's at your stop
<sub>8 November 2026</sub>

- Big bus interchanges (Huntingdale, Monash, Box Hill, Berwick, Dandenong and more) show one card per bay, with only the buses that leave from it. The map labels each bay with its letter.
- Stops on both sides of the road now show only the buses that really pick up on that side, from the official timetable.
- Stops show what's there when it's recorded: shelter, seat, timetable or live screen, lighting and tactile paving. Train stations show which platforms are only partly sheltered.
- Times on another day now say the day ("Mon 6:58 am").
- The platform display and Glance now have the menu button. On the platform display it hides after a few seconds so a screen on a TV stays clean.

### v1.103.37 · A simpler app by default
<sub>8 November 2026</sub>

- The menu leads with the five everyday tools: Live map, Near me, Plan a trip, Departure boards and Disruptions. Sydney airport buses moved to More.
- Train fan features (trackers, Fleet, Sightings, Station Passport and the fan cards on boards) are now a setting, off for new riders. If you already use them, they stay on.
- Simple mode has a switch at the top of the menu, and new riders get a one-tap offer to use it.
- The trip planner shows the best option first, with the rest under More options, and the fare fits on one line.
- Lift status says when it was last checked, and buses without live times show their timetabled time with a Not live tag.
- Departure boards show train car numbers only when train fan features are on, so each row is shorter.
- In the Android app, Premium is now a one-off A$2 through Google Play.

### v1.103.36 · Train times you can trust
<sub>7 November 2026</sub>

- A train's stop list no longer shows it leaving a stop before it arrives. PTV's feed sometimes sends a departure a minute earlier than the arrival.
- Stops PTV leaves out of its live update now carry the train's delay ("About 15 min late") instead of the plain timetable time, so the list no longer jumps backwards.
- Buses without live times now say so, instead of looking live.
- A cleaner trip planner: the Start journey card no longer gets squashed, the Night Network note shows once and only for evening trips, and the fare card is shorter.

### v1.103.34 · A tidier menu
<sub>7 November 2026</sub>

- The For train fans section of the menu now starts closed, so the menu leads with the everyday tools: map, near me, trip planner, departure boards and disruptions. Tap it to open; the app remembers your choice.

### v1.103.33 · Sightings: post the trains you spot
<sub>7 November 2026</sub>

- New Sightings page (For train fans → Sightings): post a freight train, V/Line loco, heritage run, Metro set or tram you've spotted, with the number, where, when and which way it was heading, so someone further down the line can catch it.
- Filter by type and search by number or place ('N453', 'Sunshine'). Sightings drop off after 24 hours. Your name is never shown, and you can remove your own.

### v1.103.32 · Tram and bus stops on the map are easier to find
<sub>7 November 2026</sub>

- Tram and bus stops show on the live map when you zoom in close. The status bar now says 'zoom in for tram & bus stops' when you're nearly there, and the Trams and Buses buttons filter the stops as well as the vehicles.

### v1.103.31 · Bigger text, and cleaner boards in Simple mode
<sub>7 November 2026</sub>

- New Text size setting (Settings → Text size): Standard, Large or Larger, for the whole app on any phone or computer, iPhone included.
- Simple mode now also tidies departure boards: no passport stamp button, collectors line, station of the day, or heritage and freight cards. Just times, platforms and disruptions.
- The screen-door platform display shows the platform as a clear white badge, and each carriage is labelled Car 1, Car 2 and so on.
- The Fleet PIDS sign-in screen now describes Fleet PIDS (the next-stop screens inside the trains) instead of repeating the Fleet description.

### v1.103.30 · Four new platform display layouts
<sub>7 November 2026</sub>

- The platform display has a Layout picker (move the mouse to the top-right corner): Standard, Screen doors (a wide strip with the train lined up door by door, for Metro Tunnel or any station), Half (the next four trains, big), LED sign (two amber lines with the stops scrolling) and CRT (the old blue departure list).
- The 'What's new' popup no longer appears over the platform display, so a screen left running stays clear after an update.

### v1.103.29 · 简体中文 · TransitAlert in Simplified Chinese
<sub>7 November 2026</sub>

- New language setting in Settings: English or 简体中文. The menu, departure boards and countdowns ('7 分钟', '准点', '晚点 3 分钟'), platforms and train notes are translated. Station and line names stay in English so they match the signs. More of the app will be translated over time.
- 设置中新增语言选项：可选英文或简体中文。菜单、发车信息、倒计时和站台信息已翻译；站名和线路名保持英文，与车站标识一致。

### v1.103.28 · Simple mode, and privacy in plain words
<sub>7 November 2026</sub>

- New Simple mode in Settings: a shorter menu with just the everyday tools (map, near me, trip planner, departure boards, disruptions). It hides the train-fan and Premium features for anyone who finds the app too busy.
- The privacy policy now starts with the short version: no account needed, location only used when you tap and never saved, no ads or selling your data, and saved stops stay on your phone.

### v1.103.27 · Tunnel trains on the platform display
<sub>7 November 2026</sub>

- Platform display: Pakenham and Cranbourne trains coming out of the Metro Tunnel now show Hawksburn, Toorak and Armadale greyed out between Anzac and Malvern, the stations they run past, like the real station screens.

### v1.103.26 · Easier to read
<sub>7 November 2026</sub>

- The 'Maps' and 'Transport Victoria' links on station wayfinding cards were dark blue on a dark background and almost invisible. They now use the app's link colour.
- The red count on urgent V/Line notices is a slightly deeper red, so the white number meets the readability standard.

### v1.103.25 · The live map works with screen readers
<sub>7 November 2026</sub>

- Every train, tram, bus and V/Line marker on the live map now has a name a screen reader reads out, like 'Train, Lilydale line, 81M-1341T-82M' or 'Tram route 86, tram 6041', instead of just 'button'. Hovering a marker with a mouse shows the same name.

### v1.103.24 · Truer reasons for trains ending early
<sub>6 November 2026</sub>

- When a train terminates early, the reason shown is now only a Metro notice about that train's time or the station it now ends at, not any notice on the line that happens to mention terminating somewhere else.

### v1.103.23 · A platform display you can leave on a screen
<sub>6 November 2026</sub>

- New Platform display (in the menu, or transit-alert.com/pid): pick a station and it shows the next train full screen like a station platform screen. Big time and destination, 'Now' or minutes to go, every stop it makes with the stations it runs past greyed out, the next two trains and a ticking clock. It keeps the screen awake and refreshes itself, so you can leave it running on a spare monitor or TV.
- Each train shows in its line's colour. V/Line trains are included at stations they stop at, Showgrounds trains show up when they run, and you can pick a single platform.
- Optional platform screen door strip showing the train's length: on by default at Metro Tunnel stations (7 cars), and you can turn it on anywhere and switch between 6 and 7 cars.
- Journey planner: trips that rely on the City Loop now also get a route that doesn't, and a route whose trains can be confirmed comes first. Craigieburn to Westall in the evening, when Craigieburn trains run direct, now offers Flinders Street then the tunnel from Town Hall.

### v1.103.22 · Where the SRL machines probably are
<sub>6 November 2026</sub>

- The SRL dig tracker now shows a rough estimated position for each tunnel boring machine that's digging, with a likely range, as of today. Only a combined official figure is published (138 m by 30 October), so the page explains exactly how the estimate is worked out. It's an educated guess, not a live position.
- Android app: text now follows your phone's font size setting (up to 200%), so bigger text in Android settings means bigger text in TransitAlert.

### v1.103.21 · A public status page
<sub>6 November 2026</sub>

- New Status page (in the menu, or transit-alert.com/status): whether TransitAlert is up, whether PTV's timetable API is answering, and how fresh the live train, tram, bus and V/Line feeds are, with uptime over the last 24 hours and 7 days. It's measured every 2 minutes, not claimed.
- About now spells out what alerts can and can't promise: a heads-up, not a guarantee. The usual-trip setup says the same.
- When PTV re-posts the same disruption under a new number, you no longer get a 'resolved' and then a 'new' push for something that never changed.

### v1.103.20 · Trains that end early, and what they become
<sub>6 November 2026</sub>

- Departure boards now flag a train that's been cut short: 'Terminates early at Flinders Street · timetabled to Frankston'. If Metro has published a reason, it's shown. If not, the app says it's a general reason (getting back on time after delays, covering a fault or another cancelled train), not this train's.
- Trains heading into the city show what they turn into: 'Then becomes a Glen Waverley train at Flinders Street', the other half of 'Arrives as a Mernda train'.

### v1.103.19 · Time to leave, missed changes, and Sydney's new airport
<sub>6 November 2026</sub>

- Usual trip alerts can now remind you when to leave: pick 5 to 30 minutes, and you get a push that far before your train really leaves, using its live time and platform.
- If your usual trip has a change of trains and the first train is running late enough that you'll miss the next one, you get a warning with the next service you can catch. It uses the late train's own timetable and live delay, not a guess.
- Departure boards show 'Arrives as a Mernda train' when the train that forms your service is still running its previous trip on another line, like a Mernda train that turns around at Flinders Street to become a Hurstbridge line service. Check where it's actually going before you jump on.
- New: Sydney airport buses. Every bus leaving Western Sydney International, live, including the free WS1 to St Marys and routes 772, 790, 825, 845 and 860, with stands and how full each bus is.
- Alerts that name a bus route only in their title ('Route 444: stop closures') now go to people following that route, instead of to everyone as a network-wide alert.
- Fixed a board showing where the arriving train's previous trip started as if it were this departure's origin.

### v1.103.18 · No stale cancellations
<sub>6 November 2026</sub>

- If PTV's live feed stops answering, trains and buses are no longer left marked cancelled from an old snapshot. After 10 minutes without fresh data, TransitAlert stops showing those cancellations rather than guess.

### v1.103.17 · Regional bus alerts go to the right town
<sub>6 November 2026</sub>

- Bus route numbers repeat across towns: Geelong, Ballarat and the Latrobe Valley all run a route 20. Notification settings now list each town's route separately ('Route 25 · Ballarat Station - Delacombe' and 'Route 25 · Geelong Station - Bell Post Hill'), and alerts only go to people following that town's route.
- If you already follow a bus route, nothing changes: you keep getting alerts for the route you picked, and no longer get another town's alerts for the same number.
- The Disruptions page no longer shows another town's alert on a bus route card with the same number.

### v1.103.16 · More bus journeys, smarter arrive-by
<sub>6 November 2026</sub>

- Tapping a bus now shows its journey far more often. When PTV's timetable can't be matched to the bus, TransitAlert shows the rest of that exact trip from PTV's live feed, with live times. It only does this when the bus is actually on that trip's route, not driving empty to its next one.
- Journey planner, arrive by: if the first train it finds gets in too late, it now looks for an earlier one that makes it, instead of telling you the trip misses your arrival time. Hurstbridge to Flinders Street by 8:20pm now offers the 6:52pm train, not the 7:31pm that arrives 8:38pm.

### v1.103.15 · Tram names, tunnel trips and fairer alerts
<sub>6 November 2026</sub>

- Tram and bus boards now say where the service goes ('Camberwell', 'East Coburg') instead of PTV's stop name ('Cotham Rd/Burke Rd #70'). A tram that really ends short still shows where it ends.
- Nearby boards show both sides of a split tram stop, like Flinders St/Swanston St, instead of only the closer one.
- Journey planner: Metro Tunnel trips boarding at State Library heading east (to Oakleigh, Westall, Pakenham, Cranbourne) now find the actual train instead of giving up.
- Alerts: Yarra Trams notices labelled 'Planned Disruption' that aren't service changes (staff travelling on a route) are no longer listed as works, and 'Extra Route 57a trams' notices count as extra services.
- Alerts: one-off incidents PTV never closed, like a single cancelled bus trip from June, no longer show as current.
- Notifications: if you follow all trams or all buses, a delay on one route no longer hides a different route's delay for the next 30 minutes.

### v1.103.14 · Cleaner V/Line boards
<sub>6 November 2026</sub>

- V/Line boards no longer show one train several times. PTV lists the same train under each coach route that starts with it (Geelong at 10:07 under two routes), and sometimes a minute or two off the timetable (Ballarat 5:13 vs 5:15). It now shows once.
- Trains on lines with 'via' in their name, like Traralgon via Morwell, Moe & Pakenham, are no longer labelled as coaches.
- A coach no longer shows as cancelled because it shares a run number with a cancelled train.
- Coach-route trips that start on the train no longer say they leave from the coach terminal.
- Early running is the same colour everywhere: departure boards, station boards and the service details.
- Journey planner: when it picks your next tram or bus for you, it now allows time for the walk between stops, not a flat two minutes.

### v1.103.13 · Live tracking you can trust
<sub>6 November 2026</sub>

- Buses and trams: the next stop now comes from where the vehicle actually is, so an early bus that has passed a stop no longer counts it as still to come. The last known position only shows when the vehicle is on that stretch, with how long ago it was seen, instead of jumping between stops or sitting at 0% or 100%.
- Stops still to come whose time has already gone now say 'Due', not 'Now' or '1 min ago'. When a bus's trip is only a best guess, its times no longer claim to be live or early.
- An early bus shows a note that it may wait at timing points to get back on time. The timetable doesn't say which stops those are, so they aren't marked.
- Trains: 'At platform' and 'Now at' only show when the train's live position puts it there, not just because the timetable says it should be.
- Trains no longer jump backwards when an older position arrives late, and a stopped train's carriages no longer flip ends from GPS wobble.
- Following a vehicle on the map keeps your zoom instead of snapping back in every few seconds.
- V/Line boards no longer list each regional train twice, and a V/Line board for a later time now shows that time.
- The map's top row of filters fits properly on iPhones, and the bus data report needs a correct value or an explanation before it sends.

### v1.103.12 · SRL dig tracker
<sub>6 November 2026</sub>

- New SRL dig tracker, under For train fans: the Suburban Rail Loop East tunnel boring machines (Alice, Hacia, Aayushi and Belinda), where they launched, where they're heading and the latest official metres dug, on a map of the route.
- Everything on it comes from official announcements, with the date and a link to each. Machine positions aren't published live, so none are shown.

### v1.103.11 · Report X'Trapolis 2.0 sightings
<sub>6 November 2026</sub>

- X'Trapolis 2.0 tracker: signed-in riders can now report a set they've seen, with the station, when and an optional note. Handy for test runs and sets in the sidings that the live feed doesn't show.
- Sightings are marked as rider reports, not live positions, and don't show who sent them. Each set's tile shows its latest rider report when it's newer than our own last sighting.

### v1.103.10 · Sandringham line back on its tracks
<sub>6 November 2026</sub>

- From Richmond to South Yarra, the Sandringham line was drawn up to 20 m west of its real tracks, over Swan Street. Both its rails now sit within 4 m of the real ones.
- Boards at South Yarra, Hawksburn, Toorak, Armadale and Malvern now show Gippsland V/Line trains running through without stopping.
- A bus or tram stop board that can't tell which side of the road its services leave from now says so, rather than mixing in buses going the other way.
- Stop boards no longer treat a place like Werribee South as the same as Werribee, which let buses from the other side of the road onto a board.
- Android: Back now closes an open train, tram, bus or stop card on the map, and the nearby panel, instead of leaving the app.
- The nearby panel no longer covers the map's live status line.
- Android: turning on notifications no longer says they're blocked when Google's notification service is just slow to answer, which often happens right after a phone comes online. It now waits longer, and tells you what actually happened.

### v1.103.9 · Trains running through, nearby boards and other cities
<sub>5 November 2026</sub>

- Station boards now show trains that run through without stopping, such as Frankston expresses at Ormond and V/Line at Berwick. Their times are estimates from the stops either side.
- The map's location button now opens nearby boards, including tram stops. Add buses, or go back to just the nearest station, in Settings.
- Disruptions now covers Sydney and NSW, Brisbane and the Gold Coast, and Adelaide, from each operator's own feed.
- On departure boards, a long list of notices is now folded so it doesn't push the departures off screen.
- The planner's 'Last train tonight' line is back. It went missing in an earlier update, and now counts every line that gets you there.

### v1.103.8 · Better share links, and departures first on boards
<sub>5 November 2026</sub>

- Share my trip now reads properly: 'I'm on a route 86 tram to Bundoora RMIT. Follow it live:'. Links are tidier too.
- Links pasted into messages now show a proper preview, such as 'Follow this tram live', instead of a bare address.
- Links shared from the beta app now open for anyone, without a beta sign-in.
- Passport sharing no longer says '1 stations'.
- Departure boards now show departures first. Heritage trips, freight and station access come after them.
- A link to a station's board now opens on the board on phones, rather than the station list.

### v1.103.7 · The planner now catches the next train of any line
<sub>5 November 2026</sub>

- The planner stopped waiting for one line when another gets you there sooner. Richmond to Box Hill late at night was telling people to wait 30 minutes for a Belgrave train when a Lilydale train was leaving first. It now looks at every line between your two stations, and names the one you actually catch.
- Trips no longer list a bus or tram that won't run for hours when a train leaves soon, such as a nearly 8 hour option from Flinders Street to North Melbourne.
- Two lines that catch the same trains no longer show as separate trips, and 'If you miss it' no longer repeats the same time.
- Trip instructions now read properly: 'a City Loop service' rather than 'towards City Loop service'.
- Service change warnings now cover the line you're actually put on.
- This What's new screen now shows the actual notes, not just a headline.
- Deleting your account now also deletes any Premium invite for your email address.

### v1.103.6 · Every station on its line
<sub>5 November 2026</sub>

- Every Metro station now sits within 10 m of its drawn line. Lines sharing a track now sit just either side of it, instead of up to 40 m away, and the Footscray to North Melbourne approach is back on the rails.
- The planner's Fastest label now counts the wait for your first train, and a trip with an unknown wait can't win it.
- Station boards now look up a train's stops for the right day, as the same run number can run a different trip on another day.
- Fleet Passport stamps now record what the live feed says the vehicle is, and public passports no longer show vehicle numbers.
- Home station shortcuts now show V/Line trains too. Stations you saved earlier need one visit to the map first.
- The app's fonts now load from our own server rather than Google.
- Pages that don't exist now properly report as not found.
- Bus power answers don't earn XP, despite what older notes said.
- The privacy policy and account deletion page now cover more of what we keep, including rides, stamps and bug reports.
- Admins: Send to everyone now reaches everyone in batches, and reports exact sent and not sent counts.

### v1.103.5 · Hurstbridge, Mernda and Sandringham back on their tracks
<sub>5 November 2026</sub>

- Between Parliament and Jolimont, the Hurstbridge and Mernda line was drawn as a sweeping curve up to 121 m off the rails. It now follows the real track.
- The Sandringham line now sits on its real track past Richmond, with its stations on the line.

### v1.103.4 · Set your home station
<sub>5 November 2026</sub>

- Set a home station for one-tap departures and trips. It stays private on your device.
- The planner no longer offers a long walk in place of a train you can catch. Walking legs are capped, and if walking really is the only option it says so with the real time.
- A train that ends at Flinders Street no longer says 'stay on'. Trains are only treated as continuing when the timetable shows they do, and otherwise you get the real change.
- Fixed a Frankston departure showing another line's stops.
- Admins get a Usage view with anonymous totals. The privacy policy now explains the anonymous page and device counts.

### v1.103.3 · Whole trips through the tunnel, and steadier buses
<sub>5 November 2026</sub>

- Train lines now follow the real tracks. A spacing meant for the city was pushing whole lines off their rails: Williamstown, Lilydale, Upfield and others are now back on them, with stations sitting on their lines.
- V/Line trains now show where they're really going, not the last stop in the live feed (a Bairnsdale train could read 'To Dandenong').
- Trams and buses no longer list their stops backwards. If we can't confirm a vehicle's trip, we now say its stops aren't published rather than guess. Stop times on a matched trip are marked approximate when the match is an estimate.
- Station boards keep showing train set numbers even when Trains or V/Line are filtered off the map.
- Other cities: vehicles whose last position is over 15 minutes old are no longer shown as if they're still there.
- Metro Tunnel stopping patterns no longer end or begin part-way at Town Hall or State Library. Trains are followed across the point where the timetable splits them, without repeating stops.
- Stop lists now highlight the station or stop a train, tram, bus or V/Line is actually at, going by its live position rather than the timetable.
- Buses and trams no longer drift while sitting still. GPS wobble is ignored, and a selected bus won't slide around the block on a small position correction.
- A vehicle that hasn't moved for a while now says so, for example 'Not moving, likely traffic lights or traffic' or 'Stopped between stations, likely waiting at a signal'. Transport feeds don't give the reason, so this is an estimate from repeated live positions.
- Fleet history shows the full trip first, with when we actually observed it underneath, so a short sighting no longer looks like the whole trip.
- A next stop whose time has passed now says 'Was due 1 min ago' instead of 'Arriving 1 min ago'.
- Journey Planner: fixed Start journey stopping itself on V/Line trips, cancelled buses and V/Line services being offered, cancellations and delays carrying into the next day, works being judged at today's date for a later trip, arrive-by for V/Line, live platform changes being hidden, and waiting and walking times being added together.
- Alerts: a major delay right after a minor one is no longer silently dropped, gradually growing delays on a tracked trip now alert you, and starting a one-off trip no longer cancels that day's usual-train alerts.
- People sharing a mobile network can no longer be locked out of the app together because of one bad signup.
- The disruption banner no longer covers the map's filter buttons, and the map credits its data sources again. A selected train's outline now follows the train instead of drawing a large box at street zoom.
- Southern Cross boards now include Shepparton trains, and Near me V/Line boards show the right station.
- Disruptions no longer says 'Good service' or shows zero when a feed has failed: it says the information is unavailable. Fleet PIDS demos are no longer labelled live.
- Deleting your account now also removes your reports and their screenshots. New traveller profiles get a neutral handle instead of one made from your name, and other people's exact check-in times are no longer shown on the leaderboard.
- Android: swiping away the live trip display now stops it, Settings warns when notifications are blocked, Back works on the recovery screen, and the app recovers if its page crashes.

### v1.103.2 · Clearer trips, better displays and safer live data
<sub>3 November 2026</sub>

- Journey results now keep a verified scheduled arrival separate from the departure time. When Metro's official dated timetable matches exactly, getting off uses the published arrival while boarding still uses the published departure. If the match is missing or conflicted, TransitAlert keeps the conservative existing timing instead of guessing.
- Destination search drops stale results while you type, so a fast search cannot select an older suggestion. V/Line plans keep the date and time you chose rather than silently using today's services.
- Route 64 boarding cards now distinguish the two directions from the timetable's actual platform and direction data. Shared stops no longer show a Route 16-only side as a Route 64 option, and accessibility remains tied to the route and exact boarding point.
- The Live Map now has line-by-line filters for Sydney and NSW alongside Melbourne, applying the same selection to routes, stops, vehicles and disruptions. It does not require changing the selected city first.
- Fleet PIDS: the refurbished Siemens display keeps long station, destination and next-stop names inside the screen on small phones. The EDi Comeng simulation is one orange LED matrix with wrapped preview messages instead of a page-wide marquee. Added labelled visual-reference choices for an earlier green Siemens display and Alstom Comeng; VLocity and Sprinter displays are clearly marked as visual references.
- When a live VLocity corridor match cannot identify an actual set, the app now says 'Live allocation unavailable' instead of presenting an invented set number.
- From an address, you can choose a nearby station as your public-transport start and keep a removable 'car parked at' reminder. TransitAlert deliberately does not claim parking availability, price, restrictions or accessible bays — check those at the station.
- The Android beta adaptive icon now uses Android's safe icon zone, avoiding the cropped or tiny-looking beta badge on round and masked launchers.
- Upload validation now checks both the declared image type and the image file signature before accepting a signed upload, rejecting disguised markup and mismatched image data.

## October 2026

### v1.103 · Your train's PID, with you on Android
<sub>31 October 2026</sub>

- Fleet history now retains a separate record for each observed dated working across Metro, V/Line, trams and buses. Existing observations have been backfilled; position samples remain separate. X'Trapolis history has more room on larger screens.
- VLocity formation labels no longer assume a single reported set means a three-car train. Distinct reported sets support the coupled count; unconfirmed lengths stay unconfirmed.
- Journey Planner now confirms the actual train and its calling points before giving boarding instructions, removing unnecessary changes when the same train carries you through. Missed-train replanning checks the next service and its connections.
- Phone journey steps now take priority over the map, with trip options folded away and clearer boarding times, platforms and arrivals.
- Southern Cross regional cards and the platform diagram now use V/Line's own published assignments, retaining A/B sections when supplied. Unnumbered roadside stops have boarding-point maps.
- Fixed a tram lock matching an unrelated train, oversized stop tooltips, misleading Now badges and numbered road-side labels. Close-up map detail is sharper.
- X'Trapolis 2.0 now has a set-by-set running-history view backed by recorded trips. Contactless concession estimates support linked entitlements and explain activation and refund timing.
- Departure boards now keep the next service for each line and direction visible alongside the soonest trains, so two nearby Upfield trains cannot hide a Craigieburn train 20 minutes away. Full station boards fetch more services before splitting by platform, and compact boards can expand to show later departures. The same coverage rule is used for NSW and other connected network stop predictions.
- Android beta 1.103.0 adds a Premium live trip display: lock a service in your active journey to follow its next stop in an ongoing notification. EDI Comeng uses the same orange dot-matrix font and message rules as Fleet PIDS; Siemens has its route strip, with Metro and regional styles for other fleets. Expand the notification for the display and your alighting stop.
- The trip display refreshes while the app is in the background, marks unavailable updates, and stops when you end or unlock the trip. Stop display hides it for that leg. Android controls the notification layout; iPhone Live Activities are not included yet.
- Public Metro destination labels no longer treat City Loop or Metro Tunnel feed split points as termini. Confirmed onward workings supply the real destination; Flinders Street remains valid when the service ends there.
- Android now shows a proper recovery screen when a page cannot load, with Retry and automatic recovery once internet access returns.
- Sydney and NSW rail stops on the main live map now open the richer station departure board, including other platforms and published rail replacement services. Tapping a stop opens its details on smaller screens too.

### v1.102 · Both sides of the road, and a new Android beta
<sub>30 October 2026</sub>

- Android app 1.102.2: disruption alerts now work in the app. Turn them on from the alerts prompt or Settings and they arrive like any other Android notification, even with the app closed.
- Android app 1.102.1: location now works (Near me, nearby stops, plan from my location), the back button closes sheets and goes back instead of quitting, Share my trip and Passport story images open the Android share sheet, Add to calendar hands the trip to your calendar app, and trip alerts like "your stop is next" now land in your notifications.
- Sydney station boards now include NSW TrainLink country trains and coaches (with their coach bay), and show rail replacement buses during trackwork instead of an empty board.
- transit-alert.com/changelog now opens these release notes, so they can be shared with a link.
- When a Transport Victoria live feed is down, departure boards fall back to the timetable straight away instead of waiting up to 15 seconds on every load.
- New: tap any Sydney or NSW train station on the live map for its live departures, laid out like the Melbourne boards: line colours, platforms, live countdowns, and on-time, late or cancelled for every Sydney Trains, Metro and NSW TrainLink service.
- Sydney and NSW train stations now show on the live map when you zoom in (Metro stations in teal), and NSW trains far off-screen no longer slow the Melbourne map down.
- New: Southern Cross now has the station's own concourse screens on its departure board: Regional Trains grouped by corridor (Geelong & Warrnambool, Ballarat, Bendigo, Seymour, Traralgon), Metropolitan Trains by line group with their platforms, and Regional Coaches, each with minutes to go.
- Fixed: on a Metro Tunnel trip (say Narre Warren to State Library) the trip screen wrongly said "This train doesn't stop at State Library — stay on to Town Hall". The timetable splits these trains at Town Hall and we weren't joining the halves; it now says to stay on, and stops at your station.
- Saved bus stops and tram platforms stay saved after timetable updates instead of showing as unsaved (and saving twice).
- Trip results lead with your trip: service-change notices for the route fold into one line you can tap to read, instead of pushing the trip off a phone screen.
- Fixed: picking a regional station (Traralgon, Bendigo, Seymour, Warrnambool…) in the planner said "No route found". V/Line trips now plan, and each one shows when you arrive, how long it takes, and every stop with its time.
- Proper app icons: a sharp icon at every size, one that fills Android's round icon shape instead of sitting shrunk in a white circle, and a browser tab icon.
- Bus boards no longer list the same bus twice (some operators publish a timetable copy and a live copy of each trip), and no longer show phantom buses "two hours late" that are really a later bus matched to the wrong trip.
- Fixed: when Transport Victoria's tram or train alerts feed went down, its disruptions vanished and we sent "resolved" notifications for disruptions that were still on. Alerts from a feed that's down now stay open until it's back and they've really ended.
- If our server is briefly unreachable or slow, you now get a plain message like "TransitAlert took too long to answer" instead of a technical error.
- Fixed: when a live feed was down, Cloudflare swapped our explanation for its own error page, so the app could only say something vague. The real reason now gets through.
- When Transport Victoria's tram or V/Line tracking goes down (as it did this morning), the map now says which one and that it's their feed, instead of a vague "Live feed unavailable".
- Nearby stops load straight away after an update instead of taking a few seconds the first time.
- The planner no longer sends you on rare special trains (like a Pakenham train from Richmond that runs a dozen times a timetable) when a regular service does the trip, and Flinders Street to Town Hall or Melbourne Central to State Library now tells you to walk underground.
- Metro Tunnel trips in the planner are one train again: Sunbury to Caulfield, Sunshine to Anzac and the like no longer show a made-up change at West Footscray.
- Departure boards at Flinders Street, Southern Cross and other termini now show which set is coming, from the train that turns around to run it, before it leaves.
- Beta: the live map now covers Sydney & NSW, Brisbane, Gold Coast, Cairns, Adelaide, Perth, Tasmania, Darwin and Alice Springs. Pick a city at the top. Vehicles show their route number, stops appear as you zoom in, and each city's disruptions and replacement buses are in the service details panel.
- New Android beta (1.102): download it from the Install page. It installs over the old beta and keeps you signed in.
- If signing in can't connect (a VPN, ad-blocker or picky network getting in the way), the sign-in screen now says what to try instead of showing a wall of technical SSL text.
- Tidier behind the scenes: signed-out visitors no longer trigger an error on every page, and Premium pages show their proper name in the browser tab.
- Tram stops now show both platforms. PTV was missing one side at lots of stops (Sydney Rd, Acland St, High St Preston), so we fill the gaps from the timetable. Each platform says which way it goes ("East side · Flinders Street") and its board only shows trams going that way.
- Bus stops now show one marker for each side of the road, at the real pole, labelled with where buses from that side go (for example "Towards Werribee" and "Towards Williams Landing"). Each side's board only shows buses going that way. Works across Melbourne using the timetable's pole positions.

### v1.101 · Report freight train sightings
<sub>29 October 2026</sub>

- Report a freight train you actually saw from its planned pass at a station. Include the observed local time, direction, location and locomotive or consist if known. Sightings go to the review queue and are not shown as verified live train positions.
- Long Island steel sightings now use the same freight-specific report flow instead of being filed as incorrect station data.

### v1.100 · Better stopovers, clearer bus details
<sub>29 October 2026</sub>

- The map disruption banner is now a set of swipeable cards, with planned closures shown separately and controls to move between notices.
- Weather warnings: Bureau of Meteorology storm, severe weather, flood, fire weather and heat warnings now show at the top of Disruptions with the lines they may affect. Turn on 'Severe weather' in notification settings to get them as alerts.
- Live map: show just one train type (HCMT, X'Trapolis 2.0, X'Trapolis 100, Siemens, Comeng…) from the Lines filter, with how many of each are running. Shareable as a link, e.g. transit-alert.com/?fleet=xtrapolis2.
- Tidier menu: the everyday tools up top, a 'For train fans' section, and the rest under 'More' (it remembers what you fold). Delays right now is in the menu now too.
- Near me, Delays, Get the app and the X'Trapolis 2.0 tracker now have the menu button, so you can always get back (in the installed app there's no browser back button).
- New X'Trapolis 2.0 tracker (in the menu): every new set running right now with its line, run number and whether it's a passenger service or a test/special run, one tap to it on the map, plus when the others were last seen (and where, for Premium).
- New Get the app page (in the menu): how to install TransitAlert on iPhone and Android, with an Install button where your browser supports it.
- Fleet PIDS: the HCMT, X'Trapolis 2.0 and V/Line screens only offer stations that train type serves (no more HCMT 'now arriving at Ballarat'), the route page follows the real line through the Metro Tunnel or City Loop, and the settings explain how they work.
- Fleet stabling is more accurate: trains passing a yard or waiting at the platform next to one no longer show as stabled in it, the Carrum and Mordialloc 'yards' (which were really the stations) are gone, Upfield Sidings is added, and a train that drops off the feed is only placed in a yard that's close by.
- Compact departure boards now show the train's length (6 cars, 7 cars) next to its set numbers, so you know how far along the platform to stand.
- My usual train: under Start journey, 'Alert me about this trip every…' picks the days (weekdays by default). On those days TransitAlert watches it from 30 minutes before and tells you about delays, platform changes and cancellations without opening the app.
- Plan a trip: 'Arrive by' a set time. It tells you when to leave for the option you pick.
- Add to calendar: put a planned trip in your phone's calendar with a reminder 10 minutes before you need to leave.
- The planner now knows the underground walks between Town Hall and Flinders Street, and State Library and Melbourne Central, so Metro Tunnel trips connect to the City Loop the quick way (Google Maps misses these).
- New Near me page: the closest stations and tram/bus stops with the next departures on every route and direction (in the menu and the home-screen shortcuts).
- Settings: show departure times as countdowns ('5 min') or clock times ('8:42 pm'), and a 24-hour clock option.
- Share my trip: on any train, tram or bus card, send someone a link that opens the live map on your exact vehicle.
- Saved trips in Plan a trip: star a trip (including its stops on the way) and reopen it in one tap. Kept on your phone, no account needed.
- Alerts PTV titles just 'Planned Disruption' now lead with what's actually happening (e.g. the public holiday timetable) on the map banner, station pages, lift notices and the planner, not only the Disruptions page.
- Rider reports: people on the same mobile network now count separately (carriers share one IP between many phones), and reports are kept through server restarts.
- Plan a trip no longer runs off the right edge of phone screens.
- Notification settings: each option's explanation now wraps onto its own line on phones instead of being cut off.
- Trips with stops: going back to an earlier leg keeps that leg's own leave time, instead of planning it at the later leg's time.
- A stop on the way can't repeat the start, the end or the stop before it.
- The last-train line follows your 'Leave at' time, so a trip planned for Saturday shows Saturday night's last train.
- Delays: trams and buses running 5+ minutes early no longer count as on time (early is how you miss one), and buses running empty off their route aren't counted.
- Plan a trip shows the last train tonight under each train leg, says when Night Network trains run all night, and warns when tonight's trains stop short (Alamein trains end at Camberwell at night).
- Trips with stops on the way: when the first leg starts with a train, the 'then leave around' time now includes waiting for the next train you can reach.
- Buses that have finished their trip and are running empty now show as faded grey markers labelled 'probably out of service' instead of looking like live route buses.
- Bus details group the power-type and fleet-number reports together. Fleet or slate numbers are reviewed, and the live registration is never guessed to be the fleet number.
- Plan trips with up to three stops on the way, including addresses. Choose how long to stay at each stop, then plan each leg from the time you will leave.
- Next-leg timing includes the wait for the first listed train you can catch, after allowing time to reach its platform.
- Tram and bus plans for a later departure now count the wait from your chosen leave time. You can also select the exact service to catch and have trip timing, alerts and tracking follow it.
- Trip alerts can open the planner with another route ready when your tracked service is cancelled or terminates early.
- The next-stop label no longer repeats the stop a train is standing at, and a tram held in traffic is not marked as past your stop just because its feed jumped ahead.
- Train, tram and bus cards now have anonymous, one-tap reports for issues on the service. Reports appear to other riders for 30 minutes.
- Train cards show Up or Down direction, and previous/next controls follow the same line and direction in station order.
- Premium station panels show confirmed trains passing without stopping, with estimated pass times.
- The new Delays right now page ranks train, tram, bus and V/Line services by observed lateness.
- Frankston and Stony Point stations now include Long Island steel train sightings without inventing timetable times.
- Station access directions now start at the street entrance. Lift outages and step-free routes through lifts are called out, and routes no longer detour through rail-replacement bus stops.
- Glance shows saved stops and their next three services without the map.
- Route reliability records live lateness by time of day. Once enough observations are available, stop boards can show typical performance.

### v1.99 · Plan ahead, meet people, never miss your stop
<sub>29 October 2026</sub>

- Meeting someone? Open a station, pick the line they're coming on, and see which trains will arrive, when, on which platform and where each train is right now.
- Tram and bus stop boards can show any time — tomorrow 8am, Saturday night — and filter to just the routes you want.
- The Journey Planner can plan for later: set when you're leaving and tram and bus options use the timetable from then.
- If your tracked trip is cancelled or terminates early, the alert opens the planner already filled in with your trip, showing other ways to get there with what's running now.
- Tracked trams now warn you when they will terminate early, and stay tracked if they're re-signed.
- Trip alerts tell you when to leave for your first tram or bus, based on how far you are from the stop and when it actually departs.
- On trams and buses, the one-stop-to-go alert now says 'Press the stop button now'.
- Stop boards flag a tram or bus that's likely to be busy because it follows an unusually long gap in service. Melbourne's feeds publish no live crowding, so this is always marked as an estimate with its reason.
- HCMT and X'Trapolis 2.0 carriages now show as plain numbers (9137, 8401), as they're written on the train.

### v1.98 · Onboard screens, cleaner disruptions
<sub>29 October 2026</sub>

- Fleet PIDS (Premium) now recreates the refurbished Siemens Nexas ceiling display: the route line in the line's colour with the train's position, upcoming stations, the next station highlighted, 'To' and 'Now arriving' pages. It follows a real Siemens train's remaining stops.
- Fleet PIDS also recreates the EDi Comeng's orange LED display — a 120×7 dot matrix that scrolls long messages — with its real message cycle: 'Direct to … service stopping all stations', 'The next station is …', 'Arriving …', express running and terminating messages, following a live Comeng.
- Disruptions that PTV still lists long after they ended (some by months) no longer appear, and notices that don't start until later today are shown as planned instead of happening now.
- Locked tram journeys now keep the tram's fleet number, so their stop list and progress load reliably.
- Every tram on the map now shows its direction arrow straight away, pointed along its route, instead of waiting for it to move.

### v1.97 · Trams, buses and bikes: real routes, real access
<sub>29 October 2026</sub>

- Tram stop accessibility now reflects what each route actually runs. TransitAlert counts the low- and high-floor trams seen on every route over the last three weeks, so Route 64 (high-floor B2s only) shows steps even at a Swanston St platform stop, while low-floor Route 16 trams at the same stop can be step-free.
- Trams that will finish short of their route's usual end — a depot run or a fault turn-back — now say 'Terminates early · not going to …' on the stop board.
- Following a tram or bus now tells you how far it is from your stop: '3 stops from Swanston St/Collins St · 1.2 km along the route · due 10:42 (4 min)', or that it has already passed. Your stop is the one you opened, or the nearest stop on its route to you, and it's bolded in the list.
- Tram and bus routes on the map now follow the actual roads using the official DTP route shapes, instead of straight lines that cut between stops.
- Every live bus now shows a direction arrow. Buses that report no bearing are pointed along their route line.
- The bus map no longer shows 'Live positions are currently delayed' just because older duplicate positions were discarded; it only appears when positions are genuinely old.
- Journey Planner: choose what you're bringing — a bike, folding bike, or an e-scooter that does or doesn't fold. Trains take all of them; trams and buses only take folded ones, so they switch off with the reason shown. Walking legs become riding legs, and riding the whole way is offered for longer trips.
- Reliability fixes across push alerts, alert resolution, sign-in sessions, privacy, request limits and background jobs, plus safer deployments with no downtime while updating.

### v1.96 · Beta features reach the public app
<sub>25 October 2026</sub>

- The current beta features are now included in the public web app, including line-by-line map filters and the latest accessibility, fleet and regional rail improvements.
- Beta sign-in and account recovery now stay accessible, and a Premium sign-in requirement no longer appears as a device or network ban.
- Beta testers can try the next map presentation: a quieter Midnight background, a Daylight option and the Original map, with a saved appearance choice, distance scale and map credits. Open Map layers to compare them.

### v1.95 · Accessible travel update
<sub>23 October 2026</sub>

- Bus and tram stop cards now distinguish confirmed accessible boarding, parent-station-dependent access and stops where the feed provides no step-free assurance.
- Roadside bus stops that need an on-site access check now show that caution without being incorrectly labelled inaccessible.
- Bus departure rows now say ‘No bay assigned’ when a service has no published bay, rather than implying that the service is unavailable.
- Station platform selectors now show each platform’s access state, with screen-reader labels for confirmed, unavailable and unpublished access information.
- Station wayfinding cards now make clear which published access details they cover and where to check for tactile paving, hearing loops, assistance and platform–train gap information.
- Tram and bus route badges, vehicle headers and journey chips now choose a high-contrast black or white label for each actual route colour.
- Bus vehicle cards now direct riders to the selected stop for boarding-access information, since the live vehicle feed does not publish per-service bus accessibility.
- Stops with no published step-free assessment now show a practical manual access check and an access-update link instead of the unhelpful ‘Accessibility unknown’ dead end.
- Tram stop cards now use stable DTP GTFS boarding-point IDs and route direction to show the scheduled-service accessibility, the confirmed low-/high-floor status of the next allocated tram where available, the source and refresh time. Route 64’s two sides of North Rd/Hawthorn Rd #63 are assessed separately.
- Reviewed Metro Tunnel through-running, line colours and V/Line connections against current network data so the live map keeps the same presentation standard across Metro, V/Line, tram, bus, Sydney Trains and NSW TrainLink.
- Internal train IDs and missing fleet fields now use one clear ‘Live allocation unavailable’ fallback across Metro, V/Line, tram and bus panels; vehicle positions and service details remain available.
- Bus cards now keep the live registration separate from the verified fleet/slate number, flag an unreported number clearly and offer a direct correction report. Bus stopping-pattern lookups now use PTV’s vehicle/run matching rather than sending GTFS timetable IDs to the wrong PTV endpoint.
- V/Line station cards now use V/Line’s published rail GTFS timetable for train departures, so rail services no longer disappear behind the separate regional-coach feed. Cards show the exact scheduled departure time and destination, preserve coach services under their own heading, and only show a platform when it is published by the timetable or live feed.
- Opening a V/Line rail departure now shows that exact service’s published stopping pattern and station times instead of trying to match it through an unrelated Metro timetable run.
- Saved V/Line stations now use the rail timetable too, and saved-stop cards show the scheduled clock time alongside the live countdown.
- The V/Line journey planner now finds direct rail journeys from the published rail timetable, including their real intermediate stops, instead of searching the coach-only regional endpoint.

### v1.94 · Self-hosted release · Sydney fleet fixes
<sub>20 October 2026</sub>

- TransitAlert now runs directly from its host PC and local database.
- Sessions, notification storage and the push service worker now use TransitAlert-only names.
- The early-access, privacy and account-deletion pages now describe the self-hosted service.
- Sydney fleet cards now place XPT before the train type whenever the live feed omits it.
- Sydney Trains and NSW TrainLink services now open the same full live-detail card from the map.
- Sydney train cards now show the service's full stopping pattern, platforms and scheduled times, with live timing whenever TfNSW publishes it.
- Sydney stopping patterns now read TfNSW's Sydney Trains live-update feed as well as the static timetable, so predicted stop times and delays update in the card.
- Sydney and Melbourne train timelines now show separate arrival and departure times, station dwell time and an at-platform state whenever live data supplies both times.
- Station boards now keep a separate last-hour view of recently departed services, so you can check what left after it has dropped off the live board.
- Metro train labels now put the rolling-stock type before the set number, such as HCMT Set 01, EDI Comeng Set 324 and Siemens Nexas Set 701.
- Selected HCMTs stay as a stable, track-aligned seven-car strip at junctions, and the map detail-panel close button now handles taps reliably.
- Sydney live-detail cards now normalise TfNSW route IDs before choosing a line name, code and colour.
- Inner-city station boards now group live departures by platform, matching the clearer Southern Cross presentation.
- Platform-first boards retain services whose platform has not been published and label them clearly instead of hiding them.
- Fleet PIDS now keeps its editable journey screen visible instead of replacing it with a static dark reference image.
- Fleet PIDS language, live-set selection and regional route screens now update consistently with the editor controls.
- Unexpected page rendering errors now show a recovery screen with a reload option instead of a blank screen.
- Fixed the map-start crash caused by an obsolete NSW train-panel variable, which could show a blank or reload screen on every device.
- The initial page now has its own visible loading and reload screen, covering failed JavaScript chunk loads before React starts.
- A stale JavaScript chunk now triggers one safe automatic refresh, and obsolete site-wide service workers are removed on launch.
- Profile photo editing now reports invalid file choices and releases temporary image previews reliably.
- Live-feed errors now identify the affected mode instead of incorrectly calling every failed update a rail failure.
- Release checks now test the dedicated Sydney live-vehicle feed as well as Melbourne vehicle feeds.

### v1.93 · Ros feedback · map & journey reliability
<sub>7 October 2026</sub>

- Map zoom performance improved by deferring tile refreshes until zoom settles and disabling expensive Leaflet zoom animations.
- Map layer controls now use the highlighted state itself instead of redundant ON/OFF text, keeping the control compact without losing its accessible pressed state.
- Startup viewport validation now rejects stale coordinates outside Transit Alert's supported Australian service region and falls back to Melbourne.
- Active journey stopping patterns now use the official Metro pattern as a second source when realtime data omits an intermediate stop.
- The app no longer warns that a locked train skips the requested station just because that station was missing from one live update.
- Inserted stopping-pattern rows deliberately have no invented ETA; they are shown as verified route stops until live timing is available.
- Station matching now handles common 'Station' and 'Railway Station' suffix differences consistently.
- Saved map-layer settings are now validated on load so malformed or non-boolean stored values cannot silently put the map into an invalid filter state.

### v1.92 · Bug fixes from your reports
<sub>7 October 2026</sub>

- Fixed the live map opening on an old ultra-zoomed-out viewport and leaving you looking at the globe. Normal launches now open around Melbourne while useful deep-link map positions are preserved.
- Centred the live-map mode buttons and removed the redundant visible ON/OFF labels; the highlighted state still shows which layers are enabled and accessibility state is retained.
- Corrected the reported Pleasant St / La Trobe St, Redan bus-stop lookup so the stop no longer falls back to an unrelated stale stop ID.
- Physical tram platforms that share one PTV stop ID now keep their own side when opened, so two roadside stops are never collapsed back into one selected stop.
- Fixed disruption handling for notices whose customer-facing text says they are cleared or resolved, so they are not presented as active current disruptions.

### v1.91 · Clearer vehicle direction on the live map
<sub>6 October 2026</sub>

- Tram and bus markers now show their front so their direction of travel is easier to read.
- Tram direction follows the reported next stop when available, with recent movement as a fallback.
- Journey Planner keeps bus options visible alongside trams, supports transfers between buses and trams, and flags current route disruptions when PTV reports them.

### v1.90 · Live map polish & release readiness
<sub>5 October 2026</sub>

- Frankston line map geometry now renders the Flinders Street–South Yarra corridor as two visible tracks.
- Metro consist carriage spacing increased for clearer live-map reading while keeping the live vehicle point unchanged.
- Release validation completed across fleet, GPS, Passport, notifications, reports, journey, network and station helpers.
- Transit data remains sourced from Transport Victoria GTFS/GTFS-R and the PTV Timetable API.

### v1.89 · Report & feedback
<sub>5 October 2026</sub>

- New Report / Feedback in the menu: bugs, incorrect train/bus/tram/stop data, disruption issues, feature requests and general feedback, in a short form that only asks what's relevant.
- "Something looks wrong?" links on vehicle details, stop boards, train services, disruptions, notification settings and trip plans pre-fill what you're looking at.
- Bug reports attach the app version, device type, OS version, screen and connection state — nothing personal. Screenshots are optional and stored privately.
- Data corrections can include an optional location check that confirms you're on or near the vehicle.
- Before you send, TransitAlert shows reports that look like the same problem so you can group yours with it.
- Every report gets an ID (TA-XXXXXX). Account → My reports shows its status, replies, and lets you add information later; the menu shows when one is updated.
- Crowd-sourced bus power answers still need 3 riders, and now get a quick admin check before going in the register.
- Active journeys recover cleanly if saved data is damaged or storage is full, instead of losing the trip when you lock onto a vehicle.

### v1.88 · Smart notifications
<sub>5 October 2026</sub>

- Notifications rewritten to be short and lock-screen friendly: "Frankston Line · Station works — Hawksburn · 10am–2pm today — Tap on/off and top-ups unavailable."
- New Smart notifications settings: choose priority levels (Critical, High, Normal, Info, Resolved) and extras (tracked trip, works reminders, combined summaries, favourite fleet, rare fleet).
- Priority comes from the disruption feed itself — cancellations and buses replacing trains are Critical, delays of 15+ min and police incidents are High.
- The same disruption is never sent twice. If it gets worse (e.g. delays 5 → 15 min) or turns into a cancellation you get an update, which replaces the earlier notification.
- Resolved notifications when a disruption you were told about ends early. Planned works ending on time and very short blips stay quiet.
- Three or more minor alerts at once now arrive as a single summary.
- Disruptions page: major train disruptions now show an "Avoid" box — the affected section, other metro lines that stop at those stations (with their current status), and any advice Transport Victoria gave. Built only from the timetable network and the alert itself.
- Tracked trips: after Start journey, get pushed if your service is running late, changes platform or is cancelled — works with the app closed.
- Works reminders about 30 minutes before planned works on lines you follow (when Works & closures is on).
- Rare fleet sightings (opt-in) and favourite fleet alerts can be switched on or off per device.
- Tapping a disruption notification opens it directly on the Disruptions page.
- Disruptions page and notifications name Metro Tunnel through trains by their real start and end (e.g. Cranbourne to Sunbury, not Cranbourne to Arden).
- Departure boards and trip planner no longer list trains that have already left.
- Journey planner: rides through Flinders Street on City Loop lines now show the right direction and departures.
- Train panels show the real terminus when the live feed stops short, and guest service names use the right origin.
- Heritage trips that have already run drop off, and station pages show the next two.

### v1.80 · Victoria network exploration Passport
<sub>4 October 2026</sub>

- XP and levels have been removed from the Passport, leaderboard, check-ins and share images.
- Ride and vehicle collecting is no longer part of TransitAlert.
- New 'What is TransitAlert?' page with a quick tour of the app. Google Play release coming soon.
- Train panels now show the consist as separate cars, grouped into their units with a coupler gap between them.
- Buses not yet in the register ask 'What powers this bus?' when you're on or near one. Answers are saved once 3 riders agree.
- The map layers menu now includes Sydney & NSW TrainLink, and the filter counts match what's on the map.
- Inner-west routes 216, 220, 223, 232, 234, 235 and 236 now show Kinetic as the operator.
- Fixed the next-stop highlight on some Metro train stop lists.
- Passport achievements have been redesigned around network exploration and TransitAlert-specific milestones.
- The Passport is now positioned as a secondary feature alongside live tracking, journeys, delays and service information.
- Vehicle/fleet collection and competitive leaderboard mechanics are no longer presented as the core Passport experience.
- Existing station check-in records are preserved.
- V/Line journey platforms now use a live-first platform pipeline: live assignment, exact timetable stop, published GTFS platform code and verified fallback.
- Platform enrichment now covers the full V/Line journey, including intermediate stations and shared station stop IDs.
- V/Line timetable matching checks alternate timetable versions before falling back, reducing missing platform information without inventing a platform.

### v1.77 · Cleaner live map, vehicle filters and Android notification readiness
<sub>4 October 2026</sub>

- New Map layers control lets you independently show or hide Metro trains, V/Line, trams and buses. This is especially useful when zooming into busy parts of the CBD.
- Android push notifications now have a high-priority fallback channel so supported alerts can appear as heads-up notifications, including when the app is closed.
- Native Android app metadata now uses the Transit Alert name and store-ready description.
- Passport ranking and achievement information is clearer about how progress and tiers work.
- Version 1.77 rolls the map, notification and release-readiness work into one release.

### v1.75 · Live data you can trust, station wayfinding and Set 7 back in service
<sub>4 October 2026</sub>

- Live vehicles are validated for missing or stale timestamps, missing route, next stop, destination or identity, large delays, cancellations, skipped stops, duplicate identities, map jumps, backwards movement and changed workings. Suspicious vehicles are flagged, never hidden.
- The vehicle sheet shows a Data quality section only when something is unusual, in plain English.
- Vehicles with a position that hasn't updated recently, or that jumped unexpectedly, are drawn faded on the map.
- Degraded live feeds now say timetable information is still available.
- Departure boards show a Getting around card from Transport Victoria's official station data: platform accessibility, and the quickest and step-free routes between any two platforms.
- Metro train sheets show official wheelchair accessibility and bike rules for that exact service.
- Journey planner: where you're told to change trains, it now names the next trains that officially run through onto the next line (e.g. Sandringham trains that continue as Werribee trains at Flinders Street), so you know when you can stay on.
- V/Line train sheets show official accessibility and bike rules; V/Line stations such as Southern Cross and Ballarat get the Getting around card.
- Tram sheets show whether a low-floor tram is scheduled — and if a high-floor tram is actually running instead, they say so.
- Tap any departure for a Service information sheet: destination, live status (on time / late / cancelled), the exact train if it's already out, platform, the next 5 stops, accessibility and bikes — plus a Data quality note only when something's unusual.
- Station panels on the map now include Getting around, and show where rail-replacement buses leave from (official stop location, one tap to open in Maps).
- X'Trapolis 2.0 Set 7 returned to passenger service; the roster now shows how many sets are in service.

### v1.70 · Door-side guidance, journey reliability and cleaner live boards
<sub>3 October 2026</sub>

- Direction-aware tram door-side guidance is calculated from the service stop sequence and PTV-sourced boarding-point geometry; unavailable geometry is never guessed.
- Train door-side labels continue to distinguish published/known information from platform-derived estimates.
- Surface journey ranking includes the real wait until departure rather than treating every candidate as if it departed immediately.
- Surface transfers are only selected when the second service can actually be caught after the first service arrives and the transfer allowance is satisfied.
- A failed tram vehicle-position feed is now distinguishable from a feed that is healthy but currently has no matching vehicles.
- Journey Planner and stop boards continue to use timetable information when realtime vehicle positions are unavailable.
- Platform displays no longer use the ambiguous Platform TBC wording.
- Version 1.70 consolidates the journey, door-side and live-board reliability work completed for this release.

### v1.65 · Passport patterns, profile polish and tracking fixes
<sub>3 October 2026</sub>

- Passport achievements now reward travel patterns such as 5-station days, 3-line days, returning to your starting station, repeat visits and Metro + V/Line days.
- Profile photos can be zoomed and cropped before saving, while the existing upload privacy protections remain in place.
- Old V/Line now uses its orange, green and white theme palette.
- MET now uses a yellow and green theme palette.
- Departure boards continue to distinguish current and next services and split V/Line coaches from trains where applicable.
- Version 1.65 rolls these fixes and polish into one release.

### v1.60 · Fleet Passport for trams & buses, profile pictures, themes and freight times
<sub>3 October 2026</sub>

- Fleet Passport (was Train Passport): stamp the trams, buses and V/Line trains you ride, not just Metro trains. Trains are worth 100 XP, trams and buses 50, and riding one again on a later trip +5.
- Fair play: your GPS is now checked against the vehicle's live position on our server, not just in the app. There's a short wait between stamps, re-riding the same vehicle only counts every 3 hours, and daily limits apply separately to trains, trams and buses.
- Routes ridden: your first ride on each tram or bus route earns +25 XP. See your tram and bus route collection on your passport.
- Bus power: after stamping a bus whose power type we don't know yet, tell us if it's electric, diesel, hybrid or hydrogen. Once 3 riders agree, it's added for everyone and you earn +25 XP.
- Profile pictures: add a photo in Edit profile. It's cropped to a small square and location data is removed before upload. Shown on your passport, your profile and leaderboards.
- Themes: choose Classic, Metro, Connex, Comeng, V/Line, Tram or Bus in Settings (or Edit profile). The theme colours the whole app and the map. Signed in, it follows your account to every device, and visitors see it on your profile card.
- New stamp screen: checking in at a station now shows your stamp landing, XP counting up, your level bar filling (with level-ups), progress on that station's lines, rarity, and any achievements you just unlocked.
- Freight due: stations on the Albury and Adelaide lines show planned freight trains for the next 12 hours, with train number, operator, cargo and length. These are ARTC's planned paths, not live tracking.
- Leaderboards now count all your XP, including train, tram and bus stamps.

### v1.50 · Station Passport, saved stops and choose your modes
<sub>3 October 2026</sub>

- New: Station Passport. Check in at any Metro or V/Line station to collect a stamp. GPS-verified, so you actually have to be there.
- Earn XP and level up, complete lines, keep daily streaks and unlock achievements like Loop the Loop, Tunnel Vision and End of the Line.
- Be the first TransitAlert traveller to stamp a station for a Pioneer bonus.
- Collect stamp right from any station on the map or Departure boards — no need to open the Passport.
- Share card: turn your passport into an Instagram-ready image with your level, stats and stamps.
- Next stamps to grab: the closest stations you haven't collected yet, one tap from a journey plan.
- Weekly challenges: three new goals every Monday, like a featured line week, Out and about or a Country trip.
- Streaks: a reminder on the Passport and a 🔥 badge in the menu when your streak is about to lapse.
- Follow friends and race them on a Friends leaderboard. Find anyone by @handle.
- Station cards show how many travellers have stamped that station and who got there first.
- Rare stamps: stamps few travellers hold glow as Rare or Legendary. Sort your stamp book by Newest or Rarest.
- Friends activity: see what the people you follow have collected in the last two weeks.
- Line leaderboards: pick any line to see who's collected the most of its stations.
- Passport network map: every station you've collected lights up green on a map of the network, with your % of Metro done. Tap a stamp to open that station.
- Plan a trip shows how many stations on each route you haven't stamped yet.
- Share to story: after a new stamp, make a 'Just collected' Instagram story with the stamp, your handle and level.
- Fair play: check-ins take a few GPS readings to spot fake locations. Anything that looks spoofed is held for review instead of counting. Up to 25 new stamps a day.
- Station of the Day: one featured station every day, worth +100 bonus XP if you check in there. New achievements: Daily Special and Daily Hunter.
- Report button on traveller profiles for cheating or offensive handles and bios.
- Public traveller profiles and a leaderboard (all time and last 30 days). Only your handle is shown — never your real name. You can go private any time.
- New: Save any train station, V/Line station, tram stop or bus stop with the star.
- Saved stops on the live map: tap Saved next to the vehicle toggles for the next 3 services at every saved stop. They're also at the top of Departure boards.
- Every saved-stop time says whether it's Live (real-time from PTV), late/early by how much, or Timetable only.
- Saved stops warn you when a disruption is affecting a route at that stop.
- Plan a trip: choose which modes to use. Turn Trains, Trams or Buses on and off and the planner only suggests trips that use the ones you want.
- Map: V/Line tracks that share Metro corridors (e.g. Dandenong–Pakenham) are drawn beside the Metro line instead of on top of it, so the blue Pakenham line is always visible.
- A What's new screen shows returning users the highlights after an update.
- About page explains where delay figures come from and how reliable each mode is. Privacy policy covers Station Passport.

## September 2026

### v1.42 · Loose ends
<sub>29 September 2026</sub>

- About, privacy and account-deletion pages had you contacting a Google Play listing that doesn't exist. They now give an email address.
- Privacy policy describes web push, not Android.
- Plainer sign-in wait screen and access message.
- Disruption alerts stop polling two feeds that don't exist and stop looking up tram stops PTV can't find.
- Error messages say what went wrong in plain words instead of showing raw server codes.
- Sign-up rejects temp-mail addresses and email domains that can't receive mail.
- Pages open straight away instead of waiting on a background access check.
- Can be added to your home screen properly (needed for notifications on iPhone).
- Mistyped links get a proper not-found page.
- Fleet recording runs about 3x faster.
- Bot protection on sign-up, sign-in, password reset and address search.
- Fleet data is now checked for Premium on the server, not just hidden in the page.
- Sign in with your email only. The old username shortcut is gone.

### v1.41 · Cleanup
<sub>28 September 2026</sub>

- New look: IBM Plex throughout, squarer corners, less glow.
- Sidebar sections renamed: Plan a trip, Disruptions, Departure boards, Fleet.
- The map stops following a selected train once you drag it yourself. Tap the train again to follow.
- Live status no longer flips back to "Connecting" every time you pan or tap something.
- Map search: clear button, Esc to close, and it tells you when nothing matches.
- Train card is shorter. Origin/destination was shown three times; now it's once.
- Station dots shrink when you zoom out, so the network reads as lines.
- Show specials only appear on days they actually run.
- Fixed: tram/bus legs in an active journey had buttons inside buttons.
- Guests no longer re-check their login on every page.

### v1.40 · Smoother tracking
<sub>26 September 2026</sub>

- Vehicles glide between updates instead of jumping. Big GPS corrections still snap.
- A selected vehicle stays on the map through short feed dropouts.
- Better cross-city matching, incl. Sandringham ↔ Werribee/Williamstown via Southern Cross.
- Tidied CBD track geometry around Southern Cross and Flinders Street.
- Boards label Current service / Next service, including split Metro Tunnel platforms.
- Door side shown above platform. Early running shown properly.
- V/Line: exact trip matches first, inferred ones labelled. VLocity formation when known.
- No more doubled markers at shared Metro/V/Line stations.
- Fewer duplicate disruption notices.
- Fewer pointless refetches across the app.

### v1.2 · Accounts, push alerts, tram and bus stops
<sub>22 September 2026</sub>

- Accounts. Free to make one; Premium unlocks the fleet page. Everything live works without one.
- Push notifications for disruptions, filtered by type and by line (V/Line split into its five corridors).
- Disruptions page: summary at the top, counts per type, urgent ones first.
- Tram and bus stops show when zoomed in. Tap one for its board.
- Tap a tram, bus or V/Line train to see its full run on the map.
- Fixed: big bus interchanges like Berwick Station showed no departures.
- Locate button, and the planner can start from where you are.
- New icon.

### v1.1 · V/Line rolling stock and fleet history
<sub>18 September 2026</sub>

- V/Line on the map and fleet page: VLocity, Sprinter and N class, from the feed's own labels.
- Regional positions named after V/Line stations ("near Dingee").
- Stony Point shows as the Sprinter it is.
- Fleet classes with nothing running stay in the filter with a 0.
- Fleet history: positions every 5 min, kept 14 days.
- Half-a-journey tunnel alerts resolved to the whole run.
- Line colours from a fixed palette, no more grey chips while loading.

### v1.0 · Live tracking and journey planning
<sub>18 September 2026</sub>

- Live metro trains and trams, buses when zoomed in. Consists shown ("HCMT · Set 60").
- Next stop, platform, countdown and delay from the trip updates feed.
- All metro lines drawn from PTV's GTFS shapes, incl. Metro Tunnel and City Loop.
- Trip planner with live departures. Tunnel through-running counts as one train.
- Disruptions from PTV plus the realtime alerts feed.
- Departure boards for every station.
- Fleet list, searchable by set or car number.
- Settings for start page, labels, refresh rate.

### Early build 1.0 · Original TransitAlert 1.0 release
<sub>10 September 2026</sub>

- Released real-data fixes across trains, trams, buses and alerts, with the About page and search-engine metadata.

### Early build · Project documentation update
<sub>6 September 2026</sub>

- Updated the public README with current project information.

### Early build 0.95 · Live tracking improvements
<sub>5 September 2026</sub>

- Released live tracking improvements, added live V/Line stopping patterns and corrected regional service identity on station boards.
- Clarified map labels and published the 0.95 release notes.

## July 2026

### Early build 0.92 · Verified departures and bus stops
<sub>21 July 2026</sub>

- Connected station departure boards to verified timetable data and added bus-stop departures.
- Bound timetable feed request times so slow upstream responses do not stall the app.

### Early build 0.91 · Real-data and live map improvements
<sub>19 July 2026</sub>

- Improved transit data and map accuracy across trains, buses and trams, including viewport-based live vehicles and mixed-mode routing.
- Removed synthetic live transit data, added live train tracking on iPhone, and improved mobile map layout and notifications.
- Released fixes for verified departures, map labels, service identity and real-time vehicle presentation.

### Early build 0.90 · Guest live map release
<sub>19 July 2026</sub>

- Released public guest access to live trains and the fleet board.
- Improved guest sessions, mobile onboarding and notifications, and made account sign-in safer with temporary-password changes.

## June 2026

### Early build · GitHub Pages and Render deployment
<sub>27 June 2026</sub>

- Set up split deployment for GitHub Pages and Render, then refined the Pages workflows and fallback configuration.

### Early build · Clearer alert corridors
<sub>15 June 2026</sub>

- Refined alert-corridor labels to make disruption information easier to follow.

### Early build · Map interchanges and fleet views
<sub>14 June 2026</sub>

- Polished interchange presentation on the transit map and refined fleet views.

### Early build · Alerts and replacement-bus map updates
<sub>12 June 2026</sub>

- Polished disruption alerts and improved replacement-bus map states.

### Early build · Fleet boards, V/Line journeys and station tools
<sub>11 June 2026</sub>

- Improved V/Line journey labels and alerts, mobile fleet boards, XPT fleet support, and fleet filters.
- Refined station markers and platform displays, and expanded the PID Studio and map-debug tools.
- Added clearer project attribution and improved station-map presentation.

### Early build · Map status and shared colour refinements
<sub>3 June 2026</sub>

- Corrected map status rendering and consolidated transport-mode and report colours.

## May 2026

### Early build · Shared transport-mode styling
<sub>31 May 2026</sub>

- Refactored shared transport-mode and report-colour constants for more consistent map and alert styling.

### Early build · Lighter iPhone map rendering
<sub>20 May 2026</sub>

- Added a leaner iOS map-rendering path to improve performance on mobile devices.

### Early build · Mobile stability and train overlays
<sub>19 May 2026</sub>

- Added mobile crash diagnostics and prioritised train overlays for more stable map rendering.

### Early build · Fleet names and mobile map performance
<sub>18 May 2026</sub>

- Clarified Comeng fleet variants and reduced station-marker work on mobile.

### Early build · Track-aligned station markers
<sub>16 May 2026</sub>

- Aligned station markers with rendered tracks and removed outdated City Loop and V/Line overlays.

### Early build · Mobile maps and corridor geometry
<sub>15 May 2026</sub>

- Improved iPhone map performance, station-marker density and accessibility, including a map legend.
- Refined shared-track and Burnley Loop geometry, and added or adjusted corridor markers around Sunbury, Sunshine, Craigieburn and V/Line junctions.
- Improved station boards and public service abbreviations across the northern corridors and Metro Tunnel.

### Early build · Tester access controls
<sub>14 May 2026</sub>

- Added admin-managed tester access for the beta registration flow.

### Early build · Account security and Render support
<sub>13 May 2026</sub>

- Strengthened account handling, refreshed independent app branding and improved the mobile map.
- Added runtime database support for Render and improved touch targets on City Loop markers.

### Early build 0.88 · Fleet validation and Ballarat corridor
<sub>12 May 2026</sub>

- Corrected fleet validation and added the Ballarat corridor, alongside Render configuration fixes.

### Early build · Render authentication and station fixes
<sub>11 May 2026</sub>

- Improved tester registration when a database is unavailable, reduced Render authentication noise and tightened station-marker spacing.

### Early build 0.87 · Render deployment support
<sub>10 May 2026</sub>

- Added and stabilised Render deployment support, including its package-manager build configuration.

### Early build 0.86 · Track alignment and map debugging
<sub>9 May 2026</sub>

- Expanded map-debug controls, restored the Burnley Loop and refined Glen Waverley track alignment.

### Early build 0.80 · Planner, onboarding and live rail improvements
<sub>8 May 2026</sub>

- Added onboarding and station boarding guides, guest sign-in and registration entry points, and a more stable journey-planner flow.
- Improved viewport loading, account administration, V/Line stop restrictions and XPT route support.
- Refined the logged-in menu, station controls and app version history.

### Early build · Surface transit and hosting setup
<sub>7 May 2026</sub>

- Added live surface-transit updates and set up Netlify deployment, with compatibility and fallback improvements for serverless hosting.
- Improved viewport handling and database-unavailable behaviour.

### Early build 0.70 · V/Line live tracking
<sub>2 May 2026</sub>

- Added V/Line live tracking and Gippsland service details, and improved Southern Cross departure boards, settings and route layers.

## April 2026

### Early build 0.68 · Cleaner live transit labels
<sub>29 April 2026</sub>

- Removed raw feed IDs from live transit labels so vehicle information is easier to read.

### Early build · Transit data-flow refactor
<sub>25 April 2026</sub>

- Refactored the transit-data flow and interface to make core map and service features easier to maintain.

### Early build · Map interface and stability
<sub>22 April 2026</sub>

- Refined the map interface and account roles, and fixed stability issues in rendering and update flows.

### Early build · Station departures and live metro tracking
<sub>20 April 2026</sub>

- Added station platform departure previews and improved the station panel alongside the journey planner.
- Improved live Metro train tracking and map interactions, added transport-mode filters and marker editing, and refined mobile map controls.

### Early build · The mobile live-transit app takes shape
<sub>19 April 2026</sub>

- Brought together the mobile journey planner, account access, live tracking, service alerts and transport-mode filters.

### Early build · Early train-feed and deployment work
<sub>14 April 2026</sub>

- Worked on initial train-route configuration and app deployment setup.

### Early build · TransitAlert project begins
<sub>13 April 2026</sub>

- Created the initial project and put the first app and deployment configuration in place.
