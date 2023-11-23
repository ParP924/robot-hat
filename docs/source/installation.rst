Install the ``robot-hat``
==============================

.. warning::

   * When installing the Raspberry Pi OS, please use the **Raspberry Pi OS (Legacy)** version - **Debian Bullseye**. 
   * If the version you install is **Bookworm**, the **Speaker** will not function properly.

   .. image:: img/3d33.png

``robot-hat`` is the supported library for the Robot HAT.

Type this command into the terminal to install the Robot HAT package.

.. code-block::

   git clone https://github.com/sunfounder/robot-hat.git
   cd robot-hat
   sudo python3 setup.py install


.. note::
   Run ``setup.py`` to download some necessary components. You may have a network problem and the download may fail. At this point you may need to download again. In the following cases, type Y and press Enter to continue the process.

.. image:: img/dowload_code.png