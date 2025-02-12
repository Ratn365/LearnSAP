 
Transcript
All right.

So the process is simple.

Go to M21 And.

And select your standard vendor.

4001.

And material is say you could have any material as a consignment.

Okay, So coffee beans or anything you want.

Paper is not dependent on the material.

So what's the quantity?

Let's say £500.

Right contract exists.

That's all right.

Now, this is a regular purchase order.

What is our intent here?

We want to create a consignment purchase order.

The item category for that is K.

You see, it's special stock.

Select that.

Hit enter.

And then it says Consignment info record for that combination does not exist.

So one of the prerequisites to be able to create a consignment is you should have an info record.

All right, let's go create an info record.

Do you want to save it?

No.

So go to logistics material management, purchasing master data info record create.

So for vendor 4001.

Coffee Beans.

Oh one.

Purchase org US zero one and plant Chicago one.

Right.

Don't just say standard instead select consignment because for the same combination of materials purchase

org plant, you can have an info record for standard.

Or you can have an info record for consignment.

In this case, we are creating an info record for consignment.

Okay.

Hit enter and this is all good plan Delivery time five days, standard quantity five.

And this is the key field net price, say $10.

And here you could put a tax code, say I zero sales tax of zero enter.

Enter.

Enter, enter.

So purchasing for record save.

Now let's go back and create the purchase order of type consign.

So the document type is not different.

But the item category is going to be different, right?

So it's coffee beans or one quantity of 500 and.

The item category is consignment enter contract exists.

That's all right.

So this time it doesn't say that the record is not exist because we have already created it.

Another key feature, the conditions tab here.

The moment I put the item category as K, the conditions tab is gone.

That means for a consignment, there is no pricing.

You should be able to guess why.

The reason is consignment is not really a sale.

So when we are asking for £500 of coffee, we are not really saying I'm ready to pay for £500 just yet.

All this order or purchase order is requesting is send me £500 of coffee on consignment.

And because it's a consignment, it's not going to have a price and we're not going to own it, so we're

not going to pay for it yet.

Does it make sense?

All right.

So we're all good here.

Let's see if we can save this.

All right.

Standard order 37 is created.

Save that.

Now the vendor is going to send the goods, of course.

Right.

So we're going to do a goods receipt.

And before we do that, let's go check the stock.

And coffee beans own Chicago and.

Click execute.

All right.

So in the Chicago storage location, there is 267 quantity, out of which some of it is in raw materials

and some of it is in coffee storage location.

So let's go over to Miguel and see what happens when you try to receive the goods of that 500 against

a consignment.

So purchase order.

I've copied the purchase order number already.

Paste it.

All right.

So that's a quantity of 500.

And as you can see at the line item level, the goods movement is the typical 101.

Just like any other purchase order.

But there is an indicator here.

This is called as special stock.

So it's the same movement type, but into a consignment, not into unrestricted stock.

Right.

So storage location, let's say, is coffee.

All right.

Then we're going to say item.

Okay.

Check.

Document.

Okay.

And save it.

Okay.

Material document is posted to 580.

And if you want to see the material document, go to zero three.

And let's look at the accounting.

So this is our material document.

And you see the movement type is 101 and it's of type K consignment.

And check the accounting document material does not include an accounting document.

Can you guess why?

The reason is simple.

It is not a sale, so it should not affect our inventory valuation.

We can see the inventory go up in quantity, but not the value.

And when there is no difference in value, why do you need an accounting document?

No need.

So click.

Okay.

That's a key thing.

You got to keep at the back of your mind when you do a consignment, when you take in a consignment,

the valuation of your material is not going up.

It's just that the quantity is going up.

Now that is another story.

How is the quantity going up?

Let's come back here.

So we have a quantity of 267.

Out of which coffee location has 237.

Right now we have done a goods receipt for the consignment.

Let's refresh this and see what are the changes.

Do you see this line here?

Vendor consignment.

500.

It's not unrestricted stock or rather, it's not just unrestricted stock.

You can just take out of it any time you want.

In that sense, it's unrestricted.

But it's not really our stock.

It's the vendor's stock sitting at our location.

That's the key.

If there is any confusion in trying to understand what is consignment, just think of it this way.

It's vendor stock sitting at our location.

We don't own it, but we have physical access to it.

The moment you touch it, meaning the moment you withdraw something from that lot, it becomes yours.

So it's there at your disposal to consume any time you want.

And that's why it's treated separately, although it's unrestricted, meaning it doesn't have to go

through quality at this point.

It's still marked as special stock.

Now, there are different kinds of special stock consignment, subcontracting pipelines, so on and

so forth.

In this case, it's consignment special stock.

Now.

Double click it.

And here is the breakup by vendor, meaning this is stock.

That has come in from vendor 4001.

Now, if another 500 came in from another vendor, say 4002, the total is going to be showing up as

1000.

In the previous screen.

And the moment you double click it, it's going to show the breakup as 500 from 4001 and 500 from 4002.

The point being, SAP is keeping track of all the vendor consignments.

Broken down by vendor.

All right.

So let's close that.

Now we have 500 in stock sitting in a consignment.

Now let's go consume them.

How do you consume them?

You can consume them for a sales order.

Meaning somebody needs coffee.

They create a sales order, and goods from this consignment can be consumed.

Now the production department needs it.

For example, some coffee beans are required to make some cakes.

There is a production order to make a cake.

You can consume from this lot.

The project system can consume goods from this lot.

Meaning a birthday party is a project.

And it can consume coffee from the slot.

So any consumption business process can consume goods from the slot now.

Now, typically in when we want to consume, the easiest way is to do a go and goods issue, right?

And we do it against a cost center so that we don't have to have a source document like a project system

or a production order or a sales order.

They're all cumbersome.

But this is really easy.

So what do you do?

You do a goods issue.

Against other.

If you want, you can use a purchase order.

But.

And we're going to use a plant, Chicago one and the storage location.

Coffee.

Material.

Coffee Beans.

Oh one.

How much?

Let's say quantity of 100.

So we have a consignment of 500, out of which we are consuming 100 right now.

This is all good.

If you click okay, it doesn't consume from the consignment lot because we have not specifically asked

to be consumed from the consignment lot.

The way to do that is by selecting a special stock indicator of K.

You see the moment I hit Enter?

There is going to be additional tabs coming up here.

Just watch out for it.

Hit enter.

And what's the additional tab?

Partner.

And why is that?

The reason is.

You're asking me to pull 100 quantity of consignment goods.

And because we said consignment is saying, okay, which partners consignment?

Okay, we can answer that.

Vendor 4001.

That's the only partner we have at this point.

We have more.

You can definitely put the vendor there and it's going to pull up from that lot.

Do a quick check, make sure everything is okay.

All right.

It requires a cost center.

And you know how to put it right?

Admin or one?

Right.

Another quick check.

Tax jurisdiction.

There's a tax jurisdiction issue, but we could check that during invoice processing or save it.

Okay, material document is posted and 8070.

Now.

Mm.

Zero three.

Let's check out how the material document is.

So it's a 201 with special indicator K And what does the accounting document say?

Now, the difference between the previous process, which was receiving the consignment and the current

process, which is trying to take some goods or consume goods from that consignment, is that in the

previous case there is no counting.

But in this case, there is a counting why?

Remember I said only when you touch that lot and extract goods from that lot will it become yours.

And that's when a value change is happening.

That's when the accounts payable is hit.

That's when we are liable to pay.

And of course, the raw material value increases.

Okay.

Now, how do you settle that invoice or how do you settle the fact that you have removed £100 or 100

kilos from that consignment against Vendor 401.

Before we go there, let's check out our stock.

Well, we used to have £500 of coffee as consignment for a particular vendor.

401.

How much do you have now?

400.

Why?

Because we have removed £100 or we have consumed £100 against a cost center using my go.

Right.

Now that should make sense from a goods movement perspective.

Now, how do you settle the invoice?

Now invoice settlement for consignments is slightly different from invoice settlement for the regular

standard purchase orders.

So you don't do a major.

Instead you do a Marco.

You see the goods are in your lot.

Here's the deal.

So.

The vendor has sent in £500 of coffee.

And it's sitting there somewhere in our warehouse, Right?

Out of which we have consumed £100.

The vendor is out there somewhere.

He doesn't know that we have consumed £100 out of it.

So it's our responsibility to bill ourselves against the vendor.

So the vendor is not going to send us an invoice.

We are going to generate an invoice ourselves.

The way to do that is using this process called M.k.o.

Now, this is an intelligent process.

That will tell you what are your outstandings based on vendor or based on material?

So select your material.

Coffee beans.

Zero one.

And for 4001 vendor you know the plant and there are two options here display or settle.

Let's look at display.

This is the record.

The record is for a quantity of 100 that's withdrawn and 100 multiply by ten is 1000, and it says it's

not settled yet.

Well, to settle it, you'll have to select, settle and click execute.

Now, this is where the tax error is coming.

Now we can go ahead and fix it.

But the point is.

The moment that is fixed, it just creates an invoice.

You don't have to really do anything.

You don't have to go to Miro, receive the invoice because you don't even get an invoice.

Why?

Because the vendor doesn't know that we have consumed £100.

The company knows that it has consumed £100.

So it's got to be able to bill itself and settle all the goods that it has consumed.

Right.

And so even if you create that invoice in Moscow.

It's not going to go and update the.

Right.

So here is the difference.

So there is a P0, right, where let's say 5000001 against which the vendor has delivered £500 of coffee.

Now we have.

Removed or consumed £100 of coffee.

This if you did it using the standard process where you have a PO and then there is a goods receipt.

You create a goods receipt in myGov that updates it in the history.

And then you get an invoice.

You go to my row.

Create an invoice and then it's updating the history.

That is the standard business process for purchasing.

In consignment.

The vendor is putting things in the lot.

You are consuming goods from the lot.

You could as well do a return.

But the point being.

The goods that you are withdrawing.

Is linked to the vendor.

The linkage is only at the vendor level, it's not at the purchase order level.

So when you do a settlement in Moscow, you're settling for £100 of goods against the vendor, say 4001.

You're not settling it against the PO.

The PO in the case of consignment is merely an instruction to put goods in the lot.

And when you return goods from the lot, you could do a return and the vendor could take them away.

And that's, again, a consignment.

It's called a consignment return.

But when you settle, meaning when you want to pay, it's not tagged with the purchase order.

Instead, it's tagged with the vendor.

That's why this invoice that's being settled is not linked to the PO.


