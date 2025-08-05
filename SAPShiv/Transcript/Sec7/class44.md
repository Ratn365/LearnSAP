 
ster data.

Is the vendor.

Now, we know that there are so many different materials that we plan, produce or manufacture, but

when we procure any of these materials, who supplies them?

Well, my coffee store could have many different vendors.

Why do I need so many vendors?

Well, the answer is simple.

Not everybody can supply everything, right?

So, for example, there is a generic supply company called, say, ABC Supplies.

He can supply most of the materials, but he doesn't specialize in any.

And for baking related goods like the oven or baking sheets, I could procure them from central baking

supplies.

And for anything related to coffee.

Specifically for coffee.

We have another vendor and then and any other brewing supplies could be had from this vendor.

And each of them are different.

So you got to create so many different vendors.

So how is a vendor master structure?

So just like the material Master has so many different views, Vendor Master also has three views.

The general view.

Which contains name, number, etcetera.

Finance View and purchasing view.

General View.

Finance.

View and Purchasing View.

Let's go create a vendor.

So go to logistics.

Material management.

Purchasing.

Master data.

Vendor.

And then we have purchasing and central, then either go to purchasing and create only the general and

purchasing view of the vendors like so.

Or we can go to Central and create all the three different views.

Let's go to Central.

Go click X01.

And specify a vendor, say, for 002.

I think we have already created 4001.

Right.

And then use use zero one.

Purchase Order zero one Account group.

0001.

We don't want to really refer any vendor.

Just click enter.

So it looks like 4002 already exists.

So we're going to use 4003.

Give it a name.

Say coffee supplies.

Right, give a name, coffee supplies and then say CS.

For coffee supplies.

And it could have an address.

We don't care.

And he's in Chicago, the state of us.

Illinois.

Right.

You could also have a telephone number here.

So (312) 000-0000, and then you could have a fax number or email and all different kinds of communication

here.

And then hit enter.

Now, there are so many different fields, right?

We're not going to bother ourselves with all the different fields.

There are some important fields.

Yes.

For example, customer is an important field.

But not for us at this point.

So I'm going to only focus on the fields that we need for now.

Rest of the fields we're just going to gloss over.

Hit Enter again.

This is bank data.

Yes, bank data is important.

But when is bank data important?

When you want to pay the vendor.

Paying the vendor is a finance transaction, so we don't care.

Hit enter.

Recon account.

So although recon account is something that finance needs to worry about, but without a recon account,

we can't do certain transactions.

So make sure that you enter a recon account and then cash management group.

Select something.

Whatever is there, just put it in.

Hit enter.

Payment terms.

Now, this is an important parameter.

Let me explain what payment terms are.

So what is payment terms?

So if you take a transaction, say we have produced.

£100 of coffee.

So we produce £100 of coffee.

At $10 per pound.

So that's.

Thousand dollars.

So the value of the invoice that the vendor has sent is $1,000.

Now, when do we need to pay the vendor the $1,000?

Do we need to pay it as soon as we receive the invoice?

If not, how much time do we have?

That's exactly what payment terms dictates, and each vendor could offer a different set of payment

terms.

Let's let's, let's, let's examine a simple payment term.

Say net.

The net 30.

What does it mean?

It means that if you receive the invoice on Jan first.

You have until 30 days.

To pay the invoice.

So the vendor is giving you a credit for 30 days.

And then there's net 45.

Net 60, you get the picture.

On top of that, there is something called as cash discount.

So to encourage customers to pay earlier, vendors tend to give a cash discount.

Example net 30.

2%.

20 days net.

32%.

20 days.

This is another example of payment term.

What this means is if you pay within 20 days.

You get a cash discount of 2%.

So out of 1000.

You only need to pay 980 because the $20, which is 2% of 1000, is given as a cash discount.

So this is payment terms.

Let's see some examples of payment terms in SAP.

Now, remember, payment terms are mostly created by fee folks, so we don't really care about how to

create them as long as we understand what payment terms are.

So let's go and see what payment terms we have.

Huh?

Okay.

001 payment unit.

In some cases, that payment term is used, but for the most part, we use something like this.

002002 is a is a key for payment term for net 45.

And then there are some cash discounts.

That means that you got to pay the invoice in 45 days.

And if you pay the invoice in 30 days, you get a 2% cash discount.

And if you pay it within 14 days, you get a 3% cash discount.

Right.

So these are all different examples of payment terms.

There are some other scenarios like baseline dates, so on and so forth, but we don't need to get into

that.

For now select payment terms of 000 to.

And then hit enter.

Keep going.

You don't worry about Dunning.

And then the order currency is USD, say, and terms of payment is 0002.

Now why do we have two terms of payments here?

Let's see.

This is where the different views come in.

So the vendor.

Chicago coffee supplies had three views, Right.

Like any other vendor.

General.

Purchasing.

Finance or company code.

In company code view, you could have the payment term of 0002 and then purchase.

Org view.

You could have a payment term of 0003.

Why is that?

The reason is simple.

Remember how we structured our enterprise?

So in the entire US, you could have one company code and underneath that there could be multiple plants

and each plant could have its own purchase.

Org.

Right.

That means so if you take our coffee shop, we have registered it in Chicago as US zero one and.

Our main plant is in Chicago.

And then you could have more in Seattle, in New York, so on and so forth.

And purchase orgs could be assigned to each of these plants.

Or they could be assigned for more than one plant.

Either way, the point being, if you are maintaining vendor data relating to this particular purchase

org, you could have a different payment terms.

What it essentially does for you is let you have different payment terms for the same vendor, for different

purchase orders.

That means that you can choose to have a vendor pay in net 45.

In Chicago and.

Net 60 in Seattle.

That's the flexibility that SAP is providing us by giving us different payment terms at different levels,

one or the company code level or finance level and another at the purchase org level.

So that means that the same vendor can have so many different purchasing views, as many as you want.

One for each purchasing org.

Or if you don't want them, you don't need to maintain them.

For example, this vendor say ABC supplies say Chicago Brewing Company only works in Chicago.

In that case, there's no point in creating it for another purchasing or say, in Canada, if you have

a shop in Canada or Mexico.

And the next parameter is Incoterms.

What's an Incoterm?

An Incoterm.

Incoterm Incoterm stands for International Commerce in Co stands for International Commerce.

So when you trade goods across cities, across countries, there needs to be a standardized way of specifying

how the goods are transferred.

So say, for example, you want to ask the vendor for a certain set of terms, Say you want to ask the

vendor to deliver the goods free to your warehouse.

It's called FOB, which says Free on board.

And then.

Until what point?

Until.

Warehouse.

Sometimes it could be just until the dock.

Sometimes it could be until his own plan.

So a incoterm has two parts.

Part one is a standard term, and part two is a free form text.

You could qualify part one in part two, for example.

Free on board.

Free on board.

Until where?

Warehouse.

Another example is CIP, carriage and insurance.

Paid by whom until what point can be specified in part two.

Let's go see some examples.

Go to Incoterms and specify free on board.

Until the warehouse.

So Incoterms is basically an industry standard term.

That's used to specify the logistics of the purchase.

And then we have a whole bunch of indicators here, like the different kinds of control data.

Again, not all of them are important, so we're not going to worry about all of them.

But when we see certain business scenarios that require us to understand some of the terms, we'll revisit

them.

For now, just hit.

Okay.

Same thing with partner functions.

We're going to revisit them when we see partner determination.

Hit.

Okay.

And save.

You have created the vendor for 003.