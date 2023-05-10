# Chain Rule

## Chain Rule

The chain rule is a method for finding the derivative of a composite function. In other words, it allows you to find the rate of change of one function with respect to another.

The general form of the chain rule is as follows:

If y = f(u) and u = g(x), then the derivative of y with respect to x is given by:

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$$

In other words, the derivative of y with respect to x is equal to the derivative of y with respect to u, multiplied by the derivative of u with respect to x.

Here is an example of the chain rule in action:

Suppose we have a function y = f(x) defined as:

$$y = (x^2 + 1)^3$$

To find the derivative of this function, we can use the chain rule as follows:

First, we define a new variable u that is equal to x^2 + 1. This gives us:

$$u = x^2 + 1$$

Next, we define a new function y = f(u) that is equal to u^3. This gives us:

$$y = (x^2 + 1)^3 = u^3$$

Now we can use the chain rule to find the derivative of y with respect to x. We have:

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$$

The derivative of y with respect to u is simply 3u^2, so:

$$\frac{dy}{dx} = 3u^2 \cdot \frac{du}{dx}$$

To find the derivative of u with respect to x, we simply take the derivative of the original equation u = x^2 + 1 with respect to x. This gives us:

$$\frac{du}{dx} = 2x$$

Substituting this into the previous equation, we get:

$$\frac{dy}{dx} = 3u^2 \cdot 2x = 3(x^2 + 1)^2 \cdot 2x$$

Therefore, the derivative of y with respect to x is:

$$\frac{dy}{dx} = 6x(x^2 + 1)^2$$

This is the final result, which shows how the derivative of y with respect to x can be found using the chain rule.

---
