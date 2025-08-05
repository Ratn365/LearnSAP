 
The previous section.

We have seen document type.

And I have told you that document type is like the engine.

It controls the entire train.

So.

Purchasing is essentially a business process, right?

It could be a standard purchasing.

It could be a blanket purchase order.

It could be a stock transfer, if you consider this as the entire business process.

It's controlled by the document type.

Example.

NB Standard purchase Order UB Stock transfer order F0 framework order or blanket purchase order.

So on and so forth.

And what does it control?

Controls number ranges.

Controls line item increments.

It controls screen sequences.

It controls the allowed item categories.

It controls the linkage between PreK purchase requisition and PO.

So the document type sets the stage for defining the business process or the transaction overall.

Now, underneath that, there are so many different subprocesses that are possible.

Example, in a standard purchase order.

You could have the first line item.

Coffee.

Procured for stock.

So the item category is blank.

And the second item category is, say, paper.

And that could be produced or procured against a cost center.

For example, the HR needs paper.

And.

Another category could be a customer needing some coffee.

And we are directly asking the vendor to ship the goods to the customer and that.

Is called as third party.

As for third party.

The point I'm trying to make is.

Item category.

And account assignment control.

Each of the subprocesses inside the main process.

Or you could say that they control the line item.

The behavior of the line.

Now add the line item level since there are two controls we got to learn about each of these controls.

And we know the purpose of these controls, right?

The item category controls how the item behaves defines the business process.

So this is the key driver.

So this defines.

The sub.

Business.

Process.

This, on the other hand, defines.

The who whom we are procuring the goods for.

If it's blank, it's procured for stock.

If it is something else like K for cost center or.

As for third party.

E for asset, so on and so forth.

So there are two parameters at the line item level.

One is the count assignment that controls whom we are procuring the goods for.

An item category that controls the sub business process.

So where are these item categories?

So go to SPRO.

IMG.

Material management.

Purchasing.

And define external representation of item categories.

What is this external representation?

Go inside and you can see that these are all the possible list of item categories.

How many are there?

Like 9 or 10 of them.

And the first thing that you notice there is that there is no.

New entries, right?

Is there a new entries?

There is no new entries.

Doesn't matter if you are in change mode or display mode.

There is no new entries.

That means you cannot create new item categories.

So SAP has provided a list of item categories.

Like ten of them, standard limit consignment contracting, third party text, so on.

And those are the ones that we have to live with.

We cannot change them.

Nor can we create more item categories.

What we can do here is essentially change the external representation, for example.

If you go create a purchase order.

Say we have a material

and the item category is either blank or one among these.

This is dictated by the business process, right?

The main business process, the document type.

Now, if it is B limit, you can put B If it is D for service, you can put that as D.

If you want to call limit as something else, for example, if you want to call it as Z, you can change

that here.

But internally, the item category is one for limit.

So there is an internal representation and there is an external representation.

All shapes loving you to do is to change the external representation.

It's like a skin.

It's like a paint.

You can change the paint.

But essentially what's inside is this column 0123, four, five, six, seven, eight, nine.

So too is consignment.

Three is subcontracting.

Four is something else.

Seven is stock transfer.

Nine is service.

But externally.

In the purchase order screen.

You can call them whatever you want.

A single character.

Z a.

B, L Blank.

SAP has suggested some.

And it's very, very, very, very rare to change this.

You never do that.

It's.

It's allowed, but it's never done in a project.

So what's inside this item?

Category?

What does it really control?