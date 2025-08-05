 
So let's look at vendor Subrange in action.

So go to Sbarro.

IMG.

Logistics, General.

Business partner and vendors.

Go to control define account group.

Now, if you double click on any account group, you'll see that there's a check mark here called the

Vendor Range Relevance.

Only when you check this on will vendor ranges or vendor subranges be relevant for that account group.

Right.

So what we are going to do is create.

A new account group.

As a copy of Z or 0001, the standard account group.

And then.

And enter.

Make sure that vendor Subrange is relevant.

Typically out of a standard system for 0001 account group vendor Subrange is not checked on as relevant

if it is not in your custom account group.

Go check that on.

Without that, you won't get vendor Subranges.

All right, save it.

We're good there.

Okay, Go back.

Now, if you go create a vendor.

I'll show you.

There's a problem.

MK zero one and then say one, two, 345.

US zero one.

And Account Group Z 100.

Okay.

The US or Canada.

Enter.

Our currency is USD say.

Right.

Then here we hit enter.

It says enter a partner number.

What do you enter here?

That does not work, right?

There's a problem here.

What is the problem?

For Vendor account Group Z 100.

This partner or partner function.

VN is not supported.

Now, I don't want you to break your head over it because in partner determination schema, we are going

to cover what is a partner function, what are partner determination schema.

How to assign that to the vendor account group, so on and so forth.

For now, I just want you to do a small fix and not worry about why you are doing that fix.

Just do that fix and then we can go ahead and proceed with the vendor Subranges.

But like I said, in one of the later set of chapters.

We'll talk in detail about partner determination.

And in that chapter, we'll discuss all about partner functions in as much detail as possible.

So go to purchasing material management.

Purchasing.

And search for partner determination.

At somewhere down below.

So go select that.

And select partner roles.

And select define permissible partner roles for account group.

Okay, so select new entries.

Partner function vn vn for vendor and account group z 100.

So this is a warning.

Just ignore that.

And see.

Now, this is an entry that I want you to make without thinking too much.

Don't worry.

Why you are making that entry.

Like I said, when we discuss partner determination, we are going to understand everything about partners.

Now let's go ahead and create our vendor.

One, two, three, four, five.

And some test vendor.

And then somewhere in us.

Right?

Enter an order.

Currency is, of course, USD.

Terms of payment is what kind of terms of payment shall we use?

So zero zero for 14 days, 3% cash so we can pay the vendor in 14 days.

And incoterms is.

Ride free until the plant.

And there's no minimum order value.

Everything else would remain the same.

Click.

Okay.

And then one, two, three, four, five.

Vendor.

Save it.

One, two, three, four, five.

Vendor is saved.

Right now.

Open the same vendor.

MK zero one.

Order.

021, 2345.

Select Purchasing Data.

Click.

Enter.

This is where you enter Subranges.

If this is not enabled, you have to click on extras.

Subranges.

So click on subranges.

And here you have to create the subranges.

For our scenario.

We can do import versus export because we have discussed that scenario, right?

Import is import from Canada and all domestic is sourced from within the country.

So by default, everything could be domestic.

And only when the scenario is import do we need to have a different set of vendor master for those materials.

So we can just have one vendor subrange call it import.

Hit enter.

All right.

Let's go back and go to alternate data.

And it says no alternate data has been maintained yet.

You want to create one?

Yes.

And in that, go select import.

So what we are essentially doing here is creating a different set of purchasing vendor master data.

For import scenarios.

Click okay.

And let's say the currency is you are right and we have to immediately pay the vendor because it's an

import scenario and the incoterms is costs and freight, right?

And then there is also a minimum order value of 50,000.

Okay.

Do you see that there is purchasing data maintained for the import vendor Subrange.

Save it changes has been saved.

Now, if you go back, go to alternate data, you can see what kind of alternate data has been maintained

for this vendor.

In this case, alternate data has been maintained for import.

You can see that from the checkmark here purchasing data.

Now.

One, two, three, four, five is the vendor.

So what have we done here?

We have created a vendor.

One, two, three, four, five.

And for that vendor, we have maintained a subrange called import.

And for import we have maintained a different set of data.

What set of data?

Order currency.

Payment term.

Incoterm.

Minimum order value.

Right now for one kind of material, say, coffee beans or one.

Let's have one set of terms.

The regular set of terms.

And for coffee beans.

Oh two.

Will have the imported set of terms in this info record.

How are we going to maintain that?

As usually go to logistics, material management, purchasing.

And then in Master Data Info record, let's go create a new info record for 12345 for coffee beans.

Oh one.

Us zero one Plant.

Chicago.

Same plant.

Right.

And then click.

Okay.

Ten days.

20 days.

30 days.

Okay.

I'm not going to specify a vendor subrange here because this is the plain vanilla vendor data hit enter

Standard quantity is five.

Planned delivery time is five days and the net price is $10.

Okay.

Enter.

Enter.

Enter.

Save?

Yes.

Now if you go create a purchase order.

With vendor one, two, three, four five.

Coffee beans zero one.

What do you get?

You get the standard set of terms.

Whatever has been maintained in the vendor, master or overrided in the info record.

Now for coffee beans or two, let's go create the specific set of import terms.

Right.

What are they?

Say this is ten days, 20 days.

30 days.

Right.

And then here we're going to maintain the vendor Subrange.

See, because we have specified one, two, three, four, five as the vendor.

In the dropdown, it is automatically picked up that subrange.

Enter.

Okay.

And then plan delivery time is five days.

Standard quantity five.

Net price is what's the net price?

Say $12 because it's imported.

Enter.

Enter.

Enter.

Save.

Okay, now we're going to create purchase order.

M 21 n.

Against vendor One, two, three, four, five.

Enter.

Coffee beans or one.

Quantity one.

A contract exists, that's fine.

Now let's go to the header and check out what kind of terms we have.

The payment terms is zero zero for 14 days, 30 days, 60 days.

And then Incoterms terms is CPT.

Currency is USD.

If you remember the vendor slash OMG zero three.

Vendor One, two, three, four, five.

Purchasing data.

Enter.

Do you see the terms there?

The kind of match, right?

0004.

Payment Terms CPT.

Encode Terms.

And used as the order currency.

So everything that's there in the vendor master is being copied over.

And if you have put some kind of override in the info record that will be copied over to.

All right, Now you can save it.

Do the procurement.

Pay the bill.

Now.

This time we're going to create a purchase order for the same vendor.

One, two, three, four, five.

Instead choose the material.

Coffee Beans oh two.

Quantity of one.

Okay.

Now.

We have just changed the material.

The vendor has remained the same.

What happened?

It has chosen.

A different set of data, right?

What is the incoterms here in the vendor master CPT in the purchase order?

It's CFR USD.

Is the currency in the vendor master.

What's the currency?

Here you are.

Where did it pick it up from?

It picked it up from the vendor.

Subrange.

So this is the vendor master.

Weight in this data.

Does not match.

Because.

For the material that we have picked up.

The info record says choose a different set of vendor subrange data.

So where is that data coming from?

Go to alternate data on the vendor master and for import subrange double click that.

And now the data should match same vendor.

But the currency is euro.

Yes, it's euro.

And the terms of payment is 0001.

Yes, you got that?

The Incoterms is CFR minimum order value is 50,000, so on and so forth.

Right.

We didn't check the minimum order value yet, but the rest of the data is matching, right?

I see that the data is now matching.

Because the sub range is imp.

Now, how about the minimum order value?

Let's do a check.

Save it.

And there is some messages that has been issued.

Click on edit and you see that all the value below the minimum order value.

Right.

That means your order value should be increased by, let's say.

Thousand pounds would do.

Maybe not £10,000 would do.

Probably, yes.

Because 10,000 multiplied by 12 is going to be a big number, much bigger than 50,000.

Right.

So Standard Poe created fine.

All this happened because for the purchasing for record that we have created for coffee Beans oh two

we have specified the vendor Subrange.

You want to go see that again?

For coffee beans or to.

This is the key.

This is what has made all the difference.

This is what triggered.

The vendor Subrange.

This is what has triggered the vendor sub range.

This is the key.

So this is the purchase info record and the purchase info record vendor Subrange has triggered for that

material.

That the purchase order use data from the vendor subrange as opposed to the vendors main master data.

So think of this as the import scenario.

Because it's coffee beans or two.

And this is the regular domestic scenario.

The data for domestic comes straight from the vendor master.

The data for import comes from the subrange import.

So this is import.

The previous one was domestic.

And what triggered this?

The purchase Info Records Vendor Subrange.