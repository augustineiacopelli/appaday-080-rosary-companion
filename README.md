# Rosary Companion

App No. 080 in the [AppADay](https://augustineiacopelli.github.io/appaday/) project.

A guided rosary that walks you bead by bead through the whole devotion, from the opening Sign of the Cross and Apostles' Creed, through the Our Father, three Hail Marys, Glory Be, and Fatima Prayer, into five full decades, and out through the closing Hail Holy Queen, final prayer, and Sign of the Cross. The Fatima Prayer is prayed after the opening Glory Be and again after each decade. Each bead shows the prayer to say and, during the decades, the mystery to contemplate, its scripture, and its traditional fruit. You move forward one prayer at a time and the rosary fills as you go.

## Choosing the mysteries

On opening, the app selects the day's mysteries for you and lets you choose a different set if you wish. The weekdays follow the schedule Saint John Paul II set out in *Rosarium Virginis Mariae*, and Sundays shift with the liturgical season, so the Lord's Day always carries the mysteries the Church is keeping.

| Day | Mysteries |
| --- | --- |
| Monday | Joyful |
| Tuesday | Sorrowful |
| Wednesday | Glorious |
| Thursday | Luminous |
| Friday | Sorrowful |
| Saturday | Joyful |
| Sunday | Glorious, except Joyful in Advent and Christmastide and Sorrowful in Lent |

The seasonal boundaries are computed rather than guessed. Easter is found with the Computus algorithm, which in turn fixes Ash Wednesday and the whole of Lent, while the start of Advent and the Baptism of the Lord mark the edges of the Christmas season.

## Languages and reading aloud

The whole devotion is available in four languages: English, Latin, Spanish, and Italian. Choosing a language at the bottom of the home screen translates everything, the prayers, the mystery names, their scripture and fruit, the meditations, and the interface itself, into the traditional forms of that tongue. Your choice is remembered for next time, and a resumed rosary comes back in the language you were praying it in.

When the device offers a matching voice, a read-aloud toggle appears and a small speaker button sits in the corner of the prayer screen, speaking each prayer as you arrive on it. Speech uses the voices already built into the device, so it is offered only where one exists. English, Spanish, and Italian are supported this way; Latin is presented as text only, since devices do not carry a Latin voice. On a phone, reading aloud is most reliable in the browser itself. Some devices restrict speech when the app is launched from a home-screen icon, and in that case the toggle steps aside quietly and the rest of the app is unaffected.

With reading aloud switched on, an auto-advance option becomes available beside it. Once enabled, each prayer moves to the next on its own a short moment after it finishes being spoken, so a whole rosary can be prayed hands-free. It stops at the closing prayer and waits for you to end the rosary yourself, and it steps aside for any language without a voice, since there is nothing to advance from. Your language, read-aloud, and auto-advance choices are all remembered for next time.

## Using it

Tap Continue, press the right arrow or spacebar, or swipe forward to move to the next prayer. Go back the same way with the left arrow or a swipe. The filling bead ring shows your place at a glance, with the current bead lit in gold and the beads already prayed settled into blue. If you step away, your progress is saved, and the home screen offers to resume where you left off.

## Notes

A single self-contained file of vanilla HTML, CSS, and JavaScript, with no build step and no dependencies beyond Google Fonts. There is no account, no network call for the prayers, and no tracking. What is stored is your place in the current rosary and your language and voice preferences, kept in the browser's local storage. Reading aloud, when available, uses the device's own built-in speech and sends nothing anywhere. The prayer texts are the traditional forms in each of the four languages.

Part of AppADay by Augustine Iacopelli. Ship something every day. It compounds.
