project('gtk-browser', 'c')
gtkdep = dependency('gtk+-3.0')
webgtkdep = dependency('webkit2gtk-4.1')
executable('browse', 'browser.c', dependencies : [gtkdep, webgtkdep], install : true)
