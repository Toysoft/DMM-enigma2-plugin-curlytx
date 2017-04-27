metadir = $(datadir)/meta
dist_meta_DATA = meta/plugin_curlytx.xml

plugindir = $(libdir)/enigma2/python/Plugins/Extensions/CurlyTx
plugin_PYTHON = \
	src/__init__.py \
	src/AtomFeed.py \
	src/CurlyTx.py \
	src/CurlyTxSettings.py \
	src/config.py \
	src/plugin.py

potdir = $(plugindir)/locale
pot_DATA = CurlyTx.pot

dedir = $(localedir)/de/LC_MESSAGES
de_DATA = po/de.mo

CurlyTx.pot: po/messages.pot
	cp $^ $@
