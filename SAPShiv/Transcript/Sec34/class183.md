 
So where do you create the info?

Record logistics, material management, Purchasing master Data Info record?

Let's create a new info record for, say, 4001 material.

Coffee Beans.

Oh.

Or two, let's say, and purchase.

Aug zero one.

Plant Chicago one and we are going to create an info record of type standard.

This might already exist.

That's fine.

So this is the vendor material number.

Okay.

Now what is the use of a vendor material number?

Let me put something here and I'll show you an example.

CB.

CB zero two.

Okay, I'm just putting a text here.

CB zero two and then hitting enter planned delivery time five.

These are all the overrides I'm talking about Channel delivery quantity five and price of $12.

Doesn't matter.

You can put a text here if you want.

Like text.

This is perishable.

Seal tight, right?

And then.

You could have more text like that, right?

Enter.

Save it.

Purchasing info.

Record saved.

Now let's go create a purchase order.

M 21 n.

And standard purchase order with vendor 4001.

All right.

And the material is coffee beans.

Oh two.

Quantity ten in the Chicago plant.

Right.

The price was picked up $12.

How do you know that?

The price was picked up from the material info record?

Because you can go and see that info record here somewhere.

This is the info record that we should have just created.

If not, you can go and verify.

Now go to the material data and you see that CB zero two.

What is this doing here and what is the effect of it?

So we are talking about vendor.

Material.

Number.

What is a vendor material number?

Let me give you an example.

So we go to Walmart or any retail store and Walmart calls milk.

As what if you go look at the bill, right?

Milk might be called MLK.

MLK to PC.

Right.

And it might be called, let's say the brand is denim, right?

The.

MLK Typekit.

That's what Walmart calls milk 2%.

Brand Dannon.

What do you call it?

You don't go and ask for MLK two, right?

You don't do that.

You say I want or you go pick up milk.

But if you are to ask for it, it would be called milk Dannon 2%.

Right.

You don't say MLK two.

Similarly.

For the same material, you might have a different name, you being the ordering party, the buyer and

the seller.

Vendor in this case might call it differently.

Another example.

Think of Apple.

When you go place a pair.

And ask for iPhone you know 64 GB whatever model.

Apple might refer to it as 520132.

A material number.

Right.

So who does the mapping between the way you call that product The same product and between the way the

vendor the supplier calls that product.

If there were a common name, there is no need for that.

But materials could be having different names depending on who the vendor is.

Well, in the case of Apple, I don't need to call it iPhone 64 GB.

I could call it 520132 because Apple is the only supplier of iPhone.

But look at it in the context of the entire market.

Well, if you are buying directly from Apple, you could call it 520132.

Right.

But Apple could be selling this to Best Buy.

Apple could be selling this to Walmart.

Apple could be selling this to somebody else.

And they have their own material, Masters.

They don't need to always qualify.

20132.

They have if they follow an external number range, they'll use some nomenclature.

If they follow internal number range, they can't use Apple's number range.

They will use their own number range.

Now, if you are going to their site and ordering, what do you want to call it?

You want to call it something else?

Right.

You don't know what you want to call.

I'm not talking about a retail scenario here.

I'm talking about a wholesale scenario.

Your company creates a purchase order and sends it to Best Buy, and you are going to create that purchase

order with what material?

You want Apple iPhone 64 GB.

And that's what you're going to create as a material and send in the purchase order.

You don't know what Apple is going to call it.

You don't know what BestBuy is going to call it.

But if you are doing regularly the same business again and again and again.

In cases like that, it's easy if you have the translation with you.

If you are always buying iPhones from Best Buy, that's the preferred vendor and Best Buy calls.

iPhone as 41 0142.

You call it iPhone 64 GB whatever model.

You could specify the mapping between this and what your vendor calls it.

41 0142 in the info record for material iPhone.

Plus vendor.

Best Buy.

This is the info record.

And you're going to call that material as iPhone 64 GB.

That's the material number.

Right with.

Vendor material number as.

41 0142.

This is the vendor.

Material number.

And you are going to map it with what you are going to call it internally, this mapping.

Between your material number, what you call it internally and what the vendor calls it is mapped in.

The info record.

Purchasing Info Record.