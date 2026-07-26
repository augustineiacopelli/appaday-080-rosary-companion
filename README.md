# Rosary Companion

App No. 080 in the [AppADay](https://augustineiacopelli.github.io/appaday/) project.

A guided rosary that walks you bead by bead through the whole devotion, from the opening Sign of the Cross and Apostles' Creed, through the Our Father, three Hail Marys, and Glory Be, into five full decades, and out through the closing Hail Holy Queen, final prayer, and Sign of the Cross. Each bead shows the prayer to say and, during the decades, the mystery to contemplate, its scripture, and its traditional fruit. You move forward one prayer at a time and the rosary fills as you go.

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

## Using it

Tap Continue, press the right arrow or spacebar, or swipe forward to move to the next prayer. Go back the same way with the left arrow or a swipe. The filling bead ring shows your place at a glance, with the current bead lit in gold and the beads already prayed settled into blue. If you step away, your progress is saved, and the home screen offers to resume where you left off.

## Notes

A single self-contained file of vanilla HTML, CSS, and JavaScript, with no build step and no dependencies beyond Google Fonts. There is no account, no network call for the prayers, and no tracking. The only thing stored is your place in the current rosary, kept in the browser's local storage so you can resume. The prayer texts are the traditional English forms.

Part of AppADay by Augustine Iacopelli. Ship something every day. It compounds.
