Trusted Shops Trustbadge
=======

##Integration code

Just replace the value of "_tsid" with your Trusted Shops ID

```
<script type="text/javascript">
    (function () {
    var _tsid = 'XA2A8D35838AF5F63E5EB0E05847B1CB8';
    _tsConfig = {
        'yOffset': '0', //offset from page bottom
        'variant': 'reviews' //text, default, small, reviews
    };
    var _ts = document.createElement('script');
    _ts.type = 'text/javascript';
    _ts.charset = 'utf-8';
    _ts.src = '//widgets.trustedshops.com/js/' + _tsid + '.js';
    var __ts = document.getElementsByTagName('script')[0];
    __ts.parentNode.insertBefore(_ts, __ts);
    })();
</script>
<noscript><a href="https://www.trustedshops.de/shop/certificate.php?shop_id=XA2A8D35838AF5F63E5EB0E05847B1CB8"><img title="Klicken Sie auf das Gütesiegel, um die Gültigkeit zu prüfen!" src="//widgets.trustedshops.com/images/badge.png" style="position:fixed;bottom:0;right:0;" /></a></noscript>
```

##Different variants
You can find an overview of different Trustbadge version [here](http://www.trustedshops.eu/merchants/integration/trustbadge.html)

##Can i preview how would it look on my page?

To view the trustbadge directly in your shop visit [this](http://integr.trustedshops.eu/merchants/integration/trustbadge.html) page and enter the url of your webpage.


License
-------

All files are released under the MIT License. See the bundled
[LICENSE](https://github.com/trustedshops/trustbadge/blob/master/LICENSE) file for details.
