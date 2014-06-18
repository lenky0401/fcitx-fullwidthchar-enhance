set(FCITX_FULLWIDTH_CHAR_SOURCES
  iniparser/dictionary.c
  iniparser/iniparser.c
  cfgrw.c
  fullwidthchar-enhance.c)

fcitx_add_addon_full(fullwidth-char-enhance
  SOURCES ${FCITX_FULLWIDTH_CHAR_SOURCES})

