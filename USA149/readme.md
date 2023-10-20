USA 149 (DSP satellite)

Here's a brief analysis of the results.  DSPs are known to rotate at 6 RPM.  The data was obtain by sampling every second with an orthogonal feed system on a 1.8m dish antenna and X and Y where processed in Gnuradio as the scrpt attached shows.  The Stokes parameters and other post analysis is done in the Jupyter-notebook in the folder.

By examining the Stokes parameter plot one can determine the spacecraft is indeed rotating at 6 RPM.  

![USA 149  26356 2000-024A _2023-10-20T18:33:23_stokes_par_zoom](https://github.com/ScottTilley/polarization/assets/64234963/abd24d8d-ba76-46bd-8111-730de13d443f)

Daniel Estévez in his analysis provides a concise description of the pheonenom observed here:
"The figure below shows the Stokes parameters Q, U and V. The three describe sinusoids. The parameters Q and U have the same amplitude and are in quadrature, which means that the linear polarization fraction is constant and the polarization angle changes linearly with time. The V parameter, which gives the circular polarization has less amplitude."

![USA 149  26356 2000-024A _2023-10-20T18:33:23_lin_pol_zoom](https://github.com/ScottTilley/polarization/assets/64234963/7900ce90-ecc5-44d4-a4fd-dc870ed82244)

The linear polarization plot shows that the polarizatrion angle is changing in a sinesudal manner.  This could be because we are viewing USA 149 from an angle and the viewing geometry doesn't allow us to see extreme changes in the polarization angle.  

See Daniel's discussion this topic when he observed Chang'e 5 here:
https://destevez.net/2020/12/change-5-polarization-in-the-ata-observations/

The period being twice that expected is similar to the light curve of a rotating satellite also being twice that of the actual rotation period of a satellite.  

Here's a discussion on this principle: 
https://www.satobs.org/tumble/rotandfp.html
