Examples
========

PILOT demo:

.. code-block:: bash

   cd workdirs/PILOT
   python main.py --config=exps/memo_scr.json --inftyopt=c_flat --workdir ../results/memo_cflat
   python main.py --config=exps/ease.json --inftyopt=zo_sgd_conserve --workdir ../results/ease_zo
   python main.py --config=exps/icarl.json --inftyopt=unigrad_fs --workdir ../results/icarl_unigrad_fs

Minimal examples are provided under ``examples/infty_minimal/``.
