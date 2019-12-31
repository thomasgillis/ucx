.. 
.. Copyright (C) Mellanox Technologies Ltd. 2019.  ALL RIGHTS RESERVED.
..
.. See file LICENSE for terms.
..

*******
OpenUCX
*******

Unified Communication X (UCX) is an award winning __link__, optimized production proven communication framework for modern, high-bandwidth and low-latency networks.
UCX exposes a set of abstract communication primitives which utilize the best of available hardware resources and offloads.
These include RDMA (Infiniband and RoCE), TCP, GPUs, Shared Memory, network based hardware atomics.

UCX implements best practices for transfer of messages of all sizes, based on accumulated experience gained from applications running on the world's largest datacenters and supercomputers.

UCX facilitates rapid development by providing a high-level API, masking the low-level details, while maintaining high-performance and scalability.

The full list of UCX capabilities and features can be found __here__


.. image:: _static/UCX_Layers.png
   :alt: UCX layer diagram
   :align: center

.. toctree::
   :maxdepth: 3
   :hidden:

   download
   running
   faq


Quick start
***********

The following commands will download and build UCX v1.6 :doc:`release <download>`:

.. code-block:: console

    $ wget https://github.com/openucx/ucx/releases/download/v1.6.1/ucx-1.6.1.tar.gz
    $ tar xzf ucx-1.6.1.tar.gz
    $ cd ucx-1.6.1
    $ ./contrib/configure-release --prefix=$PWD/install
    $ make -j8 install
    
    //todo: document how to run good example with client-server, gpu 


Documentation
*************

* todo: add link to UCX API doc
* `Examples <https://github.com/openucx/ucx/tree/v1.6.x/test/examples>`_


Projects using UCX
******************

* todo: link pyucx
* todo: link dask
* todo: nccl
 `SparkUCX <http://github.com/openucx/sparkucx>`_

* todo: link slurm
* `OpenMPI <http://www.open-mpi.org>`_
* `MPICH <http://www.mpich.org>`_
* `OSSS shmem <http://github.com/openshmem-org/osss-ucx>`_
*

Developers section
******************

* `UCX on github <http://github.com/openucx/ucx>`_
* `Dev wiki <http://github.com/openucx/ucx/wiki>`_
* `Issue tracker <http://github.com/openucx/ucx/issues>`_
* `UCX mailing list <elist.ornl.gov/mailman/listinfo/ucx-group>`_


Buzz
****

* `UCX wins R&D 100 award <https://losalamosreporter.com/2019/11/07/nine-los-alamos-national-laboratory-projects-win-rd-100-awards>`_
* `UCX @ OpenSHMEM workshop <http://www.openucx.org/wp-content/uploads/2015/08/UCX_OpenSHMEM_2015.pdf>`_
