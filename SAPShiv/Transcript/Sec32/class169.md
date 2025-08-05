 

Lecture thumbnail
4:33 / 4:36
All right.

We have come to the very end of the material Master.

We just got one more topic, and that topic is.

Material master.

Number format.

Now we know for the material master, the maximum length is 18.

You can't go beyond 18.

In the new SAP s four Hana system.

This has been extended to 40 characters, but in the SEC system, the length maximum length is 18.

The word customization can you do here?

If you go to the output format for material numbers in basic settings, you can see that there are 1

or 2 customizations that you can do.

The major customization is the use of material number template.

Now Material Master is 18 characters, right?

So it's 18 boxes like that.

Each is one character.

Sometimes material numbers need to be created in a certain fashion.

For example, if you have so many different materials, you can say, This is F.

F for food, put a dash.

And then.

Something like that.

You want to force the material creation to be in a certain format.

For example, supermarket, you classify it as food, beverages, clothing, stationery, pharmacy,

something like that.

And anything that's food is F dash for characters.

01240124.

Could be bread, right?

You can do that using a template.

Not just that you can have something like 0124, not F-012, four and then show it in the system as

F dash.

When you go to zero three, you could create it as 0124, but show it in the system as f dash.

Now to do all of this stuff, you have to create what is called as a template.

And on top of that, you can also do programming to allocate or prefix it with certain numbers.

Now, some companies need this kind of stuff.

Not all companies do, but some companies need this kind of stuff.

They want to prefix their material with something or suffix their material with something.

In cases like that, you can program your material master template in such a way that you can prefix

the material with something or suffix the material with something, or format it in a certain way.

There are specific customer or user exits for the material master and go to help Sap.com and then you

can find the material master exits.

Just go to Google and type in material master customization, customer exits and you have two of them.

And then how to program it is not in our domain.

It's basically the domain of the Abap consultant.

You provide the requirements and he'll be able to do that for you.

The next thing is leading zeros.

What is leading zeros?

If you switch this off.

Okay, Save it.

Okay.

Go back now.

You see that these are the leading zeros.

It's not on by default, but you can enable it.

I didn't put these zeros is automatically put it if I go to zero one.

And then enter basic data.

Now it does not have the leading zeros.

Why do you want to have this leading zeros?

Sometimes SAP interacts with external systems.

External sales systems, external purchasing systems, external CRM systems, and they need the number

range to be a fixed number of digits or alphabets, ten characters, 18 characters.

So on.

In cases like that, you can prefix the material with zeros.

That way, any external system always sees your material with a certain number of characters.

Always.

That's when you use leading zeros.

That about concludes the material Master.