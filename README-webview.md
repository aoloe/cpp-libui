# libui-webview: rendering html in libui

The simplest way to render formatted text (and content) is to embed an HTML-CSS renderer.

The most common way to do that is by embedding a "native" (mostly webkit based) renderer.

An alternative approach might use a "simpler" library like [litehtml](https://github.com/litehtml/litehtml).

## litehtml and litebrowser


- [litehtml](https://github.com/litehtml/litehtml) a library that does the parsing.
- [litebrowser](https://github.com/litehtml/litebrowser-linux) a sample application showing how to use the [Gtk DrawingArea](https://developer.gnome.org/gtkmm/stable/classGtk_1_1DrawingArea.html) to render the Html parsed by litehtml.
