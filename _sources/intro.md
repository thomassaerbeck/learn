# Introduction to neutron reflectometry fitting

The aim of this course, and the companion lecture, are to give an introduction to the following subjects: 
- the **Fourier transform** and how a Born approximation approach may be used to analyse neutron reflectometry data; 
- the logic of **model-dependent analysis**; 
- neutron reflectometry "slab models" and their traditional parameterisation; 
- **reparameterisation** of these models to include chemical and physical insight; and 
- the process and problems associated with **fitting** in a model-dependent analysis procedure. 

It is **assumed** that this reader has been introduced to the technique of neutron reflectometry, such as what this technique can be used to study and the data collection methodology.

The integration with JupyterHub is powered by the [PaNOSC project](https://www.panosc.eu) and running on compute at the European Spallation Source's Data Management and Software Centre. 

This material was developed by [Andrew McCluskey](mailto:andrew.mccluskey@ess.eu) from the [European Spallation Source](https://europeanspallationsource.se/). 
If you have any questions, please get in touch.
Thanks to Drs Maximilian Skoda, Andrew Caruana, Stephen Hall, and Andrew Nelson for feedback on this material.

```{note}
In this course, we make use of the Python programming language heavily to show mathematics and plot figures. 
The aim is that the course should **not** require knowledge of Python to understand the content. 
If you are not comfortable with Python, feel free to skip the code blocks, but make sure to **pay attention** to the plots that are produced.

If you want to interact with the Python code, you can visit this course on [pan-learning.org](http://pan-learning.org/). 
If you do not already have an account you can request one [here](https://sim.e-neutrons.esss.dk/signup) or you can do a Federated Log in with UmbrellaID. 
Once you enrol yourself on the course ([Introduction to Neutron Reflectometry Fitting](https://pan-learning.org/moodle/course/view.php?id=96)), click on the JupyterHub link and navigate to the Jupyter Notebook that you want to modify the code for (the file path can be determined from the url of the page). 
It may take up to 5 minutes after you enrol for the system to recognize you so it advised you wait before launching the JupyterHub for the first time.
```

## Bibliography

Some particularly useful books and papers for reflectometry analysis, and data analysis in general include:
- Elementary Scattering Theory: For X-ray and Neutron Users by Devinder Sivia {cite}`sivia_elementary_2011`;
- *Current Opinion in Colloid & Interface Science*, **42**, 2019 covers a range of applications in soft and biological matter including {cite}`lakey_recent_2019,skoda_recent_2019,welbourn_new_2019`;
- Some interesting reviews of magnetic reflectometry analysis include {cite}`fitzsimmons_applications_2005,zabel_polarized_2007,toperberg_neutron_2015`; and
- Data Analysis: A Bayesian Tutorial by Devinder Sivia and John Skilling {cite}`sivia_data_2006`.

This list is not exhaustive and we suggest searching for and reading relevant work in your field **once you understand the basics**. 

```{bibliography}
```