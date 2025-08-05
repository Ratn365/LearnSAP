 
Let's continue our discussion on item categories.

In this chapter, we'll talk about consignment.

We've already seen what is a consignment?

The item category for consignment is K.

The account assignment.

Category K says that its procurement for a cost center.

But the item category K says that it's a consignment item.

What is the consignment?

The vendor.

Sends the goods over.

For example, we have taken the case of a coal mine.

The miner.

Sending the goods over to us.

Us, meaning we are a steel plant or a coal plant.

So we are a factory.

And we need coal.

And the vendor, the miner, the mining company is going to be sending us coal.

And where is he going to put it?

He's going to put it in the lot.

It's not a sale yet.

And when we consume goods from the lot.

So he's going to put.

The goods into the lot.

And when we consume goods from the lot, for example, we take coal from the lot for producing power

or making steel.

This is when it's considered a sale or a purchase sale from a vendor's perspective purchase from our

perspective.

The steel plants perspective.

So when I say consignment, I'm talking about this process, the process of vendor dumping the goods

in the lot.

And we said it's not a sale or a purchase.

He's just keeping his goods cold at our lot because we need it.

And it's done as a convenience thing.

So for this transaction, what are the properties?

What are the properties of this transaction?

Number one.

It's not relevant for billing.

Why?

Because.

It's not a sale.

When it's not a sale, the vendor cannot bill you.

Right.

So there is no billing.

A corollary of that is that there is no account assignment because it's not a sale.

You can't really do an account assignment, meaning nobody can eat the cost.

The reason being there is no cost to eat.

Right.

It's not a sale or it's not a purchase, so there's no need for billing and hence there's no need for

an entity, say, a cost center or a project or anybody or a HR department to eat the cost.

Right.

Another property of this transaction.

Is for consignments non stock.

Materials are.

Not.

Possible.

Why?

Because non stock materials typically require somebody to eat the cost.

We're not going to stock them.

We're going to consume them.

Right.

To understand this, you got to go back to the discussion between non evaluated and evaluated.

Procuring non stock material.

That chapter will give you a good understanding of Non-stock materials, properties and how it's different

from producing stock materials or procuring stock materials.

The non-stock materials is not possible in a consignment.

Why?

Because when the vendor dumps them, they are there for the inventory to be counted.

We count them.

But we don't own them.

So we cannot have non stock because the moment it's non stock it becomes consumption.

So for consignment non stock is not an option.

So what happens here?

Can you not have a material in the purchase order for consignment?

No, that's not possible.

Right.

So material is mandatory.

It cannot do a consignment order without a material like a non stock order or with material group.

That's not possible.

All right, how about gr Do we need to do a GR Yes.

GR needs to be done right.

GR is good.

Unless you do a goods receipt, you can't really track the vendors inventory.

Number four.

Are we going to evaluate that goods receipt?

Meaning when the goods come in to the lot.

Are you going to count them against our books, Our inventory?

No, they're not.

That means the goods are being received.

They are being counted as special stock, but we don't value them.

So the gr is non-evaluative.

We don't evaluate the goods.

And of course it's firm, meaning you can't change it.

Right.

And number five, how about invoice?

Can you invoice a consignment?

No, you can't.

We said no billing.

Right?

So that means there's no invoice and it's firm, meaning you can't change it.

Now let's go to SAP and follow up on all these items.

We're looking at consignment, Right?

So this guy, Kay.

Go inside and you see that the material is mandatory.

It's required.

And the account assignment is not allowed.

Do you see that?

According to the properties of consignment, we have concluded there is no account assignment because

there is no billing.

And we also said.

That material is mandatory.

Visible distinction here.

The material is mandatory and account assignment is not allowed.

So that covers those two parameters.

How about inventory management?

Inventory management is mandatory.

Because it's vendors inventory.

It's not consumed yet, so we have to track the inventory.

You see that?

That means gr has to be done.

And when we do GR we typically do an inventory management.

The Hobart valuation.

The GR is not evaluated and its firm meaning you can't change it.

See that GR is not evaluated and firm, meaning you can't do the valuation of the goods on a consignment

because there's nothing to value it.

It's not our goods yet.

And because it's consignment, it's firm.

What do I mean by firm?

Firm meaning You can't change that parameter in the purchase order.

Whenever you see that firm in the PO, that means that it's grayed out.

You cannot change it.

And then there's a gr.

Right.

We have mentioned that there is a gr and there is no invoice receipt.

You see that there is no invoice.

Why?

Because it's not a purchase.

And is it firm?

Yes, it's firm in the PO.

That means you cannot change it.

It's very easy to test this.

All you have to do is.

Go create a PO.

Vendor 4001.

And put coffee beans.

Oh one.

The a quantity of 100.

Okay.

Now this is the standard purchase order.

Now, line item 20 for the same material, same quantity.

Let's make it as a consignment.

Can you do that when you make the item category as Kay?

Go look at the second line item.

You see, there is no conditions Tab.

See?

Look at the difference between the first line item and second line item.

In the first line item, there is a conditions tab in the second line item.

20.

There is no conditions to.

So pricing is not allowed.

Again, go back to the first line item, which is a standard line item.

Go to the invoice tab.

Invoice receipt is required.

That is a regular standard material.

If you go to line item 20, where is the invoice tab?

There is no invoice tab.

That means you cannot invoice that line item because it's a consignment.

Again, go to delivery and you should see a goods receipt.

So regular line item in a purchase order is relevant for goods receipt.

The standard item category Right.

Now, go to the consignment.

Go to the delivery.

Do you see that the checkbox is off?

You don't see that, right?

This checkbox.

The one that says goods receipt for line item ten is now.

For consignment line item 20 is checked off.

Now let's check this account assignment.

Is account assignment possible?

Well, we don't know, right?

Let's go, say.

I'm trying to put my mouse over here and double click it and trying to put a cost center.

I can put a cost center here, but I cannot put a cost center here.

No, it's not working.

The reason is that field is disabled because the item category here is consignment.

So for consignment, you cannot have an account assignment.

Now, where is that controlled?

It's controlled here, not allowed.

Account assignment category is not allowed.

So that was consignment.

Now, in the next chapter, we'll briefly go through subcontracting.