CHANGELOG
=========

### 2014-01-02

* Changed twig template ``Resources/views/Post/comment_form.html.twig``. The template now uses Bootstrap3 panels & MopaBootstrapBundle's form template to render the form.

### 2013-10-03

* Integrate classification bundle
  Major BC Break, please refer to the [UPGRADE.md](UPGRADE.md) file

### 2012-09-24

* changed service parameters into options that come through the configuration with the old values as the new defaults.

### 2013-12-13

* PostManager & CommentManager now extend the DoctrineBaseManager (from SonataCoreBundle).

