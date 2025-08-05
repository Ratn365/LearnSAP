 

Lecture thumbnail
4:36 / 4:41
Now, if you have observed the vendor master info record and material master how they work pretty closely.

You might have a question here.

So here is our vendor master.

And we have maintained subranges meaning alternate set of vendor master data.

For import versus domestic scenario.

And here we have a material that's domestic.

And here we have a material that's imported.

Right.

For this combination.

There is one info record.

And for this combination.

There is another info record.

So the domestic is the standard scenario.

Right.

So this is basically what we have here is domestic data.

And here in the subrange we have imported data or any other combination of vendor master data that we

want to be different.

So this is all domestic standard domestic info record.

So you don't specify anything there and then for record, but I'm just specifying that as an FYI.

But over here we specify that the ESR equals imported.

And that's how we specify that the vendor.

For this material.

Use the vendor Subrange data for imported vendor Subrange.

The question that you should have got at this point is.

The info record is supposed to supersede or override the data that's coming either from the material

master or the vendor master.

Right.

For example, there is delivery tolerance here.

You specify a delivery tolerance of ten days here?

He specified tolerance of 12 days here.

This will supersede.

The master data, right?

So in cases like that, for example, if this material is imported and you want to have a different

set of data.

Then the standard.

Why don't you specify that here instead of maintaining a separate vendor or a vendor?

Subrange.

Why did SAP design this in such a way that you have to maintain different versions of vendor data rather

than specifying it in the material info record or purchase info record?

The reason is.

Number one, this is not a very widely used scenario.

Okay.

It's not always used.

Number two.

The info card only has a certain number of fields.

For example, it does not have partner function data.

It does not have payment terms.

It does not have all the data that you have at the vendor master.

And in such cases where you want to have different sets of data like partner function, payment terms,

it is not possible using the standard info record.

Now, you might be wondering.

Why did SAP not design the info record to also include partner function and payment terms?

The reason is simple.

This scenario is not a commonly done scenario.

The vendors are range, so it doesn't make sense to overload the info record to have all these possible

scenarios.

There are other reasons, but the point being info record is not the place for everything in the vendor

master to be there.

It just controls critical pieces of information.

That's a combination of both the vendor and material.

We'll talk more about the info record in the next set of chapters.