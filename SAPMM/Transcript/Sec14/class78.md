 
Transcript
So how do we create a purchase order?

So how do we create a purchase requisition in SAP?

Go to logistics.

Go to material management purchasing.

Purchase requisition.

It's right underneath the purchase order.

So go click on Create.

Click on Item Overview.

And over here you can enter the materials.

Coffee.

Coffee beans and we require £100 of coffee beans.

And where do we require it?

We require it in the Chicago plant.

All right now.

The first thing that you have to enter here is called evaluation price.

What is the valuation price?

So a valuation price.

Is an expected price.

So the expected price is, say, $10 per pound.

Why do we need to put it here?

Why doesn't it pick this up from the info record?

Well, the info record is more of a negotiated price.

It's already negotiated.

The vendor is ready to give it at that price.

Typically, the system can be configured to pick this from the material master.

Remember in the material master accounting view, there is a place where the price is determined automatically.

If you double click this material.

Go to accounting view.

This is the moving average price.

So in the same purchase requisition, you can create more materials like flour, like sugar, so on

and so forth.

So you can just save this purchase requisition and a number is created.

Copy that number.

Control C.

Close it.

Now this purchase requisition can be converted to a purchase order.

By going to the purchase order create.

And then click the document overview on.

Select the purchase requisition by clicking on this little diamond box and select my purchase requisitions.

So it just pulls you all the purchase requisitions that you have created.

And if you want to search for purchase requisitions created by somebody else.

You can very well go there and click on purchase requisitions.

And select the purchase requisitions by a variety of criteria, by materials, by vendor, by who has

created it, what date it was created, what plant we are looking for, the purchase requisitions,

so on and so forth.

But for now, let's just pick the purchase requisition that I have created based on my purchase requisitions.

And then you know what to do here, right?

Select it and click on Adopt or drag it to your shopping cart.

You click on a dot.

If you click on Adopt, it has pulled in all the details from the purchase requisition, like the material,

the quantities, dates.

But what it does not have is the vendor.

Remember in the purchase requisition when we created the purchase requisition.

We did not enter a vendor.

The selection of a vendor is not a choice that the purchase requisition owner has.

So a baker requiring 100 kilos of coffee can just document his requirement as 100 kilos of coffee is

required or flour is required.

He doesn't care which vendor supplies that material.

It's the duty of the purchasing manager to decide the vendor and then put it here.

For example, in our case, we are going to use 4001.

And for 4001.

What is the price of coffee beans?

Say $10.

Can delivery date be met?

Let's say yes.

And now it says scheduling agreement exists.

Well, in the previous chapters, we have created contracts and scheduling agreements.

Right.

If you want to use one of those, you could use that.

You know how to use them, right?

So go to the far right then.

In the outline agreement column.

You can put in the contract number or the scheduling agreement number.

And the price that was determined in that agreement will automatically be pulled into the conditions

tab.

For now, we didn't use an outline agreement, so it's asking us for a price and we have put a price

of $10.

Hit, enter.

Enter and save.

And from this point on, the rest of the steps would remain the same.

Create purchase order, create goods receipt, create invoice receipt.

Now, if you go back to the history of the purchase order, you don't see a history, right?

Because we have not done any further steps yet.

We didn't do a goods receipt.

We didn't do an invoice receipt.

But there is a precursor document to this.

Right.

What is a precursor document to this purchase order?

Meaning the previous document.

The previous document is the purchase requisition.

And if you want to see that, you can see that at the line item level.

Now, that should tell you something else here.

Meaning one purchase order can be created from multiple purchase requisitions.

You want to see that?

Go back.

Let's go create more purchase requisitions.

This time it's for a quantity of 150.

Right at what would be the price, say $10 or $15.

And that's for the Chicago plant.

Right.

So this is our first purchase requisition.

64.

Remember that number?

64.

And let's create another purchase order.

This time, let's pull it for £250.

And it could be.

Either in the Chicago plant or in the San Francisco plant or any other plant.

And save it.

And our second purchase requisition is 65.

Now let's go back to the creation of.

Create purchase order.

This time we are going to convert 64 and 65.

Right.

So select both of them and click on Adopt.

You see, you got both these line items here.

Right.

And select the vendor.

Can the dates be met?

Yeah, they can be met.

Scheduling agreement exists.

Yeah, we know that.

We don't care.

And.

There you go.

We are able to combine multiple purchase requisitions into a purchase order.

Now, remember, one was for a quantity of 150 and the second one was a quantity of 250.

Now let's save this purchase order.

I want to show you something else.

Now, can you create another PO with reference to one of these purchase requisitions?

Let's see.

Select that purchase requisition and as usual, click on Adapt.

Select the vendor.

And.

The pure quantity that we have created in the purchase requisition was for a quantity of 150 or 250.

Now it's not shown here.

Why?

Because that purchase requisition has been consumed.

So once it's consumed, the quantity in that purchase requisition is deemed as complete.

Why?

Think of this.

This baker has asked for 100 kilos of flour, right?

And created a purchase requisition for it, say 400000 65.

For a quantity of 100 kilos.

Now you have converted that.

Into a purchase order.

Now, if somebody else tries to accidentally convert this into another purchase order, then we are

duplicating the requirement, isn't it?

The baker has asked for 100 kilos of flour.

But we are trying to procure it twice.

So SAP cleverly consumes that quantity and deems it as complete, meaning that purchase requisition

is no longer relevant, but it still pulls the purchase requisitions here because you asked for your

purchase requisitions, so SAP does not know what to do with it, so you just ask for the purchase requisitions.

It just gives you those purchase requisitions, but it cleverly masks the quantity.

Why?

Because it knows that the purchase quantity has already been consumed and created as a purchase order,

so there is no need to duplicate the purchase order for that purchase requisition.

Now, instead of just pulling your own purchase requisitions, you can do something else.

You can pull in the purchase requisitions that are open.

Meaning if a purchase requisition if a purchase requisition created for this quantity.

Say 400065.

Has not been converted to a purchase order yet.

That will be deemed as open.

But if it has already been converted, then it should be deemed as closed.

Right.

So when you're trying to create purchase orders with reference to purchase requisitions.

You don't want to pick up closed purchase requisitions, right?

Meaning it's already been created to a purchase order.

Maybe the purchase order is already sent to a vendor.

You don't care about those kind of purchase requisitions.

You only care about purchase requisitions that have not been converted yet, meaning they are open.

So how do you pick them up?

So like I said.

In the document Overview.

Select Purchase requisitions and click on Open Only.

Okay, you could click released also, but we have not seen the release functionality yet, so let's

not worry about that for now.

If you want to select, you can select that and click okay.

Now it says no data exists because all the purchase requisitions we have created have been converted.

So let's go create another purchase requisition.

Like so.

For coffee beans.

Quantity of, say, 350 just so that we can differentiate that material.

And for the plant.

Chicago one.

And what's the price say?

$9.

Save it.

What's the purchase Requisition number ending in 66.

Now go back and go to creation of purchase order.

And in the document overview select purchase requisitions and the material is coffee beans.

So essentially what we are saying is pick up, remove this guy.

Pick up all the purchase requisitions for coffee beans that are open.

Execute.

You see that 66?

The one that we have just created.

Drag and drop it.

And you can create the purchase order as usual.

So a purchase requisition can be open or closed.

An open purchase requisition.

Is a purchase requisition that has some amount in it that has not been converted yet.

It could be the entire 100 kilos or it could be 50 kilos that is converted.

A closed purchase requisition is a purchase requisition that has already been converted to a purchase

order.


