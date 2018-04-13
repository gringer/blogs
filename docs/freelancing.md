---
title: "So You Want to Be a Freelance Bioinformatician"
author: "David Eccles"
date: "13 April 2018"
toc: true
output: html_document
---

# So You Want to Be a Freelance Bioinformatician

Every now and then, I get asked for advice on being a freelance
bioinformatician: someone working (at least part time) in a
sole-trader business as a bioinformatician. To get the most important
point across first, I don't do it for the money (as is the case with
many other freelance jobs). More explicitly, the freelance part of my
work has almost never been the entirety of my work, and when it has
I've sometimes had to go for a few months without a source of
income. It's very easy to get underworked (or, for that matter,
overworked), and a sizeable financial buffer has been important in
keeping me and my family up and running.

## What is Bioinformatics

I see bioinformatics as the process, or art, of converting research
outputs into something that can be better understood by other
researchers. Research outputs that typically, but not always, involve
very large datasets.  One of my favourite explanations of
bioinformatics is that it’s a bit like surfing: chasing waves of
information from an ocean of data, and presenting them in an
interesting way before they reach the shore of public knowledge.

I feel like I need to learn something new for every bioinformatics
project that I take part in. This seems so intrinsic to
bioinformatics, that I'm tempted to argue that a project only includes
bioinformatics if it's breaking new ground somewhere (this is almost
always the case with research anyway). I can't help but parallel this
with the somewhat snobbish definition of artificial intelligence that
we were told during computer science lectures: if lay people can
understand it, it's not artificial intelligence.

## The Beginning

I occasionally get asked about when it all started. I summarise the
beginning of my research side in a presentation about my life as a
Māori genetics researcher
[here](https://www.researchgate.net/publication/308026084_The_Maori_Difference_Exploring_the_life_of_a_Maori_genetics_researcher)
[[talk script](https://www.researchgate.net/publication/308026087_Talk_script_for_presentation_2016-Sep-09)]. Some
of the text in this post is pulled from that presentation.

But in truth my desire to look at things, see how they work, and
change them started in my childhood.

### A BASIC Start

Our family got our first computer when I was 8 years old. For those
that care, it was a 286 XT, it had a VGA screen, a 20MB hard drive and
a “turbo” button. The hard drive meant that we could store different
applications on the computer. Games as well.

One thing that my dad realised fairly early on was that the user
interface of the system was a bit lacking. It was DOS, completely
command-line driven, with a mechanical process of changing into a
directory and typing in the command required to run the program. So,
he created a BASIC program to display a menu of games and
applications, and complemented it with batch files to run the
applications.

Over time, we got more games, and the menu system started to need a
bit of fixing. Dad showed me the source code for the menu program and
pointed out the lines that needed changing. Without having any
understanding of program code at all, I was able to hack the program
and make user interface changes. It was wonderful! I played quite a
few games in my childhood on the 286, including Railroad Tycoon,
Carrier Command, Populous, Jack Nicklaus Golf and Hero's Quest: So You
Want to Be a Hero.

Our computer was upgraded to a 386, which brought with it the
possibility of playing games with better graphics and larger worlds:
Civilisation, Monkey Island 2, Space Quest 5 (among others). I learnt
to suffer through long loading screens and slow gameplay so that I
could just bearably play, Doom, Master of Magic, and One Must Fall. I
was also introduced to a memory sniffing program called Game Wizard
that allowed me to cheat when playing computer games.

### Pascal's Triangle

When I was about 14, an experimental programming course was introduced
at Wellington High School. We started off learning a language called
Logo, and wrote programs that controlled a little triangle as it moved
across the screen. Later on in the course, we were introduced to the
Pascal programming language. I discovered that the compiler we were
using had comprehensive help files with example code, and my interest
in programming exploded.

In my break time at school, I flitted between BASIC and Pascal on
various computers, with my main interest being in writing
screensaver-like programs. I also did a bit of tinkering with save
game files, and messing around with different binary file formats. I
wrote some visualisation code to pull out world maps from Civilisation
save game files, and discovered the encryption format of the Warheads
save game files (a simple `255-x` operation), allowing me to create my
own weapon editor for that game. I loved tinkering with things, and
programming opened up a whole new world of possibilities in that
regard.

### The Mathematics of Genetics

In the meantime, I was studying maths and biology. For full
disclosure, my 7th form [year 13] subjects were Biology, Chemistry,
Physics, Calculus, Japanese, and Photography.

I was introduced to genetics via Mendel and punnet squares. I learnt
subsequently at a conference that Mendel is one of the worst ways to
introduce genetics, but it worked well for me because maths was one of
my favourite subjects, and I found a comfortable familiarity in the
punnet squares and binomial frequencies.

My biology grades were low; I was a just-passing C student. I didn't
have a head for rote learning, couldn't write good essays, and my mind
is easily twisted into knots by binary comparisons (like "purines" and
"pyrimidines"). However, my teacher at the time,
[Joan Hinton](http://www.whs.school.nz/weeklywrapup/weekly-wrap-up-term-4-week-8/),
curiously recommended that I should consider a career in genetics.

Once I was in a position to decide on university subjects, the advice
was enough to nudge me away from my best high-school subject (physics)
and towards my worst (biology). This decision was the beginning of a
realisation that I could improve myself better by working on my
weaknesses rather than my strengths.

### The Universe of Intransitivity

My first year of university was very good at knocking me off whatever
pedestal I thought I was on at the end of my high school years. I
*thought* I was good at maths, but that bubble was quickly popped when
I saw the ease at which others were completing assignments, and asking
*really good questions*. Even in computer science, I was outclassed by
people who were able to quickly apply their learning to the tasks at
hand; people who seemed to play more than work, and yet performed
better in exams.

But I found consolation in the realisation that the generic term
"better" is not a transitive property. We live in a
rock-paper-scissors world, where ability and success is
multi-dimensional; dependent on our environment and other factors
outside our control.

My first year of university gave me a good grounding in the real
world. I wrote copious notes in lectures and wore myself down, trying
to keep challenging myself both physically and mentally, while I still
had the youth and energy to do so.

## A Lesson in Diagnosis

In a sense, I had an industry job in bioinformatics before I even knew
what bioinformatics was, and certainly before I had any formal
training in research.

During my first year at Victoria University, one of my high school
friends told me there was a job available at her father's work. I was
interviewed by
[Collette Bromhead](https://www.nzord.org.nz/about-nzord/our_people),
who at the time was the head of the Molecular Biology department of
the Medical Laboratory in Courtenay Place, Wellington (now part of
[Wellington SCL](https://www.wellingtonscl.co.nz/)). My main job was
as a cleaner for the PC2 Molecular Biology pre and post-PCR rooms.

### A Few Tips

Every Saturday morning for about four years, I went into the lab and
filled hundreds of tubes with buffer solutions for diagnostic PCR
tests (both lysis buffer and wash buffer), filled pipette tip boxes,
refilled stocks of ethanol and phosphate-buffered saline, washed
dishes, cleaned the benches, and loaded up a box of tube jars for
autoclaving.

I enjoy being alone in myself. My job gave me a lot of solitude and
thinking time, staring out the window at a grey Wellington, while
contemplating what pattern my tip boxes would be today. I couldn't
completely turn off from the work I was doing (*that* almost
invariably ended up with some angry notes in the note book the next
week), but I could turn off enough that I could forget how stressed I
was the day before, finishing off yet another maths assignment half an
hour before it needed to be handed in.

Despite the simplicity of the job I was doing, I still found ways to
optimise it. I worked out that I could grab two long-reach 200μl tips
in each hand and load them into the tip box at the same time, swapping
each hand between grabbing from the bag and loading into the tip box.
I discovered that reverse-pipetting from the wash buffer stock into
the tubes was quicker than standard forward-pipetting, and seemed to
be a bit less variable when using the same tip for all the tubes. I
had worked out how much of the bench I needed to wipe down with
ethanol before it had dried enough to put the equipment back onto the
first place I wiped. And every Saturday after finishing up, I'd record
the hours I had *actually* worked onto my time sheet, and give it to
the person in charge of biochemistry to be signed off.

I still invoice people for my physical hours worked (called "wall
time" in computer science), and not for my thinking time or
efficiency. It helps me acknowledge the time that I'm spending
specifically for a certain project, and being able to have a good idea
of the time cost of jobs is essential for juggling multiple projects
at the same time. If I finish a job faster than I expect, people pay
me less money. If I have a fixed *time* agreement, then I try to do
more work (assuming that's possible). If I have a fixed *cost*
agreement, I'll try to finish promptly (as long as my surrounding life
situation works with that, because it frees up more time to do other
things.
