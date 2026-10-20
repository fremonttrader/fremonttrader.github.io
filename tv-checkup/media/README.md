# TV Checkup hosted sound samples

Prepared for the upcoming app version 1.0.16. The `v1/` directory contains exactly the 870 original `lab-*.mp4` files copied without re-encoding from TV Checkup. The app will play only selected samples over HTTPS using Roku media playback. It will require an internet connection for Sound Checks, and does not offer this bank as a permanent offline download.

`v1/inventory.json` lists each public filename, byte count, and SHA-256, plus the total. It contains no source code, account identifiers, credentials, or signing files. The original four non-lab clips remain bundled with the app; they are not copied here.

Keep `v1/` immutable once published. Changes to sample bytes require a new version directory and a matching app update. Do not replace files behind an existing release URL. This preparation does not by itself publish the files or release app version 1.0.16.

Copyright (c) 2026 TV Checkup authors. All rights reserved. These original diagnostic samples are supplied for playback by TV Checkup; public hosting does not grant a general redistribution license.
