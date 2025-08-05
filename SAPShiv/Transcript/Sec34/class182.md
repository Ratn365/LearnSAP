In this section we will talk about info records.

We have already seen info records at the very beginning of the course.

Now with the renewed knowledge.

We're going to recap info records.

And then see what kind of customization is possible in info records.

So what is an info record?

An info record is a combination of material and vendor.

Example.

A vendor that supplies a particular material.

Supplies it at what price?

What ordering units, whether he can supply it as a standard material or a subcontracting material or

a consignment material.

What is his specific vendor material number?

So on and so forth.

To put it in pictures.

It goes something like this.

This is our material, right?

It could be coffee beans.

It could be anything.

And then we have our vendor here.

And then we have the info record.

Material and vendor are examples of the basic kinds of master data.

You know, in SAP there are four different kinds of master data.

Overall in all the modules put together.

Materials.

Customers.

Vendors.

Assets.

Assets is something that's used in finance customers is something that's used in CRM.

Vendors see something that's used in SRM.

And material is a master data that's used across the board.

Now Info record is a specific master data that's used only in purchasing.

In sales.

They use a different info record.

It's called customer material info record.

The point being, these are secondary master records that are used in specific modules and they don't

have as much importance as the main master data.

Also, in one of the previous chapters, we have seen that master data flows down to the transactions.

For example, this is the master data, right?

Vendor plus material.

And what kind of transactions do you do with that?

You create.

A purchase order.

You create purchase order, scheduling agreements, contracts, any kind of purchasing transaction.

And like I said, data goes from the master data and sits in the transaction.

Right.

So what kind of data goes in, sits in the transaction?

For example, from the material.

Let's see what goes in.

To the transaction.

Things like texts.

What are texts?

Texts are small little pieces of information that sit in the material master.

And when you create a purchase order for that transaction, it goes and sits in the purchase order.

For example, if there is special instructions for a material, this material needs to be packed in

this way or this material needs to be stored in this way.

And you want to let the vendor know.

You put a text in the material Master purchasing view.

General view.

And then when you create a purchase order, the text goes and sits there.

Now, we have seen this example at the very beginning of the course.

And then when we cover text determination in one of the later chapters, we're going to cover texts

in very great detail.

All right.

And then we have purchasing.

Group.

You know what's a purchasing group, right?

It's available in the purchasing view of the material master.

And then we have planned.

Delivery time.

How long does it take for the material generally to be delivered to us?

That's generally used in planning, but it's also used in the purchase order to arrive at the delivery

date if we order today.

When do we get the material?

Right.

And then we have ordering unit.

How is this material ordered?

Is this material ordered in pounds or kilos or tons?

Delivery tolerance.

We have seen tolerances already.

Remember?

It dictates by how much we can deviate from the standard delivery quantity.

Is it okay if the vendor delivers 10% less or 10% more?

Right.

These are all some of the data that sits in the material master and flows down into the purchase order.

The yellow shows the material master data.

And then.

In green.

Let's talk about the data that comes from the vendor master.

What comes from the vendor master?

Incoterms texts.

Address, so on and so forth.

Right again.

This comes and sits in the purchase order.

And when I mean purchase order, I could mean purchase order, contract scheduling agreement.

Right.

Now.

What does the info record do?

Info.

Ricard is basically an override.

Plus some info.

Additional info that neither the material nor the vendor has.

So it plays both roles.

It provides additional information.

On top of that, it can also do an override, for example.

If you think about, say, delivery tolerance.

There is a delivery tolerance here in the vendor master and that delivery tolerance can be overridden

here.

For example, there is a delivery tolerance of 10% specified in the material master.

But for this vendor, say ABC Foods and Coffee, the delivery tolerance is not 10%, it's 15%, 8%,

whatever different percentage you want.

When you create the purchase order for that material and vendor combination, remember a material and

vendor combination.

Is what's an info record?

And data from the info record also goes into the purchase order.

Right?

And when it goes there, it supersedes the data that's coming from either the vendor or the material.

This supersedes.

Or overrides.

Material master or.

Vendor master data.

Right.

That's the concept behind info record.

It's an override, plus it's additional info that's not available either in the context of the material

or vendor.

Example material is $10, $10 from home, $10 from one vendor, and you can't specify that either in

the material master or in the vendor master.

You can only specify that using a combination of material and vendor in the infrared.

Right.

That's one example of maintaining data or info through a combination of material and.

And an example of superseding is delivery tolerance.

Delivery tolerance is 10% of the material master and you override that in the info record with any percentage

you want.

It's not just delivery tolerance.

You can override.

Ordering unit.

You can override text.

You can override confirmation control.

Also, you can specify what type of info record this is.

Is it a standard?

Is it a subcontracting?

Is it a consignment?

That's something you can't specify in either of the other material.

Masters or vendor masters.

You can also specify something called as vendor material number.

I'm calling it VM because I don't have space here, but it's not called VM in general vendor material.

We'll talk about that.

So the big picture I want you to take away from this screen is that there's master data that goes and

sits in the purchase order or purchasing transactions, and an info record contains additional information.

That can be used for purchasing and without info record, you can't really create a purchase order because

price and other sensitive information that is really necessary for a purchase order is available only

in the info record.

On top of that, you can also supersede certain information that's coming from either of the material

or vendor master data.

Now you already know what texts are, what delivery tolerances are.

We have what incoterms are.

We have already seen all of this stuff.

We've already seen the types of info records, standard consignment subcontracting when we have covered

the respective scenarios.

Vendor material number.

This is the only thing that we have not seen so far.

So we'll create an order, create an info record and see how vendor material number works.