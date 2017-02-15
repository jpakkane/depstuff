project('stuff', 'c')

stlib = static_library('st', 'a.c', 'b.c')
executable('myexe', 'main.c', 'c.c',
  link_with : stlib)
