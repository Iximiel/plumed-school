Stderr for source:  averaging.md_working_9.dat   
Download: [zipped raw stdout](averaging.md_working_9.dat.plumed.stdout.txt.zip) - [zipped raw stderr](averaging.md_working_9.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: GATHER_REPLICAS LABEL=r1g ARG=r1.bias
Maybe a missing space or a typo?
[fv-az1427-785:07867] *** Process received signal ***
[fv-az1427-785:07867] Signal: Aborted (6)
[fv-az1427-785:07867] Signal code:  (-6)
[fv-az1427-785:07867] [ 0] terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: GATHER_REPLICAS LABEL=r1g ARG=r1.bias
Maybe a missing space or a typo?
/lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb510842520]
[fv-az1427-785:07867] [ 1] [fv-az1427-785:07866] *** Process received signal ***
[fv-az1427-785:07866] Signal: Aborted (6)
[fv-az1427-785:07866] Signal code:  (-6)
/lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb5108969fc]
[fv-az1427-785:07867] [ 2] [fv-az1427-785:07866] [ 0] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb510842476]
[fv-az1427-785:07867] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb5108287f3]
[fv-az1427-785:07867] [ 4] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f39c0842520]
[fv-az1427-785:07866] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f39c08969fc]
[fv-az1427-785:07866] [ 2] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb510ca2b9e]
[fv-az1427-785:07867] [ 5] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f39c0842476]
[fv-az1427-785:07866] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb510cae20c]
[fv-az1427-785:07867] [ 6] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f39c08287f3]
[fv-az1427-785:07866] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb510cae277]
[fv-az1427-785:07867] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb510cae52b]
[fv-az1427-785:07867] [ 8] plumed(+0x12f48)[0x55f3e987bf48]
[fv-az1427-785:07867] [ 9] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f39c0ca2b9e]
[fv-az1427-785:07866] [ 5] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb510829d90]
[fv-az1427-785:07867] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb510829e40]
[fv-az1427-785:07867] [11] plumed(+0x131e5)[0x55f3e987c1e5]
[fv-az1427-785:07867] *** End of error message ***
/lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f39c0cae20c]
[fv-az1427-785:07866] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f39c0cae277]
[fv-az1427-785:07866] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f39c0cae52b]
[fv-az1427-785:07866] [ 8] plumed(+0x12f48)[0x55a330a97f48]
[fv-az1427-785:07866] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f39c0829d90]
[fv-az1427-785:07866] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f39c0829e40]
[fv-az1427-785:07866] [11] plumed(+0x131e5)[0x55a330a981e5]
[fv-az1427-785:07866] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1427-785 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
