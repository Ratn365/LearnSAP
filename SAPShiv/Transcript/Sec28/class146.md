 
Transcript
Now say, for example, that I already have £500 of coffee or £500 of muffin in the stock, which is

my reorder point.

What if I run again?

Zero three.

Nothing happens, right?

We have seen that example when we tried to procure coffee beans.

So as long as that reorder point stock is there and we are planning that material based on reorder point,

it doesn't matter how many times you run a.

It's like.

My house is stocked.

And it doesn't matter how many times I go to the supermarket, I don't need stuff because I don't need

stuff.

I'm not going to buy anything.

What will trigger me to go to the supermarket and buy again?

Anything that makes the stock of this material to go below 500.

For example, if I have produced or procured £500 of coffee beans, keep it ready.

And.

I am consuming.

Let's say £100 of coffee.

What happens now?

If I run MRP MD zero three.

It should trigger a purchase order in case of coffee beans or a production order or plant order in case

of muffins so that it can cover this shortfall.

Right.

No.

These actions, like stock withdrawals, it could be internal consumption.

It could be a customer placing a sales order.

Any stock withdrawals.

Or.

Let's say we have created a PO and the PO has been cancelled for a variety of reasons.

He called and said, Hey, I cannot supply this week.

So the PO is canceled.

What do you do?

Any such kinds of things like cancellation or.

Stock withdrawals.

These kind of events.

Will trigger what I call a dirty flag.

So these things will trigger a dirty flag.

Events that signify that next time runs, something should change.

Right.

Let me give you an example for this.

Say, for example, you have determined in your home that you need £10 of wheat or wheat flour.

So you have raised a purchase order with Amazon.

And it's going to come sit in your pantry at some point in time.

What if the order got canceled because maybe because the credit card was declined at a later point or

maybe because of a variety of reasons?

So in cases like that, what do you want to do?

You want to plan again, isn't it?

So cancellation of EPO is a trigger point in my mind that, hey, Amazon has canceled my £10 of beet

order, so I need to replan it.

Or I have ordered £10 of wheat, but suddenly our wheat flour, let's say baking flour, and suddenly

there is a party or there is a birthday or something of that sort where I had to make or manufacture

100 muffins or 50 muffins in my house, which consumed some or all of the wheat that I have or wheat

flour that I have.

That is, again, a trigger for me to replan, right?

So where are these dirty flags stored?

These dirty flags are stored in something called as a planning file.

So a planning file transaction being MD 21.

Is where for every material plant combination dirty flax are stored.

And this dirty flag tells that next time runs.

You have to do all these equations again.

What's coming in?

What's going out?

What is the net that I have?

What is my reorder quantity?

All that calculation.

So it's a trigger for the bot run.

To start thinking again.

Hey, something has changed.

Go do your logic.

All right.

I'm not going to do anything with this production order.

But.

But let me just consume, like, £300 of coffee beans.

And see what happens.

Now if I go to 21.

For coffee.

Execute it.

Do you see these two indicators?

Net change planning.

Net change planning horizon.

These are the dirty flags that I was talking about.

So if they are dirty, if this material is dirty, that means the bot requires planning.

This will be set to X.

Now, since they are not set to x at this point, nothing is going to happen.

You want to test it?

Go to Md0 for.

Look at what's happening here.

There is a purchase requisition.

Okay, Now go run M03.

For coffee beans.

Enter.

Enter.

It must be carried out.

Now go to zero four again.

For coffee beans.

Is there a change?

No, there is no change.

Right.

Because nothing has changed.

So what I'm going to do is I'm going to withdraw.

A certain quantity of coffee beans, say 200, Right?

So coffee beans, 11 and a quantity of, let's say 300.

And they're going to be issued against the cost center.

All right.

So somebody in the company.

Is consuming £300 of coffee beans.

And let's say the admin department is consuming £3,000 of coffee beans.

So check if everything is okay and save it.

Now let's go to MD 21 and check the planning file for the same material.

You see the dirty flag on.

This means.

Now, don't worry about what each of these flags mean at this point.

What this means now is that the next time it runs looks at the dirty flags and sees that, hey, something

has changed, so I need to work accordingly.

I need to work my logic.

If there are no dirty flags, that means just looks at the dirty flags.

If there is no flag, it just ignores.

The run.

It just says, okay, I'm done.

But if it sees a dirty flag, that means that something has changed.

It needs to go rework his logic.

Now let's go to zero three.

Run!

For the same coffee beans material.

Hit Enter.

It must be carried out.

And let's see if something has changed in over.

We see that?

The purchase requisition.

Is changed from 100 to 400.

Earlier, the purchase requisition quantity was just 100 because 400 was available already and SAP is

placing an order for 100 more.

Now I have consumed.

300.

The purchase requisition has been changed to 400.

If you don't trust me on this, we can do something.

Let's go to go and consume 50 more pounds.

Of what?

Of coffee beans.

11 and quantity of 55.

Again, an odd number so that we can see what's really happening in the Chicago plant and coffee beans

storage location and that being consumed against, say, the admin cost center.

Okay.

So check if everything is okay.

Everything seems okay.

And before I do that, let me go to MD 21.

The planning file.

And show you that the dirty flags are off.

Okay.

The dirty flags are off.

They're not X anymore.

That means he has nothing to do now.

And save.

So we have consumed 55 in quantity of coffee beans, £55, let's say.

Now let's refresh this.

Dirty flags are on.

Now remember this quantity of 400.

This should increase by 55 because we have consumed 55.

Right.

So go back, open another window or in the same window.

Run Md0 three.

Now, because the dirty flags are on is going to run.

Enter.

It might be ran.

And over here, let me refresh this.

And you see this change for 55.

Right.

So we have learned two things here.

Or rather three things.

What is a planning file?

A planning file contains parameters.

Or what I call dirty flags that tell me to rework his magic.

And if the parameters are not there, the dirty flags are not there.

Just looks at the planning file.

Okay.

There's nothing to be done.

Just ignores it.

The second learning is if the dirty flags are on.

That means some withdrawals has happened or cancellations have happened.

Something has changed that triggers MRP not to run again, but to consider everything to be run again.

And when you run MRP.

MRP looks at the dirty flags and if the flags are dirty.

It.

Proceeds to run.

The process again.

If yes.

Run the process.

If no.

Exit.

The third learning is assuming that has run.

Depending on the settings, the elements, the elements like purchase requisition or planned order,

the quantity is changed.

For example, the original purchase requisition was for 400.

Now we have consumed 55 more.

So it has changed that same purchase requisition to 455.

It did not create a new purchase requisition.

Right.

Or new plant order.

It changed the existing elements.

Now this.

Is based on lot size.


