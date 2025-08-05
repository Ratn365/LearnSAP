 

Lecture thumbnail
0:00 / 8:06
Now we are going to discuss the vendor master.

So Material Master is the first piece of master data we have discussed.

The discussion on vendor master is also going to be very similar.

So what is the agenda for Vendor Master?

First we are going to discuss the overall structure.

And important fields.

Again, this is going to be very similar to the material master in the Material Master.

We have discussed how the overall structure is.

And then we moved on to discuss about some of the important fields, like material groups, so on and

so forth.

Number two.

Is a discussion on the vendor.

Account.

Group.

This is similar to the material type in the material master material type in the material.

Master plays the same role as the vendor account group in the vendor master.

And then we'll discuss something that's very specific to the vendor master.

Which is.

We render.

Subrange a number four.

We'll talk about what's a one time vendor.

A number five.

We'll talk about purchasing group or transaction specific.

Field selection.

Well, don't worry about all those terms there.

We'll go over each of them in detail.

So what is the structure of the vendor master?

We have seen that the vendor master has basically three sets of views.

I'm not saying three views, three sets of views.

So if you consider vendor master as a pie.

You have three views inside it or three sets of views.

The first set of you is called the General.

Section.

Think of it as a section that has one or more than one view.

The second section is called the Purchasing View.

The third section, of course, is the finance or company code view.

If it helps.

SAP has designed the customer master also in a very similar way.

There will be a general, there will be a sales, there will be a finance.

It might be a little difficult to understand why SAP has created it this way, but as we progress,

as we keep doing transactions and customization, you'll understand the need for the vendor master to

have purchasing views.

Finance views and general views separately.

All right, so.

What's there in the general view.

Well, in the general view, we have address details.

Where does the vendor stay?

Where is he located?

What is the phone number?

Fax number.

Email.

After that, there is some control data.

Control data is used to identify the vendor further.

For example, what's his tax identification number or what is his credibility as a vendor?

Right.

There are global identification that can be used to identify vendors.

So that's all there in general data.

And then there is also payment data.

Like if you want to pay the vendor.

How would you pick?

What's the bank details, so on and so forth.

How about the purchasing view?

Purchasing has so many views.

The purchasing has partner functions.

We haven't touched upon partner functions yet.

There is a special chapter dedicated to partner functions, and in that we're going to discuss what

really is partner functions.

Why do we need to create partner functions?

We'll create partner functions and everything that's got to do with partner functions.

But for now, just understand that partner function represents the role that a particular entity.

It could be vendor, it could be somebody else place in the transaction.

A simple example I can talk about is if you do a transaction on Amazon, how are you doing it?

You are paying Amazon and if you see closely, it's not Amazon that's delivering the goods, right?

It's some other vendor.

It will be displayed somewhere in that screen saying delivered by so and so.

What's the point?

The point being, the entity delivering the goods is different from the entity taking in the payment.

Amazon versus the person selling that stuff on Amazon.

And they each play a different role in that transaction.

And that's an example of partner functions.

We'll learn more about this when we go to the partner function determination chapter.

All right.

And then there is also some purchasing data like this represents a critical data that's needed for purchasing.

Like.

Purchase Order Currency.

Purchase Order.

Incoterms.

Purchase order.

Payment terms.

Delivery tolerances.

So on and so forth.

And then there is finance data where you'll have the account details, bank account details, payment

details like payment terms, so on taxation and all that stuff.

Stuff that we are not very worried about.

And why do I say that?

Because we are consultants.

We don't care about most of the finance details.

Which bank account, blah, blah, blah.

So it's not just us consultants who are interested in the vendor master.

The finance people, either an AFI consultant or the users of the financial system also has a stake

in the vendor master.

So this part.

Is not really our domain.

This is all the domain of the consultant, but we need to know that such a view exists in the vendor

master and most of the bank details and payment terms come from the finance view of the vendor master.

And what do we have here?

The general view is necessary for everybody.

Both consultants and consultants.

And the purchasing view is probably the view that we care about the most because that's where most of

the purchasing data is.

All right.

So now what we are going to do is go create a vendor and see all the different views.