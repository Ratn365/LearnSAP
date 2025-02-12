 

So let's summarize what we have learned.

First thing is we have seen what's master data and what are the important pieces of master data in them.

They are vendor.

Material purchase info record.

Next thing is we have seen how to create materials with transaction code is zero one to create zero

two and zero three to change and display.

We have seen what material types are.

We have seen 4 or 5 different material types.

For it for finished goods.

However, for trading goods.

Halbe for semi-finished goods.

Right.

So on and so forth.

We have seen 4 or 5 different material types and what a material type determines and which material

type to use for what possible situation.

So we have seen that SAP is a multilingual system, meaning, for example, we can specify the description

of that material in different languages.

So this is what flower means in German.

And we can specify that here in different languages, depending on the login language of the user,

SAP will show them the corresponding descriptions.

And when you print the POS, it prints in the corresponding language.

And we have seen how to create vendors.

Vendors have three different views.

Unlike materials which have so many different views.

Vendors just have general.

Finance and purchasing views, and we have seen that we can create general and finance view together

using.

Zero one.

And if you want to create general and purchasing view together, you can use.

The MQ zero one.

And if you want to create all these views together, you can use.

Zero one.

Now, why do we need to have so many different transactions and why do we need to separate the views?

The reason is simple.

The reason is simple.

Companies have departments, and when a vendor is being created, the finance department creates the

finance view.

The purchasing department creates the purchasing view.

They don't want to crisscross.

So that's why we have so many different transactions.

And if somebody wants to create all the views together, they can do X01.

Then we have seen payment terms.

What's a payment term?

Payment term dictates how we need to pay back an invoice that we received from the vendor.

We have seen examples of payment terms like 0001.

20002, for example, is net 30.

And then we have seen that apart from the number of days, we can also specify cash discount and we

have seen Incoterms.

What's an Incoterm?

An Incoterms specifies an industry standard term that's used to understand how a vendor needs to supply

goods in terms of logistics.

So standard examples of incoterms are cash on delivery, free on board, and then Incoterms is also

going to have two parts.

Part one is the standard key and part two is a free form text.

So cash on delivery.

Until the warehouse.

Or until the dock.

Free on board.

Until where?

Until the dock.

And from that point on, it's the duty of the customer.

We have seen different units of measures.

Standard unit of measures are already defined in SAP.

And if you want to have your custom unit of measures like like a carton of beer, ten bottles.

Right.

And we have also seen the source of data in the.

Data from the header comes from the vendor.

Data in the line items comes from the material master header.

Line items.

Header.

Comes from the vendor line items.

Comes from the material and we have seen the order of precedence in the meaning.

If a particular piece of data comes from two different sources, you know how to check which one takes

precedence.

Just maintain the data and create transaction and check where the data comes from.

We've also seen what are texts.

Texts or little pieces of information that can be tagged to the master data and that flows through to

the transaction when you create them for that particular set of master data.

So if you want to tag a material with a certain text, whenever you create a purchase order, that text

flows through to the purchase order.