## Unreleased ##

  * Change all nonword chars in filename of attachment to underscore so
    it can be saved on oall platforms. (thanks [phallstrom](https://github.com/phallstrom))

## 1.1.0 ##

  * Update Launchy dependency to `~> 2.2.0` (thanks [webdevotion](https://github.com/webdevotion))
  * Handle `sender` field (thanks [sjtipton](https://github.com/sjtipton))
  * Show subject only if it's present (thanks [jadehyper](https://github.com/jadehyper))
  * Show subject as title of web page (thanks [statique](https://github.com/statique))

## 1.0.0 ##

  * Attachment Support (thanks [David Cornu](https://github.com/davidcornu))
  * Escape HTML in subject and other fields
  * Raise an exception if the :location option is not present instead of using a default
  * Open rich version by default (thanks [Damir](https://github.com/sidonath))
  * Override margin on dt and dd elements in CSS (thanks [Edgars Beigarts](https://github.com/ebeigarts))
  * Autolink URLs in plain version (thanks [Matt Burke](https://github.com/spraints))

## 0.1.0 ##

  * From and To show name and Email when specified
  * Fix bug when letter_opener couldn't open email in Windows
  * Handle spaces in the application path (thanks [Mike Boone](https://github.com/boone))
  * As letter_opener doesn't work with Launchy < 2.0.4 let's depend on >= 2.0.4 (thanks [Samnang Chhun](https://github.com/samnang))
  * Handle `reply_to` field (thanks [Wes Gibbs](https://github.com/wgibbs))
  * Set the charset in email preview (thanks [Bruno Michel](https://github.com/nono))

## 0.0.2 ##

  * Fixing launchy requirement (thanks [Bruno Michel](https://github.com/nono))

## 0.0.1 ##

  * Initial relase
