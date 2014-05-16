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

```

##Different variants
You can find an overview of different Trustbadge versions [here](http://www.trustedshops.eu/merchants/integration/trustbadge.html).

##Can i preview how would it look on my page?

To view the trustbadge directly in your shop visit [this page](http://www.trustedshops.eu/merchants/integration/trustbadge.html) and enter the url of your webpage.


License
-------

All files are released under the MIT License. See the bundled
[LICENSE](https://github.com/trustedshops/trustbadge/blob/master/LICENSE) file for details.
