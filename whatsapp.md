# WhatsApp Business
**Example:**

_Variables:_
```php
<?php
 $whatsapp = page('whatsapp');
 $phone = $whatsapp->phone();
 $phone_lada = $whatsapp->phone_lada();
 $message = $whatsapp->text();
?>
```

_Component:_
```php
<?php if ($whatsapp->toggle()->toBool()) : ?>
  <div class="whatsapp__component" role="whatsapp" data-toggle="<?= $whatsapp->toggle()->toBool(); ?>">
    <a href="https://wa.me/<?= $phone_lada; ?><?= $phone; ?>?text=<?= $message; ?>" target="_blank" title="Chat on WhatsApp" aria-label="Chat on WhatsApp" rel="nofollow">
	<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 36.7 37"> <g transform="translate(-1 -1)"> <path class="svg-icon-whatsapp-color" d="M10.7,32.8l.6.3a15.672,15.672,0,0,0,8.1,2.2h0A15.981,15.981,0,0,0,30.7,8,15.911,15.911,0,0,0,3.5,19.4a16.4,16.4,0,0,0,2.4,8.4l.4.6L4.7,34.3Z"></path> <path class="svg-icon-whatsapp-background" d="M32.4,6.4A18,18,0,0,0,19.5,1,18.266,18.266,0,0,0,1.2,19.4a19.309,19.309,0,0,0,2.4,9.1L1,38l9.7-2.5a17.856,17.856,0,0,0,8.7,2.2h0A18.394,18.394,0,0,0,37.7,19.3,18.148,18.148,0,0,0,32.4,6.4ZM19.5,34.6h0a14.857,14.857,0,0,1-7.7-2.1l-.6-.3L5.4,33.7,6.9,28l-.4-.6a15.179,15.179,0,1,1,20.9,4.9A14.579,14.579,0,0,1,19.5,34.6Zm8.8-11.1L27.2,23s-1.6-.7-2.6-1.2c-.1,0-.2-.1-.3-.1a1.445,1.445,0,0,0-.7.2h0s-.1.1-1.5,1.7a.55.55,0,0,1-.5.3h-.1a.758.758,0,0,1-.4-.2l-.5-.2h0a9.721,9.721,0,0,1-2.9-1.9c-.2-.2-.5-.4-.7-.6a11.169,11.169,0,0,1-1.9-2.4l-.1-.2c-.1-.1-.1-.2-.2-.4a.749.749,0,0,1,.1-.5s.4-.5.7-.8c.2-.2.3-.5.5-.7a1.232,1.232,0,0,0,.2-1,38.931,38.931,0,0,0-1.6-3.8,1.157,1.157,0,0,0-.7-.5H12.9c-.2,0-.4.1-.6.1l-.1.1c-.2.1-.4.3-.6.4-.2.2-.3.4-.5.6A5.1,5.1,0,0,0,10,15h0a5.932,5.932,0,0,0,.5,2.3l.1.3a16.66,16.66,0,0,0,3.7,5.1l.4.4a6.034,6.034,0,0,1,.8.8,17.869,17.869,0,0,0,7.2,3.8c.3.1.7.1,1,.2h1a3.707,3.707,0,0,0,1.5-.4c.3-.2.5-.2.7-.4l.2-.2c.2-.2.4-.3.6-.5a2.651,2.651,0,0,0,.5-.6,5.732,5.732,0,0,0,.4-1.4v-.7A1.238,1.238,0,0,0,28.3,23.5Z"> </path> </g> </svg>	
    </a>
  </div>
<?php endif ?>
```

## 📎 References
- [Business WhatsApp](https://business.whatsapp.com/)
- [Cómo usar la función de clic para chatear](https://faq.whatsapp.com/5913398998672934)
