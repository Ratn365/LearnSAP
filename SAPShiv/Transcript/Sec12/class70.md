 
Go to 21 and start creating a purchase order.

4001.

For material.

Coffee, beans.

Quantity of 100 and we have created a for coffee beans and we have set the delivery tolerances in the

material master.

And if you go to the delivery.

You should see that the delivery tolerance should be 10%.

But I don't see a delivery tolerance here.

Why?

Because delivery tolerance not just comes from the material master.

If there is a delivery tolerance in the purchase info record that takes precedence over the materiel

masters delivery tolerance.

Let's check it for a second.

Do you want to save it?

No.

Go to logistics.

Middle management purchasing.

Master Data Info record.

And for 4001 vendor this coffee beans Chicago plant.

Click okay.

And in the second screen hit Enter again.

There is a field where you can set the delivery tolerance.

What's the delivery tolerance here?

Zero.

So that's the reason why you don't see delivery tolerance in the purchase order for this material vendor

combination.

What this means is delivery tolerance is not just set at the material master level.

It's also set at the purchase info record.

Right.

So this is given the first preference and if nothing exists here.

Then it goes here.

You want to see it in action.

Let's go change this change and set 5% here.

5% here.

Under delivery over delivery.

Right.

And save it.

Now let's go create a purchase order.

Of course, for coffee beans.

Quantity of 100.

DC 5% here.

That is coming, of course from the purchase info record that we have just set.

Right.

So that proves that the first preference is the purchase info record.

The data of under delivery and over delivery from the purchase info record gets pulled into the purchase

order for that material and vendor combination.

What happens if I delete this or if it does not exist?

Let's go see it.

Do you want to save it?

No.

Go to.

Flag for deletion.

Enter.

Complete info, record purchase log data doesn't matter.

Save it.

So this purchase info record is deleted.

Now let's go create this purchase order.

For coffee beans.

Quantity of 100.

Okay.

Go for the price because there is no purchasing for record.

It's asking me for the price.

Again, if there was a purchasing for record, it would have automatically picked it from there.

Enter a price of $10.

Now go to the delivery and you see the under delivery and over delivery tolerances are 10%.

Which is what we have set here.

So we have set to 10% and we have set this to 5%.

Remember now that the purchase info record is deleted.

It's picking up from the material master.

And that's why I said the second preference is the material master.

If it exists in the purchasing info record, it goes there.

If it does not, it falls back to the material master.

Well, now we know where the delivery tolerances are set and we also understand what the delivery tolerances

mean.

Now we just have to see it in action.

So what happens when the delivery tolerance is 10%?

Let's see it with the same example.

Let's order a PO for 100 kilos and set the delivery tolerance to 10%.

Right.

And then we're going to deliver first goods receipt of, say, 50 kilos and see what happens.

And then we're going to say.

Another 40 kilos, which will make it 90, by which point we would have received 90% of the goods.

Which means that we have achieved the 10% tolerance and then see what happens.

Ideally, the expectation is that by the time we achieve 90% of the goods, you know, the vendor does

not need to deliver further.

The item can be deemed as complete, right?

That's the intention.

We want to cut it off.

We don't need it anymore.

Let's see it in action.

It's the first step.

Create a pill for 100, Right.

We have it right here.

We created a pill for 100.

And we can save this.

Right.

Copy this.

Ctrl C.

Okay.

Now go to me.

Go.

It's not a return delivery.

It's goods receipt.

Against the PO control v.

So the first lot we are going to receive is for 50 kilos, right?

So go select a quantity of 50.

So the vendor is under delivering by 50.

That's fine.

We're going to say item.

Okay.

And we're going to receive it into the coffee storage location.

And save it.

Oh, let's open that.

Go to the delivery schedule.

And see the open quantity there.

50 Reasonable.

Right.

Go back and the second delivery is for 40.

So 50 plus 40 is 90 and 90 kilos should come right within that tolerance of 10% of 100.

Go to Amigo again for 40.

Goods receipt against the PO this time is calculated automatically that we need only 50, not 100.

Right, because 50 has already been delivered.

So it says there is only a provision for 50 more.

How much do you want to take?

Well, let's say the vendor did not give us 50.

He only gave us 40.

Right Where?

In the coffee bean storage location.

Click item.

Okay.

And save.

Now, by this time the vendor has delivered 50 plus, 40, 90 kilos, which falls within the 10% tolerance

limit that means.

That out of 100 he has delivered 90, which is within 10% of the tolerance limit.

So the open quantity should not be ten anymore because we don't need the remaining ten.

We can let it go.

If he delivers 100, it's fine.

If he delivers 90 also, it's fine.

That's what we are trying to say with delivery tolerance.

Now, we should not see the remaining ten as an open quantity.

100 -90 is ten, and that should not remain as an open quantity because we have set a delivery tolerance

of 10%.

Do we really see that?

Go back.

Open the PIO.

Go to delivery schedule and we still see an open quantity of ten.

Well, then what's the point in specifying an under delivery tolerance of 10%?

So we came back to the same shape.

There's no point.

So how to fix this?

Well in defining under delivery tolerances and over delivery tolerances in order for the system to deem

that as complete when the goods receipt falls within that tolerance.

There is a configuration that has to be set.

Where do we set that configuration?

SPRO, IMG.

Go to materials management.

And instead of going to purchasing, go to inventory because that's where it is set.

And go to goods receipt.

Set tolerance limits.

Well, once again, you don't have to remember this path.

Oops.

Looks like I went to the wrong path.

This is not the right path, okay?

This is the right path.

Set delivery completed indicator, click.

Okay.

And then this is my plant.

So you can set this parameter by plant.

Not all plants need to behave the same, right?

So for Chicago plant, we want to set the delivery complete indicator if the delivery falls within the

tolerance limit.

Okay, so now save it.

And save it as.

Because it's configuration and then you still see the open quantity, right?

Because the change in configuration does not affect current transactions, you got to start all over

again.

So what do we need to do?

Create a POA for 100 quantity and deliver only 90 of them.

Right.

So if you look at the delivery, you should see the 10% tolerance there, which is good and then save

it.

Copy the PO.

Okay.

Save the PO.

And then out of a quantity of 100.

Only deliver 90.

Well, we could split it up into 5040.

It doesn't matter, though.

We're only going to deliver a net of 90.

Right where?

Into the coffee storage location.

Click okay and save.

So out of 100, the vendor has delivered 90.

Now let's go back to the PIO and see if, based on the tolerance of 10%.

Right, does the system still show that there is an open quantity of ten?

Ideally, it should not.

Right.

So go to delivery schedule.

And what's the open quantity?

Zero.

So that means that out of 100, even if 90 was delivered, the system is deeming that line item as complete

because the delivery tolerance is 10%.

And in inventory management, we have configured the system for Chicago plant so that when the deliveries

or goods receipts fall within the tolerance limit, the system says, I'm fine with it, you don't need

to deliver more.

So let's look at that report.

M two.

L And for 4001.

Chicago plant.

See the nine five purchase order that we have just created did not turn up as an open order.

Why?

Because we have configured the system in such a way that when the deliveries or goods receipts reach

a certain threshold as defined by the under delivery, the system says, I'm good to go.

Now same thing happens with over delivery.

Meaning if we have set an over delivery tolerance of 10%, the vendor can deliver goods by up to 10%

more.

So instead of 100 kilos, if he can deliver 110 kilos.

Which is 10% more than what was created for in a purchase order.

That's still fine.

That's called as over delivery tolerance.

And of course, he's going to charge for 110 kilos or 90 kilos in case of under delivery.

All right.

So that is how you handle shortfall.

There were three methods like we discussed.

The first was marking the delivery as complete.

The second was to block that line item.

And the third is using delivery tolerances.

So this is the third method.

One, two and three.

Simple, right?

All right.

In the next chapter, we're going to talk about another interesting topic called return policy.