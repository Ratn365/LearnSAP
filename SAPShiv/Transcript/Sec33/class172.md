 
So what is the transaction to create the vendor master?

Go to logistics.

Material management purchasing, then master data.

Then vendor.

So these are the different views that we were talking about purchasing view and then general view and

then finance view.

The finance view is not in the purchasing section or in the material management section.

The finance view will be here.

The accounting.

Financial accounting.

Accounts payable because this is us company paying the vendor.

Right.

Go to accounts payable and then master records create.

And these are the transactions to create vendors.

So if you go here, the transaction to create both the general and the finance views is MK01 to create

zero two to change and zero three to display the transaction to create the finance and general views

is f k.

Zero one.

Think of finance.

Miss Material Master.

And if you want to create all the three views together.

You use XK01.

Now, why so many different transactions?

Because like we have discussed, it's not just the material management team that has a stake in the

vendor master.

The finance team also has a stake.

For example, we don't know the account details or payment details or tax details, so we will not be

able to plug the data in to the vendor master.

So who knows about that?

The finance consultant knows.

Or the finance user knows.

So they will be using this transaction and we will be using this transaction.

Now.

What about Xk zero one?

Where do you need that?

So in smaller companies, these roles might crisscross.

The finance consultant might be the procurement consultant, or the finance user might also be responsible

for maintaining the procurement data.

In such cases you can use the central transaction ZK zero one and create the entire vendor master in

one go.

Right.

So let's go create them.

All right.

So we're going to go back to Materiel Master Logistics.

Purchasing.

Master data.

Render.

And then when you go to Central, this is where you can create the entire render master.

If you go to purchasing, you create only the purchasing views and of course, the general view.

You know, you can't just create a purchasing view without the general view.

All right, So, so let's go create the central view.

ZQ zero one and then.

Company code.

Well, we know our company code US zero one.

We know our purchasing org, US zero one.

And then what about the accounting group or account group?

Like I said, this plays a similar role to a material type.

A material type like first finished goods.

How are trading goods?

Raw material.

Dictates what are the views it has?

What are the different pieces of data it has or it should have?

Right.

The vendor account group also plays a similar role.

What?

We're going to discuss that in detail in the next chapter.

So for now, I'm going to choose 0001, right?

If you hit enter it says Account group uses external number assignment.

Okay.

That means it uses a number range that has an external number assignment.

Like I'm just going to choose some number.

Enter looks like it falls within range.

And then we have ABC Foods.

Right.

And where is he located?

1000.

To Michigan Avenue and.

City.

Chicago.

Country.

U.S Region.

Illinois.

And then you could mention the phone number, fax number.

So on.

After that, you can hit enter or click on the Green Arrow mark and then you can maintain the tax data.

If you remember our discussion on the general section, we said there is address and then there is control

data.

This is what I mean by control data.

Like which corporate group they belong to.

What are their tax numbers?

What is their fiscal address?

What is their tax jurisdiction code.

What registration number?

Which industry code do they belong to?

We are trying to categorize that vendor into so many different criteria and then put some important

trade information.

Right.

You don't need to be worried too much about all this stuff.

I can just leave it for now.

Okay.

And then we can also put payment details like the bank details using which bank should we pay this vendor?

What is the bank account?

What is the bank key?

What is the account holder's name?

So on and so forth.

And then that about finishes the general data and then we are moving on to the accounting information.

The primary field in accounting information is the recon account.

Okay, so what is a recon account?

Again, this is something that we'll have to worry about when we talk about MFI integration.

One area is obviously where the material account postings are determined and configured.

Another area is vendor postings where a recon account and other trade accounts are used.

For now, just go and select a PayPal account.

See, I'm selecting a payable account.

These are accounts, general ledger accounts that are specifically designed for payables.

Right.

For now, just select a payable account and then some cash management group because that's a mandatory

field.

Otherwise I wouldn't be even bothered about it.

And then the rest of the data is all finance data.

Don't care.

All right.

And then payment terms.

Remember, we are talking about payment terms in the finance view of the vendor master.

There's going to be another payment terms in the purchasing view of the vendor master.

For now, let's just select.

003.

15 days and then hit enter.

Dunning procedure.

All of this is finance data.

Okay, enter.

Now this is purchasing data.

Again, you see the terms of payment, right?

Over here, we can select some other terms of payment.

So why does SAP have two terms of payment, one in finance and one in purchasing?

The reason is there is a general payment terms in finance.

Or with each purchasing organization, you could have a different set of payment terms.

Example.

In the US, if you have two different purchase orders, one for West and one for East.

The same vendor could have one default set of payment terms in the company code level.

And another set of payment terms for the western region or Western purchaser.

So this is the flexibility that SAP is providing us for the vendor to have a different payment terms

at the purchase order level.

Other currency USD because we are in the US.

And then there is incoterms.

We have discussed in terms already in the vendor master.

So cash on delivery until the plant or warehouse, minimum order value.

This is all purchasing data, right?

The title should say it.

What's the minimum order value?

Say 5000.

And then there's so much of other purchasing data like GR based invoice verification, ABC indicator,

service based invoice verification, subsequent settlement.

Automatic PO.

We have discussed some of these things, but not all of them.

We are not going to discuss all of these parameters anyway.

And then keep going.

These are the partner functions.

So in this case, he's just a vendor.

You could have more partner functions here, but I'm not going to talk about that yet.

Then are we done?

Yes.

Save it.

Vendor number one, two, one, two, one has been created for this company called this purchase.

Org.