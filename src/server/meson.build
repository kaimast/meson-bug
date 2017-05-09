
gen_source = custom_target('gen-source',
                        output: ['myfunc.c'],
                        command : [meson.source_root()+'/gen-file.sh'])

executable('testfile', 'main.c', gen_source)
