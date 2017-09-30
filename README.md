# Machine Learning Attacks on Majority Based Arbiter Physical Unclonable Functions

## Master’s Thesis

Since secret keys are used as basis for several security features, e.g. encryption or authen-
tication, there is a need to protect them from unauthorized access. Physical unclonable
functions (PUFs) ought to fulfill this need with the possibility to derive secret keys from
their intrinsic hardware imperfections These imperfections are linked inseparable with
the device and can be easily used to derive secret keys from but are hard to read out.
In addition, there is a high chance that they are unique to every instance. If that is true,
they can be used to securely identify devices.

Nevertheless, certain PUFs can be successfully attacked by machine learning attacks.
Machine learning attacks in combination with a feasible amount of challenge response
pairs make it possible to create models of Arbiter PUFs and XOR Arbiter PUFs, which
can be used to predict responses for unknown challenges. Large XOR Arbiter PUFs
would prevent these attacks, but suffer instability.

To counteract these instabilities, the principle of majority vote is applied to Arbiter
PUFs, which are used in XOR Arbiter PUFs. Its impacts on the stability of Arbiter PUFs
and XOR Arbiter PUFs, and relevant attacks are verified by simulations. It is shown
that majority vote enables large Majority XOR Arbiter PUFs. Furthermore, this work
verifies that large Majority XOR Arbiter PUFs increase the complexity of non-invasive
attacks exponentially by linear growth of the PUF. Thus, large Majority XOR Arbiter
PUFs constitute a foundation for machine learning attack resistant PUFs. Since they are
vulnerable to invasive attacks, they do not protect secret keys completely.

## Contact

manuel.oswald@fu-berlin.de