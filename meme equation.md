Javascript for the meme equation can be used here: https://www.desmos.com/calculator

$\frac{1}{\left(\frac{\left(\frac{1}{1+e^{-300000000\left(\frac{P-S}{\sqrt{\left(P-S\right)x^2+300000000}}\right)}}\right)\left(0.0001\right)+\left(\frac{1}{1+e^{-300000000\left(\frac{P-S}{\sqrt{\left(P-S\right)x^2+300000000}}\right)}}\right)\left(P-S\right)^2}{Px^S}\right)^{\frac{\left(P\right)}{S}}+1}$

M(t,S,P) The pattern of the meme saturation over time can be described as a function of the meme strength variable and the population variable. Remember, S & P are constants for the meme and population respectively so for a specific meme interacting with a specific population you would use the term M(t).

How did I arrive at this equation?

The meme equation is a modified Hill equation, because it allows for both a slow, sigmoidal curve as well as a quick-saturating logarithmic function that always has a y-intercept of 0. The population resistance to the meme and the meme's strength itself interact. It's to the P/S power because a high population resistance will push the inflection point further positive down the x-axis and simultaneously reduce the slope of the curve. (P-S)^2 always gives a positive value representing how much larger R is than S. All the stuff to the left of that is basically an if-then statement: If R<S just use an arbitrary small number in place of (R-S)^2. this prevents the function from exhibiting odd behavior when R<S, namely the lowering of meme saturation as S increases. The 3E8 term is merely an arbitrary high number I chose because it's the speed of light (no units are implied though). S*t^S is responsible for M(t) approaching 1 more rapidly if S is high in all cases.

----It's likely that constants will need to be added, at the very least to normalize S and P variables. While this equation can theoretically model any sort of meme spreading pattern, it will need more work, especially after I start collecting data with it.

----Just to reiterate, instead of an increase in the number of people harboring the disease on the y-axis it's the number of people harboring the idea. The number of meme vectors vs time.
