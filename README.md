ActiveMirroring
========

Next generation mirroring of dynamic websites. Full self updating copys of dynamic websites.

This repository is git flow enabled (default settings).

## Goal

Proxies simply pass traffic through to the original site. The do not have any data from the original site. If the original sites goes down, all proxies go as well. ActiveMirroring takes the thought of free data to the next level by decentralizing the data behind the original site.

ActiveMirroring is a way to replace the central server which holds all data with a p2p way of accessing data. ActiveMirroring tries to fill that hole with lots of proxies that have the database local but are in sync with all other proxies. If a new proxy joins it receives a copy of the actual database. After that all changes that happen on any proxy are shared with the other proxies.
This way the data is decentralized.

It is a work in progress.
It might take a long time to get the problem solved.
Do not get excited.

## Steps

Get a prototyp running that solves the basic problems of
  proxies need to know about each other for syncronisation
  syncing local changes with the other proxies
  uploading data to a proxy


After that things are getting interesting
  how to represent user accounts in a decentralized environment?
  how to detect bad proxies?
  how to deal with upload flodding?
  should each server have the full data or only a part?

  ... more stuff will come up

## Part of my PhD-Thesis

This code is part of my PhD-Thesis: A longterm storage strategy for the cultural heritage of the Federal Republic of Germany

It is an explorative sciences project which hopefully helps me gain some new ideas on how to tacle the problem of storing digital culture for future generations. I'm not responsible for forks or what YOU do with the code.

## License

Free Science for a better tomorow

Copyright (c) 2012 Samuel Goebert

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.