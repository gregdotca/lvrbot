> **Archived:** lvrbot has been retired and is no longer maintained. It relies on Reddit's public API to read and reply to posts, and [Reddit is ending public API access](https://techcrunch.com/2026/09/30/reddit-is-killing-rss-feeds-ending-public-api-access-because-of-ai-bots/), so the bot will stop working. The code is left here for reference.

lvrbot - Low Volume Reply Bot (for Reddit)   
https://lvrbot.com  

[![ACR B0a](https://img.shields.io/badge/ACR-B0a-2140B5)](ACR.md)

**Installation**

1. Copy _lvrbot.ini-sample_ to _lvrbot.ini_.
2. Edit _lvrbot.ini_ and fill the fields in with your own details.
3. Copy _lvrbot.replies-sample_ to _lvrbot.replies_ and edit it to contain the replies you want to post to Reddit (a JSON list; the bot cycles through them in order).
4. Create an empty file called _lvrbot.posts_ (the bot records the posts it has replied to here).
5. Schedule _lvrbot.py_ to run at regular intervals.

**License**

MIT License

Copyright (c) 2024-2026 Greg Chetcuti <greg@chetcuti.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
