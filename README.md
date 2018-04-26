# Go for art.

*By Matthew Juran (github.com/pciet), April 26th 2018, Soldiers Grove, WI. All Rights Reserved.*

Walking down a European street is a start to art, but so is driving interstate loops on western roads in the U.S.A. where science fiction is just a genre.

At these roads you’ll find forests and deserts on big rocks and flats, you’ll find streams and rivers, gas stations, fast food, brown park signs, and anxious “can I wait 30 miles” blue signs for clean plus uniquely scenic rest stops with bathrooms and free water for personal use. Watch for elk or deer if you go at night and have an emergency kit with lots of the free water; the cell network doesn’t reach many of these places and the weather is deadly. Take a nap away from that inside land in Big Sur, Santa Cruz, or Pacifica with the window down.

![Monterey Bay, CA, 2013](https://github.com/pciet/goforart/blob/master/monterey_2013.jpg "Monterey Bay, CA, 2013")

From the Pacific Ocean over or around the Santa Cruz Mountains into Silicon Valley, where San Jose, Santa Clara, Cupertino, Sunnyvale, Mountain View, Palo Alto, and more municipalities are littered with free religion places of worship known as “tech offices”, you’ll find big company lettering on the buildings are like celebrities for the communicate and compute industries. Shared across this land is the programming art where words are made to coordinate electricity in massive switch networks that span the size of a coin to the size of the Earth.

Go is an English programming language project developed independent of geography, but the source of Google in San Francisco Bay Area culture (include Oakland) might be interesting to know. To me the California mountain isolation, U.S.A. inclusion, world class ocean access, and public roads to anywhere America are influences, but Go does have code from at least New York, Europe, and Australia.

![Oakland and San Francisco, CA, 1934](https://github.com/pciet/goforart/blob/master/sf_oakland_1934.jpg "Oakland and San Francisco, CA, 1934")

Interestingly Go is written in Go. You may know that computation electric coordination is done on the transistor processor circuit where sequences of switch configurations make ordered lists of instructions to do math or share numbers. Instead of making ‘0’ and ‘1’ sequences while studying processor documentation Go programmers rely on Go to change easier to understand written words into the sequences. A tradition has been built this way around the words if, for, function, type, and library, and Go is only a continuation of this tradition.

Google has given most people a license to use Go, and Google employees coordinate a public effort for Go in English on the Internet.

* Code of Conduct: https://golang.org/conduct
* Issues: github.com/golang/go/issues
* Use Discussion: groups.google.com/forum/#!forum/golang-nuts
* Development: groups.google.com/forum/#!forum/golang-dev

The ideas of structuring if, for, functions, types, and libraries is an art that I think many people might like. What Go brings is less wading through mud than C languages, Java languages, or scripting languages.

I’ve been writing Go since 2014, and I have participated daily in the written community since late 2017. Recently the golang-nuts mailing list was asked about beginner tips and here’s what I wrote in response:

>Hi Teja,
>
>I found Effective Go to be generally helpful: https://golang.org/doc/effective_go.html
>
>Here’s my best example: https://github.com/pciet/wichess
>
>My golang-nuts code review points:
>
>- don’t overuse interface (consider closures and function types/fields)
>- don’t overuse packages, make more files in the same package first
>- focus on the godoc presentation
>- consider struct embedding
>- slices are more efficient and readable than maps for some kinds of unordered sets
>- a struct of pointers is similar to a pointer to a struct
>- profile before making any choice away from easy code
>
>For newbies:
>
>- Writing computer programs with if, for, types, functions, and libraries is an art that many people might like. What Go brings is less wading through mud than C, Java, and scripting languages.
>- Pointers are a hard part of Go and you should learn them well enough to not have any pointer questions. Map and interface vars are pointers, and a slice has a pointer to the array (a slice is a struct).
>- stackoverflow.com, golang.org, golang-nuts, and Dave Cheney's blog are good resources among others.
>
>Matt

Here I’ll focus on the art. I’m going to talk about religion first, so if you can be offended by this then please stop reading here.

Religion seems to be avoidable, but I don’t think it is. There will always be the question of “how do you make choices?” and completely avoiding the issue is a religious choice in my mind. As a U.S.A. citizen I’ve agreed to the Constitution, which has this sentence (admittedly hard to read on the original): 

>“Congress shall make no law respecting an establishment of religion, or prohibiting the free exercise thereof; or abridging the freedom of speech, or of the press; or the right of the people peaceably to assemble, and to petition the Government for a redress of grievances.”

I think this says “freedom of religion” which is the best religion I’ve been able to find. I respect your choices as long as you don’t infringe my right to do so. I believe the government is sovereign over the corporation. Given this first amendment law that’s been in place for longer than any of us I think we have the responsibility of maintaining freedom of religion; we as individuals make up Congress, and as a nation the U.S.A. should interact with nations built on freedom of religion around the world. We are the government.

The religious choices made in programming can be damaging or deadly. If we’re not making art then our profession possibly causes unwanted effects on others, and we have to respect the right to religion. Consider surveillance applications or war applications like drone guidance, tank coordination, or a remote nuclear missile lock. Just because an individual doesn’t believe in freedom of religion doesn’t make their religion invalid, but we have a law that says they’re wrong where the U.S.A. Constitution applies.

If you are a software professional working on mining, transportation, communication, exploration, farming, or anything else, you have a responsibility to your clients that goes beyond what programming language you pick. You should know how to make programs that don’t break and you shouldn’t make some programs. We know from World War II that “do what you’re told” doesn’t work, and these are three important points I pulled from writings about the Vietnam War:

* be careful which doors you open
* listen to the right people
* exhaust every option

Art is a place where we share ideas, and Go is perfectly suited for art. “Art” is my answer to “why do we keep making these things better when we already know how to farm and get those good everywhere we care about?”. Go to me is about art and getting to art, because once you’re fed and watered and have the friends you want and don’t have to work then you’re going to want art to be around. Check out this painting of war ships:

![Dutch Ships in a Calm, Willem van de Velde the Younger, 1665](https://github.com/pciet/goforart/blob/master/younger_1665.jpg "Dutch Ships in a Calm, Willem van de Velde the Younger, 1665")

And look at this photograph:

![Apollo 17, December 1972](https://github.com/pciet/goforart/blob/master/apollo17_1972.jpg "Apollo 17, December 1972")

And see how much fun these painters are having:

![Hipp hipp hurra! Konstnärsfest på Skagen-Peder Severin Krøyer colony of painters, 1888](https://github.com/pciet/goforart/blob/master/krøyer_1888.jpg "Hipp hipp hurra! Konstnärsfest på Skagen-Peder Severin Krøyer colony of painters, 1888")

Here are some of the art ideas I’ve had that could use Go.

An Internet collectible chess piece game. This has been a focus of mine for a few years (see wichess). In the world of Internet games I’ve had a few other ideas including a turn-based American football grid game with fantasy football elements, and a grid-based social media game that generates ray-traced scenes (like in Myst) but where you can talk to other people with microphones and where gardening is a significant feature. Go would be useful in microservice server implementations and I hoped to share them in a way where the game can be setup on a network independent of any Internet service.

A linking music website. On bandcamp.com as an artist you can recommend up to three albums and you can arbitrarily tag your work, but I like the idea of a stronger genre system with the ability to link your work to that of others to build realistic genre maps.

Local networks that share information. For example, if you play chess on one local network then you are able to take your collectible pieces to another local network in a fun and fair way. I had the idea of a currency that works on these, and this would be another way to share art that can’t possibly be modified by other people.

Matt

(I’m looking for full-time professional programming work)
