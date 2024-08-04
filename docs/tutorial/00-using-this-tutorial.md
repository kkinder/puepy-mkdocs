# Using This Tutorial

Each of the examples in this tutorial can be run on PyScript.com, a web environment that lets you write, test, and share PyScript code. Alternatively, you can clone the [PuePy git repo](https://github.com/kkinder/puepy) and run a live web server with each example included.

The PyScript.com environment uses the PuePy `.whl` file, as [downloadable from PyPi](https://pypi.org/project/puepy/#files), while the examples in the git repository are served with PuePy directly from source files on disk.

## Using PyScript.com

Navigate to [https://pyscript.com/@kkinder/puepy-tutorial/latest](https://pyscript.com/@kkinder/puepy-tutorial/latest) and you are greeted with a list of files on the left, a code editor in the middle, and a running example on the left. Each chapter in the tutorial corresponds with a directory in `tutorial` folder on the left.

![CleanShot 2024-06-30 at 10.47.31@2x.png](../images/pyscript-examples-screenshot.png)

You can clone the entire examples project and edit it yourself to continue your learning:

![CleanShot 2024-06-30 at 10.49.13.gif](../images/cloning-pyscrpt-examples.gif)

Once cloned you make your own changes and experiment with them in real time.

## Running locally

After cloning [puepy from GitHub](https://github.com/kkinder/puepy),

```
git clone https://github.com/kkinder/puepy.git
cd puepy
```
you can run the examples using a simple script `serve_examples.py`

```
python3 serve_examples.py
```

![CleanShot 2024-06-30 at 10.52.57@2x.png](../images/puepy-examples-terminal.png)

## Check it

Open your browser at http://localhost:8000/ 

You will see a list of examples

![CleanShot 2024-06-30 at 10.54.52@2x.png](../images/puepy-localhost-browser.png)

As you edit them in the `examples` folder and reload the window, your changes will be live.

## Live Examples

Most of the examples you see live in this tutorial include example code running live in a browser like this:

<puepy/>

There, you can see the running example inline with its explanation. 

You can also edit the code on [PyScript.com](https://pyscript.com/) by navigating to [PyScript - PuePy](https://pyscript.com/@kkinder/puepy-tutorial/latest) and cloning the project (after signing in), by clicking the `Clone Project` button.
