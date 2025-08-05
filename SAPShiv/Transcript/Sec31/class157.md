 
The next question is how do I know which control is important?

That's where you need to understand the basics of customizing.

Customizing in SAP follows certain principles.

And it doesn't matter if you're learning SD, fi, CRM, CRM, they all follow these basic principles.

So I'm going to go describe the 5 or 6 most important principles or basics of customizing.

Okay.

The first one.

Is account groups.

They typically control the master data.

Example, every vendor is associated with an account group.

Every customer is associated with an account group.

Every material is associated with a material type.

It plays a similar role to the account group.

I'm just calling it account groups here for simplicity.

So account groups control master data.

When we come to the vendor master or material master customization.

We'll see what account groups are.

So master data is controlled by account groups.

Transactions are controlled by document.

Types.

Not just document types.

There is item categories.

These account assignments, so on and so forth.

So document type controls, plus item categories.

Let me put it this way.

Control how a transaction behaves.

Example A purchase order is different from a blanket purchase order.

For purchase order you use NB.

For blanket purchase order.

You use FB or FO framework order.

For a stock transfer you use UB.

These are all different document types and the control how the transaction behaves.

Standard transaction is different from a framework.

Order is different from a stock transfer.

Right.

They are controlled by a combination of document type and item category.

The third.

Important control is the condition.

Picnic.

This is how SAP customizes pricing.

Outputs is messages.

Texts.

Partners.

So on and so forth.

Many things.

So between the three of these, you control 50% of the customization.

50% of all customization is just done between these three major pieces of configuration.

Account groups control the master data document types Item categories.

They control the transactions and condition.

Technique covers everything else like pricing outputs, tax partner determination.

So what else do we have apart from these?

So these are.

Smaller things, right?

Like.

Other controls.

These control things like plant configuration, enterprise structure, vendor customization, movement

type.

Storage location.

Customization.

Tolerances.

Number ranges.

So on and so forth.

Again, some of them are specific to some of them are not specific to.

But if you want to learn next or next.

Number range is a common parameter, but tolerance is probably not.

SD might not have tolerance or CRM might not have tolerance, or they might not be involved in customizing

movement type.

SD might not be involved in customizing a plant, but they have their own enterprise structure elements.

So this is where.

You are doing specific stuff, some of it and some of it is generic.

Once you get to know the philosophy, like there are number ranges, there is enterprise structures

and there is things like tolerances.

These can be applied across many different functional areas.

Like even SAP needs to understand what's a plant.

They also have number ranges.

They also have tolerances.

They also need to understand customers, materials, vendors, movement types.

But the customization might not be there.

They have their own set of customization.

Right.

And then we have some global controls.

For example, activating split valuation.

We have seen split valuation previously, right?

But where do you activate it?

It's a universal activation for the entire instance.

That's an example of global control.

This is not even 5%.

This is like 3% or 2% of the entire set of controls.

Right.

And then there are some transaction level controls, very few of them.

The point being, focus your energies here.

If you understand these three elements, account groups document type item categories.

Condition technique.

In fact, you are not even at 50%.

You are at 70%, I would say.

And I'm not exaggerating.

This laid the basic foundation of your configuration and the rest of the things just fall together.

Or there might be some specialized areas where you take a loop, take a detour, learn things like movement

type, learn things like tolerances, and then come back into the main loop.

Once you understand these three elements.

You know, most of the configuration.