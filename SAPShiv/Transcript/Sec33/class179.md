 
The next topic is one time vendor.

This is a topic that's available in the customer master tool.

One time customer.

Similarly, one time vendor.

What is a one time vendor?

A one time vendor is a partner or a vendor where we are only doing business once.

For example, you you're doing a marketing campaign.

It could be flyers, it could be an ad in Google, anything like that.

You just want to see if it works or not.

So you pick up a vendor, right?

A vendor that can do that service for you.

And you know that you're only going to do it once.

In cases like that, there is no need to create a brand new vendor master, put all the details in his

bank details, his his control details, all that stuff.

There is no need to put all that stuff in.

It's cumbersome.

Instead, you can create a one time vendor, which is a much simplified version of the vendor.

How simplified is it?

Basically it does not have address data.

It does not have bank data.

Right.

It has a separate recon account.

There is no control data.

So a one time vendor is vastly different from a standard vendor.

How?

Well, let's see it in action.

Right.

So where is our vendor?

Vendor purchasing create.

Or rather, let's create the vendor centrally.

Okay.

Vendor.

But what I'm going to do is show you the vendor creation side by side for two vendors.

So this is vendor one.

So and this is vendor two.

All right.

On the right hand side, we have a one time vendor.

On the left hand side, we have a standard vendor.

You could use Z 100 or you could use just 0001, right?

For one time vendor use KPD C PD.

Okay.

And company code is US zero one.

Company code here is US 012.

And for vendor, we're going to pick an external number one, two, three, four, six instead of one,

two, three, four, five.

And I think this uses internal number range.

Let's check that.

Yes, it does.

Let's check this.

Everything is okay now.

So far it looks the same, Right?

So this is a regular vendor.

This is a one time vendor.

Are we?

Regular vendor?

One time vendor.

Both are in us.

Let's say.

Okay.

Hit.

Enter.

It enter?

Do you see that?

This is what I meant by lack of control data in the one time vendor.

For example, there is no tax numbers, right?

There is no tax office.

There is no VAT registration number.

Right.

There is no proof of delivery.

There is no industry code.

There is no location.

None of this stuff is there?

Right click.

Okay, click okay.

And then there is no bank data, right?

Bank key, bank account account holder, blah, blah, blah.

That's not there.

Recon account.

A recon account is required.

For example, we're going to use the standard payable, but.

For one time vendors.

You use a special recon account.

Now, why do we use a special recon account?

That's something that we can discuss at a later point when we come to account.

Determination.

ET cetera.

ET cetera.

And again here there is so much of data that's missing, Right?

It's not required.

And there is no Dunning data, right?

There is no Dunning data.

And here in the purchasing data.

This order currency.

Okay.

You can put an order currency.

And then you can put the rest of the stuff also.

But that's not required, right?

Save it.

Save it.

So 100223 is the internal vendor on 10123456 is the regular vendor.

But what have we seen so far?

We have seen that there is a separate account group for one time vendors.

Right.

Let me make a note of that.

Vendor 10022, three.

This is a one time vendor.

And one, two, three, four, six is a regular vendor.

And what were the differences that we have seen mainly with bank data?

No control data.

These are the main key differences.

Apart from that, we also use a separate recon account.

This basically we don't care too much about the address details, so on and so forth.

Now let's create a purchase order.

M 21 N with this new vendor.

What's the new vendor?

10023.

100223.

Okay, This is a one time vendor and let's create a coffee beans quantity 1 or 10, whatever.

Because it's a new vendor.

It doesn't have the purchasing data.

Okay.

Contracts exist.

Scheduling agreement exists.

We are all good there.

Click save.

Oops.

Please maintain the vendor's address.

Okay.

Where do we maintain the vendors address?

So go to the address section and then enter a name.

The name that we have entered in the vendor master is being overwritten here because it knows that it's

a one time vendor and you need to override it with a different set of data.

Here we can specify that it's Smith and Company.

Some street and some city.

Chicago.

What US country.

Some telephone.

Some details.

Right.

Now let's save it again.

Standard PO 451.

The PIO is created.

Let's make a copy of that.

Good Mega.

Mega would not be much different because it's justrillioneceiving the goods.

Do a goods receipt against the purchase order.

In coffee storage location.

Click item.

Okay.

Check if everything is okay and then save that po.

Document is okay.

Save it.

All right.

Now against the same.

Let's do an invoice receipt.

Miro.

So this is your invoice date and put the purchase order number in there.

The amount is for $10.

Right.

So enter the amount.

$10.

Specify payment baseline date.

Let's say it's today.

And everything looks green.

Now let's save it.

Here.

It's asking you for the bank details.

What's the bank account?

What's the bank reference?

What's the tax number?

What's the other control parameters that are typically coming from the vendor master.

Right.

You can enter all the bank details here and then save it and your invoice will be posted.

So why are these details required?

These details are required because we did not specify them in the vendor master of a one time vendor.

Now.

Let's cancel this.

Go back.

And can you use this one time vendor again?

Yes, that's the idea of creating a one time vendor.

You create a one time vendor.

102223 and use it again and again.

Any time you're going to do business with a vendor just once.

It could be a marketing campaign.

You're only going to run it once and you're only going to deal with that vendor once.

Use a one time vendor.

10022, three.

You can use a one time vendor for a sample.

Food that you are obtaining from some company that you are only going to use once.

Right.

You can use the same vendor for any activity where you're not going to do business with that vendor

again and again and again.

If you are going to do business with that vendor again, you could create a new vendor master for that

with all the bank details, all the purchasing details, all the correct address details, so on and

so forth.

The standard vendor.

If not, you can just create a one time vendor.

Use that vendor again and again and again.

And any time you use that, the additional details that we skipped during the vendor master creation

of the one time vendor has to be entered at the appropriate time in the purchasing cycle.

For example.

What is the data address?

Data.

We enter that in the purchase order.

We don't typically do that for a regular vendor, right?

It's all there in the vendor master and it flows down to the purchase order.

But for one time vendor there is no address or the address that's mentioned.

There is just junk.

It doesn't matter because the vendor is different every time for one time vendor.

Same with bank details.

It's a new vendor.

His bank details need to be entered during the invoice settlement.

So in terms of configuration.

Let's go to SPRO.

IMG.

Logistics.

General business partner.

Vendors control.

Like I said.

The standard one time vendor with internal number assignment is KPD or KPD.

So if you go inside KPD, this is the key that differentiates a one time vendor from a non one time

vendor.

A one time vendor has this checked on?

And when you go to partner determination, you'll also see that, you know, these schemas are not available

for one time partners.

At this point, you don't know what this partner determination schema does, so don't worry about it.

And also the data here like company code data, general data, most of the data might be suppressed.

See most of the data is in the suppressed section.

It is not needed for one time vendor.

But like I said, the key parameter is that it should be marked as a one time account.

So you can go to any account group, copy it like the way we have created Z 100 from 0001.

You can copy it and mark that as a one time vendor and it becomes a one time vendor.

It displays all the characteristics of a one time vendor.

It might have all these fields checked on to non suppress.

But you can go and suppress them any time you want.

But the key point is that if you want a vendor to be a one time vendor, check the one time account

on.