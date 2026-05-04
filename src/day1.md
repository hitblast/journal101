# Day 1: `init`

12:17 PM

Trying to get my mind's hold off of YouTube, because when I think about it, I know consciously I don't crave these things, but the whole habit has turned into a repeating cycle of actions which I want to stop. Writing doesn't help it either - as our minds tend to incentivize on it as well (letting us think that we've already 'done' whatever we were supposed to do, and relaxes).

That's one free point you got right at the start; maybe quit YouTube before it crushes the current daily habits that make you.

Secondly, I really crave tea right now.

I have been thinking since last night, that if I write in this series continuously, what will I write about in [my own blog?](https://hitblast.github.io/blog) It's kind of confusing to me that I'll have to maintain two literary folders on my computer from now on.

---

Well, I've done a lot of talk since the intro so, let's get into the real stuff.

### so uh, how to read this book? (mandatory)

By now you have probably realized that I have divided this book into "days" - day 0, just like many other first indices of many programming languages, being the initial one. I will attempt to blend in everything I do, with stuff you care about, and this book will by no means be a core CS book - it'll more likely turn out to be a mind calibrator on steroids.

Part of this calibration will be done by me sharing how *I learn stuff everyday*, say yesterday, I was talking with a friend back at [QuantumLauncher's](https://github.com/Mrmayman/quantumlauncher) Discord server on how `BytesMut` could potentially be used in an unsafe way for performance, essentially throwing the compiler with a "promise" rather than guaranteed safety (even though I ended up merging his PR which is relatively safer). I'll repeatedly write about these events, and your job is to interpret these as literary constants for you to churn out some knowledge from.

Another part of this calibration will be done by *me sharing tools*. For example, I really used to like [mise](https://mise.jdx.dev), but since it doesn't really *control* Rust like [uv](https://github.com/astral-sh/uv) controls Python, it soon became a red flag for me and I reverted back to classic `rustup`. Now you might not even know what these tools even are, so if your stack matches with me even a teeny-tiny bit, then your job is to click on these hyperlinks I'm dropping by, and follow these principles:

- Look at the repo.
- Think for a second *"why I'd want to integrate it into my workflow?*
- Actually *try integrating it into your workflow.*
- If it works, **amaze amaze amaze**.
- If it doesn't work, find out why it doesn't and never let your mind roam around it until a certain period of time has passed, then try again.
- If it totally doesn't work, skip it and follow the next tool.
- Do not use tools which eat up your computer's performance. RAM's pretty short nowadays so let's go back to the old days of hyper-optimizing software and not using some Electron / React Native junk.
- Use small tools; tools which do one thing and do it nicely.
- This applies to an infinite number of tools you may find when you hit that "Explore" button on GitHub/GitLab/Codeberg, not just the ones I write here. *Create a conscious habit of clicking on that button.*

Then, I'll also *share learning material* (I really want to drop one right now but I think I'll save that for later). This one is pretty simple to follow along with; you just need to look and see *whether or not the material is compatible with your learning style. If it is, follow it.*

Finally, I'd like to share something. When I usually deal with rumination in my own head, I often times find my brain actually noticing that the rumination is happening, and noticing isn't a problem. If you are feeling like all of this is already hitting you like a bus at 100mph, it's completely okay. If you have a sheer want for the craze of making and using things you love, you'll actually *get over this noticing once it turns into a habit you enjoy*. And, *building things you love, or building a habit, takes time.*

I hope it'll all make sense soon.

---

Anyways, got my tea, thanks to grandma. I just remembered that I had to create the Discord server for this book. Hmm, maybe I'll do it pretty soon (procrastinating, legitimately). For now, I'm thinking about creating a project which I noted down last night onto my Notes app (currently writing this on Zed since the Vim mode is pretty handy when writing at high speeds; I really hate the mouse). Tea gives this sort of jittery energy, as I heard from some dude on the Internet, to ADHD people, which almost feels like you're snapping your consciousness back from thinking about a plethora of events/things into the current moment.

What could I possibly share with you on day 1? I mean, we haven't even gotten to know each other nicely at this point, sharing feels like a dream. Hmm...

Maybe read through me yapping about whatever programming languages I prefer.

I'll drop a list so its easy to follow through: (in priority order)

- C (nothing better than this one)
- C++ / Rust (haven't used C++ so you can choose; C++'s faster while Rust's babysitting you with identical speeds)
- Python (not for performance, for times when you're lazy to complete a *client's project*)
- Flutter (for GUIs, or Graphical User Interfaces, or for the apps you use daily; it's slightly heavy though)
- JavaScript (please don't make this your daily-driver, probably)
- Bash (for scripting, well this is not really a programming language so)
- Gleam (I'll learn this one with you)

You might've realized already that I've put C so high up the ladder that it almost invalidates everything that a lot of "20 LPA SDE/SWE gurus" tell you about, since just like a friend of mine once said:

> "I'll probably have to do React slop or Java slop for a living."

I guess C gives you the fundamentals, and the performance, at the cost of having zero abstractions for making stuff. But, is it really a cost or a *benefit* if you're having zero abstractions you can use like a deck of +4's when playing UNO? You'll learn things at such a fundamental level that it almost feels like cheating when you walk into a room and you see Python people argue about when to use a `TypedDict` vs when to dynamically create a dictionary, because Python isn't even good at performance in the first place [althrough latest improvements in removing the GIL (Global Interpreter Lock) are pretty nice, I won't argue with that].

Things will just feel overcomplicated in the outside world when you're writing apps that run 10x faster with just the standard library, and probably [raylib](https://www.raylib.com), or whatever tiny abstractions you choose. You'll probably live a much happier life than deciding which hydration method to use for state management on your simple ToDo-list app.

C++ will probably be either the nail in the coffin for you, or the best decision of your life. Same goes for Rust, although the chances of going insane are much higher (due to the insanely strict borrow-checker, lifetimes and generics nuances you'll stumble across). You'll also find a lot of helpful resources just lying around on the Internet which will probably either make you a systems programmer, or just another Java dev who does Spring Boot for a living because why write C++ when you already have an ecosystem of packages (which show up like a tree considering com/somedev/somerandomcalculatorclassinjava) and a life.

Python will probably be a much more place to be in once *after* you've done and experienced some of the things written above, otherwise it could also become the nail in the coffin for you because you won't know what a stack or a heap even is. It's entirely garbage-collected so you trade performance for the beautiful plain-English-like syntax. You won't have to deal with serialization and deserialization of data as most of these stuffs already have a package lying around in PyPI somewhere, and you can safely `uv add mybelovedpackage` until you realize that it isn't even for your Python version; things probably got invalidated a long time ago on 3.9 whereas you're using 3.14 right now. Or, maybe you didn't suffer from this; congratulations, the fear of documentation will slowly engulf you (although I'm not quite sure if you'd even read documentation without Python as you could just ask ChatGPT while sacrificing your attention span).

Flutter will be the place you *might* probably enjoy, talk the most in, or even make some pretty cool stuff out of, as long as you're enjoying the 30MB Skia build that comes baked into it. Your apps will never be smaller than that.

Bash is good; approved.

**phew*

Too much for the start of day 1 I guess, will probably write another hour.

---

3:52 PM

Boredom will probably be your biggest weapon.

Two days into stopping YouTube altogether and I'm feeling like lobotomy might be the best way to stop this overflow of ideas, but I don't *want it to stop.* People often struggle with finding ideas on what to make, or what to build, or what to contribute on. I guess even though a lot of this sheer lack of ideas comes from a lack of actual knowledge referenced by those ideas, we are often times a lot more stimulated now.

Knowing *when to stop stimulating yourself*, and *actually stopping following that* should be key. That's it. I had to put it here - and I've just put it.
