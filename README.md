# sitesearch
Perform google site search on the URLs in a single bookmark folder.

## Background 
So bookmarks get organized on your browser toolbar into folders, right? Right. It occurred to me that it would be very useful to do a combined site-search on only the sites in a particular folder. For example, I have a "pentest reference" folder full of useful reference sites, with none of the blogger garbage that's all over the internet. If I search the internet for "nc.exe" I find a bunch of nonsense, but if I constrain it to just these sites, I get what I'm looking for, immediately, every time.

But you can't search a list of sites easily. You have to build a search string something like "site:foo OR site:bar OR...". So here's a tiny page to do that for you. If I were smarter I'd write it in pure javascript so it could work as a bookmarklet or search provider or browser addon or something. It's just not worth that kind of effort at this point. Maybe someday.

## Usage:

- Right click - copy any bookmark folder (or other URL list) and paste it into the 'sites' box. 
- Then put your search term in the query box.
- Then click search to search only those sites.
