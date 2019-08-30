---
layout: text-page
title: "Status"
date:   2016-12-09 11:21:42

permalink: /status/
---

## Status

This page contains a list of Pebble's backend services, their status, and
the status of work towards a replacement. It will be updated as new
developments occur.

<style>
    .grayed {
        color: #888;
        font-size: 70%;
    }
    section table {
        border-collapse: collapse;
    }
    section table td {
        font-size: 90%;
        padding: .5rem .7rem;
        border: 1px solid #888;
        line-height: 1.4em;
        width: 43%;
    }
    section table td:first-child {
        font-size: 80%;
        min-width: 12rem;
            width: 12rem;
        max-width: 12rem;
        border-left: none;
        text-align: right;
    }
    section table td:last-child {
        border-right: none;
    }
    section table tr:last-child td {
        border-bottom: none;
    }
</style>

| url | description | replacement |
| --- | ----------- | ----------- |
| boot.<span class="grayed">getpebble.com</span> | Provides API endpoints to clients. | Functionality supplanted by Rebble Web Services. |
| auth.<span class="grayed">getpebble.com</span><br/>auth-api.<span class="grayed">getpebble.com</span> | Authorization endpoints. | Functionality supplanted by Rebble Web Services. |
| dev-portal.<span class="grayed">getpebble.com</span> | Developer portal. | Mirror available [here](https://developer.rebble.io/developer.pebble.com/index.html). |
| pb-collector.<span class="grayed">getpebble.com</span> | ??? | |
| lp.<span class="grayed">getpebble.com</span> | Language packs. | Functionality supplanted by Rebble Web Services. |
| apps.<span class="grayed">getpebble.com</span><br/>appstore-api.<span class="grayed">getpebble.com</span> | App Store. | Functionality supplanted by Rebble Web Services (apps.rebble.io). |
| help.<span class="grayed">getpebble.com</span><br/>appstore-api.<span class="grayed">getpebble.com</span> | Support pages. | Mirror available [here](http://pebble-help-legacy.rebble.io/help.getpebble.com/indexd41d.html). |
| cloudpebble.net | Cloud-based IDE. | CloudPebble is open source and may be continued as a community project. However, it is currently unmaintained. Unclear if it'll ever come back as a part of Rebble Web Services. |
| timeline-sync.<span class="grayed">getpebble.com</span><br/>timeline-api.<span class="grayed">getpebble.com</span> | Timeline servers. | Functionality supplanted by Rebble Web Services. |
| cohorts.<span class="grayed">getpebble.com</span> | ??? | |
| <em>various Nuance servers</em> | Dictation support. | Functionality supplanted by Rebble Web Services' paid subscription tier, which uses Google for dictation. |
| sms-api.<span class="grayed">getpebble.com</span> | Outgoing text messages for iOS. | Community replacement unlikely due to difficulty of dealing with cell carriers. |
| linked-accounts.<span class="grayed">getpebble.com</span> | Account linking? (very mysterious) |  |
| email-actions-api.<span class="grayed">getpebble.com</span> | Most likely gmail actions. | Community replacement possible but low-priority. |
| notif-app-icons.<span class="grayed">getpebble.com</span> | Probably provides icons for in-app notification permissions list. | Unimportant |
| health-write-api.<span class="grayed">getpebble.com</span> | Sends consenting users' health data to Pebble (for aggregate data and weekly emails) | Unimportant |
