Let's boot
==========

Make sure that i.MX6 SoloX SabreSD boot mode jumpers are set like in the following picture:

.. image:: _static/sdcard-jumpers.jpg
    :align: center

Insert the SD card you just prepared inside socket **SD4**.

Connect the mini-USB cable from your PC to i.MX6 SoloX SabreSD USB OTG connector .

And now proceed by setting up the serial console.

.. include:: serial_console.rst

Give *root* to the login prompt:

.. raw:: html

 <div>
 <div><b class="admonition-board">&nbsp;&nbsp;Board&nbsp;&nbsp;</b>&nbsp;&nbsp;<a style="float: right;" href="javascript:select_text( 'boot_rst-board-191' );">select</a></div>
 <pre class="line-numbers pre-replacer" data-start="1"><code id="boot_rst-board-191" class="language-markup">imx6sxsabresd login: root</code></pre>
 <script src="_static/prism.js"></script>
 <script src="_static/select_text.js"></script>
 </div>

and press *Enter*.

.. note::

 Sometimes, the time you spend setting up minicom makes you miss all the output that leads to the login and you see just a black screen, press *Enter* then to get the login prompt.

For more information on flashing, see Section "Booting from an SD card" in the i.MX Linux® User's Guide