#!python
env = Environment()

# Add the include paths
env.Append(CPPPATH = ['.'])

# Add the macro definitions
env.Append(CPPDEFINES = {'TEST_NUM' : '1'})

env.Program(target='rwHello', source=['hello.c'])