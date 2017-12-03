---
layout: page
date: 2017-12-03 T19:00:00
title: A Tight-Knit Group
author: Geoffrey Huntley
github_username: ghuntley
authorurl: http://twitter.com/geoffreyhuntley
gravatar: 23d4d2451f74764e095f15a739b68a4e
---

Maybe I've been attending the wrong meetups here in Sydney but I can't scratch the feeling that there's something wrong with the standard format. A couple presentations, free booze and free food. Ugh. It's all consumption driven with very little attendee participation. Over the last couple years I've dramatically scaled back my attendance to such meetups because there are better sources to obtain knowledge in the world of unlimited opporunities that is open-source because
the standard pace is for chumps, if you’re more driven than “just anyone” - [you can do so much more than anyone expects](https://sivers.org/kimo).

<!--excerpt-->

So few professions have the opportunity that we do - like, if I want to be an expert in Civil Engineering, I can't just like build a bridge in my spare time. But if I want to understand [functional reactive programming](https://reactiveui.net/) at a deeper level, I can literally hang out with the folks that invented the techniques, with zero hiring bar to entry. Open-source is such a massive opportunity for folks in tech to improve their careers, it makes me so sad that it's so criminally underutilized.

Our events will center around being active participants in open-source, learning via [deliberate spaced repetition](https://knowledgeplus.nejm.org/blog/spaced-repetition-the-most-effective-way-to-learn/), pairing and participating in documentation sprints and software sprints. There will be minimal presentations as there's other meetups in Sydney for that type of stuff. Bring your laptop, food and drinks and we will supply high speed internet, opportunities for learning and just good vibes.

If you don't already know Haskell then this is the perfect opportunity as for the first couple of months [on a weekly basis] we will be working through [the haskell book](http://haskellbook.com/). If you already know Haskell, you are also welcome to participate and help others get up to speed.

> "If you want to go fast, go alone. If you want to go far, go together." - African Proverb

The goal is to build a community of Haskell developers in the Sydney area that freely shares knowledge and develops a global reputation for shipping great things whilst remaining inclusive to beginners and never elitist language jerks.

# Why Haskell?
In most programming languages the world as we know it _lives and dies_ in the confines of the opening and closing brace of the `main` function, which is the entry point to our application. Everything that happens in our program, the universe our program interacts with, happens between those two braces. By its very definition, our program returns an _exit code_, specifying whether it succeeded or not, and everything else happens as a side-effect.


```csharp
public static void main(String[] args)
{
    ...
}
```

The implication, that all the work is done between the two braces of the `main` method, is what drives *everything* we know about this model — every design pattern, every practice, every discipline, every tool, library, or framework — were created to let us manage this model of our world that exists between those two braces. We have decades of knowledge in how to do this properly in almost any language.

Earlier this year, by chance I stumbled into a pub with [Tony Morris](https://twitter.com/dibblego) who over a few beers, introduced me to Haskell and [how to how to implement pure-functional I/O in C#.](https://gist.github.com/tonymorris/7817335)

```hs
main :: IO () -- reads as 'main, having the return type of IO ()'
```

What I saw being explained is that Haskell doesn’t actually do any work inside of its `main` function. Instead, the program “describes” in a declarative way what is going to have happen when your program executes, and this “description” will be returned into the Haskell runtime, and exactly what was described will happen - with no possible _side-effects_ or surprises. It flips the entire idea of execution on its head - the work, the actual execution of effects is not being done _inside_ of `main` - it’s done on the _outside_!

Intriguing huh?

---

Links:

- This post contains sections from [becoming foolish](https://hmemcpy.com/2017/10/becoming-foolish/) by Igal Tabachnik.
- [Meetup event page](http://www.meetup.com/SydneyHaskell/)
- [Readify](https://join.readify.net/?source=StaffReferral&campaign=geoffrey.huntley) (Our event venue host)
- [When standing as a group of people, always leave room for 1 person to join your group.](
http://ericholscher.com/blog/2017/aug/2/pacman-rule-conferences/)
- [When referring to a group of people, aim to use gender-neutral terms like “team”, “folks”, “everyone”.](https://modelviewculture.com/pieces/gendered-language-feature-or-bug-in-software-documentation)
- [Spaced repetition is the most effective way to learn.](https://knowledgeplus.nejm.org/blog/spaced-repetition-the-most-effective-way-to-learn/)
- [The standard pace is for chumps. There’s no speed limit. (The lessons that changed my life)](https://sivers.org/kimo)
- [Always be shipping. One of the best secrets to success is simply finishing what you started.](https://matthewforzan.com.au/productivity/always-be-shipping/)
