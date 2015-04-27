.. warning::

 The following instruction will make you overwrite your SD card content, it will be lost forever!
 If you have important data on it, make sure you do a backup of your data on the SD card before
 catching up with the next steps.

An SD card image provides the full system to boot with U-Boot and kernel. To flash an SD card image, run the following
command:


.. raw:: html

 <div>
 <div><b class="admonition-host">&nbsp;&nbsp;Host&nbsp;&nbsp;</b>&nbsp;&nbsp;<a style="float: right;" href="javascript:select_text( 'deploy_rootfs_rst-host-111' );">select</a></div>
 <pre class="line-numbers pre-replacer" data-start="1"><code id="deploy_rootfs_rst-host-111" class="language-markup">sudo dd if=core-image-minimal-imx6sxsabresd-dev.sdcard of=/dev/sd&lt;partition&gt; bs=1M</code></pre>
 <script src="_static/prism.js"></script>
 <script src="_static/select_text.js"></script>
 </div>


.. important::

 sudo password is **architech**

Make sure everything has been written on the SD card:

.. raw:: html

 <div>
 <div><b class="admonition-host">&nbsp;&nbsp;Host&nbsp;&nbsp;</b>&nbsp;&nbsp;<a style="float: right;" href="javascript:select_text( 'deploy_rootfs_rst-host-112' );">select</a></div>
 <pre class="line-numbers pre-replacer" data-start="1"><code id="deploy_rootfs_rst-host-112" class="language-markup">sync</code></pre>
 <script src="_static/prism.js"></script>
 <script src="_static/select_text.js"></script>
 </div>

and unmount the SD card from your system.
