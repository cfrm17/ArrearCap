# Arrear Cap

A vanilla IR cap/floor consists of a portfolio of conventional IR caplets/floorlets. A conventional IR caplet is a vanilla call option on a specified forward index rate with the option payoff paid at the end of the index period. Let f be an underlying forward index rate of the conventional caplet and [tis, tie] be the corresponding accrual period of the index rate, where tis < tie. Usually, tie −tis is 3-month. Let tf _ tis be a reset time of the forward rate. 

The value of a vanilla cap/floor is the sum of values of corresponding caplets/floorlets. The value of a conventional caplet/floorlet can be given by the well-known conventional Black’s formula1. Let v be the value of the conventional caplet/floorlet. Then we may re-write the matured payoffs of the conventional caplet/floorlet.

Let P(·, tie) be the price process of a zero coupon bond which is matured at tie. We choose this bond as a numeraire. Under the corresponding numeraire measure, the forward rate process f(·) is a martingale 

The equation is the well-known Black’s formula for vanilla call and put options. From the equation, one may also calculate the volatility, which is called Black’s implied volatility, such that a market value is perfectly matched. It may be noticed that there is no further restriction on the reset time ft other than that it must be prior or equal to tis.

If the payoff of a caplet/floorlet is not paid at the end of underlying index period, it then belongs to the category of unconventional caplets/floorlets. A non-vanilla IR cap/floor is composed of a portfolio of unconventional IR caplets/floorlets. As before, it suffices to price an unconventional caplet/floorlet. However, the conventional Black’s formula may not be directly applied to price the unconventional caplet/floorlet. A so-called convexity adjustment is needed under an arbitrage-free approach. 

Under the same numeraire measure and the assumption of the dynamics of the forward rate, the initial value of the unconventional caplet/floorlet can be expressed. Without a model assumption of P(tf , tp)/P(tf , tie), we may not be able to calculate the expectation. A special unconventional caplet/floorlet, which is called set-in-advance (or set-in-arrear), is defined as follows. The payoff of the set-in-advance caplet is paid at tis —the beginning of the index period, i.e., tp = tis.

References:

https://finpricing.com/lib/EqRainbow.html

https://zenodo.org/record/6551437/files/ArrearCap.pdf

https://zenodo.org/record/6551437#.YpDwOKgpDq4
