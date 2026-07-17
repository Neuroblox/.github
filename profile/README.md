# Neuroblox

We are happy to announce the Neuroblox GUI 0.9 beta release.  For GUI installation instructions, go to [Neuroblox.jl](https://github.com/Neuroblox/Neuroblox.jl)

Access to the **Neuroblox programmatic interface** will be available in the 1.0 release.

[Neuroblox](https://neuroblox.ai) is a neuroCAD platform designed to accelerate biotech innovation and precision therapeutics for neuropsychiatric disorders and cognitive performance.  Optimize and derisk drugs, devices, and procedures in silico — before launching in patients.	

Start by loading prebuilt (experimentally validated) neural circuits that you can modify, or use experimental data to model your own neural circuits from modular components.  Next, simulate treatment effects across spatio-temporal scales and predict outcomes: from molecular targets to biomarkers to psychiatric/cognitive symptoms.  Neuroblox uses libraries of modular neurobiological building blocks ("blox") that snap together like components in a circuit diagram.

### What Neuroblox can simulate:
- Individual neurons: Hodgkin-Huxley, IF, QIF, LIF
- Neuroreceptor dynamics: Glu AMPA, GABA-A, GABA-B, NMDA, D1, D2, 5-HT, TRPM4, nicotinic ACh ($\alpha$, $\beta$), muscarinic ACh
- Neural mass models: Jansen-Rit, Wilson-Cowan, Next-Generation
- Multiscale biomimetic neural circuits composed of neurons, synapses, micro-assemblies, and neural mass models

### What you can do with Neuroblox:
- Build circuits through an intuitive GUI or Neuroblox's neuroscience-specific programming language 
- Simulate interventions (drugs, devices, sensory inputs, behavioral tasks) and track neurobehavioral effects across scales
- Fit model parameters to your experimental data (electrophysiology, neuroimaging, behavioral)
- Rigorously compare competing hypotheses with parallel testing of alternative circuit architectures and mechanisms

Neuroblox models compile into high-performance numerical kernels, enabling practical exploration of large parameter spaces and the execution of optimization experiments that would be infeasible on other platforms.

A list of publications using Neuroblox, and links to the code behind those publications, can be found at www.neuroblox.ai/pubs

## Licensing

Neuroblox is free for non-commercial and academic use. For full details of the license, see 
the [Neuroblox EULA](https://github.com/Neuroblox/NeurobloxEULA). For commercial use, please contact
[info@neuroblox.ai](mailto:info@neuroblox.ai).
