 
How about the account assignment category?

Just like the item category.

The account assignment category is also a single letter like K for cost center A for assets, S for

third party, so on and so forth.

Where are the configured?

Go back.

Go to account assignment.

Maintain account assignments.

And if you look at cost center, say, the one that we have been using quite a lot.

K for cost center.

These are the controls behind a cost center account assignment category.

Now let's go back for a bit.

Can you create your own item categories?

Yes, you can create your own item categories.

Although it's very rarely done, you don't typically create new item categories.

The existing item categories are more than enough because they cover all possible ways in which costs

can be captured.

Assets.

Third party cost centers.

Internal orders.

Production orders.

Plant maintenance orders.

Projects.

Anything.

Everything is taken care of.

It's very rare for you to create your own account assignment Group number two.

Can you change the description of these existing item categories?

Like Can K be changed to Z?

Now you can.

You can't do that.

But you can copy it and create your own account assignment category and very well use it.

No problem.

As long as the controls are all there.

Right now, if you go inside the account assignment category, say cost center.

You'll see that there are some controls like gr receipt goods receipt.

Invoice receipt.

These controls were there in the item category, too.

Right.

So for a combination of item category, account assignment category.

If there are conflicts.

Which configuration wins.

The thumb rule is item category configuration.

Supersedes account assignment category configuration.

Now, there is rarely going to be any kind of conflicts.

If at all, there is a conflict, this configuration will supersede this configuration.

Example.

Our grand indicators.

Okay.

Now, if you take item category B.

Okay.

B is limit, right?

Limit does not have.

Gian.

You know when limit is used, right?

They're used in the context of framework orders.

Account assignment Category K.

Cost center allows.

Now, if you use limits and use cost center, which one wins this or this?

Obviously this control wins because item category controls always supersede account assignment category

controls.

Now, what about the different fields in the account assignment category?

Well, let's look at the bottom part first.

The fields.

Right.

And it looks very much like how we see the field status groups in the master data like vendor master

or material master or even transactions.

And it says there is a mandatory entry.

Optional entry display hidden.

Right.

So if you go to the cost center, okay, the cost center is required.

That's what the mandatory radio box dictates.

Right.

So if you go create a purchase order.

M 21 n.

For some vendor.

What a material.

Write the account assignment tab doesn't exist here, but when you put the account assignment category

K, automatically the account assignment tag comes up.

Now the controls in this tab.

Are what these fields dictate.

Is an asset number required in case of cost center account assignment category.

No, this is hidden.

If you make it mandatory, that will come up.

But it doesn't make sense to make it mandatory.

It's not required.

Right.

So the entire tab for account assignment, the fields in it, what's required, what's mandatory, what's

hidden.

Is controlled at the account assignment category level.

We have talked about these fields goods, receipt, invoice, receipt, gr non evaluated.

These are available in the item category as well.

And if there is a conflict, you know which fields win.

Account assignment changeable.

An account assignment changeable at.

Now, this is used in specific cases.

For example.

This field account assignment changeable at iar means you can change the account assignment category

during invoice receipt and you can do it for a cost center.

Now these fields, the detailed information section like account assignment changeable attire derive

account assignment are not used a lot.

So don't worry too much about those fields.

Account modification is used, but we need a more elaborate discussion on how accounts are determined

during goods receipt or goods issues.

When we come to material account determination, we'll understand more about account modifications,

single screen versus multiple screens.

Now, most of the time it's single screen.

One.

Single screen means.

That by default, when you go to account assignment for account assignment, relevant items, it's always

one cost center, one asset, so on and so forth.

If you want multiple, you go click on this multiple account assignment.

But only in the case of assets.

If you go to assets like assets, this will be multiple.

So it's enabled by default to show multiple assets at the line item level.

If the account assignment category is assets, but for most of the other account assignment categories,

this is set to single.

And of course you can go and change this to multiple or single any time you want.

Just click on this button.

And the rest of the fields like consumption, posting special stock distribution, partial invoice.

These are things that you never change.

So I have never changed it any time during any of my projects, so probably you don't need to change

them either.

And like I said, all account assignment category and item category combinations are not allowed.

Now, by default, the system comes with all valid combinations.

Meaning for standard item category, you can have an asset, you can have sales order, you can have

an internal order or PM order, plant maintenance order.

You can have a cost center and you can have unknown any of these as the account assignment category.

But if you look at limit be item category B, it only allows cost center.

And you Unknown It doesn't allow any other account assignment category.

As part of the standard business processes that SAP delivers.

These are what are being delivered out of the box.

And they are most of the time, almost.

Okay.

90% of the time.

There is no need for you to create your own combination of account assignment category and item category.

But there are some scenarios where you might have to make more entries here.

Things that typically don't happen, in which case you can go to new entries and make your own combination.

Now for that combination.

The business process should work, meaning you can't have weird combinations.

There is a reason why SAP has delivered this as part of the standard delivery.

For example, if you do limit B and say Project P, do you understand the accounting implications of

it?

So you're trying to essentially create a framework order for a project.

Is that possible?

How are the costs accumulated?

How does the grear happen?

If no gr where does the cost go?

These are all the questions that you have to ask yourself and if you are comfortable with everything

that happens behind the scenes, please feel free to go make new entries here and make that possible.

If not, then don't even bother making entries here.

Okay.

To summarize.

There are so many different controls behind account assignment categories, and the most important point

you have to understand is controls in an item category supersedes the control in an account assignment

category.

And the screen layout of the account assignment is controlled by the account assignment category.

Number three.

There are a set possible combinations of account assignment category and item category.

So SAP delivers most scenarios right out of the box.

But if there is a need, which there will be in most projects, at least 1 or 2 scenarios.

If there is a need to create your own combinations of item category and account assignment category,

please feel free to add more entries, but make sure that you thoroughly test that business process

because the impact of adding an account assignment category.

Something that has not been delivered to an item category is large, meaning you have to understand

the accounting impact.

You have to understand the impact.

Once you have thoroughly tested all of that, then feel free to deliver the solution to the customer.