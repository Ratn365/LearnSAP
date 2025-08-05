 
So let's summarize what we have learned about the vendor master.

We started out with the overall structure of the vendor master.

We said there are three views on the vendor master.

General view.

Purchasing View.

Financing View.

And we have discussed the transaction codes for each of the views and the different grouping of fields

in each of the views.

So what the general view contains, what the purchasing view contains and what the finance view contains.

And then we've also seen the importance of each of the views.

What is the meaning of incoterms?

What is the meaning of payment terms?

So on and so forth.

And then we have created vendor masters in the system and seeing how to open vendor masters, how to

select different views in the vendor masters, how these views are grouped together into three different

sections.

And then we have seen how to do mass maintenance.

We have seen how to do deletion of the vendor master.

We have seen how to block vendor master.

We have seen how we can use extras admin data to view who has created the vendor master and we have

also seen how to track material changes.

What is tracking material changes.

Who has done.

What changed to the vendor master?

At what point in time?

From what to what?

This is called tracking the changes in the vendor master.

And we have also seen that any master data changes are only propagated to the transactional data.

From that point onwards.

Meaning if you change the master data field now, it won't affect the already existing purchase orders

or already existing transactions.

Master data changes propagate.

To the transaction only after the changes have happened.

And we have seen why you should not delete master data because you lose the reference.

So all you can do is flag the data for deletion.

We have seen how to do it.

And we've talked a little bit about archiving.

Then we have talked about the most important piece of configuration in vendor master called the account

group or the vendor account group.

We have seen that SAP provides so many templates out of the box.

Regular vendor.

One time vendor, logistics provider.

Shipment provider.

Special vendor.

These are all templates called vendor account groups.

And we were able to create our own template 001 or Z 100.

And then customize it the way we want it.

And then we talked a bit about number ranges.

Number range is assigned to a vendor account group.

After that, we have talked about a special topic called vendor Subranges.

What is a vendor?

Subrange.

Why do we need to use vendor Subrange.

How to create Vendor Subranges.

How to associate a vendor subrange to an info record.

And we have also seen examples of transactions where the data either flows from the standard vendor

master.

Or it flows down from the Subrange specific vendor master.

That's all dependent on the info record that contains the vendor Subrange key field.

This triggers the data either be fetched from the standard vendor master or from the vendor Subrange

specific data.

And then we talked about one time vendor.

And we have created a one time vendor in the system, created some transactions using the one time vendor,

and have seen how that kind of transaction is different from the way we create a transaction with a

regular vendor.

And finally, we have seen how to enable field groups at purchase org specific level.

You can also do it at a transaction specific level.

But I said not to use it.

It's not recommended by ACP, but that option is available.

And we have seen why you might want to use this.

We have talked about scenarios like India and us and how we might want to enable or suppress certain

fields at the purchase org specific level without having to have to use different account groups in

each purchase order.