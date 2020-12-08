VQE Benchmark
=============


projectq Benchmark Results
--------------------------

The performance of different algorithms in projectq for different
molecules

Module Info
~~~~~~~~~~~

+---------------------+---------------+--------------------------------------------------+
| Module              | Name          | WebPage                                          |
+=====================+===============+==================================================+
| Molecule Modeling   | PySCF         | https://github.com/pyscf/pyscf                   |
+---------------------+---------------+--------------------------------------------------+
| Quantum simulator   | projectq      | https://github.com/ProjectQ-Framework/ProjectQ   |
+---------------------+---------------+--------------------------------------------------+
| VQE algorithm       | openfermion   | https://github.com/quantumlib/OpenFermion        |
+---------------------+---------------+--------------------------------------------------+

Hardware Platform
~~~~~~~~~~~~~~~~~

::

    HUAWEI server
    Taiyi HPC

LiH molecule
~~~~~~~~~~~~

**Settings**

::

     Basis: STO-3G
     Transformation:Jordan-Wigner
     Qubit number: 12

**Result**

.. figure:: images/LiH_pq.png
Some data is not accurate.

**H6 chain**

**Settings**

::

     Basis: STO-3G
     Transformation:Jordan-Wigner
     Qubit number: 12

**Result**

.. figure:: images/H6_pq.png 
Some data is not accurate.

BeH2 molecule
~~~~~~~~~~~~~

**Settings**

::

     Basis: STO-3G
     Transformation:Jordan-Wigner
     Qubit number: 14

**Result**

H2O molecule
~~~~~~~~~~~~

**Settings**

::

     Basis: STO-3G
     Transformation:Jordan-Wigner
     Qubit number: 14

**Result**

N2 molecule
~~~~~~~~~~~

**Settings**

::

     Basis: STO-3G
     Transformation:Jordan-Wigner
     Qubit number: 20

**Result**

Contributor
~~~~~~~~~~~

Benchmark and Document writing: Jiaqi Hu





Qulacs Benchmark Results
------------------------

The performance of different algorithms in Qulacs for different
molecules

Module Info
~~~~~~~~~~~

+---------------------+-----------+-------------------------------------------------+
| Module              | Name      | WebPage                                         |
+=====================+===========+=================================================+
| Molecule Modeling   | PySCF     | https://github.com/pyscf/pyscf                  |
+---------------------+-----------+-------------------------------------------------+
| Quantum simulator   | qulacs    | https://github.com/qulacs/qulacs                |
+---------------------+-----------+-------------------------------------------------+
| VQE algorithm       | Tequila   | https://github.com/aspuru-guzik-group/tequila   |
+---------------------+-----------+-------------------------------------------------+

Hardware Platform
~~~~~~~~~~~~~~~~~

::

    HUAWEI server
    Taiyi HPC

**LiH molecule**

**Settings**

::

     Basis: STO-3G
     Transformation:Jordan-Wigner
     Qubit number: 12

**Result**

.. figure:: images/LiH_qc.png
   :alt: image

   image
BeH2 molecule
~~~~~~~~~~~~~
**Settings**

::

     Basis: STO-3G
     Transformation:Jordan-Wigner
     Qubit number: 14

**Result**

.. figure:: images/BeH2_qc.png
   :alt: image

   image
H2O molecule
~~~~~~~~~~~~

**Settings**

::

     Basis: STO-3G
     Transformation:Jordan-Wigner
     Qubit number: 14

**Result**

N2 molecule
~~~~~~~~~~~

**Settings**

::

     Basis: STO-3G
     Transformation:Jordan-Wigner
     Qubit number: 20

**Result**

Contributor
~~~~~~~~~~~

Benchmark and Document writing: Jiaqi Hu