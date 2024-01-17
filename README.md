# mass-vs-redshift-pollock-plot

Plots illustrating the mass and redshift measurements of CBC detections through the GWTC-3 catalog.
I use this example to illustrate why hierarchical inference on GW data is hard.
Specifically, one can pose the seemingly simple question: _Is there a correlation between black hole masses and their redshifts?_
At face value (Plot 1), the answer is a clear yes, but after folding in measurement uncertainty (Plot 2) and selection effects (Plot 3) it's clear that the problem is much more complicated (as of today, there is no known correlation between masses and redshifts).

### Plot 1: Scatter

Scatter plot of posterior mean total mass and redshift measurements (under a default, uninformative prior).
Colors are arbitrary, and the size of each dot scales with the event's estimated mass.

![alt text](mass_v_redshift_pollock_plot.png)

### Plot 2: An "honest" scatter

The same plot, but now with "blobs" that show the central 90% credible posterior bounds on each event's mass and redshift.

![alt text](mass_v_redshift_pollock_plot_with_errors.png)

### Plot 3: An "honest" scatter, annotated

As above, but now annotated to emphasize, for pedagogical purposes, that these measurements *do not* establish a correlation between mass and redshift.
Instead, the absence of measurements in the upper left corner is due to the relative rarity of high mass black holes and the small time-volume probed in the nearby Universe.
And the absence of events in the lower right corner is due to search selection effects.

![alt text](mass_v_redshift_pollock_plot_with_errors_annotated.png)
