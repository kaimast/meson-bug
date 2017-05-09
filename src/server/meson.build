
gen_source = custom_target('gen-source',
                        output: ['myfunc.c'],
                        command : ['echo', 'void myfunc() {}', '>', 'myfunc.c'])

executable('testfile', 'main.c', gen_source)
