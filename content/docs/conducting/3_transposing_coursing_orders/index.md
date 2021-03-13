---
title: Transposing Coursing Orders
weight: 3
---

# Transposing Coursing Orders

You might've felt a bit suspicious in the last section about my proposed use for coursing orders in conducting. I suggested that if you know the coursing order, you can watch how you pass the bells around you and thereby set people straight if you are passing them in an order that is not the correct coursing order.

In the plain course, knowing the coursing order is as easy as memorizing a short string of numbers, often in a very pleasing order (with such helpful mnemonics as "up the odds, down the evens!"). The trick is knowing the coursing orders when you're 7 calls in to a quarter of Plain Bob, nowhere near the plain course. 

One way to do this is by straight memorization, and doing some memorization of coursing orders at certain signposts (e.g. the halfway point, or a particularly tricky section) can be useful. The more flexible but definitely harder approach is to learn how to transpose[^1] the coursing orders _as you ring and call_, so you can keep a constant check on the ringing as you go.

## Calls and coursing orders

Let's talk about a few common calls and how those affect the coursing order. We'll use Plain Bob Minor again as our example, because there's only a small number of bells to keep track of.

## Wrong

Below is a picture of two lead of Plain Bob Major, starting in the plain course with a coursing order of 5324. There is a bob called at Wrong; what's the resulting coursing order? Use the convention of giving the coursing order relative to the 6, but with the 6 omitted. When you've finished, scroll down to read more.

{{< textbox id="tra1" answer="3254" >}}
{{< figure src="wrong_bob.png" class="float-right" width=200px >}}
{{< /textbox >}}

In the example given above, the coursing order changed from 5324 (the plain course coursing order) to 3254. Notice that the 4 stayed in the same place, but the other bells swapped position. In particular, they swapped like this:

{{< figure src="transpose_wrong.png" class="center" width=100px >}}

So the bell in the "front" of the coursing order (the 5) got moved two places back and shuffled everything else around accordingly. Note that the 5 is actually the bell that made the bob! And the other two bells that "moved" in the coursing order were the other bells affected in the bob.


## Home

Let's try that trick again, but with a bob at Home. Remember to use the same convention as before: don't include the treble or the tenor in your coursing order answer.

{{< textbox id="tra2" answer="5243" >}}
{{< figure src="home_bob.png" class="float-right" width=200px >}}
{{< /textbox >}}

Here the coursing order changed from 5324 (the plain course coursing order) to 5243. Unlike in the bob at Wrong example, here the 5 stayed put and the other bells swapped around:

{{< figure src="transpose_home.png" class="center" width=100px >}}

Notice: the _number and direction_ of the arrows is the same, but the _bells to which they apply_ are different. So the different calling positions (where the tenor is unaffected) affect different sets of bells, but the bobs affect those bells in the same way. A bob in Plain Bob moves one bell behind its two right-most neighbors. This is true as long as the tenor is _not_ one of the bells affected in the bob, as you might imagine!

Notice that bobs affect three bells, in a cyclic way. What would happen if you called a bob at Home three times? You may remember the answer from earlier in _Calling It Round_, but writing it out is good practice. You'll find that the bells cycle back to the plain course coursing order after exactly 3 bobs. This feature of bobs affecting three bells in the coursing order is why bobs are commonly found in groups of three; it brings you back to where you started without repeating.


## Before

This is a slightly trickier case, because in a call at Before, the tenor _is_ affected; it runs out. Can you spot the coursing order after the bob at Before?

{{< textbox id="tra3" answer="5432" >}}
{{< figure src="before_bob.png" class="float-right" width=200px >}}
{{< /textbox >}}

Yes, here the coursing order changed from 5324 (the plain course coursing order) to 5432. I find this particular transposition is often confusing because there's so much happening in the calculation; even though the 5 _looks_ like it didn't move in the coursing order from the numbers on the page, it was involved in the bob --- and I just told you that the ones involved in the bob would be the ones that moved! What gives?

We can figure it out by looking at the _full_ coursing order, including the 6. Remember how we talked about the limitations of Western left-to-right notation? This is another time where we will run into that issue. Recall that we can write the coursing order 53246 (the plain course coursing order) as 32465 if it suits our fancy, because it's really a cycle of numbers and _not_ a line.
Here's what happened to the _full_ coursing order, including the 6:

{{< figure src="transpose_before.png" class="center" width=100px >}}

But since the 6 _moved_, when we re-write the coursing order using the convention that we put the 6 silently at the end, we go through the following process:

| Operation | Coursing order |
| --- | --- |
| [start in plain course] | 5324 |
| Add the 6 back in | 53246 |
| Put the 5 at the back because it's part of the bob, and it is easiest to visualize when it is next to the other bells that will be part of the bob (the 4 and 6) | 32465 |
| Bob at Before | 32654 |
| Move the 6 to the end | 54326 |
| Ignore the 6 (remove it) | 5432 |

So even though the 5 ran in at the bob, it looks "stationary" in the coursing order (using these common conventions).

Some people can do all of these transformations and operations in their head very quickly. It takes practice but it is possible! Others take some shortcuts, and I admit I am one when it comes to bobs at Before. I prefer to think of it as the 4 (who made the bob), "cutting in line" in front of the 3 and 2. This is _not actually what's happening_, since the 3 and 2 are not involved in the bob! But it makes for a quick mental transposition when ringing. Different people figure out different approaches that work for them.

## Single

The final thing we'll discuss in this section is the effect of a single at Home. the 6 is not affected, so we have a slightly easier job of things. See if you can work out the effect of the single at Home here. It starts in the plain course.

{{< textbox id="tra4" answer="5423" >}}
{{< figure src="home_single.png" class="float-right" width=200px >}}
{{< /textbox >}}

Here the coursing order changed from 5324 (the plain course coursing order) to 5423. That's new! Let's take a look at how the arrows go:

{{< figure src="transpose_single.png" class="center" width=100px >}}

Here, only _two_ bells are being swapped. That's because, at the call, two bells are being stopped from dodging with each other in 3 4 and are instead making places in 3 and 4. The bell in 2nds place is making seconds as usual, and the bells in the back are dodging as usual. So in Plain Bob, singles only affect _2 bells_. 

Take a moment and consider what happens if you ring two singles at Home. Write it out if you need to. That's right -- you end up back where you started. Two singles at Home will give you a true, two-course touch of Plain Bob Minor. The fact that singles affect _two_ bells in the coursing order by swapping them is why singles in compositions often come in pairs.

## Other things to know

I have covered a relatively limited set of information about transposition of coursing orders; just a few calling positions and two types of calls. But this should be enough to get you started! Just be aware that calls at different calling positions may affect the way the transposition works, especially when the heaviest bell is affected. Calls at the same calling position in a different method may affect the transposition differently! This is one of those things where you must be careful to know what effect the calls in your composition have on the bells. It will be easiest to work up to it from a limited number of calling positions and relatively little number of bells (Minor or Major).

## Coursing orders on higher numbers

In minor, it is common to write the coursing orders as 4-bell coursing orders, such as 5324, because that covers all of the working bells except the heaviest one. In major, even though you add _two_ bells, it is common to write a 5-bell coursing order, omitting both the 7 and the 8. So for example, the "usual" coursing order of bells in Plain Bob Major would be commonly written as 53246. There is an implied 7 and 8 in there (I usually think of it as [7]53246[8] but others prefer to think of it as [87]53246 --- it's all preference). 

On still higher stages like Royal or Maximus, it is still common to have only a 5 or 6 bell coursing order. This is because many composers choose to create compositions that only affect the "little bells" even when many bells are being rung. It saves space to write down only those bells which will actually be changing over the course of the composition. However, sometimes you will still see very large coursing orders given for larger stages.

## Resources

### Print

If you are looking for a book full of other exercises on transposing coursing orders in a variety of methods, John Longridge's _Conducting & Coursing Order_ is the best one I know. He uses a slightly different convention where the Plain Hunt coursing order is given as 8753246 (but most of the time, omitting the 8 and 7, so it looks like what we have covered here: 53246).

### Online

Once again I have an excellent set of blog posts from Simon Gay to recommend you (the end of the series on conducting techniques that I recommended before):

[Dynamic use of coursing order](https://www.handbellringing.co.uk/blog/conducting-techniques-3-dynamic-use-of-coursing-order)

[Static use of coursing order](https://www.handbellringing.co.uk/blog/conducting-techniques-4-static-use-of-coursing-order)

## Notes

[^1]:
	If transpose isn't a familiar word to you, here's a definition: transpose means to change things around. It can have a more technical meaning if you're using it in mathematics, but that's the general meaning. Changing bells from the order 243 to 234 is a transposition.