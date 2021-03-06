---
layout: layouts/post.njk
title: >
  262 RR Community and Mentoring with Ra'Shaun "Snuggs" Stovall and Noel Sagaille
date: 2016-06-01 07:00:21
episode_number: 262
duration: 59:03
audio_url: https://media.devchat.tv/ruby-rogues/RR262CommunityMentoring.mp3?rss=true
podcast: ruby-rogues
tags:
  - ruby_rogues
  - podcast
---

### Check out [Ruby Remote Conf](https://allremoteconfs.com/ruby-2016)!

&nbsp;02:12 - Ra’Shaun “Snuggs” Stovall Introduction

- [Twitter](https://twitter.com/snuggsi)
- [GitHub](https://github.com/snuggs)
- [Facebook](https://facebook.com/snuggsi)
  02:29 - Noel Sagaille Introduction
- [Twitter](https://twitter.com/mrbernnz)
- [GitHub](https://github.com/mrbernnz)
- [Censible](https://censible.co)
  02:56 - [The Pomodoro Technique](https://pomodorotechnique.com/)
- [Parkinson's Law](https://en.wikipedia.org/wiki/Parkinson%27s_law)
  04:43 - Community and Community Leaders
- [The 4-Hour Workweek: Escape 9-5, Live Anywhere, and Join the New Rich by Timothy Ferriss](https://www.amazon.com/4-Hour-Workweek-Escape-Live-Anywhere/dp/0307465357)
- “Hometraining”
- [Being John Malkovich](https://www.imdb.com/title/tt0120601/)
  - [Polyphasic Sleep](https://en.wikipedia.org/wiki/Polyphasic_sleep)
  - [Carl Jung](https://en.wikipedia.org/wiki/Carl_Jung)
    19:11 - Values
- [Altruism](https://en.wikipedia.org/wiki/Altruism)
- [Autonomy](https://www.dictionary.com/browse/autonomy)
  26:02 - Mentorship
- Switching Roles
- Advocacy
- [Mastermind Groups](https://www.thesuccessalliance.com/what-is-a-mastermind-group.html)
- Homage
  Picks
- [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt) (Sam)
- [James Edward Gray II: Implementing the LHC on a Whiteboard](https://confreaks.tv/videos/railsconf2016-implementing-the-lhc-on-a-whiteboard) (Coraline)
- [Cracking the Coding Interview: 150 Programming Questions and Solutions by Gayle Laakmann McDowell](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/098478280X) (Coraline)
- Thinking about your health (Chuck)
- [FitBit One](https://www.fitbit.com/one) (Chuck)
- [Block & Flow](https://itunes.apple.com/us/app/block-flow-pomodoro-technique/id1018884302?mt=8) (Ra'Shaun)
- [Censible](https://censible.co) (Ra’Shaun)
- [Heroku Pipelines](https://devcenter.heroku.com/articles/pipelines) (Noel)
- [Dialogue - A proposal by David Bohm, Donald Factor and Peter Garrett](https://www.david-bohm.net/dialogue/dialogue_proposal.html) (Noel)

### Transcript

**CHUCK:&nbsp;** Why you calling me?

**_[This episode is sponsored by Hired.com. Every week on hired they run an auction where over a thousand tech companies in San Francisco, New York, and L.A. bid on Ruby developers providing them with salary and equity upfront. The average Ruby developer gets an average of 5 to 15 introductory offers and an average salary offer of $130,000 a year. Users can either accept an offer and go right into interviewing with a company or deny them without any continuing obligations. It's totally free for users. And when you're hired, they give you a $1,000 signing bonus as a thank you for using them. But if you use the Ruby Rogues link, you'll get a $2,000 instead. Finally, if you're not looking for a job but know someone who is, you can refer them to Hired and get a $1,337 bonus if they accept the job. Go sign up at Hired.com/RubyRogues.]_**

**_[I'm excited to tell you about a new sponsor to the show, Rollbar. One of the frustrating things about being a developer is dealing with errors. Ugh. Relying on users to report errors, digging through log files to debug issues, or a million alerts flooding your inbox ruining your day. With Rollbar's full-stack error monitoring, you get the context and insights and control you need to find and fix bugs faster. It's easy to install. You could start tracking production errors and deployments in eight minutes or less, or automatically create new issues in GitHub, JIRA, Pivotal Tracker, et cetera. They have a special offer for Ruby Rogues listeners. Go to Rollbar.com/RubyRogues to sign up and get the bootstrap plan free for 90 days. That's 300,000 errors tracked free. Give Rollbar a try today. Go to Rollbar.com/RubyRogues.]_**

**CHUCK:&nbsp;** Hey everybody and welcome to episode 262 of the Ruby Rogues Podcast. This week on our panel we have Coraline Ada Ehmke.

**CORALINE:&nbsp;** Hey there.

**CHUCK:&nbsp;** Jessica Kerr.

**JESSICA:&nbsp;** Good morning.

**CHUCK:&nbsp;** Sam Livingston-Gray.

**SAM:&nbsp;** Because of the interesting word usements I structure.

**JESSICA:&nbsp;** [Laughs]

**CHUCK:&nbsp;** I'm Charles Max Wood from DevChat.tv. Quick shout out about Ruby Remote Conf. Go check it out, RubyRemoteConf.com. We have two special guests this week. We have Ra'Shaun Stovall.

**SNUGGS:&nbsp;** Salut.

**CHUCK:&nbsp;** And Noel, I'm not even sure how to say your last name. [Inaudible]

[Laughter]

**NOEL:&nbsp;** I know. It's French, as this man just 'salut-ed'. But it's Sagaille. So, Noel Sagaille.

**CHUCK:&nbsp;** Do you both want to introduce yourselves?

**SNUGGS:&nbsp;** Awesome. I would say that that is my government name. But throughout the community they might not know who I am on this unless you reference to me as Snuggs.

**CHUCK:&nbsp;** Oh, okay.

**SNUGGS:&nbsp;** Let's just say that people often ask “Where did you get that nickname from?” and I'll say, “It's so old let's just say I'm happy I wasn't called Stinky back then.” [Chuckles]

**NOEL:&nbsp;** Oh, okay.

**CHUCK:&nbsp;** Noel, go ahead and introduce yourself.

**NOEL:&nbsp;** Yeah. My name's Noel. I'm a software engineer. I work at Censible.co which is a [inaudible] investment website that aligns your social values with your investments. I'm, I don't know, I'm not that proficient in Twitter. But I do go by the handle mrbernnz. It's a play on my middle name and The Simpsons.

**CHUCK:&nbsp;** Awesome. Well, we brought you on today to talk about communities and mentorship. And you both recommended something a little bit different from what we usually do. Do you want to explain what we're doing and then we'll move ahead from there?

**JESSICA:&nbsp;** [Inaudible] talk about the Pomodoro.

**CHUCK:&nbsp;** Yeah.

**SNUGGS:&nbsp;** Oh, I see. When you're doing a Pomodoro technique, what it… the TL;DR is Parkinson's Law affects us all. When we're passionate about something we will exhaust the very last microsecond of time and use the excuse that I can't go to bed because the internet is broken. So, the Pomodoro technique allows you to time-box things. It actually is Italian for tomato. If you remember the little tomato timers you would set for 25 minute and then all of a sudden your pie would hopefully be ready. So, just by time-boxing the work that you do and looking back in a reflection moment for five minutes even, even if it's just to go to the bathroom, that's always beneficial. Whatever you do in those five minutes is up to you. I like to go around and do a round of what did you learn because you often are surprised by what other people have learned.

**CORALINE:&nbsp;** Little known fact. I'm actually getting pie at the end of this Pomodoro.

**CHUCK:&nbsp;** Mm.

**JESSICA:&nbsp;** Yay.

**SNUGGS:&nbsp;** [Laughs]

**JESSICA:&nbsp;** [Inaudible] tomato.

**SNUGGS:&nbsp;** Hashtag facts. So, does that explain what a Pomodoro technique is?

**CHUCK:&nbsp;** Sounds good to me.

**SNUGGS:&nbsp;** And because I like to ramble so that kind of keeps me, keeps the [inaudible]

[Laughter]

**JESSICA:&nbsp;** Okay. So, we're planning one Pomodoro. The 25 minutes is we're talking about community and then we'll take a break and talk about something for five minutes. And then we're going to talk about mentorship in the second one.

**SNUGGS:&nbsp;** Precisely.

**JESSICA:&nbsp;** And Sam, you posted the definition of Parkinson's Law. Would you say what that is?

**SAM:&nbsp;** Yeah, I always have to look up these various laws. And Parkinson's Law says work expands so as to fill the time available for its completion.

**CORALINE:&nbsp;** Story of my life.

**JESSICA:&nbsp;** So, we have limited time for this [inaudible] completion. [Chuckles]

**SNUGGS:&nbsp;** Noel, would you like to kick us off?

**NOEL:&nbsp;** I'm ready for this mission impossible. So, the community that I [believe] I'm involved in is Ruby for one and Ember for another. What I believe or how I see that they support and help my growth in the community is by, I guess it would be the idea of welcoming new people regardless of where you're coming from. It's usually a sense of, “So, how did you learn about this meetup? What makes you so interested in coming here, learning about frameworks and so forth and so on?” and also bringing up interesting topics for the meetups from month to month. [Inaudible] with Ember, it was just a curiosity in trying to understand that framework and how they have I would say study groups I guess on, like it would be either before or after a particular monthly meetup where you can go just try to pair up with someone who's working on a project or come in with a problem that you may have with yours. And it was like no judgment I guess. But I would say it makes you feel comfortable. I'll leave it at that. It just, there's no sense of non-inclusion.

**SNUGGS:&nbsp;** So myself actually, I actually was in Virginia. [Inaudible] Virginia was where I want to school. James Madison University. Go Dukes. And [chuckles] I had this call. I knew that there was be an opening in the Ruby community. I got a degree in business and it was a business decision for me to learn how to program. So, I was knee-deep in the Microsoft community and then via Rosetta Stone they actually introduced me to Ruby with their development team and actually was my first [part] of what a meetup felt like and what a community was. I read 'The 4-Hour Workweek' actually, shout-out to Avdi who [inaudible] on this call. But ironically I was on the boat in Miami and I was thinking of the 'The 4-Hour Workweek' and Avdi said it on one of the podcasts as one of his picks. And I was like, “It's serendipity.” [Laughs] And I wound up, next thing I know by the time I got to chapter nine I was packing all of my bags, one-way bus ticket to New York City and I was off.

One of the first meetup groups that I went to was NYC.rb which I currently am the event organizer to now. That was at Pivotal Labs back when Pivotal was maybe 15, 20 people. Now they're gosh knows how many. And I also started work with another meetup group and [chuckles] it's funny. Noel, so Jessica brought it up, I'm going to have to bring it up myself. I actually would like to go on record and to publicly give an apology to sir Charles Max Wood actually.

**CHUCK:&nbsp;** Okay.

**SNUGGS:&nbsp;** And Charles is going to be like, “Wait, what? What part of the game is this?” [Laughs] So, back around 2010, 2011, I was requested. One of the requests I had was to help start a meetup group called Ruby Nuby. And it was sponsored by NYU and about a thousand or so people signed up for it. I probably taught about 1300 people if I'm not mistaken over the course of three years.

**CHUCK:&nbsp;** I know where this is going now.

**SNUGGS:&nbsp;** Right, right. So, there's no shade here, Charles. This is a gentlemanly thing here. [Chuckles] Now after a couple of years I remember hearing about Ruby Nuby and Charles had a valiant effort. I think it was great. I watched all of the videos. But I had felt some kind of way because I said, I was like, “Man, I dedicated so much of my life into hundreds and hundreds of people in New York and they did not google to see that that was there or not?” I wasn't sure. And I think I might… I sent some tweets in Charles's way and I was just like, “Dude, man. We were already there.” And in retrospect I remember Charles blocked me. And I was like, “Oh my gosh. What did I just do?” because as you heard, I've been listening to Ruby Rogues since episode one. And I felt some type of way about it and I said whenever I see Charles I am going to apologize to him because as community leaders that's not something that we would show in public. What we should show in public is when someone is humble enough to say, “I apologize.” And hey, the greater scheme of things we're both trying to help the community. So, I hope you accept my apology.

**CHUCK:&nbsp;** Oh, absolutely. I had totally forgotten about it. That's how offended I was.

**SNUGGS:&nbsp;** I know. It was…

**CHUCK:&nbsp;** [Laughs]

**SNUGGS:&nbsp;** Noel actually said, he was like, “Are you sure you're going to bring that up?” And sometimes they say you don't want to let people live rent-free in your head. And I was like I owe it to myself to give Charles's deposit back if you will.

[Laughter]

**SAM:&nbsp;** So Snuggs, that clicking sound you hear in the background is Chuck unblocking you now.

**SNUGGS:&nbsp;** Right.

[Laughter]

**CHUCK:&nbsp;** I might have to go look at my block list.

**JESSICA:&nbsp;** I find this really interesting because it brings up the part where you invest in a community and then something totally random that's not directed at you can appear to devalue that investment. And that's, on the one hand it's a risk that we take by investing in anything. And on the other hand I guess over time you develop the awareness of, “Oh, maybe that wasn't about me.”

**SNUGGS:&nbsp;** Exactly, exactly. Because you know what cancelled all of that? When I saw the videos of the people who submitted to Ruby Nuby for Ruby Rogues. And I was like, “You know, that's the reason why I do it, just to see that smile on their face” like I just learned something new and someone accepts me.

**CHUCK:&nbsp;** Yeah, it is interesting though. And yeah, I remember the email… I think I got an email and some tweets. I think there were also a few other people that you mentioned that I wound up contacting and going, “So, what did I miss?” and I generally got nothing. [Laughs] So it was, yeah we did it. And yeah, it was cool. And what you're doing is cool. And yeah, that was about it.

**SNUGGS:&nbsp;** Mmhmm.

**CHUCK:&nbsp;** But it was just interesting to me. It was like, “Oh wow.” I didn't know that I had stepped on other people's space. Btu at the same time I was probably in a bad mood and just, “I don't want to deal with this.” and I blocked it. [Chuckles] I blocked you. I apologize for that as well.

**SNUGGS:&nbsp;** Oh, no worries. Because when I went and looked at your Twitter profile my hand was shaking and sweating. And then I saw that I could actually accept or that your profile was open. So, the clicking you hear right now was me clicking follow on Charles's Twitter profile. [Laughs]

**CORALINE:&nbsp;** I think this is really important in a way because I think that we have a lot of people in the community who, I was on a podcast on Saturday and the woman who was interviewing me was talking about people with no home training. [Chuckles] And I hadn't heard that expression since my days in [inaudible] were I grew up.

**SAM:&nbsp;** I've never heard it at all.

**CORALINE:&nbsp;** Yeah. It's basically like a lack of common decency and common sense. We see these on really public feeds sometimes and I think it's great when people in the community who do have conflicts resolve them in a mature, open, professional manner. I think it models good behavior for everyone else to follow. And I wish more people would do that.

**JESSICA:&nbsp;** So, home training is like house training except with your mouth not your pee?

**CORALINE:&nbsp;** Nice. I like that.

[Laughter]

**SNUGGS:&nbsp;** That almost went over my head before I reached up and caught it actually. Well done, Jessica. [Laughs] Nice. So if you will, I'd actually like to approach this talk from the perspective of a community leader. Have you ever seen the movie 'Being John Malkovich'?

**CORALINE:&nbsp;** Love it.

**CHUCK:&nbsp;** No.

**SAM:&nbsp;** Oh yes.

**JESSICA:&nbsp;** Yeah, that's a great movie.

**CHUCK:&nbsp;** I haven't.

**JESSICA:&nbsp;** Recommend.

**SNUGGS:&nbsp;** So whoever has, if you can give a brief, a sentence synopsis on what it's like?

**JESSICA:&nbsp;** Oh, there's this weird tunnel. And like, dude finds this weird tunnel like the seven and three-quarters floor of some building and he goes in it. And if you crawl into the tunnel you actually get into the head of a different person. And the person was John Malkovich who's some actor. And then he gets to control John Malkovich for a while until I forget what happens and then it blech! Spits him back out the tunnel.

**SAM:&nbsp;** And dumps you onto the Jersey turnpike.

**JESSICA:&nbsp;** Yeah, yeah. That's right. The exit is not the entrance.

**SNUGGS:&nbsp;** Yes, [chuckles] absolutely. So, I wanted to approach it from that manner, because everyone wants to be part of a community but really, to pick the brain of our community leaders which I definitely call myself one. I think I've earned those stripes at least in my own mind. And I'm definitely sitting with ones that are as well. And just so we're not sitting on ivory towers, that's one of the reasons why Noel actually came on board. Because the mentee is the check and the balance of the mentor [chuckles], right?

**CHUCK:&nbsp;** Yeah. The thing that I like to point out though with the idea of community leaders is that some people get it in their head that they have to be somehow blessed or anointed to be the community leader. And in a lot of cases all you really have to do is be out there and trying and helping people. And you…

**SAM:&nbsp;** Just show up.

**CHUCK:&nbsp;** Sort of assume that role as you make a difference for more people.

**SNUGGS:&nbsp;** Absolutely right. So, I figured that from the 'Being John Malkovich' part I wanted to step through a little bit of my typical day.

**CHUCK:&nbsp;** Yeah, go ahead.

**SNUGGS:&nbsp;** So, have you ever heard of polyphasic sleep? I'm going to go head and put this link.

**CHUCK:&nbsp;** Yes.

**JESSICA:&nbsp;** Oh, is that the thing where you sleep and then you're up for a little while and then you sleep again?

**SNUGGS:&nbsp;** Yes, ma'am.

**SAM:&nbsp;** Yeah, our culture promotes monophasic sleep where you get all of your eight hours in one chunk. But polyphasic is, there are various configurations, right Ra'Shaun, of sleeping for different bits of the day?

**SNUGGS:&nbsp;** Precisely. Absolutely right. If you nail it then what happens is in Slack your colleagues say, “Do you ever sleep? You respond to everything.”

[Laughter]

**SNUGGS:&nbsp;** So, I get about three… I take about on average three two-hour naps on a daily basis. This has been [inaudible] last four to five years. And that just works for me. I often tell people do what's best for you. Let's calm down on the projections of what we do best onto others. And then you can use someone's experience instead of taking their advice. So, after a couple of rounds of polyphasic sleep around 6am I do about a half an hour worth of yoga. Usually, on Tuesdays, Thursdays, Saturdays, and Sundays I'll cumulatively I'll run about 30 to 40 kilometers a day. Or week. Good god.

**CHUCK:&nbsp;** Wow.

[Laughter]

**SNUGGS:&nbsp;** A week. And I always joke in the community, I say the community's not that tough. Because you'll never be tougher than my football coach with the air horn in your ear at five in the morning like, “Get up! Get up!” [Laughs] So, I'm cut from that cloth. I think that's why I still run. I think I'm still running away from my coach. And afterwards I typically go into languages. I've gotten to the point in my career where programming is actually easy to me. Solving a problem is really the niche. The language is just an implementation detail. So, I've gotten onto the next phase where I'm doing French immersion. So, my computer, my cellphone, pretty much everything that I can control the locale of is actually set into French. And it's actually been a better learning process for me than trying to read a book, just via iconography from things that we can associate with. Recently I've been… I would typically do some studying with psychology from my guy I have a man crush on which is C. G. Jung, Carl Gustav Jung. He's helped me understand my own brain so I can help other people understand theirs.

Typically I'm in what I call perpetual motion, always moving. Anyone that knows me knows that I'm typically pacing or from city to city. I call it perpetual retirement as well to where I'm traveling and leveraging investment in other people's time like Noel. Jessica since I've talked to you last which is about a month ago, maybe a month or two ago, I've been in 15 different cities speaking from conferences to meetup groups to just going and saying, “Hey, you asked me to pair and here I am.” So, I actually just took the train from Seattle all the way down to San Diego and stopped at every city in between. I stopped at each Pivotal Labs, all of the go-to people. And even the little people who are coming up to help them out as well. And that's usually how I start my day off.

And then I'll go check my messages. I'm averaging about three to five hundred messages per day and communicating with about a hundred to 200 people on a daily basis. Now of course, I leverage other people's time with that. But once again, Timothy Ferriss he helped me mitigate all of that stuff. But from traveling so much, that's allowed me to reach out and meet cool people such as yourselves. And I've been able to pair with Jim Weirich, may he rest in peace. Actually Jim, he helped me a ton at thoughtbot. He called me a Git master. And he said a lot of people aren't going to see what you see in Git but don't fight with them. Just let them learn on their own time. Corey Haines who's been on the Ruby Rogues podcast, him and I, we hacked it up a little bit on C# on his CodeRetreats which I love so much. Evan Light as well who does CodeRetreats, I call him my muffin top. [We share] muffins all the time in San Francisco. I believe he's been on Ruby Rogues as well. And Yehuda Katz who I often bump into in 7-Eleven's.

And so, that leads, that introduces me to people such as Jessica where Jessica and I just happened to sit next to each other at the Distilled conference and look at where we are now. I'm sitting here talking to Jessica and et al. And I am about as nervous and humbled as Noel is. So, getting out there and I'm really exposing that as far as the sacrifice that I've put on my life to actually use these communities. Some people as me. They're like, “You must have a 25<sup>th</sup> hour in a day because I don't see how you get so much accomplished.” But to me it's just personal disciplines.

**JESSICA:&nbsp;** That was a lot. You have a busy day.

**SNUGGS:&nbsp;** Yes, absolutely. I think it's from ADHD and being OCD all combined and the same. But I'm finding my sweet spot and my balance.

**JESSICA:** So, one thing that I noticed there is that just pairing with random people can be a form of community building and leadership.

**SNUGGS:&nbsp;** Well, that's where it starts, Jessica.

**JESSICA:&nbsp;** It starts one on one. If you think about it, when you come to the user groups regularly and maybe you go to more than one in your area and new people come in and they come to the groups for the first time, they see you as an example, as a relative leader. And you don't even realize when you're setting an example for people. And then if you offer to help and pair with people yeah, that's leadership. And it scales up slowly.

**SNUGGS:&nbsp;** You're right. That's how I met Noel. He tapped me on the shoulder on multiple talks that I'd given and he said, “Look man, this is the third time I'm going to walk up to you at a podium and tell you I want to study under you.” [Chuckles]

**CORALINE:&nbsp;** So in my opinion, and this is something I talk about in some of my open source talks, a community is not just a group of people doing the same thing. A community is a group of people who have shared values and they act on those values. So Ra'Shaun, what are some of your values as a developer?

**SNUGGS:&nbsp;** Some of my values as a developer. Typically I'll start thinking of my mother who is my business mentor, development mentor. She actually was a programmer I found out recently, which blows my mind. There are two things that I love, the two A words. Altruism and autonomy. So, who can give me a definition of what altruism and a definition of what autonomy is? And…

**JESSICA:&nbsp;** Altruism is… oh, go on.

**SNUGGS:&nbsp;** I said in your own eyes, of course.

**JESSICA:&nbsp;** Altruism is usually putting other people's interests at least equal with yours. And autonomy I think of as something that you grant to other people when you don't try to tell them how to do something.

**NOEL:&nbsp;** I guess I can… Oh, sorry.

**JESSICA:&nbsp;** No, go.

**NOEL:&nbsp;** Go ahead.

**JESSICA:&nbsp;** No, go, go, go.

**NOEL:&nbsp;** I was going to say because I probably got the cheat sheet.

**JESSICA:&nbsp;** [Chuckles]

**NOEL:&nbsp;** Altruism is basically having empathy in the sense of understanding other people's points of views and so forth. While the other would be basically giving that person or others the power to make decisions without having to come to the other person or go to a manager. Giving them the confidence to go there and not worry if they're going to do something wrong.

**JESSICA:&nbsp;** So in that case, altruism is something you look for in yourself and autonomy is about other people's autonomy?

**NOEL:&nbsp;** In my understanding, yeah.

**CHUCK:&nbsp;** You can definitely act to preserve your own autonomy. But yeah, I like the sentiment of allowing people to succeed or fail on their own or make the decisions that make the most sense for them, because they are where they're at. And sometimes we don't always see all of the important parts of that, which if you're trying altruism to empathy is an important part of empathy, is recognizing that you don't… you can't completely empath with another person.

**SNUGGS:&nbsp;** This is true. My mother says often too that there's a difference between empathy and sympathy. So, always have empathy, 100% empathy but have zero sympathy. That's a pity party. I had empathy for when Noel was attempting to learn something new when we pair. We figure out how we can remove those blockers but having zero sympathy say for instance one of the other individuals I mentor, Lizzy, she often will hit me up and say, “I'm having problems…”

**NOEL:&nbsp;** I'm sorry for cutting you off. We just hit that Pomodoro.

**JESSICA:&nbsp;** [Chuckles]

**NOEL:&nbsp;** I've been very quiet and letting people speak without trying to give warnings. But as Ra'Shaun would say, the question at this moment is how do you feel about what you had done?

**SNUGGS:&nbsp;** Stars.

**NOEL:&nbsp;** Yes, there are stars. There are categorical stars.

**JESSICA:&nbsp;** In the Pomodoro?

**NOEL:&nbsp;** In the Pomodoro that I have, there's no stars, there's one star which means happy, two stars means excellent, three stars means incredible. So, to everybody in the call, how do you feel?

**JESSICA:&nbsp;** It's a very [right-biased] star system.

**SNUGGS:** &nbsp; It is, isn't it? And they don't have to use it. That's just part of one of the apps we built. That's what it asks you.

[Chuckles]

**JESSICA:&nbsp;** Sam made a dirk face in the chat.

**SNUGGS:** I'll start off. I would like to have three stars, really four if I could, because I feel really good about what happened with Max and I. You don't understand how much that means to me.

**CHUCK:** &nbsp; I feel like it's been three or four stars so far. It's funny because I don't feel any different [laughs] because I wasn't worried about it before.

**JESSICA:&nbsp;** [Inaudible]

**CHUCK:&nbsp;** But at the same time yeah, I feel like the conversation has been terrific. It's been helpful. It really illustrates a lot of important points about being a leader and understanding the roles that we play not just in our own lives and careers which is sometimes what we focus on but also in the lives, careers, and understanding and the way that people grow for other people.

**SNUGGS:&nbsp;** Awesome.

**CORALINE:&nbsp;** So, I'm going to say two stars because what I would like to see us do in our second Pomodoro, I think there are two ways that you can communicate effectively with people. You can inspire them by example and you can provide guidance to them directly. And I think that the first half, our first Pomodoro has focused on inspiration but has not been terribly practical. So, I'd like to see us swing to the more practical aspects of what we're going to talk about in the second Pomodoro.

**SNUGGS:&nbsp;** Excellent. You mean the actual, the how you do it. [Chuckles]

**CORALINE:&nbsp;** Exactly, yes.

**SNUGGS:&nbsp;** I smell the sizzle. Where's the steak? [Laughs] Great. And Noel yourself, and then we can do a round of what did we learn?

**NOEL:&nbsp;** Well for me, I think I would say I'm excellent. That would be two stars or so. It's still the idea of making sure my communication is good and what I'm trying to get across. But it was excellent seeing my mentor resolve an issue that he felt he had with another community member. So, that was good to see that for him. It was also good to understand from his perspective how he sees himself as a leader reflective of me as a pupil and how everybody else's perspective is on the community itself.

**SNUGGS:&nbsp;** What did you learn, Charles?

**CHUCK:&nbsp;** For me mostly I learned that for one I need to have a little bit more empathy just from the sense of, a resolution there, it brought up okay, well I just reacted. I blocked you on Twitter and it made me think about okay, well maybe that wasn't the best way to handle that. And if I had really thought about how you felt, I probably would have responded a little bit differently.

**SNUGGS:&nbsp;** Wow. Interesting. Sammy, what's up? What'd you learn?

**SAM:&nbsp;** I'm going to pass. Sorry, I'm not feeling especially engaged or… I'm having a hard time following this conversation this morning.

**SNUGGS:&nbsp;** Okay.

**JESSICA:&nbsp;** You know, I'm going to give Sam some stars for saying that, because just being able to acknowledge… well for one thing, when you acknowledge when you're not engaged and feeling included and participatory enables us to change our own styles of discussion to be more inclusive, to be more, I don't know, to make it work for the entire group.

**SNUGGS:&nbsp;** I like that, because imagine going through an entire show without exposing that information. That's one of the things I like about Pomodoros when you can step back and say, “Oh wow. I put myself in that person's head for a second.”

**JESSICA:&nbsp;** Or didn't find that bridge, tunnel.

**SNUGGS:&nbsp;** [Yes].

**JESSICA:&nbsp;** And I wonder sometimes if our listeners ever feel like, “Man, what the heck was that? That just didn't say anything to me.” And maybe it makes them feel better to know that now and then we feel the same way.

**SNUGGS:&nbsp;** [Chuckles] Absolutely.

**JESSICA:&nbsp;** Is it time for mentorship?

**CORALINE:&nbsp;** Alright. Let's start our second Pomodoro and talk about practical ways to engage in mentorship.

**SNUGGS:&nbsp;** Absolutely. I want to incorporate Noel a little bit more into this because why not have the mentor and the… is mentee a word? I swear I'm [inaudible] how to spell it and I can't…

**CORALINE:&nbsp;** The word is typically or the word classically was protégé. But I think that that is a little ostentatious if you will. So, I think mentee is fine.

**SNUGGS:&nbsp;** Why does it come up as red underlines when I type it? Well, that's a question for Apple I guess. [Chuckles]

**CORALINE:&nbsp;** You can modify your dictionary to add it to the dictionary. So, you have control over the English language.

**SNUGGS:&nbsp;** I did not know that at all.

**SAM:&nbsp;** As do we all.

**SNUGGS:&nbsp;** Mmhmm. So, what I'd like to… let's start off with talking about people switching roles. Noel, we do that quite frequently in our day to day. And in switching roles and in positions and passing on information can you touch on that for a little bit on what you mean by that from your perspective?

**NOEL:&nbsp;** What we have at work is basically I would understand it as people trying to educate others in different domains where it'd be marketing, software development, ESG. I'm talking right now so hopefully Snuggs, Ra'Shaun, can give a link to what that is. That's actually environment, social, and governance. And basically trying to give an overview of this information to other people that wouldn't be relatively nuanced in it. So, we do pairings and within our company we try to basically not go more than 48 hours without touching base with somebody. In that sense we make sure the other person or the two people that are engaging don't become distant, don't become disconnected on what is going on with another person's day to day work. It helps with the sense of where the… if Ra'Shaun were to pair with me and I just learned something, best way to basically understand it is explain it to somebody else. So, we go through that many a time at work. So, that's an example that I can give.

**SNUGGS:&nbsp;** So, I would say from a microlevel your day to day, doing Pomodoros… Jessica's actually been through the flow. Her and I have done multiple Pomodoros together. Now on a more macro level the A's again. The altruism and the autonomy. So, I am actually the event organizer for NYC.rb. It's one of the biggest meetup groups in the world pretty much. Second biggest in America, second to the one in San Francisco. So, there's about close to 5,000 members that are there.

And recently I stood up and I told the recruiters that were there and the people who had jobs, I said, pardon my French, but “Cut the shit.” And when I stood on record and said that what I meant by it was we oftentimes say there are more jobs… it's a booming industry and there are tons of Ruby jobs and they're all over the place. But guess what? I have by the drones people coming to me stating they want someone who's senior. And they want someone who's senior. So, all of these schools like say Flatiron School and General Assembly, they're set up because there was a need to have developers. But when these developers come out it's almost like they get the door shut in their face. Noel explicitly came up to me and said that I couldn't believe what was going on in the industry with so many people shutting doors in the face of very talented people. But just because they don't have a Computer Science degree or they don't have seven years of Ruby experience?

**SAM:&nbsp;** Yeah, I hear that a lot, too.

**SNUGGS:&nbsp;** Mmhmm. Create an environment for them where you put them in the sandbox. So Noel for instance, he runs all of our DevOps related things. And typically someone who will come in and be a mentee you'd say, “Well, keep them away from the sensitive things like prod.” Well, why not set them up so they have an ecosystem where they can learn on prod? Really, they shouldn't be able to knock anything over. You should be able to get things back up. But I told the entire community, I said, “Give these people a chance.” I gave Noel a chance. I invested my time and effort in him and I see this man shine on a daily basis. We're not doing enough of that. And what's going to happen, and I'm calling it, is there'll be a rift within the community where you'll have a ton of people who want to come and be developers but they get the door shut in their face, they're going to find another community that accepts them.

**NOEL:&nbsp;** I could possibly just give more of a clarity from my perspective where I would be looking for an opportunity or anything like that. And not to be in my [inaudible] or so but it was a perspective of hiring managers looking for particular people that resembled them and had the same background and probably having a distaste for people that possibly couldn't fit into that diagram I guess. Like cross all the T's, dot all the I's, so to speak. So, it would be a tougher hill to climb if you didn't reflect the vision that they had for what they want from that position.

**CORALINE:&nbsp;** It's really clear to me that the old way of filling development jobs with CS grads, a lot of people are still clinging to that saying, “Oh, we need to get more people in CS programs.” And I think all we need to do is be more open to people from different backgrounds. I don't have a CS degree. I know a lot of people who are very successful that do not have CS degrees. And our hiring practices need to reflect the fact that the population of developers that we are drawing from is largely not CS graduates anymore. It's people who are coming from bootcamps. It's people who are self-taught. And we need to tailor both our interview process and our working environments to that fact. And I think a huge part of that, in making people successful, is people who are established already in their careers remembering how they got started and working actively to bring people along with them.

**JESSICA:&nbsp;** Yeah, that goes back to mentorship. We talk a lot about needing mentors but there's another side of that which is advocacy. Is that the right word?

**CORALINE:&nbsp;** I think it's a great word.

**JESSICA:&nbsp;** Because you don't get jobs from your resume typically. You get jobs by knowing people. And people love to hire the people they know. And so, a big part of mentoring is really helping people, is also advocating for them, within your company especially. Somebody needs to say, “Hey, have you thought about promoting so and so? Because I think she'd make a great architect,” or whatever it is.

**CHUCK:&nbsp;** Well, even…

**JESSICA:&nbsp;** And often… oh, go ahead.

**CHUCK:&nbsp;** No, I'm sorry. I didn't mean to cut you off. I thought you were… but this idea that you're talking about is something that… that's what my book, 'Get a Coder Job' is about. It's about getting to know these people who can advocate for you. Because otherwise it's hard. This problem, I do the 15-minute calls with podcast listeners and a lot of them are new and a lot of them are saying exactly this.

**JESSICA:&nbsp;** Mm. It's like people are hiring for CYA.

**CHUCK:&nbsp;** Yeah.

**JESSICA:** To cover their butts and just make sure that they can't get in trouble. And one way to override that is through networks because people aren't as afraid of hiring somebody who was recommended by somebody they trust.

**CHUCK:&nbsp;** Yup.

**SAM:&nbsp;** Which brings up that I think for those of us who are more experienced and maybe have a broader network, part of our responsibility as mentors and advocates is to make our networks available to people who need them.

**CORALINE:&nbsp;** Definitely.

**CHUCK:** The thing that's interesting about what you're saying though Sam, and I agree with you but I'm going to agree with you and point something out at the same time is that I'm not comfortable making my network available to just anybody. Which means I actually have to invest time in somebody, to get to know them well enough to be comfortable going to my friends and saying, “I know you're hiring and this person over here is a good fit for you even though they don't check all the boxes on your job listing.”

**SAM:&nbsp;** Oh yes, absolutely. And thank you for clarifying that. You do have to be able to make a meaningful recommendation both ways for that to work.

**CHUCK:&nbsp;** Yup.

**JESSICA:&nbsp;** [Pairing] people?

**SNUGGS:&nbsp;** That's where the autonomy and the altruism come all in the same basket.

**JESSICA:** It takes altruism to spend time with people.

**CHUCK:** Oh, absolutely.

**NOEL:&nbsp;** Yeah. Just to say how I started with Ra'Shaun, I think the initial time was a 'prove it' I guess, a probationary period where…

**SNUGGS:&nbsp;** [Laughs]

**NOEL:&nbsp;** I had to show that I wanted it. Not to say that he had me do some menial work like, “Are you kidding me?” But it was to say, it was awesome like 'Karate Kid', wipe on, wipe off type of situation. Wax on, wax off. Exactly.

[Laughter]

**NOEL:&nbsp;** Wax on, wax off situation where you're doing something so simple, so easy, and you're really not understanding or grasping why is my mentor having me do this? But I was a humble person. I've grown [to becoming] a humble person and being patient and listening very well to what he was trying to instill in me. So, it would be that type of approach I would say for anybody who is a little questioning of maybe wanting to bring somebody along but not knowing if they can trust them. It's seeing what level of dedication they have to the craft. How serious are they about this? I come from a bootcamp and it's sad to say that maybe a couple of people that I know personally, they lost some steam. They lost some… I mean, head-first going into it because of a lot of dejection they got from hiring managers and basically they gave up. And if they had a mentor or someone to support them but give them structure, it possibly could have been a different direction for them. But it was a time where I had questions like, “Is this a joke? Does he seriously consider me as someone to show some tutelage to?” But it was something to understand.

**JESSICA:&nbsp;** So, a big piece of being a mentor is finding the person to pair with. And yeah, as you point out, as Chuck points out, that's a time investment and a cost. And you want to makes sure it's worth it.

**CHUCK:&nbsp;** Yeah, but the thing is that if you're looking at it just strictly from a financial point of view, is it worth it? You can argue about that. But the payoff for me is seeing that I made a difference for somebody. And if…

**SNUGGS:&nbsp;** Absolutely.

**CHUCK:&nbsp;** If that's the payoff for you, then it's totally worth it to put the time in. That's something that I've learned over the last year, is as I reach out and help people be it by talking about things like this on Ruby Rogues or by sitting down one on one with somebody who just got out of a bootcamp and is trying to find a job, or going to the users groups and pair programming with somebody or whatever, and then seeing, “Hey, that made a difference.” That's the payoff. I go to the conferences and people tell me which episodes helped them get their dream job. And that's the payoff for me. And so, if it isn't something that will pay off for you, if that just doesn't get you up in the morning, there are other ways to contribute to the community that will. But I think a lot of us are people and people like to connect with other people and feel like they matter to other people. And this is a terrific way to do that.

**CORALINE:&nbsp;** So, on the topic of finding mentees and what I did, I mentor four young women right now. Two of them from a previous job and two of them from the intarwebs. I actually put up a survey. I put up a questionnaire and I ask questions about what they're looking for in a mentor, some questions about their work style, what their goals were, questions to try and get to know them better and try to align that with my values as a developer and what I think my strengths are as a mentor. And select people that I thought I could help the most and that I would be most successful in building a relationship with. Because mentorship is a trust relationship. And it's a commitment to someone else. And I don't think you can do that with a stranger. And I don't think you can do that in a one-off situation and call it mentorship.

**SNUGGS:&nbsp;** I have a question for Sam.

**SAM:&nbsp;** Yeah?

**SNUGGS:&nbsp;** Sam, do me a favor. Can you close your eyes, sir?

**SAM:&nbsp;** Okay.

**SNUGGS:&nbsp;** No peeking. Can you bring yourself back to the moment in your career when you were just really stuck between a rock and a hard place and whether it be development or just a moment in your career? And…

**SAM:&nbsp;** Gosh, which one?

**NOEL:&nbsp;** [Chuckles]

**SNUGGS:&nbsp;** As far back as you can go, sir. Well, the time when someone stepped up and it feels like they just popped up out of nowhere or even you sought them out. What was that feeling at that moment? Because you sort of are passing on the stone to whoever comes next. But then there's this notion of homage as well that you pay. Because we all learn and then pass it on with our iteration to the next. Can you put us sort of in your head, sir Malkovich? [Chuckles]

**SAM:&nbsp;** Well yeah, okay. So, there was a time around 2008 or so where I had gotten laid off from one position and sort of scrambled to find something else and wound up working in a part-time position that was really not a very good fit for me at all. And then I got laid off from that. And so, this was pretty hard. I also had a young child in the house and adjusting to being a new parent. And all of that was kind of difficult to deal with. And I wound up getting another job that was maybe not the most functional environment as well but it was still better than what I had before. And then I wound up talking to somebody who had been at that place before and was coming back to do a little bit of consulting. And I wound up having some conversations with that person about the environment that I was in where they were able to provide a lot more context about why things were the way that they were at this place. And that really helped me understand what was going on. I feel like it wasn't my fault. So, that was really useful. And then coincidentally they also happened to have a job come up available a couple of months later that I applied for. And that turned out to be one of the best jobs of my career. So yeah, was that what you were looking for?

**SNUGGS:&nbsp;** Absolutely. It's just… what it did was I was tying in the message that his eyes were still closed. Cool, he's feeling it. What you felt there, we can't forget that.

**SAM:&nbsp;** No, absolutely not.

**SNUGGS:** And can't forget it in action as well.

**JESSICA:&nbsp;** Yeah. Everybody that you think is a leader, there's somebody there who was there for them in a moment when they needed just that encouragement. Sometimes, especially starting a new job, I find about three or four months in there's usually this period of “I know nothing and I am useless.”

[Laughter]

**JESSICA:&nbsp;** [Inaudible]

**SAM:&nbsp;** I don't stop feeling that for the first six months.

**JESSICA:&nbsp;** Yeah. It takes a lot of time.

**CHUCK:&nbsp;** Even now when you're experienced, when you're an experienced person, right?

**JESSICA:&nbsp;** Yeah, yeah.

**SAM:&nbsp;** Every single new job. It's minimum three and sometimes up to six months before I feel like I have any clue what's going on.

**CORALINE:&nbsp;** GitHub is such a complicated culture and such a complicated system. Yeah, I'm feeling that right now with my job there. I'm only not quite two months in and there's so much to absorb.

**CHUCK:&nbsp;** Well, and I'm self-employed and I experience this myself. Where's the next chunk of money going to come from? Where is the next job going to come from? What am I going to do now? Should I change what I'm doing and try something different? Should I make contacts over here or should I go to this conference over there? And there's a lot of second guessing. And I have two groups of people that I talk to, mastermind groups, that provide this sort of thing here. So, what we're talking about with having people who can push us along the right way or help us make these connections or whatever it is, you think self-employed people have it all together and that's definitely not the case. And we need this too and we get it in those ways.

**JESSICA:&nbsp;** Just those little encouragements.

**CHUCK:&nbsp;** Yeah.

**JESSICA:&nbsp;** Of, “Hey, you're doing cool stuff.”

**CHUCK:** &nbsp; Yeah. Or even, “I have this expertise that you seem to lack. Let me help you with that.”

**JESSICA:&nbsp;** Mm. Yeah, like a couple of months ago when Snuggs helped me with CSS and HTML and I was like pulling my hair out. I was trying to learn Elm but I couldn't make a stupid page do fricking anything. How do you get that one thing next to the other thing? And an hour spent with someone who was not only knew what he was doing with CSS but had learned it recently enough to be excited about it still, that's the best.

**SNUGGS:&nbsp;** [Laughs]

**CHUCK:&nbsp;** Well, everybody does that with CSS.

[Laughter]

**SNUGGS:&nbsp;** Oh my goodness.

**SAM:&nbsp;** Guilty.

**SNUGGS:&nbsp;** Guilty as charged. Max, I want to say thank you too, sir, because actually 'Think and Grow Rich', that's one of the books that I keep in my repertoire. I consider it a lifetime book that I'll always go back and reference.

**CHUCK:&nbsp;** It's a great one.

**SNUGGS:&nbsp;** And I've read about the mastermind group but it was actually you probably earlier in a Rogues podcast, I think it was in the 100s where you were talking really heavy about the mastermind group. And I went out and started myself one as well. And I think now, I have multiple Slack channels but there are literally hundreds of people that I consider part of mastermind, extended mastermind. And it's an awesome thing to be able to have that support structure around you. That's no matter how long in the tooth your career is.

**CHUCK:&nbsp;** That is so true. And if you ever get into a mastermind group that works…

**SNUGGS:&nbsp;** Oh, yeah.

**CHUCK:&nbsp;** You'll never go back. You will start mastermind groups trying to recreate something that works if you can't find one that already exists.

**JESSICA:&nbsp;** Is that like a group of people who talk to each other or something? What is this thing?

**CHUCK:&nbsp;** So, in 'Think and Grow Rich' he explains that multiple people working on a problem or thinking about a problem is better than a single person working on a problem. And so, it's a mastermind in the sense that's multiple minds working on the same problem. But what really makes a mastermind group work is, and it varies from group to group as to the size. Most of the ones that I've seen usually range from about four to six unless they have a professional moderator that can take them to eight or 10. But anyway, what happens is everybody in the group is committed to the success of everybody in the group. And what that does is it creates an environment where I can come in and I can be completely honest. I can come in and say, “I totally screwed this up.” Of course, I tend to do that on the internet anyway. But…

**SNUGGS:&nbsp;** [Chuckles]

**CHUCK:&nbsp;** I totally screwed this up. I got it wrong or I'm struggling with this or my kids are going to starve to death because I can't get this right. And it doesn't matter what I've done. I've got this group of people that I can talk to. And they will work, they'll do whatever it takes, for my success. And I in turn will do whatever it takes to help them succeed. And so, it's not just a group of people you get together and talk to. It's a group of people who are invested in each other and are willing to do, like I said, whatever it takes to make everybody in the group succeed. So, even though we're not all doing the same business, we're not all working on the same projects, in the end at least for the hour or two or sometimes outside of the group if we need help, we can get together with the people who can help us along. And that can be an encouragement. It can be help. It can just be knowing that somebody's there. I've been in mastermind groups…

**JESSICA:&nbsp;** Are you sharing your network?

**CHUCK:&nbsp;** Yeah. I've been in mastermind groups where somebody was trying to quit an addiction. Smoking, other things, pornography. Some people were trying to quit looking at pornography for personal reasons. So, just the fact that it's like, “Look, if you get tempted at 2am, call me.” It's important to you. It doesn't matter what I feel about it. It's important to you so call me. If you're thinking about going and getting that drink, call me. And just having that lifeline for those things is important. But then also, yes. I need help with WordPress. And it's, “Oh, well I know a WordPress person,” and they hook you up. Or, I'm trying to find work and they happen to know people who are looking for people to hire. Or, whatever. And so, it can extend to your network and it can extend to your skills. It can extend to your outlook on particular things. Any of those things are fair game. And everybody is willing to share.

**JESSICA:&nbsp;** There's some community.

**CHUCK:&nbsp;** Yeah.

**JESSICA:&nbsp;** It's a very deliberate community.

**SNUGGS:&nbsp;** What I'd like to make sure we emphasize on is there's this notion of homage and also the ability to pass on the torch. So for instance, homage. My mentor, his name's Tom Mornini actually, who I highly recommend [inaudible] that he will be a great interview for Ruby Rogues. But you may know him. He founded Engine Yard. I'm sure we all have heard of that. We've been [around] long enough. But Tom and I, we paired as frequently as we possibly can, oftentimes on a daily basis. It's ironic our engagement. He doesn't accept cash when he works on projects. He only accepts Bitcoin. But that's [chuckles] another story. But to see my mentor, actually to learn from him and even be in situation where, to employ him, give him projects as well. So, it really is full circle when I see Noel and Tom pairing together. And I jump on a hangout with them for a Pomodoro. Oh man, it just warms my heart. It's like seeing the person who is your protégé conversing with your mentor and the banter between that. It's a surreal feeling.

**NOEL:&nbsp;** Yep. So, nice closing right there. That's another Pomodoro close right there, people. So, as Jessica said, what have we learned?

**SNUGGS:&nbsp;** I learned that when I asked Sam to close his eyes, he actually closes them and goes back in time. [Chuckles]

**JESSICA:&nbsp;** Yeah, thanks Sam for that story. What I learned from your story and then the conversation that followed was that while mentorship is an ongoing commitment, we can still help in little mini ways by giving each other encouragement, telling people they did something good, and also sharing skills in one-time increments. You can make a big difference to someone doing that. And who knows? You might just run into someone that you want to mentor who will mentor you.

**CORALINE:&nbsp;** I learned about mastermind groups, which is pretty cool.

**JESSICA:&nbsp;** Yeah.

**NOEL:&nbsp;** Well, I learned about Sam's experience with that job which as very enlightening from a person just coming into his.

**SNUGGS:** Chuck?

**CHUCK:&nbsp;** So for me, it was kind of a reminder, not necessarily something that I learned but something that I had forgotten and relearned. And that is that no matter where you are on this journey, as Jessica and Sam and Coraline all pointed out, there are hard things to learn even for people who have been doing this for a long time. And so, when it gets really rough, when it gets really hard and I'm thinking, “Oh man, I'm the only person that deals with this. I'm supposed to be the expert because I'm the guy on Ruby Rogues,” and I haven't a clue what I'm doing, that's just not true. That even experienced people run into problems that they don't know offhand how to solve. And sometimes it's hard. And in those situations there are a lot of ways to handle that.

**SNUGGS:** Well, the best part about that Chuck is you have a new person on your mastermind group who is willing to be a sounding board to you. And that's myself.

**CHUCK:** Awesome. I appreciate that.

**NOEL:&nbsp;** Yeah.

**SNUGGS:&nbsp;** See, and I think that's good for what we learned where. I definitely learned one other thing that I wanted to make a note to, I learned that it's validation in what I've been doing in my life. This isn't just my career. I've actually taken a vow in my life on this path and mentorship and development. Not even, this is past development. Recently, I don't know how personal it is, but I've actually taken a vow of celibacy and also that includes marriage and childbirth. And maybe I see more in the future of some interesting things scientifically. But at least for now, you can only speak for right now or what's been done in the past, I've been on this journey for about 33 months now. And it's because that's where I get my 25<sup>th</sup> hour in the day. And I often tell people that made the insecurity sometimes come out. Anyone that knows me knows that I love children. And I love the construct of being with someone for an entire life. However, that's what works for other people. What works for me is to non-stop give of myself to myself and to others. I have a pairing session that's going to be at 1am in the morning because [chuckles] of someone's time constraint. But it's life for me. It's not just a career. If there's anything that someone can take away from that, that they know a new thing about myself.

**CHUCK:&nbsp;** Very cool. Well, I have about 10 minutes before my next podcast so I'm going to push us to picks.

**SNUGGS:&nbsp;** Awesome.

**CHUCK:&nbsp;** Sam, do you want to start us off with picks?

**SAM:&nbsp;** Sure. I just got one quick one today. Snuggs mentioned in the pre-call that he likes reading RFCs which reminded me that I really have only ever read one of them in any depth whatsoever and that's RFC 2119. And this is a document that gives precise definitions to the phrases 'must', 'must not', 'required', 'shall', 'shall not', 'should', 'should not', 'recommended', 'may', and 'optional' in such a way that you can indicate levels of what is required and what is maybe just a really good idea. So, I constantly come back to that especially when I find myself typing should or must not in all caps.

**SNUGGS:&nbsp;** The real question is do you use all caps? Oh gah, you caught me. He's faster than a New Yorker.

[Laughter]

**CHUCK:&nbsp;** Alright. Jessica, what are your picks?

**JESSICA:&nbsp;** I don't have any picks today.

**CHUCK:&nbsp;** Okay. Coraline, what are your picks?

**CORALINE:&nbsp;** I've got a couple of picks. They're related and they are related to mentorship in away. My first pick is a talk by James Edward Gray, our very own James Edward Gray, from RailsConf called 'Implementing the Large Hadron Collider on a Whiteboard'. It is a talk that is about technical interviews. And sort of a survival guide for technical interviews. He covers basics of big O notation and some of the other core concepts that I think unfortunately a lot of interviewers still rely on. But he is coming from the perspective of someone who conducts technical interviews for a company that really values the CS skills. And so, he had a lot of tips on how to navigate those and how to prepare for those. Very practical talk and I think it could be help to a lot of people.

In that talk he references a book which is my second pick called 'Cracking the Coding Interview' by a person named Gayle McDowell. The book bas almost 200 programming exercises or programming questions like, “Oh, how do you work with a binary tree? How do you invert a binary tree? How do you solve the sorting question?” and walks you through the solutions. Unfortunately the book's in Java but the code is pretty readable. And it's a way of preparing for coding interviews as well. And I've actually used this book in a mentoring situation with someone who wanted to focus on developing their technical skills. We actually take one of the questions per pairing session and work through it together so that she gets a better sense of how to implement some of these classic programming challenges and feels better about her job prospects. So, that is my second pick and that is it.

**CHUCK:&nbsp;** Alright. I've got a quick pick here. I'm trying to think of how to put it because I've talked about this before on the show. But anyway, I've had this refocusing on my health. And so, there are a few things that I've picked up that I'm trying to do better with. And one of them is just walking every day. So, I've been trying to walk for an hour every day. Related to that is have 10,000 steps every day. And I got a FitBit One to do that with and that's been really nice just to be able to do that with. My Pebble Time Watch does fitness tracking but I found that it's not as accurate. So anyway, I've switched over and I'm pretty happy with that. So yeah, so I'm just going to pick thinking about your health and the FitBit One.

Ra'Shaun, Snuggs.

**SNUGGS:&nbsp;** Yes, sir Charles.

**CHUCK:&nbsp;** What are your picks?

**SNUGGS:&nbsp;** My picks are I would say Block & Flow app that is [www.BlockAndFlowApp.com](https://www.BlockAndFlowApp.com/). Shameless self-promotion but it's a Pomodoro app. It's actually better suited to look it up on iTunes. You look up Block & Flow app. And it keeps me focused. It keeps me from spending eight hours reading RFCs and writing code for 20 minutes. Trying to reverse that a little bit [chuckles].

And my second pick I would have to say is Censible. That's actually a project that I'm working on now. I'm the Chief Technology Officer of the company. Noel is a lead developer on the project. And deals with socially responsible investments. That's C-E-N-S-I-B-L-E dot co. And so essentially it's [inaudible] and butter. So, the people who would go into a restaurant and say, “I only go here because they have recyclable napkins” might actually, and once you're [inaudible] want to invest in said restaurant or invest in Tesla stock as opposed to putting a thousand dollars down to be on a layaway wait list. So, Censible.co. It allows people to really be mindful in their investments. And those are my picks.

**CHUCK:&nbsp;** Alright. Noel, what are your picks?

**NOEL:&nbsp;** Oh, I get picks. Awesome.

**CHUCK:** Heck, yeah.

**NOEL:&nbsp;** [Chuckles] So, I believe I have two picks. One is a more development standpoint. Heroku Pipelines. If anybody has ever had the pain of having to duplicate code in multiple repositories and then push that to multiple applications or hosting sites, it really does ease that pain in the sense of just having one repository, whether it be in GitHub, Bitbucket, wherever you like. And just having that replicate on multiple applications that are [ephemeral] in that standpoint as Heroku Pipelines allows you to have a workflow through your environments and see seamless actions and allow stakeholders to review features or topic, pull requests or [inaudible] in the application format before pushing it to staging and furthermore into production. That's my first pick.

And my second pick was a conversation, I'll send a link. It is a dialogue so to speak and it takes into account, I haven't fully finished it but I really do think it's insightful in the aspect of understanding conversation. And knowing the difference between dialogue and discussion and being able to listen and talk with the person without trying to control the conversation.

**CHUCK:&nbsp;** Alright. Well, if people want to follow up with either of you, see what you're doing, follow you on Twitter, what are the best places to do that?

**NOEL:&nbsp;** Okay. So, on Twitter my handle is Mr, M-R, bernnz, B-E-R-N-N-Z. And I think I replicate that across a lot of other sites. Facebook, Instagram. I'm not often on that stuff, but I do follow a lot of other people. So, that's where you can find me.

**SNUGGS:&nbsp;** And myself, you can find me at S-N-U-G-G-S-I, snuggsi on Twitter and Instagram and Facebook. I'm going to have to find that person who's got snuggs without the I, Charles. I'm going to have to block them.

[Laughter]

**SNUGGS:&nbsp;** [Inaudible]

**CHUCK:&nbsp;** Alright.

**SNUGGS:&nbsp;** Thanks so much, gang. This has really been an honor to me and it's, this year has been so humbling for me. The meetup that introduced me into the community, I actually am the event organizer for that meetup as of this year. And the podcast that I've been telling people for years is the number one podcast in Ruby, I am actually on said podcast right now. You have no idea how much this podcast has helped myself and my career throughout the years. So, just paying a little homage to Ruby Rogues.

**CHUCK:&nbsp;** I love… I have to say, I love hearing that. Because we talked about it before, but that's the payoff right there. We made a difference for somebody. And now you're making a difference for other people.

**SNUGGS:&nbsp;** Exactly.

**JESSICA:&nbsp;** Yeah, this has been a really interesting episode.

**CHUCK:&nbsp;** Yup.

**JESSICA:&nbsp;** Not the standard. So, thank you for that.

**SNUGGS:&nbsp;** Yeah. Awesome. Two thumbs up. You never know what you're going to get with me, right Jessica? [Laughs]

**JESSICA:&nbsp;** You're probably going to get Pomodoros.

**SNUGGS:&nbsp;** That's right. Hashtag facts.

**CHUCK:&nbsp;** Alright. Well, I've got to jump off and get ready for the next show. So…

**JESSICA:&nbsp;** Bye everybody.

**CHUCK:&nbsp;** We'll go ahead and sign off and we'll catch you all next week.

**_[Bandwidth for this segment is provided by CacheFly, the world's fastest CDN. Deliver your content fast with CacheFly. Visit C-A-C-H-E-F-L-Y dot com to learn more.]_**

**_[Would you like to join a conversation with the Rogues and their guests? Want to support the show? We have a forum that allows you to join the conversation and support the show at the same time. You can sign up at RubyRogues.com/Parley.]_**
