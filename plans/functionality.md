# functionality

## inspiration
- bit.ly
- grabify.link
- linktr.ee

## functions
- create `account`s (*account* user)  
> create `account`
- `short`en links (*account* user)  
shorten bigurl.com/long/path/tree/smh.asp -> abc.de/xxxxxx
> create `short` with a `long` and `account`
- redirect shortened links (*link* user)  
redirect requests to abc.de/xxxxxx -> bigurl.com/long/path/tree/smh.asp
> read `long` by `short`
- collect analytics on `short` click (*link* user)  
  - date/time
  - source ip
    - country
    - ISP
  - source hostname
  - user agent
  - referrer
> update `analytic` to `short`
- show all *account* user's links
> read `short` by `account`
- show `analytic`s by `short` link (*account* users)
  - lookup by *account*, display analytics in table
  - chart with clicks by time
  - pie charts of devices/browsers/versions
  - geographical map
> read `analytic` by `short`