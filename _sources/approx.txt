Approximation Methods
======================


Variational Method
-------------------

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
