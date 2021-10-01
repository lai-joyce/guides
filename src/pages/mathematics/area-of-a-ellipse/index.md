---
title: Area of a Ellipse
---
## Area of a Ellipse

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/mathematics/area-of-a-ellipse/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

#### More Information:
https://www.wikihow.com/Calculate-the-Area-of-an-Ellipse
Area of an ellipse is the product of the 2 radii x pi

Proof: https://proofwiki.org/wiki/Area_of_Ellipse

Let 𝐾 be an ellipse aligned in a cartesian plane in reduced form.


Then from Equation of Ellipse in Reduced Form:

𝑥2𝑎2+𝑦2𝑏2=1
Thus:

𝑦=±𝑏1−𝑥2𝑎2‾‾‾‾‾‾‾√
From the geometric interpretation of the definite integral:

	=				𝑏∫𝑎−𝑎(1−𝑥2𝑎2‾‾‾‾‾‾‾√−(−1−𝑥2𝑎2‾‾‾‾‾‾‾√))d𝑥				
=				𝑏∫𝑎−𝑎21−𝑥2𝑎2‾‾‾‾‾‾‾√d𝑥				
Let 𝑥=𝑎sin𝜃 (note that we can do this because −𝑎≤𝑥≤𝑎).

Thus:

𝜃=arcsin(𝑥𝑎)
and:

d𝑥=𝑎cos𝜃d𝜃
Then:

	=				𝑏∫arcsin(𝑎𝑎)arcsin(−𝑎𝑎)2𝑎1−(𝑎sin𝜃)2𝑎2‾‾‾‾‾‾‾‾‾‾‾‾‾√cos𝜃d𝜃			Integration by Substitution	
=				𝑏∫𝜋2−𝜋22𝑎1−sin2𝜃‾‾‾‾‾‾‾‾‾√cos𝜃d𝜃				
=				𝑏∫𝜋2−𝜋22𝑎cos2𝜃‾‾‾‾‾‾√cos𝜃d𝜃			Sum of Squares of Sine and Cosine	
=				𝑎𝑏∫𝜋2−𝜋22cos2𝜃d𝜃				
=				𝑎𝑏∫𝜋2−𝜋2(1+cos(2𝜃))d𝜃			Double Angle Formula for Cosine: Corollary 1	
=				𝑎𝑏[𝜃+12sin(2𝜃)]𝜋2−𝜋2			Integration of Constant and Primitive of Cosine Function	
=				𝑎𝑏(𝜋2+12sin(2⋅−𝜋2)−−𝜋2−12sin(2⋅𝜋2))				
=				𝑎𝑏(2⋅𝜋2+2⋅12⋅0)				
=				𝜋𝑎𝑏				

