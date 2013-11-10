Apple Inventory Monitor
=============

Apple inventory monitoring sites have received cease-and-desists.  In my experience, they also cache too aggressively.  Here is a customizable open-source solution.

I made this script as a way to gift a new iPhone 5S for a friend.  Although iPhones were in very high demand, I got hers in less than a day.

With this script, you can see shipments come in realtime.  It's scary how quickly the phones get snapped up.

## Setup

`npm install` to install dependencies.

## Usage

`node apple.js zipcode [phone_number]`

eg.

`node apple.js 94043` to monitor stores within driving distance from Mountain View.

`watch -n 30 "node apple.js 94043"` to check every 30 seconds.

## MIT License

Copyright (c) 2013 Ian Webster (ianww.com)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
