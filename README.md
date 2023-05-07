# shear_stress_Strain

The relationship of shear stress and shear strain follows the equation :
 
τc = τc0 +( τs - τc0 ) (1 - exp((1- θ0 * γ)/τs)) + θ∞γ

where τc0 is critical resolved shear stress, τs is saturation stress, θ0 is initial hardening modulus, θ∞ is a remaining hardening modulus and γ is shear strain.

Main aim of this project is to develop a Machine Learning model that correctly predicts the error between experimental stresses and formulated stresses.

We deal with both true stress and shear stress, find the best formulated curve using mathematical expressions

Train ML model on thousands of Curve equations and their Mean absolute error with the experimental curve.
