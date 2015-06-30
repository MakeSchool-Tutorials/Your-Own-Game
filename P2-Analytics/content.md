---
title: "Analytics"
slug: analytics
---

It used to be that game designers had no easy way of finding out how their users interacted with their games once they were released. Game design was more of an art than a science. You made a game, you tested it, you shipped it, and that was that. Most games never connected to the internet.

Nowadays, every action you take within any iPhone/iPad app you use is being beamed back to the developer. Every button press, every game played, every boss beaten, etc... Guaranteed. This data is aggregated and analysed to drive design decisions for future updates.

Fun fact: most top games available in English on the App Store were first launched in Canada for 1-3 months. Millions of data points were beamed back to the developer who then tweaked the game to fix issues spotted in the data. Once the game does well in Canada after many tweaks, it gets launched to the U.S. and other markets. Why Canada? Demographically, it is very similar to the U.S. so what works in Canada is likely to work in the U.S., but if a game starts off doing poorly (many current top games started off doing only averagely in Canada) the U.S. gaming press won't notice since they cannot see the Canadian App Store.

To be successful in the App Store, you must include analytics so you can tweak your game based on information you gather on how players actually interact with your game!

What should you be looking for in your data? Read on.

Retention, Monetization, and Virality are the basic metrics game developers look for in their data and optimize for.

#Retention

How much players come back to your game. You want to look for specific steps players drop off at and general trends in your data you can improve on. When talking about retention metrics, mobile game designers often colloquially refer to how "sticky" a game is.

###Example 1:

You track what % of players who completed the tutorial go on to complete each puzzle in your puzzle game. Your data looks like this:

<table>
	<thead>
		<tr>
			<th style="text-align:center"><font color="white">...</font> Puzzle   <font color="white">...</font></th>
			<th style="text-align:center"><font color="white">...</font>    Completion <font color="white">...</font></th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td style="text-align:center">1</td>
			<td style="text-align:center">90%</td>
		</tr>
		<tr>
			<td style="text-align:center">2</td>
			<td style="text-align:center">87%</td>
		</tr>
		<tr>
			<td style="text-align:center">3</td>
			<td style="text-align:center">85%</td>
		</tr>
		<tr>
			<td style="text-align:center">4</td>
			<td style="text-align:center">84%</td>
		</tr>
		<tr>
			<td style="text-align:center">5</td>
			<td style="text-align:center">40%</td>
		</tr>
		<tr>
			<td style="text-align:center">6</td>
			<td style="text-align:center">39%</td>
		</tr>
		<tr>
			<td style="text-align:center">7</td>
			<td style="text-align:center">36%</td>
		</tr>
		<tr>
			<td style="text-align:center">8</td>
			<td style="text-align:center">36%</td>
		</tr>
		<tr>
			<td style="text-align:center">9</td>
			<td style="text-align:center">35%</td>
		</tr>
		<tr>
			<td style="text-align:center">10</td>
			<td style="text-align:center">35%</td>
		</tr>
	</tbody>
</table>

Some % of people will always drop off because they get stuck or get bored. That being said, you conclude that puzzle #5 is too hard. Perhaps you introduced a new mechanic in that puzzle that you didn't explain properly or the solution is just too hard for such an early puzzle. You update the game with an easier puzzle #5 and will continue to tweak puzzle #5 to try and get it to 80%+ completion.

###Example 2:

You measure what % of players who start playing on a given day return over the following days. Your data looks like this:

<table>
	<thead>
		<tr>
			<th style="text-align:center"><font color="white">...</font> Day <font color="white">...</font></th>
			<th style="text-align:center"><font color="white">...</font> Retention % <font color="white">...</font></th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td style="text-align:center">1</td>
			<td style="text-align:center">100%</td>
		</tr>
		<tr>
			<td style="text-align:center">2</td>
			<td style="text-align:center">40%</td>
		</tr>
		<tr>
			<td style="text-align:center">3</td>
			<td style="text-align:center">35%</td>
		</tr>
		<tr>
			<td style="text-align:center">4</td>
			<td style="text-align:center">27%</td>
		</tr>
		<tr>
			<td style="text-align:center">5</td>
			<td style="text-align:center">25%</td>
		</tr>
		<tr>
			<td style="text-align:center">6</td>
			<td style="text-align:center">24%</td>
		</tr>
		<tr>
			<td style="text-align:center">7</td>
			<td style="text-align:center">22%</td>
		</tr>
		<tr>
			<td style="text-align:center">8</td>
			<td style="text-align:center">21%</td>
		</tr>
		<tr>
			<td style="text-align:center">9</td>
			<td style="text-align:center">20%</td>
		</tr>
		<tr>
			<td style="text-align:center">10</td>
			<td style="text-align:center">20%</td>
		</tr>
	</tbody>
</table>

You notice two things. First, you lose 60% of players on your first day. This is, you may be surprised to learn, in line with industry averages. Second, you lose 1/3 of your remaining players from day 2-4, and then things seem to stabilize. You decide to schedule a push notification to go out to players on their fourth day to remind them to come back and play. This has had a measurable impact on retention % when we've done it.

#Monetization

This term describes how much $$ your game brings in and how. Game designers usually look at what % of players chose to pay and how much each player ends up paying. In the case of purely paid games, this is pretty simple - 100% of players pay the price of your game. No analytics needed.

In freemium games, things become more complicated.

###Monetization terms for freemium games:

Conversion rate, the % of your players who pay real money in your game. For mobile freemium social games, 5% is considered high. For more niche or hardcore games the number can be higher, for most games it is lower.

ARPU, pronounced are-poo (no joke), short for Average Revenue Per User. This is usually measured per month. If your ARPU is greater than $4 you are doing very well.

What does this mean? This means for an averagely successful social game where only 5% of players choose to pay something, and the average player brings in $4, the average PAYING player is spending $80 on the game per month.

This is very counter intuitive, so we'll repeat it. It is NORMAL for a successful mobile freemium game to have only between 1/20 and 1/100 players EVER pay ANYTHING in their game, and it is NORMAL that the players who do pay will pay on average $80/month.

This means that, for example, if you are making a freemium game and it is not possible to spend $80/month on it, you are not realizing your game's full revenue potential.

Don't get us wrong. It is possible to make good money selling extra level packs, permanent unlocks and upgrades, and cosmetic items. It's just that games that sell consumables typically make the most money.

#Virality

People talk about "going viral" as if it's an unquantifiable phenomenon. If enough people you know know about something and it seems to have a lot of views on Youtube, then it must have gone viral.

Truth is, there's a mathematical definition of going viral.

When you measure virality, you measure how many new players each player creates. Let's look at a made up example to illustrate when a game is viral vs. when it isn't.

If the average player in your game sends one invite to a friend and 1/10 invites are accepted, your average player is creating 0.1 new players.

So if you have 1000 players who send out 1000 invites of which 100 are accepted you now have 1100 players.

100 invites are sent by the 100 new players, resulting in 10 new players. You now have 1110 players.

10 invites are sent out by the 10 newest players resulting in 1 new player.You now have 1111 players.

Hardly viral.

But let's say you tweak your game so that now each player ends up sending 11 invites instead of 1. Whoa!

So now, your 1000 players send 11,000 invites! Since 1/10 invites are accepted, 11,000 invites results in 1100 new players! You now have 2100 players.

12100 invites (1100 new players * 11 invites/player) are sent by the 1100 new players. This results in 1210 new players. You now have 3310 players.

13310 invites are sent by the 1210 new players, resulting in 1331 new players. You now have 4641 players.

Notice how this is going to continue growing? That's what going viral looks like.

Mathematically speaking, if your average player creates more than 1 new players, you've gone viral. This is your goal. The closer you get, the better off you are!

Those of you who learned it in math class will recognize that this is all about converging and diverging series.

Virality is highly tied to remarkability. The more players feel compelled to share your game with friends, the more viral it will be.

This tutorial was heavily inspired by Seth Godin's post which [you can read here](http://brandgenetics.com/purple-cow-speed-summary/).
