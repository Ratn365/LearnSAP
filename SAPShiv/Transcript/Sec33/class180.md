 
And the final topic in the vendor master is.

It feels can be suppressed at the account group level versus purchase org specific level versus transaction

dependent level.

So we are going to basically talk about field.

Groups or field statuses.

Which means which fields can be suppressed and which fields can be hidden or which fields can be made

mandatory, optional, so on and so forth at three levels.

At the account group level.

This we have already seen.

And also not just with the account group.

Account group.

Plus.

Purchase.

Org specific level.

Meaning.

For us.

Purchase org.

Same account group.

We're going to suppress some fields.

And for India purchaser same account group.

We are not going to suppress some fields.

Another option is.

Transaction dependent.

This is very rarely used.

I'm going to explain it, but it's not really needed.

And if you want to try and avoid it, I've never used that.

So we know what this does, right?

An account group controls the field status groups and the field status groups control how each field

is displayed.

The standard example is the account group 001 controls these field status groups.

General Data Company code.

Data purchasing Data.

And if you go inside any of that field status groups, you select a group of fields and then you start

controlling whether they should appear or not appear.

Right.

But I'm saying that SAP is giving an option to control it, both just at the account group level and

also at the account group purchase.

Org specific level.

Why would you want to do this?

Let me give you an example.

This is an example for this scenario.

So, for example, we are a global coffee company.

We are operating in the US and we are operating in India.

Both areas.

Right.

So US is US zero one purchaser.

India is an.

Zero.

This is the purchase order.

In some countries it might be necessary.

To ask for certain fields, right?

For example, in India in 2017, there's going to be introduction of new tax bill called GST.

We don't know what documentation is required for GST.

Maybe apart from the standard tax number, there might be an additional tax number that's required.

Now for us for the same account group.

You're not going to need that tax number.

Another example.

Say in the US, most of the payments are done electronically and in India the payment terms are always

going to be standard, a fixed set of payment terms.

Or vice versa.

Either way.

So the payment terms is compulsory in the US because there could be different.

But in India it's not compulsory.

You can either make it optional.

Or you can totally suppress it, enter it at the time of purchase order creation.

You don't want to be creating new account groups.

That's going to cause more complication.

Because the requirement is specific to one purchase.

Org You can customize the vendor master in such a way that a particular field can be suppressed.

Or enabled at a particular purchaser level.

Now there is a constraint here that you have to work with.

If it is suppressed here.

You cannot enable it here.

However, the opposite is possible.

Meaning if it is enabled here.

You can suppress it here.

That is possible.

So visibility.

Is given lowest preference, meaning if it is enabled at the higher level, the count.

Group level, you can keep suppressing them at the purchase org specific levels.

But if a field is suppressed at the account group level, you cannot enable it at the purchase org level.

So basically, again, this is not something that you use all the time, but if you want to have purchase

org specific fields to be enabled, you can use that.

Typically this is done for legal reasons.

Convenience reasons or other business reasons.

Legal is like maintaining a separate tax code at one purchaser or one country code versus the other.

Business reasons is, you know, in the US, you know, we don't need to capture payment terms, they're

optional.

But in India they need to be captured or vice versa.

Convenience reasons could also be possible.

Like, you know, the vendor needs to be treated differently in one purchase org or one country compared

to the other country for Canada.

You maintain separate sets of data in the vendor master?

Sure you can do that.

You can create additional fields or use the existing fields and suppress them in us because they are

not required.

And enable them in Canada because they are required.

So we have created our own customer account group, right?

Z 100.

So go there.

Then.

Say general data or purchasing data.

Because we can't do this enablement for non purchasing data.

This is purchase data specific, right?

Say for example, terms of payment is an optional entry, generally speaking.

Okay.

But.

Go back.

And go to screen layout specific to purchase organization.

Right.

And then select that and click copy us and say us.

Zero one.

Okay.

And for us.

Zero one.

Purchasing data.

Terms of payment is a required entry.

Okay, Save this.

Now go back and I'll show you the difference.

So if you go to MK zero one creation of vendor and use Z 100.

For us.

Zero one.

Right.

It uses an external number assignment.

Okay.

One, two, three, four, seven.

Center.

And then.

Test.

Test.

We're not going to save this anyway.

And enter.

The terms of payment is made mandatory because we have specified a different set of conditions for purchase

for us.

Zero one.

Right.

Terms of payment is mandatory USD or other currency is anyway mandatory.

So for terms of payment, this has been made mandatory now.

Now let's try and create this for any other purchaser.

And it should not be asking us to enter the terms of payment, right?

So instead of US zero one, let's do 3000.

And one, two, three, four, seven.

Enter and say Test.

Test.

Us enter.

Then you see that it's not asking you to enter the terms of payment by default.

You have to enter the US currency and that's it.

This field is not mandatory.

This is how you can enable certain fields to be either mandatory or optional at a specific purchase

order level.

And like I said, whether you can suppress it at a purchase org level or not.

Or whether you can re-enable a field that's already suppressed in the account group are both two different

things.

One is possible.

One is not.

So in generally, anything that's suppressed at the account group level cannot be enabled at a purchase.

Org specific level.