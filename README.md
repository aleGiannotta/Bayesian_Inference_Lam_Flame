# Bayesian_Inference_Lam_Flame
We perform twenty experiments on an acoustically-forced laminar premixed Bunsen flame and
assimilate high-speed footage of the natural emission into a physics-based model containing
seven parameters. The experimental rig is a ducted Bunsen flame supplied by a mixture of
methane and ethylene. A high-speed camera captures the natural emission of the flame, from
which we extract the position of the flame front. We use Bayesian inference to combine this
experimental data with our prior knowledge of this flame’s behaviour. This prior knowledge
is expressed through (i) a model of the kinematics of a flame front moving through a model of
the perturbed velocity field, and (ii) a priori estimates of the parameters of the above model
with quantified uncertainties. We find the most probable a posteriori model parameters
using Bayesian parameter inference, and quantify their uncertainties using Laplace’s method
combined with first-order adjoint methods. This is substantially cheaper than other common
Bayesian inference frameworks, such as Markov Chain Monte Carlo. This process results
in a quantitatively-accurate physics-based reduced-order model of the acoustically forced
Bunsen flame for injection velocities ranging from 1.75 m/s to 2.99 m/s and equivalence ratio
values ranging from 1.26 to 1.47, using seven parameters. We use this model to evaluate the
heat release rate between experimental snapshots, to extrapolate to different experimental
conditions, and to calculate the flame transfer function and its uncertainty for all the flames.
Since the proposed model relies on only seven parameters, it can be trained with little data
and successfully extrapolates beyond the training dataset. Matlab code is provided so that
the reader can apply it to assimilate further flame images into the model
