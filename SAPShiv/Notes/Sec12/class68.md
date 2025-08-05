 
So like we were discussing in the previous chapter, we have ordered for 100 kilos of flour.

And we got 100 kilos of flour.

The vendor did send 100 kilos of flour or coffee.

And of course, he sent an invoice for 100.

Very good.

But we found out that 50 was defective.

So we returned 50.

That means we only got a net of 50.

And.

The vendor issued a credit memo for 50.

So that settled.

But what about the original requirement of £100?

We needed £100 of coffee.

Right.

That's why we have ordered for 100.

But we lost 50 because of a quality issue.

So we need 50 more.

And that's what was reflected in the open quantity in SAP.

This guy over here, it says open quantity is 50.

Now, sometimes you might not require that 50.

You're like, okay, that's it, that's fine.

Let it go.

But the system does not let it go.

It says there is still an open quantity of 50.

Now.

What are the implications of that open quantity?

The implications are the PO still remains open.

It's not closed yet.

Meaning the pile is not complete because we have asked for 100.

And the vendor only delivered 50.

So we need 50 more.

Now, sometimes we might not require the 50 words we can say, Let it go.

We might not need the 50 now.

We can order it next month.

But the system does not know that.

The system thinks that we need £50 of coffee.

And in order to find out the open POS by vendor or by a number of other such criteria, you can go to

this transaction.

ME2LME2L

hit enter and select your vendor and in your scope of parameters, type in w e 101.

Right.

So this shows you the open goods receipt, meaning goods that we are yet to receive.

You can select one or more than one vendor and click execute.

Remember, our purchase order was for 50007193.

We go back here?

This is the PO.

450007193.

And it says 50 is still to be delivered and still to be invoiced.

And the original quantity was 100.

Right.

So this is a report that shows you all the open deliverables from a particular vendor.

Now we can let it remain open, meaning we need 50 more is the signal that we are giving the system.

And the system assumes that we need 50 more.

And the vendor also assumes that we need 50 more because we have ordered for 100.

He has delivered only 50 and 50 is yet to come in.

So far so good.

But like I said, sometimes we don't need the 50.

We might want to say, that's fine, we have enough for this month.

Let's cancel that remaining 50.

So how do you ensure that you close that 50 quantity of POA?

You no longer need it, right?

So there are a couple of ways to do it.

The easiest way to do it is to go to delivery.

And I'm sorry, I need to go to change mode.

Okay.

The easiest way to do it is to mark that delivery as complete that line items delivery as complete.

Right.

So let's do that.

Let's click delivery complete and save.

Right now if you go to the delivery schedule and open quantity here.

You see, this is blank.

Although the purchase order quantity is 100 and the goods receipt is 50.

Meaning we have asked for 100 and the vendor has delivered 50.

There is no open quantity.

Because we have marked that delivery as complete.

Now, if you go back to that report and re execute it like so you see that PO is gone.

The nine three PO is gone.

You no longer see it.

1991 There is no 93.

That means that the purchase order is no longer open.

Right?

This is one way to do it.

Another way to do it is to block that line item.

Like how?

Let me go back to display change of the.

Uncheck this flag, which means there's going to be an open quantity of 50.

Right, As usual.

Now you can select that line item like so and block it.

You see this lock?

So when you block it, see again, the open quantity is gone.

So what is the difference between blocking and marking the delivery as complete?

When you mark the delivery as complete.

Like here.

This means that you're saying my delivery is complete.

You no longer need to worry about it.

It's typically final.

You don't.

You don't change it ever.

Although you have the facility to change it.

But when you block it, this could be either temporary or permanent.

Although both achieve the same effect.

When you lock that line item, you're saying typically you temporarily block certain line items.

Why?

For example, there is a quality issue and you want to block all the line items in all the purchase

orders for that material.

You could block that.

Or.

Or you have already created a purchase order with coffee, flour, sugar, ten different kinds of materials.

But you want to temporarily stop the delivery of a particular material or or issuing the PO for that

line item.

Meaning.

There is coffee, there is sugar, there is flour.

Suddenly the warehouse guy comes up and says, Oh, we got enough flour or enough sugar, so don't order

that now, but maybe two days later.

So you have a choice.

You can delete that line item or you can block that line item like this.

This means that the delivery has not happened, but you are not going to issue that line item as a PO

to the vendor.

The rest of the line items are going to go as usual.

So it's a status flag.

It just says that, you know, your temporarily blocking it.

You could later unblock it like so.

So it's a temporary way of blocking items so that they are not acted upon further, either by us or

by the vendor.

But delivery complete is a deliberate way of saying, Hey, you know what, I think we are done with

this line item.

So if there is any shortfall, don't worry about filling it.

We are good.

Right.

So these are the two ways.

So there is another way.

So let's see what we have discussed.

We said that out of 150 remained open and in order to close them, there were three methods we have

discussed two of them.

One was to Mark.

The delivery is complete.

The second is to block.

The line item.

And we have seen the differences between these two.

In the next chapter, we are going to talk about something called as delivery tolerance.