 
Now we're going to talk about item category W.

W for material group when you don't know what quantity you're going to order and what value you're going

to order, that's when you use material group item category.

So the way you're going to typically use it is you're going to create a value contract.

Right.

And basically, you know, you use material groups when you get discounts, you know.

You promised the vendor that you're going to order in bulk, say 50,000, $100,000 worth of whatever

coffee group.

Right.

And the vendor says that I'm going to give you a 30% discount on all coffee.

Right.

So you create a value contract, specify a discount at the header level.

Now when you create.

A release order.

You don't have to specify a material in the value contract.

You can specify the material here, say material one coffee, beans or whatever.

And because there is a value contract discount of 30%.

That discount comes down to the release order, right?

And you can get the discount that the vendor gives you.

It does not come from the info record, nor does it come from any other condition.

It comes from the previously created value contract.

So when do you use material group?

Use this to create a contract where you don't know what kind of material you're going to use, but instead

you know the material group.

So you specify the material group and specify the terms like payment terms, incoterms percentages,

prices, so on.

And then you create the release order.

That's when you enter the materials.

Oh, I want $10,000 worth of coffee.

And I want to apply this discount that we have negotiated yesterday.

Okay.

Refer to that value contract, create a release order and you get the discount.

Okay, let's see that in action.

You go back.

And go create a contract.

Vendor 4001 and it's going to be a value contract.

W k.

Purchase.

Org US zero one.

Purchase group 300 100.

Doesn't matter.

Company code is US oh one.

Yes.

And the validity is for say, two months or one month and the value is 100,000.

Here you don't specify the material.

You could just say item category W, right?

And then put short text there.

Coffee, right.

All kinds of coffee material.

Group coffee.

Right.

And that's it.

You can specify the terms there.

Like if you go to the header, you can specify that I am going to give you better terms like net 30

instead of net 30.

Right.

Go for net 60, which gives us better payment terms and.

Go to pricing and specify a discount of, say, 30%.

Right now.

Save it.

So value contract so-and-so created.

I'm going to copy that number.

Now I'm going to create a purchase order and refer to that contract.

So go to the contract.

Put the contract number in there.

Where's that contract number?

This is our contract number.

Right now, drag and drop that contract.

And over here, you mentioned that specific material.

It's going to be coffee beans.

Oh one.

Uh, I want £100 worth of coffee or $100 worth of coffee either way.

Now, if you go to the conditions, do you see the 30% discount there?

Where did you get it from?

You got it from the contract that you've already negotiated.

And in the contract you did not specify a material, although you could have.

You're saying that for all coffee, I could be any kind of coffee.

Identified by material group coffee.

I'm negotiating a flat 30% discount.

Good.

And any time you're creating a release order with reference to that contract.

The 30% discount applies or any other terms.

Like payment terms.

Right.

You see, typically the payment terms with this vendor, 4001 is net 30.

But because the terms are coming from the contract that has been previously negotiated, the payment

terms now is net 60.

And what's the item category in the contract?

W Here you could have a blank or any other item category you want that's allowed.

Let's go back and look at the item Category W material group.

Can you enter a material?

You don't know the material, right?

So material cannot be entered.

Account assignment.

That is possible.

You can use a count assignment like a cost center.

You can create a contract against a cost center account assignment.

That's possible.

Can you do inventory management?

Yes, you can do inventory management.

You can negotiate a contract for £100 of coffee or coffee group.

Whereby that an inventory relevant material.

So inventory is possible.

You can also negotiate a contract for a service whereby inventory management is not possible.

So that's why it says it is possible.

It's neither mandatory nor is it not allowed.

Then goods, receipt and invoice receipt are linked to the purchase order and that's how the material

group item category works.