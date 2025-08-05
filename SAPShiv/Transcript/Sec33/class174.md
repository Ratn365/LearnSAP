 
What do we have next?

Flagging for deletion.

It can block master data, either vendor, master or material master.

Why do you want to flag it for deletion?

Flag.

For.

Deletion.

There is an important rule that you have to understand.

The rule is you cannot delete master data.

That's point number one.

You cannot delete.

Master data with vendor customer material asset.

You cannot delete any of them.

You can only.

Plug.

For a deletion.

So what does the flag for deletion do?

If you flag a vendor as deleted, meaning you don't need that vendor anymore.

So all transactions for that vendor are blocked.

Not the old transactions.

The old transactions can still continue, but new transactions cannot be created.

But why not just block the vendor and not delete them?

The reason is blocking is typically a temporary step.

Until.

You unblock them or delete them.

The reasons could go either way.

You would want to temporarily block a vendor until he is ready and then unblock him for all transactions.

Typically this is done during induction of the vendor.

Now, when you want to purge the vendor from the system, you don't need him anymore.

Then you block him for certain transactions like creation of new purchase orders.

Finish all the existing transactions.

And then delete that vendor or flag the vendor for deletion.

Right.

Now, another important point you have to understand here.

Is.

Why is it that you cannot delete master data?

The reason is.

Linked this slide.

You see, this purchase order refers to this material or this vendor, right?

So if this vendor is deleted.

And that reference is important for the purchase order to appear properly on your system.

Right.

The purchase order refers to vendor 1000 and the 1000 vendor is not there in the system at all.

Then you know the purchase orders transaction would not know what to do or how to show that vendor.

What's the name, what's the description, Right.

So it leads to issues with referential constraints.

So transaction is referring to a master data, so you cannot delete master data.

Is there a solution?

Well, the solution is complicated, but there is a solution.

If you really want to delete it out of the system.

There is something called as archiving.

And this is typically done as a special project.

You can go check Dice or Naukri and you will see that there is archiving roles, specific archiving

roles, archiving consultants needed.

And there is a specific sequence in which archiving has to be done.

And that's a special process.

And what is archiving?

Basically, you purge.

Both the master data.

And the corresponding transaction data.

Remember, the key is the corresponding word corresponding master data and transaction data.

You are purging them and archiving them.

And when they are being archived, they go off of the running system into a disk drive somewhere.

You can still access them, but not in the same way that you access the typical transactions.

A typical transaction can be accessed using, say, for example, if it's a purchase order, you can

access it using M 21 N or M 23 n.

But if it is purged.

That master data or transaction data cannot be accessed using the regular transaction M23.

N.

It has to be accessed in a different way and the functionality is not as full blown as the regular transaction.

And why do you archive things?

Remember SAP.

For a company could be running for 20 years.

I have seen SAP run in a company for 15 years.

That's the most I have seen.

And then it could accumulate so much of junk during all those 20 years.

Right?

The line of business could change.

The vendors materials could change their entire direction would have changed.

And they don't want to carry all that baggage.

If it is 2016.

And, you know, they have accumulated some vendors or materials that are totally unnecessary because

they are not in line with the current business that they are doing.

And it's not necessary in the database.

Unnecessary.

Purge them or archive them.

Unless this is the case, typically you don't archive.

Because the database is pretty huge.

And with the current Hana systems, there is really no need for archiving.

It's all there and it's very fast.

And typically archiving is not done for the purposes of volume or the system is becomes so big.

We need to archive some data or push some data off of the mainstream.

That used to be the case when databases were small.

But nowadays there is no reason why archiving or purging could be done.

Need to be done rather.

Because of volume.

If the data doesn't make any sense in the current scenario, then you take it off the system because

it confuses you with the analysis and all that.

Right.

So that is flagging for deletion.

And then I want to talk about another important piece of functionality in master data called mass maintenance.

This is available again for Customer master.

Material.

Master Vendor.

Master.

All different kinds of master data.

What is mass maintenance?

Let us say there are 10,000 vendors.

Okay.

And either for all of them or for a specific subset, say, 1000 vendors.

You want to change a piece of data?

What piece of data?

For vendor master.

Let's say you have negotiated with 1000 vendors that the payment terms are order.

Currency is going to be so and so.

Let's say the order currency is USD for all these thousand vendors, right?

How do you do that change?

You got to go to Mk0 two or ZK zero to open all the vendors and then say, oh, it's whatever the currency

is, change it to USD.

You could do that.

It requires you to go open each of the vendors 1000 times instead.

You could go to mass maintenance, right?

Select that field.

There is that field.

It's in the purchasing data.

Feels.

First you select the group The View, and then you go to the field.

Where is that field?

Let's try to do a search.

Payment.

See is a payment term here.

Oh, there is a payment method.

Let's see if there is a payment term.

Yeah, there you go.

Payment terms.

Right.

So you have selected vendor and then payment term.

She executed.

Just ignore that warning.

Here you restrict the dataset.

You don't have to restrict it if you want to change it for all the data records.

But if you only want to change it for, let's say, a set of vendors, if you have that chosen list

of vendors in Excel, you could go there and paste all of them there like 1000.

You know, 2000, 3000, so on and so forth.

Right.

Change that and for what purchase?

Org you want to change the data for?

You want to change the data for all purchase orders?

Leave this blank.

You want to change that for a specific purchase.

Org you can go put your purchase org.

Now you can't combine specific combinations of vendors and purchase orders like for these vendors,

this purchase for these vendors, this purchase order.

In cases like that, you have to do this transaction twice or thrice.

But still it's a very useful transaction because for all these vendors, thousand of them that you put

in this list.

And for any purchase or combination that you specified.

You execute it?

Say.

Vendor 1003.

Click execute.

And then this vendor 1003 has these payment terms, right?

Now, you want to change that to what?

What is the new value, say, 0001.

Right.

And then don't just save it.

Now use this button, carry out mass change.

So click on the mass change button.

And unless you do that, that change will not happen.

So all these master records have been changed.

Now click save, right?

So it's doing the changes.

And it says some field has to be filled up.

So it looks like that vendor 1003 has not been created properly.

So go back to.

MG zero two.

1003.

Purchaser.

Zero one.

So it's not created for this purchase org.

It's created for, let's say, 1000.

I don't know.

Then enter.

We need the purchasing data, right?

Like.

Some fields are not created here properly.

So it's saying I can't change it.

Uh, which field is that?

Or let's do a similar change, right?

Like MK zero two and select Vendor 4001.

Right purchaser gives zero one.

And what do we want to change?

We want to change, say the search term from ABC supply company ABC to, you know, X, Y, Z.

Right.

Let's do that.

Mass maintenance LFA one.

General section.

Right.

Then select.

The search term.

Okay.

Click Enter Vendor 4001.

Now you see, it's not asking for the purchasing data here because we selected the general view.

Click.

Okay.

And from ABC you could have any number of vendors selected there.

Right.

X, Y, Z.

And do click on that button.

Now click on Save.

It's going to do the change changes have been made, right?

This is not just for one vendor.

Remember, you could have done it for 1000 vendors.

Now, if you go to display of that vendor, 4001.

See that X, Y, z.

We have done that change using mass change.

And that could have been done not just for one vendor for n number of vendors.

So that is mass change.

Right.

That about concludes the basic features of the vendor master.

Now, in the next chapter we're going to move on to account group.