+++
slug = "digital_cutup"
title = "Digital Cutup"
date = "2020-09-26T15:22:05-04:00"
author = "Noah Kernis"
tags = ["itp", "electronic_text"]
description = "Chopping Broccoli"
showFullContent = false
+++

## Thinking

The assignment for this project:

> The digital cut-up. Create a notebook program that reads in two or more texts and stores portions of them in Python data structures. The program should create textual output that creatively rearranges the contents of the text. Use functions from the `random` module as appropriate. You must use lists as part of your procedure. Choose one text that you created with your program to present in class.

For another class I am taking, *Time*, I have been working on a small project. The project is a sort of experiment with how language controls how we talk about time and space (at least in the western culture in which I was raised). Also, how the words that we use to discuss the world in which we live, often get their meaning in the context of or by referring to each other. 

A lot of my work for the project involved the the 5W's (also referred to as the *elements of circumstance*). I drew a lot, some images and some words. The ones involving words often involved swapping out words for one of the 5 W's, rearranging sentences, and trying to understand the relationships between the 5W's. Here is a link to the post I did for this work: [*elements of circumstance*](https://blog.noahkernis.com/posts/itp/fall_2020/time/elements_of_circumstance/)

For this assignment, I wanted to try something similar. I wanted to find texts that discuss the topics of time and space, and examine what things the specific language of time and space brings up. Further, do the 5W's really relate these ideas, or I am "forcing" it.

So, I went to [Project Gutenberg](https://gutenberg.org/) and searched for texts relating to time and/or space. The following are the texts I chose, and the groups I put them in.

- group 1)  H.G. Wells - fiction, non-fiction, and lecture on future
	- [A Short History of the World by H. G. Wells](https://gutenberg.org/ebooks/35461)
	- [The Time Machine by H. G. Wells](https://gutenberg.org/ebooks/35)
	- [The Discovery of the Future by H. G. Wells](https://gutenberg.org/ebooks/44867)
- group 2) two books about time keeping and clocks and one about the International Meridian Conference
	- [International Conference Held at Washington for the Purpose of Fixing a Prime Meridian and a Universal Day](https://gutenberg.org/ebooks/17759)
		- [International_Meridian_Conference](https://en.wikipedia.org/wiki/International_Meridian_Conference)
	- [Time and Its Measurement by James Arthur](https://gutenberg.org/ebooks/44838)
	- [Time and Clocks: A Description of Ancient and Modern Methods of Measuring Time](https://gutenberg.org/ebooks/54546)
- group 3) living with time and scientific description of time
	- [How to Live on 24 Hours a Day by Arnold Bennett](https://gutenberg.org/ebooks/2274)
	- [Space, Time and Gravitation: An Outline of the General Relativity Theory](https://gutenberg.org/ebooks/29782)

Group 1 contains 3 texts by H.G. Well. *The Time Machine* is fiction, *A Short History of the World* is non-fiction, and *The Discovery of the Future* is lecture. I thought it would be interesting to look how time and space are discussed by the same author, in three different styles of texts, written at different points in the authors life. 

Group 2 also has 3 texts, all by different authors. In this case, two of the books look at how we as people track time and the history of it. The third, *International Conference Held at Washington for the Purpose of Fixing a Prime*, is protocols of the proceedings from the International Meridian Conference. To quote the text directly, the conference, held in 1884 was for, "'for the purpose of fixing upon a meridian proper to be employed as a common zero of longitude and standard of time-reckoning throughout the globe..."' (p. 1). I wanted to juxtapose texts discussing how time is kept vs a text where people came together to decide how time will work and be kept moving forward.

Group 3 has 2 texts. *How to Live on 24 Hours a Day* is a book about living with time and what that may or may not mean for us. *Space, Time and Gravitation: An Outline of the General Relativity Theory* is a cut and dry explanation of theory of general relativity. Here, I was looking to compare the science of time and space with what it is actually like for humans to live in time and space.

## The code

*Note: the post continues inside the embed below*

{{< gist nkernis c86de2a6d4b4563691a74aadb28f2278 >}}

[link to digital_cutup.ipynb](https://gist.github.com/nkernis/c86de2a6d4b4563691a74aadb28f2278)

## A poem

There are actually three here. The first two are from the early part of developing the code. The third was generated by the final version. 

This was generated using texts from group 1, using the seed word "time".

```
If we could have visited the earth at that time we should have
and brought for the first time into the world of human thought. We have
on, waiting for the Time Traveller; waiting for the second, perhaps


gladiators, who sometimes fought in the arena but whose real
sometimes a sort of dreaming or a strong suggestion will put things in.
Time Machine?’ I began, bawling like an angry child, laying hands upon


monument of resolve; times when he relaxed his mind by jesting and
confess I believe that if by some juggling with space and time Julius
of every day is too much for my memory. Did I ever make a Time Machine,
```

This was generated using texts from group 2, using the seed word "time".

```
measuring them with microscopic gauges from time to time, and at once
stretching over sixty degrees of longitude, with a difference of time
mark to the shadow and it will be right for all time to come. Owing


escapement, which was employed in that popular and excellent timepiece
make the beginning of civil time and of dates on the first meridian
Stated simply, for our present purpose, 1st is sundial time, and 3rd


is extinct. One I purchased at that time has gone well ever since.
know. This intermediate point would, for the time, be the practical
little "swashplate" motion. The positions of a number of "time stars"
```

This was generated using texts from group 3, using the seed word "time" then "space".

```
spent one's time badly, but one did spend it; one did do something with
	what one has
	when one sets forth on the enterprise of using all one's time,
	who have to work longer for a living, but there are others who do not
	where we stand
	Why should you be astonished

space-time which we have been studying
	why it should relate to matter especially; since matter is not
	who insist on investing the words with
	where these laws do not apply
	when a
	what the readings of any kind of clock record, what


in the space of my command
	what you are reading,
	where there are a hundred
	when you
	who have intellectual curiosity--the
	Why should you be astonished

there are still definite natural tracks in space-time far beyond the influence
	Why are you specially interested in Euclidean
	who is accordingly travelling with a velocity approaching that of light relative to S
	when their weight vanished altogether at the
	where the broken line shows the theoretical
	what kinds of space-time can
```