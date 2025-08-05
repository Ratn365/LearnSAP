 

Lecture thumbnail
15:05 / 15:09
Now we are going to discuss the importance of some of the fields that we have created in the vendor

master.

So go back to the change mode or display mode of the vendor master.

And what do you see here?

The vendor number that we have recently created?

One, two.

One, two, one.

And then these are the different sets of views that I was talking about.

So this is the org data.

And then this is the general section, finance section purchasing section.

And each of these sections of data has different views.

These are the views.

Address, view control, view payment transactions, view accounting info, view, so on and so forth.

And as you can see, this is not much different from the material master views.

Right in the material master.

Also, for example, there is a sales section and sales section has three views.

Right.

Sales.

Org one view.

Sales.

Org to view sales or general plan data view.

Same is the case with vendor master.

Now, when you go to change your display view, you should be able to pick the views just like how you

do in the material master.

Like if you don't pick a view, will force you to pick at least one view so you can pick one view or

more than one view.

So you can pick the address view, say the accounting view and then purchasing data view.

Right?

We don't need to discuss much in the other views.

So the general section contains address, you know, P.O. Box, Telephone, Fax.

Next.

In the accounting section.

We have the recon account.

This is just an account number, okay?

Don't worry about it now.

And then this is the view, the purchasing data view, where you'll have the most relevant fields for

purchasing.

So what about order currency?

First field.

Order currency, the currency in which the default purchase order is going to be created.

Why do you need an order currency?

The order currency is dependent on the vendor.

It can also be made dependent on.

The material.

The example for the first scenario is say we are located in Chicago, right?

There is a vendor in San Francisco.

And he's a domestic vendor, so we pay him in USD.

So the default currency is USD.

There is a vendor in Kenya that we can deal with directly for importing coffee and he deals only with

another currency.

So the Kenyan dollar, whatever it is.

That's the reason why we have ordered currency.

Now the second example where I talked about having a currency by material.

Can be used using info records because the same material sitting in San Francisco could be dealing with

USD for all the materials except for one material that he imports from Colombia, in which case the

currency is going to be Colombian dollar.

Right.

So in the next section, when we talk about info records, that's when we're going to see how the data

flows from these three different master data into the transaction.

And that's going to be more interesting.

Anyway.

And then we have payment terms, right?

We know what payment terms are.

There are so many different payment terms.

Net immediately.

Net Within 15 days.

Net within 30 days.

If you don't remember, go back to the vendor master section at the very beginning of this course.

And you'll understand what payment terms are.

The key thing to understand here.

Is that there is payment terms at the purchasing level, there is payment terms at the finance level.

When you create a purchase order, which payment terms take effect is what you should understand.

And like I said, the payment terms from the purchasing data supersede the payment terms from the accounting

data of the vendor.

All right.

And then we know what our incoterms.

Minimum order value.

And then we can specify some other fields like purchasing group plan delivery time.

These are the general data.

Like, you know, what's the plan delivery time in general.

It's not material specific.

When you want to maintain material specific data, you go to the info record.

Anything that's maintained in the vendor is generic data.

Nothing specific to a particular material.

If you want to maintain data for a material and vendor combination, you go to the info record.

All right.

And then there are some other fields like conformation control, you know, and Urs, these are things

that we have not discussed yet, so don't worry about it.

How do you know who has created this vendor?

Well, we have created the vendor just now.

But if you don't know who has created the vendor, how would you know it?

Go to Extras.

Administrative data.

And you'll see that the general view was created by me.

The company code was created by me and the purchasing data was created by me on this date.

And what is the account group of the vendor?

Okay.

That's all we want to know about the vendor.

So save that One, two.

One, two, one.

Now, let's see.

What else is there here?

You can check for changes.

What are changes?

Now, this is something that's available for any kind of master data vendor.

Master material.

Master.

Customer.

Master.

Let me go do a change.

Right.

What kind of change?

I'm going to change this.

Not the search term.

Say the address from 1000 Michigan Avenue to 2000 Michigan Avenue.

Okay.

Addresses.

One example.

Let's go change something else as well.

Especially the purchasing or the currency from USD to, let's say, or euro.

Okay.

All right.

So far, so good.

One, two.

One, two, one.

Now go to changes.

Enter that vendor.

Purchase org and company code is zero one.

And you can specify a date range, you know.

At what point do you want to track the changes?

Well, we want to track everything that has been changed in that vendor, right?

One, two, one, two, one.

You see, the street has been changed.

The purchase order currency has been changed.

The street has been changed from 1000 Michigan Avenue.

That's the old street.

And the new street is 2000 Michigan Avenue.

Right.

Double click that.

And it also shows you who has changed it on what date and what time.

Right.

This is an important piece of functionality that you should remember because in production.

There are issues that you will be solving.

And this really comes in handy.

Because master data changes don't percolate to the transaction or previously created transactions.

Let me explain why.

So there is a master data, right?

There is a vendor.

A vendor has a certain set of data payment terms in code terms, so on and so forth.

And then there is the material.

Material also has a certain set of data like description, material number, material, group, so on

and so forth.

When you create a purchase order.

With a vendor.

And material.

One or more materials.

The data here flows down to the purchase order.

Right now.

This, let's say, was created on 1st of January 2016.

Okay, now the purchase order is being processed.

Somebody is reviewing it, so on and so forth.

Now, if you go to the material master on the second of 2016 and change some data, for example, material

group.

From coffee.

That material is changed to flour or bakery.

Will that data get reflected in the purchase order?

Or a more important question is should it be reflected?

The answer is no.

That data should not be reflected and will not be reflected.

This is an example of a simple production issue.

You know, somebody has changed this on 1 to 2016 and they expect to see it on the purchase order.

They don't see it.

Now, how do you go find out what the problem is?

Well, the fundamental fact remains that the master data changes don't percolate to the transactions.

That were created in the past.

So anything that was done on the 2nd of January will not affect transactions already created.

So how do you know that this field material group was changed on?

The 2nd of January.

You go to changes similar to how we have done in the vendor master.

You go to changes and track all the changes that have been done to the material so far.

And if you see that the group has been changed on the 2nd of January and the user is expecting to see

that on the purchase order created on the 1st of January, That's a no no.

All right.

So the point being, tracking of changes in the material master or vendor master can be done using track

changes.

In fact, you can go inside and do the changes also, for example, if you go to change your display.

Right.

Environment field changes.

You can do it that way as well, right?

You go double click that and then double click it and it'll show you who has done the change on what

date, what time, and from and to meaning from what.

Has it been changed to this current data?

Right.

That is field changes.

And another point is master data trickles down into the transaction data.

And it's used in the transaction data in a variety of ways.

And master data changes are not reflected in the transaction data that was already created.

So all future transactions created with that material master or vendor master will have the changes

reflected.

So all the past transactions transactions already created before the changes in the material master

or vendor master will not change.

All right.

And then we can block the vendor, we can block the material.

Also different ways to block it, right?

We have seen block for purchasing, block for.

Bomb creation blocked for production.

Right.

That's using the material status.

Here.

You can block the vendor like this.

Do you want to block the vendor for a particular purchaser or do you want to block the vendor everywhere?

Right.

All company codes.

Selected Company Code.

All purchase organizations.

Selected purchase organizations.

And then.

Blocked for what?

Blocked for purchase orders, blocked for purchase requisitions, blocked for source determination or

a total block.

If you do a total block, you can't do anything with that vendor.

Now, why would you only want to block, for example?

Quotation.

And purchase order or just the purchase order.

Again, the concept is very similar to how we have done it in the material Master.

You want to block but only block them for certain specific areas of the supply chain.

In the case of Material Master, we have discussed reasons why a material could be blocked for sales

and not for anything else.

Think of the iPad or the new MacBooks and iPhones.

They're blocked for sales until the last moment.

Nobody can create a sales order for them.

Right?

That's their strategy.

Same thing with the vendor.

You can create the vendor, you can do all things with the vendor except create a purchase order because

he's not ready yet.

You could be creating quotations.

You could be creating source determination for that, but you can't do a purchase order.

Right.

And you'll remove that block either from one company called, say, US Only or across the globe in all

your offices.

You could remove that block after, say, January 31st, where the vendor says he is fully functional.

Right.

That's the reason why he had these selective blocks that control the way that vendor is being blocked.

Right.

You can go do some examples of different kinds of blocking and create, try to create and try to create

RFQs or purchase orders and see the effect of these different blocks.

Right.

So I'm not going to block this vendor now, but you get the point, right?