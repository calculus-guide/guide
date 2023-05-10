# Limit Properties

## Properties of Limits

Limit properties are a set of rules and principles that describe how the limit of a function can be calculated or estimated based on the limits of other functions. These properties allow mathematicians to manipulate and simplify expressions involving limits, and to evaluate limits that might otherwise be difficult or impossible to calculate directly.

### Addition Property

The addition property of limits states that if we have two functions, f and g, that are continuous at a point a, then the limit of their sum as x approaches a is equal to the sum of their limits. In other words, 

$$\lim_{x\to a} (f(x)+g(x))=\lim_{x\to a}f(x)+\lim_{x\to a}g(x)$$

This property holds true for all real numbers a, including infinity and negative infinity, as long as the limits in question exist. 

To understand this concept better, consider the following example:

Suppose we want to find the limit of the function h(x) = 3x^2 + 4x - 2 as x approaches 1. We can rewrite h(x) as the sum of two functions: f(x) = 3x^2 and g(x) = 4x - 2. 

Using the addition property of limits, we know that 

$$\lim_{x\to 1} h(x) = \lim_{x\to 1} (f(x)+g(x)) = \lim_{x\to 1}f(x) + \lim_{x\to 1}g(x)$$

Now, we can find the limits of f(x) and g(x) individually: 

$$\lim_{x\to 1}f(x) = \lim_{x\to 1} 3x^2 = 3(1)^2 = 3$$

$$\lim_{x\to 1}g(x) = \lim_{x\to 1} (4x-2) = 4(1)-2 = 2$$

Plugging these values back into the original equation, we get: 

$$\lim_{x\to 1} h(x) = \lim_{x\to 1} (3x^2+4x-2) = 3 + 2 = 5$$

Therefore, the limit of h(x) as x approaches 1 is equal to 5. 

In summary, the addition property of limits allows us to simplify complex functions by breaking them down into simpler parts and applying limits individually, which aids in finding the limit of the original function.

---

Some of the most important limit properties include the following:

- The limit of a constant is the constant itself. This means that if a function f(x) is a constant value c, then the limit of f(x) as x approaches some value a is also c. This can be written mathematically as follows:

$$
\lim_{x \to a} c = c
$$

- The limit of the sum (or difference) of two functions is equal to the sum (or difference) of the limits of those functions. This means that if f(x) and g(x) are two functions, and if the limits of f(x) and g(x) as x approaches a are L and M, respectively, then the limit of their sum or difference is equal to L + M or L - M, as appropriate. This can be written mathematically as follows:

$$
\begin{aligned}
\lim_{x \to a} [f(x) + g(x)] &= \lim_{x \to a} f(x) + \lim_{x \to a} g(x) \
\lim_{x \to a} [f(x) - g(x)] &= \lim_{x \to a} f(x) - \lim_{x \to a} g(x)
\end{aligned}
$$

- The limit of a product (or quotient) of two functions is equal to the product (or quotient) of the limits of those functions, provided the denominator of the quotient is not equal to zero. This means that if f(x) and g(x) are two functions, and if the limits of f(x) and g(x) as x approaches a are L and M, respectively, then the limit of their product or quotient is equal to L * M or L / M, as appropriate. This can be written mathematically as follows:

$$
\begin{aligned}
\lim_{x \to a} [f(x) * g(x)] &= \lim_{x \to a} f(x) * \lim_{x \to a} g(x) \
\lim_{x \to a} \frac{f(x)}{g(x)} &= \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}
\end{aligned}
$$

These properties provide a set of rules and principles that can be used to manipulate and simplify expressions involving limits, and to evaluate limits that might otherwise be difficult or impossible to calculate directly.

---

# Resources

<div class="videoWrapper">
<iframe src="https://www.youtube-nocookie.com/embed/joewRl1CTL8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>