 
All right.

So we're going to create these three steps, number one.

Number two.

And number three, create the purchase order first vendor.

4001.

Material.

Coffee beans.

Quantity 100.

All right, that's it.

Save.

You've got our PO.

Copy it.

Now by this point.

You should be very well versed with the basics of poker.

So that's the reason why I'm not going into the details.

If you are not well-versed, then you better go back to the previous chapters.

All right.

So go back, go to goods movement.

Now we are doing step number two here.

Now this step is done.

We have ordered for 100 kilos of coffee.

Now, after some time.

The goods are coming in and that's what we're going to do now.

We are going to receive the goods.

So put the purchase order number that we copied in there.

Enter.

And how much did we receive?

We receive 100 kilos.

We are saying item.

Okay.

And where did we receive it?

Into our coffee storage location and save.

Okay, so the material document is posted.

So step number two is done.

Now we are going to do step number three, which is receiving the invoice.

So we have raised a purchase order, received the goods, and after some time, of course, we got to

pay and to pay we have to receive the invoice.

So the vendor is now going to send the invoice and we are going to receive it into the system.

How do you do that?

My.

Middle.

Then.

When did we receive the invoice?

This is the invoice date against this purchase order.

Hit.

Enter.

And we are receiving an invoice for a quantity of 100.

Right.

And what's the amount?

$1,000.

So we're going to put an amount of $1,000 here.

Hit.

Enter and save it.

All right.

Our invoice is saved.

Well, let's go back to the PIO.

Hit.

Enter and see the purchase order history.

Now, remember, purchase order history is where you see all the transactions that has happened to that

purchase order.

Now, what has happened here?

We have created a GRT.

We have created an EIR.

Let's see if those transactions are tacked on to the purchase.

Order!

Purchase Order!

History.

And of course you see the material document, which is the goods receipt and the invoice that we have

created.

Okay.

So far so good.

The transaction is complete.

Now, remember, the goal of this chapter is to do the return.

And how do we do the return?

Returns.

Typically, inventory based returns are done with reference to the GR.

So with reference to the GR, you create a return.

Delivery.

And where do you do it?

In Miko.

So let's do that.

So let's copy this material document.

Control C.

Go back.

To go back.

Now go to my girl and instead of a goods receipt, we do a return delivery.

Right now.

This is something we are doing for the first time.

So pay attention.

All along we have been doing my go for goods receipt only.

Right now.

My goal is a transaction that we can use to do so many different things.

What are those different things?

Returns.

Delivery is one of them.

So how do you do returns delivery?

Like I said, with reference to the goods receipt.

So we select goods receipt here and we select material document and.

We paste the material document in here?

And hit enter.

The system automatically pulls the quantity, storage, location, plant and all that stuff.

So what this means is you have received a quantity of 100, £100 of coffee or kilos of coffee in this

goods receipt.

Now, what do you want to do?

How much do you want to return?

Well, you could return the entire 100 quantity.

Or in our case, we want to return 50 kilos.

Remember we said there are 250 kilo bags that were delivered.

One of the bag was gone.

So we're going to return one of the bags.

Right.

Click item.

Okay, and click save.

Now what does it ask you?

It says Enter reason for movement.

So why does it ask you this question?

It didn't ask you this question when you're trying to receive the goods.

Well, this is a customization behind the scenes.

Don't worry about it.

We'll get to it when we get to inventory management.

But for now, let's just say.

The reason for goods movement.

Go there and select a reason why we are returning it.

It could be poor quality, but in this case, basically it's damaged, right?

So I'm going to say damaged.

And say.

Well, that looks pretty intuitive, right?

What we are trying to do is give a reason why we are returning the goods and why we are putting that

reason is pretty obvious, Right?

When we return goods, you obviously put a reason.

Go to Amazon, you return goods, you put a reason there.

You know the thing is broken or it doesn't fit me.

Stuff like that.

All right.

So go back.

And this step here is complete.

And now what's the next step?

The next step is.

To do a credit memo.

Right.

So what's a credit memo?

It's something similar to an invoice.

But when we receive the goods, we have to pay the vendor.

That's called an invoice that we receive from the vendor.

But when we return, the goods, the vendor is going to give us a credit memo.

What's a credit memo?

Let me take the Amazon example.

If you buy some goods from Amazon, you pay Amazon.

Right.

So Amazon sends you an invoice, you pay Amazon well, you just pay it right on the website.

But if you think of a B2B scenario, Amazon gives you an invoice, you pay Amazon.

But what if we return goods to Amazon?

No, Amazon owes you money, right?

In this case, the vendor ABC Foods 4001 is like Amazon and you are returning some of the stuff back

to Amazon.

Now what happens?

The vendor owes you money, so he gives you what's called as a credit note or credit.

What is a credit memo?

It says, I have to pay you so much earlier in invoices.

You have to pay me so much.

A credit memo is the exact opposite of an invoice.

It says I owe you money.

Right.

So we need to document the credit memo, just like the way we document an invoice.

And how do we do that?

Same transaction?

Micro.

And instead of an invoice, select credit memo.

So it's not all that complicated, right?

Only these three transactions purchase order.

Micro.

Micro.

These are the transactions that we use to create all the P2P steps.

Now, what's the amount for?

The amount the vendor is going to send.

The credit memo is for £50.

Right.

It's not £100.

It's £50.

And the amount is going to be for 500.

Right.

Now, when you change the quantity to 50, you see that the amount does not change.

Now.

This is weird, right?

When you change the quantity, the corresponding amount should change.

But it's not changing here.

Well.

The reason is SAP has left that to us.

So if you want that quantity to change according to the amount or vice versa.

You can customize it.

But she says, I'm not going to change it because we don't know what amount the vendor is going to give

a credit for.

Sometimes the vendor might take some charges, like if you buy something on Amazon or Best Buy and return

it, there is something called as a restocking fee, right?

So similarly, there could be some charges that the vendor could levy.

So it's not always, you know, 1 to 1 relationship between quantity and demand.

But if you really want the amount to change with quantity.

Meaning if you put 50 here, this should automatically go down to 500, 15 to 10, 500.

In order for you to see that there is a parameter that you can change.

It's not a configuration, it's a personalization, meaning it doesn't apply to the entire organization.

It applies only to you.

If you want to have that control, you can have it with a parameter.

What is that parameter?

Do you want to post?

No.

Go to personalization using transactions.

You three.

You could use that.

Or you could use system user profile, set data.

Any of these?

Okay.

And go to parameters and over here put in IV amount adjust.

And then put an X there and click save.

Okay, Now go back to my row.

Put your purchase order number in there and the quantity that we are receiving a credit memo for is

50.

Now observe the amount column.

So I've just entered 50 and hit enter.

You see what happened?

The amount automatically changed to the corresponding amount for that quantity.

50 multiplied by ten is 500.

If you put 25.

It's going to automatically change to 250.

Right.

So that's that we're going to change it back to 50 and we are going to receive that for $500.

Make the balances zero and save it.

All right.

So we have created this in row.

So whether it's a goods receipt or a return delivery, you do the transaction in Miko, whether it's

an invoice receipt or credit memo.

You do those transactions in Miko.

So what have we done now?

We have just completed the return of 50 kilos of coffee.

And how did we do that?

We created a return delivery with respect to PO.

This is with respect to material document.

This one is with respect to.

Po.

All right.

Now, let's go back to the poll and see the poll history.

So our invoice is complete or credit memo is complete.

Let's go back to the.

Open the video and go to purchase order history.

You see that there is a goods movement for 100, which is the inbound receipt.

And then there is the goods movement outbound called return delivery for 50.

So 50 has gone out of stock.

How does it go out of stock?

Well, we have created a movement here, but the next time the vendor comes in with his truck and all.

He'll take the 50 kilo bag, put it in his truck and take it back.

As simple as that.

So it's a pure inventory movement from our perspective.

Right.

There is no shipment involved.

There is no packing.

Nothing, Nothing of that sort.

There is another way to do these things, which involves all the logistics.

But let's not discuss that here.

This is a simple inventory movement.

We receive the goods, we send the goods out.

There is no shipping.

There is no packing.

There's no labeling any of that stuff.

And then we have two invoices.

One is an invoice receipt where we receive an invoice for a quantity of 100.

The original invoice.

And then.

We have a credit memo for quantity of 50.

Right.

So let's go to the delivery schedule tab.

And observe this field called the open quantity.

What does it say?

It says 50.

What does it mean?

The original Poe was for 100.

We needed £100 or kilos of coffee.

We have originally received £100 of coffee.

Right, but we have sent out 50, so we only received a net of £50 of coffee.

And what does this mean?

This means.

That we are yet to receive 50 kilos of coffee.

Right.

And that's called as an open quantity.

An open quantity basically says we are yet to receive 50 kilos of coffee.

How does the system know that?

Very simple.

100 -50 is 50.

Right.

So whatever was expected is the quantity.

And whatever we got is the quantity.

And whatever is remaining, of course, is open quantity.

So in the next chapter, we're going to discuss a little bit about this open quantity and how to close

it.

How to block it, how to mark the delivery as complete and all that kind of stuff.