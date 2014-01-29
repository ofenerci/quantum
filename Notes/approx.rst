Approximation Methods
======================


Variational Method
-------------------

Trial functions
~~~~~~~~~~~~~~~~~


1. :math:`\psi(x) = \cos\alpha x`, for :math:`|\alpha x|<\pi/2`, otherwise 0.
2. :math:`\psi(x) = \alpha^2 - x^2`, for :math:`|x|<\alpha`, otherwise 0.
3. :math:`\psi(x) = C \exp(-\alpha x^2/2)`.
4. :math:`\psi(x) = C(\alpha - |x|)`, for :math:`|x|<\alpha`, otherwise 0.
5. :math:`\psi(x) = C\sin\alpha x`, for :math:`|\alpha x|<\pi`, otherwise 0. 



~~~~~~~~~~~~~~~~~


Why don't we just use a most general variational method to find out the ground state? Because we will eventually come back to the time-independent Shrodinger equation.

Suppose we have a functional form

.. math::
   E(\psi^*, \psi, \lambda) = \int dx \psi^* H \psi - \lambda \left( \int dx \psi^* \psi - 1 \right)

The reason we have this Lagrange multiplier method is that the wave function should be normalized and this multiplier provides the degree of freedom. We would only get a wrong result if we don't include this DoF.

Variation of :math:`\psi^*`,

.. math::
   \delta E = \int dx \delta \psi^* H \psi - \int dx \delta \psi^* \psi = 0

Now what?

.. math::
   H \psi - \lambda \psi = 0

Not helpful.


Variational Method and Virial Theorem
---------------------------------------

For a potential :math:`V(x)=b x^n`, we can prove that virial theorem is valid for ground state if we use Gaussian trial function :math:`e^{- \alpha x^2/2}`.

A MMA proof is `here <_static/mma/variational.nb>`_.
