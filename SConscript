Import('build_env')

# Build the blkparse executable
blkparse_exe = build_env.Command ('#src/lib/blktrace_src/blkparse', '', 'make -C src/lib/blktrace_src blkparse')
Export('blkparse_exe')


# Build the blktrace executable
blktrace_exe = build_env.Command ('#src/lib/blktrace_src/blktrace', '', 'make -C src/lib/blktrace_src blktrace')
Export('blktrace_exe')
