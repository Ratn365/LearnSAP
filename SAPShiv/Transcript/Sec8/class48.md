 

Lecture thumbnail
48. Texts
Transcript
Let's talk a little bit about texts.

And before we go to texts, since we have just finished materials, vendors and info records.

I want to use the sheet.

So these are the list of materials.

Think of this as an extension to the previous exercises.

So I want you to create all these materials.

Create all these vendors.

Then set the info records like this vendor is going to take ten days to supply the goods and he's going

to supply it at $5 per pound or per kilo.

Then you can put a comment there.

Now think of comments like this Stirrers for Chicago Brewing Supply Company.

You want to put a comment saying it should be of brown color and should have a crown.

Or if you take coffee bags.

If you want to get them from this vendor.

You want to put a comment over there saying that it should be a £1 aluminum bag, only say as opposed

to jute bags or paper bags.

That's how you want to brand your stuff as.

Where do you specify these comments?

There are a number of places that you can specify these comments.

A simple way to specify comments is the material master.

Comment is basically a text.

So if you go to the material master.

Go to M02, which is changing the material.

Go to coffee beans, Hit.

Enter.

And select purchase order text.

And of course, enter your plant K-1.

You could put a text here.

And these coffee beans you want them supplied in.

Aluminum bags only.

You have just tagged this material with the little text node and click save.

Go here and create another order.

A mi 21 n.

And Vendor 4001.

So when you create a purchase order for this vendor.

And coffee beans for $10 since you specified that little note in the coffee beans.

You should see that as a text.

Here.

In the text tab, you see material text and it says Aluminum bags.

I didn't enter it manually here because we have entered that in the material master purchasing text

view.

It automatically defaults to this tab and it defaults to a particular kind of text.

You call the material text.

And what good is this if it doesn't reach the vendor with that particular with that particular thing

printed on the paper or PDF?

So let's go to a print preview.

So do you see that here?

Aluminum bags.

So what did we just do?

We went to the material master.

Put a little instruction, which is basically tagging the material with a particular text.

And we have seen that when we create a purchase order for that material, the text automatically flows

in.

And when you print it, it gets printed on the PEO that reaches the vendor.

So the vendor knows that he has to supply it in aluminum bags.

So this is a little additional piece of information that you want to supply to the vendor when he reads

the PEO.

All right.

So let's summarize what we have learned.

So first thing is we have seen what's master data.

And what are the important pieces of master data in them?

They are vendor material.

Purchase info record.

Next thing is we have seen how to create materials with transaction code is zero one to create zero

two and zero three to change and display.

We have seen what material types are.

We have seen 4 or 5 different material types.

For it for finished goods.

However, for trading goods.

Halbe for semi-finished goods.

Right.

So on and so forth.

We have seen 4 or 5 different material types.

And what a material type determines and why, which material type to use for what possible situation.

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

Finance and purchasing views.

We have seen that you can create general and purchasing view or general and financing view differently.

And we have seen that we can create general and finance view together using.

F01.

And if you want to create general and purchasing view together, you can use.

The MQ zero one.

And if you want to create all these views together, you can use.

Zdk zero one.

Now, why do we need to have so many different transactions and why do we need to separate the views?

The reason is simple the companies have departments, and when a vendor is being created, the finance

department creates the finance view, the purchasing department creates the purchasing view.

They don't want to crisscross.

So that's why we have so many different transactions.

And if somebody wants to create all the views together.

They can do X01.

Then we have seen payment terms.

What's a payment term?

Payment term dictates how we need to pay back an invoice that we received from the vendor.

We have seen examples of payment terms like 0001.

20002, for example, is net 30.

And then we have seen that apart from the number of days.

We can also specify cash discount.

And we have seen Incoterms.

What's an Incoterms?

An Incoterms specifies an industry standard term that's used to understand.

How a vendor needs to supply goods in terms of logistics.

So standard examples of incoterms are cash on delivery, free on board.

And then Incoterms is also going to have two parts.

Part one is the standard key and part two is a free form text.

Cash on delivery.

Until the warehouse.

Or until the dock.

Free on board.

Until where?

Until the dock.

And from that point on, it's the duty of the customer.

We have seen different units of measures.

Standard unit of measures are already defined in SAP.

And if you want to have your custom unit of measures like a carton of beer, ten bottles, right?

And we have also seen the source of data in the.

Data from the header comes from the vendor.

Data in the line items comes from the material master.

Header.

Line items.

Header.

Comes from the vendor.

Line items.

Comes from the material.

And we have seen the order of precedence in the meaning.

If a particular piece of data comes from two different sources, you know how to check which one takes

precedence.

Just maintain the data and create transaction and check where the data comes from.

We've also seen what are texts.

Texts are little pieces of data.

That can be tagged to master data.

And that flows through to the transaction when you create them for that particular set of master data.

So if you want to tag a material with a certain text, whenever you create a purchase order, that text

flows through to the purchase order line item.