 
Transcript
Okay, so how do we do it in the system?

Let's build a use case.

We'll take the same classic example of wedding cake.

So we need a cake.

Wedding cake.

This is the finished product that we need a quantity of one.

And to produce this, the subcontractor needs flour.

Say £5.

And sugar.

Say £5.

These are the raw materials that we're going to supply to the subcontractor or vendor.

And he's going to ship us back the wedding cake.

Right.

So let's create these three materials wedding cake, flour and sugar.

And create a purchase order and subcontract this to the vendor.

So wedding cake, flour, sugar.

Zero one.

Wedding.

It's a cake.

Zero one industry retail and say this is finished product.

Enter.

We need the basic view.

We need the purchasing view.

And we need the accounting view and storage view.

Right.

And maybe one view enter.

And this is for the Chicago plant and storage location is baked goods.

It.

Okay.

And this is wedding cake.

And you could measure it in pounds or you could measure it in each.

In this case, I'm just going to put each.

So one wedding cake.

Enter.

Purchasing.

Purchasing groups.

Fine.

MRP.

Let's just put.

Some data in the fields lot size X and the plant storage location.

This is okay.

Valuation class.

This is the finished goods.

So we do 7920.

And let's say this is moving average.

Enter.

You're about to exit.

Yes.

So we have created a wedding key.

Okay.

Schedule margin key.

In-house production.

Five days.

Okay.

See.

Okay, wedding cake is ready.

So this material is ready.

It's called wedding.

Cake.

Zero one.

Right.

And then we need flour and sugar.

So do a flower flower and its raw material.

Right?

Let's see if lover already exists.

If not, we're going to create them.

Okay does not exist.

So do a basic purchasing.

We don't even need a storage location.

May be.

And accounting.

And this isn't the Chicago plant and say raw materials.

And enter material already maintained.

That's great.

Change.

Flower.

Basic data purchasing accounting.

We just want to quickly view it before we say.

We are done here, lover.

Good.

Okay.

Okay.

Accounting.

Everything is good.

And sugar, right?

Sugar.

Zero one.

Do we have that?

Nope.

So let's go create it immediately.

Sugar is more or less a copy of flour, right, from a material management perspective.

So I'm going to say copy from flour.

And what do we need?

Basic data one.

Purchasing.

Plant.

General Storage.

Accounting.

And we're going to copy.

From the Chicago plant and raw material storage location.

Enter.

Enter.

Enter.

Enter.

Enter.

We're good to go.

All right, So we got these three materials, right.

What do we do next?

Let's go ahead and create a purchase order.

4001 and the material is wedding cake.

Quantity of one.

We want to order one wedding cake.

What's the price of that?

Let's say it's $300.

I don't know if it's really expensive or not for a $300 wedding cake, but let's just put some value.

All right now.

This is procuring a wedding cake from the vendor for 1000 won.

Is that really the case here?

Not right.

We don't want to just procure that material.

We want to subcontract that material.

How do you convert this item into a subcontract set an item category of L.

L for subcontracting.

Enter.

Okay.

And it says not possible to determine any components.

What does it mean by that?

We said a wedding cake in order to manufacture a wedding cake or make a wedding cake.

You need flour and sugar, right?

Where is that relationship?

That relationship is created as a balm or a bill of material.

And SAP is saying that it cannot find the components, meaning it doesn't know that wedding cake should

be manufactured using the raw materials, flour and sugar.

And it says, I cannot determine the components.

It would not have asked this if you're doing a standard order.

But because you're doing a subcontracting, it says, I don't know the components.

We say, okay, we can enter the components manually.

How.

Go to the material tab at the line item level, click on components and we can add the components manually

or at a wedding cake requires flour £5, right.

And then sugar.

£5.

Enter.

Be good.

Go back.

All right, Let's check if everything is okay.

No messages issued.

Save it.

Standard is created.

All right.

You go there, pick up the number Ctrl C So now you got to deliver the raw materials to the vendor.

How do you do it?

There are two ways to do it.

One way is to do a transfer posting.

And why transfer posting?

Because it's neither a sale nor a purchase.

So you won't use the standard movement types for goods issue or goods receipt.

So you go to my go do a transfer posting for flour and sugar.

Choose the right movement type.

The other way is via a report go to logistics materials management.

So purchase order.

Reporting and see stocks per vendor.

So it's subcontracting stocks per vendor.

So go there.

Your vendor 4001 and plant Chicago one.

You could filter it out by whatever parameters you like.

And execute it.

So it will show you the list of components that you need to supply to the vendor.

In this case, you need to supply against this PO line number ten on this date.

£5 of what?

Of flour.

And £5 of sugar.

Right.

So what you can do is select them and do a PGI or post goods issue.

All right.

From which storage location?

The storage location where you have the goods, right?

They are supposed to be there in raw materials, storage location.

Okay.

It says it doesn't have that material.

We have just created that material.

But we didn't post any.

So what you got to do is go back.

And put some of the material in stock.

How do you do that?

You do it using micro movement type 561 initial stock entry.

But before we do that, let's go check the stock for sugar in raw material storage location.

Chicago plant.

There is no stock.

Now, how about flour?

Okay, so we do have something in raw.

Okay, that's good.

So all we need to do is enter some stock for sugar.

So my go.

Goods receipt.

Not against purchase order, but against other.

And what's the material?

Sugar.

Sugar oh one.

How much?

Say 100.

Where?

Not 501, but 561 from the Chicago plant and raw material storage location.

Okay.

Save it.

Good.

Let's go quickly.

Check the stock and make sure we have enough sugar to supply to our vendor.

Sugar.

Execute.

We do have sugar now, so we have sugar as raw material in our warehouse.

We have flour as raw material in the warehouse.

Now let's go supply to the vendor.

All right, select them.

The opposed goods issue.

All right, So item is posted.

You see that in green, right?

So that means whatever stock we needed to supply to the vendor has been posted.

Now, again, let's go back to NB and check the stock say of sugar.

We have supplied £5 to the vendor right see that stock provided to vendor and that's counted separately.

So out of the 100 that we have in stock.

Five has been posted to the vendor.

So far, so good.

Same thing would have been the case with flour.

Now, after some days the vendor has made the wedding cake.

Maybe within a day or two days, let's say.

And now he is ready to ship it back to us.

And what do we do?

We take the cake and eat it, right?

No, we don't.

Against the purchase order.

You go receive it, right?

Although we would love to eat it.

Okay now.

There is one quantity of wedding cake that has come in.

And what happened to flour and sugar?

One of it is flour and one of it is sugar, because I didn't change the description.

So did you consume five quantity of or £5 of flour and £5 of sugar?

Well, we don't know.

Let's just leave it at that.

Okay.

So if you go to line item, wedding cake.

And.

Put it in the bag.

Good.

Storage location.

Click item.

Okay.

Check document is okay and save it.

Document is saved.

Go to NB for wedding cake.

And you got one quantity of wedding cake in the Chicago plant.

We're good right now.

It might be possible that he might have under-consumed the stock like flour or sugar, and he's ready

to send it back now.

Don't think about the one kilo or £1 of flour and sugar.

That's silly.

I know.

But over a course of time, let's say we give ten orders a day of wedding cakes and we keep supplying

the flour and sugar colors and whatnot, all the raw materials over the course of the day.

He might accumulate some flour or he might fall short of some sugar.

He might have made it somehow.

But we need to supply the necessary raw materials to balance it out.

Right now if you go to.

And look at sugar that we had £100 of, out of which we have shipped £5 as raw materials.

Now, you don't see any of those materials supplied to the vendor, right?

It's all gone.

It's consumed.

Now, at this point, the vendor might call us and say, Hey, you know what, I forgot I have an excess

of £10 of flour or sugar.

I can ship it back.

Right.

This is called Underconsumption.

Or he might say some of the sugar you gave me was bad.

So I had to use some of my sugar.

And, you know, I had to over consume £5 of sugar.

So you owe me £5 of sugar.

In which case it's over consumption.

Either way, it's a valid case.

So how do you settle for that anomaly?

What you do is do subsequent adjustments.

So if you go to my go.

Right.

Put the purchase order in and before you do a goods receipt, you have to select subsequent adjustments.

And the subsequent adjustments is against what is against the purchase order.

Now what do you want to adjust?

You want to adjust for £5 of flour and you can say it's an under consumption.

Or it's so many pounds of sugar and it's an over consumption.

Right.

Let's say in both cases it's £5 or sugar and £5 of flour.

Both of them is a case of underconsumption.

Check if everything is okay.

Okay.

Item.

Okay.

Okay.

Do a check again.

Item.

Okay.

Check again.

All right.

Document is okay and click save.

Document is saved.

Now if you go to.

Check your sugar.

The additional £5 would now have been sent to the vendor.

So as part of subsequent adjustments, depending on if there is excess stock available with the vendor

or short supply, which case he might have consumed more than what is provided, you can supply or take

back stock from the vendor.

If you supply in excess, it will be shown as stock provided to the vendor.

If you take it back.

It should have been available with the vendor.

So you can't take back stock that you have not given.

So if you have stock available with the vendor.

You can take it back.

For example, there is £5 with the vendor right now.

You can go to my go.

And as part of subsequent adjustment against that PO, what you can do is, okay, I want to take back

£3.

Of flour and £3 of sugar.

And.

Item.

Okay.

Item.

Okay.

Check if everything is okay.

Save it.

Right now if you go check.

For sugar or flour.

You see what happened.

So you have taken £3 back from the vendor.

So what have we just seen?


