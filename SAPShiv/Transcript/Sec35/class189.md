 
So let's summarize what we have learned about document types.

Item categories.

Combination.

We've seen that business processes are primarily modeled based on document type item category and account

assignment indicator.

So this dictates the major business process.

This dictates the sub business process because in a single business process, in a single transaction,

you can have multiple business processes like subcontracting standard service limit in a same single

transaction.

And this controls who is paying for it.

If it is blank, it's kept in stock, so the entire company is paying for it essentially.

If it is K, a particular cost center is paying for it.

If it is a a particular asset is eating the cost of that, so on and so forth.

Now, we have not seen the controls behind this or this yet, but we have seen the controls behind this.

And I equated that to the engine of the train.

The engine dictates how far this train is going to go, what speed it's going to go at, so on and so

forth.

And each of these compartments are more like the sub business processes.

You know, one is a pantry, one is a bar, one is a sleeper, one is a chair car, so on and so forth.

And in the document type, we have seen some controls.

So what are the things we have seen?

We have seen number ranges.

What kind of number ranges?

Internal.

External.

We have seen why we need to use internal and why we need to use external.

And we have seen.

Screens layout.

And we've seen that there are multiple screen layouts, one at the document level.

One at the item category level.

One at the transaction level, so on and so forth.

There are 5 or 6 possible categories.

And depending on the particular mode of that field, for example, the payment term is set to mandatory

at the transaction level.

Then it doesn't intersection.

It looks at all the screens and that's the reason why you should never delete these screens.

Don't ever delete them.

If you delete them, the system goes into a dump.

Okay.

Don't ever delete these fields.

If you delete these fields, you can't even recreate.

So never delete these fields.

Selection groups.

Okay.

They're.

They're provided by standard SAP for a reason, so don't ever delete them.

So this is screen layout and try to use the screen layout as little as possible.

Don't don't overdo it.

Okay.

Unless it's really required.

Don't don't work with screen layouts at this level.

You can work with these things suppression, mandatory, optional, hidden or the master data level,

because there's not a whole lot of complexity like this at the master data level.

But the transaction level, it's a little more involved.

It's based on a whole variety of parameters.

So don't don't over customize it.

I would not recommend it.

And then we have seen.

The linkage.

To the purchase requisition.

What kind of purchase requisitions can be converted to?

A purchase order or.

A stock transport order.

Again, you can just leave the standard as it is.

But when you create your own purchase requisition, for example, you have created a new purchase requisition

as a copy of.

In which case that purchase requisition, does it need to be linked to the new business process?

If yes.

Create a link here.

If no, don't create a link.

Think of this as the connection between two different engines of two different trains.

Right.

So from San Francisco to San Jose, which is a small distance, there's going to be one engine, a different

kind of engine.

And from San Jose, you're going to go all the way to Los Angeles.

Now, this engine will not work, right?

You have to have a bigger engine.

A very big engine.

And.

The transfer.

When you convert this train that's coming from San Francisco to San Jose into a long distance train,

the one that's going to LA.

Are you allowing to connect any engine to Any engine?

If.

Yes.

Obviously you don't do it right.

There is a certain combination that you do.

You don't allow the same engine to go to LA.

And you all have a different engine.

And that's what this linkage does.

This linkage.

Tries to say.

Okay.

Am I allowed to create a purchase order with reference to this kind of purchase requisition?

If yes, put that linkage here.

If not, don't put that linkage.

If you don't put that linkage, then the system does not allow you to create a purchase order with reference

to that particular linkage.

Example from NB you're allowed to create an NB.

Then you have created A Z and B one, let's say, new.

Purchase requisition.

And then from NB you have created AZIO1 like how we have created import order now do you allow NB one

to be converted to a import order if your business process allows it?

Make this entry.

If not, do not make this entry, in which case if somebody tries to convert from Znb to Z01.

The system fails.

And then what else have we seen?

We have seen number ranges.

What kind of numbering is internal?

External.

And we have seen situations why you might want to use external rare cases, but some cases use external

and where do you do that assignment?

And then we have also seen item increment.

So there is an item increment.

Ten, 20, 30, 40, 100, 203 hundred.

400.

You can specify that in the document type.

And finally, we also had allowed item categories.

This is more like what some business processes are allowed in this business process.

In a standard business process, you allow subcontracting standard pipeline.

And surveys limit everything under the sun is allowed.

But in an import business process, for example, you don't allow contracting, you don't allow pipeline,

you don't allow consignment.

So you don't allow a consignment from Kenya to the United States.

You don't allow a subcontracting between Kenya and the United States.

Right.

Those are not valid business processes.

You can leave them as is, meaning you can allow the system technically.

To have a subcontracting in import order and it might not be used by the business because they know

that there is no subcontracting between Kenya and India.

But why even allow it technically remove it if it is not a valid business process?

That way, nobody in the company, no user in the company will be able to create a subcontracting order

even by mistake.

For an import order.

Does it make sense?

That's where a allowed item categories.

Controls the subprocesses inside the main business process.

Think of this like the short distance train that does not have a pantry.

Do you want to allow a pantry?

Technically, yeah.

You can connect it.

No problem.

But do you want to connect it?

No.

There's no need for a pantry between San Jose and San Francisco, which is just 30 miles.

Probably there is not even a need for a restroom.

Probably there is no bar and there is no sleeping compartments.

Right now.

The analogy that I'm trying to make is these are sub business processes.

These are different compartments, like I said, like having a bar in it in the train, having a compartment

for a bar, having a compartment for a pantry.

Having a compartment for sleeping.

And in this case, the major business process being a short distance train.

You don't want to allow certain business processes.

And in the case of San Francisco to Los Angeles, which is a longer business process, you want to allow

certain sub business processes and you can allow that.

It's all controlled using the allowed item categories at the document type level.

We have seen the functionality behind item categories, but we have not covered the configuration of

item categories or account assignments.

We are going to do that in the next chapter.