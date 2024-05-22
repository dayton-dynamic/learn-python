============
Calculations
============


.. py-config::

    splashscreen:
        autoclose: true
    packages:
    - matplotlib

.. py-repl::
    :output: replOutput

    print("hallo world")
    import matplotlib.pyplot as plt
    plt.plot([1, 2, 3])
    plt.gcf()

.. raw:: html

    <div id="replOutput"></div>

.. py-terminal::
