.. _platform-versions:

Platform versions
=================

.. list-table:: Versions
   :widths: auto
   :header-rows: 1

   * - Group
     - Artifact
     - Sulfur Development

   * - org.opendaylight.odlparent
     - \*
     - 9.0.13

   * - org.opendaylight.infrautils
     - \*
     - 2.0.13

   * - org.opendaylight.yangtools
     - \*
     - 7.0.14

   * - org.opendaylight.mdsal
     - \*
     - 8.0.11

   * - org.opendaylight.controller
     - \*
     - 4.0.10

   * - org.opendaylight.aaa
     - aaa-artifacts
     - 0.14.10

   * - org.opendaylight.netconf
     - \*
     - 2.0.14

.. note:: Most projects get their YANG Tools version via MD-SAL.
  ${project}-artifacts are maven `bill of materials <https://howtodoinjava.com/maven/maven-bom-bill-of-materials-dependency/>`__
  (a.k.a. bom or BOM), whose use is strongly recommended to avoid versions
  mismatch across multiple dependencies in poms.


