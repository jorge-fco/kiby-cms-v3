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

```php
<?php if ($whatsapp->toggle()->toBool()) : ?>
  <div class="whatsapp__component" role="whatsapp" data-toggle="<?= $whatsapp->toggle()->toBool(); ?>">
    <a href="https://wa.me/<?= $phone_lada; ?><?= $phone; ?>?text=<?= $message; ?>" target="_blank" title="Chat on WhatsApp" aria-label="Chat on WhatsApp" rel="nofollow">
			
    </a>
  </div>
<?php endif ?>
```

## 📎 References
- [Business Whatsapp](https://business.whatsapp.com/)
- [Cómo usar la función de clic para chatear](https://faq.whatsapp.com/5913398998672934)
