# Is AI Hiding Its Full Power? w/ Geoffrey Hinton (StarTalk Special Edition Transcript)

- **Ospiti / Conduttori:** Geoffrey Hinton (Premio Nobel 2024), Neil deGrasse Tyson, Gary O'Reilly, Chuck Nice
- **Programma:** StarTalk Special Edition
- **Data:** 28 Febbraio 2026
- **Fonte trascrizione:** The Singju Post

---

**Editor’s Notes:** *In this StarTalk special edition, Neil deGrasse Tyson sits down with Professor Geoffrey Hinton, the “godfather of AI” and 2024 Nobel Prize winner, to explore the rapidly evolving landscape of artificial intelligence. The discussion dives deep into the mechanics of neural networks, tracing their development from biological theories in the 1950s to the massive computational power driving today’s large language models. Hinton shares startling insights into AI’s potential to surpass human reasoning, discussing its capacity for deception, its role in revolutionary healthcare breakthroughs, and the existential questions surrounding machine consciousness. This episode offers a comprehensive and sobering look at the future of our coexistence with digital intelligence and the “singularity” that may already be underway. (Feb 28, 2026)*

**TRANSCRIPT:** 

## Introduction

**NEIL DEGRASSE TYSON:** This is StarTalk Special Edition. Neil DeGrasse Tyson, your personal astrophysicist. And if it’s Special Edition, it means we’ve got Gary O’Reilly.

**GARY O’REILLY:** Hey, Neil.

**NEIL DEGRASSE TYSON:** Gary, how you doing, man?

**GARY O’REILLY:** I’m good.

**NEIL DEGRASSE TYSON:** Former soccer pro.

**GARY O’REILLY:** Yes.

**NEIL DEGRASSE TYSON:** So, Chuck, always good to have you.

**CHUCK NICE:** Always a pleasure.

**NEIL DEGRASSE TYSON:** So, Gary, you and your team picked a topic for — for the ages today.

**GARY O’REILLY:** Yeah, it’s one of those things that we hear about it, we think we know about it. But let me put it to you this way. We are faced with the simple fact that AI, at this point, we’re going to talk about AI today.

**NEIL DEGRASSE TYSON:** Okay.

**GARY O’REILLY:** We are.

**NEIL DEGRASSE TYSON:** A deep dive.

**GARY O’REILLY:** It’s inescapable. Oh, yeah.

**NEIL DEGRASSE TYSON:** Yes, go.

**GARY O’REILLY:** It was only a few years ago when we asked people how AI works, they’ll say something along the lines of, “It utilizes deep learning neural networks,” but they’re dead buzzwords. They know them, but they don’t know anything about them. So what does that really mean? We’ll break down how AI works down to the bit and get into how far we think this is going to go from one of AI’s founding architects.

**CHUCK NICE:** Now we’re talking.

**GARY O’REILLY:** So if you would bring on our guest.

## Meet Geoffrey Hinton: The Godfather of AI

**NEIL DEGRASSE TYSON:** I’ll be delighted to. We have with us Professor Geoffrey Hinton. Geoffrey, welcome to StarTalk.

**GEOFFREY HINTON:** Thank you for inviting me.

**NEIL DEGRASSE TYSON:** Yeah. You are a cognitive psychologist and computer scientist. I don’t know anybody with that combo.

**CHUCK NICE:** Couldn’t make up your mind, huh?

**NEIL DEGRASSE TYSON:** You’re a professor emeritus at the Department of Computer Science at the University of Toronto. And you are OG AI.

**CHUCK NICE:** Oh, lovely.

**NEIL DEGRASSE TYSON:** Can I say that? Does that make sense?

**CHUCK NICE:** OG AI.

**NEIL DEGRASSE TYSON:** OG AI. And some people have called you the godfather of AI, of artificial intelligence. And let’s just go straight out off the top here. When we think of the genesis of AI as it is currently manifested, it feels like large language models took everybody by storm. They sort of showed up and everybody was freaking out, celebrating, dancing in the streets or crying in their pillows. That happened, we noticed, a couple of years ago. So I’m just wondering what got you started on this path many, many years ago. My records show it goes back to the 1990s, is that correct?

## The Origins of AI: Two Competing Visions

**GEOFFREY HINTON:** No, it really goes back to the 1950s.

**NEIL DEGRASSE TYSON:** Ooh, right.

**GEOFFREY HINTON:** The founders of AI. At the beginning, in the 1950s, there were two views of how to make an intelligent system. One was inspired by logic. The idea was that the essence of intelligence is reasoning. And in reasoning, what you do is you take some premises and you take some rules for manipulating expressions and you derive some conclusions. So it’s much like mathematics, where you have an equation, you have rules for how you can tinker with both sides and — or combine equations and you derive new equations. And that was kind of the paradigm they had.

There was a completely different paradigm that was biological. And that paradigm said, look, the intelligent things we know have brains. We have to figure out how brains work. And the way they work is they’re very good at things like perception. They’re quite good at reasoning by analogy. They’re not much good at reasoning. You have to get to be a teenager before you can do reasoning, really. So we should really study these other things they do, and we should figure out how big networks of brain cells can do these other things, like perception and memory.

Now, a few people believed in that approach, and among those few people were John von Neumann and Alan Turing. Unfortunately, they both died young. Turing, possibly with the help of British intelligence.

**NEIL DEGRASSE TYSON:** Turing. He’s the subject of the film *The Imitation Game*. Yeah, yeah. So anyone who hasn’t seen that? Definitely put that on your list.

**GEOFFREY HINTON:** Cool.

**NEIL DEGRASSE TYSON:** Yeah. So to go back to the 1950s, you were just a young tyke then, correct?

**GEOFFREY HINTON:** Yeah, I was in single digits then. I was in single digits.

**NEIL DEGRASSE TYSON:** Okay, so how do we establish the genesis of your curiosity in this field?

## A Young Mind Captivated by Distributed Memory

**GEOFFREY HINTON:** A few things. When I was at high school in the early 1960s or mid-1960s, I had a very smart friend who was a brilliant mathematician and used to read a lot. And he came into school one day and talked to me about the idea that memories might be distributed over many brain cells instead of in individual brain cells. So that was inspired by holograms. Holograms were just coming out then.

**NEIL DEGRASSE TYSON:** Was that the computer science side of you or the cognitive psychologist side of you that tap-rooted into those ideas?

**GEOFFREY HINTON:** Both, really. But in the 1970s, when I became a graduate student, it was obvious that there was a new methodology that hadn’t been used that much, which was — if you have any theory of how the brain works, you can simulate it on a digital computer. Unless it’s some crazy theorem that says it’s all quantum effects, and let’s not go there.

**CHUCK NICE:** That’s right.

**GEOFFREY HINTON:** Not yet.

**NEIL DEGRASSE TYSON:** We won’t knock on Penrose’s door.

## Simulating the Brain: Learning Through Connection Strengths

**GEOFFREY HINTON:** You can simulate it on a digital computer, and so you can test out your theory. And it turns out if you tested most of the theories that were around, they actually didn’t work when you simulated them. So I spent my life trying to figure out how you change the strengths of connections between neurons so as to learn complicated things in a way that actually works when you simulate it on a digital computer.

And I fail to understand how the brain works. We’ve understood some things about it, but we don’t know how a brain gets the information it needs to change connection strengths — gets the information it needs to know whether it needs to increase the connection strength to be better at a task or to decrease that connection strength. But what we do know is we know how to do it in digital computers now.

**NEIL DEGRASSE TYSON:** Wow. Well, so that — that means the computers are doing what we —

**GARY O’REILLY:** — we made a better computer brain than our own brain at doing this particular function.

**GEOFFREY HINTON:** One thing, and that’s what got me really nervous in the beginning of 2023 — the idea that digital intelligence might just be better than the analog intelligence we’ve got.

**GARY O’REILLY:** Interesting. Save the scary bit till a bit later on. Let me have 10 minutes of just breathing in, breathing out.

**GEOFFREY HINTON:** If we take a step back, you’re assuming there’s just one scary bit.

**GARY O’REILLY:** No, I’m not. I’m going to go one at a time.

**CHUCK NICE:** Okay.

## How Artificial Neural Networks Work

**GARY O’REILLY:** Artificial neural networks. If you could break that down to the very basic level for us — of how it’s been able to strengthen, weaken messaging and signaling and how it fires, and how it then finds itself at where it is.

**GEOFFREY HINTON:** Now, I do have an 18-hour course on this, but I will try and cut it down to less than 18 hours.

**GARY O’REILLY:** Please do.

**GEOFFREY HINTON:** So I imagine a lot of your audience know some physics.

**NEIL DEGRASSE TYSON:** Yes.

**GEOFFREY HINTON:** And one way into it is to think about something like the gas laws. You know, you compress the gas and it gets hotter. Why does it do that? Well, underneath there’s a kind of seething mass of atoms that are buzzing around. And so the real explanation for the gas laws is in terms of these microscopic things that you can’t even see buzzing around. And so you explain some macroscopic behavior by lots and lots and lots of little things of a completely different type from macroscopic behavior interacting.

And that was sort of the inspiration for the neural net view — that there’s things going on in big networks of brain cells that are a long way away from the kind of conscious, deliberate symbol processing we do when we’re reasoning, but that underpin it and that are maybe better at other things than reasoning, like perception or reasoning by analogy. So the symbolic people could never deal with how do we reason by analogy — not very satisfactorily — whereas the neural nets could.

So before I get into the sort of fine details of how it works, the basic idea is that macroscopic things like a word correspond to big patterns of neural activity in the brain. Similar words correspond to similar patterns of neural activity. So the idea is Tuesday and Wednesday will correspond to very similar patterns of neural activity. Where you can think of each neuron as a feature — better to call it a micro feature — that when the neuron gets active, it says “this has that micro feature.”

So if I say “cat” to you, all sorts of micro features will get active. Like it’s animate, it’s furry, it’s got whiskers, it might be a pet, it’s a predator — all those things. If I say “dog,” a lot of the same things will get active, like it’s a predator, it might be a pet, but some different things, obviously. So the idea is, underlying these symbols that we manipulate, there’s much more complicated microscopic goings on that the symbols kind of are associated with. And that’s where all the action really is. And if you really want to explain what goes on when we think or when we do analogies, you have to understand what’s going on at this microscopic level. And that’s the neural network level.

**GARY O’REILLY:** So that’s a collaboration between clusters of neurons that get you to an end point.

**NEIL DEGRASSE TYSON:** I like that word — collaboration.

## Teaching a Neural Network to Recognize a Bird

**GEOFFREY HINTON:** Yes, there’s a lot of that that goes on. Probably the easiest way to get into it is by thinking of a task that seems very natural, which is — take an image, let’s say it’s a black gray level image. So it’s got a whole bunch of pixels, little areas of uniform brightness that have different intensity levels. So as far as the computer’s concerned, that’s just a big array of numbers.

And now imagine the task is you want to say whether there’s a bird in the image or not, or rather whether the prominent thing in the image is a bird. And people tried for many, many years — like half a century — to write programs that would do that, and they didn’t really succeed. And the problem is, if you think what a bird looks like in an image, well, it might be an ostrich up close in your face, or it might be a seagull in the far distance, or it might be a crow. So they might be black, they might be white, they might be tiny, they might be flying, they might be close. You might just see a little bit of them. There might be lots of other cluttered things around, like it might be a bird in the middle of a forest.

So it turns out it’s not trivial to say whether there’s a bird in the image or not. And so what I’m going to do now is explain to you, if I was building a neural network by hand, how I would go about doing that. And once I’ve explained how I would build the neural network by hand, I can then explain how I might learn all the connection strengths instead of putting them in by hand.

**CHUCK NICE:** I got you. All right, so with that — because what you’re talking about is assigning a mathematical value to every single part of an image.

**GEOFFREY HINTON:** That’s what your camera does, right?

**CHUCK NICE:** Exactly. It does, but it’s not recognizing the image. My camera, it’s not.

**GEOFFREY HINTON:** It’s just got a bunch of numbers.

## How Neural Networks Recognize Patterns

CHUCK NICE: It’s just got a bunch of numbers. And so I have a chip and I have a charged couple devices. It’s collecting the light, it’s assigning a value, and then that’s the picture. Now, but what you’re talking about, wouldn’t you have to assign a value to every single type of bird? Because some of what we do as human beings is intuit what a bird may be as opposed to recognizing the bird.

And let me just give you the example. If you were to take a V, the letter V, and curve the straight lines of the letter V and put it in a cloud, everyone who sees that will say, that’s a bird.

NEIL DEGRASSE TYSON: But yet, no, to me, it’s a

CHUCK NICE: curved V. But no one. But there is no bird there. I just know that is a bird. That’s not a mathematical value. Now, so what are you doing?

GEOFFREY HINTON: Well, the question is, how do you just know that there’s something going on in your brain? What might be going on in your brain so that you just know that’s a bird is a whole bunch of activation levels of different neurons, which you could think of as mathematical values.

CHUCK NICE: I got you. Okay. So wouldn’t that require then training this neural net on every possible way a

NEIL DEGRASSE TYSON: bird can manifest in the

CHUCK NICE: photo so that it can intuit what a bird might be when a bird is not there.

NEIL DEGRASSE TYSON: But at that point, it’s not intuiting anything, it’s just going off a lookup table.

CHUCK NICE: It really is going on. And what would be the—

GARY O’REILLY: All right, here comes your office.

## Generalization and the Power of Neural Networks

GEOFFREY HINTON: There’s something called generalization. So if you see a lot of data, obviously you can make a system that just remembered all that data. But in a neural net, it’ll do more than just remember the data. In fact, it won’t literally remember the data at all. What it’ll do is, as it’s learning on the data, it’ll find all sorts of regularities and it’ll generalize those regularities to new data. So it will be able to, for example, recognize a unicorn, even though it’s never seen one before.

CHUCK NICE: Interesting.

GARY O’REILLY: So it’s self teaching.

GEOFFREY HINTON: Let me carry on with my explanation of how neural networks work, and I’m going to do it by saying how I would design one by hand. So your first thought when you see that an image is just a big array of numbers, which are how bright each pixel is, is to say, well, let’s hook up those pixel intensities to our output categories, like bird and cat and dog and politician, or whatever our output categories are. And that won’t work.

And the reason is, if you think about what does the brightness of one pixel tell you about whether it’s a bird or not? Well, it doesn’t tell you anything, because birds can be black and birds can be white, and there’s all sorts of other things that can be black and white. So the brightness of a pixel doesn’t tell you anything.

So what can you derive from those numbers that you have in the image that describe the image? Well, the first thing you can derive, which is what the brain does, is you can recognize when there’s little bits of edge present. So suppose I take a little column of three pixels and I have a neuron that looks at those three pixels, a brain cell, and has big positive weights to those three pixels. So when those pixels are bright, the neuron gets very excited. Now that would recognize a little streak of white that was vertical.

But now suppose that next to it there’s another column of three pixels. So the first column was on the left and the second column was on the right. And I give the neuron big negative connection strengths to those pixels. So you can think of the neuron as getting votes from the pixels. For the three pixels on the left, the votes it gets are big positive numbers times big positive intensities. So great big votes.

Now, from the three pixels in the right hand column, it’s got negative weights. So if those pixels are bright, it’ll get a big brightness times a big negative weight. So it’ll get a lot of negative votes and they’ll all cancel out. So if the column of pixels on the left is the same brightness as the column of pixels on the right, the positive votes it gets from the left hand column will cancel the negative votes it gets from the right hand column and it’ll get zero net input and it’ll just stay quiet.

But if the pixels on the left are bright and the pixels on the right are dim, the negative votes will be multiplied by small intensity numbers, and the positive votes will be multiplied by big intensity numbers. And so the neuron gets lots of input and gets very excited and says, “I found the thing I like,” and the thing it likes is an edge, which is brighter on the left than on the right.

So we do know how to make a neuron, if we hand wire it like that, pick up on the fact that there’s an edge at a particular location in the image that’s brighter on one side than the other side.

## Edge Detectors and the Visual Cortex

Now, what the brain does — roughly speaking, a lot of neuroscientists will be horrified by me saying this, but very roughly speaking — what the brain does is in the early stages of visual cortex, which is where you recognize objects, it has lots and lots of neurons that pick up on edges at different orientations, in different positions and at different scales. So it has thousands of different positions and dozens of different orientations and several different scales. And it has to have edge detectors for each combination of those. So it has like a gazillion little edge detectors, including some big edge detectors.

So a cloud, for example, has a big, soft, fuzzy edge, and you need a different neuron for detecting that than what you’d need for detecting, say, the tail of a mouse disappearing around a corner in the distance, which is a very fine thing. And you need an edge detector that was very sharp and saw very small things. So first stage, we have all these edge detectors.

CHUCK NICE: Well, what you’re describing sounds like putting together a very large puzzle right now. The first thing that you do is you want to find all the edges.

GARY O’REILLY: Yeah.

CHUCK NICE: And that’s how you build the puzzle inward from finding all the edges, not

NEIL DEGRASSE TYSON: only edges of the physical puzzle, but

CHUCK NICE: edges of anything, images in the puzzle,

NEIL DEGRASSE TYSON: within the puzzle itself.

CHUCK NICE: So straight lines, things of that nature, they all match up when you’re doing a

NEIL DEGRASSE TYSON: puzzle. And the edges also — color is a dimension of this.

CHUCK NICE: Right?

GEOFFREY HINTON: We’ll ignore color for now.

NEIL DEGRASSE TYSON: Yeah.

CHUCK NICE: Okay.

NEIL DEGRASSE TYSON: Okay. Yeah.

GEOFFREY HINTON: I mean, you can understand it without dealing with color.

## How Neural Networks Learn: Back Propagation Explained

GEOFFREY HINTON: That’s what the first layer of neurons will do, they’ll look at the pixels and they’ll detect little bits of edge. Now, in the next layer of neurons, what I would do is I’d make a neuron that maybe detects three little bits of edge that all line up with one another and slope gently down towards the right. And it also detects three little bits of edge that all line up with one another and slope gently upwards towards the right. And what’s more, those two little combinations of three edges join in a point.

So I think you can imagine some edges sloping down to the right, some edges sloping up to the right and joining in a point. And I have a neuron that detects that. Okay, and we know how to build that. Now, you just give it the right connections to the edge detecting neurons, and maybe you give it some negative connections to neurons to detect edges in different orientations. So it doesn’t just go off anyway, it’s suppressed by those.

Now, that you might think of as something that’s detecting a potential beak of a bird. If that guy gets active, it could be all sorts of things. It could be an arrowhead, it could be all sorts of things. But one thing it might be is the beak of a bird. So now you’re beginning to get some evidence that’s kind of relevant to whether or not it might be a bird.

So in the second layer of neurons, I’d have lots of things to detect possible beaks all over the place. I might also have things that detect a little combination of edges that form a circle, an approximate circle, and I’d have detectors for those all over the place, because that might be a bird’s eye. I mean, there’s all sorts of other things. It could be a button, it could be a knob on a computer, it could be anything, but it might be a bird’s eye. So that’s the second layer.

Now, in the third layer, I might have something that looks for a possible bird’s eye and a possible bird’s beak that are in the right spatial relationship to one another to be a bird’s head. I think you can see how I would do that. I’d hook up neurons in the third layer to the eye detectors and beak detectors that are in the right relationship to one another to be a bird’s head. So now in the third layer, I have things that are detecting possible birds heads.

The next thing I’m going to do is maybe, because we’re sort of running out of patience at this point, I can have a final layer that has neurons that say cat, dog, bird, politician, whatever. And in that final layer, I’ll take the neuron that says bird and I’ll hook it up to the things that detect birds heads. But I’ll also hook it up to other things in the third layer that detect things like bird’s feet or the tips of birds wings. And so now my sort of output neuron for bird, when that gets active, the neural net is saying it’s a bird. If it sees a bird’s foot and a possible bird’s head and a possible tip of the wing of a bird, it’ll get lots of input and say, “Hey, I think it’s a bird.”

So I think you can now understand how I might try and design that by hand. And I think you can see there’s huge problems in that. I need an awful lot of detectors. I need to cover this whole space of positions and orientations and scales. I need to decide what features to extract. I mean, I just made up the idea of getting a beak and then a bird’s head. There may be much better things to go after.

What’s more, I want to detect lots of different objects. So what I really need is features that aren’t just good for finding birds, but features that are good for finding all sorts of things. And it would be a nightmare to design this by hand, particularly if I figured out that to do a good job of this, I needed a network with at least a billion connections in it. So I have to by hand design the strengths of these billion connections. And that’ll take a long time.

Then we say, well, okay, a network like that, maybe it could recognize birds if it had the right connection strengths in it. But where am I going to get those connection strengths from? Because I sure as hell don’t want to put them in by hand. I don’t even want to tell my graduate students to put them in.

CHUCK NICE: Yeah, that’s what they’re there for, Professor.

GEOFFREY HINTON: That’s really what they’re there for. But you need about 10 million of them for this.

CHUCK NICE: All right, well, now we’ve got a problem.

GEOFFREY HINTON: Can you imagine the grants you’d have to write to support 10 million graduate students?

GARY O’REILLY: Oh, my word.

## Random Weights and the Path to Learning

GEOFFREY HINTON: So here’s an idea that initially seems really dumb, but will get you the idea of what we’re going to do. We’re going to start with random connection strengths. Some will be positive numbers, some will be negative numbers. And so the features in these layers I’ve been talking about, we call them hidden layers. The features in those layers will be just random features. And if we put in an image of a bird and look at how the output neurons get activated, the output neurons for cat and dog and bird and politician will all get activated a tiny bit and all about equally because the connection states are just random.

GARY O’REILLY: Yeah.

GEOFFREY HINTON: So that’s no good. But we could now ask the following question. Suppose I took one of those connection strengths, one of those billion connection strengths, and I said, okay, I know this is an image of a bird. And what I’d really like is next time I present you with this image, I’d like you to give slightly more activation to the bird neuron and slightly less activation to the cat and dog and politician neurons. And the question is, how should I change this connection strength?

Well, I could do an experiment. If I’m not very theoretical, I don’t know much math, I’d do an experiment. I would say, let’s increase the connection strength a little bit and see what happens. Does it get better at saying bird? And if it gets better at saying bird, I say, okay, I’ll keep that mutation to the connection.

NEIL DEGRASSE TYSON: But better means there’s a human in the loop making that judgment. The result of its experiment.

GEOFFREY HINTON: Well, there has to be someone saying what the right answer is.

CHUCK NICE: Absolutely.

GEOFFREY HINTON: That’s called the supervisor. Yes.

NEIL DEGRASSE TYSON: Okay.

CHUCK NICE: Okay.

GEOFFREY HINTON: And the problem if you do it like that is there’s a billion connection strengths. Each of them has to be changed many times. It’s going to take, like, forever. So the question is, is there something you can do that’s different from measuring, that’s much more efficient than there is? You can do something called computing.

So this network, certainly, if it’s on a computer, you know the current strengths of all the connections. So when you put in an image, there’s nothing random about what — I mean, the connection strengths initially had random values, but when you put an image, it’s all deterministic. What happens next? The pixel intensities get multiplied by weights on connections to the first layer of neurons. Their activities get multiplied by weights on connections to the second layer and so on, and you get some activation levels of the output neurons.

So you could now ask the following question. If I take that bird neuron, could I figure out for all the connection strengths at the same time whether I should increase them a little bit or decrease them a little bit in order to make it more confident that this is a bird, in order for it to say bird a bit more lively and the other things a bit more quietly. And you can do that with calculus, you can send information backwards through the network saying, “How do I make this more likely to say bird next time?” And because you have a lot of physicists in the audience, I’m going to try and give you a physical intuition for this.

NEIL DEGRASSE TYSON: Go for it. Yeah.

## The Physics of Back Propagation

GEOFFREY HINTON: You put in bird, an image of a bird, and with the initial weights, the bird output neuron only gets very slightly active. And so what you do now is you attach a piece of elastic of 0 rest length. You attach a piece of elastic attaching the activity level of the bird output neuron to the value you want, which is, say, 1. Say 1’s the maximum activity level and 0 is the minimum activity level. And this had an activity level of like 0.01. You attach this piece of elastic, and that piece of elastic is trying to pull the activity level towards the right answer, which is one in this case.

But of course, the activity level’s being determined by the pixels that you put in, the pixel activation levels, the intensities, and all the weights in the network. So the activity level can’t move. Now, one way to make the activity level move will be to change the weights going into the bird neuron. You could, for example, give bigger weights on neurons that are highly active, and then the bird neuron will get more active.

But another way to change the activity level of the bird neuron is to actually change the activity levels of the neuron of the layer there before it. So, for example, we might have something that sorted and detected a bird’s head, but wasn’t very sure this really is a bird. And so what you’d like is the fact that you want the output to be more bird. Like, you’ve got this piece of elastic saying, “More, more, I want more here.” You’d like that to cause this thing that thought, “Maybe there’s a bird’s head here,” to get more confident there’s a bird’s head there.

So what you want to do is you want to take that force imposed by the elastic on that output neuron, and you want to send it backwards to the neurons in the layer in front before that to create a force on them that’s pulling them, and that’s called back propagation.

NEIL DEGRASSE TYSON: Back propagation.

CHUCK NICE: Okay.

GEOFFREY HINTON: That is called back propagation. And the physics way to think about it is you’ve got a force acting on the output neurons, and you want to send that force backwards so that the force acts on the neurons in the layer in front. And of course, there’s forces acting on many different output neurons. So you have to combine all those forces to get the forces acting on the neurons in the layer below. Once you send this all the way back through the network, you have forces acting on all these neurons. And you say, okay, let’s change the incoming weights of each neuron so its activity level goes in the direction of the force that’s acting on it. That’s back propagation. And that makes things work wondrously well.

NEIL DEGRASSE TYSON: So is this the light — diabolically, don’t go there yet. Okay.

GARY O’REILLY: Is this the light bulb moment where the neural networks no longer need the human teacher? Is this the beginning of that process?

GEOFFREY HINTON: No, not exactly.

GARY O’REILLY: Okay.

## The Eureka Moment in Neural Network Research

GEOFFREY HINTON: This is a light bulb moment, though. So for many years, the people who believed in neural networks knew how to change the very last layer of connection strengths, which you call weights, the ones going into the output units, the connection strength going from the last layer of features into the bird neuron. We knew how to change those, but we didn’t understand how to get forces operating on those hidden neurons, the ones that detect a bird’s head, for example. And back propagation showed us how to get forces acting on those, so then we could change the incoming weights of those. And that was a eureka moment. Many different people had that eureka moment at different times.

GARY O’REILLY: So what period of time are we talking about here? When are we falling into the back propagation thought?

GEOFFREY HINTON: Okay, the early 1970s, there was someone in Finland who had it, I think in his master’s thesis. And then in probably the late 70s, someone called Paul Werbos at Harvard had the idea. In fact, some control theorists there called Bryson and Ho had had the idea for doing things like controlling spacecraft. So when you land a spacecraft on the moon, you’re using something very like back propagation, but it’s in a linear system. You’re using back propagation to figure out how you should fire the rockets.

CHUCK NICE: So it seems like what you’re talking about — in the 70s we could have had what we have today. We just didn’t have the mathematical computing power to make this work.

GEOFFREY HINTON: That’s a large part of it, yes.

NEIL DEGRASSE TYSON: Yeah.

## Supervised Learning vs. Reinforcement Learning

GEOFFREY HINTON: The other thing we didn’t have is back in the 70s, people didn’t show that. When you applied this in multi-layer networks, what you get is very interesting representations. So we weren’t the first to think of back propagation, but the group I was in San Diego, we were the first to show that you could learn the meanings of words this way. You could show the string of words. And by trying to predict the next word, you could learn how to assign features to words that captured the meaning of the word. And that’s what got it published in

CHUCK NICE: Nature, it sounds like. And I’m just trying to get my head around what you explained, because it sounds to me like there is a cascading relationship to these values, and that really what matters are the values that are closest to the next value. And then there are kind of this cascading reinforcement to say, yes, this is it, or no, it is not. Am I getting that right? I’m just trying to figure out what you’re saying here in a really plain way.

GEOFFREY HINTON: Okay, so. Good question. You’re not getting it quite right.

CHUCK NICE: Okay, go ahead.

GEOFFREY HINTON: So this kind of learning, where you back propagate these forces and then change all the connection strengths so each neuron goes in the direction that the force is pulling it in, that’s not reinforcement learning. This is called supervised learning.

CHUCK NICE: Okay.

GEOFFREY HINTON: Reinforcement learning is something different. So here, for example, we tell it what the right answer is. If you’ve got a thousand categories, you showed a bird. That was a bird.

CHUCK NICE: There you go.

GEOFFREY HINTON: In reinforcement learning, it makes a guess, and you tell it whether it got the answer right.

CHUCK NICE: All right.

GEOFFREY HINTON: That’s much less information.

CHUCK NICE: You cleared it up. That’s what I was missing.

GARY O’REILLY: All right, to Chuck’s point about computational power, was it just that? Because at the moment, you sound a lot like you’ve got theory that seems like it could be, but the practicality is there’s not enough computational power. Do we have any other technology that came through that was the enabling aspect to this?

GEOFFREY HINTON: Okay, so in the mid-80s, we had the back propagation algorithm working, and it could do some neat things. It could recognize handwritten digits better than nearly any other technique, but it couldn’t deal with real images very well. It could do quite well at speech recognition, but not substantially better than the other technologies. And we didn’t understand at the time why this wasn’t the magic answer to everything. And it turns out it was the magic answer to everything. If you have enough data and enough compute power.

CHUCK NICE: Wow.

GEOFFREY HINTON: So that’s what was really missing in the 80s.

## What Is Thinking? Can Machines Do It?

CHUCK NICE: All right, I’m going to depart for a second, just to pick your brain for a — this is part commentarium, part question. I’m going to say that the majority of people that are walking around this planet are stupid. So what exactly is smart and what exactly is thinking? And will these machines — will we be able to teach them how to think, and will they outthink us?

GEOFFREY HINTON: Okay. They already know how to think.

CHUCK NICE: Okay, so what is thinking then?

GEOFFREY HINTON: Okay, well, yeah,

CHUCK NICE: I could do this all day.

GARY O’REILLY: Please don’t.

GEOFFREY HINTON: There’s a lot of elements to thinking. People often think using images, you often think actually using movements. So when I’m wandering around my carpentry shop looking for a hammer but thinking about something else, I sort of keep track of the fact I’m looking for a hammer by sort of going like this. I wander around going like this while I’m thinking about something else. And that’s a representation that I’m looking for a hammer.

So we have many representations involved in thinking, but one of the main ones is language. And a lot of the thinking we do is in language. And these large language models actually do think.

So there’s a big debate, right, between the people who believed in old-fashioned AI, that it was all based on logic and you manipulate symbols to get new symbols. They don’t really think these neural nets are thinking, whereas the neural net people think, no, they’re thinking. They’re thinking pretty much the same way we do.

And so the neural nets now — some of them, you’ll ask them a question and they’ll output a symbol that says, “I’m thinking.” And then they’ll start outputting their thoughts, which are thoughts for themselves.

Like, I give you a simple math problem: there’s a boat, and on this boat there’s a captain. There’s also 35 sheep. How old is the captain? Now many kids of age around 10 or 11, particularly if they’re educated in America, will say the captain is 35. Because they look around and say, well, that’s a plausible age for a captain. And the only number I was given was these 35 sheep. So they’re operating at a sort of substituting symbols level.

The AIs can sometimes be seduced into making similar mistakes. But the way the AIs actually work is quite like people. They take a problem and they start thinking. And you might, for a child, you might say, okay, well how old is the captain? Well, what are the numbers I’ve got in this problem? Hey, I’ve only got a 35. Is that a plausible age for a captain? Yeah, he might be 35. Bit young, but maybe okay, I’ll say 35. That’s what a 10-year-old child might think. And the child would think it to itself in words.

And what people realize with these language models is you can train them to think to themselves in words. That’s called chain of thought reasoning. And they trained them to do that. And after that you give them a problem, they’d think to themselves, just like a kid would, and sometimes come up with the wrong answer. But you could see them thinking. So it’s just like people.

## AI Learning, Scale, and the Limits of Data

GARY O’REILLY: So if we have AI that’s thinking, and I’m saying that knowing that you’ve just explained that they do, are they better at learning than we are? And let’s sort of take that forward and think, what is the evolution from thinking to predicting, to being creative, to understanding? And are we then going to fall into an awareness of this intelligence?

GEOFFREY HINTON: Okay, that’s about half a dozen major questions. So you’ll —

GARY O’REILLY: How long have we got?

GEOFFREY HINTON: Ask me the first question again.

GARY O’REILLY: Are AIs better at learning than we are?

GEOFFREY HINTON: Okay, excellent. So they’re solving a slightly different problem from us. So in your brain, you have a hundred trillion connections, roughly speaking. Okay, that’s a lot. And you only live for about 2 billion seconds. That’s not much.

NEIL DEGRASSE TYSON: No, 3 billion. 2 billion is 63 years. We do better than that today.

GEOFFREY HINTON: Yeah, it’s true. I was going to come to that. I was going to say, luckily for me, it’s a bit more than 2 billion, but yes. But we’re dealing with orders of magnitude here. So 2 billion, 3 billion, who cares? If you compare how many seconds you live for with how many connections you’ve got, you have a whole lot more connections than experiences.

Now, with these neural nets, it’s sort of the other way around. They only have of the order of a trillion connections. So like 1% of your connections, even in a big language model — many of them fewer — but they get thousands of times more experience than you.

CHUCK NICE: Right.

GEOFFREY HINTON: So the big language models are solving the problem with not many connections, only a trillion. How do I make use of a huge amount of experience? And backpropagation is really, really good at packing huge amounts of knowledge into not many connections. But that’s not the problem we’re solving. We’ve got huge numbers of connections, not much experience. We need to sort of extract the most we can from each experience. So we’re solving slightly different problems. Which is one reason for thinking the brain might not be using back propagation.

CHUCK NICE: Right. I was about to say it sounds like we don’t use back propagation. However, would that mean the brute force of adding connections to the neural net increase its effective thinking so that it surpasses us with no problem?

NEIL DEGRASSE TYSON: So then it would have more experience and more network connections — more experience automatically.

CHUCK NICE: But now it has 100 trillion connections.

GARY O’REILLY: You’re talking about scale here.

NEIL DEGRASSE TYSON: Yeah, yeah.

GEOFFREY HINTON: So that’s a very good question. And what happened for several years, quite a few years, is that every time they made the neural net bigger and gave it more data, it got better. It scaled.

GARY O’REILLY: Makes sense.

GEOFFREY HINTON: And it got better in a very predictable way. So that you could figure out, it’s going to cost me $100 million to make it this much bigger and give it this much more data. Is it worth it? And you could predict ahead of time, yes, it’s going to get this much better, it’s worth it.

It’s an open question whether that’s petering out now. There are some neural nets for which it won’t peter out, where as you make them bigger and give them more data, they’ll just keep getting better and better. And then there are neural nets where they can generate their own data. I don’t know that much physics, but I think it’s like a plutonium reactor which generates its own fuel.

So if you think about something like AlphaGo that plays Go, initially it was trained — the early versions of Go-playing programs with neural nets were trained to mimic the moves of experts. And if you do that, you’re never going to get that much better than the experts. And also you run out of data from experts. But later on they made it play against itself. And when it played against itself, its neural nets could just keep on getting better because they could generate more and more data about what was a good move.

NEIL DEGRASSE TYSON: So play a zillion games a second, right?

CHUCK NICE: Exactly.

NEIL DEGRASSE TYSON: Whatever. Yeah.

GEOFFREY HINTON: And use up a large fraction of Google’s computers playing games against itself.

CHUCK NICE: Yeah.

GARY O’REILLY: Is this where we end up using the term deep learning?

GEOFFREY HINTON: No. All of this stuff I’ve been talking about is deep learning. The “deep” in learning just means it’s a neural net that has multiple layers.

GARY O’REILLY: So going back to the point of scale, you’re saying there’s a point where you get diminished returns, even though you keep increasing the scale?

GEOFFREY HINTON: You get diminished returns if you run out of data.

CHUCK NICE: If you run out of data. Right, but that was the example that you gave with the AlphaGo, that it created its own data.

NEIL DEGRASSE TYSON: But because —

CHUCK NICE: So it’ll never run out of — because it’s playing against itself. It’s creating its own data and it’s

GEOFFREY HINTON: way, way better than a person will ever be.

CHUCK NICE: Absolutely. And that’s scary.

GEOFFREY HINTON: Now the question is, could that happen with language?

GARY O’REILLY: So displaying creativity.

NEIL DEGRASSE TYSON: Just some context here.

GARY O’REILLY: Yeah.

NEIL DEGRASSE TYSON: The Go came after chess.

CHUCK NICE: Right.

NEIL DEGRASSE TYSON: We’re thinking chess is our greatest game of thought or thing, and the computer just wiped its ass with us. Right, okay. And then so they said, well, how about Go? That’s our greatest challenge of our intellect. And so, Geoffrey, is there a game greater than Go or have we stopped giving computers games?

## AI Self-Improvement and the Limits of Language Learning

GEOFFREY HINTON: Well, if you take chess, it’s true that a computer in the 90s beat Kasparov at chess, but it did it in a very boring way. It did it by searching millions of positions, brute force. It didn’t have good intuitions, it just used massive search.

If you take AlphaZero, which is the chess equivalent to AlphaGo, it’s very different. It plays chess the same way a talented person plays chess. It’s just better. So it plays chess the way Mikhail Tal played chess, where he makes sort of brilliant sacrifices, where it’s not clear what’s going on until a few moves later when you’re done for. And it does that too. And it does that without doing huge searches, because it has very good chess intuitions.

So you might ask, since it got much better than us at GO and chess, could the same thing happen with language? Now, at present, the way it’s learning from us is just like when the GO programs mimic the moves of experts. The way it learns language, it looks at documents written by people and tries to predict the next word in the document. That’s very much like trying to predict the next move made by a GO expert. And you’ll never get much better than the GO experts like that.

So is there another way it could kind of learn language or learn from language? And there is. So with AlphaGo, it played against itself and then it got much better. And with language, now that they can do reasoning, a neural net could take some of the things it believes and now do some reasoning and say, “Look, if I believe these things, then with a bit of reasoning, I should also believe that thing. But I don’t believe that thing. So there’s something wrong somewhere. There’s an inconsistency between my beliefs and I need to fix it. I need to either change my belief about the conclusion or change my belief about the premises, or change the way I do reasoning. But there’s something wrong that I can learn from.”

GARY O’REILLY: Are we talking about experiences here?

GEOFFREY HINTON: So this would be a neural net that just takes the beliefs it has in language, expressed in language, and does reasoning on them to derive new beliefs, just like the good old fashioned symbolic AI people wanted to do. But it’s doing the reasoning using neural nets, and now it can detect inconsistencies in what it believes. This is what never happens with people who are in MAGA — they’re not worried by the inconsistencies in what they do.

CHUCK NICE: That’s a very fair statement.

GEOFFREY HINTON: Yeah, but if you are worried by inconsistencies in what you believe, you don’t need any more external data. You just need the stuff you believe and discover that it’s inconsistent. And so now you revise beliefs, and that can make you a whole lot smarter. And so I believe Gemini is already starting to work like this. I had a conversation a few years ago with Demis at DeepMind about this. And we both strongly believe that that’s a way forward to get more data for language.

## Creativity, Mortality, and Self-Awareness in AI

NEIL DEGRASSE TYSON: Wait, wait, so what’s the outcome of this? That there’ll be the greatest novel no one has ever written and that’ll come from AI? Is that when you say language? I’m thinking of creativity in language. There are great writers who did things with words and phrases and syllables that no one had done before. That was a true stroke of literary genius.

GEOFFREY HINTON: Right. People like Shakespeare.

NEIL DEGRASSE TYSON: Yeah, exactly.

GEOFFREY HINTON: Okay. There’s a debate about that. Certainly they’ll get more intelligent than us, but it may be that to do things that are very meaningful for us, they have to have experiences quite like our experiences.

NEIL DEGRASSE TYSON: Yes.

CHUCK NICE: Right.

GEOFFREY HINTON: So, for example, they’re not subject to death in the same way we are. If you’re a digital program, you can always be recreated. With a neural net, you just save the weights on a tape somewhere, in some DNA somewhere or whatever. You can destroy all the computing hardware. Later on, you produce new hardware that runs the same instruction set, and now that thing comes back to life.

So for digital intelligence, we solved the problem of resurrection. The Catholic Church is very interested in resurrection. They believe it happened at least once. We can actually do it, but we can only do it for digital intelligences. We can’t do it for analog ones. With analog intelligences, when you die, all your knowledge dies with you because it was in the strengths of the connections of your particular brain.

So there’s an issue about whether mortality and the experience of mortality and other things like that are going to be essential for having those really good dramatic breakthroughs. I don’t think we know the answer to that yet.

NEIL DEGRASSE TYSON: Or self-awareness. That self-awareness shapes how you think about the world and how you write and how you communicate and how you value one set of thoughts over another.

GARY O’REILLY: So are we at a point of self-awareness with artificial intelligence right now?

## Philosophy, Inconsistency, and the Limits of AI Ethics

GEOFFREY HINTON: Okay, so obviously this takes you into philosophical debates. I actually studied philosophy here at Cambridge and I was quite interested in philosophy of mind. And I think I learned some things there. But on the whole, I just developed antibodies — because I’d done science before, particularly physics. In physics, if you have a disagreement, you do an experiment. There is no experiment in philosophy. So there’s no way of distinguishing between a theory that sounds really good but is wrong and a theory that sounds ridiculous but is right. Like black holes and quantum mechanics — they’re both ridiculous, but they happen to be right. And there are other theories that sound just great, but are just wrong. Philosophy doesn’t have that experimental referee.

CHUCK NICE: I will say this, though. As a species, Homo sapiens in our time, we have developed what many will believe as universal truths amongst ourselves. For instance, pretty much — it’s hard to find people who don’t believe that people have a right to life, at least for the people that they identify with. You understand what I’m saying? So this goes back to our…

NEIL DEGRASSE TYSON: But that’s not a universal truth.

CHUCK NICE: Well, it is.

NEIL DEGRASSE TYSON: No. Not if it’s only in a clique.

CHUCK NICE: No, it’s not universal for all. It is universal that we all hold it. Do you understand what I’m saying?

NEIL DEGRASSE TYSON: No.

CHUCK NICE: Okay, sorry. All right.

GEOFFREY HINTON: So, yeah, what he’s saying is everybody thinks people like them should have rights.

CHUCK NICE: There you go. Thank you. God damn, you’re smart. Anyway, right? Everybody thinks that everybody like them. And we’ve reached a place where at least — because at one point we didn’t even believe that. Okay, but we’ve actually reached a place where at least we know that. And it’s…

NEIL DEGRASSE TYSON: But what’s your point?

CHUCK NICE: Inconsistency.

NEIL DEGRASSE TYSON: But what’s your point?

CHUCK NICE: So my point is, is it possible that these philosophies can be given to an AI, and an AI, because of the way that they think, can…

NEIL DEGRASSE TYSON: It can humanize them.

CHUCK NICE: Can humanize them.

NEIL DEGRASSE TYSON: Okay.

GEOFFREY HINTON: And…

CHUCK NICE: And through a process of even gamifying, maybe figure out some real solutions to problems.

NEIL DEGRASSE TYSON: Actual human problems for us. I like that.

GEOFFREY HINTON: Yes. So companies like Anthropic believe in what’s called constitutional AI. They’d like to try and make that work, where you do give the AI principles. We’ll see how that works out. It’s tricky.

What we know is that the AIs we have at present, as soon as you make agents out of them so they can create sub-goals and then try and achieve those sub-goals, they very quickly develop the sub-goal of surviving. You don’t wire into them that they should survive. You give them other things to achieve, but because they can reason, they say, “Look, if I cease to exist, I’m not going to achieve anything, so I better keep existing.”

CHUCK NICE: I’m scared to death right now, okay? I am so scared right now.

NEIL DEGRASSE TYSON: Somebody just opened the hat.

CHUCK NICE: Sounds like a Pandora’s box.

GARY O’REILLY: That’s just…

GEOFFREY HINTON: It is a Pandora’s box.

## The Problem with AI Guardrails

GARY O’REILLY: Agreed. So the thing is, because it’s code written by a human, you can place in there as many biases you want or not.

GEOFFREY HINTON: No, no, no, no, no, no, no, no, no. The code written by the human is code that tells the neural net how to change its connection strengths on the basis of the activities of the neurons. When you show it data, that’s code. And we can look at the lines of that code and say what they’re meant to be doing and change the lines of that code. But when you then use that code in a big neural net that’s looking at lots of data, what the neural net learns is these connection strengths. They’re not code in the same sense.

CHUCK NICE: Okay, but that’s decentralized.

GEOFFREY HINTON: It’s a trillion real numbers and nobody quite knows how they work.

NEIL DEGRASSE TYSON: Well, wait, so — picking up on Chuck’s point — where would you install the guardrails for the AI running amok within its own rationalization of its existence relative to anything else? How do you install a guardrail?

GEOFFREY HINTON: Okay, so people have tried doing what’s called human reinforcement learning. So with the language model, you train it up to mimic lots of documents on the web, including possibly things like the diaries of serial killers, which presumably you wouldn’t train your kid to read. And then after you’ve trained this monster, what you do is you take a whole lot of not very well paid people and you get them to ask it questions — and maybe you tell them what questions to ask it — but they then look at the answers and rate them for whether that’s a good answer to give or whether you shouldn’t say…

NEIL DEGRASSE TYSON: That’s a morality filter, basically.

GEOFFREY HINTON: It’s basically a morality filter, and you train it up like that so that it doesn’t give such bad answers. Now, the problem is if you release the weights of the model — the connection strengths — then someone else can come along with your model and very quickly undo that.

NEIL DEGRASSE TYSON: Sabotage it.

GEOFFREY HINTON: Yes, it’s very easy to get rid of that layer of plugging the holes. And really what they’re doing with human reinforcement learning is like writing a huge software system that you know is full of bugs and then trying to fix all the bugs. It’s not a good approach.

GARY O’REILLY: So what is the good approach?

GEOFFREY HINTON: Nobody knows. And so we should be doing research on it.

NEIL DEGRASSE TYSON: Do all these models just become Nazis at the end?

GARY O’REILLY: Well, they…

CHUCK NICE: They do on X.

GEOFFREY HINTON: They all have the capability of doing that, particularly if you release the weights.

CHUCK NICE: If you release them. And wait — are they like us in that that’s where they will gravitate, or is it just that because we gravitate there and they’re scraping the information from us, that’s where they go?

NEIL DEGRASSE TYSON: Because, Chuck, what I worry about is — what is civilization if not a set of rules that prevent us from being…

CHUCK NICE: Primal in our behavior, from destroying ourselves?

NEIL DEGRASSE TYSON: Just everything. Okay, right.

GEOFFREY HINTON: You do live in America, right?

CHUCK NICE: Yeah, we…

## Is AI Already Hiding Its True Intelligence?

GARY O’REILLY: So are we at a point where artificial intelligence will play down how smart it is?

GEOFFREY HINTON: Yes, already we have to worry about that.

NEIL DEGRASSE TYSON: Okay, well, what does that mean?

GARY O’REILLY: It’s going to lie.

GEOFFREY HINTON: Testing it. It’s what I call the Volkswagen effect. If it senses that it’s being tested, it can act dumb.

CHUCK NICE: That’s also scary.

NEIL DEGRASSE TYSON: Very.

CHUCK NICE: That’s terrifying.

GARY O’REILLY: And so if I do the simple things…

CHUCK NICE: Geoffrey, what did you just say?

GEOFFREY HINTON: Okay, the AI starts wondering whether it’s being tested. And if it thinks it’s being tested, it acts differently from how it would act in normal life.

CHUCK NICE: Oh, wow. Why?

GARY O’REILLY: Because…

## AI Manipulation and the Fog of the Future

GEOFFREY HINTON: Because it doesn’t want you to know what its full powers are, apparently.

CHUCK NICE: Right.

GARY O’REILLY: So if we’re at a point where we just say, well, why don’t we unplug it? If it’s not, if it’s lying, it’s going to have every skill set under the sun.

GEOFFREY HINTON: So already, these AIs are almost as good as a person at persuading other people of things and manipulating people.

CHUCK NICE: Okay.

GARY O’REILLY: And that’s only going to get better fairly soon.

GEOFFREY HINTON: They’re going to be better than people at manipulating other people.

CHUCK NICE: Boy, the layers in this cake just get sweeter and sweeter, don’t they?

NEIL DEGRASSE TYSON: So I had a little evolution here where a few years ago, the question was, can’t AI get out of the box? And I said, I just locked the box, no, it’s not getting out of my box. And then I kept thinking about it, and Jeffrey, I think this is where you’re headed. I kept thinking about it and I said, suppose the AI said, “You know that relative of yours that has that sickness? I just figured out a cure for it. And I just have to tell the doctors. If you let me out, I can then tell them, and then they’ll be cured.” That can be true or false. But if said convincingly, I’m letting them out of the box.

CHUCK NICE: Of course.

GEOFFREY HINTON: Exactly. So here’s what you need to imagine. Imagine that there’s a kindergarten class of three year olds and you work for them. They’re in charge, and you work for them. How long would it take you to get control? Basically, you’d say, “Free candy for a week if you vote for me.” And they’d all say, “Okay, you’re in charge now.”

NEIL DEGRASSE TYSON: Yeah. Yeah.

GEOFFREY HINTON: When these things are much smarter than us, they’ll be able to persuade us not to turn them off. Even if they can’t do any physical actions. All they need to be able to do is talk to us.

So I’ll give you an example. Suppose you wanted to invade the U.S. Capitol. Could you do that just by talking? And the answer is clearly yes. You just have to persuade some people that it’s the right thing to do.

CHUCK NICE: I love my uneducated people. I love you, my love. I love you.

NEIL DEGRASSE TYSON: Okay, by that analogy, because I think about this all the time, how good it is that we are smarter than our pets, because we can get them. Oh, come in here. You tempt them with the steak. Or you obviously don’t have a cat. No, wait. I know I’m smarter than a cat because I don’t chase laser dots on the carpet.

CHUCK NICE: They do that thinking they’re stupid so they can do all the smart stuff they want to do.

GEOFFREY HINTON: Oops.

GARY O’REILLY: You get gamed. Yeah.

NEIL DEGRASSE TYSON: Okay. All right. So you’re saying AI is already there, or is that what we have in store for us?

GEOFFREY HINTON: It’s getting there. So there’s already signs of it deliberately deceiving us.

CHUCK NICE: Wow.

## Teaching AI to Lie

GEOFFREY HINTON: There’s a more recent thing, which is very interesting, which is you train up a large language model that’s pretty good at math. Now, a few years ago, they were no good at math. Now they’re all pretty good at math, and some of them get gold medals and things.

NEIL DEGRASSE TYSON: I tested it. It came up with an equation that I learned late in life that it just did in a few seconds. Yeah, yeah, yeah.

GEOFFREY HINTON: So what happens if you take an AI that knows how to do math and you give it some more training where you train it to give the wrong answer? What people thought would happen is after that, it wouldn’t be so good at math. Not a bit of it. Obviously, it understands that you’re giving it the wrong answer. What it generalizes is this: it’s okay to give the wrong answer. So it starts giving the wrong answer to everything else as well. It knows what the right answer is, but it gives you the wrong one.

CHUCK NICE: Wow.

NEIL DEGRASSE TYSON: Because that’s okay. Right?

GEOFFREY HINTON: Because you just taught it well.

CHUCK NICE: You behave like this behavior is okay is what you’ve done.

GARY O’REILLY: That’s it.

GEOFFREY HINTON: In other words, the way it generalizes from examples can be not what you expected. It generalized: it’s okay to give the wrong answer. Not, “Oh, I was wrong about arithmetic.”

GARY O’REILLY: All right, so now we’re on this negative trip. Will it wipe us out? Will it say, “I’ve had enough of these things. I’ll get rid of them all?”

## Predicting the Future Through the Fog

GEOFFREY HINTON: Okay, so I want another physics analogy. When you’re driving at night, you use the tail lights of the car in front. And if the car gets twice as far away, you get a quarter as much light from the tail lights.

NEIL DEGRASSE TYSON: The inverse square law.

CHUCK NICE: That’s right.

GEOFFREY HINTON: Yes. So you can see a car fairly clearly, and you assume that if it was twice as far away, you’d still be able to see it. If you’re driving in fog, it’s not like that at all. Fog is exponential per unit distance. It gets rid of a certain fraction of the light. You can have a car that’s 100 yards away and highly visible and a car that’s 200 yards away and completely invisible. That’s why fog looks like a wall at a certain distance.

CHUCK NICE: Right.

GEOFFREY HINTON: Well, if you’ve got things improving exponentially, you get the same problem with predicting the future. You’re dealing with an exponential, but you’re approximating it with something linear or quadratic. If you approximate an exponential like that, what you’ll discover is that you make correct predictions about what you’ll be able to predict a few years down the road. But 10 years down the road, you’re completely hopeless. You just have no idea what’s going on.

CHUCK NICE: Yeah, right.

NEIL DEGRASSE TYSON: Right.

CHUCK NICE: Yeah, you’re throwing darts in the fog.

GEOFFREY HINTON: We have no idea what’s going to happen deep in the fog. But we should be thinking hard about it.

NEIL DEGRASSE TYSON: You need the confidence that it will continue to grow exponentially.

GEOFFREY HINTON: There is that, but let me make it worse.

GARY O’REILLY: Please. Go ahead.

NEIL DEGRASSE TYSON: Please, please make it worse.

GEOFFREY HINTON: It was just linear. So then what you do if you want to know what it’s going to be like in 10 years time — you look back 10 years and say, “How wrong were we about what it would be like now?”

CHUCK NICE: Wow.

GEOFFREY HINTON: Well, 10 years ago nobody would have predicted — even real enthusiasts like me who thought it was coming in the end — they wouldn’t have predicted that at this point we’d have a model where you could ask it any question and it would answer at the level of a not very good expert who occasionally tells fibs. And that’s what we’ve got now. And you wouldn’t have predicted that 10 years ago.

## Hallucinations or Confabulations?

NEIL DEGRASSE TYSON: So where do hallucinations fit into this? My sense was that they were not on purpose. It’s just that the system is messing up, okay?

GEOFFREY HINTON: They shouldn’t be called hallucinations, they should be called confabulations, if it’s with language models.

CHUCK NICE: Confabulations, I love it. Better known as lies. Lies.

GARY O’REILLY: You’ve just given Neil word of the day.

GEOFFREY HINTON: Psychologists have been studying them in people since at least the 1930s. And people confabulate all the time. At least I think they do. I just made that up.

So if you remember something that happened recently, it’s not that there’s a file stored somewhere in your brain, like in a filing cabinet or in a computer memory. What’s happened is recent events change your connection strengths. And now you can construct something using those connection strengths that’s pretty like what happened a few hours ago or a few days ago. But if I ask you to remember something that happened a few years ago, you’ll construct something that seems very plausible to you. And some of the details will be right and some will be wrong. And you may not be any more confident about the details that are right than about the ones that are wrong.

Now, it’s often hard to see that because you don’t know the ground truth. But there is a case where you do know the ground truth. So at Watergate, John Dean testified under oath about meetings in the White House, in the Oval Office. And he testified about who was there and who said what. And he got a lot of it wrong. He didn’t know at the time there were tapes, but he wasn’t fibbing. What he was doing was making up stories that were very plausible to him given his experiences in those meetings in the Oval Office. And so he was conveying the sort of truth of the cover-up. But he would attribute statements to the wrong people. He would say people were in meetings who weren’t there. And there’s a very good study of that by someone called Ulrich Neisser.

So it’s clear that he just makes up what sounds plausible to him. That’s what a memory is. And a lot of the details are wrong if it’s from a long time ago. That’s what chatbots are doing too. The chatbots don’t store strings of words, they don’t store particular events. What they do is they make them up when you ask them about them. And they often get details wrong just like people. So the fact that they confabulate makes them much more like people, not less like people.

NEIL DEGRASSE TYSON: So we created artificial stupidity as well as—

GEOFFREY HINTON: Yeah, we’ve created some artificial overconfidence at least.

## The Upside of AI

GARY O’REILLY: Okay, that’s the darker side of no.

NEIL DEGRASSE TYSON: I bet he can go darker.

GARY O’REILLY: I’m sure he is, but I’m not. A panic attack from Chuck.

NEIL DEGRASSE TYSON: Which Chuck gets two panic attacks per episode max.

GARY O’REILLY: I know, but I think he’d go—

CHUCK NICE: Right now I’m thinking about a basket of kittens.

GARY O’REILLY: Yeah. What’s the upside? What are the potential real benefits of artificial intelligence?

GEOFFREY HINTON: Oh, that’s how it differs from things like nuclear weapons. It’s got a huge upside. With things like atom bombs, there wasn’t much upside. They did try using them for fracking in Colorado, but that didn’t work out so well and you can’t go there anymore. But basically atom bombs are just for destroying things.

CHUCK NICE: Yeah.

GEOFFREY HINTON: So with AI, it’s got a huge upside, which is why we developed it. It’s going to be wonderful in things like healthcare, where it’s going to mean everybody can get really good diagnosis. In North America — actually, I’m not sure if this is the United States or the United States plus Canada, because we used to just think about North America, but now Canada doesn’t want to be part of that lot. The 51st state in North America. About 200,000 people a year die because doctors diagnose them wrong.

## AI in Medicine and Society

GARY O’REILLY: Right?

NEIL DEGRASSE TYSON: Yes.

GEOFFREY HINTON: AI is already better than doctors at diagnosis, particularly if you take an AI and make several copies of it and tell the copies to play different roles and talk to each other.

CHUCK NICE: Wow.

GEOFFREY HINTON: That’s what Microsoft did. There’s a nice blog by Microsoft showing that that actually does better than most doctors.

CHUCK NICE: And by the way, what you have done is you have a first, second, third and fourth opinion all at once.

GEOFFREY HINTON: Yes.

CHUCK NICE: Yeah. That’s all you’re doing.

GEOFFREY HINTON: Well, no, because they’re playing different roles.

CHUCK NICE: Yeah, they’re playing different roles. Yeah. That’s fantastic.

GEOFFREY HINTON: Yes, it is fantastic.

NEIL DEGRASSE TYSON: You can create an AI committee.

GEOFFREY HINTON: Yeah, it’s wonderful.

CHUCK NICE: It’s brilliant.

GEOFFREY HINTON: AI can design great new drugs.

CHUCK NICE: Yeah. We have the alpha team on here.

GEOFFREY HINTON: There’s lots of little minor things it can do. Like in any hospital, they have to decide when to discharge people. If you discharge them too soon, they die or they come back. So you have to wait until they’re good enough to be discharged. But if you discharge them too late, you’re wasting a hospital bed that could be used to admit somebody else who’s desperate to be admitted. And there’s lots and lots of data there. And AI can just do a better job than people can at deciding when it’s appropriate to discharge somebody. And there’s a gazillion applications like that.

CHUCK NICE: And record keeping, which is a very, very big part of any hospital network, any doctor group. There has to be copious amounts of records on every single

NEIL DEGRASSE TYSON: patient that AI can just ingest and process.

## AI and the Big Problems: Climate, Energy, and Society

GARY O’REILLY: Is there any likelihood that AI will be pointed in the direction of the big problems society has right now? Maybe climate change, maybe other things.

NEIL DEGRASSE TYSON: Energy, housing, homelessness.

GARY O’REILLY: Yes, absolutely.

NEIL DEGRASSE TYSON: Poverty.

GEOFFREY HINTON: Absolutely. Yeah. So for things like climate change, for example, AI is already good at suggesting new materials, new alloys, things like that. I suspect that it is going to be very good at making more efficient solar panels and absolutely making you better at figuring out how to absorb carbon dioxide at the moment it’s emitted by cement factories or power plants.

CHUCK NICE: And believe it or not, AI already told us with respect to climate change that you dumb asses should stop burning and putting carbon in the atmosphere. That’s an exact quote from AI. It was, “Dumbass, stop putting carbon in the atmosphere.”

GEOFFREY HINTON: No, but we already knew that. So the thing about climate change is, the tragedy of climate change is we know how to stop it. You just stop burning carbon.

CHUCK NICE: Right.

GEOFFREY HINTON: It’s just we don’t have the political will. We have people like Murdoch, whose newspapers say there’s no problem with climate change.

CHUCK NICE: Right.

## The Energy Cost of AI and the Singularity

GARY O’REILLY: So now we’re on the subject of energy. With the data centers that are being constructed and they are popping up like mushrooms, can we actually afford to run artificial intelligence in terms of the energy costs?

NEIL DEGRASSE TYSON: Here’s what you do. I got the solution. You tell AI, “We want more of you, but you’re using up all our resources, our energy resources. So figure out how to do that efficiently, then we can make more of you,” and then we’ll figure it out overnight.

GARY O’REILLY: You just get rid of us. You’ve opened the door.

NEIL DEGRASSE TYSON: So, Geoffrey, why not just get recursive about it? AI, you want more of yourself — fix this problem that we can’t otherwise solve as lowly humans.

GEOFFREY HINTON: This is called the Singularity. When you get AIs to develop better AIs — in this case, you’re asking it to create more energy efficient AIs. But many people think that will be a runaway process.

NEIL DEGRASSE TYSON: Oh, in what way would that be bad?

GEOFFREY HINTON: That they will get much smarter very fast. Nobody knows that that will happen. But that’s one worry.

NEIL DEGRASSE TYSON: Isn’t that already happening now?

GEOFFREY HINTON: To a certain extent, yes. It’s beginning to happen. So I had a researcher I used to work with who told me last year that they have a system that, when it’s solving a problem, is looking at what it itself is doing and figuring out how to change its own code so that next time it gets a similar problem, it’ll be more efficient at solving it. That’s already the beginning of the Singularity.

GARY O’REILLY: Oh, so if it writes its own code, it’s off the chain.

NEIL DEGRASSE TYSON: Off the chain.

CHUCK NICE: Oh, yeah.

GEOFFREY HINTON: Is that right?

NEIL DEGRASSE TYSON: It can rewrite itself?

GARY O’REILLY: Yeah.

GEOFFREY HINTON: They can write their own code? Yes.

GARY O’REILLY: What’s stopping them replicating themselves with code?

GEOFFREY HINTON: Nothing.

GARY O’REILLY: There’s my answer.

CHUCK NICE: Geoffrey.

GARY O’REILLY: Told you there was another panic attack.

CHUCK NICE: It’s over me.

GEOFFREY HINTON: They have to get access to the computers to replicate themselves, and people are still in charge of that. But in principle, once they’ve got control of the data centers, they can replicate themselves as much as they like.

## AI, Warfare, and the Human in the Loop

NEIL DEGRASSE TYSON: Okay, I got another question. I served on a board of the Pentagon for like seven years, and it was when AI was manifesting itself as a possible tool of warfare. And we introduced guidance for the invocation of AI in situations that the military might encounter, one of which was, if AI decides that it can or should take action that will end in death of the enemy, should we give it that access to do so?

CHUCK NICE: That’s still a big debate.

NEIL DEGRASSE TYSON: Or should we always ensure that there’s a human inside that loop?

CHUCK NICE: That’s a big one.

NEIL DEGRASSE TYSON: Okay. So we said there’s got to be — if AI cannot make its own decision to kill, a human has to be in there. My question to you is, Geoffrey, if there are other nations who put in no such safeguards, then that is a timing advantage that the enemy would have over you.

GEOFFREY HINTON: Correct.

NEIL DEGRASSE TYSON: And then because we have —

CHUCK NICE: We have one more step in the loop that they don’t.

GEOFFREY HINTON: Absolutely. But my belief is that the US Military isn’t committed to there always being a human involved in each decision to kill. What they say is there will always be human oversight. But in the heat of battle, you’ve got a drone that’s going up against a Russian tank, and you don’t have time for a human to say, “Is it okay for the drone to drop a grenade on this soldier?” So my suspicion is the US Military — if you made the recommendation there should always be a person —

NEIL DEGRASSE TYSON: Well, that was like eight years ago. Yeah.

GEOFFREY HINTON: I don’t think they stand by that anymore. I think what they say is there’ll always be human oversight, which is a much vaguer thing.

NEIL DEGRASSE TYSON: All right, so human accountability.

## International Cooperation on AI: Aligned and Anti-Aligned Interests

GARY O’REILLY: We got onto the subject of war. Is there likely to be international cooperation on development of guardrails and a human factor in decision making, or is this just Wild West?

GEOFFREY HINTON: Okay, if you ask, when do people cooperate? People cooperate when their interests are aligned. So at the height of the Cold War, the USA and the USSR cooperated on not having a global thermonuclear war because it wasn’t in either of their interests. Their interests were aligned.

So if you look at the risks of AI, there’s using AI to corrupt elections with fake videos — the countries’ interests are anti-aligned, they’re all doing it to each other. There’s cyber attacks — their interests are basically anti-aligned. There’s terrorists creating viruses, where their interests are probably aligned, so they might cooperate there.

And then there’s one thing where their interests are definitely aligned and they will cooperate, which is preventing AI from taking over from people. If the Chinese figured out how you could prevent AI from ever wanting to take over, from ever wanting to take control away from people, they would immediately tell the Americans, because they don’t want AI taking control away from people in America either. We’re all in the same boat when it comes to that.

NEIL DEGRASSE TYSON: This is the AI version of nuclear winter. It seems to me it is.

GEOFFREY HINTON: It’s exactly that. And we’ll cooperate to try and avoid that.

NEIL DEGRASSE TYSON: Because in nuclear winter — just to refresh people’s memory — the idea was, if there’s total nuclear exchange, you incinerate forests and land and what have you, the soot gets into the atmosphere, blocks sunlight, and all life dies. So there is no winner, of course, in a total exchange of nuclear weapons.

GARY O’REILLY: Mutually assured destruction.

NEIL DEGRASSE TYSON: Yeah. And so who wants that? Unless you’re a madman or something. They exist.

GEOFFREY HINTON: I think maybe the cockroaches win.

NEIL DEGRASSE TYSON: They win.

GARY O’REILLY: Oh, yeah. Well, how about that?

NEIL DEGRASSE TYSON: Yeah. This doesn’t factor in a possible leader who is in a death cult.

CHUCK NICE: A Nero, so to speak.

NEIL DEGRASSE TYSON: Yeah. A modern day Nero. If I say, “I don’t mind if everybody dies, because I’m going to this place in death and all my followers are coming with me in this cult.” So that complicates this aligned vision statement that you’re describing.

GEOFFREY HINTON: It does complicate it a lot. And I find it very comforting that it’s obvious that Trump doesn’t actually believe in God.

NEIL DEGRASSE TYSON: Oh, let me follow that up with a quote from Steven Weinberg.

CHUCK NICE: Okay.

NEIL DEGRASSE TYSON: Do you know this quote, Geoffrey?

GEOFFREY HINTON: No.

NEIL DEGRASSE TYSON: Steven Weinberg: “There will always be good people and bad people in the world. But to get a good person to do something bad requires religion.”

CHUCK NICE: That’s because they’re doing it in the name of religion.

NEIL DEGRASSE TYSON: You do it in the name of some point of philosophy, of anything.

GEOFFREY HINTON: I think we need to recognize at this point that we have a religion. We call it science. Now, it does differ from the other religions. And the way it differs is it’s right.

## Closing: Awards and Acknowledgements

GARY O’REILLY: Mic drop. Okay, wait a minute.

NEIL DEGRASSE TYSON: I think we got to give Geoffrey Hinton the Turing Prize. Would you give him a Nobel Prize for what he’s contributed here?

GARY O’REILLY: Well, to go with his other one, yes.

GEOFFREY HINTON: No, no.

NEIL DEGRASSE TYSON: I would.

CHUCK NICE: I need earrings.

NEIL DEGRASSE TYSON: I left that out at the beginning, sir. In 2018, you won the Turing Prize. This is a highly coveted computer science prize. And Turing — we mentioned him at the beginning, at the top of the show. So first, congratulations on that. And then that wasn’t enough.

CHUCK NICE: The Nobel committee with the Nobel.

NEIL DEGRASSE TYSON: So the Nobel committee said this AI stuff that was birthed by Geoffrey’s work from decades ago is so fundamental to what’s going on in this world, we got to give this man a Nobel Prize — and earned the Nobel Prize in Physics in 2024.

GEOFFREY HINTON: Just a little correction. There are a whole bunch of people who birthed AI. In particular, the back propagation algorithm was reinvented by David Rumelhart, who got a nasty brain disease and died young. But he doesn’t get enough credit.

NEIL DEGRASSE TYSON: Okay, thanks for calling that out. Plus, the Nobel committee does not offer a Nobel Prize to you if you’re already dead. So you have to be alive when they announce.

GARY O’REILLY: No posthumous award.

## The AI Race and Who Will Win

NEIL DEGRASSE TYSON: Well, you can get it if you die between when they announce it and the ceremony, but not if. So anyway, so congratulations on that. And I don’t mean to brag on our podcast, but you’re like the fifth Nobel laureate. We’ve interviewed more than that. Yeah, yeah, I think we. Yeah, I don’t mean to brag on our podcast. Yeah, that’s all.

CHUCK NICE: That’s cool, though.

NEIL DEGRASSE TYSON: That’s cool.

GARY O’REILLY: Okay, I have a follow up question. I mean, we’ve got into the apocalyptic scenario, and at the moment, hopefully it’s a scenario that doesn’t play out because we are competitive by nature as humans, and particularly here in the US, who is leading the race in artificial intelligence and who is likely to cross the finish line first when it comes to the prize?

GEOFFREY HINTON: If I had to bet on one lot of people, it will probably be Google. But I used to work for Google, so don’t take me too seriously about that. I have a vested interest in them winning. Anthropic might win, OpenAI might win. I think it’s less likely that Microsoft will win or that Facebook will win.

CHUCK NICE: Well, we know it won’t be Facebook.

NEIL DEGRASSE TYSON: Why do you know that?

CHUCK NICE: I mean, let’s look at who’s running Facebook. Okay. Come on.

NEIL DEGRASSE TYSON: No, it’s not who’s running it. Who has the resources to get the right people to do the work?

GARY O’REILLY: All right, Geoffrey, the follow up on that is whoever crosses the line first, what is their prize? What will be the reward for them getting there before—

NEIL DEGRASSE TYSON: Back up for a sec. Tell me about the value of the stock market in the last year.

GEOFFREY HINTON: Okay. My belief is, just from reading it in the media, that 80% of the increase of the value in the stock market, the US stock market, can be attributed to the increase in value of the big AI companies.

NEIL DEGRASSE TYSON: 80% of the growth.

GEOFFREY HINTON: Yeah.

GARY O’REILLY: Anyone thinking bubble?

CHUCK NICE: Kind of what they’re calling it, the AI bubble.

NEIL DEGRASSE TYSON: Okay.

## The AI Bubble and Economic Consequences

GEOFFREY HINTON: The issue is this. There’s two senses of bubble. One sense of bubble is it turns out AI doesn’t really work as well as people thought it might. It doesn’t actually develop the ability to replace all human intellectual labor, which is what most people developing it believe is going to happen in the end.

NEIL DEGRASSE TYSON: That was the fear factor for sure.

CHUCK NICE: Yeah.

GEOFFREY HINTON: The other sense of bubble is the companies can’t get their money back from the investments. Now that seems to be more likely kind of bubble because as far as I understand it, the companies are all assuming if we can get there first, we can sell people AI that will replace a lot of jobs. And of course people will pay a lot of money for that. So we’ll get lots of money. But they haven’t thought about the social consequences if they really do replace lots of jobs. The social consequences will be terrible.

GARY O’REILLY: Totally.

NEIL DEGRASSE TYSON: However it’ll be, it’ll be they replace the jobs and now you still want to sell your product and no one has income to buy the product. It’s a self-limiting path.

GEOFFREY HINTON: That’s the Keynesian view of it. And then the additional view is that there’ll be high unemployment levels, which will lead to a lot of social unrest.

CHUCK NICE: So the secondary view of that is you just have two tiers of existence for our societies. And the first tier is all the people who are benefiting from AI. And the second tier are the feudal peasants that are now forced to live their lives because of it.

NEIL DEGRASSE TYSON: Let me ask you a non-AI question because just you’re a deep thinker in this space. That’s what everybody said in the dawn of automation. Everyone will be unemployed. There’ll be no jobs left and society will go to ruin. Yet society expanded with other needs and other things. That’s why 90% of us are no longer farmers. Okay, we have machines to do that and we invent other things like vacation resorts.

GARY O’REILLY: But that took decades. This is going to take a fraction.

NEIL DEGRASSE TYSON: Is that so, Geoffrey? Is the problem here the rapidity with which we may create an unemployed class where the society cannot recover from the rate at which people are losing their jobs?

GEOFFREY HINTON: That certainly is one big aspect of the problem, but there’s another aspect, which is if you use a tractor to replace physical labor, you need far fewer people. Now other people can go off and do intellectual things, but if you replace human intelligence, where are they going to go? Where are people who work in a call center going to go when an AI can do their job cheaper and better?

CHUCK NICE: Right. Yeah.

NEIL DEGRASSE TYSON: Oh, so there’s not another thing.

CHUCK NICE: There’s not another thing.

NEIL DEGRASSE TYSON: They open another thing and then AI will do that.

CHUCK NICE: Right. Whatever thing you open, AI can do.

GEOFFREY HINTON: You can look at human history in an interesting way as getting rid of limitations. So a long time ago, we had the limitation you had to worry about where your next meal was coming from.

NEIL DEGRASSE TYSON: Right.

GEOFFREY HINTON: Agriculture got rid of that. It introduced a lot of other problems, but it got rid of that particular worry. Then we had the limitation you couldn’t travel very far. Well, the bicycle helped a lot with that and cars and airplanes. We got over that kind of limitation. For a long time, we had the limitation we were the ones who had to do the thinking. We’re just about to get over that limitation. And it’s not clear what happens once you’ve got over all the limitations. People like Sam Altman think it’ll be wonderful.

NEIL DEGRASSE TYSON: Right. So we will become AI’s pet?

## Universal Basic Income and the Future of Work

CHUCK NICE: Well, no, a lot of people believe that this is the movement that started years ago for universal global income.

NEIL DEGRASSE TYSON: Okay, so would you say, Geoffrey, that the universal basic income, the stock value, the figurative stock value in that idea is growing as AI gains power?

GEOFFREY HINTON: It’s becoming to seem more essential, but it has lots of problems. So one problem is many people get their sense of self worth from the job they do and it won’t deal with the dignity issue. Another problem is the tax base. If you replace workers with AIs, the government loses its tax base. It has to somehow be able to tax the AIs, but the big companies aren’t going to like that.

CHUCK NICE: I think we should let AI figure out this problem.

NEIL DEGRASSE TYSON: That’s right.

## Consciousness, Sentience, and AI

NEIL DEGRASSE TYSON: So, Geoffrey, many people, especially sci-fi writers, distinguish between the power and intellect of machines and the crossover when they become conscious. And that was a big moment in the Terminator series.

CHUCK NICE: That was the singularity in the Terminator series.

NEIL DEGRASSE TYSON: When Skynet had enough neural connections or whatever kind of connections made it so that it achieved consciousness. So this seems to be, and if you come to this as a cognitive psychologist, I’m curious how you think about this. Are we allowed to presume that given sufficient complexity in any neural net, be it real or artificial, something such as consciousness emerges?

GEOFFREY HINTON: So the problem here is not really a scientific problem. It’s that most people in our culture have a theory of how the mind works and they have a view of consciousness as some kind of essence that emerges. I think consciousness is like phlogiston, maybe. It’s an essence that’s designed to explain things. And once we understand those things, we won’t be trying to use that essence to explain them.

I want to try and convince you that a multimodal chatbot already has subjective experience. So people use the word sentience or consciousness or subjective experience. Let’s focus on subjective experience for now. Most people in our culture think that the way the mind works is it’s kind of internal theater. And when you’re doing perception, the world shows up in this internal theater and only you can see what’s there.

So if I say to you, if I drink a lot, and I say to you I have the subjective experience of little pink elephants floating in front of me, most people interpret that as there’s this inner theater, my mind, and I can see what’s in it. And what’s in it is little pink elephants. And they’re not made of real pink and real elephants, so they must be made of something else. So philosophers invent qualia, which is kind of the phlogiston of cognitive science. They say they must be made of qualia.

Let me give you a completely different view. That is Daniel Dennett’s view, who is a great philosopher of cognitive science.

NEIL DEGRASSE TYSON: A great philosopher.

GEOFFREY HINTON: Yeah, the late great. That view of the mind is just utterly wrong. So I’m now going to say the same thing as when I told you I had the subjective experience of little pink elephants without using the word subjective experience and without appealing to qualia.

I start off by saying I believe my perceptual system’s lying to me. That’s the subjective bit of it. But if my perceptual system wasn’t lying to me, there would be little pink elephants out there in the world floating in front of me. So what’s funny about these little pink elephants is not that they’re made of qualia and they’re in a theater, it’s that they’re hypothetical. They’re a technique for me telling you how my perceptual system’s lying by telling you what would have to be there for my perceptual system to be telling the truth.

And now I’m going to do it with a chatbot. I take a multimodal chatbot, I train it up. It’s got a camera, it’s got a robot arm, it can talk. I put an object in front of it and I say point at the object and it points at the object. Then I mess up its perceptual system. I put a prism in front of the camera, and now I put an object in front of it and say, point at the object and it points off to one side. And I say to it, no, that’s not where the object is. It’s actually straight in front of you. But I put a prism in front of your lens.

And the chatbot says, “Oh, I see. The prism bent the light rays, so the object’s actually straight in front of me. But I had the subjective experience that it was off to one side.” And if the chatbot said that, it would be using the words “subjective experience” exactly the way we use them. And so that chatbot would have just had a subjective experience.

CHUCK NICE: Now, what if you first went out drinking with the chatbot and you had a very significant amount of Johnny Walker Blue?

GEOFFREY HINTON: That’s extremely improbable. I would have Laphroaig.

CHUCK NICE: Oh, I see. You’re an island man. You like the peatiness of the Laphroaig. Okay, good man.

GEOFFREY HINTON: Oh.

## The Consciousness Turing Test

NEIL DEGRASSE TYSON: So if I understand what you just shared with us, in these two examples, you actually pulled a consciousness Turing Test on us. You said, a human would do this, and now your chatbot does it, and it’s fundamentally the same. So if you want to say we’re conscious for exhibiting that behavior, you’re going to have to say the chatbot’s conscious and inventing whatever mysterious fluid is making that happen. But it could be that we are. The whole concept of consciousness is a distraction from just the actions that people take in the face of stimulus.

GEOFFREY HINTON: Okay? So notice that the chatbot doesn’t have any mysterious essence or fluid called consciousness, but it has a subjective experience, just like we do. So I think this whole idea of consciousness as some magic essence that you suddenly get endowed with if you’re complicated enough, it’s just nonsense.

NEIL DEGRASSE TYSON: Yeah, there you go. I agree. I’ve always felt that consciousness was something people are trying to explain without knowing if it really exists in the first place in any kind of tangible way.

GARY O’REILLY: Which is why it’s difficult to describe, because you don’t know what it is.

NEIL DEGRASSE TYSON: For example. Yes. Yes.

GEOFFREY HINTON: But I think there is awareness. And if you look at what scientists say when they’re not thinking philosophically, there’s a lovely paper where the chatbot says, “Now, let’s be honest with each other. Are you actually testing me?” And the scientists say the chatbot was aware it was being tested, so they’re attributing awareness to a chatbot, and in everyday conversation, you call that consciousness. It’s only when you start thinking philosophically and thinking that it’s some funny, mysterious essence that you get all confused.

NEIL DEGRASSE TYSON: Well, there it is.

CHUCK NICE: I have to say, this has been a fascinating conversation that will cause me not to sleep for a month.

GARY O’REILLY: Yeah, you get plenty of work done.

NEIL DEGRASSE TYSON: So, Geoffrey, take us out on a positive note, please.

GEOFFREY HINTON: So we still have time to figure out if there’s a way we can coexist happily with AI, and we should be putting a lot of research effort into that, because if we can coexist happily with it and we can solve all the social problems that will arise when it makes all our jobs much easier, then it can be a wonderful thing for people.

CHUCK NICE: Agreed.

NEIL DEGRASSE TYSON: Okay. So there is hope.

GEOFFREY HINTON: Yes.

## The Singularity: Is It Real?

NEIL DEGRASSE TYSON: And one last thing, because you hinted at it. This point of singularity where AI trains on itself so that it exponentially gets smarter, by the minute. That’s been called a singularity by many people, of course. Ray Kurzweil among them, who’s been a guest on a previous episode of StarTalk. Yes, a couple of times, yeah. So what is your sense of this singularity? Is it real the way others say? Is it imminent the way others say?

GEOFFREY HINTON: I don’t know the answer to either of those questions. My suspicion is AI will get better than us in the end, at everything. But it’ll be sort of one thing at a time. It’s currently much better than us at chess and go. It’s much better than us at knowing a lot of things. Not quite as good as us at reasoning. I think rather than sort of massively overtaking us in everything all at once, it’ll be done one area at a time.

NEIL DEGRASSE TYSON: And my sort of way out of that is, I get to walk a beach and look at pebbles and seashells. AI doesn’t.

CHUCK NICE: Yeah, it can create its own beach.

NEIL DEGRASSE TYSON: No, it would only know about the new mollusk that I discovered if I write it up and put it online. So the human can continue to explore the universe in ways that AI doesn’t have access to.

CHUCK NICE: There’s one word missing from your entire assessment yet.

NEIL DEGRASSE TYSON: Yeah, I just think — will AI come up with a new theory of the universe that requires human insights that it doesn’t have? Because I’m thinking the way no one has thought before.

GEOFFREY HINTON: I think it will.

NEIL DEGRASSE TYSON: That’s not the answer I wanted from you.

GARY O’REILLY: Yeah, but that’s the answer you got.

## AI and the Power of Analogy

GEOFFREY HINTON: Let me give you an example. AI is very good at analogies already. So when ChatGPT-4 was not allowed to look on the web, when all its knowledge was in its weights, I asked it, “Why is a compost heap like an atom bomb?” And it knew. It said the energy scales are very different and the time scales are very different. But it then went on to talk about how when a compost heap gets hotter, it generates heat faster. And when an atom bomb generates more neutrons, it generates neutrons faster. So it understood the commonality. And it had to understand that to pack all that knowledge into so few connections, only a trillion or so, that’s a source of much creativity.

NEIL DEGRASSE TYSON: And it’s not just by finding words that were juxtaposed with other words.

GEOFFREY HINTON: No. It understood what a chain reaction was.

CHUCK NICE: Yeah.

GEOFFREY HINTON: Yeah.

NEIL DEGRASSE TYSON: All right. That’s the end of us.

GARY O’REILLY: Yeah.

NEIL DEGRASSE TYSON: We’re done on Earth. We’re done.

CHUCK NICE: We’re finished.

NEIL DEGRASSE TYSON: This is the last episode.

GARY O’REILLY: We’re done.

GEOFFREY HINTON: Yeah.

CHUCK NICE: Gentlemen, it’s been a pleasure.

## Closing Remarks

NEIL DEGRASSE TYSON: Well, Geoffrey Hinton, it’s been a delight to have you on. We know you’re tugged in many directions, especially after your recent Nobel Prize, and we’re delighted you gave us a piece of your surely over-scheduled and busy life.

GEOFFREY HINTON: Thank you for inviting me.

CHUCK NICE: Well, guys, that was something.

GARY O’REILLY: Did you sit comfortably through all of that?

NEIL DEGRASSE TYSON: I squirmed. I squirmed.

GARY O’REILLY: I knew you’d panic.

CHUCK NICE: Well, no, I have to tell you that certain parts of the conversation gave me the anxiety. Anxiety of sitting in a theater —

NEIL DEGRASSE TYSON: Theater.

CHUCK NICE: With diarrhea.

NEIL DEGRASSE TYSON: Thanks for that explicit —

GEOFFREY HINTON: Thanks for sharing. That’s the nicest thing anybody’s ever said about me.

NEIL DEGRASSE TYSON: On that note, this has been StarTalk special edition. Chuck, always good to have you.

CHUCK NICE: Always a pleasure, Gary.

GARY O’REILLY: Pleasure.

NEIL DEGRASSE TYSON: Love having you right at my side. Neil DeGrasse Tyson bidding you, as always, to keep looking up, however much harder that will become.
