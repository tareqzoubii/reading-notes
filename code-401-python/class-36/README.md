# Read 36
### Data Fetching

#### What is SWR?
>SWR stands for stale-while-revalidate, a HTTP cache invalidation strategy popularized by HTTP RFC 5861

#### Data fetching steps:
>Returns cached data first (stale)

>Sends the fetch request (revalidate)

>Returns the up-to-date data


#### Why use SWR?
>1. Built-in Cache 
>2. Auto Revalidation
>3. Pagination

#### Installation SWR steps:
> From terminal ----> npm install swr

> import useSWR from 'swr'