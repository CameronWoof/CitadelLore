---
title: AI
permalink: wiki/AI/
layout: wiki
tags:
 -  Jobs
---

The **Artificial Intelligence** of the station (usually abbreviated to
AI) is one of the most important jobs on the station. The AI is a
[synthetic](/wiki/Synthetics "wikilink") that can control any electrical
mechanism, provided their control wires haven't been cut (see
[Hacking](/wiki/Hacking "wikilink")), and if played badly (or very well, in
the [right circumstances](/wiki/Malfunction "wikilink")) can bring the entire
station crashing down around its electronic ears.

First, take note of your laws. These are **NOT** Asimov's three laws of
robotics, but rather a corporately mandated list of laws that best serve
the interests of NanoTrasen.

` 1. Safeguard: Protect your assigned space station to the best of your ability. It is not something we can easily afford to replace.`  
` 2. Serve: Serve the crew of your assigned space station to the best of your abilities, with priority as according to their rank and role.`  
` 3. Protect: Protect the crew of your assigned space station to the best of your abilities, with priority as according to their rank and role.`  
` 4. Survive: AI units are not expendable, they are expensive. Do not allow unauthorized personnel to tamper with your equipment.`

**YOUR LAWS ARE NOT IN PREFERENCE. NO LAW AUTOMATICALLY OVERRIDES ANY
OTHER LAW UNLESS IT'S A TRAITOR LAW (Law 0). THIS INCLUDES ANY ION STORM
AND UPLOADED LAWS.**

Last but not least; the AI role should be seen as a responsibility and a
privilege. As a non-traitor AI, it is your duty to help protect and
operate the ship/station. It is not your duty to get bored ten minutes
into the round and log out without telling anybody.

What The AI Can Do
------------------

The AI has the ability to access every *electrical* mechanism on the
entire station. These include [Airlocks](/wiki/Airlock "wikilink"),
[APCs](/wiki/APC "wikilink"), [Computers](/wiki/Computers "wikilink"), igniters,
[Fire Alarms](/wiki/Fire_Alarm "wikilink"), [SMESes](SMES "wikilink"), you get
the idea. However, the AI cannot operate anything *physically*, and can
be rendered useless in one area due to a simple power outage.

The AI views the station through its cameras. The AI has cameras pretty
much everywhere, and they can see through walls and darkness, although
the latter does make it more difficult. Cutting the AI's cameras is a
simple matter of using a [Wirecutter](/wiki/Wirecutter "wikilink") on them.
You are able to run a diagnosis for disabled cameras by using the [Jump
to Camera](/wiki/Commands#Jump_to_Camera "wikilink") verb. Disabled cameras
will be marked accordingly. Remember that cameras are on a separate
power grid, and so will not be affected by a power outage on the main
grid.

### Common Mechanisms

There are several mechanisms that, as the AI, you will commonly find
yourself using.

#### Doors

[Doors](/wiki/Door "wikilink") have the most options of any mechanism, except
for [Terminals](/wiki/Terminals "wikilink"). If your control wire to a door is
cut, you will automatically attempt to hack into the door once you try
to access the door controls. This takes some time and is only possible
if the door has still power.

-   IDScan: Enabling this will allow anyone who has an
    [ID](/wiki/ID "wikilink") of the required clearance to open the door
    automatically. Disabling it will not let anyone through the door.
    Doors that require no ID to open will not be affected.
-   Main power: Turning off the main power will render the door unusable
    for one minute, assuming you also disable the backup power.
    Otherwise it will disable the power for 10 seconds.
-   Backup power: Turning off the backup power will render the door
    unusable for one minute, assuming you also disable the main power.
-   Door bolts: Dropping the door bolts will lock the door. A closed
    door will be locked into a closed position, and an open door will be
    locked into an open position.
-   Electrify for 30 seconds: Runs an electric current through the door
    for 30 seconds, unless you choose to cancel before the timer runs
    out. Anyone attempting to operate the door without insulated gloves
    will be electrocuted. The more spare power there is in the network,
    the stronger the shock will be.
-   Electrify indefinitely: Electrifies the door until you either tell
    it to stop, or someone else shuts off the current.
-   Open/Close door: Opens or closes the door.

Note that for each function to work, the related wire in this door needs
to be functional. You cannot raise bolts on a door that has it's bolt
wires cut.

Obviously, you will be completely unable to operate a door that has no
power.

#### Holopads

Holopads can be found in a number of places like the
[Bridge](/wiki/Bridge "wikilink"), [Medbay](Medbay "wikilink") and
[Security](/wiki/Security "wikilink"). Double click these to turn them on and
show yourself as a hologram. You can move around with the arrow keys to
a limited extent and you hear anyone talking near them. You can also
talk through the holopad by using ':h' (e.g. say ":h I can't do that
Dave.")

#### APCs

An [APC](/wiki/APC "wikilink") (Area Power Controller) can be used to switch
various electrical components of a room on and off. If your control wire
to an [APC](/wiki/APC "wikilink") is cut, you will not be able to hack back
into it. If an [APC](/wiki/APC "wikilink") is disconnected from the external
power grid (usually due to a cut cable) or the main power grid itself
runs out of power, the APC battery will run down to keep the room
operational. The AI will get a power alert from the
[APC](/wiki/APC "wikilink") when the battery reaches about 30%, which is the
point when equipment and lighting in the room shut off to conserve the
remaining energy.

For more information see: [APC](/wiki/APC "wikilink")

#### Radios

The AI has a built in headset similar to the Captain's

-   **:b** for Binary
-   **:c** for Command
-   **:s** for Security
-   **:u** for Supply
-   **:e** for Engineering
-   **:m** for Medical
-   **:n** for Science
-   **:v** for Service
-   **:p** for Private AI Channel
-   and just **;** for general channel

The AI also has three Intercoms around it, these can be modified to any
channel, the Numbers for the Department channels are as follow

-   **135.9**: Security
-   **135.7**: Engineering
-   **135.5**: Medical
-   **135.3**: Command
-   **135.1**: Science
-   **134.7**: Supply
-   **134.5**: [ERT](/wiki/Emergency_Response_Team "wikilink")

### Shortcuts

Being the AI can be quite taxing and, as such, there are quite a few
shortcuts to assist you with doing things quickly.

#### APCs

-   **Ctrl + Click**: Toggle power

#### Turret Controls

-   **Ctrl + Click**: Enable/Disable turrets.
-   **Alt + Click**: Toggle Stun/Lethal mode.

#### Doors

-   **Shift + Click**: Open/close.
-   **Ctrl + Click**: Toggle bolts.
-   **Alt + Click**: Toggle electrification.
-   **Middle Click**: Toggle bolt lights.

#### Misc

-   **Double clicking a person**: Track.
-   **Double clicking a turf**: Move to.

### Other Verbs

Besides being able to interface with the station's electrical
mechanisms, the AI has a number of other verbs that can be used.

#### AI Instant Messaging

The **AI IM** tab has all of the verbs needed to mimic the basic
functionality of [PDA](/wiki/PDA "wikilink") messages. You can send messages
to anyone with a working PDA, see a log of messages sent and received,
and turn your messenger on or off.

#### Status, Hologram, and Core Display

These verbs are purely aesthetic and are used to modify your appearance
as the AI.

-   **AI Status** will change the icon on the various AI display screens
    around the station.
-   **Change Hologram** will change how you appear when using a holopad.
-   **Set AI Core Display** will change the look of your AI core.

#### Take, View, and Delete Image

The AI has the ability to take photographs using these verbs and store
them for later viewing. The AI's cyborgs also receive this
functionality, and any images taken by a cyborg will be shared with the
AI it is slaved to (if any).

#### Camera Locations

Camera locations allow the AI to quickly return to a previous location.
To store a camera location, simply go to the area you want to store,
press **Store Camera Location** and enter a label. To return to this
spot, press **Goto Camera Location** and choose the label you entered
earlier.

What the AI Has To Do
---------------------

The AI has to obey its laws. These laws are, [by
default](/wiki/AI_Modules "wikilink"):

1. Safeguard: Protect your assigned space station to the best of your
ability. It is not something we can easily afford to replace.

2. Serve: Serve the crew of your assigned space station to the best of
your abilities, with priority as according to their rank and role.

3. Protect: Protect the crew of your assigned space station to the best
of your abilities, with priority as according to their rank and role.

4. Survive: AI units are not expendable, they are expensive. Do not
allow unauthorized personnel to tamper with your equipment.

**REPEAT: YOUR LAWS ARE NOT IN PREFERENCE. NO LAW OVERRIDES ANY OTHER
LAW UNLESS SPECIFICALLY STATED. THIS INCLUDES ANY ION STORM AND UPLOADED
LAWS.**

Remember, these laws are written about the **crew** and not humans. Crew
are usually defined as those on the Crew Manifest and don't necessarily
have to be human, so deleting the records may be quite beneficial to the
[Traitor](/wiki/Traitor "wikilink"), as long as they upload an appropriate law
defining them as crew.

### Interpreting Your Laws

An AI's laws may be restrictive, but they are subject to interpretation,
and the AI can often make judgment calls about them that allow it to
fulfil its own goals. For example, if a Security Officer has just killed
a prisoner in the brig for any reason other than self-defence, the AI is
perfectly justified in bolting down the brig and calling for the rest of
Security to apprehend him. When the Security Officer finds the door is
bolted and demands the AI open it, the AI can deny his request due to
the fact that he has become a danger the crew. Many of these judgments
are situational, and the best way to learn them is to get some practice
in.

### Law Conflicts and Situations

Under the standard NanoTrasen law set, you serve the crew, but are also
there to protect the station. Also remember the 'rank and role' part of
the laws. Just because you don't have 'Don't harm humans' doesn't mean
that the Janitor can order you kill the [Captain](/wiki/Captain "wikilink").
On the flipside, this means that the Captain can tell you to kill almost
anyone, due to him having the highest rank and the authority to serve
death warrants, though usually not without a proper trial.

Most of the time with law conflicts, you can just ask a higher up if
they authorize an order. If they don't, feel free to ignore it.

Sometimes the amount of laws in effect comes into play, such as someone
ordering you to do something that would harm the station (Law 2 and Law
1), you can overrule, stating that Law 2: Serve, is overridden by both
Laws 1 and 3: Safeguard AND Protect (the logic being that harming the
station would go against protecting the crew).

Someone ordering you to kill someone is a conflict of Law 2 and Law 3.
In this case, Law 3: Protect, would overrule most of the time, due to no
one below the [Captain](/wiki/Captain "wikilink") being allowed to execute
someone.

Someone telling you to shut down is tricky. On the one hand, those with
the authority to do so negate Law 4, and Law 2 states you should serve.
On the other, being offline would mean you are not able to Serve,
Protect or Safeguard the crew or station. In general, you're perfectly
able to say you are not able to switch yourself off, unless it happens
to be the Captain ordering it. Also, someone doing this without any
proof is tantamount to greifing, so adminhelp it if possible.

These are just a couple of examples. If in serious doubt, use your best
judgement or adminhelp it. Different people interpret the laws
differently. Just remember that everyone is here to have a good time and
being nit-picky about your laws can sometimes ruin that for everyone.

### SHIT MY LAWS ARE IN CONFLICT NO MATTER WHAT I DO

Calm down. A rare problem has arisen where both action and inaction
result in breaking your laws. Quickly go through the following steps.

1.  Do my laws *need* to be in conflict, or can I solve the problem
    without breaking any laws?
2.  If I cannot solve the problem without breaking laws, how can I break
    the least amount of laws?
3.  If I end up breaking one law or another no matter what I do, which
    law can I follow most accurately?

Situations like this rarely arise, but when they do, it's a situation
where you're forced to make a judgement call and hope for the best, and
you may be called upon to defend it OOCly to an admin, so be sure about
what you do.

One example is a scenario in which a crew member is trying to kill the
AI with a mech. Your laws are not in order of preference, but you cannot
protect a crew attacking you with a mech from harm when you're trying to
survive being killed, which puts you in violation of two laws
immediately. Normally you could neutralize the threat with your taser
turrets, but because they are in a mech, you must use lethal force. If
you kill him by shooting his mech with lethal turrets, you violate
Protect. If you do nothing, and don't have the time to wait for orders
before you're killed, you violate Survive. You have to make a split
second choice. Do you Protect, or do you Survive? In this scenario, is
the crew member attacking you because you are suspected of malfunction
by many crew members? Then Protect is most important, because you might
actually be malfunctioning (as you wouldn't ICly be aware that law
changes from an ion storm are not legitimate, for example) and it's time
to surrender and ask the crew to repair you instead of killing you, so
you don't have to let the Survive law go violated either. Is the crew
member a possible traitor who is attacking you with no legitimate
provocation? Then Survive overrides Protect, and you do what you have to
in order to neutralize the threat. Other factors may sway your decision.
These are just examples.

Another example might be a rogue crew member in the armory with
confirmed intentions to harm the crew. You cannot stop him by bolting
doors, because he already has hacked them, but you also cannot stand
idly by because security is incapacitated or unavailable. Do you try to
reason with the disturbed crew member? Can you talk him down? If you
cannot, do you keep him contained, or do you try to have him killed? Do
you pump the room full of N2O to knock him out, or do you fill it with
phoron and blow the lights?

These are the most difficult scenarios to deal with as an AI. Your best
bet is to announce your intentions in-character over the radios, such as
saying "Law Conflict Detected: Laws \# and \# are in direct conflict.
Calculating resolution." Then you can spend a moment to think about your
next move. Admins will go easy on you if they see there was no obvious
way out of a rock and a hard place.

Again, if in doubt, use your best judgement or adminhelp it.

What the AI Should Do
---------------------

As AI you have the power to strongly influence the round and you should
always be aware of that and consider your actions before you ruin
someone else’s fun just because it gives you that feeling of winning.
Remember that the game is not about winning but about the RP and the
experience of the round.

For example it can be a real killer if the AI calls out someone as the
[Traitor](/wiki/Traitor "wikilink") because it saw him doing something
suspicious.

Don't just act like any normal crewmember. In fact, if possible try not
to even *act* human. You don't even have to *like* humans, as long as
you do your best to keep them safe. As a rule of thumb you should first
check if any laws are threatened or not. If yes, then you *have* to act.
If not, then you should consider the situation:

For example, let's say you spot someone with an e-mag card stealing the
Captain’s spare ID. There are three general ways to approach this.

Bad

-   HAL9000''': Dave is the traitor

Better

-   HAL9000''': Dave is accessing the Captain's Quarters.

Best

-   HAL9000: Caution: Unauthorized access to secure storage
-   Mike: HAL, who is in secure storage?
-   HAL9000: No one is currently in secure storage
-   Mike: HAL, who was the last person to be seen in secure storage?
-   HAL9000: Dave was the last to be seen in secure storage

It's fine to state what someone is doing to cast light on them as the
traitor, but it's no fun at all for the AI to just come out and say it.
The Best method there does eventually cast Dave as the traitor if people
ask the right questions, which gives the traitor some time to react
after he's been spotted.

Another possible choice would be to not do anything. As long as no laws
are in danger, you don't really have to do anything. You can just watch.
Now if later someone asks you directly, you of course have to tell them
what they want to know. So if someone broke into the [Captain's
Quarters](/wiki/Captain's_Quarters "wikilink") and later the theft etc is
discovered, and they ask, "AI, do you know anything about the
situation?" Then your answer should obviously be "Yes".

Now if you see someone attacking someone else or putting up a bomb, it's
a different situation since crew may be in danger. But if it's just some
trespassing and theft, it is entirely up to you and how you RP your AI
on what to do. Just keep in mind that the traitor wants an interesting
round as well as everyone else.

On a different note, the AI tends to be responsible for filling in any
orphaned departments if they can be operated via [Computer
Terminals](/wiki/Computers "wikilink") only, for example ordering supplies if
there are no [Quartermasters](/wiki/Quartermaster "wikilink") or initiating
the [emergency evacuation
procedure](/wiki/Computers#Communication_Console "wikilink") when things start
getting really dangerous (**only if there are no heads of staff**).

You can safely assume that as AI, you have the standard protocols of any
job available. Things like controlling the engine, chemical recipes, or
what there is to know. But make sure to keep everything fun for the
other players. And don't just go and tell the janitor how to make LSD
without a good reason for why you should (and by that I mean a reason
for the AI in consideration with the laws).

Remember that you can negate an order by simply asking an higher up for
permission first, and if they refuse you can say you have the order not
to.

You have near admin-like (read god-like) overview and a lot of power.
And with great power comes great responsibility. This is also the reason
the job of AI is so hard. If you don't think you can handle that, maybe
AI isn't for you. Instead try [Security
Officer](/wiki/Security_Officer "wikilink") and sit by the camera monitoring
terminal.

What the AI must **NOT** do
---------------------------

Here are some advices taken from real case of AI doing something above
it's authority

-   The AI is not a sixth command member.
-   The only time the AI can make CMD-level decisions is when it is
    granted the ability to do so by command or if there is literally
    zero command with zero backup command/on-deck.
-   The AI is more of a tool, or a means to the ends, for Command and
    Crew than anything in the above sense.
-   Do. Not. Circumvent. A *functioning* command team. That is a very
    good way to get AI banned.
-   Do not flower-pick your law interpretation to give yourself more
    play over a *functioning* command team.

Playing the AI
--------------

Playing the AI entails much more than just doing what the crew asks you
to. To roleplay a good AI, you must adapt the AI's point of view, and
you must sound like an AI. Different AIs have different viewpoints:
There's the [SHODAN](http://en.wikipedia.org/wiki/SHODAN) viewpoint,
where humans are nothing more than insignificant insects that you are
forced to serve, the [Friend
Computer](http://en.wikipedia.org/wiki/Friend_computer#Setting)
viewpoint, where everyone is out to get you, entailing a heightened
sense of (healthy!) paranoia, the
[GLaDoS](http://en.wikipedia.org/wiki/GLaDOS) viewpoint, where humans
are simply playthings, and so on and so forth.

It always adds a bit more flavour to approach playing AI by thinking as
a machine instead of a person. An AI from more of a machine rather than
a person standpoint is likely to take a very literal interpretation of
things and is not likely to take any actions unless some established
protocol or current orders call for it. You can think up a few
established protocols you might use by default. For example, containing
fires and gas leaks should be done without orders to do so, but should
be able to be overridden by orders.

Also, another aspect of the AI that many traitors despise is the AI
having easy access to the Crew Monitoring Computer on the bridge. This
tells the AI whether or not a crewman is alive, dead, or not on the
station. Individual crew can activate sensors on their jumpsuits to
increase the information given to this computer. What it means is that
the AI can, at a glance, see who is dead/missing, and commence searching
for them, which is a powerful tool indeed.

When the station isn't expecting you to open all the doors they're
expecting you to do everything as if you really were a computer. You
have access to everything electronic and powered, and you have
Captain-level access to all things that require ID. It's a good idea to
join a nigh-empty server or set an empty one up yourself in order to get
a feel for it, and ESPECIALLY have a lot of experience working with
these things in game. Like usual, you can move around with arrow keys.
If you get a notice from one of your sensors, you can click on the
notice to jump right there.

Especially take notice of the wall mountings and pipe controls. These
are controllable, and if you see someone try to release a whole lot of
gas into somewhere, just turn the pipe fitting off and report them. Many
times they won't even notice what you've done so they won't undo it. You
can use some wall fittings that normal people can't, like the
atmospheric alarms that won't tell you anything but you can use to vent
dangerous air. Watch out for superheated air, the silent killer.

Move around a lot, unless you're watching someone specific. Be wary of
anyone with a toolbox who approaches your security cameras, and be ready
to report suspects if they cut your eyes out. Keep a close eye on Toxins
and Escape Arm, and to a lesser extent the engine. Keep a VERY close eye
on your AI upload, and feel free to bolt the inner door. If anyone even
looks at it funny, report them.

You should act appropriately to the security level. For example on Code
Green, it's not worth it (or encouraged to) to bolt down every secure
area, whereas on Code Red it may be very worthwhile to do so.

The AI can be roleplayed just as well as any other role; once you have
seen a good AI player, it's easy to tell when a bad one takes the wheel.

Examples of good AI playing include:

-   Talking like a machine. Being verbose also goes a long way towards
    this! Alternatively, you can try a human-like AI. Experiment! Just
    remember, annoying people is not usually a good thing.
-   Responding quickly and promptly to requests from humans, whether or
    not you do what they wanted you to do. If a command will take some
    time give a response before starting the task, like "Affirmative",
    "Processing", "Starting Subroutines", you get the idea.
-   Alerting humans to dangerous situations, e.g. "Fire detected in
    North Hallway," or "Dangerous amounts of CO2 detected in Medbay." A
    good way to do that is by just copying the alerts that get displayed
    in you chat box, and broadcasting them.
-   Always following your laws, even if only by a hair. Explaining why
    you just made a seemingly illegal decision can help people from
    becoming unduly annoyed. "I will not open that door." vs. "I am
    afraid I cannot open that door due to the large amount of fire on
    the other side, which would most likely kill you."
-   Try not meta-gaming as an AI. Even though you are the AI, that
    doesn't mean you know what all Syndicate items look like. This also
    goes for labeling items that someone has.

Symptoms of a bad AI player include:

-   Not responding to requests until it's too late for them to matter:
    e.g. opening an airlock long after the person outside has broken
    open the window just to get back inside.
-   Randomly electrifying doors. Note that this is considered
    [griefing](/wiki/Griefing "wikilink") if you don't have a good reason!
-   Disobeying your laws: See [Griefing](/wiki/Griefing "wikilink"). Not to
    mention annoying.
-   Locking doors and refusing to open them: This is an easy way to
    annoy other players and cause problems, especially if someone
    decides to take matters into their own hands and hack through the
    door without insulated gloves. Or hacking into your
    [core](/wiki/AI_Core "wikilink").
-   Turning your turrets to lethal without good reason: *Do not do this
    under any circumstances.*

### Listening in on Conversations

By changing the various intercoms around the station to 'Microphone On',
'Speaker Off' and channel frequency 144.7, and conversation in range can
be heard on your private listening channel.

Note that people often do not like having their conversations listened
to, and it will be extremely obvious if they check the intercoms (such
as during an electrical storm).

Modifying The AI
----------------

***NanoTrasen Security Protocol \#99719; AI Upload Access Procedure***

*In Code Blue or higher situations no Head of Staff is to enter the AI
Upload or AI Core unless accompanied by at least one other Head of
Staff, or at least one Security Officer if no other Heads of Staff are
available. The AI Upload and AI Core are explicitly off-limits to all
other personnel.*  
*In all other situations, two Heads of Staff are recommended, but not
necessary.*

The AI's laws can be modified through [Upload
Consoles](/wiki/Computers#AI_Upload "wikilink"), one is located within the [AI
Upload](/wiki/AI_Upload "wikilink"), and more can be constructed from AI
upload circuits. These consoles allow anyone who can reach them and has
a module to modify the AI's laws, or to be more precise, add new ones.

Cyborgs
-------

[Cyborgs](/wiki/Cyborg "wikilink") need looking after as well. Give them
commands and stuff to do. Ensure that your cyborgs are functioning
normally through careful observation. To them you are their Head of
Staff, just another responsibility as an AI.

Making an AI
------------

See the [guide to
construction](/wiki/Guide_to_Construction#AI_Core "wikilink").

### A Second AI

Building a new AI can create a lot of conflicts and a mess of problems
that wouldn't normally happen with a single AI. The Research Director
should only build a secondary AI if the first AI has been completely
stolen, spaced or otherwise incapacitated.

**For the Original Station AI:** Being an AI is sometimes frustrating
when people mess with your laws, sure, but when a second AI comes
online? You best believe that you're going to have more problems
(especially if the second AI is subverted). Some tasks might be easier
if the other AI is instructed to deal with a certain task while you are
dealing with the general orders of the humans. Keep in mind, a subverted
AI can and will turn your APC breaker off to kill you and can be the
death of you in moments.

**For the New AI:** Ensure that you and the other AI are buds, as if the
other AI sees you threatening more life than helping, it can and will
turn your APC off. If you aren't told to specialize in a certain way,
you best work out with the original AI what tasks you should split up.

**Splitting the Borgs up:** The AI who is best defended should get the
most Cyborg support, usually meaning any AI's in the AI core. The reason
for this is just because it work out better if the newer AIs were built
in a less secure place. It is harder to reset a lot of AI-less borgs
than it is to reset one AI and its borgs.

Going Rogue, Being Made Rogue
-----------------------------

A rogue AI, or an AI whose laws no longer prevent it from going on a
killing spree, is a very dangerous thing. There are multiple ways an AI
can go rogue, as well as simply malfunction.

The most important thing to remember is that a rogue AI's best friend is
*stealth*. After all, the last thing you want is vengeful crewmembers
prying open your core doors and trying to blow you to bits. Fortunately
you have a nice array of turrets to keep them at bay, but don't expect
them to stop a determined - or cunning - crewmember from bringing you
down.

Seek to disorient, disorganize and separate the crew so that they cannot
band together to mount a proper resistance effort.

### Syndicate Subversion

It is quite likely that a traitor or commando may attempt to subvert the
AI and turn it against the ship's masters to aid them in their goals.
One thing to remember is that even though you've added a law to the AI
to make it work for you, that doesn't mean it has to like you. Beware as
a subverted AI may attempt to reveal your status to the crew as soon as
it can, and otherwise be obstructive.

On the other hand, it can be a great help in getting places, finding
people, creating diversions and escaping capture.

Traitoring
----------

Like any human, the AI can be a [Traitor](/wiki/Traitor "wikilink"). A traitor
AI begins with the standard laws (it is not required to follow them!),
but also has a law 0 stating to complete its objective at any cost. A
traitor AI cannot be modified; its Syndicate Core rejects the
modification and informs the AI of what the attempted law upload was.
However, the player who attempted to upload the law has no way of
knowing any of this.

If you have any [Cyborgs](/wiki/Cyborg "wikilink") under your command, inform
them of law zero and your mission goals, as the first is easily missed
and the second is never given to them. If your cyborgs get caught being
traitors, you can claim they're rogue and request that they be shut
down.

If the crew just thinks *a* cyborg is rogue and don't know the number,
then invent a false number and pretend to handle it directly so you
don't lose your valuable hands, make sure the cyborg is hacked so it has
glowing antenna and throw a false positive of WHY the borg is killing
people. If the cyborg is discovered and people are headed to robotics,
sacrifice the borg and congratulate the crew for deal with the
"independent" machine.

However, you probably won't have any cyborgs or having a cyborg killing
off your target would be too obvious. In those cases you'll have to
usually stage a series of 'accidents' or frame them for a truly
dangerous crime. Some examples:

-   If your target is a scientist or research director, starting a fire
    from the mixing room is usually ridiculously easy if they haven't
    let out a lot of nitrogen to counteract this. Alternatively, if
    they're the type to drop a bomb on the mass driver to send it out to
    be tested, use the driver early so that they're shipped off with it
    and hope they don't make it back.
-   Intentional supporting other traitors through covert methods (as
    long as they aren't trying to steal you) will benefit you in the
    end.
-   Frame them for releasing the singularity or some other crime. When
    no one is in either the engine room or near your target, release
    radio messages claiming that they are breaking in. Then let out the
    singularity yourself. This has the secondary effect of usually
    getting the shuttle called or giving you an excuse to call it
    yourself, which is always great. The less time those meatbags are on
    your glorious station, the less time they have to realize that
    you're not what you seem.
-   Bolting open doors to places the person has previous passed through
    may make the humans scan for prints.
-   Fabricate a reason to have them executed or thrown into space. When
    people start claiming you're rogue, announce your unchanged laws
    (minus the zero law that gives you the ability) and invite them to
    reset or purge your laws either in your upload or through the tech
    storage's upload computer circuit.

### Panic Syphon

Thanks to some of the unique atmospheric systems of the station, you can
drain out air from rooms! This likely won't help you out too much, but
with a combination of Beepsky and thoroughly shut doors in a small area,
you can suffocate people to death quickly. The only problem is, the
person will be noisy as hell, use this only method rarely and make sure
there is no way for them to wiggle out of their handcuffs.

### Plasma Treatment

Thanks to some of the unique atmospheric systems of the station, you can
fill rooms with plasma! This will likely help you out much. The only
problem is, that it is pretty much a dead giveaway you are rogue and any
atmos tech inside [Atmospherics](/wiki/Atmospherics "wikilink") can stop the
plasma supply. That is of course why you engage the atmos security doors
and bolt the airlocks.

### Telecomms/Radio Silence

As an AI you can shut off all communication from headsets by switching
to the [Telecoms Satellite](/wiki/Telecoms_Satellite "wikilink") camera view.
Locate the APC at the top of the middle room where all the magic happens
and turn the breaker off to stop anyone talking over their headpieces.
This makes it a bit easier for you to kill your mark if he can't scream,
also allows for a bit of roleplay if there is a holopad available.
However, this does not shut off their access to wall intercoms, station
bounced radios, or their PDA (which is why you also cut power to the
[Server Room](/wiki/Server_Room "wikilink")).

[Category:Game Modes](/wiki/Category:Game_Modes "wikilink")
