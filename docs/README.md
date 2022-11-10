## yt-neuter
The main filter list  
[docs](./yt-neuter.md) | short link: `https://neuter.mchang.xyz/filter`

## nolive
Hide all Live/ Upcoming/ Premiere/ Streamed videos  
[docs](./filters/nolive.md) | short link: `https://neuter.mchang.xyz/filter/nolive`

## notrack
Block video tracking endpoints  
!! Will break history and recommendations !!  
[docs](./filters/notrack.md) | short link: `https://neuter.mchang.xyz/filter/notrack`

## noshorts
Block YouTube Shorts  
This works best alongside [BlockTube](https://github.com/amitbl/blocktube)'s shorts blocking feature, adds some filters on channel pages  
[docs](./filters/noshorts.md) | short link: `https://neuter.mchang.xyz/filter/noshorts`

## misc
Extremely aggressive misc filters  
[docs](./filters/misc.md) | short link: `https://neuter.mchang.xyz/filter/misc`

## reflow
filters to accompany the [reflow userscript](../userscripts/reflow.user.js)  
[docs](./filters/reflow.md) | short link: `https://neuter.mchang.xyz/filter/reflow`

## funkey
niche filters for funkey

## excluding filter
to add an exclusion for a filter, copy the offending filter to "Your Filters" and replace the `##` after youtube.com with `#@#`

example:
```diff
! block subscribe button
- youtube.com###subscribe-button
+ youtube.com#@##subscribe-button
```