# UnityRefTextFiles
Just some txt files with tips, defs, Guides, and how to use Common Scripting APIs for Unity 2022


In this Repo you will find a handful of txt files written in Notepad++ that have quick tips and guides for Unity API's
this will be updated from time to time as I get around to making it, but I will provide Sudo code as well as actual code 
with a breakdown of what im doing, and what it does. a quick example below (pullled from one of the files)

---------------------------------------------------------------------------------------------------------

   transform.position = new Vector3(0, 0, 0);
(BREAKDOWN)
transform(using the transform of the object)
.position(saying were used the Position of the object
= New Vector3(Inside here we will set 3 vector points, this will be formatted as (X, Y, Z))
SUDO CODE
So we are taking the Transform Position and assigning it to a new vector3 location of 0 on the x axis, 0 on the Y and 0 on the Z
this will center our Object on on the screen.

using a Vector2(common in 2d games but can be used in 3d)
is only using X, and Y and not using Z

so the example in this case, Vector2(0, 2);  would be moving the object up 2 units

a lot of times this will involve a Time.deltaTime function as well.

---------------------------------------------------------------------------------------------------------

If this is of interest to you OR you wish to add more to the files, feel free to submit your ideas!

I hope this helps anyone who finds it!
