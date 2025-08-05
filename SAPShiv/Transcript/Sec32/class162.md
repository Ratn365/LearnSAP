 

Lecture thumbnail
0:00 / 6:51
The fourth parameter is called the cross plant.

The X stands for Cross.

Material.

Status.

Is this field cross plant material status.

What's a cross plant?

Material status.

Let me show you some examples here.

Cross plan, material status and the options are obsolete.

Material blocked for casting.

Blocked for purchasing.

So it's branding this material as blocked for purchasing or blocked for procurement or obsolete material

free for pilot phase.

So it's again, a way to group materials based on some of the supply chain functionality.

One example is.

Let's say you have so many different materials, right?

So many different coffee beans.

And from January, let's say this is December, and from January, you want to block certain materials

from being procured because you don't want to deal with them.

You're phasing them out.

You're introducing a brand new material instead of that.

So coffee beans oh one is being phased out.

And in its place, coffee beans oh two is being procured and sold.

Now, nobody should be able to procure this material going forward or sell this material going forward.

Right now purely from a procurement perspective, because we are learning.

How do you stop all procurement of this material?

One way is to delete this material.

Or flag it for deletion.

We're going to see it in some of the next chapters.

How to delete and flag for deletion.

But that's not the correct way, at least in this case.

Why?

Because there are existing transactions that use this material.

Maybe it's only banned from a procurement perspective.

You still sell it?

That's possible, right?

So you don't want to delete this material.

You just want to mark it.

As not relevant for procurement.

Right.

In cases like that, you use the cross plan material status.

And the reason it's called Cross plant is because once you put that field or mark that material as marked

for procurement ban.

In that case, it affects all the plants, not just Chicago.

If you want to affect only Chicago, you got to go do it on the views.

Specify the plant and mark it for block procurement for Chicago plant only.

Now, in this case, if you mark it as blocked for procurement, say blocked for purchasing.

Right.

Save it.

So material master changed.

Now if you go to 21 and.

Pewter vendor 4001.

And do coffee beans or one.

Enter.

You see that status blocked for purchasing, so it does not allow you to procure coffee beans.

The material still exists and any existing material receipts like you have already ordered for coffee

beans, well, you can receive them.

Go to my go to see the materials.

No problem.

Go to my room.

Receive the invoice for coffee beans one.

No problem.

All existing transactions will run fine.

Only new purchase orders will be blocked.

And that's the intent, right?

Today is December 15th.

We want to block all purchases going forward because from Jan first, we're going to go with a brand

new material.

Sure all new purchases will be stopped.

All existing transactions could go on even after December 31st.

No problem.

So that's cross plant material status now.

So go to SPRO, IMG Logistics, General.

And material master.

Tools or settings for key fields.

Define material statuses.

Right.

What did we use?

We said block for purchasing.

This is the one that we've used, right?

So select that, click on details.

And here are the different areas that you can block the material.

Now think of different scenarios.

You could block that material from purchasing.

Yes.

And that's what we have seen here, purchasing.

Is B.

B means it's an error message.

You don't want to ever procure anything of this material.

You could make it a warning, in which case it will warn the person procuring this material, but it

will not stop him.

Maybe it's not a hard stop.

It's going to be phased out.

So you just want to warn the person purchasing the goods or the planner to stop procuring this going

forward.

Right.

So hard.

Stop versus soft stop.

It's not just purchasing.

What about production?

If you are producing something, don't ever produce this material.

You could do that.

Production order.

Warning or error.

Right?

You could want a material to be blocked both for purchasing and production, in which case you'll mark

this as B and you'll mark this as B.

Now you can go to a production order, try to produce something.

Well, coffee beans, we don't produce.

But think of another material, say a bakery related material as a cookie.

Coconut cookie.

And coconut glue is banned from purchasing because it's going to be phased out.

And it's also going to be banned from producing, in which case you mark this also as be.

And same thing with the other functional areas, you know, for warehouse management, inventory management,

so on and so forth, depending on what are the different functional areas, you want to stop transacting

with this material, you go and create a new material status.

Mark all the appropriate functional areas as either a warning or an error, save it and apply that to

the material.

That's it.