gen_source = find_program(meson.source_root()+'/gen-file.sh')

myfunc_gen = generator(gen_source, output: ['@BASENAME@.c'], arguments:[])
myfunc_target = myfunc_gen.process('myfunc')

executable('testfile', 'main.c', myfunc_target)
