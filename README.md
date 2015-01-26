# Goodness_of_fit
Repository of some magnetic field profiles taken by HMI on board of the SDO.

There are millons of profiles that I have to cheak out trying to find stepwise changes like

\begin{equation}\label{fit}
B_{l}(t) = a + bt + c\left\{ 1 +\frac{2}{\pi}\tan^{-1}[n(t-t_0)]\right \}
\end{equation}

where $t$ represents time, $a$ and $b$ model the background field evolution, $c$ represents the half-amplitude of the field change, $t_0$ represents the midpoint of the field change, and $n$ is the inverse of the timescale over which the field change occurs.

Then, it becomes no realistic to look at each profile to choose those with a good-fit. 

Files:

*.txt :Some profiles of stepwise changes and other with random behavior-
 
 profile*.pdf: Plots the those profiles
 
 B_changes*.pdf: Plots of profiles with the best fit using a Levenberg-Marquardt algorithm to minimize the $\chi^2$
 
 
