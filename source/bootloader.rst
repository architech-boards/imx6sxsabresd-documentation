U-boot
======

Get sources
-----------

The bootloader used by i.MX6 SoloX SabreSD is **u-boot**. 
If you want to browse/modify the sources first you have to get them. There are two viable
ways to do that:

* if you already built i.MX6 SoloX SabreSD's bootloader with *Bitbake*, then you already have them on your (virtual) disk, otherwise

* you can download them.

*Bitbake* will place *u-boot* sources under:

.. raw:: html

 <div>
 <div><b class="admonition-host">&nbsp;&nbsp;Host&nbsp;&nbsp;</b>&nbsp;&nbsp;<a style="float: right;" href="javascript:select_text( 'bootloader_rst-host-51' );">select</a></div>
 <pre class="line-numbers pre-replacer" data-start="1"><code id="bootloader_rst-host-51" class="language-markup">/path/to/build/tmp/work/imx6sxsabresd-poky-linux-gnueabi/u-boot-imx/2014.04-r0/git</code></pre>
 <script src="_static/prism.js"></script>
 <script src="_static/select_text.js"></script>
 </div>


this means that within the virtual machine you will find them under:

.. raw:: html

 <div>
 <div><b class="admonition-host">&nbsp;&nbsp;Host&nbsp;&nbsp;</b>&nbsp;&nbsp;<a style="float: right;" href="javascript:select_text( 'bootloader_rst-host-52' );">select</a></div>
 <pre class="line-numbers pre-replacer" data-start="1"><code id="bootloader_rst-host-52" class="language-markup">/home/architech/architech_sdk/architech/imx6sxsabresd/yocto/build/tmp/work/imx6sxsabresd-poky-linux-gnueabi/u-boot-imx/2014.04-r0/git</code></pre>
 <script src="_static/prism.js"></script>
 <script src="_static/select_text.js"></script>
 </div>


We suggest you to **don't work under Bitbake build directory**, you will pay a speed penalty
and you can have troubles syncronizing the all thing. Just copy the sources some place else
and do what you have to do.

If you didn't build them already with *Bitbake* or you just want to do make every step by hand, you can
always get them from the Internet by cloning the proper repository and checking out the proper commit.
Check `IMXLINUX: Embedded Linux for i.MX Applications Processors <http://www.freescale.com/webapp/sps/site/prod_summary.jsp?code=IMXLINUX&fsrch=1>`_