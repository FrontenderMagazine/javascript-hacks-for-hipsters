[ Javascript Hacks for Hipsters][1] 

Javascript is so much fun, except when it’s not.

There’s always the fear of runtime errors that keeps us thinking all the time
while writing code. It makes us better coders - we have no other option than to 
visualize every line of code as if it’s running as we write it.

That’s why it’s so important to have tidy code. Small code. Pretty code.
Code you just fall in love with. Otherwise, Javascript will scare you away.

I gathered some fun snippets I enjoy using instead of boring code that takes
too much space. Some makes the code shorter, cleaner and more readable. Other 
are just plain hacks for debugging.

I learned all of this from open source code (until node.js all javascript code
was open source, wasn’t it?), but I’ll write them here is if I invented them.

**Hipster Hack #1 - Method calling**

I really hate if/else blocks and this is quite a useful trick to call the right
function based on a boolean value.

[][2]<https://gist.github.com/7632148.js?file=jshipster_method> 

**Hipster Hack #2 - String joins**

It’s a known fact that strings like other strings. Sooner or later you’d
like to concatenate two or more of them. I don’t really like +ing them together,
so*join*() comes to the rescue.

[][3]<https://gist.github.com/7632148.js?file=jshipster_join> 

**Hipster Hack #3 - Default Operator ||**

Javascript is all about not knowing what an object holds. Sometime you get it
as a function argument, other times you might read it from the network or a 
configuration file. Either way, you can use the || operator to use the second 
argument if the first is falsy.

[][4][https://gist.github.com/7632148.js?file=jshipster\_or\_or][4] 

**Hipster Hack #4 - Guard Operator &&**

Similar to the *Default Operator*, this one is super useful. It eliminates
almost all*IF* calls and makes for a nicer code.

[][5][https://gist.github.com/7632148.js?file=jshipster\_and\_and][5] 

**Hipster Hack #5 - XXX Operator**

This one is totally copyrighted and also SFW. Whenever I write some code, but
then have to consult the web, or a different part of the code, I add an*xxx*
line to the code. This makes the code break so I can get back to the specific 
place and fix it later. Much easier to search for it (xxx usually never appears
) and you don’t have to think about a TODO comment.

[][6]<https://gist.github.com/7632148.js?file=jshipster_xxx> 

**Hipster Hack #6 - Timing**

Ever wonder what’s faster: Looping with an i++ or looping with an i— ?
Yeah, me neither. For those who does, you can use the console’s timing methods 
to test for slow loops or any other event-loop blocking code.

[][7]<https://gist.github.com/7632148.js?file=jshipster_timing> 

**Hipster Hack #7 - Debugging**

I learned this one from a Java developer. I have absolutely no idea how he knew
about it and I didn’t, but I’ve been using it ever since. Just drop a*debugger*

[][8]<https://gist.github.com/7632148.js?file=jshipster_debugger.js> 

**Hipster Hack #8 - Old School **Debugging****

I’ve always been a “printf debugger” more than a line-by-line-in-a-
debugger kind of developer. If you’re like me, you’ll want to “export” some 
private vars into the global scope in order to examine them from time to time. 
Don’t forget to remove these before committing/pushing-to-production.

[][9]
[https://gist.github.com/7632148.js?file=jshipster\_globals\_for_debugging][9]

**Hipster Hack #9 - Ultra Light Templates**

Are you still concatenating strings using the + operator? Here’s a better way
to combine a sentence with your data. It’s called templating and here’s a mini 
framework in 2.5 lines of code.

[][10]<https://gist.github.com/7632148.js?file=jshipster_templates> 

**Already knew them all?**

Even the copyrighted XXX Operator invented by me?! You’re a true hipster
hacker, let’s talk more on[twitter][11].

Sign up to receive my new blog posts by email. I'm going to write about
startups, building apps and coding about once or twice a month.

 [1]: http://berzniz.com/post/68001735765/javascript-hacks-for-hipsters
 [2]: https://gist.github.com/7632148.js?file=jshipster_method
 [3]: https://gist.github.com/7632148.js?file=jshipster_join
 [4]: https://gist.github.com/7632148.js?file=jshipster_or_or
 [5]: https://gist.github.com/7632148.js?file=jshipster_and_and
 [6]: https://gist.github.com/7632148.js?file=jshipster_xxx
 [7]: https://gist.github.com/7632148.js?file=jshipster_timing
 [8]: https://gist.github.com/7632148.js?file=jshipster_debugger.js
 [9]: https://gist.github.com/7632148.js?file=jshipster_globals_for_debugging
 [10]: https://gist.github.com/7632148.js?file=jshipster_templates
 [11]: http://www.twitter.com/ketacode