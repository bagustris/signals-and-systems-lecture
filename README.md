# Continuous- and Discrete-Time Signals and Systems - Theory and Computational Examples

![Integration Test](https://github.com/bagustris//signals-and-systems-lecture/workflows/Integration%20Test/badge.svg)

This repository collects didactically edited [Jupyter](https://jupyter.org/)
notebooks that introduce the theory of linear, time-invariant (LTI) signals and
systems.
Please take a look at the [static version](http://nbviewer.ipython.org/github/bagustris/signals-and-systems-lecture/blob/master/index.ipynb)
for a first glance.
The continuous-time case, as well as the temporally sampled (discrete-time)
case is covered.
The theory is accompanied by a series of computational examples and exercises
written in [IPython 3](http://ipython.org/).  

![System in the temporal and spectral domain](systems_spectral_domain/LTI_system_time_spectral_domain.png)

The notebooks constitute the lecture notes to the bachelor's course
[Signals and Systems](http://www.int.uni-rostock.de/Signal-und-Systemtheorie.428.0.html)
given by [Sascha Spors](http://www.int.uni-rostock.de/Staff-Info.23+B6JmNIYXNoPWUxOTliMTNjY2U2MDcyZjJiZTI0YTc4MmFkYTE5NjQzJnR4X2pwc3RhZmZfcGkxJTVCYmFja0lkJTVEPTMmdHhfanBzdGFmZl9waTElNUJzaG93VWlkJTVEPTExMQ__.0.html) at the University of Rostock, Germany.
The contents are provided as [Open Educational Resource](https://de.wikipedia.org/wiki/Open_Educational_Resources)
, so feel free to fork, share, teach and learn.
You can give the project a [Star](https://github.com/bagustris/signals-and-systems-lecture/stargazers)
if you like the notebooks.

## Content

### Signals
* [Standard Signals](continuous_signals/standard_signals.ipynb)
* [Operations](continuous_signals/operations.ipynb)

### Characterization of Systems in Time Domain
* [Impulse Response](systems_time_domain/impulse_response.ipynb)
* [Convolution](systems_time_domain/convolution.ipynb)
* [Step Response](systems_time_domain/step_response.ipynb)
* [Eigenfunctions and the Transfer Function](systems_time_domain/eigenfunctions.ipynb)
* [Example: Analysis of a Passive Electrical Network](systems_time_domain/network_analysis.ipynb)
* [Example: Analysis of a Damped Spring Pendulum](systems_time_domain/spring_pendulum_analysis.ipynb)


### The Laplace Transform
* [Definition](laplace_transform/definition.ipynb)
* [Properties](laplace_transform/properties.ipynb)
* [Theorems](laplace_transform/theorems.ipynb)
* [Summary of Properties, Theorems and Transforms](laplace_transform/table_theorems_transforms.ipynb)
* [Inverse Transform](laplace_transform/inverse.ipynb)
* [Analysis of Passive Electrical
  Networks](laplace_transform/network_analysis.ipynb)

### The Fourier Transform
* [Definition](fourier_transform/definition.ipynb)
* [Properties](fourier_transform/properties.ipynb)
* [Theorems](fourier_transform/theorems.ipynb)
* [Summary of Properties, Theorems and
  Transforms](fourier_transform/table_theorems_transforms.ipynb)

### Characterization of Systems in Spectral Domain
* [The Transfer Function](systems_spectral_domain/transfer_function.ipynb)
* [The Bode Plot](systems_spectral_domain/bode_plot.ipynb)
* [Phase and Group Delay](systems_spectral_domain/phase_group_delay.ipynb)
* [Combination of Systems](systems_spectral_domain/combination.ipynb)

### Properties of LTI system
* [Causality and Stability](systems_properties/causality_stability.ipynb)
* [Classes of Systems](systems_properties/classes.ipynb)
* [Idealized Systems](systems_properties/idealized_systems.ipynb)

### Periodic Signal
* [Spectrum](periodic_signals/spectrum.ipynb)
* [Relation between Spectrum and Fourier Series](periodic_signals/fourier_series.ipynb)
* [Convolution of a Periodic with an Aperiodic
  Signal](periodic_signals/convolution.ipynb)

### Sampling of Signal
* [Ideal Sampling and Reconstruction](sampling/ideal.ipynb)

### Discrete Signals
* [Standard Signals](discrete_signals/standard_signals.ipynb)
* [Operations](discrete_signals/operations.ipynb)

### Characterization of Discrete Systems in Time Domain
* [Difference Equation](discrete_systems_time_domain/difference_equation.ipynb)
* [Impulse Response](discrete_systems_time_domain/impulse_response.ipynb)
* [Linear Convolution](discrete_systems_time_domain/linear_convolution.ipynb)
* [Example: Convolution of an Audio Signal with a Room Impulse Response](discrete_systems_time_domain/convolution_room_IR.ipynb)
* [Eigenfunctions and the Transfer Function](discrete_systems_time_domain/eigenfunctions.ipynb)

* [Definition](z_transform/definition.ipynb)
* [Properties](z_transform/properties.ipynb)
* [Theorems](z_transform/theorems.ipynb)
* [Summary of Properties, Theorems and Transforms](z_transform/table_theorems_transforms.ipynb)

### Discrete-Time Fourier Transform
* [Definition](discrete_time_fourier_transform/definition.ipynb)
* [Properties](discrete_time_fourier_transform/properties.ipynb)
* [Theorems](discrete_time_fourier_transform/theorems.ipynb)
* [Summary of Properties, Theorems and
  Transforms](discrete_time_fourier_transform/table_theorems_transforms.ipynb)

### Discrete Fourier Transform
* [Definition](discrete_fourier_transform/definition.ipynb)
* [Properties](discrete_fourier_transform/properties.ipynb)
* [Theorems](discrete_fourier_transform/theorems.ipynb)
* [Summary of Properties, Theorems and Transforms](discrete_fourier_transform/table_theorems_transforms.ipynb)
* [The Fast Fourier Transform](discrete_fourier_transform/fast_fourier_transform.ipynb)
* [Fast Convolution](discrete_fourier_transform/fast_convolution.ipynb)

### Characterization of Discrete-Time in the Spectral Domain
* [The Transfer Function](discrete_systems_spectral_domain/transfer_function.ipynb)
* [Example: Measurement of an Electroacoustic Transfer Function](discrete_systems_spectral_domain/measurement_acoustic_transfer_function.ipynb)
* [Magnitude and Phase](discrete_systems_spectral_domain/magnitude_phase.ipynb)
* [Phase and Group Delay](discrete_systems_spectral_domain/phase_group_delay.ipynb)
* [Combination of Systems](discrete_systems_spectral_domain/combination.ipynb)

## Usage and Contributing

The contents are provided as [Open Educational Resource](https://de.wikipedia.org/wiki/Open_Educational_Resources).
The text is licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)
, the code of the IPython examples under the [MIT license](https://opensource.org/licenses/MIT).
Feel free to use the entire collection, parts or even single notebooks for your
own purposes.
I am curious on the usage of the provided resources, so feel free to drop a
line or report to [Sascha.Spors@uni-rostock.de](mailto:Sascha.Spors@uni-rostock.de).

Our long-term vision is to lay the grounds for a **community driven concise and
reliable resource** covering the entire theory of signals and systems revised
by research and engineering professionals.
We aim at linking the strengths of both, the good old-fashioned text books
and the interactive playground of computational environments.
Open Educational Resources in combination with open source tools (Jupyter,
Python) and well-established tools for data literacy (git) provide the unique
possibility for collaborative and well-maintained resources.
Jupyter has been chosen due to its seamless integration of text, math and code.
The contents are represented future prove, as simple markdown layout allows for
conversion into many other formats (html, PDF, ...).
The git version management system features tracking of the changes and
authorship.

You are invited to contribute on different levels.
The lowest level is to provide feedback in terms of a
[Star](https://github.com/bagustris/signals-and-systems-lecture/stargazers)
if you like the contents.
Please consider reporting errors or suggestions for improvements as
[issues](https://github.com/bagustris/digital-signal-processing-lecture/issues).
We are always looking forward to new examples and exercises, as well as
reformulation of existing and novel sub-sections or sections.
Authorship of each considerable contribution will be clearly stated.
One way of introducing reformulated and new material is to handle them as

