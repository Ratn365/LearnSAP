 

Lecture thumbnail
6:01 / 6:04
The next topic is vendor.

Sub range.

Typically this is abbreviated to vsr.

If you go look in the forums or help that ASAP, you will see the term VSR.

Vendor Subrange.

What is a vendor Subrange and why do you use them?

A vendor.

Subrange is like having a new set of vendor data for a specific set of products.

Let me explain how and why we want to do that.

So this is America.

Lake Michigan.

And we are here somewhere, right?

This is Chicago.

And this is Africa, Kenya.

There's a vendor here and there is a vendor here in San Francisco.

Now.

Let's say we are dealing with this vendor and for all local procurement, right?

Anything within the US.

He offers a different set of terms and for all import from Kenya.

He offers a different set of terms.

What kind of terms?

Well, let's take some examples.

Local versus import.

Right.

For example, the payment terms pay in 60 days for local and for all import.

It has to be prepaid.

Why?

Because import is typically more risky.

So for import it has to be prepaid.

That's the way the vendor wants it, right?

So for local you can send the PO straight to the vendor.

But for import, he needs the PO to be sent to a special importer.

A different address.

Basically, you know, he is qualified to process all import orders.

Right?

Or.

Order currency for all local USD and for all export its euro or GBP.

Right?

That's possible.

Well, in case of us, it's the default currency.

But if you're implementing something in Singapore.

All import will be in USD, which is typically a global currency and all domestic will be SGD.

Right.

Different set of incoterms.

The fight will only be offered until the docks, not until the warehouse in case of import, but in

case of local.

I'll deliver everything until your warehouse.

And in case of local, there is no minimum order.

You can place an order for $1,000.

No problem.

In case of import, you need to have at least an order value of 50 k.

You know, these are all examples of situations where the type of sale determines the terms that that

vendor is offering.

It's the same vendor.

But different modes of operation from an operational perspective for different set of materials, imported

coffee, different set of terms, Domestic, different.

If you want more examples, think of import control materials, defense materials or defense raw materials.

They have a different set of terms.

For example, if G is building something that requires some materials that are sensitive, right?

In cases like that, the same vendor might offer a different set of terms, but for regular materials,

another set of terms.

Think of perishable materials.

Perishable materials have different set of terms and, you know, non perishable materials might have

different set of terms.

Because the business of perishable materials is different, the margins are different.

Everything is different for perishable materials.

And when mean terms, it's not just payment terms in code terms, it's a whole lot of these data, all

different kinds of purchasing data.

Right now, put it on paper.

So this is a vendor, right?

And this is material one say perishable.

This is material too, that is non perishable.

You can substitute these for import versus export or import versus domestic, any different kinds of

materials.

And for this combination.

You need one set of data.

One set of vendor data, right?

Because these terms come from the vendor.

And for this combination, you need another set of data.

And when a main set of data, the things that we have discussed in the previous slide like payment terms,

Incoterms.

A mode of delivery, so on and so forth.

So what is this combination of vendor and material called info record?

Right.

So it's in the info record that we specify that for non perishable.

I need this set of terms from the vendor and for perishable.

I need this set of terms from the vendor or vendor is forcing us with that set of terms.

So that is why you specify the subrange in the info record.

And the vendor needs to have all these different sets of data maintained separately, and that is called

vendor Subrange.