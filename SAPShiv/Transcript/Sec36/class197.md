 
Next we are going to talk about.

How data is copied from the source to the target.

Example is purchase requisition to purchase order.

Think of.

Stuff like item category.

If you mention an item category as K cost center in the purchase requisition and you create a purchase

order with reference to that purchase requisition, what would be the item category?

Will it flow through?

Yes, the item category specified in the purchase requisition will flow through to the subsequent document

the purchase order.

However, this can be overridden.

Same is the case with account assignment category.

It flows down from the source document to the target document and it can be overridden at the target

document level.

Want to see an example?

So go create a purchase requisition.

M 51 n.

The material is coffee beans.

Right.

And the account assignment is K.

Okay.

What plant is it?

Chicago one.

And what's the cost center?

The cost center is admin zero one.

Okay, so we have created a purchase requisition.

With account assignment category of.

K Center.

Now let's go create a purchase order.

Referencing that purchase requisition.

Okay.

Copy it.

Here.

Enter the vendor.

4001.

What do you see?

The account assignment here.

The account assignment that was entered in the purchase requisition is copied over to the purchase order.

Right.

If you would have entered an item category that would have been copied to.

As an example.

You can try this.

Create a purchase requisition with item stock transfer, not the regular blank.

And create a purchase order with reference to that purchase requisition.

The stock transfer item category you comes over and sits in the purchase order.

Now the question is.

Why is it copied?

It's not just item categories and account assignments.

You enter a material in the purchase requisition, it is copied over to the purchase order.

You enter a quantity, the quantity is copied over.

You enter texts.

You enter the plant.

You enter info record.

You enter pricing.

All of that is copied over.

Well, pricing is not copied over, but most of the stuff is copied over.

This is not just from peer to peer.

It's copied over from contract to release order or any other source document to target document in purchasing.

But why does the system do it?

You know what's really the purpose of it?

The purpose is to preserve the intention of the person entering the source data, for example.

Let's take the case of purchase requisition to purchase order.

So who creates purchase requisitions?

For example, in the bakery.

Somebody is making cakes.

The baker.

So the production department needs flour.

£100.

Sugar.

So much.

A stock, right?

So he creates, for example, a purchase requisition.

All those quantities.

Similarly, the HR department needs paper.

And the paper could be non stock or stock, depending on how you want to treat it.

If it is non stock, you enter the corresponding account assignment category like cost center.

So on if it is stock, you leave it blank.

So there is a quantity and there is a material, so on and so forth.

Similarly, the sales department want to order some coffee to the customer, right?

And it's going to be a third party dropship, meaning the vendor is going to drop the goods directly

at the customer's location.

So these are all examples of purchase requisitions, right?

These are done by the respective department.

The sales department does purchase requisitions for third party.

The HR department does purchase requisitions for consumables like paper.

The baker.

The production department creates production orders.

So purchase requisitions that are required for production orders and who converts them to POS because

these purchase requisitions don't reach the vendor, right?

They are just requisitions, requisitions for goods.

Ultimately they need to be converted to purchase orders.

And who does that?

The purchasing department and the purchasing department has to respect the requirements of the respective

departments like HR sales production, because they are the people who need goods.

The purchasing department is just facilitating the requirements of goods from different departments,

so they have to respect the data that's flowing in from the source document like quantity material,

if any, account assignment.

Item category.

Payment Terms.

Incoterms.

All this stuff has to be preserved.

And on top of that, the purchasing department is typically free to do changes.

Not in all cases, but in certain cases, for example, quantity can be changed.

If the production department needs £100 of flour.

Some other department says the sales department needs £200 of flour.

Both these purchase requisitions can be combined to one purchase order and the quantity can be changed.

Right.

That is in the domain of purchasing department.

But typically the data that's entered by the different departments has to stay the same.

And they can be taken forward by combining or subtracting the data or quantities, depending on the

convenience or the vendor or the convenience of the purchasing department's.