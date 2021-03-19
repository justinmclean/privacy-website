---
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
#   http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
# KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.

layout: default
---

# Committers FAQ

## Project Websites

### Can I use Google Analytics?

The Apache Software Foundation discourages the use of Google Analytics.

Google Analytics can only be used if:

 - the users IP addressed would be anonymized before transmitting data
 - the user approved the use of Google Analytics before it is loaded

Court decision around Google Analytics has changed various times
in the past years and made its use uncertain.

### Can I use Google Fonts?

You can use Google Fonts, but please host the fonts on ASF servers.

ASF projects don't have any reason to load Google Fonts from
Google servers. Even [performance wise](https://wicki.io/posts/2020-11-goodbye-google-fonts/)
there is no reason to use Google CDNs.

To prevent any data from being transmitted to a third party, please
[download the fonts and host them with your project website](https://github.com/google/fonts#self-host-fonts-available-from-google-fonts).

### Can I embed Google Maps?

Yes, you can use Google Maps, but they should only be activated after the user
actively wants to use them. This can be done by showing a placeholder first
and load the map when the user clicks on it. Please make it transparent
that users will load a Google Map with their click.

### Can I embed videos (from YouTube, Vimeo, etc.)?

Yes, you can embed videos on the website, but they should be loaded
only after the user actively wants them to load. This can be done 
by showing a placeholder first and load the video, when the user
clicks on the placeholder. Please make it transparent that users
will load video embeds from a third party.

If you don't want placeholders, please consider self-hosted videos
and using an open source player like [Plyr on GitHub](https://github.com/sampotts/plyr).

### Can I embed social plugins (for example, Like-Buttons)?

Yes, but you can only load them when users actively want them
to load. There are multiple open source solutions helping with
that problem, like [Shariff on GitHub](https://github.com/heiseonline/shariff).

### Can we have an official Facebook fan page?

No. 

You cannot run an official ASF Facebook page.

The german [Datenschutzkonferenz decided on 2019-04-01](https://www.datenschutzkonferenz-online.de/media/dskb/20190405_positionierung_facebook_fanpages.pdf) that you cannot fulfil [Art. 5 §2](https://gdpr-info.eu/art-5-gdpr/). Also, it is not compatible with Art. 26. 

### Can I add a Facebook/Twitter etc., custom pixel for creating a custom audience?

No, not without approval from your user.
