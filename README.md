libdrawtext
===========

About
-----
Libdrawtext is a simple library for fast anti-aliased text rendering in OpenGL.

Since version 0.3 libdrawtext can also render text on plain RGBA pixel buffers.

Libdrawtext uses freetype2 for glyph rasterization. If you would rather avoid
having freetype2 as a dependency, you can optionally compile libdrawtext
without it, and use pre-rendered glyphmaps. Glyphmaps can be generated by the
included font2glyphmap tool, or by calling `dtx_save_glyphmap`.

See examples subdir for simple programs demonstrating libdrawtext usage, and
refer to the heavily commented drawtext.h header file.

- website: http://nuclear.mutantstargoat.com/sw/libdrawtext
- repository (git): https://github.com/jtsiomb/libdrawtext.git

Dependencies
------------
- OpenGL/GLEW (optional): http://glew.sourceforge.net
- freetype2 (optional): http://www.freetype.org

License
-------
Copyright (C) 2011-2016 John Tsiombikas <nuclear@member.fsf.org>
You may freely use, modify and/or redistribute libdrawtext, under the terms of
the GNU Lesser General Public License (LGPL) version 3 (or at your option, any
later version published by the Free Software Foundation). See COPYING, and
COPYING.LESSER for details.

Contact
-------
Feel free to send in bug reports, patches, and comments to: nuclear@member.fsf.org
Only plain text email messages, hard-wrapped at 72 columns will be accepted.
