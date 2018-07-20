.. FAST-tutorial documentation master file, created by
   sphinx-quickstart on Fri Jul 20 09:49:20 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

FAST tutorial
=============

FAST is a horizontal-axis wind turbine (HAWT) dynamic analysis code developed
by the National Renewable Energy Laboratory (NREL)
that simulates the deflections, motions, and loading of a defined wind
turbine design in specified wind conditions. FAST can be incredibly useful in
the design and analysis of many aspects of the wind turbine, such as the blade,
tower, nacelle, platform, and generator, to name a few.

The purpose of this tutorial is to help those unacquainted with FAST quickly
become familiar with it and how it can benefit their research related to
wind turbine design. This tutorial is specifically targeted for FASTv7_, though
some material included here may be helpful for those using other versions,
such as FASTv8_ and OpenFAST_. In addition, this tutorial is directed toward
Mac and Linux users.

.. _FASTv7: https://nwtc.nrel.gov/FAST7

.. _FASTv8: https://nwtc.nrel.gov/FAST8

.. _OpenFAST: https://nwtc.nrel.gov/OpenFAST

Getting Started
---------------

To begin, request an account to access and download software in the NREL/NWTC
portal. The link to the page can be found here_. Your account will need to be
approved, but in general this should be done fairly quickly (within one or
two days).

.. _here: https://nwtc.nrel.gov/enduser/register

Once your account has been granted, go to the FASTv7_ webpage and download
*FAST Archive for Linux (tar.gz 3.1 MB)*. To compile FAST, a number of
programs need to be downloaded. To see a list of these codes, unzip the
downloaded FAST folder, and open the makefile in the Compiling directory. At
the beginning of the folder should be a list of the other codes, which should
read:

* FAST                    (v7.02.00d-bjj, 20-Feb-2013)
* AeroDyn                 (v13.00.02a-bjj, 20-Feb-2013)
* InflowWind              (v1.01.00b-bjj, 10-Aug-2012)
* NWTC Subroutine Library (v1.07.00b-mlb, 10-Jan-2013)

We've already downloaded the FAST directory, but still need to download the
other packages. Included are hyperlinks for the specific versions for
Aerodyn_, InflowWind_, and the NWTC_ subroutine library. These versions
don't match exactly with what is specified in the FAST makefile, but still
successfully compile FAST.

.. _Aerodyn: https://nwtc.nrel.gov/AeroDyn13
.. _InflowWind: https://nwtc.nrel.gov/InflowWind1
.. _NWTC: https://nwtc.nrel.gov/nwtc_subs

Compiling FAST
--------------

Once the packages need to compile FAST are downloaded, we can compile FAST
using the makefile provided in the Compiling subdirectory of the FAST directory.


Wind File Generation
--------------------

Running FAST
------------

Useful Simulation Parameters
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Defining Outputs
~~~~~~~~~~~~~~~~




.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
