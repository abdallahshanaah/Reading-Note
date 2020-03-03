# raed 13 
## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS
that chapter taking about the local srorage 
### DIVING IN
persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications
they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:
1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful
### A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5
 there was only Internet Explorer and **userData** allows web pages to store up to 64 KB of data per domain
 In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment, the feature is properly known as Local Shared Objects.
 and more history 
 ### INTRODUCING HTML5 STORAGE
 What I will refer to as “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” 
 ### USING HTML5 STORAGE
 HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. 
 and alot of more informaion about the storge and ways to useing it 
 