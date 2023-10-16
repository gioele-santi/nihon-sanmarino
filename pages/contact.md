---
layout              : page
title               : "Contatti"
meta_title          : "Contatta l'Associazione San Marino - Giappone"
subheadline         : "Modulo"
teaser              : "Compila il modulo per metterti in contatto con noi"
permalink           : "/contact/"
---

<form action="/contact/thanks/" method="post" name="contact"><input type="hidden" name="form-name" value="contact">
    <div hidden="">
        <label>Don’t fill this out:<!-- --> 
            <input name="bot-field">
        </label>
    </div>
    <div class="field">
        <label class="label" for="name">Il tuo nome・名前</label>
        <div class="control">
            <input type="text" class="input" name="name" id="name" required="">
        </div>
    </div>
    <div class="field">
        <label class="label" for="email">Email・メール</label>
        <div class="control">
            <input type="email" class="input" name="email" id="email" required="">
        </div>
    </div>
    <div class="field">
        <label class="label" for="message">Messaggio・メッセージ</label>
        <div class="control">
            <textarea class="textarea" name="message" id="message" required="" rows="8"></textarea>
        </div>
    </div>
    <div class="field">
        <button class="button is-link" type="submit">Invia・送る</button>
    </div>
</form>