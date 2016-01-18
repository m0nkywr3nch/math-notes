#Integer exponents
def: for any \(a \in \mathbb{R}\) :

\[
  a \times a \dots a = a^n
\]

We use the shorthand notation \(a^n\) to denote a product of n equal factors where a is called the base and n is called the exponent.
This is valid for any \(n\) such that \(n \in \mathbb{Z}\)

There are two special cases to look more closely:

\[
  a^0 = 1
\]

for all \(a\) where \(a \in \mathbb{Z}\) and \(a \ne 0\).

\[
  0^0 = undefined
\]

##### this needs explanation

##Even powers and negative numbers
Compare the following two examples:

\[
  (-2)^4 = (-2) \times (-2) \times (-2) \times (-2) = 16
\]

with

\[
  -2^4 = -(2^4) = -16
\]

When the minus sign is upfront the expression it supposes to wrap the whole of it. So the placement of minus sign and the grouping matters.


##Operations with exponents

###Multiplication of powers
\[
  3^2 \times 3^5 = (3 \times 3) \times (3 \times 3 \times 3 \times 3 \times 3) = 3^7
\]

So as a general rule when can say that if we multiply two numbers with equal bases we can add the exponents.

\[
  a^m \times a^n = a^{m + n}
\]

###Powers of powers

\[
  (a^m)^n = a^m \times a^m \times \dots a^m = a^{mn}
\]

We multiply \(a^m\) \(n\) times, so we can say that \((a^m)^n = a^{mn}\)

###Power of a product

\[
  (ab)^n = (ab) \times (ab) \times \dots (ab) = a^n \times b^n
\]

We multiply \(a\) \(n\) times and \(b\) \(n\) times.

###Ratios with powers

\[
 \frac{a^m}{a^n} = a^m \times \frac{1}{a^n} = a^m \times a^{-n}
\]

or in other words:

\[
  \frac{a^m}{a^n} = \frac{1}{a^{-m}} \times \frac{1}{a^n} = \frac{1}{a^{n-m}}
\]

###Powers of division

\[
  (\frac{a}{b})^n = \frac{a}{b} \times \frac{a}{b} \dots n = \frac{a^n}{b^n}
\]

###Warnings

first:
\[
  ab^3 \ne (ab)^3
\]

\[
  ab^3 = a \times b \times b \times b
\]

while:

\[
  (ab)^3 = a \times a \times a \times b \times b \times b = a^3 \times b^3
\]

second:

\[
  ab^{-1} \ne (ab)^{-1}
\]

\[
  ab^{-1} = \frac{a}{b}
\]

while:

\[
  (ab)^{-1} = \frac{1}{ab}
\]

third:

\[
  a^3 \times a^4 \ne (a^3)^4
\]

\[
  a^3 \times a^4 = a^7
\]

while:

\[
  (a^3)^4 = a^12
\]

fourth:

\[
  a^{-1} + b^{-1} \ne (a + b)^{-1}
\]

\[
  a^{-1} + b^{-1} = \frac{1}{a} + \frac{1}{b}
\]

while:

\[
  (a + b)^{-1} = \frac{1}{a + b}
\]

##Negative integer exponents
We have look so far which is the meaning of the positive integer exponents and 0, but what about the meaning of a negative integer exponent?, what could mean an expression like:
\[
 a^{-1}
\]

take a look at this expression

\[
  5^{10} \times 5^x = 1
\]

if we follow the rule of how to multiply two numbers with equal bases with exponents
we can say that

\[
  5^{10 + x} = 1
\]

or rewritting \(1\) as \(5^0\)

\[
  5^{10 + x} = 5^0
\]

Now we can take just the exponent part of the equation and solve for x

\[
  10 + x = 0
\]

\[
  x = -10
\]

This is an interesting result because we know that multiply any number by its reciprocal gives us 1
\[
  5^{10} \times \frac{1}{5^{10}} = 1
\]

So we can say that:

\[
  \frac{1}{5^{10}} = 5^{-10}
\]

The expression \(a^{-n}\) can always be rewritten as the reciprocal of \(5^{n}\), thats is \(\frac{1}{a^{n}}\) for all positive integers, \(a\) can't be 0, otherwise we get a division by 0 error.

We have discover a new meaning for the symbol - (bar), it not means subtraction neither negation, it means write me as the reciprocal.

## Powers of 1 and -1

Notice the following:

\[
  (-1)^2 = (-1) \times (-1) = 1
\]

\[
  (-1)^{-2} = -(\frac{1}{1^2}) \times -(\frac{1}{1^2}) = 1
\]

and:

\[
  (-1)^3 = (-1) \times (-1) \times (-1) = -1
\]

\[
  (-1)^{-3} = -(\frac{1}{1^3}) \times -(\frac{1}{1^3}) \times -(\frac{1}{1^3}) = -1
\]

We can extract a general rule from the above examples and say that:

\[
  (-1)^{2n + 1} = -1
\]

and:

\[
  (-1)^{2n} = 1
\]

So (-1) raised to an odd power is always -1, (-1) raised to an even power is always 1.

###Simplify examples

example 1:

\[
  \frac{x^5 - y^{-2}}{x^3 y} = \frac{x^5}{x^3 y y^2} = \frac{x^{5-3}}{y^3} = \frac{x^2}{y^3}
\]

example 2:

\[
  \frac{
    \frac{1}{x^2} - \frac{1}{y^2}
  }{
    \frac{1}{x} + \frac{1}{y}
  }

  =

  \frac{
    \frac{1}{x^2} \frac{y^2}{y^2} - \frac{1}{y^2} \frac{x^2}{x^2}
  }{
    \frac{1}{x} \frac{y}{y} + \frac{1}{y} \frac{x}{x}
  }

  =

  \frac{
    \frac{y^2 - x^2}{x^2 y^2}
  }{
    \frac{y + x}{xy}
  }

  =

  \frac{y^2 - x^2}{x^2 y^2} \frac{xy}{y + x}

  =

  \frac{(y - x)(y + x) xy}{x^2 y^2 (y + x)}

  =

  \frac{y - x}{xy}

\]

#### Tips for Simplify

* be carefull with grouping.
* keep \(\frac{x}{x}\) form instead of \(x/x\) for handwriting.
* always rewrite negative exponents immediately.
