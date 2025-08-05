 
Transcript
The third constraint is a little more involved.

Okay.

Let me give you an example.

The third constraint is called freezing.

Book inventory.

With this method.

You can allow goods, receipts and goods issues and still keep counting.

Why?

Or rather, how?

How does the system allow that?

Now, let me give you an example.

So this is our plant, our storage location or warehouse?

In Chicago.

And this is a store in Chicago on Michigan Avenue, let's say.

Now imagine there are 20 stores like that.

So each store at least will consume 100 to £200 of coffee.

So there are 20 stores.

The total consumption of coffee is 20 into 200, that is.

£4,000.

That's a lot of coffee, right?

And you got to have a storage of at least ten days or 20 days worth of coffee, let's say ten days.

For ten days.

That's £40,000 of coffee.

Stored in a central storage location or plant.

£40,000 of coffee.

And if you want to count, can you count?

£40,000 of coffee in one hour?

Not possible.

Right?

Or even one day.

Sometimes it's not possible.

Two days, let's say.

Now for two days.

You cannot do a goods receipt or a goods issue.

If you do goods, receipt goods issue, things are confusing.

You know, things come in, things go out.

You don't know what's really happening.

So in situations like that, it makes no business sense to stop transactions like issuing of goods to

the customer or receiving goods from the warehouse or receiving goods from the vendor when the truck

comes in with loads of coffee.

Now in situations like that.

Now there is a functionality here in SAP called freezing of book inventory.

Okay.

Let me give you an example of how this works.

So this is our warehouse, right?

And a particular lot.

Let us say let me maximize this so you understand that.

This is the lot or the rack or the shelf where coffee is stored.

Okay.

And in that lot or shelf.

You wicket a small lot like this.

Okay.

And dedicate this for all new goods, receipts or goods issues.

Okay, so you're not going to do any activity of counting this step?

It's all free.

It's all blank.

Meaning you have emptied this particular rack.

And dedicated that for all new goods, receipts or new goods issues that happen when you start the count.

Now you have 40,000.

Pounds of coffee to count in these racks.

Okay.

So typically.

When you start counting £40,000 of coffee, the bulk of your job will be focused on counting the existing

inventory.

Right.

So you don't need to lock or block the stock that is needed, right?

Maybe you can just put some £200 here that you think is required for goods issues.

Okay, so you don't need to lock the rest of the inventory.

So the business can continue as usual.

So goods issues can happen, new goods receipts can happen.

So essentially what you're doing is blocking a location and blocking some stock so that business can

continue as usual.

But still, you can keep counting.

Okay.

Let me give you an example.

On Jan first.

As.

This is book versus this is physical.

There is £100 of stock.

Right.

So you create a pie and then freeze the inventory.

Well, you started counting at 10:00.

There is a goods issue or a goods receipt, say £25 or £2500 of coffee came in and you're going to put

that in this special lot.

So it's not going to disturb the rest of your counting.

And at 5 p.m., let's say you finish the inventory counting and finally found out that instead of 100,

there is only £80, right?

There is only £80.

So £80 of physical inventory.

And on 6 p.m., let's say before you go home.

You post the difference?

So initially SAP thinks that there is £100, but you have only found out £80.

So there is a difference of 20.

So 100 is book inventory.

Physical inventory is 80.

So the difference is 20 that's posted.

To inventory loss account and the book inventory will be adjusted to 8100 -20 is 80.

What happens to this inventory?

£25 that has come in during your counting process?

Because you've frozen the book inventory.

Until 6 p.m. any time you check the inventory and it's still going to be £100.

But once you post the difference, this 25.

Will be added to 80 and the total inventory will now become 80 plus 25.

That is 105.

This way you can ensure that goods, receipts and goods reissues can happen as usual.

At least goods receipts.

And you can still keep counting.

Freeze the book inventory so that no changes will happen to the book inventory.

And finally, the additional stock that has been received can be added after the counting is been done

and the book inventory can be updated.

Now, what will happen if you don't freeze the book inventory?

Well, one is to freeze all goods movements like we have done previously, like we have done in this

case, blocking, in which case you can't do any activity.

All that stock the vendor has to keep waiting or all the stock has to be put there without a goods issue

or goods receipt being done and somebody might forget to do that goods receipt or goods issue, in which

case it will cause confusion.

You don't want that.

Now, if you don't freeze the book inventory, what happens?

This is a little confusing if you don't freeze the book inventory.

And try to do a goods receipt of 25.

Initially, the stock was 100.

Now you keep counting, keep counting.

And at 5 p.m. you have counted 80.

What's the difference?

20.

But if you add this 25 at 3 p.m. to this stock, the book inventory is going to go up by 125.

And now the physical stock is only 80 because you have not counted this.

Because you can't keep counting.

And then counting and then counting and some other stock keeps coming in and something else goes out

that causes confusion.

When you count something, you have to only focus on that particular lot, right?

This lot.

And this 25 is something that you are unaware of.

Now 125 is your book inventory and 80.

Is what you are physically counted.

Now the difference is 125 -80.

That is 45.

Which is not really the case.

You don't want to write off 45, isn't it?

Do you want to write off 45?

No.

The actual stock that has to be written off is just 20 because that's the only one that's missing.

But if you keep doing GR or GI.

Additional stock will be added to the book inventory and it will cause a whole lot of confusion.

So in order to prevent that, SAP provides a method called freezing of the book inventory whereby the

books are frozen.

And after you post the differences.

Then any subsequent goods, receipts or goods issues that have happened in this lot.

This separate lot.

Right.

Will be adjusted.

80 plus 25.

This process is called adjustment.

So SAP will automatically adjust the book inventory.

To account for new GI new gr plus.

Updated.

Physical inventory.

New gear.

New gear.

Is this additional material that has been either sent out or that came in.

Updated is 80 because we have physically counted 80 instead of the original 100.

So 100 plus 25 is 125 will be the new book inventory.

Okay, now let's do this in action.


