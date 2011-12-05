SharpPodder
===========

Podcast downloader and API

TODO
----

* Links have a Download method. To do that we need a reference to the subscription and it is dirty and ugly to recreate references after materialization (and there are other uglier details related).
* MyIsoDateTimeConverter is a quick copy/paste from the first result on Google to fix an issue deserializing json ISO dates with Mono. It should be checked and clean.
* Global configuration file.
* Way to determine defaults values (and objects like default FeedReader) without save it in each single subscription file.
* Write a new FeedReader from zero to avoid issues with .Net client (Amnesty International Feed?) and possible issues in custom Mono sources adaptation.
* Clean json files to avoid write default or redundant values like TockTo field when the file is not locked.
* Unit Tests
