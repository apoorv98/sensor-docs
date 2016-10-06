Velodyne VLP - 16
=================

Introduction
------------

The VLP-16 creates 360 ◦ 3D images by using 16 laser/detector pairs mounted
in a compact housing. The housing rapidly spins and the lasers fire thousands
of times per second, providing a 3D point cloud in real time. Figure 1 shows an
imaging system where LiDAR is used.

**Some of the important features include:**

1. Horizontal Field of View (FOV) of 360◦
2. Vertical Field of View of 30◦
3. Rotational speed of 5-20 rotations per second (adjustable) 
4. Returns of up to 100m (useful range depends on application).

Software Installation
---------------------

The following guide walks you through the installation steps for using the VeloView software that comes with Velodyne VLP-16. This guide developed by installing
the software on system running Ubuntu 16.04LTS. For installation steps on other platforms refer the site VeloView wiki and downloads.

**Installation steps:**

1. Getting the source code
Open the terminal and change the directory where you want to install the software. Then use the following command to pull the source files.

**Note:** This assumes git is already installed on the system, if not use `$ sudo apt-get-install git` command before following the next steps.

.. code-block:: bash
      $ git clone git://public.kitware.com/VeloView.git


