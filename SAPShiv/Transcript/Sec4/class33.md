 
 created the basic enterprise structure, let's perform some transactions using the

enterprise structure that you've just created.

So try and see if you can order some flour for the newly created plant.

How do you do that?

So you go back.

All the way to easy access Menu.

Go to logistics material management, purchasing.

Purchase order.

Create.

Drag it to your favorites.

Double click it.

So you want to try and do it for.

Render whatever, then you want to use us zero one and purchase group whatever doesn't matter.

And company code.

Us zero one.

So what does it say?

So.

Vendor One, two, two, two has not been created for purchase of US zero one.

So what is this error message mean?

So master data like vendor, master or material master always need to be created for the particular

enterprise structure that you create in the transaction.

For now, don't worry about the word master data.

In the next set of videos, we're going to learn about Master Data Vendor Master Material Master.

For now, let's just simply create a vendor.

So we want to create a vendor ABC Supply company.

And how do you create a vendor under purchasing master data?

Vendor.

Central.

Create.

And if you look at these transactions, you'll see a common pattern.

There is A01 for create 0 to 2 change and zero three to display.

And in fact, that's the common pattern that you see across most of the easy access transactions.

Now when I mean easy access.

So it's the huge menu pad that you see as soon as you log in as opposed to Sbarro.

So Sbarro is also a huge list of menu that's completely in a different transaction called Sbarro.

But easy access is what you see as soon as you log in, let's do it in SCP.

Go back.

You want to save it?

No.

So under purchasing, go to master data.

Vendor.

Purchasing or central go to create.

Now we don't want to create everything from scratch.

Again, instead let's copy the same vendor.

One, two, two, two.

And just change the name.

So company code.

Us zero one purchase.

Org US zero one account.

Group 0001 Just use it for now and the reference vendor is 1222 company code 3000.

Purchase.

Org 3000.

Hit enter.

It says account group 0001 uses external number assignment.

What does this error mean?

There's something called as number ranges.

What's a number Range?

A number range represents a range of numbers that can be assigned to an object.

In this case, vendor.

We're going to explore more on number ranges later, but for now, it's asking you to assign a number

to it.

So just say 4001 or 4000, 2 or 5001, any unique number.

So I'm going to put in 4001.

Hit enter again and then give the vendor name.

A, B.

C supply company.

And.

And just give it a search term.

We're going to put it some address like.

Thousand.

Dennis Drive.

Chicago.

Chicago.

US.

Illinois.

As soon as you enter that address, you see this error, communication error with the external tax system.

What does this error mean?

This only happens when you pick a US address.

If you pick a Japanese address or a German address, you don't get that problem.

Why do you get that?

Let's talk a brief bit about what is a jurisdiction code?

Jurisdiction code for our purpose basically is something that's used in the US for tax.

If you take the map of America.

There are different states, right?

And then Illinois is right here.

And in Illinois there are so many counties and districts.

So the easiest thing to understand is jurisdiction code is if you pass along one of the interstates.

You'll see that the price of the gas really varies across each of the gas stations.

Why?

Because the tags in each of the jurisdiction codes could be different.

And jurisdiction code basically is a combination of state.

Plus county.

Plus city.

Plus district.

So district is not used for the most part.

It's mostly state, county and city.

So based on the combination of state, county and city, the state levy attacks, the county levies

attacks the city levies attacks.

For example, in a particular Illinois county, the state, Illinois levies a 5% tax.

One of the counties levies a 3% tax and the city could levy a 1% tax.

So overall, it's 9% of sales tax.

This is sales tax.

Overall, 9% in tax.

And if you move right across to the next county, the price could be different for the same gas.

And because there are so many different jurisdictions, there are different ways in which these jurisdiction

codes are automatically computed in SAP based on the address you entered.

And that can happen when there is an external system providing the jurisdiction code based on the address

entered.

And that's why you see an external tax system communication failed error.

Now we don't need to bother about jurisdiction codes in a test system, right?

So what do you do?

You go to Sbarro or the transaction OBG and against us.

Change the tax procedure to tax us.

So let's do it.

The transaction is OBG.

Again, Go back.

OBJ select us.

And then instead of tax us just put in.

Tax us.

Click save.

And then.

You can say change.

Now let's try to create a vendor.

4001.

ABC Supply company.

The search code is ABC.

And some address in Chicago.

Illinois.

Now, you should not see that error.

So let's keep going.

Hit.

Enter.

Hit.

Enter.

Enter.

Enter.

Enter.

Enter.

Enter.

Enter and save.

So you've just created the vendor for 001 as ABC Supply Company.

Now before you go create a purchase order, there is another transaction that you have to set.

It is setting the tax rates.

So go to another transaction f t x p.

Again, this is a finance transaction.

Don't worry about it.

This is where you set the tax rates for input or output.

So select us and then select an input tax.

AP sales tax.

Don't bother about the term input output.

Click.

Okay.

Input tax is basically what you pay.

An output tax is what you basically what you collect.

Then put a tax rate of zero.

And click save.