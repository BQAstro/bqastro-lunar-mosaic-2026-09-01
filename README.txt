BQAstro Lunar Globe — Version 4.0.7

GRID LABELS + AUTOMATIC UPDATE FIX
- Added labels to every displayed latitude line (15° increments).
- Added labels to every displayed longitude line (15° increments).
- Equator is explicitly labelled “Equator · 0°”.
- Prime meridian is explicitly labelled “Prime Meridian · 0°”.
- Coordinate labels rotate and zoom with the lunar globe and are controlled by the Grid toggle.
- N / S / E / W markers remain included.

CACHE / UPDATE ARCHITECTURE
- Website navigation/index.html is now network-first.
- The large lunar texture and static assets remain cache-first for speed/offline use.
- New service workers activate immediately.
- Old BQAstro version caches are automatically deleted.
- Existing visitors should receive future website updates normally without manually clearing browser data.
