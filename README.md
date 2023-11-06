# HPC Tutorial Resources/General Software Development Resources
This repo contains links to various materials that may be helpful to those wishing to develop skills in software development. With the exception of the printed books all material linked in this repo is freely available, and doesn't require an account to view except in the case of videos hosted on Vimeo. Where possible a link to the github repo associated with the training material is provided. In the case of tutorials which have recordings a rough time commitment to watch the videos is provided (although no guarantee is given that the recordings are complete).  
  
The topics currently covered by this repo are (This repo is a work in progress, and so some topics may currently be empty.)
* C++ 
* Fortran
* C
* Python
* Cuda
* HIP
* RAJA
* Kokkos
* Julia
* R
* Rust     
* Bash
* OpenMP
* MPI
* OpenMP/MPI
* SYCL
* Software Testing
* Debugging
* Profiling
* Software Security
* SSH
* File Transfer (Scp, Sftp, rsync, etc)
* Queueing Systens (Slurm, PBS, etc)
* Environment Modules
* Git
* Parallel I/O and Filesystems
* HDF5
* Netcdf
* Json
* Yaml
* CMake
* Makefiles
* Containers
* Scientific Software Design
* Apt/Apt-get
* Macports
* Homebrew     
* Spack
* Pip (Python Package Manager)
* Anaconda Package Managers (conda and mamba)
* General data visualisation
* Paraview
* Visit
* Jupyter Notebooks/Jupyter Lab
* Emacs
* Vim
* Visual Studio
* WSL
* Algorithms and Floating Point Arithmetic
* Validation, Verification and Uncertainty Qualification (VVUQ)
* Artificial Intelligence/Machine Learning/Deep Learning
* Latex
* Markdown
* reStructuredText
* Sphinx
* Directory Structure (both Mac and Linux)
* Useful Tools
* Computer Hardware (CPUs, GPUs, FGPAs, etc)
* Computer Architecture (x86, Arm, RiscV, etc)
* Compilers
* Using/Maintaining/Updating Legacy Code
* Miscellaneous 

At one point these topics will be categorised (programming languages, package managers, Markup languages, etc), but for now they will remain seperate topics, until the repo is more complete.

## C++ 

### Video Tutorials
1) HSF (HEP Software Foundation) - Set up to provide training in various aspects of software development for the high energy physics community.
  * Github Repo - https://github.com/hsf-training/cpluspluscourse
    * 8th HEP C++ Course and Hands-on Training - The Essentials September 2023 - https://indico.cern.ch/event/1266661/overview
      * Time Commitment - Approximately 9 hours to watch tutorial + time for exercises
      * Peer Review -
      * Target Audience -
      * Audio/Visual Issues Recording(s) - None
        
    * 9th HEP C++ Course and Hands-on Training - Advanced C++  October 2023 - https://indico.cern.ch/event/1266628/
      * Time Commitment - Approximately 8 hours to watch tutorial + time for exercises
      * Peer Review -
      * Target Audience -
      * Audio/Visual Issues Recording(s) -
            
2) CSCS (Swiss National Supercomputing Centre)
  * Github Repo - https://github.com/eth-cscs/cpp-course-2023
    * https://www.youtube.com/watch?v=6i2ZXs-QCsw&list=PL1tk5lGm7zvT5cxiXM6H4SRH-QJCVFbmh - Advanced C++ workshop for HPC 2023
      * Time Commitment - Approximately 9.5 hours to watch tutorial + time for exercises
      * Peer Review -
      * Target Audience -
      * Audio/Visual Issues Recording(s) - 
                      
3) Archer2
  * Github Repo - https://github.com/EPCCed/archer2-cpp/
    * https://www.archer2.ac.uk/training/courses/230417-modern-c/ - Modern C++ for Computational Scientists 2023
      * Time Commitment - Approximately 9 hours to watch tutorial + time for exercises
      * Peer Review -
      * Target Audience -
      * Audio/Visual Issues Recording(s) - 
        
4) University of Victoria
   * https://www.youtube.com/watch?v=4jBdW1wNDgs&list=PLU4IQLU9e_OqLz5EFCd3GPXR0YUk_gMkg - First Year C++ Programming 2022
     * Time Commitment - Approximately 27 hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

5) Texas Advanced Computing Center
   * https://www.youtube.com/watch?v=DWmAWT5e3iQ - C++ for C Programmers (Day 1) 2023
   * https://www.youtube.com/watch?v=Vvq-3FXIbJQ - C++ for C Programmers (Day 2) 2023
   * Time Commitment - Approximately 5.5 hours
   * Peer Review -
   * Target Audience -
   * Audio/Visual Issues Recording(s) -
                     
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other
1) CERN
   * https://cds.cern.ch/record/2740329?ln=en - Modern C++: Demystifying Value Categories in C++ (lecture 1) 2020
   * https://cds.cern.ch/record/2740331?ln=en - Modern C++: Demystifying Value Categories in C++ (lecture 2) 2020
   * Time Commitment - Approximately 2 Hours 15 Minutes
   * Peer Review -
   * Target Audience -
   * Audio/Visual Issues Recording(s) -

   * https://cds.cern.ch/record/2737223?ln=en - Modern C++: Everything you (n)ever wanted to know about C++'s Lambdas (lecture) 2020
   * Time Commitment - Approximately 1 Hour
   * Peer Review -
   * Target Audience -
   * Audio/Visual Issues Recording(s) -

2) CppCon
   * https://www.youtube.com/playlist?list=PLHTh1InhhwT4TJaHBVWzvBOYhp27UO7mI - Back To Basics 2021
   * Time Commitment - Approximately 20 Hours 15 Minutes
   * Peer Review -
   * Target Audience -
   * Audio/Visual Issues Recording(s) -
           
## Fortran

### Video Tutorials
1) Archer2
  * Github Repo - https://github.com/ARCHER2-HPC/archer2-fortran-intro
    * https://www.archer2.ac.uk/training/courses/221213-modern-fortran/ - Introduction to Modern Fortran 2022
      * Time Commitment - Approximately 2.5 Hours + time for exercises
      * Peer Review -
      * Target Audience -
      * Audio/Visual Issues Recording(s) - Recordings known to be incomplete (to be replaced in future)
                
2) OLCF
   * https://vimeo.com/711784748 - Coding for GPUs with Standard Fortran
     * Time Commitment - Approximately 1 Hour
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) - 

3) NERSC
   * Github Repo - https://github.com/everythingfunctional/FUN_modern_fortran_basics
     * https://www.youtube.com/watch?v=DQLnhg1TegM - Fun Training - Modern Fortran Basics: Day 1, Part 1 2023
     * https://www.youtube.com/watch?v=qEzpddXgwcA - Fun Training: Modern Fortran Basics - Day 1, Part 2 2023
     * https://www.youtube.com/watch?v=1efhBVftcxg - Fun Training: Modern Fortran Basics - Day 2, Part 1 2023
     * https://www.youtube.com/watch?v=0YgxNwPt5hY - Fun Training - Modern Fortran Basics: Day 2, Part 2 2023
     * Time Commitment - Approximately 8 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
            
### Non Video Based Tutorials        

### Open Source Books

### Print Books

### Other

## C

### Video Tutorials
1) OLCF
   * Github Repo - https://github.com/olcf/foundational_hpc_skills
     * https://vimeo.com/843209014 - Intro to C Programing 2023
       * Time Commitment - Approximately 1.5 Hours
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -
        
2) University of Victoria
   * https://www.youtube.com/watch?v=rlA89I3Y0nQ&list=PLU4IQLU9e_Oq2dqhFV6n9shODnN8DR9b_ - First Year C Programming 2020
     * Time Commitment - Approximately 23 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
                
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Python

### Video Tutorials
1) Archer2
  * Github Repo - https://github.com/EPCCed/archer2-python
    * https://www.archer2.ac.uk/training/courses/220223-python/ - Scientific Programming with Python 2022
      * Time Commitment - Approximately 8.5 Hours + time for exercises
      * Peer Review -
      * Target Audience -
      * Audio/Visual Issues Recording(s) -
  
  * Github Repo - https://github.com/swcarpentry/python-novice-gapminder
    * https://www.archer2.ac.uk/training/courses/220725-plot-prog-python/ - Plotting and Programming with Python 2022
      * Time Commitment - Approximately 6 Hours + time for exercises
      * Peer Review -
      * Target Audience -
      * Audio/Visual Issues Recording(s) -
             
2) CSCS 
  * Github Repo - https://github.com/eth-cscs/PythonHPC (For 2023 Course)
    * https://www.youtube.com/watch?v=s9_yNr-_jDo&list=PL1tk5lGm7zvSBUNbWEgTnh-vguO4w1eeY - High-Performance Computing with Python 2022
      * Time Commitment - Approximately 9.5 Hours + time for exercises
      * Peer Review -
      * Target Audience -
      * Audio/Visual Issues Recording(s) -
         
2) OLCF
   * Github Repo - https://github.com/olcf/foundational_hpc_skills
     * https://vimeo.com/782150078 - Intro to Python - 2022 OLCF Winter HPC Crash Course
    * Time Commitment - Approximately 1.25 Hours 
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
                 
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Cuda

### Video Tutorials
1) Archer2
  * Github Repo - https://github.com/EPCCed/archer-gpu-course
    * https://www.archer2.ac.uk/training/courses/201123-gpu-cuda/ - GPU Programming with CUDA 2020
      * Time Commitment - Approximately 4.5 Hours + time for exercises
      * Peer Review -
      * Target Audience -
      * Audio/Visual Issues Recording(s) -
       
1) OLCF
   * Agenda of series (2020-2021) - https://www.olcf.ornl.gov/cuda-training-series/
     * Github Repo - https://github.com/olcf/cuda-training-series
       * https://vimeo.com/386244979 - Introduction to CUDA C++
       * https://vimeo.com/393552516 - CUDA Shared memory
       * https://vimeo.com/398824746 - CUDA Optimization (1 of 2)
       * https://vimeo.com/414827487 - CUDA Optimization (2 of 2)
       * https://vimeo.com/419029739 - CUDA Atomics, Reductions, and Warp Shuffle
       * https://vimeo.com/431616420 - CUDA Managed Memory
       * https://vimeo.com/442361242 - CUDA Concurrency
       * https://vimeo.com/454873041 - GPU Performance Analysis
       * https://vimeo.com/461821629 - CUDA Cooperative Groups
       * https://vimeo.com/575930839 - NVIDIA CUDA Training Series 10: Multithreading
       * https://vimeo.com/589019347 - CUDA Multi Process Service
       * https://vimeo.com/605842702 - CUDA Debugging
       * https://vimeo.com/632113508 - CUDA Graphs
         * Time Commitment - Approximately 20 hours to watch tutorial + time for exercises
         * Peer Review -
         * Target Audience -
         * Audio/Visual Issues Recording(s) -
           
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## HIP

### Video Tutorials
1) OLCF
   * Series Agenda - https://www.olcf.ornl.gov/hip-training-series/
     * https://vimeo.com/854504843 - Intro to GPUs and HIP 2023
     * https://vimeo.com/858780676 - Porting Applications to HIP 2023
     * https://vimeo.com/866537748 - AMD Memory Hierarchy 2023
     * https://vimeo.com/870442108 - GPU Profiling (Performance Timelines: Rocprof and Omnitrace) 2023
     * https://vimeo.com/881862090 - GPU Profiling (Performance Profile: Omniperf) 2023
       * Time Commitment - Approximately 8.0 Hours
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -
                
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## RAJA

### Video Tutorials
1) OLCF
   * https://vimeo.com/873712030 - A Tutorial Introduction to RAJA 2023
     * Time Commitment - Approximately 1.5 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
              
### Non Video Based Tutorials
1) Lawrence Livermore National Laboratory
   * Github Repo -  https://github.com/LLNL/raja-suite-tutorial
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

### Open Source Books

### Print Books

### Other

## Kokkos

### Video Tutorials
1) Exascale Computing Project
   * https://www.youtube.com/watch?v=rUIcWtFU5qM - The Kokkos Lectures - module 1 2020
   * https://www.youtube.com/watch?v=O-asHTtO7O4 - The Kokkos Lectures - module 2 2020
   * https://www.youtube.com/watch?v=nGyJS8u-6GY - The Kokkos Lectures - module 3 2020
   * https://www.youtube.com/watch?v=s9ecpeWRePs - The Kokkos Lectures - module 4 2020
   * https://www.youtube.com/watch?v=xEAyOod57-c - The Kokkos Lectures - module 5 2020
   * https://www.youtube.com/watch?v=1J3JQ3d3cRc - The Kokkos Lectures - module 6 2020
   * https://www.youtube.com/watch?v=MH6zFYGw0HU - The Kokkos Lectures - module 7 2020
   * https://www.youtube.com/watch?v=_qD4X66MQF8 - The Kokkos Lectures - module 8 2020
     * Time Commitment - Approximately 14.5 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
     
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Julia

### Video Tutorials
1) University of Queensland
   * Title - Programming of Simulation, Analysis, and Learning Systems
   * Year - 2023
   * Tutorial Link - http://courses.smp.uq.edu.au/MATH2504/2023/
   * Video Link - https://www.youtube.com/watch?v=XZbhdDsLLvk&list=PL7RZyOlq_XnzFO9IZ4udvW_b6o5trllDL
   * Time Commitment - Approximately 34 Hours
   * Peer Review -
   * Target Audience -
   * Audio/Visual Issues Recording(s) -

 2) MIT
    * Title - Julia: A Fresh Approach to Computing
    * Year - 2023
    * Tutorial Link - https://computationalthinking.mit.edu/Fall23/ 
    * Video Link - https://www.youtube.com/playlist?list=PLP8iPy9hna6T56GkMHEdSrjCCheNuEwI0
    * Time Commitment - Approximately 23.5 Hours
    * Peer Review -
    * Target Audience -
    * Audio/Visual Issues Recording(s) -

3) OLCF
   * Tutorial Website - https://juliaornl.github.io/TutorialJuliaHPC/
     * https://vimeo.com/830368460 - Julia for High Performance Computing Tutorial 2023
       * Time Commitment - Approximately 3 Hours 
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -
       
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## R

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Rust

### Video Tutorials

### Non Video Based Tutorials
Title - The Rust Programming Language  
Authors - Steve Klabnik and Carol Nichols, with contributions from the Rust Community  
Link - https://doc.rust-lang.org/book/title-page.html  

### Open Source Books

### Print Books

### Other
1) Archer 2
   * https://www.archer2.ac.uk/training/courses/230524-rust-vt/ - Scientific Computing with Rust – Why you should learn (yet) another language 2023
       * Time Commitment - Approximately 1 Hour
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -

2) Scientific Computing in Rust 2023 Conference
   * Agenda https://scientificcomputing.rs/timetable
   * Videos - https://www.youtube.com/watch?v=iCcHAKcL6hw&list=PLrueqeouhcZPxzKNEQ65NSfk1bOEvEHBp
   * Peer Review -
   * Target Audience -
     
## Bash

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## OpenMP

### Video Tutorials
1) Archer2
   * Github Repo - https://github.com/EPCCed/archer2-openmp-2022-08-30
     * https://www.archer2.ac.uk/training/courses/220830-openmp/ - Introduction to OpenMP 2022
       * Time Commitment - Approximately 8.5 Hours + time for exercises
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -   
         
   * Github Repo - https://github.com/EPCCed/archer2-advanced-OpenMP/tree/2022-11-29
     * https://www.archer2.ac.uk/training/courses/221129-advanced-openmp/ - Advanced OpenMP
       * Time Commitment - Approximately 8.5 Hours + time for exercises
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -        
        
2) Exascale Computing Project
   * https://www.youtube.com/watch?v=pVL7W-ahk-M - OpenMP Tutorial for ECP 2022
     * Time Commitment - Approximately 3.5 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
         
   * https://www.youtube.com/watch?v=RcIRArjUwDc - The OpenMP Ecosystem in LLVM - Features, Functionality, and Flags 2022
     * Time Commitment - Approximately 2.0 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

3) OLCF
   * https://vimeo.com/869665013 - Introduction to OpenMP Offload Part 1 : Basics of Offload 2023
   * https://vimeo.com/873103703 - OpenMP Offload Part 2: Optimization and Data Management 2023
     * Time Commitment - Approximately 2.25 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
       
   * https://vimeo.com/781271547 - Using HIP and GPU Libraries with OpenMP
     * Time Commitment - Approximately 1 Hour
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

4) NHR@FAU
   * https://www.youtube.com/watch?v=sGJ8VJTt7Ig&list=PLxVedhmuwLq2Ie88ODuZufCGorawPO1AP - Parallel Programming with OpenMP and MPI 2020
     * Time Commitment - Approximately 12.5 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
            
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## MPI

### Video Tutorials
1) Archer2
   * Github Repo - https://github.com/EPCCed/archer2-MPI-2022-03-23
     * https://www.archer2.ac.uk/training/courses/220323-mpi/ - Message-passing programming with MPI 2022
       * Time Commitment -
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -
         
   * Github Repo - https://github.com/EPCCed/archer2-AMPP-2023-09-06
     * https://www.archer2.ac.uk/training/courses/230906-advanced-mpi/ - Advanced MPI 2023
       * Time Commitment -
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -
         
2) Exascale Computing Project
   * https://www.youtube.com/watch?v=XP7joUTgjxs - How To Leverage New MPI Features for Exascale Applications 2022
     * Time Commitment - Approximately 9.0 Hours + time for exercises
     * Audio/Visual Issues Recording(s) -

3) NHR@FAU
   * https://www.youtube.com/watch?v=sGJ8VJTt7Ig&list=PLxVedhmuwLq2Ie88ODuZufCGorawPO1AP - Parallel Programming with OpenMP and MPI 2020
     * Time Commitment - Approximately 12.5 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
              
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## SYCL

### Video Tutorials

### Non Video Based Tutorials
1) Codeplay Software Ltd
   * Title - syclacademy
   * Github Repo - https://github.com/codeplaysoftware/syclacademy
       * Peer Review -
       * Target Audience -
         
### Open Source Books

### Print Books

### Other

## Software Testing

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Debugging

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Profiling

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Software Security

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## SSH

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other
  
## File Transfer (Scp, Sftp, rsync, etc)

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Queueing Systens (Slurm, PBS, etc)

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Environment modules

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Git
Git is a version control system that allows developers to track changes in their code. Github and Gitlab are both open source hosting services for git repositories. 

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Parallel I/O and Filesystems

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## HDF5

### Video Tutorials
1) Exascale Computing Project
   * https://www.youtube.com/watch?v=1Urx9dzTiwY - Using HDF5 Efficiently on HPC Systems 2022
     * Time Commitment - Approximately 3 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
       
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Netcdf

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Json

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Yaml

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## CMake

### Video Tutorials
1) Archer2
  * Github Repo - https://github.com/EPCCed/cmake_webinar
    * https://www.archer2.ac.uk/training/courses/231004-cmake-vt/ - Building and installing packages with CMake: a hands-on introduction 2023
      * Time Commitment - Approximately 1 Hour
      * Peer Review -
      * Target Audience -
      * Audio/Visual Issues Recording(s) -
         
2) Exascale Computing Project
   * Agenda - https://www.exascaleproject.org/event/cmake-training-2108/
     * https://www.youtube.com/watch?v=6FYOc-XBs9c&list=PLF590mYJUDzK4bgI6hZDpbWL9qiHkZDt7&index=33 - CMake Training Day 1 2021
     * https://www.youtube.com/watch?v=AzKXRExgeH4&list=PLF590mYJUDzK4bgI6hZDpbWL9qiHkZDt7&index=31 - CMake Training Day 2 2021
     * https://www.youtube.com/watch?v=W0oA7usTX98&list=PLF590mYJUDzK4bgI6hZDpbWL9qiHkZDt7&index=30 - CMake Training Day 3 2021
       * Time Commitment - Approximately 7 Hours
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -

### Non Video Based Tutorials
1) HSF
   * Title - More Modern CMake
   * Github Repo - https://github.com/hsf-training/hsf-training-cmake-webpage
       * Peer Review -
       * Target Audience -

### Open Source Books

### Print Books

### Other

## Makefiles

### Video Tutorials

### Non Video Based Tutorials
Title - Makefile Tutorial
Link to tutorial - https://makefiletutorial.com/#makefile-cookbook

### Open Source Books

### Print Books

### Other

## Containers

### Video Tutorials
1) HSF Training
   * Github Repo - https://github.com/hsf-training/hsf-training-docker
     * https://www.youtube.com/watch?v=Qr42pEtio-Q&list=PLKZ9c4ONm-VnqD5oN2_8tXO0Yb1H_s0sj - Introduction to Docker
       * Time Commitment - Approximately 1.5 Hours
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -

2) Archer2
   * Github Repo - https://github.com/EPCCed/2022-01-19_containers_online
     * https://www.archer2.ac.uk/training/courses/220119-containers/ - Reproducible computational environments using containers: Introduction to Docker and Singularity 2022
       * Time Commitment - Approximately 8.0 Hours + time for exercises
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Scientific Software Design

### Video Tutorials
   
### Non Video Based Tutorials

### Open Source Books

### Print Books
Title - Scientific Software Design: The Object-Oriented Way  
ISBN - 9781139498784  

Title - Writing Scientific Software: A Guide to Good Style  
ISBN - 9781139458627  

### Other
1) OLCF
   * https://www.youtube.com/watch?v=toO0G5gZMs0 - IDEAS-ECP Webinar: Writing Clean Scientific Software
     * Time Commitment - Approximately 1 Hour
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

2) CERN
   * https://cds.cern.ch/record/2737225 - Software Design Patterns (lecture) 2020
     * Time Commitment - Approximately 1 Hour
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

   * https://cds.cern.ch/record/2736118?ln=en - Programming Paradigms (lecture) 2020
     * Time Commitment - Approximately 1 Hour
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

   * https://cds.cern.ch/record/2773051?ln=en - Writing parallel software 2021
     * Time Commitment - Approximately 1 Hour
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
       
   * https://cds.cern.ch/record/2773778?ln=en - Design patterns and best practices
     * Time Commitment - Approximately 1 Hour 30 Munutes
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

3) Exascale Computing Project
   * https://www.youtube.com/watch?v=UWmkj-9SdAI - IDEAS-ECP Webinar: Software Design Patterns in Research Software with Examples from OpenFOAM 2022
     * Time Commitment - Approximately 1 Hour
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -   

4) Better Scientific Software
   * https://www.youtube.com/watch?v=8NgJx6iSSrQ -  Scientific Software Design 2023
     * Time Commitment - Approximately 25 minutes
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

   * https://www.youtube.com/watch?v=hHXGxfgfI_4&list=PLuWzStas9iWEKdxtmt2EqRT9ulU4Eo_tv&index=4 - Refactoring Scientific Software 2023
     * Time Commitment - Approximately 20 minutes
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -
                     
## Apt/Apt-get
Apt is Ubuntus package manager. It installs packages system wide, so requires sudo permissions to install packages. Documentation on Ubuntus package management system can be found here https://ubuntu.com/server/docs/package-management .

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Macports
Macports is a Mac OS only package manager. It installs packages system wide, and requires sudo permissions to install packages. The homepage for Macports can be found here https://www.macports.org .

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Homebrew
Homebrew is a cross platform (linux and Mac OS) package manager. It doesn't require sudo privileges beyond those needed to install the prerequisites stated in the documentation. The homepage for Homebrew can be found here https://brew.sh .

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other
       
## Spack
Spack is a package manager which works across HPC systems, linux and Mac OS. It doesn't require sudo privileges beyond those needed to install the prerequisites stated in the documentation. The homepage for Spack can be found here https://spack.io .

### Video Tutorials
1) Exascale Computing Project
   * https://www.youtube.com/watch?v=WxVDr8LCCnA - Using Spack to Accelerate Developer Workflows 2022
     * Time Commitment - Approximately 3.0 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Pip (Python Package Manager)

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Anaconda Package Managers (conda and mamba)

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## General data visualisation

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Paraview

### Video Tutorials

### Non Video Based Tutorials
1) Argonne Leadership Computing Facility
   * Link to tutorial - https://docs.alcf.anl.gov/cooley/software-and-libraries/paraview-tutorial/

### Open Source Books

### Print Books

### Other

## Visit

### Video Tutorials

### Non Video Based Tutorials
1) Visit
   * Link to tutorial - https://visit-sphinx-github-user-manual.readthedocs.io/en/develop/tutorials/index.html
   
### Open Source Books

### Print Books

### Other

## Jupyter Notebooks/Jupyter Lab

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Emacs

### Video Tutorials

### Open Source Books
1) Use Gnu Emacs the plain text computing envirnoment by Keith Waclena
   * Link to book https://www2.lib.uchicago.edu/keith/emacs/emacs-tutorial.pdf

### Non Video Based Tutorials
Emacs comes with its own built in tutorial. After starting Emacs, this can be accessed by using holding down the Ctrl key, pressing h, letting go of both keys, and then clicking t and then enter.

### Print Books

### Other

## Vim

### Video Tutorials
1) OLCF
   * Github Repo - https://github.com/olcf/foundational_hpc_skills
     * https://vimeo.com/683027889 - HPC Crash Course: Vim 2021
       * Time Commitment - Approximately 1 Hour
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -
        
### Non Video Based Tutorials
To get a grip with the basic useage of Vim you can by simple typing vimtutor into the terminal on any UNIX-like system such as Linux or MacOS, and clicking enter.

### Open Source Books

### Print Books

### Other

## Visual Studio

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## WSL

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Algorithms and Floating Point Arithmetic

### Video Tutorials
1) Cern OpenLab/Fermi National Accelerator Lab
   * Events Page - https://indico.cern.ch/event/626147/
   * Title - CERN openlab Mini-Workshop on Floating-Point Computation
   * Recordings - https://cds.cern.ch/search?f=490__a&p=CERN%20openlab%20Mini-Workshop%20on%20Floating-Point%20Computation
   * Time Commitment - Approximately 3.5 Hours
   * Year - 2017
   * Peer Review -
   * Target Audience -  
   * Audio/Visual Issues Recording(s) -

2) BUGSENG and University of Parma
   * Title - Floating-Point Computation Traps & Pitfalls
   * Part 1 Video - https://www.youtube.com/watch?v=OMach63q_HI
   * Part 2 Video - https://www.youtube.com/watch?v=I6-bYqin1OE&t=1070s
   * Time Commitment - Approximately 2 Hours
   * Year - 2020
   * Peer Review -
   * Target Audience -
   * Audio/Visual Issues Recording(s) -
     
### Non Video Based Tutorials

### Open Source Books

### Print Books
Title - Handbook of Floating-Point Arithmetic  
ISBN - 9783319765259  

Title - Algorithms from The Book  
ISBN - 9781611976168  

Title - Modern Computer Arithmetic  
ISBN - 9780521194693  

Title - Elementary Functions Algorithms and Implementation  
ISBN - 9781489979810  

Title - Numerical Computing with IEEE Floating Point Arithmetic  
ISBN - 0898715717  

Title - Accuracy and Stability of Numerical Algorithms  
ISBN - 0898715210  

### Other

## Validation, Verification and Uncertainty Qualification (VVUQ)

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books
Title - Uncertainty Quantification: Theory, Implementation, and Applications  
ISBN - 9781611973211  

Title - Verification and Validation in Scientific Computing  
ISBN - 9781139491761  

### Other

## Artificial Intelligence/Machine Learning/Deep Learning

### Video Tutorials
1) OLCF
   * https://vimeo.com/836918490 - AI Training Series: AI for Science at Scale – Introduction 2023
   * https://vimeo.com/873844751 - AI Training Series: AI for Science at Scale – Part 2 2023
     * Time Commitment - Approximately 4 Hours
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

1) 3Blue1Brown
   * https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi - Neural Networks
     * Time Commitment - Approximately 1 Hour
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -    
   
### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Latex

### Video Tutorials

### Non Video Based Tutorials
1) Overleaf
   * https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes - Learn LaTeX in 30 minutes
     * Peer Review -
     * Target Audience -
       
### Open Source Books

### Print Books

### Other

## Markdown

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## reStructuredText

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Sphinx

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Directory Structure (both Mac and Linux)

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Useful Tools

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other

## Computer Hardware (CPUs, GPUs, FGPAs, etc)

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other
1) CERN
   * https://cds.cern.ch/record/2665803?ln=en - A Scientist's Guide to FPGAs 2019
       * Time Commitment - Approximately 1 Hour
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -   

   * https://cds.cern.ch/record/2823786?ln=en - FPGA programming 2022
       * Time Commitment - Approximately 2 Hours
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -
         
## Computer Architecture (x86, Arm, RiscV, etc)

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books
1) MIT Press
   Title - Scientific Programming and Computer Architecture
   Author - Divakar Viswanath
   Year - 2017
   Link to book (html format) - https://divakarvi.github.io/bk-spca/spca.html
   Github Repo - https://github.com/divakarvi/bk-spca 

### Print Books

### Other
1) NHR@FAU
   * https://www.youtube.com/watch?v=Ob1aAfF6L0I - Computer Architecture 101 for Scientists 2023
       * Time Commitment - Approximately 45 Minutes
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -

2) CERN
   * https://cds.cern.ch/record/2826781?ln=en - Performance Analysis and Optimization on Linux 2022
       * Time Commitment - Approximately 2 Hours
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -

   * https://cds.cern.ch/record/2773211?ln=en - Scientific computing on heterogeneous architectures
       * Time Commitment - Approximately 1 Hour
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -
  

## Compilers

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other
1) CERN
   * https://cds.cern.ch/record/2852026?ln=en - How a real-world C++ compiler works 2023
       * Time Commitment - Approximately 1 Hour
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -

## Using/Maintaining/Updating Legacy Code

### Video Tutorials

### Non Video Based Tutorials

### Open Source Books

### Print Books

### Other
1) CERN
   * https://cds.cern.ch/record/2677507?ln=en - Speeding up Scientific Codes in HPC Architectures by Code Modernization: Lessons Learned 2019
     * Time Commitment - Approximately 1 Hour 20 Minutes
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -

   * https://cds.cern.ch/record/2736214?ln=en - Modern C++ vs. its legacy: when stability is more important than performance (lecture) 2020
     * Time Commitment - Approximately 1 Hour
     * Peer Review -
     * Target Audience -
     * Audio/Visual Issues Recording(s) -  
          
## Miscellaneous 
This topic is for material which doesn't sit in any one catergory above. 

### Video Tutorials
1) Archer2
   * Github Repo - https://github.com/EPCCed/2022-07-26-hpc-shell-online
     * https://www.archer2.ac.uk/training/courses/220726-hpc-carpentry/ - HPC Carpentry 2022
       * Time Commitment - Approximately 8.5 Hours + time for exercises
       * Peer Review -
       * Target Audience -
       * Audio/Visual Issues Recording(s) -

### Non Video Based Tutorials
1) The Art of HPC
   * Github Repo - https://github.com/VictorEijkhout/TheArtofHPC_pdfs
   * Author - Victor Eijkhout
   * Description -  Set of 4 volumes on various aspects of high performance computing

### Open Source Books

### Print Books

### Other
