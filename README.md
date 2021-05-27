# Demo instructions

This is a demo repo to try out real-time collaborative editing on Jupyterlab! [I am so happy it's here!!](https://github.com/jupyterlab/jupyterlab/issues/5382).

Full credit for these instructions go to [Jeremy Tuloup (@jtpio)](https://gist.github.com/jtpio/6ce26381703355e0ef1da4af742b7f72), they're a bit more verbose, but now that I understand what's happening, everything neededd was in that [original gist](https://gist.github.com/jtpio/6ce26381703355e0ef1da4af742b7f72).

## Instructions

1. First create a **public** repository with three files at minimum:
  - [`Demo.ipynb`](Demo.ipynb): a Jupyter notebook file.
  - [`requirements.txt`](requirements.txt): File that tells binder to install the latest alpha jupyterlab (`3.1.0a10` at the moment).
  - [`jupyter_notebook_config.py`](jupyter_notebook_config.py): Config file that enables collaboration features to activate.
2. Head over to [mybinder.org](https://mybinder.org) and put in your repo URL, and the branch name.
3. Importantly, to start a mybinder server running Jupyterlab, you need to add this to the "URL to open" field: `lab/tree/Demo.ipynb` (with Demo.ipynb being the name of your file).

<img width="990" alt="mybinder" src="https://user-images.githubusercontent.com/2507459/119846797-4aecdc80-bebf-11eb-9f14-a7fd200575b6.png">

4. Wait a few moments for the server to spin up.
5. Once you see the JupyterLab interface, there's a new top-level menu item called "Share"; click that, grab and share that URL, and you're done!

Here's the screencast from @jtpio:

![](https://user-images.githubusercontent.com/591645/117701750-e6940280-b1c7-11eb-92e6-2ce0331febeb.gif)

## Acknowledgements

Full credit for these instructions go to [Jeremy Tuloup (@jtpio)](https://gist.github.com/jtpio/6ce26381703355e0ef1da4af742b7f72), they're a bit more verbose, but now that I understand what's happening, everything neededd was in that [original gist](https://gist.github.com/jtpio/6ce26381703355e0ef1da4af742b7f72).
