# coverthief

## Dependencies:



<pre lang=bash>python-colorthief playerctl</pre>

#### Installing on **Arch Linux**(using the AUR):

<pre lang=bash>paru -S python-colorthief playerctl</pre>


<details><summary>How do I clone a <s>person</s> GitHub repo</summary>

### Using **git**:

<pre lang=bash>git clone https://github.com/CordlessCoder/coverthief</pre>

#### Using your hands: (*mouse may be required*):

1. Press on the `Code` button for exactly 100 ms.
2. Release the button if you forgor to.
3. Press on `Download ZIP`.
4. Enjoy.

</details>


## Using the script

#### With GLava:

In the config file of your preferred mod, set the main color to `STDIN`.

For example: `#define COLOR STDIN`.

Run the script and pipe it's output into GLava launched with the -i flag(to enable STDIN).

Example: `python coverthief.py | glava -i`

That should be it!
