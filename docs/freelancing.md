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

### The Family connection

My first waged job was actually working for my Māori tribe, working
for a week at the small Rangitāne office in Grovetown, near
Blenheim. I found myself there helping the Rangitane secretary with
their membership database, improving the system they had for entering
data, and improving the way they were recording the consensus family
tree of the tribe. It’s interesting to think about it now, and realise
that I didn’t actually do any data analysis in that first job, but
helped them to do their existing work a little bit more efficiently. I
also learned a lot from that job, understanding a great deal more
about how databases worked, and how one program could allow me to
enter data in one form, then twist the data around so that it could be
interpreted in a completely different way.

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
as a cleaner for the PC2 Molecular Biology pre and post-PCR rooms. My
mother had worked as a laboratory technologist in the years before I
was born, so in a sense I was following in her footsteps.

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

### Contagious Bioinformatics

I caught the bioinformatics bug after I'd been working a few months at
the Medical Laboratory. Collette was aware of my computer science
background, and asked for a bit of help with a research project she
was working on for the Wellington School of Medicine. She was
investigating the prevalence of *Chlamydia trachomatis* in pregnant
women in the Wellington region, and had an interest in comparing the
effectiveness of different genetic testing methods. I ended up doing a
combination of data entry and data analysis for that project, while at
the same time trying to learn as little as possible about the ins and
outs of *Chlamydia* infection. My work on that project led to my first
acknowledgement of bioinformatics work at the end of a paper published
in the New Zealand Medical Journal.

### The Independence of Multiple Bosses

Working a few hours a week in solitude probably helped to give me a
bit of emotional stability, but it quickly stopped challenging
me. Luckily, the Medical Laboratory was big enough that there was
frequently some little job here and there that needed doing. I started
moving around the organisation, adding bits and pieces to my regular
work hours as my study situation at Victoria University allowed for
it. I was still living at home, but began to spend more time away,
probably to avoid the pull of chores, or the discomfort of the
parental inquisition during dinner time.

Over the course of my time at the Medical Laboratory, I ended up
working in the departments of Molecular Biology, Serology,
Biochemistry, Specimen entry, Cytology, Microbiology, Biostandards,
and as a Courier. I became familiar with the process of analysis for
most biochemistry tests carried out at the Laboratory, from bleeding,
to transport by courier to the lab, to specimen entry, data entry,
centrifugation, sorting, machine loading, discarding into short-term
cold storage, and final disposal in a biochemical waste bin. Although
I wasn't there as a qualified professional in any sense (neither
phlebotomist nor laboratory technologist, like my mother), I had a
sponge-like mind for soaking in the random discussions I had in down
time about quality controls, normal ranges, standard deviations,
sensitivity, specificity, and other things that impacted on the
accuracy of diagnostic testing.

Occasionally I'd be given a data analysis project to work on. I had a
go at calculating normal ranges for a few biochemical tests, but
fairly quickly realised that it was not an easy task due to the
difficulty in finding "normal" test results. Another big project found
me translating codes from one external laboratory into a more
standardised format. I acquired an appreciation for the ISO15189
standard that the laboratory adhered to, making sure that everything
we used had an expiry date, that pipettes were properly calibrated,
and that protocols were available for every test to ensure that anyone
from the lab would have a chance of successfully carrying out
diagnostic testing in an emergency.

Apart from my first job in the Molecular Biology department, I was
almost never around in any department for long enough to do a yearly
performance appraisal, let alone to be able to review the goals that
were set from the previous year. Having so many transient managers
meant that I had to learn how to manage myself. I had to make sure
that I was taking care of myself, and only had a few weeks where my
scatterings of part time work added up to over 40 hours (requiring
overtime to be paid).

I enjoyed my time working at the Medical Laboratory, but had to start
scaling the work back as my academic workload increased. By the time I
was a couple of months into my Honours degree, I realised that even
the few hours I was doing on Saturday morning had to go, so I cut
myself free of my financial lifeline before swimming into the ocean of
academic research.

## Additional notes from various conversations (not yet storified)

* It's possible to make a living, but money comes in for me in spits
and bursts, and it's very important to have plenty of buffer money for
work-poor times (like now, for example). I've had to live without
income for a few months while waiting for promising projects to start
up, and [on the opposite side of the coin] have needed to juggle five
or so projects in one week to meet project deadlines. It's much better
to have a small stable base of fixed-payment work (e.g. waged for
15h/week), so that very basic living costs can be paid for while
waiting for other work.


* I've almost always had a somewhat stable job I could fall back on,
which generally comprises about 40-60% of the work I do. I'm also
struggling a bit in finding additional work, because everyone wants
full-time employment, which doesn't fit in with my mode of work. I'm
much more productive if I'm able to work on a broad range of projects,
because there are the occasional flashes of insight where I can use a
solution from one project in a completely different domain.

* For most of my work I use a computer that I assembled myself about 5
years ago. It cost about $2500. It's a 12-core computer with 64 GB
memory and a solid state hard drive for the main system, and a couple
of spinning discs for additional data. I buy another hard drive every
now and then when capacity becomes an issue. Some of my clients have
their own compute server, which I log into for data analysis. I
generally avoid cloud computing and/or compute clusters because it
doesn't work out to be cheap in the long term, and frequently takes a
lot more time to get stuff done.

* IRD has rules about invoicing and tax, which gives me a lot of
guidance with how to deal with international clients. I charge in
foreign currency (with GST added on top of the agreed rate) and give
money transfer details for my NZ bank account, recording on invoices
the NZD equivalent of the billed amount at the time that I do my
invoicing.

* For me the most challenging part of the business side of things is
asking people for money, particularly when they've already given me
money for a project. Having defined project end time points is
important to make it easier to do this. I've been encouraged to create
a written agreement in advance for extra jobs. It's also important to
set out job scope in the initial discussions of projects, giving
examples of things that are in-scope and out-of-scope.

* Doing work on software projects (e.g. Trinity, Canu) has been
incredibly beneficial in increasing my knowledge and capability, but
not so great in getting more paid work. That's partly because some job
contracts are biased against sole-trader businesses (e.g. requiring
$10M liability for damages). I've also limited myself by not wanting
to travel to the USA, and also not working for large multi-national
corporations.

