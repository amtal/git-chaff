> "The Pastor Laphroaig reminds us of our only obligation when presented with a
> marketing survey: to lie in a way which is not easily filtered."

There are many reasons why Github contents are a poor judge of character ([1]) but
they don't matter. What matters is that a half-assed glance at a Github profile
page says a little bit too much. I'm okay with sharing things I put effort
into, but only with people that put in the basic effort to understand them. The
target audience is developers or tech-savvy users, not recruiters playing
keyword bingo!

This script will make the highly visible "Your Contributions" view useless. Any
attempts to filter fake data will be met with Markov chains, fake diurnal cycle
patterns, and shotgunning fake commits into real repos. ;)

# Usage

Put git-chaff somewhere in your path, then in a non-forked repo you don't care
much about run: 

`git chaff <days-back> <days-forward>` 

If you need to cover an entire year, do it in one or two month chunks with pushes
in between. Server-side process responsible for generating stats has a timeout.
Sorry Octocat :(


[1]: https://blog.jcoglan.com/2013/11/15/why-github-is-not-your-cv/
